<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Online Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>My Online Store</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#products">Products</a></li>
            <li><a href="#products">Products</a></li>
        
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="products">
        <h2>Products</h2>
        <div class="product">
            <img src="product1.jpg" alt="Product 1">
            <h3>Product 1</h3>
            <p>$10.00</p>
            <button onclick="addToCart('Product 1', 10.00)">Add to Cart</button>
        </div>
        <div class="product">
            <img src="product2.jpg" alt="Product 2">
            <h3>Product 2</h3>
            <p>$15.00</p>
            <button onclick="addToCart('Product 2', 15.00)">Add to Cart</button>
        </div>
        <!-- Add more products as needed -->
    </section>

    <aside id="cart">
        <h2>Shopping Cart</h2>
        <ul id="cart-items">
            <!-- Cart items will be added here by JavaScript -->
        </ul>
        <p>Total: $<span id="total">0.00</span></p>
        <button onclick="checkout()">Checkout</button>
    </aside>

    <footer>
        <p>&copy; 2024 My Online Store</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>


