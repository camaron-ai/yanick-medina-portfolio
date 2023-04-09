# Projects in Data Science, Machine Learning and Computer Science

## OTTO – Multi-Objective Recommender System 2023, hosted by  Kaggle.

<img src="images/kaggle-otto-sysrec.png?raw=true"/>

the competition challenged participants to build a real-time multi-objective system that leverages user-timeline data to provide personalized recommendations for clicks, cart additions, and orders events.

My solution involved:
- Managed a large data pipeline of over 220 million events, 12 million users, and 1.8 million unique products by performing parallel distributed computations.
- Designed and implemented multiple candidate retrieval strategies by leveraging both hand-engineered features and learned automatic data representation (embeddings) of the user’s timeline.
- Trained a gradient boosting machine (GBM) ensemble (Using LGBM, XGBoost and CatBoost implementations) to generate personalized recommendations for users.


[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/PyTorch-white?logo=pytorch)](#) [![](https://img.shields.io/badge/sklearn-white?logo=scikit-learn)](#) ![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)

[Challange description](https://www.kaggle.com/competitions/otto-recommender-system/overview)

---
## Mars Spectrometry: Detect Evidence for Past Habitability 2022, hosted by DrivenData and NASA
<img src="images/mars_spec.png?raw=true"/>

I participated in the Mars Exploration Challenge, where participants were tasked to detect families of chemical compounds in mass spectrometry data. Despite the complexity of the task, I achieved 5th place by engineering hundreds of features from raw mass spectrometry data to train gradient boosting machine models. Additionally, I used data augmentation and transfer learning techniques to train large machine-learning models with less than 1000 training examples.


[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/PyTorch-white?logo=pytorch)](#) [![](https://img.shields.io/badge/sklearn-white?logo=scikit-learn)](#)

[Challange description](https://www.nasa.gov/mars-spectrometry-challenge)

[View code on github](https://github.com/camaron-ai/mars_spectrometry)

---
## Advent of Code 2022
I have taken on the challenge of solving daily coding problems from Advent of Code 2022.
Every day, I approach a new problem and work to find the most efficient solution. On my GitHub, I provide a clear explanation, along with the time and space complexity and its implementation using Python3.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#)

[View code on github](https://github.com/camaron-ai/adventofcode-2022)

---
## MAGNET: Model the Geomagnetic Field 2021, hosted by DrivenData and NASA.
<img src="images/noaa-cover-img.png?raw=true"/>
The competition challenged participants to forecast the Earth's magnetic field based on real-time solar wind data using satellite data from NOAA's Deep Space Climate Observatory and NASA's Advanced Composition Explorer.

I achieved 3rd place by engineering solar wind time series into powerful features such as trend, frequency content statistics, moving average statistics, among others. To improve out-of-sample performance, I developed an ensemble approach that combined neural-network-based and tree-based models.

My solution proved to be best solution during extreme solar periods.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/PyTorch-white?logo=pytorch)](#) [![](https://img.shields.io/badge/sklearn-white?logo=scikit-learn)](#)

<img src="images/performance-plot-magnet-extreme.png?raw=true"/>

[Challange description](https://www.drivendata.org/competitions/73/noaa-magnetic-forecasting/)

[Solution Overview](https://drivendata.co/blog/magnet-geomagnetic-field-winners/)

[View code on github](https://github.com/camaron-ai/magnet_competition)

---
