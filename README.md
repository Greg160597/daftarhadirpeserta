<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulir Registrasi</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f0f0;
            text-align: center;
            margin: 50px;
        }
        .registration-form {
            max-width: 600px;
            margin: auto;
            background-color: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .registration-form label {
            display: block;
            margin: 15px 0 5px;
            text-align: left;
        }
        .registration-form input {
            width: calc(100% - 20px);
            padding: 10px;
            margin-bottom: 15px;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .registration-form select {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .registration-form button {
            background-color: #4CAF50;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .registration-form button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <div class="registration-form">
        <h2>Formulir Registrasi</h2>
        <form action="https://www.instagram.com/insidepontianakcom/" method="get">
            <label for="nama">Nama:</label>
            <input type="text" id="nama" name="nama" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="alamat">Alamat:</label>
            <input type="text" id="alamat" name="alamat" required>

            <label for="asal">Asal:</label>
            <input type="text" id="asal" name="asal" required>

            <label for="jenisKelamin">Jenis Kelamin:</label>
            <select id="jenisKelamin" name="jenisKelamin" required>
                <option value="pria">Pria</option>
                <option value="wanita">Wanita</option>
            </select>

            <button type="submit">Daftar</button>
        </form>
    </div>

</body>
</html>
