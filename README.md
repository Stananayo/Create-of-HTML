<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Sample HTML5 Document</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            line-height: 1.6;
        }
        header, footer {
            background-color: #f8f8f8;
            padding: 10px;
            text-align: center;
            border: 1px solid #ddd;
        }
        main {
            margin: 20px 0;
        }
        section {
            margin-bottom: 20px;
        }
        article {
            background-color: #eef;
            padding: 10px;
            border: 1px solid #bbc;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to My Website</h1>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<main>
    <section id="about">
        <h2>About Us</h2>
        <article>
            <h3>Our Mission</h3>
            <p>We strive to provide the best services to our clients, ensuring maximum satisfaction and quality.</p>
        </article>
        <article>
            <h3>Our History</h3>
            <p>Founded in 2021, our company has grown from a small startup into a leading enterprise in our field.</p>
        </article>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Consulting</li>
            <li>Product Development</li>
            <li>Customer Support</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form action="/submit-form" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required />

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required />

            <input type="submit" value="Send" />
        </form>
    </section>
</main>

<footer>
    <p>&copy; 2023 My Company. All rights reserved.</p>
</footer>

</body>
</html>
