---
layout: about
published: true

monograph-3:  
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2009-82.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2007-33.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2007-34.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2007-35.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2010-60.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2010-61.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2010-62.jpg

publications:
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2015-45.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2015-44.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2014-81.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2014-80.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2014-79.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2014-67.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2014-66.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2014-65.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2014-64.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2014-58.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2014-40.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2014-39.jpg
  - image_path: /assets/publications/TrisVonnaMichell-monographs-2014-37.jpg
---

**Rhythm of the Interval. Projection Circulation and Fragmentation of Images and Words in Tris Vonna-Michell’s Art practice by Lilian Haberer (2015)**<br/>
Published in PhotoResearcher 57 No 24 | 2015

**Notes on Finding Chopin: Dans l’Essex by Tris Vonna-Michell (2015)** [.pdf]({{site.baseurl}}/assets/pdf/TrisVM-text-on-filming-Finding-Chopin-published-by-OEI.pdf)<br/>
Published in OEI #69–70: On Film

**The noise of reception by Vincent Bonin (2014)** [.pdf]({{site.baseurl}}/assets/pdf/TrisVM-essay-by-Vincent-Bonin-for-TPW-Toronto.pdf)<br/>
Accompanied the exhibition:<br/>
Capitol Complex<br/>
10 May - 7 June 2014<br/>
Gallery TPW, Toronto

**Overflowing history by Yuki Higashino (2014)** [.pdf]({{site.baseurl}}/assets/pdf/TrisVM-essay-by-Yuki-Higashino-VOX.pdf)<br/>
Accompanied the exhibition:<br/>
Tris Vonna-Michell<br/>
7 February - 12 April 2014<br/>
VOX Centre de l’image contemporaine, Montreal

**Postscript I (Berlin) by Christophe Gallois (2013)** [.pdf]({{site.baseurl}}/assets/pdf/TrisVM-text-by-Christophe-Gallois-MUDAM-text.pdf)<br/>
Published in Newspaper Jan Mot | No. 89, okt 2013 and accompanied the
exhibition:<br/>
The Butterfly Image<br/>
23 March - 8 September 2013<br/>
Mudam, Luxembourg

**Tall Tales and Short Stories by Beatrix Ruf (2012)** [.pdf]({{site.baseurl}}/assets/pdf/TrisVM-essay-by-Beatrix-Ruf-for-Hugo-Boss-Prize-2012-catalogue.pdf)<br/>
Accompanied the Hugo Boss Prize 2012

**Nothing is more dubious than this sentence by Elena Filipovic (2009)** <!--[.pdf]({{site.baseurl}}/assets/pdf/TrisVM-Jeu-de-Paume-Paris.pdf)--><br/>
Accompanied the exhibition:<br/>
Finding Chopin: Endnotes, 2005–2009<br/>
20 October 2009 - 17 January 2010<br/>
Jeu de Paume, Paris

## Monographs

<ul>
    {% for post in site.categories.monographs %}
    {% if post.url %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>


## Monographs
<div class="popup-gallery">
  {% for image in page.monograph-3 %}
    <a href="{{ image.image_path }}"><img src="{{ image.image_path }}" alt="{{ image.title}}" width="200" height="134" /></a>
  {% endfor %}
</div>

## Publications

<div class="popup-gallery">
  {% for image in page.publications %}
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
