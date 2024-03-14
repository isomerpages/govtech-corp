---
layout: post
title: How AI and a camera phone help keep food on our tables
permalink: /media/technews/how-ai-and-a-camera-phone-help-keep-food-on-our-tables/
image: /images/technews/rotifer_microscope__2_.png
date: 2021-03-30
description: "🐟🔬 Discover how AI and camera phones are revolutionizing fish
  farm productivity by automating rotifer examination. #FoodSecurity 🌊🍽️"
variant: tiptap
---
<p>What did you have for lunch? Chances are, most of the ingredients came
from overseas as Singapore imports more than 90 per cent of its food.</p>
<p>But with global supply chains under stress from the ongoing pandemic,
it has become all the more important to achieve Singapore’s&nbsp;<a href="https://www.channelnewsasia.com/news/singapore/singapore-produce-30-own-food-up-from-10-nutritional-needs-11320426" class="editor-rtfLink" rel="noopener noreferrer nofollow" target="_blank">“30 by 30” goal</a>&nbsp;of
producing 30 per cent of our food needs on our shores by 2030.</p>
<p>To hit this target, local farms will have to ride on tech to supercharge
productivity – as seen in a project using AI and camera phones to improve
efficiency at fish farms.</p>
<h3>First, a primer on how fish farms work</h3>
<p>Large-scale fish production is essentially about rearing fish larvae to
a size that’s ready for our dinner tables. The fish larvae feed on a type
of plankton known as rotifers, which are tiny aquatic animals that are
optimal food due to their diminutive size.</p>
<p>Ensuring an adequate supply of rotifers is a huge challenge for fish farms
as fish larvae have a voracious appetite. To produce 250,000 pieces of
fish fry, between three and four billion rotifers are needed to feed the
requisite amount of fish larvae in the first two weeks alone! And since
fish larvae need to be fed every few hours, a disruption of rotifer supply
for just a single day can lead to a significant loss in harvest.</p>
<h3>Who said eye power isn’t useful?</h3>
<p>To prevent such a catastrophe, hatchery technicians – including Singapore
Food Agency (SFA) staff – have to manually examine samples from the rotifer
supply. Using a microscope, they assess the rotifers’ swimming activity,
look out for contaminants such as ciliates, and implement mitigating action
to improve the health of the rotifers if needed. As you can see from the
images below, examining the rotifers even with the help of a microscope
is no simple task and it takes one well-trained staff about 40 minutes
daily to vet the samples.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Rotifers under a microscope" src="/images/technews/rotifer_microscope__1__compressed.gif">
</div>
<p><em>Rotifers under a microscope</em>
</p>
<p>Given the laborious nature of the work, automation was explored but no
off-the-shelf products were found. Hence, GovTech and SFA teamed up to
develop a solution and turned to Artificial Intelligence (AI) to save the
technicians precious time as well as from eye strain.</p>
<h3>Which image capturing device to use?</h3>
<p>To create a machine that could automatically examine samples, the team
first had to capture images of the samples with a good balance of quality
and cost effectiveness. SFA considered four different methods – a laboratory
microscope; a basic student microscope; a table magnifier; and a camera
phone. Based on user feedback, the camera phone was picked as it was a
cheap solution that was easy to use and produced photo resolutions that
were sufficient for this project.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Review of image capturing devices used to analyse the rotifers" src="/images/technews/rotifer_microscope__2_.png">
</div>
<p><em>Image capturing devices review</em>
</p>
<h3>Creating intelligence</h3>
<p>AI works by training a machine through examples. For instance, you start
training a computer by showing it 1000 photos of cats and 1000 photos of
dogs. Thus, when you show it a new, previously unseen photo, it can easily
identify the subject of the photo and go: “Based on the photos I’ve seen
in the past, this photo looks more like a cat than a dog. Aha, it’s a cat!”
But crucially, each training photo has to be correctly labelled “cat” or
“dog” so the machine learns to identify what cats and dogs look like.</p>
<p>Similarly, images captured of the rotifer sample have to be carefully
annotated so the machine learns what healthy rotifers look like.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Different types of rotifers and how to differentiate them based on physical appearances" src="/images/technews/rotifer_microscope__3_.png">
</div>
<p><em>Breakdown of the 6 rotifer classes</em>
</p>
<p>So an image like this:</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Rotifers in a petri-dish being analysed" src="/images/technews/rotifer_microscope__4_.jpg">
</div>
<p><em>Different classes of rotifers in a water sample</em>
</p>
<p>Has to be painstakingly labelled by SFA officers who have the necessary
knowledge, producing something like this:</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Rotifer classes labelled from the petri-dish" src="/images/technews/rotifer_microscope__5_.jpg">
</div>
<p><em>Rotifer classes labelled on the water sample</em>
</p>
<p>The team also cropped the photos so that distracting shadows in the background
were eliminated. As this was a time-consuming process, it explored and
succeeded in automating the cropping.</p>
<p>After this is done, the team separated its stash of images into two groups,
one to train the machine (training images) and the other to evaluate its
performance (test images). The training images were fed to the AI model
so that it learns (through the labels on the images) to differentiate health
rotifers from unhealthy ones.</p>
<p>Next, the AI model is given the test images, but without the labels on
the rotifers. The AI model has to identify each rotifer from the test images,
based on its earlier training. The outcomes to its identification on the
test images are then compared to labels done by the SFA officers to evaluate
how well the model performed. Although the machine didn’t do a good job
identifying unhealthy rotifers, it fared much better in finding the healthy
ones.</p>
<p>Based on this result, the model was rolled out to the hatchery technicians
for beta testing and collection of more data for model refinement.</p>
<h3>An instant calculator in your hands</h3>
<p>The AI model was approved by SFA and the team went on to make a mobile
app, allowing users to upload images that will be automatically assessed
instantly.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Application of the rotifer counting technology seen from a smartphone." src="/images/technews/rotifer_microscope__6_.jpg">
</div>
<p><em>Application for rotifers counting results</em>
</p>
<p>Instead of 40 minutes of tedious “eye-power”, all it takes now is just
a minute of photo uploading to evaluate the rotifer samples. A single hatchery
technician is needed to prepare the samples, photograph them, and pass
the images to the machine. Besides drastically improving productivity,
the SFA officers and farmers also have more time to focus on higher-value
tasks.</p>
<p>The project was awarded the Ministry of Sustainability and the Environment
(MSE) Innovation Award in 2020. Moving forward, the team hopes to expand
the project to other forms of object detection such as counting and classifying
small crustaceans. After all, more time saved ultimately means strengthened
food security, ensuring our food shelves remain well stocked.</p>