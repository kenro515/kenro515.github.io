<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Pages 動的ページ</title>
</head>
<body>
    <h1>天気情報</h1>
    <p id="weather"></p>

    <script>
        fetch('https://api.open-meteo.com/v1/forecast?latitude=35.6895&longitude=139.6917&current_weather=true')
            .then(response => response.json())
            .then(data => {
                document.getElementById('weather').textContent = `東京の気温: ${data.current_weather.temperature}°C`;
            })
            .catch(error => console.error('エラー:', error));
    </script>

</body>
</html>
