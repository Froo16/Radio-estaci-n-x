# Radio-estaci-n-x
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Radio Online</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #000428, #004e92);
      color: white;
      scroll-behavior: smooth;
    }

    header {
      text-align: center;
      padding: 40px 20px;
      background-color: #111;
      animation: fadeIn 2s ease-in-out;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
    }

    .player {
      text-align: center;
      padding: 40px 20px;
    }

    audio {
      width: 80%;
      max-width: 400px;
      margin-top: 20px;
    }

    .about, .contact, .social {
      padding: 40px 20px;
      text-align: center;
    }

    form {
      max-width: 500px;
      margin: 0 auto;
      background: rgba(255,255,255,0.1);
      padding: 20px;
      border-radius: 12px;
    }

    input, textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: none;
      border-radius: 8px;
      font-size: 1rem;
    }

    button {
      background-color: #ff4d4d;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 8px;
      cursor: pointer;
      font-size: 1rem;
    }

    button:hover {
      background-color: #cc0000;
    }

    .social-icons a {
      color: #fff;
      margin: 0 10px;
      font-size: 2rem;
      transition: transform 0.3s ease;
    }

    .social-icons a:hover {
      transform: scale(1.2);
      color: #ff4d4d;
    }

    footer {
      background-color: #000;
      color: white;
      text-align: center;
      padding: 15px;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>

  <header>
    <h1>Radio Viva FM</h1>
    <p>La mejor música en vivo, 24/7</p>
  </header>

  <section class="player">
    <h2>Escúchanos en vivo</h2>
    <audio controls autoplay>
      <source src="https://example.com/stream.mp3" type="audio/mpeg" />
      Tu navegador no soporta el reproductor de audio.
    </audio>
  </section>

  <section class="about">
    <h2>Sobre Nosotros</h2>
    <p>Radio Viva FM transmite los mejores hits del momento, noticias, entrevistas y mucho más. ¡Conéctate con nosotros donde sea que estés!</p>
  </section>

  <section class="contact">
    <h2>Contáctanos</h2>
    <form>
      <input type="text" placeholder="Tu nombre" required />
      <input type="email" placeholder="Tu correo" required />
      <textarea rows="4" placeholder="Tu mensaje..." required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <section class="social">
    <h2>Síguenos</h2>
    <div class="social-icons">
      <a href="#"><i class="fab fa-facebook-square"></i></a>
      <a href="#"><i class="fab fa-instagram"></i></a>
      <a href="#"><i class="fab fa-twitter-square"></i></a>
      <a href="#"><i class="fab fa-youtube"></i></a>
    </div>
  </section>

  <footer>
    &copy; 2025 Radio Viva FM - Todos los derechos reservados
  </footer>

</body>
</html>
