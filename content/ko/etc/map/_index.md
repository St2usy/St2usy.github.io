---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing
---

<link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" />
<script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"></script>

<div id="map" style="height: 400px;"></div>
<script>
  var map = L.map('map').setView([35.847069, 127.129879], 15);
  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    attribution: '© OpenStreetMap contributors'
  }).addTo(map);
  
  var marker = L.marker([35.847069, 127.129879]).addTo(map)
    .bindPopup('Location marker').openPopup();
</script>
