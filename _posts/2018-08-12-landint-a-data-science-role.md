---
layout: post
title: 'Make Your Jump!'
date: 2018-02-22 20:12:55.000000000 -08:00
categories: []
tags: []
status: publish
type: post
published: true
---
### Why I’m Writing This
Now that I’ve been working as a data scientist for over a year, I’ve been asked a few times to speak about my experiences, specifically about my journey from academic researcher to data scientist. I hope you read this and perhaps find inspiration to make the jump yourself, and preferably you can avoid the same traps that I fell into on the way. Although I share my experiences as an interviewer later in the post, I’m sharing my overall experience over the years, and do not cover company-specific details.

### Who This Is For
Academics contemplating making the switch to industry, and anyone interested in learning about landing their first data science role in general.

### Why I Left Academia
I’ll keep this section brief. I actually enjoyed my life as an academic, but in short, I felt I could be making more meaningful contributions outside of the ivory tower.

In a sense, academia can also be viewed through the lens of a business model, although many professors don’t look at it this way. Papers → Grants → Overhead for university. Institutions that provide grants also need to "invest" funds among a list of potential researchers they think will eventually yield substantial positive scientific returns (i.e. scientific breakthroughs). One of the primary ways these grant institutions seem to evaluate applicants is through their expertise in the research field, and that is typically demonstrated via past grants and research publications. This is why academic departments use publication records (and ultimately grant records) to assess tenure.

I've previously discussed the pitfalls of focusing too heavily on short-term productivity metrics like paper publications. Even Nobel laureates have spoken out against the use of impact factors.

Combine all of this with decreased year-over-year funding for the sciences for three political administrations in a row, and we have an environment where it behooves researchers to seek new routes.

There seem to be endless articles about this topic, and I am actually not writing this blog post to highlight that in particular. 

This post, actually, is about data science :-)

### What I Enjoy About Working For A Company
I can work on projects that are unique to the company I’m working at -- unique data, unique resources, unique problems to solve, unique opportunities. Although I personally weigh this aspect quite heavily when I’m searching for a new role, I realize that not everyone shares the same interest or prioritization.

Many of the questions I’ve received about being a data scientist have to do in some form or another with compensation. And yes, compensation can be leaps and bounds better than a postdoc salary. A ballpark data scientist salary range would be 2-3x a postdoc salary, not including signing bonuses, stock, retirement matching, and additional benefits (transportation, discounts, etc.), all of which factor into overall compensation. There are plenty of resources that collate this information -- glassdoor.com is a reasonable place to start.

### My Skills and Experience Prior To Switching
Another reason I’m writing this is because I’ve seen a few articles about how to “get into” data science, but those seem to be intended for professionals who work with data (software engineers, data engineers, data analysts, etc). This post will likely be most helpful to those who are in the same situation I was in, where I had the majority of the skills and knowledge required for the role, but I was missing a couple of key attributes.

When I made the switch from Illumina to graduate school, I essentially traded Python2 for R, Javascript, and Java. Since most of my apps were biological data visualizations, I made thorough use of D3.js -- so much so I did a video set of O’Reilly, helping those with a background in Python learn how to use Javascript and D3.js.
-A very quick note on writing technical books or programs: I’ve done two of these now, and I can say that they obsolesce very quickly! If I do more technical books or programs in the future, they will certainly be focused on first principles, business cases, and methodology, rather than technology.

ML/AI/Stats are skills I learned through classes over the years, from high school through graduate school. I’ve also competed in a handful of machine learning bake-offs, and have had the privilege of working with ML/AI researchers who collectively have taught me a quite a bit!

Naturally, I also had a background in biology, which isn’t so useful for general data science so I won’t harp too much on it. Suffice it to say, there are some very interesting computer applications/methodologies in the field of biomedicine, so coding on those projects helped me learn and grow my software engineering skills.

### What Helped Me Along The Way
Insight Data Science:
If you fit the same profile I did prior to landing a data science role, then perhaps like me, it could be worth investing in SQL skills, and knowledge of business models. A book I found to be enormously helpful for the “business side” was Lean Analytics. I feel this book provides the scaffolding/roadmap necessary to “speak the language,” if you will (KPIs, SaaS, CLV, churn, etc.). This might seem unnecessary, but I assure you it is vital. Put yourself in the shoes of a hiring manager or employer -- if you ran a business, would you want to hire someone with little to no business training to run an essential part of your company?

As far a SQL goes, it seems every business I’ve ever interacted with uses SQL in some capacity. And as a data scientist, you need to be able to retrieve, format, transform, and clean data. Bioinformatics may be somewhat unique in that it is an NLP-heavy domain, working primarily with text data, sometimes stored as inconsistent flat files, and because of this, SQL is not a skill that I was accustomed to using.

There are obviously more data science incubators/camps than just Insight Data Science and Thinkful Inc, but I’m not as experienced with the others. Off of the top of my head, in the Seattle area, we also have Galvanize, General Assembly, and Metis. If you are considering one of these, please be sure you ask about their business model and how they make money, and whether you are required to “find a job” through them. One of the reasons I like Insight is because they work like recruiters (a bit more about that below) and they seem to value developing and supporting a strong data science community more than they do making a profit.

Recruiters (mutually incentivized to find you a good fit)
If you are looking for a data science role, it helps to work with a recruiter. I actually built quite a decent relationship with a couple of recruiters, each of whom provided great advice and support along the way. Anecdotally, the incentivization structure seems quite healthy -- recruiters get paid if they place you into a role you love, perform well in, and stay in for a guaranteed period of time. The company you are hired at makes the recruiting fee it paid back multi-fold in productivity and efficiency. The downside is that you will find a large number of recruiters who will try to fit you into a role you are not suitable for, at borderline harassment levels.

Note: Since some people have asked, one of the recruiters I had a wonderful experience with was Richard Marion from CyberCoders.

Another Note: I registered for a few recruiting services, such as Hired, TheLadders, and LinkedIn Premium. I didn’t have much luck with Hired or TheLadders, but LinkedIn Premium seemed to do reasonably well at connecting me with the right recruiters. More importantly than that, LinkedIn Premium provides some interesting information on which roles I may be a particularly good fit for and why. Personally, I think this is worth the value of the free trial :-D

### Practice, Practice, Practice! Especially To Perform Under Pressure!
Think about a concept you have read about -- one that is fundamental, and you think you might know like the back of your hand. If you need ideas, try the central limit theorem, or stochastic gradient descent. Got one? Good. Now explain this concept succinctly, but accurately, in less than 60 seconds. If you are reading this on your phone, or in the office, and you feel self-conscious, whisper it under your breath. I think you’ll find it’s more difficult than you thought.
Here is the interesting part: You very likely actually do know this concept. Whether it’s over the phone, Skype, or in-person, perhaps you just need some practice explaining concepts well!

Since my own background is in a technical field like biomedical informatics, as I started preparing for interviews, most of my time went into reviewing and practicing technical concepts. However, because I have a quantitative PhD, this was actually not what I needed to practice, and in hindsight, may have been more of a crutch. The two skills I should have been investing in were SQL skills and product sense.

Note: This reminds me of an excerpt from the book, “Bayes Theorem: the theory that wouldn’t die.” When a number of planes that were shot down in WWII were analyzed for bullet holes, the scientist that was making suggestions to the military counter-intuitively suggested covering the parts of the plane without bullet holes. This is because of selection bias, where planes that were shot down were thought to have exploded, thus making the parts of the plane with bullet holes more resilient, and less in need of armor, than the parts without bullet holes!

### A Challenging Job Search
The range of interview questions I was asked and my overall experiences seemed to look very different at each company. Depending on that company’s business model, and current challenges, certain skill sets may be more or less useful than others. In my current team at Microsoft, we have a team of specialists. Each data scientist has a specialty -- natural language processing, time series forecasting, classification, clustering and matrix factorization. We all overlap in each others’ area of expertise, and ultimately are able to make valuable contributions in a particular area.

I won't be going into specifics about each and every interview I went through. I will say, however, that I felt like the whole interview process was rather unfair. 

I have a particular dislike for "take-home" interviews. I imagine these are useful for two reasons: (1) to mitigate bias towards extroverts in face-to-face interviews, (2) to mitigate any biases that may be subconsious on the part of the interviewer, (3) to save time (the reviewer of the notebook only need spend a few minutes judging, rather than a whole hour). As the interviewee, these homework assignments are full-day investments, and more often than not, I feel like I'm being manipulated into doing unpaid work. My personal advice is to withdraw from any interview pipelines that make you waste time with these notebooks -- you'll likely not receive much in the way of feedback anyway. But obviously, to each their own.

Interestingly, I think we can tell what data science might look like at a company depending on the interview questions you receive. For instance, if you feel you are receiving ridiculous programming interview question(s), there is a good chance that role is actually a software engineering role disguised as a data science role. If you feel you are receiving many business-oriented questions, then perhaps that role is less technical, which may not may not be what you want.

### Questions You Should Ask
This is one of the most underrated parts of an interview, and at least some of the onus on finding the right fit is on you, not just the companies you are interviewing at. People have varying opinions on this, but personally, I like to ask the questions below. I think they are relevant, tough, and provide a reasonable approximation of the culture of the company.

* What is the gender ratio of your the group, and at the office?
* Who was the last person that was fired from the group and why?
* Do people typically eat lunch at their desks?
* What was the last data science / engineering mishap you had and how do you hope to prevent it from happening again?
* What percent of employees leave the company within 1 year? 2 years? 4 years?

It may feel scary to ask these important questions, but I can assure you that as an interviewer, it’s also scary to receive them. Furthermore, there are a number of trite, softball questions I’ve been asked as an interviewer, and many of these can be found in web pages scattered across the Internet. For instance, if you ask anyone, “Why do you love working here?”, I’d say there is a decent chance the reply might be, “the people!” I’d suggest asking something more specific in the same vein, such as, “Could you tell me about a time you felt like you were overextended, and your team came to your rescue?”

### I Applied For 57 jobs in a 12 Month Period
I used an excel sheet I used to track my job search in 2017. Most of these companies did not provide feedback along with their decision. There was only one company I interviewed with that did provide constructive feedback, which reflected very positively on them (General Assembly). My most negative interview experiences were with large companies like Facebook and KPMG.

When I was at Insight, the program directors had me keep track of companies I had in my pipeline in Trello, which seemed to work well. My board was quite sparse though, as I converged good fit rather quickly.

Data science is still a very young field (although, I remember learning about it in 2009 when HBR called it the sexiest job of the 21st century). Moreover, data science looks different at every company, which makes it difficult to anticipate if you are actually a good fit for a data science role at company X. Because of this, I think, I experiencing a wide range of interviews with over 30 companies, and still hadn’t converged on anything I would consider “signal.” In hindsight, I think this was partly on me, because I wasn’t telling companies “no” enough. I now use phone interviews, especially the initial phone calls with someone from the group I’m interviewing with, as an opportunity for me to assess how I can bring value to their team. This means understanding a few aspects about the group: their technology stack, problem-solving approach, team bond, etc. Your goal for this phone call is to get a feel for whether you would accept an offer from this group/company. If it doesn’t seem like a good fit, it’s best to be honest with yourself, acknowledge the place you are interviewing at will likely not be a good fit, and remove yourself from the remainder of the interview process.

### Skills Gap
Every year, additional methodologies and case studies are accepted into the corpus of data science skills. Although the many of the fundamentals remain unchanged, specific examples that may have an obvious answer may not seem so obvious to those who haven’t studied the phenomenon. In short, there is an evolving culture in the field, and it is difficult to point to any one resource one may follow to stay up to date.

### Job Boards
Here is a list of data science job boards I collected. It’s obviously not exhaustive, and likely has some cross-posted requistions, but was useful for me when I was searching for the right data science role:

* https://www.kaggle.com/jobs
* https://www.r-users.com/jobs/
* http://www.startuphire.com/
* WeWorkRemotely
* FlexJobs
* Github Jobs
* LinkedIn
* http://jobs.qb3.org/careers_home.php
* http://jobs.sciencecareers.org/jobs/bioinformatics/faculty/
* http://workintech.io/
* https://www.analyticsvidhya.com/jobs/#/
* https://www.cybercoders.com/?logo=1
* http://www.geekwire.com/jobs/
* https://www.roberthalf.com/technology/jobs/data-scientist/seattle-wa
* Github Careers - Data Science Analyst
* Biospace
* http://kellymitchell.com/
* http://www.kdnuggets.com/jobs/index.html
* https://www.datawerq.com/seattle/
* https://datajobs.com/Big-Data-Jobs/Seattle-WA~3
* http://datasciencereport.com/datascience-jobs/
* https://remoteok.io/remote-clojure-jobs
* https://www.insightglobal.net/careers/job-search/placement-process/

In fact, if you want, you can sign up for the very same MailChimp list I setup for myself. It lassos all of these sources together and then creates an email that is sent out every Thursday morning:

<!-- Begin Mailchimp Signup Form -->
<div id="mc_embed_signup">
<form action="https://nikhilgopal.us7.list-manage.com/subscribe/post?u=b0b52489b0b8cc0e8222a8c2a&amp;id=ec1aa1c4e5" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
    <div id="mc_embed_signup_scroll">
	<h2>Subscribe to job list</h2>
<div class="indicates-required"><span class="asterisk">*</span> indicates required</div>
<div class="mc-field-group">
	<label for="mce-EMAIL">Email Address  <span class="asterisk">*</span>
</label>
	<input type="email" value="" name="EMAIL" class="required email" id="mce-EMAIL">
</div>
<div class="mc-field-group">
	<label for="mce-FNAME">First Name </label>
	<input type="text" value="" name="FNAME" class="" id="mce-FNAME">
</div>
<div class="mc-field-group">
	<label for="mce-LNAME">Last Name </label>
	<input type="text" value="" name="LNAME" class="" id="mce-LNAME">
</div>
	<div id="mce-responses" class="clear">
		<div class="response" id="mce-error-response" style="display:none"></div>
		<div class="response" id="mce-success-response" style="display:none"></div>
	</div>    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
    <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_b0b52489b0b8cc0e8222a8c2a_ec1aa1c4e5" tabindex="-1" value=""></div>
    <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
    </div>
</form>
</div>

<!--End mc_embed_signup-->

## A Short Selection of What Data Science "Looks Like" At Various Companies
I'll leave some brief notes here on my data science experiences at some of the companies where I feel I gained substantial data science skills.

#### Bioinformatics at Illumina (i.e. Biological Data Science)
For those who don’t know what a bioinformatics scientist is, it is basically a data scientist that works with molecular biology data. The role I had from 2009 to 2012 has substantial overlap with my current role in terms of fundamental skills. However, domain expertise is a significant factor, and I would say there it is less of a challenge for a bioinformatician to transition into data science, than there is for a data scientist to transition into bioinformatics (unless you already have a background in biology that is).

#### Data Science at RealSelf
This role was very business-focused, PM attributes, Data Engineering attributes. This was a super-fun place to work, and I miss being there. I would say it was my first “true” data science role, in that the decisions I made directly affected business decisions. Colleagues have asked me how my current role at Microsoft is different from RealSelf. The short of it is, at RealSelf, I needed to be a bit more of a data engineer and product manager in addition to my data science role.

#### Data Science at Microsoft
My role at microsoft is also very business-focused. However, I would say 80% of it is data science. There are still some data engineering and PM tasks I need to dive into, but I have the support of a dedicated data engineer and project manager on my team. Since we all work well together, this leads to a very productive and happy work environment.

### Data Science Feels Inaccessible to Newcomers
Data science still seems inaccessible, although I do think democratization of data science is the future. I’ve thought about why this might be the case, beyond just “hiring is broken,” and one of the reasons this might be is because there are very few entry-level data science roles. And I think this might be because the stakes are too high. Imagine putting a multi-million dollar business decision in the hands of a freshly-minted data science grad. Imagine allowing a entry-level data scientist provide advisory to a multi-million dollar client. The margin of error is quite small, and in a sense, the jobs of your co-workers, and revenue that families depend on may be affected as a consequence of your work/decisions.

Another reason why may be that it is too draconian to label an entry-level data scientist “incompetent”. After all, they are just starting their career! However, the performance of a model, or the deliverables produced as a result of it, are products we are accountable for. If your forecast is off by a percentage point, you will get questions about why it was wrong, what the cost of the error was, and perhaps why the company should trust your work at all. In harsh cases you may even find that those affected are able to attach dollar values to the consequences of your decision. These are tough questions, and they can catch even experienced data scientists a little off guard. Not to scare you off, but don’t be surprised if you feel like you are betting your badge on your work.

### "How can I succeed in data science if I don’t have a PhD?"
At this point, I would suggest the following: pick 1-2 areas you can become an expert in (classification, A/B testing, etc), and make that your primary skill. Then find a startup job that needs that skill in particular. Why a startup? Because they generally have a difficult time recruiting. Why 1-2 areas you can be an expert in? Because you have to compete with experienced data scientists.

Every now and then, people reach out to me on LinkedIn, alumni networks, etc and ask me about how they can get into data science. I think a bit of advice that I’ll provide that you are unlikely to hear anywhere else, is to start with a data science role that is “low stakes”. If you see a data science job posting at a company, and if you can already tell it is going to be an impactful role, then that might not be for you -- at least just yet. The stakes can be quite high with data science projects. An inflated error rate can mean millions of dollars in lost revenue, being unable to properly interpret a model may lead to a fundamentally poor business decision, etc. Think about this carefully -- this means people’s jobs, people’s retirement funds, etc. Many tutorials seem to make data science seem like the job is primarily "painting with data" and that we can pull down off-the-shelf sci-kit learn solutions to solve business problems, but I promise you there is the very small tip of a very large iceberg.

The question I ask myself before I deploy a model into production is: Am I willing to bet my badge on this? And sometimes you will have to regardless due to circumstances outside of your control.

It might be worth asking yourself the question about whether you truly want to do the work of a data scientist. I’ve noticed many roles that have a skills overlap with data scientist roles -- quantitative analyst, data analyst, etc. I know people with these titles, I consider them my peers, learn frequently from them, and they are very happy doing what they are doing because they are doing what they love! Today, data scientists may be called data scientists, and tomorrow they may be rebranded as something else. One way to determine this might be the following: Would you continue in the role you have right now if your title was changed to data scientist overnight?

### More Advice:
A useful bit of advice would be to think about the economics of the company you are interviewing at. For instance, startups tend to have short financial runways, so the likelihood of a startup willing to take a chance on someone who has solid fundamentals but lacks practical experience may be low, because it is risky for them. Whereas a larger company may appreciate the idea of hiring someone completely new, and teaching them their best practices, etc. At the same time, recruiting is difficult for startups, so the likelihood of getting further down the interview process more quickly is higher versus larger companies.

Also realize that as a job seeker, startups are risky. It’s very possible the startup you are going to work for may not receive their Series A, or end up being acquired by a larger company, which means you may be job searching yet again, and much sooner than anticipated.

## What It’s like being on the other side (being the interviewer):
I can appreciate now how difficult interviewing is for the interviewer as well. Imagine having to make a decision on whether someone will be a good fit for the group, have the opportunity to grow, is truly interested in the job, is competent, is reliable, can work under pressure, etc. in 30-60 minutes. Most interviewers aren’t going to doubt your ability, but will want to see you demonstrate it to see if he/she can follow your thought process -- we are sharing work with each other after all, and we need to have mutual confidence in each other’s work.

## Hiring a Data Science Manager
After interviewing no less than 7 data science managers, I’ve found that they generally fall into 4 buckets. This may be true for those seeking data scientist positions too. I’ll summarize these in three personas:

* The Machinist - Someone who is technically strong, but has little to no business acumen or product sense
* The Visionary - Someone who has a strong product sense / business acumen, but is not technically strong
* The Consultant - Someone who has had exposure to a wide breadth of experience
* The Professor - A domain specialist who has been working on the same problem for 10-20 years. Think Depth.


### Addendum on Choking and Yips:
[https://www.youtube.com/watch?v=CqgmozFr_GM](https://www.youtube.com/watch?v=CqgmozFr_GM)

### Good Luck
Hopefully all of this information is helpful! As time passes, I'm sure some of this information will be changing over time, so please use your best judgement. Best of luck on your search.

### Sign Up For Updates:
Congratulations on making it this far! You got through approximately 4,246 words (25,946 characters). This is perhaps 10x longer than most blog posts on the internet :-D. Please consider signing up so I can send you email updates when I make more blog posts. You can hit reply and get in touch with me directly as well.


<link href="//cdn-images.mailchimp.com/embedcode/classic-10_7.css" rel="stylesheet" type="text/css">
<div id="mc_embed_signup">
<form action="https://nikhilgopal.us7.list-manage.com/subscribe/post?u=b0b52489b0b8cc0e8222a8c2a&amp;id=7c04e611ce" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
    <div id="mc_embed_signup_scroll">
	<h2>Subscribe</h2>
<div class="indicates-required"><span class="asterisk">*</span> indicates required</div>
<div class="mc-field-group">
	<label for="mce-EMAIL">Email Address  <span class="asterisk">*</span>
</label>
	<input type="email" value="" name="EMAIL" class="required email" id="mce-EMAIL">
</div>
<div class="mc-field-group">
	<label for="mce-FNAME">First Name </label>
	<input type="text" value="" name="FNAME" class="" id="mce-FNAME">
</div>
<div class="mc-field-group">
	<label for="mce-LNAME">Last Name </label>
	<input type="text" value="" name="LNAME" class="" id="mce-LNAME">
</div>
	<div id="mce-responses" class="clear">
		<div class="response" id="mce-error-response" style="display:none"></div>
		<div class="response" id="mce-success-response" style="display:none"></div>
	</div>    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
    <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_b0b52489b0b8cc0e8222a8c2a_7c04e611ce" tabindex="-1" value=""></div>
    <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
    </div>
</form>
</div>
<script type='text/javascript' src='//s3.amazonaws.com/downloads.mailchimp.com/js/mc-validate.js'></script><script type='text/javascript'>(function($) {window.fnames = new Array(); window.ftypes = new Array();fnames[0]='EMAIL';ftypes[0]='email';fnames[1]='FNAME';ftypes[1]='text';fnames[2]='LNAME';ftypes[2]='text';fnames[3]='ADDRESS';ftypes[3]='address';fnames[4]='PHONE';ftypes[4]='phone';}(jQuery));var $mcj = jQuery.noConflict(true);</script>
<!--End mc_embed_signup-->


-------
