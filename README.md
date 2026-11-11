
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ng Yih Ming | Personal Website</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #0f172a;
            color: white;
            line-height: 1.6;
        }

        header {
            padding: 20px 10%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h2 {
            color: #38bdf8;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
        }

        nav a:hover {
            color: #38bdf8;
        }

        .hero {
            min-height: 75vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 40px 20px;
        }

        .hero h1 {
            font-size: 48px;
            margin-bottom: 10px;
        }

        .hero h1 span {
            color: #38bdf8;
        }

        .hero p {
            color: #cbd5e1;
            max-width: 550px;
            margin: 10px 0;
        }

        .tag {
            display: inline-block;
            background: #1e293b;
            color: #38bdf8;
            padding: 8px 18px;
            border-radius: 20px;
            margin-bottom: 20px;
        }

        section {
            padding: 60px 10%;
            text-align: center;
        }

        section h2 {
            font-size: 30px;
            color: #38bdf8;
            margin-bottom: 25px;
        }

        .card-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .card {
            background: #1e293b;
            padding: 25px;
            border-radius: 12px;
            width: 230px;
            border: 1px solid #334155;
        }

        .card h3 {
            color: #38bdf8;
            margin-bottom: 10px;
        }

        .card p {
            color: #cbd5e1;
        }

        footer {
            background: #020617;
            text-align: center;
            padding: 20px;
            color: #94a3b8;
        }

        @media (max-width: 600px) {
            header {
                flex-direction: column;
                gap: 15px;
            }

            nav a {
                margin: 0 8px;
            }

            .hero h1 {
                font-size: 34px;
            }
        }
    </style>
</head>

<body>

    <header>
        <h2>NYM.</h2>

        <nav>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#interests">Interests</a>
        </nav>
    </header>

    <div class="hero">
        <div class="tag">UTM Student</div>

        <h1>Hello, I'm <span>Ng Yih Ming</span></h1>

        <p>
            A Computer Networks & Security student
            at Universiti Teknologi Malaysia.
            Passionate about technology, learning
            new things and exploring the digital world.
        </p>
    </div>

    <section id="about">
        <h2>About Me</h2>

        <p>
            Hi! I'm Yih Ming from Skudai, Johor, Malaysia.
            Currently studying at Universiti Teknologi Malaysia.
            I enjoy learning about technology and improving
            my skills. My future goal is to build a career
            in Cyber Security.
        </p>
    </section>

    <section id="skills">
        <h2>My Skills</h2>

        <div class="card-container">

            <div class="card">
                <h3>Problem Solving</h3>
                <p>Enjoy finding solutions to different challenges.</p>
            </div>

            <div class="card">
                <h3>Teamwork</h3>
                <p>Enjoy working and learning together with others.</p>
            </div>

        </div>
    </section>

    <section id="interests">
        <h2>My Interests</h2>

        <div class="card-container">

            <div class="card">
                <h3>Anime</h3>
                <p>Watching anime in my free time.</p>
            </div>

            <div class="card">
                <h3>Gaming</h3>
                <p>Enjoy playing different games.</p>
            </div>

            <div class="card">
                <h3>Technology</h3>
                <p>Exploring new technology and gadgets.</p>
            </div>

            <div class="card">
                <h3>Basketball</h3>
                <p>Enjoying sports and staying active.</p>
            </div>

        </div>
    </section>

    <footer>
        <p>© 2026 Ng Yih Ming | Personal Website</p>
    </footer>

</body>
</html>

