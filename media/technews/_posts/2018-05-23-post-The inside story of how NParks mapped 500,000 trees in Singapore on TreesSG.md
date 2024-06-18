---
layout: post
title: The inside story of how NParks mapped 500,000 trees in Singapore on TreesSG
permalink: /media/technews/the-inside-story-of-how-nparks-mapped-500000-trees-in-singapore-on-treessg/
image: /images/technews/the-inside-story-of-how-nparks-mapped-500000-trees-in-singapore-on-treessg-part-1.png
variant: tiptap
date: 2018-05-23
description: ""
---
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="the inside story of how nparks mapped 500,000 trees in singapore on trees.sg" src="/images/technews/the-inside-story-of-how-nparks-mapped-500000-trees-in-singapore-on-treessg-part-1.png">
</div>
<p><em>TL: DR: <a href="https://www.nparks.gov.sg/trees" rel="noopener noreferrer nofollow" target="_blank">trees.sg</a> helps citizens learn about more than half a million of Singapore’s urban trees on an interactive map. Developed by NParks with support from GovTech, the online portal allows the community to interact with the trees as well, such as by indicating when they are flowering.</em>
</p>
<p><em>Curious about how this forest of data was populated? Read on for our interview with two members of the project team.</em>
</p>
<hr>
<p>Have you ever walked past a tree and wondered what species it is? If you’re
like most people, you probably stopped for a second to admire its flowers
or unique shape, and then moved on with the rest of your day, forgetting
to indulge your curiosity.</p>
<p>Now, however, you can look up your tree right away on <a href="https://www.nparks.gov.sg/trees" rel="noopener noreferrer nofollow" target="_blank">trees.sg</a>,
an online portal developed by Singapore’s National Parks Board (NParks)
with support from the Government Technology Agency of Singapore (GovTech).
With data on more than 500,000 urban trees and counting, the portal not
only lets you locate individual trees on a map, but also provides information
on their scientific and common names, dimensions, carbon content, pruning
schedule and more.</p>
<p>The community can also indicate if the trees are flowering, upload their
pictures of the trees and leave messages. The portal is part of NParks’
larger effort to harness science and technology to advance capabilities
in greening, conservation and tree care management, as well as involving
the community to realise the City in a Garden vision.</p>
<p>Curious about how the portal came to be? We sat down with two members
of the project team, Mr Abhishek Tandon and his colleague Mr Joseph Sia,
who are both GovTech Geospatial Specialists seconded to the National Parks
Board, to find out more about how their work on geospatial technology at
NParks provides the data that trees.sg uses.</p>
<h3><strong>Phase 1</strong></h3>
<h3><strong>The roots: data collection</strong></h3>
<p>The roots of trees.sg actually lie in NParks’ mobile tree inspection (mobile
TI) application, an iPad app implemented three years ago to help staff
enter data from tree inspections more easily. “Mobile TI was the first
step towards collecting the data you now see on trees.sg,” said Mr Tandon.</p>
<p>During the development of mobile TI, however, the team ran into many performance
issues—for one, the need to encrypt and decrypt data on the iPad meant
that maps didn’t load quickly enough.</p>
<p>To address these problems, the team roped in geospatial specialists from
GovTech, and made a concerted effort to work together with vendors and
developers to find and fix bugs. “We went back to the basics, literally
sitting down with the developers to compile and code with them,” explained
Mr Tandon, adding that this strategy allowed the team to shorten the mobile
TI rollout from an estimated eight months to 26 days.</p>
<h3><strong>Phase 2</strong></h3>
<h3><strong>The trunk: data consolidation</strong></h3>
<p>Mobile TI is not the only source of data on trees in Singapore—NParks
also collects a range of other datasets, including vegetation, biodiversity
and leaf area index maps. To get more meaningful insights, the team consolidated
all these datasets onto a central platform called Maven, which today serves
as an API platform—the trunk, if you will—for trees.sg and other applications.</p>
<p>“All this data was in different platforms and silos; we have now consolidated
about 1,300 datasets into a single platform,” explained Mr Tandon.</p>
<p>Here, the challenge lay in managing hundreds of disparate datasets, said
Mr Sia, who was tasked with extraction, transformation and loading (ETL)—the
process of integrating data from multiple sources and owners into a common
repository. “It’s a lot of project management—you need to have a very clear
idea of the various processes that need to happen,” said Mr Sia, adding
that mapping these processes out on paper helps him with his planning.</p>
<p>At this point, given that the project involved multiple data owners, the
team also had to engage these stakeholders, said Mr Tandon.</p>
<h3><strong>Phase 3</strong></h3>
<h3><strong>The leaves: taking the data public</strong></h3>
<p>With a common data repository in place, the time was right to send out
branches and leaves into the public domain—in the form of public-facing
applications like trees.sg.</p>
<p>Building trees.sg was a team effort and required various NParks divisions
to collaborate to ensure that the information presented was accurate and
up to date. Hence, the trees.sg project team worked with Mr Tandon and
Mr Sia to ensure that the datasets could be extracted and utilised in an
effective manner.</p>
<p>Collaboration was also necessary because trees.sg interfaces with some
of NParks’ existing platforms—for example, it pulls the species and common
names of trees from <a href="https://florafaunaweb.nparks.gov.sg/Home.aspx" rel="noopener noreferrer nofollow" target="_blank">NParks Flora&amp;FloraWeb</a>,
an information portal on plants and animals in Singapore.</p>
<p>The project team also had to figure out the best way to visualise data
and present it to the user. For example, they had to decide on how many
clusters of trees would be shown at each zoom level of the map—too many
clusters would clutter up the map, while too few would defeat the purpose.</p>
<p>The team’s approach to decision making was to have many iterations. They
also sourced for multiple opinions and worked with users and stakeholders
to reach a consensus.</p>
<p>If Mr Tandon and Mr Sia are any indication, trees.sg is already doing
its job of getting people excited about nature—contributing to the project
has made the two techies look up from their computer screens and out at
Singapore’s greenery. “We became nature lovers at NParks. Prior to this
we were just technology lovers,” quipped Mr Tandon.</p>