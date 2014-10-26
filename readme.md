orolo
========

Fraa Orolo is a Decenarian Fraa from the Concent of Saunt Edhar. He is an 
eminent cosmographer and Erasmas's mentor at the concent, but he's later 
thrown back for using forbidden technology to observe the Geometers in violation
of the Discipline's isolation requirements. - [Anathem](http://en.wikipedia.org/wiki/Anathem)

This repository is a collection of technologies, techniques and associated
artifacts depicting their use. There are so many wonderful technologies and
techniques being created, I typically won't have direct use for them but will
want to remember for a future avocation.

Before the list, here are some anecdotes that I've really enjoyed finding:

[The Zen of Python](http://legacy.python.org/dev/peps/pep-0020/)

    Beautiful is better than ugly.
    Explicit is better than implicit.
    Simple is better than complex.
    Complex is better than complicated.
    Flat is better than nested.
    Sparse is better than dense.
    Readability counts.
    Special cases aren't special enough to break the rules.
    Although practicality beats purity.
    Errors should never pass silently.
    Unless explicitly silenced.
    In the face of ambiguity, refuse the temptation to guess.
    There should be one-- and preferably only one --obvious way to do it.
    Although that way may not be obvious at first unless you're Dutch.
    Now is better than never.
    Although never is often better than *right* now.
    If the implementation is hard to explain, it's a bad idea.
    If the implementation is easy to explain, it may be a good idea.
    Namespaces are one honking great idea -- let's do more of those!

[Composable & Contextual, Dietzler's Law for Access](http://nealford.com/memeagora/2013/01/22/why_everyone_eventually_hates_maven.html)

    Every Access project will eventually fail because, while 80% of what the
    user wants is fast and easy to create, and the next 10% is possible with 
    difficulty, ultimately the last 10% is impossible because you can’t get far
    enough underneath the built-in abstractions, and users always want 100% of 
    what they want.

# Technologies

## Languages

#### Python
[Python](https://www.python.org/)
is a widely used general-purpose, high-level programming language. Its design 
philosophy emphasizes code readability, and its syntax allows programmers to 
express concepts in fewer lines of code than would be possible in languages 
such as C. The language provides constructs intended to enable clear programs 
on both a small and large scale. The standard library has extensive support for
complex data structures and I/O through standard formats and protocols. As of 
January 2014, the Python Package Index, the official repository of third-party 
software for Python, contains more than 38,000 packages.

#### Julia
[Julia](http://julialang.org/)
is a high-level, high-performance dynamic programming language for technical 
computing, with syntax that is familiar to users of other technical computing 
environments. It provides a sophisticated compiler, distributed parallel 
execution, numerical accuracy, and an extensive mathematical function library.

Julia is an ambitious language. It aims to be as fast as C, as easy to use as 
Python, and as statistically inclined as R (to name a few goals).

[Neural networks and a dive into Julia](http://blog.yhathq.com/posts/julia-neural-networks.html)

#### R
[R](http://www.r-project.org/)
is a free software environment for statistical computing and graphics. The
language is widely used among statisticians and data miners for developing
statistical software and data analysis. 

The capabilities of R are extended through user-created packages, which allow 
specialized statistical techniques, graphical devices (ggplot2), import/export 
capabilities, reporting tools (knitr, Sweave), etc. These packages are developed
primarily in R, and sometimes in Java, C and Fortran. A core set of packages is
included with the installation of R, with more than 5,800 additional packages 
and 120,000 functions (as of June 2014) available at the Comprehensive R Archive
Network (CRAN), Bioconductor, and other repositories. 

[10 R packages I wish I knew about earlier](http://blog.yhathq.com/posts/10-R-packages-I-wish-I-knew-about-earlier.html)
[recommender systems in R](http://blog.yhathq.com/posts/recommender-system-in-r.html)

## Visualization

### 2D

#### matplotlib
[matplotlib](http://matplotlib.org)
is Python's most popular and comprehensive plotting library that is 
especially useful in combination with NumPy/SciPy.

[Latexify your matplotlib plots](http://nipunbatra.github.io/2014/08/latexify/)
[Aggregating & plotting time series in Python](http://blog.yhathq.com/posts/aggregating-and-plotting-time-series-in-python.html)


#### Prettyplotlib
[Prettyplotlib](http://olgabot.github.io/prettyplotlib/)
is a nice enhancement-library that turns matplotlib's default
styles into beautiful, presentation-ready plots based on information design and
color perception studies.

#### Seaborn
[Seaborn](https://github.com/mwaskom/seaborn)
is a Python visualization library based on matplotlib. It provides a
high-level interface for drawing attractive statistical graphics.

#### Bokeh
[Bokeh](http://bokeh.pydata.org)
is a plotting library that is focused on aesthetic layouts and
interactivity to produce high-quality plots for web browsers.

#### ggplot
[ggplot](https://github.com/yhat/ggplot)
is a port of R's popular ggplot2 library, which brings the alternative 
syntax and unique visualization style to Python.

[ggplot for python](http://blog.yhathq.com/posts/ggplot-for-python.html)

#### Gizeh
[gizeh](https://github.com/Zulko/gizeh)
is a Python library for vector graphics.

[Vector Animations with Python](http://zulko.github.io/blog/2014/09/20/vector-animations-with-python/)

#### D3js
[D3js](http://d3js.org/)
is a JavaScript library for manipulating documents based on data.

#### D3py
[D3py](https://github.com/mikedewar/d3py)
is a plotting library to create interactive data visualizations based on D3. 

#### C3.js
[C3.js](http://c3js.org/)
is a D3-based reusable chart library that enables deeper integration of
charts into web applications.

#### chartist.js
[chartist.js](https://github.com/gionkunz/chartist-js)
simple responsing charts

#### nvd3
[nvd3](https://github.com/novus/nvd3)
is a collection of re-usable charts and chart components for d3.js.

#### raw
[raw](https://github.com/densitydesign/raw/)
raw is an application to create custom vector-based visualizations on top of D3.js.

#### rickshaw
[rickshaw](https://github.com/shutterstock/rickshaw)
is a library for creating interactive time series graphs based on D3.js.

#### Pre3d
[Pre3d](http://deanm.github.io/pre3d/)
is a JavaScript 3d rendering engine

#### sigma.js
[sigma.js](https://github.com/jacomyal/sigma.js)
is an open-source lightweight library to display interactively static and dynamic 
graphs.

#### arbor.js
[arbor.js](http://arborjs.org/)
is a  library of force-directed layout algorithms plus abstractions for graph 
organization and refresh handling.

#### circos
[circos](http://circos.ca/)
is a software package for visualizing data in a circular layout.

#### gephi
[gephi](http://gephi.org)
is a visualization and exploration platform for networks with dynamic and 
hierarchical graphs.

#### Raphaël
[Raphaël](http://raphaeljs.com/)
is a small library that simplifies working with vector graphics on the web.

#### prefuse
[prefuse](https://github.com/prefuse/Prefuse)
is a set of software tools for creating rich interactive data 
visualizations in the Java programming language.

#### tangle
[tangle](http://worrydream.com/Tangle/)
is a JavaScript library for creating reactive documents.

#### processing
[processing](http://processing.org)
is a visual programming language implemented in Java.

#### processing.js
[processing.js](http://processingjs.org)
is the sister project of the popular Processing visual programming
language, designed for the web.


### 3D

#### three.js
[three.js](http://threejs.org/)
is a lightweight 3D library with a very low level of complexity

#### VisIt
[VisIt](https://wci.llnl.gov/simulation/computer-codes/visit/)
is an Open Source, interactive, scalable, visualization, animation and analysis 
tool. From Unix, Windows or Mac workstations, users can interactively visualize 
and analyze data ranging in scale from small (<101 core) desktop-sized projects 
to large (>105 core) leadership-class computing facility simulation campaigns. 
Users can quickly generate visualizations, animate them through time, manipulate
them with a variety of operators and mathematical expressions, and save the 
resulting images and animations for presentations. VisIt contains a rich set of 
visualization features to enable users to view a wide variety of data including 
scalar and vector fields defined on two- and three-dimensional (2D and 3D) 
structured, adaptive and unstructured meshes. Owing to its customizeable plugin 
design, VisIt is capabable of visualizing data from over 120 different
scientific data formats.

### Mapping

#### kartograph
[kartograph](http://kartograph.org/)
is a simple and lightweight framework for building interactive map 
applications without Google Maps or any other mapping service. It was created 
with the needs of designers and data journalists in mind.

#### polymaps
[polymaps](https://github.com/simplegeo/polymaps)
is a library for making dynamic, interactive maps with image- and vector-based 
tiles.

#### leaflet
[leaflet](http://leafletjs.com/)
is a lightweight JavaScript library for making tile-based interactive maps for 
desktop and mobile browsers.

#### cesium
[cesium](http://cesiumjs.org)
is a JavaScript library for creating 3D globes and 2D maps in a web 
browser without a plugin.

#### unfolding
[unfolding](http://unfoldingmaps.org/)
is a library to create interactive maps and geovisualizations in 
Processing and Java.

### Image Processing

#### Pillow
[Pillow](https://github.com/python-pillow/Pillow)
is the "friendly" PIL fork by Alex Clark and Contributors. PIL is the Python
Imaging Library by Fredrik Lundh and Contributors.

[Little Planet Projection](https://www.richwareham.com/articles/2014/09/29/little-planet-projection)

## Scientific Computing

#### IPython
[IPython](http://ipython.org/notebook.html)
is an alternative Python command line shell for interactive computing 
with lots of useful enhancements over the "default" Python interpreter.  

The browser-based documents IPython Notebooks are a great environment for 
scientific computing: Not only to execute code, but also to add informative 
documentation via Markdown, HTML, LaTeX, embedded images, and in-line data plots 
via e.g., matplotlib. 

#### SciPy
[SciPy](http://scipy.org)
is a considered to be one of the core packages for scientific computing 
routines. As a useful expansion of the NumPy core functionality, it contains a 
broad range of functions for linear algebra, interpolation, integration, 
clustering, and [many more](http://docs.scipy.org/doc/scipy/reference/index.html).

#### NumPy
[NumPy](http://www.numpy.org)
is probably the most fundamental package for efficient scientific 
computing in Python through linear algebra routines. One of NumPy's major 
strength is that most operations are implemented as C/C++ and FORTRAN code for 
efficiency. At its core, NumPy works with multi-dimensional array objects that 
support broadcasting and lead to efficient, vectorized code.

#### Pandas
[pandas](http://pandas.pydata.org)
is a library for operating with table-like structures. It comes with a 
powerful DataFrame object, which is a multi-dimensional array object for 
efficient numerical operations similar to NumPy's *ndarray* with additional 
functionalities.

[Weather forecasting with Twitter and Pandas](http://blog.yhathq.com/posts/predict-weather-with-kaggle-twitter-emoticons-pandas.html)

#### Blaze
[Blaze](https://github.com/ContinuumIO/blaze)
extends the usability of NumPy and Pandas to distributed and out-of-core 
computing. Blaze provides an interface similar to that of the NumPy ND-Array or 
Pandas DataFrame but maps these familiar interfaces onto a variety of other 
computational engines like Postgres or Spark.

#### Theano
[Theano](https://github.com/Theano/Theano)
is an optimizing GPU-meta-programming code generating array oriented optimizing 
math compiler in Python


## Math

#### SymPy
[SymPy](http://www.sympygamma.com)
is a Python library for symbolic mathematical computations. It has a broad
range of features, ranging from calculus, algebra, geometry, discrete 
mathematics, and even quantum physics. It also includes basic plotting 
functionality and print functions with LaTeX support.


## Machine Learning

#### Scikit-learn
[Scikit-learn](http://scikit-learn.org/stable/)
is is probably the most popular general machine library for Python.
It includes a broad range of different classifiers, cross-validation and other 
model selection methods, dimensionality reduction techniques, modules for 
regression and clustering analysis, and a useful data-preprocessing module.

[Predicting Churn with Scikit-Learn](http://blog.yhathq.com/posts/predicting-customer-churn-with-sklearn.html)
[Random forests in Python](http://blog.yhathq.com/posts/random-forests-in-python.html)
[Intuitive Classification using KNN and Python](http://blog.yhathq.com/posts/classification-using-knn-and-python.html)
[Sparse Random Projections](http://blog.yhathq.com/posts/sparse-random-projections.html)
[Doing Data Science in Python](http://blog.yhathq.com/posts/data-science-in-python-tutorial.html)

#### Shogun
[Shogun](https://github.com/shogun-toolbox/shogun)
is a machine learning library that is focused on large-scale kernel 
methods. Its particular strengths are Support Vector Machines (SVMs) and it 
comes with a range of different SVM implementations.

#### PyBrain
[PyBrain](http://pybrain.org)
(Python-Based Reinforcement Learning, Artificial Intelligence and 
Neural Network Library) is a machine learning library that uses neural networks
to focus on supervised learning, reinforcement learning, and evolutionary methods.

#### PyLearn2
[PyLearn2](https://github.com/lisa-lab/pylearn2)
is a machine learning **research** library - a library to study machine
learning - focused on deep and convolution neural networks, restricted Boltzman 
machines, and auto-encoders.

#### PyMC
[PyMC](https://github.com/pymc-devs/pymc)
is a python module for Bayesian statistical modeling and model fitting 
which focuses on advanced Markov chain Monte Carlo fitting algorithms. Its 
flexibility and extensibility make it applicable to a large suite of problems.

#### inspyred
[inspyred](https://github.com/aarongarrett/inspyred)
is a free, open source framework for creating biologically-inspired 
computational intelligence algorithms in Python, including evolutionary 
computation, swarm intelligence, and immunocomputing. Additionally, inspyred 
provides easy-to-use canonical versions of many bio-inspired algorithms for 
users who don't need much customization.

## Statistics

#### statsmodels
[statsmodels](http://statsmodels.sourceforge.net)
is a Python library that is centered around statistical data
analysis mainly through linear models and includes a variety of statistical tests.

[Logistic Regression in Python](http://blog.yhathq.com/posts/logistic-regression-and-python.html)

#### Patsy
[Patsy](https://github.com/pydata/patsy)
is a Python library for describing statistical models (especially linear
models, or models that have a linear component) and building design matrices. 
Patsy brings the convenience of R "formulas" to Python.

#### kcbo
[kcbo](https://github.com/HHammond/kcbo)
is a Bayesian testing framework written in Python.


## Image Processing

#### Scikit-image
[Scikit-image](http://scikit-image.org/)
is a collection of algorithms for image processing. It is available
free of charge and free of restriction.

[Image Processing with Scikit-image](http://blog.yhathq.com/posts/image-processing-with-scikit-image.html)

## Scraping

#### dragline
[dragline](https://github.com/inzyte/dragline)
is a distributed python web crawling framework.


## Profiling

#### snakefood
[snakefood](http://furius.ca/snakefood/)
Python Dependency Graphs

# Topics

# References
[datavisualization.ch](http://selection.datavisualization.ch/)

[Sebastian Raschka](https://github.com/rasbt/pattern_classification)
