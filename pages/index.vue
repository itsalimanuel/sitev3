<script setup>

</script>

<template>
  <main class="home">
    <div class="home-container">
      <div class="home-container-box">
        <h1 id="name">Ali Khalouf</h1>
        <h4>Creative Developer</h4>
      </div>
      <div class="home-scroll">
        <div class="home-scroll-circle">
          <svg
            version="1.1"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            x="0px"
            y="0px"
            width="300px"
            height="300px"
            viewBox="0 0 300 300"
            enable-background="new 0 0 300 300"
            xml:space="preserve"
          >
            <defs>
              <path
                id="circlePath"
                d="M 150, 150 m -60, 0 a 60,60 0 0,1 120,0 a 60,60 0 0,1 -120,0 "
              />
            </defs>
            <circle cx="150" cy="100" r="75" fill="none" />
            <g>
              <use xlink:href="#circlePath" fill="none" />
              <text fill="#000">
                <textPath xlink:href="#circlePath">
                  Scroll-Scroll-Scroll-Scroll-Scroll-Scroll -
                </textPath>
              </text>
            </g>
          </svg>
        </div>
      </div>
    </div>
    <div class="home-info">
      <div data-container="sm">
        <p>
          As human beings, we often find ourselves feeling out of place in the
          world around us. We sense that something is not quite right, that the
          reality we experience is not necessarily the truth. And yet, we are
          bound by the beliefs and illusions that have been ingrained in us
          since childhood. It can be a difficult and confusing journey to try
          and unravel these beliefs, to see beyond the layers of deception that
          cloud our vision. We may feel as though we need to make an effort, to
          strive for enlightenment, to grasp at something just beyond our reach.
          But what if the answer is not found in effort, but in surrender? What
          if we simply allow ourselves to be carried by the flow of existence,
          to trust in the natural rhythm of life itself?
        </p>
      </div>
    </div>
    <div class="home-works">
      <div class="--title">
        <h1>Works</h1>
      </div>
      <div class="content" data-scroll>
        <div class="item">
          <div class="item__img-wrap">
            <div class="item__img item__img--t1"></div>
          </div>
          <div class="item__caption">
            <h2 class="item__caption-title">Central view</h2>
            <p class="item__caption-copy">
              Great turbulent clouds emerged into consciousness citizens.
            </p>
          </div>
        </div>
        <div class="item">
          <div class="item__img-wrap">
            <div class="item__img item__img--t2"></div>
          </div>
          <div class="item__caption">
            <h2 class="item__caption-title">Lost in time</h2>
            <p class="item__caption-copy">
              Brain is the seed of intelligence the sky calls to us a very small
              stage.
            </p>
          </div>
        </div>
        <div class="item">
          <div class="item__img-wrap">
            <div class="item__img item__img--t3"></div>
          </div>
          <div class="item__caption">
            <h2 class="item__caption-title">Ready to land</h2>
            <p class="item__caption-copy">
              Cosmos encyclopaedia galactica a billion trillion culture cosmic
              ocean.
            </p>
          </div>
        </div>
        <div class="item">
          <div class="item__img-wrap">
            <div class="item__img item__img--t1"></div>
          </div>
          <div class="item__caption">
            <h2 class="item__caption-title">All equal</h2>
            <p class="item__caption-copy">
              Network of wormholes dream of the mind's eye finite but unbounded
              concept.
            </p>
          </div>
        </div>
        <div class="item">
          <div class="item__img-wrap">
            <div class="item__img item__img--t2"></div>
          </div>
          <div class="item__caption">
            <h2 class="item__caption-title">Connections</h2>
            <p class="item__caption-copy">
              Two ghostly white figures in coveralls and helmets are softly
              dancing vastness.
            </p>
          </div>
        </div>
        <div class="item">
          <div class="item__img-wrap">
            <div class="item__img item__img--t3"></div>
          </div>
          <div class="item__caption">
            <h2 class="item__caption-title">The state of divergence</h2>
            <p class="item__caption-copy">
              Vastness is bearable only through love invent the universe
              vanquish.
            </p>
          </div>
        </div>
        <div class="item">
          <div class="item__img-wrap">
            <div class="item__img item__img--t1"></div>
          </div>
          <div class="item__caption">
            <h2 class="item__caption-title">Open perspective</h2>
            <p class="item__caption-copy">
              The only home we've ever known concept of the number one.
            </p>
          </div>
        </div>
        <div class="item">
          <div class="item__img-wrap">
            <div class="item__img item__img--t3"></div>
          </div>
          <div class="item__caption">
            <h2 class="item__caption-title">Discovery of shapes</h2>
            <p class="item__caption-copy">
              Decipherment explorations tesseract as a patch of light.
            </p>
          </div>
        </div>
        <div class="item">
          <div class="item__img-wrap">
            <div class="item__img item__img--t2"></div>
          </div>
          <div class="item__caption">
            <h2 class="item__caption-title">The Observer</h2>
            <p class="item__caption-copy">
              Astonishment muse about dispassionate extraterrestrial observer.
            </p>
          </div>
        </div>
      </div>
    </div>
  </main>
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
                    font-size: 16vw
                    letter-spacing: 5px
                    span
                        color: #fff
                h4
                    font-size: 46px
                    color: #27272A
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
                    font-size: 25vw
            .--list
                display: grid
                grid-template-columns: 1fr
                gap: 20px
                .--item
                    display: grid
                    grid-template-columns: 1fr 2fr
                    gap: 20px
                    align-items: center
                    &-name
                        h2
                            font-size: 48px
@keyframes rotate
    from
        transform: rotate(360deg)
    to
        transform: rotate(0)
</style>
<style>
.content {
  display: flex;
  flex-direction: column;
  position: relative;
  align-items: center;
  padding: 12rem 0;
  counter-reset: figure;
}

.item {
  margin: 10vh auto;
  max-width: 100%;
  position: relative;
  will-change: transform;
}

.item::before {
  counter-increment: figure;
  content: counter(figure, decimal-leading-zero);
  position: absolute;
  font-family: paralucent, sans-serif;
  font-size: 10rem;
  color: var(--color-deco);
  bottom: calc(100% - 3rem);
}

.item:nth-child(even)::before {
  right: 0;
}

.item__img-wrap {
  --aspect-ratio: 1/1.5;
  overflow: hidden;
  width: 500px;
  margin: 0 auto;
  padding-bottom: calc(100% / (var(--aspect-ratio)));
  max-width: calc(100% - 2rem);
  will-change: transform;
}

.item:first-child .item__img-wrap {
  --aspect-ratio: 8/10;
  --image: url(https://tympanus.net/Tutorials/SmoothScrollAnimations/img/1.jpg);
}

.item:nth-child(2) .item__img-wrap {
  width: 1000px;
  --aspect-ratio: 120/76;
  --image: url(https://tympanus.net/Tutorials/SmoothScrollAnimations/img/2.jpg);
}

.item:nth-child(3) .item__img-wrap {
  --aspect-ratio: 60/75;
  --image: url(https://tympanus.net/Tutorials/SmoothScrollAnimations/img/3.jpg);
}

.item:nth-child(4) .item__img-wrap {
  width: 800px;
  --aspect-ratio: 900/505;
  --image: url(https://tympanus.net/Tutorials/SmoothScrollAnimations/img/4.jpg);
}

.item:nth-child(5) .item__img-wrap {
  --aspect-ratio: 6/8;
  --image: url(https://tympanus.net/Tutorials/SmoothScrollAnimations/img/5.jpg);
}

.item:nth-child(6) .item__img-wrap {
  width: calc(100vw - 2rem);
  --aspect-ratio: 1500/844;
  --image: url(https://tympanus.net/Tutorials/SmoothScrollAnimations/img/6.jpg);
}

.item:nth-child(7) .item__img-wrap {
  width: 900px;
  --aspect-ratio: 1000/749;
  --image: url(https://tympanus.net/Tutorials/SmoothScrollAnimations/img/7.jpg);
}

.item:nth-child(8) .item__img-wrap {
  width: 900px;
  --aspect-ratio: 1000/562;
  --image: url(https://tympanus.net/Tutorials/SmoothScrollAnimations/img/8.jpg);
}

.item:nth-child(9) .item__img-wrap {
  --aspect-ratio: 60/75;
  --image: url(https://tympanus.net/Tutorials/SmoothScrollAnimations/img/9.jpg);
}

.item__img {
  --overflow: 40px;
  height: calc(100% + (2 * var(--overflow)));
  top: calc(-1 * var(--overflow));
  width: 100%;
  position: absolute;
  background-image: var(--image);
  background-size: cover;
  background-position: 50% 0%;
  will-change: transform;
}

.item__img--t1 {
  --overflow: 60px;
}

.item__img--t2 {
  --overflow: 80px;
}

.item__img--t3 {
  --overflow: 120px;
}

.item__caption {
  padding: 2rem 1rem;
}

.item__caption-title {
  font-family: paralucent, sans-serif;
  font-weight: 400;
  font-size: 3rem;
  margin: 0;
}

.item__caption-copy {
  margin: 0;
}

.item__caption-copy::before {
  content: "__";
  line-height: 1;
  color: var(--color-link);
  font-weight: 700;
  font-size: 3rem;
  margin: 0 0 1rem;
  display: block;
}
</style>
