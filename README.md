<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jhay Unlocker (J-R Design) - Designer Créatif</title>
    <style>
        /* Styles de base */
        body {
            background-color: #0D1117;
            color: #FFFFFF;
            font-family: 'Roboto', Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        
        /* Animation au défilement */
        .fade-in {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.6s ease-out, transform 0.6s ease-out;
        }
        .fade-in.active {
            opacity: 1;
            transform: translateY(0);
        }

        /* Header */
        header {
            background: #1E1E2E;
            padding: 20px;
            text-align: center;
            border-bottom: 4px solid #1D9BF0;
        }
        header h1 {
            color: #FFFFFF;
            font-size: 2em;
            text-shadow: 0px 4px 10px rgba(29, 155, 240, 0.5);
        }
        nav a {
            color: #1D9BF0;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: #F0F8FF;
            border-bottom: 2px solid #F0F8FF;
        }

        /* Sections */
        .section {
            padding: 40px 20px;
            background-color: #10141C;
            margin: 20px auto;
            max-width: 1000px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            border: 2px solid #1D9BF0;
            position: relative;
        }

        /* Shape styles */
        .shape {
            position: absolute;
            border-radius: 50%;
            opacity: 0.1;
        }
        .shape.shape1 {
            width: 200px;
            height: 200px;
            top: -50px;
            right: -50px;
            background: #1D9BF0;
            animation: float 6s ease-in-out infinite;
        }
        .shape.shape2 {
            width: 150px;
            height: 150px;
            bottom: -50px;
            left: -50px;
            background: #1D9BF0;
            animation: float 8s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% {
                transform: translateY(0px);
            }
            50% {
                transform: translateY(-20px);
            }
        }

        h2 {
            color: #1D9BF0;
            font-size: 1.8em;
            position: relative;
        }

        /* Liste de services avec effet au survol */
        .service ul {
            list-style-type: none;
            padding: 0;
        }
        .service ul li {
            background-color: #1E1E2E;
            color: #1D9BF0;
            margin: 10px 0;
            padding: 10px;
            border-radius: 5px;
            border: 2px solid #1D9BF0;
            transition: transform 0.3s, border 0.3s;
        }
        .service ul li:hover {
            transform: scale(1.05);
            border: 2px solid #F0F8FF;
        }
        
        /* Formulaire de contact */
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 2px solid #1D9BF0;
            border-radius: 8px;
            background: #0D1117;
            color: #FFFFFF;
            box-shadow: inset 0 2px 4px rgba(0, 0, 0, 0.5);
        }
        .contact-form button {
            background: #1D9BF0;
            color: #FFFFFF;
            padding: 10px 20px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: background 0.3s, transform 0.3s;
        }
        .contact-form button:hover {
            background: #0A8FD4;
            transform: scale(1.05);
        }

        /* Footer */
        .footer {
            background-color: #1E1E2E;
            text-align: center;
            padding: 10px;
            color: #999;
            border-top: 2px solid #1D9BF0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Jhay Unlocker (J-R Design)</h1>
        <nav>
            <a href="#about">À propos</a>
            <a href="#services">Services</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="about" class="section about fade-in">
        <div class="shape shape1"></div>
        <h2>🌟 Designer Créatif</h2>
        <p>🎨 Graphiste | Spécialiste UI/UX</p>
        <p>✍️ Stratège de Contenu</p>
        <p>🎥 Motion Design & Montage Vidéo</p>
        <p>✨ Création de Logos Personnalisés & Identité de Marque</p>
        <p>📲 Déblocage de Téléphones (Android, iPhone) | Déblocage Réseau & ID</p>
    </section>

    <section id="services" class="section service fade-in">
        <div class="shape shape2"></div>
        <h2>Nos Services</h2>
        <p>Création de logos, flyers, design UI/UX, montage vidéo, et bien plus.</p>
        <p>📲 Spécialisé dans le déblocage de téléphones (Android et iPhone).</p>
        <p>🪄 Suivi du Programme Humanitaire de Biden (CBP - USCIS, Vérification de Case).</p>
        <p><span class="highlight">Pour commencer un projet, un dépôt est requis :</span></p>
        <ul>
            <li>Natcash : 32838891 (Nom : Jonel Registre)</li>
            <li>Moncash : 44315552 (Nom : Jonel Registre)</li>
        </ul>
        <p>Sans dépôt, aucun travail ne pourra débuter. Merci de votre compréhension et de votre patience.</p>
        <p>📧 Email : jonelregistre5@gmail.com</p>
        <p>📱 WhatsApp : (+509)3283-8891 | Appel : (+509)4431-5552</p>
    </section>

  <section id="contact" class="section contact fade-in">
        <h2>Contactez-moi</h2>
        <p>Pour toute demande, laissez un message détaillant le service souhaité et l’objectif de votre demande. Je vous répondrai dès que possible.</p>
        <form class="contact-form">
            <input type="text" placeholder="Nom" required>
            <input type="email" placeholder="Email" required>
            <textarea placeholder="Votre message" required></textarea>
            <button type="submit">Envoyer</button>
        </form>
    </section>

    <footer class="footer">
        <p>&copy; 2024 Jhay Unlocker (J-R Design). Tous droits réservés.</p>
    </footer>

    <script>
        // Animation au défilement
        const faders = document.querySelectorAll('.fade-in');
        const appearOptions = {
            threshold: 0.2,
            rootMargin: "0px 0px -50px 0px"
        };
        const appearOnScroll = new IntersectionObserver(function(entries, appearOnScroll) {
            entries.forEach(entry => {
                if (!entry.isIntersecting) return;
                entry.target.classList.add("active");
                appearOnScroll.unobserve(entry.target);
            });
        }, appearOptions);
        faders.forEach(fader => appearOnScroll.observe(fader));
    </script>
</body>
