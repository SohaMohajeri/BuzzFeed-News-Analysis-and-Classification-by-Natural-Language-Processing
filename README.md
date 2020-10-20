# BuzzFeed News Analysis and Classification

![4](https://user-images.githubusercontent.com/69224996/96525972-3661ab00-1231-11eb-815f-f9a1ddb7500b.jpg)

FakenewsNet is a repository for an ongoing data collection project for fake news research at ASU. The repository consists of comprehensive dataset of Buzzfeed news and politifact which contains two separate datasets of real and fake news. The FakenewsNet consists of multi-dimension information that not only provides signals for detecting fake news but can also be used for researches such as understanding fake news propagation and fake news intervention. However, the repository is very wide and multi-dimensional, In this project, we perform a detailed analysis on Buzzfeed news dataset.

The Buzzfeed news dataset comprises a complete sample of news published in Facebook from 9 news agencies over a week close to the 2016 U.S. election from September 19 to 23 and September 26 and 27. Every post and the linked article were fact-checked claim-by-claim by 5 BuzzFeed journalists. There are two datsets of Buzzfeed news one dataset of fake news and another dataset of real news in the form of csv files, each have 91 observations and 12 features/variables.

The Buzzfeed news dataset consists of two datasets contain the following main features:

- id: the id assigned to the news article webpage Real if the article is real or fake if reported fake.

- title : It refers to the headline that aims to catch the attention of readers and relates well to the major of the news topic.

- text : Text refers to the body of the article, it elaborates the details of news story. Usually there is a major claim which shaped the angle of the publisher and is specifically highlighted and elaborated upon.

- source: It indicates the author or publisher of the news article.

- images: It is an important part of body content of news article, which provides visual cues to frame the story.

- movies: It is also an important part of news article, a link to video or a movie clip included in a article, also provides visual cues to frame the story.

In this analysis, we do not consider features like url, top_img, authors, publish_date, canonical link and metedata because these usually provide redundant information which we can be obtained from other main variables and do not add more value to our analysis.

The two main features we care about are the source of the fake news and the language used in the fake news. In particular, we are interested in finding sources which published fake news and finding words that are more associated with one category than other.

The main purpose of this analysis is to develop methods to analyze fake news versus real news. This project is divided into two parts: (1) Exploratory Data Analysis (2) Classification. The goal of the first part is to analyze the real and fake news datasets to find sources that often published fake news and determine the most frequent words included in the title and body of fake and real news. The goal of the second part is to a classifer that can predict and detect fakenews. We use three different classifiers to classify documents into real/fake news categories.
