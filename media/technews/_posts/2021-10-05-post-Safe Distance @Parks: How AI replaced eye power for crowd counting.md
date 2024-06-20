---
layout: post
title: "Safe Distance @Parks: How AI replaced eye power for crowd counting"
permalink: /media/technews/safe-distance-at-nparks/
image: /images/technews/Safe_Distance___Parks__how_AI_replaced_eye_power_for_crowd_counting__1_.jpg
date: 2021-10-05
description: Led by Abhishek Tandon from GovTech, discover how SG's Safe
  Distance @ Parks app tackled overcrowding in green spaces during the pandemic.
  🌳
variant: tiptap
---
<p>Singapore is well known for having ample green spaces amid the urban landscape
that stem from our commitment to building a network of parks over the years.</p>
<p>Beset by the many challenges that cropped up during the circuit breaker
period last year, Singaporeans flocked to the parks to find respite in
nature. As a result, popular parks like East Coast Park became congested
with many visitors.</p>
<p>The Government quickly rolled out the Safe Distance @ Parks website and
app, which could display near real-time crowd sizes for parks across Singapore
so that people could avoid those with high footfall. Developed in 3.5 days
and subsequently enhanced with automated updates, Safe Distance @ Parks
is a great example of the Government’s commitment to using tech in an agile
manner to make people’s lives better.</p>
<p>Mr Abhishek Tandon, who is from GovTech’s Services division and is currently
seconded to NParks, led the combined NParks and GovTech team, which developed
Safe Distance @ Parks. We spoke to him to learn more about what it took
to make the project a reality.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Led by Abhishek Tandon from GovTech, this project utilised technology for real-time crowd monitoring" src="/images/technews/Safe_Distance___Parks__how_AI_replaced_eye_power_for_crowd_counting__1_.jpg">
</div>
<p><em>Abhishek Tandon led the team which developed Safe Distance @ Parks. Photo: GovTech</em>
</p>
<h3>Qn: Let’s start with an overview of Safe Distance @ Parks. What problem was it meant to tackle and how did it do so?</h3>
<p>As you observed, the pandemic led to a spike in visitors to our parks
and with the Covid-19 situation still ongoing, NParks is still seeing heightened
public interest in Singapore’s green spaces.</p>
<p>As a result, NParks’ staff who patrol gardens, parks, nature reserves
and park connectors as part of their daily work, have also been working
to enforce safe distancing measures in our green spaces. This manpower-intensive
effort has involved staff and volunteers from other public agencies to
patrol more than 500 green spaces.</p>
<p>So NParks wanted to leverage technology to support its safe distancing
operations, developing the Safe Distance @ Parks app (Diagram 1) to allow
members of the public to look for a park near them and check visitor levels
before leaving their homes. The app receives near real-time updates on
crowd sizes.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Crowd map density view via the Safe Distance @ Parks app" src="/images/technews/Safe_Distance___Parks__how_AI_replaced_eye_power_for_crowd_counting__2_.png">
</div>
<p><em>Diagram 1 Photo: GovTech</em>
</p>
<p>We used these prepared examples to train a case-details recogniser which
can identify the different types of key information with 85 per cent accuracy.</p>
<p>At this stage, we are able to automatically identify the nature of the
complaint, extract the relevant details, fill out the feedback template,
and prompt the user to add missing information.</p>
<h3>Qn: The Safe Distance @ parks website was developed in 3.5 days, and the automated update was developed in two weeks. Prior to the automated counting enabled by computer vision, how were crowd sizes determined and updated on the site? What did the team change or improve on?</h3>
<p>As GovTechies, we are ABC (Agile, Bold, and Collaborative). With support
from GovTech and NParks management, we got the portal up and running in
3.5 days. Initially, the crowd sizes were determined by observations from
NParks officers on the ground. Basically, that meant NParks officers were
manually counting and assessing!</p>
<p>They would then use the Safe Distance @ Parks mobile app to update visitor
levels at fixed intervals as well as to communicate any remarks or recommendations
for specific locations.</p>
<p>But we knew from the start that this manpower-intensive way of doing things
might not be sustainable. So, we developed an automated update system that
is scalable, able to get inputs from various sources (CCTV, Drones, EPS
carpark, etc. - Diagram 3) and makes use of analytics to assess crowd sizes
and update the Safe Distance @ Parks app.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Infographic of how the Safe Distance @ Park app works and collects data for live updates" src="/images/technews/Safe_Distance___Parks__how_AI_replaced_eye_power_for_crowd_counting__3_.png">
</div>
<p><em>Diagram 3 Photo: GovTech</em>
</p>
<p>This process was developed within 2 weeks to reduce the reliance on staff
input. This was achieved by deploying CCTV cameras with live streaming
capability extensively in our parks to reduce the physical deployment of
staff, employing central video analytics systems and integrating with Electronic
Parking Systems. Given that the COVID-19 situation is still ongoing, this
has helped to free up staff time to perform essential greenery and park
maintenance tasks.</p>
<h3>Qn: What were the main challenges involved in this project?</h3>
<p>One of the challenges was establishing the networks of cameras for automated
updating.</p>
<p>There were already existing cameras in place at various gardens and parks,
but they were not enough to meet the operational needs of the automated
updating system. Also, not all cameras had the ability to live-stream the
feeds to a central location or share images. NParks rapidly deployed additional
CCTV cameras to our parks, gardens and nature reserves, prioritising sites
that were more popular with visitors and required closer monitoring.</p>
<h3>Qn: What was it like working across agencies and partnering with the data science team from GovTech? What processes did you use to enable rapid development and deployment of the solution?</h3>
<p>Actually, Safe Distance @ Parks is not the only project we have collaborated
with GovTech on. Another example is the “Spot the Robot dog”, which was
programmed to monitor social distancing.</p>
<p>For Safe Distance @ Parks, we started with a loose set of requirements
by explaining our goal of “people counting” to the GovTech Data Science
team.</p>
<p>The GovTech team compared three commercial off-the-shelf people detection
and counting algorithms. They also built a prototype using a native cloud
service provider and quickly sorted out various technical tasks, such as
standardised protocol to receive images from the cameras.</p>
<p>All teams worked together to gather feedback from operational staff on
everything from the frequency of updating the public website, limitations,
existing camera height, coverage area and so on. The team optimised algorithms
as well as suggested placement of camera location.</p>
<p>In all, NParks was able to reduce manpower deployed for safe distancing
measures in parks by two-thirds. This allowed Singaporeans to continue
to seek respite at our parks safely, reaping the benefits of greenery and
nature for their health and wellbeing during this period.</p>
<h3>Qn: How essential were cloud services to this project?</h3>
<p>A major part of Safe Distance @ Parks is hosted on the cloud. The various
teams’ familiarity with cloud systems gave us a significant head start
in rapidly deploying our CCTV analytics prototype.</p>
<p>The flexibility of the cloud platforms also enabled us to scale up and
down different aspects of the project as and when necessary, such as during
a sudden surge in website traffic. The website received 620,000 monthly
visits at its peak.</p>
<p>To sum up, the end-to-end architecture is scalable, resilient, and secure.</p>
<h3>Qn: What other tech projects can we look forward to from NParks?</h3>
<p>We’re always looking to collaborate with partners from both the public
and private sectors, as well as institutes of higher learning. The “Spot
the Robot dog” example earlier is one. We’re also working with Garuda Robotics
for drone analytics and Ngee Ann Polytechnic on park surveillance robots,
which are autonomous machines that can detect the flouting of safe distancing
measures.</p>
<p>And, of course, we’re always working to enhance the capabilities of our
existing systems. We hope to have exciting new updates in the future! Stay
safe and healthy!</p>
<p></p>