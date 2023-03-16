# HLT project

This is the project for the Human Language Technologies course, at the University of Pisa (a.y. 2022/2023). It consists in the comparison of different classifier models for a stance detection task in order to analyze different behaviour and similarities. The models compared are supervised models (Naive Bayes, SVM), and transformers (BERT, ChatGPT). The models were compared on two different datasets: [IBM Debater - Claim Stance dataset](https://research.ibm.com/haifa/dept/vst/debating_data.shtml#Argument_Stance) with 2 stance categories (pro/con) on 55 topics, and [Fake News Challenge dataset](http://www.fakenewschallenge.org/) with 4 stance categories (agree/disagree/discussed/unrelated).

## Built with
![python](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)
![jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)
![sklearn](https://img.shields.io/badge/scikitlearn-F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![tf](https://img.shields.io/badge/TensorFlow-FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)


# Project tour
The project is divided in the following folders:

1. `src` - contains all the notebooks and the code.
2. `data` - contains train/test datasets of IBM and FNC.
3. `models` - contains the grid search csv of the trained models.
4. `plots` - contains plots of the experiments.

