Slider.css
===

HTML presentation without javascript.

[DEMO](http://nodejs.in/slider.css/)

Feature
--

- Forward / Backward
- Transitions
- Progressbar(Chrome #enable-experimental-web-platform-features)
- Maximize / Minimize
- Page number
- Basic layout

How to start
--

Put the code below into your page.

    <link rel="stylesheet" href="/some/path/slider.css" />
    <div style="width: 640px;height: 400px;">
        <!-- Maximize  -->
        <input id="slider-max" type="checkbox" checked/>
        <article class="slider slider-indicator">
        <a id="slider-default"></a>
        <label for="slider-max" title="Maximize"></label>

        <section id="slider-1" default>
            <!-- layout -->
            <div>
                <h1>Slider.css</h1>
                <p>HTML presentation without javascript.</p>
            </div>
        </section>
        <div>
            <!-- triggers -->
            <a></a>
            <a href="#slider-2"></a>
            <!-- progressbar -->
            <span></span>
        </div>

        <!-- start page -->
        <div id="slider">
            <a href="#slider-default" class="slider-start">PLAY</a>
        </div>

        <!-- progressbar container -->
        <div class="slider-progress"></div>
        </article>
    </div>

LICENSE
---

MIT
