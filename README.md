# ZIYATI
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZIYATI - Tienda Online</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #1e1e1e;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: #fff;
            padding: 15px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #555;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background-color: #eee;
        }
        .hero h1 {
            font-size: 48px;
            margin-bottom: 10px;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .product {
            background-color: #fff;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            text-align: center;
        }
        .product img {
            max-width: 100%;
            border-radius: 10px;
        }
        .product h3 {
            margin: 10px 0;
        }
        .product p {
            color: #555;
        }
        .product button {
            padding: 10px 20px;
            background-color: #1e1e1e;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .product button:hover {
            background-color: #444;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #1e1e1e;
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>ZIYATI</h1>
        <p>Tu tienda online de confianza</p>
    </header>

    <nav>
        <a href="#productos">Productos</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <section class="hero">
        <h1>Bienvenido a ZIYATI</h1>
        <p>Encuentra los mejores productos al mejor precio</p>
    </section>

    <section id="productos" class="products">
        <div class="product">
            <img src="https://via.placeholder.com/250" alt="Producto 1">
            <h3>Producto 1</h3>
            <p>Descripción breve del producto.</p>
            <button>Comprar</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/250" alt="Producto 2">
            <h3>Producto 2</h3>
            <p>Descripción breve del producto.</p>
            <button>Comprar</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/250" alt="Producto 3">
            <h3>Producto 3</h3>
            <p>Descripción breve del producto.</p>
            <button>Comprar</button>
        </div>
    </section>

    <section id="contacto" style="text-align:center; padding:50px 20px;">
        <h2>Contacto</h2>
        <p>Escríbenos a <a href="mailto:contacto@ziyati.com">contacto@ziyati.com</a></p>
    </section>

    <footer>
        &copy; 2025 ZIYATI. Todos los derechos reservados.
    </footer>
</body>
</html>
