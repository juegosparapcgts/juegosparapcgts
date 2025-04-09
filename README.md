<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Descarga de Juegos</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenido a la Página de Descarga de Juegos</h1>
    </header>
    <main>
        <section>
            <h2>Sube tu Juego</h2>
            <form action="upload.php" method="post" enctype="multipart/form-data">
                <label for="gameName">Nombre del Juego:</label>
                <input type="text" id="gameName" name="gameName" required>
                
                <label for="gameFile">Selecciona el archivo:</label>
                <input type="file" id="gameFile" name="gameFile" accept=".zip,.rar,.exe" required>
                
                <button type="submit">Subir Juego</button>
            </form>
        </section>
        <section>
            <h2>Juegos Disponibles</h2>
            <ul id="gameList">
                <li><a href="juegos/juego1.zip">Juego 1</a></li>
                <li><a href="juegos/juego2.zip">Juego 2</a></li>
                <li><a href="juegos/juego3.zip">Juego 3</a></li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Descarga de Juegos. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
