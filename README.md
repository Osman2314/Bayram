Selamun aleykum>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bayram Kutlama</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        #message {
            display: none;
            margin-top: 20px;
            font-size: 24px;
        }
        img {
            width: 100px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <a href="#" onclick="afficherMessage()">Cliquez ici pour un message spécial</a>

    <div id="message">
        <p>Ramazan Bayramınız mübarek olsun Şişman ailesi !</p>
        <img src="https://upload.wikimedia.org/wikipedia/commons/b/b4/Flag_of_Turkey.svg" alt="Drapeau de la Turquie">
    </div>

    <script>
        function afficherMessage() {
            document.getElementById('message').style.display = 'block';
        }
    </script>

</body>
</html>
