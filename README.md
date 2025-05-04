<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bienvenue chez Merveil</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to right, #2c3e50, #3498db);
      color: white;
      text-align: center;
      display: flex;
      flex-direction: column;
      justify-content: center;
      height: 100vh;
    }

    h1 {
      font-size: 3em;
      animation: fadeIn 1.5s ease;
    }

    p {
      font-size: 1.2em;
      max-width: 600px;
      margin: 0 auto 20px;
      animation: fadeIn 2s ease;
    }

    a {
      display: inline-block;
      padding: 12px 25px;
      background: white;
      color: #2c3e50;
      font-weight: bold;
      border-radius: 30px;
      text-decoration: none;
      transition: background 0.3s, transform 0.2s;
    }

    a:hover {
      background: #ecf0f1;
      transform: scale(1.05);
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    footer {
      margin-top: 40px;
      font-size: 0.9em;
      color: #ddd;
    }
  </style>
</head>
<body>
  <h1>Bienvenue sur mon site !</h1>
  <p>Je suis Merveil Kayembe, étudiant passionné par la technologie, la création de contenu et le développement web.</p>
  <a href="mailto:ninhomerviekayembe@gmail.com">Me contacter</a>

  <footer>&copy; 2025 Merveil Kayembe. Tous droits réservés.</footer>
</body>
</html>
