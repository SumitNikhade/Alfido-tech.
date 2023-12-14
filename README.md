# page-html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            background-color: #333333;
            color: white;
            padding: 10px;
            text-align: center;
        }

        nav {
            background-color: blue;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 10px;
            margin: 0 10px;
        }

        nav a:hover {
            background-color: blue;
            color: #fff;
        }

        .homepage {
            background-color: #f2f2f2;
            padding: 20px;
            text-align: center;
        }

        .body-section {
            padding: 20px;
            text-align: center;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 10px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>Your Landing Page</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </nav>

    <div class="homepage">
        <h2>Welcome to Our Website!</h2>
        <p>This is the homepage section of your landing page.</p>
    </div>

    <div class="body-section">
        <h2>Body Section</h2>
        <p>This is the main content area of your landing page.</p>
    </div>

    <footer>
        <p>&copy; 2023 Your Landing Page. All rights reserved.</p>
    </footer>

</body>
</html>
