<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Santosh BK - Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
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
        .hero h2 {
            font-size: 24px;
            margin-top: 10px;
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
        <img src="prfile img.png" fullcreen="Santosh BK" class="profile-pic">
        <p>Passionate about creating visually appealing designs and coding amazing web experiences.</p>
        <a href="#contact" class="button">Contact Me</a>
    </section>
    <section id="home" style="
    height: 100vh;
    background: url('10ad86b0-51b2-4e0a-879d-97606fde92f3.png') no-repeat center center/cover;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: white;
    position: relative;">
    
    <div style="
        background-color: rgba(0, 0, 0, 0.5);
        padding: 40px;
        border-radius: 10px;
        max-width: 90%;
        backdrop-filter: blur(4px);">
        
        <h1 style="font-size: 48px; font-weight: bold;">Hey, I'm <span style="color: #f4a261;">Santosh BK</span></h1>
        <h2 style="font-size: 24px; margin: 20px 0;">Graphic Designer & Developer</h2>
        <p style="font-size: 18px; margin-bottom: 30px;">
            I create stylish visuals and smart websites that make an impact.
        </p>
        <a href="#contact" class="button" style="
            background-color: #f4a261;
            padding: 12px 30px;
            border-radius: 6px;
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            font-size: 16px;
            transition: background 0.3s;">
            Contact Me
        </a>
    </div>
</section>

    
    <section id="about" class="section">
        <h2>About Me</h2>
        <p>My name is Santosh BK. I have one year of experience in graphic design and skills in Java, Adobe Illustrator, and Adobe Photoshop.</p>
    </section>
    
    <section id="projects" class="section">
        <h2>Projects</h2>
        <div class="project">
            <h3>Graphic design </h3>
            <p>Designed promotional materials such as posters, banners, and social media graphics.</p>
        </div>
        <div class="project">
            <h3>Webdesign</h3>
            <p>Description of the project.</p>
        </div>
    </section>

    <section id="home" class="hero" style="display: flex; flex-wrap: wrap; align-items: center; justify-content: space-between; padding: 60px 10%; background: #f9f9f9;">
        <div style="flex: 1; min-width: 300px; max-width: 600px;">
            <h1 style="font-size: 36px; color: #222;">Your <span style="color: #f4a261;">Creative Designer</span> Santosh</h1>
            <p style="font-size: 18px; color: #444; margin: 20px 0;">
                Passionate Graphic Designer and Developer skilled in Java, HTML, Python and Adobe Photoshop & Illustrator.
            </p>
            <a href="#contact" class="button" style="background: #007bff; color: white; padding: 12px 25px; border-radius: 5px; font-weight: bold; text-decoration: none;">Get Started</a>
        </div>
        <div style="flex: 1; min-width: 300px; text-align: center;">
            <img src="prfile img.png" alt="Santosh BK" style="max-width: 40%; height: auto; border-radius: 5px;">
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
