---
layout: gallery
published: true

7inch:
  - url: /assets/publications/TrisVonnaMichell-monographs-2007-33.jpg
    size: 2000x1335
    title: Tall Tales and Short Stories (7 inch vinyl)
  - url: /assets/publications/TrisVonnaMichell-monographs-2007-34.jpg
    size: 2000x1335
    title: Tall Tales and Short Stories (7 inch vinyl)
  - url: /assets/publications/TrisVonnaMichell-monographs-2007-35.jpg
    size: 2000x1647
    title: Tall Tales and Short Stories (7 inch vinyl)

12inch:    
  - url: /assets/publications/TrisVonnaMichell-monographs-2010-60.jpg
    size: 2000x1335
    title: Monumental Detours / Insignificant Fixtures (12 inch vinyl)
  - url: /assets/publications/TrisVonnaMichell-monographs-2010-61.jpg
    size: 2000x1335
    title: Monumental Detours / Insignificant Fixtures (12 inch vinyl)
  - url: /assets/publications/TrisVonnaMichell-monographs-2010-62.jpg
    size: 2000x1335
    title: Monumental Detours / Insignificant Fixtures (12 inch vinyl)
---
## Records

**[Capitol Complex / Ulterior Vistas]({{site.baseurl}}/publications/monographs/)**<br/>
(book and 10 inch vinyl), published by Focal Point Gallery, Southend-on-Sea and Mount Analogue, Stockholm, 2013

**GAMeC 12 inch**<br/>
Monumental Detours / Insignificant Fixtures (12 inch vinyl), published by GAMeC Bergamo and Kunsthalle Zürich, 2009

<div class="popup-gallery" style="margin-bottom:10px;">
  {% for image in page.12inch %}
    <a href="{{image.url}}" data-size="{{image.size}}" data-author="Tris Vonna-Michell">
      <img src="{{image.url}}" alt="" />
      <figure>{{image.title}}</figure>
    </a>
  {% endfor %}
</div>

**WdW 7 inch**<br/>
Tall Tales and Short Stories (7 inch vinyl), published by Witte de With, Rotterdam, 2007

<div class="popup-gallery">
  {% for image in page.7inch %}
    <a href="{{image.url}}" data-size="{{image.size}}" data-author="Tris Vonna-Michell">
      <img src="{{image.url}}" alt="" />
      <figure>{{image.title}}</figure>
    </a>
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
