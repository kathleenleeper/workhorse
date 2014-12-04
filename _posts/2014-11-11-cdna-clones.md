---
layout: post
title: "cDNA clones"
category: labwork
tags: [mash1, cloning]
intent: clone Mash1 with negative primer controls
---
{% include JB/setup %}

##intention

Clone Mash1 out of cDNA, but run a negative control with just 5' and just 3' reactions as well.

##protocol


| reagant             | per 25 &#956; l  rxn | x2, 5'-3'            | x2, 3' | x2, 5' |
|---------------------|-------------------|----------------------|--------|--------|
| 5'                  | .5                | 1                    | 1      |  -     |
| 3'                  | .5                | 1                    |  -     | 1      |
| RPE or P19 cDNA     | .5                | add directly to tube |  add directly  |  add directly   |
| dNTPs               | .5                | 1                    | 1      | 1      |
| 10x DreamTaq buffer | 2.5               | 5                    | 5      | 5      |
| DreamTaq            | .3                | .6                   | .6     | .6     |
| ddH20               | -                 | 40.4                 |        | 41.4   |

##cycle

| temp | time    |     |
|------|---------|-----|
| 94   | 5 mins  |     |
| 94   | 30 s    | x35 |
| 55   | 30 s    | x35 |
| 72   | 30 s    | x35 |
| 72   | 3 mins  |     |
| 4    | &infin; |     |

##results

Honestly, I have no idea why this is completely blank. I ran a second PCR the exact same way, with the same results. Probably a result of my pipetting setup, which requires pipetting .5&#956;ls of cDNA into each tube and has no duplicates. 

![1% agarose gel]({{ site.url }}/Data/11-12-14_cDNA-cloning_annotated.png)





