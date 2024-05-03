<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simplyland 2016 Homepage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #8a2be2; /* Purple */
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            background-color: #800080; /* Dark purple */
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
        main {
            padding: 20px;
        }
        section {
            margin-bottom: 40px; /* Increased space between sections */
        }
        h2 {
            margin-bottom: 20px; /* Increased space below category headings */
        }
        .item {
            display: inline-block;
            text-align: center;
            margin-right: 20px;
        }
        .item img {
            width: 150px;
            height: auto;
            border-radius: 10px;
            margin-bottom: 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Simplyland!</h1>
    </header>
    <nav>
        <a href="#">Games</a>
        <a href="#">Items</a>
        <a href="#">Develop</a>
        <a href="#">Simplybucks</a> <!-- Changed Robux to Simplybucks -->
        <a href="#">Help</a>
    </nav>
    <main>
        <section>
            <h2>Games</h2>
            <div class="item">
                <a href="#">
                    <img src="game1.jpg" alt="Game 1">
                    <p>Game 1</p>
                </a>
            </div>
            <div class="item">
                <a href="#">
                    <img src="game2.jpg" alt="Game 2">
                    <p>Game 2</p>
                </a>
            </div>
            <div class="item">
                <a href="#">
                    <img src="game3.jpg" alt="Game 3">
                    <p>Game 3</p>
                </a>
            </div>
        </section>
        <section>
            <h2>Items</h2>
            <div class="item">
                <a href="#">
                    <img src="item1.jpg" alt="Item 1">
                    <p>Item 1</p>
                </a>
            </div>
            <div class="item">
                <a href="#">
                    <img src="item2.jpg" alt="Item 2">
                    <p>Item 2</p>
                </a>
            </div>
            <div class="item">
                <a href="#">
                    <img src="item3.jpg" alt="Item 3">
                    <p>Item 3</p>
                </a>
            </div>
        </section>
    </main>
    <footer>
        &copy; 2024 Simplyland Corporation. All rights reserved.
    </footer>
</body>
</html>
