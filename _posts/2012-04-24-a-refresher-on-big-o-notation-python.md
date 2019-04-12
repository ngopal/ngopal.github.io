---
layout: post
title: A Refresher on "Big O" Notation (Python)
date: 2012-04-24 15:22:00.000000000 -07:00
categories:
- code optimization
- python
tags: []
status: publish
type: post
published: true
---
<p><span>It's well known that asymptotic notation is used to convey the speed and efficiency of code blocks in computer programs. I haven't used them very much while working with Python, so I needed to refresh my memory before trying to use this great tool.</span><br /><span><br /></span><br /><b><span>Cardinal Rule: Focus primarily the largest value in the equation of time complexity. All other factors in the time complexity equation are essentially trumped.</span></b><br /><span><br /></span><br /><span>O(n^4+n^2+n^3+nm+100) ~= O(n^4)</span><br /><span><i>Update: assuming m is linear.</i></span><br /><span><br /></span><br /><b><u><span>Trump Rules for Time Complexity:</span></u></b></p>
<ul>
<li><span>Notes</span></li>
<ul>
<li><span>Remember that we care most about the upper bound and are not so concerned with the lower (in general)</span></li>
<li><span>The smaller the upper bound number the better (and consequently, faster)</span></li>
</ul>
<li><span>The Ladder</span></li>
<ul>
<li><span>Constants are less than logarithms</span></li>
<li><span>Logarithms are less than polynomials</span></li>
<li><span>Polynomials are less than exponentials</span></li>
<li><span>Exponentials are less than factorials</span></li>
</ul>
</ul>
<div>
<span><br /></span></div>
<div>
<div>
<u><b><span>Notation and Hierarchy (Smaller Is Better):</span></b></u></div>
<div>
<span><span><br /></span></span></div>
<div>
<span><span>Constant Θ</span>(1)</span></div>
<div>
<span><span>Logarithmic Θ</span>(lg n) </span></div>
<div>
<span><span>Linear Θ</span>(n) </span></div>
<div>
<span><span>Loglinear Θ</span>(n lg n) </span></div>
<div>
<span><span>QuadraticΘ</span>(n^<span>2</span>) </span></div>
<div>
<span><span>Cubic Θ</span>(n^<span>3</span>) </span></div>
<div>
<span>Polynomial O(n^<span>k</span>) </span></div>
<div>
<span><span>Exponential O</span>(k^<span>n</span>) </span></div>
<div>
<span><span>Factorial Θ</span>(n!)</span></div>
<div>
<span><br /></span></div>
<div>
<b><u><span>Quick Examples:</span></u></b></div>
<div>
<span><br /></span></div>
<div>
<span>[i for i in list] <b>{linear}</b></span></div>
<div>
<span><i>Functions that generally operate on lists or generators (sum, map, filter, reduce, min, max, etc) tend to be linear in time complexity</i></span></div>
<div>
<span><br /></span></div>
<div>
<span>[i+k for i in list for k in list] <b>{quadratic}</b></span></div>
<div>
<span>[i+k for i in list1 for k in list2] <b>O(list1*list2) {quadratic I think, since it's linear*linear}</b></span></div>
<div>
<span><i>Add 1 to the exponent value for each nested loop. For example. [j+i+k+n for j in list1 for i in list1 for k in list1 for n in list1] would have a time complexity of O(n^4)</i></span></div>
<div>
<span><br /></span></div>
<div>
<span>Note: Some programmers reduce quadratic time complexity a bit when using nested loops with sorted lists by ensuring that calculations aren't performed more than once. Consequently, that code block runs faster and faster and less and less has to be evaluated through each iteration of the loop. For example:</span></div>
<div>
<span><br /></span></div>
<div>
<span>list1 = [i for i in range(10)]</span></div>
<div>
<span>size = len(list1)</span></div>
<div>
<span>number=100</span></div>
<div>
<span>for n in range(size-1):</span></div>
<div>
<span>    for k in range(n+1, size):</span></div>
<div>
<span>        print number*(n+k)</span></div>
<div>
<span><br /></span></div>
<div>
</div>
</div>
