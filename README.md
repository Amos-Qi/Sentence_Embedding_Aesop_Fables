# Sentence_Embedding_Aesop_Fables


## Introduction:
This demo delves into the intersection of NLP and classic literary. The goal is to leverage the power of modern machine learning techniques to analyze the linguistic structure of Aesop's Fables and generate the summaries of these influencing stories.

Here's a breakdown of this demo:
### Part 1: Sentence Embedding Generation
* Utilizing **Sentence-BERT**, a state-of-the-art model for generating sentence embeddings that capture deep semantic meanings, we'll transform each sentence from `Aesop_Fables.txt` into a high-dimensional vector space.

### Part 2: Semantic Similarity Computation
* By calculating **cosine similarities** between sentence embeddings, we'll identify and rank the sentences in Aesop's Fables that are semantically close to the given phrase.

### Part 3: 🌟 Fable Summarization:
* In the realm of storytelling, fables are known for their brevity and moral lessons. However, even these concise tales can benefit from summarization, especially when looking to quickly grasp the underlying message or for educational purposes. Harnessing the insights gained from our analysis, we'll attempt to summarize each fable in 3 sentences using **K-Means Clustering**.
