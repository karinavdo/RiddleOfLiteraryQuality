---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title:  "Figure 6.6: Mean sentence length (in words) of Dutch-language Literary novels"
---
Interactive version of the graph on p. 174 of *The Riddle of Literary Quality*.

Hovering over a symbol in the graph reveals which book is represented (the author's name and the title of the book).


<style>
path.regressionLine {
    stroke: #d85040;
    fill: none;
    stroke-width: 1.5;
    stroke-dasharray: 3,5;
  }
</style>

<script src="https://d3js.org/d3.v6.min.js" defer></script>
<script src="https://d3js.org/d3-scale.v3.min.js" defer></script>
<script src="https://unpkg.com/simple-statistics@7.7.0/dist/simple-statistics.min.js" defer></script>
<script src="js/companion_utils_locale-nl.js" defer></script>
<script src="js/companion_utils_colors.js" defer></script>
<script src="js/companion_utils_svg2png.js" defer></script>

<script src="js/companion_chart_11-4_sentence-length.js" defer></script>

<div class="chart_float" id="chart_11-4_sentence-length"></div>
<div class="chart_float" id="chart_11-5_sentence-length-variance"></div>

