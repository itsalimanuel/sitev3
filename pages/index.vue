<script setup>


</script>

<template>
    <div class="home">
        <div class="home-container">
            <div class="home-container-box">
                <h1 id="name"> Ali Khalouf</h1>
                <h4>Creative Developer</h4>
            </div>
            <div class="home-scroll">
                <div class="home-scroll-circle">
                    <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px"
                        y="0px" width="300px" height="300px" viewBox="0 0 300 300" enable-background="new 0 0 300 300"
                        xml:space="preserve">
                        <defs>
                            <path id="circlePath" d="M 150, 150 m -60, 0 a 60,60 0 0,1 120,0 a 60,60 0 0,1 -120,0 " />
                        </defs>
                        <circle cx="150" cy="100" r="75" fill="none" />
                        <g>
                            <use xlink:href="#circlePath" fill="none" />
                            <text fill="#000">
                                <textPath xlink:href="#circlePath">Scroll-Scroll-Scroll-Scroll-Scroll-Scroll -</textPath>
                            </text>
                        </g>
                    </svg>
                </div>
            </div>
        </div>
        <div class="home-info">
            <div data-container="sm">
                <p>As human beings, we often find ourselves feeling out of place in the world around us. We sense that
                    something is not quite right, that the reality we experience is not necessarily the truth. And yet, we
                    are bound by the beliefs and illusions that have been ingrained in us since childhood. It can be a
                    difficult and confusing journey to try and unravel these beliefs, to see beyond the layers of deception
                    that cloud our vision. We may feel as though we need to make an effort, to strive for enlightenment, to
                    grasp at something just beyond our reach. But what if the answer is not found in effort, but in
                    surrender? What if we simply allow ourselves to be carried by the flow of existence, to trust in the
                    natural rhythm of life itself?</p>
            </div>
        </div>
        <div class="home-works">
            <div class="--title">
                <h1>Works</h1>
            </div>
            <div data-container="lg" class="--list">
                <div class="--item">
                    <div class="--item-image"></div>
                    <div class="--item-number"></div>
                    <div class="--item-name"></div>
                </div>
            </div>
        </div>
    </div>
</template>


<style lang="sass" scoped>
    .home
        position: relative
        &-container
            width: 100%
            height: 600px
            background: #fff
            position: relative
            &-box
                width: 100%
                height: 100%
                max-width: 1300px
                margin: auto
                display: flex
                flex-direction: column
                align-items: center
                justify-content: center
                h1
                    color: #27272A
                    font-size: 182px
                    letter-spacing: 5px
                    span
                        color: #fff
                h4
                    font-size: 46px
                    color: #000
        &-scroll
            position: absolute
            bottom: 0
            left: 50%
            transform: translate(-50%,50%)
            width: 400px
            height: 400px
            &-circle
                position: relative
                width: 100%
                height: 100%
                overflow: hidden
                svg
                    position: absolute
                    top: 0
                    left: 0
                    width: 100%
                    height: 100%
                    animation-name: rotate
                    animation-duration: 12s
                    animation-iteration-count: infinite
                    animation-timing-function: linear
        &-info
            position: relative
            padding: 300px 0
            p
                font-weight: 200
                font-size: 22px
                font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
        &-works
            overflow: hidden
            .--title
                h1
                    text-align: center
                    font-size: 500px
@keyframes rotate 
    from 
        transform: rotate(360deg)
    to  
        transform: rotate(0) 

</style>