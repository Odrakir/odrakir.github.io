---
layout: project
title:  "Sincrolab"
subtitle: "Cognitive training"
banner: p_sincrolab.jpg
gallery:
 - image: sincrolab1
   size: 1024x768
   cols: 3u 6u(narrower)
 - image: sincrolab2
   size: 1024x768
   cols: 3u 6u(narrower)
 - image: sincrolab3
   size: 1024x768
   cols: 3u 6u(narrower)
 - image: sincrolab4
   size: 1024x768
   cols: 3u 6u(narrower)
 - image: sincrolab5
   size: 1024x768
   cols: 3u 6u(narrower)
 - image: sincrolab6
   size: 1024x768
   cols: 3u 6u(narrower)
 - image: sincrolab7
   size: 1024x768
   cols: 3u 6u(narrower)
 - image: sincrolab8
   size: 1024x768
   cols: 3u 6u(narrower)
 - image: sincrolab9
   size: 1024x768
   cols: 3u 6u(narrower)

---
###Description
This is an iPad app which has two very different faces depending on who logs in. For kids it shows three games, each one of them tailored to the specific need the child has in the field of cognitive training.

For tutors (parents or clinical professional) it provides the tools to setup and update those games, manage kid profiles and follow their evolution with global and personal graphs and statistics.

It's using **SpriteKit** for the games and the backend is made with parse.

<a href="https://geo.itunes.apple.com/es/app/sincrolab/id848202360?mt=8" style="display:inline-block;overflow:hidden;background:url(http://linkmaker.itunes.apple.com/images/badges/en-us/badge_appstore-lrg.svg) no-repeat;width:165px;height:40px;"></a>

###Screenshots
<div class="my-gallery" itemscope itemtype="http://schema.org/ImageGallery">
  <div class="picture row" itemscope itemtype="http://schema.org/ImageGallery">

    {% for image in page.gallery %}
      <figure class="{{ image.cols }}" itemprop="associatedMedia" itemscope itemtype="http://schema.org/ImageObject">
        <a href="projects/screenshots/sincrolab/{{ image.image }}.jpg" itemprop="contentUrl" data-size="{{ image.size }}" data-index="0">
          <img src="projects/screenshots/sincrolab/t_{{ image.image }}.jpg" itemprop="thumbnail">
        </a>
      </figure>
    {% endfor %}

  </div>
</div>
