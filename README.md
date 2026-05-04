<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Nuestra Boda</title>
<style>
    body {
        font-family: 'Arial', sans-serif;
        text-align: center;
        background-color: #fdf6f0;
        color: #333;
        margin: 0;
    }
    .container {
        padding: 40px;
    }
    h1 {
        font-size: 40px;
    }
    .fecha {
        font-size: 24px;
        margin: 20px 0;
    }
    .box {
        background: white;
        padding: 20px;
        margin: 20px auto;
        max-width: 500px;
        border-radius: 15px;
        box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    button {
        background-color: #d4a373;
        border: none;
        padding: 15px;
        color: white;
        font-size: 16px;
        border-radius: 10px;
        cursor: pointer;
    }
</style>
</head>

<body>

<div class="container">
    <h1>💍 ¡Nos Casamos! 💍</h1>
    
    <p class="fecha">Fernanda & [Nombre pareja]</p>
    <p class="fecha">12 de Diciembre 2026</p>

    <div class="box">
        <h2>📍 Lugar</h2>
        <p>Salón de Eventos [Nombre]</p>
    </div>

    <div class="box">
        <h2>⏰ Hora</h2>
        <p>18:00 hrs</p>
    </div>

    <div class="box">
        <h2>👗 Dress Code</h2>
        <p>Formal elegante</p>
    </div>

    <div class="box">
        <h2>✅ Confirmación</h2>
        <p>Confirma tu asistencia aquí:</p>
        <button onclick="window.open('https://wa.me/569XXXXXXXX','_blank')">
            Confirmar por WhatsApp
        </button>
    </div>

</div>

</body>
</html>
