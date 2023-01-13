# 2.5+ Million Rows Egyptian Datasets Collection

Kaggle Link: https://www.kaggle.com/datasets/mostafanofal/two-million-rows-egyptian-datasets

---

# Intro

## Objective

The datasets were collected for our Master's graduation project sponsered by Microsoft.

## Title

Automating novel terms and usage detection in Egyptian Arabic dialect

## Description

The project aims at identifying unfamiliar terms relatively new in the Egyptian Arabic dialect. In addition to words that their meaning was changed over time with another context or misspelled to enhance the translation corpus.

## Team Members

[Khaled Elsaka](https://www.linkedin.com/in/khaled-el-saka-962700161/)

[Nada Montasser](https://www.linkedin.com/in/nada-montasser-014b1616b/)

[Shaimaa Mamdouh](https://www.linkedin.com/in/shaimaa-mamdouh-2616a9159/)

[Aya Reda](https://www.linkedin.com/in/aya-reda-5202b2191/)

[Mostafa Nofal](https://www.linkedin.com/in/mostafa-nofal-772625194/)

---

## Websites

The datasets were collected from:


*   Kaggle
*   Github
*   Huggingface
*   Google Datasets
*   ScienceDirect
*   ResearchGate
*   IEEE Xplore

---

# Pandas Read

`import pandas as pd`
`data = pd.read_excel("Name.xlsx")`

# Notes

• All Datasets have 3 columns (Text, Year, Source)

• Maximum Rows for excel file is 1,048,576 rows

• If Arabic is encoded in excel:
           - Create new excel file
           - In the Data tab, click on (From Text/CSV) button
           - Browse and select the excel file
           - Change the File_origin to "Unicode (UTF-8)"
           - Save

---

# Egyptian Datasets Description

## Format

Every dataset has the following format

• Year

• Source Name

• Information

• Rows Number

• File Name

---

## 1.Arabic Online Commentary (AOC)

2010

Online version of Arabic newspaper: Al-Youm Al-Sabe’.

688,550 rows AOC_youm7_articles (ar)

1,048,576 rows AOC_youm7_comments

333,225 rows RestOf_AOC_youm7_comments

564,854 rows AOC_subtitles_authors

---

## 2.Arabic Egyptian Tweets

2019

Egyptian tweets cover a blend of different general topics (sentiment analysis)

40,000 rows

Egyptian Tweets

---

## 3.TaghreedT

2021

Egyptian Dialect Corpus (EDC) from Facebook

13,740 rows

TaghreedT

---

## 4.Topic Extraction Data

2019

Egyptian dialect tweets used for topic extraction and topic modelling research

2,256 rows TE_News

2,052 rows TE_Sports

2,358 rows TE_Telecom

2,065 rows TE_Tweets

---

## 5.Habibi Lyrics Corpus

2019

Arabic Song Lyrics corpus

139,162 rows

Habibi

---

## 6.Arabic Political Tweets

2019

Twitter hashtag

431,452 rows

Political Tweets

---

## 7.ArabicReddit

2021

Arabic dataset of Reddit titles and comments from Arab and Egypt subreddits

10,129 rows

Reddit

---

## 8.ar_arz_wiki_corpus

2017

Arabic (Modern Standard) and Egyptian Arabic dialect comparable documents from Wikipedia

9126 rows

Arabic_Egyptian_Wikipedia (ar)

---

## 9.QCRI

2018

Manually segmented and POS tagged tweets

350 rows

QCRI

---

## 10.SADID Benchmark Dataset

2020

SADID Evaluation Datasets for Low-Resource Spoken Language Machine Translation of Arabic Dialects

8,989 rows

SADID

---

## 11.DART

2018

A Large Dataset of Dialectal Arabic Tweets (c) 2018 Qatar University

5,889 rows

DART

---

## 12.Callhome Corpus

2014

Egyptian Arabic Speech Translation Corpus

9,637 rows

Callhome

---

# Other Arabic Datasets Links

## Contact

TEAD:

Two million  egyptian tweets for sentiment analysis

https://github.com/HSMAabdellaoui/TEAD


QADI

67,783 egyptian tweets

https://alt.qcri.org/resources/qadi


2016

5963 words

Egyptian Arabic and Modern Standard Arabic sentiment words and their polarity

https://github.com/NileTMRG/NileULex


Egyptian-Dialect-Gender-Annotated-Dataset

https://github.com/shery91/Egyptian-Dialect-Gender-Annotated-Dataset


2020

ar_cov19

1M tweets of COVID-19 pandemic include both retweets and conversational threads

https://huggingface.co/datasets/ar_cov19


Arabic Poetry

 55K Arabic poem from different Categories with poets from different countries and era

https://www.kaggle.com/datasets/ahmedabelal/arabic-poetry


2016

93,700 hotel reviews in Modern Standard Arabic as well as dialectal Arabic from Booking.com

https://huggingface.co/datasets/hard


2015

8364 restaurant reviews from qaym.com in Arabic for sentiment analysis

https://huggingface.co/datasets/ar_res_reviews


2019

Arabic Flood Twitter Dataset

https://github.com/alaa-a-a/Arabic-Twitter-Corpus-for-Flood-Detection


2021

Arabizi transliteration

https://github.com/bashartalafha/Arabizi-Transliteration


2018

15,050 labelled YouTube comments in Arabic

Anti-Social Behaviour in Online Communication

https://onedrive.live.com/?authkey=!ACDXj_ZNcZPqzy0&id=6EF6951FBF8217F9!105&cid=6EF6951FBF8217F9


arabic-hatespeech-data

https://github.com/motazsaad/arabic-hatespeech-data/blob/master/OSACT4/README.md


Arabic Offensive Comments dataset from Multiple Social Media Platforms

https://github.com/shammur/Arabic-Offensive-Multi-Platform-SocialMedia-Comment-Dataset


2017

75 million of fully vocalized words mainly 97 books from classical and modern Arabic language

https://huggingface.co/datasets/tashkeela


NADiA:

News Articles Dataset in Arabic for Multi-Label Text Categorization
SkyNewsArabia will be referred to as NADiA1, while the latter would be NADiA2. NADiA1 is a big dataset containing 37,445 files, while NADiA2 is a huge dataset that contains 678,563 files. However, after filtering and cleaning we reduced the numbers to 35,416 and 451,230 for NADiA 1 and 2, respectively.
News, North Africa, Levant, Middle East, The Americas, Research, Finance & Economy, War & Terrorism, Gulf, Europe, Political Figures, Iran, Technology, Russia, Sports, Tennis, Football, English League, Arabian Sports, Spanish League, Health, East Asia, Environment, Other Countries

https://data.mendeley.com/datasets/hhrb7phdyx/1


Arabic dialect dictionary  (Django)
Arabic to English or English to Arabic definitions and see results in Levantine, Gulf, or Egyptian
https://github.com/moraesc/arabic-dialect-dict


2018

Arabic POS Dialect

350 manually segmented and POS tagged tweets for each of four dialects: Egyptian, Levantine, Gulf, and Maghrebi

https://huggingface.co/datasets/arabic_pos_dialect


2017

10,547 tweets, 1,682 (16%) of which are sarcastic
Arabic sentiment analysis datasets (SemEval 2017 and ASTD) and adds sarcasm and dialect labels to them

{ "Name": "Egyptian", "Dialect": "ar-EG: (Arabic (Egypt))", "Volume": "2,383", "Unit": "sentences" }  and others

https://huggingface.co/datasets/ar_sarcasm


2021

50K posts

Sentiment Analysis for social media posts in Arabic dialect

{ "Name":"Egyptian", "Dialect": "ar-EG: (Arabic (Egypt))", "Volume": "7,519", "Unit": "sentences" }

https://msda.um6p.ma/msda_datasets


2018

 { "Name": "EGY", "Dialect": "ar-EG: (Arabic (Egypt))", "Volume": "4,061", "Unit": "sentences" }

https://www.lancaster.ac.uk/staff/elhaj/corpora.html


2020 (Register)

{ "Name": "Egypt", "Dialect": "ar-EG: (Arabic (Egypt))", "Volume": "6,635", "Unit": "sentences" }

https://sites.google.com/view/nadi-shared-task


2015

ASTD: Arabic Sentiment Tweets Dataset

10k Arabic sentiment tweets classified into four classes subjective positive, subjective negative, subjective mixed, and objective 

https://github.com/mahmoudnabil/ASTD


2013

A Large Scale Arabic Book Reviews Dataset

63,000 book reviews in Arabic

https://huggingface.co/datasets/labr


2017

Emotional-Tone

10065 tweets in Arabic for Emotion detection in Arabic text

https://huggingface.co/datasets/emotone_ar


2016

BRAD: Books Reviews in Arabic Dataset

510,600 book reviews in Arabic language

https://github.com/elnagara/BRAD-Arabic-Dataset


Dialectal system 

https://mt.qcri.org/api

https://alt.qcri.org/resources1/mt/arabench


2020

COVID-19-Arabic-Tweets-Dataset

6 milllion

https://github.com/SarahAlqurashi/COVID-19-Arabic-Tweets-Dataset


2014

educational video subtitles

Machine learning translation

English and arabic

https://huggingface.co/datasets/qed_amara


2020

QCRI Parallel Tweets

https://huggingface.co/datasets/tweets_ar_en_parallel


2015

Arabic News Article Classification

14 million words with 15,891,729 tokens contained in 57,827 different articles

https://github.com/saidziani/Arabic-News-Article-Classification


2015

Large Multi-Domain Resources for Arabic Sentiment Analysis

https://github.com/hadyelsahar/large-arabic-sentiment-analysis-resouces


##Papers

Freely Available Arabic Corpora: A Scoping Review  (various)

https://www.sciencedirect.com/science/article/pii/S2666990022000015#bib0039


combination of subsets of five corpora: DART, SHAMI, TSAC, PADIC and AOC

https://www.sciencedirect.com/science/article/pii/S2352340921010519

## Papers

NileULex: A Phrase and Word Level Sentiment Lexicon for Egyptian and Modern Standard Arabic

https://aclanthology.org/L16-1463.pdf

DART: A Large Dataset of Dialectal Arabic Tweets
L18-1579.pdf

https://aclanthology.org/L18-1579.pdf


Colloquial Arabic Tweets: Collection, Automatic Annotation, and Classification 

https://ieeexplore.ieee.org/abstract/document/9310507


A Multidialectal Parallel Corpus of Arabic

https://aclanthology.org/L14-1435/#:~:text=The%20daily%20spoken%20variety%20of,within%20other%20Arabic%20speaking%20communities


Automatic Building of Arabic Multi Dialect Text Corpora by Bootstrapping Dialect Words

https://www.researchgate.net/publication/261489194_Automatic_building_of_Arabic_multi_dialect_text_corpora_by_bootstrapping_dialect_words

## License

2021

10,828 Arabic tweets annotated with 10 different labels
multi-label Arabic COVID-19 fake news and hate speech detection dataset

https://github.com/MohamedHadjAmeur/AraCOVID19-MFH


2016

Arabic Web16

150,211,934 Arabic Web pages with high coverage of dialectal Arabic

https://sites.google.com/view/arabicweb16/


Camel Resources

https://docs.google.com/forms/d/e1FAIpQLSfQqhxslVSkBN5ScQ2bvvM0xUVCUnjXxtvkAjupvxm3SSeZGw/viewform

https://camel.abudhabi.nyu.edu/madar-parallel-corpus/


BOLT Egyptian Arabic PropBank and Sense -- Discussion Forum, SMS/Chat, and Conversational Telephone Speech

https://abacus.library.ubc.ca/dataset.xhtml?persistentId=hdl:11272.1/AB2/YS81IR


BOLT Egyptian-English Word Alignment -- Discussion Forum Training
400,448 words of Egyptian Arabic and English parallel text enhanced with linguistic tags to indicate word relations

https://abacus.library.ubc.ca/dataset.xhtml?persistentId=hdl:11272.1/AB2/AR1QCS


BOLT Egyptian Arabic SMS/Chat Parallel Training Data
723,000 tokens of Egyptian Arabic SMS/Chat data collected for the DARPA BOLT program along with their corresponding English translations.

https://datasetsearch.research.google.com/search?src=0&query=egyptian%20dialect&docid=L2cvMTFwNjZfMXRieg%3D%3D
