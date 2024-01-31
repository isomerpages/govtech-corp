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

    .iso-template .content-text {
        width: 100%;
        height: auto;
        float: left;
        margin-bottom: 24px
    }

    .iso-template .content-title {
        width: 100%;
        height: auto;
        float: left;
        margin-bottom: 8px
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

        .iso-template .content-text {
            margin-bottom: 16px
        }

        .iso-template .content-title {
            margin-bottom: 4px
        }
    }
</style>
<style>
    .iso-template .card-container {
        width: 100%;
        margin-top: 24px;
    }

    .iso-template .card-box {
        border-top: 1px solid #D8D9DA;
        width: 100%;
        height: auto;
        min-height: 205px;
        padding: 24px 0px;
        display: flex;
        flex-direction: row;
    }

    .iso-template .card-box > img {
        width: 273px;
        height: 205px;
        border-radius: 10px;
        margin: 0px
    }

    .iso-template .card-one-details {
        width: calc(100% - 273px);
        height: auto;
        box-sizing: border-box;
        padding: 0px 20px;
    }

    .iso-template .card-container.two-column .card-box,
    .iso-template .card-container.three-column .card-box {
        flex-direction: column;
    }

    .iso-template .card-container.two-column,
    .iso-template .card-container.three-column {
        display: flex;
        flex-wrap: wrap;
    }

    .iso-template .card-container.two-column .card-box,
    .iso-template .card-container.three-column .card-box {
        border-top: none;
        width: 100%;
        min-height: 0px;
    }

    .iso-template .card-container.two-column .card-box:last-of-type,
    .iso-template .card-container.three-column .card-box:last-of-type {
        border-bottom: none
    }

    .iso-template .card-container.two-column .card-box > img,
    .iso-template .card-container.three-column .card-box > img {
        width: 100%;
        height: auto;
        border-radius: 10px;
        margin-bottom: 24px
    }

    .iso-template .card-container.two-column .card-one-details,
    .iso-template .card-container.three-column .card-one-details {
        width: 100%;
        height: auto;
        padding: 0px;
    }

    .iso-template .card-container.two-column .card-box {
        flex: 0 0 50%;
    }

    .iso-template .card-container.three-column .card-box {
        flex: 0 0 33.3333%;
    }

    .iso-template .card-container.two-column .card-box:nth-of-type(odd) {
        padding-right: 12px;
    }

    .iso-template .card-container.two-column .card-box:nth-of-type(even) {
        padding-left: 12px;
    }

    .iso-template .card-container.three-column .card-box:nth-of-type(3n+1) {
        padding-right: 16px;
    }

    .iso-template .card-container.three-column .card-box:nth-of-type(3n+2) {
        padding-right: 8px;
        padding-left: 8px;
    }

    .iso-template .card-container.three-column .card-box:nth-of-type(3n+3) {
        padding-left: 16px;
    }

    @media only screen and (max-width: 768px) {
        .iso-template .card-container {
            margin-top: 0px;
        }

        .iso-template .card-box {
            flex-direction: column;
            padding-bottom: 0px;
        }

        .iso-template .card-box {
            border-top: none;
        }

        .iso-template .card-box:last-of-type {
            border-bottom: none;
        }

        .iso-template .card-box > img {
            width: 100%;
            height: auto;
            margin-bottom: 16px;
        }

        .iso-template .card-one-details {
            width: 100%;
            padding: 0px;
        }

        .iso-template .card-container.two-column .card-box,
        .iso-template .card-container.three-column .card-box {
            flex: 0 0 100%
        }

        .iso-template .card-container.two-column .card-box > img,
        .iso-template .card-container.three-column .card-box > img {
            margin-bottom: 16px
        }

        .iso-template .card-container.two-column .card-box:nth-of-type(odd),
        .iso-template .card-container.two-column .card-box:nth-of-type(even),
        .iso-template .card-container.three-column .card-box:nth-of-type(3n+1),
        .iso-template .card-container.three-column .card-box:nth-of-type(3n+2),
        .iso-template .card-container.three-column .card-box:nth-of-type(3n+3) {
            padding-right: 0px;
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
        <a href="https://www.google.com.sg/" class="button secondary">
            BUTTON
        </a>
        <a href="https://www.google.com.sg/" class="button primary">
            BUTTON
        </a>
    </div>
    <div class="section">
        <a href="https://www.google.com.sg/" class="button text">
            TEXT CTA 
            <svg fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path stroke-linejoin="round" stroke-linecap="round" stroke-width="1.5" stroke="#B41E8E" d="M10 7L15 12L10 17"></path></svg>
        </a>
    </div>
    <div class="section line-divider"></div>
    <div class="section">
        <div class="text-label-1">[Label 1] One Column - Lorem ipsum amet conse</div>
        <h3 id="anchorlink-1">[H3] One Column - Lorem ipsum dolor sit amet consectetur nisl id odio</h3>
        <div class="card-container">
            <div class="card-box">
                <img alt="" src="https://i.ibb.co/rGPw8T6/Frame-162.png">
                <div class="card-one-details">
                    <h4 class="content-title">[H4] Lorem ipsum dolor sit amet consectetur</h4>
                    <div class="content-text text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl aliquam nisl. Eget maecenas pulvinar venenatis viverra sociis ut bibendum nulla. Orci aliquet in consequat lobortis mauris. Augue facilisis arcu egestas lectus convallis adipiscing. Sed nam felis id.
                    </div>
                    <a class="button secondary" href="https://www.google.com.sg/">
                        BUTTON
                    </a>
                </div>
            </div>
            <div class="card-box">
                <img alt="" src="https://i.ibb.co/rGPw8T6/Frame-162.png">
                <div class="card-one-details">
                    <h4 class="content-title">[H4] Lorem ipsum dolor sit amet consectetur</h4>
                    <div class="content-text text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl aliquam nisl. Eget maecenas pulvinar venenatis viverra sociis ut bibendum nulla. Orci aliquet in consequat lobortis mauris. Augue facilisis arcu egestas lectus convallis adipiscing. Sed nam felis id.
                    </div>
                    <a class="button secondary" href="https://www.google.com.sg/">
                        BUTTON
                    </a>
                </div>
            </div>
            <div class="card-box">
                <img alt="" src="https://i.ibb.co/rGPw8T6/Frame-162.png">
                <div class="card-one-details">
                    <h4 class="content-title">[H4] Lorem ipsum dolor sit amet consectetur</h4>
                    <div class="content-text text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl aliquam nisl. Eget maecenas pulvinar venenatis viverra sociis ut bibendum nulla. Orci aliquet in consequat lobortis mauris. Augue facilisis arcu egestas lectus convallis adipiscing. Sed nam felis id.
                    </div>
                    <a class="button secondary" href="https://www.google.com.sg/">
                        BUTTON
                    </a>
                </div>
            </div>
            <div class="card-box">
                <img alt="" src="https://i.ibb.co/rGPw8T6/Frame-162.png">
                <div class="card-one-details">
                    <h4 class="content-title">[H4] Lorem ipsum dolor sit amet consectetur</h4>
                    <div class="content-text text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl aliquam nisl. Eget maecenas pulvinar venenatis viverra sociis ut bibendum nulla. Orci aliquet in consequat lobortis mauris. Augue facilisis arcu egestas lectus convallis adipiscing. Sed nam felis id.
                    </div>
                    <a class="button secondary" href="https://www.google.com.sg/">
                        BUTTON
                    </a>
                </div>
            </div>
        </div>
    </div>
    <div class="section line-divider"></div>
    <div class="section">
        <div class="text-label-1">[Label 1] Two Columns - Lorem ipsum amet conse</div>
        <h3 id="anchorlink-1">[H3] Two Columns - Lorem ipsum dolor sit amet consectetur nisl id odio</h3>
        <div class="card-container two-column">
            <div class="card-box">
                <img alt="" src="https://i.ibb.co/rGPw8T6/Frame-162.png">
                <div class="card-one-details">
                    <h4 class="content-title">[H4] Lorem ipsum dolor sit amet conse ctetur mattis iaculis lectus</h4>
                    <div class="content-text text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl aliquam nisl. Eget maecenas pulvinar venenatis viverra sociis ut bibendum nulla. Orci aliquet in consequat lobortis. 
                    </div>
                    <a class="button secondary" href="https://www.google.com.sg/">
                        BUTTON
                    </a>
                </div>
            </div>
            <div class="card-box">
                <img alt="" src="https://i.ibb.co/rGPw8T6/Frame-162.png">
                <div class="card-one-details">
                    <h4 class="content-title">[H4] Lorem ipsum dolor sit amet conse ctetur mattis iaculis lectus</h4>
                    <div class="content-text text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl aliquam nisl. Eget maecenas pulvinar venenatis viverra sociis ut bibendum nulla. Orci aliquet in consequat lobortis. 
                    </div>
                    <a class="button secondary" href="https://www.google.com.sg/">
                        BUTTON
                    </a>
                </div>
            </div>
            <div class="card-box">
                <img alt="" src="https://i.ibb.co/rGPw8T6/Frame-162.png">
                <div class="card-one-details">
                    <h4 class="content-title">[H4] Lorem ipsum dolor sit amet conse ctetur mattis iaculis lectus</h4>
                    <div class="content-text text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl aliquam nisl. Eget maecenas pulvinar venenatis viverra sociis ut bibendum nulla. Orci aliquet in consequat lobortis. 
                    </div>
                    <a class="button secondary" href="https://www.google.com.sg/">
                        BUTTON
                    </a>
                </div>
            </div>
            <div class="card-box">
                <img alt="" src="https://i.ibb.co/rGPw8T6/Frame-162.png">
                <div class="card-one-details">
                    <h4 class="content-title">[H4] Lorem ipsum dolor sit amet conse ctetur mattis iaculis lectus</h4>
                    <div class="content-text text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl aliquam nisl. Eget maecenas pulvinar venenatis viverra sociis ut bibendum nulla. Orci aliquet in consequat lobortis. 
                    </div>
                    <a class="button secondary" href="https://www.google.com.sg/">
                        BUTTON
                    </a>
                </div>
            </div>
        </div>
    </div>
    <div class="section line-divider"></div>
    <div class="section">
        <div class="text-label-1">[Label 1] Three Columns - Lorem ipsum amet conse</div>
        <h3 id="anchorlink-1">[H3] Three Columns - Lorem ipsum dolor sit amet consectetur nisl id odio</h3>
        <div class="card-container three-column">
            <div class="card-box">
                <img alt="" src="https://i.ibb.co/rGPw8T6/Frame-162.png">
                <div class="card-one-details">
                    <h4 class="content-title">[H4] Lorem ipsum dolor sit amet</h4>
                    <div class="content-text text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl aliquam nisl. Eget maecenas pulvinar.
                    </div>
                    <a class="button secondary" href="https://www.google.com.sg/">
                        BUTTON
                    </a>
                </div>
            </div>
            <div class="card-box">
                <img alt="" src="https://i.ibb.co/rGPw8T6/Frame-162.png">
                <div class="card-one-details">
                    <h4 class="content-title">[H4] Lorem ipsum dolor sit amet</h4>
                    <div class="content-text text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl aliquam nisl. Eget maecenas pulvinar.
                    </div>
                    <a class="button secondary" href="https://www.google.com.sg/">
                        BUTTON
                    </a>
                </div>
            </div>
            <div class="card-box">
                <img alt="" src="https://i.ibb.co/rGPw8T6/Frame-162.png">
                <div class="card-one-details">
                    <h4 class="content-title">[H4] Lorem ipsum dolor sit amet</h4>
                    <div class="content-text text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl aliquam nisl. Eget maecenas pulvinar.
                    </div>
                    <a class="button secondary" href="https://www.google.com.sg/">
                        BUTTON
                    </a>
                </div>
            </div>
            <div class="card-box">
                <img alt="" src="https://i.ibb.co/rGPw8T6/Frame-162.png">
                <div class="card-one-details">
                    <h4 class="content-title">[H4] Lorem ipsum dolor sit amet</h4>
                    <div class="content-text text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl aliquam nisl. Eget maecenas pulvinar.
                    </div>
                    <a class="button secondary" href="https://www.google.com.sg/">
                        BUTTON
                    </a>
                </div>
            </div>
            <div class="card-box">
                <img alt="" src="https://i.ibb.co/rGPw8T6/Frame-162.png">
                <div class="card-one-details">
                    <h4 class="content-title">[H4] Lorem ipsum dolor sit amet</h4>
                    <div class="content-text text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl aliquam nisl. Eget maecenas pulvinar.
                    </div>
                    <a class="button secondary" href="https://www.google.com.sg/">
                        BUTTON
                    </a>
                </div>
            </div>
            <div class="card-box">
                <img alt="" src="https://i.ibb.co/rGPw8T6/Frame-162.png">
                <div class="card-one-details">
                    <h4 class="content-title">[H4] Lorem ipsum dolor sit amet</h4>
                    <div class="content-text text-body-2">
                        [Body 2] Lorem ipsum dolor sit amet consectetur. Amet venenatis mattis aliquam pharetra aenean turpis nisl aliquam nisl. Eget maecenas pulvinar.
                    </div>
                    <a class="button secondary" href="https://www.google.com.sg/">
                        BUTTON
                    </a>
                </div>
            </div>
        </div>
    </div>
</div>