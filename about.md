<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diğer Çalışma Alanlarımız</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        h1 {
            text-align: center;
            color: #2c3e50;
            padding: 20px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }

        .gallery img:hover {
            transform: scale(1.05);
        }

        .gallery-item {
            text-align: center;
        }

        .gallery-item h3 {
            margin-top: 10px;
            color: #333;
            font-size: 18px;
        }

    </style>
</head>
<body>

    <h1>Diğer Çalışma Alanlarımız</h1>

    <div class="gallery">
        <div class="gallery-item">
            <img src="1bilişim.png" alt="Çalışma Alanı 1">
            <h3>Çalışma Alanı 1</h3>
        </div>
        <div class="gallery-item">
            <img src="2imar.png" alt="Çalışma Alanı 2">
            <h3>Çalışma Alanı 2</h3>
        </div>
        <div class="gallery-item">
            <img src="3iş.png" alt="Çalışma Alanı 3">
            <h3>Çalışma Alanı 3</h3>
        </div>
        <div class="gallery-item">
            <img src="4kamuihale.png" alt="Çalışma Alanı 4">
            <h3>Çalışma Alanı 4</h3>
        </div>
        <div class="gallery-item">
            <img src="5ekonomiceza.png" alt="Çalışma Alanı 5">
            <h3>Çalışma Alanı 5</h3>
        </div>
        <div class="gallery-item">
            <img src="6çocuk.png" alt="Çalışma Alanı 6">
            <h3>Çalışma Alanı 6</h3>
        </div>
        <div class="gallery-item">
            <img src="7gayrimenkul.png" alt="Çalışma Alanı 7">
            <h3>Çalışma Alanı 7</h3>
        </div>
        <div class="gallery-item">
            <img src="8tazminat.png" alt="Çalışma Alanı 8">
            <h3>Çalışma Alanı 8</h3>
        </div>
        <div class="gallery-item">
            <img src="9sağlık.png" alt="Çalışma Alanı 9">
            <h3>Çalışma Alanı 9</h3>
        </div>
    </div>

</body>
</html>
