<!DOCTYPE html>
<html>
<head>
    <title>生日快乐！🎂</title>
    <style>
        body {
            background: linear-gradient(45deg, #ff6b6b, #ff9f43);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: 'Comic Sans MS', cursive;
        }

        .card {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 0 20px rgba(0,0,0,0.2);
            text-align: center;
            max-width: 500px;
        }

        h1 {
            color: #e74c3c;
            font-size: 2.5em;
            margin-bottom: 1rem;
        }

        .balloons {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin: 2rem 0;
        }

        .balloon {
            width: 60px;
            height: 80px;
            background: #ff9ff3;
            border-radius: 50%;
            animation: float 3s ease-in-out infinite;
        }

        .cake {
            font-size: 4em;
            cursor: pointer;
            transition: transform 0.3s;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }

        .message {
            font-size: 1.2em;
            line-height: 1.5;
            color: #2c3e50;
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="balloons">
            <div class="balloon" style="background: #ff9ff3"></div>
            <div class="balloon" style="background: #feca57"></div>
            <div class="balloon" style="background: #54a0ff"></div>
        </div>
        <h1>🎉 生日快乐！ 🎉</h1>
        <div class="message">
            <p>愿你的每一天都充满阳光与欢笑，</p>
            <p>所有愿望都能成真！</p>
            <p>❤️ 来自关心你的人 ❤️</p>
        </div>
        <div class="cake" onclick="playMusic()">🎂</div>
    </div>

    <script>
        function playMusic() {
            const audio = new Audio('https://assets.mixkit.co/active_storage/sfx/2862/2862-preview.mp3');
            audio.play();
            document.querySelector('.cake').style.transform = 'scale(1.2)';
            setTimeout(() => {
                document.querySelector('.cake').style.transform = 'scale(1)';
            }, 300);
        }

        // 添加随机气球动画
        document.querySelectorAll('.balloon').forEach(balloon => {
            balloon.style.animationDelay = Math.random() * 2 + 's';
        });
    </script>
</body>
</html>
