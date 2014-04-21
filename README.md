### Computational Social Science in Python


This is my list of Python tutorials and annoted analyses. I've tried to list the pages that are accessible to social scientists with little background in Python and/or machine learning. It emphasizes the package that I've found most useful, such as Pandas and scikit-learn learn. Many are IPython Notebooks, so they can be downloaded and run locally.


__Getting Set Up__

* [An Introduction to scikit-learn: Machine Learning in Python](http://nbviewer.ipython.org/github/jakevdp/sklearn_pycon2014/blob/master/notebooks/00_Preliminaries.ipynb) by [Jake Vanderplas](http://www.vanderplas.com/)


__Entire Analysis__
One of the great things about IPython Notebooks is that you can present code and context in the same document.

* [Diving into Open Data with IPython Notebook & Pandas](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/jvns/talks/master/pycon2014/bike_paths.ipynb?create=1) by [Julia Evans](http://twitter.com/b0rk). Do people bike when it rains using Pandas.

* [The Need for Openness in Data Journalism](http://nbviewer.ipython.org/github/brianckeegan/Bechdel/blob/master/Bechdel_test.ipynb) by [Brian Keegan](https://twitter.com/bkeegan)  Reanlysis of a 538 post on the Bechdel Test and films using Pandas and statsmodels. I had a problem with the BeautifulSoup part.

* [Predicting customer churn with scikit-learn](http://blog.yhathq.com/posts/predicting-customer-churn-with-sklearn.html) by [Eric Chiang](https://github.com/EricChiang). I don't care about customers, but it's a well written wall-through of machine learning classification.

* [538 Model](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/jseabold/538model/master/silver_model.ipynb) by [Skipper Seabold](https://twitter.com/jseabold). Recreating the classic 538 prediction model using Pandas. 

* [Heat and Violence in Chicago](http://nbviewer.ipython.org/github/brianckeegan/WeatherCrime/blob/master/Analysis.ipynb?create=1) by [Brian Keegan](https://twitter.com/bkeegan).  Walkthrough of an impressive analysis of crime trends.

__Using APIs__

* [Mining Twitter: Exploring Trending Topics, Discovering What People Are Talking About, and More](http://nbviewer.ipython.org/github/ptwobrussell/Mining-the-Social-Web-2nd-Edition/blob/master/ipynb/Chapter%201%20-%20Mining%20Twitter.ipynb) by [Matthew Russell](http://twitter.com/ptwobrussell
[http://newcoder.io/api/)
* [Sushi Bars and Buffets: Measuring local culture with the Yelp API](http://nealcaren.github.io/sushi_bars.html) by [me](https://twitter.com/haphazardsoc). Using the Yelp API to gather data about local food cultures and how they vary by SES.

__Web Scraping__

* [Web scraping in Python](http://nbviewer.ipython.org/url/www.unc.edu/%7Encaren/Lax-1.ipynb.json) by [me](https://twitter.com/haphazardsoc). Grabbing lacrosse scores and turnig them into a CSV file.

__Data Managment__

* [College Basketball three pointers](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/jgbos/IPython-Notebooks/master/3-pointers%20after%20offensive%20rebounds.ipynb?create=1) by [Justin Goodwin](https://twitter.com/jgbos).
Pandas. Uncommented.
* [Aggregating & plotting time series in python](http://blog.yhathq.com/posts/aggregating-and-plotting-time-series-in-python.html) by yhatq. Basics of managing time series data in Pandas.
* [Pandas cookbook](https://github.com/jvns/pandas-cookbook/blob/master/README.md) by [Julia Evans](https://twitter.com/b0rk). Lots of great examples for handling data in Pandas.

__Text Managment__

* [Using Pandas to Curate Data from the New York Public Library's What's On the Menu? Project](http://nbviewer.ipython.org/gist/trevormunoz/8358810) by[Trevor Muñoz](https://twitter.com/trevormunoz). People spell potatoes au gratin a lot of different ways.
* [Statistical Natural Language Processing in Python or How To Do Things With Words. And Counters. or  Everything I Needed to Know About NLP I learned From Sesame Street. Except Kneser-Ney Smoothing. The Count Didn't Cover That.](http://nbviewer.ipython.org/url/norvig.com/ipython/How%20to%20Do%20Things%20with%20Words.ipynb) by [Peter Norvig](http://norvig.com). This actually isn't that useful to social scientists, but his code is beautiful.

__Introduction to data analysis__

* [Basic principles of machine learning](http://nbviewer.ipython.org/github/jakevdp/sklearn_pycon2014/blob/master/notebooks/03_basic_principles.ipynb)  by [Jake Vanderplas](http://www.vanderplas.com/) Scikit-learn
* [Introduction to Scikit-Learn](http://nbviewer.ipython.org/github/tdhopper/Research-Triangle-Analysts--Intro-to-scikit-learn/blob/master/Intro%20to%20Scikit-Learn.ipynb) by [Tim Hopper](https://twitter.com/tdhopper).
* [Using Python to see how the Times writes about men and women](http://nbviewer.ipython.org/gist/nealcaren/5105037) by [me](https://twitter.com/haphazardsoc). Basics of counting words.

__Classification__

* [Predicting NFL Field Goal Percentages](http://nbviewer.ipython.org/github/jgbos/iPython-Notebooks/blob/master/Cold%20Weather%20FG.ipynb) by [Justin Goodwin](https://twitter.com/jgbos). Pandas and scikit-learn Random Forests Classifer.
* [Basic Random Forest Model](http://nbviewer.ipython.org/github/treycausey/thespread/blob/master/notebooks/basic_random_forest_wp_model.ipynb?create=1) by [Trey Causey](https://twitter.com/treycausey). Minimally commented but clear code for using Pandas and scikit-learn to analyze in-game NFL win probabilities.
* [Supervised Learning In-Depth: SVMs and Random Forests](http://nbviewer.ipython.org/github/jakevdp/sklearn_pycon2014/blob/master/notebooks/04_supervised_in_depth.ipynb) by [Jake Vanderplas](http://www.vanderplas.com/)

__Unsupervised Learning__

* [Topics extraction with Non-Negative Matrix Factorization](http://nbviewer.ipython.org/github/ogrisel/notebooks/blob/master/nmf_topics.ipynb?create=1) by [Oliver Grisel](https://twitter.com/ogrisel). It isn't topic models, but it's close and it's in scikit-learn.

__Regression__

* [Multiple Regression using Statsmodels](http://nbviewer.ipython.org/urls/s3.amazonaws.com/datarobotblog/notebooks/multiple_regression_in_python.ipynb) by by [DataRobot](http://www.datarobot.com/blog/). The stuff you already know how to do but this time in Python.
* [Gradient Boosted Regression Trees](http://nbviewer.ipython.org/urls/s3.amazonaws.com/datarobotblog/notebooks/gbm-tutorial.ipynb) by [DataRobot](http://www.datarobot.com/blog/). Scikit-learn analysis of a continuous outcome measure.

__Model Selection__

* [Machine Learning with Scikit-Learn: Validation and Model Selection](http://nbviewer.ipython.org/github/jakevdp/sklearn_pycon2014/blob/master/notebooks/04_validation.ipynb) by [Jake Vanderplas](http://www.vanderplas.com/). Scikit-learn
* [Testing and Validation in Scikit-Learn](http://nbviewer.ipython.org/gist/sarguido/8969894) by [Sarah Guido](https://twitter.com/sarah_guido)

__Networks__

* [Citation Network Analysis](http://nbviewer.ipython.org/github/twneale/citation-network-analysis/blob/master/Citation%20Network%20Analysis.ipynb) by [Thom Neale](https://github.com/twneale). 
* [Six Degrees of Kevin Bacon](http://graphlab.com/learn/notebooks/graph_analytics_movies.html) by Brian Kent. Using NetworkX.
* [Analysis of Twitter stream data with the IPython Notebook](http://nbviewer.ipython.org/github/ellisonbg/talk-strata2013/blob/master/TwitterNetworkX.ipynb) by [Brian Granger](https://twitter.com/ellisonbg). Words as nodes in a network analysis of Twitter data. 

__Plotting__

* [Plotting and Visualization](http://nbviewer.ipython.org/urls/gist.github.com/fonnesbeck/5850463/raw/a29d9ffb863bfab09ff6c1fc853e1d5bf69fe3e4/3.+Plotting+and+Visualization.ipynb) by [Chris Fonnesbeck](http://stronginference.com). Great overview of using matplotlib and pandas.
* [Computational data visualization in Python](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/olgabot/pycon2014_dataviz/master/pycon2014_dataviz.ipynb) by [Olga Botvinnik](https://twitter.com/olgabot).  using Seaborn to make pretty picutres from your numbers.
* [A Gallery of Statistical Graphs in Matplotlib](http://nbviewer.ipython.org/github/cs109/content/blob/master/lec_03_statistical_graphs.ipynb) by [Chris Beaumont](https://github.com/ChrisBeaumont). Pretty and practical examples.
* [Nine matplotlib figures made in Plotly](http://nbviewer.ipython.org/gist/msund/10016970). plotly. 
& [D3 in Python](http://nbviewer.ipython.org/gist/z-m-k/4484816/ipyD3sample.ipynb) by [z-m-k](https://github.com/z-m-k). Fairly complicated worked examples.
* [Vincent](http://nbviewer.ipython.org/github/wrobstory/vincent/blob/master/examples/Vincent_Examples.ipynb) by [Roby Story](https://github.com/wrobstory). Basics of plotting with 


__Images as data__

* [Image Processing with scikit-image](http://blog.yhathq.com/posts/image-processing-with-scikit-image.html) by [Eric Chiang](https://github.com/EricChiang)`
