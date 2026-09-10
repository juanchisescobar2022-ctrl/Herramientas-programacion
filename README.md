<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Ejercicios - Herramientas de Programación I</title>

    <style>
        /* =========================
           CONFIGURACIÓN
        ========================= */

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            min-height: 100vh;
            font-family: Arial, sans-serif;
            color: white;

            background:
                radial-gradient(circle at top, #062b45, transparent 45%),
                linear-gradient(135deg, #02040a, #061522, #02040a);
        }

        /* =========================
           HEADER
        ========================= */

        header {
            text-align: center;
            padding: 45px 20px;

            background: rgba(2, 10, 18, 0.9);
            border-bottom: 2px solid #00eaff;

            box-shadow:
                0 5px 25px rgba(0, 234, 255, 0.4);
        }

        header h1 {
            color: #00eaff;
            font-size: 32px;
            margin-bottom: 15px;

            text-shadow:
                0 0 5px #00eaff,
                0 0 15px #00eaff,
                0 0 30px #008cff;
        }

        header p {
            color: #bdefff;
            margin: 7px;
        }

        /* =========================
           CONTENIDO
        ========================= */

        main {
            width: 90%;
            max-width: 950px;
            margin: 45px auto;
        }

        /* =========================
           TARJETAS
        ========================= */

        .contenedor {
            padding: 30px;
            margin-bottom: 30px;

            background: rgba(5, 18, 30, 0.9);

            border: 1px solid #0077ff;
            border-radius: 18px;

            box-shadow:
                0 0 15px rgba(0, 140, 255, 0.4),
                inset 0 0 20px rgba(0, 234, 255, 0.05);
        }

        .contenedor h2 {
            color: #00eaff;
            text-align: center;
            margin-bottom: 25px;

            text-shadow: 0 0 10px #00eaff;
        }

        /* =========================
           BOTONES DE LAS CLASES
        ========================= */

        .botones {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 18px;

            list-style: none;
        }

        .boton {
            display: flex;
            flex-direction: column;

            padding: 20px;

            text-decoration: none;
            color: white;

            background: linear-gradient(
                135deg,
                #081c2c,
                #0b2d46
            );

            border: 1px solid #008cff;
            border-radius: 12px;

            box-shadow:
                0 5px 15px rgba(0, 0, 0, 0.5),
                0 0 8px rgba(0, 140, 255, 0.4);

            font-size: 18px;
            font-weight: bold;

            transition: 0.3s ease;
        }

        /* =========================
           EFECTO AL PASAR EL MOUSE
        ========================= */

        .boton:hover {
            transform: translateY(-5px) scale(1.02);

            background: linear-gradient(
                135deg,
                #073b5c,
                #005ca8
            );

            border-color: #00eaff;

            box-shadow:
                0 0 10px #00eaff,
                0 0 25px #008cff,
                0 10px 30px rgba(0, 0, 0, 0.7);
        }

        /* =========================
           PROYECTO
        ========================= */

        .proyecto {
            text-align: center;
        }

        .proyecto p {
            margin: 15px 0;
            color: #bdefff;
        }

        /* =========================
           BOTÓN DEL PROYECTO
        ========================= */

        .boton-proyecto {
            display: inline-block;

            padding: 16px 35px;
            margin: 10px;

            color: #001018;
            background: #00eaff;

            border-radius: 30px;

            text-decoration: none;
            font-weight: bold;

            box-shadow:
                0 0 10px #00eaff,
                0 0 25px #008cff;

            transition: 0.3s;
        }

        .boton-proyecto:hover {
            transform: scale(1.08);

            background: white;

            box-shadow:
                0 0 15px white,
                0 0 35px #00eaff;
        }

        /* =========================
           ESTADO
        ========================= */

        .estado {
            color: #00eaff !important;
            font-weight: bold;

            text-shadow: 0 0 8px #00eaff;
        }

        /* =========================
           FOOTER
        ========================= */

        footer {
            text-align: center;

            padding: 30px;

            background: #030a11;

            border-top: 2px solid #0077ff;

            box-shadow:
                0 -5px 20px rgba(0, 140, 255, 0.3);

            color: #8eefff;
        }

        footer p {
            margin: 7px;
        }

        /* =========================
           CELULARES
        ========================= */

        @media (max-width: 600px) {

            .botones {
                grid-template-columns: 1fr;
            }

            header h1 {
                font-size: 24px;
            }

            .contenedor {
                padding: 20px;
            }
        }
    </style>
</head>

<body>

    <!-- ENCABEZADO -->

    <header>
        <h1>🎮 EJERCICIOS DE PROGRAMACIÓN 🎮</h1>

        <p>
            Herramientas de Programación I · Grado 10°
        </p>

        <p>
            Juan Escobar · Ale Mora · Jaco Piza
        </p>
    </header>


    <!-- CONTENIDO PRINCIPAL -->

    <main>

        <!-- SECCIÓN DE CLASES -->

        <section class="contenedor">

            <h2>🎮 MIS CLASES</h2>

            <ul class="botones">

                <li>
                    <a class="boton" href="clase01/index.html">
                        🎯 Clase 1 — Sobre mí videogames
                    </a>
                </li>

                <li>
                    <a class="boton" href="clase02/index.html">
                        🎮 Clase 2 — Sobre los videojuegos
                    </a>
                </li>

                <li>
                    <a class="boton" href="clase03/index.html">
                        📊 Clase 3 — Información de la página en formato tabla
                    </a>
                </li>

                <li>
                    <a class="boton" href="clase04/index.html">
                        🧮 Clase 4 — Fórmulas
                    </a>
                </li>

                <li>
                    <a class="boton" href="clase05/index.html">
                        🎨 Clase 5 — Estilos y CSS
                    </a>
                </li>

                <li>
                    <a class="boton" href="clase06/index.html">
                        🔒 Clase 6 — Próximamente
                    </a>
                </li>

            </ul>

        </section>


        <!-- SECCIÓN DEL PROYECTO -->

        <section class="contenedor proyecto">

            <h2>🚀 MI PROYECTO</h2>

            <p>
                Mi aplicación:
            </p>

            <a class="boton-proyecto" href="proyecto/index.html">
                🎮 GESTOR DE TAREAS
            </a>

            <p class="estado">
                ⚡ Proyecto en construcción
            </p>

        </section>

    </main>


    <!-- PIE DE PÁGINA -->

    <footer>

        <p>
            🎮 Herramientas de Programación I
        </p>

        <p>
            Grado 10° · Proyecto Gamer
        </p>

    </footer>

</body>

</html>
