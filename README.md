<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Burger Haven</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Burger Haven</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="order.html">Order</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h2>Welcome to Burger Haven</h2>
            <p>Delicious burgers, crispy fries, and savory hotdogs made fresh just for you!</p>
            <p><a href="about.html">Learn more about us</a></p>
        </section>
        <section id="about">
            <h2>About Us</h2>
            <p>Burger Haven is dedicated to serving high-quality fast food with fresh ingredients and great taste.</p>
            <p><a href="menu.html">Check out our menu</a></p>
        </section>
        <section id="menu">
            <h2>Our Menu</h2>
            <ul>
                <li>Burgers</li>
                <li>Fries</li>
                <li>Hotdogs</li>
                <li>Drinks</li>
            </ul>
            <p><a href="order.html">Place your order now</a></p>
        </section>
        <section id="order">
            <h2>Order Now</h2>
            <p>Place your order online and enjoy delicious food at your convenience.</p>
            <form>
                <label for="item">Select Item:</label>
                <select id="item" name="item">
                    <option value="burger">Burger</option>
                    <option value="fries">Fries</option>
                    <option value="hotdog">Hotdog</option>
                </select>
                <label for="quantity">Quantity:</label>
                <input type="number" id="quantity" name="quantity" min="1" value="1">
                <button type="submit">Order Now</button>
            </form>
            <p><a href="contact.html">Contact us for inquiries</a></p>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <p>Email: contact@burgerhaven.com</p>
            <p>Phone: (123) 456-7890</p>
            <p><a href="index.html">Return to Home</a></p>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Burger Haven. All rights reserved.</p>
    </footer>
</body>
</html>
