---
title: Listing
permalink: /test-folder/listing/
variant: markdown
description: ""
---
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
        color: #4372D6;
        font-family: Lato;
        font-size: 32px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        padding-bottom: 44px;
        border-bottom: 1px solid #d6d6d6;
        margin-bottom: 22px;
    }

    .listing-template .section.article-title {
        color: #4372D6;
        font-family: Lato;
        font-size: 32px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        padding-top: 22px;
        padding-bottom: 22px;
    }

    .listing-template .section.article-subtitle {
        color: #4372D6;
        font-family: Lato;
        font-size: 24px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        padding-top: 22px;
        padding-bottom: 22px;
    }

    .listing-template .section.article-text {
        color: #484848;
        font-family: Lato;
        font-size: 20px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        padding-top: 22px;
        padding-bottom: 22px;
    }

    .listing-template .section.card-one-container {
        width: 100%;
        margin-top: 22px;
    }

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
        color: #4372D6;
        font-family: Lato;
        font-size: 26px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        float: left;
    }

    .listing-template .card-one-text {
        width: 100%;
        height: auto;
        color: #484848;
        font-family: Lato;
        font-size: 16px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        padding: 12px 0px;
        float: left;
    }

    .listing-template .card-one-button {
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
        cursor: pointer;
        float: left;
    }

    @media only screen and (max-width: 1279px) {
        
    }

    @media only screen and (max-width: 1023px) {
        
    }

    @media only screen and (max-width: 768px) {
        
    }

    input {
        display: none;
    }

    label {
        display: block;
        padding: 8px 22px;
        margin: 0 0 5px 0;
        cursor: pointor;
        background: #a7a9ac;
        border-radius: 3px;
        color: #484848;
        transition: ease .5s;
        font-size: 1.5em;
    }

    label:hover {
        background: #B41E8E;
        color: #FFF;
    }

    .accordion-content {
        padding: 10px 0px 30px 30px;
        margin: 0 0 1px 0;
        border-radius: 3px;
    }

    input:checked + label {
        position: fixed;
        width: 100%;
        height: 100%;
        top: 0px;
        left: 0px;
        background-color: rgba(0,0,0,0.5);
    }

    input:checked + label > span{
        display: none
    }

    input + label + .accordion-content {
        display: none;
    }

    input:checked + label + .accordion-content {
        display: flex;
        position: fixed;
        width: 100%;
        height: 100%;
        top: 0px;
        left: 0px;
        pointer-events: none;
        align-items: center;
        justify-content: center;
    }

    input:checked + label + .accordion-content > img{
        width: 600px
    }
</style>

<div class="listing-template">
    <div class="section heading-text">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna fermentum nisi, ac mattis nulla velit eu quam.
    </div>
    <div class="section article-title">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit
    </div>
    <div class="section article-text">
        Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
    </div>
    <div class="section article-subtitle">
        Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
    </div>
    <div class="section article-text">
        Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.
    </div>
    <div class="section card-one-container">
        <div class="card-one-box">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="card-one-details">
                <div class="card-one-title">
                    Card title 
                </div>
                <div class="card-one-text">
                    Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna velit eu.
                </div>
                <div class="card-one-button">
                    BUTTON
                </div>
            </div>
        </div>
        <div class="card-one-box">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="card-one-details">
                <div class="card-one-title">
                    Card title 
                </div>
                <div class="card-one-text">
                    Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna velit eu.
                </div>
                <div class="card-one-button">
                    BUTTON
                </div>
            </div>
        </div>
        <div class="card-one-box">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
            <div class="card-one-details">
                <div class="card-one-title">
                    Card title 
                </div>
                <div class="card-one-text">
                    Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna velit eu.
                </div>
                <div class="card-one-button">
                    BUTTON
                </div>
            </div>
        </div>
    </div>
    <div>
        <input type="checkbox" id="title1"><label for="title1"><span>Sustainable Organisation</span></label>
        <div class="accordion-content">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
        </div>
    </div>
</div>