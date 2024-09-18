<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Nombre</title>
    <style>
        body {
            background-color: hsl(208, 61%, 60%);
            font-family: 'arial', sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        h1 {
            color: #333;
            font-size: 2.5em;
        }
        button {
            background-color: #4CAF50;
            color: white;
            padding: 15px 32px;
            font-size: 1.5em;
            border: none;
            cursor: pointer;
            border-radius: 8px;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <h1>Presiona el botón para mostrar tu nombre</h1>
    <button onclick="mostrarNombre()">Mostrar Nombre</button>

    <script>
        function mostrarNombre() {
            let nombre = "Mi nombre es PATRICIO CASTILLO";
            console.log(nombre);
            alert(nombre);
        }
    </script>
</body>
</html>

