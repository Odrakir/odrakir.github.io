---
layout: project
title:  "Sincrolab"
subtitle: "Cognitive training"
banner: p_sincrolab.jpg
gallery:
 - image: ecdls10
   size: 375x667
   cols: 3u 6u(narrower)
 - image: ecdls11
   size: 375x667
   cols: 3u 6u(narrower)   
 - image: ecdls12
   size: 375x667
   cols: 3u 6u(narrower)      
 - image: ecdls13
   size: 375x667
   cols: 3u 6u(narrower)
   
---
###Description
n bla bla bla

###Videos
<style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin-bottom: 30px;} .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='http://www.youtube.com/embed/EvxSWpFCFkM' frameborder='0' allowfullscreen></iframe></div>

###Screenshots
<div class="my-gallery" itemscope itemtype="http://schema.org/ImageGallery">
  <div class="picture row" itemscope itemtype="http://schema.org/ImageGallery">
                  
    {% for image in page.gallery %}
      <figure class="{{ image.cols }}" itemprop="associatedMedia" itemscope itemtype="http://schema.org/ImageObject">
        <a href="projects/screenshots/{{ image.image }}.jpg" itemprop="contentUrl" data-size="{{ image.size }}" data-index="0">
          <img src="projects/screenshots/t_{{ image.image }}.jpg" itemprop="thumbnail">
        </a>
      </figure>
    {% endfor %}

  </div>
</div>

