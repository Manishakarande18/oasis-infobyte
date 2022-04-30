# oasis-infobyte
oasis infobyte
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Complete Responsive Food / Restaurant Website Design Tutorial</title>

   <!-- font awesome cdn link  -->
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
   <link rel="stylesheet" href="https://unpkg.com/swiper@7/swiper-bundle.min.css" />
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lightgallery-js/1.4.0/css/lightgallery.min.css">

   <!-- custom css file link  -->
   <link rel="stylesheet" href="css/style.css">

</head>
<body>
   
<!-- header section starts     -->

<section class="header">

   <a href="#" class="logo"> <i class="fas fa-utensils"></i> food. </a>

   <nav class="navbar">
      <a href="#home">home</a>
      <a href="#about">about</a>
      <a href="#food">food</a>
      <a href="#gallery">gallery</a>
     
      <a href="#order">order</a>
      <a href="#blogs">blogs</a>
   </nav>

   <div id="menu-btn" class="fas fa-bars"></div>

</section>

<!-- header section ends    -->

<!-- home section starts  -->

<section class="home" id="home">

   <div class="swiper home-slider">

      <div class="swiper-wrapper">

         <div class="swiper-slide slide" style="background: url(images/home-slide-1.jpg) no-repeat;">
            <div class="content">
               <span>outstanding food</span>
               <h3>Wishful cooking</h3>
               <a href="#" class="btn">get started</a>
            </div>
         </div>

         <div class="swiper-slide slide" style="background: url(images/home-slide-2.jpg) no-repeat;">
            <div class="content">
               <span>outstanding food</span>
               <h3>morning moment</h3>
               <a href="#" class="btn">get started</a>
            </div>
         </div>

         <div class="swiper-slide slide" style="background: url(images/home-slide-3.jpg) no-repeat;">
            <div class="content">
               <span>outstanding food</span>
               <h3>delicious cooking</h3>
               <a href="#" class="btn">get started</a>
            </div>
         </div>

      </div>

      <div class="swiper-button-next"></div>
      <div class="swiper-button-prev"></div>

   </div>

</section>

<!-- home section ends -->

<!-- about section starts  -->

<section class="about" id="about">

   <div class="image">
      <img src="images/about-img.png" alt="">
   </div>

   <div class="content">
      <h3 class="title">welcome to our restaurant</h3>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi optio at, saepe accusamus dolorum, quos eos nesciunt amet exercitationem illum quis nostrum, repellat quaerat eum debitis fugit alias magnam omnis!</p>
      <a href="#" class="btn">read more</a>
      <div class="icons-container">
         <div class="icons">
            <img src="images/about-icon-1.png" alt="">
            <h3>quality food</h3>
         </div>
         <div class="icons">
            <img src="images/about-icon-2.png" alt="">
            <h3>food & drinks</h3>
         </div>
         <div class="icons">
            <img src="images/about-icon-3.png" alt="">
            <h3>expert chefs</h3>
         </div>
      </div>
   </div>

</section>

<!-- about section ends -->

<!-- food section starts  -->

<section class="food" id="food">

   <div class="heading">  
      <span>popular dishes</span>
      <h3>our delicious food</h3>
   </div>

   <div class="swiper food-slider">

      <div class="swiper-wrapper">

         <div class="swiper-slide slide" data-name="food-1">
            <img src="images/food-img-1.png" alt="">
            <h3>delicious food</h3>
            <div class="price">$49.99</div>
         </div>

         <div class="swiper-slide slide" data-name="food-2">
            <img src="images/food-img-2.png" alt="">
            <h3>delicious food</h3>
            <div class="price">$49.99</div>
         </div>

         <div class="swiper-slide slide" data-name="food-3">
            <img src="images/food-img-3.png" alt="">
            <h3>delicious food</h3>
            <div class="price">$49.99</div>
         </div>

         <div class="swiper-slide slide" data-name="food-4">
            <img src="images/food-img-4.png" alt="">
            <h3>delicious food</h3>
            <div class="price">$49.99</div>
         </div>

         <div class="swiper-slide slide" data-name="food-5">
            <img src="images/food-img-5.png" alt="">
            <h3>delicious food</h3>
            <div class="price">$49.99</div>
         </div>

      </div>

      <div class="swiper-pagination"></div>

   </div>

</section>

<!-- food section ends -->

<!-- food preview section starts  -->

<section class="food-preview-container">

   <div id="close-preview" class="fas fa-times"></div>

   <div class="food-preview" data-target="food-1">
      <img src="images/food-img-1.png" alt="">
      <h3>delicious food</h3>
      <div class="stars">
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
      </div>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, hic!</p>
      <div class="price">$49.99</div>
      <a href="#" class="btn">buy now</a>
   </div>

   <div class="food-preview" data-target="food-2">
      <img src="images/food-img-2.png" alt="">
      <h3>delicious food</h3>
      <div class="stars">
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
      </div>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, hic!</p>
      <div class="price">$49.99</div>
      <a href="#" class="btn">buy now</a>
   </div>

   <div class="food-preview" data-target="food-3">
      <img src="images/food-img-3.png" alt="">
      <h3>delicious food</h3>
      <div class="stars">
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
      </div>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, hic!</p>
      <div class="price">$49.99</div>
      <a href="#" class="btn">buy now</a>
   </div>

   <div class="food-preview" data-target="food-4">
      <img src="images/food-img-4.png" alt="">
      <h3>delicious food</h3>
      <div class="stars">
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
      </div>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, hic!</p>
      <div class="price">$49.99</div>
      <a href="#" class="btn">buy now</a>
   </div>

   <div class="food-preview" data-target="food-5">
      <img src="images/food-img-5.png" alt="">
      <h3>delicious food</h3>
      <div class="stars">
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
      </div>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, hic!</p>
      <div class="price">$49.99</div>
      <a href="#" class="btn">buy now</a>
   </div>

</section>

<!-- food preview section ends -->

<!-- gallery section starts  -->

<section class="gallery" id="gallery">

   <div class="heading">
      <span>our gallery</span>
      <h3>our untold stories</h3>
   </div>

   <div class="gallery-container">

      <a href="images/food-galler-img-1.jpg" class="box">
         <img src="images/food-galler-img-1.jpg" alt="">
         <div class="icon"> <i class="fas fa-plus"></i> </div>
      </a>

      <a href="images/food-galler-img-2.jpg" class="box">
         <img src="images/food-galler-img-2.jpg" alt="">
         <div class="icon"> <i class="fas fa-plus"></i> </div>
      </a>

      <a href="images/food-galler-img-3.jpg" class="box">
         <img src="images/food-galler-img-3.jpg" alt="">
         <div class="icon"> <i class="fas fa-plus"></i> </div>
      </a>

      
      

   </div>

</section>




<!-- blogs section ends -->

<!-- footer section starts  -->

<section class="footer">

   <div class="icons-container">

      <div class="icons">
         <i class="fas fa-clock"></i>
         <h3>opening hours</h3>
         <p>07:00am to 10:00pm</p>
      </div>

      <div class="icons">
         <i class="fas fa-phone"></i>
         <h3>phone</h3>
         <p>9373767565</p>
         <p>9847567388</p>
      </div>

      <div class="icons">
         <i class="fas fa-envelope"></i>
         <h3>email</h3>
         <p>mohinigoykar76@gmail.com</p>
         <p>goykarmohini7@gmail.com</p>
      </div>

      <div class="icons">
         <i class="fas fa-map"></i>
         <h3>address</h3>
         <p>baramati, india - 400104</p>
      </div>

   </div>

   <div class="share">
      <a href="#" class="fab fa-facebook-f"></a>
      <a href="#" class="fab fa-twitter"></a>
      <a href="#" class="fab fa-instagram"></a>
      <a href="#" class="fab fa-linkedin"></a>
   </div>

   <div class="credit"> created by <span>ms. web designer</span> | all rights reserved! </div>

</section>

<!-- footer section ends  -->










<script src="https://unpkg.com/swiper@7/swiper-bundle.min.js"></script>

<script src="https://cdnjs.cloudflare.com/ajax/libs/lightgallery-js/1.4.0/js/lightgallery.min.js"></script>

<!-- custom js file link  -->
<script src="js/script.js"></script>

<script>
   lightGallery(document.querySelector('.gallery .gallery-container'));
</script>

</body>
</html>
