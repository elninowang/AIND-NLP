# AIND: Natural Language Processing 自然语言处理

Coding exercises for the Natural Language Processing concentration, part of Udacity's Artificial Intelligence Nanodegree program.

自然语言处理浓度的编码练习，是Udacity人工智能纳米程序的一部分。

## Setup 设置

You need Python 3.6+, and the packages mentioned in `requirements.txt`. You can install them using:

你需要Python 3.6+以及 `requirements.txt` 中提到的包。 您可以使用以下方式安装

```bash
pip install -r requirements.txt
```

## Data 数据

Data files for exercises are included under `data/`, but some of the NLP libraries require additional data for performing tasks like 
PoS tagging, lemmatization, etc. Specifically, `nltk` will throw an error if the required data is not installed. You can use the 
following Python statement to open the NLTK downloader and select the desired package(s) to install:

练习的数据文件包含在 `data/` 下，但是一些NLP库需要额外的数据来执行PoS标记，引用等等。特别的是，如果没有安装所需的数据，`nltk` 会抛出错误。 您可以使用以下Python语句打开NLTK下载器并选择要安装的所需软件包：

```python
nltk.download()
```

You can also download all available NLTK data packages, which includes a number of sample corpora as well, but that may take a while 
(10+GB).

您可以下载所有可用的NLTK数据包，其中包括许多示例语料库，但可能需要一段时间 (10+GB)。

## Run 运行

To run any script file, use: 

运行任何脚本，使用:

```bash
python <script.py>
```

To open a notebook, use:

打开笔记本，使用:

```bash
jupyter notebook <notebook.ipynb>
```

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>. Please refer to [Udacity Terms of Service](https://www.udacity.com/legal) for further information.
