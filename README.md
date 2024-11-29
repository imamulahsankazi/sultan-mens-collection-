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
/* Basic reset and universal styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

/* Header Section */
header {
    background-color: #2c3e50;
    color: white;
    padding: 20px;
    text-align: center;
}

header h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 1.1em;
}

nav ul li a:hover {
    text-decoration: underline;
}

/* Homepage Section */
#home {
    text-align: center;
    background-color: #ecf0f1;
    padding: 50px 0;
}

#home h2 {
    font-size: 2em;
    color: #2c3e50;
}

#home p {
    font-size: 1.2em;
    color: #7f8c8d;
}

/* Products Section */
#products {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    padding: 20px 0;
}

.product {
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    width: 280px;
    margin: 15px;
    transition: transform 0.3s ease;
}

.product img {
    width: 100%;
    border-radius: 8px;
    height: 200px;
    object-fit: cover;
}

.product h3 {
    font-size: 1.5em;
    margin-top: 15px;
    color: #2c3e50;
}

.product p {
    color: #7f8c8d;
    margin: 10px 0;
}

.product button {
    background-color: #28a745;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.product button:hover {
    background-color: #218838;
}

.product:hover {
    transform: translateY(-10px);
}

/* Contact Form Styles */
#contact {
    padding: 50px 20px;
    background-color: #ecf0f1;
    text-align: center;
}

#contact h2 {
    font-size: 2em;
    color: #2c3e50;
}

form {
    max-width: 600px;
    margin: 0 auto;
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

form input, form textarea {
    width: 100%;
    padding: 12px;
    margin-bottom: 15px;
    border-radius: 5px;
    border: 1px solid #ccc;
}

form button {
    background-color: #3498db;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 1.1em;
}

form button:hover {
    background-color: #2980b9;
}

/* Footer Styles */
footer {
    background-color: #2c3e50;
    color: white;
    padding: 15px 0;
    text-align: center;
}

footer p {
    font-size: 1.1em;
}![1000016773](https://github.com/user-attachments/assets/67d934fe-0897-42bb-af4e-b3885fa2c452)
