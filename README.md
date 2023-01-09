# NYCU_ML_Final

## Background

Solution of a kaggle competition : [Tabular Playground Series - Aug 2022](https://www.kaggle.com/competitions/tabular-playground-series-aug-2022/overview)

## Requirements

To install requirements:

(this file is downloaded from Google Colab, so there are plenty of unnecessary libraries)

```setup
pip install -r requirements.txt
```
## Dataset

Training Dataset : `train.csv`

Testing Dataset : `test.csv`

## Training

```train
109550137_Final_train.ipynb
```

## Pre-trained Model

You can download pretrained models here, and use it in in inference file

- [Logistic Regression model](https://drive.google.com/drive/folders/15H1Gmzj7jPi61YhHIPpySuUBJeLezLcK?usp=share_link)

## Inferencing

You need to download `test.csv` and the pre-trained model mentioned above

```inference
109550137_Final_inference.ipynb
```

## Results

My model achieves the following performance on :

| Model name                  | Private Socre | Public Socre |
| --------------------------- | ------------- | ------------ |
| Logistic Regression model   |    0.59184    |    0.58339   |

Result file : `109550137_submission.csv`

I also provide the csv file I produced, since there is no randomness during training and inferencing, you can reproduce the same file
