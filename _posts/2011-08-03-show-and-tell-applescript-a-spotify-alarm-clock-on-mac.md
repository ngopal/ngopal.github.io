---
layout: post
title: 'Show and Tell: "AppleScript" a Spotify Alarm Clock on Mac'
date: 2011-08-03 06:34:00.000000000 -07:00
categories:
- applescript
- utility
tags: []
status: publish
type: post
published: true
---
<p><span>I don't know about you guys, but I've really been enjoying Spotify. Being one of the first American users has been a real treat. Making the switch from iTunes wasn't painful at all. Sorry iTunes, sometimes the best things in life are free...</span><br /><span><br /></span><br /><span>A few weeks ago, I used <a href="http://www.seevishal.com/?p=226">this applescript tutorial</a> to setup iTunes to be my morning alarm clock. I love this. Nothing makes it easier to get out of bed than waking up to a song that energizes you.</span><br /><span><br /></span><br /><span>I've found a way to use Spotify instead of iTunes in the alarm clock script, and this post is going to be a quick show and tell. It's not as easy as just replacing "iTunes" with "Spotify" in the iTunes alarm clock script.</span><br /><span><br /></span><br /><span>I would suggest following the tutorial in the link I provided earlier, substituting the script provided for the one I provide in step 1 below. Otherwise, you can follow my attempt at a walkthrough.</span>
<div>
<span><br /></span></div>
<ul>
<li><span>Open up spotlight and open up "AppleScript Editor." Copy the code below into your editor and save it (with an easy-to-remember name). </span></li>
<ul>
<li><span>Edit out my username with yours</span></li>
<li><span>Edit out my playlist "muzic" with the name of your playlist</span></li>
<li><span>Press the Run button to make sure it actually works.</span></li>
<li><span><b>Update 8/13/2012:</b> I've added the code in the image below to github as a <a href="https://gist.github.com/3344086">gist</a>.</span></li>
</ul>
<li><a href="http://4.bp.blogspot.com/-3DkSqt519tg/Tjed1AubCpI/AAAAAAAAACg/vgnJg3HxwOw/s1600/Screen+shot+2011-08-01+at+7.08.27+PM.png" imageanchor="1"><span><img border="0" height="400" src="{{ site.url }}/assets/Screen+shot+2011-08-01+at+7.08.27+PM.png" width="371" /></span></a></li>
<li><span>Next, pop open your terminal window and type in "crontab -e" without the quotes</span></li>
<li><a href="http://2.bp.blogspot.com/-uVEjTcfhxqE/TjeeXJdxxkI/AAAAAAAAACk/WJSqdZmXirM/s1600/Screen+shot+2011-08-01+at+7.05.56+PM.png" imageanchor="1"><span><img border="0" height="267" src="{{ site.url }}/assets/Screen+shot+2011-08-01+at+7.05.56+PM.png" width="400" /></span></a></li>
<li><span>Now you will be in VI editor, so press "i" on your keyboard to "insert," and type in the following line (the one line at the bottom is all you need). Make sure the path points to the script you just made in step 1. Also note that the pound sign on the first line "comments out" the line, so that line of code is ignored.</span></li>
<li><a href="http://3.bp.blogspot.com/-PHBKSydGvWY/Tjee7nRDJ0I/AAAAAAAAACo/rz08zQWrN4w/s1600/Screen+shot+2011-08-01+at+7.05.44+PM.png" imageanchor="1"><span><img border="0" height="267" src="{{ site.url }}/assets/Screen+shot+2011-08-01+at+7.05.44+PM.png" width="400" /></span></a></li>
<li><span>After you are done typing in the code, press "esc" so that a colon show up in the bottom left corner of the screen. Then type in "wq!" to save and quit the editor.</span></li>
<ul>
<li><span>As a note, my alarm confguration (shared in the image above) is set to wake me up at 6:01AM. I would <a href="http://adminschoice.com/crontab-quick-reference">look here</a> to find out how to edit the cron job to awaken you at a time of your own choosing.</span></li>
</ul>
<li><span>Next, you have to make sure your computer is on maybe 5 minutes before your alarm goes off. This can be done in the "System Preferences" application. </span></li>
<li><a href="http://3.bp.blogspot.com/-JbGcP3GNkX4/TjehBn047eI/AAAAAAAAADA/newtIshICog/s1600/Screen+shot+2011-08-01+at+7.14.19+PM.png" imageanchor="1"><span><img border="0" height="340" src="{{ site.url }}/assets/Screen+shot+2011-08-01+at+7.14.19+PM.png" width="400" /></span></a></li>
<li><span>Click on the "Energy Saver" option</span></li>
<li><a href="http://1.bp.blogspot.com/-5CqODLJGYPQ/TjehB9cs08I/AAAAAAAAADE/HdMVU8-NAC8/s1600/Screen+shot+2011-08-01+at+7.14.36+PM.png" imageanchor="1"><span><img border="0" height="300" src="{{ site.url }}/assets/Screen+shot+2011-08-01+at+7.14.36+PM.png" width="400" /></span></a></li>
<li><span>You don't have to mess with your sleep and display configuration, but you do need to click the "Schedule..." button on the bottom right hand corner</span></li>
<li><a href="http://4.bp.blogspot.com/-Alk3mpmYMPA/TjehCMxkNDI/AAAAAAAAADI/TiXcTXOivnA/s1600/Screen+shot+2011-08-01+at+7.14.40+PM.png" imageanchor="1"><span><img border="0" height="178" src="{{ site.url }}/assets/Screen+shot+2011-08-01+at+7.14.40+PM.png" width="400" /></span></a></li>
<li><span>Set your mac to wake up or start up 5 minutes before your cron job kicks off. You're all done!</span></li>
</ul>
<div>
<span><br /></span></div>
<div>
<span><b>Congratulations, you've just setup your own Spotify alarm clock!</b></span></div>
