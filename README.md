# Introduction to Numerical Python for Engineers, [YouTube](https://www.youtube.com/watch?v=sY1_SU1U_3E)

**Hello**! Numerical programming is becoming a key skill for modern engineers and you will need to use Python in some of your modules for labs and coursework. This is a quick introduction to numerical programming in [Python](https://www.python.org/) using a set of interactive  [Jupyter](https://jupyter.org/) notebooks. 
1. [Python Basics](https://colab.research.google.com/github/weymouth/NumericalPython/blob/main/01PythonBasics.ipynb)
1. [Conditionals and Lists](https://colab.research.google.com/github/weymouth/NumericalPython/blob/main/02ConditionalsAndLists.ipynb)
1. [Numerical Python and Plotting](https://colab.research.google.com/github/weymouth/NumericalPython/blob/main/03NumpyAndPlotting.ipynb)
1. [Example: Potential flow plot](https://colab.research.google.com/github/weymouth/NumericalPython/blob/main/04FlowPlotExample.ipynb)
1. [Scientific Python library](https://colab.research.google.com/github/weymouth/NumericalPython/blob/main/05SciPy.ipynb)

## How to complete this introduction?

You can use these notebooks in two ways:
- You can run the notebooks on [google colab](https://research.google.com/colaboratory/faq.html). This is extremely convenient, requiring nothing but a Google account! Just click the links above to get started.
- Alternatively, you can run the notebooks on your own machine. To do this, you need to download this github repository using the green `code` button above; for example as a [zip file](https://github.com/weymouth/NumericalPython/archive/main.zip) or using github desktop. If you haven't already, you should also [install Anaconda](https://docs.anaconda.com/anaconda/install/). This will install Python and the Jupyter notebook environment, letting you run the notebooks locally.

I've also made a [playlist on youtube](https://youtube.com/playlist?list=PLQO9vKCRROdZkciP8FwS9SaQ1hlgy_wYt) going through the notebooks. **You won't learn much from watching the videos alone!** Make sure to complete the exercises by running the notebooks in one of the two ways described above.

## Why use programming for analysis?

The programming approach is **highly** preferred to using spreadsheets (like `Excel`) which are [extremely dangerous to use for important work](https://www.forbes.com/sites/timworstall/2013/02/13/microsofts-excel-might-be-the-most-dangerous-software-on-the-planet/?sh=536d1fa0633d). Well documented spreadsheet errors have led to catastrophes in [business](https://www.marketwatch.com/story/88-of-spreadsheets-have-errors-2013-04-17), [economic policy](https://www.bloomberg.com/news/articles/2013-04-18/faq-reinhart-rogoff-and-the-excel-error-that-changed-history) and [health care](https://www.theguardian.com/politics/2020/oct/05/how-excel-may-have-caused-loss-of-16000-covid-tests-in-england). This is because:
- Spreadsheets *hide their methodology* behind the data. This makes it difficult and error-prone to transfer methods to new data. In contrast, a program *is* the methodology, making testing and reproduction much easier.
- Spreadsheets are not extensible. Their limited numerical methods make them inappropriate for any advanced engineering analysis.

## Why use Python?

![Python is growing like wildfire](SharedScreenshot.jpg)

Python has a few important advantages as a numerical programming language:
- Python is in high demand. This means learning Python is a good way to improve your job prospects; particularly for engineering positions related to data-science and machine learning.
- Python has the largest community of users and developers. [The figure above](https://insights.stackoverflow.com/trends) indicates that Python is around five times larger than any other programming language used for numerical work. This means Python is being continuously developed and tested, and it is very easy to get help.
- It is open-source and free to use. This helps the community grow and also ensures future employers can use your skills - no need to pay for a Matlab license. 
- Python is easy to learn and the lessons are generally transferable to other languages. A basis in Python will help make other growing numerical languages like [Julia](https://julialang.org/) and [R](https://www.r-project.org/about.html) more approachable. 

## What if I need more help?

This introduction is meant to get you familiar with numerical Python as quickly as possible. It assumes very little knowledge of programming, but accelerates quickly up to fairly advanced examples. If you are a complete beginner or if you prefer a slower pace then you might try these additional resources:
 - https://www.udemy.com/course/python-for-absolute-beginners-u/
 - https://www.kaggle.com/learn/overview
 - https://docs.python.org/3/tutorial/
 - https://numpy.org/devdocs/user/quickstart.html
