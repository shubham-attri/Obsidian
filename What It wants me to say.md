
## Introduction

The introduction of the paper provides an overview of the problem of abstraction matching in the context of end-user programming with large language models (LLMs). The authors highlight the challenges faced by non-expert programmers in communicating their intent to LLMs and the need for a structured approach to abstraction matching that can help users develop a mental model of the level of abstraction at which the LLM operates.

The authors then introduce their proposed approach, which uses grounded abstraction matching to map natural language descriptions to specific code constructs. The grounded approach provides a structured way for users to express their intent and can help users develop a mental model of the level of abstraction at which the LLM operates. The authors also highlight the potential benefits of the proposed approach, including improved user confidence and sense of control in using the system.

The introduction concludes by outlining the structure of the paper and what to expect in each section. The authors note that the paper includes a review of related work, a description of the user study that evaluates the proposed approach, and a discussion of the results and their implications for future research. Overall, the introduction provides a clear and concise overview of the problem and the proposed approach, setting the stage for the rest of the paper.

## Background and Related Work

Background: 
End-user programmers are individuals who use programming tools to solve problems in their domain of expertise, but who do not have formal training in computer science. These individuals often struggle with the problem of "abstraction matching," which involves selecting an utterance that will translate into the desired system action. This problem is particularly acute when working with large language models (LLMs), which can generate code from natural language descriptions. The goal of this study is to investigate the problem of abstraction matching in the context of end-user programmers working with LLMs, and to propose a solution that can help bridge the "abstraction gap" between users and the LLM.

Related Work:
The paper reviews related work in two areas: interaction design and machine learning. In the area of interaction design, the paper discusses research on end-user programming, natural language programming, and abstraction matching. The paper notes that while previous research has proposed various solutions to the problem of abstraction matching, none of these solutions has been targeted towards end-user programmers working with LLMs. In the area of machine learning, the paper discusses recent advances in large language models, such as GPT-3, and notes that these models have the potential to revolutionize end-user programming. However, the paper also notes that these models present new challenges for interaction design, particularly in the area of abstraction matching.


## Methodology 

1. Participants: The study recruited 20 participants who were end-user programmers with varying levels of programming experience. Participants were recruited through Amazon Mechanical Turk and were compensated for their participation.

 2. Task: Participants were given a data manipulation task to perform using a prototype system that generated Python code from natural language descriptions. The task was designed to be complex enough to require the use of the code-generating system, but simple enough that participants could complete it within the allotted time.

3. Procedure: Participants were given a brief tutorial on how to use the prototype system, and then were given the task to complete. During the task, participants were encouraged to think aloud and verbalize their thought processes. After completing the task, participants were asked to complete two questionnaires (NASA TLX and System Usability Scale) and participate in a semi-structured interview.

4. Data Collection: The study collected both quantitative and qualitative data. Quantitative data was collected through the questionnaires, which measured the perceived workload and usability of the system. Qualitative data was collected through the think-aloud protocol and the semi-structured interview, which provided insights into participants' thought processes and experiences using the system.

5. Data Analysis: The study used a mixed-methods approach to analyze the data. Quantitative data was analyzed using descriptive statistics, while qualitative data was analyzed using open coding and thematic analysis.

6. Ethical Considerations: The study was approved by the institution's ethics review board, and participants provided informed consent before participating in the study.


## System Design and Implementation 

The paper describes two systems that were built to address the problem of abstraction matching in the context of end-user programming with LLMs. Both systems were implemented as Microsoft Excel spreadsheet add-ins, and shared a common code generation, execution, and output display pipeline. The two systems are described as follows:

1. System I: This system implements grounded abstraction matching, which involves mapping natural language descriptions to specific code constructs. The system uses a set of "grounding rules" to map natural language descriptions to specific code constructs, and provides feedback to the user in the form of highlighted code constructs and explanations of how the natural language description was mapped to the code. The system also provides a "code preview" feature that allows the user to see the generated code before executing it.

2. System II: This system implements an ungrounded yet viable alternative solution to the abstraction matching problem based on previously established guidelines for effectively writing queries for large language models. The system uses a set of "query templates" that provide a structured way for users to express their intent, and generates code based on these templates. The system also provides feedback to the user in the form of highlighted code constructs and explanations of how the query template was mapped to the code.

The paper notes that both systems were designed to be user-friendly and to provide feedback to the user in a way that helps them develop a mental model of the level of abstraction at which the LLM operates. The paper also notes that the systems were evaluated through a user study, which showed that the grounded approach improves users' abilities to recover from system failures, and that users gain greater confidence and sense of control in using the system.

Overall, the system design and implementation discussed in this paper provide a novel solution to the problem of abstraction matching in the context of end-user programming with LLMs, and demonstrate the potential of grounded abstraction matching and query templates as effective approaches to this problem.

## Results

The paper presents the results of a user study that was conducted to evaluate the effectiveness of the two systems described in the paper (System I and System II) in addressing the problem of abstraction matching in the context of end-user programming with LLMs. The study recruited 20 participants who were end-user programmers with varying levels of programming experience. Participants were given a data manipulation task to perform using a prototype system that generated Python code from natural language descriptions. The study collected both quantitative and qualitative data, and the results are presented as follows:

1. Quantitative Results: The study found that participants who used System I (grounded abstraction matching) had significantly higher task completion rates and lower error rates than participants who used System II (query templates). Participants who used System I also reported significantly higher levels of confidence and sense of control in using the system than participants who used System II.

2. Qualitative Results: The study found that participants who used System I were more likely to verbalize their thought processes and engage in problem-solving behaviors than participants who used System II. Participants who used System I also reported that the system was more intuitive and easier to use than System II.

Overall, the results of the study suggest that grounded abstraction matching is a more effective approach to the problem of abstraction matching in the context of end-user programming with LLMs than query templates. The study also suggests that grounded abstraction matching can improve users' abilities to recover from system failures, and that users gain greater confidence and sense of control in using the system. The paper concludes by discussing the implications of these results for the design of future systems that aim to bridge the "abstraction gap" between end-user programmers and LLMs.


## Failure Models 

Additionally, the paper discusses the failure modes that were identified during the user study. The study revealed twelve different types of model failures, which were loosely organized into four themes: technical failures, input failures, output failures, and logic failures. Technical failures included issues such as slow response times and system crashes. Input failures included issues such as ambiguity in the natural language description and incorrect syntax. Output failures included issues such as errors in the output format and missing or extra columns. Logic failures included issues such as incorrect or incomplete code generation. The paper notes that these failure modes highlight the need for robust error handling and feedback mechanisms in systems that generate code from natural language descriptions. The paper also notes that the grounded abstraction matching approach was found to be more effective than an ungrounded approach in helping users recover from system failures.


## Strengths and Weakness

The paper has several strengths, including its novel approach to the problem of abstraction matching in the context of end-user programming with LLMs. The paper's grounded abstraction matching approach provides a structured way for users to express their intent and maps natural language descriptions to specific code constructs, which can help users develop a mental model of the level of abstraction at which the LLM operates. The paper also presents a user study that evaluates the effectiveness of the proposed approach and provides both quantitative and qualitative data to support the findings.

However, the paper also has some limitations. The user study was conducted with a relatively small sample size of 20 participants, which may limit the generalizability of the results. The study also focused on a specific type of data manipulation task and may not be representative of other types of programming tasks. Additionally, the paper does not provide a detailed analysis of the computational complexity of the proposed approach, which may be a concern for large-scale applications.

Overall, the paper provides a valuable contribution to the field of end-user programming with LLMs and demonstrates the potential of grounded abstraction matching as an effective approach to the problem of abstraction matching. However, further research is needed to address the limitations of the study and to explore the scalability and generalizability of the proposed approach.


## Discussion 

One of the key strengths of the proposed approach is its ability to provide users with a structured way to express their intent and map natural language descriptions to specific code constructs. This can help users develop a mental model of the level of abstraction at which the LLM operates and improve their ability to communicate with the system. The authors also note that the grounded abstraction matching approach was found to be more effective than an ungrounded approach in helping users recover from system failures.

However, the authors also acknowledge several limitations of the study, including the small sample size and the focus on a specific type of data manipulation task. The authors suggest that future research should explore the scalability and generalizability of the proposed approach and investigate its effectiveness for other types of programming tasks.

The authors also discuss the implications of their findings for the design of future systems that aim to bridge the "abstraction gap" between end-user programmers and LLMs. They suggest that future systems should incorporate robust error handling and feedback mechanisms to help users recover from system failures and improve their confidence and sense of control in using the system.

Overall, the discussion section provides a thoughtful analysis of the results and their implications for future research. The authors highlight the strengths and limitations of the proposed approach and suggest several areas for future work, which can help guide the development of more effective systems for end-user programming with LLMs.