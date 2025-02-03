
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的個人網頁</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- 導航欄 -->
    <nav>
        <ul>
            <li><a href="#about">關於我</a></li>
            <li><a href="#skills">技能</a></li>
            <li><a href="#portfolio">作品集</a></li>
            <li><a href="#contact">聯絡我</a></li>
        </ul>
    </nav>

    <!-- 個人簡介 -->
    <section id="about">
        <h1>關於我</h1>
        <p>你好！我是[你的名字]，我是一名[你的職業或興趣]，熱愛[你的興趣或專長]。</p>
    </section>

    <!-- 技能 -->
    <section id="skills">
        <h2>我的技能</h2>
        <ul>
            <li>HTML & CSS</li>
            <li>JavaScript</li>
            <li>UI/UX 設計</li>
        </ul>
    </section>

    <!-- 作品集 -->
    <section id="portfolio">
        <h2>作品集</h2>
        <div class="project">
            <h3>專案 1</h3>
            <p>這是我第一個專案的簡介。</p>
        </div>
        <div class="project">
            <h3>專案 2</h3>
            <p>這是我第二個專案的簡介。</p>
        </div>
    </section>

    <!-- 聯絡方式 -->
    <section id="contact">
        <h2>聯絡我</h2>
        <form action="submit_form.php" method="post">
            <label for="name">姓名：</label>
            <input type="text" id="name" name="name" required>
            <label for="email">電子郵件：</label>
            <input type="email" id="email" name="email" required>
            <label for="message">訊息：</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">送出</button>
        </form>
    </section>

    <!-- 頁尾 -->
    <footer>
        <p>&copy; 2023 [你的名字]. 保留所有權利。</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
