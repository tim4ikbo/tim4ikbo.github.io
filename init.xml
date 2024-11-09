<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Photo Grid</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }
        .container {
            position: relative;
            width: 80%;
            max-width: 1200px;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            grid-gap: 10px;
        }
        .grid img {
            width: 100%;
            height: auto; /* Maintain aspect ratio */
            object-fit: cover; /* Cover the area without distortion */
        }
        .text-overlay {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: white;
            font-size: 2em;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="grid">
            <img src="photo1.jpg" alt="Photo 1" style="grid-column: span 2; grid-row: span 2;">
            <img src="photo2.jpg" alt="Photo 2">
            <img src="photo3.jpg" alt="Photo 3">
            <img src="photo4.jpg" alt="Photo 4">
            <img src="photo5.jpg" alt="Photo 5">
            <img src="photo6.jpg" alt="Photo 6">
            <img src="photo7.jpg" alt="Photo 7">
            <img src="photo8.jpg" alt="Photo 8">
            <img src="photo9.jpg" alt="Photo 9">
        </div>
        <div class="text-overlay">Contacts</div>
    </div>
</body>
</html>
