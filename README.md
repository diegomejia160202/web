<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Labtec - Laboratorio Médico</title>
    <link rel="stylesheet" href="diseño.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Encabezado -->
    <header>
        <div class="logo-container">
            <img src="LABTEC.png" alt="Labtec Logo">
            <h1>Labtec</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Servicios</a></li>
                <li><a href="#">Acerca de</a></li>
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <!-- Sección principal -->
    <main>
        <section class="hero parallax">
            <h2>Excelencia en Diagnóstico Médico</h2>
        </section>

        <section class="intro">
            <div class="intro-logo-container">
                <img class="intro-logo" src="LABTEC.png" alt="Labtec Logo">
            </div>
            <h2>BIENVENIDOS A LABTEC</h2>
            <p>TECNOLOGÍA QUE CUIDA DE TI</p>
            <a href="#contacto" class="btn">Contáctanos</a>
        </section>

        <!-- Sección de botones -->
        <section class="botones">
            <a href="#" class="btn">Consulta tus resultados</a>
            <a href="#" class="btn">Realiza tu cita</a>
            <a href="#" class="btn">Cotiza tus estudios</a>
            <a href="#" class="btn">Ver más servicios</a>
        </section>

        <!-- Sección de servicios -->
        <section class="servicios" id="servicios">
            <h2>Nuestros Servicios</h2>
            <div class="servicio">
                <img src="icono-microscopio.svg" alt="Microscopio">
                <h3>Pruebas de laboratorio</h3>
                <p>Ofrecemos análisis de sangre, orina y otros estudios clínicos de alta precisión.</p>
            </div>
            <div class="servicio">
                <img src="icono-diagnostico.svg" alt="Diagnóstico">
                <h3>Diagnóstico médico</h3>
                <p>Utilizamos tecnología avanzada para detectar y prevenir enfermedades.</p>
            </div>
            <div class="servicio">
                <img src="icono-atencion.svg" alt="Atención personalizada">
                <h3>Atención personalizada</h3>
                <p>Nuestro equipo profesional brinda un servicio cercano y humano.</p>
            </div>
        </section>

        <!-- Sección de contacto -->
        <section class="contacto" id="contacto">
            <h2>Contáctanos</h2>
            <p>Estamos aquí para ayudarte. Llámanos o visítanos para cualquier consulta.</p>
            <form action="#">
                <label for="nombre">Nombre:</label>
                <input type="text" id="nombre" name="nombre" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="mensaje">Mensaje:</label>
                <textarea id="mensaje" name="mensaje" required></textarea>
                
                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>

    <!-- Pie de página -->
    <footer>
        <p>&copy; 2024 Labtec - Laboratorio Médico. Todos los derechos reservados.</p>
        <div class="social-icons">
            <a href="#"><img src="icon-facebook.svg" alt="Facebook"></a>
            <a href="#"><img src="icon-twitter.svg" alt="Twitter"></a>
            <a href="#"><img src="icon-instagram.svg" alt="Instagram"></a>
        </div>
    </footer>
</body>
</html>
