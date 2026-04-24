<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Formulario</title>
</head>
<body>

    <h2>Formulario de Registro</h2>

    <form>

        <!-- Nombre -->
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" required>
        <br><br>

        <!-- Correo -->
        <label for="correo">Correo:</label>
        <input type="email" id="correo" name="correo" required>
        <br><br>

        <!-- Edad -->
        <label for="edad">Edad:</label>
        <input type="number" id="edad" name="edad" min="1" max="100" required>
        <br><br>

        <!-- Fecha de nacimiento -->
        <label for="fecha">Fecha de nacimiento:</label>
        <input type="date" id="fecha" name="fecha" required>
        <br><br>

        <!-- Contraseña -->
        <label for="password">Contraseña:</label>
        <input type="password" id="password" name="password" required>
        <br><br>

        <!-- Botón -->
        <button type="submit">Enviar</button>

    </form>

</body>
</html>
