# Reciclaje 
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Campaña Ecológica Cecyteh Tizayuca</title>
  <link rel="stylesheet" href="style.css" />
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Anton&display=swap" rel="stylesheet">
</head>
<body>
  <header>
    <img src="logo cecyteh.jpeg" alt="Logo Cecyteh" class="logo" />
    <h1>Campaña Ecológica Cecyteh Tizayuca</h1>
    <button id="tema-btn">🌙</button>
  </header>

  <nav>
    <ul>
      <li><a href="#intro">Inicio</a></li>
      <li><a href="#materiales">Materiales reciclables</a></li>
      <li><a href="#formulario">Participa</a></li>
    </ul>
  </nav>

  <main>
    <section id="intro">
      <h2>¿Qué es la campaña?</h2>
      <p>Una iniciativa escolar para fomentar el reciclaje y la conciencia ecológica en los alumnos y docentes del Cecyteh Tizayuca.</p>
    </section>

    <section id="materiales">
      <h2>¿Qué reciclamos?</h2>
      <div class="grid">
        <article>
          <img src="como-es-proceso-reciclaje-carton.jpg" alt="Papel reciclado" />
          <h3>Papel y cartón</h3>
        </article>
        <article>
          <img src="plastic.jpg" alt="Botellas plásticas" />
          <h3>Plástico</h3>
        </article>
        <article>
          <img src="reciclar-vidrio-1.jpg" alt="Vidrio reciclado" />
          <h3>Vidrio</h3>
        </article>
        <article>
          <img src="reciclaje_electronico.jpg" alt="Desechos electrónicos" />
          <h3>Electrónicos</h3>
        </article>
      </div>
    </section>

    <section id="faq">
      <h2>Preguntas frecuentes</h2>
      <div class="accordion">
        <button class="acordeon-btn">¿Quién puede participar?</button>
        <div class="panel"><p>Todos los estudiantes, maestros y personal administrativo del plantel.</p></div>

        <button class="acordeon-btn">¿Dónde se depositan los residuos?</button>
        <div class="panel"><p>En los contenedores verdes ubicados en la entrada principal y áreas comunes.</p></div>

        <button class="acordeon-btn">¿Qué se hace con lo recolectado?</button>
        <div class="panel"><p>Se clasifica y se entrega a centros de reciclaje certificados.</p></div>
      </div>
    </section>

    <section id="formulario">
      <h2>Únete a la campaña</h2>
      <form id="eco-form">
        <label>Nombre:
          <input type="text" id="nombre" required />
        </label>
        <label>Email:
          <input type="email" id="email" required />
        </label>
        <label>Comentario:
          <textarea id="comentario" required></textarea>
        </label>
        <button type="submit">Enviar</button>
        <p id="mensaje"></p>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Cecyteh Tizayuca - Campaña Ecológica</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
