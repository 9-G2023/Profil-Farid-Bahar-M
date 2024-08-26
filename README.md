<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Siswa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }

        .header {
            background-color: #0056b3;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .container {
            display: flex;
            justify-content: center;
            margin: 20px;
        }

        .card {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            width: 300px; /* Ukuran card yang lebih besar */
            text-align: center;
            padding: 20px;
            transition: transform 0.2s;
        }

        .card:hover {
            transform: scale(1.05);
        }

        .card img {
            border-radius: 50%;
            width: 150px; /* Ukuran gambar yang lebih besar */
            height: 150px; /* Ukuran gambar yang lebih besar */
            object-fit: cover;
        }

        .card h3 {
            margin: 15px 0 10px;
            font-size: 24px; /* Ukuran font nama yang lebih besar */
        }

        .card p {
            margin: 0;
            color: #666;
            font-size: 18px; /* Ukuran font deskripsi yang lebih besar */
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>Profil Siswa 9-G</h1>
    </div>

    <div class="container">
        <div class="card">
            <img src="image 2/FARID BAHAR (1).JPG" alt="Foto Siswa">
            <h3>Farid Bahar Muharrom</h3>
            <p>Bogor , 29 Desember 2008</p>
        </div>
    </div>

</body>
</html>
