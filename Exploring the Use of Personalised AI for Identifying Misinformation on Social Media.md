
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

## Remarks 
