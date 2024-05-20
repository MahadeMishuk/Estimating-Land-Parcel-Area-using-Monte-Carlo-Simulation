# Estimating-Land-Parcel-Area-using-Monte-Carlo-Simulation

Introduction
The purpose of this project is in real estate or environmental assessment, it's often necessary to estimate the area of irregularly shaped land parcels. Traditional methods may be time-consuming or impractical. Monte Carlo simulation offers could be an alternative approach to estimate the area efficiently.

Monte Carlo Simulation
Monte Carlo simulation is a technique that uses random sampling and modeling to estimate mathematical functions and the operations of complex systems. Monte Carlo simulation can provide an effective and accurate means of calculating the area. The method involves generating random points within a boundary and using these points to approximate the area of the land parcel.

Goucher College Campus
  
In my project I choose a complex irregular polygon shape Goucher Campus to esitimates it's area by using Monte-Carlo Simulation. For tools, I have used PlotDigitizer (https://www.PlotDigitizer.com/app) to plot Goucher College land acre area which I defind x1 to x2 is 30 units, as well y1 to y2 30 units, I took small area of graph for smooth calculation. Later which I will compare with actual area of Goucher College by using calcmaps(https://www.calcmaps.com/map-distance/).


Methodology
1.	Data Collection: Obtain detailed maps and satellite imagery of the Goucher College campus. I created a dataset using PlotDigitizer software. The csv file name Goucher.csv (attached)
2.	Boundary Definition: Define the boundaries of Goucher land to measure. Boundaries is important for the Monte Carlo simulation.
3.	 Random Point Generation: Generate a large number (7000) of random points within the defined boundary and rectangle area.
4.	Area Estimation: Calculate the proportion of random points that fall within the parcel boundaries. Use this proportion, along with the total area of the bounding box, to estimate the area.
5.	Validation and Comparison: Compare the Monte Carlo simulation results with actual area to assess accuracy and efficiency of this method.
