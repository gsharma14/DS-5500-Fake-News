# DS-5500
## Is it all fake? – Fake News Detection
**Authors:** Gopalika Sharma and Surya Menon 

#### Summary:
The news is an integral part of our society; informing the public about the local, national, and international events is essential to ensuring communities are knowledgeable enough to make the best possible decisions in their lives and are prepared to hold institutions accountable for the consequences of their actions. Recent events have truly underscored the importance of the news in our daily lives, from better understanding the status of a pandemic to evaluating how the stock market is reacting to political events (e.g., judge nominations and presidential elections). With the expansion of the Internet and the rise of social media, we are being bombarded with more news sources than ever before. However, with this increased availability of information, it is often difficult to distinguish between articles with false information and those providing real, fact-checked news. Furthermore, rising political turbulence and societal unrest has enabled the dissemination of fake or inaccurate news, that is quickly spread and accepted by large groups of individuals (1).

The widespread effects of fake news and the ease with which individuals are tricked into believing false information necessitates more concentrated efforts to improve and automate fake news detection; having resources to detect misinformation is an important step in rebuilding trust in the news media by better establishing standards for journalistic integrity and truth (2). The goal of this project is to detect the language patterns that characterize fake and real news, utilizing machine learning and natural language processing (NLP) techniques. We hope that developing a model to accurately detect fake news will help in flushing out the onslaught of misleading information that has steadily seeped into our society.

To accomplish this task, we plan to primarily use a dataset from the IEEE DataPort platform that contains news sample text from various publications; these articles have been labeled as either “real” or “fake” (3). From our exploratory data analysis (EDA), we hope to identify general features or concepts that an individual can use to efficiently evaluate an article for its authenticity. After preprocessing the raw text data to produce document frequency metrics, we plan to fit multiple binary classification models, including Logistic Regression, Support Vector Machines (SVM), and a pre-trained neural network, to detect fake news articles. Additionally, we would like to train models to better classify specific news topics (e.g., politics, entertainment, disasters, etc.) as real or fake. Finally, time permitting, we would like to build an application that can classify user-submitted text input as fake or real. Our work can help define the essential factors of consistent and trustworthy news reporting and can ultimately be used to empower our community to better recognize, filter out, and denounce fake news.
<br />


#### References:
1. Flores, L. (2020, September 30). Fake News: Why Does it Persist and Who’s Sharing it? The Decision Lab. https://thedecisionlab.com/insights/society/fake-news-why-does-it-persist-and-whos-sharing-it/

2. West, D. M. (2017, December 18). How to combat fake news and disinformation. Brookings.
https://www.brookings.edu/research/how-to-combat-fake-news-and-disinformation/

3. Sadeghi, F., Bidgoly, A. J., & Amirkhani, H. (2020, August 18). FNID: Fake News Inference Dataset. IEEE. https://ieee-dataport.org/open-access/fnid-fake-news-inference-dataset

