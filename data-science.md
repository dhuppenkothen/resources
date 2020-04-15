# Resources for Data Science

This website collects some resources for learning about data science-related topics, like data visualization, (Bayesian) statistics, machine learning, software engineering and data science ethics. It is mainly a collection of things I've seen or found useful in either my learning, teaching or research, and makes no claim to any completeness. If you have interesting and/or useful things to add, I very much welcome a [pull request](https://github.com/dhuppenkothen/resources/pulls).  

## Data Science Ethics

Any data science project (yes, even astronomy ones) should start with an assessment about whether it is ethical to do in the first place, and ethics should be a continuous part of project work. This section compiles a number of resources related to data science thics:

### Online Resources
* [A list of data science ethics syllabi](https://medium.com/@cfiesler/tech-ethics-curricula-a-collection-of-syllabi-3eedfb76be18) from various university classes taught around the world. There ought to be lots of great resources there that might be wonderful starting points for a deeper exploration
* O'Reilly has a free book called [Data Science and Ethics](https://www.oreilly.com/library/view/ethics-and-data/9781492043898/) that is short and handy as an introduction to start thinking about these issues, and comes with a checklist. 
* [Calling Bullshit](https://callingbullshit.org) is a class at UW in critical data reasoning. Materials and videos of lectures are all online, and are both highly informative and entertaining.
* The [ACM Fairness, Accountability and Transparency (ACM FAT) Conference](https://fatconference.org) happens every year and should have interesting papers on the topic
* [Data & Society](https://datasociety.net) is a think tank dedicated to exploring the societal implications of the use of data. They have some highly interesting and informative stuff.
* The [AI Now Institute](https://ainowinstitute.org) is an interdisciplinary center dedicated to exploring the social impact of Artificial Intelligence

### Books

There have been a number of books on the topic of the use and mis-use of data in recent years. Most of them focus on the ways data science can go wrong, but some offer an at least somewhat optimistic outlook. Here's an (incomplete) list:
* Meredith Broussard: [Artificial Unintelligence](https://mitpress.mit.edu/books/artificial-unintelligence)
* Cathy O'Neil: [Weapons of Math Destruction](https://weaponsofmathdestructionbook.com)
* Virginia Eubanks: [Automating Inequality](https://us.macmillan.com/books/9781250074317)
* Safiya Umoja Noble: [Algorithms of Oppression](https://nyupress.org/9781479837243/algorithms-of-oppression/)
* Marie Hicks: [Programmed Inequality](https://mitpress.mit.edu/books/programmed-inequality)


## General Data Science/Multiple Topics

Below are some resources for general data science related topics. There are a myriad of online classes and tutorials now, but these are the ones I've come across. 

### Online Classes + Tutorials

* UC Berkeley has an introductory data science class for first year undergraduates called [Data8](http://data8.org), for which all materials (including lecture videos and assignments) are online. If you're completely new to data analysis, start here.
* UC Berkeley also has somewhat more advanced follow-up data science class to Data8 called [DS100](http://www.ds100.org) for which the [textbook](https://www.textbook.ds100.org/intro) is available for free online.
* The Linux Foundation has [online classes](https://datapractices.org) related to a number of data science topics.
* [Data Carpentry](https://datacarpentry.org) is usually a two-day in-person workshop, but the materials (some specialized to different disciplines) are all (online)[https://datacarpentry.org/lessons/]
* At [Astro Hack Week](http://astrohackweek.org) we run tutorials on data science-related topics every year. Materials are available online on [GitHub](https://github.com/AstroHackWeek). For example, you can find the materials for 2019 in the [AstroHackWeek2019 repository](https://github.com/AstroHackWeek/AstroHackWeek2019). Because this is an astronomy-themed workshop, some utilize astronomy data sets.
* The [LSST Data Science Fellowship Programme](https://astrodatascience.org) is a two-year programme encompassing six summer schools on many data science related topics. Their materials, too, are all on [GitHub](https://github.com/LSSTC-DSFP/LSSTC-DSFP-Sessions).


-------

## Statistics

### Books
* Vaughan: [Scientific Inference: Learning from Data](https://www.star.le.ac.uk/sav2/stats.html) General-purpose undergraduate-level introduction to statistics (with examples in R)
* Sivia: [Data Analysis: A Bayesian Tutorial](https://global.oup.com/academic/product/data-analysis-9780198568322): This is the book that taught me Bayesian statistics. I really like it for being fairly introductory, but good at building an intuition.
* Gelman, Carlin, Stern, Dunson, Vehtari, Rubin: [Bayesian Data Analysis](http://www.stat.columbia.edu/~gelman/book/): Invaluable reference, but I don't think I would recommend astronomers to try and learn Bayesian statistics from this book. I found it incomprehensible when I started (less so after reading Sivia).

### Online Classes + Papers
* von Toussaint: [Bayesian Statistics for Physics](https://link.aps.org/doi/10.1103/RevModPhys.83.943) is an introduction into Bayesian statistics for physicists
* Hogg: [Probability Calculus for Inference](https://arxiv.org/abs/1205.4446) looks at probabilistic inference through the lens of dimensional analysis
* Hogg, Foreman-Mackey: [Using Markov Chain Monte Carlo](https://arxiv.org/abs/1710.06068) is an introductory-level paper on MCMC.


### Online Tutorials/Summer Schools
* Learn Bayesian Statistics with Legos in [this online tutorial](https://www.countbayesie.com/blog/2015/2/18/bayes-theorem-with-lego)
* Learn about Bayesian priors with Han Solo in [this online tutorial](https://www.countbayesie.com/blog/2015/2/18/hans-solo-and-bayesian-priors)
* Gwen Eadie (U Toronto) came up with a [cool class activity](https://www.tandfonline.com/doi/full/10.1080/10691898.2019.1604106) to teach Bayesian statistics with M&Ms. I wrote an accompanying set of [tutorial notes](http://dhuppenkothen.github.io/bayesian-statistics-tutorial), which are a bit messy and not in final state, but comments + corrections are welcome!

### Software Packages

-------

## Machine Learning
### Books
* James, Witten, Hastie, Tibshirani: [An Introduction to Statistical Learning](http://faculty.marshall.usc.edu/gareth-james/ISL/): I've not read this book, but it looks like a good overview of machine learning, and the PDF is available for download for free!
* Bishop: [Pattern Recognition and Machine Learning]: also an introduction into machine learning from a statistical perspective, also with a [free PDF](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf) online. I found this one hard to get into when I started reading it (the language is quite different from what I was used to), but it remains my favourite book to go back to.
* Müller: [An Introduction to Machine Learning with Python](http://shop.oreilly.com/product/0636920030515.do): This is a really good book to start out with if you're completely new to machine learning. Not a lot of maths, but a good way to build intuition. 
* Rasmussen, Williams: [Gaussian Process for Machine Learning](http://www.gaussianprocess.org/gpml/) is a book specifically on Gaussian Processes, but the PDF is available online for free.

### Online Classes
* [Applied Machine Learning](https://www.cs.columbia.edu/~amueller/comsw4995s19/) by [Andreas Müller](https://amueller.github.io) at Columbia University. Slides and videos are available online.
* Coursera has a popular undergraduate introductory course on [Machine Learning](https://www.coursera.org/learn/machine-learning). As of Dec 2019, it's possible to enrol for free (without getting a certificate, but with access to all course materials).

### Online Tutorials/Summer Schools
* [scikit-learn](https://scikit-learn.org) is a Python library for machine learning that comes with a host of really good [tutorials](https://scikit-learn.org/stable/tutorial/index.html).
* Similarly, [TensorFlow](https://www.tensorflow.org) also has a number of [tutorials](https://www.tensorflow.org/tutorials) to start out with.
* [NeurIPS](https://neurips.cc) is a major machine learning conference that runs [tutorials](https://nips.cc/Conferences/2019/Schedule?type=Tutorial) on machine learning-related topics every year. Usually the videos of those tutorials can be found on YouTube. For example, [here's a list of 2018 tutorials](https://www.youtube.com/results?search_query=neurips+2018+tutorial). These tutorials are generally 2-4 hours long, and a good way to get an introduction into some state-of-the-art methods that might not have their own textbook yet. Note: before the conference was renamed in 2018, it ran under the very unfortunate name "NIPS" (in case you want to search for older tutorials on YouTube).
* [Machine Learning for Everyone](https://vas3k.com/blog/machine_learning/): Every-day language tutorial about machine learning basics

### Software Packages
-------

### Programming (in Python)
* [Real Python](https://realpython.com): a bunch of Python tutorials
* [Project Euler](https://projecteuler.net): programming principles

-------

## Software Development

### Books

### Online Classes
* [Software Engineering for Data Scientists](http://uwseds.github.io/syllabus.html) is a graduate-level class in software engineering to help scientists get started with good software practices in their own work. Slides and videos available online.
* [Software Carpentry](https://www.software-carpentry.org) provides two-day in-person workshops on scientific software development, on topics like the Unix shell, version control with git, and programming in Python and R. Materials are available [on the website](https://software-carpentry.org/lessons/)


### Online Tutorials/Summer Schools
* NSLS-II [Scientific Python Cookie Cutter Tutorial](https://nsls-ii.github.io/scientific-python-cookiecutter/): comprehensive tutorial to building your first scientific Python package.

-------

## Data Visualization

### Books
* Tufte: [The Visual Display of Quantitative Information](https://www.edwardtufte.com/tufte/books_vdqi). Classic visualization reference.
* Ware: [Information Visualization](https://www.elsevier.com/books/information-visualization/ware/978-0-12-381464-7): in-depth textbook on perception as it relates to visualizing information. Probably too thorough and detailed if you just want to know what colour palette to use, but if you're excited to learn all the gory technical details about how screens display colour information, this is the book for you.

### Online Classes
* [Data Visualization](https://courses.cs.washington.edu/courses/cse512/16sp/) is a graduate-level UW class; slides and assignments available online, as are textbook suggestions

### Online Tutorials/Summer Schools
* I've run a number of visualization tutorials at various summer schools, so I've made a step-by-step [online version](https://huppenkothen.org/data-visualization-tutorial/) of that tutorial material. It's still a bit rough and in draft stage, so comments + fixes are welcome. :) 
* The [Data Visualization Catalogue](https://datavizcatalogue.com) is a great resources that sorts types of visualizations by function. Great if you want inspiration how to best display your data.
* The [Data Viz Project](https://datavizproject.com) does something very similar to the Data Visualization Catalogue.
* [Data-To-Viz](https://www.data-to-viz.com) is another website to help you select a type of visualization, using a decision tree to help guide you.


### Software Packages
* [matplotlib](): perhaps the most standard Python library for data visualization
* [seaborn](https://seaborn.pydata.org): built on top of matplotlib to provide higher-level functionality and make plots prettier.
* [D3.js](https://d3js.org): data visualization in JavaScript. Used by the New York Times (and others)
* [Vega](https://vega.github.io) is a visualization grammar built on top of D3.js and is somewhat easier (for me) to understand (but I also don't know JavaScript). Even that requires a lot of custom code for even simple plots, so if you don't need the flexibility, try [Vega-Lite](https://vega.github.io/vega-lite/), instead, or if you use Python try [Altair](https://altair-viz.github.io), which provides Python bindings to Vega-Lite.
* [HoloViz](https://holoviz.org) includes a collection of high-level tools for (interactive) visualization in Python.
