---
layout: post
title: "Mash1 primer update"
description: ""
category: labwork
tags: [mash1, update]
---
{% include JB/setup %}

##so

My lab notebook isn't quite up to date. It will be, and I'll update this update according (yay, git!), but first defining the new courses of research is better.

Basically, it doesn't take too much effort to look at the list of notebook entries and see a long, long, bunch of repetitive entries stretching back to August. I've actually run even more than immediately appear, because each "entry" may run three or four git versions back. 

Anyway, since [this post]({% post_url 2014-10-15-cloning-mash1-from-rat-cdna %}), I've been working on cloning Mash1 from cDNA, cleaning it up, inserting it into a vector, and growing it up in e. coli. The log shows how difficult and excruciating each step has done. For naught, it turns out, because [last week]({ % post_url 2014-11-06-testing-mash1-primers %}) John and I had the idea to finally test <i>what</i>, exactly, my Mash1 primers were doing. And. Well. 

![testing the Mash1 insert]({{ site.url }}/Data/11-06-14_mash1-screen.png) 

For those of you not compulsively looking at these gels like I am, or who aren't as familiar, what we <i>should</i> have seen here is a signal in lane 1, the 100 bp ladder. Lane 2, the colony screen, was...irrelevant. Then, the sticky stuff. 3' -5' primers should have a signal. Either primer by itself is, (in theory), a negative control, and the lanes should be empty of any signal at all. The appearance of a beautifully bright ~700bp chunk of DNA in lane 5 is an indication that whatever "Mash1" insert I've been working with is not, in fact, Mash1, but instead some horrid mutant DNA that's amplified by the 5' alone. And that is very bad news. 

###what it means

 1.  most, if not all, of the work and/or accomplishments related to this gene were doomed from the get go. Anything tagged mash1? Useless.
 2. I need new primers. We'll see if we can do better this time around. The rest of my entries will be up for posterity, and so I can feel good about the amount of time I spent, if nothing else, but the real work won't start again for at least a week.
