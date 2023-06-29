<!DOCTYPE html>
<html>
<head>
    <title>Mi Portafolio Parallax</title>
    <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <link rel="stylesheet" type="text/css" href="styles.css">
    <style>
        .footer {
            background-color: #333;
            color: #fff;
            padding: 20px;
        }

        .footer a {
            color: #fff;
            text-decoration: none;
        }

        .footer a:hover {
            color: #fff;
            text-decoration: underline;
        }

        .footer ul {
            list-style: none;
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 0;
            padding: 0;
        }

        .footer ul li {
            margin: 0 10px;
        }

        .footer ul li:first-child {
            margin-left: 0;
        }

        .footer ul li:last-child {
            margin-right: 0;
        }

        .footer i {
            font-size: 24px;
        }

        .footer p {
            margin-bottom: 0;
        }

        @media (max-width: 768px) {
            .footer ul {
                flex-direction: column;
                align-items: center;
            }
            
            .footer ul li {
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>
    <section class="parallax">
        <h1>Astartes Developer</h1>
    </section>
    
    <section class="content">
        <div class="project">
            <h2>Proyecto 1</h2>
            <p>Descripcion del proyecto 1.</p>
        </div>
        
        <div class="project">
            <h2>Proyecto 2</h2>
            <p>Descripcion del proyecto 2.</p>
        </div>
        
        <!-- Agrega más proyectos aquí -->
    </section>

    <footer class="footer bg-dark text-light text-center py-3">
        <div class="container">
            <ul class="social-media-icons">
                <li><a href="https://www.linkedin.com/" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a></li>
                <li><a href="https://www.twitter.com/" target="_blank"><i class="fab fa-twitter"></i> Twitter</a></li>
                <li><a href="https://www.instagram.com/" target="_blank"><i class="fab fa-instagram"></i> Instagram</a></li>
                <li><a href="mailto:tuemail@gmail.com"><i class="fas fa-envelope"></i> Contacto</a></li>
            </ul>
            <p>© 2023 Mi Portafolio. Todos los derechos reservados.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
