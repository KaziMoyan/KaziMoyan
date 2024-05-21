
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kazi Moyan's Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 10px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        main {
            padding: 1rem;
        }

        section {
            margin-bottom: 2rem;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        .github-stats {
            display: flex;
            justify-content: center;
            margin-top: 1rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Kazi Moyan's Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Hi there 👋</p>
            <p>I am Moyan, a student of Daffodil International University, Department of Software Engineering.</p>
            <div class="github-stats">
                <img src="https://github-readme-stats.vercel.app/api?username=KaziMoyan&theme=dark&show_icons=true" alt="Kazi Moyan's GitHub stats">
            </div>
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <div class="project">
                <h3>Food Ordering System</h3>
                <p>This project is a food ordering system developed with PHP. You can find the project repository on <a href="https://github.com/KaziMoyan/restaurent.git" target="_blank">GitHub</a>.</p>
            </div>
            <!-- Add more projects as needed -->
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>Phone: 01602385010<br>
            Email: <a href="mailto:moyeenkazi03@gmail.com">moyeenkazi03@gmail.com</a></p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Kazi Moyan</p>
    </footer>
</body>
</html>
