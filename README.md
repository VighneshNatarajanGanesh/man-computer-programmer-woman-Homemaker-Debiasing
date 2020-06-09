# man-computer-programmer-woman-Homemaker-Debiasing

#### Is Man: Computer Programmer same as Woman: Homemaker?

Well the word vectors trained on large corpura says so (A word vector is a one dimentional matrix of numbers that is used by ML algorithms to understand what a word represents). But given how ML models are used nowadays to make many important decisions that affect the lives of so may people we cannot let this happen. This is where debiasing word vectors come in. 

This problem was talked by a paper: [link to pdf](https://papers.nips.cc/paper/6228-man-is-to-computer-programmer-as-woman-is-to-homemaker-debiasing-word-embeddings.pdf)

## Problem Definition:

* Section 1 deals with finding similarity of words. To find similarity between words we use cosine similarity on their word vectors. 
* Section 2 deals with the task of word anology
* Section 3 deals with debiasing word vectors.

This notebook is deriver from the MOOC course [Sequence Models](https://www.coursera.org/learn/nlp-sequence-models) by deeplearning.ai
