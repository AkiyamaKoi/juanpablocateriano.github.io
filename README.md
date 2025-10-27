# JuanPabloCaterianoJusto.github.io
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Juan Pablo Cateriano Justo</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap');

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: "Poppins", sans-serif;
    }

    body {
      background: #0f172a; /* azul oscuro base */
      color: #e2e8f0; /* texto claro */
      line-height: 1.6;
      overflow-x: hidden;
    }

    header {
      background: linear-gradient(90deg, #0ea5e9, #06b6d4);
      text-align: center;
      padding: 3rem 1rem;
      box-shadow: 0 0 25px rgba(6, 182, 212, 0.4);
    }

    header h1 {
      font-size: 2.8rem;
      color: #f8fafc;
      letter-spacing: 1px;
    }

    header p {
      font-size: 1.2rem;
      color: #cffafe;
      opacity: 0.9;
    }

    section {
      padding: 2.5rem 1.5rem;
      max-width: 950px;
      margin: auto;
    }

    h2 {
      border-left: 5px solid #22d3ee;
      padding-left: 10px;
      margin-bottom: 1rem;
      font-size: 1.6rem;
      color: #67e8f9;
    }

    .bio p {
      margin-bottom: 1rem;
    }

    .datos ul {
      list-style: none;
    }

    .datos li {
      margin-bottom: 0.5rem;
    }

    .intereses, .habilidades {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1rem;
    }

    .card {
      background: #1e293b;
      border-radius: 14px;
      padding: 1.2rem;
      text-align: center;
      box-shadow: 0 0 10px rgba(34, 211, 238, 0.15);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 0 20px rgba(6, 182, 212, 0.3);
    }

    footer {
      text-align: center;
      padding: 1.5rem;
      background: #1e293b;
      color: #94a3b8;
      font-size: 0.9rem;
      letter-spacing: 0.5px;
    }

    a {
      color: #22d3ee;
      text-decoration: none;
      transition: color 0.2s ease;
    }

    a:hover {
      color: #67e8f9;
    }

    /* Pequeña animación en el título */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    header h1, header p {
      animation: fadeIn 1s ease forwards;
    }

    /* Sutil efecto de resplandor al pasar por títulos */
    h2:hover {
      text-shadow: 0 0 10px #22d3ee;
      transition: 0.3s;
    }
  </style>
</head>
<body>

  <header>
    <h1>Juan Pablo Cateriano Justo</h1>
    <p>Desarrollador en formación • Curioso • Creativo</p>
  </header>

  <section class="bio">
    <h2>Sobre mí</h2>
    <p>
      Soy Juan Pablo Cateriano Justo, un joven apasionado por la tecnología, la lógica y el diseño de experiencias interactivas. 
      Me encanta aprender, crear y explorar ideas nuevas que combinen creatividad, precisión y técnicismos.
    </p>
    <p>
      Mi objetivo es seguir creciendo como desarrollador, y construir proyectos que conecten emoción, arte y código.
    </p>
  </section>

  <section class="datos">
    <h2>Datos generales</h2>
    <ul>
      <li><strong>Nombre completo:</strong> Juan Pablo Cateriano Justo</li>
      <li><strong>Nacionalidad:</strong> Peruano 🇵🇪</li>
      <li><strong>Edad:</strong> 18 años (aprox.)</li>
      <li><strong>Idiomas:</strong> Español (nativo), Inglés (intermedio)</li>
      <li><strong>Intereses:</strong> Programación, videojuegos, música, filosofía y escritura creativa</li>
    </ul>
  </section>

  <section>
    <h2>Intereses</h2>
    <div class="intereses">
      <div class="card">🎮 Desarrollo de videojuegos (Godot, pixel art)</div>
      <div class="card">🧠 Inteligencia Artificial y razonamiento lógico</div>
      <div class="card">📚 Psicología, filosofía y narrativas complejas</div>
      <div class="card">💻 Programación en Python y C++</div>
    </div>
  </section>

  <section>
    <h2>Habilidades</h2>
    <div class="habilidades">
      <div class="card">✅ Programación en Python</div>
      <div class="card">✅ Conocimientos en C y C++</div>
      <div class="card">✅ Diseño de juegos 2D con Godot</div>
      <div class="card">✅ Resolución de problemas lógicos</div>
      <div class="card">✅ Escritura narrativa y creatividad</div>
    </div>
  </section>

  <section>
    <h2>Contacto</h2>
    <p>Puedes contactarme para colaboraciones o proyectos personales:</p>
    <ul>
      <li><strong>Email:</strong> juanpablo.cateriano@example.com</li>
      <li><strong>GitHub:</strong> <a href="#">github.com/JuanPabloCateriano</a></li>
      <li><strong>LinkedIn:</strong> <a href="#">https://www.linkedin.com/me?trk=p_mwlite_feed-secondary_nav</li>
