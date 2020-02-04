---
layout: post
title: "Presentation: A simple satisficing model"
header-image: /assets/img/news/2020-09-01-icmc-kobe-port.jpg
author: Erlend Dancke Sandorf
image: /assets/img/news/2020-09-01-icmc-kobe-port.jpg
category: [news, presentation]
excerpt: "Danny Campbell presented our preliminary simulation work: A simple satisficing model"
---
## Link to presentation
[A simple satisficing model](/assets/docs/2019-09-01-icmc-kobe-presentation-campbell.pdf)

## Abstract
Economic theory is built on the assumption that people are omniscient utility maximizers. That they have complete information about all available options, knowledge of their preferences and the ability to calculate their expected utility from choosing any one option. While these assumptions are necessary for welfare economics, they may not fully describe how people make choices in real life. Indeed, people routinely make decisions that cannot readily be described by the standard model of rationality. People often lack the memory and cognitive abilities to be perfectly rational, but instead act boundedly rational. The idea of bounded rationality is built on the premise that people rarely have complete information about alternatives nor do they have perfect knowledge of their preferences, but learn about both through (costly) search for information and deliberation.

In some situations people may make a sequence of decisions based on whether or not the utility of the current alternative exceeds some threshold utility. As such, the decision process is one in which each alternative is evaluated sequentially and the first one exceeding the threshold utility is chosen. This decision rule is called satisficing, i.e., choosing the first alternative that is satisfactory. A choice following this type of decision rule may or may not be utility maximizing. If the first satisfactory alternative encountered happens to be the one that gives the highest global utility, then that choice is also utility maximizing. However, any other choice is by definition satisfactory, but not maximizing.

This decision rule has received limited interest from choice modellers. Only a few papers have developed models that can identify satisficing behavior in more traditional discrete choice data, and none are necessarily readily implemented within existing software. In this paper, we develop a simple satisficing model that can be run on standard data that involves choosing the first alternative with utility exceeding some threshold level of utility. This threshold utility is estimated. To test the performance of our model, we run a series of Monte-Carlo simulations. We see how well our model retrieves the true parameters under various assumptions about the level of the threshold utility. Our results show that if the threshold utility is sufficiently low, then the first alternative seen will be chosen. At the other extreme, where the threshold is sufficiently high, then no decision can be made following a satisficing rule, i.e., no alternatives give higher utility than the threshold. This implies that the observed choice must be made following some other decision rule. We discuss implications of our results and ways forward.
