# Absolute fundamentals of programming for humanists

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/jiemakel/dhintro/master)

This repository is an attempt to give someone from a humanities background the **absolute basic tools** needed to start delving into programming by reading and dissecting ready-made examples that abound on the Internet.

The core idea behind this is that nowadays, for everything in data processing or visualization one wants to do, there is a library (e.g. [Pandas](http://pandas.pydata.org/), [Mallet](http://mallet.cs.umass.edu/), [LDAvis](https://cran.r-project.org/web/packages/LDAvis/README.html), [Matplotlib](http://matplotlib.org/), [Requests](http://docs.python-requests.org/en/latest/), [tm](https://cran.r-project.org/web/packages/tm/index.html), [plotly](https://plot.ly/)). So, nowadays, programming is mostly reading up how on to use these libraries from their documentation, and writing glue code to hook them together to perform what one wants. This is mostly done through trial and error, and lots of googling.

However, in order to understand the documentation and examples, knowledge of some **fundamental concepts of programming** is required.

Therefore, the repository contains first two [Jupyter](http://jupyter.org/) notebooks that describe these core concepts in the two programming languages currently most relevant to data science: [Python](http://python.org/) and [R](https://www.r-project.org/). Jupyter notebooks are interactive notebooks that mix textual and code cells in an interactive manner, which is great for introducing programming concepts in bite-sized chunks (They also happen to be useful building blocks for [literate programming](https://en.wikipedia.org/wiki/Literate_programming) and [reproducible research](https://ropensci.org/blog/2014/06/09/reproducibility/), both important concepts in themselves for data scientists). To open them, you either need to install the [nteract](https://nteract.io/) app, or just use a temporary web instance at [https://try.jupyter.org/](https://try.jupyter.org/). 

If you have a user account at a Finnish university (a HAKA account), things are even easier for you, as there is a ready web environment set up with all the necessary files and libraries already included. To access this, go to https://notebooks.csc.fi/, and log in using your HAKA credentials. Then, you need to navigate to your Account -page, click on "Join Group" and enter the code `meth4dh-x9qk6` as the group code. After this, navigate back to your dashboard, and you should see a "Introduction to methods for digital humanities" environment there that you can launch (you'll need to wait for a bit before it can be accessed).

The two notebooks, [python_intro.pynb](https://raw.githubusercontent.com/jiemakel/dhintro/master/python_intro.ipynb) (right click on the link, choose save as and then upload into Jupyter) and [r_intro.pynb](https://raw.githubusercontent.com/jiemakel/dhintro/master/r_intro.ipynb) (do the same) are intented to be viewed and progressed through side by side (in two browser windows). This way, one also gets a bit deeper understanding of the concepts, and not just the peculiarities of their implementation in a specific language.

After the two introductory notebooks, the reader is advised to move on to [waiwa.pynb](https://raw.githubusercontent.com/jiemakel/dhintro/master/waiwa.ipynb), which contains an actual, relatively simple process where data is sourced, transformed and then visualized. This notebook also contains tasks for the reader that are typical of what one will encounter when doing similar processing on one's own.

Other notebooks of interest include [shakespeare.ipynb](https://raw.githubusercontent.com/jiemakel/dhintro/master/shakespeare.ipynb) and [fiwiki.ipynb](https://raw.githubusercontent.com/jiemakel/dhintro/master/fiwiki.ipynb) which contain two further example workflows, as well as a [reference cheatsheet](programming_cheatsheet.ipynb) to server as a memory aid on the core concepts learned (available also as a [downloadable notebook](https://raw.githubusercontent.com/jiemakel/dhintro/master/programming_cheatsheet.ipynb)). A final notebook is [python_figure_out.ipynb](https://raw.githubusercontent.com/jiemakel/dhintro/master/python_figure_out.ipynb), where the exercise is to figure out what is actually going on in the program using the instructions given in the reference cheatsheet.
