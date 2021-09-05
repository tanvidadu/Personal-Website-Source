---
title: "Sarcasm Detection using Context Separators in Online Discourse"
date: 2020-07-09
tags: ["sarcasm detection" , "natural language processing", "social media analysis"]
series: ["Figurative Language Processing@ACL 2020"]
---

Sarcasm is an intricate form of speech, where meaning is conveyed implicitly. Being a convoluted form of expression, detecting sarcasm is an assiduous problem. The difficulty in recognition of sarcasm has many pitfalls, including misunderstandings in everyday communications, which leads us to an increasing focus on automated sarcasm detection. In the second edition of the Figurative Language Processing (FigLang 2020) workshop, the shared task of sarcasm detection released two datasets, containing responses along with their context sampled from Twitter and Reddit. In this work, we use RoBERTa large to detect sarcasm in both the datasets. We further assert the importance of context in improving the performance of contextual word embedding based models by using three different types of inputs-Response-only, Context-Response, and Context-Response (Separated). We show that our proposed architecture performs competitively for both the datasets. We also show that the addition of a separation token between context and target response results in an improvement of 5.13% in the F1-score in the Reddit dataset

