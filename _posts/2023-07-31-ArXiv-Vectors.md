---
layout: post
title: "ArXiv Vectors"
tags: [NLP, Embeddings, VDB, Pinecone, Svelte]
thumbnail: /images/xmas22/xmas22.png
description: "Recent small project to search ArXiv for relevant papers"
---

Last summer, I was working on a project and spent significant amount of time searching for relevant previous papers. Therefore, I built this framework that uses LLM embeddings and vector databases to find the most relevant papers.

<!--more-->

<center>
<img src="/images/arxiv.png" style="max-width:650px"/>
[Demo](https://arxiv.fly.dev/)
</center>


Frankly, there are a lot of CS/ML papers on arXiv. Perhaps too much. There are projects such as arXiv sanity which tries to alleviate this issue, but with arrivial of vector databases and high-quality LLM embeddings, I thought it'd be fun to quickly build a search engine for arXiv papers. Suprisingly it only costs $6 to embed all CS/ML abstracts from arXiv using OpenAI embedding service. I've used pinecone for vector database, Svelte for building the application, and fly.io for hosting.