# :iphone: Mobile price classification
![Alt text](Mobile.jpg)


### :book: overview
---
Bob has started his own mobile company. He wants to give tough fight to big companies like Apple,Samsung etc.

He does not know how to estimate price of mobiles his company creates. In this competitive mobile phone market you cannot simply assume things. To solve this problem he collects sales data of mobile phones of various companies.

Bob wants to find out some relation between features of a mobile phone(eg:- RAM,Internal Memory etc) and its selling price. But he is not so good at Machine Learning. So he needs your help to solve this problem.

In this problem you do not have to predict actual price but a price range indicating how high the price is

What i want to do is :  
train my data with 3 classification algorithms which are :
Decision tree
Random forest
SVM (Support Vector Machine)


### :chart_with_downwards_trend: Dataset Description
---
There are two datasets named train & test
In train dataset there are 2000 moblies and their features.
These samples have prices which we know them as target.
The target values are classified into 4 classes.
Also in test dataset there are some sample without price column which i'm going to predict their prices.

| columns | Description |
| ------ | ----------- |
| ID | Mobile ID |
| battery_power	| Total energy a battery can store in one time measured in mAh |
| blue | Has bluetooth or not |
| clock_speed | speed at which microprocessor executes instructions |	
| dual_sim | Has dual sim support or |
| fc | Front Camera mega pixels |	
| four_g | Has 4G or not |
| int_memory | Internal Memory in Gigabytes |
| m_dep	| Mobile Depth in cm |
| mobile_wt | Weight of mobile phone |
| n_cores| Number of cores of processor |
| pc | Primary Camera mega pixels |
| px_height	| Pixel Resolution Height |
| px_width | Pixel Resolution Width |	
| ram | Random Access Memory in Megabytes |	
| sc_h | Screen Height of mobile in cm |	
| sc_w | Screen Width of mobile in cm |	
| talk_time	| longest time that a single battery charge will last when you are |	
| three_g | Has 3G or not |
| touch_screen | Has touch screen or not |
| wifi | Has wifi or not |
| Price_range |	This is the target variable (3: Very High Cost, 2: High Cost, 1: Medium Cost, 0: Low Cost) |


### :open_file_folder: File Descriptions
---
+ notebook / classification project : ipynb file which includes all codes, classification algorithms and range predictions.
+ dataset / train : csv file which is the dataset i worked on it for training.
+ dataset / test : csv file which is the dataset i worked on it for testing.


### :paperclip: Additional Links
---
+ Kaggle : You can follow me on kaggle to check my works and outputs in easier way. [My kaggle profile](https://www.kaggle.com/hameddelavar)
+ Linkedin : Also you can contact me on linkedin by [My linkedin profile](https://www.linkedin.com/in/hamed-delavar-b030172a4)
