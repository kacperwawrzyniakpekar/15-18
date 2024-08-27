<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Strona z trzema układami</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        .container {
            width: 90%;
            height: 400px;
            margin: 20px;
            border: 2px solid #333;
            background-color: #fff;
        }
        iframe {
            width: 100%;
            height: 100%;
            border: none;
        }
        h2 {
            text-align: center;
            margin: 10px 0;
        }
    </style>
</head>
<body>

    <h2>Układ 1: Okno mniejsze po prawej → menu pionowe</h2>
    <div class="container">
        <iframe src="layout1.html"></iframe>
    </div>

    <h2>Układ 2: Okno mniejsze na dole → menu poziome</h2>
    <div class="container">
        <iframe src="layout2.html"></iframe>
    </div>

    <h2>Układ 3: Okno mniejsze na górze → menu poziome</h2>
    <div class="container">
        <iframe src="layout3.html"></iframe>
    </div>

</body>
</html>
