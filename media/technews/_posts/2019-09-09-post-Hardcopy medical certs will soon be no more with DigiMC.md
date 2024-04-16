---
layout: post
title: Hardcopy medical certs will soon be no more with DigiMC
permalink: /media/technews/hardcopy-medical-certs-will-soon-be-no-more-with-digimc/
image: /images/technews/Hardcopy_medical_certs_will_soon_be_no_more_with_DigiMC_1.jpg
date: 2019-09-09
description: Say goodbye to hardcopy medical certificates! DigiMC by GovTech
  digitalises MC issuance, ensuring authenticity and convenience for patients
  and employers.
variant: tiptap
---
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="With Digital MC, you can view your official medical certificates online" src="/images/technews/Hardcopy_medical_certs_will_soon_be_no_more_with_DigiMC_1.jpg">
</div>
<h3>Hardcopy medical certificates will soon be a thing of the past with DigiMC, a system that digitalises the issuance and submission of medical certificates.</h3>
<p>For most working adults, submitting a medical certificate (MC) is a certainty
when one falls sick. In 2017, about one million hardcopy MCs were generated
by SingHealth, Singapore’s largest public healthcare cluster. Not only
are such documents easily misplaced, but they can also be damaged or even
forged. Organisations also experience administrative hassle when keeping
records of all their employees’ submissions.</p>
<p>Seeking to overcome these pain points, a team from Open Government Products
(OGP), a division of the Government Technology Agency of Singapore (GovTech),
has built a digital medical certificate system called&nbsp;<a href="https://www.mc.gov.sg/" class="editor-rtfLink" rel="noopener noreferrer nofollow" target="_blank">DigiMC</a>.
Product managers Mr Chong Zi Xin and Ms Annabelle Ng at OGP shared with
TechNews some of the key features of DigiMC and explained how the system
is being integrated into Singapore’s broader healthcare ecosystem.</p>
<p></p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="The GovTech team behind DigiMC" src="/images/technews/Hardcopy_medical_certs_will_soon_be_no_more_with_DigiMC_2.jpg">
</div>
<p><em>The GovTech team behind DigiMC</em>
</p>
<h3>Healthy ambitions</h3>
<p>The team’s first goal was to create a system allowing clinics and hospitals
to generate MCs in digital form, fulfilling three criteria: the digital
MCs must be verifiable as true copies, be sharable between healthcare providers,
patients and employers, and be easy to incorporate into existing workflows.</p>
<p>With DigiMC, all a doctor has to do is click ‘save’ on their existing
MC creation interface, and a digital MC is generated using a URL that is
sent to the patient’s registered phone number. “Instead of printing a hardcopy
MC, an SMS message [containing the URL for accessing the digital MC] is
sent to the patient, which they can forward to their employers,” Ms Ng
explained.</p>
<p>Digital MCs are also less likely to be misplaced, and the SMS messages
can be backed up on commercial Cloud services for later reference, said
Ms Ng, adding that the URL does not expire, so the MC can be accessed perpetually.</p>
<p>However, as MCs may contain private information such as NRIC, concerns
have been raised over the privacy of data disseminated on DigiMC. For instance,
what if a patient inputs the wrong phone number during registration at
a clinic? Will his or her MC be disclosed to a stranger receiving the SMS
message?</p>
<p>The OGP team has thought through these vulnerabilities and put safeguards
in place. For instance, a front-end safeguard requires patients to unlock
the digital MC with their date of birth (DOB). “For now, it is a one-time
unlock. Once the digital MC is unlocked, it can be forwarded, and subsequent
users would not have to unlock it again,” said Ms Ng. In future, the team
may implement a relock with DOB after seven days to avoid exposure in the
long run. Thereafter, each subsequent view will require the patient’s DOB
to unlock.</p>
<p>However, the key way to prevent sending information to the wrong phone
numbers is still through physical verification, where one updates his or
her phone number in the healthcare institution’s system while registering
for an appointment at the clinic. On the off chance that a patient accidentally
inputs a wrong phone number during registration, the DOB unlock serves
as an additional safeguard.</p>
<h3>Digital but not doctored</h3>
<p>Convenience aside, employers may still be concerned with the authenticity
of digital MCs. To allay such fears, each document generated via DigiMC
is hosted on a government-affiliated web domain (<a href="https://www.mc.gov.sg/" rel="noopener noreferrer nofollow" target="_blank">mc.gov.sg</a>), instilling legitimacy.</p>
<p>Moreover, a unique hash—a string of alphanumeric characters—assigned to
the end of the URL ensures that each digital MC has a uniquely identifiable
key. “Even if the digital MC is downloaded and saved as a PDF, employers
can still validate the document using the URL printed at the bottom of
the digital MC [to make sure that the digital MC has not been altered],”
said Mr Chong.</p>
<p>The system has been carefully designed to facilitate seamless integration.
For example, DigiMC does not alter the doctor’s workflow for generating
MCs, and the hospital interface that the staff sees remains the same. On
the backend, data from the healthcare institution’s system are managed
by the Integrated Health Information Systems (IHiS), sent to DigiMC through
authenticated APIs, and pushed out to patients via SMS.</p>
<p></p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="The process of how DigiMC works" src="/images/technews/Hardcopy_medical_certs_will_soon_be_no_more_with_DigiMC_3.png">
</div>
<h3>Going paperless by 2020</h3>
<p>So far, DigiMC has been piloted at two institutions under SingHealth—the
Singapore General Hospital and the National Heart Centre Singapore. Mr
Chong said 95 percent of 179 patients surveyed over a four-month period
said that they were satisfied with the new system.</p>
<p>The OGP team is now focusing on getting a critical user base on board
DigiMC. It plans to implement DigiMC across all SingHealth institutions
by early 2020. DigiMCs will be issued in parallel with hardcopy MCs to
ensure a smooth transition for a few months before the latter is eventually
phased out. This will also allow time for employers to become used to DigiMC
and adapt their internal MC submission procedures accordingly.</p>
<p>The team has also prepared various recommendations on how to handle digital
MCs in their FAQs for employers. However, patients will still be able to
request a paper MC if they require it.</p>
<p>In the longer run, the team also will explore integrating DigiMC with
other government applications such as HealthHub to create a one-stop solution
for all medical records and appointments, Mr Chong concluded.</p>
<p></p>