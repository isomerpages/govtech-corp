---
title: Informative
permalink: /test-folder/informative/
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

    .iso-template .button-image {
        width: auto;
        height: 43px;
        border-radius: 8px;
        cursor: pointer;
        display: inline-block;
        margin: 0px 8px;
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
    .informative-template {
        width: 100%;
        display: flex;
        flex-direction: column;
    }

    .informative-template .section {
        width: 100%;
        position: relative;
        margin-bottom: 44px
    }

    .informative-template .section.infographic {
        width: 100%;
        position: relative;
    }

    .informative-template .section.infographic > img {
        width: 100%;
        height: auto;
    }

    .informative-template .section.linebreak {
        width: 100%;
        height: 1px;
        background-color: #D6D6D6;
        position: relative;
    }

    .informative-template .section.info-cards-container {
        display: flex;
        flex-wrap: wrap;
    }

    .informative-template .info-cards {
        flex: 0 0 33.33333%;
        box-sizing: border-box;
    }

    .informative-template .info-cards:nth-of-type(3n+1) {
        padding-right: 16px;
    }

    .informative-template .info-cards:nth-of-type(3n+2) {
        padding-right: 8px;
        padding-left: 8px;
    }

    .informative-template .info-cards:nth-of-type(3n+3) {
        padding-left: 16px;
    }

    .informative-template .info-cards > img {
        width: 100%;
        height: auto;
        float: left;
        display: block;
        border-top-right-radius: 10px;
        border-top-left-radius: 10px;
        border: 2px solid #D9D9D9;
        box-sizing: border-box;
        border-bottom: none;
    }

    .informative-template .info-cards-details {
        width: 100%;
        height: auto;
        float: left;
        display: block;
        border: 2px solid #D9D9D9;
        border-bottom-right-radius: 10px;
        border-bottom-left-radius: 10px;
        box-sizing: border-box;
        padding: 12px;
        border-top: none;
    }

    .informative-template .info-cards-details.no-image {
        border-top: 2px solid #D9D9D9;
        border-top-right-radius: 10px;
        border-top-left-radius: 10px;
    }

    .informative-template .portrait-box > img {
        width: 246px;
        height: 246px;
        border-radius: 10px;
        float: left;
    }

    .informative-template .portrait-box-details {
        width: calc(100% - 246px);
        height: 246px;
        float: left;
        display: flex;
        justify-content: center;
        box-sizing: border-box;
        padding-left: 35px;
        flex-direction: column;
    }

    .informative-template .portrait-box-details > h4 {
        margin-bottom: 11px
    }

    .informative-template .quote-box > .body-text-small {
        margin-top: 11px;
        text-align: right;
    }

    .informative-template .section.swap-image-container {
        display: flex;
        flex-direction: column;
    }

    .informative-template .swap-image-box {
        display: flex;
        flex-direction: row;
        margin-bottom: 44px;
    }

    .informative-template .swap-image-box:last-of-type {
        margin-bottom: 0px;
    }

    .informative-template .swap-image-box:nth-of-type(even) {
        flex-direction: row-reverse;
    }

    .informative-template .swap-image-box > img {
        width: 294px;
        height: 221px;
        border-radius: 10px
    }

    .informative-template .swap-image-box > .swap-image-details {
        width: calc(100% - 294px);
        height: 221px;
        box-sizing: border-box;
        padding-left: 26px;
        display: flex;
        justify-content: center;
        flex-direction: column;
    }

    .informative-template .swap-image-box:nth-of-type(even) > .swap-image-details {
        padding-left: 0px;
        padding-right: 26px;
    }

    .informative-template .swap-image-details > h4 {
        margin-bottom: 30px
    }

    .informative-template .accordion-container {
        border-bottom: 1px solid #8A8A8A;
    }

    .informative-template .accordion-container input {
        display: none;
    }

    .informative-template .accordion-container label {
        display: flex;
        padding: 11px 15px;
        margin: 0 0 5px 0;
        cursor: pointer;
        transition: ease .5s;
        font-size: 1.5em;
        border-top: 1px solid #8A8A8A;
        justify-content: space-between;
        align-items: center;
    }

    .informative-template .accordion-container label h5 {
        color: #484848 !important; 
    }
   
    .informative-template .accordion-container label .open-accordion-icon {
        display: block;
    }

    .informative-template .accordion-container label .close-accordion-icon {
        display: none;
    }

    .informative-template .accordion-container .accordion-content {
        padding: 10px 0px 30px 30px;
        margin: 0 0 1px 0;
        border-radius: 3px;
    }

    .informative-template .accordion-container input:checked + label h5 {
        color: #4372D6 !important;
    }

    .informative-template .accordion-container input:checked + label .open-accordion-icon {
        display: none;
    }

    .informative-template .accordion-container input:checked + label .close-accordion-icon {
        display: block;
    }

    .informative-template .accordion-container input + label + .accordion-content {
        display: none;
    }

    .informative-template .accordion-container input:checked + label + .accordion-content {
        display: flex;
    }

    .informative-template .feature-image {
        width: 100%;
        height: auto;
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .informative-template .feature-image > img {
        width: 500px;
        height: 375px;
        margin-bottom: 20px;
        border-radius: 10px
    }

    .informative-template .feature-image-button-holder {
        width: 100%;
        display: flex;
        justify-content: center;
    }

    .informative-template .feature-image-button-holder > .button-blue,
    .informative-template .feature-image-button-holder > .button-default {
        margin: 0px 10px
    }

    .informative-template .feature-image-text {
        margin-top: 20px
    }

    .informative-template .feature-center {
        text-align: center;
    }

    .informative-template .feature-center > h3 {
        margin-bottom: 30px
    }

    .informative-template .feature-center > .body-text-regular {
        margin-bottom: 30px
    }

    .informative-template .feature-center > img {
        margin-bottom: 30px;
        width: 412px;
        height: 232px;
        border-radius: 10px
    }

    @media only screen and (max-width: 768px) {
        .informative-template .info-cards {
            flex: 0 0 100%;
            padding-bottom: 32px;
        }

        .informative-template .info-cards:last-of-type {
            padding-bottom: 0px;
        }

        .informative-template .info-cards-details {
            padding: 15px
        }

        .informative-template .info-cards:nth-of-type(3n+1) {
            padding-right: 0px;
        }

        .informative-template .info-cards:nth-of-type(3n+2) {
            padding-right: 0px;
            padding-left: 0px;
        }

        .informative-template .info-cards:nth-of-type(3n+3) {
            padding-left: 0px;
        }

        .informative-template .info-cards-details .body-text-small {
            display: block;
            margin-top: 11px
        }

        .informative-template .portrait-box > img {
            width: 100%;
            height: auto;
        }

        .informative-template .portrait-box-details {
            width: 100%;
            height: auto;
            padding-left: 0px;
            padding-top: 20px;
        }

        .informative-template .portrait-box-details > h4 {
            font-size: 28px;
        }

        .informative-template .swap-image-box,
        .informative-template .swap-image-box:nth-of-type(even) {
            flex-direction: column;
        }

        .informative-template .swap-image-box > img {
            width: 100%;
            height: auto;
        }

        .informative-template .swap-image-box > .swap-image-details {
            width: 100%;
            height: auto;
            padding-left: 0px;
            padding-top: 20px;
        }

        .informative-template .accordion-container .accordion-content {
            padding: 10px 12px 30px 12px;
        }

        .informative-template .feature-image > img {
            width: 100%;
            height: auto;
            max-width: 320px;
        }

        .informative-template .feature-center > img {
            width: 100%;
            height: auto;
        }
    }
</style>

<div class="iso-template informative-template">
    <div class="section">
        <h3>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna fermentum nisi, ac mattis nulla velit eu quam.</h3>
    </div>
    <div class="section infographic">
        <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
    </div>
    <div class="section linebreak"></div>
    <div class="section">
        <h3>Lorem ipsum dolor sit amet, consectetur adipiscing elit</h3>
    </div>
    <div class="section">
        <span class="body-text-regular">Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.</span>
    </div>
    <div class="section">
        <h4>Fusce feugiat, risus id euismod gravida, lectus urna fermentum:</h4>
    </div>
    <div class="section">
        <span class="body-text-regular">Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.</span>
    </div>
    <div class="section info-cards-container">
        <div class="info-cards">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="info-cards-details">
                <h5>Praesent eu libero at velit vestibulum</h5>
                <span class="body-text-small">
                    Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
                </span>
            </div>
        </div>
        <div class="info-cards">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="info-cards-details">
                <h5>Praesent eu libero at velit vestibulum</h5>
                <span class="body-text-small">
                    Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
                </span>
            </div>
        </div>
        <div class="info-cards">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="info-cards-details">
                <h5>Praesent eu libero at velit vestibulum</h5>
                <span class="body-text-small">
                    Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
                </span>
            </div>
        </div>
    </div>
    <div class="section info-cards-container">
        <div class="info-cards">
            <div class="info-cards-details no-image">
                <h5>Praesent eu libero at velit vestibulum</h5>
                <span class="body-text-small">
                    Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
                </span>
            </div>
        </div>
        <div class="info-cards">
            <div class="info-cards-details no-image">
                <h5>Praesent eu libero at velit vestibulum</h5>
                <span class="body-text-small">
                    Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
                </span>
            </div>
        </div>
        <div class="info-cards">
            <div class="info-cards-details no-image">
                <h5>Praesent eu libero at velit vestibulum</h5>
                <span class="body-text-small">
                    Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
                </span>
            </div>
        </div>
    </div>
    <div class="section linebreak"></div>
    <div class="section">
        <h3>Lorem ipsum dolor sit amet, consectetur adipiscing elit</h3>
    </div>
    <div class="section">
        <span class="body-text-regular">Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.</span>
    </div>
    <div class="section portrait-box">
        <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
        <div class="portrait-box-details">
            <h4>“Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut,  erat.”</h4>
            <span class="body-text-small">– Vestibulum tincidunt, neque at </span>
        </div>
    </div>
    <div class="section quote-box">
        <h3>“Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut,  erat.”</h3>
        <div class="body-text-small">– Vestibulum tincidunt, neque at </div>
    </div>
    <div class="section linebreak"></div>
    <div class="section">
        <h3>Lorem ipsum dolor sit amet, consectetur adipiscing elit</h3>
    </div>
    <div class="section">
        <span class="body-text-regular">Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.</span>
    </div>
    <div class="section swap-image-container">
        <div class="swap-image-box">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="swap-image-details">
                <h4>Nam tempor in lorem nec ornare</h4>
                <span class="body-text-small">
                    Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
                    <br><br>
                    Click <a target="_blank" href="https://www.google.com/">here</a> to find out more 
                </span>
            </div>
        </div>
        <div class="swap-image-box">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="swap-image-details">
                <h4>Nam tempor in lorem nec ornare</h4>
                <span class="body-text-small">
                    Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
                    <br><br>
                    Click <a target="_blank" href="https://www.google.com/">here</a> to find out more 
                </span>
            </div>
        </div>
    </div>
    <div class="section linebreak"></div>
    <div class="section">
        <h3>Lorem ipsum dolor sit amet, consectetur adipiscing elit</h3>
    </div>
    <div class="section">
        <span class="body-text-regular">Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.</span>
    </div>
    <div class="section accordion-container">
        <input type="checkbox" id="title1">
        <label for="title1">
            <h5>Nam tempor in lorem nec ornare</h5>
            <svg class="open-accordion-icon" fill="none" viewBox="0 0 22 22" height="22" width="22" xmlns="http://www.w3.org/2000/svg"><path fill="#4372D6" d="M12.9841 12.8664L20.1104 12.8995C20.5081 12.8995 20.8727 12.5349 20.8727 12.1371V10.4799C20.8727 10.0821 20.5081 9.71752 20.1104 9.71752L12.9841 9.75066V2.59121C12.9841 2.19346 12.6195 1.82886 12.2217 1.82886H10.5644C10.1667 1.82886 9.80208 2.19346 9.80208 2.59121L9.83522 9.71752H2.67577C2.27802 9.71752 1.91342 10.0821 1.91342 10.4799V12.1371C1.91342 12.5349 2.27802 12.8995 2.67577 12.8995H9.83522L9.80208 20.0258C9.80208 20.4236 10.1667 20.7882 10.5644 20.7882H12.2217C12.6195 20.7882 12.9841 20.4236 12.9841 20.0258V12.8664Z"></path></svg><svg class="close-accordion-icon" fill="none" viewBox="0 0 21 22" height="22" width="21" xmlns="http://www.w3.org/2000/svg"><path fill="#4372D6" d="M12.7266 11.2849L17.7891 6.26929C18.0703 5.98804 18.0703 5.47241 17.7891 5.19116L16.6172 4.01929C16.3359 3.73804 15.8203 3.73804 15.5391 4.01929L10.5234 9.08179L5.46094 4.01929C5.17969 3.73804 4.66406 3.73804 4.38281 4.01929L3.21094 5.19116C2.92969 5.47241 2.92969 5.98804 3.21094 6.26929L8.27344 11.2849L3.21094 16.3474C2.92969 16.6287 2.92969 17.1443 3.21094 17.4255L4.38281 18.5974C4.66406 18.8787 5.17969 18.8787 5.46094 18.5974L10.5234 13.5349L15.5391 18.5974C15.8203 18.8787 16.3359 18.8787 16.6172 18.5974L17.7891 17.4255C18.0703 17.1443 18.0703 16.6287 17.7891 16.3474L12.7266 11.2849Z"></path></svg>
        </label>
        <div class="accordion-content">
            <div class="feature-image">
                <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
                <div class="feature-image-button-holder">
                    <div class="button-blue">
                        BUTTON
                    </div>
                    <div class="button-blue">
                        BUTTON
                        <svg fill="none" viewBox="0 0 16 17" height="17" width="16" xmlns="http://www.w3.org/2000/svg"><path fill="white" d="M10 0.723633C9.44687 0.723633 9 1.17051 9 1.72363C9 2.27676 9.44687 2.72363 10 2.72363H12.5844L6.29375 9.01738C5.90312 9.40801 5.90312 10.0424 6.29375 10.433C6.68437 10.8236 7.31875 10.8236 7.70937 10.433L14 4.13926V6.72363C14 7.27676 14.4469 7.72363 15 7.72363C15.5531 7.72363 16 7.27676 16 6.72363V1.72363C16 1.17051 15.5531 0.723633 15 0.723633H10ZM2.5 1.72363C1.11875 1.72363 0 2.84238 0 4.22363V14.2236C0 15.6049 1.11875 16.7236 2.5 16.7236H12.5C13.8813 16.7236 15 15.6049 15 14.2236V10.7236C15 10.1705 14.5531 9.72363 14 9.72363C13.4469 9.72363 13 10.1705 13 10.7236V14.2236C13 14.4986 12.775 14.7236 12.5 14.7236H2.5C2.225 14.7236 2 14.4986 2 14.2236V4.22363C2 3.94863 2.225 3.72363 2.5 3.72363H6C6.55312 3.72363 7 3.27676 7 2.72363C7 2.17051 6.55312 1.72363 6 1.72363H2.5Z"></path></svg>
                    </div>
                </div>
                <div class="feature-image-text">
                    <span class="body-text-small">
                        Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
                        <br><br>
                        Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
                    </span>
                </div>
            </div>
        </div>
        <input type="checkbox" id="title2">
        <label for="title2">
            <h5>Nam tempor in lorem nec ornare</h5>
            <svg class="open-accordion-icon" fill="none" viewBox="0 0 22 22" height="22" width="22" xmlns="http://www.w3.org/2000/svg"><path fill="#4372D6" d="M12.9841 12.8664L20.1104 12.8995C20.5081 12.8995 20.8727 12.5349 20.8727 12.1371V10.4799C20.8727 10.0821 20.5081 9.71752 20.1104 9.71752L12.9841 9.75066V2.59121C12.9841 2.19346 12.6195 1.82886 12.2217 1.82886H10.5644C10.1667 1.82886 9.80208 2.19346 9.80208 2.59121L9.83522 9.71752H2.67577C2.27802 9.71752 1.91342 10.0821 1.91342 10.4799V12.1371C1.91342 12.5349 2.27802 12.8995 2.67577 12.8995H9.83522L9.80208 20.0258C9.80208 20.4236 10.1667 20.7882 10.5644 20.7882H12.2217C12.6195 20.7882 12.9841 20.4236 12.9841 20.0258V12.8664Z"></path></svg><svg class="close-accordion-icon" fill="none" viewBox="0 0 21 22" height="22" width="21" xmlns="http://www.w3.org/2000/svg"><path fill="#4372D6" d="M12.7266 11.2849L17.7891 6.26929C18.0703 5.98804 18.0703 5.47241 17.7891 5.19116L16.6172 4.01929C16.3359 3.73804 15.8203 3.73804 15.5391 4.01929L10.5234 9.08179L5.46094 4.01929C5.17969 3.73804 4.66406 3.73804 4.38281 4.01929L3.21094 5.19116C2.92969 5.47241 2.92969 5.98804 3.21094 6.26929L8.27344 11.2849L3.21094 16.3474C2.92969 16.6287 2.92969 17.1443 3.21094 17.4255L4.38281 18.5974C4.66406 18.8787 5.17969 18.8787 5.46094 18.5974L10.5234 13.5349L15.5391 18.5974C15.8203 18.8787 16.3359 18.8787 16.6172 18.5974L17.7891 17.4255C18.0703 17.1443 18.0703 16.6287 17.7891 16.3474L12.7266 11.2849Z"></path></svg>
        </label>
        <div class="accordion-content">
            <div class="feature-image">
                <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
                <div class="feature-image-button-holder">
                    <div class="button-blue">
                        BUTTON
                    </div>
                    <div class="button-blue">
                        BUTTON
                        <svg fill="none" viewBox="0 0 16 17" height="17" width="16" xmlns="http://www.w3.org/2000/svg"><path fill="white" d="M10 0.723633C9.44687 0.723633 9 1.17051 9 1.72363C9 2.27676 9.44687 2.72363 10 2.72363H12.5844L6.29375 9.01738C5.90312 9.40801 5.90312 10.0424 6.29375 10.433C6.68437 10.8236 7.31875 10.8236 7.70937 10.433L14 4.13926V6.72363C14 7.27676 14.4469 7.72363 15 7.72363C15.5531 7.72363 16 7.27676 16 6.72363V1.72363C16 1.17051 15.5531 0.723633 15 0.723633H10ZM2.5 1.72363C1.11875 1.72363 0 2.84238 0 4.22363V14.2236C0 15.6049 1.11875 16.7236 2.5 16.7236H12.5C13.8813 16.7236 15 15.6049 15 14.2236V10.7236C15 10.1705 14.5531 9.72363 14 9.72363C13.4469 9.72363 13 10.1705 13 10.7236V14.2236C13 14.4986 12.775 14.7236 12.5 14.7236H2.5C2.225 14.7236 2 14.4986 2 14.2236V4.22363C2 3.94863 2.225 3.72363 2.5 3.72363H6C6.55312 3.72363 7 3.27676 7 2.72363C7 2.17051 6.55312 1.72363 6 1.72363H2.5Z"></path></svg>
                    </div>
                </div>
                <div class="feature-image-text">
                    <span class="body-text-small">
                        Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
                        <br><br>
                        Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
                    </span>
                </div>
            </div>
        </div>
        <input type="checkbox" id="title3">
        <label for="title3">
            <h5>Nam tempor in lorem nec ornare</h5>
            <svg class="open-accordion-icon" fill="none" viewBox="0 0 22 22" height="22" width="22" xmlns="http://www.w3.org/2000/svg"><path fill="#4372D6" d="M12.9841 12.8664L20.1104 12.8995C20.5081 12.8995 20.8727 12.5349 20.8727 12.1371V10.4799C20.8727 10.0821 20.5081 9.71752 20.1104 9.71752L12.9841 9.75066V2.59121C12.9841 2.19346 12.6195 1.82886 12.2217 1.82886H10.5644C10.1667 1.82886 9.80208 2.19346 9.80208 2.59121L9.83522 9.71752H2.67577C2.27802 9.71752 1.91342 10.0821 1.91342 10.4799V12.1371C1.91342 12.5349 2.27802 12.8995 2.67577 12.8995H9.83522L9.80208 20.0258C9.80208 20.4236 10.1667 20.7882 10.5644 20.7882H12.2217C12.6195 20.7882 12.9841 20.4236 12.9841 20.0258V12.8664Z"></path></svg><svg class="close-accordion-icon" fill="none" viewBox="0 0 21 22" height="22" width="21" xmlns="http://www.w3.org/2000/svg"><path fill="#4372D6" d="M12.7266 11.2849L17.7891 6.26929C18.0703 5.98804 18.0703 5.47241 17.7891 5.19116L16.6172 4.01929C16.3359 3.73804 15.8203 3.73804 15.5391 4.01929L10.5234 9.08179L5.46094 4.01929C5.17969 3.73804 4.66406 3.73804 4.38281 4.01929L3.21094 5.19116C2.92969 5.47241 2.92969 5.98804 3.21094 6.26929L8.27344 11.2849L3.21094 16.3474C2.92969 16.6287 2.92969 17.1443 3.21094 17.4255L4.38281 18.5974C4.66406 18.8787 5.17969 18.8787 5.46094 18.5974L10.5234 13.5349L15.5391 18.5974C15.8203 18.8787 16.3359 18.8787 16.6172 18.5974L17.7891 17.4255C18.0703 17.1443 18.0703 16.6287 17.7891 16.3474L12.7266 11.2849Z"></path></svg>
        </label>
        <div class="accordion-content">
            <div class="feature-image">
                <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
                <div class="feature-image-button-holder">
                    <div class="button-blue">
                        BUTTON
                    </div>
                    <div class="button-blue">
                        BUTTON
                        <svg fill="none" viewBox="0 0 16 17" height="17" width="16" xmlns="http://www.w3.org/2000/svg"><path fill="white" d="M10 0.723633C9.44687 0.723633 9 1.17051 9 1.72363C9 2.27676 9.44687 2.72363 10 2.72363H12.5844L6.29375 9.01738C5.90312 9.40801 5.90312 10.0424 6.29375 10.433C6.68437 10.8236 7.31875 10.8236 7.70937 10.433L14 4.13926V6.72363C14 7.27676 14.4469 7.72363 15 7.72363C15.5531 7.72363 16 7.27676 16 6.72363V1.72363C16 1.17051 15.5531 0.723633 15 0.723633H10ZM2.5 1.72363C1.11875 1.72363 0 2.84238 0 4.22363V14.2236C0 15.6049 1.11875 16.7236 2.5 16.7236H12.5C13.8813 16.7236 15 15.6049 15 14.2236V10.7236C15 10.1705 14.5531 9.72363 14 9.72363C13.4469 9.72363 13 10.1705 13 10.7236V14.2236C13 14.4986 12.775 14.7236 12.5 14.7236H2.5C2.225 14.7236 2 14.4986 2 14.2236V4.22363C2 3.94863 2.225 3.72363 2.5 3.72363H6C6.55312 3.72363 7 3.27676 7 2.72363C7 2.17051 6.55312 1.72363 6 1.72363H2.5Z"></path></svg>
                    </div>
                </div>
                <div class="feature-image-text">
                    <span class="body-text-small">
                        Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
                        <br><br>
                        Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
                    </span>
                </div>
            </div>
        </div>
        <input type="checkbox" id="title4">
        <label for="title4">
            <h5>Nam tempor in lorem nec ornare</h5>
            <svg class="open-accordion-icon" fill="none" viewBox="0 0 22 22" height="22" width="22" xmlns="http://www.w3.org/2000/svg"><path fill="#4372D6" d="M12.9841 12.8664L20.1104 12.8995C20.5081 12.8995 20.8727 12.5349 20.8727 12.1371V10.4799C20.8727 10.0821 20.5081 9.71752 20.1104 9.71752L12.9841 9.75066V2.59121C12.9841 2.19346 12.6195 1.82886 12.2217 1.82886H10.5644C10.1667 1.82886 9.80208 2.19346 9.80208 2.59121L9.83522 9.71752H2.67577C2.27802 9.71752 1.91342 10.0821 1.91342 10.4799V12.1371C1.91342 12.5349 2.27802 12.8995 2.67577 12.8995H9.83522L9.80208 20.0258C9.80208 20.4236 10.1667 20.7882 10.5644 20.7882H12.2217C12.6195 20.7882 12.9841 20.4236 12.9841 20.0258V12.8664Z"></path></svg><svg class="close-accordion-icon" fill="none" viewBox="0 0 21 22" height="22" width="21" xmlns="http://www.w3.org/2000/svg"><path fill="#4372D6" d="M12.7266 11.2849L17.7891 6.26929C18.0703 5.98804 18.0703 5.47241 17.7891 5.19116L16.6172 4.01929C16.3359 3.73804 15.8203 3.73804 15.5391 4.01929L10.5234 9.08179L5.46094 4.01929C5.17969 3.73804 4.66406 3.73804 4.38281 4.01929L3.21094 5.19116C2.92969 5.47241 2.92969 5.98804 3.21094 6.26929L8.27344 11.2849L3.21094 16.3474C2.92969 16.6287 2.92969 17.1443 3.21094 17.4255L4.38281 18.5974C4.66406 18.8787 5.17969 18.8787 5.46094 18.5974L10.5234 13.5349L15.5391 18.5974C15.8203 18.8787 16.3359 18.8787 16.6172 18.5974L17.7891 17.4255C18.0703 17.1443 18.0703 16.6287 17.7891 16.3474L12.7266 11.2849Z"></path></svg>
        </label>
        <div class="accordion-content">
            <div class="feature-image">
                <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
                <div class="feature-image-button-holder">
                    <div class="button-blue">
                        BUTTON
                    </div>
                    <div class="button-blue">
                        BUTTON
                        <svg fill="none" viewBox="0 0 16 17" height="17" width="16" xmlns="http://www.w3.org/2000/svg"><path fill="white" d="M10 0.723633C9.44687 0.723633 9 1.17051 9 1.72363C9 2.27676 9.44687 2.72363 10 2.72363H12.5844L6.29375 9.01738C5.90312 9.40801 5.90312 10.0424 6.29375 10.433C6.68437 10.8236 7.31875 10.8236 7.70937 10.433L14 4.13926V6.72363C14 7.27676 14.4469 7.72363 15 7.72363C15.5531 7.72363 16 7.27676 16 6.72363V1.72363C16 1.17051 15.5531 0.723633 15 0.723633H10ZM2.5 1.72363C1.11875 1.72363 0 2.84238 0 4.22363V14.2236C0 15.6049 1.11875 16.7236 2.5 16.7236H12.5C13.8813 16.7236 15 15.6049 15 14.2236V10.7236C15 10.1705 14.5531 9.72363 14 9.72363C13.4469 9.72363 13 10.1705 13 10.7236V14.2236C13 14.4986 12.775 14.7236 12.5 14.7236H2.5C2.225 14.7236 2 14.4986 2 14.2236V4.22363C2 3.94863 2.225 3.72363 2.5 3.72363H6C6.55312 3.72363 7 3.27676 7 2.72363C7 2.17051 6.55312 1.72363 6 1.72363H2.5Z"></path></svg>
                    </div>
                </div>
                <div class="feature-image-text">
                    <span class="body-text-small">
                        Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
                        <br><br>
                        Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
                    </span>
                </div>
            </div>
        </div>
    </div>
    <div class="section feature-center">
        <h3>
            Nam tempor in lorem nec ornare
        </h3>
        <div class="body-text-regular">
            Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
        </div>
        <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
        <div class="feature-image-button-holder">
            <div class="button-blue">
                BUTTON
            </div>
            <div class="button-blue">
                BUTTON
                <svg fill="none" viewBox="0 0 16 17" height="17" width="16" xmlns="http://www.w3.org/2000/svg"><path fill="white" d="M10 0.723633C9.44687 0.723633 9 1.17051 9 1.72363C9 2.27676 9.44687 2.72363 10 2.72363H12.5844L6.29375 9.01738C5.90312 9.40801 5.90312 10.0424 6.29375 10.433C6.68437 10.8236 7.31875 10.8236 7.70937 10.433L14 4.13926V6.72363C14 7.27676 14.4469 7.72363 15 7.72363C15.5531 7.72363 16 7.27676 16 6.72363V1.72363C16 1.17051 15.5531 0.723633 15 0.723633H10ZM2.5 1.72363C1.11875 1.72363 0 2.84238 0 4.22363V14.2236C0 15.6049 1.11875 16.7236 2.5 16.7236H12.5C13.8813 16.7236 15 15.6049 15 14.2236V10.7236C15 10.1705 14.5531 9.72363 14 9.72363C13.4469 9.72363 13 10.1705 13 10.7236V14.2236C13 14.4986 12.775 14.7236 12.5 14.7236H2.5C2.225 14.7236 2 14.4986 2 14.2236V4.22363C2 3.94863 2.225 3.72363 2.5 3.72363H6C6.55312 3.72363 7 3.27676 7 2.72363C7 2.17051 6.55312 1.72363 6 1.72363H2.5Z"></path></svg>
            </div>
        </div>
    </div>
    <div class="section feature-center">
        <div class="feature-image-button-holder">
            <img class="button-image" alt="" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAJQAAAArCAMAAACpflFGAAAAP1BMVEUAAAD////f39+/v78/Pz8fHx8QEBBfX1+fn59/f3/v7++Pj48wMDDPz8+vr69vb29PT09wcHCAgIBQUFALCwus2gJnAAADyklEQVRYw+zU2YrbQBCF4VNbV+/a8v7PmshScGwraBTCDAP+QCBV98UPBcLb29vbNxa04oGllBb8xVDwbIknl6+bMo14oDlG5oBD6bXABQdU7pevmomo4oEyACnA1KOhVEwOHVC0d0OK+xzeZQG0xyRb23oc4iQxAAg9R6Q4iwPWxXFBJSLGQZQz5jZOHEoCC8oALiodKe7z2nXMwSgpy62JR1+/i7ayRk1NkdroVI29titVnYjqUZQ2NAXYVUwktAqucEGK+xzBncwFGG5RMqyP0ba0+/pYF3bvVxaZKTuOomIHj0AbA7ungQG2LWqfL5z2KN+iHOjpKMqbuys+Lg4Br1FmM1WUCM0G4aoc71H7fOhQMs01bOtLzSrbH1Ec9qiQDdOCc2GWnKOuL0zUouGuMnNfj2JuCngDmgNiGDuGss+t5SSGlFvqWJXMA4x//wiC8O1NFAuTBJyqTDfcaMMVX80yPWN8NaFnueKT/cAjpReOf1ZVw3+IKvSs4YkTJXxAmDP9Eg1XhbPtvQYwkeCcMRH/bLdMkhuHYSjKDxIcQE2J73/Xbgiw5FhVdKcrCy/yFzZJQeLDIFBxBkipWuP/h5pfZm8CCVJ4qQpJxqYuAOkbUE/5o5dQFbX+S/5m1KC6Afm7UPlV+uoleylB7HSkLUUg6n4rdV4EczntuueRQydAaLN+7DaRpi5LCFMUSOURVMWz5KtFAoXs+YvoRzQbIkH1ebr34bfuUESb1ZmYo4QFiBpI0VUeQBVcFJ+zpz/d911yYFLwBlAKvBx5mkTvbT6z5ao24QNoCoXGzISeA8+IA6iMq+LphQcpWfwiSP8YWBWK7brnWwFVVA6o7BXaIAqlhgXk2z5uMuwJ11ZVQLZ12W3rUdPNrboauHirM4B+h0pA9g7NgfZHLIhFJSgDqIRhT4+Q+FeCuE/akdLmCVhBl3Y1OVQBbE2XyP1yDaHCPDqQGYfyXuhOekaqgS5f1cWhboAtPUaqJlMeQaVRoAqIVZNgVRiLjk6aldmxloDp7sfmUAwke4oEh+qI4z7l6oNGNd9nVR8WrQF8quPNaufj7kMWzGyWYIUqRpz3jFaHUvbksbt09EGt04Htrp6BiCDEGnecBgLV6Mk2PFpaFTs99WLSval3AbFBWQhq64I+OPtUuQLSEqdOj/3A+szZGpoWeoO/Xg3xRni0LwSVrPvEymAimM0BpSHW7cJL8XQf8NP30fQwVKjA25aDQYWcyhf7tLaSfJy9lKfNbXTuV4oOf0oKZTKot9BbQlVaj/FKS/jVr95XfwB09R5uLWLOgQAAAABJRU5ErkJggg==">
            <img class="button-image" alt="" src="data:image/png;base64,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">
        </div>
    </div>
</div>