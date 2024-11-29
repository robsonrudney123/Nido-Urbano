# Nido-Urbano
/nido-urbano
 <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nido Urbano</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #004080;
            color: white;
            padding: 1.5rem 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #00264d;
            padding: 0.5rem;
        }
        nav a {
            color: white;
            margin: 0 1rem;
            text-decoration: none;
            font-weight: bold;
            display: flex;
            align-items: center;
        }
        nav a i {
            margin-right: 0.5rem;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }
        .section {
            margin-bottom: 2rem;
        }
        footer {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        .capsule-image {
            width: 100%;
            max-height: 400px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 1rem;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
            margin-top: 1rem;
        }
        .gallery img {
            width: 100%;
            border-radius: 10px;
            object-fit: cover;
        }
        .cta-button {
            display: inline-block;
            background-color: #0073e6;
            color: white;
            padding: 0.75rem 1.5rem;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 1rem;
        }
        .cta-button:hover {
            background-color: #005bb5;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form input, form textarea, form button {
            margin-bottom: 1rem;
            padding: 0.75rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
        }
        form button {
            background-color: #0073e6;
            color: white;
            border: none;
            font-weight: bold;
            cursor: pointer;
        }
        form button:hover {
            background-color: #005bb5;
        }
    </style>
</head>
<body>
    <header>
        <h1>Nido Urbano</h1>
        <p>Tu espacio de descanso ideal para estudiantes universitarios</p>
    </header>

    <nav>
        <a href="#inicio"><i class="fas fa-home"></i>Inicio</a>
        <a href="#servicios"><i class="fas fa-concierge-bell"></i>Servicios</a>
        <a href="#precios"><i class="fas fa-money-bill-wave"></i>Precios</a>
        <a href="#contacto"><i class="fas fa-envelope"></i>Contacto</a>
    </nav>

    <div class="container">
        <section id="inicio" class="section">
            <h2>Bienvenidos a Nido Urbano</h2>
            <img src="capsula.jpg" alt="Imagen de una cápsula para dormir" class="capsule-image">
            <p>En Nido Urbano ofrecemos cápsulas para dormir especialmente diseñadas para estudiantes universitarios. Nuestro objetivo es proporcionar un lugar cómodo, seguro y accesible para que puedas descansar entre tus actividades académicas.</p>
            <div class="gallery">
                <img src="capsula1.jpg" alt="Cápsula moderna">
                <img src="capsula2.jpg" alt="Cápsula cómoda">
                <img src="capsula3.jpg" alt="Vista interna">
            </div>
        </section>

        <section id="servicios" class="section">
            <h2>Servicios</h2>
            <ul>
                <li>Cápsulas privadas con medidas de 2.2m x 1.2m x 1.1m</li>
                <li>Ambiente climatizado y silencioso</li>
                <li>Acceso a consumibles como Maruchan, sándwiches, jugos y refrescos</li>
                <li>Higiene garantizada con limpieza después de cada uso</li>
            </ul>
        </section>

        <section id="precios" class="section">
            <h2>Precios</h2>
            <p>El costo de uso de nuestras cápsulas es de <strong>7 Bs por hora</strong>.</p>
            <h3>Productos adicionales:</h3>
            <ul>
                <li>Maruchan: 5 Bs</li>
                <li>Sándwiches: 5 Bs</li>
                <li>Jugos: 2 Bs</li>
                <li>Refrescos 200ml: 2 Bs</li>
            </ul>
        </section>

        <section id="contacto" class="section">
            <h2>Contacto</h2>
            <p>¿Tienes preguntas o quieres más información? Contáctanos:</p>
            <form action="mailto:contacto@nido-urbano.com" method="post" enctype="text/plain">
                <input type="text" name="nombre" placeholder="Tu nombre" required>
                <input type="email" name="email" placeholder="Tu correo electrónico" required>
                <textarea name="mensaje" placeholder="Escribe tu mensaje aquí" rows="5" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Nido Urbano. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

