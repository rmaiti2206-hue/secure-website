# secure-website
<!DOCTYPE html>
<html>
<head>
<title>My E-Commerce Store</title>

<style>

body{
font-family: Arial;
margin:0;
background:#f4f4f4;
}

/* Navbar */

.navbar{
background:#222;
color:white;
padding:15px;
display:flex;
justify-content:space-between;
}

.navbar a{
color:white;
text-decoration:none;
margin:0 15px;
}

/* Hero Section */

.hero{
background:#0077ff;
color:white;
text-align:center;
padding:40px;
}

.hero h1{
margin:0;
}

/* Product Section */

.products{
display:flex;
justify-content:center;
flex-wrap:wrap;
padding:20px;
}

.product-card{
background:white;
width:250px;
margin:15px;
border-radius:10px;
box-shadow:0 4px 10px rgba(0,0,0,0.1);
text-align:center;
padding:20px;
}

.product-card img{
width:100%;
border-radius:10px;
}

.price{
color:green;
font-size:20px;
margin:10px 0;
}

button{
background:#0077ff;
color:white;
border:none;
padding:10px 15px;
border-radius:5px;
cursor:pointer;
}

button:hover{
background:#0056cc;
}

/* Footer */

footer{
background:#222;
color:white;
text-align:center;
padding:15px;
margin-top:20px;
}

</style>
</head>

<body>

<!-- Navbar -->

<div class="navbar">
<div><b>MyShop</b></div>

<div>
<a href="#">Home</a>
<a href="#">Products</a>
<a href="#">Cart</a>
<a href="#">Contact</a>
</div>
</div>

<!-- Hero -->

<div class="hero">
<h1>Welcome to My Online Store</h1>
<p>Best Deals Everyday</p>
</div>

<!-- Products -->

<div class="products">

<div class="product-card">
<img src="https://via.placeholder.com/250">
<h3>Smart Watch</h3>
<p class="price">₹2999</p>
<button>Add to Cart</button>
</div>

<div class="product-card">
<img src="https://via.placeholder.com/250">
<h3>Wireless Headphones</h3>
<p class="price">₹1999</p>
<button>Add to Cart</button>
</div>

<div class="product-card">
<img src="https://via.placeholder.com/250">
<h3>Running Shoes</h3>
<p class="price">₹2499</p>
<button>Add to Cart</button>
</div>

<div class="product-card">
<img src="https://via.placeholder.com/250">
<h3>Gaming Mouse</h3>
<p class="price">₹999</p>
<button>Add to Cart</button>
</div>

</div>

<!-- Footer -->

<footer>
<p>© 2026 MyShop E-Commerce Website</p>
</footer>

</body>
</html>
