# Class-project-for-NLP-ZLA-Test

## Introduction
This is a class project for 24 Spring NLP course in UPF.<br>
Zipf’s Law of Abbreviation (ZLA) refers to a linguistic law that more frequently a word is used, shorter the word will be. <br>
This project is going to test whether English and Chinese news reports conform to this law.


## Instructions
To implement this work, you need to download and install Anaconda3. Here is the official link for Anaconda: [https://www.anaconda.com/products/individual-d](https://www.anaconda.com/download) <br>
After installing Anaconda3, please execute the following command block in the terminal. <br>

```Bash
# create a conda environment
conda create -n zla_test python=3.11 ipython
conda activate zla_test

# install libraries for tokenization
pip install spacy==3.7.2
python -m spacy download en_core_web_sm
pip install jieba==0.42.1

# install libraries for data processing
pip install beautifulsoup4==4.12.2
pip install matplotlib==3.8.1
pip install pandas==2.1.1
pip install seaborn==0.13.2
pip install numpy==1.24.4
pip install scipy==1.11.3
```

