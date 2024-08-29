---
title: "Step-by-Step Guide: Creating a Linear Calibration Curve Using Microsoft Excel"
date: 2024-08-27 22:49:17
updated: 2024-08-29 11:35:31
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/272ead7cf67b3a822b77b0890cd7f03854b0d3a76e27e4ba95f164ba07265247.jpg
---

## Step-by-Step Guide: Creating a Linear Calibration Curve Using Microsoft Excel

### Quick Links

* [What is a Calibration Curve and How is Excel Useful When Creating One?](https://ai-video-tools.techidaily.com/speed-up-your-storytelling-time-lapse-video-creation-in-final-cut-pro-for-2024/)
* [Let's Look at an Example](https://location-social.techidaily.com/in-2024-how-to-change-your-oppo-f25-pro-5g-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/)

 Excel has built-in features that you can use to display your calibration data and calculate a line-of-best-fit. This can be helpful when you are writing a chemistry lab report or programming a correction factor into a piece of equipment.

 In this article, we'll look at how to use Excel to create a chart, plot a linear calibration curve, display the calibration curve's formula, and then set up simple formulas with the SLOPE and INTERCEPT functions to use the calibration equation in Excel.

##  What is a Calibration Curve and How is Excel Useful When Creating One?

 To perform a calibration, you compare the readings of a device (like the temperature that a thermometer displays) to known values called standards (like the freezing and boiling points of water). This lets you create a series of data pairs that you'll then use to develop a calibration curve.

 A two-point calibration of a thermometer using the freezing and boiling points of water would have two data pairs: one from when the thermometer is placed in ice water (32**°**F or 0**°**C) and one in boiling water (212**°**F or 100**°**C). When you plot those two data pairs as points and draw a line between them (the calibration curve), then assuming the response of the thermometer is linear, you could pick any point on the line that corresponds to the value the thermometer displays, and you could find the corresponding "true" temperature.

 So, the line is essentially filling in the information between the two known points for you so that you can be reasonably certain when estimating the actual temperature when the thermometer is reading 57.2 degrees, but when you have never measured a "standard" that corresponds to that reading.

 Excel has features that allow you to plot the data pairs graphically in a chart, add a trendline (calibration curve), and display the calibration curve's equation on the chart. This is useful for a visual display, but you can also calculate the formula of the line using Excel's SLOPE and INTERCEPT functions. When you enter these values into simple formulas, you will be able to automatically calculate the "true" value based on any measurement.

##  Let's Look at an Example

 For this example, we will develop a calibration curve from a series of ten data pairs, each consisting of an X-value and a Y-value. The X-values will be our "standards," and they could represent anything from the concentration of a chemical solution we are measuring using a scientific instrument to the input variable of a program that controls a marble launching machine.

 The Y-values will be the "responses," and they would represent the reading the instrument provided when measuring each chemical solution or the measured distance of how far away from the launcher the marble landed using each input value.

 After we graphically depict the calibration curve, we will use the SLOPE and INTERCEPT functions to calculate the calibration line's formula and determine the concentration of an "unknown" chemical solution based on the instrument's reading or decide what input we should give the program so that the marble lands a certain distance away from the launcher.

###  Step One: Create Your Chart

 Our simple example spreadsheet consists of two columns: X-Value and Y-Value.

![creating an x-value and y-value column](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-01.png) 

 Let's start by selecting the data to plot in the chart.

 First, select the 'X-Value' column cells.

![select the x-value column](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-02.png) 

 Now press the Ctrl key and then click the Y-Value column cells.

![hold Ctrl while clicking the Y-value column](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-03.png) 

 Go to the "Insert" tab.

![insert tab](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-04.png) 

 Navigate to the "Charts" menu and select the first option in the "Scatter" drop-down.

![choose charts &gt; scatter](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-05.png) 

 A chart will appear containing the data points from the two columns.

![the chart appears](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-06.png) 

 Select the series by clicking on one of the blue points. Once selected, Excel outlines the points will be outlined.

![select the data points](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-07.png) 

 Right-click one of the points and then select the "Add Trendline" option.

![choose the add trendline option](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-08.png) 

 A straight line will appear on the chart.

![the trendline now displays on the chart](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-09.png) 

 On the right side of the screen, the "Format Trendline" menu will appear. Check the boxes next to "Display Equation on chart" and "Display R-squared value on chart." The R-squared value is a statistic that tells you how closely the line fits the data. The best R-squared value is 1.000, which means every data point touches the line. As the differences between the data points and the line grow, the r-squared value drops, with 0.000 being the lowest possible value.

![the format trendline pane](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-10.png) 

 The equation and R-squared statistic of the trendline will appear on the chart. Note that the correlation of the data is very good in our example, with an R-squared value of 0.988.

 The equation is in the form "Y = Mx + B," where M is the slope and B is the y-axis intercept of the straight line.

![the equations now show on the chart](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-11.png) 

 Now that the calibration is complete, let's work on customizing the chart by editing the title and adding axis titles.

 To change the chart title, click on it to select the text.

![changing the chart title](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-12.png) 

 Now type in a new title that describes the chart.

![the new titles appears on the chart](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-13.png) 

 To add titles to the x-axis and y-axis, first, navigate to Chart Tools > Design.

![head to chart tools &gt; design](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-14.png) 

 Click the "Add a Chart Element" drop-down.

![click the add chart element button](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-15.png) 

 Now, navigate to Axis Titles > Primary Horizontal.

![head to axis tools &gt; primary horizontal](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-16.png) 

 An axis title will appear.

![the axis title appears](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-17.png) 

 To rename the axis title, first, select the text, and then type in a new title.

![changing the axis title](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-18.png) 

 Now, head to Axis Titles > Primary Vertical.

![adding a primary vertical axis title](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-19.png) 

 An axis title will appear.

![showing the new axis title](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-20.png) 

 Rename this title by selecting the text and typing in a new title.

![renaming the axis title](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-21.png) 

 Your chart is now complete.

![viewing the complete chart](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-22.png) 

###  Step Two: Calculate the Line Equation and R-Squared Statistic

 Now let's calculate the line equation and R-squared statistic using Excel's built-in SLOPE, INTERCEPT, and CORREL functions.

 To our sheet (in row 14) we've added titles for those three functions. We'll perform the actual calculations in the cells beneath those titles.

 First, we will calculate the SLOPE. Select cell A15.

![select the cell for the slope data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-23.png) 

 Navigate to Formulas > More Functions > Statistical > SLOPE.

![Navigate to Formulas &gt; More Functions &gt; Statistical &gt; SLOPE](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-24.png) 

 The Function Arguments window pops up. In the "Known\_ys" field, select or type in the Y-Value column cells.

![select or type in the Y-Value column cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-25.png) 

 In the "Known\_xs" field, select or type in the X-Value column cells. The order of the 'Known\_ys' and 'Known\_xs' fields matters in the SLOPE function.

![select or type in the X-Value column cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-26.png) 

 Click "OK." The final formula in the formula bar should look like this:

        `=SLOPE(C3:C12,B3:B12)`
    
 Note that the value returned by the SLOPE function in cell A15 matches the value displayed on the chart.

![slope value displayed](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-27.png) 

 Next, select cell B15 and then navigate to Formulas > More Functions > Statistical > INTERCEPT.

![navigate to Formulas &gt; More Functions &gt; Statistical &gt; INTERCEPT](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-28.png) 

 The Function Arguments window pops up. Select or type in the Y-Value column cells for the "Known\_ys" field.

![Select or type in the Y-Value column cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-29.png) 

 Select or type in the X-Value column cells for the "Known\_xs" field. The order of the 'Known\_ys' and 'Known\_xs' fields also matters in the INTERCEPT function.

![Select or type in the X-Value column cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-30.png) 

 Click "OK." The final formula in the formula bar should look like this:

        `=INTERCEPT(C3:C12,B3:B12)`
    
 Note that the value returned by the INTERCEPT function matches the y-intercept displayed in the chart.

![showing the intercept function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-31.png) 

 Next, select cell C15 and navigate to Formulas > More Functions > Statistical > CORREL.

![navigate to Formulas &gt; More Functions &gt; Statistical &gt; CORREL](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-32.png) 

 The Function Arguments window pops up. Select or type in either of the two cell ranges for the "Array1" field. Unlike SLOPE and INTERCEPT, the order does not affect the result of the CORREL function.

![enter the first cell range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-33.png) 

 Select or type in the other of the two cell ranges for the "Array2" field.

![enter the second cell range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-34.png) 

 Click "OK." The formula should look like this in the formula bar:

        `=CORREL(B3:B12,C3:C12)`
    
 Note that the value returned by the CORREL function does not match the "r-squared" value on the chart. The CORREL function returns "R," so we must square it to calculate "R-squared."

![showing the correl function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-35.png) 

 Click inside the Function Bar and add "^2" to the end of the formula to square the value returned by the CORREL function. The completed formula should now look like this:

        `=CORREL(B3:B12,C3:C12)^2`
    
 Press Enter.

![viewing the completed formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-36.png) 

 After changing the formula, the "R-squared" value now matches the one displayed in the chart.

![the r-squared value now matches](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-37.png) 

###  Step Three: Set Up Formulas For Quickly Calculating Values

 Now we can use these values in simple formulas to determine the concentration of that "unknown" solution or what input we should enter into the code so that the marble flies a certain distance.

 These steps will set up the formulas required for you to be able to enter an X-value or a Y-value and get the corresponding value based on the calibration curve.

![enter an X-value or a Y-value and get the corresponding value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-38.png) 

 The equation of the line-of-best-fit is in the form "Y-value = SLOPE \* X-value + INTERCEPT," so solving for the "Y-value" is done by multiplying the X-value and SLOPE and then adding the INTERCEPT.

![values displayed based on input](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-39.png) 

 As an example, we put zero in as the X-value. The Y-value returned should be equal to the INTERCEPT of the line of best fit. It matches, so we know the formula is working correctly.

![showing the zero as the X-value being equal to the INTERCEPT](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-40.png) 

 Solving for the X-value based on a Y-value is done by subtracting the INTERCEPT from the Y-value and dividing the result by the SLOPE:

X-value=(Y-value-INTERCEPT)/SLOPE

![solving for an x value based on a y value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-41.png) 

 As an example, we used the INTERCEPT as a Y-value. The X-value returned should be equal to zero, but the value returned is 3.14934E-06\. The value returned is not zero because we inadvertently truncated the INTERCEPT result when typing the value. The formula is working correctly, though, because the result of the formula is 0.00000314934, which is essentially zero.

![showing a truncated result](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-42.png) 

 You can enter in any X-value you'd like into the first thick-bordered cell and Excel will calculate the corresponding Y-value automatically.

![solving Y for an x value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-43.png) 

 Entering any Y-value into the second thick-bordered cell will give the corresponding X-value. This formula is what you would use to calculate the concentration of that solution or what input is needed to launch the marble a certain distance.

![solving x for a y value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-44.png) 

 In this case, the instrument reads "5" so the calibration would suggest a concentration of 4.94 or we want the marble to travel five units of distance so the calibration suggests we enter 4.94 as the input variable for the program controlling the marble launcher. We can be reasonably confident in these results because of the high R-squared value in this example.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
