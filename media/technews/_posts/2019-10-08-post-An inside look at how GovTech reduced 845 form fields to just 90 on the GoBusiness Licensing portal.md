---
layout: post
title: An inside look at how GovTech reduced 845 form fields to just 90 on the
  GoBusiness Licensing portal
permalink: /media/technews/inside-look-at-gobusiness/
image: /images/technews/GoBusiness_Licensing_portal_1.jpg
date: 2019-10-08
description: Learn about the team behind the GoBusiness Licensing portal, their
  challenges, and triumphs in simplifying the licensing process for
  entrepreneurs. 🛠️💼
variant: tiptap
---
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="The GovTech team who helped build the GoBusiness Licensing portal" src="/images/technews/GoBusiness_Licensing_portal_1.jpg">
</div>
<h3>Get to know the GovTech team who helped build the GoBusiness Licensing portal, and learn about their challenges and triumphs along the way.</h3>
<p>So you’ve got a brilliant idea for a new business—you’ve done the sums,
selected an ideal location for a shopfront, found the right partners and
are raring to go. Your first hurdle?</p>
<p>Registering your company with the Accounting and Corporate Regulatory
Authority (ACRA). That’s simple enough, but as many entrepreneurs soon
discover, incorporation is just the first step of a long and sometimes
confusing journey.</p>
<p>Depending on the type of business you intend to run, you need to obtain
different licenses, permits, and certificates from the government before
you can begin operations. At this stage, things often get complicated.</p>
<p>For instance, a would-be restauranteur may have to approach the Urban
Redevelopment Authority to obtain a change-of-use permit for a premise,
the Singapore Food Agency to get a food shop license, the Singapore Civil
Defence Force for a fire safety certificate… the list goes on to yield
a total of 14 separate touch points spanning multiple government agencies—all
just to set up a makan place (eatery)!</p>
<p>“We put ourselves in the shoes of the prospective business owner in the
food sector, and we realised that there was an opportunity to build a service
journey to better guide them to achieve their goals,” said Mr Daniel Chan,
deputy director of Moments of Life (Business) at the Government Technology
Agency of Singapore (GovTech). Thus began the conceptualisation of the
GoBusiness Licensing portal in early 2018.</p>
<h3>An e-advisor to light the way</h3>
<p>Developed in collaboration with the Smart Nation and Digital Government
Office (SNDGO) and the Ministry of Trade and Industry (MTI), the GoBusiness
Licensing portal is meant to streamline regulatory requirements and digitalise
transactions between the government and businesses. This is part of the
larger effort to foster a pro-enterprise environment for businesses to
grow. “The food services sector was chosen primarily because of the complexity
involved in obtaining the right licenses, as well as the relatively high
volume of annual transactions in the sector,” Mr Chan explained.</p>
<p>Before even a single line of code was typed out, the user experience (UX)
team working on GoBusiness consulted with experienced and inexperienced
business owners to figure out hidden frictions in the application processes.
The Restaurant Association of Singapore played an important role in making
these consultations possible between May and September 2018.</p>
<p>“We found that while experienced business owners were able to associate
licenses with the relevant granting agency, newcomers to the food sector
may not know where to start applying to,” said Ms Lim Min Er, UX designer
at GovTech. “Inexperienced users also highlighted to us that licensing
information is frequently siloed at the agency level and that some regulations
were vague to them.”</p>
<p>This formed the basis of the ‘Guided Journey’ feature of the GoBusiness
Licensing portal, whereby users go through a four-step process to identify
which licenses they need and which agency to approach to get their food
business up and running.</p>
<p>In summary, by answering a series of questions about their proposed food
business and the address of the premises, users will be provided with a
list of ‘types’ of business to select from.</p>
<p>After the selection is made, the portal will automatically surface the
license requirements and the relevant granting agencies to applicants,
alongside any associated costs.</p>
<p>“The order and dependencies of licenses will be mapped out for business
owners so that they can navigate the entire process more easily. License
applications can be completed on the GoBusiness platform itself, and the
information will be automatically disseminated to the right avenues by
the system,” said Mr Jonathan Lee, product manager at GovTech.</p>
<h3>Reducing 845 fields to 90</h3>
<p></p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Creating a user flow chart to remove unnecessary steps and form fields to streamline the process" src="/images/technews/GoBusiness_Licensing_portal_2.jpg">
</div>
<p>To achieve this simplicity, however, the GovTech team had to do some major
technical lifting behind the scenes. Imagine coming up with 14 different
travel adaptors to fit the power sockets of different countries. That was
how Mr Charles Koh, software developer at GovTech, described the process
of making sure no hiccups occur when information is requested by the GoBusiness
portal from an agency’s database, or when new data is input on the portal
and sent to the respective agencies.</p>
<p>“Different agencies use different protocols to transmit and receive data,
and some of those methods may be a little bit old—what we call legacy systems,”
Mr Poh Quan Wei, technical product manager at GovTech, added. Hence, the
challenge was to “service wrap” the legacy formats into a configuration
that can be used by GoBusiness.</p>
<p>In this aspect, GovTech’s&nbsp;<a href="https://www.tech.gov.sg/media/technews/getting-to-know-nectar-and-apex" class="editor-rtfLink" rel="noopener noreferrer nofollow" target="_blank">Application Programming Interface Exchange (APEX)</a>&nbsp;came
in handy as a central repository of authorised and searchable application
programming interfaces (APIs) for handling data transactions.</p>
<p>The GovTech team also had to examine the logic of the fields that applicants
need to fill in for each license. For example, one agency may require ‘name’
and ‘surname’ to be input as two separate fields, while another agency
may only have one field for ‘full name’. Finding commonalities and reducing
redundancies in such fields was another challenge the GovTech team had
to overcome. At the end of the process, 845 fields had been whittled down
to just 90, saving substantial time and effort for public officers and
applicants.</p>
<p>Looking to further streamline the license application process, the GovTech
team thought it might be a good idea to create an auto-deduct function
for payments. “Typically, there is an application fee and a license fee,
so we thought business owners would love the convenience of not having
to log in a second time to pay the license fee,” said Mr Lee.</p>
<p>This turned out to be untrue, as the team found out during the usability
testing phase of development. At the earliest stages of setting up their
companies, new business owners preferred to manually process such payments.
Keeping user-centricity in mind, the team eventually removed the auto-deduct
function, though it remains a possible option for licenses that need to
be renewed on a recurrent basis, Ms Lim said.</p>
<h3>Getting better with time</h3>
<p>By May 2019, the GoBusiness Licensing portal was released for beta-testing
by users, to generally positive reviews. New and inexperienced entrepreneurs
felt that the learning curve for setting up a food business was significantly
less steep, and having everything hosted in one place, with a guided onboarding
process, was useful.</p>
<p>Some of the tangible benefits from using the portal include a reduction
of total fees by up to S$500, a reduction of 10-14 days turnaround time
for license applications, and the removal of unnecessary steps in the application
process. Being able to tap on ACRA’s database to pre-populate forms also
makes transactions more convenient, users said. The GoBusiness Licensing
portal has since been launched on 31st October 2019.</p>
<p>The journey doesn’t end here. Users of the portal have requested for further
clarifications on some regulations, so the GovTech team continues to look
into how those regulations can be made more understandable to laymen, perhaps
with infographics. At the same time, GovTech works with other agencies
to carry out process re-engineering to better reconcile front- and back-end
processes, Mr Lee noted.</p>
<p>Going forward, MTI, SNDGO and GovTech will also expand the ‘Guided Journey’
feature to include more licences from other sectors, especially those with
complex licensing requirements, such as the retail sector. Other multi-step
transactions, in the course of businesses’ engagements with the government,
may also benefit from the ‘Guided Journey’ approach, said Mr Chan. “What
we’re working towards is a comprehensive business home page for businesses
to interact seamlessly with the government,” he concluded.</p>
<p></p>