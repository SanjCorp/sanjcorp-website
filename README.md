<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sanj Corp</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f9f9f9;
        }
        header {
            background-color: #0047ab;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            font-size: 1.2rem;
        }
        nav {
            background-color: #003580;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .mission-vision {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin-bottom: 30px;
        }
        .mission-vision div {
            flex: 1;
            min-width: 300px;
            padding: 20px;
            background: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        footer {
            background-color: #003580;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 30px;
        }
        form {
            display: flex;
            flex-direction: column;
            gap: 10px;
            max-width: 400px;
            margin: 0 auto;
        }
        input, textarea, button {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #0047ab;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #003580;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenidos a Sanj Corp</h1>
        <p>Innovamos el futuro, creamos posibilidades</p>
    </header>
    <nav>
        <a href="#about">Sobre Nosotros</a>
        <a href="#services">Servicios</a>
        <a href="#contact">Contacto</a>
    </nav>
    <section id="about">
        <h2>Sobre Sanj Corp</h2>
        <div class="mission-vision">
            <div>
                <h3>Misión</h3>
                <p>Innovar con tecnologías disruptivas y crear soluciones que impacten el mundo.</p>
            </div>
            <div>
                <h3>Visión</h3>
                <p>Convertirnos en líderes globales en soluciones tecnológicas y desarrollo industrial.</p>
            </div>
        </div>
    </section>
    <section id="services">
        <h2>Servicios</h2>
        <ul>
            <li>Robótica avanzada</li>
            <li>Impresión 3D</li>
            <li>Desarrollo de software a medida</li>
            <li>Innovación tecnológica para industrias</li>
        </ul>
    </section>
    <section id="contact">
        <h2>Contacto</h2>
        <form>
            <input type="text" name="name" placeholder="Nombre" required>
            <input type="email" name="email" placeholder="Correo Electrónico" required>
            <textarea name="message" placeholder="Escribe tu mensaje" rows="5" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2025 Sanj Corp. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
