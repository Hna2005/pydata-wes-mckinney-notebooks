# 🐍 Python for Data Analysis - My Notes

> Personal notes and Jupyter notebooks while studying **Python for Data Analysis** by Wes McKinney.

## 📖 About

This repository contains my notes, code examples, and experiments while working through:

**Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython**
Wes McKinney, 3rd Edition, O'Reilly

I am using the book as the main reference, but I don't just copy the examples into a notebook. I usually write the code myself, run it, change it, and add small examples when I need to understand something better.

So this repository is more like my study notebook than a collection of finished projects.

## 📚 Topics

The notebooks currently cover the following parts of the book:

| Folder                            | Topics                                                                                |
| --------------------------------- | ------------------------------------------------------------------------------------- |
| `02-ipython`                      | IPython, magic commands, introspection, debugging, timing, keyboard shortcuts         |
| `03-data-structures`              | Lists, tuples, dictionaries, sets, functions, files, mutable and immutable objects    |
| `04-numpy`                        | NumPy arrays, array operations, universal functions, file input                       |
| `05-pandas`                       | Series, DataFrames, indexing, selection, filtering, functions, descriptive statistics |
| `06-data-loading-and-file-format` | Reading and writing data, CSV, JSON, Excel, XML, HTML, text files                     |
| `07-data-cleaning`                | Missing data, data types, transformations, and basic data cleaning                    |

## 📁 Repository Structure

```text
pydata-wes-mckinney-notebooks/
│
├── 02-ipython/
│   ├── images/
│   └── ipython-and-python.ipynb
│
├── 03-data-structures/
│   ├── 01-tuple-and-list.ipynb
│   ├── 02-dictionaries-and-set.ipynb
│   ├── 03-functions-and-files.ipynb
│   └── examples/
│
├── 04-numpy/
│   ├── 01-numpy-basics.ipynb
│   ├── 02-universal-functions.ipynb
│   └── 03-file-input.ipynb
│
├── 05-pandas/
│   ├── 01-baisic-pandas-essential-functions.ipynb
│   └── 02-function-and-statistic.ipynb
│
├── 06-data-loading-and-file-format/
│   ├── 01-reading-and-writing-data.ipynb
│   └── examples/
│
├── 07-data-cleaning/
│   ├── 01-missing-and-teransformation.ipynb
│   └── data/
│
├── requirements.txt
└── README.md
```

## 🔍 A Closer Look

### `02-ipython`

The first notebook is mostly about getting comfortable with IPython and using it as a working environment.

Some of the things covered here are:

* Starting and using IPython
* `?` and `??` for inspecting objects
* Wildcard searches
* `%run` and `%run -i`
* `%load`
* `%debug`
* `%time` and `%timeit`
* `%paste` and `%cpaste`
* Command history
* Useful keyboard shortcuts
* IPython magic commands

There are also notes and examples about Python itself, including copying objects, mutability, object identity, string formatting, and working with dates and times.

### `03-data-structures`

This section is split into three notebooks:

* Tuples and Lists
* Dictionaries and Sets
* Functions and Files

I also keep a few small text files in the `examples` folder because some of the examples in this part of the book work with files.

### `04-numpy`

The NumPy section currently contains three notebooks:

* NumPy basics
* Universal functions
* File input

The notebooks include examples with arrays, array operations, data types, vectorized operations, and reading data from files.

### `05-pandas`

This is where the repository starts moving more directly into data analysis.

The current notebooks cover things such as:

* `Series` and `DataFrame`
* Indexing and selection
* Filtering
* Reindexing
* Basic DataFrame operations
* Applying functions
* Sorting
* Descriptive statistics
* Working with unique values and value counts

This section will grow as I continue through the pandas chapters of the book.

### `06-data-loading-and-file-format`

This section is about getting data into Python and writing it back to files.

The examples include different formats such as:

* CSV
* JSON
* Excel
* XML
* HTML
* TXT

There is also an `examples` folder containing the small files used in the notebooks.

### `07-data-cleaning`

The current notebook focuses on missing data and data transformation.

This section also contains a small `movie.csv` dataset that I use while working through the examples.

## 🛠️ Tools

The main tools used in these notebooks are:

* Python
* Jupyter Notebook
* IPython
* NumPy
* Pandas
## 📦 Installation

Install the required packages with:

```bash
pip install -r requirements.txt
```

## 🎯 Why I Keep This Repository

I made this repository mainly for myself.

When I finish a chapter, I want to have something I can open later instead of going back through the whole book to find one small thing I forgot.

Writing the examples myself also helps me notice the parts I don't understand yet. Some notebooks are more detailed than others for this reason.

This repository is also a record of what I have studied so far.

## 📌 Current Progress

* [x] Chapter 2 — Python Language Basics, IPython, and Jupyter Notebooks
* [x] Chapter 3 — Built-In Data Structures, Functions, and Files
* [x] Chapter 4 — NumPy Basics
* [x] Chapter 5 — Getting Started with pandas
* [x] Chapter 6 — Data Loading, Storage, and File Formats
* [x] Chapter 7 — Data Cleaning and Preparation

The notebooks for the following chapters have not been added yet.

## 📖 Book

**Python for Data Analysis, 3rd Edition**

Wes McKinney

O'Reilly Media, 2022

- [Book / Open Edition](https://wesmckinney.com/book/)
- [O'Reilly](https://www.oreilly.com/library/view/python-for-data/9781098104030/)
- [Wes McKinney](https://wesmckinney.com/)
- [Wes McKinney on GitHub](https://github.com/wesm)
- [Official book repository](https://github.com/wesm/pydata-book)

## ⚠️ Note

This repository contains my personal study notes and code written while reading the book.

It is not intended to replace the book. The explanations are written from my own understanding, and some examples have been changed or added while studying.

The book and its original material belong to Wes McKinney and O'Reilly Media.

For the original book materials and the author's notebooks,

 see [Wes McKinney's official repository](https://github.com/wesm/pydata-book).
