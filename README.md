# Machine Learning and Statistics
### Tasks 2020
### Due: last commit on or before January 1st, 2021
Four tasks will included in Jupyter Notebook. Tasks Descriptor listed below:

### Task 1
##### Task: Write a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places. 
###### Notes: The modules and packages that come as standard with Python cannot be used. 
###### Include research, references and a description of your algorithm.
#### Observations and  Limitations:

### Task 2
#####  Task: The Chi-squared test for independence is a statistical hypothesis test like a t-test. It is used to analyse whether two categorical variables are independent. Use the table in Wikipedia article on Chi-Squared test as an example and validate the outputs stated.
###### Notes: Use scipy.stats to verify the value give in the test and calculate the associated p value.
###### Include references, research and justify your analysis. 
#### Observations and  Limitations:

### Task 3
##### Compare the Microsoft Excel standard deviation functions: STDEV.P and STDEV.S and perform an evaluation the better estimate for standard deviation of a sample of a populate using NumPy package.
###### Note: Research and explain standard deviation, the Excel functions and the differences between them in terms of accuracy of calculation.
###### Use research and NumPy to perform a simulation demonstrating any findings. 
#### Observations and  Limitations:

### Task 4
##### November 30th, 2020: Use scikit-learn to apply k-means clustering to Fisher’s famous Iris data set. You will easily obtain a copy of the data set online. Explain in a Markdown cell how your code works and how accurate it might be, and then explain how your model could be used to make predictions of species of iris
###### Note: Research, apply and assess scikit k-means clustering on Fisher's Data Set to see if it can help predict the species types of the Iris within the data set.
###### Use research and scikit k-means clustering to perform a simulation demonstrating any findings. 
#### Observations and  Limitations:


INTRODUCTION Ronald Aylmer Fisher's Iris data set has been consulted in a vast range of articles and disciplines as noticeable during initial research. Ronald Fisher, himself, was an English statistician firstly, with intrinsic ties to the studies of genetics, eugenics and biology as a whole who compiled the Iris Data Set as per this study (Yates and Mather, 1963). His studies have given him the affectionate title of "Father of Statistics" by some and he believed his various studies allowed greater ties between mathematics and biology as statistics, especially, are useful while trying to explain the various phenomena of science (Yates and Mather, 1963). His own 1936 study titled "The use of multiple measurements in taxonomic problems" portrayed data on three different Iris flower species;- Iris Setosa, Iris Virginica and Iris Versicolor. The data compiled comprised of four features of each species, i.e. sepal length, sepal width, petal length and petal width. The total flowers contained in the data set were 150, split into 50 of each of the three species. All of the attribute information was measured in cm. The data set characteristics are summarized in the following list (Fisher, 1936, adapted from the UCI Machine Learning Repository, Iris data set):

Classes: 3 - Species - Setosa, Virginica, Veriscolor.
No of Inputs: 150 - 50 of each class above.
Number of Attributes: 4 - Sepal Length, Sepal Width, Petal Length, Petal Width.
Attribute Measurement: cm.
Analysis Type: Multivariate
The multivariate analysis type utilized by Fisher allows a range of measurement techniques on this data set as there are more than one variable and those variables are correlated (Olkin and Sampson, 2001). The intention of this project is to firstly, upload the data set, compile various calculations (using the Python programming language) of various variables within the data set and summarize the results with the aid of statistics, tables and diagrams, where required, to attempt to explain its usefulness and its ties to machine learning and data analysis overall.

#### Marking scheme
The following marking scheme will be used to mark your submission out of 100%:
25% Research:
Evidence of research performed on topic; submission based on referenced literature, particularly academic literature; evidence of understanding of the documentation for any software
or libraries used.
25% Development:
Environment can be set up as described; code works without tweaking and as described; code is efficient, clean, and clear; evidence of consideration of standards and conventions appropriate to code of this kind.
25% Consistency:
Evidence of planning and project management; pragmatic attitude to work as evidenced by well-considered commit history; commits are of a reasonable size; consideration of how commit history will be perceived by others.
25% Documentation:
Clear documentation of how to create an environment in which any code will run, how to prepare the code for running, how to run the code including setting any options or flags, and what to expect upon running the code. Concise descriptions of code in comments and README.


The primary resources for data analysis of the simulated dataset in this assignment are:
utilizing python programming language through Anaconda, Visual Studio Code, Python.org tutorials and w3schools tutorials
packages such as scikit, matplotlib and numpy by researching their respective documentation and this will be utilized alongside various other compositions regarding the same.
These will be stored on a Jupyter notebook and submitted and hosted in a Github repository for reviewing.

KEY TERMS/TOOLS IN ASSIGNMENT:
Jupyter - "a loose acronym meaning Julia, Python, and R" (Datacamp, 2019) - The base languages jupyter was created to include but it now includes various other languages, including Python.
GitHub account previously created on GitHub.com for creation of repositories of code, assignment and lecture content input. GitHub is the worlds leading software development and sharing platform which brings together the worlds greatest community of developers (GitHub.com, 2019).
* Descriptive statistics - "are brief descriptive coefficients that summarize a given data set, which can be either a representation of the entire or a sample of a population" Investopedia (2019).
* Mean - average of all numbers.
* Median - is the middle value or average of two middle values of a sorted set of numbers.
* MACHINE LEARNING - allows "computers the ability to learn without being explicitly programmed" (Arthur Samuel). Allows processing of BIG DATA.
* DATA ANALYSIS - is the inspection and modelling of data to discover information and conclusions which may aid the process of decision making.
* DATA MINING - is the examination of existing databases in order to produce new information.
* MULTIVARIATE ANALYSIS: more than two forms of variables for analysis.
* BIVARIATE ANALYSIS: two variable for analysis.
* UNIVARIATE ANALYSIS: one varaible for analysis.
* STANDARD DEVIATION: the variance from the mean. It can be a low or high variance depending on the distribution of differences from the mean.
* Dependent Variable: factor that needs to understood or predicted.
* Independent Variables: the factors that may impact on your dependent variable.
* NumPy is "the fundamental package supported for presenting and computing data with high performance in Python" Phuong and Czygan (2015, p. 11)
* Pandas - "is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language" (pandas Documentation, 2019).
* Matplotlib - "tries to make easy things easy and hard things possible. You can generate plots, histograms, power spectra, bar charts, errorcharts, scatterplots, etc., with just a few lines of code" (Matplotlib Documentation, 2019).
* Seaborn - a higher level data visualization package than matlplotlib which is built on top of it and Waskom has described it as "If Matplotlib “tries to make easy things easy and hard things possible”, seaborn tries to make a well-defined set of hard things easy too.” (Singh, 2019). Seaborn is an amazing Python visualization library built on top of matplotlib and seaborn has a high-level interface as compared to the low level of Matplotlib (Singh, 2019).
Primary Issues:
* Generating accurate data measurements for the data set, using a lot of trial and error.
* Choosing the correct generation and analysis techniques.
* Time keeping in line with other assignments and other aspects as part of entire online course.
* Researching accurate components for all aspects of the project.
* Correctly inputting and learning of the Python programming language used for analysis.
* Learning, testing and editing code and readme file continuously while rememebering to add sources for newly learned material.
* Time management and accuracy of outputs.

Reference List within Notebook: tasks2020.ipynb
README.md - core file for project with content of project contained or described and includes observations and reference list.
iris_csv.csv - csv file containing the Iris dataset, the core component of this project.





APPENDICES



REFERENCE LIST:

Class Content, Background Reading and Python Learning Tutorials were prelimary references supplemented by the following list of references;

Python Software Foundation. Accessed online at: https://www.python.org/
w3Schools.com Tutorials. Accessed online at: https://www.w3schools.com
Python by Programiz Tutorials. Accessed online at: https://www.programiz.com/
Pandas: Python Data Analysis Library. Accessed online at: https://pandas.pydata.org.
NumPy. Accessed online at: http://www.numpy.org
Stack Overflow - Various queries for comparison and improving code output. Accessed online at: https://stackoverflow.com
Matplotlib Tutorials. Accessed online at: https://matplotlib.org/tutorials/index.html
Wikipedia: Introduction to Fisher's Iris Data Set. Accessed online at: https://en.wikipedia.org/wiki/Iris_flower_data_set
Fisher, R. A. (1936) The use of multiple measurements in taxonomic problems. The Annals of Eugenics (1935-1954). Accessed online at: https://onlinelibrary.wiley.com/doi/epdf/10.1111/j.1469-1809.1936.tb02137.x
Kaggle (2019) Machine Learning with Iris dataset. Accessed online at: https://www.kaggle.com/jchen2186/machine-learning-with-iris-dataset
Sci-kit Learn (2019) The Iris dataset. Accessed online at: https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html
Taylor, J. (2011) Stats 202: Data Mining. Stanford Univeristy. Accessed online at: http://statweb.stanford.edu/~jtaylo/courses/stats202/visualization.html
Dong, N. (2019) RPubs: Introduction 1 - Iris dataset. Accessed online at: https://rpubs.com/nandong/imlp-ch1-iris - Introduction to Iris Data set by rPubs.
Tutorialspoint (2019) AI with Python – Supervised Learning: Classification. Accessed online at: https://www.tutorialspoint.com/artificial_intelligence_with_python/artificial_intelligence_with_python_supervised_learning_classification.html
Tutorialspoint (2019) Python - Correlation. Accessed online at: https://www.tutorialspoint.com/python/python_correlation.html
GitHub Inc. “GitHub”. Accessed online at: https://github.com/.
GMIT, “Quality Assurance Framework”. Accessed online at: https://www.gmit.ie/general/quality-assurance-framework.
I. McLoughlin. “Using git for assessments”. Accessed online at: https://github.com/ianmcloughlin/using-git-for-assessments/.
Wikipedia contributors, “Chi-squared test — Wikipedia, the free encyclopedia,” 2020, Accessed online at:https://en.wikipedia.org/w/index.php?title=Chi-squared test&oldid=983024096
Datacamp, 2019
