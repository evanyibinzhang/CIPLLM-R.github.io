<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project Name</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"> <!-- Font Awesome for icons -->
    <style>
        /* Add custom styles here or link an external CSS file */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }
        header {
            background-color: #007bff;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        .container {
            max-width: 960px;
            margin: 0 auto;
            padding: 0 20px;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline-block;
            margin-right: 20px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 16px;
        }
        section {
            padding: 50px 0;
            text-align: center;
        }
        h2 {
            color: #007bff;
        }
        .member-list {
            list-style-type: none;
            padding: 0;
            margin: 20px 0;
        }
        .member-list li {
            display: inline-block;
            margin-right: 10px;
            padding: 5px 10px;
            border: 1px solid #ccc;
            background-color: #fff;
            border-radius: 20px;
        }
        .contact-list {
            list-style-type: none;
            padding: 0;
            margin: 20px 0;
        }
        .contact-list li {
            margin-bottom: 10px;
        }
        .contact-list li i {
            margin-right: 5px;
        }
        footer {
            background-color: #007bff;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Project Name</h1>
            <nav>
                <ul>
                    <li><a href="#overview">Overview</a></li>
                    <li><a href="#members">Members</a></li>
                    <li><a href="#timeline">Timeline</a></li>
                    <li><a href="#technologies">Technologies</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="overview">
        <div class="container">
            <h2>Project Overview</h2>
            <p>This section provides an overview of your project. Describe what the project is about, its goals, objectives, and any other relevant information.</p>
        </div>
    </section>

    <section id="members">
        <div class="container">
            <h2>Project Members</h2>
            <ul class="member-list">
                <li>XIA Rui</li>
                <li>YIN Chenxi</li>
                <li>ZHANG Yibin</li>
            </ul>
        </div>
    </section>

    <section id="timeline">
        <div class="container">
            <h2>Project Timeline</h2>
            <p>Describe the timeline of your project, including key milestones, deadlines, and progress updates.</p>
        </div>
    </section>

    <section id="technologies">
        <div class="container">
            <h2>Technologies Used</h2>
            <ul class="tech-list">
                <li>Technology 1</li>
                <li>Technology 2</li>
                <!-- Add more technologies as needed -->
            </ul>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Information</h2>
            <p>Provide contact information for inquiries or collaboration opportunities related to the project.</p>
            <ul class="contact-list">
                <li><i class="fas fa-envelope"></i> Email: yourname@example.com</li>
                <li><i class="fab fa-github"></i> GitHub: <a href="https://github.com/yourgithub">yourgithub</a></li>
                <!-- Add more contact information as needed -->
            </ul>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Project Name. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
