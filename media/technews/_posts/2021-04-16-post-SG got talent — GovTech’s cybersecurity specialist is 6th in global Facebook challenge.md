---
layout: post
title: SG got talent — GovTech’s cybersecurity specialist is 6th in global
  Facebook challenge
permalink: /media/technews/sg-got-talent-govtech-cybersecurity-specialist-sixth-in-global-facebook-challenge/
image: /images/technews/SG_got_talent.jpg
date: 2021-04-16
description: 🔍💻 GovTech cybersecurity specialist Eugene Lim secured 6th place
  at BountyCon with his expertise in hacking Facebook Gameroom. 🏆👨‍💻 Find out
  more!
variant: tiptap
---
<div class="isomer-image-wrapper">
<img style="width: 50%;" height="auto" width="100%" alt="Eugene Lim, Cybersecurity Specialist who secured 6th place in the global Facebook challenge" src="/images/technews/SG_got_talent.jpg">
</div>
<p><em>Eugene took 6th place during a live hacking segment held at BountyCon. PHOTO: GOVTECH</em>
</p>
<p>Now, say what you will about TikTok gaining popularity among teenagers,
but the fact remains that a large portion of Singaporean youth still use
Facebook. Notice I used the word ‘youth’, which, according to the National
Youth Council, refers to people aged 15–35.</p>
<p>Yes, 35; you did not read it wrongly.</p>
<p>With such a large portion of society still on Facebook, it is really important
for the platform to remain secure and proactively search for any hidden
vulnerabilities.</p>
<p>That’s exactly what GovTech cybersecurity specialist Eugene Lim did! Not
only did he try his hands at it last year, he flew the Singapore flag high
by coming in sixth at a global cybersecurity hacking challenge.</p>
<p>Bountycon – the invitation-only security conference – was organised by
Facebook and featured a live hacking segment where participants were tasked
to find cybersecurity vulnerabilities in any of Facebook’s assets – including
beta and internal features not yet released to the public. Facebook encouraged
the participants to focus more in particular on “Facebook Gaming”.</p>
<p>Yup, this is not a drill, fellas.</p>
<h3>Zooming in on Facebook Gameroom</h3>
<p>Eugene – whose duties at GovTech include simulating attacks on government
cyber infrastructure to discover potential routes of attacks – started
the competition on the backfoot due to administrative issues that delayed
his entry. To maximise the opportunity, he strategically chose to focus
on Facebook Gameroom, a desktop gaming platform that was launched in November
2016 to compete with the likes of the popular gaming platform Steam.</p>
<p>He began by systematically probing for weaknesses that could be exploited
through offensive reverse engineering. This involved examining a software
system to trace its original design and implementation,</p>
<p>This approach yielded an early moment of promise when Eugene managed to
modify a file used by Facebook Gameroom that could be parsed in an unsafe
manner. In theory, this meant he could “hack” Gameroom into running a malicious
program from the file instead of its usual functions.</p>
<p>However, this proved to be a false dawn. The Facebook team clarified that
this did not qualify for points in the hacking segment as he had not found
a way to pull off the same thing remotely on another person’s machine.
In cybersecurity parlance, there was no viable remote attack vector.</p>
<p>“I learnt an important lesson about the different threat landscape posed
by native applications – search for a viable remote attack vector first
before diving into the code-level vulnerabilities,” he said.</p>
<h3>Redirecting users to danger</h3>
<p>Eugene eventually found success by targeting custom URIs – a type of link
that launches a program when it is clicked. One common example is a Zoom
meeting invitation link; when you click on the invitation link, the Zoom
program will launch, and you will be taken straight to the meeting room.</p>
<p>Similarly, when you click on a custom Facebook Gameroom URI on the web
browser, Gameroom will automatically open. This was the key vulnerability
Eugene had been seeking for. He also noticed that Gameroom relied on an
outdated version of the Chromium (which Chrome is based on) web browser
to display web content. After experimenting with various workarounds, Eugene
managed to create a URI that opened Gameroom and directed users to web
content he controlled instead of launching the intended web content that
the users wanted to access.</p>
<p>In other words, a hacker could exploit this to display authentic-looking
requests for users to perform cyber-attacks such as phishing. A hacker
could also run JavaScript code that would exploit the outdated Chromium
browser to execute malicious programs.</p>
<p>For a technical walkthrough, check out&nbsp;<a href="https://spaceraccoon.dev/applying-offensive-reverse-engineering-to-facebook-gameroom" class="editor-rtfLink" rel="noopener noreferrer nofollow" target="_blank">Eugene’s blog</a>&nbsp;for
his experience during the challenge.</p>
<h3>Showcasing SG expertise</h3>
<p>Eugene’s discovery propelled him into the top ten leaderboard for Bountycon,
and eventually, he secured the sixth position.</p>
<p>His achievement endorses Singapore’s position on the tech world map, sending
a clear message that the country is a prime choice for tech companies to
sink roots not only because of its outstanding infrastructure and business
environment but also because it has a strong pool of tech talent to offer.
It also reaffirms Singapore’s efforts to nurture homegrown tech talent
– from newbies joining the workforce to mid-career professionals. Eugene
had previously been awarded the Most Valuable Hacker at a similar live
hacking event co-organised by Verizon Media (Yahoo), the US Air Force,
and the UK Ministry of Defense, as well as won the Best Team award at a
PayPal live hacking event.</p>
<p>Although Facebook Gameroom is a relatively unknown product and is scheduled
to be decommissioned in June 2021, Eugene – who has been with GovTech for
just over a year – said it was still satisfying to see that Facebook patched
the vulnerability, cutting off this potential route of attack for bad actors.</p>
<p>He added: “Although Gameroom will be shut down soon, this episode definitely
left me with some fond memories of the practice of applying basic offensive
reverse engineering to discover system vulnerabilities.”</p>