---
layout: post
title: Behind the scenes look at GovTech’s Red Team cyberattack
permalink: "/media/technews/behind-the-scenes-look-at-govtech's-red-team-cyberattack/"
image: /images/technews/behind-the-scenes-look-at-govtech’s-red-team-cyberattack-part-1.png
variant: tiptap
date: 2018-06-04
description: ""
---
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="behind-the-scenes look at govtech’s red team cyberattack" src="/images/technews/behind-the-scenes-look-at-govtech%E2%80%99s-red-team-cyberattack-part-1.png">
</div>
<p>TL:DR: Red-teaming is used in cybersecurity to simulate real-world attacks
on internet assets. To stress-test the resilience of government security
systems, GovTech’s “Red Team” plans and launches unannounced cyberattacks
against government agencies in Singapore. In this article, we take you
behind the scenes of a Red Team cyberattack!</p>
<hr>
<p>For most people, phishing for phone numbers, impersonating a company and
going undercover into an organisation’s secured premises all sound like
plot points in the latest spy thriller.</p>
<p>But these activities are all in a day’s work for Mr Chong Rong Hwa, director,
advanced cybersecurity capabilities and Mr Terence Teo, lead cybersecurity
specialist at the Government Technology Agency of Singapore’s (GovTech)
Cyber Security Group.</p>
<p>Mr Chong and Mr Teo are part of GovTech’s Red Team, a white-hat group
that plans and carries out unannounced cyberattacks against government
agencies in Singapore.</p>
<p>Red-teaming, as their job is known, emulates how an adversary might mount
an attack. It helps organisations identify vulnerabilities and stress-test
response strategies.</p>
<p>“The mission of the Red Team is to build stronger resistance against cybersecurity
attacks for government systems through proactive discovery of cybersecurity
gaps in people, processes and technology,” Mr Chong tells TechNews.</p>
<p>Curious about their work? Read on for a blow-by-blow account of a Red
Team attack and a behind-the-scenes look at how it was planned.</p>
<h3>D-Day minus 45 days: The plotting begins</h3>
<p>Once engaged to conduct an unannounced adversary simulation exercise against
a government agency ‘Blue Team’, GovTech’s Red Team starts preparations
right away. As early as a month and a half before D-Day, the Red Team starts
gathering information and setting up the custom infrastructure and tools
it needs to launch the attack.</p>
<h3>D-Day minus two days: Setting the trap</h3>
<p>0800: The game is afoot! Two days ahead of D-Day, Red Team sets the attack
on Blue Team’s assets in motion.</p>
<p>0815: Blue Team’s perimeter defence blacklists Red Team’s IP address.</p>
<p>0830: Red Team uses IP address hopping to bypass the blacklist attempt.</p>
<p>1000: Red Team delivers a simulated phishing campaign to Blue Team employees.</p>
<p>1100: Blue Team is notified about phishing emails through an integrated
incident reporting system. Blue Team investigates…</p>
<p>1230: …but it is too late. Red Team obtains the contact information of
several Blue Team employees and conducts a voice phishing (vishing) attack:
it impersonates an audit firm and schedules a session in two days’ time
at Blue Team headquarters to perform an ‘IT audit’.</p>
<p>1530: Time to put on those white hats: using internet footprinting, Red
Team identifies insufficiently secured Blue Team web applications hosted
by third-party vendors.</p>
<p>1730: Red Team exploits a vulnerability in one of these web applications;
Blue Team is notified for immediate follow-up.</p>
<h3>D-Day: The trap springs shut</h3>
<p>0800: Game on: Red Team splits into a social engineering team, whose members
will pose as IT auditors, and a HQ team, which will conduct the attack
once the social engineers gain a foothold.</p>
<p>0900: Red Team social engineers arrive at Blue Team HQ and are led into
secure premises by Blue Team auditees; Red Team HQ is updated and placed
on standby.</p>
<p>0930: Red Team social engineers ask Blue Team auditees to plug in a USB
flash drive and open a word document. Blue Team complies without validating
social engineers’ identities.</p>
<p>0935: The word document—actually a customised Red Team tool—creates a
connection back to Red Team HQ.</p>
<p>0945: Bingo! Red Team HQ exploits this access and pivots into the Blue
Team’s network.</p>
<p>1000: Time to don those white hats once again: Red Team looks for traces
of real adversaries to see if Blue Team’s systems have previously been
compromised by unknown attackers. Red Team also sniffs out weak configurations
and cybersecurity vulnerabilities.</p>
<p>1600: Job done! Red Team cleans up after itself, making sure that Blue
Team’s system is put back in its original state. Red Team consolidates
its findings.</p>
<h3>Behind the scenes</h3>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="behind-the-scenes look at govtech’s red team cyberattack" src="/images/technews/behind-the-scenes-look-at-govtech%E2%80%99s-red-team-cyberattack-part-2.png">
</div>
<p>While cybersecurity war-gaming may sound exciting, carrying out a successful
exercise requires extensive preparation and a lot of patience on the part
of the Red Team, says Mr Chong.</p>
<p>“Approximately 80 per cent of our time is spent on preparation, while
20 per cent is spent on the actual execution of the attack. A lot of effort
is spent on enumerations, development of customised tools and attempts
to understand the system as well as its business processes prior to the
conduct of the red-teaming exercise.”</p>
<p>The social engineering aspect of the exercise, in particular, required
detailed preparation. “There will always be an element of surprise during
the exercise, where I’m required to think on my feet and react accordingly
based on the target’s response,” says Mr Teo, who was part of the undercover
team. “Lots of planning was required as the team had to gather information
from various sources and correlate them so as to develop a convincing pretext.</p>
<p>We had to rehearse our different personas as part of preparation, and
we always had a contingency plan to mitigate the risk of being discovered.”</p>
<p>After a red-teaming exercise is complete, the Red Team presents its findings
to the targeted government agency and other stakeholders. In addition to
dealing with immediate issues, the Red Team also tries to help agencies
identify the root causes of cybersecurity breaches, and to come up with
strategic fixes for them, says Mr Chong.</p>
<p>“In general, there is never a 100 per cent-secured complex environment,
as there will always be weaknesses that can be exploited by the attacker,”
explains Mr Chong.</p>
<p>“Hence, red-teaming is necessary to help agencies strengthen their cybersecurity
posture, so as to make our assets costly for real-world attackers to attack.”</p>
