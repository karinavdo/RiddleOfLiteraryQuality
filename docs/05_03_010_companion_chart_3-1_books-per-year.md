---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title:  "Grafiek 3.1 Aantal boeken dat deelnemers aangaven per jaar te lezen"

---


Interactieve versie van de grafiek op p. 48 van *Het raadsel literatuur*.

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

In de linker grafiek hierboven staat het aantal deelnemers afgezet tegen het aantal boeken dat zij aangaven per jaar ongeveer te lezen. De eerste verticale balk duidt aan dat iets minder dan 6100 deelnemers een aantal van 1 tot 20 boeken invulden, bijna 3800 deelnemers een getal van 21 tot 40, en zo verder. <br> De rechter grafiek is interactief. Hier kunt u de precieze aantallen achterhalen. Op de regel onder de horizontale as kunt u bepalen op welk deel van de grafiek u wilt inzoomen; sleep de rechter markering bijvoorbeeld helemaal naar rechts en de linker naar 300. Door op de balken in de grafiek te klikken ziet u hoeveel respondenten een getal in het geselecteerde bereik invulden. Zo ziet u dat er een paar deelnemers waren die gemiddeld meer dan 1 boek per dag lazen.

<!-- **Hoe zijn de metingen te repliceren?**
VOORBEELDQUERY HIER! -->
