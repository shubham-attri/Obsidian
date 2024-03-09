
Transformer Architecture 
Vision Transformers are used in multimodal models

Using the right size foundational LLM Model, depending on the use case. Optimising the resource utilisation.


More parameters, more memory, can do more work and do more complex works.

Prompt, 
Context Window is the prompt input.
Output is completion
Generation is infraction

Next word prediction
Entity Extraction, A form of information Retrieval

Formatting API Query, making requests, and giving outcome based on outside source.

Generating text with RNN
Attention is all you need, The transformer architecture unlocked the progress we are making, In RNN they utilised a lot of resource as we scaled the context.

Transformers

Each word in the sentence have attention weights to each other trained while training LLM model. There is a attention map. There is also a self attention concept.

Encoder and decoder work in conjunction. 

Tokenizer -> Input -> Embeddings to Encoder and Decoder -> Encoder <-> Decoder -> Ouput

Embedding is a vector space where the tokens are put.
![[Pasted image 20240309081945.png]]

Positional encoding keeps the sequence of the input intact, the self attention weight keeps the context alive.
![[Pasted image 20240309082117.png]]

Multi headed self-attention learns various context for every aspect of language.

Feed forward network 
A vector of logic with various weights which are further put to softmax output where their probabilities are normalised
![[Pasted image 20240309082329.png]]


Translation 
Sequence to sequence task
![[Pasted image 20240309082633.png]]

![[Pasted image 20240309082741.png]]


There is only encoder model only, where they can be used only for classification, like the sentimental analysis.

Decoder only models, include GPT family and many more like them.


Prompt and Prompt Engineering

In context learning : zero shot inference; no example


one shot inference
![[Pasted image 20240309090715.png]]

few shot instance
![[Pasted image 20240309090826.png]]

There is a limit to context window so prompt should be accordingly.

![[Pasted image 20240309091820.png]]

Generative AI Project Lifecycle
![[Pasted image 20240309092353.png]]