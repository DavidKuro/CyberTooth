
<!DOCTYPE html>
<html lang="en">
    
    <head>
        {% block head_title%} Adeda {% endblock%}
        {% block extra_head %} {% endblock%}
    
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="Adeda offers quality sneaker brand in Africa, that sells quality sneaker to its customers directly from the manufacturer">
    <meta name="author" content="David Oyinkuro Zipamone also Known as David Oz">
    <link rel="icon" type="image/png" href="{% static 'img/fav-icon.png'%}">
    <link href="{% static 'vendor/bootstrap/css/bootstrap.min.css'%}" rel="stylesheet">
    <link rel="stylesheet" href="{% static 'vendor/slider/slider.css' %}">
    <link href="{% static 'vendor/select2/css/select2-bootstrap.css' %}"/>
    <link href="{% static 'vendor/select2/css/select2.min.css' %}" rel="stylesheet" />
    <link href="{% static 'vendor/fontawesome/css/all.min.css' %}" rel="stylesheet">
    <link href="{% static 'vendor/icofont/icofont.min.css' %} " rel="stylesheet">
    <link href="{% static 'css/style.css'%}" rel="stylesheet"/>    
    <link rel="stylesheet" href="{% static 'vendor/owl-carousel/owl.carousel.css' %}">
    <link rel="stylesheet" href="{% static 'vendor/owl-carousel/owl.theme.css' %}">
    </head>

    
    <body>
    <div class="btn-primary pt-2 pb-2">
    <div class="container-fluid">
    <div class="row">
    <div class="col-lg-12 text-center">
    <a href="#" class="mb-0 text-white">
    40% CASHBACK FOR NEW USERS | <strong><span class="text-light"> ADEDA<span class="mdi mdi-tag-faces"></span></span> </strong>
    </a>
    </div>
    </div>
    </div>
    </div>
    <div class="modal fade login-modal-main" id="login">
    <div class="modal-dialog modal-lg modal-dialog-centered" role="document">
    <div class="modal-content">
    <div class="modal-body">
    <div class="login-modal">
    <div class="row">
    <div class="col-lg-6 d-flex align-items-center">
    <div class="login-modal-left p-4 text-center pl-5">
    <img src="{% static 'img/login.jpg' %}" alt="Adeda">
    </div>
    </div>
    </div>

    <div class="col-lg-6">
    <button type="button" class="close close-top-right position-absolute" data-dismiss="modal" aria-label="Close">
    <span aria-hidden="true"><i class="icofont-close-line"></i></span>
    <span class="sr-only">Close</span>
    </button>
    

     <!-----------------------------------------------------this is a form---------------------------------->
    <form class="position-relative">
    <ul class="mt-4 mr-4 nav nav-tabs-login float-right position-absolute" role="tablist">
    <li>
    <a class="nav-link-login active" data-toggle="tab" href="{% url 'london:login' %}" role="tab"><i class="icofont-ui-lock"></i> LOGIN</a>
    </li>
    <li>
    <a class="nav-link-login" data-toggle="tab" href="{% url 'london:register' %}" role="tab"><i class="icofont icofont-pencil"></i> REGISTER</a>
    </li>
    </ul>

    <div class="login-modal-right p-4">
    
    <div class="tab-content">
    <div class="tab-pane active" id="login-form" role="tabpanel">
    <h5 class="heading-design-h5 text-dark">LOGIN</h5>
    <fieldset class="form-group mt-4">
    <label>Enter Email/Mobile number</label>
    <input type="text" class="form-control" placeholder="+234-708-690-8085">
    </fieldset>
    <fieldset class="form-group">
     <label>Enter Password</label>
    <input type="password" class="form-control" placeholder="********">
    </fieldset>
    <fieldset class="form-group">
    <button type="submit" class="btn btn-lg btn-primary btn-block">Enter to your
    account</button>
    </fieldset>
    <div class="custom-control custom-checkbox">
    <input type="checkbox" class="custom-control-input" id="customCheck1">
    <label class="custom-control-label" for="customCheck1">Remember me</label>
    </div>
    <div class="login-with-sites mt-4">
    <p class="mb-2">or Login with your social profile:</p>
    <div class="row text-center">
    <div class="col-6 pr-1">
    <button class="btn-facebook btn-block login-icons btn-lg"><i class="icofont icofont-facebook"></i> Facebook</button>
    </div>
    <div class="col-6 pl-1">
    <button class="btn-google btn-block login-icons btn-lg"><i class="icofont icofont-google-plus"></i> Google</button>
    </div>
    </div>
    </div>
    </div>
    <div class="tab-pane" id="register" role="tabpanel">
    <h5 class="heading-design-h5 text-dark">REGISTER</h5>
    <fieldset class="form-group mt-4">
    <label>Enter Email/Mobile number</label>
    <input type="text" class="form-control" placeholder="+234-708-690-8085">
    </fieldset>
    <fieldset class="form-group">
    <label>Enter Password</label>
    <input type="password" class="form-control" placeholder="********">
    </fieldset>
    <fieldset class="form-group">
    <label>Enter Confirm Password </label>
    <input type="password" class="form-control" placeholder="********">
    </fieldset>
    <fieldset class="form-group">
    <button type="submit" class="btn btn-lg btn-primary btn-block">Create Your Account</button>
    </fieldset>
    <div class="custom-control custom-checkbox">
    <input type="checkbox" class="custom-control-input" id="customCheck2">
    <label class="custom-control-label" for="">I Agree with <a href="#">Term and Conditions</a></label>
    </div>
    <div class="login-with-sites mt-4">
    <p class="mb-2">or Login with your social profile:</p>
    <div class="row text-center">
    <div class="col-6 pr-1">
    <button class="btn-facebook btn-block login-icons btn-lg"><i class="icofont icofont-facebook"></i> Facebook</button>
    </div>
    <div class="col-6 pl-1">
    <button class="btn-google btn-block login-icons btn-lg"><i class="icofont icofont-google-plus"></i> Google</button>
    </div>
    </div>
    </div>
    </div>
    </div>
    </div>
    </form>
    </div>
    </div>
    </div>
    </div>
    </div>
    </div>
</div>
    <!-----------------------------------------------END OF Form---------------------------------->
    <div class="bg-light">
    <div class="header-top border-bottom bg-white">
    <div class="container">
    <div class="row">
    <div class="col-lg-12">
    <ul class="list-inline float-right mb-0">
    <li class="list-inline-item border-right border-left py-1 pr-2 mr-2 pl-2">
    <a href="#"><i class="icofont icofont-iphone"></i> +234-708-690-8085</a>
    </li>
    <li class="list-inline-item border-right py-1 pr-2 mr-2">
    <a href="{% url 'london:contact' %}"><i class="icofont icofont-headphone-alt"></i> Contact Us</a>
    </li>
    <li class="list-inline-item">
    </ul>
    <p class="mb-0 py-1"> <span class="text-danger font-weight-bold"></span></p>
    </div>
    </div>
    </div>
    </div>
    
    
    <!----------------------------------------------NAVIGATION BAR STARTS HERE------------------------>
    <div class="main-nav shadow-sm">
    <nav class="navbar navbar-expand-lg navbar-light bg-white pt-0 pb-0">
    <div class="container">
    <a class="navbar-brand" href="{% url 'london:index' %}">
    <img src="{% static 'img/logo.png'%}" alt="Adeda">
    </a>

    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupporte0dContent" 
    aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto main-nav-left">
    <li class="nav-item">
    <a class="nav-link" href="{% url 'london:index' %}"><i class="icofont-ui-home"></i></a>
    </li>
    <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
        WOMEN
        </a>
        <div class="dropdown-menu dropdown-menu-right shadow-sm border-0">
        <a class="dropdown-item" href="{% url 'london:product_grid' %}">Customised sneaker</a>
        <a class="dropdown-item" href="{% url 'london:product_grid' %}">Brands</a>
        <a class="dropdown-item" href="{% url 'london:product_grid' %}">Most Ordered</a>
        <a class="dropdown-item" href="{% url 'london:product_grid' %}">Footwear</a>
        <a class="dropdown-item" href="{% url 'london:product_grid' %}">Sneaker for girls</a>
        <a class="dropdown-item" href="{% url 'london:product_grid' %}">Sport shoes</a>
        </div>
        </li>
<!--------------------------------------------------------------This is an improvement-------------------------->
    <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
        MEN
        </a>
        <div class="dropdown-menu dropdown-menu-right shadow-sm border-0">
        <a class="dropdown-item" href="{% url 'london:product_grid' %}">Customised sneaker</a>
        <a class="dropdown-item" href="{% url 'london:product_grid' %}">Brands</a>
        <a class="dropdown-item" href="{% url 'london:product_grid' %}">Most Ordered</a>
        <a class="dropdown-item" href="{% url 'london:product_grid' %}">Footwear</a>
        <a class="dropdown-item" href="{% url 'london:product_grid' %}">Sneaker for Men</a>
        <a class="dropdown-item" href="{% url 'london:product_grid' %}">Sport shoes</a>
        </div>
        </li>
    <li class="nav-item">
    <a class="nav-link" href="{% url 'london:product_grid' %}">SALE</a>
    </li>
    <li class="nav-item dropdown">
    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    PAGES
    </a>
    <div class="dropdown-menu dropdown-menu-right shadow-sm border-0">
    <a class="dropdown-item" href="{% url 'london:product_grid' %}">Product List</a>
    <a class="dropdown-item" href="{% url 'london:product_detail' %}">Product Detail</a>
    <a class="dropdown-item" href="{% url 'london:checkout' %}">Checkout</a>
    <a class="dropdown-item" href="{% url 'london:profile' %}">My Account</a>
    <a class="dropdown-item" href="{% url 'london:contact' %}">Contact Us</a>
    </div>
    </li>
    </ul>
    <form class="form-inline my-2 my-lg-0 top-search">
    <button class="btn-link" type="submit"><i class="icofont-search"></i></button>
    <input class="form-control mr-sm-2" type="search" placeholder="Search for products, brands and more" aria-label="Search">
    </form>
    <ul class="navbar-nav ml-auto profile-nav-right">
    <li class="nav-item">
    <a href="{% url 'london:product_grid' %}" data-target="#login" data-toggle="modal" class="nav-link ml-0">
    <i class="icofont-ui-user"></i> Login/Sign Up
    </a>
    </li>
    <li class="nav-item cart-nav">
    <a data-toggle="offcanvas" class="nav-link" href="#">
    <i class="icofont-basket"></i> Cart
    <span class="badge badge-danger">5</span>
    </a>
    </li>
    </ul>
    </div>
    </div>
    </nav>
    
    </div>
    <div class="py-0">
    <div class="container-fluid">
    <div class="row">
    <div class="col-lg-12 px-0">
    <header>
    <div id="owl-carousel-one" class="owl-carousel">
    <div class="item"><img class="img-fluid mx-auto" src="{% static 'img/banner/1.jpg' %}"></div>
    <div class="item"><img class="img-fluid mx-auto" src="{% static 'img/banner/2.jpg' %}"></div>
    <div class="item"><img class="img-fluid mx-auto" src="{% static 'img/banner/3.jpg' %}">
    <div class="item"><img class="img-fluid mx-auto" src="{% static 'img/banner/4.jpg' %}">
    </div+>
    </header++>
    </div>
    </div>
    </div>
    </div>
    </div>

    {% comment %} <section class="py-5 d-none">
    <div class="container">
    <div class="row">
    <div class="col-4">
    </div>
    </div>
    </section>
    {% endcomment %}

    <section class="product-list pbc-5 pb-4 pt-5 bg-light">
    <div class="container">
    <h6 class="mt-1 mb-0 float-right"><a href="#">View All Items</a></h6>
    <h4 class="mt-0 mb-3 text-dark font-weight-normel">Best Selling Items</h4>
    <div class="row">
    <div class="col-6 col-md-3">
    <div class="card list-item bg-white rounded overflow-hidden position-relative shadow-sm">
    <span class="like-icon"><a href="#"> <i class="icofont icofont-heart"></i></a></span>
    <a href="#">
    <span class="badge badge-danger">NEW</span>
    <img src="{% static 'img/item/1.jpg' %}" class="card-img-top" alt="..."></a>
    <div class="card-body">
    <h6 class="card-title mb-1">Adidas</h6>
    <div class="stars-rating">
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star"></i> 
        <!--<span>613</span>-->
    </div>
    <p class="mb-0 text-dark">&#8358 25000.00 <span class="text-black-50"><del>&#8358 35000.00 </del></span></p>
    </div>
    </div>
    </div>


    <div class="col-6 col-md-3">
    <div class="card list-item bg-white rounded overflow-hidden position-relative shadow-sm">
    <span class="like-icon"><a href="#"> <i class="icofont icofont-heart"></i></a></span>
    <a href="#">
    <span class="badge badge-success">50% OFF</span>
    <img src="{% static 'img/item/2.jpg' %}" class="card-img-top" alt="..."></a>
    <div class="card-body">
    <h6 class="card-title mb-1">Prada</h6>
    <div class="stars-rating">
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star"></i> <span>613</span>
    </div>
    <p class="mb-0 text-dark">&#8358 25000.00 <span class="text-black-50">
        <del>&#8358 50000.00 </del>
    </span> 
    <span class="bg-danger  rounded-sm pl-1 ml-1 pr-1 text-white small"> 50% OFF</span>
    </p>
    </div>
    </div>
    </div>


    <div class="col-6 col-md-3">
    <div class="card list-item bg-white rounded overflow-hidden position-relative shadow-sm">
    <span class="like-icon"><a class="active" href="#"> <i class="icofont icofont-heart"></i></a></span>
    <a href="#">
    <span class="badge badge-danger">NEW</span>
    <img src="{% static 'img/item/3.jpg' %}" class="card-img-top" alt="..."></a>
    <div class="card-body">
    <h6 class="card-title mb-1">Gucci</h6>
    <div class="stars-rating"><i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star"></i> <span>613</span>
    </div>
    <p class="mb-0 text-dark">&#8358 25000.00 <span class="text-black-50"><del>&#8358 50000.00 </del></span> 
        <span class="bg-info rounded-sm pl-1 ml-1 pr-1 text-white small"> 50% OFF</span></p>
    </div>
    </div>
    </div>


    <div class="col-6 col-md-3">
    <div class="card list-item bg-white rounded overflow-hidden position-relative shadow-sm">
    <span class="like-icon"><a href="#"> <i class="icofont icofont-heart"></i></a></span>
    <a href="#">
    <span class="badge badge-success">50% OFF</span>
    <img src="{% static 'img/item/4.jpg'%}" class="card-img-top" alt="..."></a>
    <div class="card-body">
    <h6 class="card-title mb-1">Sketchers</h6>
    <div class="stars-rating"><i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i><i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i><i class="icofont icofont-star"></i> <span>613</span>
    </div>
    <p class="mb-0 text-dark">&#8358 25000.00 <span class="text-black-50"><del>&#8358 50000.00 </del></span></p>
    </div>
    </div>
    </div>


    <div class="col-6 col-md-3">
    <div class="card list-item bg-white rounded overflow-hidden position-relative shadow-sm">
    <a href="#">
    <span class="badge badge-danger">NEW</span>
    <img src="{% static 'img/item/5.jpg' %} " class="card-img-top" alt="..."></a>
    <div class="card-body">
    <h6 class="card-title mb-1">Sketchers</h6>
    <div class="stars-rating"><i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i><i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i><i class="icofont icofont-star"></i> <span>613</span>
    </div>
    <p class="mb-0 text-dark">&#8358 25000.00 <span class="text-black-50"><del>&#8358 50000.00 </del></span></p>
    </div>
    </div>
    </div>


    <div class="col-6 col-md-3">
    <div class="card list-item bg-white rounded overflow-hidden position-relative shadow-sm">
    <span class="like-icon"><a class="active" href="#"> <i class="icofont icofont-heart"></i></a></span>
    <a href="#">
    <span class="badge badge-success">50% OFF</span>
    <img src="{% static 'img/item/6.jpg' %}" class="card-img-top" alt="..."></a>
    <div class="card-body">
    <h6 class="card-title mb-1">Charks</h6>
    <div class="stars-rating"><i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i><i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i><i class="icofont icofont-star"></i> <span>613</span>
    </div>
    <p class="mb-0 text-dark">&#8358 25000.00 <span class="text-black-50"><del>&#8358 50000.00 </del></span></p>
    </div>
    </div>
    </div>


    <div class="col-6 col-md-3">
    <div class="card list-item bg-white rounded overflow-hidden position-relative shadow-sm">
    <span class="like-icon"><a href="#"> <i class="icofont icofont-heart"></i></a></span>
    <a href="#">
    <span class="badge badge-danger">NEW</span>
    <img src="{% static 'img/item/7.jpg'%}" class="card-img-top" alt="..."></a>
    <div class="card-body">
    <h6 class="card-title mb-1">Nike</h6>
    <div class="stars-rating"><i class="icofont icofont-star active"></i><i class="icofont icofont-star active"></i><i class="icofont icofont-star active"></i><i class="icofont icofont-star active"></i><i class="icofont icofont-star"></i> <span>613</span>
    </div>
    <p class="mb-0 text-dark">&#8358 25000.00 <span class="text-black-50"><del>&#8358 35000.00 </del></span></p>
    </div>
    </div>
    </div>

    
    <div class="col-6 col-md-3">
    <div class="card list-item bg-white rounded overflow-hidden position-relative shadow-sm">
    <span class="like-icon"><a href="#"> <i class="icofont icofont-heart"></i></a></span>
    <a href="#">
    <span class="badge badge-success">50% OFF</span>
    <img src="{% static 'img/item/8.jpg' %}" class="card-img-top" alt="..."></a>
    <div class="card-body">
    <h6 class="card-title mb-1">Puma</h6>
    <div class="stars-rating">
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star"></i> <span>613</span>
    </div>
    <p class="mb-0 text-dark">&#8358 25000.00 <span class="text-black-50"><del>&#8358 35000.00 </del></span></p>
    </div>
    </div>
    </div>
    </div>
    </div>
    </div>
    </section>

    <section class="offer-product py-5">
    <div class="container">
    <div class="row">
    <div class="col-6">
        <!---This is for the image on the base/footer-->
    <div class="offers-block"><a href="#"><img class="img-fluid" src="{% static 'img/ad/3.jpg' %}" alt=""></a></div>
    </div>
    <div class="col-6">
    <div class="offers-block"><a href="#"><img class="img-fluid" src="{% static 'img/ad/8.jpg' %}" alt=""></a></div>
    </div>
    </div>
    </div>
    </section>


    <section class="product-list pbc-5 pb-4 pt-5 bg-light">
    <div class="container">
    <h6 class="mt-1 mb-0 float-right"><a href="#">View All Items</a></h6>
    <h4 class="mt-0 mb-3 text-dark">Top Savers Today</h4>
    <div class="row">
    <div class="col-md-12">
    <div class="owl-carousel owl-carousel-category owl-theme">
    <div class="item">
    <div class="card list-item bg-white rounded overflow-hidden position-relative shadow-sm">
    <span class="like-icon"><a href="#"> <i class="icofont icofont-heart"></i></a></span>
    <a href="#">
    <span class="badge badge-danger">NEW</span>
    <img src="{% static 'img/item/1.jpg'%}" class="card-img-top" alt="..."></a>
    <div class="card-body">
    <h6 class="card-title mb-1">Gucci</h6>
    <div class="stars-rating"><i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star"></i>
    <span>613</span></div>
    <p class="mb-0 text-dark">&#8358 25000.00 <span class="text-black-50"><del>&#8358 35000.00 </del></span>
    <span class="bg-danger  rounded-sm pl-1 ml-1 pr-1 text-white small"> 50% OFF</span></p>
    </div>
    </div>
    </div>


    <div class="item">
    <div class="card list-item bg-white rounded overflow-hidden position-relative shadow-sm">
    <span class="like-icon"><a href="#"> <i class="icofont icofont-heart"></i></a></span>
    <a href="#">
    <span class="badge badge-success">50% OFF</span>
    <img src="{% static 'img/item/2.jpg'%}" class="card-img-top" alt="..."></a>
    <div class="card-body">
    <h6 class="card-title mb-1">New Balance</h6>
    <div class="stars-rating">
        <i class="icofont icofont-star active"></i
            ><i class="icofont icofont-star active"></i>
            <i class="icofont icofont-star active"></i>
            <i class="icofont icofont-star active"></i>
            <i class="icofont icofont-star"></i>
    <span>613</span></div>
    <p class="mb-0 text-dark">&#8358 25000.00 <span class="text-black-50"><del>&#8358 35000.00 </del></span></p>
    </div>
    </div>
    </div>


    <div class="item">
    <div class="card list-item bg-white rounded overflow-hidden position-relative shadow-sm">
    <span class="like-icon"><a class="active" href="#"> <i class="icofont icofont-heart"></i></a></span>
    <a href="#">
    <span class="badge badge-danger">NEW</span>
    <img src="{% static 'img/item/3.jpg' %}" class="card-img-top" alt="..."></a>
    <div class="card-body">
    <h6 class="card-title mb-1">Prada</h6>
    <div class="stars-rating">
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star"></i>
    <span>613</span></div>
    <p class="mb-0 text-dark">&#8358 25000.00 <span class="text-black-50"><del>&#8358 35000.00 </del></span></p>
    </div>
    </div>
    </div>


    <div class="item">
    <div class="card list-item bg-white rounded overflow-hidden position-relative shadow-sm">
    <span class="like-icon"><a href="#"> <i class="icofont icofont-heart"></i></a></span>
    <a href="#">
    <span class="badge badge-success">50% OFF</span>
    <img src="{% static 'img/item/4.jpg' %}" class="card-img-top" alt="..."></a>
    <div class="card-body">
    <h6 class="card-title mb-1">Charks</h6>
    <div class="stars-rating">
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star"></i>
    <span>613</span></div>
    <p class="mb-0 text-dark">&#8358 25000.00 <span class="text-black-50"><del>&#8358 35000.00</del></span></p>
    </div>
    </div>
    </div>


    <div class="item">
    <div class="card list-item bg-white rounded overflow-hidden position-relative shadow-sm">
    <span class="like-icon"><a href="#"> <i class="icofont icofont-heart"></i></a></span>
    <a href="#">
    <span class="badge badge-danger">NEW</span>
    <img src="{% static 'img/item/5.jpg' %} " class="card-img-top" alt="..."></a>
    <div class="card-body">
    <h6 class="card-title mb-1">Prada</h6>
    <div class="stars-rating">
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star"></i>
    <span>613</span></div>
    <p class="mb-0 text-dark">&#8358 25000.00<span class="text-black-50"><del>&#8358 35000.00 </del></span></p>
    </div>
    </div>
    </div>


    <div class="item">
    <div class="card list-item bg-white rounded overflow-hidden position-relative shadow-sm">
    <span class="like-icon"><a href="#"> <i class="icofont icofont-heart"></i></a></span>
    <a href="#">
    <span class="badge badge-success">50% OFF</span>
    <img src="{% static 'img/item/6.jpg'%}" class="card-img-top" alt="..."></a>
    <div class="card-body">
    <h6 class="card-title mb-1">Dior</h6>
    <div class="stars-rating">
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star"></i>
    <span>613</span></div>
    <p class="mb-0 text-dark">&#8358 25000.00<span class="text-black-50"><del>&#8358 35000.00 </del></span></p>
    </div>
    </div>
    </div>
    </div>
    </div>
    </div>
     </div>
    </section>
    
    <footer class="bg-white border-bottom border-top">
    <div class="container">
    <div class="row no-gutters">
    <div class="col-md-4">
    <div class="border-right py-5 pr-5">
    <h6 class="mt-0 mb-4 f-14 text-dark font-weight-bold">TOP CATEGORIES</h6>
    <div class="row no-gutters">
    <div class="col-6">
    <ul class="list-unstyled mb-0">
    <li><a href="#">Sneeker for Men</a></li>
    <li><a href="#">Sneeker for women</a></li>
    <li><a href="#">Sneeker for Girls</a></li>
    <li><a href="#">Sneeker for boys</a></li>
    <li><a href="#">Sneeker for Sports</a></li>
    </ul>
    </div>
    </div>
    </div>
    </div>
    <div class="col-md-4">
    <div class="border-right py-5 px-5">
    <h6 class="mt-0 mb-4 f-14 text-dark font-weight-bold">ABOUT US</h6>
    <div class="row no-gutters">
    <div class="col-6">
    <ul class="list-unstyled mb-0">
    <li><a href="#"></a></li>
    <li><a href="#">Terms & Conditions</a></li>
    <li><a href="#">Privacy Policy</a></li>
    <li><a href="#">Careers</a></li>
    <li><a href="#">Offers</a></li>
    </ul>
    </div>
    </div>
    </div>
    </div>
    <!--<div class="col-md-4">
    <div class="py-5 pl-5">
    <h6 class="mt-0 mb-4 f-14 text-dark font-weight-bold">DOWNLOAD APP</h6>
    <div class="app">
    <a href="#">
    <img class="img-fluid" src="{% static 'img/google.png' %}">
    </a>
    <a href="#">
    <img class="img-fluid" src="{% static 'img/apple.png' %}">
    </a>
    </div>-->
    <h6 class="mt-4 mb-4 f-14 text-dark font-weight-bold">KEEP IN TOUCH</h6>
    <div class="footer-social">
    <a class="btn-facebook" href="https://www.facebook.com/Adedasneakers/"><i class="icofont-facebook"></i></a>
    <a class="btn-twitter" href="#"><i class="icofont-twitter"></i></a>
    <a class="btn-instagram" href="https://instagram.com/adedasneaker?r=nametag"><i class="icofont-instagram"></i></a>
    <a class="btn-whatsapp" href="#"><i class="icofont-whatsapp"></i></a>
    <a class="btn-messenger" href="#"><i class="icofont-facebook-messenger"></i></a>
    <a class="btn-google" href="#"><i class="icofont-google-plus"></i></a>
    </div>
    </div>
    </div>
    </div>
    </div>
    
    </footer>
    <div class="popular-tag py-5">
    <div class="container">
    <div class="row">
    <div class="col-lg-12">
    <h6 class="mt-0 mb-4 f-14 text-dark font-weight-bold">POPULAR SEARCHES</h6>
    <p class="mb-0">
    <a href="#">Sandals</a> &nbsp; | &nbsp; <a href="#">Sport Shoes</a> &nbsp; | &nbsp; <a href="#">Reebok Shoes</a> &nbsp; | &nbsp; 
    <a href="#">Puma Shoes</a> &nbsp; | &nbsp;<a href="#">Nike shoes</a> &nbsp; | &nbsp; <a href="#">Addidas shoes</a>&nbsp; | &nbsp; 
    <a href="#">Addidas Sports</a> &nbsp; | &nbsp; <a href="#">Nike Sports</a> &nbsp; | &nbsp; <a href="#">Spike shoes</a> &nbsp; | &nbsp; 
    <a href="#">Soccer shoes</a> &nbsp; | &nbsp; <a href="#">Nike
    Shoes</a> &nbsp; | &nbsp; <a href="#">Puma Sports</a> &nbsp; | &nbsp; <a href="#">Puma</a>&nbsp; | &nbsp; <a href="#">Adidas Spike</a>
     &nbsp; | &nbsp; 
    </p>
    </div>
    </div>
    </div>
    </div>


    <div class="copyright bg-light py-3">
    <div class="container">
    <div class="row">
    <div class="col-md-6 d-flex align-items-center">
    <p class="mb-0">?? Copyright 2022 <a href="#">Adeda</a> . All Rights Reserved
    </p>
    </div>


    <div class="col-md-6 text-right">
    <img class="img-fluid" src="{% static 'img/payment_methods.png' %}">
    </div>
    </div>
    </div>
    </div>


    <div class="cart-sidebar">
    <div class="cart-sidebar-header">
    <h5>
    My Cart <span class="text-info">(5 item)</span> 
    <a data-toggle="offcanvas" class="float-right" href="#">
        <i class="icofont icofont-close-line"></i>
    </a>
    </h5>
    </div>


    <div class="cart-sidebar-body">
    <div class="cart-list-product">
    <a class="float-right remove-cart" href="#"><i class="icofont icofont-close-circled"></i></a>
    <img class="img-fluid" src="{% static 'img/item/1.jpg'%}" alt="">
    <span class="badge badge-success">50% OFF</span>
    <div class="stars-rating"><i class="icofont icofont-star active"></i><i class="icofont icofont-star active"></i>
     <i class="icofont icofont-star active"></i>
    <i class="icofont icofont-star active"></i>
    <i class="icofont icofont-star"></i> 
    <span>613</span></div>
    <p class="f-14 mb-0 text-dark float-right">&#8358 25000.00 <del class="small text-secondary">&#8358 35000.00 </del></p>
    <span class="count-number float-left">
    <button class="btn btn-outline-secondary  btn-sm left dec"> <i class="icofont-minus"></i> </button>
    <input class="count-number-input" type="text" value="1" readonly="">
    <button class="btn btn-outline-secondary btn-sm right inc"> <i class="icofont-plus"></i> </button>
    </span>
    </div>

    <div class="cart-list-product">
    <a class="float-right remove-cart" href="#"><i class="icofont icofont-close-circled"></i></a>
    <img class="img-fluid" src="{% static 'img/item/2.jpg'%}" alt="">
    <span class="badge badge-danger">55% OFF</span>
    <h5><a href="#">Puma</a></h5>
    <div class="stars-rating">
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
            <i class="icofont icofont-star active"></i>
            <i class="icofont icofont-star active"></i>
            <i class="icofont icofont-star"></i> 
            <span>613</span></div>
    <p class="f-14 mb-0 text-dark float-right">&#8358 25000.00 <del class="small text-secondary">&#8358 35000.00 </del> 
        <span class="bg-info rounded-sm pl-1 ml-1 pr-1 text-white small">NEW</span> </p>
    <span class="count-number float-left">
    <button class="btn btn-outline-secondary  btn-sm left dec"> <i class="icofont-minus"></i> </button>
    <input class="count-number-input" type="text" value="1" readonly="">
    <button class="btn btn-outline-secondary btn-sm right inc"> <i class="icofont-plus"></i> </button>
    </span>
    </div>


    <div class="cart-list-product">
    <a class="float-right remove-cart" href="#"><i class="icofont icofont-close-circled"></i></a>
    <img class="img-fluid" src="{% static 'img/item/3.jpg' %}" alt="">
    <span class="badge badge-info">NEW</span>
    <h5><a href="#">Reebok</a></h5>
    <div class="stars-rating">
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star"></i> 
        <span>613</span></div>
    <p class="f-14 mb-0 text-dark float-right">&#8358 25000.00 <del class="small text-secondary">&#8358 35000.00 </del>
         <span class="bg-danger  rounded-sm pl-1 ml-1 pr-1 text-white small"> 50% OFF</span> </p>
    <span class="count-number float-left">
    <button class="btn btn-outline-secondary  btn-sm left dec"> <i class="icofont-minus"></i> </button>
    <input class="count-number-input" type="text" value="1" readonly="">
    <button class="btn btn-outline-secondary btn-sm right inc"> <i class="icofont-plus"></i> </button>
    </span>
    </div>


    <div class="cart-list-product">
    <a class="float-right remove-cart" href="#"><i class="icofont icofont-close-circled"></i></a>
    <img class="img-fluid" src="{% static 'img/item/4.jpg' %}" alt="">
    <span class="badge badge-danger">NEW</span>
    <h5><a href="#">Adidas</a></h5>
    <div class="stars-rating">
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star"></i>
         <span>613</span></div>
    <p class="f-14 mb-0 text-dark float-right">&#8358 25000.00<del class="small text-secondary">&#8358 35000.00 </del>
         <span class="bg-danger  rounded-sm pl-1 ml-1 pr-1 text-white small"> 50% OFF</span> </p>
    <span class="count-number float-left">
     <button class="btn btn-outline-secondary  btn-sm left dec"> <i class="icofont-minus"></i> </button>
    <input class="count-number-input" type="text" value="1" readonly="">
    <button class="btn btn-outline-secondary btn-sm right inc"> <i class="icofont-plus"></i> </button>
    </span>
    </div>


    <div class="cart-list-product">
    <a class="float-right remove-cart" href="#"><i class="icofont icofont-close-circled"></i></a>
    <img class="img-fluid" src="{% static 'img/item/5.jpg' %}" alt="">
    <span class="badge badge-info">NEW</span>
    <h5><a href="#">Puma</a></h5>
    <div class="stars-rating">
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star active"></i>
        <i class="icofont icofont-star"></i>
         <span>613</span></div>
    <p class="f-14 mb-0 text-dark float-right">&#8358 25000.00 <del class="small text-secondary">&#8358 35000.00 </del>
         <span class="bg-danger  rounded-sm pl-1 ml-1 pr-1 text-white small"> 50% OFF</span> </p>
    <span class="count-number float-left">
    <button class="btn btn-outline-secondary  btn-sm left dec"> <i class="icofont-minus"></i> </button>
    <input class="count-number-input" type="text" value="1" readonly="">
    <button class="btn btn-outline-secondary btn-sm right inc"> <i class="icofont-plus"></i> </button>
    </span>
    </div>
    </div>


    <div class="cart-sidebar-footer">
    <div class="cart-store-details">
    <p>Sub Total <strong class="float-right">&#8358 25000.00</strong></p>
    <p>Delivery Charges <strong class="float-right text-danger">+ &#8358 250</strong></p>
    <h6>Your total savings <strong class="float-right text-danger">&#8358 55 (42.31%)</strong></h6>
    </div>
    <a href="london:checkout.html"><button class="btn btn-primary btn-lg btn-block text-left" type="button">
        <span class="float-left"><i class="icofont icofont-cart"></i> Proceed to Checkout </span>
        <span class="float-right"><strong>&#8358 25000.00</strong> <span class="icofont icofont-bubble-right"></span></span></button></a>
    </div>
    </div>
    
    
    <script src="{% static 'vendor/jquery/jquery.min.js' %}" type="1f9d808afb4dd0e29dd32d14-text/javascript"></script>
    <script src="{% static 'vendor/bootstrap/js/bootstrap.bundle.min.js' %}" type="1f9d808afb4dd0e29dd32d14-text/javascript"></script>
    
    <script src="{% static 'vendor/select2/js/select2.min.js' %}" type="1f9d808afb4dd0e29dd32d14-text/javascript"></script>
    
    <script src="{% static 'vendor/owl-carousel/owl.carousel.js' %}" type="1f9d808afb4dd0e29dd32d14-text/javascript"></script>
    
    <script src="{% static 'vendor/slider/slider.js' %}" type="1f9d808afb4dd0e29dd32d14-text/javascript"></script>
    
    <script src="{% static 'js/custom.js' %}" type="1f9d808afb4dd0e29dd32d14-text/javascript"></script>

   
    <script src="{% static 'cdn-cgi/scripts/7d0fa10a/cloudflare-static/rocket-loader.min.js' %}" data-cf-settings="1f9d808afb4dd0e29dd32d14-|49" defer=""></script>
    
    <script defer src="{% static 'https://static.cloudflareinsights.com/beacon.min.js/v652eace1692a40cfa3763df669d7439c1639079717194' %}" integrity="sha512-Gi7xpJR8tSkrpF7aordPZQlW2DLtzUlZcumS8dMQjwDHEnw9I7ZLyiOj/6tZStRBGtGgN6ceN6cMH8z7etPGlw==" data-cf-beacon='{"rayId":"6edec4bb4c6b7713","version":"2021.12.0","r":1,"token":"dd471ab1978346bbb991feaa79e6ce5c","si":100}' crossorigin="anonymous"></script>
   
     
    
</body>
    
    <!-- AS designed by David Oyinkuro Zipamone also known as David Oz -->
    </html>
