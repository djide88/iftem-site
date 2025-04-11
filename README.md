<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>IFTEM - Institut de Formation en Techniques et Métiers</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Roboto', sans-serif; }
  </style>
</head>
<body class="bg-gray-50 text-gray-800">
  <!-- Navbar -->
  <header class="bg-white shadow-md sticky top-0 z-50">
    <div class="max-w-7xl mx-auto flex justify-between items-center p-4">
      <div class="flex items-center space-x-2">
        <svg class="w-8 h-8 text-blue-600" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
          <path d="M12 2L2 7h20L12 2z"/><path d="M2 7v13h20V7"/><path d="M12 22V12"/>
        </svg>
        <h1 class="text-xl font-bold text-blue-700">IFTEM</h1>
      </div>
      <nav class="space-x-4 hidden md:block">
        <a href="#accueil" class="hover:text-blue-600">Accueil</a>
        <a href="#formations" class="hover:text-blue-600">Formations</a>
        <a href="#infrastructures" class="hover:text-blue-600">Infrastructures</a>
        <a href="#inscriptions" class="hover:text-blue-600">Inscriptions</a>
        <a href="#contact" class="hover:text-blue-600">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Accueil -->
  <section id="accueil" class="bg-blue-100 py-20 text-center">
    <h2 class="text-4xl font-bold text-blue-700 mb-4">L'énergie du savoir pour transformer le Tchad</h2>
    <p class="max-w-xl mx-auto">Bienvenue à l'IFTEM, un centre de formation professionnelle aux métiers du futur : Maintenance, Froid & Climatisation, Électrotechnique.</p>
  </section>

  <!-- Formations -->
  <section id="formations" class="py-16 bg-white">
    <div class="max-w-6xl mx-auto text-center">
      <h3 class="text-3xl font-bold text-blue-700 mb-8">Nos Formations</h3>
      <div class="grid md:grid-cols-3 gap-6">
        <div class="bg-blue-50 p-6 rounded-xl shadow">
          <h4 class="text-xl font-semibold mb-2">Maintenance Industrielle</h4>
          <p>Bac Pro & BTS orientés réparation, entretien et installation industrielle.</p>
        </div>
        <div class="bg-blue-50 p-6 rounded-xl shadow">
          <h4 class="text-xl font-semibold mb-2">Froid & Climatisation</h4>
          <p>Maîtriser les systèmes frigorifiques et les technologies du froid.</p>
        </div>
        <div class="bg-blue-50 p-6 rounded-xl shadow">
          <h4 class="text-xl font-semibold mb-2">Électrotechnique</h4>
          <p>Formation aux installations électriques, automatismes et systèmes énergétiques.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Infrastructures -->
  <section id="infrastructures" class="py-16 bg-gray-100">
    <div class="max-w-6xl mx-auto text-center">
      <h3 class="text-3xl font-bold text-blue-700 mb-8">Nos Infrastructures</h3>
      <p class="mb-4">Des ateliers modernes équipés pour la pratique professionnelle, avec salles multimédia, laboratoires techniques et espaces de co-travail.</p>
      <img src="https://source.unsplash.com/featured/?workshop,technology" alt="Infrastructures" class="mx-auto rounded-xl shadow-lg w-full max-w-4xl">
    </div>
  </section>

  <!-- Inscriptions -->
  <section id="inscriptions" class="py-16 bg-white">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-bold text-blue-700 mb-4">Inscriptions</h3>
      <p class="mb-2">Les inscriptions sont ouvertes de mars à juillet.</p>
      <p class="mb-2">Conditions : niveau 3e minimum pour le Bac Pro, Bac pour le BTS.</p>
      <p>Frais abordables avec possibilité de bourses.</p>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-16 bg-blue-50">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-bold text-blue-700 mb-6">Contact</h3>
      <p class="mb-2">📍 N'Djamena, Tchad</p>
      <p class="mb-2">📧 contact@iftem.td</p>
      <p class="mb-6">📞 +235 66 00 00 00</p>
      <form class="grid grid-cols-1 gap-4 max-w-md mx-auto">
        <input type="text" placeholder="Nom" class="p-2 rounded border">
        <input type="email" placeholder="Email" class="p-2 rounded border">
        <textarea placeholder="Message" class="p-2 rounded border"></textarea>
        <button class="bg-blue-600 text-white py-2 px-4 rounded hover:bg-blue-700">Envoyer</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-white text-center py-6 shadow-inner">
    <p class="text-sm">&copy; 2025 IFTEM - Institut de Formation en Techniques et Métiers. Tous droits réservés.</p>
  </footer>
</body>
</html>
