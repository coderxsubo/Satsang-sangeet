<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Landing Page</title>
    <style>
        /* General Styles */
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background: #1e1e2f;
            color: white;
            text-align: center;
        }

        /* Navbar */
        nav {
            display: flex;
            justify-content: space-between;
            padding: 20px;
            background: #161623;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        .nav-links li {
            display: inline;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            transition: 0.3s;
        }

        .nav-links a:hover {
            color: #ff4c60;
        }

        /* Hero Section */
        .hero {
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .hero h1 {
            font-size: 48px;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 20px;
            opacity: 0.8;
        }

        /* Button */
        .btn {
            margin-top: 20px;
            padding: 12px 24px;
            background: #ff4c60;
            color: white;
            text-decoration: none;
            font-size: 18px;
            border-radius: 8px;
            transition: 0.3s;
        }

        .btn:hover {
            background: #ff3045;
        }
    </style>
</head>
<body>

    <header>
        <nav>
            <div class="logo">S U B _ X</div>
            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Welcome to My Website</h1>
        <p>A modern and minimalistic landing page.</p>
        <a href="#" class="btn">Get Started</a>
    </section>

</body>
</html>