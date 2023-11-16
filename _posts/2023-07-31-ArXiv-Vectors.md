---
layout: post
title: "ArXiv Vectors"
tags: [NLP, Embeddings, VDB, Pinecone, Svelte]
thumbnail: /images/xmas22/xmas22.png
description: "Recent small project to search ArXiv for relevant papers"
---

Last summer, while working on a project, I spent ages searching for old papers. At one point, I wished for a magic oracle that I could ask about any paper. Luckily, we have embeddings and vector databases. They turned my wish into reality, helping me create my own oracle. 
<!--more-->

<center>
<img src="/images/arxiv.png" style="max-width:650px"/>
</center>

You can try it yourself [here](https://arxiv.fly.dev/)!

Frankly, there are a lot of CS/ML papers on arXiv. Perhaps too much. There are projects such as arXiv sanity which tries to alleviate this issue, but with arrivial of vector databases and high-quality LLM embeddings, I thought it'd be fun to quickly build a search engine for arXiv papers. Suprisingly it only costs $6 to embed all CS/ML abstracts from arXiv using OpenAI embedding service. I've used pinecone for vector database, Svelte for building the application, and fly.io for hosting.
