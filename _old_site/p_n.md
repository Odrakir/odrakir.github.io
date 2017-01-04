---
layout: project
title:  "n"
subtitle: "by Jorge Drexler"
banner: p_n.jpg
gallery:
 - image: n1
   size: 852x639
   cols: 6u 6u(narrower)
 - image: n1_2
   size: 852x639
   cols: 6u 6u(narrower)
 - image: n2
   size: 852x639
   cols: 6u 6u(narrower)
 - image: n2_2
   size: 852x639
   cols: 6u 6u(narrower)
 - image: n3
   size: 852x639
   cols: 6u 6u(narrower)

---
###Description
This project was kind of an experiment. Three songs composed by Academy Awards winning singer-songwriter Jorge Drexler to enable the user to change the music as it plays. Each of the three songs were composed and recorded with the app in mind and each of them with a different mechanic.

This time I had to come up and design the interface for the three songs and developed versions in Adobe Flash so that Android and iOS programmers could base their work on.

####**n1 "Room 316"**
"Room 316" can be listened in english lets the user choose and change the lyrics as they play in an exercise of combinatory poetry.
<style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin-bottom: 30px;} .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='http://www.youtube.com/embed/EvxSWpFCFkM' frameborder='0' allowfullscreen></iframe></div>

####**n2 "Madera de deriva"**
"Madera de deriva" (driftwood) is a song about how life makes you drift and changes you. The app plays with the user location unlocking instruments of an orchestra as he travels.
<style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin-bottom: 30px;} .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='http://www.youtube.com/embed/p_bwFUBK--U' frameborder='0' allowfullscreen></iframe></div>

####**n3 "Décima a la décima"**
"Décima a la décima" (Décima to the power of ten) experiments with time and combinatory poetry inviting 9 other famous singers so the user can choose who sings the next phrase.
<style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin-bottom: 30px;} .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='http://www.youtube.com/embed/AO1pzr_KlkM' frameborder='0' allowfullscreen></iframe></div>

<a href="https://geo.itunes.apple.com/us/app/n-jorge-drexler/id589029116?mt=8" style="display:inline-block;overflow:hidden;background:url(http://linkmaker.itunes.apple.com/images/badges/en-us/badge_appstore-lrg.svg) no-repeat;width:165px;height:40px;"></a>
<a href="https://play.google.com/store/apps/details?id=com.drexlerlite">
  <img alt="Get it on Google Play"
       src="https://developer.android.com/images/brand/en_generic_rgb_wo_45.png" />
</a>

###Screenshots
<div class="my-gallery" itemscope itemtype="http://schema.org/ImageGallery">
  <div class="picture row" itemscope itemtype="http://schema.org/ImageGallery">

    {% for image in page.gallery %}
      <figure class="{{ image.cols }}" itemprop="associatedMedia" itemscope itemtype="http://schema.org/ImageObject">
        <a href="projects/screenshots/n/{{ image.image }}.png" itemprop="contentUrl" data-size="{{ image.size }}" data-index="0">
          <img src="projects/screenshots/n/t_{{ image.image }}.png" itemprop="thumbnail">
        </a>
      </figure>
    {% endfor %}

  </div>
</div>
