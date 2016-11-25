---
layout: post
title: 'FINDING CHOPIN ENDNOTES, 2005-2009'
category: monographs
published: true

monograph-3:  
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2009-82.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2007-33.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2007-34.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2007-35.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2010-60.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2010-61.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2010-62.jpg
---

<div class="popup-gallery"><br/>
  {% for image in page.monograph-3 %}
    <a href="{{ image.image_path }}"><img src="{{ image.image_path }}" alt="{{ image.title}}" width="200" height="134" /></a>
  {% endfor %}
</div>

<script type="text/javascript">
  $(document).ready(function() {
    $('.popup-gallery').magnificPopup({
      delegate: 'a',
      type: 'image',
      tLoading: 'Loading image #%curr%...',
      mainClass: 'mfp-img-mobile',
      gallery: {
        enabled: true,
        navigateByImgClick: true,
        preload: [0,1] // Will preload 0 - before current, and 1 after the current image
      },
      image: {
        tError: '<a href="%url%">The image #%curr%</a> could not be loaded.',
        titleSrc: function(item) {
          return 'Publications' + '<small>Tris Vonna-Michell</small>';
        }
      }
    });
  });
</script>
