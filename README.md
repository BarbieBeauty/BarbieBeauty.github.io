<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Barbie Beauty</title>
    <link rel="stylesheet" href="styles.css"> <!-- Puedes crear un archivo CSS para estilos -->
</head>
<body>
    <header>
        <h1>Barbie Beauty</h1>
        <nav>
            <ul>
                <li><a href="#productos">Productos</a></li>
                <li><a href="#sobre-nosotros">Sobre Nosotros</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="hero">
            <h2>Bienvenida a Barbie Beauty</h2>
            <p>¡Descubre la magia de la belleza con nuestros productos inspirados en Barbie!</p>
        </section>

        <section id="productos">
            <h2>Nuestros Productos</h2>
            <div class="producto">
                <img src="tenis nike blancos.jpeg" alt="Producto 1">
                <h3>TENIS NIKE</h3>
                <p>Tenis nike de excelente calidad. CALIDAD G5</p>
                <p>Precio: $1100</p>
                <button onclick="window.open('modelos tenis.html', '_blank')">Ver Modelos</button> <!-- Botón "Ver Modelos" -->
            </div>
            <div class="producto">
                <img src="Brasier mujer variados.jpeg" alt="Producto 2">
                <h3>Brasier</h3>
                <p>Varios colores.</p>
                <p>Precio: $150 c/u</p>
                <button onclick="window.open('modelos BRASIER.html', '_blank')">Ver Modelos</button> <!-- Botón "Ver Modelos" -->
            </div>
            <div class="producto">
                <img src="Conjunto deportivo negro.jpeg" alt="Producto 3">
                <h3>Conjuntos</h3>
                <p>Conjunto deportivo para salidas o gimnasio.</p>
                <p>Precio: $700</p>
            </div>
            <div class="producto">
                <img src="camisa.jpg" alt="Producto 4">
                <h3>Camisa</h3>
                <p>camisa casual.</p>
                <p>Precio: $150</p>
            </div>
        </section>

        <section id="sobre-nosotros">
            <h2>Sobre Nosotros</h2>
            <p>En Barbie Beauty, creemos que cada persona tiene su propia belleza. Nuestra misión es proporcionar productos que celebren la diversidad y la creatividad.</p>
        </section>

        <section id="contacto">
            <h2>Contacto</h2>
            <form>
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

    <footer>
        <p>&copy; 2024 Barbie Beauty . Todos los derechos reservados.</p>
    </footer>
</body>
</html>

