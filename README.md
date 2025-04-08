<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FISIOTERAPIA | Rehalife</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #e0f7fa;
      padding: 20px;
      text-align: center;
    }
    header img {
      max-width: 250px;
      height: auto;
    }
    nav {
      background-color: #00bcd4;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    h1, h2 {
      color: #00acc1;
    }
    form {
      display: flex;
      flex-direction: column;
    }
    input, textarea, button {
      margin: 10px 0;
      padding: 10px;
      font-size: 16px;
    }
    button {
      background-color: #00acc1;
      color: white;
      border: none;
      cursor: pointer;
    }
    footer {
      background-color: #ccc;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo-rehalife.png" alt="Rehalife Logo">
  </header>  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#servicios">Servicios</a>
    <a href="#contacto">Contacto</a>
  </nav>  <section id="inicio">
    <h1>Bienvenidos a Rehalife</h1>
    <p>En Rehalife Centro de Fisioterapia, te acompañamos en tu camino hacia una vida saludable y sin dolor. Ofrecemos atención personalizada con profesionales comprometidos con tu bienestar.</p>
  </section>  <section id="servicios">
    <h2>Servicios</h2>
    <ul>
      <li>Rehabilitación física</li>
      <li>Terapia manual</li>
      <li>Electroterapia</li>
      <li>Ejercicios terapéuticos</li>
      <li>Consultas personalizadas</li>
    </ul>
  </section>  <section id="contacto">
    <h2>Agenda tu cita</h2>
    <form action="mailto:riverosarita32@gmail.com" method="post" enctype="text/plain">
      <input type="text" name="nombre" placeholder="Nombre completo" required>
      <input type="email" name="email" placeholder="Correo electrónico" required>
      <textarea name="mensaje" rows="5" placeholder="Describe tu consulta o el servicio que necesitas" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>  <footer>
    <p>&copy; 2025 Rehalife Centro de Fisioterapia. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
