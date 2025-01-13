<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        .nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }

        .nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }

        .nav a:hover {
            background-color: #ddd;
            color: black;
        }

        .section {
            padding: 50px 20px;
            text-align: center;
        }

        .about, .skills, .contact {
            background-color: white;
            margin: 20px 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
        }

        .about h2, .skills h2, .contact h2 {
            margin: 0;
            color: #333;
        }

        .about p, .skills p, .contact p {
            color: #666;
            line-height: 1.6;
        }

        .contact form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .contact input, .contact textarea {
            width: 300px;
            padding: 10px;
            margin: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .contact button {
            background-color: #333;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .contact button:hover {
            background-color: #555;
        }

        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 20px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Your Name</h1>
        <p>Web Developer | Designer</p>
    </header>

    <div class="nav">
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
    </div>

    <div id="about" class="section about">
        <h2>About Me</h2>
        <p>Hello! I'm a passionate web developer with experience in front-end and back-end development. I enjoy creating user-friendly and responsive websites.</p>
    </div>

    <div id="skills" class="section skills">
        <h2>Skills</h2>
        <p>HTML, CSS, JavaScript, PHP, MySQL, Laravel, React, Node.js</p>
    </div>

    <div id="contact" class="section contact">
        <h2>Contact Me</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </div>

    <footer>
        <p>&copy; 2025 Your Name</p>
    </footer>

</body>
</html>
