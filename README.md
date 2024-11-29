# sultan-mens-collection-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sultan Men's Collection - Ready-Made Clothing for Men</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Sultan Men's Collection</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Homepage Section -->
    <section id="home">
        <h2>Welcome to Sultan Men's Collection</h2>
        <p>Your destination for stylish and ready-made men's clothing. High-quality fabrics, tailored for modern men.</p>
    </section>

    <!-- Product Section -->
    <section id="products">
        <h2>Our Featured Products</h2>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Product 1">
            <h3>Classic Suit</h3>
            <p>Perfectly tailored, high-quality suit for formal occasions.</p>
            <p>Price: $99.99</p>
            <button class="snipcart-add-item"
                    data-item-id="product1"
                    data-item-name="Classic Suit"
                    data-item-price="99.99"
                    data-item-url="/"
                    data-item-description="Perfectly tailored, high-quality suit for formal occasions.">
                    Add to Cart
            </button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Product 2">
            <h3>Casual Shirt</h3>
            <p>Comfortable, stylish shirt for everyday wear.</p>
            <p>Price: $39.99</p>
            <button class="snipcart-add-item"
                    data-item-id="product2"
                    data-item-name="Casual Shirt"
                    data-item-price="39.99"
                    data-item-url="/"
                    data-item-description="Comfortable, stylish shirt for everyday wear.">
                    Add to Cart
            </button>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <form action="mailto:your-email@example.com" method="POST" enctype="text/plain">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br><br>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Sultan Men's Collection</p>
    </footer>

    <!-- Snipcart Integration -->
    <script src="https://cdn.snipcart.com/themes/v3.0.0/default/snipcart.js"></script>
    <div hidden id="snipcart" data-api-key="your-snippet-api-key"></div>
</body>
</html>
