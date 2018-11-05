Datasets of Automatic Keyphrase Extraction
============================================

This repository contains annotated datasets of Automatic Keyphrase Extraction.

If you know any more datasets, and want to contribute, please, notify me.

In summary, this repository has 20 datasets, with the following statistics:

| Dataset                         | Language | Type of Doc     | Domain        | #Docs | #Gold Keys (per doc) | #Tokens per doc | Absent GoldKey | 
| ------------------------------- | -------- | --------------- | ------------- | ----- | -------------------- | --------------- | -------------- |
| [__110-PT-BN-KP__](#110)        | PT       | News            | Misc.         | 110   | 2610 (23.73)         | 304.00          | 2.5%           |
| [__500N-KPCrowd-v1.1__](#500)   | EN       | News            | Misc.         | 500   | 24459 (48.92)        | 408.33          | 13.5%          |
| [__Inspec__](#Inspec)           | EN       | Abstract        | Comp. Science | 2000  | 29230 (14.62)        | 128.20          | 37.7%          |
| [__Krapivin2009__](#Krapivin)   | EN       | Paper           | Comp. Science | 2304  | 14599 (6.34)         | 8040.74         | 15.3%          |
| [__KWTweet__](#KWTweet)         | EN       | Tweets          | Misc.         | 7736  | 31759 (4.12)         | 19.79           | 7.87%          |
| [__Nguyen2007__](#Nguyen)       | EN       | Paper           | Comp. Science | 209   | 2369 (11.33)         | 5201.09         | 17.8%          |
| [__PubMed__](#PubMed)           | EN       | Paper           | Comp. Science | 500   | 7620 (15.24)         | 3992.78         | 60.2%          |
| [__Schutz2008__](#Schutz)       | EN       | Paper           | Comp. Science | 1231  | 55013 (44.69)        | 3901.31         | 13.6%          |
| [__SemEval2010__](#SemEval2010) | EN       | Paper           | Comp. Science | 243   | 4002 (16.47)         | 8332.34         | 11.3%          |
| [__SemEval2017__](#SemEval2017) | EN       | Paragraph       | Misc.         | 493   | 8969 (18.19)         | 178.22          | 0.0%           |
| [__WikiNews__](#WKC)            | FR       | News            | Misc.         | 100   | 1177 (11.77)         | 293.52          | 5.0%           |
| [__cacic__](#cacic)             | ES       | Paper           | Comp. Science | 888   | 4282 (4.82)          | 3985.84         | 2.2%           |
| [__citeulike180__](#citeulike)  | EN       | Paper           | Misc.         | 183   | 3370 (18.42)         | 4796.08         | 32.2%          |
| [__fao30__](#fao30)             | EN       | Paper           | Agriculture   | 30    | 997 (33.23)          | 4777.70         | 41.7%          |
| [__fao780__](#fao780)           | EN       | Paper           | Agriculture   | 779   | 6990 (8.97)          | 4971.79         | 36.1%          |
| [__kdd__](#kdd)                 | EN       | Paper           | Comp. Science | 755   | 3831 (5.07)          | 75.97           | 53.2%          |
| [__pak2018__](#pak)             | PL       | Abstract        | Misc.         | 50    | 232 (4.64)           | 97.36           | 64.7%          |
| [__theses100__](#theses)        | EN       | Msc/Phd Thesis  | Misc.         | 100   | 767 (7.67)           | 4728.86         | 47.6%          |
| [__wicc__](#wicc)               | ES       | Paper           | Comp. Science | 1640  | 7498 (4.57)          | 1955.56         | 2.7%           |
| [__wiki20__](#wiki20)           | EN       | Research Report | Comp. Science | 20    | 730 (36.50)          | 6177.65         | 51.8%          |
| [__www__](#www)                 | EN       | Paper           | Comp. Science | 1330  | 7711 (5.80)          | 84.08           | 55.0%          |

<br><br>

<a name="110"></a>
### 110-PT-BN-KP

**Dateset**: [110-PT-BN-KP](datasets/110-PT-BN-KP.zip)

**Cite**: [Supervised Topical Key Phrase Extraction of News Stories using Crowdsourcing, Light Filtering and Co-reference Normalization](https://arxiv.org/abs/1306.4886)

**Description**: The 110-PT-BN-KP is a TV Broadcast News (BN) dataset that contains 110 transcription text documents from 8 broadcast news programs from the European Portuguese ALERT BN database ranging from politics, sports, finance and other broadcast news. After the speech to text transcription, each news was manually reexamined to fix any segmentation error and the gold keywords were created asking one tagger to extract all keywords that summarize the document content.

---

<a name="500"></a>
### 500N-KPCrowd-v1.1

**Dateset**: [500N-KPCrowd-v1.1](datasets/500N-KPCrowd-v1.1.zip)

**Cite**: [Keyphrase cloud generation of broadcast news](https://arxiv.org/abs/1306.4606)

**Description**: 500N-KPCrowd-v1.1 is a broadcast news transcription dataset. This dataset consists of 500 English broadcast news stories from 10 different categories (art and culture; business; crime; fashion; health; politics us; politics world; science; sports; technology) with 50 docs per category. The ground truth is built using Amazon’s Mechanical Turk service to recruit and manage taggers. Multiple annotators were required to look at the same news story and assign a set of keywords from the text itself. The final ground truth consists of keywords selected at least by 90% of the taggers.

---

<a name="cacic"></a>
### cacic

**Dateset**: [cacic](datasets/cacic.zip)

**Cite**: [Keyword Identification in Spanish Documents using Neural Networks](http://sedici.unlp.edu.ar/handle/10915/50087)

**Description**: The cacic collection is a Spanish dataset formed by a set of scientific articles published between 2005 and 2013 and consist of 888 scientific papers published in the Argentine Congress of Computer Science [CACIC](http://redunci.info.unlp.edu.ar/cacic.html). 

---

<a name="citeulike"></a>
### citeulike180

**Dateset**: [citeulike180](datasets/citeulike180.zip)

**Cite**: [Human-competitive Tagging Using Automatic Keyphrase Extraction](https://dl.acm.org/citation.cfm?id=1699678)

**Description**: The citeulike180 dataset is based on CiteULike.org platform which organizes academic citations. The CiteULike.org corpus is a full-text paper collection freely available that contains information about the users who tagged the documents. The dataset is based on a subset of CiteULike.org containing documents that have been indexed with at least three keywords on which at least two users have agreed. As well as filtering the document set, the dataset only considers annotators who have at least two additional co-annotators tagging the same common document. The result is a set of 180 documents indexed by 332 taggers, where most documents are related to the area of bioinformatics.

---

<a name="fao30"></a>
### fao30

**Dateset**: [fao30](datasets/fao30.zip)

**Cite**: [Domain‐independent automatic keyphrase indexing with small training sets](https://onlinelibrary.wiley.com/doi/abs/10.1002/asi.20790)

**Description**: fao30 dataset is based on agricultural documents obtained from the two datasets based on Food and Agriculture Organization (FAO) of the United Nations, with 30 documents. It is full-text documents randomly selected from the FAO’s repository, where the keywords were manually assigned by six professional annotators at FAO.

---

<a name="fao780"></a>
### fao780

**Dateset**: [fao780](datasets/fao780.zip)

**Cite**: [Domain‐independent automatic keyphrase indexing with small training sets](https://onlinelibrary.wiley.com/doi/abs/10.1002/asi.20790)

**Description**: fao780 dataset is based on agricultural documents obtained from the two datasets based on Food and Agriculture Organization (FAO) of the United Nations, with 780 documents. It is full-text documents randomly selected from the FAO’s repository, where the keywords were manually tagged by professional FAO staff with terms from the Agrovoc thesaurus.

---

<a name="Inspec"></a>
### Inspec

**Dateset**: [Inspec](datasets/Inspec.zip)

**Cite**: [Improved automatic keyword extraction given more linguistic knowledge](https://dl.acm.org/citation.cfm?id=1119383)

**Description**: Inspec consists of 2,000 abstracts of scientific journal papers from Computer Science collected between the years 1998 and 2002. Each document has two sets of keywords assigned: the controlled keywords, which are manually controlled assigned keywords that appear in the Inspec thesaurus but may not appear in the document, and the uncontrolled keywords which are freely assigned by the editors, i.e., are not restricted to the thesaurus or to the document. In our repository, we consider a union of both sets as the ground-truth.

---

<a name="kdd"></a>
### kdd

**Dateset**: [kdd](datasets/kdd.zip)

**Cite**: [Extracting Keyphrases from Research Papers using Citation Networks](https://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/viewFile/8662/8618)

**Description**: The KDD collection is based on the abstracts of papers collected from the ACM Conference on Knowledge Discovery and Data Mining (KDD) published during the period 2004-2014, with 755 documents. The gold-keywords of these papers are the author-labeled terms. 

---

<a name="Krapivin"></a>
### Krapivin2009

**Dateset**: [Krapivin2009](datasets/Krapivin2009.zip)

**Cite**: [Large dataset for keyphrases extraction](http://eprints.biblio.unitn.it/1671/)

**Description**: The Krapivin2009 is the biggest dataset in terms of documents, with 2,304 full papers from the Computer Science domain, which were published by ACM in the period ranging from 2003 to 2005. The papers were downloaded from CiteSeerX Autonomous Digital Library and each one has its keywords assigned by the authors and verified by the reviewers.

---

<a name="KWTweet"></a>
### KWTweet

**Dateset**: [KWTweet](datasets/KWTweets.zip)

**Cite**: Not public yet! <!-- [Large dataset for keyphrases extraction](http://eprints.biblio.unitn.it/1671/) -->

**Description**: KWTweet Dataset is a collection of 7736 tweets from 25 users (from several different domains) published during the period of one complete month (September 1, 2017 to September 30, 2017) which was labelled by 15 annotators. Each tweet has at most 140 characters and 19.79 tokens on average.

---

<a name="Nguyen"></a>
### Nguyen2007

**Dateset**: [Nguyen2007](datasets/Nguyen2007.zip)

**Cite**: [Keyphrase Extraction in Scientific Publications](https://link.springer.com/chapter/10.1007%2F978-3-540-77094-7_41)

**Description**: The Nguyen2007 is a dataset composed of 211 scientific conference papers. The gold keywords were manually assigned by volunteers’ students who were given three papers to read. The keywords assigned by the authors of the paper were hidden to avoid bias. 

---

<a name="pak"></a>
### pak2018

**Dateset**: [pak2018](datasets/pak2018.zip)

**Cite**: [[OUR]](DOI)

**Description**: pak2018 is a dataset in Polish formed by 50 abstracts of journals on technical topics collected from [Measurement Automation and Monitoring](http://pak.info.pl/) (in Polish “Pomiary, Automatyka, Kontrola”). The gold keywords are those author-assigned, resulting in 2-6 keywords per document.

---

<a name="PubMed"></a>
### PubMed

**Dateset**: [PubMed](datasets/PubMed.zip)

**Cite**: [???](DOI)

**Description**: PubMed dataset is based on full-text papers collected from PubMed Central, which comprises over 26 million citations for biomedical literature from MEDLINE, life science journals, and online books. It consists of 500 papers selected from the same source. PubMed uses the Medical Subject Headings [MeSH](https://www.ncbi.nlm.nih.gov/mesh), a controlled vocabulary thesaurus used for indexing articles for PubMed, as the gold keywords to the documents.

---

<a name="Schutz"></a>
### Schutz2008

**Dateset**: [Schutz2008](datasets/Schutz2008.zip)

**Cite**: [Keyphrase Extraction from Single Documents in the Open Domain Exploiting Linguistic and Statistical Methods](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.394.5372&rep=rep1&type=pdf)

**Description**: Schutz2008 dataset is based on full-text papers collected from PubMed Central, which comprises over 26 million citations for biomedical literature from MEDLINE, life science journals, and online books. It consists of 1,231 papers selected from PubMed Central that the documents are distributed across 254 different journals, ranging from Abdominal Imaging to World
Journal of Urology. These keywords assigned by the authors are hidden in the article and used as gold keywords.

---

<a name="SemEval2010"></a>
### SemEval2010

**Dateset**: [SemEval2010](datasets/SemEval2010.zip)

**Cite**: [Semeval-2010 task 5: Automatic keyphrase extraction from scientific articles](https://dl.acm.org/citation.cfm?id=1859668)

**Description**: SemEval2010 consists of 244 full scientific papers extracted from the ACM Digital Library (one of the most popular datasets which have been previously used for keyword extraction evaluation), each one ranging from 6 to 8 pages and belonging to four different computer science research areas (distributed systems; information search and retrieval; distributed artificial intelligence – multiagent systems; social and behavioral sciences – economics). Each paper has an author-assigned set of keywords (which are part of the original pdf file) and a set of keywords assigned by professional editors, both of which, may or may not appear explicitly in the text.

---

<a name="SemEval2017"></a>
### SemEval2017

**Dateset**: [SemEval2017](datasets/SemEval2017.zip)

**Cite**: [Semeval 2017 task 10: Scienceie-extracting keyphrases and relations from scientific publications](https://arxiv.org/abs/1704.02853)

**Description**: SemEval2017 consists of 500 paragraphs selected from 500 ScienceDirect journal articles, evenly distributed among the domains of Computer Science, Material Sciences and Physics. Each text has a number of keywords selected by one undergraduate student and an expert annotator. The expert's annotation is prioritized whenever there is disagreement between both annotators. The original purpose is extracting keywords and relations from scientific publications.

---

<a name="theses"></a>
### theses100

**Dateset**: [theses100](datasets/theses100.zip)

**Cite**: [???](DOI)

**Description**: The theses100 dataset consists of 100 full master and Ph.D. theses from the University of Waikato, New Zeland. The domain of the theses made available is quite different ranging from chemistry, computer science, economics to psychology, philosophy, history, and others.

---

<a name="wicc"></a>
### wicc

**Dateset**: [wicc](datasets/wicc.zip)

**Cite**: [Keyword Identification in Spanish Documents using Neural Networks](http://sedici.unlp.edu.ar/handle/10915/50087)

**Description**: The wicc dataset is composed of 1640 scientific articles published between 1999 and 2012 of the Workshop of Researchers in Computer Science [WICC](http://redunci.info.unlp.edu.ar/wicc.html). 

---

<a name="wiki20"></a>
### wiki20

**Dateset**: [wiki20](datasets/wiki20.zip)

**Cite**: [Topic indexing with Wikipedia](http://www.aaai.org/Papers/Workshops/2008/WS-08-15/WS08-15-004.pdf)

**Description**: wiki20 consists of 20 English technical research reports covering different aspects of computer science. Fifteen teams, each consisting of two senior computer science undergraduates assigned keywords to each report using Wikipedia article titles as the candidate vocabulary. The teams were instructed to assign around 5 keywords to each document. Each team assigned 5.7 keywords on average. 

---

<a name="WKC"></a>
### WikiNews

**Dateset**: [WikiNews](datasets/WKC.zip)

**Cite**: [???](DOI)

**Description**: WikiNews is a French corpus created from the French version of WikiNews that contains 100 news articles published between May 2012 and December 2012 and manually annotated by at least three students.

---

<a name="www"></a>
### www

**Dateset**: [www](datasets/www.zip)

**Cite**: [Extracting Keyphrases from Research Papers using Citation Networks](https://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/viewFile/8662/8618)

**Description**: the WWW collection is based on the abstracts of papers collected from the World Wide Web Conference (WWW) published during the period 2004-2014, with 1330 documents. The gold-keywords of these papers are the author-labeled terms. 

---