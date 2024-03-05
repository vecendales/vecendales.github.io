<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfil Profesional - Victor Cendales</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Victor Eduardo Cendales</h1>
        <nav>
            <a href="#quiensoy">Quien soy</a>
            <a href="#habilidades">Mis Habilidades</a>
            <a href="#proyectos">Mis proyectos</a>
            <a href="#contact">Contacto</a>
        </nav>
    </header>
    
    <section id="quiensoy" class="container">
        <div class="row">
          <div class="col">
            <h2>Quien soy</h2>
            <p>"Soy un apasionado desarrollador web con experiencia en la creación de sitios web dinámicos y funcionales. Me especializo en el uso de tecnologías como HTML, CSS, JavaScript. Tengo habilidades sólidas en el diseño de interfaces atractivas y fáciles de usar, así como en la optimización del rendimiento de los sitios para una experiencia de usuario óptima. Mi objetivo es seguir aprendiendo y creciendo en el campo del desarrollo web para crear soluciones innovadoras y de calidad para mis clientes."</p>
          </div>
          <div class="col">
            <img src="imagenes/foto.jpeg" alt="Foto de perfil de Victor Cendales">
          </div>
        </div>
      </section>

    <section id="habilidades">
        <h2>Habilidades</h2>
        <ul>
            <li>HTML5</li>
            <li>CSS3</li>
            <li>JavaScript</li>
        </ul>
    </section>
    
    <section id="proyectos">
        <h2>Proyectos</h2>
        <div class="proyectos">
            <h3>Proyecto 1</h3>
            <p>Descripción del proyecto 1</p>
        </div>
        <div class="proyectos">
            <h3>Proyecto 2</h3>
            <p>Descripción del proyecto 2</p>
        </div>
    </section>
    <div class="contact-section">
        <h2>Contactanos</h2>
        <form action="/contact_form" method="post">
          <label for="name">Nombre:</label><br>
          <input type="text" id="name" name="name" required><br>
          <label for="email">Email:</label><br>
          <input type="email" id="email" name="email" required><br>
          <label for="message">Mensaje:</label><br>
          <textarea id="message" name="message" required></textarea><br>
          <input type="submit" value="Send Message"><br>
        </form>
      </div>
</body>
<footer>
    <div class="footer-content">
        <p>Copyright © 2024 Todos los derechos reservados.</p>
    </div>
</footer>
</html>
