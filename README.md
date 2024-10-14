<!DOCTYPE html>

<html lang="es">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Disculpa</title>

    <style>


        body {

            font-family: Arial, sans-serif;

            background-color: #f0f0f0;

            display: flex;

            justify-content: center;

            align-items: center;

            height: 100vh;

            margin: 0;

        }

        .container {

            background-color: #fff;

            padding: 20px;

            border-radius: 10px;

            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);

            text-align: center;

            width: 300px;

        }

        h1 {

            color: #333;

        }

        .buttons {

            margin-top: 15px;

        }

        button {

            background-color: #4CAF50;

            color: white;

            border: none;

            padding: 10px 20px;

            margin: 5px;

            border-radius: 5px;

            cursor: pointer;

            transition: background-color 0.3s;

        }

        button:hover {

            background-color: #45a049;

        }

        .no-button {

            background-color: #f44336;

        }

        .no-button:hover {

            background-color: #d32f2f;

        }

    </style>

</head>



    <div class="container">

        <h1>me perdonas Carlitos</h1>

        <p>¿Aceptas mi dinodisculpa?</p>

        <div class="buttons">

            <button onclick="response('sí bebé')">Sí bebé</button>

            <button class="no-button" onclick="response('no, te odio ')">No, te odio</button>

        </div>

        <p id="message"></p>

    </div>

<img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/dcb5f0e5-306a-45a8-8a79-6e7073a33376/d6uvo9y-4bcfa515-0639-4766-af97-c3c60fb1839c.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2RjYjVmMGU1LTMwNmEtNDVhOC04YTc5LTZlNzA3M2EzMzM3NlwvZDZ1dm85eS00YmNmYTUxNS0wNjM5LTQ3NjYtYWY5Ny1jM2M2MGZiMTgzOWMuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.MhmmFonwXn1VGvgKvdKNdLCUNDtvL0rUoM_4_ZZSrI4" alt="GIF de Hello Kitty">

    <script>

        function response(answer) {

            const message = document.getElementById('message');

            if (answer === 'sí bebé') {

                message.textContent = '¡te amo!';

            } else {

                message.textContent = '¡Grosero!';

            }

        }
        
    

    

    </script>

</body>

</html>
