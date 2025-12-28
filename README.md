<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Bhargav Fashion</title>

<style>
*{margin:0;padding:0;box-sizing:border-box}
body{font-family:Arial;background:#f4f4f4}

/* HEADER */
header{
    background:#ff3c00;
    color:white;
    text-align:center;
    padding:20px;
}
header img{
    height:60px;
    margin-bottom:10px;
}

/* NAV */
nav{
    background:#222;
    display:flex;
    justify-content:center;
}
nav a{
    color:white;
    padding:15px;
    text-decoration:none;
    font-weight:bold;
}
nav a:hover{background:#ff3c00}

/* PRODUCTS */
.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:20px;
    padding:20px;
}
.product{
    background:white;
    padding:10px;
    border-radius:10px;
    text-align:center;
}
.product img{
    width:100%;
    border-radius:10px;
}
.product button{
    background:#ff3c00;
    color:white;
    border:none;
    padding:10px;
    width:100%;
    border-radius:5px;
    cursor:pointer;
}

/* GALLERY */
.gallery{
    padding:20px;
    background:white;
}
.gallery h2{
    text-align:center;
    color:#ff3c00;
    margin-bottom:15px;
}
.gallery-images{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
}
.gallery-images img{
    width:250px;
    margin:10px;
    border-radius:10px;
}

/* PAYMENT */
.payment{
    background:white;
    margin:20px;
    padding:20px;
    text-align:center;
    border-radius:10px;
}
.payment input{
    width:90%;
    padding:10px;
    margin:10px 0;
}
.payment button{
    background:#ff3c00;
    color:white;
    padding:12px;
    width:90%;
    border:none;
    border-radius:5px;
    font-size:16px;
}

/* FOOTER */
footer{
    background:#222;
    color:white;
    text-align:center;
    padding:15px;
}
</style>
</head>

<body>

<!-- HEADER -->
<header>
    <img src="https://via.placeholder.com/200x60?text=LOGO" alt="Logo">
    <h1>Bhargav Fashion</h1>
</header>

<!-- NAV -->
<nav>
    <a href="#shop">Shop</a>
    <a href="#gallery">Gallery</a>
    <a href="#payment">Payment</a>
</nav>

<!-- PRODUCTS -->
<section id="shop" class="products">

    <div class="product">
        <img src="https://via.placeholder.com/300x300?text=T-Shirt">
        <h3>Red T‑Shirt</h3>
        <p>₹499</p>
        <button>Add to Cart</button>
    </div>

    <div class="product">
        <img src="https://via.placeholder.com/300x300?text=Jeans">
        <h3>Blue Jeans</h3>
        <p>₹899</p>
        <button>Add to Cart</button>
    </div>

    <div class="product">
        <img src="https://via.placeholder.com/300x300?text=Jacket">
        <h3>Black Jacket</h3>
        <p>₹1299</p>
        <button>Add to Cart</button>
    </div>

    <div class="product">
        <img src="https://via.placeholder.com/300x300?text=Shoes">
        <h3>White Shoes</h3>
        <p>₹1499</p>
        <button>Add to Cart</button>
    </div>

</section>

<!-- GALLERY -->
<section id="gallery" class="gallery">
<h2>Product Gallery</h2>
<div class="gallery-images">
    <img src="https://via.placeholder.com/400x300?text=Fashion+1">
    <img src="https://via.placeholder.com/400x300?text=Fashion+2">
    <img src="https://via.placeholder.com/400x300?text=Fashion+3">
</div>
</section>

<!-- PAYMENT -->
<section id="payment" class="payment">
<h2>Pay via UPI</h2>
<p><b>UPI ID:</b> Shihorabhargav0@oksbi</p>
<input type="text" placeholder="Your Name">
<input type="number" placeholder="Mobile Number">
<button onclick="alert('Order Placed Successfully')">Pay & Order</button>
</section>

<!-- FOOTER -->
<footer>
© 2025 Bhargav Fashion | All Rights Reserved
</footer>

</body>
</html>
