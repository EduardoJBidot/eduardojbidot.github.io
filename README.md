<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* CSS styling directly in the HTML file */

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        header {
            background-color: #333;
            color: white;
            padding: 1rem;
            text-align: center;
        }

        main {
            flex: 1;
            padding: 2rem;
        }

        h1, h2 {
            margin-bottom: 1rem;
        }

        .project-grid {
            display: flex;
            gap: 2rem;
            flex-wrap: wrap;
            justify-content: center;
        }

        .project-card {
            background-color: #f9f9f9;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 1rem;
            width: 300px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: box-shadow 0.3s;
            text-align: center;
        }

        .project-card:hover {
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }

        .project-card h3 {
            margin-bottom: 0.5rem;
        }

        .project-card p {
            color: #555;
            margin-bottom: 1rem;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 1rem;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <p>Here are some of my projects and code samples.</p>
    </header>
    
    <main>
        <section id="projects">
            <h2>Projects</h2>
            <div class="project-grid">
                <!-- Add your project entries here -->
                <div class="project-card">
                    <h3>Project 1</h3>
                    <p>A brief description of the project.</p>
                    <a href="https://github.com/your-username/project1" target="_blank">View on GitHub</a>
                </div>
                <div class="project-card">
                    <h3>Project 2</h3>
                    <p>A brief description of the project.</p>
                    <a href="https://github.com/your-username/project2" target="_blank">View on GitHub</a>
                </div>
                <!-- Add more project cards as needed -->
            </div>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2023 Your Name. All rights reserved.</p>
        <p>Connect with me: 
            <a href="https://github.com/your-username" target="_blank">GitHub</a> | 
            <a href="https://www.linkedin.com/in/your-linkedin-profile/" target="_blank">LinkedIn</a>
        </p>
    </footer>

    <!-- Optional JavaScript for future enhancements -->
    <script>
        // JavaScript code can go here if you need interactivity in the future
    </script>
</body>
</html>
