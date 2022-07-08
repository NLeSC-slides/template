<!-- .slide: data-state="standard" data-background="./files/gears-1236578_1920.jpg"-->

# Interaction

---

<!-- .slide: data-state="clear_background logo yellow_flag" data-background-iframe="https://en.wikipedia.org"-->

<div style="color: black; background-color: rgba(255, 255, 255, .8);">
  <h2 style="color: black;">Embed websites</h2>
  <ul>
    <li>They have to allow it though...</li>
    <li>A "clear_background" removes all overlays and allows for interaction with the website</li>
    <li>Any elements you put on top (like this text frame) lie on top, so click on the website behind to interact with it</li>
    <li>Once you interact with the website (clicking, etc.) the focus for navigation is gone</li>
    <ul>
      <li>This means you need to click on the arrows on the bottom right to proceed</li>
    </ul>
  </ul>
</div>

---

<!-- .slide: data-state="clear_background logo yellow_flag" data-background-image="https://jupyterlab.readthedocs.io/en/stable/_images/jupyterlab.png"-->

<div style="color: black; background-color: rgba(255, 255, 255, .8);">
  <h2 style="color: black">Embed Jupyter Notebooks</h2>
  <p>Show your own work when sharing your screen...</p>
  <p>... or let everybody in the audience code in their browser and play with data</p>
  <br/>
  <p>(static image as an example, you have to host it somewhere yourself)</p>
</div>

---

<!-- .slide: data-state="standard" data-background="./files/gears-1236578_1920.jpg"-->

## Embed Interactive Visualizations 1

<div style="width: 50%; float: left;">
  <p>Embed D3 visualizations into slides, and keep the original interactivity.</p>
  <p>(click on the globe and drag it to explore the different paths!)</p>
  <p><span class="u">Visualization:</span><br><a href='https://bl.ocks.org/Fil/63366253a5d2f00640c15b096c29a38c' target='_blank'>Eclipses path</a> by Philippe Riviere and friends</p>
</div>
<div style="width: 45%; max-height: 40vh; float: right;" class="fig-container" data-file="./reveal.js/4.3.1/reveal.js-plugins/reveal.js-d3/demo/d3-fig/eclipses.html">
</div>

---

<!-- .slide: data-state="standard" data-background="./files/gears-1236578_1920.jpg" class="fig-container" data-no-background data-file="./reveal.js/4.3.1/reveal.js-plugins/reveal.js-d3/demo/d3-fig/collision-detection.html" style="overflow: visible"-->

## Embed Interactive Visualizations 2

- Advance slides to trigger visualization transitions
- Use mouse to interact with the visualization
- Adapted from [Collision detection](https://bl.ocks.org/mbostock/3231298) by Mike Bostock

---

<!-- .slide: data-state="black_overlay logo yellow_flag" data-background="./files/gears-1236578_1920.jpg"-->

## Multi-visualizations

<div style="width: 48%; float: left;">
  <p class="no-margin-top small">
    <a href='https://bl.ocks.org/olearym/ec27b9ac1bf0da42ed8a0d533181693b' target='_blank'>Gooey effect - Hexagon</a> by Nadieh Bremer</p>
  <div class="fig-container no-margin-top" data-file="./reveal.js/4.3.1/reveal.js-plugins/reveal.js-d3/demo/d3-fig/gooey.html">
  </div>
</div>
<div style="width: 48%; float: right;">
  <p class="no-margin-top small">
    <a href='https://bl.ocks.org/olearym/ec27b9ac1bf0da42ed8a0d533181693b' target='_blank'>Modular Multiplication Circle</a> by Megan O'Leary</p>
  <div class="fig-container no-margin-top" data-file="./reveal.js/4.3.1/reveal.js-plugins/reveal.js-d3/demo/d3-fig/modular-multiplication.html"></div>
</div>

---

<!-- .slide: data-state="black_overlay logo yellow_flag" data-background="./files/gears-1236578_1920.jpg"-->

## Independent Transitions

<div style="width: 48%; float: left;">
    <a href='https://bl.ocks.org/mbostock/4165404' target='_blank'>Rainbow worm</a> by Mike Bostock <br>
    transition on 1 and 3
  <div class="fig-container no-margin-top" data-preload data-file="./reveal.js/4.3.1/reveal.js-plugins/reveal.js-d3/demo/d3-fig/rainbow.html"></div>
</div>
<div style="width: 48%; float: right;">
  <p class="no-margin-top small">
    Simple bar graph <br>
    transition on 2 and 3
  <div class="fig-container no-margin-top" data-file="./reveal.js/4.3.1/reveal.js-plugins/reveal.js-d3/demo/d3-fig/bar-chart.html"></div>
</div>

---

<!-- .slide: data-state="black_overlay logo yellow_flag" data-background="./files/gears-1236578_1920.jpg"-->

## Other Libraries

- Also works with other libraries
- Use mouse-over to learn more about the shown data

<div style="width: 400px; margin: auto;">
  <a href='https://emeeks.github.io/semiotic/#/semiotic/chord' target='_blank'>Chord diagram</a>
  <div class="fig-container" data-file="./reveal.js/4.3.1/reveal.js-plugins/reveal.js-d3/demo/d3-fig/semiotic-chord.html" data-preload></div>
</div>

