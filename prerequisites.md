# Prerequisites for the Text Mining course

## Prerequisites for Day 1

__1. Install Miniconda__

Got to https://docs.conda.io/en/latest/miniconda.html and download the correct version.  We will be working with Python version 3.7, so you need to select the appropriate version of Miniconda for your operating system with Python 3.7.

__2. Install Jupyter Notebook__

If you're on Windows, install jupyter notebook via the Anaconda prompt. If you're on Mac/Linux, go to a termninal window and run the following command:


```python
conda install -c anaconda jupyter 
```

    Collecting package metadata (current_repodata.json): done
    Solving environment: done
    
    ## Package Plan ##
    
      environment location: /Users/balex/anaconda3
    
      added / updated specs:
        - jupyter
    
    
    The following packages will be downloaded:
    
        package                    |            build
        ---------------------------|-----------------
        ca-certificates-2019.10.16 |                0         131 KB  anaconda
        certifi-2019.9.11          |           py37_0         154 KB  anaconda
        conda-4.7.12               |           py37_0         3.0 MB  anaconda
        jupyter-1.0.0              |           py37_7           6 KB  anaconda
        openssl-1.1.1              |       h1de35cc_0         4.6 MB  anaconda
        ------------------------------------------------------------
                                               Total:         7.9 MB
    
    The following packages will be UPDATED:
    
      ca-certificates    conda-forge::ca-certificates-2019.9.1~ --> anaconda::ca-certificates-2019.10.16-0
      openssl            conda-forge::openssl-1.1.1c-h01d97ff_0 --> anaconda::openssl-1.1.1-h1de35cc_0
    
    The following packages will be SUPERSEDED by a higher-priority channel:
    
      certifi                                       conda-forge --> anaconda
      conda                                         conda-forge --> anaconda
      jupyter                                         pkgs/main --> anaconda
    
    
    
    Downloading and Extracting Packages
    certifi-2019.9.11    | 154 KB    | ##################################### | 100% 
    ca-certificates-2019 | 131 KB    | ##################################### | 100% 
    jupyter-1.0.0        | 6 KB      | ##################################### | 100% 
    openssl-1.1.1        | 4.6 MB    | ##################################### | 100% 
    conda-4.7.12         | 3.0 MB    | ##################################### | 100% 
    Preparing transaction: done
    Verifying transaction: done
    Executing transaction: done
    
    Note: you may need to restart the kernel to use updated packages.


__3. Install NLTK__

If you're on Windows, install nltk via the Anaconda prompt. If you're on Mac/Linux, run the following command in your terminal:


```python
conda install -c anaconda nltk
```

    Collecting package metadata (current_repodata.json): done
    Solving environment: done
    
    ## Package Plan ##
    
      environment location: /Users/balex/anaconda3
    
      added / updated specs:
        - nltk
    
    
    The following packages will be downloaded:
    
        package                    |            build
        ---------------------------|-----------------
        nltk-3.4.5                 |           py37_0         2.1 MB  anaconda
        ------------------------------------------------------------
                                               Total:         2.1 MB
    
    The following packages will be SUPERSEDED by a higher-priority channel:
    
      nltk                                            pkgs/main --> anaconda
    
    
    
    Downloading and Extracting Packages
    nltk-3.4.5           | 2.1 MB    | ##################################### | 100% 
    Preparing transaction: done
    Verifying transaction: done
    Executing transaction: done
    
    Note: you may need to restart the kernel to use updated packages.


__4. Install numpy__

If you're on Windows, install numpy via the Anaconda prompt. If you're on Mac/Linux, run the following command in your terminal:


```python
conda install numpy
```

    Collecting package metadata (current_repodata.json): done
    Solving environment: done
    
    ## Package Plan ##
    
      environment location: /Users/balex/anaconda3
    
      added / updated specs:
        - numpy
    
    
    The following packages will be downloaded:
    
        package                    |            build
        ---------------------------|-----------------
        ca-certificates-2019.10.16 |                0         131 KB
        certifi-2019.9.11          |           py37_0         154 KB
        conda-4.7.12               |           py37_0         3.0 MB
        openssl-1.1.1d             |       h1de35cc_3         3.4 MB
        ------------------------------------------------------------
                                               Total:         6.7 MB
    
    The following packages will be SUPERSEDED by a higher-priority channel:
    
      ca-certificates                                  anaconda --> pkgs/main
      certifi                                          anaconda --> pkgs/main
      conda                                            anaconda --> pkgs/main
      openssl                anaconda::openssl-1.1.1-h1de35cc_0 --> pkgs/main::openssl-1.1.1d-h1de35cc_3
    
    
    
    Downloading and Extracting Packages
    conda-4.7.12         | 3.0 MB    | ##################################### | 100% 
    certifi-2019.9.11    | 154 KB    | ##################################### | 100% 
    ca-certificates-2019 | 131 KB    | ##################################### | 100% 
    openssl-1.1.1d       | 3.4 MB    | ##################################### | 100% 
    Preparing transaction: done
    Verifying transaction: done
    Executing transaction: done
    
    Note: you may need to restart the kernel to use updated packages.


__5. Install matplotlib__

If you're on Windows, install matplotlib via the Anaconda prompt. If you're on Mac/Linux, run the following command in your terminal:


```python
conda install -c conda-forge matplotlib 
```

    Collecting package metadata (current_repodata.json): done
    Solving environment: done
    
    ## Package Plan ##
    
      environment location: /Users/balex/anaconda3
    
      added / updated specs:
        - matplotlib
    
    
    The following packages will be downloaded:
    
        package                    |            build
        ---------------------------|-----------------
        certifi-2019.9.11          |           py37_0         147 KB  conda-forge
        conda-4.7.12               |           py37_0         3.0 MB  conda-forge
        matplotlib-3.1.1           |           py37_1           6 KB  conda-forge
        matplotlib-base-3.1.1      |   py37h3a684a6_1         6.6 MB  conda-forge
        ------------------------------------------------------------
                                               Total:         9.8 MB
    
    The following NEW packages will be INSTALLED:
    
      matplotlib-base    conda-forge/osx-64::matplotlib-base-3.1.1-py37h3a684a6_1
    
    The following packages will be UPDATED:
    
      matplotlib         pkgs/main::matplotlib-3.1.1-py37h54f8~ --> conda-forge::matplotlib-3.1.1-py37_1
    
    The following packages will be SUPERSEDED by a higher-priority channel:
    
      ca-certificates    pkgs/main::ca-certificates-2019.10.16~ --> conda-forge::ca-certificates-2019.9.11-hecc5488_0
      certifi                                         pkgs/main --> conda-forge
      conda                                           pkgs/main --> conda-forge
      openssl              pkgs/main::openssl-1.1.1d-h1de35cc_3 --> conda-forge::openssl-1.1.1c-h01d97ff_0
    
    
    
    Downloading and Extracting Packages
    matplotlib-3.1.1     | 6 KB      | ##################################### | 100% 
    conda-4.7.12         | 3.0 MB    | ##################################### | 100% 
    certifi-2019.9.11    | 147 KB    | ##################################### | 100% 
    matplotlib-base-3.1. | 6.6 MB    | ##################################### | 100% 
    Preparing transaction: done
    Verifying transaction: done
    Executing transaction: done
    
    Note: you may need to restart the kernel to use updated packages.


__6. Install wordcloud__

If you're on Windows, install wordcloud via the Anaconda prompt. If you're on Mac/Linux, run the following command in your terminal:


```python
conda install -c conda-forge wordcloud 
```

    Collecting package metadata (current_repodata.json): done
    Solving environment: done
    
    # All requested packages already installed.
    
    
    Note: you may need to restart the kernel to use updated packages.


## Prerequisites for Day 2

__7. Install Stanford NER tagger__

Go to the following URL and if you computer doesn't automatically download it, then download it yourself. 

https://nlp.stanford.edu/software/stanford-ner-2018-10-16.zip

You can put the tagger anywhere you like.  For this workshop we recommend you put it into your Download folder.  The directory path to the Standford tagger is needed to be able to run some of the excersises on day 2.

__8. Install pandas__

If you're on Windows, install pandas via the Anaconda prompt. If you're on Mac/Linux, run the following command in your terminal:


```python
conda install pandas
```

    Collecting package metadata (current_repodata.json): done
    Solving environment: done
    
    ## Package Plan ##
    
      environment location: /Users/balex/anaconda3
    
      added / updated specs:
        - pandas
    
    
    The following packages will be downloaded:
    
        package                    |            build
        ---------------------------|-----------------
        certifi-2019.9.11          |           py37_0         154 KB
        conda-4.7.12               |           py37_0         3.0 MB
        pandas-0.25.2              |   py37h0a44026_0        10.2 MB
        ------------------------------------------------------------
                                               Total:        13.4 MB
    
    The following packages will be UPDATED:
    
      ca-certificates    conda-forge::ca-certificates-2019.9.1~ --> pkgs/main::ca-certificates-2019.10.16-0
      openssl            conda-forge::openssl-1.1.1c-h01d97ff_0 --> pkgs/main::openssl-1.1.1d-h1de35cc_3
      pandas                              0.25.1-py37h0a44026_0 --> 0.25.2-py37h0a44026_0
    
    The following packages will be SUPERSEDED by a higher-priority channel:
    
      certifi                                       conda-forge --> pkgs/main
      conda                                         conda-forge --> pkgs/main
    
    
    
    Downloading and Extracting Packages
    certifi-2019.9.11    | 154 KB    | ##################################### | 100% 
    conda-4.7.12         | 3.0 MB    | ##################################### | 100% 
    pandas-0.25.2        | 10.2 MB   | ##################################### | 100% 
    Preparing transaction: done
    Verifying transaction: done
    Executing transaction: done
    
    Note: you may need to restart the kernel to use updated packages.


__9. Install networkx__

If you're on Windows, install networkx via the Anaconda prompt. If you're on Mac/Linux, run the following command in your terminal:


```python
conda install networkx
```

    Collecting package metadata (current_repodata.json): done
    Solving environment: done
    
    ## Package Plan ##
    
      environment location: /Users/balex/anaconda3
    
      added / updated specs:
        - networkx
    
    
    The following packages will be downloaded:
    
        package                    |            build
        ---------------------------|-----------------
        networkx-2.4               |             py_0         1.2 MB
        ------------------------------------------------------------
                                               Total:         1.2 MB
    
    The following packages will be UPDATED:
    
      networkx                                         2.3-py_0 --> 2.4-py_0
    
    
    
    Downloading and Extracting Packages
    networkx-2.4         | 1.2 MB    | ##################################### | 100% 
    Preparing transaction: done
    Verifying transaction: done
    Executing transaction: done
    
    Note: you may need to restart the kernel to use updated packages.


[Next: Text Mining - Day 1](http://htmlpreview.github.io/?https://github.com/bea-alex/text-mining-course/blob/master/text-mining-day1.html)
