# my-code
<!DOCTYPE html>
<html lang="en2">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Santosh BK - Portfolio</title>
    <link rel="stylesheet" href="prifile img.png">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #f5ebe0, #d6a07e);
            color: #333;
        }
        header {
            background: rgba(255, 255, 255, 0.8);
            padding: 20px;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            text-align: right;
        }
        nav ul li {
            display: inline;
            margin: 0 20px;
        }
        nav ul li a {
            color: #333;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #b5651d;
        }
        .hero {
            margin-top: 120px;
            text-align: center;
            padding: 50px;
        }
        .profile-pic {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid #b5651d;
            margin: 20px 0;
        }
        .hero h1 {
            font-size: 36px;
            font-weight: bold;
        }
        .hero p {
            font-size: 18px;
        }
        .section {
            padding: 60px 20px;
            max-width: 800px;
            margin: auto;
            text-align: center;
        }
        .button {
            display: inline-block;
            background: #b5651d;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s;
        }
        .button:hover {
            background: #894312;
        }
        footer {
            background: rgba(255, 255, 255, 0.8);
            padding: 15px;
            text-align: center;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home" class="hero">
        <h1>Hey, I'm <span style="color: #b5651d;">Santosh BK</span></h1>
        <h2>I'm a <span style="color: #b5651d;">Graphic Designer & Developer</span></h2>
        <img src="profile.jpg" alt="Santosh BK" class="profile-pic">
        <p>Passionate about creating visually appealing designs and coding amazing web experiences.</p>
        <a href="#contact" class="button">Contact Me</a>
    </section>
    
    <section id="about" class="section">
        <h2>About Me</h2>
        <p>My name is Santosh BK. I have one year of experience in graphic design and skills in Java, Adobe Illustrator, and Adobe Photoshop.</p>
    </section>
    
    <section id="projects" class="section">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project Title 1</h3>
            <p>Description of the project.</p>
        </div>
        <div class="project">
            <h3>Project Title 2</h3>
            <p>Description of the project.</p>
        </div>
    </section>
    
    <section id="contact" class="section">
        <h2>Contact Me</h2>
        <p>Email: santosu3368@gmail.com</p>
        <p>Phone: 07017328516</p>
        <p>Address: 神戸市東灘区御影石町1丁目8番23-701号</p>
    </section>
    
    <footer>
        <p>&copy; 2025 Santosh BK. All rights reserved.</p>
    </footer>
</body>
</html>
