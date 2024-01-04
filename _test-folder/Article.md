---
title: Article
permalink: /test-folder/article/
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
    .article-template {
        width: 100%;
        display: flex;
        flex-direction: column;
    }

    .article-template .section {
        width: 100%;
        position: relative;
        margin-bottom: 44px
    }

    .article-template .section.tldr {
        background-color: #f5f5f5;
        border-radius: 10px;
        padding: 24px 30px;
    }

    .article-template .section.tldr > h5{
        padding-bottom: 15px;
    }

    .article-template .section.linebreak {
        width: 100%;
        height: 1px;
        background-color: #D6D6D6;
        position: relative;
    }

    .article-template .banner-image {
        width: 100%;
        height: auto;
        border-radius: 10px;
    }

    .article-template .section.swap-image-container {
        display: flex;
        flex-direction: column;
    }

    .article-template .swap-image-box {
        display: flex;
        flex-direction: row;
        margin-bottom: 44px;
    }

    .article-template .swap-image-box:last-of-type {
        margin-bottom: 0px;
    }

    .article-template .swap-image-box:nth-of-type(even) {
        flex-direction: row-reverse;
    }

    .article-template .swap-image-box > img {
        width: 294px;
        height: 221px;
        border-radius: 10px
    }

    .article-template .swap-image-box > .swap-image-details {
        width: calc(100% - 294px);
        height: 221px;
        box-sizing: border-box;
        padding-left: 26px;
        display: flex;
        justify-content: center;
        flex-direction: column;
    }

    .article-template .swap-image-box:nth-of-type(even) > .swap-image-details {
        padding-left: 0px;
        padding-right: 26px;
    }

    .article-template .swap-image-details > h4 {
        margin-bottom: 30px
    }

    .article-template .section.swap-banner-container {
        display: flex;
        flex-direction: column;
    }

    .article-template .swap-banner-box {
        display: flex;
        flex-direction: row;
        margin-bottom: 44px;
        background-position: center;
        background-size: cover;
        border-radius: 10px;
    }

    .article-template .swap-banner-box:last-of-type {
        margin-bottom: 0px;
    }

    .article-template .swap-banner-box:nth-of-type(even) {
        flex-direction: row-reverse;
    }

    .article-template .swap-banner-box > .swap-banner-details {
        width: 55%;
        height: 300px;
        box-sizing: border-box;
        padding-left: 26px;
        display: flex;
        justify-content: center;
        flex-direction: column;
    }

    .article-template .swap-banner-box:nth-of-type(even) > .swap-banner-details {
        padding-left: 0px;
        padding-right: 26px;
    }

    .article-template .swap-banner-details > h3 {
        margin-bottom: 30px
    }

    .article-template .swap-banner-details > .body-text-small {
        margin-bottom: 30px
    }

    .article-template .section.card-banner-container,
    .article-template .section.card-banner-container-three  {
        display: flex;
        flex-wrap: wrap;
    }

    .article-template .card-banner-box {
        flex: 0 0 50%;
        position: relative;
    }

    .article-template .section.card-banner-container-three .card-banner-box {
        flex: 0 0 33%;
    }

    .article-template .card-banner-image {
        width: calc(100% - 12px);
        box-sizing: border-box;
        padding: 30px;
        background-position: center;
        background-size: cover;
        border-radius: 10px;
        height: 300px
    }

    .article-template .card-banner-box:nth-of-type(odd) .card-banner-image {
        margin-right: 12px;
    }

    .article-template .card-banner-box:nth-of-type(even) .card-banner-image {
        margin-left: 12px;
    }

    .article-template .section.card-banner-container-three .card-banner-image {
        width: calc(100% - 16px);
    }

    .article-template .section.card-banner-container-three .card-banner-box:nth-of-type(3n-2) .card-banner-image {
        margin-right: 16px;
    }

    .article-template .section.card-banner-container-three .card-banner-box:nth-of-type(3n-1) .card-banner-image {
        margin-right: 8px;
        margin-left: 8px;
    }

    .article-template .section.card-banner-container-three .card-banner-box:nth-of-type(3n-0) .card-banner-image {
        margin-left: 16px;
    }

    .article-template .card-banner-image h3,
    .article-template .card-banner-image h5 {
        margin-bottom: 15px
    }

    .article-template .section.related-content h5 {
        margin-bottom: 44px
    }

    .article-template .section.related-content ul,
    .article-template .section.related-content li,
    .article-template .section.related-content a {
        color: #4372D6
    }

    @media only screen and (max-width: 768px) {
        .article-template .section.tldr {
            padding: 18px 24px;
        }

        .article-template .swap-image-box,
        .article-template .swap-image-box:nth-of-type(even) {
            flex-direction: column;
        }

        .article-template .swap-image-box > img {
            width: 100%;
            height: auto
        }

        .article-template .swap-image-box > .swap-image-details {
            width: 100%;
            height: auto;
            padding-left: 0px;
            padding-top: 20px;
        }

        .article-template .swap-banner-box {
            min-height: 100vw;
        }

        .article-template .swap-banner-box > .swap-banner-details,
        .article-template .swap-banner-box:nth-of-type(even) > .swap-banner-details {
            width: 100%;
            height: auto;
            justify-content: flex-start;
            padding-left: 30px;
            padding-right: 30px;
            padding-top: 30px;
            padding-bottom: 30px;
        }

        .article-template .card-banner-box {
            flex: 0 0 100%;
        }

        .article-template .section.card-banner-container-three .card-banner-box {
            flex: 0 0 100%;
        }

        .article-template .card-banner-image {
            width: 100%;
            height: auto;
            min-height: 90vw;
            margin-bottom: 44px;
        }

        .article-template .card-banner-box:nth-of-type(odd) .card-banner-image {
            margin-right: 0px;
        }

        .article-template .card-banner-box:nth-of-type(even) .card-banner-image {
            margin-left: 0px;
        }

        .article-template .section.card-banner-container-three .card-banner-image {
            width: 100%;
            height: auto;
            min-height: 90vw;
            margin-bottom: 44px;
        }

        .article-template .section.card-banner-container-three .card-banner-box:nth-of-type(3n-2) .card-banner-image {
            margin-right: 0px;
        }

        .article-template .section.card-banner-container-three .card-banner-box:nth-of-type(3n-1) .card-banner-image {
            margin-right: 0px;
            margin-left: 0px;
        }

        .article-template .section.card-banner-container-three .card-banner-box:nth-of-type(3n-0) .card-banner-image {
            margin-left: 0px;
        }
    }
</style>

<div class="iso-template article-template">
    <div class="section">
        <img class="banner-image" alt="" src="https://i.ibb.co/9gLh4zh/image-63-4.jpg">
    </div>
    <div class="section">
        <h3>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna fermentum nisi, ac mattis nulla velit eu quam.</h3>
    </div>
    <div class="section tldr">
        <h5>TL;DR</h5>
        <span class="body-text-regular">Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.</span>
    </div>
    <div class="section linebreak"></div>
    <div class="section">
        <h3>Lorem ipsum dolor sit amet, consectetur adipiscing elit</h3>
    </div>
    <div class="section">
        <span class="body-text-regular">Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.</span>
    </div>
    <div class="section">
        <h5>Fusce feugiat, risus id euismod gravida, lectus urna fermentum:</h5>
    </div>
    <div class="section">
        <img class="banner-image" alt="" src="https://i.ibb.co/9YkB81q/sample-2.jpg">
    </div>
    <div class="section">
        <img class="banner-image" alt="" src="https://i.ibb.co/j5qfrLs/image-63-3.jpg">
    </div>
    <div class="section">
        <img class="banner-image" alt="" src="https://i.ibb.co/8836Zxf/Rectangle-10.jpg">
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
    <div class="section swap-banner-container">
        <div style="background-image: url(https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png)" class="swap-banner-box">
            <div class="swap-banner-details">
                <h3>Nam tempor in lorem nec ornare</h3>
                <span class="body-text-small">
                    Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
                </span>
                <span>
                    <div class="button-blue">BUTTON</div>
                </span>
            </div>
        </div>
        <div style="background-image: url(https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png)" class="swap-banner-box">
            <div class="swap-banner-details">
                <h3>Nam tempor in lorem nec ornare</h3>
                <span class="body-text-small">
                    Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
                </span>
                <span>
                    <div class="button-blue">BUTTON</div>
                </span>
            </div>
        </div>
    </div>
    <div class="section linebreak"></div>
    <div class="section card-banner-container">
        <div class="card-banner-box">
            <div style="background-image: url(https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png)" class="card-banner-image">
                <h3>Nam tempor in lorem nec ornare</h3>
                <a class="anchorlink" href="https://www.google.com/">HYPERLINK</a>
            </div>
        </div>
        <div class="card-banner-box">
            <div style="background-image: url(https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png)" class="card-banner-image">
                <h3>Nam tempor in lorem nec ornare</h3>
                <a class="anchorlink" href="https://www.google.com/">HYPERLINK</a>
            </div>
        </div>
    </div>
    <div class="section card-banner-container-three">
        <div class="card-banner-box">
            <div style="background-image: url(https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png)" class="card-banner-image">
                <h5>Nam tempor in lorem nec ornare</h5>
                <a class="anchorlink" href="https://www.google.com/">HYPERLINK</a>
            </div>
        </div>
        <div class="card-banner-box">
            <div style="background-image: url(https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png)" class="card-banner-image">
                <h5>Nam tempor in lorem nec ornare</h5>
                <a class="anchorlink" href="https://www.google.com/">HYPERLINK</a>
            </div>
        </div>
        <div class="card-banner-box">
            <div style="background-image: url(https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png)" class="card-banner-image">
                <h5>Nam tempor in lorem nec ornare</h5>
                <a class="anchorlink" href="https://www.google.com/">HYPERLINK</a>
            </div>
        </div>
    </div>
    <div class="section linebreak"></div>
    <div class="section related-content">
        <h5>Related Content</h5>
        <ul class="body-text-regular">
            <li><a href="#dummy-1">Vestibulum tincidunt neque at elit dictum cursus</a></li>
            <li><a href="#dummy-2">Praesent eu libero at velit vestibulum sollicitudin vel non lorem</a></li>
            <li><a href="#dummy-3">Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.</a></li>
            <li><a href="#dummy-4">Nam tempor in lorem nec ornare</a></li>
            <li><a href="#dummy-5">Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum </a></li>
        </ul>
    </div>
</div>