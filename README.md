# DS-5500
## Is it all fake? – Fake News Detection
**Authors:** Gopalika Sharma and Surya Menon 

#### Summary:
Recent events have truly highlighted the importance of consistent and accurate news reporting for our society to function effectively. With the prominence of the Internet, we are often bombarded with huge amounts of content that shape our world views and ultimately influence our behaviors. Access to high quality information is an essential resource, not only for individuals to make informed decisions in their daily lives, but also for communities to assess the actions of the leaders and institutions responsible for public safety and security. 
While the significance and impact of news is constant, our news consumption habits have continued to evolve, especially within the past decade, due to the rapid rise of social media. These platforms allow for large amounts of information to be quickly accessed and easily shared to wide audiences. Consequently, recent studies have shown that close to 20% of American adults primarily receive political news from social media (1). 

However, this democratization of information has also facilitated the growing influence of fake news in our mainstream culture (2). More content creates increasing opportunities for individuals to encounter and spread inaccurate stories to friends and family. As a result of our reliance on social media versus actual journalism, we have become less informed as communities and are often consuming content to validate our pre-conceived notions, rather than to educate. The large-scale negative impacts of fake news are still emerging, but some of the far-reaching consequences include: the dissemination of propaganda to wider audiences, attempts to undermine democratic systems, and the general erosion of trust in the government and media institutions (3). 

The goal of this capstone project was to explore the features and text of news articles with machine learning and natural language processing (NLP) methods, in order to improve how individuals engage with this content and to reduce the impact of misleading stories. To achieve these goals, we used two datasets that contained news articles labeled as either “real” or “fake”. We first utilized the Fake News Inference Dataset (FNID), which is composed of political news stories between 2007 and August 2020 (4). We also created an article dataset covering the following topics: politics, entertainment, COVID-19, and disasters.

Extensive exploratory data analysis (EDA) was conducted on both datasets to identify general strategies that individuals can employ in their daily lives to evaluate article authenticity. We explored associated article metadata (e.g., publication source) and additional features, such article length, for differences in real and fake news content. We delved further into the raw text data through n-gram extraction, sentiment analysis, and topic modeling. Binary classification models for fake news detection were then developed as resources to effectively combat the onslaught of fake news stories in the widening news landscape. We also experimented with topic-specific classifiers and evaluated the performance between these models to assess if certain topics have more discernable patterns between real and fake content.

Our exploratory analysis revealed distinct patterns between fake and real news stories in terms of article length, publication source, punctuation, and sentiment. Individuals can leverage these findings to more effectively identify fake or misleading stories when browsing news content. Through predictive modeling, we were able to develop effective classifiers to detect general fake news stories; furthermore, topic-specific modeling revealed particular topics, such as politics and COVID-19 reporting, had higher accuracy in fake news detection, perhaps due to the clear differences in language patterns between the real and fake content for these topics.
<br />


#### References:
1. Mitchell, A., Jurkowitz, M., Oliphant, B. J., & Shearer, E. (2020, July 30). Americans Who Mainly Get Their News on Social Media Are Less Engaged, Less Knowledgeable. Pew Research Center. https://www.journalism.org/2020/07/30/americans-who-mainly-get-their-news-on-social-media-are-less-engaged-less-knowledgeable/

2. Flores, L. (2020, September 30). Fake News: Why Does it Persist and Who’s Sharing it? The Decision Lab. https://thedecisionlab.com/insights/society/fake-news-why-does-it-persist-and-whos-sharing-it/

3. West, D. M. (2017, December 18). How to combat fake news and disinformation. Brookings.
https://www.brookings.edu/research/how-to-combat-fake-news-and-disinformation/

4. Sadeghi, F., Bidgoly, A. J., & Amirkhani, H. (2020, August 18). FNID: Fake News Inference Dataset. IEEE. https://ieee-dataport.org/open-access/fnid-fake-news-inference-dataset

5. KaiDMML/FakeNewsNet. (n.d.). GitHub. Retrieved 2020, from https://github.com/KaiDMML/FakeNewsNet  

6. susanli2016/NLP-with-Python. (n.d.). GitHub. Retrieved 2020, from https://github.com/susanli2016/NLP-with-Python/tree/master/data 

7. Kaggle. (n.d.). Real or Not? NLP with Disaster Tweets | Kaggle. Retrieved 2020, from https://www.kaggle.com/c/nlp-getting-started   

