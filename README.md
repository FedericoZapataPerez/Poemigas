<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RedirecciÃ³n Aleatoria</title>
</head>
<body>
    <script>
        // Lista de URLs de los documentos
        const documentos = [
            "https://drive.google.com/file/d/1gae0whDHgI_RFMEolom-gU4EK9P9Zwdy/view?usp=drive_link",
            "https://drive.google.com/file/d/1--SUbD39uQx-ypg8kA2nDZsLQNz3zexn/view?usp=drive_link",
            "https://drive.google.com/file/d/17r7_XtDhquZxKmFZDUz2Pbf0hGlPqOBi/view?usp=drive_link",
            "https://drive.google.com/file/d/1JZqzX9Kju5qosNn55iwFaLWOg-5KWnbr/view?usp=drive_link",
            
        ];

        // SelecciÃ³n aleatoria
        const aleatorio = documentos[Math.floor(Math.random() * documentos.length)];

        // Redirigir al enlace seleccionado
        window.location.href = aleatorio;
    </script>
    <p>Redirigiendo a un poema aleatorio...</p>
</body>
</html>
