# Lesson 1: Introduction

## What is LLM and RAG?
### Language Model 
- models that can predicts the next word
### Large Language Model (LLM)
- language models that was trained with large amount of data
- can able to predict the next word, but it can mimics how human communicates
- receives an input (Prompt) and provides an output (Response)

### Retrieval Augmented Generation (RAG)
* Retrieval - search; to provide more context with the LLM; usually these are the knowledge base
* Generation - LLM to create answer based on the given context

*How does RAG Framework works?*
![RAG Framework]['rag-framework.png']
1. user will provide question (prompt)
2. send the prompt to the DB
3. retrieve the documents from the DB
4. documents will provide context to the LLM
5. based on the context, LLM will generate the answer (response) to be provided to the user

## Preparing the environment

