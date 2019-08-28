# jQueryCarousel
Simple jQuery Carousel (slider) made by [Sofiia Teplova](https://github.com/stplva)  
You can use it in your personal projects!
     
## Usage  
1. Set up your HTML markup:  
```
<div class="carousel">
      <div class="carousel-arrow carousel-arrow-prev"><i class="fas fa-chevron-left"></i></div>
      <div class="carousel-hider">
        <ul class="carousel-ul">
          <li class="carousel-li">
            <img src="path/to/your/img">
            <p class="carousel-description">Your description</p>
          </li>
          <li class="carousel-li">
            <img src="path/to/your/img">
            <p class="carousel-description">Your description</p>
          </li>
          <li class="carousel-li">
            <img src="path/to/your/img">
            <p class="carousel-description">Your description</p>
          </li>
        </ul>
      </div>
      <div class="carousel-arrow carousel-arrow-next"><i class="fas fa-chevron-right"></i></div>
</div>
```  
2. Move the jquery.carousel files into your project (jquery.carousel.js and jquery.carousel.css).
3. Install [FontAwesome](https://fontawesome.com/?from=io).
4. Add **jquery.carousel.css** in your \<head>.  
```
<link rel="stylesheet" type="text/css" href="path/to/jquery.carousel.css"/>
```
5. Add **jquery.carousel.js** before your closing \</body> tag, after jQuery.  
```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script> 
<script type="text/javascript" src="path/to/jquery.carousel.js"></script>
```
6. Initialize your carousel in your script file or as an inline script tag  
```
$('.carousel').carousel();
```
7. You are all set up!
