
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Modern GitHub Page</title>

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
        }

        header {
            padding: 30px;
            text-align: center;
        }

        header h1 {
            font-size: 2.5em;
        }

        header p {
            opacity: 0.8;
        }

        nav {
            margin-top: 15px;
        }

        nav a {
            color: white;
            margin: 0 10px;
            text-decoration: none;
            font-weight: 500;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            padding: 40px;
            max-width: 1000px;
            margin: auto;
        }

        .card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 15px;
            padding: 25px;
            margin-bottom: 25px;
            box-shadow: 0 8px 32px rgba(0,0,0,0.2);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .btn {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            border-radius: 25px;
            background: linear-gradient(45deg, #ff7eb3, #ff758c);
            color: white;
            text-decoration: none;
            transition: 0.3s;
        }

        .btn:hover {
            opacity: 0.85;
        }

        ul {
            margin-top: 10px;
            padding-left: 20px;
        }

        footer {
            text-align: center;
            padding: 20px;
            opacity: 0.7;
        }

        /* Animasi fade in */
        .fade-in {
            animation: fadeIn 1s ease forwards;
            opacity: 0;
        }

        @keyframes fadeIn {
            to {
                opacity: 1;
            }
        }
    </style>
</head>
<body>

<header class="fade-in">
    <h1>✨ Ariel-Real</h1>
    <p>Frontend Developer | UI Enthusiast</p>
    <nav>
        <a href="#">Home</a>
        <a href="#">Projects</a>
        <a href="#">Contact</a>
    </nav>
</header>

<div class="container">

    <div class="card fade-in">
        <h2>👋 Tentang Saya</h2>
        <p>Saya suka membuat tampilan web modern, interaktif, dan user-friendly.</p>
    </div>

    <div class="card fade-in">
        <h2>🚀 Project Saya</h2>
        <ul>
            <li>Website Portfolio</li>
            <li>Aplikasi To-Do List</li>
            <li>Landing Page Modern</li>
        </ul>
        <a href="https://github.com/riel-real/wpu-resolusi.git" class="btn">Lihat GitHub</a>
    </div>

</div>

<footer>
    <p>© 2026 - Dibuat dengan cinta💜</p>
</footer>

</body>
</html>
