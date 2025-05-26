<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gédéon Tech - Accueil</title>
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
      line-height: 1.6;
    }
    header {
      background-color: #1e90ff;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #ffffff;
      padding: 10px;
      text-align: center;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #1e90ff;
      font-weight: bold;
    }
    .container {
      max-width: 1200px;
      margin: auto;
      padding: 20px;
    }
    section {
      margin-bottom: 50px;
    }
    iframe {
      width: 100%;
      height: 400px;
      border: 0;
    }
    .contact, .services, .gallery, .progedeon, .formulaire {
      background-color: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .whatsapp {
      display: inline-block;
      background-color: #25D366;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 10px;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background-color: #1e90ff;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      margin-top: 10px;
      cursor: pointer;
    }
    img {
      width: 100%;
      max-width: 300px;
      margin: 10px;
      border-radius: 10px;
    }
    @media (max-width: 768px) {
      nav a {
        display: block;
        margin: 10px 0;
      }
      img {
        width: 100%;
        max-width: 100%;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Gédéon Tech</h1>
    <p>Optimisation et dépannage - Moundou</p>
  </header>

  <nav>
    <a href="#accueil">Accueil</a>
    <a href="#services">Services</a>
    <a href="#localisation">Localisation</a>
    <a href="#contact">Contact</a>
    <a href="#formulaire">Formulaire</a>
    <a href="#galerie">Galerie</a>
    <a href="#progedeon">Progedeon</a>
  </nav>

  <div class="container">
    <section id="accueil">
      <h2>Bienvenue chez Gédéon Tech</h2>
      <p>Nous sommes spécialisés dans la maintenance informatique, l’électricité, l’installation d’antennes, ainsi que le développement de sites web à Moundou. Notre objectif est de vous proposer des services fiables, rapides et professionnels.</p>
    </section>

    <section id="services" class="services">
      <h2>Nos services</h2>
      <ul>
        <li>Maintenance informatique et réseaux</li>
        <li>Installation et réparation de systèmes électriques</li>
        <li>Installation d’antennes satellites et TNT</li>
        <li>Création de sites web professionnels</li>
        <li>Conseils techniques et optimisation PC</li>
      </ul>
    </section>

    <section id="localisation">
      <h2>Notre localisation</h2>
      <p><strong>Adresse :</strong> Quartier Fouda, près de la station AXX Fouda, Moundou</p>
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d3979.0!2d11.5200!3d3.8600!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2sG%C3%A9d%C3%A9on+Tech!5e0!3m2!1sfr!2scm!4v1620000000000"
        allowfullscreen=""
        loading="lazy">
      </iframe>
    </section>

    <section id="contact" class="contact">
      <h2>Contact</h2>
      <p><strong>Téléphone / WhatsApp :</strong> <a href="https://wa.me/23563026990" class="whatsapp">+235 6302 6990</a></p>
      <p><strong>Email :</strong> contact@gedeontech.com (exemple)</p>
    </section>

    <section id="formulaire" class="formulaire">
      <h2>Formulaire de contact</h2>
      <form action="#" method="post">
        <label for="nom">Nom :</label>
        <input type="text" id="nom" name="nom" required>

        <label for="email">Email :</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Message :</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit">Envoyer</button>
      </form>
    </section>

    <section id="galerie" class="gallery">
      <h2>Galerie</h2>
      <p>Voici quelques exemples de nos réalisations :</p>
      <div style="display: flex; flex-wrap: wrap; justify-content: center;">
        <img src="https://via.placeholder.com/300x200" alt="Photo 1">
        <img src="https://via.placeholder.com/300x200" alt="Photo 2">
        <img src="https://via.placeholder.com/300x200" alt="Photo 3">
      </div>
    </section>

    <section id="progedeon" class="progedeon">
      <h2>Projet Progedeon</h2>
      <p>Progedeon est un espace numérique pour le partage de documents, d’informations et de recherches. Vous pouvez : </p>
      <ul>
        <li>Consulter des articles et ressources utiles</li>
        <li>Télécharger des fichiers</li>
        <li>Rechercher du contenu via Google</li>
      </ul>
      <form action="https://www.google.com/search" method="get" target="_blank">
        <input type="text" name="q" placeholder="Rechercher sur Google...">
        <button type="submit">Rechercher</button>
      </form>
    </section>
  </div>
</body>
</html>
