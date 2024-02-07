---
layout: post
title: "Clearing the air: Using tech to keep our environment smoke free"
permalink: /media/technews/clearing-the-air-using-tech-to-keep-our-environment-smoke-free/
image: /images/technews/Clearing_the_air__Using_tech_to_keep_our_environment_smoke_free.jpg
date: 2022-02-22
description: 🌿 Discover how Singapore uses video analytics in the Balefire
  project to detect outdoor smoking, maintaining a clean and smoke-free
  environment. 🚭👀
variant: tiptap
---
<p>As a garden city, Singapore is known for its lush greenery, clean streets,
and fresh air.</p>
<p>Speaking of which, technology has been tapped in the last two years to
maintain that fresh air that we value, whether we are in an urban setting
or in the great outdoors.</p>
<p>In this article, we take a look at how video analytics is being used to
detect smoking that takes place outside of designated public places.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Irresponsible disposal of cigarette. Using tech to keep environment smoke free" src="/images/technews/Clearing_the_air__Using_tech_to_keep_our_environment_smoke_free.jpg">
</div>
<p>Let’s see how tech can be used to keep our environment smoke-free! Photo
by&nbsp;<a href="https://unsplash.com/@johnmcclane?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText" class="editor-rtfLink" rel="noopener noreferrer nofollow" target="_blank">Andres Siimon</a>&nbsp;on&nbsp;
<a href="https://unsplash.com/s/photos/smoking-zone?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText" class="editor-rtfLink" rel="noopener noreferrer nofollow" target="_blank">Unsplash</a>
</p>
<h3>A fun name for a serious subject</h3>
<p>Every project needs a name, and the team chose “Balefire” for this smoking
detection video analytics project. A balefire is a bonfire used for sending
smoke signals. So since there’s smoke involved and signals need to be sent
regarding smoking taking place, Balefire was chosen!</p>
<h3>The key to training a machine – data, data, data</h3>
<p>Balefire’s basic premise is to train a machine to recognise smoking activities
within videos. To do so, the machine needs to be shown many examples of
a human smoking, preferably in different poses and stances.</p>
<p>The team deployed cameras at smoking hotspots, such as near dustbins,
to capture videos. They then manually labelled the data so that the machine
understood what it was seeing. They also used powerful machine learning
models that could identify key parts of a person, such as face, elbows,
and knees) accurately, enabling them to analyse different stances more
accurately.</p>
<p>The labelled data is then used to train the machine so that it eventually
can tell when a video shows someone smoking, even though it has not been
explicitly labelled as such.</p>
<h3>First trial – proof of concept</h3>
<p>A two-week trial was carried out in March 2019. Mobile cameras were deployed
at a hotspot where illicit smoking was known to take place.</p>
<p>Video is uploaded to a cloud server, where it is analysed for instances
of smoking taking place. Once detected, Telegram alerts are triggered for
National Environment Agency (NEA) officers to carry out enforcement.</p>
<p>While the solution worked, there were some drawbacks. It was expensive
to constantly send data up to the cloud. Areas with a high number of mobile
devices also caused the 4G network there to be congested, affecting video
streaming quality and the accuracy of video analytics.</p>
<h3>Second trial – effectiveness enhanced</h3>
<p>The second trial, which lasted a month in September 2020, saw higher accuracy
thanks to a few factors.</p>
<p>One, the team had collected a bigger data set with more varied scenarios
of smoking, enabling the machine to recognise even more instances of smoking.
They also enhanced the analytics pipeline to include pose estimation.</p>
<p>Two, video analytics was now done in a device deployed together with the
mobile camera, enabling near real-time analysis. Known as edge data processing,
this meant that video no longer needed to be streamed to the cloud and
intermittent 4G networks were no longer a problem. It was also more cost
effective as it was not constantly uploading data.</p>
<p>This “video analytics on the edge” was made possible thanks to increasingly
powerful computational power on smaller hardware that required less power.</p>
<h3>Tech challenges accepted and overcome</h3>
<p>Overall, there were three major areas of tech challenges to overcome.</p>
<ul data-tight="true" class="tight">
<li>
<p>Video analytics – It took years to tune the video analytics engine so
that it performs well in a variety of settings such as crowded areas, narrow
alleys, and a large amount of daylight.</p>
</li>
<li>
<p>Deployability – The solution had to be scalable, meaning it had to be
deployed in different locations with minimal manual effort and without
having onerous infrastructure support. The edge processing of video was
a major development that allowed scalability.</p>
</li>
<li>
<p>Robustness – To ensure operation across the island 24/7 without crashing,
the team built data pipelines to back up data, raise alerts to NEA, monitor
the functioning of deployed devices, and also collect feedback.</p>
</li>
</ul>
<h3>What’s next?</h3>
<p>The video analytics team is constantly exploring other video analytics
models that can be deployed on the edge so as to expand the use of this
technology.</p>
<p>It is also hoped that other government agencies can tap into the tech
behind Balefire to support their operational needs in monitoring, security,
and surveillance.</p>