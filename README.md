!DOCTYPE html>
<html>
<head>
    <title>Gaming Company</title>
    <link>
    <style>
        body {
            font-family: Arial, sans-serif;
            color: #333;
            margin: 0;
            padding: 0;
            background: #000;
            color: #fff;
        }

        header, footer {
            background: #111;
            padding: 1rem 2rem;
            text-align: center;
        }

        nav a {
            margin: 0 1rem;
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: #FFD700;
        }

        .hero {
            background: url(') center/cover no-repeat;
            color: #fff;
            text-align: center;
            padding: 5rem 2rem;
        }

        .section {
            padding: 2rem;
            text-align: center;
        }

        .games, .team {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        .game-card, .team-card {
            background: #222;
            border-radius: 8px;
            margin: 1rem;
            padding: 1rem;
            width: 250px;
        }

        .game-card img, .team-card img {
            max-width: 100%;
            border-radius: 8px;
        }

        footer p {
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Breaking Games</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#games">Games</a>
            <a href="#team">Team</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="home" class="hero">
        <h2>Welcome to Breaking Games</h2>
        <p>Where imagination meets reality.</p>
        <a href="#games" style="color: #FFD700; font-weight: bold;">Explore Our Games</a>
    </section>

    <section id="about" class="section">
        <h2>About Us</h2>
        <p>Gaming Company is dedicated to creating immersive gaming experiences that captivate and entertain players worldwide.</p>
    </section>

    <section id="games" class="section">
        <h2>Our Games</h2>
        <div class="games">
            <div class="game-card">
                <img src="data:image/jpeg;base64,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" alt="Game 1">
                <h3>Drug dealer 2</h3>
                <p>It is about a chemistry teacher who got into a drug business</p>
            </div>
            <div class="game-card">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT3LmYk8MPJTtQhEyBnvSp2gv8qtmssh7hijg&s" alt="Game 2">
                <h3>GTA IV liberty city</h3>
                <p>This a multiplayer story mode game about our CEO </p>
    </section>

    <section id="team" class="section">
        <h2>Meet the Team</h2>
        <div class="team">
            <div class="team-card">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQM4Wbz21YyGMDnLVQ5cL8PQvNv7k6fQ9w8Vg&s" alt="Team Member 1">
                <h3>Tommy vercetti</h3>
                <p>CEO</p>
            </div>
            <div class="team-card">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR863qNOmDLCB7wStmUv5pXBs8G5Oksoy03nw&s" alt="Team Member 2">
                <h3>Walter white</h3>
                <p>Vice president</p>
    </section>

    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <p>FOR ENQUIRES DO NOT CALL US AS WE DON'T TAKE CALL</p>
 </section>


    <footer>
        <p>&copy; 2024 Breaking Games. All Rights Reserved.</p>
    </footer>

</body>
</html>
