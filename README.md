# Project-Ecomerce-Store
I developed this Ecomerce Store website using HTML and CSS.
Redstore | Ecomerce Website Design
I created this project, I am the group leader. My name is Muhammad Usman. A lot of time and effort has gone into making this project. This project is an ecommerce store. This project is very well done. This project has 5 pages. The idea of ​​making this project came to my mind. I hope you will like this project very much.
#index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redstore | Ecomerce Website Design</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link href="//maxcdn.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css" rel="stylesheet">
<body>


<div class="header">
 <div class="container">
        <div class="navbar">
            <div class="logo">
               <a href="index.html"> <img src="Saved Pictures/logo.png" width="125px"></a>
            </div>
            <nav>
                <ul id="MenuItems">
                    <li><a href="index.html">Home</a></li>
                    <li><a href="product.html">Products</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact</a></li>
                    <li><a href="account.html">Account</a></li>
                </ul>
            </nav>
            <img src="Saved Pictures/cart.png" width="30px" height="30px">
            <img src="Saved Pictures/menu.png" class="menu-icon" onclick="menutoggle()">
        </div>
        <div class="row">
            <div class="col-2">
<h1>Give Your Workout <br> A New Style!</h1>
<p>Success isn't always about greatness. It's about consistency. Consistent <br> hard work gains success. Greatness will come.</p>
<a href="" class="btn">Explore Now &#8594;</a>
            </div>
            <div class="col-2">
<img src="Saved Pictures/image1.png" alt="">
            </div>
        </div>
    </div>
</div>

<!------- featured categories ------->
<div class="categories">
    <div class="small-container">
        <div class="row">
        <div class="col-3">
            <img src="Saved Pictures/category-1.jpg" >
        </div>
        <div class="col-3">
            <img src="Saved Pictures/category-2.jpg" >
        </div>
        <div class="col-3">
            <img src="Saved Pictures/category-3.jpg" >
        </div>
    </div>
</div>
    </div>
    <!------- featured products ------->
<div class="small-container">
    <h2 class="title">Featured Products</h2>
    <div class="row">
        <div class="col-4">
            <img src="Saved Pictures/product-1.jpg" >
            <h4>Red Printed T-Shirt</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-o"></i>
            </div>
            <p>$50.00</p>
        </div>
        <div class="col-4">
            <img src="Saved Pictures/product-2.jpg" >
            <h4>Shoes</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-half-o"></i>
                <i class="fa fa-star-o"></i>
            </div>
            <p>$55.00</p>
        </div>
        <div class="col-4">
            <img src="Saved Pictures/product-3.jpg" >
            <h4>Brown Paint</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-half-o"></i>
            </div>
            <p>$40.00</p>
        </div>
        <div class="col-4">
            <img src="Saved Pictures/product-4.jpg" >
            <h4>Blue Printed T-Shirt</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-o"></i>
            </div>
            <p>$50.00</p>
        </div>
    </div>
    <h2 class="title">Latest Products</h2>
    <div class="row">
        <div class="col-4">
            <img src="Saved Pictures/product-5.jpg" >
            <h4>White Shoes</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-o"></i>
            </div>
            <p>$45.00</p>
        </div>
        <div class="col-4">
            <img src="Saved Pictures/product-6.jpg" >
            <h4>Printed T-Shirt</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-half-o"></i>
                <i class="fa fa-star-o"></i>
            </div>
            <p>$50.00</p>
        </div>
        <div class="col-4">
            <img src="Saved Pictures/product-7.jpg" >
            <h4>Socks</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-half-o"></i>
            </div>
            <p>$25.00</p>
        </div>
        <div class="col-4">
            <img src="Saved Pictures/product-8.jpg" >
            <h4>Fossil Watch</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-o"></i>
            </div>
            <p>$35.00</p>
        </div>
        <div class="row">
            <div class="col-4">
                <img src="Saved Pictures/product-9.jpg" >
                <h4>Rodstar Watch</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-o"></i>
                </div>
                <p>$35.00</p>
            </div>
            <div class="col-4">
                <img src="Saved Pictures/product-10.jpg" >
                <h4>Shoes</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-half-o"></i>
                    <i class="fa fa-star-o"></i>
                </div>
                <p>$40.00</p>
            </div>
            <div class="col-4">
                <img src="Saved Pictures/product-11.jpg" >
                <h4>Shoes</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-half-o"></i>
                </div>
                <p>$40.00</p>
            </div>
            <div class="col-4">
                <img src="Saved Pictures/product-12.jpg" >
                <h4>Black Trouser</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-o"></i>
                </div>
                <p>$43.00</p>
            </div>
        </div>
    </div>
</div>
<!------- offer --------->
<div class="offer">
    <div class="small-container">
        <div class="row">
            <div class="col-2">
                <img src="Saved Pictures/exclusive.png" class="offer-img">
            </div>
            <div class="col-2">
                <p>Exclusively Available on Redstore</p>
                <h1>Smart Band 4</h1>
                <small>
                    The Mi Smart Band 4 features a 39.9% larger (than Mi Band 3) AMOLED color full-touch display with adjustable brightness, so everything is clear as can be.</small>
    <a href="" class="btn">Buy Now &#8594;</a>
            </div>
        </div>
    </div>
</div>


<!----------testimonial---------->

<div class="testimonial">
    <div class="small-container">
        <div class="row">
            <div class="col-3">
                <i class="fa fa-quote-left"></i>
                <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever</p>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-o"></i>
                </div>
                <img src="Saved Pictures/user-1.png">
                <h3>Sean Parker</h3>
            </div>
            <div class="col-3">
                <i class="fa fa-quote-left"></i>
                <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever</p>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-o"></i>
                </div>
                <img src="Saved Pictures/user-2.png">
                <h3>Mike Smith</h3>
            </div>
            <div class="col-3">
                <i class="fa fa-quote-left"></i>
                <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever</p>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-o"></i>
                </div>
                <img src="Saved Pictures/user-3.png">
                <h3>Mabel Joe</h3>
            </div>
        </div>
    </div>
</div>
<!-- brands -->
<div class="brands">
    <div class="small-container">
        <div class="row">
            <div class="col-5">
                <img src="Saved Pictures/logo-godrej.png" alt="">
            </div>
            <div class="col-5">
                <img src="Saved Pictures/logo-oppo.png" alt="">
            </div>
            <div class="col-5">
                <img src="Saved Pictures/logo-coca-cola.png" alt="">
            </div>
            <div class="col-5">
                <img src="Saved Pictures/logo-paypal.png" alt="">
            </div>
            <div class="col-5">
                <img src="Saved Pictures/logo-philips.png" alt="">
            </div>
        </div>
    </div>
</div>
<!-- footer -->
<div class="footer">
    <div class="container">
        <div class="row">
            <div class="footer-col-1">
                <h3>Download Our App</h3>
                <p>Download App for Android and ios mobile phone.</p>
                <div class="app-logo">
                    <img src="Saved Pictures/play-store.png">
                    <img src="Saved Pictures/app-store.png">
                </div>
            </div>
            <div class="footer-col-2">
                <img src="Saved Pictures/logo-white.png">
                <p>Our Purpose Is To Sustainably Make the Pleasure and Benefits of Sports Accessible to the Many.</p>
            </div>
            <div class="footer-col-3">
                <h3>Useful Links</h3>
                <ul>
                    <li>Coupons</li>
                    <li>Blog Post</li>
                    <li>Return Policy</li>
                    <li>Join Affiliate</li>
                </ul>
            </div>
            <div class="footer-col-4">
                <h3>Follow us</h3>
                <ul>
                    <li>Facebook</li>
                    <li>Twitter</li>
                    <li>Instagram</li>
                    <li>YouTube</li>
                </ul>
            </div>
        </div>
        <hr>
        <p class="copyright">Copy right 2024 - Muhammad Usman</p>
    </div>
</div>
<!-- js for toggle menu -->
<script>
    var MenuItems = document.getElementById("MenuItems")

    MenuItems.style.maxHeight = "0px";

    function menutoggle(){
        if(MenuItems.style.maxHeight == "0px")
    
{
    MenuItems.style.maxHeight = "200px"
}
else
{
    MenuItems.style.maxHeight = "0px"
}
    }
</script>
</body>
</html>

#product.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>All Products - Redstore</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link href="//maxcdn.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css" rel="stylesheet">
<body>


 <div class="container">
        <div class="navbar">
            <div class="logo">
                <a href="index.html"> <img src="Saved Pictures/logo.png" width="125px"></a>
            </div>
            <nav>
                <ul id="MenuItems">
                    <li><a href="index.html">Home</a></li>
                    <li><a href="product.html">Products</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact</a></li>
                    <li><a href="account.html">Account</a></li>
                </ul>
            </nav>
            <img src="Saved Pictures/cart.png" width="30px" height="30px">
            <img src="Saved Pictures/menu.png" class="menu-icon" onclick="menutoggle()">
        </div>
        
    </div>


<div class="small-container">
    <div class="row row-2">
        <h2>All Products</h2>
        <select>
            <option>Default Shorting</option>
            <option>Short by price</option>
            <option>Short by popularity</option>
            <option>Short by rating</option>
            <option>Short by sale</option>
        </select>
    </div>



    <div class="row">
        <div class="col-4">
            <img src="Saved Pictures/product-1.jpg" >
            <h4>Red Printed T-Shirt</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-o"></i>
            </div>
            <p>$50.00</p>
        </div>
        <div class="col-4">
            <img src="Saved Pictures/product-2.jpg" >
            <h4>Shoes</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-half-o"></i>
                <i class="fa fa-star-o"></i>
            </div>
            <p>$55.00</p>
        </div>
        <div class="col-4">
            <img src="Saved Pictures/product-3.jpg" >
            <h4>Brown Paint</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-half-o"></i>
            </div>
            <p>$40.00</p>
        </div>
        <div class="col-4">
            <img src="Saved Pictures/product-4.jpg" >
            <h4>Blue Printed T-Shirt</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-o"></i>
            </div>
            <p>$50.00</p>
        </div>
    </div>
    <div class="row">
        <div class="col-4">
            <img src="Saved Pictures/product-5.jpg" >
            <h4>White Shoes</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-o"></i>
            </div>
            <p>$45.00</p>
        </div>
        <div class="col-4">
            <img src="Saved Pictures/product-6.jpg" >
            <h4>Printed T-Shirt</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-half-o"></i>
                <i class="fa fa-star-o"></i>
            </div>
            <p>$50.00</p>
        </div>
        <div class="col-4">
            <img src="Saved Pictures/product-7.jpg" >
            <h4>Socks</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-half-o"></i>
            </div>
            <p>$25.00</p>
        </div>
        <div class="col-4">
            <img src="Saved Pictures/product-8.jpg" >
            <h4>Fossil Watch</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-o"></i>
            </div>
            <p>$35.00</p>
        </div>
        <div class="row">
            <div class="col-4">
                <img src="Saved Pictures/product-9.jpg" >
                <h4>Rodstar Watch</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-o"></i>
                </div>
                <p>$35.00</p>
            </div>
            <div class="col-4">
                <img src="Saved Pictures/product-10.jpg" >
                <h4>Shoes</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-half-o"></i>
                    <i class="fa fa-star-o"></i>
                </div>
                <p>$40.00</p>
            </div>
            <div class="col-4">
                <img src="Saved Pictures/product-11.jpg" >
                <h4>Shoes</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-half-o"></i>
                </div>
                <p>$40.00</p>
            </div>
            <div class="col-4">
                <img src="Saved Pictures/product-12.jpg" >
                <h4>Black Trouser</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-o"></i>
                </div>
                <p>$43.00</p>
            </div>
        </div>
    </div>

    <div class="page-btn">
        <span>1</span>
        <span>2</span>
        <span>3</span>
        <span>4</span>
        <span>&#8594;</span>
    </div>
</div>


<!-- footer -->
<div class="footer">
    <div class="container">
        <div class="row">
            <div class="footer-col-1">
                <h3>Download Our App</h3>
                <p>Download App for Android and ios mobile phone.</p>
                <div class="app-logo">
                    <img src="Saved Pictures/play-store.png">
                    <img src="Saved Pictures/app-store.png">
                </div>
            </div>
            <div class="footer-col-2">
                <img src="Saved Pictures/logo-white.png">
                <p>Our Purpose Is To Sustainably Make the Pleasure and Benefits of Sports Accessible to the Many.</p>
            </div>
            <div class="footer-col-3">
                <h3>Useful Links</h3>
                <ul>
                    <li>Coupons</li>
                    <li>Blog Post</li>
                    <li>Return Policy</li>
                    <li>Join Affiliate</li>
                </ul>
            </div>
            <div class="footer-col-4">
                <h3>Follow us</h3>
                <ul>
                    <li>Facebook</li>
                    <li>Twitter</li>
                    <li>Instagram</li>
                    <li>YouTube</li>
                </ul>
            </div>
        </div>
        <hr>
        <p class="copyright">Copy right 2024 - Muhammad Usman</p>
    </div>
</div>
<!-- js for toggle menu -->
<script>
    var MenuItems = document.getElementById("MenuItems")

    MenuItems.style.maxHeight = "0px";

    function menutoggle(){
        if(MenuItems.style.maxHeight == "0px")
    
{
    MenuItems.style.maxHeight = "200px"
}
else
{
    MenuItems.style.maxHeight = "0px"
}
    }
</script>
</body>
</html>

#about.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>All Products - Redstore</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link href="//maxcdn.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css" rel="stylesheet">
<body>


 <div class="container">
        <div class="navbar">
            <div class="logo">
                <a href="index.html"> <img src="Saved Pictures/logo.png" width="125px"></a>
            </div>
            <nav>
                <ul id="MenuItems">
                    <li><a href="index.html">Home</a></li>
                    <li><a href="product.html">Products</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact</a></li>
                    <li><a href="account.html">Account</a></li>
                </ul>
            </nav>
            <img src="Saved Pictures/cart.png" width="30px" height="30px">
            <img src="Saved Pictures/menu.png" class="menu-icon" onclick="menutoggle()">
        </div>
        
    </div>

<!-- account-page -->

<div class="account-page">
    <div class="container">
        <div class="row">
            <div class="col-2">
                <img src="Saved Pictures/image1.png" width="100%">
            </div>
            <div class="col-2">
                <div class="form-container">
                    <div class="form-btn">
                       <h1>About Us</h1>
                       <hr id="Indicatorabout">
                       <br>
                       <div class="content">
                        Red store has been renewed and awaits all of you with the products of your favorite team. The experience of the online shopping really takes off with the use of innovating and modern features with orientation the philosophy of mobile through the responsive edition of tablets and smartphones!
                       </div>
                    
                    </div>
                    
                </div>
            </div>
        </div>
    </div>
</div>



<!-- footer -->
<div class="footer">
    <div class="container">
        <div class="row">
            <div class="footer-col-1">
                <h3>Download Our App</h3>
                <p>Download App for Android and ios mobile phone.</p>
                <div class="app-logo">
                    <img src="Saved Pictures/play-store.png">
                    <img src="Saved Pictures/app-store.png">
                </div>
            </div>
            <div class="footer-col-2">
                <img src="Saved Pictures/logo-white.png">
                <p>Our Purpose Is To Sustainably Make the Pleasure and Benefits of Sports Accessible to the Many.</p>
            </div>
            <div class="footer-col-3">
                <h3>Useful Links</h3>
                <ul>
                    <li>Coupons</li>
                    <li>Blog Post</li>
                    <li>Return Policy</li>
                    <li>Join Affiliate</li>
                </ul>
            </div>
            <div class="footer-col-4">
                <h3>Follow us</h3>
                <ul>
                    <li>Facebook</li>
                    <li>Twitter</li>
                    <li>Instagram</li>
                    <li>YouTube</li>
                </ul>
            </div>
        </div>
        <hr>
        <p class="copyright">Copy right 2024 - Muhammad Usman</p>
    </div>
</div>
<!-- js for toggle menu -->
<script>
    var MenuItems = document.getElementById("MenuItems")

    MenuItems.style.maxHeight = "0px";

    function menutoggle(){
        if(MenuItems.style.maxHeight == "0px")
    
{
    MenuItems.style.maxHeight = "200px"
}
else
{
    MenuItems.style.maxHeight = "0px"
}
    }
</script>
</body>
</html>

#contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>All Products - Redstore</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link href="//maxcdn.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css" rel="stylesheet">
<body>


 <div class="container">
        <div class="navbar">
            <div class="logo">
                <a href="index.html"> <img src="Saved Pictures/logo.png" width="125px"></a>
            </div>
            <nav>
                <ul id="MenuItems">
                    <li><a href="index.html">Home</a></li>
                    <li><a href="product.html">Products</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact</a></li>
                    <li><a href="account.html">Account</a></li>
                </ul>
            </nav>
            <img src="Saved Pictures/cart.png" width="30px" height="30px">
            <img src="Saved Pictures/menu.png" class="menu-icon" onclick="menutoggle()">
        </div>
        
    </div>

<!-- account-page -->

<div class="account-page">
    <div class="container">
        <div class="row">
            <div class="col-2">
                <img src="Saved Pictures/image1.png" width="100%">
            </div>
            <div class="col-2">
                <div class="form-container">
                    <div class="form-btn">
                       <h1>Contact Us</h1>
                       <hr id="Indicatorabout">
                     <br><Address> Address: Redstore Level -1
                        Canada Place
                        Canary Wharf
                        London
                        E18 5AH</Address>
                        <br>
<br>
                  <address><p>Call:+30 2284436560</p> <br>
                  <br> <p>Email Address:info@redstore.com</p> </address>   
                    </div>
                    
                </div>
            </div>
        </div>
    </div>
</div>



<!-- footer -->
<div class="footer">
    <div class="container">
        <div class="row">
            <div class="footer-col-1">
                <h3>Download Our App</h3>
                <p>Download App for Android and ios mobile phone.</p>
                <div class="app-logo">
                    <img src="Saved Pictures/play-store.png">
                    <img src="Saved Pictures/app-store.png">
                </div>
            </div>
            <div class="footer-col-2">
                <img src="Saved Pictures/logo-white.png">
                <p>Our Purpose Is To Sustainably Make the Pleasure and Benefits of Sports Accessible to the Many.</p>
            </div>
            <div class="footer-col-3">
                <h3>Useful Links</h3>
                <ul>
                    <li>Coupons</li>
                    <li>Blog Post</li>
                    <li>Return Policy</li>
                    <li>Join Affiliate</li>
                </ul>
            </div>
            <div class="footer-col-4">
                <h3>Follow us</h3>
                <ul>
                    <li>Facebook</li>
                    <li>Twitter</li>
                    <li>Instagram</li>
                    <li>YouTube</li>
                </ul>
            </div>
        </div>
        <hr>
        <p class="copyright">Copy right 2024 - Muhammad Usman</p>
    </div>
</div>
<!-- js for toggle menu -->
<script>
    var MenuItems = document.getElementById("MenuItems")

    MenuItems.style.maxHeight = "0px";

    function menutoggle(){
        if(MenuItems.style.maxHeight == "0px")
    
{
    MenuItems.style.maxHeight = "200px"
}
else
{
    MenuItems.style.maxHeight = "0px"
}
    }
</script>
</body>
</html>

#account.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>All Products - Redstore</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link href="//maxcdn.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css" rel="stylesheet">
<body>


 <div class="container">
        <div class="navbar">
            <div class="logo">
                <a href="index.html"> <img src="Saved Pictures/logo.png" width="125px"></a>
            </div>
            <nav>
                <ul id="MenuItems">
                    <li><a href="index.html">Home</a></li>
                    <li><a href="product.html">Products</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact</a></li>
                    <li><a href="account.html">Account</a></li>
                </ul>
            </nav>
            <img src="Saved Pictures/cart.png" width="30px" height="30px">
            <img src="Saved Pictures/menu.png" class="menu-icon" onclick="menutoggle()">
        </div>
        
    </div>

<!-- account-page -->

<div class="account-page">
    <div class="container">
        <div class="row">
            <div class="col-2">
                <img src="Saved Pictures/image1.png" width="100%">
            </div>
            <div class="col-2">
                <div class="form-container">
                    <div class="form-btn">
                        <span onclick="login()">Login</span>
                        <span onclick="register()">Register</span>
                        <hr id="Indicator">
                    </div>
                    <form id="LoginForm">
                        <input type="text" placeholder="Username">
                        <input type="password" placeholder="Password">
                        <button type="submit" class="btn">Login</button>
                        <a href="">Forgot password</a>
                    </form>

                    <form id="RegForm">
                        <input type="text" placeholder="Username">
                        <input type="email" placeholder="Email">
                        <input type="password" placeholder="Password">
                        <button type="submit" class="btn">Register</button>
                    </form>
                </div>
            </div>
        </div>
    </div>
</div>



<!-- footer -->
<div class="footer">
    <div class="container">
        <div class="row">
            <div class="footer-col-1">
                <h3>Download Our App</h3>
                <p>Download App for Android and ios mobile phone.</p>
                <div class="app-logo">
                    <img src="Saved Pictures/play-store.png">
                    <img src="Saved Pictures/app-store.png">
                </div>
            </div>
            <div class="footer-col-2">
                <img src="Saved Pictures/logo-white.png">
                <p>Our Purpose Is To Sustainably Make the Pleasure and Benefits of Sports Accessible to the Many.</p>
            </div>
            <div class="footer-col-3">
                <h3>Useful Links</h3>
                <ul>
                    <li>Coupons</li>
                    <li>Blog Post</li>
                    <li>Return Policy</li>
                    <li>Join Affiliate</li>
                </ul>
            </div>
            <div class="footer-col-4">
                <h3>Follow us</h3>
                <ul>
                    <li>Facebook</li>
                    <li>Twitter</li>
                    <li>Instagram</li>
                    <li>YouTube</li>
                </ul>
            </div>
        </div>
        <hr>
        <p class="copyright">Copy right 2024 - Muhammad Usman</p>
    </div>
</div>
<!-- js for toggle menu -->
<script>
    var MenuItems = document.getElementById("MenuItems")

    MenuItems.style.maxHeight = "0px";

    function menutoggle(){
        if(MenuItems.style.maxHeight == "0px")
    
{
    MenuItems.style.maxHeight = "200px"
}
else
{
    MenuItems.style.maxHeight = "0px"
}
    }
</script>

<!-- js for toggle Form -->
<script>

    var LoginForm = document.getElementById("LoginForm")
    var RegForm = document.getElementById("RegForm")
    var Indicator = document.getElementById("Indicator")

function register(){
    RegForm.style.transform = "translateX(0px)";
    LoginForm.style.transform = "translateX(0px)";
    Indicator.style.transform = "translateX(100px)";
}
function login(){
    RegForm.style.transform = "translateX(300px)";
    LoginForm.style.transform = "translateX(300px)";
    Indicator.style.transform = "translateX(0px)";
}
</script>
</body>
</html>

#style.css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    font-family: 'Poppins', sans-serif;
}
.navbar{
display: flex;
align-items: center;
padding: 20px;
}
nav{
    flex: 1;
    text-align: right;
}
nav ul{
    display: inline-block;
    list-style-type: none;
}
nav ul li{
    display: inline-block;
    margin-right: 20px;
}
a{
    text-decoration: none;
    color: #555;
}
p{
    color: #555;
}
.container{
    max-width: 1300px;
    margin: auto;
    padding-left: 25px;
    padding-right: 25px;
}
.row{
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    justify-content: space-around;
}
.col-2{
    flex-basis: 50%;
    min-width: 300px;
}
.col-2 img{
max-width: 100%;
padding: 50px 0;
}
.col-2 h1{
    font-size: 50px;
    line-height: 60px;
    margin: 25px 0;
}
.btn{
    display: inline-block;
    background: #ff523b;
    color: #fff;
    padding: 8px 30px;
    margin: 30px 0;
    border-radius: 30px;
transition: background 0.5s;
}
.btn:hover{
    background: #563434;
}
.header{
    background: radial-gradient(#fff,#ffd6d6);
}
.header .row{
    margin-top: 70px;
}
.categories{
    margin: 70px 0;
}
.col-3{
    flex-basis: 30%;
    min-width: 250px;
    margin-bottom: 30px;
}
.col-3 img{
    width: 100%;
}
.small-container{
    max-width: 1080px;
    margin: auto;
    padding-left: 25px;
    padding-right: 25px;
}
.col-4{
    flex-basis: 25%;
    padding: 10px;
    min-width: 200px;
    margin-bottom: 50px;
    transition: transform 0.5s;
}
.col-4 img{
    width: 100%;
}
.title{
    text-align: center;
    margin: 0 auto 80px;
    position: relative;
    line-height: 60px;
    color: #555;
}
.title::after{
    content: '';
    background: #ff523b;
    width: 80px;
    height: 5px;
    border-radius: 5px;
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%)
}
h4{
    color: #555;
    font-weight: normal;
}
.col-4{
    font-size: 14px;
}
.rating .fa{
    color: #ff523b;
}
.col-4:hover{
    transform: translateY(-5px);
}

/*---------offer-------*/

.offer{
    background: radial-gradient(#fff,#ffd6d6);
    margin-top: 80px;
    padding: 30px 0;
}
.col-2 .offer-img{
    padding: 50px;
}
small{
    color: #555;
}
/*----------------- testimonial------------- */
.testimonial{
    padding-top: 100px;
}
.testimonial .col-3{
    text-align: center;
    padding: 40px 20px;
    box-shadow: 0 0 20px 0px rgba(0, 0, 0, 0.1);
    cursor: pointer;
    transition: transform 0.5s;
}
.testimonial .col-3 img{
    width: 50px;
    margin-top: 20px;
    border-radius: 50%;
}
.testimonial .col-3:hover{
    transform: translateY(-10px);
}
.fa.fa-quote-left{
    font-size: 34px;
    color:#ff523b;
}
.col-3.p{
    font-size: 12px;
    margin: 12px 0;
    color: #777;
}
.testimonial .col-3 h3{
    font-weight: 600;
    color: #555;
    font-size: 16px;
}
/* -------------------brands------------------ */
.brands{
    margin: 100px auto;
}
.col-5{
    width: 160px;
}
.col-5 img{
    width: 100%;
    cursor: pointer;
    filter: grayscale(100%);
}
.col-5 img:hover{
    filter: grayscale(0);
}
/* ------------footer------------ */
.footer{
    background: #000;
    color: #8a8a8a;
    font-size: 14px;
    padding: 60px 0 20px;
}
.footer p{
    color: #8a8a8a;
}
.footer h3{
color: #fff;
margin-bottom: 20px;
}
.footer-col-1, .footer-col-2, .footer-col-3, .footer-col-4{
    min-width: 250px;
    margin-bottom: 20px;
}
.footer-col-1{
    flex-basis: 30%;
}
.footer-col-2{
    flex: 1;
    text-align: center;
}
.footer-col-2 img{
    width: 180px;
    margin-bottom: 20px;
}
.footer-col-3, .footer-col-4{
flex-basis: 12%;
text-align: center;
}
ul{
    list-style-type: none;
}
.app-logo{
    margin-top: 20px;
}
.app-logo img{
    width: 140px;
}
.footer hr{
    border: none;
    background: #b5b5b5;
    height: 1px;
    margin: 20px 0;
}
.copyright{
    text-align: center;
}
.menu-icon{
    width: 28px;
    margin-left: 20px;
    display: none;
}
/* -------------------media query for menu------------------- */
@media only screen and (max-width: 800px){

    nav ul{
        position: absolute;
        top: 70px;
        left: 0;
        background: #333;
        width: 100%;
        overflow: hidden;
        transition: max-height 0.5s;
    }
    nav ul li{
        display: block;
        margin-right: 50px;
        margin-top: 10px;
        margin-bottom: 10px;
    }
    nav ul li a{
color: #fff;
}
.menu-icon{
    display: block;
    cursor: pointer;
}
}
/* ---------------all products page------------------ */
.row-2{
    justify-content: space-between;
    margin: 100px auto 50px;
}
select{
    border: 1px solid #ff523b;
    padding: 5px;
}
select:focus{
    outline: none;
}
.page-btn{
    margin: 0 auto 80px;
}
.page-btn span{
    display: inline-block;
    border: 1px solid #ff523b;
    margin-left: 10px;
    width: 40px;
    height: 40px;
    text-align: center;
    line-height: 40px;
    cursor: pointer;
}
.page-btn span:hover{
    background: #ff523b;
    color: #fff;
}

/* ----------account pagr------------ */
.account-page{
    padding: 50px 0;
    background: radial-gradient(#fff,#ffd6d6);
}
.form-container{
    background:#fff ;
    width: 300px;
    height: 400px;
    position: relative;
    text-align: center;
    padding: 20px 0;
    margin: auto;
    box-shadow:0 0 20px 0px rgba(0, 0, 0, 0.1) ;
    overflow: hidden;
}
.form-container span{
    font-weight: bold;
    padding: 0 10px;
    color: #555;
    cursor: pointer;
    width: 100px;
    display: inline-block;
}
.form-btn{
    display: inline-block;
}
.form-container form{
    max-width: 300px;
    padding: 0 20px;
    position: absolute;
    top: 130px;
    transition: transform 1s;

}
form input{
    width: 100%;
    height: 30px;
    margin: 10px 0;
    padding: 0 10px;
    border: 1px solid #ccc;
}
form .btn{
    width: 100%;
    border: none;
    cursor: pointer;
    margin: 10px 0;
}
form .btn:focus{
    outline: none;
}
#LoginForm{
    left: -300px;
}
#RegForm{
    left: 0;
}
form a{
    font-size: 12px;
}
#Indicator{
    width: 100px;
    border: none;
    background: #ff523b;
    height: 3px;
    margin-top: 8px;
    transform: translateX(100px);
    transition: transform 1s;
}
/* --------about--------- */
.Indicatorabout{
    width: 100%;
    border: none;
    background: #ff523b;
    height: 3px;
    margin-top: 8px;
    transform: translateX(100px);
    transition: transform 1s;
}
/* ----------media query for menu less than 600 screen size---------------- */
@media only screen and (max-width: 600px){
   .row{
    text-align: center;
   }
   .col-2, .col-3, .col-4{
flex-basis: 100%;
   }
}



Deployment
This Project is deployed at Vercel.com

  https://project-ecomerce-store.vercel.app/index.html
Feedback
If you have any feedback, please reach out to us my gmail account wwwusmancom745@gmail.com
