Regression analysis is the process of determining how related or unalike two variables are when compared with each other. It is helpful to think if the case in which two variables are considered, the dependent and independent variable. 

A dependent variable is the outcome you hope to observe under conditions determined by measuring the independent variable. Say you want to determine the correlation of plant growth under certain conditions. With a given [[periodicity|period]] over the course of some months, you sit down before a baby coffee plant and [[measurement|measure]] its height as it grows. You provide the same amount of light each day, and administer a constant amount of water. These are your control variables At the end of your experiment, you collate the dates and heights and plot them. Here's the example rendered in python.

		from matplotlib import pyplot as plt
		import numpy
		
		x = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
		y = [0.2, 0.6, 1.6, 2.4, 4.1, 6.0, 11.7, 16.2, 21.4, 27.4]
		
		plt.plot(x,y,'go')
		plt.xlabel('weeks')
		plt.ylabel('height in cm')
		plt.title('plant_growth')
		plt.show()
		
And here's the plot!

![[plant_growth.png]]

The information above is a visual representation of a hypothetical coffee plant, growing over time and under very specific conditions. In the course of your investigation, you have found a clever way to project three dimensional information into two dimensions -- congratulations, you are a wizard!

But what does this mean? Take a look at the plot and as you do, notice that the data points seem to trend upwards over time. Of course! We expected the plant to grow *up* and so it did. We have recorded the state of the system. Each data point is a representation of state. We can use this information to develop a mathematical model of the growing plant. 

A [[model]] is a way to use reliable mathematics to describe the states of a system over a chosen domain. Let's examine the case of the growing plant. From algebra, we know that a line has the characteristic form of 


Now, there may be several variables associated with *why* the plant did this, and it would be helpful to 

Code and plots mine, some words taken from the [Harvard Business Review's post](https://hbr.org/2015/11/a-refresher-on-regression-analysis) published within Analytics and Data Science on regression analysis. November 4, 2015.

I am also taking notes from [this textbook](https://users.aalto.fi/~ave/ROS.pdf), *Regression and Other Stories* by 

#data #regression-analysis #user-guide  #statistics