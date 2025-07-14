<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <title>Portfolio - Fadhila Chergui</title>
    <!-- AOS Animation Library -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <style>
        * {
            box-sizing: border-box;
        }

        body {
            background: black;
            color: white;
            font-family: cursive;
            font-size: 20px;
            margin: 0;
            padding: 0;
            border: 3px solid white;
            box-shadow: 5px 5px 5px gray;
            
        }

        .div1 {
            position: relative;
            width: 100%;
            height: 420px;
            background-image: url('Touty.avif');
            background-size: cover;
            background-position: center;
        }

        .div2 {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.4);
            padding: 30px;
            text-align: center;
        }

        .hel {
            text-shadow: 3px 2px 2px black;
        }

        .hoby {
            text-shadow: 3px 2px 2px orange;
            font-size: 40px;
        }

        .hoby:hover {
            color: olivedrab;
            text-shadow: 3px 2px 2px white;
        }

        ul {
            list-style: none;
            padding: 0;
            margin: 0 auto;
            width: fit-content;
            text-align: left;
        }

        ul li {
            padding: 10px 15px;
            margin-bottom: 8px;
            background-color: black;
            border-radius: 8px;
            transition: 0.3s ease-in-out;
            text-shadow: 0px 2px 2px olive;
        }

        ul li:hover {
            background-color: rgba(255, 255, 255, 0.4);
            color: black;
            cursor: pointer;
            text-shadow: 0px 2px 2px orange;
        }

        ul li::before {
            content: "✓";
            color: olivedrab;
            margin-right: 10px;
        }

        #uld,
        .acc,
        .projects,
        .contact,
        .works {
            text-align: center;
            margin: 40px auto;
            max-width: 600px;
        }

        .acc a,
        .works a {
            margin: 10px;
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }

        .acc a:hover,
        .works a:hover {
            color: cadetblue;
        }

        form {
            text-align: center;
            margin-top: 20px;
            border: 2px solid cadetblue;
            border-radius: 20px;
            padding: 30px;
            box-shadow: 3px 3px 3px white;
        }

        form input {
            padding: 8px;
            border: none;
            border-radius: 40px;
            width: 60%;
            max-width: 400px;
            background-color: cadetblue;
            color: white;
            border: 2px solid white;
        }

        form input:active {
            background-color: aliceblue;
            border: 2px solid cadetblue;
        }

        form button {
            padding: 8px 16px;
            margin-left: 10px;
            background-color: cadetblue;
            box-shadow: 3px 3px 3px white;
            color: black;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        form button:hover {
            background-color: olive;
            box-shadow: 3px 3px 3px gray;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #111;
            color: white;
            margin-top: 40px;
        }

    </style>
</head>

<body>

    <!-- Header Section -->
    <div class="div1">
        <div class="div2" data-aos="fade-down">
            <h1 class="hel">Hello</h1>
            <h1 class="hel">I am Fadhila Chergui</h1>
            <p>
                I am a passionate and relentless software developer with a deep-rooted focus on networks and cybersecurity.
                My journey in programming is driven not merely by logic, but by an obsession with crafting meaningful digital
                solutions that merge functionality with innovation.
            </p>
        </div>
    </div>

    <!-- Hobby Section -->
    <div id="uld" data-aos="fade-up">
        <h3 class="hoby">My Hobby</h3>
        <ul>
            <li>Programming</li>
            <li>Fashion and Footwear Design</li>
            <li>Boxing</li>
            <li>Story Writing</li>
            <li>Motivating Others</li>
        </ul>
    </div>

    <!-- Accounts Section -->
    <div class="acc" data-aos="fade-right">
        <h3 class="hoby">My Accounts</h3>
        <a href="#">Facebook</a>
        <a href="#">Instagram</a>
        <a href="#">Telegram</a>
    </div>

    <!-- Works Section -->
    <div class="works" data-aos="zoom-in">
        <h3 class="hoby">My Works</h3>
        <a href="#">GitHub</a>
        <h5>Email: Fadhilachergui5@gmail.com</h5>
    </div>

    <!-- Projects Section -->
    <div class="projects" data-aos="fade-left">
        <h3 class="hoby">Projects</h3>
        <ul>
            <li>Android Calculator App</li>
            <li>Network Monitoring Tool</li>
            <li>Portfolio Website (this one!)</li>
            <li>Cybersecurity Blog System</li>
        </ul>
    </div>

    <!-- Contact Section -->
    <div class="contact" data-aos="flip-left">
        <h2 class="hoby">Contact Me</h2>
        <form>
            <label>Your Message</label><br><br>
            <input type="text" placeholder="Write something..." /><br><br>
            <button>Send</button>
        </form>
    </div>

    <!-- Footer -->
    <footer>
        <p>© 2025 Fadhila Chergui - All rights reserved</p>
    </footer>

    <!-- AOS Script -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init({
            duration: 1200,
            once: true
        });

    </script>
</body>

</html>

