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

Now, let's take a look at the Wikipedia text. For this, the readable text on Wikipedia has been extracted and analysed.
For a broader understanding of the results, the text from Wikipedia is being compared to the chapter texts of "Gray's Anatomy (41st edition)" textbook.

### Results

Let's start by taking a look at the overall text stats.

As seen in Table 1, there are less words on the extracted Wikipedia pages, than in the textbook.
This can be interpreted as Wikipedia being less descriptive than the textbook, and the textbook is going into more detail about the organs.
It can also mean that everything described by the book is not represented by the extracted Wikipedia texts.
In any case, let's continue the analysis.

The next noticible thing in Table 1 is that the sentences are 2.50 words longer pr. sentence, indicating that Wikipedia, in general, is trying to say more in every sentence.
Later, we can see if this is the case by looking at stopwords, e.g. the, a, is, are.

Lastly, there is a lack of lexical richness (percentage of unique words) in the text.
This is most likely a result of the texts containing an extreme amount of words.
Knowing the texts, the number of unique words are even higher as a large result of references in both the textbook and Wikipedia.
One would also expect a shorter text to contain more lexical richness.

Text	|	Words	|	Sentences	|	Words pr. sentence	|	Unique words	|	% of text
---	|	---	|	---	|	---	|	---	|	---
Wikipedia	|	633058	|	24546	|	25.79	|	23025	|	3.64%
Gray's Anatomy	|	1084200	|	46554	|	23.29	|	24552	|	2.26%

> Table 1: General text information.

...

Text | Long words (10+)	|	% of text	|	Long Words (15+)	|	% of text	|	Long words (20+)	|	% of text
--- | ---	|	---	|	---	|	---	|	---	|	---
Wikipedia      | 53284	|	8.42%	|	3417	|	0.54%	|	192	|	0.03%
Gray's Anatomy | 109598	|	10.11%	|	8930	|	0.82%	|	299	|	0.03%

> Table 2: The word lengths.

Text	| Stopwords	|	% of text
---	| ---	|	---
Wikipedia	| 269171	|	42.52%
Gray's Anatomy	| 456496	|	42.10%

> Table 3: Stopwords.

Text | Lix Score
---- | ---------
The Ugly Duckling   | 30
The Holy Bible      | 42
Wikipedia           | 56
Gray's Anatomy      | 56
The US Constitution | 71

> Table 4: LIX readability analysis. LIX is a readability measure indicating the difficulty of reading a text developed by Swedish scholar Carl-Hugo Björnsson. LIX was originally developed for Swedish texts, but it can be seen that applying it to litterary works in English has some merit. All texts in the table have been analyzed using the same algorithm.

Text	|	Words	|	Sentences	|	Words pr. sentence	|	Unique words	|	% of text	|	long words (10+)	|	% of text	|	Long Words (15+)	|	% of text	|	Long words (20+)	|	% of text	|	Stopwords	|	% of text	|	Lix score	|	Sentiment score
---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---
Wikipedia	|	633058	|	24546	|	25.79	|	23025	|	3.64%	|	53284	|	8.42%	|	3417	|	0.54%	|	192	|	0.03%	|	269171	|	42.52%	|	56	|	
Gray's Anatomy	|	1084200	|	46554	|	23.29	|	24552	|	2.26%	|	109598	|	10.11%	|	8930	|	0.82%	|	299	|	0.03%	|	456496	|	42.10%	|	56	|	

> Table 5: Summation of the overall text analysis.

### Word clouds

! Compare the texts and talk about readability

Read further about the text analysis results of [Wikipedia](https://noramurakozy.github.io/wiki) or [Gray's Anatomy](https://noramurakozy.github.io/book).

### Communities



# Conclusions


