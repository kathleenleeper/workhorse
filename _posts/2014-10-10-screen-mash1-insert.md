---
layout: post
title: "screen Mash1 insert"
category: labwork
tags: [iteration-1, Mash1, molecular bio]
intent: 
---
{% include JB/setup %}

##intention

Re-screen the colonies. Because there was no signal in the Mash 5' - SV40 3' lane, it indicates either (a) there wasn't enough primer in the Mash 5' tube or, more ominously, (b) the gene the 3' primer is cloning in the vector (eg the SV40- Mash 3') is actually some strange hybrid mix from the initial cloning of Mash1.

So: 
 1. Make new primer stock. 
 2. Run a miniprep on the bacteria for a more consistent genome amount to run PCR on.
 3. Run PCR with more control conditions (specifically a -/Mash 3' negative control)  

##protocol

###new primer stock

 * SV40 3' : 50 uls of 20 um stock, 50 uls H20
 * Mash 3' : 10 uls 10 mM stock, 90 uls H20
 * Mash 3' : 10 uls 10 mM stock, 90 uls H20

###miniprep

Miniprep run with a Promega Miniprep kit using centrifugation; protocol available at [the Promega page](http://www.promega.com/products/dna-and-rna-purification/plasmid-purification/pureyield-plasmid-miniprep-system/) 

####nanodrop concentrations (approx.)

C1: 35 ng/ul
C3: 30 ng/ul

###PCR 

####primers

| Primer Pair | Expected Band Length | label/intent |
| ------------- | ------------| ----|
| CMV 5', SV40 3' | 1400 | + |
| CMV 5', Mash1 3'  &nbsp; &nbsp;| 700 | A |
| Mash 5', SV40 3' | 1400 | B |
| Mash 5', Mash 3' | 700 | C |
| -, Mash 3' | - | - |

For two screenings in duplicate, 4 reactions of each primer pair

####PCR mix 

| Reagant | uls per rxn | x 5 rxns | neg control |
| ------------- |----------------------| --------------------| -----|
| 5' primer | .5 | 2.5 | n/a |
| 3' | .5 | 2.5 | .5 |
| dNTPs | .5 | 2.5 | no change |
| 10x DreamTaq buffer &nbsp; &nbsp; &nbsp; | 2.5 | 12.5 | -  |
| DreamTaq | .3 | 1.5 | - |
| template | .5 | 2.5 |  - |
| ddH2O | 20.2 | 101 | 20.7*5 = 103.5 |


##results &/or notes
*Nothing yet!*
