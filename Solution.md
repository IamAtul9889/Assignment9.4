```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Creative Studio</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f8fafc;
            color: #1e293b;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 8%;
            background: #1e293b;
            color: white;
        }

        nav {
            display: flex;
            gap: 25px;
        }

        nav a {
            color: white;
            text-decoration: none;
        }

        .hero {
            display: grid;
            grid-template-columns: 1fr 1fr;
            align-items: center;
            gap: 40px;
            padding: 60px 8%;
        }

        .hero h1 {
            font-size: 48px;
        }

        .hero p {
            line-height: 1.7;
        }

        .hero img {
            width: 100%;
            border-radius: 12px;
        }

        .btn {
            display: inline-block;
            background: #2563eb;
            color: white;
            padding: 12px 24px;
            border-radius: 6px;
            text-decoration: none;
        }

        .features {
            padding: 40px 8%;
            text-align: center;
        }

        .cards {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }

        .card {
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 2px 8px #00000015;
        }

        footer {
            background: #1e293b;
            color: white;
            text-align: center;
            padding: 20px;
        }

        @media (max-width: 700px) {
            header {
                flex-direction: column;
                gap: 15px;
            }

            nav {
                gap: 15px;
            }

            .hero {
                grid-template-columns: 1fr;
                padding: 30px 5%;
            }

            .hero h1 {
                font-size: 34px;
            }

            .cards {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

<header>
    <h2>CreativeStudio</h2>
    <nav>
        <a href="#">Home</a>
        <a href="#features">Features</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <div>
        <h1>Build Something Amazing</h1>
        <p>Create modern websites with beautiful designs and powerful features.</p>
        <a href="#features" class="btn">Get Started</a>
    </div>
    <img src="https://picsum.photos/id/0/600/400" alt="Laptop workspace">
</section>

<section id="features" class="features">
    <h2>Our Features</h2>
    <div class="cards">
        <div class="card">
            <h3>Modern Design</h3>
            <p>Beautiful and clean website layouts.</p>
        </div>
        <div class="card">
            <h3>Fast Performance</h3>
            <p>Simple and efficient user experience.</p>
        </div>
        <div class="card">
            <h3>Responsive Layout</h3>
            <p>Works on desktop, tablet, and mobile.</p>
        </div>
    </div>
</section>

<footer id="contact">
    <p>© 2026 CreativeStudio</p>
</footer>

</body>
</html>
```