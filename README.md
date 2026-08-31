# Transformers Notebooks

This repository contains the example code from our O'Reilly book [Natural Language Processing with Transformers](https://www.oreilly.com/library/view/natural-language-processing/9781098136789/):

<img alt="book-cover" height=200 src="images/book_cover.jpg" id="book-cover"/>

## Getting started

You can run these notebooks on cloud platforms like [Google Colab](https://colab.research.google.com/) or your local machine. Note that most chapters require a GPU to run in a reasonable amount of time, so we recommend one of the cloud platforms as they come pre-installed with CUDA.

### 2026년 가을 학기 실습 안내

2026년 가을 학기 기준으로 다음 여섯 개 실습 자료를 Google Colab의 Python 3.13 환경에서 실행할 수 있도록 정비하고 검증했습니다: 01장 Introduction, 02장 Text Classification, 03장 Transformer Anatomy, 04장 Multilingual NER, 05장 Text Generation, 10장 Training Transformers from Scratch.

실습 시 다음 사항에 주의하세요.

- 새 Colab GPU 런타임에서 노트북의 첫 번째 설치 셀부터 순서대로 실행하세요.
- 02장의 TensorFlow 실습은 이번 기본 실습 범위에서 제외했습니다.
- 10장은 토크나이저 훈련 과정을 보여주는 Colab용 데모 설정을 기본으로 사용합니다. 원본의 대규모 데이터 처리와 장시간 사전학습 설정은 기본 실행 경로가 아닙니다.
- 기본 실행에는 Hugging Face Hub 또는 Weights & Biases 로그인이 필요하지 않습니다. 모델 업로드와 외부 로깅은 별도 인증이 필요한 선택 과정입니다.
- 위 여섯 개 이외의 노트북과 Colab 이외의 실행 환경은 이번 정비 범위에 포함되지 않았습니다.

### Running on a cloud platform

To run these notebooks on a cloud platform, just click on one of the badges in the table below:

<!--This table is automatically generated, do not fill manually!-->



| Chapter                                     | Colab                                                                                                                                                                                               | Kaggle                                                                                                                                                                                                   | Gradient                                                                                                                                                                               | Studio Lab                                                                                                                                                                                                   |
|:--------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Introduction                                | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jangmino/nlp-with-transformers-notebooks/blob/main/01_introduction.ipynb)              | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/nlp-with-transformers/notebooks/blob/main/01_introduction.ipynb)              | [![Gradient](https://assets.paperspace.io/img/gradient-badge.svg)](https://console.paperspace.com/github/nlp-with-transformers/notebooks/blob/main/01_introduction.ipynb)              | [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/nlp-with-transformers/notebooks/blob/main/01_introduction.ipynb)              |
| Text Classification                         | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jangmino/nlp-with-transformers-notebooks/blob/main/02_classification.ipynb)            | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/nlp-with-transformers/notebooks/blob/main/02_classification.ipynb)            | [![Gradient](https://assets.paperspace.io/img/gradient-badge.svg)](https://console.paperspace.com/github/nlp-with-transformers/notebooks/blob/main/02_classification.ipynb)            | [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/nlp-with-transformers/notebooks/blob/main/02_classification.ipynb)            |
| Transformer Anatomy                         | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jangmino/nlp-with-transformers-notebooks/blob/main/03_transformer-anatomy.ipynb)       | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github/jangmino/nlp-with-transformers-notebooks/blob/main/03_transformer-anatomy.ipynb)       | [![Gradient](https://assets.paperspace.io/img/gradient-badge.svg)](https://console.paperspace.com/github/jangmino/nlp-with-transformers-notebooks/blob/main/03_transformer-anatomy.ipynb)       | [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/jangmino/nlp-with-transformers-notebooks/blob/main/03_transformer-anatomy.ipynb)       |
| Multilingual Named Entity Recognition       | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jangmino/nlp-with-transformers-notebooks/blob/main/04_multilingual-ner.ipynb)          | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/jangmino/nlp-with-transformers-notebooks/blob/main/04_multilingual-ner.ipynb)          | [![Gradient](https://assets.paperspace.io/img/gradient-badge.svg)](https://console.paperspace.com/github/jangmino/nlp-with-transformers-notebooks/blob/main/04_multilingual-ner.ipynb)          | [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/jangmino/nlp-with-transformers-notebooks/blob/main/04_multilingual-ner.ipynb)          |
| Text Generation                             | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jangmino/nlp-with-transformers-notebooks/blob/main/05_text-generation.ipynb)           | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/jangmino/nlp-with-transformers-notebooks/blob/main/05_text-generation.ipynb)           | [![Gradient](https://assets.paperspace.io/img/gradient-badge.svg)](https://console.paperspace.com/github/jangmino/nlp-with-transformers-notebooks/blob/main/05_text-generation.ipynb)           | [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/jangmino/nlp-with-transformers-notebooks/blob/main/05_text-generation.ipynb)           |
| Training Transformers from Scratch          | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jangmino/nlp-with-transformers-notebooks/blob/main/10_transformers-from-scratch.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/jangmino/nlp-with-transformers-notebooks/blob/main/10_transformers-from-scratch.ipynb) | [![Gradient](https://assets.paperspace.io/img/gradient-badge.svg)](https://console.paperspace.com/github/jangmino/nlp-with-transformers-notebooks/blob/main/10_transformers-from-scratch.ipynb) | [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/jangmino/nlp-with-transformers-notebooks/blob/main/10_transformers-from-scratch.ipynb) |
<!-- | Summarization                               | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nlp-with-transformers/notebooks/blob/main/06_summarization.ipynb)             | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/nlp-with-transformers/notebooks/blob/main/06_summarization.ipynb)             | [![Gradient](https://assets.paperspace.io/img/gradient-badge.svg)](https://console.paperspace.com/github/nlp-with-transformers/notebooks/blob/main/06_summarization.ipynb)             | [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/nlp-with-transformers/notebooks/blob/main/06_summarization.ipynb)             |
| Question Answering                          | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nlp-with-transformers/notebooks/blob/main/07_question-answering.ipynb)        | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/nlp-with-transformers/notebooks/blob/main/07_question-answering.ipynb)        | [![Gradient](https://assets.paperspace.io/img/gradient-badge.svg)](https://console.paperspace.com/github/nlp-with-transformers/notebooks/blob/main/07_question-answering.ipynb)        | [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/nlp-with-transformers/notebooks/blob/main/07_question-answering.ipynb)        |
| Making Transformers Efficient in Production | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nlp-with-transformers/notebooks/blob/main/08_model-compression.ipynb)         | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/nlp-with-transformers/notebooks/blob/main/08_model-compression.ipynb)         | [![Gradient](https://assets.paperspace.io/img/gradient-badge.svg)](https://console.paperspace.com/github/nlp-with-transformers/notebooks/blob/main/08_model-compression.ipynb)         | [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/nlp-with-transformers/notebooks/blob/main/08_model-compression.ipynb)         |
| Dealing with Few to No Labels               | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nlp-with-transformers/notebooks/blob/main/09_few-to-no-labels.ipynb)          | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/nlp-with-transformers/notebooks/blob/main/09_few-to-no-labels.ipynb)          | [![Gradient](https://assets.paperspace.io/img/gradient-badge.svg)](https://console.paperspace.com/github/nlp-with-transformers/notebooks/blob/main/09_few-to-no-labels.ipynb)          | [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/nlp-with-transformers/notebooks/blob/main/09_few-to-no-labels.ipynb)          |
| Training Transformers from Scratch          | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nlp-with-transformers/notebooks/blob/main/10_transformers-from-scratch.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/nlp-with-transformers/notebooks/blob/main/10_transformers-from-scratch.ipynb) | [![Gradient](https://assets.paperspace.io/img/gradient-badge.svg)](https://console.paperspace.com/github/nlp-with-transformers/notebooks/blob/main/10_transformers-from-scratch.ipynb) | [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/nlp-with-transformers/notebooks/blob/main/10_transformers-from-scratch.ipynb) |
| Future Directions                           | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nlp-with-transformers/notebooks/blob/main/11_future-directions.ipynb)         | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/nlp-with-transformers/notebooks/blob/main/11_future-directions.ipynb)         | [![Gradient](https://assets.paperspace.io/img/gradient-badge.svg)](https://console.paperspace.com/github/nlp-with-transformers/notebooks/blob/main/11_future-directions.ipynb)         | [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/nlp-with-transformers/notebooks/blob/main/11_future-directions.ipynb)         | -->

<!--End of table-->

Nowadays, the GPUs on Colab tend to be K80s (which have limited memory), so we recommend using [Kaggle](https://www.kaggle.com/docs/notebooks), [Gradient](https://gradient.run/notebooks), or [SageMaker Studio Lab](https://studiolab.sagemaker.aws/). These platforms tend to provide more performant GPUs like P100s, all for free!

> Note: some cloud platforms like Kaggle require you to restart the notebook after installing new packages.

### Running on your machine

To run the notebooks on your own machine, first clone the repository and navigate to it:

```bash
$ git clone https://github.com/nlp-with-transformers/notebooks.git
$ cd notebooks
```

Next, run the following command to create a `conda` virtual environment that contains all the libraries needed to run the notebooks:

```bash
$ conda env create -f environment.yml
```

> Note: You'll need a GPU that supports NVIDIA's [CUDA Toolkit](https://developer.nvidia.com/cuda-toolkit) to build the environment. Currently, this means you cannot build locally on Apple silicon 😢.

Chapter 7 (Question Answering) has a special set of dependencies, so to run that chapter you'll need a separate environment:

```bash
$ conda env create -f environment-chapter7.yml
```

Once you've installed the dependencies, you can activate the `conda` environment and spin up the notebooks as follows:

```bash
$ conda activate book # or conda activate book-chapter7
$ jupyter notebook
```

## FAQ

### When trying to clone the notebooks on Kaggle I get a message that I am unable to access the book's Github repository. How can I solve this issue?

This issue is likely due to a missing internet connection. When running your first notebook on Kaggle you need to enable internet access in the settings menu on the right side. 

### How do you select a GPU on Kaggle?

You can enable GPU usage by selecting *GPU* as *Accelerator* in the settings menu on the right side.

## Citations

If you'd like to cite this book, you can use the following BibTeX entry:

```
@book{tunstall2022natural,
  title={Natural Language Processing with Transformers: Building Language Applications with Hugging Face},
  author={Tunstall, Lewis and von Werra, Leandro and Wolf, Thomas},
  isbn={1098103246},
  url={https://books.google.ch/books?id=7hhyzgEACAAJ},
  year={2022},
  publisher={O'Reilly Media, Incorporated}
}
```
