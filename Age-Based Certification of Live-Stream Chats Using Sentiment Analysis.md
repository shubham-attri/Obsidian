
**Overview:**
Live streaming has become immensely popular, enabling real-time interaction through chats. However, the anonymous and dynamic nature of these chats can expose children to inappropriate content. Platforms often disable chats for younger audiences, depriving them of engagement. We propose an ML model to analyse chat sentiment and give age-based certification, allowing safer access.

**Motivation:**
- Children are vulnerable to mean, *aggressive, or sexual comments* in live chats. 
- They may share personal information with strangers.
- *Cyberbullying and excessive advertising* target children.
- Disabling chats deprives children of knowledge from questioning and engaging.

Our model will use *sentiment analysis of chats to provide age-based ratings, enabling safer, selective access*.

**Related Works:**
- [Live Chat Analysis Using Machine Learning](https://www.researchgate.net/publication/350769799_Live_Chat_Analysis_Using_Machine_Learning)(Conference Paper)
	- Large amount of user emotion data in social media comments about events, products, politics.
	- Sentiment analysis classifies positive/negative content. Useful for NLP tasks but lacks labeled data.
- [Sentiment analysis of Twitch chats using ML](https://ieeexplore.ieee.org/document/9616932) (Conference Paper) 
	- Applies logistic regression and SVM for sentiment analysis on Twitch chats.
	- Uses word embeddings and message metadata like emotes as features.
	- Achieves 86% accuracy on a dataset of 55,000 Twitch messages.
	- Provides insights into chat sentiment and effect of emotes.
- [Sentiment analysis for chat based Application using R](https://www.jetir.org/papers/JETIR1903556.pdf) (Journal Paper)
	-  Sentiment analysis involves computationally studying opinions, emotions expressed in text/emoticons.
	- Project aims to develop a report analysing sentiment in chat app data.
	- Report will provide insights into sentiments at particular times.
	- It is a data analysis project - chat database as input, no textual query.
	- Analysis classifies chat sentiments as positive, negative or neutral.
	- Challenging due to informal language and lack of labeled data.

**Methodology:** 
- Week 3-4: Literature review, data collection, visualisation and processing
- Week 5-7: Build models - Logistic Regression, Decision Trees
- Week 9-10: SVM, Random Forests
- Week 11-13: XGBoost, finalise model, write report

**Team:**
- **Aniket:** Data visualisation and analysis, Decision Trees, Random Forests, SVM
- **Shubham:** Literature review, Logistic Regression, Decision Trees, XGBoost
- **Mayank:** Data preprocessing and analysis, Logistic Regression, SVM
- **Piyush:** Literature review, Data preprocessing, Random Forest, XGBoost

**Impact:**
This project will allow us to apply ML techniques to solve a real-world problem. The model has potential for wider applications like *online classrooms*. Ultimately, it will ***enable safer access and engagement for children.***