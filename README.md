<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>個人網站</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f5f5f5;
      color: #333;
    }

    header {
      background-color: #222;
      color: white;
      padding: 60px 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
    }

    header p {
      font-size: 1.2em;
      color: #ccc;
    }

    section {
      padding: 60px 20px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      border-left: 5px solid #0077cc;
      padding-left: 15px;
      margin-bottom: 20px;
    }

    .skills, .contact {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
    }

    .skill-item, .contact-item {
      background: #fff;
      padding: 15px 20px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      flex: 1 1 200px;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
    }

    .project-card {
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      padding: 15px;
    }

    .project-card h3 {
      margin-top: 0;
    }

    footer {
      text-align: center;
      padding: 40px 20px;
      background: #eee;
      color: #777;
    }

    a {
      color: #0077cc;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <header>
    <h1>你的名字</h1>
    <p>這裡是一句簡短的自我介紹或座右銘</p>
  </header>

  <section>
    <h2>關於我</h2>
    <p>這裡可以寫一段自我介紹，描述你的背景、專業領域、興趣、目標等等。</p>
  </section>

  <section>
    <h2>技能</h2>
    <div class="skills">
      <div class="skill-item">HTML / CSS</div>
      <div class="skill-item">JavaScript</div>
      <div class="skill-item">Python</div>
      <div class="skill-item">UI/UX 設計</div>
      <div class="skill-item">影像處理</div>
    </div>
  </section>

  <section>
    <h2>作品集</h2>
    <div class="projects">
      <div class="project-card">
        <h3>作品名稱 1</h3>
        <p>這是第一個作品的簡介，可以放連結或描述使用的技術。</p>
      </div>
      <div class="project-card">
        <h3>作品名稱 2</h3>
        <p>第二個作品的說明文字。</p>
      </div>
      <div class="project-card">
        <h3>作品名稱 3</h3>
        <p>第三個作品的相關介紹。</p>
      </div>
    </div>
  </section>

  <section>
    <h2>聯絡方式</h2>
    <div class="contact">
      <div class="contact-item">Email: yourname@example.com</div>
      <div class="contact-item"><a href="https://linkedin.com" target="_blank">LinkedIn</a></div>
      <div class="contact-item"><a href="https://github.com" target="_blank">GitHub</a></div>
      <div class="contact-item"><a href="https://instagram.com" target="_blank">Instagram</a></div>
    </div>
  </section>

  <footer>
    &copy; 2025 你的名字 | All rights reserved.
  </footer>

</body>
</html>
