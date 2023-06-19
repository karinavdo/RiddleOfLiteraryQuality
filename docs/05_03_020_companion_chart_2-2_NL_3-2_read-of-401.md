---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title:  "Figure 2.2 Number of books read (left) and number of books rated (right)"

---
Interactive version of the graph on p. 42 of *The Riddle of Literary Quality*.

<script src="https://d3js.org/d3.v6.min.js" defer></script>
<script src="https://d3js.org/d3-scale.v3.min.js" defer></script>
<script src="https://unpkg.com/d3-simple-slider"></script>

<script src="js/companion_utils_locale-nl.js" defer></script>
<script src="js/companion_utils_colors.js" defer></script>
<script src="js/companion_utils_svg2png.js" defer></script>
<script src="js/companion_abstraction_data_point_labeler.js" defer></script>
<script src="js/companion_abstraction_histogram.js" defer></script>

<script src="js/companion_chart_3-2_read-of-401.js" defer></script>
<script src="js/companion_chart_3-3_rated-of-401.js" defer></script>

<div class="chart_float" id="chart_3-2_read-of-401">
  <div class="plot"></div>
  <div class="slider"></div>
</div>

<div class="chart_float" id="chart_3-3_rated-of-401">
  <div class="plot"></div>
  <div class="slider"></div>
</div>

Figure 2.2: Number of books read out of 401 (left) and number of books reviewed (right).
Both graphs are interactive. On the line below the horizontal axis, you can select which part of the graph you want to zoom in on. By clicking on the bars in the graph, you can see how many respondents filled in a number in the selected range.<br>

