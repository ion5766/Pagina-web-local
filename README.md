<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diseño Web</title>

    <style>
        /* RESET */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            color: #333;
            line-height: 1.6;
        }

        /* HEADER */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 40px;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        nav a {
            text-decoration: none;
            color: #000;
            font-weight: 500;
        }

        /* MAIN CONTAINER */
        main {
            padding: 20px 40px;
        }

        /* SECCION SUPERIOR */
        .intro {
            display: flex;
            gap: 40px;
            margin-bottom: 40px;
        }

        .intro-text {
            flex: 1;
        }

        .intro-text h2 {
            margin-bottom: 10px;
        }

        .intro-text h3 {
            margin-top: 20px;
            margin-bottom: 10px;
        }

        .intro-text ul {
            padding-left: 20px;
        }

        .intro-image {
            flex: 1;
        }

        .intro-image img {
            width: 100%;
            border-radius: 5px;
        }

        /* ESPECIFICACIONES */
        .specs h3 {
            margin-bottom: 15px;
        }

        .specs-content {
            display: flex;
            gap: 40px;
            align-items: flex-start;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th, td {
            border: 1px solid #ccc;
            padding: 10px;
        }

        th {
            background-color: #f4f4f4;
        }

        .specs-image img {
            max-width: 300px;
            border-radius: 5px;
        }

        /* RESPONSIVE */
        @media (max-width: 768px) {
            header {
                flex-direction: column;
                gap: 10px;
            }

            .intro,
            .specs-content {
                flex-direction: column;
            }
        }
    </style>
</head>

<body>

    <!-- HEADER -->
    <header>
        <h1>Diseño Web</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Categorías</a></li>
                <li><a href="#">Carrito</a></li>
            </ul>
        </nav>
    </header>

    <!-- MAIN -->
    <main>

        <!-- SECCION PRINCIPAL -->
        <section class="intro">
            <div class="intro-text">
                <h2>Lorem Ipsum</h2>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Sed diam nonummy nibh euismod tincidunt ut laoreet dolore
                    magna aliquam erat volutpat.
                </p>

                <h3>Características Clave</h3>
                <ul>
                    <li>Rendimiento confiable</li>
                    <li>User-friendly experience</li>
                    <li>Diseño adaptable</li>
                    <li>Compra en línea segura</li>
                </ul>
            </div>

            <div class="intro-image">
                <!-- Reemplaza la URL por la imagen que te dé el profe -->
                <img src="IMAGENES/profe2.PNG" alt="Producto">
            </div>
        </section>

        <!-- ESPECIFICACIONES -->
        <section class="specs">
            <h3>Especificaciones del Producto</h3>

            <div class="specs-content">
                <table>
                    <thead>
                        <tr>
                            <th>Característica</th>
                            <th>Detalles</th>
                            <th>Garantía (años)</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Display</td>
                            <td>15.6” Full HD</td>
                            <td>2 y</td>
                        </tr>
                        <tr>
                            <td>Processor</td>
                            <td>Intel Core I7</td>
                            <td>2 y</td>
                        </tr>
                        <tr>
                            <td>RAM</td>
                            <td>16GB DDR4</td>
                            <td>2 y</td>
                        </tr>
                    </tbody>
                </table>

                <div class="specs-image">
                    <!-- Reemplaza la URL por la imagen que te dé el profe -->
                    <img src="IMAGENES/profe.jpg" alt="Laptop">
                </div>
            </div>
        </section>

        <footer>
    <p>
        © 2026 — 
        <a href="https://www.cibertec.edu.pe" target="_blank" rel="noopener noreferrer">
            Cibertec
        </a>
    </p>
</footer>

    </main>

</body>
</html>
