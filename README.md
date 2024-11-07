<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mapa Conceptual</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f4f4f4;
        }

        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            max-width: 800px;
        }

        .box {
            border: 2px solid #4CAF50;
            padding: 20px;
            margin: 10px;
            border-radius: 10px;
            background-color: #fff;
            width: 100%;
            text-align: center;
            box-shadow: 0px 4px 6px rgba(0,0,0,0.1);
        }

        .arrow-down {
            width: 0;
            height: 0;
            border-left: 20px solid transparent;
            border-right: 20px solid transparent;
            border-top: 20px solid #4CAF50;
            margin: 10px;
        }

        .title {
            font-size: 24px;
            font-weight: bold;
            color: #333;
        }

        .subtitle {
            font-size: 18px;
            font-weight: bold;
            margin-top: 10px;
            color: #555;
        }

        .list {
            text-align: left;
            margin: 10px 0;
            padding-left: 20px;
        }

        .list li {
            margin-bottom: 5px;
        }

        @media (max-width: 600px) {
            .box {
                padding: 15px;
            }
            .title {
                font-size: 20px;
            }
            .subtitle {
                font-size: 16px;
            }
        }
    </style>
</head>
<body>

<div class="container">
    <div class="box">
        <div class="title">Protocolo de Investigación</div>
        <ul class="list">
            <li><strong>Título:</strong> Nombre del proyecto</li>
            <li><strong>Objetivos:</strong> Metas claras del estudio</li>
            <li><strong>Justificación:</strong> Razones para realizar la investigación</li>
            <li><strong>Marco Teórico:</strong> Base conceptual del estudio</li>
            <li><strong>Metodología:</strong> Procedimientos, tipo de investigación, y herramientas</li>
            <li><strong>Cronograma:</strong> Tiempos asignados</li>
            <li><strong>Recursos:</strong> Materiales, humanos, económicos</li>
        </ul>
    </div>

    <div class="arrow-down"></div>

    <div class="box">
        <div class="title">Planteamiento del Problema</div>
        <div class="subtitle">Árbol del Problema</div>
        <ul class="list">
            <li><strong>Problema Central:</strong> Situación principal a resolver</li>
            <li><strong>Causas:</strong> Factores que originan el problema (raíces del árbol)</li>
            <li><strong>Efectos:</strong> Consecuencias del problema (ramas del árbol)</li>
        </ul>
    </div>

    <div class="arrow-down"></div>

    <div class="box">
        <div class="title">Investigación Descriptiva</div>
        <ul class="list">
            <li><strong>Definición:</strong> Describir características de un fenómeno sin analizar relaciones causales</li>
            <li><strong>Objetivo:</strong> Describir el "qué" de un fenómeno</li>
            <li><strong>Métodos:</strong> Observación, encuestas, análisis de datos</li>
            <li><strong>Resultados:</strong> Información detallada sobre el fenómeno estudiado</li>
        </ul>
    </div>
</div>

</body>
</html>
