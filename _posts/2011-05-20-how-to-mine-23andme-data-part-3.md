---
layout: post
title: 'How to Mine 23andMe Data: Part 3'
date: 2011-05-20 23:53:00.000000000 -07:00
categories:
- 23andMe
- bioinformatics
tags: []
status: publish
type: post
published: true
---
<p><span><b><u>A Note on Choice of Language:</u></b></span><br /><span><b><u><br /></u></b></span><br /><span>I'm going to cheat a little bit. Taking my own advice from my post, "<a href="http://www.nikhilgopal.com/2011/05/bioinformatics-programming-like-experts.html">Bioinformatics Programming Like Experts</a>," I've found it much simpler to answer my next few questions using R. R has a number of complicated statistical tests built-in -- performing them on data is trivial.</span><br /><span><br /></span><br /><span><b><u>What I've Done: Principal Component Analysis:</u></b></span><br /><span><b><u><br /></u></b></span><br /><span>I've performed principal component analysis on my family's 23andMe data. In a nutshell, principal component analysis transforms multi-dimensional data into a number of components which reflect the amount of variance in each dimension. Thus, the first principal component corresponds to the dimension which accounts for most of the variation in a dataset and the last principal component </span><span>corresponds to the dimension which</span><span> </span><span>accounts for the least variation in a dataset. The process of obtaining these numbers is very involved. </span><br /><span><br /></span><br /><span><b><u>What Are We Looking At?:</u></b></span><br /><span><b><u><br /></u></b></span><br /><span>To get to the punchline and share what I've posted in simple terms, we can plot "principal component 1" values against "principal component 2" values and the similar data points will "cluster."</span><br /><span><br /></span>
<div><a href="http://1.bp.blogspot.com/-D7Jxx4rYBzs/TdHjjrgsv8I/AAAAAAAAABw/6sl8bmM5oWA/s1600/PCA.png" imageanchor="1"><span><img border="0" src="{{ site.url }}/assets/PCA.png" /></span></a></div>
<p><span><br /></span><br /><span><br /></span><br /><span>Since I didn't include a legend in the image above, here is who each data point corresponds to (and rough coordinates for folks who can't see color too well):</span></p>
<ul>
<li><span>Red = Me (-700, 1000)</span></li>
<li><span>Purple = Sister (-550, 100)</span></li>
<li><span>Pink = Mom (-1750, -1000)</span></li>
<li><span>Green = Dad (1300, 1000)</span></li>
<li><span>Blue = Grandfather (1700, -1500)</span></li>
</ul>
<div><span><b><u>Brief Explanation of the Image:</u></b></span><br /><span><b><u><br /></u></b></span></div>
<div><span>My sister and I are roughly half of my mother and father. So, our data points straddle between the mom and dad data points. Based on the location of the grandpa data point, its obvious whether grandpa is paternal or maternal.</span></div>
