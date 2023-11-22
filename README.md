# SKATE-WORLD
## Proyecto IA DEVF
Para la creación de este proyecto se uso en su totalidad Chat GPT. Su proposito es aprender a usar herramientas como las inteligencias artifiales para facilitar mis proyectos.
Comparto el codigo generado por la IA, sin ninguna alteración mia, pues este proyecto es creado sin conocimientos en programación.

[Webview](https://skate-world--richardedmond.repl.co/) 

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SKATE WORLD</title>
    <style>
        body {
            background: url(space.jpg) no-repeat center center fixed;
            background-size: cover;
            color: #fff;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #222;
            padding: 10px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: space-around;
            margin-top: 10px;
        }

        nav a {
            text-decoration: none;
            color: #fff;
        }

        main {
            padding: 20px;
        }

        button {
            background-color: #4CAF50;
            color: #fff;
            padding: 10px 20px;
            font-size: 16px;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background-color: #45a049;
        }

        section {
            margin-bottom: 20px;
            text-align: center;
        }

        h2 {
            font-weight: bold;
        }

        .horizontal-section {
            display: flex;
            justify-content: space-between;
        }

        .city-section, .item-section {
            width: 30%;
            text-align: center;
            max-width: 300px; /* Establecer el ancho máximo deseado */
            margin: 0 auto; /* Centrar la sección */
        }

        .city-section img, .item-section img {
            max-width: 100%;
            max-height: 200px; /* Establecer la altura máxima deseada */
            border-radius: 8px;
        }

        footer {
            background-color: #222;
            padding: 10px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>SKATE WORLD</h1>
        <nav>
            <a href="#">Inicio</a>
            <button>Carrito</button>
        </nav>
    </header>

    <main>
        <section>
            <h2>NUESTRAS NUEVAS TABLAS</h2>
            <div class="horizontal-section">
                <div class="item-section">
                    <img src="patineta1.jpeg" alt="Artículo 1">
                    <p><strong>SKATE LABS SPACE</strong></p>
                </div>
                <div class="item-section">
                    <img src="paineta2.jpg" alt="Artículo 2">
                    <p><strong>MINI SKATE LABS ALIEN</strong></p>
                </div>
                <div class="item-section">
                    <img src="patineta 3.jpg" alt="Artículo 3">
                    <p><strong>SKATE LABS BLUE</strong></p>
                </div>
            </div>
            <div class="horizontal-section">
                <div class="item-section">
                    <img src="patineta 4.jpeg" alt="Artículo 4">
                    <p><strong>SKATE LABS YETI</strong></p>
                </div>
                <div class="item-section">
                    <img src="patineta 5.jpg" alt="Artículo 5">
                    <p><strong>SKATE LABS ROSES</strong></p>
                </div>
                <div class="item-section">
                    <img src="patineta 6.avif" alt="Artículo 6">
                    <p><strong>SKATE LABS RED</strong></p>
                </div>
            </div>
        </section>

    </main>

    <footer>
        <p>&copy; 2023 Mi Sitio Web. Todos los derechos reservados.</p>
    </footer>

    <section>
        <h2>TIENDAS FISICAS EN</h2>
        <div class="horizontal-section">
                  <div class="item-section">
                      <p>EDOMEX</p>
                  </div>
                  <div class="item-section">
                      <p>CDMX</p>
                  </div>
                  <div class="item-section">
                      <p>GUADALAJARA</p>
                  </div>
              </div>
      <section>
              <h2></h2>
              <div class="horizontal-section">
                  <div class="column-section">
                      <p>Contenido de la Columna 1</p>
                  </div>
                  <div class="column-section">
                      <p>Contenido de la Columna 2</p>
                  </div>
                  <div class="column-section">
                      <p>Contenido de la Columna 3</p>
                  </div>
              </div>
          </section>
