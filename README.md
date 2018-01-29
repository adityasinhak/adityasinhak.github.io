## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/adityasinhak/adityasinhak.poorly.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

<style type="text/css">

.reveal pre code {
  display: block; padding: 0.3em;
  font-size: 1em;
  
</style>

Developing Data Products : R Markdown Presentation & Plotly - Heatmap
========================================================
author: Aditya Sinha
date: 28/01/2018


Overview
========================================================

The **Interactive Plots** presented in this Assignment are as follows -

1. A **Heatmap** depicting the Daily Ozone Levels in New York over a period of 5 months (May to September 1973).
2. A **Time-Series chart** of the Population of the United States (in millions) for the period 1790-1970.

Data used
========================================================

The data used for this Assignment is as below:



```
     Ozone           Solar.R           Wind             Temp      
 Min.   :  1.00   Min.   :  7.0   Min.   : 1.700   Min.   :56.00  
 1st Qu.: 18.00   1st Qu.:115.8   1st Qu.: 7.400   1st Qu.:72.00  
 Median : 31.50   Median :205.0   Median : 9.700   Median :79.00  
 Mean   : 42.13   Mean   :185.9   Mean   : 9.958   Mean   :77.88  
 3rd Qu.: 63.25   3rd Qu.:258.8   3rd Qu.:11.500   3rd Qu.:85.00  
 Max.   :168.00   Max.   :334.0   Max.   :20.700   Max.   :97.00  
 NA's   :37       NA's   :7                                       
     Month            Day      
 Min.   :5.000   Min.   : 1.0  
 1st Qu.:6.000   1st Qu.: 8.0  
 Median :7.000   Median :16.0  
 Mean   :6.993   Mean   :15.8  
 3rd Qu.:8.000   3rd Qu.:23.0  
 Max.   :9.000   Max.   :31.0  
                               
```

Plotly - Interactive Plot 1: Heatmap







<iframe src="demo.html" style="position:absolute;height:50%;width:50%"></iframe>












