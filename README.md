# Semantic-Search-With-LLM

## Using semantic search with LLM
<img width="462" alt="image" src="https://github.com/KhushMody/Semantic-Search-With-LLM/assets/50273729/b9b16705-776d-4f2b-85ba-7bf519d3df15">

Here given a database we first find the relevant article using semantic search and give that article as context to our large language model(LLM) with the query this ensures that the answer provided by the LLM is factually correct and if there is no such document present it returns an answering saying "no answers found"


This repository has 2 files:
* Semantic search with LLM
* Semantic search from scratch

## Semantic search with LLM
### This file has the following things
* Keyword search
* Semantic Search
* Comparision between keyword and semantic search
* Reranking of search results
* Using a search system with LLM

### Database
* Wikipedia articles

### TechStack
* cohere api
* weaviate
* python

## Semantic Search From Scratch
This file creates its own vector database using Annoy and performs semantic search for the retrieved database


