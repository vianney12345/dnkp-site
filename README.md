<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>DNKP - Banque & Services Financiers</title>
  <style>
    /* Reset basique */
    * {
      margin: 0; padding: 0; box-sizing: border-box;
      font-family: Arial, sans-serif;
    }
    body {
      background: #f5f7fa;
      color: #0a1f44; /* bleu foncé */
      line-height: 1.6;
    }
    header {
      background: #002855; /* bleu marine */
      color: #d4af37; /* doré */
      padding: 20px 40px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      position: sticky;
      top: 0;
      z-index: 100;
    }
    header h1 {
      font-size: 1.8rem;
    }
    nav a {
      color: #d4af37;
      text-decoration: none;
      margin-left: 25px;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #f9d976;
    }
    main {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }
    section {
      margin-bottom: 60px;
    }
    h2 {
      color: #002855;
      margin-bottom: 20px;
      border-bottom: 3px solid #d4af37;
      display: inline-block;
      padding-bottom: 5px;
    }
    p {
      font-size: 1.1rem;
      margin-bottom: 15px;
    }
    .services {
      display: flex;
      gap: 30px;
      flex-wrap: wrap;
    }
    .service-item {
      background: white;
      flex: 1 1 250px;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
      transition: box-shadow 0.3s;
    }
    .service-item:hover {
      box-shadow: 0 0 15px #d4af37;
    }
    form {
      background: white;
      padding: 25px;
      border-radius: 8px;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
      max-width: 500px;
    }
    form label {
      display: block;
      margin-bottom: 8px;
      font-weight: bold;
      color: #002855;
    }
    form input, form textarea {
      width: 100%;
      padding: 8px 12px;
      margin-bottom: 20px;
      border: 2px solid #d4af37;
      border-radius: 4px;
      font-size: 1rem;
      font-family: Arial, sans-serif;
      resize: vertical;
    }
    form button {
      background: #d4af37;
      color: #002855;
      border: none;
      padding: 12px 25px;
      font-size: 1.1rem;
      font-weight: bold;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }
    form button:hover {
      background: #f9d976;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #002855;
      color: #d4af37;
      font-size: 0.9rem;
    }
    @media(max-width: 600px) {
      .services {
        flex-direction: column;
      }
      header {
        flex-direction: column;
        align-items: flex-start;
      }
      nav {
        margin-top: 15px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>DNKP Banque</h1>
    <nav>
      <a href="#about">À propos</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  <main>
    <section id="about">
      <h2>À propos de DNKP</h2>
      <p>DNKP est votre partenaire financier de confiance, offrant des solutions bancaires personnalisées et innovantes pour particuliers et entreprises.</p>
      <p>Notre mission : vous accompagner dans vos projets avec transparence, sécurité et expertise.</p>
    </section>

    <section id="services">
      <h2>Nos Services</h2>
      <div class="services">
        <div class="service-item">
          <h3>Comptes bancaires</h3>
          <p>Gestion facile de vos comptes courants, épargne et placements adaptés à vos besoins.</p>
        </div>
        <div class="service-item">
          <h3>Crédits & Prêts</h3>
          <p>Solutions de financement sur mesure, avec des taux compétitifs et un accompagnement personnalisé.</p>
        </div>
        <div class="service-item">
          <h3>Conseil financier</h3>
          <p>Des experts à votre écoute pour optimiser votre gestion patrimoniale et fiscale.</p>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contactez-nous</h2>
      <form action="mailto:contact@dnkp.fr" method="POST" enctype="text/plain">
        <label for="name">Nom complet</label>
        <input type="text" id="name" name="name" required />

        <label for="email">Email</label>
        <input type="email" id="email" name="email" required />

        <label for="message">Message</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit">Envoyer</button>
      </form>
      <p>Ou par email directement : <a href="mailto:contact@dnkp.fr">contact@dnkp.fr</a></p>
    </section>
  </main>
  <footer>
    &copy; 2025 DNKP Banque - Tous droits réservés
  </footer>
</body>
</html>
