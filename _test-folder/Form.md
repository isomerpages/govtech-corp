---
title: Form
permalink: /test-folder/form/
variant: markdown
description: ""
---
<style>
    .iso-template h3 {
        color: #4372D6 !important;
        font-family: Lato;
        font-size: 32px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        margin-bottom: 0px;
    }

    .iso-template h4 {
        color: #4372D6 !important;
        font-family: Lato;
        font-size: 26px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        margin-bottom: 0px;
    }

    .iso-template h5 {
        color: #4372D6 !important;
        font-family: Lato;
        font-size: 24px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        margin-bottom: 0px;
    }

    .iso-template .body-text-regular {
        color: #484848 !important;
        font-family: Lato;
        font-size: 20px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
    }

    .iso-template .body-text-small {
        color: #484848 !important;
        font-family: Lato;
        font-size: 16px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
    }

    .iso-template .body-text-bold {
        color: #000 !important;
        font-family: Lato;
        font-size: 20px;
        font-style: normal;
        font-weight: 700;
        line-height: normal;
    }

    .iso-template .body-text-small-bold {
        color: #4372D6 !important;
        font-family: Lato;
        font-size: 16px;
        font-style: normal;
        font-weight: 700;
        line-height: normal;
    }

    .iso-template .anchorlink {
        color: #4372D6 !important;
        font-family: Lato;
        font-size: 20px;
        font-style: normal;
        font-weight: 700;
        line-height: normal;
        text-decoration-line: underline;
    }

    .iso-template .button-default {
        width: auto;
        height: auto;
        padding: 15px 20px;
        border-radius: 8px;
        border: 1px solid #4372D6;
        color: #4372D6 !important;
        font-family: Lato;
        font-size: 16px;
        font-style: normal;
        font-weight: 700;
        line-height: normal;
        text-transform: uppercase;
        cursor: pointer;
        display: inline-block;
    }

    .iso-template .button-blue {
        width: auto;
        height: auto;
        padding: 15px 20px;
        border-radius: 8px;
        border: 1px solid #4372D6;
        color: #fff !important;
        background-color: #4372D6;
        font-family: Lato;
        font-size: 16px;
        font-style: normal;
        font-weight: 700;
        line-height: normal;
        text-transform: uppercase;
        cursor: pointer;
        display: inline-block;
    }

    .iso-template .button-blue > svg {
        display: inline;
        margin-left: 15px
    }

    @media only screen and (max-width: 768px) {
        .iso-template h3 {
            font-size: 28px;
        }

        .iso-template h4 {
            font-size: 24px;
        }

        .iso-template h5 {
            font-size: 22px;
        }
    }
</style>
<style>
    .form-template {
        width: 100%;
        display: flex;
        flex-direction: column;
    }

    .form-template .section {
        width: 100%;
        position: relative;
        margin-bottom: 44px
    }

    .form-template .section.linebreak {
        width: 100%;
        height: 1px;
        background-color: #D6D6D6;
        position: relative;
    }

    .form-template .banner-image {
        width: 100%;
        height: auto
    }

    .form-template #mc_embed_signup {
        background: #F0F4F6;
        padding: 30px;
        display: inline-block;
    }

    .form-template #mc_embed_signup input,
    .form-template #mc_embed_signup select {
        height: 40px;
        border-radius: 5px;
        padding: 0px 15px;
        font-family: Lato;
        font-size: 16px;
        box-sizing: border-box;
        border: 1px solid #D6D6D6;
    }

    .form-template #mc_embed_signup .section.form-fields {
        display: flex;
        position: relative;
    }

    .form-template #mc_embed_signup .section.form-fields .mc-field-group {
        width: calc(50% - 12px);
        display: flex;
        flex-direction: column;
        margin: 0px;
    }

    .form-template #mc_embed_signup .section.form-fields .mc-field-group:nth-of-type(odd){
        margin-right: 12px;
    }

    .form-template #mc_embed_signup .section.form-fields .mc-field-group:nth-of-type(even){
        margin-left: 12px;
    }

    .form-template #mc_embed_signup .section.form-fields .mc-field-group.full-width {
        width: 100%;
        margin: 0px;
    }

    .form-template #mc_embed_signup .section.form-fields .mc-field-group label {
        margin-bottom: 10px;
    }

    .form-template ul {
        margin: 0px;
    }

    .form-template #mc_embed_signup li {
        margin: 0px;
        margin-right: 20px
    }

    .form-template li input {
        width: 25px;
        height: 25px;
        margin-right: 7px;
    }

    .form-template #mc_embed_signup .section.form-fields .mc-field-group li label {
        margin-bottom: 0px;
        height: 40px;
        display: flex;
        align-items: center;
    }

    .form-template ul, .form-template li {
        list-style: none;
        list-style-type: none;
        display: flex;
        flex-direction: row;
    }

    .form-template ul.ul-vertical {
        flex-direction: column;
    }

    @media only screen and (max-width: 768px) {
        .form-template #mc_embed_signup {
            width: calc(100% + 48px);
            margin-left: -24px;
        }

        .form-template #mc_embed_signup .section.form-fields .mc-field-group {
            width: 100%;
        }

        .form-template #mc_embed_signup .section.form-fields .mc-field-group:nth-of-type(odd){
            margin-right: 0px;
            margin-bottom: 44px;
        }

        .form-template #mc_embed_signup .section.form-fields .mc-field-group:nth-of-type(even){
            margin-left: 0px;
        }

        .form-template #mc_embed_signup .section.form-fields {
            flex-direction: column;
        }
    }
</style>
<div class="iso-template form-template">
    <div class="section">
        <img class="banner-image" alt="" src="https://d33wubrfki0l68.cloudfront.net/1a641c70cd44a129a6f979edd891e20f8dfcdc4f/00ff9/images/technews/technews-logo.png">
    </div>
    <div class="section" id="welcome-to-the-technews-community">
        <h3>Welcome to the TechNews community!</h3>
    </div>
    <div class="section">
        <span class="body-text-regular">Join over 20,000 readers and subscribe to GovTech’s newsletter for the latest GovTech updates, tech tips, and behind-the-scenes stories.</span>
    </div>
    <div id="mc_embed_signup" class="section">
        <form novalidate="" target="_blank" class="validate" name="mc-embedded-subscribe-form" id="mc-embedded-subscribe-form" method="post" action="https://tech.us16.list-manage.com/subscribe/post?u=9326ff42459737140a6baa881&amp;id=8b7e185878&amp;f_id=00b0c2e1f0">
            <div id="mc_embed_signup_scroll">
                <div class="section form-fields">
                    <div class="mc-field-group">
                        <label class="body-text-bold" for="mce-EMAIL">Email Address <span class="asterisk">*</span>
                        </label>
                        <input placeholder="Type here" required="" id="mce-EMAIL" class="required email" name="EMAIL" value="" type="email">
                        <span class="helper_text" id="mce-EMAIL-HELPERTEXT"></span>
                    </div>
                    <div class="mc-field-group">
                        <label class="body-text-bold" for="mce-FNAME">Full Name <span class="asterisk">*</span>
                        </label>
                        <input placeholder="Type here" required="" id="mce-FNAME" class="required" name="FNAME" value="" type="text">
                        <span class="helper_text" id="mce-FNAME-HELPERTEXT"></span>
                    </div>
                </div>
                <div class="section form-fields">
                    <div class="mc-field-group input-group">
                        <strong class="body-text-bold">Gender <span class="asterisk">*</span>
                        </strong>
                        <ul>
                            <li>
                                <input id="mce-GENDER-0" name="GENDER" value="Female" type="radio">
                                <label class="body-text-regular" for="mce-GENDER-0">Female</label>
                            </li>
                            <li>
                                <input id="mce-GENDER-1" name="GENDER" value="Male" type="radio">
                                <label class="body-text-regular" for="mce-GENDER-1">Male</label>
                            </li>
                        </ul>
                        <span class="helper_text" id="mce-GENDER-HELPERTEXT"></span>
                    </div>
                    <div class="mc-field-group">
                        <label class="body-text-bold" for="mce-BIRTHYEAR">Which year were you born in? <span class="asterisk">*</span>
                        </label>
                        <input required="" id="mce-BIRTHYEAR" value="" class="required" name="BIRTHYEAR" type="number">
                        <span class="helper_text" id="mce-BIRTHYEAR-HELPERTEXT"></span>
                    </div>
                </div>
                <div class="section form-fields">
                    <div class="mc-field-group full-width">
                        <label class="body-text-bold" for="mce-TECH">Are you in a tech-based job / field of study? <span class="asterisk">*</span>
                        </label>
                        <select required="" id="mce-TECH" class="required" name="TECH">
                            <option value=""></option>
                            <option value="Yes">Yes</option>
                            <option value="No">No</option>
                        </select>
                        <span class="helper_text" id="mce-TECH-HELPERTEXT"></span>
                    </div>
                </div>
                <div class="section form-fields">
                    <div class="mc-field-group full-width">
                        <label class="body-text-bold" for="mce-INDUSTRY">Which industry do you primarily work in? <span class="asterisk">*</span>
                        </label>
                        <select required="" id="mce-INDUSTRY" class="required" name="INDUSTRY">
                            <option value=""></option>
                            <option value="Manufacturing - Energy &amp; Chemicals">Manufacturing - Energy &amp; Chemicals</option>
                            <option value="Manufacturing - Precision Engineering">Manufacturing - Precision Engineering</option>
                            <option value="Manufacturing - Marine &amp; Offshore">Manufacturing - Marine &amp; Offshore</option>
                            <option value="Manufacturing - Aerospace">Manufacturing - Aerospace</option>
                            <option value="Manufacturing - Electronics">Manufacturing - Electronics</option>
                            <option value="Built Environment - Construction &amp; Architecture">Built Environment - Construction &amp; Architecture</option>
                            <option value="Built Environment - Real Estate">Built Environment - Real Estate</option>
                            <option value="Built Environment - Cleaning">Built Environment - Cleaning</option>
                            <option value="Built Environment - Security">Built Environment - Security</option>
                            <option value="Trade &amp; Connectivity - Logistics">Trade &amp; Connectivity - Logistics</option>
                            <option value="Trade &amp; Connectivity - Transportation">Trade &amp; Connectivity - Transportation</option>
                            <option value="Trade &amp; Connectivity - Wholesale Trade">Trade &amp; Connectivity - Wholesale Trade</option>
                            <option value="Essential Services - Healthcare">Essential Services - Healthcare</option>
                            <option value="Essential Services - Education">Essential Services - Education</option>
                            <option value="Professional Services - Professional &amp; Consulting Services">Professional Services - Professional &amp; Consulting Services</option>
                            <option value="Professional Services - Financial Services">Professional Services - Financial Services</option>
                            <option value="Professional Services - Infocomm, Technology &amp; Media">Professional Services - Infocomm, Technology &amp; Media</option>
                            <option value="Lifestyle - Food &amp; Beverage">Lifestyle - Food &amp; Beverage</option>
                            <option value="Lifestyle - Retail">Lifestyle - Retail</option>
                            <option value="Lifestyle - Hotels &amp; Tourism">Lifestyle - Hotels &amp; Tourism</option>
                            <option value="Lifestyle - Food Manufacturing">Lifestyle - Food Manufacturing</option>
                            <option value="Government">Government</option>
                            <option value="Other Industry">Other Industry</option>
                            <option value="Not Applicable">Not Applicable</option>
                        </select>
                        <span class="helper_text" id="mce-INDUSTRY-HELPERTEXT"></span>
                    </div>
                </div>
                <div class="section form-fields">
                    <div class="mc-field-group input-group full-width">
                        <strong class="body-text-bold">Keen to co-create with GovTech? (eg. User Testing) </strong>
                        <ul>
                            <li>
                                <input id="mce-group[59]-59-0" name="group[59]" value="1" type="radio">
                                <label class="body-text-regular" for="mce-group[59]-59-0">Yes</label>
                            </li>
                            <li>
                                <input id="mce-group[59]-59-1" name="group[59]" value="2" type="radio">
                                <label class="body-text-regular" for="mce-group[59]-59-1">No</label>
                            </li>
                        </ul>
                        <span class="helper_text" id="mce-group[59]-HELPERTEXT"></span>
                    </div>
                </div>
                <div class="section form-fields">
                    <div class="mc-field-group input-group full-width">
                        <strong class="body-text-bold">Tech topics I am keen to hear about: </strong>
                        <ul class="ul-vertical">
                            <li>
                                <input id="mce-group[71]-71-0" name="group[71][4]" value="4" type="checkbox">
                                <label for="mce-group[71]-71-0" class="body-text-regular">Diversity and Inclusion in Tech</label>
                            </li>
                            <li>
                                <input id="mce-group[71]-71-1" name="group[71][8]" value="8" type="checkbox">
                                <label for="mce-group[71]-71-1" class="body-text-regular">User Experience and Interface (UX/UI)</label>
                            </li>
                            <li>
                                <input id="mce-group[71]-71-2" name="group[71][16]" value="16" type="checkbox">
                                <label for="mce-group[71]-71-2" class="body-text-regular">Smart Nation</label>
                            </li>
                            <li>
                                <input id="mce-group[71]-71-3" name="group[71][32]" value="32" type="checkbox">
                                <label for="mce-group[71]-71-3" class="body-text-regular">Data Science and Analytics</label>
                            </li>
                            <li>
                                <input id="mce-group[71]-71-4" name="group[71][64]" value="64" type="checkbox">
                                <label for="mce-group[71]-71-4" class="body-text-regular">Cybersecurity</label>
                            </li>
                            <li>
                                <input id="mce-group[71]-71-5" name="group[71][128]" value="128" type="checkbox">
                                <label for="mce-group[71]-71-5" class="body-text-regular">Chatbots and Virtual Assistants</label>
                            </li>
                            <li>
                                <input id="mce-group[71]-71-6" name="group[71][256]" value="256" type="checkbox">
                                <label for="mce-group[71]-71-6" class="body-text-regular">Tech for Business Owners</label>
                            </li>
                        </ul>
                        <span class="helper_text" id="mce-group[71]-HELPERTEXT"></span>
                    </div>
                </div>
                <div class="clear" id="mce-responses">
                    <div style="display:none" id="mce-error-response" class="response"></div>
                    <div style="display:none" id="mce-success-response" class="response"></div>
                </div>
                <div aria-hidden="true" style="position: absolute; left: -5000px; font:20px Lato,sans-serif;"><input value="" tabindex="-1" name="b_9326ff42459737140a6baa881_8b7e185878" type="text"></div>
                <div class="clear"><input class="button-blue" id="mc-embedded-subscribe" name="subscribe" value="Subscribe Now" type="submit"></div>
            </div>
        </form>
    </div>
    <div class="section">
        <span class="body-text-small">
            By submitting this form, you accept the <a href="https://www.tech.gov.sg/files/GovTech-Subscription-Terms-Conditions-2021.pdf">Terms &amp; Conditions</a> relating to the subscription to GovTech’s digital updates and acknowledge that you have read and understood the <a href="https://www.tech.gov.sg/privacy/">Government Agency Privacy Statement</a>.
        </span>
    </div>
</div>