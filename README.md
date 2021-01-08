![GMIT Logo](https://github.com/Munster2020/HDIP_CSDA_COMP08050_PROJECT/blob/main/GMIT_Logo.jpg)
# Higher Diploma in Science in Computing (Data Analytics)
## Fundamentals of Data Analysis (COMP07084) - Project 2020
This module was an introduction to the fundamentals of data analysis, including the acquisition, cleaning and exploration of data sets. As part of the assessment we had to complete four tasks outlined below.

### 1. Repository Structure
1. Readme:
[README.md](https://github.com/Munster2020/HDIP_CSDA_COMP07084_PROJECT/blob/main/README.md)

2. Jupyter Notebook:
[project2020.ipynb](https://github.com/Munster2020/HDIP_CSDA_COMP07084_PROJECT/blob/main/project2020.ipynb)

3. PDF of Jupyter Notebook:
[project2020.pdf](https://github.com/Munster2020/HDIP_CSDA_COMP07084_PROJECT/blob/main/project2020.pdf)

4. Images Folder
[images](https://github.com/Munster2020/HDIP_CSDA_COMP07084_PROJECT/tree/main/images)

4. Power Production CSV
[powerproduction.csv](https://github.com/Munster2020/HDIP_CSDA_COMP07084_PROJECT/blob/main/powerproduction.csv)

If you have any issues viewing tasks2020.ipynb in github you can use Jupyter NBViewer which is a web application behind The Jupyter Notebook Viewer at https://nbviewer.jupyter.org/

### 2. Software used

![logo](https://github.com/Munster2020/HDIP_CSDA_COMP07084_PROJECT/blob/main/images/JupyterN.png "Jupyter")
![Jupyter](https://jupyter.org/) Jupyter is a free, open-source, interactive web tool known as a computational notebook, which researchers can use to combine software code, computational output, explanatory text and multimedia resources in a single document. (Source:downloads.com)

![logo](https://github.com/Munster2020/HDIP_CSDA_COMP07084_PROJECT/blob/main/images/cmdr.png "Cmder")
![Cmdr](https://cmder.net/) provides you with an alternative to the Windows default command prompt utility through a more capable console emulator that also comes packing a good-looking graphical user interface. (Source:downloads.com)

![logo](https://github.com/Munster2020/HDIP_CSDA_COMP07084_PROJECT/blob/main/images/scikit.png "Scikit")
![Scikit](https://scikit-learn.org/stable/index.html) (formerly scikits.learn) is a free software machine learning library for the Python programming language. (Source:downloads.com)

---
### 3. Project

__Problem statement__: In this project we had to perform and explain simple linear regression using Python on the powerproduction dataset available on Moodle.

The goal is to accurately predict wind turbine power output from wind speed values using the data set as a basis. Our submission had be in the form of a git repository containing, at a minimum, the following items:

- Jupyter notebook that performs simple linear regression on the data set.
- In that notebook, an explanation of your regression and an analysis of its accuracy.
- Standard items in a git repository such as a README.

To enhance our submission, we had to consider comparing simple linear regression to other types of regression on this data set.

The project is divided into nine sections outlined below.

__1.0__ Wind Energy

__2.0__ Simple Linear Regression

__3.0__ Importing the required libraries

__4.0__ Creating dataframe

__5.0__ Data exploration

__6.0__ Summary statistics

__7.0__ Simple linear regression algorithm

__8.0__ Polynomial regression algorithm

__9.0__ References

---

__1.0 Wind Energy__: This section of my project provides an outline of energy demand in the world and how wind energy contributes to this. I also provide some fact and figures on the contribution of wind energy both in Ireland and the wider world along with criteria applied in the location of wind energy turbines. 

__Learnings__: When researching wind energy and wind turbines for the project I gained a new appreciation for energy demand and the factors influencing the location of wind turbines. I also learned to download and add additional functionality in Jupyter Notebooks, including using the add-ons "Autopep8", "spellchecker" and "Table of Contents(2)". Autopep8 is excellent for formatting your code correctly, while spellchecker comes in handy in correcting those pesky spelling mistakes.

__Topics__: research, wind turbines, energy supply and demand.

---

__2.0 Simple Linear Regression__: This section covers linear regression and the equation used to perform it.

__Learnings__: linear regression, Scikit-Learn.

__Topics__: regression, linear regression.

---

__3.0 Importing the required libraries__: This section covers importing the libraries used for this project. I used Pandas for importing and manipulating the dataset. NumPy for generating arrays and Matplotlib and Seaborn for data visualisation. I also used Scikit-Learn for train_test_split() method, and regressions.

__Learnings__: I learned two things in this section. I got an understanding of Scikit-Learn and a way of making plots clearer by using the magic command %config InlineBackend.figure_format = ‘retina’.

__Topics__: NumPy, Pandas, Scikit-Learn, retina display magic command.

---

__4.0 Creating dataframe__: This is where I read in the data from the powerproduction.csv and create a dataframe. 

__Learnings__: Dataframe creation.

__Topics__: Pandas, dataframes.

---

__5.0 Data exploration__: In this section I explore the powerproduction.csv dataset. There are only two columns in the dataset ```speed``` and ```output```. Both are floats and there is 500 records in the dataset with no null values. I also provide some initial observations which are aligned with the research I carried out on wind turbine technology.

__Learnings__: I suppose what I took away from this section was the importance of taking your time and carrying out detailed research on the topic the data relates to in order to better understand the data and it's attributes.

__Topics__: Research, wind turbines, Pandas methods.

---
