---
title: Headshot
permalink: /test-folder/headshot/
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
        margin-bottom: 16px;
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

    .iso-template .text-note {
        color: #4D4D4F;
        font-family: Lato;
        font-size: 12px;
        font-style: normal;
        font-weight: 400;
        line-height: 20px; 
    }

    .iso-template a {
        color: #B41E8E;
        font-family: Lato;
        font-style: normal;
        font-weight: 700;
    }

    .iso-template .button {
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
        line-height: 24px;
        text-transform: uppercase;
        cursor: pointer;
        text-decoration: none;
        display: inline-block;
        margin: 0px;
    }

    .iso-template .button.primary {
        background-color: #B41E8E;
        border-color: #B41E8E;
        color: #fff;
    }

    .iso-template .button.secondary {
        background-color: transparent;
        border-color: #B41E8E;
        color: #B41E8E;
    }

    .iso-template .button.text {
        background-color: transparent;
        border: none;
        padding: 0px;
        color: #B41E8E;
    }

    .iso-template .button > svg {
        display: inline;
        margin-left: 2px;
        position: absolute;
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

        .iso-template .text-label-1 {
            margin-bottom: 8px
        }
    }
</style>
<style>
    .iso-template .anchorlinks-header {
        width: 100%;
        display: flex;
        flex-direction: row;
        text-align: left;
    }

    .iso-template .anchorlinks-header a {
        padding-bottom: 8px;
        border-bottom: none;
        margin-bottom: 0px;
        margin-right: 24px;
        box-sizing: border-box;
        display: inline-block;
        text-decoration: none;
    }

    .iso-template .anchorlinks-header a.active {
        border-bottom: 2px solid #B41E8E;
    }

    @media only screen and (max-width: 768px) {
        .iso-template .anchorlinks-header {
            flex-direction: column;
        }

        .iso-template .anchorlinks-header .anchor-holder {
            margin-bottom: 16px;
        }

        .iso-template .anchorlinks-header .anchor-holder:last-of-type {
            margin-bottom: 0px;
        }

        .iso-template .anchorlinks-header a {
            margin-bottom: 16px;
            margin-right: 0px;
        }
    }
</style>
<style>
    .iso-template .headshot-item {
        width: calc(50% - 12px);
        min-height: 120px;
        float: left;
        margin-bottom: 24px;
    }

    .iso-template .headshot-item:nth-of-type(odd) {
        margin-right: 12px;
    }

    .iso-template .headshot-item:nth-of-type(even) {
        margin-left: 12px;
    }

    .iso-template .headshot-item:nth-last-of-type(-n+2) {
        margin-bottom: 0px;
    }

    .iso-template .headshot-item > img {
        width: 120px;
        height: 120px;
        border-radius: 10px;
        float: left
    }

    .iso-template .headshot-item .headshot-details {
        width: calc(100% - 136px);
        min-height: 120px;
        float: left;
        display: flex;
        flex-direction: column;
        position: relative;
        box-sizing: border-box;
        padding-left: 16px;
    }

    .iso-template .headshot-item .headshot-details > * {
        width: 100%;
        height: auto;
        display: block;
    }

    .iso-template .headshot-item .headshot-details > h6 {
        margin-top: 4px;
        margin-bottom: 12px;
    }

    @media only screen and (max-width: 1279px) {
        .iso-template .headshot-item {
            width: 100%;
        }

        .iso-template .headshot-item:nth-of-type(odd) {
            margin-right: 0px;
        }

        .iso-template .headshot-item:nth-of-type(even) {
            margin-left: 0px;
        }
    }

    @media only screen and (max-width: 1023px) {
        .iso-template .headshot-item {
            width: calc(50% - 12px);
        }

        .iso-template .headshot-item:nth-of-type(odd) {
            margin-right: 12px;
        }

        .iso-template .headshot-item:nth-of-type(even) {
            margin-left: 12px;
        }
    }

    @media only screen and (max-width: 768px) {
        .iso-template .headshot-item {
            width: 100%;
            margin-bottom: 32px;
        }

        .iso-template .headshot-item:nth-of-type(odd),
        .iso-template .headshot-item:nth-of-type(even) {
            margin-right: 0px;
            margin-left: 0px;
        }

        .iso-template .headshot-item:nth-last-of-type(-n+2) {
            margin-bottom: 32px;
        }

        .iso-template .headshot-item:last-of-type {
            margin-bottom: 0px;
        }

        .iso-template .headshot-item .headshot-details {
            padding-left: 0px;
            min-height: 0px;
        }

        .iso-template .headshot-item > img {
            width: 100%;
            height: auto;
            margin-bottom: 24px;
        }

        .iso-template .headshot-item .headshot-details {
            width: 100%;
            height: auto;
        }
    }
</style>
<div class="iso-template">
    <div class="section">
        <div class="anchorlinks-header">
            <div class="anchor-holder text-label-2">
                <a class="active" href="#anchorlink-1">ANCHORLINK</a>
            </div>
            <div class="anchor-holder text-label-2">
                <a href="#anchorlink-2">ANCHORLINK</a>
            </div>
        </div>
    </div>
    <div class="section">
        <div class="text-label-1">[Label 1] Lorem ipsum amet conse</div>
        <h3 id="anchorlink-1">[H3] Lorem ipsum dolor sit amet consectetur nisl id odio</h3>
    </div>
    <div class="section">
        <div class="headshot-item">
            <img alt="" src="https://i.ibb.co/Nt1nxfX/Frame-29.png">
            <div class="headshot-details">
                <div class="text-label-2">
                    [Label 2] (Position) Lorem ipsum 
                </div>
                <h6>
                    [H6] Mr Leong Weng Keong Joseph Lorem Lipsup
                </h6>
                <div class="text-body-2">
                    [Body 2] Department/Division - consectetur. Amet venenatis mattis
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://i.ibb.co/Nt1nxfX/Frame-29.png">
            <div class="headshot-details">
                <div class="text-label-2">
                    [Label 2] (Position) Lorem ipsum 
                </div>
                <h6>
                    [H6] Mr Leong Weng Keong Joseph Lorem Lipsup
                </h6>
                <div class="text-body-2">
                    [Body 2] Department/Division - consectetur. Amet venenatis mattis
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://i.ibb.co/Nt1nxfX/Frame-29.png">
            <div class="headshot-details">
                <div class="text-label-2">
                    [Label 2] (Position) Lorem ipsum 
                </div>
                <h6>
                    [H6] Mr Leong Weng Keong Joseph Lorem Lipsup
                </h6>
                <div class="text-body-2">
                    [Body 2] Department/Division - consectetur. Amet venenatis mattis
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://i.ibb.co/Nt1nxfX/Frame-29.png">
            <div class="headshot-details">
                <div class="text-label-2">
                    [Label 2] (Position) Lorem ipsum 
                </div>
                <h6>
                    [H6] Mr Leong Weng Keong Joseph Lorem Lipsup
                </h6>
                <div class="text-body-2">
                    [Body 2] Department/Division - consectetur. Amet venenatis mattis
                </div>
            </div>
        </div>
    </div>
    <div class="section line-divider"></div>
    <div class="section">
        <div class="text-label-1">[Label 1] Lorem ipsum amet conse</div>
        <h3 id="anchorlink-1">[H3] Lorem ipsum dolor sit amet consectetur nisl id odio</h3>
    </div>
    <div class="section headshot-items-container">
        <div class="headshot-item">
            <img alt="" src="https://i.ibb.co/Nt1nxfX/Frame-29.png">
            <div class="headshot-details">
                <div class="text-label-2">
                    [Label 2] (Position) Lorem ipsum 
                </div>
                <h6>
                    [H6] Mr Leong Weng Keong Joseph Lorem Lipsup
                </h6>
                <div class="text-body-2">
                    [Body 2] Department/Division - consectetur. Amet venenatis mattis
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://i.ibb.co/Nt1nxfX/Frame-29.png">
            <div class="headshot-details">
                <div class="text-label-2">
                    [Label 2] (Position) Lorem ipsum 
                </div>
                <h6>
                    [H6] Mr Leong Weng Keong Joseph Lorem Lipsup
                </h6>
                <div class="text-body-2">
                    [Body 2] Department/Division - consectetur. Amet venenatis mattis
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://i.ibb.co/Nt1nxfX/Frame-29.png">
            <div class="headshot-details">
                <div class="text-label-2">
                    [Label 2] (Position) Lorem ipsum 
                </div>
                <h6>
                    [H6] Mr Leong Weng Keong Joseph Lorem Lipsup
                </h6>
                <div class="text-body-2">
                    [Body 2] Department/Division - consectetur. Amet venenatis mattis
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://i.ibb.co/Nt1nxfX/Frame-29.png">
            <div class="headshot-details">
                <div class="text-label-2">
                    [Label 2] (Position) Lorem ipsum 
                </div>
                <h6>
                    [H6] Mr Leong Weng Keong Joseph Lorem Lipsup
                </h6>
                <div class="text-body-2">
                    [Body 2] Department/Division - consectetur. Amet venenatis mattis
                </div>
            </div>
        </div>
    </div>
</div>