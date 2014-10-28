---
layout: post
title: "screening 10/23/14 colonies"
category: labwork
tags: [mash1]
intent: 
---
{% include JB/setup %}

##intention

Screen 4 of the colonies from the [previous transformation]({ % post_url 2014-10-23-mash1-and-new-vector.md %}) for insert, using CMV 5' - SV40 3' primers

##protocol

Running 4 colonies - 

###master mix

| Reagant | uls per 25 ul rxn | x 6 rxns |
| ------------- |-------------------------| ----------------|
| 5' primer | .5 | 3 |
| 3' | .5 | 3 |
| dNTPs | .5 | 3 |
| 10x DreamTaq buffer | 2.5 | 15 |
| DreamTaq | .3 | 1.8 |
| ddH2O | 20.7 | 124.2 |

###cycle

Run the middle 3 steps x25 times

| temp | time | cycle # |
| ------------- |-------------| -------------|
| 94 | 5 mins | - |
| 94 | :30 s | x25 |
| 55 | :30 s | x25 |
| 72 | 30 s | x25 |
| 72 | 5 mins | - |
| 4 | &#8734; | - |


##results &/or notes
All products are ~700 bp, so the insert isn't in at all.
