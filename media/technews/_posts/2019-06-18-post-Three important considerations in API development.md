---
layout: post
title: Three important considerations in API development
permalink: /media/technews/three-important-considerations-in-api-development/
image: /images/technews/3_important_considerations_in_API_development_1.jpg
date: 2019-06-18
description: "Learn from the MyInfo team at GovTech on essential aspects of API
  development: standards, security, and documentation. 🛠️🔒📚"
variant: tiptap
---
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Application programming interfaces (APIs) are essential for the interoperability of digital services" src="/images/technews/3_important_considerations_in_API_development_1.jpg">
</div>
<h3>Application programming interfaces (APIs) are essential for the interoperability of digital services.</h3>
<h4>The MyInfo team at GovTech encourages the tech community to keep standards, security and documentation in mind when developing APIs.</h4>
<p>You’re thinking about taking a holiday, but before you purchase your air
tickets, you decide to use the fare aggregator website Skyscanner to get
a sense of how much your flight may cost. Simply by keying in your desired
flight dates and clicking on the ‘search’ button, you receive a list of
fares from various airlines for comparison. It’s incredibly convenient,
but it doesn’t happen magically.</p>
<p>Behind the scenes, application programming interfaces (APIs) serve as
digital messengers, carrying requests from the Skyscanner website to each
airline’s database and then shutting back with the desired information.
APIs are responsible for allowing digital applications to communicate with
one another and enabling seamless data sharing among organisations. Content-based
systems such as Facebook and Twitter expose web APIs for other systems
to easily consume and publish content, while others like Google expose
functionalities or features which can be embedded on a website.</p>
<p>At the Government Technology Agency of Singapore (GovTech), we’re harnessing
the power of APIs to create better government digital services for citizens
and businesses.</p>
<p>For example, when a citizen uses&nbsp;<a href="https://www.singpass.gov.sg/myinfo/common/aboutus" class="editor-rtfLink" rel="noopener noreferrer nofollow" target="_blank">MyInfo</a>&nbsp;to
transact with the government, APIs are running in the background to extract
and compile information from multiple data sources. Organisations are welcome
to&nbsp;<a href="https://www.ndi-api.gov.sg/library/trusted-data/myinfo/introduction" class="editor-rtfLink" rel="noopener noreferrer nofollow" target="_blank">work with GovTech using our NDI {api} platform</a>&nbsp;to
tap on MyInfo and collaborate with the government on other digital projects.</p>
<p>If you are building an API library, the MyInfo team would recommend you
consider these three important aspects.</p>
<p></p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="MyInfo team from GovTech explaining the 3 considerations in API development" src="/images/technews/Three_important_considerations_in_API_development_2.jpg">
</div>
<h4>1. Standards</h4>
<p>Good API design is the key to adoption. Just as the USB port helped unify
the interface by which electronic devices connect to one another, API standards
ensure that digital applications follow a common set of rules and ‘speak
the same language’.</p>
<p>The World Wide Web Consortium (W3C) is the international community responsible
for defining and updating these standards, which recommend that web APIs
be delivered over the Hypertext Transfer Protocol Secure, or HTTPS system.
In essence, this means that data is encrypted before being sent over a
secure internet connection, SSL certificates for sender and recipient websites
are appropriately installed and signed, and domain names check out.</p>
<p>Also, web API responses should be in XML or JSON format. As the term ‘format’
implies, data returned in the response should be structured in a specific
way so as to make it readable across multiple web applications. Uniform
resource identifiers (URIs)—a string of text or numbers specifying a resource
(such as a user profile) should be used as well. Importantly, APIs should
be stateless; that is, authentication or authorisation protocols should
not depend on cookies or sessions.</p>
<p>Given that APIs may require frequent updates, version control for each
API is essential to maintain an organised API library. Following these
standards in API development will help expedite the development process
while ensuring interoperability between web applications.</p>
<h4>2. Security</h4>
<p>Rather than being built in only as an afterthought, security should be
integral to the process of API development. This is especially important
because, very often, APIs are the entry points to your system data or functionality.
Like a castle that is protected by a moat, high walls, and other internal
defences, a multi-layered approach to securing APIs and their associated
applications is recommended.</p>
<p>Firstly, network layer security should be in place. This secures the communication
channel between applications (e.g. to only allow communications via HTTPS)
and prevents programmes known as ‘sniffers’ from illegitimately monitoring
network traffic or deciphering data. This should be accompanied by robust
application layer security, which acts like bouncers at points where digital
applications interact with other network elements, serving to protect against
malicious attacks that expose private information.</p>
<p>Another good practice is to enforce IP whitelisting, which involves creating
lists of trusted IP addresses or IP locations from which users can access
an application. For more sensitive applications, the API should also require
user identification, which should be established using different authentication
schemes such as Basic Authentication or Open Authorisation.</p>
<h4>3. Documentation</h4>
<p>Well-designed APIs without good documentation and support are like a good
company without a sales and customer relations department. This is because
if an API's structure and function—and therefore, value—is not well communicated
to someone other than its creator, it will not be adopted or plugged into
any application ecosystem.</p>
<p>Good API documentation should be easy to read and interpret and contain
information such as developer environments, URIs, parameters and response
formats, security mechanisms, etc. Ideally, it should be supported by tutorials,
examples, and sample codes so that developers can easily integrate the
APIs with their applications.</p>
<p>Furthermore, instead of regular content creation and maintenance tools
and/or text editors, we suggest using modern and widely adopted standards
such as OpenAPI Specification to provide potential developers with a good
experience when adopting an API solution.</p>
<p>Finally, nothing is more frustrating than encountering a problem and having
no one to reach out to for help. If you are the creator of an API, do leave
your contact details and respond to queries from potential users within
a reasonable timeframe. Your community will thank you for it.</p>
<p></p>