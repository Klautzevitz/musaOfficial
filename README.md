<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>klautzevitz | GitHub Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: black;
            color: #00ff00;
            text-align: center;
            padding: 50px;
            margin: 0;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: rgba(0, 0, 0, 0.8);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 15px #00ff00;
        }
        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        p {
            font-size: 1.2em;
            margin: 5px 0;
        }
        .glitch {
            font-size: 2em;
            font-weight: bold;
            position: relative;
            display: inline-block;
            color: #00ff00;
            text-shadow: 2px 2px 4px rgba(0, 255, 0, 0.5);
        }
        .glitch::before {
            content: attr(data-text);
            position: absolute;
            left: 2px;
            color: #ff0000;
            text-shadow: -2px 0 red;
            clip: rect(0, 900px, 0, 0);
            animation: glitch 0.8s infinite linear alternate-reverse;
        }
        @keyframes glitch {
            0% { clip: rect(20px, 9999px, 100px, 0); }
            100% { clip: rect(50px, 9999px, 150px, 0); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="glitch" data-text="klautzevitz">klautzevitz</h1>
        <p>Cybersecurity Enthusiast | Pentester | Programmer</p>
        <p>Exploring the digital world, uncovering vulnerabilities, and securing the future.</p>
    </div>
</body>
</html>



![](white_rose.gif)
<br>


<!---
musaOfficial/musaOfficial is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
