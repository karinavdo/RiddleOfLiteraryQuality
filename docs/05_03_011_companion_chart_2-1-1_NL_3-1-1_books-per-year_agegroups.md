---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# kleur is een html kleurnaam of een code #dfdfdf (heel wit). Color picker: https://htmlcolorcodes.com/.
title:  "<b>Additional figure</b>: Number of read books per year per age group"

---
Interactieve grafiek ter verdieping van Grafiek 3.1 op p. 48 van *Het raadsel literatuur*.


<script src="https://d3js.org/d3.v6.min.js" defer></script>
<script src="https://d3js.org/d3-scale.v3.min.js" defer></script>
<script src="js/companion_chart_3-1-1_books-per-year_agegroups.js" defer></script>

<div>
  <div class="chart_float" id="chart_3-1-1_books-per-year_agegroups_mean"></div>
  <div class="chart_float" id="chart_3-1-1_books-per-year_agegroups_hist"></div>
</div>
<!-- TODO: solve below hack to clear -->
<div style="clear: both;"></div>

The left graph shows in a bar for each age category the approximate number of books participants from that age group reported reading per year. The right graph then presents the details for the selected age group.
