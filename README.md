# mi-nuevo-proyecto
tarea
!DOCTYPE html>
<html lang="es">
<head>
    <link rel="stylesheet" href="tarea.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hoja de Vida - Anthony Samaniego</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background-color: #f4f6f9;
            color: #333;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: #ffffff;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            overflow: hidden;
            display: grid;
            grid-template-columns: 30% 70%;
        }
        .sidebar {
            background-color: #2c3e50;
            color: #white;
            color: #fff;
            padding: 30px 20px;
            text-align: center;
        }
        .sidebar img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #1abc9c;
            margin-bottom: 20px;
        }
        .sidebar h2 {
            font-size: 1.1rem;
            margin-bottom: 15px;
            border-bottom: 2px solid #1abc9c;
            padding-bottom: 5px;
            text-transform: uppercase;
        }
        .contact-info, .skills-list {
            list-style: none;
            text-align: left;
            font-size: 0.9rem;
            line-height: 1.8;
            margin-bottom: 25px;
        }
        .skills-list li {
            background: #34495e;
            margin-bottom: 6px;
            padding: 6px 10px;
            border-radius: 4px;
        }
        .main-content {
            padding: 30px;
        }
        .header-main {
            margin-bottom: 25px;
            border-bottom: 2px solid #ecf0f1;
            padding-bottom: 15px;
        }
        .header-main h1 {
            font-size: 2.2rem;
            color: #2c3e50;
            text-transform: uppercase;
        }
        .header-main p {
            font-size: 1.1rem;
            color: #1abc9c;
            font-weight: 600;
        }
        section {
            margin-bottom: 25px;
        }
        section h3 {
            font-size: 1.2rem;
            color: #2c3e50;
            text-transform: uppercase;
            border-bottom: 2px solid #1abc9c;
            padding-bottom: 5px;
            margin-bottom: 12px;
        }
        .experience-item, .education-item {
            margin-bottom: 15px;
        }
        .experience-item h4, .education-item h4 {
            color: #34495e;
            font-size: 1rem;
        }
        .date {
            font-size: 0.85rem;
            color: #7f8c8d;
            margin-bottom: 5px;
            font-style: italic;
        }
        p {
            font-size: 0.95rem;
            line-height: 1.5;
            color: #555;
        }
        @media (max-width: 600px) {
            .container {
                grid-template-columns: 100%;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Columna Izquierda: Foto, Contacto y Habilidades -->
        <div class="sidebar">
            <img src="https://scontent.fcue2-1.fna.fbcdn.net/v/t39.30808-6/738143075_3547840782055562_7607421498991321200_n.jpg?stp=dst-jpg_tt6&cstp=mx2048x2048&ctp=s2048x2048&_nc_cat=103&_nc_map=urlgen_bucketless&ccb=1-7&_nc_sid=a5f93a&_nc_ohc=avGkQd7k5w0Q7kNvwGSDMoZ&_nc_oc=AdoeFOuT72xUw-Uq6xhZ1eq3npcMCLju79ynKm8IPRAnbwUnD7iEJg1gBWClDK7C_ok&_nc_zt=23&_nc_ht=scontent.fcue2-1.fna&_nc_gid=-ntdUkVzxZLxpDusgsmplg&_nc_ss=7b2a8&oh=00_AQSQiJckHULEJQzkFM9jW3VICxoQ-bdom9GgDg6exyHKyg&oe=6AF2710F" alt="Foto de perfil">
            
            <h2>Contacto</h2>
            <ul class="contact-info">
                <li>📍 Cuenca, Ecuador</li>
                <li>📞 +593 981171458</li>
                <li>✉️ anthokun33@email.com</li>
                
            </ul>

            <h2>Habilidades</h2>
            <ul class="skills-list">
                <li>HTML5 y CSS3</li>
                <li>JavaScript</li>  
                
         <li>Trabajo en equipo</li>
                <li>Resolución de problemas</li>
            </ul>
        </div>

        <!-- Columna Derecha: Perfil, Experiencia y Formación -->
        <div class="main-content">
            <div class="header-main">
                <h1>Anthony Samaniego</h1>
                <p>Desarrollador Web </p>
            </div>

            <section>
                <h3>Perfil Profesional</h3>
                <p>
                    aprendiendo a elaborar estructuras en html y conocimientos en JavaScript en mi materia de siseño web
                </p>
            </section>

            <section>
                <h3>Experiencia Laboral</h3>
                <div class="experience-item">
                    <h4>Desarrollador htmls </html></h4>
                    <div class="date">septiembre 2026 - Presente</div>
                    <p>Desarrollo y mantenimiento de sitios web corporativos utilizando HTML, CSS y JavaScript. Colaboración con el equipo de diseño UI/UX para implementar prototipos interactivos.</p>
                </div>
                <div class="experience-item">
                    <h4>Asistente de Soporte IT — DigitalWeb Ltda.</h4>
                    <div class="date">octumbre 2026 - noviembre2026</div>
                    <p>Mantenimiento preventivo de equipos, gestión de redes básicas y soporte técnico a usuarios internos. </p>
                </div>
            </section>

            <section>
                <h3>Formación Académica</h3>
                <div class="education-item">
                    <h4>Colegio nacional experimental benigno malo </h4>
                    <div class="date">2018 - 2022</div>
                    <p>instituto superior tecnologico sudamericano</p>
                </div>
                <div class="education-item">
                    
                    <div class="date">2026</div>
                    
                </div>
            </section>
        </div>
    </div>

</body>
</html>
