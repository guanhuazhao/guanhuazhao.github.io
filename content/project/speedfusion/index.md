---
title: Road Detection Data Analysis 
summary: Processing, analysis and fusion of detection data for a certain urban arterial road in Lianyungang, based on Matlab and python
tags:
  - Traffic Data Analysis
  - Chinese
date: '2021-06-21T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: The road segment travel speed by fusing the coil, floating car and avi detector data is based on the BP neural network
  focal_point: Smart

#links:
#  - name: Pdf
#    url: uploads/resume.pdf

url_code: ''
url_pdf: uploads/roadspeed.pdf
url_slides: uploads/roadspeedppt.pdf
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

This project is focused on the processing, analysis, and fusion of detection data for a specific urban arterial road in Lianyungang, utilizing Matlab and Python. The data used in this project consists of simulated data from a 14-hour duration, including four datasets: loop collection, floating vehicle collection, AVI collection, and real data.


Based on the collected data, road schematics, intersection flow, and signal timing plans, I have successfully completed six tasks as required.


The first task involved calculating the average travel speed for the entire arterial road, using real travel speed data as a foundation. Statistical analysis was then conducted to further analyze the results. Additionally, I used a weighted average method to complement the data by removing any anomalies.


Next, the K-means clustering algorithm was applied to analyze three variables - average speed, flow, and occupancy. Subsequently, the Euclidean distance and Dynamic Time Warping (DTW) distance were calculated to understand the dissimilarity between predicted and real data. Furthermore, covariance and correlation coefficient analysis using numpy were employed to examine the relationship between variables. Finally, the estimated errors in travel speed estimation were compared for three different detection methods.


In the final task, the travel speed data obtained from optimizing loop detection using signal control delay at each intersection was combined with new loop data, AVI data, and floating vehicle detection data using a BP neural network to estimate travel speed information for each road segment. The fit of the estimated results was verified by plotting the error chart.


