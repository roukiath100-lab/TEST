<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="MG Consulting Group - Cabinet de conseil en Analyse Financière, Stratégie et Veille en Afrique de l'Ouest.">
    <title>MG Consulting Group | Finance & Stratégie</title>
    
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

    <style>
        /* --- VARIABLES & RESET --- */
        :root {
            --primary-color: #0f172a; /* Bleu Nuit */
            --secondary-color: #ca8a04; /* Or/Bronze */
            --light-bg: #f8fafc;
            --text-color: #334155;
            --white: #ffffff;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Open Sans', sans-serif; color: var(--text-color); line-height: 1.6; background-color: var(--light-bg); }
        h1, h2, h3, h4 { font-family: 'Montserrat', sans-serif; font-weight: 700; color: var(--primary-color); }
        a { text-decoration: none; color: inherit; transition: 0.3s; }
        ul { list-style: none; }

        /* --- HEADER STICKY --- */
        header {
            background-color: var(--white);
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 5%;
            max-width: 1200px;
            margin: 0 auto;
        }

        .logo { font-size: 1.5rem; font-weight: 700; color: var(--primary-color); border-left: 5px solid var(--secondary-color); padding-left: 10px; }
        .logo span { color: var(--secondary-color); }

        .nav-links { display: flex; gap: 2rem; }
        .nav-links a { font-weight: 600; font-size: 0.9rem; text-transform: uppercase; }
        .nav-links a:hover { color: var(--secondary-color); }

        .btn-contact { background-color: var(--primary-color); color: var(--white); padding: 0.7rem 1.5rem; border-radius: 5px; font-weight: 600; }
        .btn-contact:hover { background-color: var(--secondary-color); color: var(--white); }
        .menu-toggle { display: none; font-size: 1.5rem; cursor: pointer; }

        /* --- HERO SECTION (IMAGE DE FOND) --- */
        #hero {
            /* Image : Réunion stratégique / Analyse de documents */
            background: linear-gradient(rgba(15, 23, 42, 0.85), rgba(15, 23, 42, 0.7)), url('https://images.unsplash.com/photo-1542744173-8e7e53415bb0?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80');
            background-size: cover;
            background-position: center;
            height: 90vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: var(--white);
            padding: 0 20px;
            margin-top: 60px;
        }

        #hero h1 { font-size: 3rem; margin-bottom: 1rem; color: var(--white); }
        #hero p { font-size: 1.2rem; margin-bottom: 2rem; max-width: 800px; margin-left: auto; margin-right: auto; }
        
        .btn-hero { background-color: var(--secondary-color); color: var(--white); padding: 1rem 2rem; font-size: 1.1rem; border-radius: 5px; font-weight: 700; border: 2px solid var(--secondary-color); }
        .btn-hero:hover { background-color: transparent; color: var(--secondary-color); }

        /* --- KEY FIGURES SECTION (NOUVEAU) --- */
        #stats {
            background-color: var(--primary-color);
            color: var(--white);
            padding: 3rem 5%;
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            text-align: center;
        }
        .stat-item { margin: 1rem; }
        .stat-item i { font-size: 2rem; color: var(--secondary-color); margin-bottom: 10px; }
        .stat-item h3 { color: var(--white); font-size: 1.5rem; }
        .stat-item p { font-size: 0.9rem; opacity: 0.8; }

        /* --- SERVICES SECTION --- */
        #services { padding: 5rem 5%; max-width: 1200px; margin: 0 auto; }
        .section-title { text-align: center; margin-bottom: 3rem; }
        .section-title h2 { font-size: 2.5rem; margin-bottom: 1rem; }
        .section-title span { display: block; width: 80px; height: 4px; background-color: var(--secondary-color); margin: 0 auto; }
        
        .services-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; }
        .service-card { background: var(--white); padding: 2rem; border-radius: 10px; box-shadow: 0 5px 15px rgba(0,0,0,0.05); transition: transform 0.3s ease; border-bottom: 4px solid transparent; }
        .service-card:hover { transform: translateY(-10px); border-bottom: 4px solid var(--secondary-color); }
        .icon-box { font-size: 2.5rem; color: var(--secondary-color); margin-bottom: 1.5rem; }
        .service-card h3 { margin-bottom: 1rem; font-size: 1.3rem; }
        .service-card ul { margin-top: 1rem; font-size: 0.9rem; color: #64748b; }
        .service-card li { margin-bottom: 5px; }
        .service-card li i { color: var(--secondary-color); margin-right: 5px; }

        /* --- ABOUT SECTION (IMAGE À DROITE) --- */
        #about { background-color: var(--white); padding: 5rem 5%; }
        .about-container { max-width: 1200px; margin: 0 auto; display: flex; flex-wrap: wrap; align-items: center; gap: 4rem; }
        .about-text { flex: 1; min-width: 300px; }
        
        .about-image { 
            flex: 1; 
            min-width: 300px; 
            height: 400px;
            /* Image : Partenariat / Poignée de main / Discussion business */
            background: url('https://images.unsplash.com/photo-1556761175-5973dc0f32e7?ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80') center/cover;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }

        .about-text h2 { margin-bottom: 1.5rem; font-size: 2.5rem; }
        .founders { background-color: var(--light-bg); padding: 1.5rem; border-left: 4px solid var(--secondary-color); margin-top: 2rem; }

        /* --- CONTACT SECTION (AMELIOREE) --- */
        #contact { padding: 5rem 5%; background-color: var(--light-bg); }
        #contact h2 { text-align: center; margin-bottom: 3rem; color: var(--primary-color); }

        .contact-container { max-width: 1000px; margin: 0 auto; display: flex; flex-wrap: wrap; gap: 3rem; background: var(--white); padding: 3rem; border-radius: 10px; box-shadow: 0 10px 30px rgba(0,0,0,0.05); }
        .contact-info, .contact-form { flex: 1; min-width: 300px; }

        .info-item { display: flex; align-items: center; margin-bottom: 2rem; }
        .info-item i { font-size: 1.5rem; color: var(--secondary-color); margin-right: 1.5rem; background: rgba(202, 138, 4, 0.1); padding: 15px; border-radius: 50%; }

        form input, form select, form textarea { width: 100%; padding: 1rem; margin-bottom: 1rem; border: 1px solid #e2e8f0; border-radius: 5px; font-family: inherit; background-color: #f8fafc; transition: 0.3s; }
        form input:focus, form select:focus, form textarea:focus { border-color: var(--secondary-color); outline: none; background-color: #fff; }
        
        form button { background-color: var(--secondary-color); color: var(--white); border: none; padding: 1rem 2rem; font-weight: 700; cursor: pointer; width: 100%; border-radius: 5px; transition: 0.3s; }
        form button:hover { background-color: #b45309; }

        /* --- FOOTER --- */
        footer { background-color: #020617; color: #94a3b8; padding: 3rem 5%; font-size: 0.9rem; }
        .footer-content { max-width: 1200px; margin: 0 auto; display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem; }
        .footer-col h4 { color: var(--white); margin-bottom: 1rem; font-size: 1.1rem; }
        .footer-col ul li { margin-bottom: 0.5rem; }
        .footer-col ul li a:hover { color: var(--secondary-color); }

        /* --- WHATSAPP FLOAT --- */
        .whatsapp-float { position: fixed; width: 60px; height: 60px; bottom: 40px; right: 40px; background-color: #25d366; color: #FFF; border-radius: 50px; text-align: center; font-size: 30px; box-shadow: 2px 2px 3px #999; z-index: 100; display: flex; align-items: center; justify-content: center; transition: 0.3s; }
        .whatsapp-float:hover { transform: scale(1.1); background-color: #128c7e; }

        /* --- RESPONSIVE --- */
        @media (max-width: 768px) {
            .nav-links { display: none; }
            .menu-toggle { display: block; }
            #hero h1 { font-size: 2rem; }
            .about-container { flex-direction: column-reverse; }
        }
    </style>
</head>
<body>

    <header>
        <div class="navbar">
            <div class="logo">MG <span>Consulting</span> Group</div>
            <nav class="nav-links">
                <a href="#hero">Accueil</a>
                <a href="#services">Expertises</a>
                <a href="#about">Le Cabinet</a>
                <a href="#contact" class="btn-contact">Devis Gratuit</a>
            </nav>
            <div class="menu-toggle"><i class="fas fa-bars"></i></div>
        </div>
    </header>

    <section id="hero">
        <div class="hero-content">
            <h1>Expertise Financière & Stratégique <br> en Afrique de l'Ouest</h1>
            <p>Nous transformons vos défis financiers en opportunités de croissance durable. Accompagnement sur-mesure pour PME, ONG et Grands Comptes.</p>
            <a href="#contact" class="btn-hero">Parler à un Expert</a>
        </div>
    </section>

    <section id="stats">
        <div class="stat-item">
            <i class="fas fa-shield-alt"></i>
            <h3>100%</h3>
            <p>Confidentialité Assurée</p>
        </div>
        <div class="stat-item">
            <i class="fas fa-globe-africa"></i>
            <h3>Régional</h3>
            <p>Expertise Ouest-Africaine</p>
        </div>
        <div class="stat-item">
            <i class="fas fa-hand-holding-usd"></i>
            <h3>Sur-Mesure</h3>
            <p>Solutions de Financement</p>
        </div>
        <div class="stat-item">
            <i class="fas fa-clock"></i>
            <h3>Réactif</h3>
            <p>Accompagnement Dédié</p>
        </div>
    </section>

    <section id="services">
        <div class="section-title">
            <h2>Nos Domaines d'Intervention</h2>
            <span></span>
        </div>
        
        <div class="services-grid">
            <div class="service-card">
                <div class="icon-box"><i class="fas fa-chart-line"></i></div>
                <h3>Analyse Financière & Pilotage</h3>
                <p>Transformez vos chiffres en outils de décision.</p>
                <ul>
                    <li><i class="fas fa-check"></i> Diagnostic financier complet</li>
                    <li><i class="fas fa-check"></i> Tableaux de bord & KPI</li>
                    <li><i class="fas fa-check"></i> Optimisation de trésorerie</li>
                </ul>
            </div>

            <div class="service-card">
                <div class="icon-box"><i class="fas fa-coins"></i></div>
                <h3>Finance d'Entreprise</h3>
                <p>Structurez votre capital pour grandir sereinement.</p>
                <ul>
                    <li><i class="fas fa-check"></i> Montage dossier de crédit</li>
                    <li><i class="fas fa-check"></i> Business Plans prévisionnels</li>
                    <li><i class="fas fa-check"></i> Levée de fonds</li>
                </ul>
            </div>

            <div class="service-card">
                <div class="icon-box"><i class="fas fa-eye"></i></div>
                <h3>Veille Stratégique</h3>
                <p>Anticipez les opportunités et les risques du marché.</p>
                <ul>
                    <li><i class="fas fa-check"></i> Veille concurrentielle</li>
                    <li><i class="fas fa-check"></i> Alertes appels d'offres</li>
                    <li><i class="fas fa-check"></i> Veille réglementaire</li>
                </ul>
            </div>

            <div class="service-card">
                <div class="icon-box"><i class="fas fa-chess"></i></div>
                <h3>Stratégie & Décision</h3>
                <p>Diagnostics clairs pour des décisions complexes.</p>
                <ul>
                    <li><i class="fas fa-check"></i> Analyse SWOT & PESTEL</li>
                    <li><i class="fas fa-check"></i> Étude de scénarios</li>
                    <li><i class="fas fa-check"></i> Gestion des risques</li>
                </ul>
            </div>

            <div class="service-card">
                <div class="icon-box"><i class="fas fa-hand-holding-heart"></i></div>
                <h3>ONG & Développement</h3>
                <p>Expertise dédiée aux projets à impact social.</p>
                <ul>
                    <li><i class="fas fa-check"></i> Budgétisation de projets</li>
                    <li><i class="fas fa-check"></i> Reporting bailleurs de fonds</li>
                    <li><i class="fas fa-check"></i> Études d'impact</li>
                </ul>
            </div>
        </div>
    </section>

    <section id="about">
        <div class="about-container">
            <div class="about-text">
                <h2>L'Excellence au service de votre Vision</h2>
                <p>Dans un environnement économique ouest-africain en pleine mutation, la navigation à vue n'est plus une option. <strong>MG Consulting Group</strong> est né de la volonté d'apporter aux PME et ONG une expertise de haut niveau.</p>
                <p>Nous combinons rigueur méthodologique et connaissance du terrain pour sécuriser vos financements et optimiser votre stratégie.</p>
                
                <div class="founders">
                    <p>Fondé par <strong>TCHANI Moubarak</strong> et <strong>Abdel Ganiyou</strong>, experts en finance et intelligence économique.</p>
                </div>
            </div>
            <div class="about-image"></div>
        </div>
    </section>

    <section id="contact">
        <h2>Parlons de votre Projet</h2>
        <div class="contact-container">
            <div class="contact-info">
                <div class="info-item">
                    <i class="fas fa-map-marker-alt"></i>
                    <div>
                        <h4>Notre Bureau</h4>
                        <p>Zone Économique, Afrique de l'Ouest</p>
                    </div>
                </div>
                <div class="info-item">
                    <i class="fas fa-envelope"></i>
                    <div>
                        <h4>Email</h4>
                        <p>contact@mg-consulting-group.com</p>
                    </div>
                </div>
                <div class="info-item">
                    <i class="fas fa-phone-alt"></i>
                    <div>
                        <h4>Téléphone</h4>
                        <p>+22X XX XX XX XX</p>
                    </div>
                </div>
            </div>

            <div class="contact-form">
                <form>
                    <input type="text" placeholder="Votre Nom complet" required>
                    <input type="email" placeholder="Votre Email professionnel" required>
                    <select>
                        <option value="">Type de Besoin</option>
                        <option value="audit">Analyse Financière / Audit</option>
                        <option value="funding">Recherche de Financement</option>
                        <option value="strategy">Conseil Stratégique</option>
                        <option value="ong">Projet ONG / Développement</option>
                    </select>
                    <textarea rows="4" placeholder="Décrivez brièvement votre projet..."></textarea>
                    <button type="submit">Envoyer la demande</button>
                </form>
            </div>
        </div>
    </section>

    <footer>
        <div class="footer-content">
            <div class="footer-col">
                <h4>MG Consulting Group</h4>
                <p>Votre partenaire stratégique pour la performance financière et le développement en Afrique de l'Ouest.</p>
            </div>
            <div class="footer-col">
                <h4>Liens Rapides</h4>
                <ul>
                    <li><a href="#hero">Accueil</a></li>
                    <li><a href="#services">Nos Services</a></li>
                    <li><a href="#about">À Propos</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </div>
            <div class="footer-col">
                <h4>Suivez-nous</h4>
                <ul>
                    <li><a href="#"><i class="fab fa-linkedin"></i> LinkedIn</a></li>
                    <li><a href="#"><i class="fab fa-twitter"></i> Twitter</a></li>
                </ul>
            </div>
        </div>
        <div style="text-align: center; margin-top: 2rem; border-top: 1px solid #1e293b; padding-top: 1rem;">
            <p>&copy; 2026 MG Consulting Group. Tous droits réservés.</p>
        </div>
    </footer>

    <a href="https://wa.me/22XXXXXXXXXX" class="whatsapp-float" target="_blank">
        <i class="fab fa-whatsapp"></i>
    </a>

    <script>
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        document.querySelector('form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Merci ! Votre demande a été reçue. Un expert de MG Consulting vous contactera sous 24h.');
        });
    </script>
</body>
</html>
