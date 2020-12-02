# The Human Body

The website is a result of the analysis made from [this Python notebook](link).

## Introduction

### What is this project?

The idea comes from an interest in the human body and mankinds knowledge of this subject. Wikipedia is a free webpage for learning about many subjects, and an incredible amount of unique pages about anatomy exist within. Using Wikipedia API, these pages can be extracted and analysed by creating networks, and examining the written text.

This project is all about the human body. Can we see how the internal body interacts within and out of systems by creating a network? Can we quickly learn about our anatomy without spending hours to read long, scientific pages? Does Wikipedia's information about anatomy reflect an actual anatomy textbook?

### What is the data?

A data file was manually created, containing the unique names of internal body parts and the systems that they belong to using a [Wikipedia page](https://en.wikipedia.org/wiki/List_of_organs_of_the_human_body) for inspiration.

The resulting .csv data-file can be found [here](link).

Additionaly, a cleaned version of the chapters of "Gray's Anatomy (41st edition)" (2015) is used for comparing the Wikipedia text to one of the biggest collections of knowledge of the human anatomy.

### Usage of "Gray's Anatomy"

Gray's Anatomy was chosen for comparison, as it describes all of human anatomy, and has continously been developed over many years. The 1st edition was released back in 1858, and is not on its 42nd release as of October, 2020, though only the prior version will be used for analysis in this projct.

This could potentially mean that 5 years worth of results in research on the human anatomy is not included in this analysis, and information compared to Wikipedia pages could be outdated, just as the Wikipedia pages could be likely to have outdated information.

A PDF of the book was used to extract each chapter of the book into txt files. As the book has an absurd number of references to figures, chapters, commentary, etc., a bit of data cleaning was done by excluding some text in parenthesis, as it did not otherwise contribute to the text. Also, figure text and side nodes is not included in the analysis. An analysis of the text has been made, but will not be otherwise available.

References to other medical texts/people has not been removed from the chapter texts, as it could be significant to the text, though the words "et" and "al" has been added to the list of stopwords.

## A network of the human body

A network is created using Wikipedia API to extract the text on Wikipedia pages, along with their links to other Wikipedia pages. Every Wikipedia page is a node, and directed edges are made from the references of one Wikipedia to another Wikipedia page. The result: A directed network.

As nodes cannot be expected to be linked to each other, the giant connected component (GCC) is extracted to make sure that the most possible data is being used for analysis.

### The network

### Degree distribution

### Systems

### Communities

### Centrality


## Text analysis

For analysing the text, the text of the Wikipedia pages are compared to the "Gray's Anatomy (41st edition)" textbook.

### Results

Text | Words | Sentences | Words pr. sentence | Unique words | Percentage
---- | ----- | --------- | ------------------ | ------------ | ----------
Wikipedia      |  5 | 23 | 0.1 | 2 | 2%
Gray's Anatomy | 10 | 23 | 0.2 | 4 | 3%

> Table 1: General text information.

Text | Long words (10+) | Percentage | Long words (15+) | Percentage | Long words (20+) | Percentage  
---- | ---------------- | ---------- | ---------------- | ---------- | ---------------- | ----------
Wikipedia      | 10 | 10% | 5 | 0.7% | 2 | 0.2%
Gray's Anatomy | 100 | 15% | 10 | 0.5% | 4 | 0.2%

> Table 2: The word lengths.

Text | Stop words | Percentage
---- | ---------- | ----------

> Table 3: Stopwords.

Text | Lix Score
---- | ---------
The Ugly Duckling   | 30
The Holy Bible      | 42
Wikipedia           | ??
Gray's Anatomy      | 58
The US Constitution | 71

> Table 4: LIX readability analysis. LIX is a readability measure indicating the difficulty of reading a text developed by Swedish scholar Carl-Hugo Björnsson. LIX was originally developed for Swedish texts, but it can be seen that applying it to litterary works in English has some merit. All texts in the table have been analyzed using the same algorithm.

! Compare the texts and talk about readability

Read further about analysis results of [systems](link), [pages](link), [sections](link), and [chapters](link).

### Communities



# Conclusions


