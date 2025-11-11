
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jade Aubrey | Chef de Projet</title>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
</head>
<body>
<style>
  * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Helvetica Neue', Arial, sans-serif;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 25px 60px;
  background: #fff;
}

.logo {
  display: flex;
  align-items: center;
  gap: 10px;
}

.logo .square {
  width: 15px;
  height: 15px;
  background: #0050ff;
}

.logo h1 {
  font-size: 22px;
  font-weight: 700;
}

.logo p {
  font-size: 15px;
  color: #444;
}

nav a {
  text-decoration: none;
  color: #000;
  margin-left: 25px;
  font-size: 15px;
  transition: color 0.3s;
}

nav a:first-child {
  color: #0050ff;
}

nav a:hover {
  color: #0050ff;
}


main {
  display: flex;
  min-height: calc(100vh - 80px);
}


.sidebar {
  width: 35%;
  background: #f2e8df;
  text-align: center;
  padding: 50px 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.profile-img {
  width: 180px;
  height: 180px;
  object-fit: cover;
  border-radius: 50%;
  margin-bottom: 30px;
}

.sidebar h2 {
  font-size: 28px;
  font-weight: 700;
  line-height: 1.2;
}

.sidebar span {
  display: block;
  font-weight: 700;
}

.title {
  margin-top: 15px;
  font-size: 15px;
  letter-spacing: 2px;
  color: #333;
}

.socials {
  margin-top: 30px;
}

.socials a {
  color: #000;
  margin: 0 10px;
  font-size: 20px;
  transition: color 0.3s;
}

.socials a:hover {
  color: #0050ff;
}

.content {
  width: 65%;
  padding: 100px 80px;
}

.content h1 {
  font-size: 100px;
  font-weight: 800;
  line-height: 1;
}

.content h3 {
  font-size: 24px;
  font-weight: 500;
  margin: 20px 0 40px;
}

.buttons {
  display: flex;
  gap: 20px;
  margin-bottom: 40px;
}

.btn {
  padding: 12px 40px;
  border-radius: 25px;
  text-decoration: none;
  font-weight: 600;
  transition: all 0.3s ease;
}

.primary {
  background: #0050ff;
  color: #fff;
}

.primary:hover {
  background: #003fcc;
}

.secondary {
  border: 1px solid #000;
  color: #000;
}

.secondary:hover {
  background: #000;
  color: #fff;
}

.text {
  max-width: 600px;
  line-height: 1.6;
  font-size: 16px;
  color: #333;
  margin-bottom: 20px;
}

</style>

  <header>
    <div class="logo">
      <span class="square"></span>
      <h1>Jade Aubrey</h1>
      <p>/ Développeur Web</p>
    </div>
    <nav>
      <a href="#">À PROPOS DE MOI</a>
      <a href="Page d'acceuil.html">CV</a>
      <a href="#">PROJETS</a>
      <a href="#">CONTACT</a>
    </nav>
  </header>

  <main>
    <section class="sidebar">
      <img src="https://i.imgur.com/Vs6wj7U.png" alt="Photo de profil" class="profile-img">
      <h2>Jade<br><span>Aubrey</span></h2>
      <p class="title">DEVELOPPEUR WEB</p>
      <div class="socials">
        <a href="#"><i class="fab fa-facebook-f"></i></a>
        <a href="#"><i class="fab fa-twitter"></i></a>
        <a href="#"><i class="fab fa-linkedin-in"></i></a>
        <a href="#"><i class="fab fa-instagram"></i></a>
      </div>
    </section>

   <section class="content">
      <h1>Hello</h1>
      <h3>Je m'appel Arthur Lee, je suis un étudiant en BTS SIO</h3>

  <p class="text">
        Paragraphe. Cliquez ici pour ajouter votre propre texte. Cliquez sur « Modifier Texte » 
        ou double-cliquez ici pour ajouter votre contenu et personnaliser les polices.
      </p>
      <p class="text">
        Relatez ici votre parcours et présentez votre activité à vos visiteurs.
      </p>
    </section>
  </main>

</body>
</html>
