<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="css/styles.css">
    <script src="js/main.js" defer></script>
</head>
<body>

    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Projects</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="hero">
            <h1>Welcome to My Portfolio</h1>
            <p>Showcasing my work and skills.</p>
        </section>

        <section id="about">
            <h2>About Me</h2>
            <p>A brief introduction about me.</p>
        </section>

        <section id="projects">
            <h2>My Projects</h2>
            <p>A gallery of my completed projects.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 My Portfolio</p>
    </footer>

</body>
</html>
/* Basic styles to get started */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 1rem;
}

nav a {
    color: white;
    text-decoration: none;
}

main {
    padding: 2rem;
}

footer {
    text-align: center;
    padding: 1rem;
    background-color: #f4f4f4;
}
git init
git add 
git commit -m "Initial portfolio upload"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
