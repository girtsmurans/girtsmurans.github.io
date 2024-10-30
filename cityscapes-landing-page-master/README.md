# CityScapes Landing Page
This is a free, fully responsive landing page that is easily customizable for a non web user. From the html, images can be readily changed. If you wish to tinker around with more things you can also change the variables in the SASS folder under 1-base folder, in the file named _variables.scss

Demo available in codepen: https://codepen.io/J_Enrique/pen/ypgvLN
<p><img class="grid-col-md-6" height="80px" src="img/R32w/1.png">a<p>
<p><img height="80px" src="img/R32w/2.png">a</p>
<p><img height="80px" src="img/R32w/3.png">a</p>
<p><img height="80px" src="img/R32w/4.png">a</p>
<p><img height="80px" src="img/R32w/5.png">a</p>
<p><img height="80px" src="img/R32w/6.png">a</p>
<p><img height="80px" src="img/R32w/7.png">a</p>
<p><img height="80px" src="img/R32w/8.png">a</p>
<p><img height="80px" src="img/R32w/9.png">a</p>
<p><img height="80px" src="img/R32w/10.png">a</p>
<p><img height="80px" src="img/R32w/11.png">a</p>






<!DOCTYPE html>
<html>
     <head>
          <!-- Required meta tags -->
          <meta charset="utf-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

          <!-- Title tag -->
          <title>One Page Responsive CityScapes Template</title>

          <!-- Font awesome -->
          <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">

          <!-- Animate.css -->
          <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.5.2/animate.min.css">

          <!-- Normalize -->
          <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/7.0.0/normalize.css">

          <!-- Custom CSS -->
          <link href="css/styles.css" rel="stylesheet">

          <style>
               /* If you wish to remove the astonish.js file, then also be sure to remove these styles. */
               .astonish {
                    visibility: visible;
               }

               @media (min-width: 768px) {
                    .astonish {
                         visibility: hidden;
                    }
                    .animated {
                         visibility: visible;
                    }
               }
          </style>
     </head>
     <body>
          <!-- Main Navigation -->
          <nav class="main-nav" id="main-nav">
               <div class="content-wrapper-sm">
                    <a href="#" class="navbar-brand"><img height="40px" src="img/logo2.png"></a>
                    <div id="menu-button">
                         <div class="bar1"></div>
                         <div class="bar2"></div>
                         <div class="bar3"></div>
                    </div>
                    <ul class="nav-links">
                         <li><a href="#about">About</a></li>
                         <li><a href="#reserve">Reservations</a></li>
                         <li><a href="#contact">Contact</a></li>
                    </ul>
               </div>
          </nav>

          <!-- Main header -->
          <header>
               <!-- First replaceble image -->
               <img class="img-absolute" src="img/room.png" alt="City 1">
               <div class="wrapper astonish animated fadeInDown">
                    <div class="grid-col-sm-12">
                         
                         <h1><strong>Gaisa</strong>Kondicionieri</h1>
                         <h2>Gaiss-Gaiss siltumsūkņi jūsu komfortam</h2>
                    </div>
               </div>
          </header>

          <!-- Main content -->

          <main>
               <div class="content-wrapper" id="about">
                    <!-- second replaceble image -->
                    <!-- <img class="img-absolute" src="img/city2.png" alt="City 2"> -->
                    
                    
                    <!-- THIS IS WHERE I NEED YOUR HELP -->
                    
                    <div class="features-container">
                         <div class="features">
                              <div class="feature"><img src="img/R32w/1.png"></div>
                              <div class="feature-text">AAAA</div>       
                         </div>
                    </div>

                    <!-- THIS IS WHERE IT ENDS -->







               </div>
               <div>

               </div>
               <div id="reserve" class="content-wrapper-lg text-center astonish" data-animation="zoomIn">
                    <h2 class="section-title"></h2>
                    <p>CityScapes is great for any travel agency or tour agency, that wishes to showcase the focal points of a city. If you want a unique looking landing page that has a unique artistic style that will attract clients, then this is the template for you. Go ahead and download it for free from Github.</p>
                    <a href="#" class="btn btn-outline-purple">Pieteikties</a>
               </div>

               <div class="content-wrapper" id="contact">
                    <!-- Third replaceble image -->
                    <img class="img-absolute" src="img/city3.png" alt="City 3">

          <!-- Main footer -->
          <footer>
               <div class="content-wrapper-sm display-flex-between">
                    <!-- Easily replaceble copyright information -->
                    <small>Your copyright 2017.</small>

                    <!-- Make sure to edit the links so that they go to your social media. -->
                    <div class="social-links">
                         <ul>
                              <li><a href="#"><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
                              <li><a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
                              <li><a href="#"><i class="fa fa-snapchat-square" aria-hidden="true"></i></a></li>
                              <li><a href="#"><i class="fa fa-instagram" aria-hidden="true"></i></a></li>
                         </ul>
                    </div>
               </div>
          </footer>

          <!-- Scripts placed at the bottom for faster loading -->
          <script src="https://code.jquery.com/jquery-3.2.1.min.js" integrity="sha256-hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4=" crossorigin="anonymous"></script>
          <script src="js/menu.js" charset="utf-8"></script>

          <!-- Optional js files -->
          <!-- Quick note: if you remove astonish, make sure you remove the embedded styles in the top -->
          <script src="js/astonish.js" charset="utf-8"></script>
          <script src="js/nav.js" charset="utf-8"></script>
          <script src="js/scroll.js" charset="utf-8"></script>
     </body>
</html>
