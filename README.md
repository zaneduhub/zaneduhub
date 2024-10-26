<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZanEduHub | Empowering Through Education</title>
    <style>
        /* Import Google Fonts */
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

        /* Base styling */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }

        /* Header styling */
        .header {
            background-color: #008080;
            color: #fff;
            padding: 40px 20px;
            text-align: center;
        }

        .header h1 {
            font-size: 2.5em;
            animation: typing 4s steps(30, end), blink-caret 0.5s step-end infinite;
            white-space: nowrap;
            overflow: hidden;
            border-right: 4px solid #fff;
            display: inline-block;
        }

        /* Typing effect */
        @keyframes typing {
            from { width: 0; }
            to { width: 100%; }
        }
        @keyframes blink-caret {
            50% { border-color: transparent; }
        }

        /* Main content sections */
        .section {
            background-color: #fff;
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .section h2 {
            color: #008080;
            font-size: 1.8em;
            margin-bottom: 10px;
            text-align: center;
        }

        .section p {
            color: #333;
            font-size: 1.1em;
            text-align: center;
        }

        /* Button styling */
        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #008080;
            color: #fff;
            border-radius: 5px;
            text-decoration: none;
            transition: background 0.3s;
            text-align: center;
        }

        .btn:hover {
            background-color: #004d40;
        }

        /* Responsive adjustments */
        @media (max-width: 768px) {
            .header h1 {
                font-size: 1.8em;
            }
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header class="header">
        <div class="container">
            <h1>Welcome to ZanEduHub</h1>
            <p>Empowering Individuals Through Education, Mentorship, and Opportunity</p>
        </div>
    </header>

    <!-- Mission Section -->
    <div class="section container">
        <h2>Our Mission</h2>
        <p>At ZanEduHub, we are dedicated to empowering individuals through education, mentorship, and professional growth. We believe in providing resources that enable individuals to thrive and contribute to their communities and beyond.</p>
    </div>

    <!-- Vision Section -->
    <div class="section container">
        <h2>Our Vision</h2>
        <p>We envision a world where everyone has the chance to succeed, regardless of their background. Through our programs and support, we strive to foster a more equitable and prosperous future for all.</p>
    </div>

    <!-- Projects Section -->
    <div class="section container">
        <h2>Featured Projects</h2>
        <p>Explore some of our impactful projects that are helping to bridge the educational and opportunity gaps in our communities.</p>
        <a href="#projects" class="btn">View Projects</a>
    </div>

    <!-- Footer Section -->
    <footer class="header" style="padding: 10px;">
        <p>&copy; 2024 ZanEduHub. All Rights Reserved.</p>
    </footer>

</body>
</html>
