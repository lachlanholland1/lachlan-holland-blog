---
layout: post
comments: true
title:  "Multi-stage Recommender System"
excerpt: "A multi-stage recommendation system built using PyTorch for the H&M Personalized Fashion Recommendations Kaggle competition"
date:   2023-07-02 19:42:35 +1000
---
<a href="https://github.com/lachlanholland1/multi-stage-recommender">View the code here</a>

Over a couple of weeks Nav Pathak and I developed a small multi-stage recommendation system built using PyTorch trained on data sourced from the <a href="https://www.kaggle.com/c/h-and-m-personalized-fashion-recommendations">H&M Personalized Fashion Recommendations Kaggle competition</a>. Using collaborative filtering, the system predicts the likelihood of a customer purchasing an item. Two neural networks are trained to separately encode customer and item embeddings such that the dot product of the output vectors is greater if the customer had purchased that item. Inspiration was taken from the series of blog post by Adrien Biarnes titled: <a href="https://medium.com/mlearning-ai/building-a-multi-stage-recommendation-system-part-1-1-95961ccf3dd8">Building a Multi-Stage Recommendation System</a>.
