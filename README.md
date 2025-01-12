<!DOCTYPE html>
<html lang="en">

<head>
    <!-- Basic Meta Tags -->
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <title>BIENVENUE DANS LES PRINCIPALES ACTIVITÉS DU SECOURS POPULAIRE HARFLEUR.</title>

    <!-- Favicon -->
    <link rel="icon" type="image/svg+xml" href="/img/icons/favicon.svg">
    <link rel="icon" type="image/png" sizes="32x32" href="/img/icons/favicon-32x32.png">

    <!-- External Stylesheets -->
    <link rel="stylesheet" href="/css/chunk-vendors.8eef9120.css">
    <!-- Add FontAwesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">

    <!-- Custom Styles -->
    <style>
        /* General Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(45deg, #0055A4, #FFFFFF, #EF4135);
            background-size: 200% 200%;
            animation: gradientMovement 6s ease infinite;
            color: #333;
            height: 100vh;
            background-position: center;
        }

        h1,
        h2,
        h3 {
            margin-bottom: 20px;
        }

        button {
            cursor: pointer;
            padding: 10px 20px;
            font-size: 16px;
            background-color: #0055A4;
            color: white;
            border: none;
            border-radius: 5px;
            transition: background-color 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 0 10px rgba(0, 85, 164, 0.8);
        }

        button:hover {
            background-color: #EF4135;
            box-shadow: 0 0 20px rgba(239, 65, 53, 0.8);
        }

        .navbar {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 10px;
        }

        .navbar button {
            background-color: #555;
        }

        .navbar button:hover {
            background-color: #444;
        }

        /* Hero Section */
        .hero {
            background: url('your-hero-image.jpg') center/cover no-repeat;
            padding: 80px 20px;
            color: rgb(152, 141, 226);
            text-align: center;
            position: relative;
        }

        .hero-text h2 {
            font-size: 2.5rem;
            animation: fadeIn 2s ease-out;
        }

        /* Logs Section */
        .logs-section {
            display: flex;
            justify-content: space-between;
            padding: 60px 20px;
            margin-top: 40px;
            flex-wrap: wrap;
            gap: 20px;
        }

        .log {
            width: 45%;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
            text-align: center;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .log img {
            max-width: 100%;
            border-radius: 8px;
            margin-bottom: 20px;
        }

        .log h3 {
            font-size: 1.5rem;
            color: #333;
            margin-bottom: 10px;
        }

        .log p {
            font-size: 1rem;
            color: #666;
        }

        /* Footer Section */
        .footer {
            background-color: #333;
            color: white;
            padding: 40px 20px;
            text-align: center;
            margin-top: 40px;
        }

        .footer .about,
        .footer .links,
        .footer .social {
            margin-bottom: 20px;
        }

        .footer .links a,
        .footer .social a {
            display: inline-block;
            color: #fff;
            text-decoration: none;
            font-size: 1rem;
            margin: 5px 15px;
            transition: color 0.3s;
        }

        .footer .social {
            display: flex;
            justify-content: center;
            gap: 15px;
        }

        .footer .social a {
            font-size: 1.5rem;
        }

        .footer .social a:hover {
            color: #EF4135;
        }

        @media (max-width: 768px) {
            .footer {
                padding: 20px;
            }

            .footer .links a {
                margin: 5px 10px;
            }

            .footer .social img {
                width: 35px;
                height: 35px;
            }

            .logs-section {
                flex-direction: column;
                align-items: center;
            }

            .log {
                width: 80%;
                margin-bottom: 20px;
            }
        }

        /* Keyframe Animations */
        @keyframes gradientMovement {
            0% {
                background-position: 0% 50%;
            }

            50% {
                background-position: 100% 50%;
            }

            100% {
                background-position: 0% 50%;
            }
        }

        @keyframes fadeIn {
            0% {
                opacity: 0;
            }

            100% {
                opacity: 1;
            }
        }
    </style>
</head>

<body>
    <header class="header">
        <div class="logo">SECOURS POPULAIRE HARFLEUR.</div>
        <nav class="navbar">
            <button><i class="fas fa-box"></i> Bric à Brac</button>
            <button><i class="fas fa-store"></i> Secours Populaire Français Solidair Boutique</button>
            <button><a href="https://www.secourspopulaire.fr/76-harfleur/secours-populaire/" target="_blank"
                    style="color: white; text-decoration: none;">
                    <i class="fas fa-building"></i> Jean Barbe Bureaux</a></button>
            <button><i class="fas fa-phone-alt"></i> Contact</button>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-text">
            <h2>Bienvenue aux principales activités du Secours Populaire Harfleur.</h2>
            <p>“Tout ce qui est humain est nôtre”</p>
        </div>
    </section>

    <!-- Logs Section -->
    <section class="logs-section">
        <!-- Left Log -->
        <div class="log">
            <img src="sfphrflr.jpeg" alt="sfphrflr.jpeg">
            <h3>Où nous trouver ?</h3>
            <p>Le Secours populaire est une association de terrain, indépendante et décentralisée...</p>
        </div>
        <!-- Right Log -->
        <div class="log">
            <img src="spf-harfleur.jpeg" alt="spf-harfleur.jpeg">
            <h3>On peut donner du bonheur, on peut aussi le transmettre</h3>
            <p>Jour après jour, ici comme ailleurs...</p>
        </div>
    </section>

    <footer class="footer">
        <div class="about">
            <h3>Qui sommes-nous</h3>
            <p>Explorez les dernières actualités et restez informé(e)...</p>
        </div>
        <div class="links">
            <a href="index.html">Accueil</a>
            <a href="categories.html">Catégories</a>
            <a href="tendances.html">Tendances</a>
            <a href="archives.html">Archives</a>
            <a href="contact.html">Nous Contacter</a>
        </div>
        <div class="social">
            <a href="#"><i class="fab fa-facebook-f"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
            <a href="#"><i class="fab fa-linkedin-in"></i></a>
        </div>
        <p>&copy; 2024 Secours Populaire Harfleur. Tous droits réservés.</p>
    </footer>
</body>

</html>
