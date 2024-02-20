# Data-Visualization-on-Heart-Disease-Dataset
We are going to divide the project into 5 parts:

Heart Disease EDA - Age (DistPlot)
Heart Disease EDA - Categorical Columns (Pie Charts)
Heart Disease EDA - ViolinPlot
Heart Disease EDA - Correlation - (JointPlot)
Heart Disease EDA - Corrlation (PairPlot)

Heart Disease EDA - Age (DistPlot)
In seaborn, a distplot is a function that plots a histogram, kernel density estimate (KDE) plot, and/or rug plot on a single figure. It is used to visualize the distribution of a single continuous variable.
So after doing the visualization we can infer that minimum age is around 30 and maximum age is around 80. Maximum of the data falls within the range of 40 to 70.
![image](https://github.com/Swastik-2k/Data-Visualization-on-Heart-Disease-Dataset/assets/79494966/df945ff8-e7b8-478f-b3b6-ee043eab685c)

Heart Disease EDA - Categorical Columns (Pie Charts)

A pie chart is a circular statistical graphic, which is divided into slices to illustrate numerical proportion. In a pie chart, the arc length of each slice is proportional to the quantity it represents. Pie charts are generally used to show the distribution of a categorical variable.
![image](https://github.com/Swastik-2k/Data-Visualization-on-Heart-Disease-Dataset/assets/79494966/e8c345ff-fa9c-47fe-89aa-49af642e3367)


 
With the help of pie chart we can see that 79% of the people who are having heart disease are males and 21% are females in our dataset.

 

 

Heart Disease EDA - ViolinPlot

In seaborn, a violinplot is a graphical representation of a continuous distribution, showing the probability density of the data at different values. It is a combination of a box plot and a kernel density plot, with a rotated kernel density plot on each side.

![image](https://github.com/Swastik-2k/Data-Visualization-on-Heart-Disease-Dataset/assets/79494966/d9dbf95f-94d1-44be-8884-ac8f7a4e163c)

 
So from this we can see there are more males who are having the chances of having a heart disease compared to females. 

Heart Disease EDA - Corrlation (PairPlot)

A correlation pairplot is a graphical representation of the pairwise relationships between variables in a dataset. It is a matrix of scatter plots, where each scatter plot shows the relationship between two variables. The diagonal of the matrix is a histogram or kernel density plot showing the distribution of one of the variables.

The scatter plots on the upper and lower triangles of the matrix show the relationships between pairs of variables, and the histograms or kernel density plots on the diagonal show the distribution of each variable.

You can customize the appearance of the pairplot by setting various options, such as the color map, marker type, and histogram bin width. You can also plot only a subset of the variables by specifying a list of column names in the vars argument.

Correlation pairplots are useful for visualizing the relationships between variables in a dataset and identifying potential correlations that may be of interest. They can also be used to identify variables that are highly correlated, which may be indicative of multicollinearity in a statistical model.

 

 

Heart Disease EDA - Correlation - (JointPlot)

A correlation jointplot is a graphical representation of the joint distribution of two variables, along with their individual distributions. In seaborn, you can create a jointplot using the jointplot function.

The plot includes a scatterplot of the data, with a regression line showing the trend, as well as histograms or kernel density plots of the individual variables on the x- and y-axes.

You can customize the appearance of the jointplot by setting various options, such as the marker type, color map, and bin width. You can also specify the type of plot to use for the individual variables, such as a histogram or kernel density plot.

Jointplots are useful for visualizing the relationship between two variables and the individual distributions of the variables. They can also be used to identify patterns in the data and to estimate the strength of the relationship between the variables.
![image](https://github.com/Swastik-2k/Data-Visualization-on-Heart-Disease-Dataset/assets/79494966/a1d0d4df-ab8d-4fba-a945-8dcdf0692386)



 
So from this we can see based on Cholesterol how the MaxHR is changing.
