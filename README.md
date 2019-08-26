# Metric-Analysis-of-effect-of-Partial-Shading-on-Solar-Panels
Final year Bachelor’s thesis-based project on solar energy analytics. In a group of two, pre-processed data and developed a model to predict the efficiency of solar panel installations during shading. The results of the model across different installations were 90% accurate.


This data set contains an energy analysis for 12 different building shapes, which differ in glazing area, the distribution of glass, the orientation of the building, and other attributes. The dependent variables are heating load and cooling load.

The dataset contains eight attributes (or features, denoted by X1...X8) and two responses (or outcomes, denoted by y1 and y2) and is available in EnergyEfficiency.csvPreview the document.

The R-code for the analysis on the cooling data is here.

The aim is to use the eight features to predict the heating load using neural network analyses.

Tasks

Prepare the data for neural network analysis. You may use the code demonstrated in class with the cooling load dependent variable.
Develop predictions of the heating load for the training and the test data sets. Compare the predictive accuracy for the training and test data sets. Comment on any differences between the results for the training and test data.
Try models with varying numbers of node and 1 or 2 hidden layers. Which seems to work the best?
Develop predictions for the training and test data set using linear regression. Compare the results of the regression with the results obtained using neural networks. Which method is more accurate? How does the accuracy of regression differ for the training and test data?


 

Variable list

           Relative Compactness 
           Surface Area 
           Wall Area 
           Roof Area 
           Overall Height 
           Orientation 
           Glazing Area 
           Glazing Area Distribution 
           Heating Load 
           Cooling Load

 

Details on the variables

Relative Compactness(RC): It specifies compactness. The RC of a shape is derived in that its volume to surface ratio is compared to that of the most compact shape with the same volume.

Surface Area: Total surface area in m2. It’s same as (wall Area + 2 * roof Area)

Wall Area: Total wall area in m2 x Roof Area: Total roof area in m2

Overall Height: Height of the building. It’s very correlated with Roof Area as the volume is fixed.

Orientation: Orientation of the building: has 4 values for 4 directions 

Glazing Area: Area covered in glass, expressed in terms of percentages of Roof Area- 0%, 10%, 25% and 40%. 

Glazing Area Distribution: Six different distribution scenarios- 1) uniform: with 25% glazing on each side, 2) north: 55% on the north side and 15% on each of the other sides, 3) east: 55% on the east side and 15% on each of the other sides, 4) south: 55% on the south side and 15% on each of the other sides, and 5) west: 55% on the west side and 15% on each of the other sides, 6) case where Glazing Area is 0%. 

Heating Load: Amount of heating required in the building to maintain comfortable indoor air conditions

Cooling Load: Amount of cooling required in the building to maintain comfortable indoor air conditions
