<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¡Únete a Roodland! 🐺</title>
    <style>
        body { font-family: Arial, sans-serif; background: #111; color: #fff; }
        .container { max-width: 600px; margin: 50px auto; padding: 20px; border: 2px solid gold; }
        h1 { color: gold; text-align: center; }
        .form-group { margin-bottom: 15px; }
        label { display: block; margin-bottom: 5px; }
        input, select { width: 100%; padding: 8px; background: #222; color: #fff; border: 1px solid #444; }
        button { background: gold; color: #000; padding: 10px 15px; border: none; cursor: pointer; }
    </style>
</head>
<body>
    <div class="container">
        <h1>🏰 Registro de Ciudadanía de Roodland</h1>
        <form id="ciudadaniaForm">
            <div class="form-group">
                <label for="nombre">Nombre completo:</label>
                <input type="text" id="nombre" required>
            </div>
            <div class="form-group">
                <label for="email">Correo electrónico:</label>
                <input type="email" id="email" required>
            </div>
            <div class="form-group">
                <label for="rol">Rol en Roodland:</label>
                <select id="rol" required>
                    <option value="">Selecciona...</option>
                    <option value="ciudadano">Ciudadano</option>
                    <option value="noble">Noble</option>
                    <option value="mercenario">Mercenario</option>
                </select>
            </div>
            <button type="submit">¡Enviar Solicitud!</button>
        </form>
        <p id="mensaje"></p>
    </div>

    <script src="app.js"></script>
</body>
</html># git-clone-https-github.com-tu-usuario-roodland-ciudadania