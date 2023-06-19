---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title:  "Figure 2.1: Number of books respondents indicated to have read per year"

---


Interactive version of the graph on page 39 of *The Riddle of Literary Quality*.

<script src="https://d3js.org/d3.v6.min.js" defer></script>
<script src="https://d3js.org/d3-scale.v3.min.js" defer></script>
<script src="https://unpkg.com/d3-simple-slider"></script>

<script src="js/companion_utils_locale-nl.js" defer></script>
<script src="js/companion_utils_colors.js" defer></script>
<script src="js/companion_utils_svg2png.js" defer></script>
<script src="js/companion_abstraction_data_point_labeler.js" defer></script>
<script src="js/companion_abstraction_histogram.js" defer></script>

<script src="js/companion_chart_3-1_books-per-year.js" defer></script>
<script src="js/companion_chart_3-1_books-per-year_excerpt.js" defer></script>

<div class="chart_float" id="chart_3-1_books-per-year">
  <div class="plot"></div>
</div>

<div class="chart_float" id="chart_3-1_books-per-year_excerpt">
  <div class="plot"></div>
  <div class="slider"></div>
</div>


<p id="value"></p>

The left graph above shows the number of participants compared to the approximate number of books they indicated they read per year. The first vertical bar indicates that just under 6100 participants filled in a number from 1 to 20 books, almost 3800 participants filled in a number from 21 to 40, and so on.
The right-hand chart is interactive. Here you can find out the exact numbers. On the line below the horizontal axis, you can determine which part of the graph you want to zoom in on; for example, drag the right marker all the way to the right and the left one to 300. By clicking on the bars in the graph, you can see how many respondents filled in a number in the selected range. For example, you can see that there were a few participants who read more than 1 book per day on average.



<!-- **Hoe zijn de metingen te repliceren?**
VOORBEELDQUERY HIER! -->
