<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Glory in Worship</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Glory in Worship</h1>
        <nav>
            <ul>
                <li><a href="index.html">Accueil</a></li>
                <li><a href="about.html">À propos</a></li>
                <li><a href="activities.html">Activités</a></li>
                <li><a href="membership.html">Membres</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="introduction">
            <h2>Bienvenue à Glory in Worship</h2>
            <p>Servir l’Éternel par les chants et cantiques en adorateur qui exerce ce devoir saint sacré et divin en esprit et en vérité.</p>
        </section>
        <section id="objectives">
            <h2>Objectifs</h2>
            <ul>
                <li>Louer et adorer Dieu</li>
                <li>Édification de l’Église et gagner les âmes</li>
                <li>Encadrement spirituel et moral des membres</li>
                <li>Évangélisation sous toutes ses formes</li>
            </ul>
        </section>
    </main>
    <footer>
        <p>© 2024 Glory in Worship. Tous droits réservés.</p>
    </footer>
</body>
</html>
b. Feuille de style (style.css) :
css
Copy code
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background: #f4f4f4;
}

header {
    background: #333;
    color: #fff;
    padding-top: 30px;
    min-height: 70px;
    border-bottom: #0779e4 3px solid;
}

header h1 {
    margin: 0;
    text-align: center;
}

nav ul {
    padding: 0;
    list-style: none;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
}

main {
    padding: 20px;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
