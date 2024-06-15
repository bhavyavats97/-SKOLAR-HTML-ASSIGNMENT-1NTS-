<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Semantic Elements Example</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header, nav, section, article, aside, footer {
            padding: 20px;
            margin: 10px;
        }
        header, footer {
            background-color: #a41195;
            border: 1px solid #104723;
            text-align: center;
        }
        nav {
            background-color: #177637;
            border: 1px solid #ccc;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 15px;
        }
        nav a {
            text-decoration: none;
            color: #333;
        }
        section {
            display: flex;
            flex-wrap: wrap;
        }
        article, aside {
            flex: 1;
            margin: 10px;
            padding: 20px;
            border: 1px solid #ddd;
        }
        article {
            background-color: #f9f9f9;
        }
        aside {
            background-color: #f1f1f1;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My WEB D  Website</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section>
        <article>
            <h2>WEB DEVELOPMENT </h2>
            <p>full stack web development</p>
            <p>both backend and frontend </p>
        </article>
        <aside>
            <h2>Related Content</h2>
            <p>This sECTION  contain some additional information, links, and examples.</p>
        </aside>
    </section>
    <footer>
        <p>&copy; 2024 My Website | Contact: bhavyavats009@gmail.com | 789 -4567 -8080</p>
    </footer>
</body>
</html>
