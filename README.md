## Installation



You can download the R software from [here](https://cran.r-project.org/bin/windows/base/R-3.6.1-win.exe). This software is the core of R-programming. 

We need a good interface which is called R-Studio. You can download it from [here](https://rstudio.com/products/rstudio/download/). 


We need both softwares in our workshop.

If you have problem in downloading it you may download it from [here](http://s1.mihandownload.com/2017/arjmandi/soft/RStudio.Desktop.Open.Source.License.v1.0.136%28www.MihanDownload.com%29.rar​). Please unzip it using the password 'www.mihandownload.com​​​'.



## Needed packages


After finishing installation, please open the software RStudio. You need internet connection for downloading the packages. In the console window,  copy the following and paste it in console, then press enter.

```
install.packages("ggplot2")
install.packages("pheatmap")
```


When it finishes, copy the following and paste it in console, then press enter.

```
source("http://bioconductor.org/biocLite.R"); 
biocLite(c("GEOquery", "limma"))
install.packages("DESeq2")
```




## Slides


I will upload the slides here.



## Sample codes


I will upload the sample codes here.




## Questions


If you have any question, you may ask it in Issue section of this page.




