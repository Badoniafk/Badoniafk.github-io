<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Badoni and Co.</title>
    <style>
        body {
            background-color: #111;
            color: #fff;
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            text-align: center;
            padding: 20px;
            font-size: 2em;
            font-weight: bold;
            letter-spacing: 3px;
            text-transform: uppercase;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 10px;
            padding: 20px;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 5px;
            transition: transform 0.3s ease;
        }
        .gallery img:hover {
            transform: scale(1.05);
        }
        .footer {
            text-align: center;
            padding: 20px;
            font-size: 0.9em;
            opacity: 0.7;
        }
    </style>
</head>
<body>
    <header>Badoni and Co.</header>
    <div class="gallery">
        <img src="photo1.jpg" alt="Photography Sample">
        <img src="photo2.jpg" alt="Photography Sample">
        <img src="photo3.jpg" alt="Photography Sample">
        <!-- Add more photos here -->
    </div>
    <div class="footer">&copy; 2025 Badoni and Co.</div>
</body>
</html>
