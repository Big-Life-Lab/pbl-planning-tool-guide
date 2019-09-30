# Project Big Life Planning Tool guidance document

The Project Big Life Planning Tool (http://planning.projectbiglife.ca/) was developed to support public health surveillance, planning and research. Amongst other uses, the planning tool can assess the health burden of health behaviours and the potential health impact of public health prevention strategies in Canada. 

This guidance document outlines **what the tool is**, **how it to use it**, and **how it operates**. The guidance includes the following sections:

- **Introduction:** learn about what the tool does and why you would use it
- **Getting started:** get a feel of how to use the tool with the tutorial
- **How-to:** learn how to use the tool with the practical step-by-step guides 
- **Real life applications:** see how you can apply the tool in your work
- **Key concepts:** understand how the tool works
- **Glossary:** reference terms used in the tool and guidance document

## Contributing
We welcome suggestions and additions to the Project Big Life Planning Tool documentation. Please follow [this guide](contributing/CONTRIBUTING.MD) if you would like contribute.

## Do you have a senerio or use of the planning tool that you would like to share with others?

Please tell us if you have scenarios or uses of the planning tool that you want to share with others by making a comment in this [issue](https://github.com/Big-Life-Lab/PBL-Planning-Tool-Guidance/issues/9).

## Downloading the Project Big Life Planning Tool guidance repository
Feel free to copy this repository. To do so, complete the following steps (which have been adapted from Yihui Xie's [_Bookdown: Authoring Books and Technical Documents with R Markdown_](https://bookdown.org/yihui/bookdown/)):

1) Download the latest version of R if your version is earlier then 1.0.0.

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

