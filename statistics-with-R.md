## Statistics with R

**Credits:** notes from the course [Introduction à la statistique avec R, Paris Saclay](https://www.fun-mooc.fr/courses/course-v1:ParisSaclay+71007+session14/about)

Review some notions: https://www.khanacademy.org/math/statistics-probability/analyzing-categorical-data 

Recommended book : https://rstudio-education.github.io/hopr/preface.html
R and data sciences: https://r4ds.had.co.nz/

https://rstudio-education.github.io/hopr/starting.html

### Download and installation (Ubuntu 20)

download and install last release  of R from the official website :  https://cran.r-project.org/

There is a apt for it:
        
    sudo apt install r-base

there also a links for precompiled binary versions, available for Windows, Mac and Linux.

*Rstudio*

As Rstudio for Ubuntu isn't available, download the one for Ubuntu18 Jessie. 

    dpkg -i rstudio-1.3.1073-amd64.deb

You might need to run another command to fix dependancies issues.

    sudo apt --fix-broken install
    
### Launch R interpreter, run Rstudio

Start Rstudio from the launchpad of Ubuntu

or/and

$R
runs the R interpreter in your terminal 

If you need a graphic interface, dl Rstudio https://rstudio.com/products/rstudio/download/


## Run RStudio

First install packages you'll need to draw plots: 

        Tools -> Install Packages... ->  and select package you want to install in the dialog box; here "gplots"
       
### starting keys

- In addition to the visual interface, you can launch instructions directly in the R interpretor (the **console**) and see the output (crucial for errors)
- Graphs are generated in another window.
- **R scripts** have the extention **.r**
- you hit a script by running the instruction source()

- You call the help menu by running the instruction **help()**. 

### variables

- variables names are **Case-senSitiVe** 
- Missing value is encoded such as **NA**
- mode() display the variable type *numeric* or *character* and lenght() the number of item in the variable
- factor() and levels() are helps to qualify a variable: **factor()** for what qualitative value of the variable, **labels=** for labelling the variable

to keep in mind : Variable = (element1, element2, element2, element3,...)  it's like **supervariable= []** and a lot of things inthere.


### vocabulary:
http://vita.had.co.nz/papers/layered-grammar.pdf

stat : statistical transformation

plot : 

aesthetic mapping: 

scale:  

geom:  geometric objects 
