# Python Visualization for Exploration of Data

## Tutorial presented at PyData San Francisco, August 2016  

The lessons contained in the Jupyter notebook, revolve around exploration of the characteristics of a number of automobiles. The ultimate goal is to build a model for predicting the price of a car from its characteristics. However, in these lessons you will focus on data exploration using visualization techniques. 

## About this Jupyter Notebook
The Jupyter notebook contains material to help you learn how to explore data visually. This notebook and the data set can be downloaded from GitHub:

**https://github.com/Quantia-Analytics/DyDataSF2016Visualization**  

This notebook was constructed using the Anconda 3.5 Python distribution. If you are not running version Anaconda 3.5 or higher, we suggest you update your Anaconda distribution now.  You can download the Python 3 Anaconda distribution for your operating system from the [Continum Analytics web site](https://www.continuum.io/downloads

To run this notebook you need the seaborn graphics packages. If you have not done so, you will need to install seaborn as it is not in the Anaconda distribution as of now. From a command prompt on your computer type the following command. If no errors occur, you will have installed seaborn.

``pip install seaborn``

## Why visualization?

Visualization is an essential method in any data scientist’s toolbox. Visualization is a key first step in the exploration of most data sets. As a general rule, you should never start creating models until you have examined the data and understand the relationships. Otherwise, you risk wasting your time creating models blindly. Visualization is also a powerful tool for presentation of results and for determining sources of problems with analytics. 

The concepts of exploring a data set visually were pioneered by John Tukey in the 1960s and 1970s. Tukey consolidated his many ideas on data exploration into a book in the late 1970s, ***John Tukey, Exploratory Data Analysis, 1977, Addison-Westley***.

Bill Cleveland documented his seminal work in visualization of complex data sets in his book, ***William S. Cleveland, Visualizing Data, 1993, Hobart Press***.

The key concept of exploratory data analysis (EDA) or visual exploration of data is to understand the relationships in the data set. Specifically using visualization when you approach a new data set you can:

- Explore complex data sets, using visualization to develop understanding of the inherent relationships.
- Use different chart types to create multiple views of data to highlight different aspects of the inherent relationships.
- Use plot aesthetics to project multiple dimensions. 
- Apply conditioning or faceting methods to project multiple dimensions



These lessons are divided into three parts. In each part you will learn how to use the visualization tools availble in Python.

- **Overview of plot types** is a reivew of creating basic plot types used to construct visualizations.
- **Using Asthetics** is an overview of how to project additional plot dimensions using plot asthetics.
- **Facetted plotting** also know as conditioned plotting or lattice plotting introduces a powerful method for visualizing higher dimensional data. 

In these exercises, you will use both pandas plotting and the seaborn package. We assume you have at least a bit of experience using pandas and Jupyter notebooks.  


## Resources

In this tutorial we will work with two powerful Python packages, Pandas and Seaborn. Both packages have extensive online documentation. There is an extensive tutorial on [**Visualizaton with Pandas**](http://pandas.pydata.org/pandas-docs/version/0.18.0/visualization.html).  The [**Seaborn tutorial**](https://stanford.edu/~mwaskom/software/seaborn/tutorial.html) contains many examples of data visualization. 
