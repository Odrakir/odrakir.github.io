---
layout: project
title:  "The Circle of Health"
subtitle: "An app to prevent cardiovascular diseases."
banner: p_ecdls.jpg
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
 - image: ecdls1
   size: 1024x768
   cols: 6u 12u(narrower)   
 - image: ecdls2
   size: 1024x768
   cols: 6u 12u(narrower)
 - image: ecdls4
   size: 1024x768
   cols: 3u 12u(narrower)    
 - image: ecdls5
   size: 1024x768
   cols: 3u 12u(narrower)    
 - image: ecdls6
   size: 1024x768
   cols: 3u 12u(narrower)    
 - image: ecdls8
   size: 1024x768
   cols: 3u 12u(narrower)    
---
###Description
I made this app while working at [Wake App Health](http://www.wakeapphealth.com). My task was to develop an interface based on the concept of the "circle of health" in which your overall health is defined by six risk factors grouped in three main categories: Physical (Blood Pressure and Obesity), Chemical (Cholesterol and Diabetes), Behavioural (Smoking andSedentary Lifestyle). That's why a **circular interface** with non traditional navigation seemed appropiate.

The app also has other sections in which the user can take some test to check his health and also participate in challenges to improve those aspects of his health that could be better.

I designed the whole user experience and coded the iPad and iPhone versions using **Objective-C**, **Core Data** and some **OpenGL** for the background. I also provided the material and guidelines for the Android version

<a href="https://geo.itunes.apple.com/es/app/el-circulo-de-la-salud/id919441945?mt=8&uo=6" target="itunes_store" style="vertical-align:middle;display:inline-block;overflow:hidden;background:url(http://linkmaker.itunes.apple.com/images/badges/en-us/badge_appstore-lrg.png) no-repeat;width:165px;height:40px;@media only screen{background-image:url(http://linkmaker.itunes.apple.com/images/badges/en-us/badge_appstore-lrg.svg);}"></a>Spanish version

English version soon

###Video
<style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin-bottom: 30px;} .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='https://player.vimeo.com/video/115170543' frameborder='0' webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe></div>

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