# Fisher-s-Iris-Data-Set-2019

# This reposititory contains the Project 2019 for Programming and Scripting.
# Karolina Szafran-Belzowska, 2019-04-25

This repository contains my solutions to the "Problem Set 2019" for the module "Programming and Scripting" at GMIT.
See here for the instructions : https://github.com/ianmcloughlin/problems-pands-2019/raw/master/problems.pdf 
The Iris data set concerns 150 flowers irises, which are described 4 traits (conditional attributes): length and width of the petal,
and length and width of the stem. In addition, we have an attribute decision-making (class) which takes three possible values: 
"Iris-setosa", "Iris-Versicolor" and "Iris-virginica", which divide a set of 50 observations for each of these classes (33.3%).

Numbers of instances: 150 (50 in each of three classes)

Numbers of attributes: 4 numeric and 3 classes

Attribute information:
1. Sepal length in cm,
2. Sepal width in cm,
3. Petal length in cm,
4. Petal width in cm,
5. and classes: Iris Setosa, Iris Versicolour, Iris Virginica

## How to download this repository
  1. Go to GitHub
  2. Click the download button.
  
## How to run the code
  1. Make sure you have Python installed

## Libraries used
Imported the libaries for this project: Pandas, Numpy, Matplotlib.pyplot

Pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools.

NumPy is the fundamental package for scientific computing with Python

Matplotlib.pyplot is a collection of command style functions that make matplotlib work like MATLAB.

     import numpy as np
     import pandas as pd
     import matplotlib.pyplot as plt 

## Import data
Imported the irisdata.csv / irisdata_project_2019.csv and examined all of the columns in the data.

    readCSV = csv.reader(data, delimiter=',')
    data = np.genfromtxt('irisdata.txt', delimiter=',')
       # I can specific which column I want to investigate 
    firstcol = data[:,0]
    meanfirstcol = np.mean(data[:,0])
       # I investigated all three classes of Iris flower
    data = ("irisSetosa.csv")
    names = ['sepal-length', 'sepal-width', 'petal-length', 'petal-width','species']
    dataset = pd.read_csv(data, header=0)

## Discover the histagram 
  
    pl.hist(firstcol)
    pl.show()
    
## Summarise the data using the panda library

    dataset = pd.read_csv(data, header=0)

## What each file contains
 
### iris_data_set.py 
contains Python code to show the whole Iris Flower Data Set in file.  This file stores tabular data in plain text. Each line of the file is a data record. Each record consists of one or more fields, separated by commas. The data which is called "The Iris flower data set" or "Fisher's Iris data set" is a multivariate data set introduced by the British statistician and biologist Ronald  Fisher in his 1936. 
   
   References: https://en.wikipedia.org/wiki/Iris_flower_data_set;
               https://stackoverflow.com/;
               https://www.sololearn.com/.
    
### irisdata.csv 
contains the whole data in .csv file which I created in Visual Studio Code. Adapted from: https://gist.github.com/curran/a08a1080b88344b0c8a7

### irisdata_project_2019.csv 
is again the whole data but in tabular way and as above it was adapted from: https://gist.github.com/curran/a08a1080b88344b0c8a7

### irisdata.txt 
contains the whole data in .txt file

### iris_data_data_set_txt.py
contains Python code to show the whole Iris Flower Data Set using .txt file

### firstcol_irisdata.py
contains the first column of the whole Iris Flower Data Set,
References: https://web.microsoftstream.com/video/74b18405-5ee1-47f0-a42d-e8831a453a91 (Dr Ian McLoughlin's video - week 9)

### secondcol_irisdata.py
contains the second column of the whole Iris Flower Data Set

### thirdcol_irisdata.py
contains the third column of the whole Iris Flower Data Set

### fourthcol_irisdata.py
contains the fourth column of the whole Iris Flower Data Set

### summarise.py
contains the summarise of the whole Iris Data Set,
References: https://machinelearningmastery.com/python-machine-learning-mini-course/
https://www.youtube.com/watch?v=Q06Y3DUSwz4

### firstcol_histagram.py
contains Python code to show a histagram of first column - sepal length and the mean of this column,
References: https://web.microsoftstream.com/video/74b18405-5ee1-47f0-a42d-e8831a453a91 (Dr Ian McLoughlin's video - week 9)

### firstcol histagram.png
contains histagram of first column

### secondcol_histogram.py
contains Python code to show a histagram of second column - sepal width and the mean of this column,
References: as above.

### secondcol histagram.png
contains histagram of second column

### thirdcol_histagram.py
contains Python code to show a histagram of third column - petal length and the mean of this column,
References: as above.

### thirdcol histagram.png
contains histagram of third column

### fourthcol_histagram.py
contains Python code to show a histagram of fourth column - petal width and the mean of this column,
References: as above.

### fourthcol histagram.png
contains histagram of fourth column

### irisSetosa.csv
contains the data just Iris Setosa in .csv file which I created in Visual Studio Code. Adapted from: https://gist.github.com/curran/a08a1080b88344b0c8a7

Iris setosa also known as bristle-pointed iris. [Here you can see how this flower looks like.](https://en.wikipedia.org/wiki/Iris_setosa)

### irisSetosa_summarise.py
Contains summarise of Iris Setosa Data.

### Iris_setosa.jpg
Shows an image of Iris Setosa.

### irisVersicolor.csv
contains the data just of Iris Versicolor in .csv file which I created in Visual Studio Code. Adapted from: https://gist.github.com/curran/a08a1080b88344b0c8a7

Iris versicolor also known as the blue flag, harlequin blueflag, larger blue flag, northern blue flag and poison flag. [Here you can see how this flower looks like.](https://en.wikipedia.org/wiki/Iris_versicolor)

### irisVersicolor_summarise.py
Contains summarise of Iris Versicolor Data.

### iris_versicolor.jpg
Shows an image of Iris Versicolor.

### irisVirginica.csv
contains the data just of Iris Virginica in .csv file which I created in Visual Studio Code. Adapted from: https://gist.github.com/curran/a08a1080b88344b0c8a7

Iris virginica also known as Virginia iris. [Here you can see how this flower looks like.](https://en.wikipedia.org/wiki/Iris_virginica)

### irisVirginica_summarise.py
Contains summarise of Iris Virginica Data.

### Iris_virginica.jpg
Shows an image of Iris Virginica.

### investigation_data.py
Contains the shape, the minimum, maximum, mean, median and the standard deviation values of each column.


### The following websites helped me to solve most of the problems: 
https://www.sololearn.com/; https://docs.python.org/3/library/: https://www.youtube.com/; https://stackoverflow.com/; https://en.wikipedia.org/wiki/Iris_flower_data_set https://www.geeksforgeeks.org/python-pandas-series/; https://machinelearningmastery.com/python-machine-learning-mini-course/; https://help.github.com/en/articles/adding-a-file-to-a-repository; https://guides.github.com/features/mastering-markdown/
