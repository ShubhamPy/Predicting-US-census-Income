# United-States-Census
Build a classification model based on the features that you select to predict person's yearly income is above $50k or not.

## Introduction:
US Adult Census data relating income to social factors such as Age, Education, race etc. The Us Adult income dataset was extracted by Barry Becker from the 1994 US Census Database. The data set consists of anonymous information such as occupation, age, native country, race, capital gain, capital loss, education, work class and more. Each row is labelled as either having a salary greater than ">50K" or "<=50K".
- Note that the dataset is made up of categorical and continuous features. It also contains missing values The categorical columns are: workclass, education, marital_status, occupation, relationship, race, gender, native_country

The dataset consist of 32562 rows and 14 features .
## Prerequisites:
I would highly recommend that before the hack night you have some kind of toolchain and development environment already installed and ready. If you have no idea where to start with this, try a combination like:
* Python
* scikit-learn / sklearn
* Pandas
* NumPy
* matplotlib
* An environment to work in - something like `Jupyter` or `Spyder`
* For Linux people, your package manager should be able to handle all of this. If it somehow can't, see if you can at least install Python and pip and then use pip to install the above packages.

## Dataset:
The data here is for the "Census Income" dataset, which contains data on adults from the 1994 census. This data is labeled with whether the person's yearly income is above or below $50K.
> The dataset is in the form of a csv file you can [download](https://drive.google.com/open?id=1yWtGQjyd_ryTnR0S6P2sl91GmYfPewzz) here.

## WorkFlow:
- [x] Perform data cleaning using pandas library. Which includes replacing the miscoded information and handling missing data.
- [x] Make a Exploratory Data Analysis on the data using pandas.
- [x] Visualize distributions and correlation of features using seaborn and pandas
- [x] Build a classification model for the classification of income.
- [x] Try different classifiers and compare the accuracy of all the classifiers.
## Results:
![alt text](https://github.com/ShubhamPy/Predicting-US-census-Income/blob/master/Screenshot%20(168).png)
### SVM Model give max. accuracy of 83%, also voting classifier model is second most accurate
