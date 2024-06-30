# yourusername.github.io.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alison Connor - Website Designer & Copywriter</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: #fff;
            padding: 15px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .section-title {
            margin-top: 0;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
        }
        .contact-form label {
            margin-bottom: 5px;
        }
        .contact-form input, .contact-form textarea {
            margin-bottom: 15px;
            padding: 10px;
            border: 1px solid #ccc;
        }
        .contact-form button {
            padding: 10px;
            background-color: #333;
            color: #fff;
            border: none;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>

<header>
    <h1>Alison Connor</h1>
    <p>Website Designer, Fortune 500 Copywriter, and Creative</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About Me</a>
    <a href="#contact">Contact</a>
    <a href="#pricing">Pricing</a>
</nav>

<div class="container" id="home">
    <h2 class="section-title">Welcome to My Website</h2>
    <p>Hello! I'm Alison Connor, a passionate website designer and copywriter with years of experience working with Fortune 500 companies. I create elegant, professional, and modern websites that stand out.</p>
</div>

<div class="container" id="about">
    <h2 class="section-title">About Me</h2>
    <p>I am a creative professional with a keen eye for detail and a passion for designing and writing. My journey began with a love for art and technology, and over the years, I've honed my skills to become a successful website designer and copywriter. I have had the privilege of working with top-tier companies, delivering high-quality content and designs that meet their needs and exceed their expectations.</p>
</div>

<div class="container" id="contact">
    <h2 class="section-title">Contact Me</h2>
    <form class="contact-form">
        <label for="name">Name</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email</label>
        <input type="email" id="email" name="email" required>
        
        <label for="message">Message</label>
        <textarea id="message" name="message" rows="5" required></textarea>
        
        <button type="submit">Send Message</button>
    </form>
</div>

<div class="container" id="pricing">
    <h2 class="section-title">Pricing</h2>
    <p>Please contact me for a detailed quote. I offer competitive rates and tailor my services to meet your specific needs.</p>
</div>

<footer>
    <p>&copy; 2024 Alison Connor. All rights reserved.</p>
</footer>

</body>
</html>

