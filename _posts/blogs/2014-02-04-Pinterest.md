---
layout: article
title: "What attracts attention on Pinterest?"
description: "Blog post about Pinterest paper in CSCW"
modified: 2014-02-04
category: blog
tags: [Pinterest, social network]
comments: true  
image:
  teaser: pinterest.jpg
  credit: https://www.flickr.com/photos/mkhmarketing/
---

As the third-largest English-language social network behind Facebook and Twitter, Pinterest has surpassed Reddit, Digg, and others to become the world's most popular social curation site. Despite the popularity of Pinterest, there has been little scientific work examining the strategies of successful Pinterest users. We have been studying Pinterest for the past year and a half, with one paper appearing in [CHI 2013](http://dl.acm.org/citation.cfm?id=2481336) and another one to be presented at [CSCW 2014](http://www-users.cs.umn.edu/~schang/papers/cscw14.pdf). This post summarizes the highlights of the CSCW paper.

In this work we studied the types of content and behavior that attract attention - namely repins and follows - in Pinterest. We looked at a number of factors, including the diversity of pinned content, homophily (the tendency for similar people to have more social connections), and gender.

Using our dataset of thousands of Pinterest users and millions of pins, we identified a number of factors that correlated with the number of followers a user had: the most powerful correlates were obvious factors like the amount of content the user pinned and the number of other users the user followed. However, topical diversity also played a role: **the more topically diverse one's set of pins, the more followers one tends to have, but only up to a certain point.** So, in other words, the Pinterest user who pins content in many categories - e.g. food/drink, DIY, home decor, travel, etc. - tends to have more followers than the Pinterest user who sticks to a single or small number of categories. However, when the diversity of categories gets too great, the number of followers tends to go down. The figure below shows this relationship in more detail.

![diversity]({{ site.url }}/images/blog_diversity.jpg)

The notion of [homophily](http://en.wikipedia.org/wiki/Homophily) is well known in social science: people tend to make connections with those who are similar to them. We studied how homophily of topic interests plays a role in repinning and following behavior on Pinterest. **We found that while people tend to repin from those who share similar interests, this effect is smaller when it comes to following users.** So, for instance, while a Pinterest user might follow their friends with different interests, they tend to repin less from these friends.

Finally, our findings related to gender were surprising: the content posted by men and women was not as different as one might expect. The most significant divergence across genders was that **male users tended to concentrate their pins on certain topics (i.e. specialize), whereas female users tended to pin more diverse content.** When it comes to individual topics, pins from both genders followed relatively similar distributions. As seen in the figure below, the most common pin topic was "Food/Drink" for both genders. Along the same lines, men and women both pinned content in the “Design” and "Home Decor" categories quite often. While men pinned "stereotypically male" topics like "Cars/Motorcyles" and "Sports" more than women, these topics still were not popular among men, representing only a small percentage of their pins. For example, a pin by a male user is much more likely to be about home decor than sports.
![distribution]({{ site.url }}/images/blog_pin.jpg)
