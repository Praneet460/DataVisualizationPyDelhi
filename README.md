# Exploration and Visualization of Data with Python and libraries like matplotlib and seaborn

#### Short Link to repo - <i>bit.ly/pydelhi_eda</i>

### Hands-on-Session presented at PyDelhi Meetup, September 2018
This Jupyter notebook introduces you to some basic principles of data exploration and visualization using Python language along with the libraries like Matplotlib and Seaborn.
You will learn different methods for exploration of data using visualization techniques. We will use several Python packages to create the visualizations, matplotlib, Pandas plotting, and seaborn.

### About this Jupyter Notebook
To run this notebook you need to install necessary packages, listed down. If you have not done so, you will need to install them first, as these are not in the Anaconda distribution as of now. From a command prompt on your computer type the following command. If no error occurs, you will have installed them.

```pip install seaborn```
```pip install pandas```
```pip install matplotlib```

### How to get started?
Fork the repository to run the jupyter notebook on your own computer.

### About the dataset
The datasets used for exploration is [Pokemon Dataset](https://github.com/Praneet460/DataVisualizationPyDelhi/blob/master/pokemon.csv) 

You can download the dataset from [Kaggle](https://www.kaggle.com/rounakbanik/pokemon/home)

### Why visualization?
<b>“Visualization gives you answers to questions you didn’t know you had.”</b> – [Ben Schneiderman](https://www.cs.umd.edu/users/ben/)

Visualization is an essential method in any data scientist's toolbox. Visualization is a key first step in the exploration of most datasets. These process of exploring data visually and with simple summary statistics is known as <b>Exploratory Data Analysis(EDA)</b>. As a general rule, you should never start creating models until you have an understanding of the relationships in your data. Visualization is also a powerful tool for presentation of results and for determining sources of problems with analytics.

The concept of exploring a dataset visually were pioneered by John Tukey in the 1960s and 1970s.

The key concept of exploratory data analysis(EDA) or visual exploration of data is to understand the relationship in the dataset. Specially using visualization when you approach a new dataset you can:

* Explore complex datasets, using visualization to develop understanding of the inherent relationships.
* Use different chart types to create multiple views of data to highlight differnt aspects of the inherent relationships.
* Use plot aesthetics to project multiple dimensions.
* Apply conditioning methods to project multiple dimensions.

In these exercises, you will use Pandas plotting, Matplotlib and the Seaborn package. We assume you have atleast a bit of experience using Pandas and Jupyter notebooks.

### Basic chart types
There are enumerable chart types that are used for data exploration. Some of them are explained below
* <b>Scatter plot</b> : Scatter plots show the relationship between two variables in the form of dots on the plot. In simple terms, the value along a horizontal axis are plotted against a vertical axis.
* <b>Line plot</b> : Line plots are similar to point plots. In line plots the discrete points are conneced by lines.
* <b>Bar plot</b> : Bar plots are used to display the counts of unique values of a categorical variable. The height of the bar represents the count for each unique category of the variable.
* <b>Histogram</b> : Histograms are related to bar plots. Histograms are used for numeric variables. Whereas, a bar plot shows the counts of unique categories, a histogram shows the number of data with values within a bin. The bin divide the values of the variable into equal segments. The vertical axis of the histogram shows the count of data values within each bin.
* <b>Box plot</b> : Box plots, also known as box and wisker plots, were introduced by John Tukey in 1970. Box plots are another way to visualize the distribution of data values. In this respect, box plots are comparable to histograms, but are quite different in presentation. On a box plot the median value is shown with a dark bar. The inner two quartiles of data values are contained within the 'box'. The 'wiskers' enclose the majority of the data(up to +/-2.5 * interquartile range). Outliers are shown by symbols beyond the wiskers. Several box plots can be stacked along an axis for comparison. The data are divided using a 'group by' operation, and the box plots for each group are atacked next to each other. In this way, the box plot allows you to display two dimensions of your dataset.
* <b>Kernel Density Estimation Plots(KDE)</b> : Kernel density plots are similar in concept to a histogram. A kernel density plot displays the values of a smoothed density curve of the data values. In other words, the kernel density plot is a smoothed version of a histogram.
* <b>Violin plot</b> : A violin plot combines attributes of boxplots and a kernel density estimation plot. Like a box plot, the violin plots can be stacked, with a 'group by' operation. Additionally, the violin plot provides a kernel density estimate for each group. As with the box plot, violin plots allow you to display two dimensions of your dataset.

### About the speaker
These lessons are prepared by <b>Praneet Nigam</b>. He is currently working as a <b>Machine Learning Facilitator</b> for the [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course/). For being in touch with the speaker, contact him on listed down social media links.
* [LinkedIn](https://www.linkedin.com/in/praneet460/)
* [Twitter](https://twitter.com/praneetnigam)
* Email : praneetnigam@paperwrk.in

Some of the past projects of Praneet Nigam
* [OpenAcademy](https://play.google.com/store/apps/details?id=in.paperwrk.openacademyapp)
* [Paperwrk](http://www.paperwrk.in/)

### Resources
In this tutorial we will work with powerful Python packages like Pandas, Matplotlib and Seaborn. These packages have extensive online documentation. There is an extensive tutorial on [Visualization with Pandas](http://pandas.pydata.org/pandas-docs/version/0.18.0/visualization.html). The [Seaborn tutorial](https://seaborn.pydata.org/tutorial.html) contains many examples of data visualization. The matplotlib website has addition [resources for learning plotting with Python tools](https://matplotlib.org/resources/index.html).
