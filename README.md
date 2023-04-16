# WendyWang.github.io
<iframe src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1B2n6Et8u7TaDUFyYU_QTZvQNmnppvyrLHioHajG6ZXs&font=Default&lang=en&initial_zoom=2&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>
<script src="https://storymaps.arcgis.com/stories/7e448e88453b457fb855433eae88bc07/edit"></script>
<div id="mapView"></div>
require([
  "esri/Map",
  "esri/views/MapView"
], function(Map, MapView) {
  var map = new Map({
    basemap: "streets-navigation-vector"
  });

  var view = new MapView({
    container: "mapView",
    map: map,
    center: [-118.80500, 34.02700],
    zoom: 13
  });
});
