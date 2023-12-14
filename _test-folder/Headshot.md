---
title: Headshot
permalink: /test-folder/headshot/
variant: markdown
description: ""
---
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
        font-family: Lato;
        font-size: 20px;
        font-style: normal;
        font-weight: 700;
        line-height: normal;
        text-decoration-line: underline;
        color: #4372D6;
    }

    .headshot-template .section.page-title {
        text-align: left;
        font-family: Lato;
        font-size: 32px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        color: #4372D6;
        margin: 44px 0px;
    }

    .headshot-template .section.headshot-items-container {
        margin-bottom: 44px
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
        font-family: Lato;
        font-size: 20px;
        font-style: normal;
        font-weight: 700;
        line-height: normal;
        color: #000;
    }

    .headshot-template .headshot-item .headshot-details .headshot-title {
        width: 100%;
        height: auto;
        font-family: Lato;
        font-size: 16px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
    }

    .headshot-template .headshot-item .headshot-details .headshot-department {
        width: 100%;
        height: auto;
        color: #4372D6;
        font-family: Lato;
        font-size: 16px;
        font-style: normal;
        font-weight: 700;
        line-height: normal;
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

<div class="headshot-template">
    <div class="section anchor-links">
        <a href="#anchorlink-1">ANCHORLINK #1</a>
        <a href="#anchorlink-2">ANCHORLINK #2</a>
    </div>
    <div class="section page-title">
        Section Title
    </div>
    <div class="section headshot-items-container">
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    Mr Leong Weng Keong Joseph
                </div>
                <div class="headshot-title">
                    Chairman
                </div>
                <div class="headshot-department">
                    Permanent Secretary (Smart Nation and Digital Government)
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    Ms Vaishali Rastogi
                </div>
                <div class="headshot-title">
                    Global leader of technology, media and telecommunications business
                </div>
                <div class="headshot-department">
                    BCG
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    Mr Augustin Lee
                </div>
                <div class="headshot-title">
                    Deputy Chairman
                </div>
                <div class="headshot-department">
                    Second Permanent Secretary (Smart Nation and Digital Government Group)
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    Ms Stacey N. Lacy
                </div>
                <div class="headshot-title">
                    Asia Pacific Chief Information Officer And Head Of Operations &amp; Technology
                </div>
                <div class="headshot-department">
                    Citi
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    Mr Dominic Chan
                </div>
                <div class="headshot-title">
                    Assistant Chief Executive / Senior Director (Ndi)
                </div>
                <div class="headshot-department">
                    Product Management, National Digital Identity (NDI)
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    Name of Person
                </div>
                <div class="headshot-title">
                    Position 
                </div>
                <div class="headshot-department">
                    Department/Division
                </div>
            </div>
        </div>
    </div>
    <div class="section page-title">
        Section Title
    </div>
    <div class="section headshot-items-container">
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    Mr Leong Weng Keong Joseph
                </div>
                <div class="headshot-title">
                    Chairman
                </div>
                <div class="headshot-department">
                    Permanent Secretary (Smart Nation and Digital Government)
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    Ms Vaishali Rastogi
                </div>
                <div class="headshot-title">
                    Global leader of technology, media and telecommunications business
                </div>
                <div class="headshot-department">
                    BCG
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    Mr Augustin Lee
                </div>
                <div class="headshot-title">
                    Deputy Chairman
                </div>
                <div class="headshot-department">
                    Second Permanent Secretary (Smart Nation and Digital Government Group)
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    Ms Stacey N. Lacy
                </div>
                <div class="headshot-title">
                    Asia Pacific Chief Information Officer And Head Of Operations &amp; Technology
                </div>
                <div class="headshot-department">
                    Citi
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    Mr Dominic Chan
                </div>
                <div class="headshot-title">
                    Assistant Chief Executive / Senior Director (Ndi)
                </div>
                <div class="headshot-department">
                    Product Management, National Digital Identity (NDI)
                </div>
            </div>
        </div>
        <div class="headshot-item">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="headshot-details">
                <div class="headshot-name">
                    Name of Person
                </div>
                <div class="headshot-title">
                    Position 
                </div>
                <div class="headshot-department">
                    Department/Division
                </div>
            </div>
        </div>
    </div>
</div>