# Image Classification Project

The objective of this Project is to classify wheter a labeled image is considered as a Person or not.

## Data Set

Data set was downloaded from the following source: http://cocodataset.org/#download
Json files must be stored in a folder in the root of the R Project


## Libraries and other dependencies

Make sure to install the following libraries that are required for the Project to work.
Libraries should be installed with the following command: install.packages("libraryname")

```bash
install.packages(readr)
install.packages(dplyr)
install.packages(jsonlite)
install.packages(ggplot2)
install.packages(magick)
install.packages(stringr)
install.packages(data.table)
```

## Load libraries and code in R Notebook

```bash
library(readr)
library(dplyr)
library(jsonlite)
library(ggplot2)
library(magick)
library(stringr)
library(data.table)
```

## Other dependencies

h2o is required for the Models to work. Please make sure h2o is installed and loaded before you run Models.

```bash
install.packages(h2o)
library(h2o)
h2o.init()
```
Java is also required, follow the steps to download the latest version of java before running h2o packages and initiating the JVM.

Most recent version of Java can be downloaded from the following website:
https://www.oracle.com/java/technologies/javase-downloads.html

