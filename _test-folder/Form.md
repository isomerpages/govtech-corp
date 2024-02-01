---
title: Form
permalink: /test-folder/form/
variant: markdown
description: ""
---
<style>
    .content .iso-template {
        width: 100%;
        display: flex;
        flex-direction: column;
    }

    .content .iso-template h3 {
        color: #0061AF !important;
        font-family: Lato;
        font-size: 32px;
        font-style: normal;
        font-weight: 700;
        line-height: 45px !important;
        margin-bottom: 0px;
        margin-top: 0px;
    }

    .content .iso-template h4 {
        color: #0061AF !important;
        font-family: Lato;
        font-size: 26px;
        font-style: normal;
        font-weight: 700;
        line-height: 32px !important;
        margin-bottom: 0px;
        margin-top: 0px;
    }

    .content .iso-template h5 {
        color: #0061AF !important;
        font-family: Lato;
        font-size: 22px;
        font-style: normal;
        font-weight: 700;
        line-height: 30px !important;
        margin-bottom: 0px;
        margin-top: 0px;
    }

    .content .iso-template h6 {
        color: #0061AF !important;
        font-family: Lato;
        font-size: 20px;
        font-style: normal;
        font-weight: 700;
        margin-bottom: 0px;
        line-height: 20px !important;
        margin-top: 0px;
    }
    
    .content .iso-template .text-label-1 {
        color: #4D4D4F !important;
        font-family: Lato;
        font-size: 16px;
        font-style: normal;
        font-weight: 400;
        line-height: 22px !important; 
        text-transform: uppercase;
        margin-bottom: 16px;
    }

    .content .iso-template .text-label-2 {
        color: #4D4D4F !important;
        font-family: Lato;
        font-size: 15px;
        font-style: normal;
        font-weight: 400;
        line-height: 22px !important; 
        text-transform: uppercase;
    }

    .content .iso-template .text-body-1 {
        color: #4D4D4F !important;
        font-family: Lato;
        font-size: 20px;
        font-style: normal;
        font-weight: 400;
        line-height: 32px !important; 
    }

    .content .iso-template .text-body-2 {
        color: #4D4D4F !important;
        font-family: Lato;
        font-size: 16px;
        font-style: normal;
        font-weight: 400;
        line-height: 24px !important; 
    }

    .content .iso-template .text-note {
        color: #4D4D4F !important;
        font-family: Lato;
        font-size: 12px;
        font-style: normal;
        font-weight: 400;
        line-height: 20px !important; 
    }

    .content .iso-template a {
        color: #B41E8E !important;
        font-family: Lato;
        font-style: normal;
        font-weight: 700;
    }

    .content .iso-template .spacer-24 {
        width: 100%;
        height: 24px;
    }

    .content .iso-template .spacer-16 {
        width: 100%;
        height: 16px;
    }

    .content .iso-template .button {
        width: auto;
        height: auto;
        padding: 16px 20px;
        border: 1px solid;
        box-sizing: border-box;
        border-radius: 8px;
        font-family: Lato;
        font-size: 16px;
        font-style: normal;
        font-weight: 700;
        line-height: 24px !important; 
        text-transform: uppercase;
        cursor: pointer;
        text-decoration: none;
        display: inline-block;
        margin: 0px;
    }

    .content .iso-template .button.primary {
        background-color: #B41E8E;
        border-color: #B41E8E;
        color: #fff !important;
    }

    .content .iso-template .button.secondary {
        background-color: transparent;
        border-color: #B41E8E;
        color: #B41E8E !important;
    }

    .content .iso-template .button.bright {
        background-color: #fff;
        border-color: #fff;
        color: #B41E8E !important;
    }

    .content .iso-template .button.text {
        background-color: transparent;
        border: none;
        padding: 0px;
        color: #B41E8E !important;
    }

    .content .iso-template .button.image {
        background-color: transparent;
        border: none;
        padding: 0px;
        height: 48px;
    }

    .content .iso-template .button.image > img {
        height: 100%;
        border-radius: 8px;
    }

    .content .iso-template .button.has-svg {
        padding-right: 40px;
    }

    .content .iso-template .button > svg {
        display: inline;
        margin-left: 2px;
        position: absolute;
    }

    .content .iso-template .section .text-color-grey {
        color: #4D4D4F !important;
    }

    .content .iso-template .section .text-color-white {
        color: #fff !important;
    }

    .content .iso-template .section .text-align-right {
        text-align: right !important;
    }

    .content .iso-template .section .text-align-center {
        text-align: center !important;
    }

    .content .iso-template .section .text-align-left {
        text-align: left !important;
    }

    .content .iso-template .section {
        width: 100%;
        position: relative;
        margin-bottom: 40px
    }

    .content .iso-template .line-divider {
        width: 100%;
        height: 1px;
        background-color: #D8D9DA;
    }

    .content .iso-template .rounded {
        border-radius: 10px;
    }

    .content .iso-template ul,
    .content .iso-template ol {
        margin-top: 0px
    }

    .content .iso-template ul > li,
    .content .iso-template ol > li {
        margin-top: 0px;
        margin-bottom: 0px;
        line-height: inherit;
    }

    .content .iso-template .box-two-columns {
        width: 100%;
        display: flex;
        flex-direction: row;
        padding: 24px 0px;
        border-bottom: 1px solid #D8D9DA;
        box-sizing: border-box;
    }

    .content .iso-template .box-two-columns:first-of-type {
        border-top: 1px solid #D8D9DA
    }

    .content .iso-template .box-two-columns > * {
        width: 50%;
       
        box-sizing: border-box;
    }

    .content .iso-template .box-two-columns > *:nth-of-type(odd) {
        padding-right: 10px;
    }

    .content .iso-template .box-two-columns > *:nth-of-type(even) {
        padding-left: 10px;
    }

    .content .iso-template .bp-youtube {
        position: relative;
        overflow: hidden;
        padding-top: 56.25%;
        margin-bottom: 24px;
    }

    .content .iso-template .bp-youtube iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border: 0;
    }

    .content .iso-template .infographic {
        width: 100%;
        height: auto;
    }

    .content .iso-template .feature-center {
        width: 100%;
        height: auto;
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;
    }

    .content .iso-template .feature-center > img {
        width: 100%;
        max-width: 500px;
        height: auto;
        border-radius: 10px
    }

    .content .iso-template .feature-center .button {
        margin: 0px 8px
    }

    .content .iso-template .image-box {
        width: 100%;
        height: auto;
        position: relative;
        background-position: center;
        background-size: cover;
        padding: 32px;
        box-sizing: border-box;
        display: inline-block;
    }

    .content .iso-template .image-box > .text-content {
        width: 100%;
        max-width: 420px;
    }

    .content .iso-template .image-box > .text-content.align-left {
        float: left;
    }

    .content .iso-template .image-box > .text-content.align-right {
        float: right;
    }

    .content .iso-template .image-box > .text-content.align-full {
        float: left;
        max-width: 99999px;
    }

    @media only screen and (max-width: 768px) {
        .content .iso-template .section {
            margin-bottom: 32px
        }

        .content .iso-template h3 {
            font-size: 28px;
        }

        .content .iso-template h4 {
            font-size: 24px;
        }

        .content .iso-template h5 {
            font-size: 22px;
        }

        .content .iso-template h6 {
            font-size: 22px;
        }

        .content .iso-template .text-label-1 {
            margin-bottom: 8px
        }

        .content .iso-template .bp-youtube {
            margin-bottom: 16px;
        }

        .content .iso-template .spacer-24 {
            height: 16px;
        }

        .content .iso-template .spacer-16 {
            height: 8px;
        }

        .content .iso-template .feature-center > img {
            width: 100%;
            height: auto;
            max-width: 320px;
        }

        .content .iso-template .image-box > .text-content {
            max-width: 768px !important;
        }
    }
</style>
<style>
    .content .iso-template #mc_embed_signup {
        background: #F0F4F6;
        padding: 30px;
        display: inline-block;
        border-radius: 10px;
    }

    .content .iso-template #mc_embed_signup input,
    .content .iso-template #mc_embed_signup select {
        height: 40px;
        border-radius: 5px;
        padding: 0px 15px;
        font-family: Lato;
        font-size: 16px;
        box-sizing: border-box;
        border: 1px solid #D6D6D6;
    }

    .content .iso-template #mc_embed_signup input[type="submit"]{
        width: auto;
        height: auto;
        padding: 16px 20px;
        border: 1px solid;
        box-sizing: border-box;
        border-radius: 8px;
        font-family: Lato;
        font-size: 16px;
        font-style: normal;
        font-weight: 700;
        line-height: 24px !important; 
        text-transform: uppercase;
        cursor: pointer;
        text-decoration: none;
        display: inline-block;
        margin: 0px;
    }

    .content .iso-template #mc_embed_signup .section.form-fields {
        display: flex;
        position: relative;
    }

    .content .iso-template #mc_embed_signup .section.form-fields .mc-field-group {
        width: calc(50% - 12px);
        display: flex;
        flex-direction: column;
        margin: 0px;
    }

    .content .iso-template #mc_embed_signup .section.form-fields .mc-field-group:nth-of-type(odd){
        margin-right: 12px;
    }

    .content .iso-template #mc_embed_signup .section.form-fields .mc-field-group:nth-of-type(even){
        margin-left: 12px;
    }

    .content .iso-template #mc_embed_signup .section.form-fields .mc-field-group.full-width {
        width: 100%;
        margin: 0px;
    }

    .content .iso-template #mc_embed_signup .section.form-fields .mc-field-group label {
        margin-bottom: 10px;
    }

    .content .iso-template #mc_embed_signup ul {
        margin: 0px;
    }

    .content .iso-template #mc_embed_signup li {
        margin: 0px;
        margin-right: 20px
    }

    .content .iso-template #mc_embed_signup li input {
        width: 25px;
        margin-right: 7px;
    }

    .content .iso-template #mc_embed_signup .section.form-fields .mc-field-group li label {
        margin-bottom: 0px;
        height: 40px;
        display: flex;
        align-items: center;
    }

    .content .iso-template #mc_embed_signup ul, .content .iso-template #mc_embed_signup li {
        list-style: none;
        list-style-type: none;
        display: flex;
        flex-direction: row;
    }

    .content .iso-template #mc_embed_signup ul.ul-vertical {
        flex-direction: column;
    }

    @media only screen and (max-width: 768px) {
        .content .iso-template #mc_embed_signup {
            width: calc(100% + 48px);
            margin-left: -24px;
        }

        .content .iso-template #mc_embed_signup .section.form-fields .mc-field-group {
            width: 100%;
        }

        .content .iso-template #mc_embed_signup .section.form-fields .mc-field-group:nth-of-type(odd){
            margin-right: 0px;
            margin-bottom: 44px;
        }

        .content .iso-template #mc_embed_signup .section.form-fields .mc-field-group:nth-of-type(even){
            margin-left: 0px;
        }

        .content .iso-template #mc_embed_signup .section.form-fields {
            flex-direction: column;
        }
    }
</style>
<div class="iso-template">
    <div class="section">
        <img alt="" src="https://i.ibb.co/9gLh4zh/image-63-4.jpg" class="infographic">
    </div>
    <div class="section">
        <h3>[H3] Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna fermentum nisi, ac mattis nulla velit eu quam.</h3>
    </div>
    <div class="section line-divider"></div>
    <div class="section">
        <h2>[H2] Morbi orci diam elementum et odio imperdiet facilisis</h2>
    </div>
    <div class="section">
        <h3>[H3] Morbi orci diam elementum et odio imperdiet facilisis</h3>
    </div>
    <div class="section">
        <h4>[H4] Morbi orci diam elementum et odio imperdiet facilisis</h4>
    </div>
    <div class="section">
        <h5>[H5] Morbi orci diam elementum et odio imperdiet facilisis</h5>
    </div>
    <div class="section">
        <span class="text-body-1">
            [Body 1] <b>Lorem ipsum dolor</b> sit amet, consectetur adipiscing elit. Aliquam vestibulum lectus risus, id maximus nibh consectetur aliquam. In sit amet efficitur nisl. <br><br>
            <a href="https://www.google.com.sg/">Quisque scelerisque</a> tellus vitae massa pulvinar, eu posuere diam convallis.
        </span>
    </div>
    <div class="section">
        <span class="text-body-2">
            [Body 2] <b>Lorem ipsum dolor</b> sit amet, consectetur adipiscing elit. Aliquam vestibulum lectus risus, id maximus nibh consectetur aliquam. In sit amet efficitur nisl. <br><br>
            <a href="https://www.google.com.sg/">Quisque scelerisque</a> tellus vitae massa pulvinar, eu posuere diam convallis.
        </span>
    </div>
    <div class="section">
        <span class="text-note">
            [Note] <b>Lorem ipsum dolor</b> sit amet, consectetur adipiscing elit. Aliquam vestibulum lectus risus, id maximus nibh consectetur aliquam. In sit amet efficitur nisl. <br><br>
            <a href="https://www.google.com.sg/">Quisque scelerisque</a> tellus vitae massa pulvinar, eu posuere diam convallis.
        </span>
    </div>
    <div class="section">
        <ul class="text-body-1">
            <li>
                [Body 1] <b>Lorem ipsum dolor</b> sit amet, consectetur adipiscing elit. Aliquam vestibulum lectus risus.
            </li>
            <li>
                [Body 1] <a href="https://www.google.com.sg/">Maximus nibh</a>consectetur aliquam. In sit amet efficitur nisl. Quisque scelerisque tellus vitae massa pulvinar.
            </li>
            <li>
                [Body 1] Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam vestibulum lectus risus.
            </li>
        </ul>
    </div>
    <div class="section">
        <ul class="text-body-2">
            <li>
                [Body 2] <b>Lorem ipsum dolor</b> sit amet, consectetur adipiscing elit. Aliquam vestibulum lectus risus.
            </li>
            <li>
                [Body 2] <a href="https://www.google.com.sg/">Maximus nibh</a>consectetur aliquam. In sit amet efficitur nisl. Quisque scelerisque tellus vitae massa pulvinar.
            </li>
            <li>
                [Body 2] Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam vestibulum lectus risus.
            </li>
        </ul>
    </div>
    <div class="section">
        <ul class="text-note">
            <li>
                [Note] <b>Lorem ipsum dolor</b> sit amet, consectetur adipiscing elit. Aliquam vestibulum lectus risus.
            </li>
            <li>
                [Note] <a href="https://www.google.com.sg/">Maximus nibh</a>consectetur aliquam. In sit amet efficitur nisl. Quisque scelerisque tellus vitae massa pulvinar.
            </li>
            <li>
                [Note] Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam vestibulum lectus risus.
            </li>
        </ul>
    </div>
    <div class="section">
        <ol class="text-body-1">
            <li>
                [Body 1] <b>Lorem ipsum dolor</b> sit amet, consectetur adipiscing elit. Aliquam vestibulum lectus risus.
            </li>
            <li>
                [Body 1] <a href="https://www.google.com.sg/">Maximus nibh</a>consectetur aliquam. In sit amet efficitur nisl. Quisque scelerisque tellus vitae massa pulvinar.
            </li>
            <li>
                [Body 1] Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam vestibulum lectus risus.
            </li>
        </ol>
    </div>
    <div class="section">
        <ol class="text-body-2">
            <li>
                [Body 2] <b>Lorem ipsum dolor</b> sit amet, consectetur adipiscing elit. Aliquam vestibulum lectus risus.
            </li>
            <li>
                [Body 2] <a href="https://www.google.com.sg/">Maximus nibh</a>consectetur aliquam. In sit amet efficitur nisl. Quisque scelerisque tellus vitae massa pulvinar.
            </li>
            <li>
                [Body 2] Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam vestibulum lectus risus.
            </li>
        </ol>
    </div>
    <div class="section">
        <ol class="text-note">
            <li>
                [Note] <b>Lorem ipsum dolor</b> sit amet, consectetur adipiscing elit. Aliquam vestibulum lectus risus.
            </li>
            <li>
                [Note] <a href="https://www.google.com.sg/">Maximus nibh</a>consectetur aliquam. In sit amet efficitur nisl. Quisque scelerisque tellus vitae massa pulvinar.
            </li>
            <li>
                [Note] Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam vestibulum lectus risus.
            </li>
        </ol>
    </div>
    <div class="section">
        <a href="https://www.google.com.sg/" class="button secondary">
            BUTTON
        </a>
        <a href="https://www.google.com.sg/" class="button primary">
            BUTTON
        </a>
    </div>
    <div class="section">
        <a target="_blank" href="https://www.google.com.sg/" class="button secondary has-svg">
            BUTTON
            <svg fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path fill="#B41E8E" d="M13.75 5C13.266 5 12.875 5.39102 12.875 5.875C12.875 6.35898 13.266 6.75 13.75 6.75H16.0113L10.507 12.257C10.1652 12.5988 10.1652 13.1539 10.507 13.4957C10.8488 13.8375 11.4039 13.8375 11.7457 13.4957L17.25 7.98867V10.25C17.25 10.734 17.641 11.125 18.125 11.125C18.609 11.125 19 10.734 19 10.25V5.875C19 5.39102 18.609 5 18.125 5H13.75ZM7.1875 5.875C5.97891 5.875 5 6.85391 5 8.0625V16.8125C5 18.0211 5.97891 19 7.1875 19H15.9375C17.1461 19 18.125 18.0211 18.125 16.8125V13.75C18.125 13.266 17.734 12.875 17.25 12.875C16.766 12.875 16.375 13.266 16.375 13.75V16.8125C16.375 17.0531 16.1781 17.25 15.9375 17.25H7.1875C6.94687 17.25 6.75 17.0531 6.75 16.8125V8.0625C6.75 7.82188 6.94687 7.625 7.1875 7.625H10.25C10.734 7.625 11.125 7.23398 11.125 6.75C11.125 6.26602 10.734 5.875 10.25 5.875H7.1875Z"></path></svg>
        </a>
        <a target="_blank" href="https://www.google.com.sg/" class="button primary has-svg">
            BUTTON 
            <svg fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path fill="white" d="M13.75 5C13.266 5 12.875 5.39102 12.875 5.875C12.875 6.35898 13.266 6.75 13.75 6.75H16.0113L10.507 12.257C10.1652 12.5988 10.1652 13.1539 10.507 13.4957C10.8488 13.8375 11.4039 13.8375 11.7457 13.4957L17.25 7.98867V10.25C17.25 10.734 17.641 11.125 18.125 11.125C18.609 11.125 19 10.734 19 10.25V5.875C19 5.39102 18.609 5 18.125 5H13.75ZM7.1875 5.875C5.97891 5.875 5 6.85391 5 8.0625V16.8125C5 18.0211 5.97891 19 7.1875 19H15.9375C17.1461 19 18.125 18.0211 18.125 16.8125V13.75C18.125 13.266 17.734 12.875 17.25 12.875C16.766 12.875 16.375 13.266 16.375 13.75V16.8125C16.375 17.0531 16.1781 17.25 15.9375 17.25H7.1875C6.94687 17.25 6.75 17.0531 6.75 16.8125V8.0625C6.75 7.82188 6.94687 7.625 7.1875 7.625H10.25C10.734 7.625 11.125 7.23398 11.125 6.75C11.125 6.26602 10.734 5.875 10.25 5.875H7.1875Z"></path></svg>
        </a>
    </div>
    <div class="section">
        <a href="https://www.google.com.sg/" class="button text">
            TEXT CTA 
        </a>
    </div>
    <div class="section">
        <a target="_blank" href="https://www.google.com.sg/" class="button text">
            TEXT CTA 
            <svg fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path stroke-linejoin="round" stroke-linecap="round" stroke-width="1.5" stroke="#B41E8E" d="M10 7L15 12L10 17"></path></svg>
        </a>
    </div>
    <div class="section line-divider"></div>
    <div id="mc_embed_signup" class="section">
        <form novalidate="" target="_blank" class="validate" name="mc-embedded-subscribe-form" id="mc-embedded-subscribe-form" method="post" action="https://tech.us16.list-manage.com/subscribe/post?u=9326ff42459737140a6baa881&amp;id=8b7e185878&amp;f_id=00b0c2e1f0">
            <div id="mc_embed_signup_scroll">
                <div class="section form-fields">
                    <div class="mc-field-group">
                        <label class="text-body-1" for="mce-EMAIL"><b>[Body 1] Email Address <span class="asterisk">*</span></b>
                        </label>
                        <input placeholder="Type here" required="" id="mce-EMAIL" class="required email" name="EMAIL" value="" type="email">
                        <span class="helper_text" id="mce-EMAIL-HELPERTEXT"></span>
                    </div>
                    <div class="mc-field-group">
                        <label class="text-body-1" for="mce-FNAME"><b>Full Name <span class="asterisk">*</span></b>
                        </label>
                        <input placeholder="Type here" required="" id="mce-FNAME" class="required" name="FNAME" value="" type="text">
                        <span class="helper_text" id="mce-FNAME-HELPERTEXT"></span>
                    </div>
                </div>
                <div class="section form-fields">
                    <div class="mc-field-group input-group">
                        <strong class="text-body-1"><b>Gender <span class="asterisk">*</span></b>
                        </strong>
                        <ul>
                            <li>
                                <input id="mce-GENDER-0" name="GENDER" value="Female" type="radio">
                                <label class="text-body-1" for="mce-GENDER-0">Female</label>
                            </li>
                            <li>
                                <input id="mce-GENDER-1" name="GENDER" value="Male" type="radio">
                                <label class="text-body-1" for="mce-GENDER-1">Male</label>
                            </li>
                        </ul>
                        <span class="helper_text" id="mce-GENDER-HELPERTEXT"></span>
                    </div>
                    <div class="mc-field-group">
                        <label class="text-body-1" for="mce-BIRTHYEAR"><b>Which year were you born in? <span class="asterisk">*</span></b>
                        </label>
                        <input required="" id="mce-BIRTHYEAR" value="" class="required" name="BIRTHYEAR" type="number">
                        <span class="helper_text" id="mce-BIRTHYEAR-HELPERTEXT"></span>
                    </div>
                </div>
                <div class="section form-fields">
                    <div class="mc-field-group full-width">
                        <label class="text-body-1" for="mce-TECH"><b>Are you in a tech-based job / field of study? <span class="asterisk">*</span></b>
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
                        <label class="text-body-1" for="mce-INDUSTRY"><b>Which industry do you primarily work in? <span class="asterisk">*</span></b>
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
                        <div class="text-body-1"><b>Keen to co-create with GovTech? (eg. User Testing)</b></div>
                        <ul>
                            <li>
                                <input id="mce-group[59]-59-0" name="group[59]" value="1" type="radio">
                                <label class="text-body-1" for="mce-group[59]-59-0">Yes</label>
                            </li>
                            <li>
                                <input id="mce-group[59]-59-1" name="group[59]" value="2" type="radio">
                                <label class="text-body-1" for="mce-group[59]-59-1">No</label>
                            </li>
                        </ul>
                        <span class="helper_text" id="mce-group[59]-HELPERTEXT"></span>
                    </div>
                </div>
                <div class="section form-fields">
                    <div class="mc-field-group input-group full-width">
                        <div class="text-body-1"><b>Tech topics I am keen to hear about:</b></div>
                        <ul class="ul-vertical">
                            <li>
                                <input id="mce-group[71]-71-0" name="group[71][4]" value="4" type="checkbox">
                                <label for="mce-group[71]-71-0" class="text-body-1">Diversity and Inclusion in Tech</label>
                            </li>
                            <li>
                                <input id="mce-group[71]-71-1" name="group[71][8]" value="8" type="checkbox">
                                <label for="mce-group[71]-71-1" class="text-body-1">User Experience and Interface (UX/UI)</label>
                            </li>
                            <li>
                                <input id="mce-group[71]-71-2" name="group[71][16]" value="16" type="checkbox">
                                <label for="mce-group[71]-71-2" class="text-body-1">Smart Nation</label>
                            </li>
                            <li>
                                <input id="mce-group[71]-71-3" name="group[71][32]" value="32" type="checkbox">
                                <label for="mce-group[71]-71-3" class="text-body-1">Data Science and Analytics</label>
                            </li>
                            <li>
                                <input id="mce-group[71]-71-4" name="group[71][64]" value="64" type="checkbox">
                                <label for="mce-group[71]-71-4" class="text-body-1">Cybersecurity</label>
                            </li>
                            <li>
                                <input id="mce-group[71]-71-5" name="group[71][128]" value="128" type="checkbox">
                                <label for="mce-group[71]-71-5" class="text-body-1">Chatbots and Virtual Assistants</label>
                            </li>
                            <li>
                                <input id="mce-group[71]-71-6" name="group[71][256]" value="256" type="checkbox">
                                <label for="mce-group[71]-71-6" class="text-body-1">Tech for Business Owners</label>
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
                <div class="clear"><input class="button primary" id="mc-embedded-subscribe" name="subscribe" value="Subscribe Now" type="submit"></div>
            </div>
        </form>
    </div>
    <div class="section">
        <span class="text-body-2">
            [Body 2] By submitting this form, you accept the <a href="https://www.tech.gov.sg/files/GovTech-Subscription-Terms-Conditions-2021.pdf">Terms &amp; Conditions</a> relating to the subscription to GovTech’s digital updates and acknowledge that you have read and understood the <a href="https://www.tech.gov.sg/privacy/">Government Agency Privacy Statement</a>.
        </span>
    </div>
</div>