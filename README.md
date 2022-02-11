# NAP-IV
NBM AWS Python - Interactive Viewer

This jupyter-notebook-based interactive viewer interfaces with the NOAA NBM (National Blend of Models) AWS S3 Bucket to visualize any of the available variables.  

Before running, you will need to add a "./data" folder for collecting data.

NBM data can be perused here: 
https://registry.opendata.aws/noaa-nbm/

In the interactive viewer, users can 
<ol>
  <li>select the variable they would like to display,</li>
  <li>select a different the colorscale, </li>
  <li>adjust the max, min, and number of contours on the colorscale,</li>
  <li>scale the map by lat-lon coordinates,</li>
  <li>and select which forecast hour to display.</li>
</ol>

In code, users can 
<ul>
  <li>add different map layers, </li>
  <li>pull archived dates from the AWS bucket,</li>
  <li>pull NBM QMD grib data,</li>
  <li>pull other AWS grib data,</li>
  <li>change map projections,</li>
  <li>and alter units of variables before plotting.</li>
</ul>

Users will need to add their credentials to the AWS CLI to use the AWS downloading with boto3.
