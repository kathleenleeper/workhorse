---
layout: post
title: "screening Mash1 colonies"
category: labwork
tags: [Mash1, molecular bio]
intent: screen the newly cultured e.coli for insert direction
---
{% include JB/setup %}

##intention

Screening the grown colonies (so #1 and #3) from yesterday for insert

##protocol

Run a PCR with the following conditions:

Run both colonies (#1 and #3)  in duplicate , so 4 reactions per primer pair each (except only two positive control reactions, one for each colony).

###primers

| Primer Pair | Expected Band Length |
| ------------- | ------------|
| CMV 5', Mash 3' | 700 |
| Mash 5', SV40 4' | 1400     |
| CMV 5', SV40 3' | 1400 |

###master mix

| Reagant | uls per 25 ul rxn |
| ------------- |-------------|
| 5' primer | .5 |
| 3' | .5 |
| dNTPs | .5 |
| 10x DreamTaq buffer | 2.5 |
| DreamTaq | .3 |
| ddH2O | 20.7 |


###cycle

Run the middle 3 steps x25 times

| temp | time | cycle # |
| ------------- |-------------| -------------|
| 94 | 5 mins | - |
| 94 | :30 s | x25 |
| 55 | :30 s | x25 |
| 72 | 30 s | x25 |
| 72 | 5 mins | - |
| 4 | infinite | - |

##results &/or notes

*Nothing yet!*
