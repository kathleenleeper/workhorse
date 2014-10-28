---
layout: post
title: "cutting new vector"
category: labwork
tags: [mash1, restriction digest, vector]
intent: make stock of clean digested vector
---
{% include JB/setup %}

##intention

Since neither one of the past ligation & transformation attempts with the new(ish) Mash1 insert grew, it's possible it's a vector issue. So re-cutting and re-phosphatas-ing the eGFPN1 vector.

##protocol

###restriction digest of eGFPN1

vector concentration: 239 ng/ &#956; ls
desired: 1 &#956;g
use 4.18 &#956; ls

* Mix and then spin down
  * 4.18 &#956; l vector
  * 2 &#956; l buffer (FD buffer, Promega)
  * 1 &#956;l enzyme (FD EcoRI) 
  * 12.82 &#956;l H<sub>2</sub>0 [for a total volume of 20 &956;ls]
 * incubate @ 37&deg; C for 1 hr

###Purify product w/ Quiaquick 
20 uls of digest; use [QIAquick PCR Extraction Kit](http://www.qiagen.com/products/catalog/sample-technologies/dna-sample-technologies/dna-cleanup/qiaquick-pcr-purification-kit); elute with 30 uls SUPW

###phosphatase treatment

1. combine
  * 1 &#956; l TSAP
  * 3 &#956; ls Multicore 10x buffer
  * 30 &#956; ls digested and purified vector (e.g. all)
 2. 15 mins, 37&deg;C
   * phosphate removal step
 3. 15 mins, 75&deg;C
   * inactivation of enzyme


