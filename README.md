<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Digital Medicine Tracker</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0 20px;
            background-color: #f9f9f9;
        }
        h1, h2, h3, h4 {
            color: #333;
        }
        h1 {
            font-size: 2.5em;
            margin-bottom: 0.5em;
        }
        h2 {
            font-size: 2em;
            margin-bottom: 0.75em;
        }
        h3 {
            font-size: 1.75em;
            margin-bottom: 1em;
        }
        h4 {
            font-size: 1.5em;
            margin-bottom: 1.25em;
        }
        p, ul, li {
            margin: 0 0 10px 0;
            padding: 0;
            color: #555;
        }
        ul {
            list-style-type: none;
            padding-left: 0;
        }
        li::before {
            content: "•";
            color: #ff6347;
            display: inline-block;
            width: 1em;
            margin-left: -1em;
        }
        .section-title {
            margin-top: 2em;
            border-bottom: 2px solid #eee;
            padding-bottom: 0.5em;
            font-size: 1.75em;
        }
        .emoji {
            font-size: 1.5em;
            margin-right: 0.5em;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        .code-block {
            background-color: #f4f4f4;
            padding: 10px;
            border-radius: 5px;
            font-family: monospace;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>💊 Digital Medicine Tracker</h1>
        <p>An application to find nearby medicines using Java, MySQL, JSP, Servlet, JDBC, HTML, CSS, JavaScript, and XAMPP.</p>

        <h2 class="section-title">📋 Table of Contents</h2>
        <ul>
            <li><a href="#description">Description</a></li>
            <li><a href="#technologies">Technologies</a></li>
            <li><a href="#features">Features</a></li>
            <li><a href="#getting-started">Getting Started</a></li>
            <li><a href="#prerequisites">Prerequisites</a></li>
            <li><a href="#installation-and-setup">Installation and Setup</a></li>
            <li><a href="#usage">Usage</a></li>
            <li><a href="#contributing">Contributing</a></li>
            <li><a href="#license">License</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>

        <h2 id="description" class="section-title">📄 Description</h2>
        <p>The Digital Medicine Tracker is a comprehensive solution designed to assist users in locating nearby medicines efficiently. This application empowers users to seamlessly search for specific medicines and promptly discover nearby pharmacies and medical facilities where these medicines are available.</p>
        <p>The backend is built on Java and incorporates JavaServer Pages (JSP) for rendering dynamic web pages and Servlets for managing user requests. The application's data is securely stored and managed using MySQL, ensuring efficient retrieval and storage of medicine and pharmacy information.</p>

        <h2 id="technologies" class="section-title">🛠️ Technologies</h2>
        <ul>
            <li>MySQL</li>
            <li>Java [version]</li>
            <li>JSP (JavaServer Pages)</li>
            <li>Servlet</li>
            <li>XAMPP</li>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
        </ul>

        <h2 id="features" class="section-title">✨ Features</h2>
        <ul>
            <li>Effortless Medicine Search: Users can effortlessly search for specific medicines to verify their availability nearby.</li>
            <li>Location-based Results: Leveraging location data, the application offers results relevant to the user's geographical position.</li>
            <li>Nearby Pharmacies and Facilities: Users can conveniently access a comprehensive list of nearby pharmacies and medical facilities stocked with the required medicines.</li>
            <li>User-Centric Interface: The application's intuitive interface enables easy navigation and quick access to vital information.</li>
            <li>Customizable Alerts: Users have the option to set alerts, enabling the application to notify them when nearby pharmacies have the required medicines.</li>
        </ul>

        <h2 id="getting-started" class="section-title">🚀 Getting Started</h2>

        <h3 id="prerequisites">🔧 Prerequisites</h3>
        <ul>
            <li>Java JDK [jdk-8u111-]</li>
            <li>XAMPP [xampp-windows-x64-8.0.25-0]</li>
            <li>Apache Tomcat [apache-tomcat-7.0.82]</li>
            <li>Eclipse</li>
        </ul>

        <h3 id="installation-and-setup">💻 Installation and Setup</h3>
        <p>Clone the repository:</p>
        <div class="code-block">
            <code>git clone [your-repository-url]</code>
        </div>
        <p>Set up the database using XAMPP.</p>
        <p>Open the project in your Eclipse IDE.</p>

        <h2 id="usage" class="section-title">📚 Usage</h2>
        <ul>
            <li>Launch the application.</li>
            <li>Search for the desired medicine.</li>
            <li>View a list of nearby pharmacies and medical facilities with the medicine.</li>
        </ul>

        <h2 id="contributing" class="section-title">🤝 Contributing</h2>
        <p>Contributions are welcome! To contribute to the project, please follow the guidelines outlined in the CONTRIBUTING file.</p>

        <h2 id="license" class="section-title"
