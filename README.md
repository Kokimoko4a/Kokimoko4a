<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kaloyan Rusev | Full-Stack Developer</title>
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <style>
        :root {
            --primary-color: #00d2ff;
            --secondary-color: #3a7bd5;
            --bg-dark: #0f172a;
            --card-bg: rgba(30, 41, 59, 0.7);
            --text-main: #f8fafc;
            --text-dim: #94a3b8;
        }

        body {
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            background: radial-gradient(circle at top right, #1e293b, #0f172a);
            color: var(--text-main);
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .portfolio-card {
            background: var(--card-bg);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 24px;
            max-width: 800px;
            width: 100%;
            overflow: hidden;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
            transition: transform 0.3s ease;
        }

        .header {
            background: linear-gradient(135deg, var(--secondary-color), var(--primary-color));
            padding: 40px;
            text-align: center;
            position: relative;
        }

        .profile-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid white;
            object-fit: cover;
            background: #eee;
            margin-bottom: 15px;
            box-shadow: 0 10px 15px rgba(0,0,0,0.2);
        }

        .header h1 {
            margin: 10px 0 5px;
            font-size: 2.2rem;
            letter-spacing: -0.5px;
        }

        .header p {
            font-size: 1.1rem;
            opacity: 0.9;
            font-weight: 300;
        }

        .content {
            padding: 40px;
        }

        .section-title {
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: var(--primary-color);
            margin-bottom: 20px;
            display: flex;
            align-items: center;
        }

        .section-title::after {
            content: "";
            flex: 1;
            height: 1px;
            background: rgba(255,255,255,0.1);
            margin-left: 15px;
        }

        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
            margin-bottom: 30px;
        }

        .tech-item {
            background: rgba(255, 255, 255, 0.05);
            padding: 12px;
            border-radius: 12px;
            text-align: center;
            border: 1px solid transparent;
            transition: all 0.2s;
        }

        .tech-item:hover {
            border-color: var(--primary-color);
            background: rgba(0, 210, 255, 0.1);
            transform: translateY(-3px);
        }

        .info-list {
            list-style: none;
            padding: 0;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }

        .info-list li {
            color: var(--text-dim);
            font-size: 0.95rem;
        }

        .info-list strong {
            color: var(--text-main);
            display: block;
            margin-bottom: 4px;
        }

        .footer {
            padding: 20px 40px;
            background: rgba(0,0,0,0.2);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .contact-btn {
            background: var(--primary-color);
            color: #000;
            text-decoration: none;
            padding: 10px 20px;
            border-radius: 50px;
            font-weight: 600;
            font-size: 0.9rem;
            transition: opacity 0.2s;
        }

        .contact-btn:hover {
            opacity: 0.8;
        }

        .saxophone-badge {
            font-size: 1.2rem;
            color: #fbbf24;
        }

        @media (max-width: 600px) {
            .info-list { grid-template-columns: 1fr; }
            .header h1 { font-size: 1.6rem; }
        }
    </style>
</head>
<body>

<div class="portfolio-card">
    <div class="header">
        <img src="https://ui-avatars.com/api/?name=Kaloyan+Rusev&background=random&size=120" alt="Kaloyan Rusev" class="profile-img">
        <h1>Kaloyan Rusev</h1>
        <p>Full-Stack Developer | C# & .NET Expert</p>
    </div>

    <div class="content">
        <div class="section-title">Core Stack</div>
        <div class="tech-grid">
            <div class="tech-item"><strong>C# / .NET</strong></div>
            <div class="tech-item"><strong>ASP.NET Core</strong></div>
            <div class="tech-item"><strong>SQL Server</strong></div>
            <div class="tech-item"><strong>JavaScript</strong></div>
            <div class="tech-item"><strong>Entity Framework</strong></div>
            <div class="tech-item"><strong>Web API / SPA</strong></div>
        </div>

        <div class="section-title">Current Focus</div>
        <ul class="info-list">
            <li>
                <strong>🔭 Project</strong>
                Working on <span style="color:var(--primary-color)">ACUSTICA</span>
            </li>
            <li>
                <strong>🌱 Learning</strong>
                Mastering Python & Advanced Backend Patterns
            </li>
            <li>
                <strong>🛠 Tools</strong>
                Git, Visual Studio, PostgreSQL
            </li>
            <li>
                <strong>🎨 Frontend</strong>
                Modern HTML, CSS & DOM Manipulation
            </li>
        </ul>
    </div>

    <div class="footer">
        <span class="saxophone-badge">🎷 Passionate Saxophonist</span>
        <a href="mailto:kaloyan.rusev.2007@abv.bg" class="contact-btn">Get In Touch</a>
    </div>
</div>

</body>
</html>
