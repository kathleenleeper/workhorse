---
layout: post
title: "cloning Mash1 from rat cDNA"
category: labwork
tags: [Mash1]
intent: 
---

{% include JB/setup %}

##intention

Since something (unknown) went horribly wrong with the previous Mash1 cloning set (i.e. all the work from August and September), this is starting from scratch -- or rather, with the initial cloning of the Mash1 gene from rat cDNA. Scratch -ish.

##protocol

All primer info @ the primer page*

####cDNA templates
 * kidney cDNA - tubulin (+) 
 * retinal pigment epithelium ("eye") - Mash1
 * P19 (embryonal rat carcinoma cells) - Mash 1

####PCR mix

| Reagant | uls per 25 ul rxn | x 9 for MM | x 3 for specific primers
| ------------- |------------------------| ---------------------|-----------------------------------|
| 5' primer	| .5 			| - 			| 1.5 |
| 3'		| .5 			| - 			| 1.5 |
| cDNA	| .5 			| - 			| 1.5 |
| dNTPs 	| .5 			| 4.5 		| - |
| 10x buffer | 2.5 		| 22.5 		| - | 
| Taq 	| .3 			| -			| .9 |
| ddH2O 	| 20.1 		| 180		| - |

####Cycle

Run the middle 3 steps x35 times

| temp | time | cycles |
| ------------- |-------------| -------------|
| 94 | 2 mins | - |
| 94 | :30 s | x35 |
| 55 | :30 s | x35 |
| 72 | 1:30 s | x35 |
| 72 | 3 mins | - |


