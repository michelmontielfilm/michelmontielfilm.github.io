<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video en Loop</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
        }
        video {
            max-width: 90%;
            max-height: 90%;
            border: none;
        }
    </style>
</head>
<body>
    <video autoplay loop muted>
        <source src="video.mp4" type="video/mp4">
        Tu navegador no soporta la etiqueta de video.
    </video>
</body>
</html>
