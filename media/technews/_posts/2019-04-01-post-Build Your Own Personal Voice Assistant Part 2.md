---
layout: post
title: Build Your Own Personal Voice Assistant Part 2
permalink: /media/technews/build-your-own-personal-voice-assistant-part2/
image: /images/personal_voice_assistance_head_2.jpg
date: 2019-04-01
description: Part 2 of build your DIY voice assistant with Raspberry Pi & Google
  Assistant! Control lights 🌟 & more using Sonoff WiFi plug. Easy setup guide
  included!
variant: tiptap
---
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="personal voice assistant" src="/images/technews/personal-voice-assistance-head.jpg">
</div>
<h3>In the previous <a href="https://www.tech.gov.sg/media/technews/build-your-own-personal-voice-assistant-part1" rel="noopener noreferrer nofollow" target="_blank">post</a>, we covered how to set up the Raspberry Pi and how to set up your microphone and speaker for your DIY voice assistant. In this last part of the tutorial, we will go through the process of setting up the Google Assistant and linking up the light for the finished product.</h3>
<p>&gt; Hardware and software you need and where to find them:</p><pre><code>&lt;th&gt;Hardware/Software&lt;/th&gt;
&lt;th&gt;What does it do?&lt;/th&gt;
&lt;th&gt;Where can I buy it?&lt;/th&gt;</code></pre><pre><code>&lt;td&gt;Browser Logged Into a Google Account&lt;/td&gt;
&lt;td&gt;To download the required software developer kit from Google and link the smart WiFi plug&lt;/td&gt;
&lt;td&gt;[nil]&lt;/td&gt;</code></pre><pre><code>&lt;td&gt;Lightbulb With Power Plug&lt;/td&gt;
&lt;td&gt;A home appliance that can be controlled by the smart WiFi plug&lt;/td&gt;
&lt;td&gt;Any hardware store&lt;/td&gt;</code></pre>
<table>
<tbody>
<tr>
<td rowspan="1" colspan="1">
<p></p>
</td>
<td rowspan="1" colspan="1">
<p></p>
</td>
<td rowspan="1" colspan="1">
<p></p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="3">
<p><strong>FOR VOICE CONTROL SETUP</strong>
</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p></p>
</td>
<td rowspan="1" colspan="1">
<p></p>
</td>
<td rowspan="1" colspan="1">
<p></p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="3">
<p><strong>FOR LIGHT CONTROL CIRCUIT</strong>
</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p></p>
</td>
<td rowspan="1" colspan="1">
<p></p>
</td>
<td rowspan="1" colspan="1">
<p></p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>Sonoff WiFi UK Plug (We use Sonoff in this tutorial but feel free to use
any brand of WiFi plug)</p>
</td>
<td rowspan="1" colspan="1">
<p>The plug that links with the Google account for controlling the lights</p>
</td>
<td rowspan="1" colspan="1">
<p>Tech stores or online</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>2.4Ghz WiFi</p>
</td>
<td rowspan="1" colspan="1">
<p>Required to link the WiFi plug</p>
</td>
<td rowspan="1" colspan="1">
<p>[nil]</p>
</td>
</tr>
</tbody>
</table>
<p><em>Retailers are provided for reference only. GovTech TechNews is not affiliated with any of the retailers listed in this tutorial.</em> 
<br>
</p>
<h3>Setting up the Google Project</h3>
<ol>
<li>
<p>On the Pi's browser, sign in to your Google Account. Then go to Google
<a href="https://console.actions.google.com/" rel="noopener noreferrer nofollow" target="_blank">Action Console</a>and click "New Project". Give a name to the project
and click "Create Project". This will take a while so proceed with the
next steps while leaving the tab open.</p>
</li>
<li>
<p>Go to <a href="https://console.developers.google.com/apis/api/embeddedassistant.googleapis.com/overview?pli=1" rel="noopener noreferrer nofollow" target="_blank">Google Assistant API website</a> and
click Enable. This will allow us to use the Google Assistant on our Pi.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Go to Google Assistant API website" src="/images/technews/pi1and2.jpg">
</div>
</li>
<li>
<p>Go to <a href="https://myaccount.google.com/activitycontrols?pli=1" rel="noopener noreferrer nofollow" target="_blank">Activity Control Panel</a> and
make sure the following activities are turned on.</p>
<ul data-tight="true" class="tight">
<li>
<p>Web and App Activity (including Chrome history checkbox)</p>
</li>
<li>
<p>Device Information</p>
</li>
<li>
<p>Voice and Audio Activity</p>
</li>
</ul>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Go to Activity Control Panel" src="/images/technews/pi34.jpg">
</div>
</li>
<li>
<p>Go back to Google <a href="https://console.actions.google.com" rel="noopener noreferrer nofollow" target="_blank">Action Console</a> and find the
Device Registration button.</p>
<p><em>(If you can't find the page for device registration, use </em><code>https://console.actions.google.com/u/0/project/{project-name}/deviceregistration/</code>.
Note that you should change the {project-name} in the link to the project
name you have created in Step 1)</p>
<p>Click on it and then click on Register Model. You can enter any name you
like for your Pi and Manufacturer name* (the latter is not important but
you still need to key in something), and set the Device type to Auto.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Go back to Google Action Console I" src="/images/technews/pi567.jpg">
</div>
</li>
<li>
<p>Click on Register Model and download the OAuth2.0 Credentials. After the
file has been downloaded, move it to the /home/pi directory</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Click on Register Model and download the OAuth2.0" src="/images/technews/8pi.png">
</div>
</li>
<li>
<p>Check if python is installed on the Pi by typing in the Terminal</p><pre><code> phyton</code></pre>
<p>Python should be installed by default in Raspbian. If it is installed,
you will see the following:</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Python should be installed by default in Raspbian" src="/images/technews/23pi.png">
</div>
<p>Exit out of the python programme by pressing ctrl-d.
<br>
</p>
<p>If it is not installed, install it by typing</p><pre><code> sudo apt-get install python</code></pre>
</li>
<li>
<p>Recommended by Google: Make a Python virtual environment for Google Assistant
by first installing virtual environment and virtual environment wrapper.</p><pre><code> pip install virtualenv
 pip install virtualenvwrapper</code></pre>
<p>After this is done, configure the virtual environment wrapper</p><pre><code> export WORKON_HOME=~/Envs
 source ~/.local/bin/virtualenvwrapper.sh</code></pre>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="configure the virtual environment wrapper" src="/images/technews/10pi.png">
</div>
<p>Make the environment for Google Assistant to run in</p><pre><code> mkvirtualenv env</code></pre>
<p>*If the above step throws an error, it might be that the virtualenv that
did not install properly. Try the following code to reinstall virtualenv:</p><pre><code> sudo apt install --reinstall virtualenv</code></pre>
</li>
</ol>
<h3>Setting up the lights</h3>
<ol>
<li>
<p>As we are using the Sonoff WiFi UK Plug switch in this tutorial, download
eWeLink app from the Google Play Store for Android or App Store for iOS
devices.</p>
</li>
<li>
<p>Sign up for an eWeLink account.</p>
</li>
<li>
<p>Turn on the WiFi plug and click on Add Device (plus sign) in the eWeLink
app.</p>
</li>
<li>
<p>Choose the first option (Quick Pairing Mode)
<br>
</p>
</li>
<li>
<p>Next, choose a WiFi network (note the switch only supports 2.4GHz WiFi)
and provide the credentials to the WiFi.</p>
</li>
<li>
<p>The app will then attempt to pair the switch and on success it will ask
you to name the device. You can name the device however you prefer.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="pair the switch I" src="/images/technews/pi151617.jpg">
</div>
</li>
<li>
<p>Once connected, you should be able to control the plug through the app.
Try it out by plugging the light into the plug and switching the plug on
and off through the app.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Control the plug through the app" src="/images/technews/pi18.jpg">
</div>
</li>
<li>
<p>Download Google Home on your phone. Make sure it is logged into the same
account you used for the Google Assistant setup.</p>
</li>
<li>
<p>Go to Add Device and select "Have something already set up?" option. Search
for Smart We Link on the list of support devices and select it.</p>
</li>
<li>
<p>Log into your eWeLink account and allow Google access.</p>
</li>
<li>
<p>Add the switch device which you have named in step 6. Assign it to a room
(whichever room you like).</p>
</li>
<li>
<p>Now you can control the light through your Home app as well.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="Now you can control the light through your Home app" src="/images/technews/pi2122.jpg">
</div>
</li>
<li>
<p>Try controlling the light through Raspberry Pi Assistant by saying "Ok
Google" or "Hey Google", following with "Turn on [your device name from
step 6]" The light should turn on.</p>
</li>
<li>
<p>To make things easier through voice control, you can change the device
name to "Lights" by selecting the device and then the settings icon. Now
you can control the lights by saying "Turn on/off the lights".</p>
<p>You can use the Sonoff WiFi Plug for any other household appliances as
long as it does not take up more than 10A of current, as the switch is
rated for up to a maximum of 10A. (For example, fans or pet feeder) Any
appliances connected to the switch drawing more than 10A will damage the
switch. For air conditioning control, you can look for infrared control
device such as Tado, which controls air conditioning with infrared information
rather than directly controlling the power supply (which is what the Sonoff
Switch does in this tutorial) and is able to link to Google Home as well
for voice control.</p>
<p>And with that, your AI voice assistant should be fired up and ready to
go! Definitely try your hand at building a cool case for it. Our case was
made in the form of a pie to commemorate Pi Day on March 14, but you can
let your creativity flow and make all kinds of cases - just remember to
leave holes for the speaker and microphone!</p>
</li>
</ol>
<p></p>