---
{"dg-publish":true,"permalink":"/lore/karte/"}
---

```leaflet 
id: leaflet-map 
image: [[Arkanis.png]] 
height: 500px 
lat: 50 
long: 50 
minZoom: 1 
maxZoom: 5 
defaultZoom: 10 
unit: meters 
scale: 1 
darkMode: false
```


test test

<div id="map" style="height: 400px;"></div>
```js
<script> document.addEventListener('DOMContentLoaded', function () { var map = L.map('map').setView([51.505, -0.09], 13); L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', { attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors' }).addTo(map); L.marker([51.505, -0.09]).addTo(map) .bindPopup('A pretty CSS3 popup.<br> Easily customizable.') .openPopup(); }); </script>
```

