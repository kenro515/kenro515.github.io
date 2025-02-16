<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Demo site</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        /* navigation bar */
        .navbar {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 10px 0;
        }

        .navbar a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            font-size: 18px;
        }

        .navbar a:hover {
            background-color: #575757;
        }

        /* image setup */
        .header-image {
            width: 100%;
            height: auto;
        }

        /* content setup */
        .content {
            padding: 20px;
            text-align: center;
        }
    </style>

</head>
<body>

    <!-- image -->
    <img src="header.jpg" alt="コンペサイトのヘッダー画像" class="header-image">

    <!-- navigation bar -->
    <div class="navbar">
        <a href="index.html">Home</a>
        <a href="data.md">Data</a>
        <a href="results.md">Results</a>
    </div>

    <!-- content area -->
    <div class="content">
        <h1>天気予測コンペサイトへようこそ！</h1>
        <p>ここではデータを分析し、結果を競い合うことができます。</p>
    </div>

</body>
</html>
