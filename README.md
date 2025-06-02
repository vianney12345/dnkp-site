# dnkp-site
Mon site web 
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
      resize: ve
