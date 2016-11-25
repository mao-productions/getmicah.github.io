---
layout: post
title: 'TRIS VONNA-MICHELL'
category: monographs
published: true

monograph-2:
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2011-83.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2011-84.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2011-85.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2011-86.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2011-87.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2011-88.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2011-89.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2011-90.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2011-91.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2011-93.jpg
---

<div class="popup-gallery"><br/>
  {% for image in page.monograph-2 %}
    <a href="{{ image.image_path }}"><img src="{{ image.image_path }}" alt="{{ image.title}}" width="200" height="134" /></a>
  {% endfor %}
</div>

<br/>**[TRIS VONNA-MICHELL](http://www.cornerhousepublications.org/publications/tris-vonna-michell/)** is a two-volume publication in which the stories and the visual material marks a continuation and implementation of his artistic practice through the medium of an artist’s book. Behind an identical cover, the seemingly same is presented in two variations that were developed through performative improvisations over earlier text versions, and repositioning of images and inserts.

The two variations were pendently constructed; book I began in November 2009 at Halle für Kunst in Lüneburg, in which several chapters, texts and images were printed on a Heidelberg GTO printing press on a daily basis during the exhibition ”Capstans”. In 2010 book II began as a revisitation and expansion of the first variation, in which the previous narratives, images and inserts were reconstructed.

Text and images by Tris Vonna-Michell<br/>
Graphic design by Manuel Raeder with Tris Vonna-Michell<br/>
Published by JRP|Ringier, together with with Fondazione Galleria Civica—Centro di Ricerca sulla Contemporaneità di Trento, GAMeC—Galleria d’Arte Moderna e Contemporanea di Bergamo, Halle für Kunst Lüneburg e.V., and Kunsthalle Zürich, 2011<br/>
Printed in Germany<br/>
[ISBN 978-3-03764-170-5](http://www.cornerhousepublications.org/publications/tris-vonna-michell/)

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
