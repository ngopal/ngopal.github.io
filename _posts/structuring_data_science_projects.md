---
layout: post
title: 'Structuring Build for Hypothesis Testing'
date: 2019-04-01 20:12:55.000000000 -08:00
categories: []
tags: []
status: publish
type: post
published: true
---

## First Things First
Decide on an input/output contract. Without this step, we'll never be able to build an actual, reliable system. It probably goes without saying, but I'll write it just in case -- this is definitely NOT how to structure a big data system. I can do another post on that later. 

## How Code Should Be Structured
There are 3 benefits to structuring your code this way:
* Every hypothesis you code up will be reproducible
* Every hypothesis you code up will be measureable (useful later)
* Every hypothesis you code up will be composable into an ensemble

**As long as you have a meta-model that ties everything together, you never actually lose any work.**

`
Code Structure:
-- Parent Directory
---- Data
------- dataset1.csv
------- dataset2.csv
---- Hypotheses
------- Hypothesis1.py
------- Hypothesis2.py
------- Hypothesis3.py
`