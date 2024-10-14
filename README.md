<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>twocowsong GitHub 프로필 이미지</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }
        .coding { font: bold 20px monospace; }
        .cow { font: bold 24px sans-serif; }
    </style>
</head>
<body>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 200" width="400" height="200">
        <!-- 배경 -->
        <rect width="100%" height="100%" fill="#f0f0f0"/>
        
        <!-- 코드 배경 -->
        <rect x="10" y="10" width="380" height="180" rx="10" ry="10" fill="#282c34"/>
        
        <!-- 코드 라인 -->
        <text x="30" y="40" fill="#61afef" class="coding">function twoCowSong() {</text>
        <text x="50" y="70" fill="#98c379" class="coding">console.log("Moo! Moo!");</text>
        <text x="50" y="100" fill="#98c379" class="coding">return "🎵 Two cows singing 🎵";</text>
        <text x="30" y="130" fill="#61afef" class="coding">}</text>
        
        <!-- 소 이모지와 텍스트 -->
        <text x="30" y="170" fill="#e06c75" class="cow">🐮🐮 twocowsong</text>
        
        <!-- 음표 -->
        <text x="340" y="50" fill="#c678dd" font-size="40">♪</text>
        <text x="360" y="90" fill="#c678dd" font-size="40">♫</text>
    </svg>
</body>
</html>
