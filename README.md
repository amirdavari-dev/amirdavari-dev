<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amir Davari - GitHub Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(180deg, #0a0a0a, #1a1a1a);
            color: #ffffff;
            line-height: 1.6;
            position: relative;
            overflow-x: hidden;
        }
        /* Starry background animation */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://www.transparenttextures.com/patterns/stardust.png');
            opacity: 0.3;
            animation: starry 100s linear infinite;
            z-index: -1;
        }
        @keyframes starry {
            0% { background-position: 0 0; }
            100% { background-position: 1000px 1000px; }
        }
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 40px 20px;
            position: relative;
        }
        h1 {
            font-size: 3.5rem;
            text-align: center;
            background: linear-gradient(45deg, #00d4ff, #ff007a);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 0 15px rgba(0, 212, 255, 0.7), 0 0 30px rgba(255, 0, 122, 0.5);
            animation: glow 2s ease-in-out infinite alternate;
        }
        @keyframes glow {
            0% { text-shadow: 0 0 15px rgba(0, 212, 255, 0.7), 0 0 30px rgba(255, 0, 122, 0.5); }
            100% { text-shadow: 0 0 25px rgba(0, 212, 255, 1), 0 0 40px rgba(255, 0, 122, 1); }
        }
        h2 {
            font-size: 2rem;
            color: #00d4ff;
            border-bottom: 3px solid #ff007a;
            padding-bottom: 10px;
            margin-top: 40px;
            position: relative;
            animation: slideIn 1s ease-out;
        }
        h2::after {
            content: '';
            position: absolute;
            bottom: -3px;
            left: 0;
            width: 50px;
            height: 3px;
            background: linear-gradient(90deg, #00d4ff, #ff007a);
            animation: expand 2s infinite;
        }
        @keyframes expand {
            0% { width: 50px; }
            50% { width: 100px; }
            100% { width: 50px; }
        }
        @keyframes slideIn {
            0% { opacity: 0; transform: translateX(-50px); }
            100% { opacity: 1; transform: translateX(0); }
        }
        .intro {
            text-align: center;
            font-size: 1.3rem;
            margin-bottom: 40px;
            color: #e0e0e0;
            animation: fadeIn 1.5s ease-out;
        }
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            margin: 15px 0;
            display: flex;
            align-items: center;
            font-size: 1.1rem;
            color: #d1d1d1;
            background: rgba(255, 255, 255, 0.05);
            padding: 10px;
            border-radius: 8px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        ul li:hover {
            transform: translateX(10px);
            box-shadow: 0 0 15px rgba(0, 212, 255, 0.5);
        }
        ul li::before {
            content: "🌟";
            margin-right: 10px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid #00d4ff;
            border-radius: 8px;
            overflow: hidden;
            animation: fadeIn 2s ease-out;
        }
        th, td {
            padding: 15px;
            text-align: left;
        }
        th {
            background: linear-gradient(90deg, #00d4ff, #ff007a);
            color: #1a1a1a;
            font-weight: bold;
        }
        td {
            color: #d1d1d1;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }
        .projects li::before {
            content: "💥";
            margin-right: 10px;
        }
        .projects li:nth-child(2)::before {
            content: "🔥";
        }
        .projects li:nth-child(3)::before {
            content: "⚡️";
        }
        a {
            color: #00d4ff;
            text-decoration: none;
            position: relative;
            transition: color 0.3s ease;
        }
        a::after {
            content: '';
            position: absolute;
            bottom: -2px;
            left: 0;
            width: 0;
            height: 2px;
            background: #ff007a;
            transition: width 0.3s ease;
        }
        a:hover::after {
            width: 100%;
        }
        a:hover {
            color: #ff007a;
        }
        .connect li::before {
            content: "📧";
            margin-right: 10px;
        }
        .connect li:nth-child(2)::before {
            content: "💼";
        }
        .connect li:nth-child(3)::before {
            content: "🌐";
        }
        .connect li:nth-child(4)::before {
            content: "🐦";
        }
        .fun-fact {
            font-style: italic;
            font-size: 1.2rem;
            color: #ff007a;
            text-align: center;
            margin: 40px 0;
            text-shadow: 0 0 10px rgba(255, 0, 122, 0.5);
            animation: pulse 3s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        .footer {
            text-align: center;
            font-size: 1.3rem;
            margin-top: 40px;
            color: #00d4ff;
            text-shadow: 0 0 10px rgba(0, 212, 255, 0.5);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Amir Davari 🚀✨</h1>
        <p class="intro">
            Hey there! I'm Amir Davari, a Full-Stack JavaScript Sorcerer weaving magic across frontend and backend realms. I craft blazing-fast, visually stunning web apps with a dark, futuristic aesthetic. Ready to dive into my world? 🌌
        </p>

        <h2>🌟 About Me</h2>
        <ul>
            <li>🖥️ <strong>Frontend Wizardry</strong>: Sculpting pixel-perfect, responsive UIs with React and Next.js 15 (fully updated to the latest features).</li>
            <li>⚙️ <strong>Backend Mastery</strong>: Forging robust APIs and server-side logic with Node.js.</li>
            <li>🧠 <strong>State Management Guru</strong>: Commanding Zustand, React Context, and Reducers for seamless, scalable state solutions.</li>
            <li>🌉 <strong>Full-Stack Alchemist</strong>: Bridging frontend and backend to deliver end-to-end brilliance.</li>
            <li>💻 <strong>Code Mantra</strong>: Clean, modular, and high-performance code with a sprinkle of creativity.</li>
        </ul>

        <h2>🛠️ Tech Stack</h2>
        <table>
            <tr>
                <th>Category</th>
                <th>Skills</th>
            </tr>
            <tr>
                <td>Frontend</td>
                <td>React   Next.js 15   JavaScript (ES6+)   TypeScript   Tailwind CSS   HTML5   CSS3</td>
            </tr>
            <tr>
                <td>Backend</td>
                <td>Node.js   Express.js   REST APIs   GraphQL</td>
            </tr>
            <tr>
                <td>State Management</td>
                <td>Zustand   React Context   Reducer</td>
            </tr>
            <tr>
                <td>Tools & Platforms</td>
                <td>Git   Webpack   Vite   Docker   Vercel   Netlify</td>
            </tr>
            <tr>
                <td>Databases</td>
                <td>MongoDB   PostgreSQL   Prisma</td>
            </tr>
            <tr>
                <td>Other</td>
                <td>JWT   WebSockets   CI/CD   Jest   Cypress</td>
            </tr>
        </table>

        <h2>🌌 Featured Projects</h2>
        <ul class="projects">
            <li><strong>[Project Name 1]</strong>: A Next.js 15 app with a sleek frontend and Node.js backend, powered by Zustand for state management. <a href="#">[Link to Repo]</a></li>
            <li><strong>[Project Name 2]</strong>: A full-stack e-commerce platform with real-time updates via WebSockets and React Context. <a href="#">[Link to Repo]</a></li>
            <li><strong>[Project Name 3]</strong>: A dark-themed dashboard built with Tailwind CSS and Next.js, integrated with a GraphQL API. <a href="#">[Link to Repo]</a></li>
        </ul>

        <h2>📬 Connect with Me</h2>
        <ul class="connect">
            <li><strong>Email</strong>: <a href="mailto:your.email@example.com">your.email@example.com</a></li>
            <li><strong>LinkedIn</strong>: <a href="https://www.linkedin.com/in/amirdavari">Amir Davari</a></li>
            <li><strong>Portfolio</strong>: <a href="https://amirdavari.dev">amirdavari.dev</a></li>
            <li><strong>X</strong>: <a href="https://x.com/YourXHandle">@YourXHandle</a></li>
        </ul>

        <h2>⚡ Fun Fact</h2>
        <p class="fun-fact">
            When I'm not coding, I'm either chasing the latest JS frameworks, sipping coffee, or designing dark-themed UIs that glow like the night sky. ☕🌃
        </p>

        <p class="footer">
            🌟 <strong>Star my repos to fuel the coding fire!</strong><br>
            Let's create something epic together! 😎
        </p>
    </div>
</body>
</html>
