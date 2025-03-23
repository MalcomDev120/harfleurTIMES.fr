<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Harfleur Times</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Georgia', serif;
            line-height: 1.6;
            color: #333;
            background-color: #f8f8f8;
        }

        /* Header */
        .header {
            background-color: #000;
            color: #fff;
            padding: 20px 0;
        }

        .logo-container {
            text-align: center;
        }

        .logo {
            font-size: 36px;
            font-weight: bold;
        }

        .navbar ul {
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        .navbar ul li {
            list-style: none;
        }

        .navbar button {
            background: none;
            border: 1px solid #fff;
            color: #fff;
            padding: 10px 20px;
            cursor: pointer;
            transition: background 0.3s ease;
        }

        .navbar button:hover {
            background-color: #333;
        }

        /* Hero Section */
        .hero {
            background: url('harfleur view.jpeg') center/cover no-repeat, rgba(255, 255, 255, 0.5);
            color: #fff;
            padding: 80px 20px;
            text-align: center;
        }

        .hero h2 {
            font-size: 40px;
            font-weight: bold;
            margin-bottom: 20px;
        }

        /* Main Content Layout */
        .main-content-wrapper {
            display: flex;
            justify-content: space-between;
            gap: 20px;
            flex-wrap: wrap;
            margin: 0 auto;
            max-width: 1200px;
        }

        .registration-form,
        .trending {
            width: 48%;
            box-sizing: border-box;
        }

        @media (max-width: 768px) {

            .registration-form,
            .trending {
                width: 100%;
            }
        }

        /* Registration Form */
        .registration-form {
            background: #fff;
            padding: 40px;
            max-width: 700px;
            margin: 40px auto;
            border-radius: 8px;
        }

        .registration-form h2 {
            font-size: 28px;
            margin-bottom: 20px;
        }

        .registration-form label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
        }

        .registration-form input,
        .registration-form select {
            width: 100%;
            padding: 12px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        .registration-form button {
            background-color: #d4a6a6;
            color: #fff;
            border: none;
            padding: 12px;
            cursor: pointer;
            width: 100%;
            font-size: 16px;
            border-radius: 4px;
        }

        .registration-form button:hover {
            background-color: #c2b2b2;
        }

        /* Trending Section */
        .trending .hero-text {
            margin-bottom: 20px;
        }

        .trending h2 {
            font-size: 24px;
            margin-bottom: 10px;
        }

        .trending p {
            font-size: 16px;
            line-height: 1.5;
        }

        /* Footer */
        .footer {
            background-color: #624141;
            color: #fff;
            padding: 40px 20px;
            text-align: center;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }

        .footer h3 {
            margin-bottom: 20px;
            font-size: 20px;
            font-weight: bold;
        }

        .footer p {
            margin-top: 10px;
            font-size: 14px;
        }

        .footer .about,
        .footer .links,
        .footer .social {
            margin-bottom: 20px;
        }

        .footer .about p {
            font-size: 16px;
            line-height: 1.5;
        }

        .footer .links {
            display: flex;
            justify-content: center;
            gap: 15px;
        }

        .footer .links a {
            color: #fff;
            text-decoration: none;
            font-size: 16px;
            transition: color 0.3s ease;
        }

        .footer .links a:hover {
            color: #ccc;
        }

        .footer .social {
            display: flex;
            justify-content: center;
            gap: 15px;
        }

        .footer .social a img {
            width: 25px;
            height: 25px;
            transition: transform 0.3s ease;
        }

        .footer .social a img:hover {
            transform: scale(1.1);
        }

        /* Images Section */
        .images {
            text-align: center;
        }

        .image-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 100%;
            margin: 0 auto;
            flex-wrap: wrap;
        }

        .image {
            width: 23%;
            height: 300px;
            object-fit: cover;
            margin: 0 10px;
        }

        @media (max-width: 768px) {
            .image {
                width: 48%;
                /* Adjust for smaller screens */
                margin: 10px 0;
            }
        }

        .message {
            margin-top: 20px;
            animation: moveMessage 10s linear infinite;
        }

        @keyframes moveMessage {
            0% {
                transform: translateX(100%);
            }

            100% {
                transform: translateX(-100%);
            }
        }

        .message h2 {
            font-size: 24px;
            font-weight: bold;
            white-space: nowrap;
        }
    </style>
</head>

<body>
    <header class="header">
        <div class="logo-container">
            <h1 class="logo">Harfleur TIMES</h1>
        </div>
        <nav class="navbar">
            <ul>
                <li><button onclick="location.href='actualites.html'">Actualités Mondiales</button></li>
                <li><button onclick="location.href='Divertissement.html'">Divertissement</button></li>
                <li><button onclick="location.href='emplois.html'">Emplois et Compétences</button></li>
                <li><button onclick="location.href='affaires.html'">Affaires</button></li>
                <li><button onclick="location.href='technologie.html'">Technologie</button></li>
                <li><button onclick="location.href='Bric à Brac.html'">MalcomShoppingCentre</button></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero">
            <div class="hero-text">
                <h1>Harfleur Times, Vous connectent au Monde.</h1>
                <p>
                    Harfleur Times vous rapproche du monde en vous connectant à des sources fiables. Nous vous
                    fournissons des informations, des nouvelles et des services qui rendent la vie plus simple.
                </p>
            </div>
        </section>

        <div class="main-content-wrapper">
            <section class="registration-form">
                <h2>Inscription</h2>
                <form action="/register" method="post">
                    <label for="nom">Nom</label>
                    <input type="text" name="name" id="nom" required />

                    <label for="prenom">Prénom</label>
                    <input type="text" name="prenom" id="prenom" required />

                    <label for="age">Âge</label>
                    <input type="number" name="age" id="age" required />

                    <label for="email">Email</label>
                    <input type="email" name="email" id="email" required />

                    <label for="abonnement">Abonnement</label>
                    <select name="abonnement" id="abonnement">
                        <option value="non">Non</option>
                        <option value="actualités">Abonnement aux actualités</option>
                        <option value="formation">Abonnement aux formations</option>
                        <option value="publicité">Abonnement pour la publicité</option>
                        <option value="enterprise">Abonnement d'entreprise</option>
                    </select>

                    <button type="submit">S'inscrire</button>
                </form>
            </section>

            <section class="trending">
                <div class="hero-text">
                    <h1>Pour profiter pleinement de nos services, vous devez vous abonner à nous.</h1>
                </div>
                <div class="paragraphs">
                    <h2>Ce que vous devez savoir sur nous.</h2>
                    <p>Nous sommes les personnes les plus efficaces avec lesquelles travailler et nous rencontrons
                        chaque jour tellement de choses qui affectent positivement la vie des gens...</p>
                </div>
            </section>
        </div>

        <section class="images">
            <h2>Notre groupe d'experts</h2>
            <div class="image-container">
                <img src="malcom website .jpeg" alt="image 1" class="image">
                <img src="webdesign 2.jpg" alt="image 2" class="image">
                <img src="image2 design.png" alt="image 3" class="image">
                <img src="image5.jpg" alt="image 3" class="image">
            </div>
            <div class="message">
                <h2>Un message fort pour vous !</h2>
            </div>
        </section>
    </main>

    <footer class="footer">
        <div class="about">
            <h2>Qui sommes-nous</h2>
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
            <h3>Suivez-nous</h3>
            <a href="#"><img src="https://harfleur-times.netlify.app/assets/assets/facebook_icon.png"
                    alt="Facebook" /></a>
            <a href="#"><img src="https://harfleur-times.netlify.app/assets/assets/twitter_icon.png"
                    alt="Twitter" /></a>
            <a href="#"><img src="https://harfleur-times.netlify.app/assets/assets/instagram_icon.png"
                    alt="Instagram" /></a>
            <a href="#"><img src="https://harfleur-times.netlify.app/assets/assets/linkedin_icon.png"
                    alt="LinkedIn" /></a>
        </div>
        <p>&copy; 2025 Harfleur Times. Tous droits réservés.</p>
    </footer>
</body>

</html>  

