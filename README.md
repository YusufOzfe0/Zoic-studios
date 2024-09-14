# Zoic-studios
First Repository
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kayıt Formu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
        }
        form {
            border: 1px solid #ddd;
            padding: 20px;
            border-radius: 8px;
            background-color: #f9f9f9;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .form-group {
            margin-bottom: 15px;
        }
        label {
            display: block;
            margin-bottom: 5px;
        }
        textarea,
        input[type="text"],
        input[type="number"],
        input[type="tel"] {
            width: 100%;
            padding: 8px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            display: block;
            width: 100%;
            padding: 10px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 4px;
            font-size: 16px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Kayıt Formu</h1>
        <form>
            <div class="form-group">
                <label for="age">Kaç yaşındasınız?</label>
                <input type="number" id="age" name="age" required>
            </div>
            <div class="form-group">
                <label for="reason">Neden Zoic Studio?</label>
                <textarea id="reason" name="reason" rows="4" required></textarea>
            </div>
            <div class="form-group">
                <label for="oath">İhanet etmeyeceğinize yemin edin:</label>
                <input type="text" id="oath" name="oath" required>
            </div>
            <div class="form-group">
                <label for="actions">Yetkili olduğunuzda ne yapacaksınız?</label>
                <textarea id="actions" name="actions" rows="4" required></textarea>
            </div>
            <div class="form-group">
                <label for="morph">Morph bilginiz 10/? kaç?</label>
                <input type="number" id="morph" name="morph" required>
            </div>
            <button type="submit">Gönder</button>
        </form>
    </div>
</body>
</html>
