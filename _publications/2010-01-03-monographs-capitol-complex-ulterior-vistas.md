---
layout: post
title: 'CAPITOL COMPLEX / ULTERIOR VISTAS'
category: monographs
published: true

monograph-1:
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2013-68.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2013-76.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2013-72.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2013-77.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2013-73.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2013-74.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2013-71.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2013-70.jpg
---

<div class="popup-gallery"><br/>
  {% for image in page.monograph-1 %}
    <a href="{{ image.image_path }}"><img src="{{ image.image_path }}" alt="{{ image.title}}" width="200" height="134" /></a>
  {% endfor %}
</div>

<br/>**[CAPITOL COMPLEX / ULTERIOR VISTAS](http://www.cornerhousepublications.org/publications/tris-vonna-michell-capitol-complex-ulterior-vistas/)** is constructed around the two works, Capitol Complex (2012-2015) and Ulterior Vistas (2012-2014), both of which are encapsulated on a ten-inch vinyl record. The spoken-word compositions are enclosed within a gatefold design and accompanied by the Capitol Complex manuscript as a booklet insert and a bound series of Ulterior Vistas photographic montages.

The Capitol Complex (Side A) recording pans between improvised spoken word and musical composition, evolving around a manuscript set in the Indian city of Chandigarh, which serves as an underlining blueprint for the work. Traveller, the protagonist, extends his leisurely strolls to navigating the city by night in order to induce an experience of greater intensity and anxiety of its urban architecture. After his nocturnal explorations in the city’s single-zone sectors he starts to grow weary and changes his course from architectural appreciation to searching for crevices and enclosures to reflect and observe. But urban fixtures of obstruction, surveillance and derailment direct his passages, until a shift in perception occurs.

The spoken word aspect of Ulterior Vistas (Side B) is backed by a musical score, and contextualised around the notion of a driven sales agent, orating a prospectus based on grand 18th Century English landscape garden design. The protagonist is soliciting a global perspective characterised by appropriation of cultural heritage in order to cultivate a desirable public persona for an unidentified client. Aside from offering an array of landscape gardening solutions and attributes he also proposes more abstract features such as synthetic spirituality and symbolic gestures of generosity. The conceptual framework for the Ulterior Vistas photographic series derives from the English landscape architect Humphrey Repton´s (1752-1818) famous Red Books. His books were bespoke landscape and architecture propositions for improving the estates and pleasure grounds of potential clients. The before-and-after illustrations were a key feature in
Repton´s Red Books as were his verbal presentations.

Content and concept by Tris Vonna-Michell<br/>
Edited by Diana Kaur<br/>
Recorded by Martin Ehrencrona at Studio Cobra, Stockholm<br/>
Spoken word by Tris Vonna-Michell<br/>
Instruments by Martin Ehrencrona and Markus Lindmark<br/>
Mixdown by Martin Ehrencrona and Tris Vonna-Michell<br/>
Copy editing by Andrew Hunt and Sophie Sleigh-Johnson<br/>
Designed by Konst & Teknik, assisted by Caroline Settergren<br/>
Image correction by Lena Hoxter<br/>
Printing and binding by Göteborgstryckeriet, Sweden<br/>
Published by Focal Point Gallery and Mount Analogue, 2013<br/>
Distributed by Cornerhouse<br/>
[ISBN 978-1-907185-14-4](http://www.cornerhousepublications.org/publications/tris-vonna-michell-capitol-complex-ulterior-vistas/)

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
