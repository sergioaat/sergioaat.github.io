# sergioaat.github.io
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Techme</title>
    <link rel="stylesheet" href="styles.css" />
</head>
<body>
    <header>
        <div class="container">
            <h1>Techme</h1>
            <p>Asesoría académica profesional para estudiantes y trabajadores.</p>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#servicios">Servicios</a></li>
            <li><a href="#porque">¿Por qué Techme?</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>

    <main>
        <section id="inicio" class="container">
            <h2>Bienvenido a Techme</h2>
            <p>Ofrecemos apoyo académico personalizado para estudiantes universitarios online, técnicos y personas que estudian mientras trabajan. ¡Estamos aquí para hacerte la vida más fácil!</p>
        </section>

        <section id="servicios" class="container">
            <h2>Servicios</h2>
            <ul>
                <li>Asesorías en Cálculo 1 y 2</li>
                <li>Electrónica y Electricidad básica</li>
                <li>Trigonometría y Física</li>
                <li>Biología general</li>
                <li>Otros: cuéntanos tu caso y te ayudamos</li>
            </ul>
            <p><strong>Nota:</strong> No mostramos precios fijos. <span class="resaltar">Contáctanos para cotizar tu caso.</span></p>
        </section>

        <section id="porque" class="container">
            <h2>¿Por qué elegir Techme?</h2>
            <ul>
                <li>Atención personalizada</li>
                <li>Entregas a tiempo</li>
                <li>100% confidencialidad</li>
                <li>Experiencia con estudiantes reales</li>
            </ul>
        </section>

        <section id="contacto" class="container">
            <h2>Contáctanos</h2>
            <p>¿Tienes una duda o necesitas una cotización? Escríbenos por WhatsApp.</p>
            <a class="whatsapp-button" href="https://wa.me/573001112222" target="_blank">Hablar por WhatsApp</a>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Techme. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

body {
    margin: 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #f9f9f9;
    color: #333;
}

header {
    background-color: #004d40;
    color: white;
    padding: 40px 0;
    text-align: center;
}

nav {
    background-color: #00695c;
    padding: 10px 0;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    margin: 0;
    padding: 0;
}

nav li {
    margin: 0 15px;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.container {
    padding: 20px;
    max-width: 900px;
    margin: auto;
}

.resaltar {
    color: #00796b;
    font-weight: bold;
}

.whatsapp-button {
    background-color: #25D366;
    color: white;
    padding: 12px 20px;
    text-decoration: none;
    border-radius: 5px;
    display: inline-block;
    margin-top: 10px;
}

footer {
    background-color: #004d40;
    color: white;
    text-align: center;
    padding: 15px 0;
    margin-top: 30px;
}
