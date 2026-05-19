<!DOCTYPE html>
<html lang="bs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ai Bussines | Agencija za AI Automatizaciju i Web Razvoj</title>
    <style>
        /* Osnovne postavke, resetovanje i glatko skrolanje */
        html {
            scroll-behavior: smooth;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #0f172a;
            color: #f8fafc;
            line-height: 1.6;
        }

        /* Navigacija */
        header {
            background-color: #1e293b;
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 2px solid #38bdf8;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            color: #38bdf8;
            text-decoration: none;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 2rem;
            align-items: center;
        }

        nav a {
            color: #e2e8f0;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #38bdf8;
        }

        .btn-nav {
            background-color: #38bdf8;
            color: #0f172a !important;
            padding: 0.5rem 1.2rem;
            border-radius: 5px;
            font-weight: bold;
            transition: background-color 0.3s, transform 0.2s;
        }

        .btn-nav:hover {
            background-color: #0284c7;
            transform: translateY(-2px);
        }

        /* Hero Sekcija */
        .hero {
            padding: 8rem 5%;
            text-align: center;
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 1rem;
            color: #ffffff;
        }

        .hero h1 span {
            color: #38bdf8;
        }

        .hero p {
            font-size: 1.2rem;
            color: #94a3b8;
            max-width: 600px;
            margin: 0 auto 2rem auto;
        }

        .btn {
            display: inline-block;
            padding: 0.8rem 2rem;
            background-color: #38bdf8;
            color: #0f172a;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            transition: background-color 0.3s, transform 0.2s;
            border: none;
            cursor: pointer;
            font-size: 1rem;
        }

        .btn:hover {
            background-color: #0284c7;
            transform: translateY(-2px);
        }

        /* Usluge Sekcija */
        .services {
            padding: 5rem 5%;
            background-color: #0f172a;
        }

        .section-title {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 3rem;
            color: #f8fafc;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .service-card {
            background-color: #1e293b;
            padding: 2rem;
            border-radius: 8px;
            text-align: center;
            border-top: 4px solid #38bdf8;
            transition: transform 0.3s;
        }

        .service-card:hover {
            transform: translateY(-5px);
        }

        .service-card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: #38bdf8;
        }

        .service-card p {
            color: #94a3b8;
        }

        /* Nova Forma za Kontakt */
        .contact {
            padding: 5rem 5%;
            background-color: #1e293b;
        }

        .contact-container {
            max-width: 600px;
            margin: 0 auto;
            background-color: #0f172a;
            padding: 3rem;
            border-radius: 8px;
            border: 1px solid #38bdf8;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .contact-form {
            display: flex;
            flex-direction: column;
            gap: 1.5rem;
        }

        .form-group {
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
        }

        .form-group label {
            color: #94a3b8;
            font-weight: 500;
        }

        .form-group input,
        .form-group textarea {
            padding: 0.8rem;
            border-radius: 5px;
            border: 1px solid #334155;
            background-color: #1e293b;
            color: #f8fafc;
            font-family: inherit;
        }

        .form-group input:focus,
        .form-group textarea:focus {
            outline: none;
            border-color: #38bdf8;
        }

        /* Footer */
        footer {
            background-color: #020617;
            text-align: center;
            padding: 2rem 5%;
            color: #64748b;
            border-top: 1px solid #1e293b;
        }

        /* Responzivnost */
        @media (max-width: 768px) {
            nav ul {
                gap: 1rem;
            }
            nav ul li:not(:last-child) {
                display: none;
            }
            .hero h1 {
                font-size: 2.5rem;
            }
        }
    </style>
</head>
<body>

    <!-- Navigacija -->
    <header>
        <a href="#" class="logo">Ai Bussines</a>
        <nav>
            <ul>
                <li><a href="#pocetna">Početna</a></li>
                <li><a href="#usluge">Naše Usluge</a></li>
                <li><a href="#kontakt" class="btn-nav">Kontakt</a></li>
            </ul>
        </nav>
    </header>

    <!-- Glavna Hero Sekcija -->
    <main class="hero" id="pocetna">
        <h1>Budućnost poslovanja je <span>Automatizovana</span></h1>
        <p>Prepustite teški rad umjetnoj inteligenciji. Kreiramo moderne web stranice i automatizujemo vaše poslovne procese brže, pametnije i efikasnije.</p>
        <a href="#usluge" class="btn">Pogledaj Usluge</a>
    </main>

    <!-- Sekcija sa Uslugama -->
    <section class="services" id="usluge">
        <h2 class="section-title">Šta radimo?</h2>
        <div class="services-grid">
            
            <div class="service-card">
                <h3>AI Web Dizajn</h3>
                <p>Koristimo najnovije AI alate za dizajniranje i programiranje brzih, modernih i responzivnih web stranica od nule.</p>
            </div>

            <div class="service-card">
                <h3>Automatizacija Taskova</h3>
                <p>Implementiramo rješenja koja svakodnevne, ponavljajuće zadatke na računaru prebacuju na AI agente i botove.</p>
            </div>

            <div class="service-card">
                <h3>Virtuelna Podrška</h3>
                <p>Kreiramo pametne sisteme za upravljanje digitalnom imovinom i korisničkom podrškom bez potrebe za ljudskom intervencijom.</p>
            </div>

        </div>
    </section>

    <!-- Kontakt Forma -->
    <section class="contact" id="kontakt">
        <h2 class="section-title">Započnimo Projekat</h2>
        <div class="contact-container">
            <!-- Povezivanje sa Formspree servisom -->
            <form action="https://formspree.io/f/xojbvzwr" method="POST" class="contact-form">
                
                <div class="form-group">
                    <label for="ime">Vaše Ime:</label>
                    <input type="text" id="ime" name="Ime" required placeholder="Unesite vaše ime">
                </div>

                <div class="form-group">
                    <label for="email">Vaš Email:</label>
                    <input type="email" id="email" name="Email" required placeholder="Unesite vaš email">
                </div>

                <div class="form-group">
                    <label for="poruka">Vaša Poruka:</label>
                    <textarea id="poruka" name="Poruka" rows="5" required placeholder="Kako vam možemo pomoći?"></textarea>
                </div>

                <button type="submit" class="btn">Pošalji Upit</button>
            </form>
        </div>
    </section>

    <!-- Podnožje -->
    <footer>
        <p>&copy; 2026 Ai Bussines. Sva prava zadržana.</p>
        <p>Vaš partner za digitalnu revoluciju.</p>
    </footer>

</body>
</html>
