<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Data Analyst & Data Scientist</title>
    <style>
        /* Basic reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Global styles */
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }

        a {
            color: #00aaff;
            text-decoration: none;
        }

        /* Header styles */
        header {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            margin-bottom: 15px;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
        }

        /* Banner styles */
        .banner {
            background-image: url('https://source.unsplash.com/random/1920x600');
            height: 300px;
            background-size: cover;
            background-position: center;
            position: relative;
        }

        .banner h2 {
            color: white;
            font-size: 3rem;
            text-shadow: 2px 2px 5px #000;
            position: absolute;
            bottom: 20px;
            left: 20px;
        }

        /* Introduction section */
        .intro {
            padding: 40px 20px;
            background-color: white;
            text-align: center;
        }

        .intro h2 {
            font-size: 2rem;
            margin-bottom: 20px;
        }

        .intro p {
            font-size: 1.1rem;
            max-width: 800px;
            margin: auto;
            color: #555;
        }

        /* Projects section */
        .projects {
            padding: 40px 20px;
        }

        .projects h2 {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 20px;
        }

        .project {
            background-color: white;
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .project h3 {
            margin-bottom: 10px;
        }

        .project p {
            font-size: 1rem;
        }

        /* Skills section */
        .skills {
            padding: 40px 20px;
            background-color: #333;
            color: white;
        }

        .skills h2 {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 20px;
        }

        .skills-icons {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        .skills-icons div {
            margin: 10px;
            text-align: center;
        }

        .skills-icons img {
            width: 70px;
            height: 70px;
        }

        /* Achievements section */
        .achievements {
            padding: 40px 20px;
        }

        .achievements h2 {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 20px;
        }

        .achievement {
            background-color: white;
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .achievement h3 {
            margin-bottom: 10px;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px 0;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <img src="https://via.placeholder.com/150" alt="Profile Picture">
        <h1>Husnain Malik</h1>
        <p>Data Analyst | Data Scientist</p>
    </header>

    <!-- Banner Section -->
    <section class="banner">
        <h2>Empowering Businesses with Data-Driven Insights</h2>
    </section>

    <!-- Introduction Section -->
    <section class="intro">
        <h2>About Me</h2>
        <p>
            I am a passionate data analyst and data scientist with a strong foundation in data analytics, machine learning, and data visualization. I have worked on several projects using SQL, Python, Power BI, and Excel to extract meaningful insights from complex datasets. I am always excited to solve challenging problems and make data-driven decisions.
        </p>
    </section>

    <!-- Projects Section -->
    <section class="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Social Media Advertisement Analytics (Power BI)</h3>
            <p>Analyzed key performance metrics across various social media platforms to optimize ad campaigns and improve reach.</p>
        </div>
        <div class="project">
            <h3>Pizza Hut Sales Analysis (SQL)</h3>
            <p>Extracted sales data from the database, calculated revenue and identified the most popular pizza types, and provided recommendations for future product launches.</p>
        </div>
        <div class="project">
            <h3>Energy Consumption Trends in Pakistan (Python)</h3>
            <p>Analyzed energy consumption and generation trends over 30 years using Python and visualization tools.</p>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="skills">
        <h2>Skills</h2>
        <div class="skills-icons">
            <div>
                <img src="https://img.icons8.com/color/48/000000/python.png" alt="Python">
                <p>Python</p>
            </div>
            <div>
                <img src="https://img.icons8.com/color/48/000000/sql.png" alt="SQL">
                <p>SQL</p>
            </div>
            <div>
                <img src="https://img.icons8.com/color/48/000000/power-bi.png" alt="Power BI">
                <p>Power BI</p>
            </div>
            <div>
                <img src="https://img.icons8.com/color/48/000000/microsoft-excel.png" alt="Excel">
                <p>Excel</p>
            </div>
            <div>
                <img src="https://img.icons8.com/color/48/000000/data-science.png" alt="Data Science">
                <p>Data Science</p>
            </div>
        </div>
    </section>

    <!-- Achievements Section -->
    <section class="achievements">
        <h2>Achievements</h2>
        <div class="achievement">
            <h3>International Hackathon Winner</h3>
            <p>Won a global hackathon competition by developing an AI-based project using Python and machine learning.</p>
        </div>
        <div class="achievement">
            <h3>SQL Mastery Certification</h3>
            <p>Certified in advanced SQL techniques for data manipulation and analytics.</p>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>Connect with me on <a href="https://linkedin.com/in/your-profile" target="_blank">LinkedIn</a> | GitHub: <a href="https://github.com/your-github" target="_blank">github.com/your-github</a></p>
    </footer>

</body>
</html>

