---
layout: default
permalink: 'gallery/'
title: 'Gallery'
---

Here are a selection of photographs from the project.

<!-- Flickr album embed code -->
<div class="flickr">
  <a data-flickr-embed="true" href="https://www.flickr.com/photos/anotheryourself/albums/72157686411714416" title="View the gallery on Flickr">
    <img id="flickr-embed" src="https://farm5.staticflickr.com/4207/35181832080_52962ecbe8_z.jpg" alt="View the gallery on Flickr">
  </a>
  <script>
    var flickrGallery = document.getElementById('flickr-embed');
    if (flickrGallery) {
      var width = window.innerWidth;
      var galleryWidth, galleryHeight;

      if (width < 400) {
        galleryWidth = 239;
        galleryHeight = 240;
      } else if (width < 600) {
        galleryWidth = 318;
        galleryHeight = 320;
      } else if (width < 1024) {
        galleryWidth = 497;
        galleryHeight = 500;
      } else {
        galleryWidth = 636;
        galleryHeight = 640;
      }

      flickrGallery.width = galleryWidth;
      flickrGallery.height = galleryHeight;
    }
  </script>
  <script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>
</div>
<!-- end of Flickr album embed code -->
