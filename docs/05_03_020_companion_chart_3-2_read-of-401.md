---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title:  "Grafiek 3.2 Aantal gelezen boeken en aantal beoordeelde boeken"

---
Interactieve versie van de grafiek op p. 52 van *Het raadsel literatuur*.

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

Grafiek 3.2: Aantal gelezen van de 401 boeken (links) en aantal beoordeelde boeken (rechts).<br>
Beide grafieken zijn interactief. Op de regel onder de horizontale as kunt u bepalen op welk deel van de grafiek u wilt inzoomen. Door op de balken in de grafiek te klikken ziet u hoeveel respondenten een getal in het geselecteerde bereik invulden.
<!-- **Hoe zijn de metingen te repliceren?**
VOORBEELDQUERY HIER! -->
