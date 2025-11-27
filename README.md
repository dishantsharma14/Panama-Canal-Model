<h1>Panama Canal Water Level Modeling Project</h1>


<h2>Description</h2>
This team project was carried in collaboration with Northern Illinois University (NIU) and Everstream Analytics in 2025. I acted as the Team Leader for a team of 5 members. We developed a multiple regression model to predict future water levels in the Gatun Lake, a major part of Panama Canal. During the periods of low water levels, restrictions are imposed on the number of ships that can pass through the canal. The water levels have become more variable in recent years negatively impacting the businesses. Our purpose was to improve shipping operations efficiency by creating a simple but useful method of predicting water levels in advance. We tested several explanatory variables and finally selected three that gave us the highest R-squared value of 32%. 
<br />


<h2>Languages and Platforms Used</h2>

- <b>Python</b> 
- <b>Jupyter Notebook</b>
- <b>NIU Triton Server</b>
- <b>ArcGIS Pro</b>
- <b>Microsoft Excel</b>

<h2>Project walk-through:</h2>

<p align="center">
Annonated Study Area Map Created in ArcGIS Pro :  <br/>
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
Data Cleaning in Excel and Pandas: <br/>
<img src="https://i.imgur.com/AMuuDTK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/y2XzSar.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Trend Analysis:  <br/>
<img src="https://i.imgur.com/jALJify.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/hVWrwhx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Examining Reanalysis Cimate Data Quality:  <br/>
<img src="https://i.imgur.com/BJrd35W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Correlation Matrix of Explanatory Variables and Dependent Variable (Lake Level):  <br/>
<img src="https://i.imgur.com/H7DUIcM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
BoxPlot to analyze monthly variation in Lake Level:  <br/>
<img src="https://i.imgur.com/pFUgm3w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Using ANOVA to Evaluate Relationship Between ENSO Phases (Categorical Variable) with Lake Levels:  <br/>
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
Final Model (post-calibration and removal of insignificant variables):  <br/>
<img src="https://i.imgur.com/E4BKhAg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
