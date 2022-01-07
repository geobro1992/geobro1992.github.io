---
layout: default
permalink: /photos/
author_profile: true
images:
 - image path: /images/field/anolis.jpg
   title: anolis
- image path: /images/field/blackbird.JPG
   title: blackbird
- image path: /images/field/toad.jpg
   title: toad
- image path: /images/field/creek.jpg 
   title: creek
- image path: /images/field/elaphe.jpg 
   title: elaphe
- image path: /images/field/gastrophryne.jpg
   title: gastrophryne
- image path: /images/field/gator1.JPG
   title: gator
- image path: /images/field/hummingbird1.JPG
   title: hummingbird
- image path: /images/field/hyla1.jpg
   title: hyla
- image path: /images/field/pond.jpg
   title: pond
- image path: /images/field/iguana2.JPG
   title: iguana
- image path: /images/field/indigo.jpg
   title: indigo
- image path: /images/field/lizard.jpg
   title: lizard
- image path: /images/field/monkey.JPG
   title: monkey
- image path: /images/field/gator3.JPG
   title: gator
- image path: /images/field/nerodia.jpg
   title: nerodia
- image path: /images/field/newt.jpg
   title: newt
- image path: /images/field/pond2.JPG
   title: pond   
- image path: /images/field/tortoise.jpg
   title: tortoise
- image path: /images/field/vista.JPG
   title: vista
- image path: /images/field/volcano.JPG
   title: volcano
- image path: /images/field/worm.jpg
   title: worm
- image path: /images/field/basilisk.JPG
   title: basilisk
- image path: /images/field/gator2.JPG
   title: gator
- image path: /images/field/swamp.JPG
   title: swamp
- image path: /images/field/hummingbird2.JPG
   title: hummingbird
- image path: /images/field/hyla2.jpg
   title: hyla
- image path: /images/field/lizard2.jpg
   title: lizard
- image path: /images/field/turtle.jpg
   title: turtle
- image path: /images/BorrowedTime2.JPG
   title: iguana
---

<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>
