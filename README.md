# fashionsite
simple fashion site


<!DOCTYPE html>
<html>
<head>
<title>shopping site</title>
<link rel="stylesheet" type="text/css" href="css/pro1.css">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">
<link rel="stylesheet" type="text/css" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>

</head>
<body>
	<!--navegation-bar-->
	<section id="navegation-bar">
		<nav class="navbar navbar-expand-lg navbar-light">
  <a class="navbar-brand" href="#"><img src="img/logo.png"></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item">
        <a class="nav-link" href="#">HOME</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="women.html">WOMEN</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="men.html">MEN</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="kids.html">KIDS</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="accessories.html">ACCESSORIES</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#promo">CONTACT</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="Login.php">LOGIN/SIGN IN</a>
      </li>
    </ul>
  </div>
</nav>
	</section>
	<!-- slider -->
	<div id="slider">
		<div id="headerSlider" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#headerSlider" data-slide-to="0" class="active"></li>
    <li data-target="#headerSlider" data-slide-to="1"></li>
    <li data-target="#headerSlider" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="img/girls.jpg" class="d-block img-fluid">
      <div class="carousel-caption">
        <h5 class="ontext">Shop What You Want....</h5>
      </div>
    </div>
    <div class="carousel-item">
      <img src="img/slide2.jpg" class="d-block img-fluid">
      <div class="carousel-caption">
        <h5 class="ontext">Visit Us....</h5>
      </div>
    </div>
    <div class="carousel-item">
      <img src="img/online3.jpg" class="d-block img-fluid">
      <div class="carousel-caption">
        <h5 class="ontext">Hey, Are You Ready....</h5>
      </div>
    </div>
  </div>
  <a class="carousel-control-prev" href="#headerSlider" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#headerSlider" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
	</div>
  <!---About----->
<section id="about">
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <h2>About Us</h2>
        <div class="about-content">
          Sri Lanka’s biggest fashion chain offers clothes and accessories for Men, Women and Children.If you are searching for the latest trends, comfort clothing, and style statements, you are at the right place because, we have a range of stylish accessories and apparels with a variety of colors, designs, fabrics and sizes to choose from. We have showrooms located in strategic towns and cities across the Island, in addition to our head office which is located in Kawdana Road, Dehiwela.
        </div>
        <button type="button" class="btn btn-primary" onclick="location.href='one.html'">Read More>></button>
      </div>
      <div class="col-md-6">
        <h1 style="font-size: 70px; text-align: center; padding: 70px;">D Fashion</h1>
    </div>
  </div>
</section>
<!---Services--->
<section id="Services">
  <div class="container">
    <h1>Our Services</h1>
    <div class="row Services">
      <div class="col-md-3 text-center">
        <div class="icon">
           <i class="fa fa-shopping-bag"></i>
        </div>
        <h3>Sri Lanka’s biggest fashion chain</h3>
        <p>Clothes and accessories for Men, Women and Children</p>
      </div>
      <div class="col-md-3 text-center">
        <div class="icon">
            <i class="fa fa-shopping-cart"></i>
        </div>
        <h3>Buy anything you want</h3>
        <p>What you love to buy,we are ready to serve you</p>
      </div>
      <div class="col-md-3 text-center">
        <div class="icon">
            <i class="fa fa-gift"></i>
        </div>
        <h3>Gift for you and your family</h3>
        <p>Enjoy life with our products</p>
      </div>
      <div class="col-md-3 text-center">
        <div class="icon">
            <i class="fa fa-credit-card"></i>
        </div>
        <h3>Pay esily & quickly</h3>
        <p>You can pay using credit,debit & visa cards</p>
      </div>
    </div>
  </div>
</section>
<!----- products------>
<section id="products">
<div class="container">
  <h1>Our Products</h1>
  <div class="row">
    <div class="col-md-3 profile-pic text-center">
      <div class="img-box"><a href="women.html">
        <img src="img/women.png" class="img-responsive">
        <ul>
          <a href="#"><li><i class="fa fa-facebook-square"></i></li></a>
          <a href="#"><li><i class="fa fa-twitter-square"></i></i></li></a>
          <a href="#"><li></i><i class="fa fa-instagram"></i></li></a>
        </ul>
      </div>
      <h3>Women wear</h3>
      <h5>blouse</h5>
      <h5>skirt</h5>
      <h5>trouser</h5>
      <h5>office wear</h5>
    </div>
    <div class="col-md-3 profile-pic text-center">
      <div class="img-box"><a href="men.html">
        <img src="img/ment.png" class="img-responsive">
        <ul>
          <a href="#"><li><i class="fa fa-facebook-square"></i></li></a>
          <a href="#"><li><i class="fa fa-twitter-square"></i></i></li></a>
          <a href="#"><li></i><i class="fa fa-instagram"></i></li></a>
        </ul>
      </div>
      <h3>Men wear</h3>
      <h5>Shirt</h5>
      <h5>T-shirt</h5>
      <h5>trouser</h5>
      <h5>office wear</h5>
    </div>
    <div class="col-md-3 profile-pic text-center">
      <div class="img-box"><a href="kids.html">
        <img src="img/kid.png" class="img-responsive">
        <ul>
          <a href="#"><li><i class="fa fa-facebook-square"></i></li></a>
          <a href="#"><li><i class="fa fa-twitter-square"></i></i></li></a>
          <a href="#"><li></i><i class="fa fa-instagram"></i></li></a>
        </ul>
      </div>
      <h3>Kids wear</h3>
      <h5>frocks</h5>
      <h5>t-shirts</h5>
      <h5>trouser</h5>
      <h5>shorts</h5>
    </div>
    <div class="col-md-3 profile-pic text-center">
      <div class="img-box"><a href="accessories.html">
        <img src="img/accessories.png" class="img-responsive">
        <ul>
          <a href="#"><li><i class="fa fa-facebook-square"></i></li></a>
          <a href="#"><li><i class="fa fa-twitter-square"></i></i></li></a>
          <a href="#"><li></i><i class="fa fa-instagram"></i></li></a>
        </ul>
      </div>
      <h3>Accessories</h3>
      <h5>hats</h5>
      <h5>sunglasses</h5>
      <h5>shoes</h5>
      <h5>bags</h5>
    </div>
  </div>
</div>
</section>
<!---Contact----->
<section id="promo">
  <div>
    <div class="container"> </div>
    <p>Do you have any suggestion or comment contact us.... </p>
    <a href="#" class="btn btn-primary" onclick="location.href='contact.html'">Contact Us</a>
  </div>
</section>
<!----footer------->
<section id="footer">
  <div class="container">
    <p align="center">Made with <i class="fa fa-heart-o"></i> by D Fashion</p>
    <p align="center">Copyright © 2020 - D Fashion - All Rights Reserved.</p>
    <p align="right">General Inquiry : +94 11 273 7441</p>
  </div>
</section>
</body>
</html>
