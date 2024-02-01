---
title: Persona
permalink: /test-folder/persona/
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
    .content .iso-template .banner-image {
        width: 100%;
        height: auto;
    }

    .content .iso-template .section.card-banner-container,
    .content .iso-template .section.card-banner-container-three  {
        display: flex;
        flex-wrap: wrap;
    }

    .content .iso-template .card-banner-box {
        flex: 0 0 50%;
        position: relative;
    }

    .content .iso-template .section.card-banner-container-three .card-banner-box {
        flex: 0 0 33%;
    }

    .content .iso-template .card-banner-image {
        width: calc(100% - 12px);
        box-sizing: border-box;
        padding: 30px;
        background-position: center;
        background-size: cover;
        border-radius: 10px;
        height: 300px
    }

    .content .iso-template .card-banner-box:nth-of-type(odd) .card-banner-image {
        margin-right: 12px;
    }

    .content .iso-template .card-banner-box:nth-of-type(even) .card-banner-image {
        margin-left: 12px;
    }

    .content .iso-template .section.card-banner-container-three .card-banner-image {
        width: calc(100% - 16px);
    }

    .content .iso-template .section.card-banner-container-three .card-banner-box:nth-of-type(3n-2) .card-banner-image {
        margin-right: 16px;
    }

    .content .iso-template .section.card-banner-container-three .card-banner-box:nth-of-type(3n-1) .card-banner-image {
        margin-right: 8px;
        margin-left: 8px;
    }

    .content .iso-template .section.card-banner-container-three .card-banner-box:nth-of-type(3n-0) .card-banner-image {
        margin-left: 16px;
    }

    .content .iso-template .card-banner-image h3,
    .content .iso-template .card-banner-image h5 {
        margin-bottom: 15px
    }

    .content .iso-template .section.swap-image-container {
        display: flex;
        flex-direction: column;
    }

    .content .iso-template .swap-image-box {
        display: flex;
        flex-direction: row;
        margin-bottom: 44px;
    }

    .content .iso-template .swap-image-box:last-of-type {
        margin-bottom: 0px;
    }

    .content .iso-template .swap-image-box:nth-of-type(even) {
        flex-direction: row-reverse;
    }

    .content .iso-template .swap-image-box > img {
        width: 294px;
        height: 221px;
        border-radius: 10px
    }

    .content .iso-template .swap-image-box > .swap-image-details {
        width: calc(100% - 294px);
        height: 221px;
        box-sizing: border-box;
        padding-left: 26px;
        display: flex;
        justify-content: center;
        flex-direction: column;
    }

    .content .iso-template .swap-image-box:nth-of-type(even) > .swap-image-details {
        padding-left: 0px;
        padding-right: 26px;
    }

    .content .iso-template .swap-image-details > h4 {
        margin-bottom: 30px
    }

    .content .iso-template .section.swap-banner-container {
        display: flex;
        flex-direction: column;
    }

    .content .iso-template .swap-banner-box {
        display: flex;
        flex-direction: row;
        margin-bottom: 44px;
        background-position: center;
        background-size: cover;
        border-radius: 10px;
    }

    .content .iso-template .swap-banner-box:last-of-type {
        margin-bottom: 0px;
    }

    .content .iso-template .swap-banner-box:nth-of-type(even) {
        flex-direction: row-reverse;
    }

    .content .iso-template .swap-banner-box > .swap-banner-details {
        width: 55%;
        height: 300px;
        box-sizing: border-box;
        padding-left: 26px;
        display: flex;
        justify-content: center;
        flex-direction: column;
    }

    .content .iso-template .swap-banner-box:nth-of-type(even) > .swap-banner-details {
        padding-left: 0px;
        padding-right: 26px;
    }

    .content .iso-template .swap-banner-details > h3 {
        margin-bottom: 30px
    }

    .content .iso-template .swap-banner-details > .body-text-small {
        margin-bottom: 30px
    }

    .content .iso-template .section.info-cards-container {
        display: flex;
        flex-wrap: wrap;
    }

    .content .iso-template .info-cards {
        flex: 0 0 33.33333%;
        box-sizing: border-box;
    }

    .content .iso-template .info-cards:nth-of-type(3n+1) {
        padding-right: 16px;
    }

    .content .iso-template .info-cards:nth-of-type(3n+2) {
        padding-right: 8px;
        padding-left: 8px;
    }

    .content .iso-template .info-cards:nth-of-type(3n+3) {
        padding-left: 16px;
    }

    .content .iso-template .info-cards > img {
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

    .content .iso-template .info-cards-details {
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

    .content .iso-template .info-cards-details.no-image {
        border-top: 2px solid #D9D9D9;
        border-top-right-radius: 10px;
        border-top-left-radius: 10px;
    }

    .content .iso-template .portrait-box > img {
        width: 246px;
        height: 246px;
        border-radius: 10px;
        float: left;
    }

    .content .iso-template .portrait-box-details {
        width: calc(100% - 246px);
        height: 246px;
        float: left;
        display: flex;
        justify-content: center;
        box-sizing: border-box;
        padding-left: 35px;
        flex-direction: column;
    }

    .content .iso-template .portrait-box-details > h4 {
        margin-bottom: 11px
    }

    .content .iso-template .quote-box > .body-text-small {
        margin-top: 11px;
        text-align: right;
    }

    .content .iso-template .accordion-container {
        border-bottom: 1px solid #8A8A8A;
    }

    .content .iso-template .accordion-container input {
        display: none;
    }

    .content .iso-template .accordion-container label {
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

    .content .iso-template .accordion-container label h5 {
        color: #484848 !important; 
    }

    .content .iso-template .accordion-container label .open-accordion-icon {
        display: block;
    }

    .content .iso-template .accordion-container label .close-accordion-icon {
        display: none;
    }

    .content .iso-template .accordion-container .accordion-content {
        padding: 10px 0px 30px 30px;
        margin: 0 0 1px 0;
        border-radius: 3px;
    }

    .content .iso-template .accordion-container input:checked + label h5 {
        color: #4372D6 !important;
    }

    .content .iso-template .accordion-container input:checked + label .open-accordion-icon {
        display: none;
    }

    .content .iso-template .accordion-container input:checked + label .close-accordion-icon {
        display: block;
    }

    .content .iso-template .accordion-container input + label + .accordion-content {
        display: none;
    }

    .content .iso-template .accordion-container input:checked + label + .accordion-content {
        display: flex;
    }

    .content .iso-template .feature-image {
        width: 100%;
        height: auto;
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .content .iso-template .feature-image > img {
        width: 500px;
        height: 375px;
        margin-bottom: 20px;
        border-radius: 10px
    }

    .content .iso-template .feature-image-button-holder {
        width: 100%;
        display: flex;
        justify-content: center;
    }

    .content .iso-template .feature-image-button-holder > .button-blue,
    .content .iso-template .feature-image-button-holder > .button-default {
        margin: 0px 10px
    }

    .content .iso-template .feature-image-text {
        margin-top: 20px
    }

    .content .iso-template .feature-center {
        text-align: center;
    }

    .content .iso-template .feature-center > h3 {
        margin-bottom: 30px
    }

    .content .iso-template .feature-center > .body-text-regular {
        margin-bottom: 30px
    }

    .content .iso-template .feature-center > img {
        margin-bottom: 30px;
        width: 412px;
        height: 232px;
        border-radius: 10px
    }

    @media only screen and (max-width: 768px) {
        .content .iso-template .card-banner-box {
            flex: 0 0 100%;
        }

        .content .iso-template .section.card-banner-container-three .card-banner-box {
            flex: 0 0 100%;
        }

        .content .iso-template .card-banner-image {
            width: 100%;
            height: auto;
            min-height: 90vw;
            margin-bottom: 44px;
        }

        .content .iso-template .card-banner-box:nth-of-type(odd) .card-banner-image {
            margin-right: 0px;
        }

        .content .iso-template .card-banner-box:nth-of-type(even) .card-banner-image {
            margin-left: 0px;
        }

        .content .iso-template .section.card-banner-container-three .card-banner-image {
            width: 100%;
            height: auto;
            min-height: 90vw;
            margin-bottom: 44px;
        }

        .content .iso-template .section.card-banner-container-three .card-banner-box:nth-of-type(3n-2) .card-banner-image {
            margin-right: 0px;
        }

        .content .iso-template .section.card-banner-container-three .card-banner-box:nth-of-type(3n-1) .card-banner-image {
            margin-right: 0px;
            margin-left: 0px;
        }

        .content .iso-template .section.card-banner-container-three .card-banner-box:nth-of-type(3n-0) .card-banner-image {
            margin-left: 0px;
        }

        .content .iso-template .swap-image-box,
        .content .iso-template .swap-image-box:nth-of-type(even) {
            flex-direction: column;
        }

        .content .iso-template .swap-image-box > img {
            width: 100%;
            height: auto
        }

        .content .iso-template .swap-image-box > .swap-image-details {
            width: 100%;
            height: auto;
            padding-left: 0px;
            padding-top: 20px;
        }

        .content .iso-template .swap-banner-box {
            min-height: 100vw;
        }

        .content .iso-template .swap-banner-box > .swap-banner-details,
        .content .iso-template .swap-banner-box:nth-of-type(even) > .swap-banner-details {
            width: 100%;
            height: auto;
            justify-content: flex-start;
            padding-left: 30px;
            padding-right: 30px;
            padding-top: 30px;
            padding-bottom: 30px;
        }

        .content .iso-template .info-cards {
            flex: 0 0 100%;
            padding-bottom: 32px;
        }

        .content .iso-template .info-cards:last-of-type {
            padding-bottom: 0px;
        }

        .content .iso-template .info-cards-details {
            padding: 15px
        }

        .content .iso-template .info-cards:nth-of-type(3n+1) {
            padding-right: 0px;
        }

        .content .iso-template .info-cards:nth-of-type(3n+2) {
            padding-right: 0px;
            padding-left: 0px;
        }

        .content .iso-template .info-cards:nth-of-type(3n+3) {
            padding-left: 0px;
        }

        .content .iso-template .info-cards-details .body-text-small {
            display: block;
            margin-top: 11px
        }

        .content .iso-template .portrait-box > img {
            width: 100%;
            height: auto;
        }

        .content .iso-template .portrait-box-details {
            width: 100%;
            height: auto;
            padding-left: 0px;
            padding-top: 20px;
        }

        .content .iso-template .portrait-box-details > h4 {
            font-size: 28px;
        }

        .content .iso-template .accordion-container .accordion-content {
            padding: 10px 12px 30px 12px;
        }

        .content .iso-template .feature-image > img {
            width: 100%;
            height: auto;
            max-width: 320px;
        }

        .content .iso-template .feature-center > img {
            width: 100%;
            height: auto;
        }
    }
</style>
<style>
    .content .iso-template .gradient-box-container {
        width: 100%;
        display: flex;
        flex-direction: row;
    }

    .content .iso-template .gradient-box {
        height: auto;
        border-radius: 10px;
        background: rgb(148,42,148);
        background: -moz-linear-gradient(90deg, rgba(148,42,148,1) 0%, rgba(1,97,175,1) 100%);
        background: -webkit-linear-gradient(90deg, rgba(148,42,148,1) 0%, rgba(1,97,175,1) 100%);
        background: linear-gradient(90deg, rgba(148,42,148,1) 0%, rgba(1,97,175,1) 100%);
        filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#942a94",endColorstr="#0161af",GradientType=1);
        padding: 24px;
        box-sizing: border-box;
    }

    .content .iso-template .gradient-box-container.two-column .gradient-box {
        width: calc(50% - 12px);
    }

    .content .iso-template .gradient-box-container.two-column .gradient-box:nth-of-type(odd) {
        margin-right: 12px;
    }

    .content .iso-template .gradient-box-container.two-column .gradient-box:nth-of-type(even) {
        margin-left: 12px;
    }

    .content .iso-template .gradient-box-container.three-column .gradient-box {
        width: calc(100%/3 - 16px);
    }

    .content .iso-template .gradient-box-container.three-column .gradient-box:nth-of-type(3n+1) {
        margin-right: 16px;
    }

    .content .iso-template .gradient-box-container.three-column .gradient-box:nth-of-type(3n+2) {
        margin-right: 8px;
        margin-left: 8px;
    }

    .content .iso-template .gradient-box-container.three-column .gradient-box:nth-of-type(3n+3) {
        margin-left: 16px;
    }

    @media only screen and (max-width: 768px) {
        .content .iso-template .gradient-box-container {
            flex-direction: column;
        }

        .content .iso-template .gradient-box {
            margin-bottom: 24px;
        }

        .content .iso-template .gradient-box-container.two-column .gradient-box,
        .content .iso-template .gradient-box-container.three-column .gradient-box {
            width: 100%;
        }

        .content .iso-template .gradient-box-container.two-column .gradient-box:nth-of-type(odd),
        .content .iso-template .gradient-box-container.two-column .gradient-box:nth-of-type(even),
        .content .iso-template .gradient-box-container.three-column .gradient-box:nth-of-type(3n+1),
        .content .iso-template .gradient-box-container.three-column .gradient-box:nth-of-type(3n+2),
        .content .iso-template .gradient-box-container.three-column .gradient-box:nth-of-type(3n+3) {
            margin-right: 0px;
            margin-left: 0px;
        }
    }
</style>
<style>
    .content .iso-template .info-cards-container {
        display: flex;
        flex-wrap: wrap;
    }

    .content .iso-template .info-cards-container.padding-top {
        padding-top: 24px;
    }

    .content .iso-template .info-cards {
        flex: 0 0 33.33333%;
        box-sizing: border-box;
    }

    .content .iso-template .info-cards:nth-of-type(3n+1) {
        padding-right: 16px;
    }

    .content .iso-template .info-cards:nth-of-type(3n+2) {
        padding-right: 8px;
        padding-left: 8px;
    }

    .content .iso-template .info-cards:nth-of-type(3n+3) {
        padding-left: 16px;
    }

    .content .iso-template .info-cards > img {
        width: 100%;
        height: auto;
        float: left;
        display: block;
        border-radius: 10px;
        border: none;
        box-sizing: border-box;
        margin-bottom: -10px;
    }

    .content .iso-template .info-cards-details {
        width: 100%;
        height: auto;
        float: left;
        display: block;
        border: 1px solid #D8D9DA;
        border-bottom-right-radius: 10px;
        border-bottom-left-radius: 10px;
        box-sizing: border-box;
        padding: 24px 16px;
        padding-top: 34px;
        border-top: none;
    }

    .content .iso-template .info-cards-details.no-image {
        border-top: 1px solid #D9D9D9;
        padding: 24px 16px;
        border-top-right-radius: 10px;
        border-top-left-radius: 10px;
    }

    @media only screen and (max-width: 768px) {
        .content .iso-template .info-cards {
            flex: 0 0 100%;
            padding-bottom: 24px;
        }

        .content .iso-template .info-cards:last-of-type {
            padding-bottom: 0px;
        }

        .content .iso-template .info-cards-details {
            padding: 16px;
            padding-top: 26px;
        }

        .content .iso-template .info-cards-details.no-image {
            padding: 16px;
        }

        .content .iso-template .info-cards:nth-of-type(3n+1) {
            padding-right: 0px;
        }

        .content .iso-template .info-cards:nth-of-type(3n+2) {
            padding-right: 0px;
            padding-left: 0px;
        }

        .content .iso-template .info-cards:nth-of-type(3n+3) {
            padding-left: 0px;
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
    <div class="section">
        <div class="text-label-1">[Label 1] Lorem ipsum amet conse </div>
        <h3>[H3] 2 Col - Lorem ipsum ametconse massa sit eleifend</h3>
        <div class="spacer-24"></div>
        <div class="gradient-box-container three-column">
            <div class="gradient-box">
                <h4 class="text-color-white">[H4] Nam tempor in iorem nec ornare in turpis dolor eueuismod gravida iectus</h4><br>
                <a target="_blank" href="https://www.google.com.sg/" class="button text text-color-white">
                    TEXT CTA 
                    <svg fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path stroke-linejoin="round" stroke-linecap="round" stroke-width="1.5" stroke="#B41E8E" d="M10 7L15 12L10 17"></path></svg>
                </a>
            </div>
            <div class="gradient-box">
                <h4 class="text-color-white">[H4] Nam tempor in iorem nec ornare in turpis dolor eueuismod gravida iectus</h4><br>
                <a target="_blank" href="https://www.google.com.sg/" class="button text text-color-white">
                    TEXT CTA 
                    <svg fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path stroke-linejoin="round" stroke-linecap="round" stroke-width="1.5" stroke="#B41E8E" d="M10 7L15 12L10 17"></path></svg>
                </a>
            </div>
            <div class="gradient-box">
                <h4 class="text-color-white">[H4] Nam tempor in iorem nec ornare in turpis dolor eueuismod gravida iectus</h4><br>
                <a target="_blank" href="https://www.google.com.sg/" class="button text text-color-white">
                    TEXT CTA 
                    <svg fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path stroke-linejoin="round" stroke-linecap="round" stroke-width="1.5" stroke="#B41E8E" d="M10 7L15 12L10 17"></path></svg>
                </a>
            </div>
        </div>
    </div>
    <div class="section">
        <div class="text-label-1">[Label 1] Lorem ipsum amet conse </div>
        <h3>[H3] 2 Col - Lorem ipsum ametconse massa sit eleifend</h3>
        <div class="spacer-24"></div>
        <div class="info-cards-container">
            <div class="info-cards">
                <img alt="" src="https://i.ibb.co/hR7bRYp/Frame-167.png">
                <div class="info-cards-details">
                    <h5>[H5] Lorem ipsum dolor sit amet conse </h5>
                    <div class="text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl.
                    </div>
                </div>
            </div>
            <div class="info-cards">
                <img alt="" src="https://i.ibb.co/hR7bRYp/Frame-167.png">
                <div class="info-cards-details">
                    <h5>[H5] Lorem ipsum dolor sit amet conse </h5>
                    <div class="text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl.
                    </div>
                </div>
            </div>
            <div class="info-cards">
                <img alt="" src="https://i.ibb.co/hR7bRYp/Frame-167.png">
                <div class="info-cards-details">
                    <h5>[H5] Lorem ipsum dolor sit amet conse </h5>
                    <div class="text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl.
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="section">
        <div class="info-cards-container">
            <div class="info-cards">
                <div class="info-cards-details no-image">
                    <h5>[H5] Lorem ipsum dolor sit amet conse </h5>
                    <div class="text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl.
                    </div>
                </div>
            </div>
            <div class="info-cards">
                <div class="info-cards-details no-image">
                    <h5>[H5] Lorem ipsum dolor sit amet conse </h5>
                    <div class="text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl.
                    </div>
                </div>
            </div>
            <div class="info-cards">
                <div class="info-cards-details no-image">
                    <h5>[H5] Lorem ipsum dolor sit amet conse </h5>
                    <div class="text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl.
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="section">
        <img class="banner-image" alt="" src="https://i.ibb.co/9gLh4zh/image-63-4.jpg">
    </div>
    <div class="section">
        <h3>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam tempor in lorem nec ornare. In in turpis dolor. Fusce feugiat, risus id euismod gravida, lectus urna fermentum nisi, ac mattis nulla velit eu quam.</h3>
    </div>
    <div class="section">
        <h3>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</h3>
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
    <div class="section">
        <h3>Lorem ipsum dolor sit amet, consectetur adipiscing elit</h3>
    </div>
    <div class="section">
        <span class="body-text-regular">Vestibulum tincidunt neque at elit dictum cursus. Praesent eu libero at velit vestibulum sollicitudin vel non lorem. Pellentesque vitae lorem scelerisque, vehicula tellus ut, vestibulum erat.</span>
    </div>
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
    <div class="section">
        <h5>Lorem ipsum dolor sit amet, consectetur adipiscing elit</h5>
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
            <img class="button-image" alt="" src="https://i.ibb.co/dmVMjxp/download.png">
            <img class="button-image" alt="" src="https://i.ibb.co/JQxHsnk/download-1.png">
        </div>
    </div>
</div>