---
title: Listing
permalink: /test-folder/listing/
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
    .listing-template {
        width: 100%;
        display: flex;
        flex-direction: column;
    }

    .listing-template .section {
        width: 100%;
        position: relative;
    }

    .listing-template .section.heading-text {
        padding-bottom: 44px;
        border-bottom: 1px solid #d6d6d6;
        margin-bottom: 22px;
    }

    .listing-template .section.article-title {
        padding-top: 22px;
        padding-bottom: 22px;
    }

    .listing-template .section.article-subtitle {
        padding-top: 22px;
        padding-bottom: 22px;
    }

    .listing-template .section.article-text {
        padding-top: 22px;
        padding-bottom: 22px;
    }

    .listing-template .section.card-one-container {
        width: 100%;
        margin-top: 22px;
    }
</style>
<style>
    .listing-template .card-one-box {
        border-top: 1px solid #d6d6d6;
        width: 100%;
        height: auto;
        min-height: 205px;
        padding: 20px 0px;
        display: flex;
        flex-direction: row;
    }

    .listing-template .card-one-box:last-of-type {
        border-bottom: 1px solid #d6d6d6;
    }

    .listing-template .card-one-box > img {
        width: 273px;
        height: 205px;
    }

    .listing-template .card-one-details {
        width: calc(100% - 273px);
        height: auto;
        box-sizing: border-box;
        padding: 0px 20px;
    }

    .listing-template .card-one-title {
        width: 100%;
        height: auto;
        float: left;
    }

    .listing-template .card-one-text {
        width: 100%;
        height: auto;
        padding: 12px 0px;
        float: left;
    }

    @media only screen and (max-width: 768px) {
        .listing-template .card-one-box {
            flex-direction: column-reverse;
        }

        .listing-template .card-one-box > img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            margin-top: 20px;
        }

        .listing-template .card-one-details {
            width: 100%;
            padding: 0px;
        }
    }
</style>
<style>
    .listing-template .card-two-container {
        width: 100%;
        margin-top: 22px;
        display: flex;
        flex-wrap: wrap;
    }

    .listing-template .card-two-box {
        height: auto;
        flex: 0 0 50%;
        box-sizing: border-box;
        padding-bottom: 44px
    }

    .listing-template .card-two-box:nth-of-type(odd) {
        padding-right: 12px;
    }

    .listing-template .card-two-box:nth-of-type(even) {
        padding-left: 12px;
    }

    .listing-template .card-two-box > img {
        width: 410px;
        height: 301px;
    }

    .listing-template .card-two-details {
        width: 100%;
        height: auto;
        box-sizing: border-box;
        padding-top: 20px;
    }

    .listing-template .card-two-title {
        width: 100%;
        height: auto;
        float: left;
    }

    .listing-template .card-two-text {
        width: 100%;
        height: auto;
        padding: 12px 0px;
        float: left;
    }

    @media only screen and (max-width: 1279px) {
        
    }

    @media only screen and (max-width: 1023px) {
        
    }

    @media only screen and (max-width: 768px) {
        .listing-template .card-two-box {
            flex: 0 0 100%;
        }

        .listing-template .card-two-box:nth-of-type(odd) {
            padding-right: 0px;
        }

        .listing-template .card-two-box:nth-of-type(even) {
            padding-left: 0px;
        }

        .listing-template .card-two-box > img {
            width: 100%;
            height: auto
        }
    }
</style>
<style>
    .listing-template .card-three-container {
        width: 100%;
        margin-top: 22px;
        display: flex;
        flex-wrap: wrap;
    }

    .listing-template .card-three-box {
        height: auto;
        flex: 0 0 33.33333%;
        box-sizing: border-box;
        padding-bottom: 44px
    }

    .listing-template .card-three-box:nth-of-type(3n+1) {
        padding-right: 16px;
    }

    .listing-template .card-three-box:nth-of-type(3n+2) {
        padding-right: 8px;
        padding-left: 8px;
    }

    .listing-template .card-three-box:nth-of-type(3n+3) {
        padding-left: 16px;
    }

    .listing-template .card-three-box > img {
        width: 410px;
        height: 301px;
    }

    .listing-template .card-three-details {
        width: 100%;
        height: auto;
        box-sizing: border-box;
        padding-top: 20px;
    }

    .listing-template .card-three-title {
        width: 100%;
        height: auto;
        float: left;
    }

    .listing-template .card-three-text {
        width: 100%;
        height: auto;
        padding: 12px 0px;
        float: left;
    }

    @media only screen and (max-width: 1279px) {
        
    }

    @media only screen and (max-width: 1023px) {
        
    }

    @media only screen and (max-width: 768px) {
        .listing-template .card-three-box {
            flex: 0 0 100%;
        }

        .listing-template .card-three-box:nth-of-type(3n+1) {
            padding-right: 0px;
        }

        .listing-template .card-three-box:nth-of-type(3n+2) {
            padding-right: 0px;
            padding-left: 0px;
        }

        .listing-template .card-three-box:nth-of-type(3n+3) {
            padding-left: 0px;
        }

        .listing-template .card-three-box > img {
            width: 100%;
            height: auto;
        }
    }
</style>
<div class="iso-template listing-template">
    <div class="section heading-text">
        <h3>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna fermentum nisi, ac mattis nulla velit eu quam.</h3>
    </div>
    <div class="section article-title">
        <h3>Lorem ipsum dolor sit amet, consectetur adipiscing elit</h3>
    </div>
    <div class="section article-text">
        <span class="body-text-regular">Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.</span>
    </div>
    <div class="section article-subtitle">
        <h5>Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.</h5>
    </div>
    <div class="section article-text">
        <span class="body-text-regular">Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.</span>
    </div>
    <div class="section card-one-container">
        <div class="card-one-box">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="card-one-details">
                <div class="card-one-title">
                    <h4>Card title</h4>
                </div>
                <div class="card-one-text">
                    <span class="body-text-small">Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna velit eu.</span>
                </div>
                <div class="button-default">
                    BUTTON
                </div>
            </div>
        </div>
        <div class="card-one-box">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="card-one-details">
                <div class="card-one-title">
                    <h4>Card title</h4>
                </div>
                <div class="card-one-text">
                    <span class="body-text-small">Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna velit eu.</span>
                </div>
                <div class="button-default">
                    BUTTON
                </div>
            </div>
        </div>
        <div class="card-one-box">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="card-one-details">
                <div class="card-one-title">
                    <h4>Card title</h4>
                </div>
                <div class="card-one-text">
                    <span class="body-text-small">Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna velit eu.</span>
                </div>
                <div class="button-default">
                    BUTTON
                </div>
            </div>
        </div>
    </div>
    <div class="section card-two-container">
        <div class="card-two-box">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="card-two-details">
                <div class="card-two-title">
                    <h4>Card title</h4>
                </div>
                <div class="card-two-text">
                    <span class="body-text-small">Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna velit eu.</span>
                </div>
                <div class="button-default">
                    BUTTON
                </div>
            </div>
        </div>
        <div class="card-two-box">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="card-two-details">
                <div class="card-two-title">
                    <h4>Card title</h4>
                </div>
                <div class="card-two-text">
                    <span class="body-text-small">Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna velit eu.</span>
                </div>
                <div class="button-default">
                    BUTTON
                </div>
            </div>
        </div>
        <div class="card-two-box">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="card-two-details">
                <div class="card-two-title">
                    <h4>Card title</h4>
                </div>
                <div class="card-two-text">
                    <span class="body-text-small">Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna velit eu.</span>
                </div>
                <div class="button-default">
                    BUTTON
                </div>
            </div>
        </div>
        <div class="card-two-box">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="card-two-details">
                <div class="card-two-title">
                    <h4>Card title</h4>
                </div>
                <div class="card-two-text">
                    <span class="body-text-small">Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna velit eu.</span>
                </div>
                <div class="button-default">
                    BUTTON
                </div>
            </div>
        </div>
    </div>
    <div class="section card-three-container">
        <div class="card-three-box">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="card-three-details">
                <div class="card-three-title">
                    <h4>Card title</h4>
                </div>
                <div class="card-three-text">
                    <span class="body-text-small">Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna velit eu.</span>
                </div>
                <div class="button-default">
                    BUTTON
                </div>
            </div>
        </div>
        <div class="card-three-box">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="card-three-details">
                <div class="card-three-title">
                    <h4>Card title</h4>
                </div>
                <div class="card-three-text">
                    <span class="body-text-small">Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna velit eu.</span>
                </div>
                <div class="button-default">
                    BUTTON
                </div>
            </div>
        </div>
        <div class="card-three-box">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="card-three-details">
                <div class="card-three-title">
                    <h4>Card title</h4>
                </div>
                <div class="card-three-text">
                    <span class="body-text-small">Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna velit eu.</span>
                </div>
                <div class="button-default">
                    BUTTON
                </div>
            </div>
        </div>
        <div class="card-three-box">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="card-three-details">
                <div class="card-three-title">
                    <h4>Card title</h4>
                </div>
                <div class="card-three-text">
                    <span class="body-text-small">Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna velit eu.</span>
                </div>
                <div class="button-default">
                    BUTTON
                </div>
            </div>
        </div>
        <div class="card-three-box">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="card-three-details">
                <div class="card-three-title">
                    <h4>Card title</h4>
                </div>
                <div class="card-three-text">
                    <span class="body-text-small">Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna velit eu.</span>
                </div>
                <div class="button-default">
                    BUTTON
                </div>
            </div>
        </div>
        <div class="card-three-box">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="card-three-details">
                <div class="card-three-title">
                    <h4>Card title</h4>
                </div>
                <div class="card-three-text">
                    <span class="body-text-small">Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna velit eu.</span>
                </div>
                <div class="button-default">
                    BUTTON
                </div>
            </div>
        </div>
    </div>
</div>