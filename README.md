# Adil-personal-webpag
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Personal Webpage</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #000000;
            color: #ffffff;
            margin: 0;
            padding: 0;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
        }
        header, footer, .content {
            flex: 1 100%;
        }
        header {
            background: #1a1a1a;
            padding: 20px;
            text-align: center;
        }
        footer {
            background: #1a1a1a;
            padding: 10px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
        .bio, .portfolio, .blog {
            margin: 10px;
            padding: 10px;
            background: #333333;
            flex: 1 1 calc(33% - 40px);
        }
        a {
            color: #1e90ff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <h1>Welcome to My Personal Webpage</h1>
    </header>
    <div class="container">
        <div class="content bio">
            <h2>Bio</h2>
            <p>Hi, I'm [Your Name], a [Your Profession].</p>
        </div>
        <div class="content portfolio">
            <h2>Portfolio</h2>
            <p>Here are some of my works:</p>
            <ul>
                <li>Project 1</li>
                <li>Project 2</li>
                <li>Project 3</li>
            </ul>
        </div>
        <div class="content blog">
            <h2>Blog</h2>
            <p>Check out my latest blog posts:</p>
            <ul>
                <li>Blog Post 1</li>
                <li>Blog Post 2</li>
                <li>Blog Post 3</li>
            </ul>
        </div>
    </div>
    <footer>
        <p>Connect with me on <a href="https://www.instagram.com/itz.__axzim_?igsh=MWthY3JjZ3E2bGMyYQ==">Instagram</a> and <a href="https://pin.it/5uDtP6InE">Pinterest</a>.</p>
    </footer>
</body>
</html>
