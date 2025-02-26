<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RD Tendencias</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <h1>RD Tendencias</h1>
        <nav>
            <ul>
                <li><a href="#economia">Economía</a></li>
                <li><a href="#turismo">Turismo</a></li>
                <li><a href="#negocios">Negocios</a></li>
                <li><a href="#eventos">Eventos</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="economia">
        <h2>Noticias de Economía</h2>
        <p>Últimas tendencias sobre el dólar, inflación y oportunidades de inversión.</p>
    </section>

    <section id="turismo">
        <h2>Turismo y Viajes</h2>
        <p>Explora los mejores destinos en República Dominicana.</p>
    </section>

    <section id="negocios">
        <h2>Emprendimiento y Negocios</h2>
        <p>Consejos para emprendedores y oportunidades de inversión.</p>
    </section>

    <section id="eventos">
        <h2>Eventos y Cultura</h2>
        <p>Conoce los eventos más importantes del año.</p>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <form>
            <input type="text" placeholder="Tu nombre" required>
            <input type="email" placeholder="Tu correo" required>
            <textarea placeholder="Tu mensaje"></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 RD Tendencias. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: #f4f4f4;
    color: #333;
    text-align: center;
}

header {
    background: #007BFF;
    color: white;
    padding: 20px;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 40px 20px;
}

section:nth-child(odd) {
    background: #fff;
}

section:nth-child(even) {
    background: #eaeaea;
}

form input, form textarea {
    width: 80%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ccc;
}

button {
    background: #007BFF;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
}

footer {
    background: #222;
    color: white;
    padding: 10px;
}
