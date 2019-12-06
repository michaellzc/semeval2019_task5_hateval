# cmput497_hateval

## Prerequisites

-   Python3.7
-   virtualenv

## Setup

Download `glove.twitter.27B.zip` from [stanfordnlp/GloVe](https://github.com/stanfordnlp/GloVe) and unzip to `.vector_cache`

```bash
# Setup python virtual environment
$ virtualenv venv --python=python3
$ source venv/bin/activate

# Install python dependencies
$ pip install -r requirements.txt
```

## How to run

You may either run the `ipynb` jupyter notebook on Colab with GPU acclerator (Recommend)

Or do it locally (DON'T since it will take forever unless you have a CUDA-enabled GPU)

```bash
$ python semeval2019_task5_hateval_final.py
```

## Config

You may modify the `TrainParameters` class to train classifier for different labels and different weight intilization presets. See comment for detail

## Authors

-   Yonael Bekele
-   Michael Lin
-   Helen Zhao
