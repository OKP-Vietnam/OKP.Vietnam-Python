<head>
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="chrome=1">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
    <link href='https://fonts.googleapis.com/css?family=Architects+Daughter' rel='stylesheet' type='text/css'>
    <link rel="stylesheet" type="text/css" href="stylesheets/stylesheet.css" media="screen" />
    <link rel="stylesheet" type="text/css" href="stylesheets/pygment_trac.css" media="screen" />
    <link rel="stylesheet" type="text/css" href="stylesheets/print.css" media="print" />

    <title>Exploratory computing with Python by Mark Bakker</title>
</head>

  <body>
    <header>
      <div class="inner">
        <h1>Exploratory computing with Python</h1>
        <h2>Mark Bakker</h2>
        <h2>Delft University of Technology</h2>
        <h2></h2>
      </div>
    </header>

# Hướng dẫn sử dụng Python
<p> 
Một sản phẩm của dự án OKP Climate Proof Vietnam, được dịch từ sản phẩm &mdash;
<a href="https://mbakker7.github.io/exploratory_computing_with_python/">Exploratory computing with Python</a>
 &mdash; của Mark Bakker, Đại học Công nghệ Delft (TU Delft), Vương Quốc Hà Lan.

<body>
<p>Lots of books are written on scientific computing, but very few deal with the much more common <em>exploratory computing</em> 
(a term coined by Fernando Perez), which represents daily tasks of many scientists and engineers that try to solve problems
but are not computer scientists.
This set of  Notebooks is written for scientists and engineers who want to use Python programming
for exploratory computing, scripting, data analysis, and visualization. 
Python makes
many of these programming tasks quick, easy, and, probably most importantly, fun.</p>

<p>No prior knowledge of computer programming is assumed. 
Each Notebook covers a specific topic and includes a number of exercises. 
The exercises should take less than 4 hours to complete for each Notebook.
Answers to the exercises are given at the end of the Notebook.
There are two versions of each Notebook: one with and one without output cells. The Notebooks without the output cells
are intended for people wanting to learn Python. Running the output
cells is part of the learning process. All Notebooks and accompanying data files may be downloaded
by clicking on the 'Download .zip file' button to the right.
Notebooks with output cells cells have the addition _sol and can be 
viewed by clicking on the links below.</p>

<p>
Notebooks can be run after you install Python and the appropriate packages.
The easiest way to do this is to install an installer that includes Python and a set of the most popular packages.
The most popular distribution is
<a href="https://www.anaconda.com/products/individual">Anaconda</a> (Mac, Windows, Linux).
All the Notebooks on this webiste were developed with Anaconda. After installing Anaconda, start the Navigator and then launch the Jupyter Notebook, which will open
the Jupyter Notebook dashboard in your webbrowser (starting in your Documents folder on Windows and your home directory on a Mac).
Use the dashboard to surf to the directory where you stored your Notebooks (you can only surf to lower directories not higher directories) and click on
the one you want to open.
</p>

<h2>Notebooks and accompanying videos</h2>

<p> 
Basics and Plotting &mdash;
<a href="http://nbviewer.ipython.org/github/mbakker7/exploratory_computing_with_python/blob/master/notebook1_basics_plotting/py_exploratory_comp_1_sol.ipynb">Notebook 1</a>
 &mdash; <a href="https://youtu.be/fnl6N_F7TvI">Video</a> 
</p>

<p>Arrays &mdash;
<a href="http://nbviewer.ipython.org/github/mbakker7/exploratory_computing_with_python/blob/master/notebook2_arrays/py_exploratory_comp_2_sol.ipynb">Notebook 2</a> 
&mdash; <a href="https://youtu.be/5RkeHZnZEnM">Video</a> 
</p>

<p>For loops and If/Else statements &mdash;
<a href="http://nbviewer.ipython.org/github/mbakker7/exploratory_computing_with_python/blob/master/notebook3_for_and_if/py_exploratory_comp_3_sol.ipynb">Notebook 3</a> 
&mdash; <a href="https://youtu.be/19gM-QEVugc">Video</a> 
</p>

<p>Functions &mdash;
<a href="http://nbviewer.ipython.org/github/mbakker7/exploratory_computing_with_python/blob/master/notebook4_functions/py_exploratory_comp_4_sol.ipynb">Notebook 4</a> 
&mdash;  <a href="https://youtu.be/ZqjYNtWanMM">Video</a>
</p>

<p>Finding the Zeros of a Function &mdash;
<a href="http://nbviewer.ipython.org/github/mbakker7/exploratory_computing_with_python/blob/master/notebook5_rootfinding/py_exploratory_comp_5_sol.ipynb">Notebook 5</a> 
</p>

<p>Systems of linear equations &mdash;
<a href="http://nbviewer.ipython.org/github/mbakker7/exploratory_computing_with_python/blob/master/notebook6_linear_systems/py_exploratory_comp_6_sol.ipynb">Notebook 6</a> 
</p>

<p>Bugs &mdash;
<a href="http://nbviewer.ipython.org/github/mbakker7/exploratory_computing_with_python/blob/master/notebook7_bugs/py_exploratory_comp_7_sol.ipynb">Notebook 7</a> 
</p>

<p>Pandas and Time Series &mdash;
<a href="http://nbviewer.ipython.org/github/mbakker7/exploratory_computing_with_python/blob/master/notebook8_pandas/py_exploratory_comp_8_sol.ipynb">Notebook 8</a>
&mdash;  <a href="https://youtu.be/MTdIY6uFY6M">Video</a>
</p>

<p>Discrete Random Variables &mdash;
<a href="http://nbviewer.ipython.org/github/mbakker7/exploratory_computing_with_python/blob/master/notebook9_discrete_random_variables/py_exploratory_comp_9_sol.ipynb">Notebook 9</a> 
&mdash;  <a href="https://youtu.be/iKBHWz-MHR8">Video</a>
</p>

<p>Continuous Random Variables &mdash;
<a href="http://nbviewer.ipython.org/github/mbakker7/exploratory_computing_with_python/blob/master/notebook10_continuous_random_variables/py_exploratory_comp_10_sol.ipynb">Notebook 10</a> 
&mdash;  <a href="https://youtu.be/ThpusgXnMGI">Video</a>
</p>

<p>Distribution of the Mean and Hypothesis Tests Theorem &mdash;
<a href="http://nbviewer.ipython.org/github/mbakker7/exploratory_computing_with_python/blob/master/notebook11_hypothesis_test/py_exploratory_comp_11_sol.ipynb">Notebook 11</a> 
&mdash;  <a href="http://youtu.be/OaD_bN3eg8o">Video (Python 2)</a>
</p>

<p>Object oriented programming &mdash;
<a href="http://nbviewer.ipython.org/github/mbakker7/exploratory_computing_with_python/blob/master/notebook12_oop/py_exploratory_comp_12_sol.ipynb">Notebook 12</a>
&mdash;  <a href="https://youtu.be/pNLAEDbK03s">Video (Python 2)</a>
</p>

<p>Regression I &mdash;
<a href="http://nbviewer.ipython.org/github/mbakker7/exploratory_computing_with_python/blob/master/notebook13_regression1/py_exploratory_comp_13_sol.ipynb">Notebook 13</a>
</p>

<p> 
Test Notebooks 1-4 &mdash;
<a href="http://nbviewer.ipython.org/github/mbakker7/exploratory_computing_with_python/blob/master/notebook1-4_test/notebook1-4_test.ipynb">Test Notebook 1-4</a>
</p>

</body>
