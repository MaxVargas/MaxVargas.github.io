---
layout: post
title:  "Another one~!~"
date:   2024-09-03 13:47:10 -0800
categories: jekyll update
---


Been a while! Guess I should update what I've been up to after not touching this thing for a while. After I graduated, I went on a 3 month trip to just go around and take pictures of things. But I imagine you might be here for something else. After those months, I've been working full time doing some pretty neat AI + ML stuff. I've also been enjoying spending some of my own time to learn better software practices. Currently focusing on Rust and Haskell (HAHA.. to help with Rust.. but also just because I want to).

I don't have much of a structured plan for this place (I'd want to reorganize stuff first), but most of the stuff I'll add on here will be what I've been learning or doing on the side.


Anyways, quick points on my research are below, will only write a little here but . Largely in LLMs (and some vision) consisting of:

- Studying the embedding spaces of deep neural networks (DNNs) and how we can extract interpretable, explainable, and high-level information about our data. Essentially it's about trying to unpack data that gets embedded by foundation models. In particular, I've been looking at different dimensionality reduction techniques to see what they tell us about the features of our data. A pretty big application is that we can use this to understand variance between human writing and AI-generated writing at a distributional level, but this applies to the image domain too (real images vs AI-generated images). There's also connections to understanding manifolds and other geometric objects associated to data such as raw text. You can find the preprint [by clicking here](https://www.arxiv.org/abs/2408.10437).

- Other stuff involving RAG-related tasks, in particular been looking at handling knowledge graph modalities. This has got a flavor of agentic AI and those other buzzwords we've been hearing about recently. Lots of playing with different models and the rest of the AI stack.