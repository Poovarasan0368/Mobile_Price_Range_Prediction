# Mobile_Price_Range_Prediction

![image.png](https://cdn.dribbble.com/users/3873964/screenshots/14216267/media/fe34f0470ef7899cc9594a8c9f3f2cec.gif)

## Introduction 📘
Mobile phones have become an integral part of our lives, and the prices of these devices have been steadily increasing over the years. Mobile price prediction is a process of predicting the future prices of mobile phones based on current market trends and other factors. This process can help consumers make informed decisions when it comes to purchasing a new device. It can also help manufacturers and retailers better understand the market and adjust their pricing strategies accordingly. Mobile price prediction is a complex process that requires data analysis, machine learning, and others.

## Problem Description 🤔  
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg-RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.

### The contents of Mobile price Data are:
The data contains information regarding mobile phone features, specifications etc and their price range. The various features and information can be used to predict the price range of a mobile phone.


* **Battery_power** - Total energy a battery can store in one time measured in mAh
* **Blue** - Has bluetooth or not
* **Clock_speed** - speed at which microprocessor executes instructions
* **Dual_sim** - Has dual sim support or not
* **Fc** - Front Camera mega pixels
* **Four_g** - Has 4G or not
* **Int_memory** - Internal Memory in Gigabytes
* **M_dep** - Mobile Depth in cm
* **Mobile_wt** - Weight of mobile phone
* **N_cores** - Number of cores of processor
* **Pc** - Primary Camera mega pixels
* **Px_height** - Pixel Resolution Height
* **Px_width** - Pixel Resolution Width
* **Ram** - Random Access Memory in Mega
* **Touch_screen** - Has touch screen or not
* **Wifi** - Has wifi or not
* **Sc_h** - Screen Height of mobile in cm
* **Sc_w** - Screen Width of mobile in cm
* **Talk_time** - longest time that a single battery charge will last when you are
* **Three_g** - Has 3G or not
* **Price_range** - This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost), 3(very high cost)

## The series of steps followed in this project 📃

    1. Importing Packages
    2. Reading Data
    3. Explore the structure of the Datasets
    4. Data Cleaning
    5. Exploratory Data Analysis (EDA)
    6. Data Transformation
    7. creating ML Models
	
## The tools that are going to be used for this project would be 💾
   
    1. Numpy 
    2. Pandas
    3. Matplotlib
    4. Seaborn
    5. Sklearn
   
**which I have learnt from the course.**

## Algorithm that used in this project are 🔣

    1. Decision Tree Classifier
    2. Random Forest Classifier
    3. Gradient Boosting Classifier
    4. K-Nearest Neighbours Classifier

## Conclusion ✌

**We tried a variety of models, and the table above summarizes the results of one set of models. K-Nearest Neighbours and Random Forest Classifier has the best overall accuracy of 92 percent. The optimal accuracy for Hyperparameter tunned Random forest, Decision Tree, Gradient Boosting was 91 percent, 80 percent, and 89 percent respectively. However, we'll make K-Nearest Neighbours our best model because it provides good overall and individual class accuracy.**

* From EDA, we can observe that there are four different price categories for Mobile phones. 

* Almost the same number of components are present. 

* Half of the phones have Bluetooth, and the other half don’t have Bluetooth 

* As the price range grows, the battery gradually gets bigger. 

* Ram's price range continuously rises as it moves from low to extremely high prices. 

* Expensive phones are weight lesser compare to others.

* The most important factors in determining the price range of a mobile phone were RAM, battery life, and pixels.
