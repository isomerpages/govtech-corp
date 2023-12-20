---
title: Headshot
permalink: /test-folder/headshot/
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
    .headshot-template {
        width: 100%;
        display: flex;
        flex-direction: column;
    }

    .headshot-template .section {
        width: 100%;
        position: relative;
    }

    .headshot-template .section.anchor-links {
        display: flex;
        flex-direction: row;
        text-align: left;
    }

    .headshot-template .section.anchor-links a {
        margin-bottom: 0px;
        margin-right: 44px;
    }

    .headshot-template .section.page-title {
        text-align: left;
        margin: 44px 0px;
    }

    .headshot-template .headshot-item {
        width: calc(50% - 12px);
        height: 138px;
        border-radius: 10px;
        float: left;
        overflow: hidden;
        margin-bottom: 24px;
    }

    .headshot-template .headshot-item:nth-of-type(odd) {
        margin-right: 12px;
    }

    .headshot-template .headshot-item:nth-of-type(even) {
        margin-left: 12px;
    }

    .headshot-template .headshot-item > img {
        width: 138px;
        height: 138px;
        float: left
    }

    .headshot-template .headshot-item .headshot-details {
        width: calc(100% - 138px);
        height: 138px;
        float: left;
        display: flex;
        flex-direction: column;
        position: relative;
        box-sizing: border-box;
        padding: 12px;
        justify-content: center;
        background-color: #f5f5f5;
    }

    .headshot-template .headshot-item .headshot-details .headshot-name {
        width: 100%;
        height: auto;
    }

    .headshot-template .headshot-item .headshot-details .headshot-title {
        width: 100%;
        height: auto;
    }

    .headshot-template .headshot-item .headshot-details .headshot-department {
        width: 100%;
        height: auto;
    }

    @media only screen and (max-width: 1279px) {
        .headshot-template .headshot-item {
            width: 100%;
        }

        .headshot-template .headshot-item:nth-of-type(odd) {
            margin-right: 0px;
        }

        .headshot-template .headshot-item:nth-of-type(even) {
            margin-left: 0px;
        }
    }

    @media only screen and (max-width: 1023px) {
        .headshot-template .headshot-item {
            width: calc(50% - 12px);
        }

        .headshot-template .headshot-item:nth-of-type(odd) {
            margin-right: 12px;
        }

        .headshot-template .headshot-item:nth-of-type(even) {
            margin-left: 12px;
        }
    }

    @media only screen and (max-width: 768px) {
        .headshot-template .section.anchor-links {
            flex-direction: column;
        }

        .headshot-template .section.anchor-links a {
            margin-bottom: 4px;
            margin-right: 0px;
            width: 100%;
        }

        .headshot-template .section.page-title {
            margin: 47px 0px 32px;
        }

        .headshot-template .headshot-item {
            width: 100%;
            height: auto;
            margin-bottom: 32px;
        }

        .headshot-template .headshot-item:nth-of-type(odd),
        .headshot-template .headshot-item:nth-of-type(even) {
            margin-right: 0px;
            margin-left: 0px;
        }

        .headshot-template .headshot-item > img {
            width: 100%;
            height: auto;
        }

        .headshot-template .headshot-item .headshot-details {
            width: 100%;
            height: auto;
        }
    }
</style>

<div class="iso-template headshot-template">
    <div class="section anchor-links">
        <a class="anchorlink" href="#anchorlink-1">ANCHORLINK #1</a>
        <a class="anchorlink" href="#anchorlink-2">ANCHORLINK #2</a>
    </div>
    <div class="section page-title">
        <h3>Section Title</h3>
    </div>
    <div class="section headshot-items-container">
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    <span class="body-text-bold">Mr Leong Weng Keong Joseph</span>
                </div>
                <div class="headshot-title">
                    <span class="body-text-small">Chairman</span>
                </div>
                <div class="headshot-department">
                    <span class="body-text-small-bold">Permanent Secretary (Smart Nation and Digital Government)</span>
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    <span class="body-text-bold">Ms Vaishali Rastogi</span>
                </div>
                <div class="headshot-title">
                    <span class="body-text-small">Global leader of technology, media and telecommunications business</span>
                </div>
                <div class="headshot-department">
                    <span class="body-text-small-bold">BCG</span>
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    <span class="body-text-bold">Mr Augustin Lee</span>
                </div>
                <div class="headshot-title">
                    <span class="body-text-small">Deputy Chairman</span>
                </div>
                <div class="headshot-department">
                    <span class="body-text-small-bold">Second Permanent Secretary (Smart Nation and Digital Government Group)</span>
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    <span class="body-text-bold">Ms Stacey N. Lacy</span>
                </div>
                <div class="headshot-title">
                    <span class="body-text-small">Asia Pacific Chief Information Officer And Head Of Operations &amp; Technology</span>
                </div>
                <div class="headshot-department">
                    <span class="body-text-small-bold">Citi</span>
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    <span class="body-text-bold">Mr Dominic Chan</span>
                </div>
                <div class="headshot-title">
                    <span class="body-text-small">Assistant Chief Executive / Senior Director (Ndi)</span>
                </div>
                <div class="headshot-department">
                    <span class="body-text-small-bold">Product Management, National Digital Identity (NDI)</span>
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    <span class="body-text-bold">Name of Person</span>
                </div>
                <div class="headshot-title">
                    <span class="body-text-small">Position </span>
                </div>
                <div class="headshot-department">
                    <span class="body-text-small-bold">Department/Division</span>
                </div>
            </div>
        </div>
    </div>
    <div class="section page-title">
        <h3>Section Title</h3>
    </div>
    <div class="section headshot-items-container">
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    <span class="body-text-bold">Mr Leong Weng Keong Joseph</span>
                </div>
                <div class="headshot-title">
                    <span class="body-text-small">Chairman</span>
                </div>
                <div class="headshot-department">
                    <span class="body-text-small-bold">Permanent Secretary (Smart Nation and Digital Government)</span>
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    <span class="body-text-bold">Ms Vaishali Rastogi</span>
                </div>
                <div class="headshot-title">
                    <span class="body-text-small">Global leader of technology, media and telecommunications business</span>
                </div>
                <div class="headshot-department">
                    <span class="body-text-small-bold">BCG</span>
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    <span class="body-text-bold">Mr Augustin Lee</span>
                </div>
                <div class="headshot-title">
                    <span class="body-text-small">Deputy Chairman</span>
                </div>
                <div class="headshot-department">
                    <span class="body-text-small-bold">Second Permanent Secretary (Smart Nation and Digital Government Group)</span>
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    <span class="body-text-bold">Ms Stacey N. Lacy</span>
                </div>
                <div class="headshot-title">
                    <span class="body-text-small">Asia Pacific Chief Information Officer And Head Of Operations &amp; Technology</span>
                </div>
                <div class="headshot-department">
                    <span class="body-text-small-bold">Citi</span>
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    <span class="body-text-bold">Mr Dominic Chan</span>
                </div>
                <div class="headshot-title">
                    <span class="body-text-small">Assistant Chief Executive / Senior Director (Ndi)</span>
                </div>
                <div class="headshot-department">
                    <span class="body-text-small-bold"></span>Product Management, National Digital Identity (NDI)
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    <span class="body-text-bold">Name of Person</span>
                </div>
                <div class="headshot-title">
                    <span class="body-text-small">Position</span> 
                </div>
                <div class="headshot-department">
                    <span class="body-text-small-bold">Department/Division</span>
                </div>
            </div>
        </div>
    </div>
</div>