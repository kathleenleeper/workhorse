---
layout: post
title: "update + iteration 2"
category: labwork
tags: [update, Mash1]
intent: enormous changes in workflow and version control of posts, along with re-starting most scientific lines of inquiry
---
{% include JB/setup %}

##updates

 1. Why use a date-oriented post section when I could be using a single file for a single experiment (e.g. "screening Mash1") with all the various iterations on the same experiment kept in a version control history, and only the final & functional protocol being visible?  So -- switching to a new model in which each post/entry is goal oriented, with the latest work visible; all previous work is available in the previous version files in the github repository.
 2. Branches are git's secret weapon, so I'm going to use them to organize my lines of research. There should be one for: 
   1. cloning Mash1 into a vector
   2. cloning FoxA2
   3. P19 differentiation time course of RNA expression
   4. differentiated P19 activation via acetylcholine, imaged via calcium sensors
  Once a "line" of work is completed, the entire branch can be merged back in to the master lab notebook as a "finished" record.

Net, this should take a much bigger advantage of git and version control generally, reduce time for writing and re-writing protocols, and make the actual process (e.g. methods) easier to read while maintaining the history of each step (e.g. the number of times I've failed).
