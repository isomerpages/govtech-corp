---
layout: post
title: No short supply of good ideas
permalink: /media/technews/no-short-supply-of-good-ideas/
image: /images/technews/No_short_supply_of_good_ideas.jpg
date: 2020-05-12
description: GovTech's SupplyAlly app swiftly distributes masks to
  Singaporeans📱, demonstrating efficiency in logistical coordination during the
  pandemic.
variant: tiptap
---
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="The SupplyAlly team from GovTech." src="/images/technews/No_short_supply_of_good_ideas.jpg">
</div>
<h3>This GovTech team developed a mobile app, SupplyAlly, that enabled hundreds of volunteers to distribute millions of reusable face masks to residents in Singapore over one weekend.</h3>
<p>News about diagnoses and treatments often take the limelight as governments
across the globe grapple with COVID-19. Receiving less attention is the
fact that society’s fight against the novel coronavirus is as much a logistical
undertaking as it is a healthcare one.</p>
<p>For example, distributing reusable face masks to residents was a priority
of the Singapore government as it announced ‘circuit breaker’ measures
at the start of April 2020 to curb the uptick of local COVID-19 cases.</p>
<p>The Ministry of Trade &amp; Industry (MTI) and People’s Association (PA),
tasked with coordinating the nationwide distribution effort, anticipated
two main logistical challenges that would affect mission success: Firstly,
it needed to manage a flexible pool of volunteers distributing masks at
each collection point. Secondly, those volunteers had to be able to keep
track of collection quotas—no one should be allowed to collect more than
one reusable face mask.</p>
<p>Seeking a technological solution to facilitate both processes, MTI and
PA reached out to the Government Technology Agency of Singapore (GovTech)
for assistance. Mr Steven Koh, Director of Government Digital Services
at GovTech, recalls receiving the call from Kuhan, Director of the Digitalisation
Office at MTI and Andy, Director (of IT) at PA, on 1 April 2020, 11pm,
with the request that the application be up and running by 5 April. His
first thought was that it was an April Fools joke. It was not.</p>
<h3>Hit the ground running</h3>
<p>Fortunately, Mr Koh and his colleagues at GovTech were prepared to meet
MTI’s and PA’s tight deadlines. It certainly helped that they had been
working on a similar application beforehand, which could be quickly repurposed
and refined for this distribution, said Mr Raymond Yeh, a software engineer
at GovTech.</p>
<p>After conferring with the Minister-in-charge of GovTech, Dr Janil Puthucheary,
and officers from MTI and PA to firm up operationalisation details, the
GovTech team went into full development mode. The mobile app, named SupplyAlly,
was delivered on time on 5 April.</p>
<p>Since SupplyAlly was meant to be used by volunteers at residents’ committees
and community centres, the GovTech team paid attention to user-friendliness
during app design and development. “We wanted to make sure that volunteers
needed minimal training to start using the mobile app,” noted Mr Lim Zui
Young, a DevOps and quality engineer at GovTech.</p>
<p>Indeed, after downloading the app, one simply needs to scan a PA-issued
QR code to log in. There is no need for volunteers to input their personal
particulars or identity card details for authorisation. The camera on the
mobile phone is then activated, and volunteers can begin scanning the identity
cards of individuals who show up to collect their reusable masks.</p>
<p>“The QR code login method solves a very fundamental design problem in
that it doesn’t require PA to register every single volunteer before deploying
them,” said Mr Chow Ruijie, a software engineer at GovTech. “If a new volunteer
shows up, PA can just pass him or her a barcode to authorise the use of
the app. This speeds up the onboarding process and grants PA more flexibility
in managing volunteers on the ground.”</p>
<p>Because the QR codes are permanently affiliated with the device that scanned
them, they can even be discarded without fear of someone else using them
for unauthorised logins, Mr Chow added.</p>
<h3>Fast and robust</h3>
<p>Residents concerned about data privacy also have nothing to worry about
when their identity cards are scanned with SupplyAlly at the mask collection
points. No personally identifiable information is stored by the SupplyAlly
app—instead, a timestamped digital signature is generated, indicating that
the app has ‘seen’ the identity card barcode before.</p>
<p>“This digital signature serves as a record of who has already collected
the mask and who hasn’t, without needing to know exactly who that person
is,” explained Mr Yeh. Should the digital signature appear again at another
time or place, a rejection message will be displayed on the app, alongside
the timestamp of when the digital signature was last ‘seen’.</p>
<p>“There were cases where residents tried to claim reusable masks from multiple
collection centres,” said Ms Immanuella Lim, software engineer at GovTech.
“SupplyAlly was able to flag that a prior transaction had occurred and
display the exact date and time of that transaction. This gave PA’s volunteers
greater authority to turn away individuals who attempted to ‘game’ the
system to obtain more masks.”</p>
<p>Since its launch, SupplyAlly has allowed PA to manage hundreds of volunteers
and distribute 4.2 million reusable masks. Owing to the app’s lightweight
build and minimal integrations, it could process transactions extremely
rapidly—up to 4,500 transactions per second, with a 50-millisecond response
latency, said Mr Sebastian Quek, software engineer at GovTech. As a result,
there were no queues at the mask collection points. This was especially
important at a time when safe distancing was being strictly enforced to
prevent community spread of the coronavirus.</p>
<p>“We’ve received feedback from the volunteers that SupplyAlly was very
easy to use. At the same time, we’ve seen posts on Facebook by residents
who said that the mask collection was quick and seamless, so our team is
happy with the outcome,” said Mr Quek.</p>
<h3>An ally in more ways than one</h3>
<p>Although mask distribution was the first operation that relied on SupplyAlly,
the GovTech team notes that the mobile app is relevant to other situations
requiring large-scale coordination of manpower and accounting of resources
or supplies. Mr Lim highlighted that Engineering Good, a local non-profit
organisation, is tapping SupplyAlly to distribute refurbished laptops to
needy students for home-based learning during the ‘circuit breaker’ period.</p>
<p>“Engineering Good is thankful for GovTech’s partnership. With SupplyAlly,
we hope to eliminate duplication in our efforts and optimise the efforts
of our volunteers and the beneficiary organisations,” said Mr Johann Annuar,
executive director of Engineering Good.</p>
<p>By leveraging cloud technologies and working across multiple development
environments while adopting an agile approach to software engineering,
GovTech stands ready to support other nationwide efforts in this uncertain
time of COVID-19.</p>