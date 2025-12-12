<h1>Computer Vision for Environmental Change Detection Project</h1>


<h2>Description</h2>
Mines, wineries and growing population in Chile put pressure on already scarce water supply. Meltwater from glaciers feed rivers in this region, so, estimating recent changes in glacier area is important from water policy perspective. In this individual project, I used Landsat Satellite images from 2000 and 2025 to measure glacier area loss. I used a supervised Machine Learning technique - Random Forest - to classify images into 6 land-cover classes based on pattern-recognition. The results showed a 50% loss of glacier area in this time period. Accuracy assessment was done using Error/Confusion matrices which produced an overall classification accuracy of 85%.
<br />


<h2>Platforms Used</h2>

- <b>Erdas Imagine</b> 
- <b>LucidChart AI</b>
- <b>Microsoft Excel</b>

<h2>Project walk-through:</h2>

<p align="center">
Workflow:  <br/>
<img src="https://i.imgur.com/mOIaBQl.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<br />
Subset satellite image to AOI: <br/>
<img src="https://i.imgur.com/gkdijQE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create >9000 objects using FLS segmentation :  <br/>
<img src="https://i.imgur.com/dNGI08J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create training datsets for 6 land cover classes: <br/>
<img src="https://i.imgur.com/SZmHIAI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Data preprocessing and training RF Model:  <br/>
<img src="https://i.imgur.com/iOuz6aN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/nuVtbVd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/1REkire.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
Run the trained model to classify satellite image:  <br/>
<img src="https://i.imgur.com/ajdWouX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Accuracy assessement (Error Matrix) using 60 randomly stratified selected points:  <br/>
<img src="https://i.imgur.com/RWBmJck.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Accuracy assessment report (Overall Accuracy=85%):  <br/>
<img src="https://i.imgur.com/9lSdfcb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/bd5ntsj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Bar Chart shows change in land cover in last 25 years:  <br/>
<img src="https://i.imgur.com/Nvnbuyh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
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
