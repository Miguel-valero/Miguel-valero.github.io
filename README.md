<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Miguel Valero | Porfolio</title>
    <link rel="stylesheet" href="style.css"> <style>
        /* Estilos rápidos para que funcione de inmediato */
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height: 1.6; margin: 0; color: #333; }
        header { background: #24292e; color: white; padding: 1rem; text-align: center; }
        .container { max-width: 1000px; margin: auto; padding: 20px; }
        
        /* Rejilla de Proyectos */
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .project-card {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.3s;
        }
        .project-card:hover { transform: translateY(-5px); box-shadow: 0 5px 15px rgba(0,0,0,0.1); }
        .project-info { padding: 15px; }
        .project-info h3 { margin: 0 0 10px; }
        .tags { font-size: 0.8rem; color: #666; margin-bottom: 10px; }
        .btn { display: inline-block; background: #007bff; color: white; padding: 5px 10px; border-radius: 4px; text-decoration: none; }
    </style>
</head>
<body>

<header>
    <h1>Miguel Valero</h1>
    <p>Desarrollador / Especialista en [Tu Área]</p>
</header>

<div class="container">
    <section id="about">
        <h2>Sobre mí</h2>
        <p>¡Hola! Soy Miguel. Me apasiona crear soluciones digitales y aprender nuevas tecnologías.</p>
    </section>

    <hr>

    <section id="portfolio">
        <h2>Mis Proyectos</h2>
        <div class="portfolio-grid">
            
            <div class="project-card">
                <div class="project-info">
                    <h3>Nombre del Proyecto 1</h3>
                    <p class="tags">HTML • CSS • JavaScript</p>
                    <p>Descripción breve de lo que lograste con este proyecto.</p>
                    <a href="#" class="btn">Ver Demo</a>
                    <a href="#" class="btn" style="background:#28a745;">Código</a>
                </div>
            </div>

            <div class="project-card">
                <div class="project-info">
                    <h3>Nombre del Proyecto 2</h3>
                    <p class="tags">Python • Django</p>
                    <p>Una aplicación web que resuelve X problema de forma eficiente.</p>
                    <a href="#" class="btn">Ver Demo</a>
                    <a href="#" class="btn" style="background:#28a745;">Código</a>
                </div>
            </div>

        </div>
    </section>

    <hr>

    <section id="contact">
        <h2>Contacto</h2>
        <p>¿Quieres trabajar conmigo? Escríbeme a: <strong>tu-email@ejemplo.com</strong></p>
    </section>
</div>

</body>
</html>
