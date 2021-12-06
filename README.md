# India_vs_Rest_of_the_world
It contains the code and data for the  2021 Kaggle Machine Learning &amp; Data Science Survey Competition 
| Folium Map   |      Altair Chart |
|----------|:-------------:|
| ![](https://github.com/AslanDevbrat/India_vs_Rest_of_the_world/blob/main/folium.gif) | ![](https://github.com/AslanDevbrat/India_vs_Rest_of_the_world/blob/main/scatter_bar.gif) | 


This project is a part of Kaggle's annual Machine Learning and Data Science Survey competiThe challenge objective: tell a data story about a subset of the data science community represented in this survey, through a combination of both narrative text and data exploration. A “story” could be defined any number of ways, and that’s deliberate. The challenge is to deeply explore (through data) the impact, priorities, or concerns of a specific group of data science and
machine learning
practitioners. That group can be defined in the macro (for example: anyone who does most of their coding in Python) or the micro (for example: female data science students studying machine learning in masters programs). This is an opportunity to be creative and tell the story of a community you identify with or are passionate about!tion.


## Libraries Used
In this project I have explored two new Python Libraries 
  - Folium: Python library used for visualizing geospatial data. 
  - Altair: Altair is a declarative statistical visualization library for Python, based on Vega and Vega-Lite

I have combined these two libraries to plot some amazing Interactive Maps with Dynamic Charts in it. All the chart and Plot are dynamic i.e. You can zoom in, zoom out or select a region in all the charts.
[Link To the original Kaggle Submission](https://www.kaggle.com/devbratanuragi17078/india-vs-rest-of-the-world/notebook)


## Gender Stats on Map

This Plot is combination of Marker Cluster of folium and the Bar chart of the altair. It shows the Gender Distribution of Data science community of a particular Country. The major observation is Data Science Community is dominated by Men.
![image](https://user-images.githubusercontent.com/39759685/144818024-049e9829-a1aa-4dfd-adff-5bd39b988f8d.png)

## Age Distribution using Altair

In this plot you can see the Age Distribution of people working in Data science related fields with country. You can Drag a region over the Scatter Plot to select the Country of your Interest and the bar graph will simultaneously show the age distribution for the particular country.
![image](https://user-images.githubusercontent.com/39759685/144818033-ba049a72-06cc-4b47-baf6-d66866508007.png)

## Gender distribution Using Altair
This plot show the gender Distribution using the stacked Bar. Here instead of getting the bar plot for all the countries you will get only for the selected countries. 
![image](https://user-images.githubusercontent.com/39759685/144818108-794b6ce7-9369-444b-b79e-ced5740314cb.png)

Now once I have explored Altair and Folium separately its time to combine these two. First I have Plotted Some Red labels on the map. On clicking on those red labels one can find a bar chart comparing India the other country.

# Gender Comparison in Data science Community (India Vs. Rest of the World)
In this you can click on any red marker, each marker consists of two plots, one for India and One for the country of which you have selected the label. Now you can compare the Gender stats of India with other country side-by-side.
![image](https://user-images.githubusercontent.com/39759685/144818205-167dec2b-e654-40ed-b046-5f089cbe4645.png)

### Observation:
In all countries Men dominated the Data science.

# Education Comparison in Data science Community (India Vs. Rest of the World
In this you can click on any red marker, each marker consists of two plots, one for India and One for the country of which you have selected the label. Now you can compare the Education level of people of India, working in the Data Science Related Field with other country side-by-side.
![image](https://user-images.githubusercontent.com/39759685/144818353-f0c0ea57-b892-4f5e-8e90-ca74b3447632.png)


### Observation:
Developed Country have more number of people having Master Degree working in Data science compared to Developing Countries.  In Developing Countries Majority have Bachelor’s Degree


# Profession Comparison in Data science Community (India Vs. Rest of the World)
In this you can click on any red marker, each marker consists of two plots, one for India and One for the country of which you have selected the label. Now you can compare the Profession of people of India, working in the Data Science Related Field with other country side-by-side. 
![image](https://user-images.githubusercontent.com/39759685/144818483-93dcb425-dd31-44f4-b6ac-3fb85ac51b5f.png)


### Observation:
Students contribute immensely in this field than the Professional.


# Years of Experience Comparison in Data science Community (India Vs. Rest of the World)
In this you can click on any red marker, each marker consists of two plots, one for India and One for the country of which you have selected the label. Now you can compare the Years of Experience of people of India, working in the Data Science Related Field with other country side-by-side. 

![image](https://user-images.githubusercontent.com/39759685/144818605-fcdd69f8-0ec2-4f72-8a27-19acbf7c6596.png)


### Observation:
Most of the people working In Data science have 1-3 year of experience. It suggest that this field have gained popularity in past few years
