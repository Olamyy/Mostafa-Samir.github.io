---
layout: post
categories: [python,machine-learning]
title: "The Computational Learning Theory"
image: /assets/images/locally-weighted-regression.png 
twitter_text: "An introduction to the computational learning theory"
tags: [maths, computer science, comp learn theory]
---


__Hello__, 

You should really read this to the end if:

1. You're just starting off with statistical/theoretical computational learning.
2. You're familiar with machine learning but willing to take your skills up notch.
3. You are a Machine Learning student attempting to delve into the theory of ML.


---------------------------------------------------------------------------------------------------------------------------------------

Notes:
1. This is in no way targeted at complete beginners to machine learning.You'd be better off by starting with a much more hands on 
tutorial if you're new to the field.
2. This article is a little maths heavy.I tried to make it as simple as possible but it's probably best to have some skills in calculus to be able to follow along with it.
 

---------------------------------------------------------------------------------------------------------------------------------------

Traditionally software has been built by loading a set of rules accompanied with data into a system with
the expected output as `answers` to a question.<sup>1</sup>

![Traditional Systems.](/assets/images/trad_sys.png) 

The introduction of machine learning methods introduced a search based, rule finding approach to learning.
Machine Learning systems are loaded with data accompanied by answers with the expected output as `rules`<sup>2</sup> instead of `answers` as 
produced by the traditional systems.

![ML Systems.](/assets/images/ml_sys.png)

A machine learning system generates a learning model<sup>*</sup>(rule) from the combination of the data and answer.

This model comprises of:

a.The learning input

b.The learnt output

c.A data generation model

d.A measure of success

