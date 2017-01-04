---
layout: project
title:  "Openbank"
subtitle: "Client iPhone and iPad app for Opebank"
banner: p_openbank.jpg
gallery:
 - image: openbank2
   size: 1024x768
   cols: 4u 6u(narrower)   
 - image: openbank1
   size: 1024x768
   cols: 4u 6u(narrower)
 - image: openbank4
   size: 1024x768
   cols: 4u 6u(narrower)
 - image: openbank5
   size: 1024x768
   cols: 4u 6u(narrower)   
 - image: openbank7
   size: 1024x768
   cols: 4u 12u(narrower)    
 - image: openbank8
   size: 1024x768
   cols: 4u 12u(narrower)    
 - image: openbank9
   size: 750x1334
   cols: 3u 12u(narrower)    
 - image: openbank10
   size: 750x1334
   cols: 3u 12u(narrower)    
 - image: openbank11
   size: 750x1334
   cols: 3u 12u(narrower)    
 - image: openbank12
   size: 750x1334
   cols: 3u 12u(narrower)    



---
###Description
This is the client app for Openbank, made together with [Bluemonk](http://www.bluemonk.es), who coded the communication with the backend server.

It has sections for accounts, cards, values, loans and so. It allows the user to make the normal banking operations. It's a big app and one that is going to be updated frequently, so I took extra care in making the architecture clean an solid.

<a href="https://geo.itunes.apple.com/es/app/openbank/id431241981?mt=8" style="display:inline-block;overflow:hidden;background:url(http://linkmaker.itunes.apple.com/images/badges/en-us/badge_appstore-lrg.svg) no-repeat;width:165px;height:40px;"></a>

###Video
<style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin-bottom: 30px;} .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='http://www.youtube.com/embed/RgZKyXP7pvE' frameborder='0' allowfullscreen></iframe></div>


###Screenshots
<div class="my-gallery" itemscope itemtype="http://schema.org/ImageGallery">
  <div class="picture row" itemscope itemtype="http://schema.org/ImageGallery">

    {% for image in page.gallery %}
      <figure class="{{ image.cols }}" itemprop="associatedMedia" itemscope itemtype="http://schema.org/ImageObject">
        <a href="projects/screenshots/openbank/{{ image.image }}.jpg" itemprop="contentUrl" data-size="{{ image.size }}" data-index="0">
          <img src="projects/screenshots/openbank/t_{{ image.image }}.jpg" itemprop="thumbnail">
        </a>
      </figure>
    {% endfor %}

  </div>
</div>
