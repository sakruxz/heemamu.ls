@@ -0,0 +1,184 @@
<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>roblox.com</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #1e1e1e;
            color: white;
        }
        header {
            background: #2c2c2c;
            padding: 20px;
            text-align: center;
        }
        nav {
            margin: 20px 0;
            display: flex;
            flex-direction: column;
            align-items: flex-start; /* จัดแนวซ้าย */
            padding-left: 20px; /* เว้นระยะทางซ้าย */
        }
        nav a {
            margin: 5px 0; /* เพิ่มช่องว่างระหว่างลิงก์ */
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }
        .friends {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 10px;
        }
        .friend {
            width: 80px;
            text-align: center;
        }
        .friend img {
            width: 100%;
            border-radius: 50%;
        }
        .recommended {
            padding: 20px;
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 10px;
        }
        .game {
            background: #3f3f3f;
            padding: 10px;
            border-radius: 5px;
            text-align: center;
        }
        .game img {
            width: 100%;
            border-radius: 5px;
        }
        .chat-container {
            padding: 20px;
            max-width: 500px;
            margin: 20px auto;
            background: #3f3f3f;
            border-radius: 5px;
            height: 300px;
            overflow-y: auto;
        }
        .chat-message {
            display: flex;
            align-items: center;
            margin: 10px 0;
        }
        .chat-message img {
            width: 40px;
            border-radius: 50%;
            margin-right: 10px;
        }
        .message-content {
            background: #2c2c2c;
            padding: 10px;
            border-radius: 5px;
            max-width: 80%;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #2c2c2c;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Roblox ของจริงเสียตัง</h1>
    <nav>
        <a href="#">Profile</a>
        <a href="#">Inventory</a>
        <a href="#">Trade</a>
        <a href="#">Marketplace</a>
    </nav>
</header>

<section>
    <h2>Friends (5)</h2>
    <div class="friends">
        <div class="friend">
            <img src="https://tr.rbxcdn.com/30DAY-AvatarHeadshot-AE689409A32E22C72F487AA8FF60D87E-Png/150/150/AvatarHeadshot/Webp/noFilter" alt="Friend 1">
            <p>Friend 1</p>
        </div>
        <div class="friend">
            <img src="https://tr.rbxcdn.com/30DAY-AvatarHeadshot-FE364F336376438E0EB13D4B44A3F4D7-Png/150/150/AvatarHeadshot/Webp/noFilter" alt="Friend 2">
            <p>Friend 2</p>
        </div>
        <div class="friend">
            <img src="https://tr.rbxcdn.com/30DAY-AvatarHeadshot-5CC20B06AD956B5196DE29F0648A66F4-Png/150/150/AvatarHeadshot/Webp/noFilter" alt="Friend 3">
            <p>Friend 3</p>
        </div>
        <div class="friend">
            <img src="https://tr.rbxcdn.com/30DAY-AvatarHeadshot-214FD5FBA41AE6836785604C80EECA3F-Png/150/150/AvatarHeadshot/Webp/noFilter" alt="Friend 4">
            <p>Friend 4</p>
        </div>
        <div class="friend">
            <img src="https://tr.rbxcdn.com/30DAY-AvatarHeadshot-CC797A2168ACFDD3C2D4CF3B2A4C8A36-Png/150/150/AvatarHeadshot/Webp/noFilter" alt="Friend 5">
            <p>Friend 5</p>
        </div>
    </div>
</section>

<section>
    <h2>Recommended For You</h2>
    <div class="recommended">
        <div class="game">
            <img src="https://tr.rbxcdn.com/aab22b72304b17e19b0b868fde1d7094/256/256/Image/Webp" alt="Recommended Game 1">
            <p>[NEW LEADERBOARD AND CASE...]</p>
            <p>90% Rating</p>
        </div>
        <div class="game">
            <img src="https://tr.rbxcdn.com/344d8ec5c5153c97a0c8e45f9d7d00cd/256/256/Image/Webp" alt="Recommended Game 2">
            <p>Catalog Avatar Creator Test</p>
            <p>87% Rating</p>
        </div>
        <!-- เพิ่มเกมอื่น ๆ ที่นี่ -->
    </div>
</section>

<section>
    <h2>Chat</h2>
    <div class="chat-container">
        <div class="chat-message">
            <img src="https://tr.rbxcdn.com/30DAY-AvatarHeadshot-AE689409A32E22C72F487AA8FF60D87E-Png/150/150/AvatarHeadshot/Webp/noFilter" alt="Friend 1">
            <div class="message-content">สวัสดีเพื่อน!</div>
        </div>
        <div class="chat-message">
            <img src="https://tr.rbxcdn.com/30DAY-AvatarHeadshot-FE364F336376438E0EB13D4B44A3F4D7-Png/150/150/AvatarHeadshot/Webp/noFilter" alt="Friend 2">
            <div class="message-content">สวัสดี! คุณทำอะไรอยู่?</div>
        </div>
        <div class="chat-message">
            <img src="https://tr.rbxcdn.com/30DAY-AvatarHeadshot-5CC20B06AD956B5196DE29F0648A66F4-Png/150/150/AvatarHeadshot/Webp/noFilter" alt="Friend 3">
            <div class="message-content">เล่นเกมอยู่ครับ!</div>
        </div>
        <div class="chat-message">
            <img src="https://tr.rbxcdn.com/30DAY-AvatarHeadshot-214FD5FBA41AE6836785604C80EECA3F-Png/150/150/AvatarHeadshot/Webp/noFilter" alt="Friend 4">
            <div class="message-content">เยี่ยมเลย! จะเล่นด้วยไหม?</div>
        </div>
        <div class="chat-message">
            <img src="https://tr.rbxcdn.com/30DAY-AvatarHeadshot-CC797A2168ACFDD3C2D4CF3B2A4C8A36-Png/150/150/AvatarHeadshot/Webp/noFilter" alt="Friend 5">
            <div class="message-content">แน่นอน! รออยู่เลย!</div>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2024 Roblox ของจริงเสียตัง</p>
</footer>


</body>
</html>
