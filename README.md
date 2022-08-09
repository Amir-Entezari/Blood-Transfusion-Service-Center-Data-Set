# Blood-Transfusion-Service-Center-Data-Set
In this short project we want to use a dataframe to show scatter plot and box plot
## 1.Box plot
### 1.1 Single Box plot
Box charts are shown individually in the figure below

![image](https://user-images.githubusercontent.com/80061534/183737443-ca41a92d-c889-48ed-b76f-b41ff2ab57bf.png)

![image](https://user-images.githubusercontent.com/80061534/183737496-c2c2b878-1f6a-40a7-a64c-22ba8ba93d76.png)

![image](https://user-images.githubusercontent.com/80061534/183737542-60d66937-0926-4023-ad8c-8209dc9be67b.png)

![image](https://user-images.githubusercontent.com/80061534/183737573-bb90f472-c075-4054-a60a-1254ac334c44.png)

![image](https://user-images.githubusercontent.com/80061534/183737604-78e9d18c-f582-4778-8028-c273456ea529.png)

### 1.2 All Box Plots
Now we draw a box plot for all the columns of the data frame. As we can see, the box plot for the columns (except column 3) is very dense, which is due to the difference in the units of each column. According to the explanations of the class and the book, the frequency chart is better than the rest of the charts because there is a lot of outlier data in the rest of the charts.

![image](https://user-images.githubusercontent.com/80061534/183738046-ec0325c9-bcee-4885-953b-d11e3cec9226.png)

![image](https://user-images.githubusercontent.com/80061534/183738071-d61f9498-0970-4dc8-a9fe-1d463b1ea55a.png)

## 1.Scatter Plot
### 2.1 Single Scatter Plot
In the figure below, we see an example of a scatter plot for the second column of the data frame

![image](https://user-images.githubusercontent.com/80061534/183738324-a9deb81f-ec1e-4267-b2a8-dece50965ec2.png)

### 2.2 All Scatter Plots
Now, if we draw the graph for all the columns, we will get the following figure. The graphs that have more dispersion are better graphs (because they have more distance and as a result, their similarity is less)

![image](https://user-images.githubusercontent.com/80061534/183738676-5087ae5a-de58-46f3-817d-1291801ee738.png)

In the data transformation operation, a function is used that maps the entire set of values of an assumed attribute to a new set of values. This is done in such a way that each of the old values can be identified with one of the new values. For example, a number of conversion functions are: absolute value, power, logarithm,....
Now, in the figure below, we convert the graph based on the logarithm of two to give us a better view of the data

![image](https://user-images.githubusercontent.com/80061534/183738940-930ae1ac-3b73-44a0-8a94-0a6c80d17a41.png)

As it can be seen in the figure, the data are not well separated from each other even with logarithm 2. We will also try this for the logarithm of 10 to get a better picture

![image](https://user-images.githubusercontent.com/80061534/183739119-763d1226-db2f-441e-9fdc-65a4bcd8467c.png)

It is not possible to separate the data from each other in this image, but it can be said that the time and monitoring charts are in a better position, and the data distribution is more in the frequency and monitoring charts.
Now we square the data to get a better comparison

![image](https://user-images.githubusercontent.com/80061534/183739455-5f27fb0e-d827-4f2e-a7d0-da2f30d87600.png)

In this case, it can be seen that Mantri's chart is spread more than others
  Now, for the last time, we use a combination of the previous transformations
  
![image](https://user-images.githubusercontent.com/80061534/183739531-6348b0ba-22e0-4940-ab0b-1ff923445bba.png)
  
In general, in a scatter plot, we tend to display each record as a point in a multidimensional space. But when the dimensions increase, it will be more difficult for us to display the records and understand them. In 2D scatter plots, all records are plotted based on two features. For this purpose, we consider all the desired features in pairs and for each state, we draw all the records based on the two considered features. It specifies the values of attributes, positions and locations. Therefore, the greater the dispersion, the lower the similarity and the better the graph
