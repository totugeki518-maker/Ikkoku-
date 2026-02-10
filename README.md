<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Photo Viewer</title>
    <style>
        /* スマホで見やすくするためのデザイン */
        body {
            margin: 0;
            padding: 20px;
            background-color: #1a1a1a; /* 背景を暗くして写真を引き立てる */
            color: white;
            font-family: sans-serif;
            text-align: center;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
        }
        img {
            width: 100%;       /* 横幅いっぱいに表示 */
            height: auto;      /* 比率を維持 */
            border-radius: 8px; /* 角を少し丸く */
            box-shadow: 0 4px 15px rgba(0,0,0,0.5); /* 影をつけて立体感を出す */
        }
        h1 { font-size: 1.2rem; margin-bottom: 20px; }
        p { font-size: 0.9rem; color: #ccc; margin-top: 15px; }
    </style>
</head>
<body>

<div class="container">
    <h1></h1>
    
    <img src="photo.png" alt="オリジナルの写真">
    
    <p>2026.02.10 Record</p>
</div>

</body>
</html>
