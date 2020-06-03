# Prerequisites for the Text Mining course

### Prior Knowledge

This course is aimed at participants without any prior experience with text analysis of data sets.  You will benefit from knowing how to start a terminal on your computer, how to run commands on it and how to do basic coding in the programming language python but we will go over each step required in the course for anyone with no previous knowledge of these things.

### Terminal Setup
__Linux:__ Look for Terminal in your applications and click on it to open it.  
__macOS:__ Bash is the default shell in all versions of macOS, you do not need to install anything. Open the Terminal application from ``/Applications/Utilities`` or using Spotlight search.  
__Windows:__ Open the Start Menu, type ```command``` or ```cmd``` in the search field, and then press Enter or click on the Command Prompt shortcut.

### Software Installs for Day 1

For this course, we ask you to install Miniconda and as well as the a series of software packages with it (jupyter notebook, nltk, numpy, matplotlib, wordcloud, pandas and networkx).  We also ask you to install the Stanford NER tagger (which is needed for day 2 of the course).  See instructions below.  Please take time to install these different things prior to the course.

__1. Install Miniconda__

Got to https://docs.conda.io/en/latest/miniconda.html and download the correct version.  We will be working with Python version 3.7, so you need to select the appropriate version of Miniconda for your operating system with Python 3.7.

For all of the software packages to be installed next (using conda) you will need to proceed through the terminal installation by pressing "y" when prompted on Linux/Mac or install them via the Anaconda prompt on Windows.

__2. Install Jupyter Notebook__

Windows: install jupyter notebook via the Anaconda prompt  
macOS/Linux: go to a terminal window and run the following command:


```python
conda install -c anaconda jupyter
```

__3. Install NLTK__

Windows: install NLTK via the Anaconda prompt  
macOS/Linux: run the following command in your terminal:


```python
conda install -c anaconda nltk
```

__4. Install numpy__

Windows: install numpy via the Anaconda prompt  
macOS/Linux: run the following command in your terminal:


```python
conda install numpy
```

__5. Install matplotlib__

Windows: install matplotlib via the Anaconda prompt  
macOS/Linux: run the following command in your terminal


```python
conda install -c conda-forge matplotlib 
```

__6. Install wordcloud__

Windows: install wordcloud via the Anaconda prompt  
macOS/Linux: run the following command in your terminal:


```python
conda install -c conda-forge wordcloud 
```

### Software Installs for Day 2

__7. Installing the spaCy and dowloading a model__

Windows: install spacy via the Anaconda prompt  
macOS/Linux: run the following command in your terminal:


```python
conda install -c conda-forge spacy
```

Download a spacy model in your terminal:


```python
python -m spacy download en_core_web_sm
```

__8. Install pandas__

Windows: install pandas via the Anaconda prompt  
macOS/Linux: run the following command in your terminal:


```python
conda install pandas
```

__9. Install networkx__

Windows: install networkx via the Anaconda prompt  
macOS/Linux: run the following command in your terminal:


```python
conda install networkx
```

[Next: Text Mining - Day 1](http://htmlpreview.github.io/?https://github.com/bea-alex/text-mining-course/blob/master/text-mining-day1.html)
