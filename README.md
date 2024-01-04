Index.html
----------
<!--doctype html-->
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<!--==Title==================================-->
<title>eGrocery Store</title>
<!--==Stylesheet=============================-->
<link rel="stylesheet" type="text/css" href="style.css">
<!--==Fav-icon===============================-->
<link rel="shortcut icon" href="images/fav-icon.png"/>
<!--==Using-Font-Awesome=====================-->
<link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous"/>
<!--==Import-Font-Family======================-->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
</head>
<body>
    <!--==Navigation================================-->
    <nav class="navigation">
        <!--logo-------->
        <a href="index.html" class="logo">
            <span>e</span>Grocery
        </a>
        <!--menu-btn---->
        <input type="checkbox" class="menu-btn" id="menu-btn">
        <label for="menu-btn" class="menu-icon">
            <span class="nav-icon"></span>
        </label>
        <!--menu-------->
        <ul class="menu">
            <li><a href="index.html" class="active">Home</a></li>
            <li><a href="#category">Categories</a></li>
            <li><a href="#popular-bundle-pack">Our Packages</a></li>
            <li><a href="#download-app">Our App</a></li>
        </ul>
        <!--right-nav-(cart-like)-->
        <div class="right-nav">
            <!--like----->
            <a href="#" class="like">
                <i class="far fa-heart"></i>
                <span>0</span>
            </a>
            <!--cart----->
            <a href="#" class="cart">
                <i class="fas fa-shopping-cart"></i>
                <span>0</span>
            </a>
        </div>
    </nav>
    <!--nav-end--------------------->
    <!--==Search-banner=======================================-->
    <section id="search-banner">
        <!--bg--------->
        <img alt="bg" class="bg-1" src="images/bg-1.png">
        <img alt="bg-2" class="bg-2" src="images/bg-2.png">
        <!--text------->
        <div class="search-banner-text">
            <h1>Order Your daily Groceries</h1>
            <strong>#Free Delivery</strong>
            <!--search-box------>
            <form action="" class="search-box">
                <!--icon------>
                <i class="fas fa-search"></i>
                <!--input----->
                <input type="text" class="search-input" placeholder="Search your daily groceries" name="search" required>
                <!--btn------->
                <input type="submit" class="search-btn" value="Search">
            </form>
        </div>
    </section>
    <!--search-banner-end--------------->
    <!--==category=========================================-->
    <section id="category">
        <!--heading---------------->
        <div class="category-heading">
            <h2>Category</h2>
            <span>All</span>
        </div>
        <!--box-container---------->
        <div class="category-container">
            <!--box---------------->
            <a href="#" class="category-box">
                <img alt="Fish" src="images/fish.png">
                <span>Fish & Meat</span>
            </a>
            <!--box---------------->
            <a href="#" class="category-box">
                <img alt="Fish" src="images/Vegetables.png">
                <span>Vegatbles</span>
            </a>
            <!--box---------------->
            <a href="#" class="category-box">
                <img alt="Fish" src="images/medicine.png">
                <span>Medicine</span>
            </a>
            <!--box---------------->
            <a href="#" class="category-box">
                <img alt="Fish" src="images/baby.png">
                <span>Baby</span>
            </a>
            <!--box---------------->
            <a href="#" class="category-box">
                <img alt="Fish" src="images/office.png">
                <span>Office</span>
            </a>
            <!--box---------------->
            <a href="#" class="category-box">
                <img alt="Fish" src="images/beauty.png">
                <span>Beauty</span>
            </a>
        </div>
        
    </section>
    <!--category-end----------------------------------->
    <!--==Products====================================-->
    <section id="popular-product">
        <!--heading----------->
        <div class="product-heading">
            <h3>Products</h3>
            <span>All</span>
        </div>
        <!--box-container------>
        <div class="product-container">
            <!--box---------->
            <div class="product-box">
                <img alt="apple" src="images/apple.png">
                <strong>Apple</strong>
                <span class="quantity">1 KG</span>==
                <span class="price">2$</span>
                <!--cart-btn------->
                <a href="#" class="cart-btn">
                    <i class="fas fa-shopping-bag"></i> Add Cart
                </a>
                <!--like-btn------->
                <a href="#" class="like-btn">
                    <i class="far fa-heart"></i>
                </a>
            </div>
            <!--box---------->
            <div class="product-box">
                <img alt="apple" src="images/chili.png">
                <strong>Chili</strong>
                <span class="quantity">1 KG</span>
                <span class="price">3$</span>
                <!--cart-btn------->
                <a href="#" class="cart-btn">
                    <i class="fas fa-shopping-bag"></i> Add Cart
                </a>
                <!--like-btn------->
                <a href="#" class="like-btn">
                    <i class="far fa-heart"></i>
                </a>
            </div>
            <!--box---------->
            <div class="product-box">
                <img alt="apple" src="images/onion.png">
                <strong>Onion</strong>
                <span class="quantity">1 KG</span>
                <span class="price">1$</span>
                <!--cart-btn------->
                <a href="#" class="cart-btn">
                    <i class="fas fa-shopping-bag"></i> Add Cart
                </a>
                <!--like-btn------->
                <a href="#" class="like-btn">
                    <i class="far fa-heart"></i>
                </a>
            </div>
            <!--box---------->
            <div class="product-box">
                <img alt="apple" src="images/patato.png">
                <strong>Patato</strong>
                <span class="quantity">1 KG</span>
                <span class="price">2.2$</span>
                <!--cart-btn------->
                <a href="#" class="cart-btn">
                    <i class="fas fa-shopping-bag"></i> Add Cart
                </a>
                <!--like-btn------->
                <a href="#" class="like-btn">
                    <i class="far fa-heart"></i>
                </a>
            </div>
            <!--box---------->
            <div class="product-box">
                <img alt="apple" src="images/garlic.png">
                <strong>Garlic</strong>
                <span class="quantity">1 KG</span>
                <span class="price">3$</span>
                <!--cart-btn------->
                <a href="#" class="cart-btn">
                    <i class="fas fa-shopping-bag"></i> Add Cart
                </a>
                <!--like-btn------->
                <a href="#" class="like-btn">
                    <i class="far fa-heart"></i>
                </a>
            </div>
            <!--box---------->
            <div class="product-box">
                <img alt="apple" src="images/tamato.png">
                <strong>Tamato</strong>
                <span class="quantity">1 KG</span>
                <span class="price">1.4$</span>
                <!--cart-btn------->
                <a href="#" class="cart-btn">
                    <i class="fas fa-shopping-bag"></i> Add Cart
                </a>
                <!--like-btn------->
                <a href="#" class="like-btn">
                    <i class="far fa-heart"></i>
                </a>
            </div>
            
        </div>
    </section>
    <!--popular-product-end--------------------->
    <!--Popular-bundle-pack===================================-->
    <section id="popular-bundle-pack">
        <!--heading-------------->
        <div class="product-heading">
            <h3>Popular Bundle Pack</h3>
        </div>
        <!--box-container------>
        <div class="product-container">
            <!--box---------->
            <div class="product-box">
                <img alt="pack" src="images/pack1.png">
                <strong>Big Pack</strong>
                <span class="quantity">Lemone, Tamato, Patato,+4</span>
                <span class="price">9$</span>
                <!--cart-btn------->
                <a href="#" class="cart-btn">
                    <i class="fas fa-shopping-bag"></i> Add Cart
                </a>
                <!--like-btn------->
                <a href="#" class="like-btn">
                    <i class="far fa-heart"></i>
                </a>
            </div>
            <!--box---------->
            <div class="product-box">
                <img alt="apple" src="images/pack2.jpg">
                <strong>Large Pack</strong>
                <span class="quantity">Lemone, Tamato, Patato,+2</span>
                <span class="price">5$</span>
                <!--cart-btn------->
                <a href="#" class="cart-btn">
                    <i class="fas fa-shopping-bag"></i> Add Cart
                </a>
                <!--like-btn------->
                <a href="#" class="like-btn">
                    <i class="far fa-heart"></i>
                </a>
            </div>
            <!--box---------->
            <div class="product-box">
                <img alt="apple" src="images/pack3.png">
                <strong>Small Pack</strong>
                <span class="quantity">Lemone, Tamato, Patato</span>
                <span class="price">3$</span>
                <!--cart-btn------->
                <a href="#" class="cart-btn">
                    <i class="fas fa-shopping-bag"></i> Add Cart
                </a>
                <!--like-btn------->
                <a href="#" class="like-btn">
                    <i class="far fa-heart"></i>
                </a>
            </div>
            <!--box---------->
            <div class="product-box">
                <img alt="pack" src="images/pack1.png">
                <strong>Big Pack</strong>
                <span class="quantity">Lemone, Tamato, Patato,+4</span>
                <span class="price">9$</span>
                <!--cart-btn------->
                <a href="#" class="cart-btn">
                    <i class="fas fa-shopping-bag"></i> Add Cart
                </a>
                <!--like-btn------->
                <a href="#" class="like-btn">
                    <i class="far fa-heart"></i>
                </a>
            </div>
            <!--box---------->
            <div class="product-box">
                <img alt="apple" src="images/pack2.jpg">
                <strong>Large Pack</strong>
                <span class="quantity">Lemone, Tamato, Patato,+2</span>
                <span class="price">5$</span>
                <!--cart-btn------->
                <a href="#" class="cart-btn">
                    <i class="fas fa-shopping-bag"></i> Add Cart
                </a>
                <!--like-btn------->
                <a href="#" class="like-btn">
                    <i class="far fa-heart"></i>
                </a>
            </div>
            <!--box---------->
            <div class="product-box">
                <img alt="apple" src="images/pack3.png">
                <strong>Small Pack</strong>
                <span class="quantity">Lemone, Tamato, Patato</span>
                <span class="price">3$</span>
                <!--cart-btn------->
                <a href="#" class="cart-btn">
                    <i class="fas fa-shopping-bag"></i> Add Cart
                </a>
                <!--like-btn------->
                <a href="#" class="like-btn">
                    <i class="far fa-heart"></i>
                </a>
            </div>
        </div>
    </section>
    <!--popular-bundle-pack-end-------------------------------->
    <!--==Clients===============================================-->
    <section id="clients">
        <!--heading---------------->
        <div class="client-heading">
            <h3>What Our Client's Say</h3>
        </div>
        <!--box-container---------->
        <div class="client-box-container">
            <!--box------------->
            <div class="client-box">
                <!--==profile===-->
                <div class="client-profile">
                    <!--img--->
                    <img alt="client" src="images/client-1.jpg">
                    <!--text-->
                    <div class="profile-text">
                        <strong>James Mcavoy</strong>
                        <span>CEO</span>
                    </div>
                </div>
                <!--==Rating======-->
                <div class="rating">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </div>
                <!--==comments===-->
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugiat ea id, itaque architecto atque mollitia aperiam voluptatem consequatur incidunt sed placeat, harum recusandae quaerat at hic labore eius laborum quas!</p>
            </div>
            <!--box------------->
            <div class="client-box">
                <!--==profile===-->
                <div class="client-profile">
                    <!--img--->
                    <img alt="client" src="images/client-2.jpg">
                    <!--text-->
                    <div class="profile-text">
                        <strong>Adward Mcavoy</strong>
                        <span>Software Developer</span>
                    </div>
                </div>
                <!--==Rating======-->
                <div class="rating">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </div>
                <!--==comments===-->
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugiat ea id, itaque architecto atque mollitia aperiam voluptatem consequatur incidunt sed placeat, harum recusandae quaerat at hic labore eius laborum quas!</p>
            </div>
            <!--box------------->
            <div class="client-box">
                <!--==profile===-->
                <div class="client-profile">
                    <!--img--->
                    <img alt="client" src="images/client-3.jpg">
                    <!--text-->
                    <div class="profile-text">
                        <strong>Ava Alex</strong>
                        <span>Marketer</span>
                    </div>
                </div>
                <!--==Rating======-->
                <div class="rating">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </div>
                <!--==comments===-->
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugiat ea id, itaque architecto atque mollitia aperiam voluptatem consequatur incidunt sed placeat, harum recusandae quaerat at hic labore eius laborum quas!</p>
            </div>
        </div>
    </section>
    <!--client-section-end---------->
    <!--==Partnre-logo================================-->
    <section id="partner">
        <!--heading------------>
        <div class="partner-heading">
            <h3>Our Trusted Partner</h3>
        </div>
        <!--logo-container----->
        <div class="logo-container">
            <img alt="logo" src="images/logo-1.png">
            <img alt="logo" src="images/logo-2.png">
            <img alt="logo" src="images/logo-3.png">
            <img alt="logo" src="images/logo-4.png">
        </div>
    </section>
    <!--logo-section-end--------------------->
    <!--==download-app====================================-->
    <section id="download-app">
        <!--img----------------------->
        <div class="app-img">
            <img alt="app" src="images/mobile-app.png">
        </div>
        <!--text---------------------->
        <div class="download-app-text">
            <strong>Download App</strong>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Id officiis, ratione, non doloribus similique nam aliquam doloremque, ipsa neque voluptas at recusandae est cumque ipsum. Vel sint libero odit placeat?</p>
            <!--btns------->
            <div class="download-btns">
                <a href="#"><img alt="" src="images/appstore-btn.png"></a>
                <a href="#"><img alt="" src="images/googleplay-btn.png"></a>
            </div>
        </div>
    </section>
    <!--download-app-section-end------------------------->
    <!--==Footer=============================================-->
    <footer>
        <div class="footer-container">
            <!--logo-container------>
            <div class="footer-logo">
                <a href="#"><span>e</span>Grocery</a>
                <!--social----->
                <div class="footer-social">
                    <a href="#"><i class="fab fa-facebook-f"></i></a>
                    <a href="#"><i class="fab fa-twitter"></i></a>
                    <a href="#"><i class="fab fa-instagram"></i></a>
                    <a href="#"><i class="fab fa-youtube"></i></a>
                </div>
            </div>
            <!--links------------------------->
        <div class="footer-links">
            <strong>Product</strong>
            <ul>
                <li><a href="#">Clothes</a></li>
                <li><a href="#">Packages</a></li>
                <li><a href="#">Popular</a></li>
                <li><a href="#">New</a></li>
            </ul>
        </div>
        <!--links------------------------->
        <div class="footer-links">
            <strong>Category</strong>
            <ul>
                <li><a href="#">Beauty</a></li>
                <li><a href="#">Meats</a></li>
                <li><a href="#">Kids</a></li>
                <li><a href="#">Clothes</a></li>
            </ul>
        </div>
        <!--links-------------------------->
        <div class="footer-links">
            <strong>Contact</strong>
            <ul>
                <li><a href="#">Phone : +123456789</a></li>
                <li><a href="#">Email : Example@gmail.com</a></li>
            </ul>
        </div>
        </div>
    </footer>
</body>
</html># Miniproject
