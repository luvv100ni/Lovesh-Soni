# Lovesh-Soni
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lovesh Soni | BBA Portfolio</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            color: #333;
            line-height: 1.6;
            background-color: #f4f6f9;
        }
        header {
            background: linear-gradient(135deg, #0f2027 0%, #203a43 50%, #2c5364 100%);
            color: #fff;
            padding: 50px 20px;
            text-align: center;
        }
        header h1 {
            font-size: 2.8rem;
            margin-bottom: 10px;
            letter-spacing: 1px;
        }
        header p {
            font-size: 1.2rem;
            font-weight: 300;
            opacity: 0.9;
        }
        .contact-bar {
            margin-top: 15px;
        }
        .contact-bar a {
            color: #00adb5;
            text-decoration: none;
            margin: 0 15px;
            font-weight: 500;
        }
        .contact-bar a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1000px;
            margin: 30px auto;
            padding: 0 20px;
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 20px;
        }
        @media (max-width: 768px) {
            .container { grid-template-columns: 1fr; }
        }
        section {
            background: #fff;
            padding: 25px;
            margin-bottom: 20px;
            border-radius: 6px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }
        h2 {
            color: #2c5364;
            border-bottom: 2px solid #eef2f7;
            padding-bottom: 8px;
            margin-bottom: 15px;
            font-size: 1.4rem;
        }
        .item {
            margin-bottom: 15px;
            padding-bottom: 15px;
            border-bottom: 1px dashed #eef2f7;
        }
        .item:last-child {
            border-bottom: none;
            margin-bottom: 0;
            padding-bottom: 0;
        }
        .item h3 {
            font-size: 1.1rem;
            color: #333;
        }
        .meta {
            font-size: 0.9rem;
            color: #666;
            margin-bottom: 5px;
            font-style: italic;
        }
        ul {
            list-style-type: none;
        }
        ul li {
            position: relative;
            padding-left: 15px;
            margin-bottom: 6px;
        }
        ul li::before {
            content: "•";
            color: #00adb5;
            position: absolute;
            left: 0;
            font-weight: bold;
        }
        .badge-list li {
            background: #eef2f7;
            padding: 6px 12px;
            border-radius: 20px;
            display: inline-block;
            margin: 4px;
            font-size: 0.9rem;
        }
        .badge-list li::before {
            content: "";
        }
        footer {
            text-align: center;
            padding: 20px;
            color: #777;
            font-size: 0.85rem;
            background: #fff;
            margin-top: 40px;
            border-top: 1px solid #eef2f7;
        }
    </style>
</head>
<body>

    <!-- Main Header Area -->
    <header>
        <h1>Lovesh Soni</h1>
        <p>B.B.A. Student | Aspiring Management Professional</p>
        <div class="contact-bar">
            <a href="mailto:loveshsahdevda.ls@gmail.com">Email Me</a>
            <a href="https://linkedin.com" target="_blank">LinkedIn Profile</a>
        </div>
    </header>

    <div class="container">
        
        <!-- Main Column (Experience, Education, Certifications) -->
        <div class="main-content">
            
            <section id="objective">
                <h2>Career Objective</h2>
                <p>To make a valuable contribution to the organization to the best of my ability, while continuously developing new skills to achieve new professional heights.</p>
            </section>

            <section id="experience">
                <h2>Work Experience</h2>
                <div class="item">
                    <h3>Supervisor</h3>
                    <div class="meta">Shyam Honda, Indore (04/2024 – 09/2024)</div>
                    <p>Managed supervisory tasks, demonstrated leadership qualities, and optimized team operations during the tenure.</p>
                </div>
            </section>

            <section id="education">
                <h2>Education</h2>
                <div class="item">
                    <h3>Bachelor of Business Administration (B.B.A.)</h3>
                    <div class="meta">DAVV University | 2024 - 2027 (Pursuing)</div>
                </div>
                <div class="item">
                    <h3>Class 12th</h3>
                    <div class="meta">M.P Board | 2024 (Percentage: 74.4%)</div>
                </div>
                <div class="item">
                    <h3>Class 10th</h3>
                    <div class="meta">M.P Board | 2022 (Percentage: 68%)</div>
                </div>
            </section>

            <section id="certifications">
                <h2>Professional Certifications</h2>
                <ul>
                    <li>Certificate Programme in Banking, Finance & Insurance – Bajaj Finserv</li>
                    <li>Key Accounting Concepts and Principles – Acropolis Institute</li>
                    <li>Fundamentals of Accounting – Infosys Springboard</li>
                    <li>Power BI – Acropolis Institute</li>
                    <li>Microsoft Office – Infosys Springboard</li>
                    <li>Time Management – Infosys Springboard</li>
                </ul>
            </section>
            
        </div>

        <!-- Sidebar Column (Skills & Extra Activities) -->
        <div class="sidebar">
            
            <section id="skills">
                <h2>Skills</h2>
                <ul class="badge-list">
                    <li>Microsoft Office (Word, Excel, PowerPoint)</li>
                    <li>Power BI</li>
                    <li>Canva Designing</li>
                    <li>Basic Computer</li>
                    <li>Supervisory Skills</li>
                    <li>Leadership</li>
                    <li>Quick Learner</li>
                </ul>
            </section>

            <section id="activities">
                <h2>Extracurriculars</h2>
                <ul>
                    <li>Science Olympiad Foundation</li>
                    <li>Bhartiya Sanskrit Gyan Pariksha</li>
                    <li>Amateur Qwan Ki Do Championship</li>
                    <li>Anuvrat Painting Competition</li>
                    <li>Summer Coaching Camp</li>
                </ul>
            </section>
            
        </div>

    </div>

    <!-- Page Footer -->
    <footer>
        <p>&copy; 2026 Lovesh Soni. Hosted free on GitHub Pages.</p>
    </footer>

</body>
</html>
