---
title: Lightbox
permalink: /test-folder/lightbox/
variant: markdown
description: ""
third_nav_title: Experiments
---
<style>
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

<div>
        <input type="checkbox" id="title1">
				<label for="title1"><span>Sustainable Organisation</span></label>
        <div class="accordion-content">
            <img alt="" src="https://developers.elementor.com/docs/assets/img/elementor-placeholder-image.png">
        </div>
</div>
<iframe allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" frameborder="0" title="YouTube video player" src="https://www.youtube.com/embed/u1pRapBEHlU?si=PhHY-KOtWQgXRw8W" height="315" width="560"></iframe>