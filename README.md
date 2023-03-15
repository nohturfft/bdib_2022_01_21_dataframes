# bdib_2022_01_21_dataframes

Axel Nohturfft  
St. George's University of London  
21-January-2022. 


## Topics covered  

1. Creating, reading and writing (saving) data frames  
2. Viewing, inspecting and summarising data frames  
3. The "tidy data" concept  
4. Editing and reshaping data frames  
5. Subsetting (filtering) and cleaning data  


### Install packages  

We will be using a number of different R packages.  
Please install these by running the following code from the command prompt:  

```
if (!require(magrittr)) install.packages("magrittr")
if (!require(readr)) install.packages("readr")
if (!require(readxl)) install.packages("readxl")
if (!require(lubridate)) install.packages("lubridate")
if (!require(ggplot2)) install.packages("ggplot2")
if (!require(DT)) install.packages("DT")
if (!require(knitr)) install.packages("knitr")
if (!require(rmarkdown)) install.packages("rmarkdown")
```

Alternatively, you can install packages using the RStudio `Tools > Install Packages...` menu.  

### To create a copy of this repository in RStudio follow these steps:  

1. Start RStudio  
2. File menu > New project...  
3. Choose: Version Control > Git  
4. Paste the following address into the "Repository URL" field: https://github.com/nohturfft/bdib_2022_01_21_dataframes  
5. Press tab key ("Project directory name" field will be filled automatically)  
6. Choose a desired folder in the "Create project as subdirectory of..." field  
7. Click the "Create project" button  
8. Open the first script ...

