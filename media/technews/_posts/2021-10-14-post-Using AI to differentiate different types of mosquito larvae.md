---
layout: post
title: Using AI to differentiate different types of mosquito larvae
permalink: /media/technews/using-ai-to-differentiate-mosquito-larvae/
image: /images/technews/Using_AI_to_differentiate_different_types_of_mosquito_larvae__1_.jpg
date: 2021-10-14
description: 🦟 Did you know Singapore has over 180 mosquito species? GovTech X
  NEA — using AI tech to identify mosquito larvae species and fight mosquitoes!
  🦠
variant: tiptap
---
<p>Did you know there are more than 180 species of mosquitoes in Singapore?
That’s more than the United States, which has&nbsp;<a href="https://www.mosquito.org/page/funfacts" class="editor-rtfLink" rel="noopener noreferrer nofollow" target="_blank">176 mosquito species</a>.</p>
<p>The most common types in Singapore are the&nbsp;<em>Aedes</em>&nbsp;(which
spread dengue and chikungunya),&nbsp;<em>Culex</em>&nbsp;(which spread
filariasis), and&nbsp;<em>Anopheles</em>&nbsp;(which spread malaria). The
National Environment Agency (NEA) actively monitors mosquito populations,
and correctly identifying different species is an integral part of enabling
targeted measures to eradicate mosquitoes.</p>
<p>To aid NEA in its fight against mosquitoes, GovTech teamed up with the
agency to explore the feasibility of using Artificial Intelligence (AI)
based video analytics to identify mosquito larva species. And the first
step was to understand how the job is being done by humans now.</p>
<h3>How is mosquito species identification done today?</h3>
<p>Currently, trained analysts examine taxonomical characteristics of mosquito
larvae through a microscope. A mosquito larva observed through a microscope
would look like this:</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Anatomy of mosquito larvae" src="/images/technews/Using_AI_to_differentiate_different_types_of_mosquito_larvae__1_.jpg">
</div>
<p><em>Anatomy of mosquito larvae. (Source:&nbsp;<a href="https://www.oecd-ilibrary.org/environment/safety-assessment-of-transgenic-organisms-in-the-environment-volume-8_9789264302235-en" class="editor-rtfLink" rel="noopener noreferrer nofollow" target="_blank">OECD Publication</a>)</em>
</p>
<p>A mosquito larva typically has an ovoid head, thorax, and abdomen of nine
segments. Analysts look for subtle differences to identify different species.
For example, the&nbsp;<em>Ae. aegypti</em>&nbsp;(left) has pitchfork scales,
while the&nbsp;<em>Ae. albopictus</em>&nbsp;(right) has thorn-like scales.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Using AI to differentiate the different types of mosquito larvae based on micro-imaging" src="/images/technews/Using_AI_to_differentiate_different_types_of_mosquito_larvae__2_.jpg">
</div>
<p><em>Source: Florida Medical Entomology Laboratory</em>
</p>
<p>As you can see, analysing mosquito larvae remains a challenging task due
to the high resemblance of various species, especially those within the
same groups. The distinctions among different species are difficult to
identify even for human experts with the naked eye, as subtle distinctions
can only be observed through microscopic scrutiny. Methods of larvae image
analysis mostly rely on manual work, which can be labour-intensive and
prone to human error.</p>
<h3>How did GovTech approach the problem?</h3>
<p>When we saw several studies indicating that different mosquito species
may exhibit different movement patterns, the team explored the use of video
analytics to classify larvae. We focused on the four most common species
in Singapore:</p>
<ul data-tight="true" class="tight">
<li>
<p><em>Aedes aegypti</em>,</p>
</li>
<li>
<p><em>Aedes albopictus</em>,</p>
</li>
<li>
<p><em>Culex quinquefasciatus</em>, and</p>
</li>
<li>
<p><em>Anopheles sinensis</em>
</p>
</li>
</ul>
<h3>Getting the dataset of videos</h3>
<p>NEA used a consumer-grade mobile phone to capture about 6,800 high-quality
videos of between 5 and 50 seconds. The videos were filmed in a controlled
environment so that the lighting, angle and focus were consistent, providing
a “cleaner” dataset.</p>
<p>About 92 per cent of the videos came from lab-reared samples. As they
were grown in a controlled environment, the larvae had fewer variations
within a species in terms of size, colour, body texture, and movement patterns.
The field-collected samples, which were harder to obtain, had more diverse
features, as seen below.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Comparison of lab-reared and field-collected larvae" src="/images/technews/Using_AI_to_differentiate_different_types_of_mosquito_larvae__3_.jpg">
</div>
<p><em>Comparison of lab-reared and field-collected larvae. (Source: National Environment Agency)</em>
</p>
<p>Next, we took still images from the videos at fixed intervals and then
used an automated process to detect the area of interest where the larva
is, crop the images to a consistent size, and rotate the images so that
the head was on top.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Pro-processing steps for identifying the mosquito larvae" src="/images/technews/Using_AI_to_differentiate_different_types_of_mosquito_larvae__4_.jpg">
</div>
<p><em>Pre-processing steps. (Source: GovTech and National Environment Agency)</em>
</p>
<p>These steps produced a sequence of images that can be analysed for differences
in the motion of different species.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Examples of pre-processed inputs of the mosquito larvae variety" src="/images/technews/Using_AI_to_differentiate_different_types_of_mosquito_larvae__5_.jpg">
</div>
<p><em>Examples of pre-processed inputs. (Source: National Environment Agency)</em>
</p>
<p>These images are then split into two sets: the training and test sets.
The training set is fed into the AI model – a neural network called CNN-LTSM
that is good at handling sequences of video frames. The model learns from
the training set to recognise different movement patterns in the video
frames. After it has been trained, the model is then shown the previously
unseen test set and is tasked to predict which species the video frames
come from.</p>
<h3>How did the AI model perform?</h3>
<p>When we first started the project, only lab-reared sample videos were
available. Using this limited dataset, we were able to achieve more than
99 per cent in weighted F1 score, which judges how accurate the model is!
The model could not only correctly classify species from different groups
(<em>Aedes</em>&nbsp;vs.&nbsp;<em>Culex</em>&nbsp;vs.&nbsp;<em>Anopheles</em>),
but it also managed to differentiate seemingly lookalike species (<em>Ae. aegypti</em>&nbsp;vs.&nbsp;<em>Ae. albopictus</em>)
from the same group. This was not surprising as the lab samples were consistent
in appearance within the same group.</p>
<p>However, when the lab-sample-trained model was tested on the field-collected
samples, the F1 score dropped to about 89 per cent. Clearly, the different
appearances of field-collected larvae gave the model difficulties. For
example, the appearance of lab (left) and field (right)&nbsp;<em>Ae. aegypti</em>&nbsp;looked
very different.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Colour and pattern differences in lab-reared and field-collected samples" src="/images/technews/Using_AI_to_differentiate_different_types_of_mosquito_larvae__6_.jpg">
</div>
<p><em>Colour and pattern differences in lab-reared (left) and field-collected (right) samples. (Source: National Environment Agency)</em>
</p>
<p>We had known of this problem and tried to adjust for it by adding random
colour differences to our lab-collected images. However, this solution
was clearly not enough to mitigate the problem.</p>
<p>Subsequently, we introduced more field samples to train the model and
after a few iterations, we were able to build up our F1 score to almost
100 per cent!</p>
<h3>What lies ahead</h3>
<p>The result of the project has demonstrated the viability of using AI to
classify the four most common species of mosquito larvae in Singapore.</p>
<p>However, there are a few caveats to note. The end-to-end process, including
image processing and model training, is computationally expensive. Also,
while the model can recognise the four species effectively, we don’t know
how well it can handle new species that it has not seen. It will likely
have to be retrained for every new mosquito larva we introduce.</p>
<p>Nonetheless, this project has set the stage for developing complex AI
models to handle challenging object classification problems and we are
excited about enhancing it further to apply to other cases!</p>
<h4><strong>Related Content</strong></h4>
<ul data-tight="true" class="tight">
<li>
<p><a href="https://www.tech.gov.sg/media/technews/subscribe?utm_medium=recommender_0&amp;utm_source=aHR0cHM6Ly93d3cudGVjaC5nb3Yuc2cvbWVkaWEvdGVjaG5ld3MvdXNpbmctYWktdG8tZGlmZmVyZW50aWF0ZS1tb3NxdWl0by1sYXJ2YWU=&amp;utm_content=aHR0cHM6Ly93d3cudGVjaC5nb3Yuc2cvbWVkaWEvdGVjaG5ld3Mvc3Vic2NyaWJl" class="editor-rtfLink" rel="noopener noreferrer nofollow" target="_blank">TechNews Newsletter</a>
</p>
</li>
<li>
<p><a href="https://www.tech.gov.sg/get-involved/tech-kaki-newsletter?utm_medium=recommender_1&amp;utm_source=aHR0cHM6Ly93d3cudGVjaC5nb3Yuc2cvbWVkaWEvdGVjaG5ld3MvdXNpbmctYWktdG8tZGlmZmVyZW50aWF0ZS1tb3NxdWl0by1sYXJ2YWU=&amp;utm_content=aHR0cHM6Ly93d3cudGVjaC5nb3Yuc2cvZ2V0LWludm9sdmVkL3RlY2gta2FraS1uZXdzbGV0dGVy" class="editor-rtfLink" rel="noopener noreferrer nofollow" target="_blank">Tech Kaki Newsletter</a>
</p>
</li>
<li>
<p><a href="https://www.tech.gov.sg/media/technews/is-your-smartphone-slowing-down-get-it-back-up-to-speed-with-these-hacks?utm_medium=recommender_2&amp;utm_source=aHR0cHM6Ly93d3cudGVjaC5nb3Yuc2cvbWVkaWEvdGVjaG5ld3MvdXNpbmctYWktdG8tZGlmZmVyZW50aWF0ZS1tb3NxdWl0by1sYXJ2YWU=&amp;utm_content=aHR0cHM6Ly93d3cudGVjaC5nb3Yuc2cvbWVkaWEvdGVjaG5ld3MvaXMteW91ci1zbWFydHBob25lLXNsb3dpbmctZG93bi1nZXQtaXQtYmFjay11cC10by1zcGVlZC13aXRoLXRoZXNlLWhhY2tz" class="editor-rtfLink" rel="noopener noreferrer nofollow" target="_blank">Is your smartphone slowing down? Get it back up to speed with these hacks</a>
</p>
</li>
<li>
<p><a href="https://www.tech.gov.sg/media/technews/five-movies-and-shows-that-can-teach-you-about-tech?utm_medium=recommender_3&amp;utm_source=aHR0cHM6Ly93d3cudGVjaC5nb3Yuc2cvbWVkaWEvdGVjaG5ld3MvdXNpbmctYWktdG8tZGlmZmVyZW50aWF0ZS1tb3NxdWl0by1sYXJ2YWU=&amp;utm_content=aHR0cHM6Ly93d3cudGVjaC5nb3Yuc2cvbWVkaWEvdGVjaG5ld3MvZml2ZS1tb3ZpZXMtYW5kLXNob3dzLXRoYXQtY2FuLXRlYWNoLXlvdS1hYm91dC10ZWNo" class="editor-rtfLink" rel="noopener noreferrer nofollow" target="_blank">5 Movies and TV Shows that can teach you about tech!</a>
</p>
</li>
<li>
<p><a href="https://www.tech.gov.sg/media/technews/mosquitoes-and-data-fall-into-place-with-nea-gravitrap-project?utm_medium=recommender_4&amp;utm_source=aHR0cHM6Ly93d3cudGVjaC5nb3Yuc2cvbWVkaWEvdGVjaG5ld3MvdXNpbmctYWktdG8tZGlmZmVyZW50aWF0ZS1tb3NxdWl0by1sYXJ2YWU=&amp;utm_content=aHR0cHM6Ly93d3cudGVjaC5nb3Yuc2cvbWVkaWEvdGVjaG5ld3MvbW9zcXVpdG9lcy1hbmQtZGF0YS1mYWxsLWludG8tcGxhY2Utd2l0aC1uZWEtZ3Jhdml0cmFwLXByb2plY3Q=" class="editor-rtfLink" rel="noopener noreferrer nofollow" target="_blank">Mosquitoes and data fall into place with NEA’s Gravitrap project</a>
</p>
</li>
</ul>
<p></p>