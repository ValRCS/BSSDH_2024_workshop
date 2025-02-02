# BSSDH_2024_workshop

BSSDH 2024 workshop on Intermediate Python techniques for text content analysis

## Program 

* https://www.digitalhumanities.lv/bssdh/2024/lectures-and-workshops/

## Prerequisites

Participants should have basic knowledge of Python.
Recommended experience includes primitive data types, conditionals, iteration, lists, tuples, dictionaries and sets.

Helpful but not required experience: Jupyter Notebooks including Google Colab.

### Hardware/Software requirements in the order of preference

1. Easiest - Any computer with a modern browser and the ability to connect to Google Colab (requires google account - gmail)
2. **Visual Studio Code with Python extension, Python itself and installed git** - Preferred but not required(used by Instructor) [Local Install Instructions](https://github.com/ValRCS/BSSDH_2024_workshop/blob/main/INSTALL.md)
3. PyCharm (includes Python and git support)
4. Your own custom Jupyter Notebooks setup with Python

### Test minimal prerequisites

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ValRCS/BSSDH_2024_workshop/blob/main/notebooks/test_python_setup.ipynb)

If you can run the above Notebook in an environment of your choice (Google Colab, or locally) with no errors - you are ready for the workshop!

### Practice Your Python Notebook skills (includes NumPy and Pandas library refresher)

Here is a Python syntax refresher, optional if you have good working knowledge of Python.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ValRCS/BSSDH_2024_workshop/blob/main/notebooks/python_refresher.ipynb)



### Setup

OPTIONAL: If you want to install this project locally on your computer - [Local Install Instructions](https://github.com/ValRCS/BSSDH_2024_workshop/blob/main/INSTALL.md)

## Day 1  - 23.07.2024

On the first day, participants will be introduced to the fundamentals of text content analysis, focusing on techniques to preprocess and analyze textual data. The session will cover text cleaning, tokenization, stemming, and lemmatization using libraries such as Gensim and Pandas. Attendees will learn how to convert raw text into structured data, suitable for further analysis. The day will conclude with an introduction to text feature extraction methods, including Bag-of-Words (BoW) and Term Frequency-Inverse Document Frequency (TF-IDF), to prepare participants for Day 2's machine learning applications.

Use the links below if you did not perform a local installation of Python and/or did not clone this repository to your computer

### Part 1 - Collecting Data

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ValRCS/BSSDH_2024_workshop/blob/main/notebooks/day1_part1.ipynb)

### Part 2 - Preprocessing, processing data

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ValRCS/BSSDH_2024_workshop/blob/main/notebooks/day1_part2_processing.ipynb)

### Part 3 - Creating Embeddings

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ValRCS/BSSDH_2024_workshop/blob/main/notebooks/day1_part3_embeddings.ipynb)

## Day 2 - 24.07.2024

Building on Day 1's foundation, the second day will delve into advanced discourse analysis techniques and machine learning applications, utilizing Scikit-learn and Gensim. Participants will explore various algorithms for topic modeling, such as Latent Dirichlet Allocation (LDA), and sentiment analysis, including Naïve Bayes and Support Vector Machines (SVM). Attendees will learn how to evaluate and fine-tune their models for optimal performance. The workshop will culminate in creating interactive visualizations using the Plotly library, empowering participants to effectively communicate their findings and insights to a broader audience.

Use the links below if you did not perform a local installation of Python and/or did not clone this repository to your computer

### Part 4 (Day 2 Part 1) - modeling

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ValRCS/BSSDH_2024_workshop/blob/main/notebooks/day2_part1_modeling.ipynb)

### Part 5 (Day 2 Part 2) - Visualizating results

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ValRCS/BSSDH_2024_workshop/blob/main/notebooks/day2_part2_visualizing_results.ipynb)

### Part 6 (Day 3 Part 3) - Student Work in class

This is your chance to shine! Using the provided notebook below add your own code using your own data sources.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ValRCS/BSSDH_2024_workshop/blob/main/notebooks/day2_part3_student_work.ipynb)



### Practice with virtual environments - venv

**KEY idea** - Python virtual environments are light virtualization within OS - basically folders and symlinks (contrast with containerization using Docker and heavy virtualization with VirtualBox. VMware)
* https://docs.python.org/3/library/venv.html
* https://code.visualstudio.com/docs/python/environments
* Other IDEs such as PyCharm also offer virtual environment creation

* ### Installing libraries
* Installing external libraries on Colab
* Installing external libraries locally
* 
### Text Cleaning Techniques

### Normalization
* changing case
* removing symbols, accents
* Unicode normalization - https://unicode.org/reports/tr15/#Norm_Forms

## Pre-tokenization

### Tokenization
* whitespace
* word level
* sentence level
* BPE - byte pair level encoding - see https://huggingface.co/learn/nlp-course/chapter6/5?fw=pt
* Wordpiece tokenization - by Google similar to BPE

### Stemming vs Lemmatization

* https://nlp.stanford.edu/IR-book/html/htmledition/stemming-and-lemmatization-1.html
* Caring -> car?!

### Stemming


### Lemmatization
* nltk
* Spacy
* Latvian language service and other

### Stopwords


### Gensim

### Bag of Words

### TF-IDF

* Scikit-Learn



### Topic modeling with - LDA - Latent Dirichlet Allocation

* history of LDA
* running LDA using gensim
* pyLDAvis

### Sentiment Analysis
* heuristic based sentiment analysis
* ml-based sentiment analysis

### Fine-Tuning

### Plotly Visualization

### Assignment

Students will start with a raw corpus file that they will have to clean, pre-process, analyze and provide some results including visualization.
