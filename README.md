<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bhargav Fashion</title>
    <style>
        * { margin:0; padding:0; box-sizing:border-box; }
        body { font-family: Arial, sans-serif; background:#f5f5f5; color:#333; }
        
        /* Header */
        header { background:#ff3c00; color:#fff; padding:20px; text-align:center; }
        header img { height:60px; display:block; margin:0 auto 10px; }
        header h1 { font-size:2rem; }

        /* Navigation */
        nav { display:flex; justify-content:center; background:#222; }
        nav a { color:#fff; text-decoration:none; margin:0 15px; padding:15px; display:inline-block; }
        nav a:hover { background:#ff3c00; border-radius:5px; }

        /* Products Section */
        .products { display:grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap:20px; padding:20px; }
        .product { background:#fff; border-radius:10px; padding:10px; text-align:center; box-shadow:0 0 10px rgba(0,0,0,0.1); }
        .product img { width:100%; border-radius:10px; }
        .product h3 { margin:10px 0; }
        .product p { margin:5px 0; }
        .product button { padding:10px 20px; background:#ff3c00; color:#fff; border:none; border-radius:5px; cursor:pointer; font-weight:bold; }
        .product button:hover { background:#e63900; }

        /* Gallery Section */
        .gallery { padding:20px; }
        .gallery h2 { text-align:center; margin-bottom:20px; color:#ff3c00; }
        .gallery img { width:100%; max-width:300px; margin:10px; border-radius:10px; display:inline-block; }

        /* Payment Section */
        .payment { padding:20px; text-align:center; background:#fff; margin:20px; border-radius:10px; box-shadow:0 0 10px rgba(0,0,0,0.1); }
        .payment input, .payment button { display:block; width:90%; max-width:400px; margin:10px auto; padding:10px; border-radius:5px; border:none; font-size:1rem; }
        .payment button { background:#ff3c00; color:#fff; cursor:pointer; font-weight:bold; }
        .payment button:hover { background:#e63900; }

        /* Footer */
        footer { text-align:center; padding:20px; background:#222; color:#fff; margin-top:20px; }

        @media(max-width:600px){ 
            nav { flex-direction:column; }
            nav a { margin:5px 0; }
        }
    </style>
</head>
<body>

    <!-- Header with Logo -->
    <header>
        <img src="logo.png" alt="Bhargav Fashion Logo">
        <h1>Bhargav Fashion</h1>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#home">Home</a>
        <a href="#shop">Shop</a>
        <a href="#gallery">Gallery</a>
        <a href="#payment">Cart/Payment</a>
    </nav>

    <!-- Products Section -->
    <section id="shop" class="products">
        <div class="product">
            <img src="https://i.ibb.co/7C7R5B0/product1.jpg" alt="Red T-Shirt">
            <h3>Red T-Shirt</h3>
            <p>Price: ₹499</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://i.ibb.co/2k7k1hT/product2.jpg" alt="Blue Jeans">
            <h3>Blue Jeans</h3>
            <p>Price: ₹899</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://i.ibb.co/2nQ5Tjk/product3.jpg" alt="Black Jacket">
            <h3>Black Jacket</h3>
            <p>Price: ₹1299</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://i.ibb.co/q7k1Qm0/product4.jpg" alt="White Sneakers">
            <h3>White Sneakers</h3>
            <p>Price: ₹1499</p>
            <button>Add to Cart</button>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="gallery">
        <h2>Gallery</h2>
        <img src="https://i.ibb.co/Tr0R2p6/freefire1.jpg" alt="Gallery Image 1">
        <img src="https://i.ibb.co/Y8wXYdG/freefire2.jpg" alt="Gallery Image 2">
        <img src="https://i.ibb.co/7C7R5B0/product1.jpg" alt="Gallery Image 3">
    </section>

    <!-- Payment Section -->
    <section id="payment" class="payment">
        <h2>Checkout & Pay via UPI</h2>
        <p>UPI ID: <strong>Shihorabhargav0@oksbi</strong></p>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Email" required>
        <input type="number" placeholder="Contact Number" required>
        <button onclick="alert('Payment successful! Your order is confirmed.')">Pay & Order</button>
    </section>

    <!-- Footer -->
    <footer>
        &copy; 2025 Bhargav Fashion. All rights reserved.
    </footer>

</body>
</html>
