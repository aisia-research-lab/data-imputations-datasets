# data-imputations-datasets
This repository is used to release the public datasets for data imputation tasks. These datasets are supported via the project from Vietnam National University Ho Chi Minh City with the project ID -  DS.2023.18.01

The datasets, including those we collected ourselves and other public datasets, used in our experiments can be categorized as follows

## 1. Stock market dataset
We collected data on historical stock transactions on 3 large markets in Vietnam, namely HNX, HOSE, and UPCOM. The data comprised of 1731 stocks, was collected from 04/012016 to 31/12/2021.

Please cite our journal paper when using this dataset for further purposes.
```
@inbook{an2023portfolio,
author = {Phan-Thi, Thuy-An and Dinh, Nu and Thanh, Son and Nguyen, Binh},
year = {2023},
month = {09},
pages = {},
title = {Portfolio Optimization for Long-Term Investment: An Empirical Study},
isbn = {9781643684307},
doi = {10.3233/FAIA230238}
}
```

## 2. Air pollution datasets
### 2.1. Collected data in Dalat and Hanoi
We collected data on air quality in Dalat and Hanoi (Cau Giay District and Minh Khai District). data from these locations constitute 3 datasets: [Dalat](https://github.com/BinhMisfit/air-pollution-datasets/tree/main/Dalat-air-quality-dataset), [Cau Giay](https://github.com/BinhMisfit/air-pollution-datasets/blob/main/Hanoi-air-quality-dataset/Hanoi_Cau_Giay.csv), [Minh Khai](https://github.com/BinhMisfit/air-pollution-datasets/blob/main/Hanoi-air-quality-dataset/Hanoi_Minh_Khai.csv).

Please cite our journal papers when using our datasets for further purposes.
```
@inproceedings{ton2023air,
  title={Air Pollution Forecasting Using Multimodal Data},
  author={Ton-Thien, Minh-Anh and Nguyen, Chuong Thi and Le, Quang M and Duong, Dat Q and Dao, Minh-Son and Nguyen, Binh T},
  booktitle={International Conference on Industrial, Engineering and Other Applications of Applied Intelligent Systems},
  pages={360--371},
  year={2023},
  organization={Springer}
}
```
```
@inproceedings{dao2023overview,
  title={Overview of MediaEval 2022 Urban Air: Urban Life and Air Pollution},
  author={Dao, Minh-Son and Dang, Thanh-Hai and Nguyen-Tai, Tan-Loc and Nguyen, Thanh-Binh and Dang-Nguyen, Duc-Tien},
  booktitle={Proc. of the MediaEval 2022 Workshop},
  pages={13--15},
  year={2023}
}
```
### 2.2. Frankfurt dataset
Please refer to [https://www.kaggle.com/datasets/avibagul80/air-quality-dataset](https://www.kaggle.com/datasets/avibagul80/air-quality-dataset)

### 2.3. Beijing dataset
This dataset is available upon request from the authors of the following article

'''
@article{DU2023119619,
  title = {SAITS: Self-attention-based imputation for time series},
  journal = {Expert Systems with Applications},
  volume = {219},
  pages = {119619},
  year = {2023},
  issn = {0957-4174},
  doi = {https://doi.org/10.1016/j.eswa.2023.119619},
  url = {https://www.sciencedirect.com/science/article/pii/S0957417423001203},
  author = {Wenjie Du and David Côté and Yan Liu},
  keywords = {Time series, Missing values, Imputation model, Self-attention, Neural network},
  abstract = {Missing data in time series is a pervasive problem that puts obstacles in the way of advanced analysis. A popular solution is imputation, where the fundamental challenge is to determine what values should be filled in. This paper proposes SAITS, a novel method based on the self-attention mechanism for missing value imputation in multivariate time series. Trained by a joint-optimization approach, SAITS learns missing values from a weighted combination of two diagonally-masked self-attention (DMSA) blocks. DMSA explicitly captures both the temporal dependencies and feature correlations between time steps, which improves imputation accuracy and training speed. Meanwhile, the weighted-combination design enables SAITS to dynamically assign weights to the learned representations from two DMSA blocks according to the attention map and the missingness information. Extensive experiments quantitatively and qualitatively demonstrate that SAITS outperforms the state-of-the-art methods on the time-series imputation task efficiently and reveal SAITS’ potential to improve the learning performance of pattern recognition models on incomplete time-series data from the real world.}
}
'''

### 2.4. Northern Taiwan dataset
Please refer to [https://www.kaggle.com/datasets/nelsonchu/air-quality-in-northern-taiwan](https://www.kaggle.com/datasets/nelsonchu/air-quality-in-northern-taiwan)



## 3. Multi-model datasets
### 3.1. IMDB
Please refer to [https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
### 3.2. Fashion MNIST
Please refer to [https://github.com/zalandoresearch/fashion-mnist](https://github.com/zalandoresearch/fashion-mnist)
### 3.3. MNIST
Please refer to [http://yann.lecun.com/exdb/mnist/](http://yann.lecun.com/exdb/mnist/)
### 3.4. Cifar10
Please refer to [https://www.cs.toronto.edu/~kriz/cifar.html](https://www.cs.toronto.edu/~kriz/cifar.html)

## 4. Imbalanced datasets
### 4.1. Ecoli
Please refer to the dataset "ecoli" from the [imbalanced.datasets](https://imbalanced-learn.org/stable/datasets/index.html) package
### 4.2. US Crime
Please refer to the dataset "us_crime" from the [imbalanced.datasets](https://imbalanced-learn.org/stable/datasets/index.html) package
### 4.3. Ozone Level
Please refer to the dataset "ozone_level" from the [imbalanced.datasets](https://imbalanced-learn.org/stable/datasets/index.html) package
### 4.4. Page Blocks
Please refer to [https://archive.ics.uci.edu/dataset/78/page+blocks+classification](https://archive.ics.uci.edu/dataset/78/page+blocks+classification)
### 4.5. Statlog Landsat
Please refer to [https://archive.ics.uci.edu/dataset/146/statlog+landsat+satellite](https://archive.ics.uci.edu/dataset/146/statlog+landsat+satellite)

## 5. Other datasets
### 5.1. Thyroid
Please refer to [https://archive.ics.uci.edu/dataset/102/thyroid+disease](https://archive.ics.uci.edu/dataset/102/thyroid+disease)
### 5.2. Yeast
Please refer to [https://archive.ics.uci.edu/dataset/110/yeast](https://archive.ics.uci.edu/dataset/110/yeast)
### 5.3. Seeds
Please refer to [https://archive.ics.uci.edu/dataset/236/seeds](https://archive.ics.uci.edu/dataset/236/seeds)
### 5.4. Iris
Please refer to [https://archive.ics.uci.edu/dataset/53/iris](https://archive.ics.uci.edu/dataset/53/iris)
### 5.5. Wine
Please refer to [https://archive.ics.uci.edu/dataset/109/wine](https://archive.ics.uci.edu/dataset/109/wine)
### 5.6. Breast Cancer
Please refer to [https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)
### 5.7. Gene
Please refer to [https://archive.ics.uci.edu/dataset/401/gene+expression+cancer+rna+seq](https://archive.ics.uci.edu/dataset/401/gene+expression+cancer+rna+seq)
### 5.8. Parkinson
Please refer to [https://archive.ics.uci.edu/dataset/470/parkinson+s+disease+classification](https://archive.ics.uci.edu/dataset/470/parkinson+s+disease+classification)
### 5.9. Digits
Please refer to [https://archive.ics.uci.edu/dataset/80/optical+recognition+of+handwritten+digits](https://archive.ics.uci.edu/dataset/80/optical+recognition+of+handwritten+digits)
### 5.10. Ionosphere
Please refer to [https://archive.ics.uci.edu/dataset/52/ionosphere](https://archive.ics.uci.edu/dataset/52/ionosphere)
### 5.11. Bank Marketing
Please refer to [https://archive.ics.uci.edu/dataset/222/bank+marketing](https://archive.ics.uci.edu/dataset/222/bank+marketing)
### 5.12. Heart Disease
Please refer to [https://archive.ics.uci.edu/dataset/45/heart+disease](https://archive.ics.uci.edu/dataset/45/heart+disease)
### 5.13. Statlog
Please refer to [https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data](https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data)
### 5.14. Student Performance
Please refer to [https://archive.ics.uci.edu/dataset/320/student+performance](https://archive.ics.uci.edu/dataset/320/student+performance)

# Details of our experiments
Please refer to our papers for more details of our experiments for data imputation tasks.
```
@article{10.1371/journal.pone.0306303,
    doi = {10.1371/journal.pone.0306303},
    author = {Hua, Van AND Nguyen, Thu AND Dao, Minh-Son AND Nguyen, Hien D. AND Nguyen, Binh T.},
    journal = {PLOS ONE},
    publisher = {Public Library of Science},
    title = {The impact of data imputation on air quality prediction problem},
    year = {2024},
    month = {09},
    volume = {19},
    url = {https://doi.org/10.1371/journal.pone.0306303},
    pages = {1-39},
    abstract = {With rising environmental concerns, accurate air quality predictions have become paramount as they help in planning preventive measures and policies for potential health hazards and environmental problems caused by poor air quality. Most of the time, air quality data are time series data. However, due to various reasons, we often encounter missing values in datasets collected during data preparation and aggregation steps. The inability to analyze and handle missing data will significantly hinder the data analysis process. To address this issue, this paper offers an extensive review of air quality prediction and missing data imputation techniques for time series, particularly in relation to environmental challenges. In addition, we empirically assess eight imputation methods, including mean, median, kNNI, MICE, SAITS, BRITS, MRNN, and Transformer, to scrutinize their impact on air quality data. The evaluation is conducted using diverse air quality datasets gathered from numerous cities globally. Based on these evaluations, we offer practical recommendations for practitioners dealing with missing data in time series scenarios for environmental data.},
    number = {9},
}
```



