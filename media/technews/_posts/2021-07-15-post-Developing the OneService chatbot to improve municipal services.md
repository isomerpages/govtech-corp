---
layout: post
title: Developing the OneService chatbot to improve municipal services
permalink: /media/technews/developing-the-one-service-chatbot/
image: /images/technews/Developing_the_OneService_chatbot_to_improve_municipal_services_1.png
date: 2021-07-15
description: 🤖 Explore the future of municipal issue reporting with the
  OneService Chatbot on WhatsApp and Telegram. Automate case filing and
  streamline services. 🌐
variant: tiptap
---
<p>When the Municipal Services Office (MSO) was established in 2014, it was
billed as a one-stop shop for people to provide feedback on day-to-day
issues like malfunctioning corridor lights, leaky covered walkways, and
littered common areas. The next year, the OneService App was launched to
receive feedback digitally.</p>
<p>In line with MSO’s vision to continuously improve their services and push
the technical boundaries for gathering municipal issues through other means,
MSO worked with GovTech to develop the OneService chatbot for WhatsApp
and Telegram. This enables citizens to easily lodge a case and provide
additional, crucial information about the complaint through commonly used
social messaging apps, such as WhatsApp and Telegram. Powered by machine
learning, the Chatbot would be able to:</p>
<p>1) Automatically identify the nature of the complaint and classify it
into the appropriate category (killer litter, illegal parking, etc),</p>
<p>2) Extract the relevant details of the incident that needs attention (location,
address, landmark, when it occurred, etc), fill in the feedback template,
and get the user to verify and provide additional details.</p>
<p>3) And identify the correct government agency that should take action
(NEA, NParks, LTA, etc) and pass the case on.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Chatting with the OneService chatbot via Whatsapp to report issues" src="/images/technews/Developing_the_OneService_chatbot_to_improve_municipal_services_1.png">
</div>
<p><em>Access municipal services through a platform which is already familiar to users? Yes! Photo: GovTech</em>
</p>
<p>So how did the Moments of Life Division’s Virtual Intelligent Chat Assistant
(VICA) Team and the Data Science and Artificial Intelligence Division’s
GovText team work together to develop a chatbot capable of having a conversation
such as the one below? Read on to find out.</p>
<h3>Identifying the case type</h3>
<p>With the OneService app in operation since 2015, MSO has collected a substantial
amount of feedback from the public.</p>
<p>Every time a case is looked into, an officer will tag a case with its
corresponding case type, and this information is stored in the database.
Since the feedback submitted through the Chatbot will be similar to that
submitted through the app, we can use the app’s data to train the Chatbot’s
case type categoriser.</p>
<p>Essentially, this means feeding both the feedback text and case type of
each case to the categoriser so that it learns to associate certain words
and patterns in the text with its corresponding case type. Drawing from
its experience, the case type categoriser will look for relevant words
and patterns to help it make the best guess of what the correct case type
should be, given just the feedback text.</p>
<p>Armed with over 160,000 cases from two years’ worth of OneService app
data, we tried out different techniques in Natural Language Processing
(the field of getting computers to understand human language) and managed
to build a categoriser which can predict the correct case type correctly
80% of the time!</p>
<p>Next, we have to extract the key case details and pre-fill the case form
for the user. This is trickier because, unlike the case type, we had no
existing labelled keywords, as the MSO staff had no need to label the keywords
in their work process.</p>
<p>Hence, we set up an annotation framework and got our MSO colleagues to
help us annotate the words within the feedback text with labels representing
the types of important information required to resolve a case, such as
the dates and times the incidents occurred, landmarks, and addresses.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Annotation framework for OneService chatbot" src="/images/technews/Developing_the_OneService_chatbot_to_improve_municipal_services_2.png">
</div>
<p>All in all, our MSO colleagues labelled text from 5,600 cases, yielding
us these annotations.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Statistics of the types of incidents and issues reported" src="/images/technews/Developing_the_OneService_chatbot_to_improve_municipal_services_3.png">
</div>
<p>We used these prepared examples to train a case details recogniser, which
can identify the different types of key information with 85 per cent accuracy.</p>
<p>At this stage, we are able to automatically identify the nature of the
complaint, extract the relevant details, fill out the feedback template,
and prompt the user to add missing information.</p>
<h3>Identify the appropriate agency</h3>
<p>Now that the user has successfully filed the case, it’s time to find the
correct agency to deal with it. As you might already know, municipal services
are overseen by multiple agencies, so it may not always be straightforward
nor simple for the OneService Chatbot to activate the right process.</p>
<p>For this step, in addition to the feedback text and the case type (automatically
tagged and then verified by the user), we will also use the images and
the geolocation submitted by the user.</p>
<p>At this point, you might be asking why we didn’t use the images and geolocation
to help identify the case type. While these additional data helped boost
the accuracy of the case type identification by between 2 and 3 per cent,
the relatively small gain in prediction performance did not justify the
additional time it took to generate the predicted case type. After all,
we don’t want to keep the user waiting for too long when they are conversing
with the Chatbot.</p>
<p>At the agency identification stage, however, the user is no longer involved,
and we can afford to take more time to process the geolocation and image
data.</p>
<p>Geolocations have an important role in identifying the right agency because
some types of cases can be handled by more than one agency based on just
the case description alone. Hence, the agency assigned would depend on
which agency’s land an incident took place in or is nearest to. For example,
if a Tree Pruning case is reported within a housing estate, the nearest
town council will be assigned to handle the case. However, if a similar
case happens in a park (e.g., West Coast Park), NParks will be assigned
to handle the case instead.</p>
<p>As for images submitted by users, we used an objection detection model
to look for cigarette butts, lampposts, ceiling lights, and other items
commonly associated with municipal issues. We do this because the likelihood
of certain agencies dealing with a case increase when certain objects are
present in the images (e.g. trees/bushes -&gt; NPARKs, cigarette butts
-&gt; NEA).</p>
<p>Combining these new data points, we are able to correctly direct cases
to the right agency 85% of the time!</p>
<h3>What to expect</h3>
<p>After making some tweaks based on feedback received from a completed trial
with a small segment of the public, the OneService Chatbot has been “beta”
launched and will be available on WhatsApp and Telegram since July 2021.
Residents can start a conversation with the Chatbot by texting “Hi” to
+65 9821 9004 (WhatsApp) or @OneServiceSG Bot (Telegram).</p>
<p>If you’re creatively attuned, you can also participate in the Chatbot
design competition that will help determine the Chatbot’s avatar and “personality”
for the official launch. More information can be found on the competition’s
website: <a href="https://medium.com/dsaid-govtech/training-the-oneservice-chatbot-to-analyse-feedback-on-municipal-issues-using-natural-language-4302aa5a3946" rel="noopener noreferrer nofollow" target="_blank">https://go.gov.sg/ai-chatbot</a>
</p>
<p><em>Stay tuned for the full launch, where we can look forward to greater convenience when reporting municipal feedback!</em>
</p>
<p><em>For a fuller technical explanation of how the OneService chatbot was developed, check out the&nbsp;<a href="https://medium.com/dsaid-govtech/training-the-oneservice-chatbot-to-analyse-feedback-on-municipal-issues-using-natural-language-4302aa5a3946" class="editor-rtfLink" rel="noopener noreferrer nofollow" target="_blank">blog post</a>&nbsp;by our Data Science and Artificial Intelligence Division!</em>
</p>
<p></p>