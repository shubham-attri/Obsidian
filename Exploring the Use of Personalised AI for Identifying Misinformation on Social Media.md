
![[Exploring_the_Use_of_Personalized_AI_for_Identifying_Misinformation_on_Social_Media.pdf]]


# Presentation

## Introduction

#background
Misinformation on social media platforms has become a significant problem in recent years, with false information spreading rapidly and potentially leading to negative consequences such as the propagation of false beliefs, the impact on elections, and the undermining of trust in institutions.

#currentApproaches
Current approaches to combat misinformation include fact-checking, content moderation by platforms, and credibility indicators. However, these approaches have limitations related to scale, subjectivity, and user autonomy. Fact-checking is time-consuming and cannot keep up with the volume of false information being shared. Content moderation by platforms can be subjective and may not catch all instances of false information. Credibility indicators, such as user ratings or flags, can be influenced by biases and may not be reliable indicators of accuracy.

#IdeaOfPaper
This paper explores the idea of a personalized AI that learns from user assessments on content accuracy and predicts how the user would assess new content. The motivation behind using AI is to amplify user assessments to combat misinformation at scale. By training an AI on a user's assessments, the AI can predict how the user would assess new content, allowing for a wider reach of assessments beyond what the user has personally assessed.

#ResearchQuestions
The research questions addressed in the paper relate to how users perceive a personalized AI for assessing the accuracy of online content, whether and how users are influenced by the AI's predictions, and identifying design implications and research directions for the use of a personalized AI for content moderation.


## Method

#setting
The experimental platform developed for this study allowed for the training of personalized AI models for each user in real-time based on their content assessments. The platform presented study participants with a feed of tweets that they needed to assess and train a personalized AI model for each participant in real-time based on the assessments that the participant provided. The AI that was trained for each participant evolved and updated its predictions as the participant provided more assessments. 
A total of 120 Participants and the tweet dataset was acquired using the Twitter API to fetch recent tweets related to COVID-19.

#studyProcedure
During the study procedure, users interacted with the AI by assessing tweet accuracy, seeing AI predictions update, and providing feedback. Participants were asked to assess a feed of tweets and receive their personalized AI's predictions of how they would assess other tweets that they had not already assessed. The purpose of the task was two fold: first, to expose participants to the experience of interacting with a personalized AI for determining content accuracy on social media and gauge their perceptions, and second, to compare user assessments between conditions of seeing vs not seeing AI predictions to understand the AI's influence.

#Assesment
To understand the AI's influence, user assessments were compared between conditions of seeing vs not seeing AI predictions. In the "AI prediction" condition, participants were shown the AI's predictions of how they would assess other tweets. In the "no AI prediction" condition, participants were not shown the AI's predictions. By comparing user assessments between these two conditions, the authors were able to understand the influence of the AI's predictions on user assessments.

#PostStudy
After the study, a post-study survey was conducted to capture users' perception of the AI. The survey asked participants about their experience interacting with the AI, their perception of the AI's accuracy, and their willingness to use such a tool in the future.

## Results

The study found that users generally had a positive perception of the personalized AI approach, with many seeing benefits such as the ability to receive personalized content recommendations and the potential to combat misinformation at scale. However, some users had reservations, such as concerns about the accuracy of the AI and the potential for the AI to influence their assessments.

The results showed that seeing AI predictions swayed users' assessments compared to when predictions were hidden, indicating over-reliance on the AI. Over-reliance on the AI grew over time, but this effect was mitigated when users provided reasoning for their assessments. Interestingly, agreement with the AI did not make users more confident in their assessments.

Overall, the study highlights the potential benefits and challenges of using personalized AI for content moderation on social media. While the approach has the potential to combat misinformation at scale, there are concerns about the accuracy of the AI and the potential for over-reliance on the AI. The study suggests that future work is needed to address these concerns and to develop effective ways to integrate personalized AI into content moderation on social media platforms.

#mathematicalResults
Regarding the mathematical results of the study, the authors used regression models to analyze the data and test their hypotheses. For example, they used a regression model to examine whether providing reasoning mitigated the negative effect of seeing the AI's predictions on users' agreement with the AI. The results of this analysis showed that when users provided reasoning, they were as likely to agree with the AI's predictions as when they did not see the AI's predictions. This finding was statistically significant, indicating that providing reasoning can reduce the influence of AI on user judgments. The authors also used regression models to identify factors that influenced users' agreement with the AI's predictions, such as the accuracy of the AI's predictions, the difficulty of the tweets, and the users' prior knowledge of the topic. These analyses provided valuable insights into how users perceive personalized AI for assessing the accuracy of online content and how they are influenced by seeing the AI's predictions. Overall, the authors used rigorous statistical methods to analyze the data and test their hypotheses, providing a solid foundation for their conclusions.

#2assesments
the study had two conditions: an unassisted condition and an assisted condition. In the unassisted condition, users assessed the tweets without seeing the AI's predictions, while in the assisted condition, users saw the AI's predictions before assessing the tweets. The authors measured the agreement between users' assessments and the AI's predictions in both conditions to examine the influence of the AI on users' judgments. They found that users' agreement with the AI's predictions was higher in the assisted condition than in the unassisted condition, indicating that users were influenced by the AI's predictions. However, the authors also found that asking users to provide reasoning for their assessments mitigated the negative effect of seeing the AI's predictions, suggesting that prompting users to provide reasoning could be an effective intervention to reduce the influence of AI on user judgments. Overall, the two assessments in the study allowed the authors to compare users' judgments with and without the influence of the AI's predictions and to identify effective interventions to reduce the negative effects of AI on user judgments.

## Remarks 


The issue of AI influencing user judgments is a concern for deployment, as the study found that seeing AI predictions swayed users' assessments compared to when predictions were hidden, indicating over-reliance on the AI. This over-reliance on the AI could lead to users becoming more extreme in their views or disregarding accurate content. 

To address this concern, the study suggests potential ideas such as requiring user justifications for their assessments. By prompting users to provide reasoning for their assessments, the study found that this appeared to mitigate bias and over-reliance on the AI. Future work could explore scenarios where users are prompted to indicate whether they agree or disagree with their AI's predictions and provide reasoning for their (dis)agreement.

However, there are ethical considerations around enabling personalized curation and selective exposure. The use of personalized AI for content moderation could lead to filter bubbles, where users only receive content that supports their views and are shielded from divergent views. This could have negative consequences for democracy and social cohesion. 

Moreover, there are challenges in translating this approach to real-world platforms. For example, detecting verifiable claims is a difficult task that requires significant resources and expertise. Additionally, the use of AI for content moderation raises concerns about bias and fairness, as AI models can be influenced by the data they are trained on and the biases of their creators. 

Overall, the study highlights the potential benefits and challenges of using personalized AI for content moderation on social media. While the approach has the potential to combat misinformation at scale, there are concerns about the accuracy of the AI, over-reliance on the AI, and ethical considerations around personalized curation and selective exposure. Future work is needed to address these concerns and to develop effective ways to integrate personalized AI into content moderation on social media platforms.


In the discussions and future work section, the authors highlight several important implications of their study and suggest directions for future research. One key implication is that users are influenced by the AI's predictions, but this influence can be mitigated by prompting users to provide reasoning for their assessments. This finding suggests that interventions that encourage users to think critically and justify their judgments could be effective in reducing the negative effects of AI on user judgments. Another implication is that the accuracy of the AI's predictions is an important factor that influences users' agreement with the AI. This finding suggests that improving the accuracy of AI models could lead to better user judgments and more effective content moderation. 

The authors also suggest several directions for future research, such as exploring the impact of different types of AI models on user judgments, investigating the role of social influence on user judgments, and examining the long-term effects of using personalized AI for content moderation. These directions could lead to a deeper understanding of how users perceive and interact with AI in the context of content moderation and could inform the development of more effective interventions and AI models.

Overall, this work provides valuable insights into the use of personalized AI for identifying misinformation on social media and highlights the importance of considering user perceptions and behaviors when designing AI-based content moderation systems. The findings and implications of this study could have significant implications for the development of more effective and user-friendly content moderation systems that leverage the power of AI while minimizing its negative effects.

![[ChatPDF-Exploring_the_Use_of_Personalized_AI_for_Identifying_Misinformation_on_Social_Media (1).txt]]


## Limitations 

The study has several limitations that may affect the generalizability of its findings on users' perception and AI influence. 

Firstly, the study required users to assess all tweets in the feed, whereas in reality, users may only selectively share or engage with certain tweets. This may affect the generalizability of the findings, as users' assessments and interactions with the AI may differ in a more realistic scenario.

Secondly, the AI training in the study was simplified, as it only used a single feature (the user's assessment) to update the model. In reality, AI models are often trained on a variety of features, such as user behavior, content features, and network structure. This may affect the generalizability of the findings, as the AI's influence on user assessments may differ in a more complex AI model.

Thirdly, the study did not consider users' attitudes toward AI, such as their trust in AI or their willingness to use AI for content moderation. This may affect the generalizability of the findings, as users' attitudes toward AI may influence their perception and use of personalized AI for content moderation.

Overall, these limitations suggest that the findings of the study should be interpreted with caution and that future work is needed to address these limitations and to develop a more comprehensive understanding of users' perception and AI influence in personalized AI for content moderation.


## Conclusion


Me: Summarize key takeaways from study on promise and risks of personalized AI for combating misinformation.
Emphasize that further research needed before deploying such an approach given concerns found.

#promises and #risks
The study found that personalized AI has the potential to combat misinformation at scale and that users generally had a positive perception of the approach. However, there are concerns about the accuracy of the AI, over-reliance on the AI, and ethical considerations around personalized curation and selective exposure. 

The study suggests that further research is needed before deploying such an approach, given the concerns found. Future work could explore scenarios where users are prompted to indicate whether they agree or disagree with their AI's predictions and provide reasoning for their (dis)agreement. Additionally, future work is needed to address the limitations of the study and to develop a more comprehensive understanding of users' perception and AI influence in personalized AI for content moderation. 

Overall, the study highlights the promise and risks of using personalized AI for combating misinformation on social media and suggests that further research is needed before deploying such an approach.


## Strenghts and weakness of papers

Strengths of the paper:
- The study provides valuable insights into how users perceive personalized AI for assessing the accuracy of online content and how they are influenced by seeing the accuracy predictions of the AI.
- The study identifies an intervention that could mitigate the influence of AI on user judgments, which is prompting users to provide reasoning for their assessments.
- The study highlights the potential benefits and challenges of using personalized AI for content moderation on social media and raises important ethical considerations around personalized curation and selective exposure.
- The study provides a comprehensive review of related work in the literature related to detecting and dealing with misinformation on social media platforms and the influence of AI on human decision making.

Weaknesses of the paper:
- The study has several limitations that may affect the generalizability of its findings, such as the simplified AI training and the requirement for users to assess all tweets in the feed.
- The study did not consider users' attitudes toward AI, such as their trust in AI or their willingness to use AI for content moderation.
- The study was conducted in a controlled laboratory setting, which may not reflect the complexity and diversity of real-world social media platforms.

## Possible future research scope in students' context:

- Future research could explore the use of personalized AI for identifying misinformation in educational contexts, such as online learning platforms or social media groups for students.
- Future research could investigate the effectiveness of different interventions to mitigate the influence of AI on student judgments, such as prompting students to provide reasoning for their assessments or providing feedback on the accuracy of their assessments.
- Future research could examine the ethical considerations around personalized curation and selective exposure in educational contexts, such as the potential for filter bubbles or the impact on students' critical thinking skills.
- Future research could explore the potential benefits and challenges of using personalized AI for content moderation in student communities, such as identifying and addressing cyberbullying or hate speech.
