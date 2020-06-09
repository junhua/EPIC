# Epidemic Corpus (EPIC)
A large collection of 21 million epidemic-related tweets

[![License: MIT](https://img.shields.io/badge/License-GPLv3-brightgreen.svg)](https://www.gnu.org/licenses/quick-guide-gplv3.pdf)
<br>

## Context

Since the start of COVID-19, several relevant corpora from various sources are presented in the literature that contain millions of data points. While these corpora are valuable in supporting many analysis on this specific pandemic, researchers require additional benchmark corpora that contain other epidemics to facilitate cross-epidemic pattern recognition and trend analysis tasks. During our other efforts on COVID-19 related work, we discover very little disease related corpora in the literature that are sizable and rich enough to support such cross-epidemic analysis tasks.

## EPIC

Here we present \textit{EPIC}, a large-scale epidemic corpus that contains over 21 millions tweets, spanned from year 2006 to 2020.
There are two subsets within the corpus, namely general and outbreaks. The general set contains 3 epidemics, namely Ebola, Cholera and Swine Flu, from post-2006 to 2020; the outbreak set contains 6 epidemic outbreaks, as follows:

* [2009 H1N1 Swine Flu](https://www.who.int/csr/disease/swineflu/en/) (1,961,792)
* [2010 Haiti Cholera](https://www.who.int/csr/don/2010_10_26/en/) (312,002)
* [2012 Middle-East Respiratory Syndrome (MERS)](https://www.who.int/emergencies/mers-cov/en/) (263,336)
* [2013 West African Ebola](https://www.who.int/csr/disease/ebola/en/) (643,001)
* [2016 Yemen Cholera](https://en.wikipedia.org/wiki/2016–2020_Yemen_cholera_outbreak) (61,730)
* [2018 Kivu Ebola](https://en.wikipedia.org/wiki/Kivu_Ebola_epidemic) (12,017)

Each class of data is contained by a single CSV file named after the respective event. Each file contains comma-separated fields per line, where not all files may have a value. The list of fields are as follows:

* date
* username	
* to
* replies
* retweets
* favorites
* text
* geo
* mentions
* hashtags
* id
* permalink

## Usage

This data is intended to support only for academic research purporses and may not be used for any commercial purposes, by any commercial entity, or by any party, unless otherwised authorized by the authors. 

You may download the corpus with the following: [Link1](www.linkedin.com/in/junhua)

If your publication uses the data, either in full or in part, you should cite the paper below:

```
@article{liu2019ipod,
    title={EPIC: An Epidemics Corpus Of 11 Million Relevant Tweets},
    author={Junhua Liu and Trisha Singhal and Lucienne T.M. Blessing and Kristin L. Wood and Kwan Hui Lim},
    year={2020},
    journal={arXiv preprint}
}
```
