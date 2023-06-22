---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title:  "Figure 4.1: Ratings of Nicole Krauss, <i>Het grote huis</i> (<i>Great House</i>)"

---
Interactive version of the graph on p. 97 of *The Riddle of Literary Quality*.

<script src="https://d3js.org/d3.v6.min.js" defer></script>
<script src="https://d3js.org/d3-scale.v3.min.js" defer></script>

<script src="js/companion_utils_locale-nl.js" defer></script>
<script src="js/companion_utils_colors.js" defer></script>
<script src="js/companion_utils_svg2png.js" defer></script>
<script src="js/companion_abstraction_data_point_labeler.js" defer></script>
<script src="js/companion_abstraction_barchart.js" defer></script>

<script src="js/companion_chart_bookrating.js" defer></script>
<script src="js/companion_chart_7-1_huis.js" defer></script>

<div class="chart_float" id="chart_7-1_huis">
  <div class="plot"></div>
</div>

A click on a bar in the graph reveals how many participants in The National Reader Survey assigned a certain score to the novel.
