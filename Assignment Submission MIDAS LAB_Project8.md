
## Introduction

##### Understanding the Project and Its Goal 

Project Description: "Ensuring Academic Integrity via Typing Patterns in the Age of LLMs."

With the wide adoption of LLMs and NLP based tools have brought up a new concern of the sense of lost Originality in works by many set of its user, specially the students. There have been instances of use of such tools to help them in various examinations, When we use the word Academic Integrity, we Talk more in the student perspective side. It's easier to copy a prompt generated text in helping with the assignment for sake, The typing behaviour can be subject to change. We are looking on the side that using LLM's while writing would have a impact on the behavioural way of typing a content in its report or an assignment. 

The above was discussed and the hypothesis was tested on a smaller set of people and their typing behaviour was noticed, Taking in account the ground truth, there was base to this assumption and now we this projects aim is to solidify this problem and find some potential solution to this, Maybe by developing a system that will generate a score based on its analysis for a session of user typing. 

Take example of Kyron for sake, a platform developed locally by the MIDAS lab, we can use that platform to conduct such examinations, collect data, give scores and refine solution to give a generalised solution and giving the biases to various behavioural changes while typing with and without the help of LLM's.

The below report would be my journaling the report and getting more insight for the depth of the problem statement to solidify my foundation for the future work of the project. 

##### Brief Description of the Dataset

The Dataset is provided by Stonybrook, where we would be working on the dataset gathered by an online writing platform for authors, Where It is inspired by **prosody-based speech analysis** which analysis the deceptive Intent.

Typing behaviour such as different pause timings and revision pattern and correlating a analogy in the behaviour. The results from the dataset suggests a strong relation between the behavoural pattern in typing. 

The publication "*[**Keystroke Patterns as Prosody in Digital Writings: A Case Study with Deceptive Reviews and Essays**](http://aclweb.org/anthology/D/D14/D14-1155.pdf)  
Ritwik Banerjee, Song Feng, Jun S. Kang, Yejin Choi  
Empirical Methods on Natural Language Processing (EMNLP). 2014. "*

Above work uses the 3 sets of data to find the insights in behavioural patterns while truthful and deceitful typing.

- [Restaurant Reviews](https://www3.cs.stonybrook.edu/~rbanerjee/data/restaurant-reviews.tar.bz2)
- [Gun Control](https://www3.cs.stonybrook.edu/~rbanerjee/data/gun-control.tar.bz2)
- [Gay Marriage](https://www3.cs.stonybrook.edu/~rbanerjee/data/gay-marriage.tar.bz2)

And plots various character level graphs to solidify the relations.
![[Pasted image 20240110144327.png]]
![[Pasted image 20240110144512.png]]


##### My approach 

I need to work with the ReviewMeta Column to preprocess the data for the analysis.

Clean the Data, Remove Null values from the column, Randomising the data, Scattering the data.
Making Dictionary for words and then further for sentences. Finding out various characteristics to map with each other and find relationship around them. 

To Preprocess ReviewMeta Column  Splitting Keystroke data into individual key codes.
Mapping codes to characters and extracting sentences and words.


##### ReviewMeta Column 

The data is stored as a df and every element is separated by ';' 
We have to understand about timeframe, keystroke value, and when the key is up and down accordingly to figure out the dictionary for the time taken to type various words and sentences.