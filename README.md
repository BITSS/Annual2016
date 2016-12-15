# 2016 BITSS Annual Meeting Software Workshop
by [Garret Christensen](http://www.ocf.berkeley.edu/~garret),
UC Berkeley ([Berkeley Initiative for Transparency in the Social Sciences](http://www.bitss.org) & [Berkeley Institute for Data Science](http://bids.berkeley.edu))
and [Cory Belden](http://coryrbelden.weebly.com/), UC Davis

## Contents:
## Workshop Agenda
## Materials description
## Installation Instructions
-------------------------------
### Agenda
The software workshop is from 10a-12p in the David Brower Center in Berkeley, CA. The agenda for the rest of the workshop can be found [here](http://www.bitss.org/wp-content/uploads/2015/12/AM2016_Agenda-1.pdf).

-------------------------
### Materials for the 2016 BITSS Annual Meeting Workshop

The numbered files/directories will take you through the workshop in order.

First, 1-Tools-Intro contains slides introducing software tools for reproducibility: specifically version control and dynamic documents.

Second is a set of materials to learn dynamic documents in different languages:
* 2-StataLaTeX shows a two-step method of combining Stata and LaTeX.

* 2-StataMarkdoc shows a one-step method in Stata using the markdoc add-on. It's still under development.

* 2-Rmarkdown shows a complete one-stop-shop of version-controlled one-click analysis and final paper in R Studio.

Third, 3-GitDemo.md is a set of tasks to work through to learn Git & Github.

-----------

## Installation Instructions
The workshop will introduce you to two major sets of tools that can help you make your workflow more reproducible: version control and dynamic documents. It will be helpful if you could install the following software programs before coming to the workshop, but I can assist you with it if you have issues.


### 1. Dynamic Documents with Stata and  R/R Studio

Dynamic documents allow you to write just one file that contains both your analysis code and your output (i.e. your final paper) so you can easily and reproducibly manage your work. The next time you return to a figure or table after six months and think "Where on earth is the code that generated this?" it will be obvious.

##### A Two-Step Workflow with LaTeX
Learning LaTeX for document production is a pretty daunting task, but it's quite powerful. Depending how many LaTeX users are in class, I'll describe a two-click workflow with LaTeX plus Stata/R/any stats package. You can get LaTeX [here](https://latex-project.org/ftp.html). Note that it's a large download.

##### Dynamic Documents in Stata

First, Stata isn't free. Sadly, we can't provide you with any sort of demo copy, but anyone with a UC Berkeley login can use it through [Citrix](http://citrix.berkeley.edu).

Although far less well developed in Stata than in R, dynamic documents can be created using the Markdoc ado created by E.F. Haghish. To install, run the following commands in Stata:

```
ssc install markdoc

ssc install weaver

ssc install statax

```
You may also get some links about installing Pandoc and wkhtmltopdf. You need to install those as well.

If you have ever installed these before, run ```adoupdate``` to see if you need to update.

##### Dynamic Documents in R

[R](https://www.r-project.org/) is an open source statistical analysis tool, and [R Studio](https://www.rstudio.com/products/RStudio/) is a very nice centralized tool for managing code and viewing data and output all in one program. Please download both. (At the R link, pick a location near you to download; at the R Studio link, pick R Studio Desktop.)

### 2. Version Control with Git and the Github Desktop app

Version control is a powerful way to carefully track revisions to your documents as well as to manage collaboration. Git and Github Desktop are packaged together [here](https://desktop.github.com/). Git is the command line tool, and Github Desktop is a GUI version of the same tool. There are actually [a whole bunch of GUI apps](https://git-scm.com/downloads/guis) that can act as front ends, so you might find later that you prefer another, but we'll stick with Github Desktop for the demo.

##### Optional: Specifics for Specifics Platforms

Git itself works on all platforms, but Github Desktop only works on Mac and Windows. If you're a Linux user, you might try one of [these](https://git-scm.com/download/gui/linux). Also if you're a Windows user, the command line tool that comes with Github Desktop is not the greatest, so you might want to download [this alternative](https://git-scm.com/download/win). If you've never used the command line before or any of this is confusing, don't worry about it and I'll try to clear it up at the workshop.  


### 3. A good text editor

Writing good code is facilitated by a good text editor. You can get away without one because you almost certainly already have a program on your computer that can save simple ASCII text files (Notepad for Windows, or TextEdit for Mac--but change the default from Rich Text to Plain Text) but modern text editors do syntax highlighting, auto-complete, and a bunch of other cool stuff for you. I suggest [Atom](http://atom.io). Other people like Notepad++ or Sublime.
