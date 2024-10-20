<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Võ Bảo Ngọc</title>
    <style>
        body {
            background-color: white;
            text-align: center;
            font-family: Arial, sans-serif;
        }

        .centered-text {
            color: pink;
            font-size: 80px;
            font-weight: bold;
            margin-top: 20%;
        }

        .question {
            font-size: 24px;
            margin-top: 30px;
        }

        .button {
            font-size: 20px;
            padding: 10px 20px;
            margin: 10px;
            background-color: lightgray;
            border: none;
            cursor: pointer;
        }

        .button:hover {
            background-color: #dcdcdc;
        }
    </style>
</head>
<body>

    <div class="centered-text">NGỌC khùng</div>

    <div class="question">Võ Bảo Ngọc khùng thiệt không?</div>
    
    <button class="button" onclick="answer('Có')">Có</button>
    <button class="button" onclick="answer('Không')">Không</button>

    <script>
        function answer(response) {
            if (response === 'Có' || response === 'Không') {
                alert('Có');
            }
        }
    </script>

</body>
</html>
