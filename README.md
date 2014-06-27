**Neal Caren** - University of North Carolina, Chapel Hill
[mail](mailto:neal.caren@unc.edu)
[web](http://nealcaren.web.unc.edu)
[twitter](http://twitter.com/HaphazardSoc)
[scholar](http://scholar.google.com/citations?user=cy0u16kAAAAJ&hl=en)


I’ve compiled a list of Python tutorials and annotated analyses. I've tried to list pages that are accessible to social scientists with little background in Python and/or machine learning. The list includes the packages that I've found most useful, such as Pandas and scikit-learn learn. Many are IPython Notebooks, so they can be downloaded and run locally. 

If you are totally new to Python, I would recommend installing Continuum's [Anacoda](https://store.continuum.io/cshop/anaconda/) Python distribution. It works on Macs and Windows, makes using IPython notebooks trivial, and solves most of the problems associated with installing various packages. 

If you know of anything I've left out or if links go dead, please let [me](http://twitter.com/HaphazardSoc) [know](mailto:neal.caren@unc.edu).


__Walkthroughs__

One of the great things about IPython notebooks is that they can easily blend text and code. This has led to a sharp increase in the number of data analysis projects where people carefully explain an entire research project, including data collection/importation, management and analysis. The code is right there, and you can usually run it and/or modify yourself. Looking at a few of these is an excellent introduction to what people are currently doing, even if you don't understand everything.

* [Diving into Open Data with IPython Notebook & Pandas](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/jvns/talks/master/pycon2014/bike_paths.ipynb?create=1) by [Julia Evans](http://twitter.com/b0rk). An analysis of whether people bike when it rains using Pandas.

* [The Need for Openness in Data Journalism](http://nbviewer.ipython.org/github/brianckeegan/Bechdel/blob/master/Bechdel_test.ipynb) by [Brian Keegan](https://twitter.com/bkeegan)  Reanalysis of a 538 posts on the Bechdel Test and films using Pandas and statsmodels. When I ran this one, I had an issue with the BeautifulSoup part.u

* [Predicting customer churn with scikit-learn](http://blog.yhathq.com/posts/predicting-customer-churn-with-sklearn.html) by [Eric Chiang](https://github.com/EricChiang). I don't care about customer churn, but it's a well-written walkthrough of machine learning classification.

* [538 Model](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/jseabold/538model/master/silver_model.ipynb) by [Skipper Seabold](https://twitter.com/jseabold). Recreation of the classic 538 prediction model using Pandas.

* [Heat and Violence in Chicago](http://nbviewer.ipython.org/github/brianckeegan/WeatherCrime/blob/master/Analysis.ipynb?create=1) by [Brian Keegan](https://twitter.com/bkeegan).  Walkthrough of an impressive analysis of crime trends.

* [Powerpoetry Analysis](http://nbviewer.ipython.org/github/SumAllFoundation/powerpoetry/blob/master/Powerpoetry%20Analysis.ipynb) by [SumAll Foundation](http://sumall.org). Analysis of how individual poetry styles change over time using pandas.

* [World Cup Learning](http://nbviewer.ipython.org/github/fisadev/world_cup_learning/blob/master/learn.ipynb) by [Juan Pedro Fisanotti](https://twitter.com/fisadev). Predict winners of World Cup soccer matches using the [PyBrain](http://pybrain.org/) library for machine learning. Data is also on [Github](https://github.com/fisadev/world_cup_learning). 

__Using APIs__

When a service wants you to use their data, they often provide it through an API. There are often specific Python libraries for accessing popularing, complex and/or APIs requiring authentication. Otherwises, [requests](http://docs.python-requests.org/en/latest/) is quite useful. 

* [Mining Twitter: Exploring Trending Topics, Discovering What People Are Talking About, and More](http://nbviewer.ipython.org/github/ptwobrussell/Mining-the-Social-Web-2nd-Edition/blob/master/ipynb/Chapter%201%20-%20Mining%20Twitter.ipynb) by [Matthew Russell](http://twitter.com/ptwobrussell
[http://newcoder.io/api/)
* [Sushi Bars and Buffets: Measuring local culture with the Yelp API](http://nealcaren.github.io/sushi_bars.html) by [me](https://twitter.com/haphazardsoc). Using the Yelp API to gather data about local food cultures and how they vary by SES.

__Web Scraping__

When they don't want to give you the data, you can sometimes grab it anyway by visiting one or more web pages and then extracting the parts you need. [requests](http://docs.python-requests.org/en/latest/) is a useful library for accessing web pages, and [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/bs4/doc/) is a popular choice for pulling out the good stuff. If you don't know any HTML, [regular expressions](https://docs.python.org/2/library/re.html) can sometimes work well too. 

* [Intro to Beautiful Soup](http://programminghistorian.org/lessons/intro-to-beautiful-soup) by [Jeri Wieringa](http://jerielizabeth.github.io/). Turning a table on a website into a CSV file. Part of the useful [Programming Historian](http://programminghistorian.org/) set of tutorials.
* [Web scraping in Python](http://nbviewer.ipython.org/url/www.unc.edu/%7Encaren/Lax-1.ipynb.json) by [me](https://twitter.com/haphazardsoc). Grabbing lacrosse scores and turning them into a CSV file.

__Data Management__

Going for raw data--numbers of words--to Xs that can be included in a regression equation is about 80% of the work. There's a lot of data management in the walkthroughs, but I've found a couple of others that show the process quite clearly. [Pandas](http://pandas.pydata.org/) is popular and super useful, especially the data frames.

* [Intro to pandas data structures](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/) by [Greg Reda](https://twitter.com/gjreda). A three part tutorial that is a very accessible overview to working with data using Pandas.
* [Aggregating & plotting time series in python](http://blog.yhathq.com/posts/aggregating-and-plotting-time-series-in-python.html) by yhatq. Basics of managing time series data in Pandas.
* [College Basketball three pointers](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/jgbos/IPython-Notebooks/master/3-pointers%20after%20offensive%20rebounds.ipynb?create=1) by [Justin Goodwin](https://twitter.com/jgbos).
Only lightly commented guide to analyzing basektaball stats. I'm pretty sure you can download the data yourself using the code in this [gist](https://gist.github.com/gjreda/7175267/).
* [Pandas cookbook](https://github.com/jvns/pandas-cookbook/blob/master/README.md) by [Julia Evans](https://twitter.com/b0rk). Lots of great examples for handling data in Pandas.

__Text Management__

* [Using Pandas to Curate Data from the New York Public Library's What's On the Menu? Project](http://nbviewer.ipython.org/gist/trevormunoz/8358810) by[Trevor Muñoz](https://twitter.com/trevormunoz). People spell potatoes au gratin a lot of different ways.
* [Statistical Natural Language Processing in Python or How To Do Things With Words. And Counters. or  Everything I Needed to Know About NLP I learned From Sesame Street. Except Kneser-Ney Smoothing. The Count Didn't Cover That.](http://nbviewer.ipython.org/url/norvig.com/ipython/How%20to%20Do%20Things%20with%20Words.ipynb) by [Peter Norvig](http://norvig.com). This actually isn't that useful to social scientists, but his code is beautiful.

__Introduction to data analysis__

Introductions and/or overviews of data analysis, usually using [scikit-learn](http://scikit-learn.org/stable/).

* [Basic principles of machine learning](http://nbviewer.ipython.org/github/jakevdp/sklearn_pycon2014/blob/master/notebooks/03_basic_principles.ipynb)  by [Jake Vanderplas](http://www.vanderplas.com/) An introduction to [scikit-learn](http://scikit-learn.org/stable/), the most popular machine learning library in Python. It's really great. 
* [Introduction to Scikit-Learn](http://nbviewer.ipython.org/github/tdhopper/Research-Triangle-Analysts--Intro-to-scikit-learn/blob/master/Intro%20to%20Scikit-Learn.ipynb) by [Tim Hopper](https://twitter.com/tdhopper). This introduction assumes a modest level of familiarity with Python.
* [Using Python to see how the Times writes about men and women](http://nbviewer.ipython.org/gist/nealcaren/5105037) by [me](https://twitter.com/haphazardsoc). Basics of using work counts. 

__Classification__

When the outcome variable is categorical. Social scientists usually start and stop with variations on logistic regression. Turns out, there's a lot of other things out there.

* [Predicting NFL Field Goal Percentages](http://nbviewer.ipython.org/github/jgbos/iPython-Notebooks/blob/master/Cold%20Weather%20FG.ipynb) by [Justin Goodwin](https://twitter.com/jgbos). Using Pandas and the scikit-learn Random Forests classifier.
* [Basic Random Forest Model](http://nbviewer.ipython.org/github/treycausey/thespread/blob/master/notebooks/basic_random_forest_wp_model.ipynb?create=1) by [Trey Causey](https://twitter.com/treycausey). Minimally commented but clear code for using Pandas and scikit-learn to analyze in-game NFL win probabilities.
* [Supervised Learning In-Depth: SVMs and Random Forests](http://nbviewer.ipython.org/github/jakevdp/sklearn_pycon2014/blob/master/notebooks/04_supervised_in_depth.ipynb) by [Jake Vanderplas](http://www.vanderplas.com/)

__Unsupervised Learning__

When you don't have an outcome variable and/or want to combine your explanatory variables. Sociologists usually learn about factor analysis and then never use it.

* [Unsupervised Learning In-depth: PCA and K-Means](http://nbviewer.ipython.org/github/jakevdp/sklearn_pycon2014/blob/master/notebooks/05_unsupervised_in_depth.ipynb) by [Jake Vanderplas](http://www.vanderplas.com/). 
* [Topics extraction with Non-Negative Matrix Factorization](http://nbviewer.ipython.org/github/ogrisel/notebooks/blob/master/nmf_topics.ipynb?create=1) by [Oliver Grisel](https://twitter.com/ogrisel). It isn't topic models, but it's close and it's in scikit-learn.

__Regression__

While continuous outcomes are common in the social sciences, machine learning folks rarely talk about them. 

* [Multiple Regression using Statsmodels](http://nbviewer.ipython.org/urls/s3.amazonaws.com/datarobotblog/notebooks/multiple_regression_in_python.ipynb) by by [DataRobot](http://www.datarobot.com/blog/). The stuff you already know how to do but this time in Python.
* [Gradient Boosted Regression Trees](http://nbviewer.ipython.org/urls/s3.amazonaws.com/datarobotblog/notebooks/gbm-tutorial.ipynb) by [DataRobot](http://www.datarobot.com/blog/). Scikit-learn analysis of a continuous outcome measure.

__Model/Feature Selection__

Picking which model or variables to use often happens offstage in social science research. It doesn't have to be that way, though.

* [Machine Learning with Scikit-Learn: Validation and Model Selection](http://nbviewer.ipython.org/github/jakevdp/sklearn_pycon2014/blob/master/notebooks/06_validation.ipynb) by [Jake Vanderplas](http://www.vanderplas.com/). Evaluating and improving your scikit-learn models. 
* [Testing and Validation in Scikit-Learn](http://nbviewer.ipython.org/gist/sarguido/8969894) by [Sarah Guido](https://twitter.com/sarah_guido). Short and to the point.
* [Feature](http://nbviewer.ipython.org/github/treycausey/thespread/blob/master/notebooks/feature_selection.ipynb?create=1) by [Trey Causey](https://twitter.com/treycausey). Minimally commented but clear code for using Pandas and scikit-learn to find most important features.

__Networks__

[NetworkX](http://networkx.github.io) and [igraph](http://igraph.sourceforge.net) are both fairly powerful tools for network analysis. I don't think you can use them for regression analysis, but  you can use them to do things like compute centrality measures and make pretty pictures. You can also use Python to create/manipulate your network data for analysis/display elsewhere.   

* [Six Degrees of Kevin Bacon](http://graphlab.com/learn/notebooks/graph_analytics_movies.html) by Brian Kent. A classic example of network analysis using NetworkX. 
* [Building a Foursquare Location Graph](http://nbviewer.ipython.org/github/furukama/IPythonNotebooks/blob/master/Building%20a%20Foursquare%20Location%20Graph.ipynb) by [Benedikt Koehler](https://twitter.com/furukama). Using the FourSquare API to find related venues and then graph them as a network using NetworkX.
* [Analysis of Twitter stream data with the IPython Notebook](http://nbviewer.ipython.org/github/ellisonbg/talk-strata2013/blob/master/TwitterNetworkX.ipynb) by [Brian Granger](https://twitter.com/ellisonbg). Words as nodes in a network analysis of Twitter data. 


__Plotting__

[matplotlib](http://matplotlib.org) is the default plotting library for data scientists and plays well with pandas. [seaborn](http://www.stanford.edu/~mwaskom/software/seaborn/) makes it prettier. Other programs, like [mpld3](http://mpld3.github.io), [Plotly](https://plot.ly), or [bokeh](http://bokeh.pydata.org) are also worth trying out, especially for putting stuff together on the web.

* [Plotting and Visualization](http://nbviewer.ipython.org/urls/gist.github.com/fonnesbeck/5850463/raw/a29d9ffb863bfab09ff6c1fc853e1d5bf69fe3e4/3.+Plotting+and+Visualization.ipynb) by [Chris Fonnesbeck](http://stronginference.com). Great overview of using matplotlib and pandas.
* [Exploratory graphs](http://nbviewer.ipython.org/github/herrfz/dataanalysis/blob/master/week3/exploratory_graphs.ipynb) by [herrfz](https://github.com/herrfz) Basic Pandas plots. 
* [Computational data visualization in Python](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/olgabot/pycon2014_dataviz/master/pycon2014_dataviz.ipynb) by [Olga Botvinnik](https://twitter.com/olgabot).  Using Seaborn to make pretty graphs from your numbers.
* [A Gallery of Statistical Graphs in Matplotlib](http://nbviewer.ipython.org/github/cs109/content/blob/master/lec_03_statistical_graphs.ipynb) by [Chris Beaumont](https://github.com/ChrisBeaumont). Pretty and practical examples.
* [Demo of mpld3](http://nbviewer.ipython.org/url/mpld3.github.io/_downloads/mpld3_demo.ipynb) by [Jake Vanderplas](http://www.vanderplas.com/). Interested in making interactive graphics? This is where I would start. Turns your  matplotlib code into d3 figures.
* [Nine matplotlib figures made in Plotly](http://nbviewer.ipython.org/gist/msund/10016970). Plotly makes excellent interactive graphs which are hosted on their servers.  
& [D3 in Python](http://nbviewer.ipython.org/gist/z-m-k/4484816/ipyD3sample.ipynb) by [z-m-k](https://github.com/z-m-k). Fairly complicated worked examples of an alternate way of producing D3 graphs.


__Images as data__

The great frontier for social scientists. 

* [Image Processing with scikit-image](http://blog.yhathq.com/posts/image-processing-with-scikit-image.html) by [Eric Chiang](https://github.com/EricChiang)
