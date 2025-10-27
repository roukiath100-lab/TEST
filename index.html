<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Analyse Stratégique | Performance Insights</title>
    <!-- Chosen Palette: Warm Neutrals & Professional Blue/Teal -->
    <!-- Application Structure Plan: Structure thématique d'un rapport stratégique interactif. Une navigation fixe permet de sauter aux sections clés (Marché, Finances, Stratégie, Roadmap, BMC). Cette structure est choisie car elle reflète le flux de pensée d'un investisseur : 'Qu'est-ce que c'est ?', 'Est-ce un gros marché ?', 'Est-ce rentable ?', 'Quels sont les risques ?', 'Quel est le plan ?', 'Comment ça marche en résumé ?'. L'interactivité se concentre sur les chiffres (P&L) et la visualisation des jalons. -->
    <!-- Visualization & Content Choices: 
        - Marché -> Inform/Organize -> Doughnut Chart (Chart.js) -> Hover Tooltips -> Montre la segmentation du marché (SAM/SOM). (No SVG/Mermaid)
        - Finances -> Explore/Inform -> Bar Chart (Chart.js) + HTML Slider -> L'utilisateur fait glisser "Unités" (0-3000), JS met à jour le Bar Chart (CA, COGS, EBITDA) & le texte P/L -> Rend le P&L interactif et démontre le seuil de rentabilité. (No SVG/Mermaid)
        - Stratégie -> Inform -> HTML/Tailwind Cards (Unicode icons) -> Pas d'interaction -> Explique clairement le 'pourquoi' du prix élevé et du long délai. (No SVG/Mermaid)
        - Roadmap -> Change/Organize -> Timeline Horizontale (HTML/Flexbox) -> Pas d'interaction -> Visualisation simple et claire des phases du projet. (No SVG/Mermaid)
        - BMC -> Organize/Inform -> 9-Box Grid (HTML/Grid) -> Pas d'interaction -> Cadre récapitulatif classique pour l'ensemble du business model. (No SVG/Mermaid)
    -->
    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8f9fa;
            color: #212529;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            height: 300px;
            max-height: 400px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 350px;
            }
        }
        .nav-link {
            transition: color 0.2s, border-bottom-color 0.2s;
            border-bottom: 2px solid transparent;
        }
        .nav-link:hover {
            color: #0d6efd;
            border-bottom-color: #0d6efd;
        }
        .nav-link-active {
            color: #0d6efd;
            border-bottom-color: #0d6efd;
            font-weight: 600;
        }
        .metric-card {
            background-color: white;
            border-radius: 0.75rem;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -2px rgba(0, 0, 0, 0.1);
            padding: 1.5rem;
            border-top: 4px solid #0d6efd;
        }
        .info-card {
            background-color: white;
            border-radius: 0.75rem;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -2px rgba(0, 0, 0, 0.1);
            padding: 1.5rem;
        }
        .bmc-grid {
            display: grid;
            grid-template-columns: repeat(1, minmax(0, 1fr));
            gap: 1rem;
        }
        @media (min-width: 1024px) {
            .bmc-grid {
                grid-template-columns: repeat(5, minmax(0, 1fr));
                grid-template-rows: repeat(3, minmax(0, auto));
            }
        }
        .bmc-card {
            background-color: white;
            padding: 1rem;
            border-radius: 0.5rem;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
            border: 1px solid #e5e7eb;
            min-height: 150px;
        }
    </style>
</head>
<body class="bg-gray-50">

    <header class="sticky top-0 bg-white shadow-md z-50">
        <nav class="container mx-auto px-4 sm:px-6 lg:px-8 flex justify-between items-center h-16">
            <div class="text-2xl font-bold text-blue-700">Performance Insights</div>
            <div class="hidden md:flex space-x-6">
                <a href="#accueil" class="nav-link px-2 py-1">Accueil</a>
                <a href="#marche" class="nav-link px-2 py-1">Marché</a>
                <a href="#finances" class="nav-link px-2 py-1">Finances</a>
                <a href="#strategie" class="nav-link px-2 py-1">Stratégie</a>
                <a href="#deploiement" class="nav-link px-2 py-1">Déploiement</a>
                <a href="#bmc" class="nav-link px-2 py-1">BMC</a>
            </div>
        </nav>
    </header>

    <main class="container mx-auto px-4 sm:px-6 lg:px-8 py-8">

        <!-- ===== Section Accueil ===== -->
        <section id="accueil" class="min-h-[80vh] flex flex-col justify-center py-16">
            <h1 class="text-5xl font-extrabold text-gray-900 mb-4">Analyse Stratégique</h1>
            <h2 class="text-3xl font-semibold text-blue-700 mb-8">Dispositif de Suivi Métabolique en Temps Réel</h2>
            <p class="text-lg text-gray-700 max-w-3xl mb-12">
                Cette analyse présente le plan stratégique pour un dispositif de suivi continu des biomarqueurs (glucose et lactate) destiné aux athlètes d'endurance. L'objectif est de fournir un outil permettant l'ajustement instantané de la nutrition et de l'entraînement, répondant à un besoin non couvert de suivi métabolique en temps réel.
            </p>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="info-card border-l-4 border-red-500">
                    <h3 class="text-2xl font-bold mb-3"><span class="mr-2">❗️</span>Le Problème</h3>
                    <p class="text-gray-700">Les athlètes d'endurance rencontrent des baisses d'énergie imprévues et une difficulté à adapter leur entraînement/nutrition faute de données métaboliques internes. Les outils actuels (cardio, GPS) sont insuffisants.</p>
                </div>
                <div class="info-card border-l-4 border-green-500">
                    <h3 class="text-2xl font-bold mb-3"><span class="mr-2">💡</span>La Solution</h3>
                    <p class="text-gray-700">Un capteur miniaturisé pour le suivi continu du **glucose et du lactate**. Il permet de détecter les déséquilibres en temps réel, d'ajuster l'effort et d'optimiser la performance et la durabilité de la carrière.</p>
                </div>
            </div>
             <div class="mt-8 info-card border-l-4 border-blue-500">
                <h3 class="text-2xl font-bold mb-3"><span class="mr-2">🎯</span>La Cible (SAM Initial)</h3>
                <p class="text-gray-700">Le marché adressable initial (SAM) est un segment B2B premium : les **athlètes d'endurance professionnels et semi-professionnels** (cyclisme, course à pied, triathlon) ainsi que leurs **prescripteurs** (entraîneurs et nutritionnistes).</p>
            </div>
        </section>

        <!-- ===== Section Marché ===== -->
        <section id="marche" class="min-h-[90vh] py-16">
            <h2 class="text-4xl font-bold text-center mb-4">Le Potentiel de Marché (TAM/SAM/SOM)</h2>
            <p class="text-lg text-gray-700 text-center max-w-3xl mx-auto mb-12">
                L'analyse du marché se concentre sur le segment européen pour s'aligner sur les contraintes réglementaires (MDR/CE). Nous ciblons une niche premium B2B (SAM) avec un objectif de part de marché (SOM) réaliste à 2 ans, justifiant un prix élevé.
            </p>
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 items-center">
                <div class="chart-container h-96 md:h-[400px]">
                    <canvas id="marketChart"></canvas>
                </div>
                <div class="space-y-6">
                    <div class="metric-card">
                        <h3 class="text-lg font-semibold text-gray-600">TAM (Total Adressable Market)</h3>
                        <p class="text-4xl font-extrabold text-blue-700">~ $5-10 Milliards</p>
                        <p class="text-gray-600">Marché mondial du monitoring physiologique avancé pour le sport.</p>
                    </div>
                    <div class="metric-card">
                        <h3 class="text-lg font-semibold text-gray-600">SAM (Serviceable Available Market)</h3>
                        <p class="text-4xl font-extrabold text-blue-700">$95 Millions</p>
                        <p class="text-gray-600">100 000 utilisateurs Pro/Semi-Pro & coachs en Europe (cible B2B).</p>
                    </div>
                    <div class="metric-card border-t-4 border-teal-500">
                        <h3 class="text-lg font-semibold text-gray-600">SOM (Serviceable Obtainable Market)</h3>
                        <p class="text-4xl font-extrabold text-teal-600">$2.375 Millions (2.5%)</p>
                        <p class="text-gray-600">Objectif réaliste à 2 ans (2 500 unités/abonnements).</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===== Section Finances ===== -->
        <section id="finances" class="min-h-[90vh] py-16">
            <h2 class="text-4xl font-bold text-center mb-4">La Viabilité Financière (Mini P&L)</h2>
            <p class="text-lg text-gray-700 text-center max-w-3xl mx-auto mb-12">
                Le modèle financier est basé sur l'atteinte du SOM (2 500 unités). L'interactivité ci-dessous vous permet de simuler la rentabilité en fonction du volume de ventes, démontrant la robustesse du modèle et le point mort.
            </p>
            
            <div class="bg-white p-6 rounded-xl shadow-lg border border-gray-200">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                    <div>
                        <div class="mb-6">
                            <label for="unitsSlider" class="text-lg font-semibold text-gray-800">Simulateur d'unités vendues : <span id="unitsValue" class="font-extrabold text-blue-700">2500</span></label>
                            <input id="unitsSlider" type="range" min="0" max="3500" value="2500" class="w-full h-2 bg-gray-200 rounded-lg appearance-none cursor-pointer">
                        </div>
                        <div class="grid grid-cols-2 gap-4 text-center">
                            <div class="p-4 bg-blue-50 rounded-lg">
                                <h4 class="text-sm font-semibold text-blue-800">CHIFFRE D'AFFAIRES</h4>
                                <p id="caValue" class="text-2xl font-extrabold text-blue-800">€0</p>
                            </div>
                            <div class="p-4 bg-gray-50 rounded-lg">
                                <h4 class="text-sm font-semibold text-gray-700">PROFIT / PERTE (EBITDA)</h4>
                                <p id="profitValue" class="text-2xl font-extrabold text-red-600">€0</p>
                            </div>
                        </div>
                        <div class="mt-6 p-4 bg-gray-100 rounded-lg">
                            <h4 class="text-lg font-bold text-center mb-2">Hypothèses Clés</h4>
                            <ul class="divide-y divide-gray-300">
                                <li class="flex justify-between py-2 text-sm"><span class="text-gray-600">Prix Unitaire (PU)</span><span class="font-semibold">€870</span></li>
                                <li class="flex justify-between py-2 text-sm"><span class="text-gray-600">COGS Unitaire</span><span class="font-semibold">€165</span></li>
                                <li class="flex justify-between py-2 text-sm"><span class="text-gray-600">Frais Fixes Annuels</span><span class="font-semibold">€500 000</span></li>
                                <li class="flex justify-between pt-2 text-sm font-bold"><span class="text-gray-800">Point Mort (Unités)</span><span class="text-teal-600">709 Unités</span></li>
                            </ul>
                        </div>
                    </div>
                    <div class="chart-container h-96 md:h-[450px]">
                        <canvas id="pnlChart"></canvas>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===== Section Stratégie ===== -->
        <section id="strategie" class="min-h-[80vh] py-16">
            <h2 class="text-4xl font-bold text-center mb-4">Stratégie & Contraintes Sectorielles</h2>
            <p class="text-lg text-gray-700 text-center max-w-3xl mx-auto mb-12">
                Le modèle économique est directement dicté par les contraintes sectorielles. Ces "barrières à l'entrée" sont coûteuses mais créent un avantage compétitif durable en justifiant notre positionnement premium.
            </p>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="info-card border-l-4 border-red-500">
                    <h3 class="text-2xl font-bold mb-3"><span class="mr-2">🛡️</span> 1. Règlement Dispositifs Médicaux (MDR/CE)</h3>
                    <p class="text-gray-700 mb-4">En tant que dispositif mesurant des biomarqueurs (Classe IIa min.), le marquage CE est obligatoire. C'est le goulot d'étranglement principal du projet.</p>
                    <h4 class="font-semibold text-gray-800">Implications Stratégiques :</h4>
                    <ul class="list-disc list-inside text-gray-700 mt-2 space-y-1">
                        <li>Génère des **coûts fixes élevés** (€80k+/an) pour la R&D qualité, le SMQ et les audits.</li>
                        <li>Impose un **délai de mise sur le marché long** (validation clinique, certification).</li>
                        <li>**Justifie le prix premium** : un marché de masse B2C ne pourrait absorber ces coûts.</li>
                    </ul>
                </div>
                <div class="info-card border-l-4 border-blue-500">
                    <h3 class="text-2xl font-bold mb-3"><span class="mr-2">🔒</span> 2. Protection des Données (RGPD)</h3>
                    <p class="text-gray-700 mb-4">Le dispositif collecte des données de santé sensibles, imposant des règles strictes de consentement, sécurisation et anonymisation.</p>
                    <h4 class="font-semibold text-gray-800">Implications Stratégiques :</h4>
                    <ul class="list-disc list-inside text-gray-700 mt-2 space-y-1">
                        <li>Nécessite des investissements en **infrastructure IT sécurisée** (Hébergeur de Données de Santé).</li>
                        <li>Crée un **actif secondaire de haute valeur** : les données anonymisées (avec consentement) peuvent être licenciées pour la recherche.</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- ===== Section Déploiement ===== -->
        <section id="deploiement" class="min-h-[80vh] py-16">
            <h2 class="text-4xl font-bold text-center mb-4">Feuille de Route (Go-to-Market)</h2>
            <p class="text-lg text-gray-700 text-center max-w-3xl mx-auto mb-12">
                Notre plan de déploiement est une séquence logique dictée par les impératifs technologiques et réglementaires. Le premier client "payant" est un partenaire stratégique essentiel à la certification.
            </p>
            
            <div class="relative w-full py-10">
                <div class="absolute left-1/2 top-0 bottom-0 w-1 bg-blue-200 hidden md:block"></div>
                
                <div class="relative md:flex md:justify-center md:items-center mb-12">
                    <div class="md:w-1/2 md:pr-8 md:text-right">
                        <div class="p-6 bg-white rounded-lg shadow-lg border-l-4 md:border-l-0 md:border-r-4 border-blue-600">
                            <p class="text-sm font-semibold text-blue-600">Q3 2026 (Hypothèse)</p>
                            <h3 class="text-xl font-bold text-gray-900">1. Jalon Technologique</h3>
                            <p class="text-gray-700">Validation du POC Clinique : Obtention de résultats positifs sur la fiabilité et la précision du capteur (glucose/lactate) en conditions réelles d'entraînement.</p>
                        </div>
                    </div>
                    <div class="absolute left-1/2 -ml-3 top-1/2 -translate-y-1/2 w-6 h-6 bg-blue-600 rounded-full border-4 border-white hidden md:block"></div>
                    <div class="md:w-1/2 md:pl-8"></div>
                </div>

                <div class="relative md:flex md:justify-center md:items-center mb-12">
                    <div class="md:w-1/2 md:pr-8"></div>
                    <div class="absolute left-1/2 -ml-3 top-1/2 -translate-y-1/2 w-6 h-6 bg-blue-600 rounded-full border-4 border-white hidden md:block"></div>
                    <div class="md:w-1/2 md:pl-8">
                         <div class="p-6 bg-white rounded-lg shadow-lg border-l-4 border-red-600">
                            <p class="text-sm font-semibold text-red-600">Q2 2027 (Hypothèse)</p>
                            <h3 class="text-xl font-bold text-gray-900">2. Jalon Réglementaire</h3>
                            <p class="text-gray-700">Soumission du Dossier Technique MDR à l'Organisme Notifié après finalisation du dossier, implémentation du SMQ et dépôt officiel de la demande d'audit.</p>
                        </div>
                    </div>
                </div>
                
                <div class="relative md:flex md:justify-center md:items-center">
                    <div class="md:w-1/2 md:pr-8 md:text-right">
                        <div class="p-6 bg-white rounded-lg shadow-lg border-l-4 md:border-l-0 md:border-r-4 border-teal-600">
                            <p class="text-sm font-semibold text-teal-600">Q4 2027 (Hypothèse)</p>
                            <h3 class="text-xl font-bold text-gray-900">3. Jalon Business</h3>
                            <p class="text-gray-700">Sécurisation du 1er Client Pilote : Signature d'un partenariat stratégique (ex: équipe cycliste Pro) pour générer les premières données cliniques en situation et co-financer l'effort d'audit.</p>
                        </div>
                    </div>
                    <div class="absolute left-1/2 -ml-3 top-1/2 -translate-y-1/2 w-6 h-6 bg-blue-600 rounded-full border-4 border-white hidden md:block"></div>
                    <div class="md:w-1/2 md:pl-8"></div>
                </div>
            </div>
        </section>

        <!-- ===== Section BMC ===== -->
        <section id="bmc" class="min-h-[90vh] py-16">
            <h2 class="text-4xl font-bold text-center mb-4">Business Model Canvas Final</h2>
            <p class="text-lg text-gray-700 text-center max-w-3xl mx-auto mb-12">
                Le BMC final synthétise l'ensemble de la stratégie. Il met en évidence la cohérence entre le P&L et les cases "Flux de Revenus" (abonnement premium) et "Structure de Coûts" (dominée par les frais fixes R&D et MDR).
            </p>
            
            <div class="bmc-grid bg-gray-50 p-4 rounded-lg">
                
                <div class="bmc-card lg:col-span-1">
                    <h4 class="font-bold text-blue-700 mb-2">Partenaires Clés</h4>
                    <ul class="list-disc ml-4 text-sm space-y-1">
                        <li>Centres de Recherche (Validation)</li>
                        <li>Organisme Notifié (MDR/CE)</li>
                        <li>Équipes Sportives Pro (Pilotes)</li>
                        <li>Producteurs de capteurs</li>
                    </ul>
                </div>
                
                <div class="bmc-card lg:col-span-1">
                    <h4 class="font-bold text-blue-700 mb-2">Activités Clés</h4>
                    <ul class="list-disc ml-4 text-sm space-y-1">
                        <li>R&D et Fiabilisation Capteur</li>
                        <li>Gestion Qualité (SMQ/MDR)</li>
                        <li>Développement Plateforme Data</li>
                    </ul>
                </div>
                
                <div class="bmc-card lg:col-span-1 bg-blue-100 border-blue-300">
                    <h4 class="font-bold text-blue-800 mb-2">Proposition de Valeur</h4>
                    <p class="text-sm font-semibold">Ajustement instantané de la nutrition et de l'entraînement via suivi Glucose/Lactate en temps réel.</p>
                </div>
                
                <div class="bmc-card lg:col-span-1">
                    <h4 class="font-bold text-blue-700 mb-2">Relations Clients</h4>
                    <ul class="list-disc ml-4 text-sm space-y-1">
                        <li>Support B2B personnalisé</li>
                        <li>Co-création (feedback MDR)</li>
                    </ul>
                </div>
                
                <div class="bmc-card lg:col-span-1">
                    <h4 class="font-bold text-blue-700 mb-2">Segments Clients</h4>
                    <ul class="list-disc ml-4 text-sm space-y-1">
                        <li>Athlètes Pro/Semi-Pro</li>
                        <li>Coachs & Préparateurs</li>
                        <li>Nutritionnistes Sportifs</li>
                    </ul>
                </div>
                
                <div class="bmc-card lg:col-span-1 lg:row-start-2">
                     <h4 class="font-bold text-blue-700 mb-2">Ressources Clés</h4>
                    <ul class="list-disc ml-4 text-sm space-y-1">
                        <li>Propriété Intellectuelle (Algo)</li>
                        <li>Expertise Réglementaire MDR</li>
                        <li>Infrastructure IT Sécurisée (RGPD)</li>
                    </ul>
                </div>
                
                <div class="bmc-card lg:col-span-1 lg:row-start-2">
                    <h4 class="font-bold text-blue-700 mb-2">Canaux de Distribution</h4>
                    <ul class="list-disc ml-4 text-sm space-y-1">
                        <li>Direct B2B (Équipes Pro)</li>
                        <li>Prescription (Coachs, Nutri.)</li>
                    </ul>
                </div>
                
                <div class="bmc-card lg:col-span-3 lg:col-start-1 lg:row-start-3 bg-gray-200 border-t-4 border-red-500">
                    <h4 class="font-bold text-red-700 mb-2">Structure de Coûts (P&L)</h4>
                    <ul class="list-disc ml-4 text-sm space-y-1">
                        <li>**Fixes :** R&D Cœur, Conformité MDR/SMQ (€500k/an)</li>
                        <li>**Variables :** COGS (Capteurs, Logistique - €165/u)</li>
                        <li>Marketing B2B Ciblé</li>
                    </ul>
                </div>
                
                <div class="bmc-card lg:col-span-2 lg:col-start-4 lg:row-start-3 bg-gray-200 border-t-4 border-green-500">
                    <h4 class="font-bold text-green-700 mb-2">Flux de Revenus (P&L)</h4>
                    <ul class="list-disc ml-4 text-sm space-y-1">
                        <li>**Modèle Hybride (€870 PU Total)**</li>
                        <li>Vente Initiale (Matériel)</li>
                        <li>Abonnement Annuel (Data & Consommables)</li>
                    </ul>
                </div>

            </div>
        </section>

    </main>

    <footer class="text-center py-8 bg-gray-800 text-gray-400 text-sm">
        <p>Performance Insights | Analyse Stratégique | Octobre 2025</p>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', () => {

            const projectData = {
                pu: 870,
                cogs: 165,
                ff: 500000,
                somUnits: 2500,
                samValue: 95000000,
                somValue: 2375000
            };

            const currencyFormat = new Intl.NumberFormat('fr-FR', { style: 'currency', currency: 'EUR', minimumFractionDigits: 0 });
            const numberFormat = new Intl.NumberFormat('fr-FR');

            function wrapText(ctx, text, maxWidth) {
                const words = text.split(' ');
                let lines = [];
                let currentLine = words[0];
                for (let i = 1; i < words.length; i++) {
                    const word = words[i];
                    const width = ctx.measureText(currentLine + ' ' + word).width;
                    if (width < maxWidth) {
                        currentLine += ' ' + word;
                    } else {
                        lines.push(currentLine);
                        currentLine = word;
                    }
                }
                lines.push(currentLine);
                return lines;
            }

            // ===== Chart Marché (Doughnut) =====
            const ctxMarche = document.getElementById('marketChart').getContext('2d');
            const marketChart = new Chart(ctxMarche, {
                type: 'doughnut',
                data: {
                    labels: ['SOM (Notre Cible)', 'Reste du SAM (Non Atteint)'],
                    datasets: [{
                        data: [projectData.somValue, projectData.samValue - projectData.somValue],
                        backgroundColor: [
                            'rgba(13, 110, 253, 0.8)', // Blue
                            'rgba(206, 212, 218, 0.5)' // Gray
                        ],
                        borderColor: [
                            '#ffffff',
                            '#ffffff'
                        ],
                        borderWidth: 2
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: {
                        legend: {
                            position: 'bottom',
                        },
                        title: {
                            display: true,
                            text: 'Répartition SAM vs SOM (Valeur Annuelle)'
                        },
                        tooltip: {
                            callbacks: {
                                label: function(context) {
                                    let label = context.label || '';
                                    if (label) {
                                        label += ': ';
                                    }
                                    if (context.parsed !== null) {
                                        label += currencyFormat.format(context.parsed);
                                    }
                                    return label;
                                }
                            }
                        }
                    }
                }
            });

            // ===== Chart Finances (Bar) & Interactivité =====
            const ctxFinances = document.getElementById('pnlChart').getContext('2d');
            let pnlChart = new Chart(ctxFinances, {
                type: 'bar',
                data: {
                    labels: ['Résultat Annuel Simulé'],
                    datasets: [
                        {
                            label: 'COGS (Variables)',
                            data: [0],
                            backgroundColor: 'rgba(253, 126, 20, 0.7)',
                            stack: 'stack1'
                        },
                        {
                            label: 'Frais Fixes',
                            data: [0],
                            backgroundColor: 'rgba(220, 53, 69, 0.7)',
                            stack: 'stack1'
                        },
                        {
                            label: 'EBITDA (Profit)',
                            data: [0],
                            backgroundColor: 'rgba(25, 135, 84, 0.7)',
                            stack: 'stack1'
                        }
                    ]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    indexAxis: 'y',
                    scales: {
                        x: {
                            stacked: true,
                            title: {
                                display: true,
                                text: 'Euros (€)'
                            },
                            ticks: {
                                callback: (value) => currencyFormat.format(value)
                            }
                        },
                        y: {
                            stacked: true
                        }
                    },
                    plugins: {
                        title: {
                            display: true,
                            text: 'Décomposition du Chiffre d\'Affaires'
                        },
                        tooltip: {
                            callbacks: {
                                label: function(context) {
                                    let label = context.dataset.label || '';
                                    if (label) {
                                        label += ': ';
                                    }
                                    if (context.parsed.x !== null) {
                                        label += currencyFormat.format(context.parsed.x);
                                    }
                                    return label;
                                }
                            }
                        }
                    }
                }
            });

            const slider = document.getElementById('unitsSlider');
            const unitsValueDisplay = document.getElementById('unitsValue');
            const caValueDisplay = document.getElementById('caValue');
            const profitValueDisplay = document.getElementById('profitValue');

            function updateFinances(unites) {
                const ca = unites * projectData.pu;
                const cogsTotal = unites * projectData.cogs;
                let ebitda = ca - cogsTotal - projectData.ff;
                let profitData = 0;
                let cogsData = cogsTotal;
                let ffData = projectData.ff;

                if (ebitda < 0) {
                    profitData = 0; 
                } else {
                    profitData = ebitda;
                }
                
                pnlChart.data.datasets[0].data[0] = cogsData;
                pnlChart.data.datasets[1].data[0] = ffData;
                pnlChart.data.datasets[2].data[0] = profitData;
                
                if(ebitda < 0) {
                     pnlChart.data.datasets[2].data[0] = 0;
                }
                
                if (ca < (cogsTotal + projectData.ff)) {
                    pnlChart.data.datasets[1].data[0] = ca - cogsTotal > 0 ? ca - cogsTotal : 0;
                    if (ca < cogsTotal) {
                        pnlChart.data.datasets[0].data[0] = ca;
                    }
                }
                
                pnlChart.update();

                unitsValueDisplay.textContent = numberFormat.format(unites);
                caValueDisplay.textContent = currencyFormat.format(ca);
                profitValueDisplay.textContent = currencyFormat.format(ebitda);
                
                profitValueDisplay.classList.toggle('text-green-600', ebitda >= 0);
                profitValueDisplay.classList.toggle('text-red-600', ebitda < 0);
            }

            slider.addEventListener('input', (e) => updateFinances(parseInt(e.target.value)));
            updateFinances(projectData.somUnits);

            // ===== Logique de Navigation Active =====
            const sections = document.querySelectorAll('section');
            const navLinks = document.querySelectorAll('nav a.nav-link');

            function navHighlighter() {
                let currentSectionId = '';
                sections.forEach(section => {
                    const sectionTop = section.offsetTop;
                    if (window.scrollY >= sectionTop - 100) {
                        currentSectionId = section.getAttribute('id');
                    }
                });

                navLinks.forEach(link => {
                    link.classList.remove('nav-link-active');
                    if (link.getAttribute('href') === `#${currentSectionId}`) {
                        link.classList.add('nav-link-active');
                    }
                });
            }

            window.addEventListener('scroll', navHighlighter);
            navHighlighter();

            // Smooth scroll
            navLinks.forEach(link => {
                link.addEventListener('click', e => {
                    e.preventDefault();
                    document.querySelector(link.getAttribute('href')).scrollIntoView({
                        behavior: 'smooth'
                    });
                });
            });
        });
    </script>
</body>
</html>
