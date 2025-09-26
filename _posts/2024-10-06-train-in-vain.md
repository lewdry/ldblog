---
layout: post
title: "Train in Vain: Thoughts on Retrieval-Augmented Generation"
date: 2024-10-06
---

I recently read this article on [‘Applied AI Software Engineering’](https://www.rossmcnairn.com/p/applied-ai-software-engineering) by Wordsmith CEO Ross McNairn which I found interesting. I thought I’d share here. 

It’s a code-along guide on building a Retrieval Augmented Generation (RAG) pipeline for AI large language models. I’ve been a bit cynical about AI hype over the last 18 months but I thought I’d give it a go.

Retrieval Augmented Generation is a method to give context to a large language model to build domain expertise and reduce hallucinations. If you want to train an AI model to ‘understand’ a subject, and:
* You don’t have millions of dollars of compute to build your own model; or
* You want complete control over the data you do and don’t expose to AI providers,
then you’re likely going to use some form of Retrieval Augmented Generation (RAG) to do that training.

So I followed the guide. Two hours and **$9** in OpenAI API credits later, I had a working RAG pipeline trained on my own dataset and answering questions that an untrained AI couldn’t. For the data, I used things I’ve written over the years like blogs, notes and my (now ancient) master’s thesis.

It was impressive to see correct answers coming from my data. In my case I was basically paying for an AI to repeat things I already knew, at $0.25 to $0.50 per query. Not useful, but a fun proof of concept. I do see the potential value in scaling this technique to a business context or a particular domain. The guide and the readme are easy to follow, honestly, you could do it in half the time, and yes, you can limit the API cost if you’re worried about getting a surprise bill.

The article touches on the value of ‘data as a moat’ and training AI models as a competitive advantage. For me, I’m left thinking about access to data and the ethics of using it. When I set up the RAG pipeline, I had to decide what data I’d train it on. Other people’s work? Definitely not. Emails I’ve sent? Possibly okay but a bit iffy depending on recipient and content. Safer to leave them out.

If you’re training AI to solve a business problem, there’s governance work to do upfront. What data do you actually have? What rights do you have to use it? How accurate and complete is it? Is solving the problem something you can ethically outsource to AI?

The article has some great insights about RAG and LLMs more broadly. If you’re interested in AI or you’ve been seeing the acronym RAG and have been meaning to find out more, it’s worth a read, even if you don’t build anything.
