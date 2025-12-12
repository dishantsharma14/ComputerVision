<h1>Computer Vison for Environmental Change Detection Project</h1>


<h2>Description</h2>
Mines, wineries and growing population in Chile put pressure on already scarce water supply. Meltwater from glaciers feed rivers in this region, so, estimating recent changes in glacier area is important from water policy perspective. In this individual project, I used Landsat Satellite images from 2000 and 2025 to measure glacier area loss. I used a supervised Machine Learning technique - Random Forest - to classify images into 6 land-cover classes based on pattern-recognition. The results showed a 50% loss of glacier area in this time period. Accuracy assessment was done using Error/Confusion matrices which produced an overall classification accuracy of 85%.
<br />


<h2>Platforms Used</h2>

- <b>Erdas Imagine</b> 
- <b>LucidChart AI</b>
- <b>Microsoft Excel</b>

<h2>Project walk-through:</h2>

<p align="center">
Annonated Study Area Map created in ArcGIS Pro :  <br/>
<img src="https://i.imgur.com/gTFDG4Q.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Data Extraction from Multiple Sources: <br/>
<img src="https://i.imgur.com/XN7uk4l.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/rtN5Pf4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Extracting Multidimentional Data (NetCDF) using Xarray:  <br/>
<img src="https://i.imgur.com/WpAhrgB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Data Cleaning in Excel and Pandas (Daily Lake Level data from 1965-2023): <br/>
<img src="https://i.imgur.com/AMuuDTK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/y2XzSar.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
EDA and Time-Series Analysis:  <br/>
<img src="https://i.imgur.com/jALJify.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/hVWrwhx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Examining Climate Data Quality:  <br/>
<img src="https://i.imgur.com/BJrd35W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Correlation Matrix of Explanatory Variables and Dependent Variable (Lake Level):  <br/>
<img src="https://i.imgur.com/H7DUIcM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
BoxPlot to Analyze Monthly Variation in Lake Level:  <br/>
<img src="https://i.imgur.com/pFUgm3w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Using ANOVA to Evaluate Relationship between ENSO Phases (Categorical Variable) with Lake Levels:  <br/>
<img src="https://i.imgur.com/3i8wqiE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/WxHPQxo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br />
<br />
Running Multiple Linear Regression:  <br/>
<img src="https://i.imgur.com/IQ2wNrq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/29f4wrv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Final Model (Post-Calibration and Removal of Insignificant Variables):  <br/>
<img src="https://i.imgur.com/E4BKhAg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
We predicted a lower than mean lake level for the year 2025, and that held true as of December, 2025.
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
