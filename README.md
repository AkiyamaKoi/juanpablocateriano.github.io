<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portafolio personal de Juan Pablo Cateriano">
  <title>Juan Pablo Cateriano</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: #0f172a;
      color: #f8fafc;
      line-height: 1.6;
      scroll-behavior: smooth;
    }

    header {
      background-color: #1e293b;
      padding: 1.5rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header h1 {
      font-size: 1.5rem;
      color: #38bdf8;
    }

    nav a {
      color: #f1f5f9;
      margin-left: 1.5rem;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #38bdf8;
    }

    section {
      padding: 4rem 2rem;
      max-width: 1000px;
      margin: auto;
    }

    .hero {
      text-align: center;
      padding-top: 5rem;
    }

    .hero img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #38bdf8;
      margin-bottom: 1rem;
      opacity: 0;
      animation: fadeIn 1.5s ease-in-out forwards;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.9); }
      to { opacity: 1; transform: scale(1); }
    }

    .hero h2 {
      font-size: 2.2rem;
      margin-bottom: 0.5rem;
      animation: fadeIn 2s ease-in-out forwards;
    }

    .hero p {
      color: #cbd5e1;
      font-size: 1.1rem;
    }

    .btn {
      display: inline-block;
      margin-top: 1.5rem;
      padding: 0.75rem 1.5rem;
      background-color: #38bdf8;
      color: #0f172a;
      border-radius: 8px;
      font-weight: bold;
      text-decoration: none;
      transition: background 0.3s ease;
    }

    .btn:hover {
      background-color: #0ea5e9;
    }

    .gustos-lista {
      margin-top: 1.5rem;
      list-style: none;
      padding: 0;
    }

    .gustos-lista li {
      background-color: #1e293b;
      margin-bottom: 0.8rem;
      padding: 1rem;
      border-radius: 10px;
      transition: transform 0.3s ease;
    }

    .gustos-lista li:hover {
      transform: translateX(8px);
    }

    .contactos-lista {
      list-style: none;
      margin-top: 1rem;
      padding: 0;
    }

    .contactos-lista li {
      background-color: #1e293b;
      margin-bottom: 0.8rem;
      padding: 1rem;
      border-radius: 10px;
      transition: transform 0.3s ease;
    }

    .contactos-lista li:hover {
      transform: translateX(8px);
    }

    .contactos-lista a {
      color: #38bdf8;
      text-decoration: none;
      font-weight: bold;
    }

    .contactos-lista a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      padding: 2rem;
      background-color: #1e293b;
      color: #94a3b8;
    }

    footer a {
      color: #38bdf8;
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }

    @media (max-width: 768px) {
      .hero h2 {
        font-size: 1.8rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Juan Pablo Cateriano</h1>
    <nav>
      <a href="#sobre-mi">Sobre mí</a>
      <a href="#gustos">Mis gustos</a>
      <a href="#contacto">Contacto</a>
      <a href="#red">Red de contactos</a>
    </nav>
  </header>

  <section class="hero">
    <img src="perfil.jpg" alt="Foto de Juan Pablo Cateriano">
    <h2>¡Hola! Soy Juan Pablo Cateriano 👋</h2>
    <p>Apasionado por la programación, el arte, la creatividad y el aprendizaje constante.</p>
  </section>

  <section id="sobre-mi">
    <h2>Sobre mí</h2>
    <p>
      Soy una persona curiosa y reflexiva, me gusta entender cómo funcionan las cosas
      y darles un toque propio. Disfruto combinar lo técnico con lo emocional, ya sea
      programando, escribiendo o creando ideas nuevas.
    </p>
  </section>

  <section id="gustos">
    <h2>Mis gustos</h2>
    <ul class="gustos-lista">
      <li>🎮 Crear juegos 2D con estética tipo *pixel art* (inspirado en Hollow Knight o Katana Zero).</li>
      <li>📚 Analizar historias con profundidad psicológica y simbolismo, como *Omori* o *Dentro del bosque*.</li>
      <li>💻 Aprender sobre programación, inteligencia artificial y diseño de sistemas.</li>
      <li>🎧 Escuchar música mientras trabajo, especialmente bandas sonoras y lo-fi.</li>
      <li>✍️ Escribir relatos o artículos con un toque poético y filosófico.</li>
    </ul>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p>¿Quieres charlar o colaborar en algo creativo?  
       Puedes escribirme o seguirme en mis redes:</p>
    <p>
      <a href="https://github.com/juanpablocateriano" target="_blank">GitHub</a> |
      <a href="https://linkedin.com/in/juan-pablo-cateriano-987b64385" target="_blank">LinkedIn</a> |
      <a href="mailto:juanpablocateriano@gmail.com">Correo</a>
    </p>
  </section>

  <section id="red">
    <h2>Red de contactos</h2>
    <p>Personas con las que aprendo, comparto ideas y colaboro:</p>
    <ul class="contactos-lista">
      <li><a href="https://linkedin.com/in/ecuadrosv" target="_blank">👨‍🏫 Prof. E. Cuadros</a></li>
      <!-- Agrega aquí a tus compañeros cuando tengas sus enlaces -->
      <!-- Ejemplo:
      <li><a href="https://linkedin.com/in/nombre-de-compañero" target="_blank">💻 Nombre del compañero</a></li>
      -->
    </ul>
  </section>

  <footer>
    <p>© 2025 Juan Pablo Cateriano — “El código también puede ser arte.”</p>
  </footer>
</body>
</html>
