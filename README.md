# Nexo-Shop
Nexo Shop: La tendencia es ser tú. Descubre una selección única de productos que realzan tu estilo personal. ¡Solo lo encuentras aquí!
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nexo Shop | Bisutería de Autor</title>
    <style>
        /* CSS - El diseño "Rembrandt" y Cinematográfico */
        :root {
            --oro: #d4af37;
            --negro-fondo: #0a0a0a;
            --negro-tarjeta: #1a1a1a;
            --blanco: #ffffff;
            --gris-suave: #a0a0a0;
        }

        body {
            background-color: var(--negro-fondo);
            color: var(--blanco);
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            margin: 0;
            line-height: 1.6;
        }

        header {
            height: 80vh;
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), 
                        url('https://images.unsplash.com/photo-1515562141207-7a18b5ce7142?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80'); /* Imagen de fondo elegante */
            background-size: cover;
            background-position: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            border-bottom: 2px solid var(--oro);
        }

        .logo-container img {
            max-width: 200px;
            filter: drop-shadow(0 0 10px rgba(212, 175, 55, 0.5));
            margin-bottom: 20px;
        }

        h1 {
            font-size: 3rem;
            letter-spacing: 5px;
            margin: 0;
            text-transform: uppercase;
        }

        .tagline {
            color: var(--oro);
            font-style: italic;
            font-size: 1.2rem;
            margin-bottom: 30px;
        }

        .btn-primario {
            background-color: transparent;
            color: var(--oro);
            border: 1px solid var(--oro);
            padding: 12px 30px;
            text-decoration: none;
            text-transform: uppercase;
            transition: 0.4s;
            font-weight: bold;
        }

        .btn-primario:hover {
            background-color: var(--oro);
            color: black;
            box-shadow: 0 0 20px var(--oro);
        }

        /* Sección de Productos */
        .container {
            padding: 50px 10%;
        }

        .grid-productos {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }

        .producto-card {
            background-color: var(--negro-tarjeta);
            border: 1px solid #333;
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.3s;
        }

        .producto-card:hover {
            transform: translateY(-10px);
            border-color: var(--oro);
        }

        .producto-img {
            height: 250px;
            background-color: #222;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #444;
            /* Aquí irían las fotos con luz Rembrandt */
        }

        .producto-info {
            padding: 20px;
            text-align: center;
        }

        .precio {
            color: var(--oro);
            font-size: 1.4rem;
            display: block;
            margin: 10px 0;
        }

        footer {
            background-color: #000;
            text-align: center;
            padding: 40px;
            font-size: 0.9rem;
            color: var(--gris-suave);
            border-top: 1px solid #222;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo-container">
            <img src="tu-logo.png" alt="Nexo Shop Logo">
        </div>
        <h1>NEXO SHOP</h1>
        <p class="tagline">Todo lo que necesitas en un solo punto</p>
        <a href="#productos" class="btn-primario">Explorar Colección</a>
    </header>

    <section class="container" id="productos">
        <h2 style="text-align: center; border-bottom: 1px solid var(--oro); display: inline-block;">Novedades</h2>
        
        <div class="grid-productos">
            <div class="producto-card">
                <div class="producto-img">FOTO PRODUCTO 1</div>
                <div class="producto-info">
                    <h3>Anillo Ónix Negro</h3>
                    <p>Acero quirúrgico con acabado mate.</p>
                    <span class="precio">$15.00</span>
                    <a href="#" class="btn-primario" style="padding: 5px 15px; font-size: 0.8rem;">Ver Detalle</a>
                </div>
            </div>

            <div class="producto-card">
                <div class="producto-img">FOTO PRODUCTO 2</div>
                <div class="producto-info">
                    <h3>Cadena Nexo Oro</h3>
                    <p>Bañada en oro de 18k, eslabón reforzado.</p>
                    <span class="precio">$25.00</span>
                    <a href="#" class="btn-primario" style="padding: 5px 15px; font-size: 0.8rem;">Ver Detalle</a>
                </div>
            </div>

            <div class="producto-card">
                <div class="producto-img">FOTO PRODUCTO 3</div>
                <div class="producto-info">
                    <h3>Pulsera Minimal</h3>
                    <p>Diseño ajustable, elegancia diaria.</p>
                    <span class="precio">$12.00</span>
                    <a href="#" class="btn-primario" style="padding: 5px 15px; font-size: 0.8rem;">Ver Detalle</a>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 NEXO SHOP - Diseñado con precisión.</p>
        <p>Envíos a toda Venezuela</p>
    </footer>

</body>
</html>
