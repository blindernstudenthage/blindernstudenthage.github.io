---
layout: page
title: Find the garden
<!-- subtitle: It's easier than you think -->
---

<ul class="list-inline text-center location-links" style="font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif;">

{%- if site.social-network-links.googlemaps -%}
  <li class="list-inline-item">
    <a href="{{ site.social-network-links.googlemaps }}" title="Google Maps" target="_blank">
      <span class="fa-stack fa-lg" aria-hidden="true">
        <i class="fas fa-circle fa-stack-2x"></i>
        <i class="fas fa-map-location-dot fa-stack-1x fa-inverse"></i>
      </span>
      Google Maps
      <span class="sr-only">Google Maps</span>
   </a>
  </li>
{%- endif -%}

{%- if site.social-network-links.osm -%}
  <li class="list-inline-item">
    <a href="{{ site.social-network-links.osm }}" title="OpenStreetMap" target="_blank">
      <span class="fa-stack fa-lg" aria-hidden="true">
        <i class="fas fa-circle fa-stack-2x"></i>
        <i class="fas fa-map-pin fa-stack-1x fa-inverse"></i>
      </span>
      OpenStreetMap
      <span class="sr-only">OpenStreetMap</span>
    </a>
  </li>
{%- endif -%}

</ul>
