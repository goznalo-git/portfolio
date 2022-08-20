---
layout: page
title: Research
sidebar_link: true
---



> _"The solution often turns out more beautiful than the puzzle"_ - Richard Dawkins


## Current research  🧮


I am pursuing a Ph.D. in Applied Mathematics, in Complex Networks in particular. As such, I am obviously interested in anything related to Graph Theory and Linear Algebra, as well as computer simulations involving graphs (e.g. percolation phenomena). However, Complex Networks is an interdisciplinary field, borrowing ideas from Maths, Physics, Biology, Sociology, Computer Science, etc, so it is quite natural for me finding thought-provoking ideas in unexpected places.

However, within the realm of Complex Networks the focus of my thesis is a bit more specific: understanding the properties and applicability of centrality measures, and perhaps coming up with novel ones, solving problems in those already existing. Centrality measures are actually really interesting: they allow us to rank the nodes of a network based on different definitions of importance. This might seem unrelated to the real world, but they are more influential in our day-to-day life than we think: the Google search engine ranks results based on one of these measures, and its success is what made it the huge company it is nowadays. Part of my research revolves around understanding the behavior of this, so called, PageRank centrality measure.

There are some specially intriguing, rather new variants of networks which I have also laid my eyes upon:
- _Multilayer networks_: these are networks whose interacions fall into different categories, and thus treating those interactions as equal is missing the whole picture. For instance, the connections between a set of individuals are distinct depending of whether individuals are relatives, aquaintances, friends or coworkers.  
- _Higher order networks_: these networks arise from lifting the restriction that interactions be pairwise. Consider, for example, three people writing a paper together. They did not write it "pairwise together", rather, the three of them should be considered part of the same interaction. This opens a vast world of possibilities, however, the technical difficulties encountered along the way are equally vast.

<div style='border-top: 2px dashed lightgrey; width: 100%;'></div>

## Other research interests


### Complex Systems and Non-linear Dynamics 🌀

Complex Systems are systems where the sum is greater than the parts, in the sense that there is some "global behavior" which can't be infered from the local dynamics. A classic example of this is flocks of birds: the individual movement of a bird does not directly affect the movement of the flock (in fact, if a bird dies there is no significant change in the flock behavior). This is completely different from, say, a machine: if a gear fails the outcome will be, at best, deteriorated. 

Complex Networks are another example of Complex Systems; there are many structural properties arising from the collective structure (topology) of the network, such as certain centralities or connectivity. And we can also discover complexity in dynamical systems built on top of networks, such as collections of oscillators whose interactions follow the graph's edges.

Besides networks, there are many systems whose dynamics are governed by non-linear differential equations (which I have always found fascinating), giving rise to interesting phenomena such as oscillations and chaos.


### (Theoretical) Physics ⚛️

One does not forget its beginnings. I still appreciate and enjoy reading about General Relativity (black holes, inflation, etc) and String Theory (in particular, about the AdS/CFT correspondence). I have mixed feelings about the latter, I highly doubt I'll ever go back. Regarding the former, I don't think it is that far apart as of now. In the end, GR is just differential geometry with a physics dress. And, while the discrete nature of graphs seems to be opposite to the infinitesimal nature of differential stuff, weirder connections have been established in both Maths and Physics. In fact I've already seen a couple of interesting papers in that direction.

Another area of Physics which I was really fond of was Classical Mechanics, in particular everything related to analytical mechanics. The good news about this is that it does not lie far from the realm of Complex Systems: usually, all the dynamics invoved are inferred from a mechanical system.


### Machine Learning 🤖

As a coding enthusiast I am _deeply_ interested in Machine and Deep Learning. In fact, I already have some experience with them, thanks to my short-but-fruitful absence from academia. And given the youth of this fields, there is a lot room for exploration, as well as applicability essentially everywhere. Look no further than parenclitic networks, which are ways to convert supervised datasets into graphs, which can then be studied with our beloved network-theoretic tools. 

Another subject which seems to be on the rise these days is that of Graph Neural Networks, a new kind of neural networks whose connections are graph-based rather than uniform. Complex Network theory surely has something to say there.


### Others ♾️

Something else I think is really interesting but perhaps falling far from my reach are Cellular Automata, and in particular the Game of Life. I find the idea of deterministic systems leading to unpredictable behavior fascinating. In the case of the Conway's Game of Life this is the case, using the simplest set of sensible rules one can think of.

<div style='border-top: 2px dashed lightgrey; width: 100%;'></div>


{% comment %}

Stochastic diff. eqs

{% endcomment %}



## Articles 📝

{% include 02-papers.html %}

## Talks 🙉

{% include 02-talks.html %}