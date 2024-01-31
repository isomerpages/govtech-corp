---
title: Listing
permalink: /test-folder/listing/
variant: markdown
description: ""
---
<style>
    .iso-template {
        width: 100%;
        display: flex;
        flex-direction: column;
    }

    .iso-template h3 {
        color: #0061AF;
        font-family: Lato;
        font-size: 32px;
        font-style: normal;
        font-weight: 700;
        line-height: 45px;
        margin-bottom: 0px;
        margin-top: 0px;
    }

    .iso-template h4 {
        color: #0061AF;
        font-family: Lato;
        font-size: 26px;
        font-style: normal;
        font-weight: 700;
        line-height: 32px;
        margin-bottom: 0px;
        margin-top: 0px;
    }

    .iso-template h5 {
        color: #0061AF;
        font-family: Lato;
        font-size: 24px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        margin-bottom: 0px;
        margin-top: 0px;
    }

    .iso-template h6 {
        color: #0061AF;
        font-family: Lato;
        font-size: 20px;
        font-style: normal;
        font-weight: 700;
        margin-bottom: 0px;
        margin-top: 0px;
    }
    
    .iso-template .text-label-1 {
        color: #4D4D4F;
        font-family: Lato;
        font-size: 16px;
        font-style: normal;
        font-weight: 400;
        line-height: 22px; 
        text-transform: uppercase;
    }

    .iso-template .text-label-2 {
        color: #4D4D4F;
        font-family: Lato;
        font-size: 15px;
        font-style: normal;
        font-weight: 400;
        line-height: 22px; 
        text-transform: uppercase;
    }

    .iso-template .text-body-1 {
        color: #4D4D4F;
        font-family: Lato;
        font-size: 20px;
        font-style: normal;
        font-weight: 400;
        line-height: 32px;
    }

    .iso-template .text-body-2 {
        color: #4D4D4F;
        font-family: Lato;
        font-size: 16px;
        font-style: normal;
        font-weight: 400;
        line-height: 24px; 
    }

    .iso-template a {
        color: #B41E8E;
        font-family: Lato;
        font-style: normal;
        font-weight: 700;
    }

    .iso-template .button-default {
        width: auto;
        height: auto;
        padding: 15px 20px;
        border-radius: 8px;
        border: 1px solid #4372D6;
        color: #4372D6;
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
        color: #fff;
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

    .iso-template .section {
        width: 100%;
        position: relative;
        margin-bottom: 40px
    }

    .iso-template .line-divider {
        width: 100%;
        height: 1px;
        background-color: #D8D9DA;
    }

    @media only screen and (max-width: 768px) {
        .iso-template .section {
            margin-bottom: 32px
        }

        .iso-template h3 {
            font-size: 28px;
        }

        .iso-template h4 {
            font-size: 24px;
        }

        .iso-template h5 {
            font-size: 22px;
        }

        .iso-template h6 {
            font-size: 22px;
        }
    }
</style>
<style>
    .iso-template .section.card-one-container {
        width: 100%;
        margin-top: 22px;
    }

    .iso-template .card-one-box {
        border-top: 1px solid #d6d6d6;
        width: 100%;
        height: auto;
        min-height: 205px;
        padding: 20px 0px;
        display: flex;
        flex-direction: row;
    }

    .iso-template .card-one-box:last-of-type {
        border-bottom: 1px solid #d6d6d6;
    }

    .iso-template .card-one-box > img {
        width: 273px;
        height: 205px;
        border-radius: 10px;
    }

    .iso-template .card-one-details {
        width: calc(100% - 273px);
        height: auto;
        box-sizing: border-box;
        padding: 0px 20px;
    }

    .iso-template .card-one-title {
        width: 100%;
        height: auto;
        float: left;
    }

    .iso-template .card-one-text {
        width: 100%;
        height: auto;
        padding: 12px 0px;
        float: left;
    }

    @media only screen and (max-width: 768px) {
        .iso-template .card-one-box {
            flex-direction: column-reverse;
        }

        .iso-template .card-one-box > img {
            width: 100%;
            height: auto;
            margin-top: 20px;
        }

        .iso-template .card-one-details {
            width: 100%;
            padding: 0px;
        }
    }
</style>
<style>
    .iso-template .card-two-container {
        width: 100%;
        margin-top: 22px;
        display: flex;
        flex-wrap: wrap;
    }

    .iso-template .card-two-box {
        height: auto;
        flex: 0 0 50%;
        box-sizing: border-box;
        padding-bottom: 44px
    }

    .iso-template .card-two-box:nth-of-type(odd) {
        padding-right: 12px;
    }

    .iso-template .card-two-box:nth-of-type(even) {
        padding-left: 12px;
    }

    .iso-template .card-two-box > img {
        width: 100%;
        height: auto;
        border-radius: 10px;
    }

    .iso-template .card-two-details {
        width: 100%;
        height: auto;
        box-sizing: border-box;
        padding-top: 20px;
    }

    .iso-template .card-two-title {
        width: 100%;
        height: auto;
        float: left;
    }

    .iso-template .card-two-text {
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
        .iso-template .card-two-box {
            flex: 0 0 100%;
        }

        .iso-template .card-two-box:nth-of-type(odd) {
            padding-right: 0px;
        }

        .iso-template .card-two-box:nth-of-type(even) {
            padding-left: 0px;
        }
    }
</style>
<style>
    .iso-template .card-three-container {
        width: 100%;
        margin-top: 22px;
        display: flex;
        flex-wrap: wrap;
    }

    .iso-template .card-three-box {
        height: auto;
        flex: 0 0 33.33333%;
        box-sizing: border-box;
        padding-bottom: 44px
    }

    .iso-template .card-three-box:nth-of-type(3n+1) {
        padding-right: 16px;
    }

    .iso-template .card-three-box:nth-of-type(3n+2) {
        padding-right: 8px;
        padding-left: 8px;
    }

    .iso-template .card-three-box:nth-of-type(3n+3) {
        padding-left: 16px;
    }

    .iso-template .card-three-box > img {
        width: 100%;
        height: auto;
        border-radius: 10px;
    }

    .iso-template .card-three-details {
        width: 100%;
        height: auto;
        box-sizing: border-box;
        padding-top: 20px;
    }

    .iso-template .card-three-title {
        width: 100%;
        height: auto;
        float: left;
    }

    .iso-template .card-three-text {
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
        .iso-template .card-three-box {
            flex: 0 0 100%;
        }

        .iso-template .card-three-box:nth-of-type(3n+1) {
            padding-right: 0px;
        }

        .iso-template .card-three-box:nth-of-type(3n+2) {
            padding-right: 0px;
            padding-left: 0px;
        }

        .iso-template .card-three-box:nth-of-type(3n+3) {
            padding-left: 0px;
        }
    }
</style>
<div class="iso-template">
    <div class="section">
        <h3>[H3] Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna fermentum nisi, ac mattis nulla velit eu quam.</h3>
    </div>
    <div class="section line-divider"></div>
    <div class="section">
        <h4>[H4] Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna fermentum nisi, ac mattis nulla velit eu quam.</h4>
    </div>
    <div class="section">
        <span class="text-body-1">
            <a href="https://www.google.com.sg/">Quisque scelerisque</a> tellus vitae massa pulvinar, eu posuere diam convallis.
        </span>
    </div>
    <div class="section">
        <span class="text-body-1">
            [Body 1] <b>Lorem ipsum dolor</b> sit amet, consectetur adipiscing elit. Aliquam vestibulum lectus risus, id maximus nibh consectetur aliquam. In sit amet efficitur nisl. 
        </span>
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