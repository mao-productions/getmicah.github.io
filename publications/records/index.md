---
layout: gallery
published: true

records:
  - url: /assets/publications/TrisVonnaMichell-monographs-2007-33.jpg
    size: 2000x1335
    title: WdW 7 inch
  - url: /assets/publications/TrisVonnaMichell-monographs-2007-34.jpg
    size: 2000x1335
    title: WdW 7 inch
  - url: /assets/publications/TrisVonnaMichell-monographs-2007-35.jpg
    size: 2000x1647
    title: WdW 7 inch
  - url: /assets/publications/TrisVonnaMichell-monographs-2010-60.jpg
    size: 2000x1335
    title: WdW 7 inch
  - url: /assets/publications/TrisVonnaMichell-monographs-2010-61.jpg
    size: 2000x1335
    title: WdW 7 inch
  - url: /assets/publications/TrisVonnaMichell-monographs-2010-62.jpg
    size: 2000x1335
    title: WdW 7 inch
---
## Records

**[Capitoc Complex / Ulterior Vistas](http://www.cornerhousepublications.org/publications/tris-vonna-michell-capitol-complex-ulterior-vistas/)**

**GAMeC 12 inch**<br/>
(12 inch vinyl), published by GAMeC Bergamo and Kunsthalle Zürich

**WdW 7 inch**<br/>
(7 inch vinyl), published by Witte de With, Rotterdam

<div class="popup-gallery">
  {% for image in page.records %}
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
