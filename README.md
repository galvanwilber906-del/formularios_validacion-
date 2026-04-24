<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Formulario Completo</title>
</head>
<body>

    <h2>Formulario de Registro</h2>

    <form>

        <!-- Nombre -->
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" value="wilber galvan" required>
        <br><br>

        <!-- Correo -->
        <label for="correo">Correo:</label>
        <input type="email" id="correo" name="correo" value="galvanwilber906@gmail.com" required>
        <br><br>

        <!-- Edad -->
        <label for="edad">Edad:</label>
        <input type="number" id="edad" name="edad" value="18" min="1" max="100" required>
        <br><br>

        <!-- Fecha de nacimiento -->
        <label for="fecha">Fecha de nacimiento:</label>
        <input type="date" id="fecha" name="fecha" value="2008-01-13" required>
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
