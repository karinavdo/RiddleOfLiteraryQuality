---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title:  "Figure 2.3: Number of books read per category"

---
Interactive version of the graph on p. 44 of *The Riddle of Literary Quality*.

<script src="https://d3js.org/d3.v6.min.js" defer></script>
<script src="https://d3js.org/d3-scale.v3.min.js" defer></script>
<script src="https://unpkg.com/d3-simple-slider"></script>

<script src="js/companion_utils_locale-nl.js" defer></script>
<script src="js/companion_utils_colors.js" defer></script>
<script src="js/companion_utils_svg2png.js" defer></script>
<script src="js/companion_abstraction_data_point_labeler.js" defer></script>
<script src="js/companion_abstraction_histogram.js" defer></script>

<script src="js/companion_resp_read_genre_enlarged.js" defer></script>
<script src="js/companion_resp_read_fiction.js" defer></script>
<script src="js/companion_resp_read_suspense.js" defer></script>
<script src="js/companion_resp_read_romantic.js" defer></script>
<script src="js/companion_resp_read_other.js" defer></script>

Clicking on one of the four small graphs shows more information about the selected category in the larger graph below. A click on a specific bar reveals the underlying numbers. The range of the horizontal axis of the large graph can be adjusted by dragging the two tab markers.

<div class="chart_float chart_thumb" id="resp_read_fiction">
  <div class="plot"></div>
</div>
<div class="chart_float chart_thumb" id="resp_read_suspense">
  <div class="plot"></div>
</div>
<div class="chart_float chart_thumb" id="resp_read_romantic">
  <div class="plot"></div>
</div>
<div class="chart_float chart_thumb" id="resp_read_other">
  <div class="plot"></div>
</div>

<div class="chart_float" id="resp_read_genre_enlarged">
  <div class="plot"></div>
  <div class="slider"></div>
</div>


