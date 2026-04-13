# Deseos-putrefactos-2..
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Deseos Putrefactos II - Menú Principal</title>
    <style>
        body {
            background-color: #050505;
            color: #e0e0e0;
            font-family: 'Courier New', Courier, monospace;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            margin: 0;
        }
        h1 { color: #8b0000; text-shadow: 2px 2px 5px black; font-size: 3rem; }
        .menu-container {
            border: 1px solid #333;
            padding: 40px;
            background: #111;
            box-shadow: 0 0 20px rgba(139, 0, 0, 0.2);
        }
        .boton-capitulo {
            display: block;
            width: 250px;
            padding: 15px;
            margin: 10px 0;
            background: transparent;
            color: white;
            border: 1px solid #444;
            text-align: center;
            text-decoration: none;
            transition: 0.3s;
        }
        .boton-capitulo:hover {
            background: #8b0000;
            border-color: red;
            transform: scale(1.05);
        }
    </style>
</head>
<body>

    <h1>DESEOS PUTREFACTOS II</h1>
    <p>La pesadilla continúa...</p>

    <div class="menu-container">
        <a href="capitulo1.html" class="boton-capitulo">CAPÍTULO 1</a>
        <a href="capitulo2.html" class="boton-capitulo">CAPÍTULO 2</a>
        <a href="capitulo3.html" class="boton-capitulo">CAPÍTULO 3</a>
        <div style="color: #444; text-align: center; margin-top: 20px;">Próximamente más...</div>
    </div>

</body>
</html>
