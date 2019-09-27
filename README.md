#Guidance for the Project Big Life Planning Tool 

The Project Big Life Planning Tool (http://policy.projectbiglife.ca/) was developed in order to support health professionals: research, plan, develop, and evaluate evidence-based health interventions.

This guidance document outlines **what the tool is**, **how it to use it**, and **how it operates**. The guidance includes the following sections:

- **Introduction:** learn about what the tool does and why you would use it
- **Getting started:** get a feel of how to use the tool with the tutorial
- **How-to:** learn how to use the tool with the practical step-by-step guides 
- **Real life applications:** see how you can apply the tool in your work
- **Key concepts:** understand how the tool works
- **Glossary:** reference terms used in the tool and guidance

This guidance document was created using RStudio and the bookdown package.


##Downloading the Project Big Life Planning Tool guidance repository

You may want make modifications to the Project Big Life Planning Tool repository or use it as a starting point for your own guidance document. In these cases you will have to download the Project Big Life Planning Tool repository and open it on your computer. To do so, complete the following steps. (These steps have been adapted from Yihui Xie's "Bookdown: Authoring Books and Technical Documents with R Markdown" https://bookdown.org/yihui/bookdown/.)

1) Download the latest version of R if your version is lower then 1.0.0.

2) Install the R package **bookdown**

```{}
install.packages("bookdown")
```

3) Install the following R packages if you don't already have them:
```{}
install.packages("knitr")
install.packages("kableExtra")

install.packages('tinytex')
tinytex::install_tinytex()
```
*Both lines of code are required to install tinytex

4) Download the Github repository https://github.com/Big-Life-Lab/PBL-Planning-Tool-Guidance as a Zip file, then unzip it locally. 
5) Open the downloaded ```PBL-Planning-Tool-Guidance``` repository in RStudio by clicking ```PBLT-guidance.Rproj```.

6) Open the R markdown file ```index.Rmd```. A tab ```Build``` now appears in the right corner beside the tabs: environment and history. Click the ```Build Book``` button under the ```Build``` tab.

