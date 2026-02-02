<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>HB IMMERSIVE – Hologrammes 3D en Réalité Augmentée</title>
    <meta name="description" content="HB IMMERSIVE est une application de réalité augmentée permettant de créer, manipuler et partager des hologrammes 3D interactifs depuis un smartphone.">

    <!-- Open Graph -->
    <meta property="og:title" content="HB IMMERSIVE – Portfolio Officiel">
    <meta property="og:description" content="Application de réalité augmentée pour créer et partager des hologrammes 3D.">
    <meta property="og:image" content="assets/logo.png">
    <meta property="og:url" content="https://hbimmersive.netlify.app">
    <meta property="og:type" content="website">

    <!-- Icons & Fonts -->
    <link rel="icon" href="assets/favicon.ico">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <style>
        :root {
            --primary: #6a4c93;
            --secondary: #8e44ad;
            --dark: #1f2a36;
            --light: #ecf0f1;
            --accent: #3498db;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-padding-top: 90px;
        }

        body {
            font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--light);
            color: var(--dark);
            line-height: 1.6;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: auto;
        }

        header {
            position: fixed;
            top: 0;
            width: 100%;
            background: var(--dark);
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.15);
        }

        nav {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 15px 0;
        }

        nav img {
            height: 48px;
        }

        nav a {
            color: var(--light);
            margin-left: 20px;
            text-decoration: none;
            font-weight: 500;
        }

        nav a:hover {
            color: var(--accent);
        }

        .hero {
            margin-top: 90px;
            padding: 140px 0 100px;
            text-align: center;
            color: white;
            background: linear-gradient(135deg, var(--primary), var(--secondary));
        }

        .hero h1 {
            font-size: 2.6rem;
            margin-bottom: 20px;
        }

        .hero p {
            max-width: 800px;
            margin: auto;
            font-size: 1.15rem;
        }

        .cta {
            margin-top: 30px;
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .btn {
            padding: 12px 28px;
            border-radius: 6px;
            font-weight: 600;
            text-decoration: none;
            transition: 0.3s;
        }

        .btn-primary {
            background: var(--accent);
            color: white;
        }

        .btn-secondary {
            border: 2px solid white;
            color: white;
        }

        section {
            padding: 80px 0;
        }

        h2 {
            text-align: center;
            margin-bottom: 50px;
            font-size: 2rem;
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 30px;
        }

        .feature {
            background: white;
            border-radius: 12px;
            padding: 30px;
            text-align: center;
            box-shadow: 0 10px 25px rgba(0,0,0,0.08);
        }

        .contact {
            background: var(--dark);
            color: white;
            text-align: center;
        }

        footer {
            background: var(--primary);
            color: white;
            text-align: center;
            padding: 20px;
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>

<body>

<header>
    <div class="container">
        <nav>
            <img src="assets/logo.png" alt="HB IMMERSIVE Logo">
            <div>
                <a href="#features">Fonctionnalités</a>
                <a href="#screens">Captures</a>
                <a href="#demo">Démo</a>
                <a href="#contact">Contact</a>
            </div>
        </nav>
    </div>
</header>

<section class="hero">
    <div class="container">
        <h1>HB IMMERSIVE</h1>
        <p>
            Transformez votre smartphone en projecteur holographique
            et créez des expériences 3D immersives en réalité augmentée.
        </p>
        <div class="cta">
            <a href="#" class="btn btn-primary">Google Play</a>
            <a href="#demo" class="btn btn-secondary">Voir la démo</a>
        </div>
    </div>
</section>

<section id="features">
    <div class="container">
        <h2>Fonctionnalités clés</h2>
        <div class="features-grid">
            <div class="feature">
                <i class="fas fa-vr-cardboard fa-3x"></i>
                <h3>Réalité augmentée</h3>
                <p>Interaction en temps réel avec des hologrammes 3D.</p>
            </div>
            <div class="feature">
                <i class="fas fa-share-alt fa-3x"></i>
                <h3>Partage social</h3>
                <p>Capturez et partagez instantanément vos créations.</p>
            </div>
            <div class="feature">
                <i class="fas fa-crown fa-3x"></i>
                <h3>Mode Premium</h3>
                <p>Accès exclusif à des modèles avancés sans publicité.</p>
            </div>
        </div>
    </div>
</section>

<section id="demo">
    <div class="container">
        <h2>Démonstration</h2>
        <div style="position:relative;padding-bottom:56.25%;height:0;">
            <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ"
                    style="position:absolute;width:100%;height:100%;border:0;"
                    allowfullscreen></iframe>
        </div>
    </div>
</section>

<section id="contact" class="contact">
    <div class="container">
        <h2>Contact</h2>
        <p>Partenariats, support ou presse</p>
    </div>
</section>

<footer>
    © 2026 HB IMMERSIVE — Tous droits réservés
</footer>

</body>
</html>
