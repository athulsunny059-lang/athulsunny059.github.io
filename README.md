<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Photography Portfolio</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #000;
            color: white;
        }

        /* Header */
        header {
            height: 90vh;
            background: url('https://images.unsplash.com/photo-1503264116251-35a269479413') center/cover no-repeat;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        header h1 {
            font-size: 55px;
            margin: 0;
            letter-spacing: 2px;
        }
        header p {
            font-size: 22px;
            margin-top: 10px;
        }

        /* Navigation */
        nav {
            position: sticky;
            top: 0;
            background: #111;
            padding: 15px;
            text-align: center;
            z-index: 10;
        }
        nav a {
            color: white;
            margin: 15px;
            text-decoration: none;
            font-size: 18px;
        }

        /* Sections */
        section {
            padding: 40px;
            max-width: 1000px;
            margin: auto;
        }

        /* Gallery */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
        }
        .gallery img {
            width: 100%;
            height: 230px;
            object-fit: cover;
            border-radius: 10px;
            transition: 0.3s;
        }
        .gallery img:hover {
            transform: scale(1.07);
        }

        /* Card */
        .card {
            background: #111;
            padding: 25px;
            border-radius: 10px;
        }

        /* Footer */
        footer {
            background: #111;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
        }
    </style>
</head>

<body>

<!-- Header -->
<header>
    <h1>My Photography</h1>
    <p>Capturing moments • Creating memories</p>
</header>

<!-- Navigation -->
<nav>
    <a href="#gallery">Gallery</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<!-- Gallery -->
<section id="gallery">
    <h2>Photography Gallery</h2>
    <div class="gallery">
        <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee">
        <img src="https://images.unsplash.com/photo-1519681393784-d120267933ba">
        <img src="https://images.unsplash.com/photo-1469474968028-56623f02e42e">
        <img src="https://images.unsplash.com/photo-1470770903676-69b98201ea1c">
        <img src="https://images.unsplash.com/photo-1472214103451-9374bd1c798e">
        <img src="https://images.unsplash.com/photo-1517694712202-14dd9538aa97">
    </div>
</section>

<!-- About -->
<section id="about">
    <div class="card">
        <h2>About Me</h2>
        <p>
            Hi! I'm a passionate photographer who loves capturing nature, portraits, and real-life moments.
            Photography is not just my profession — it's my emotion and creativity.
        </p>
    </div>
</section>

<!-- Contact -->
<section id="contact">
    <div class="card">
        <h2>Contact Me</h2>
        <p>Email: yourname@example.com</p>
        <p>Instagram: @yourprofile</p>
    </div>
</section>

<!-- Footer -->
<footer>
    <p>© 2025 My Photography Portfolio</p>
</footer>

</body>
</html>
