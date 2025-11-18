# osnovall 
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>OSNOVALL — Personal Hub</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
<style>
  :root{
    --bg:#000;
    --card:#0f0f0f;
    --muted: rgba(255,255,255,0.85);
    --accent:#0088CC;
  }
  *{box-sizing:border-box}
  body{
    margin:0;
    font-family:'Inter',system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;
    background:var(--bg);
    color:#fff;
    -webkit-font-smoothing:antialiased;
    -moz-osx-font-smoothing:grayscale;
    text-align:center;
  }
  header{
    padding:72px 20px 36px;
  }
  header img{
    width:92px;
    height:92px;
    opacity:.95;
    transition:transform .28s ease,opacity .28s ease;
  }
  header img:hover{ transform:translateY(-4px) scale(1.03); opacity:1; }
  header h1{
    margin:18px 0 0;
    font-size:2.2rem;
    font-weight:600;
    letter-spacing:.6px;
  }
  .container{
    max-width:820px;
    margin:0 auto;
    padding:22px;
  }
  h2{
    margin:42px 0 12px;
    font-size:1.15rem;
    font-weight:600;
  }
  p{ color:var(--muted); font-size:1rem; margin:0 auto; max-width:680px; line-height:1.5; }
  ul{ list-style:none; padding:0; margin:18px 0 0; }
  li{
    background:var(--card);
    border-radius:12px;
    padding:14px 18px;
    margin:12px 16px;
    transition:transform .28s ease, background .28s ease, box-shadow .28s ease;
    cursor:pointer;
    display:block;
    font-size:1rem;
    text-align:left;
  }
  li:hover{
    transform:translateY(-6px);
    background:#1a1a1a;
    box-shadow:0 8px 24px rgba(0,0,0,0.6);
  }
  li .name{ margin-left:8px; vertical-align:middle; color:#fff; }
  .list-wrap{ display:block; margin:0 auto; max-width:720px; }
  footer{ margin-top:46px; padding:18px 20px 60px; }
  .tg-btn{
    display:inline-block;
    background:var(--accent);
    color:#fff;
    padding:14px 26px;
    border-radius:999px;
    text-decoration:none;
    font-weight:600;
    box-shadow:0 6px 18px rgba(0,136,204,0.18);
    transition:transform .22s ease, box-shadow .22s ease, background .22s ease;
  }
  .tg-btn:hover{ transform:translateY(-4px); box-shadow:0 12px 28px rgba(0,136,204,0.20); background:#00a6ff; }
  @media (max-width:640px){
    header{ padding:48px 16px 24px; }
    header h1{ font-size:1.6rem; }
    li{ margin:10px 10px; padding:12px; border-radius:10px; }
    .container{ padding:16px; }
  }
</style>
</head>
<body>
<header>
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/3b/Ghost_icon.svg" alt="OSNOVALL Logo">
  <h1>OSNOVALL</h1>
</header>

<main class="container">
  <h2>Обо Мне</h2>
  <p>Развиваю каналы, делюсь сигналами и участвую в проектах. Люблю технологии, креатив и новые идеи.</p>

  <h2>Мои каналы и проекты</h2>
  <div class="list-wrap">
    <ul>
      <li onclick="window.open('https://ygodiacheze.t.me','_blank')">
        <span class="name">YGODIACHEZE — Telegram</span>
      </li>
      <li onclick="window.open('https://NEWCOMENTS.t.me','_blank')">
        <span class="name">NEWCOMENTS — Telegram</span>
      </li>
      <li onclick="window.open('https://blackprojecttt.t.me','_blank')">
        <span class="name">BLACK PROJECT — Telegram</span>
      </li>
      <li onclick="window.open('https://t.me/+W_gXoTTcn59hMjJl','_blank')">
        <span class="name">Private Channel — Telegram</span>
      </li>
      <li onclick="window.open('https://adapterofcounter.t.me','_blank')">
        <span class="name">Adapter of Counter — Telegram</span>
      </li>
    </ul>
  </div>

  <h2>Сигналы</h2>
  <div class="list-wrap">
    <ul>
      <li onclick="window.open('https://signicheze.t.me','_blank')">
        <span class="name">SIGNICHEZE — Telegram</span>
      </li>
    </ul>
  </div>
</main>

<footer>
  <a class="tg-btn" href="https://t.me/osnovall" target="_blank" rel="noopener noreferrer">Написать в Telegram</a>
</footer>

</body>
</html>
