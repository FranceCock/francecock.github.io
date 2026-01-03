# francecock.github.io
<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Accueil - FC</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header class="site-header">
    <div class="container">
      <a class="logo" href="index.html">France Cock.</a>
      <nav class="nav">
        <button class="nav-toggle" aria-label="Ouvrir le menu">☰</button>
        <ul class="nav-list">
          <li><a href="index.html">Accueil</a></li>
          <li><a href="projects.html">Projets</a></li>
          <li><a href="#about">À propos</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container">
        <h1>France Cocaïne</h1>
        <p class="lead">Protos, projets, projections</p>
        <a class="btn" href="projects.html">Voir les projets</a>
      </div>
    </section>

    <section class="showcase container">
      <h2>Derniers proto-projets, avec ou sans projection</h2>
      <div class="grid">
        <!-- Exemple de projet (link vers project.html?id=...) -->
        <a class="item" href="project.html?id=proj-photo-1">
          <img src="/home/gabriel/Documents/site_fc/photos_site/000032.JPG" alt="Vignette projet photo 1">
          <div class="meta"><strong>Projet Photo 1</strong><span>Photographie</span></div>
        </a>

        <a class="item" href="project.html?id=proj-video-1">
          <img src="assets/thumb-video-1.jpg" alt="Vignette projet vidéo 1">
          <div class="meta"><strong>Projet Vidéo 1</strong><span>Vidéo</span></div>
        </a>

        <a class="item" href="project.html?id=proj-text-1">
          <img src="assets/thumb-text-1.jpg" alt="Vignette projet texte 1">
          <div class="meta"><strong>Article / Texte</strong><span>Écriture</span></div>
        </a>
      </div>
    </section>

    <section id="about" class="container content">
      <h2>apropos</h2>
      <p>Projet duel multi-support : épée digitale, sans tiret, fixité. Production nue et exclusive. L'éphèbie fonctionne sans jeu, sans dé, sans détour, sans coûture : l'éphèbe est proto-académique. Il commence à faire beau, la cuisine sérieuse perd en striures – regain purement visuel. J'envisage de re-prendre la machine pour (verbe) une sensibilité (jachère)</p>
      <p>Acte d'un assouvissement réperpétré, d'un désavouement sans involonté : Point névralgique de l'anti-point, flux guattarien (emmachiné, le nature à re-trouver) -- proto-projet sans projection.</p>
    </section>

    <section id="contact" class="container content">
      <h2>Contact</h2>
      <p>Adresse e‑mail ou formulaire (optionnel).</p>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container"><p>© <span id="year"></span> MonPortfolio</p></div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
