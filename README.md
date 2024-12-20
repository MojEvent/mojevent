<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moj Event - Veranstaltungen</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
        }
        header {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
        header h1 {
            font-size: 36px;
        }
        header h1 span {
            color: red;
        }
        nav {
            background-color: #111;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        nav a:hover {
            color: red;
        }
        section {
            padding: 50px 20px;
            text-align: center;
        }
        .hero {
            background: url('/mnt/data/mein%20event-2.jpg') no-repeat center center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
        }
        .hero h2 {
            font-size: 48px;
            background-color: rgba(0, 0, 0, 0.7);
            padding: 20px;
        }
        .content {
            max-width: 800px;
            margin: 0 auto;
        }
        footer {
            background-color: #111;
            text-align: center;
            padding: 20px 0;
            margin-top: 20px;
        }
        footer p {
            margin: 0;
            color: #fff;
        }
        footer p span {
            color: red;
        }
    </style>
</head>
<body>
    <header>
        <h1>Moj <span>&hearts;</span> Event</h1>
    </header>
    <nav>
        <a href="#services">Unsere Leistungen</a>
        <a href="#about">Über Uns</a>
        <a href="#contact">Kontakt</a>
    </nav>
    <div class="hero">
        <h2>Unvergessliche Veranstaltungen mit Stil</h2>
    </div>
    <section id="services">
        <div class="content">
            <h2>Unsere Leistungen</h2>
            <p>Wir bieten professionelle Planung und Umsetzung von Veranstaltungen. Egal ob Hochzeit, Firmenevent oder Geburtstag - wir sorgen dafür, dass Ihr Event unvergesslich wird.</p>
        </div>
    </section>
    <section id="about">
        <div class="content">
            <h2>Über Uns</h2>
            <p>Bei Moj Event stehen Ihre Wünsche im Mittelpunkt. Mit Liebe zum Detail und einem professionellen Team machen wir Ihre Träume wahr.</p>
        </div>
    </section>
    <section id="contact">
        <div class="content">
            <h2>Kontakt</h2>
            <p>Haben Sie Fragen oder möchten Sie mehr erfahren? Kontaktieren Sie uns unter <a href="mailto:info@mojevent.de" style="color: red;">info@mojevent.de</a>.</p>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Moj Event. Alle Rechte vorbehalten. <span>Veranstaltungen by Zlatko</span></p>
    </footer>
</body>
</html>
