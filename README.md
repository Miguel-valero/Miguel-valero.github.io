<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Mi primera página web</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body{
margin:0;
font-family: Arial, sans-serif;
background:#0f172a;
color:white;
}
header{
background:#020617;
padding:20px;
text-align:center;
}
section{
padding:40px;
text-align:center;
}
.card{
background:#1e293b;
border-radius:12px;
padding:20px;
max-width:600px;
margin:auto;
box-shadow:0 0 20px rgba(0,0,0,0.5);
}
button{
background:#38bdf8;
border:none;
padding:12px 20px;
border-radius:8px;
cursor:pointer;
font-size:16px;
margin-top:15px;
}
button:hover{
background:#0ea5e9;
}
footer{
text-align:center;
padding:15px;
background:#020617;
font-size:14px;
margin-top:40px;
}
</style>
</head>
<body>
<header>
<h1>🚀 Mi primera web en GitHub</h1>
<p>Subida con GitHub Pages</p>
</header>
<section>
<div class="card">
<h2>Hola mundo 👋</h2>
<p>Esta es mi primera página web publicada gratis usando GitHub Pages.</p>
<p>Puedo editar este texto, cambiar colores, agregar imágenes y hacerla crecer.</p>
<button onclick="saludar()">Haz clic aquí</button>
</div>
</section>
<footer>
<p>Hecho por mí ❤️ | 2026</p>
</footer>
<script>
function saludar(){
alert("¡Funciona perfecto! 😎 Tu web ya está activa");
}
</script>


</body>
</html>
