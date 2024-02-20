## Click2Buy-Predictive-Purchase-Conversion

Welcome to the repository for the final project of DS 5220 Supervised Machine Learning at Northeastern University, led by Pareekshit Reddy Gaddam, Deepak Rao Nadipelly and Ziyue Wang

In this project, we delve into the exciting realm of predicting purchase conversion rates for an e-commerce website. Every click on a product represents a potential sale, but not all clicks convert into purchases. Our aim is to leverage machine learning techniques to forecast whether a click will result in a successful purchase based on a myriad of features.

As an online retailer, understanding conversion rates is paramount. Conversions signify the number of times a user fulfills a desired action on the platform. In our case, that desired action is completing a purchase. Accurate prediction of conversion rates enables retailers to enhance various aspects of their business operations, from improving recommendation algorithms to optimizing search results and targeted product advertisements.

The dataset we utilize for this project was sourced from a Kaggle competition and encompasses a rich array of item features, sales data, and logistical details. Through our analysis and predictive modeling, we aim to provide valuable insights that can empower online retailers to make informed decisions and maximize their conversion rates.

Thank you for joining us on this journey of exploration and discovery in the realm of e-commerce analytics. Let's unlock the potential of predictive analytics to drive success in the digital marketplace. This dataset was taken from a Kaggle competition.
Source of the dataset: [Kaggle](https://www.kaggle.com/c/conversion-rate-prediction/data)

## Guide
The project mainly consists of two parts: EDA (Explanatory Data Analysis) and Modeling. To run the code, you need to make sure your local machine meets the requirements presented in `requirements.txt`
## Modeling structure
```
Modeling.ipynb
│   Data Import    
│
└───Data Preprocessing
└───Feature Engineering
└───Utils
└───Modele Buiding
│   └───Data split
│   └───Classical Models
│       │   Logistic Regression
│       │   Naive Bayes
│       │   Random Forest
│       │   Linear SVC
│   └───Boosters
│       │   XGB
│       │   LightGBM
│   └───Neural Network
│       │   Preprocessing
│       │   Modeling
│   └───Model Ensembling
│   └───Model Stacking
│   └───Stepwise regression
```


*Framework inspired by [Weipeng Zhang](https://github.com/Wp-Zhang). Special thanks to him.*
