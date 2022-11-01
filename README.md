# Rock-Matching

The Contents:
<ol>

<li> Rock_Matching (Hub Rock Based Matching and Neighborhood Polygon Based Matching): <br> 
     This file contains the code for matching algorithms which attempt matching the rocks based on properties of hub rock and properties of polygon formed by connecting n-nearest neighbors of every hub rock. 
     The Properties are: <br> 
     <ul> 
     <li>area
     <li>ecc
     <li>perimeter
     <li>compactness
     <li>convexity
     <li>solidity
     <li>angle
     </ul>
     
<li> Rock_Matching_testing_Exp0 (Matching with same time frame without change):<br>
     Contains code for same experiments as described in 1 but keeping both the time frames identical so as to know the num of incorrect matches. 
     
<li> Rock_Matching_testing_Exp1 (Matching with same time frame with vertical translation):<br>
     Contains code for same experiments as described in 1 but keeping both the time frames identical and translating one time frame vertically.

<li> Rock_Matching_testing_Exp1 (Matching with same time frame with horizonatal translation):<br>
     Contains code for same experiments as described in 1 but keeping both the time frames identical and translating one time frame horizontally.
     
<li> Rock_Matching_Initial_Experiments:<br>
     This file contains code for algorithms matching rocks based on distribution of properties of neighborhood rocks. 
     The algorithms creates such distributions for each hub rock and tries to match the rocks by calculating distance between such distributions. 
     There several ways the explored for distribution matching: <br> 
     <ul>
     <li> TS_SS Based Matching
     <li> Wasstein Materic Based Matching (Earth Mover's Distance) 
     <li> RMSE Based Matching
     </ul>
     This file also contains expriments for matching where matching is done based on the mean of distributions of properties of neighborhood rocks (Area, Distance, Eccentricity).<br>
     It also includes algorithms which perform matching based on second order statistics of neighborhood information. (i.e takin the properties of neighbors of neighbors into account) 
     
     
