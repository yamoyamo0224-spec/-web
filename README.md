<html lang="ja">
<head>
<meta charset="UTF-8">
<title>やもweb!</title>
<link rel="icon" href="https://www.minecraft.net/ja-jp">

<style>

/* 背景 */
body{
 margin:0;
 font-family:Arial, sans-serif;
 color:white;
 background-image:url('https://images.unsplash.com/photo-1447433819943-74a20887a81e?q=80&w=2070&auto=format&fit=crop');
 background-size:cover;
 background-attachment:fixed;

 padding-top:260px; 
}

/* Discordスタッツ */
#discord {
 position:fixed;
 top:0;
 left:0;
 width:100%;
 text-align:center;

 background:rgba(0,0,0,0.55);
 padding:10px;

 z-index:9999;
}

/* メニュー */
#toc {
 position:fixed;
 top:120px;
 left:0;
 width:100%;
 text-align:center;

 background:rgba(0,0,0,0.6);
 padding:10px;

 z-index:9999;
}

#toc a{
 color:#66ccff;
 margin:0 10px;
 text-decoration:none;
}

#toc a:hover{ text-decoration:underline; }

/* セクション */
section {
 padding:30px;
 background:rgba(0,0,0,0.55);
 margin:40px;

 opacity:0;
 transform:translateX(-40px);

 animation:fade 0.7s forwards;

 scroll-margin-top:170px; 
}

@keyframes fade {
 to{ opacity:1; transform:translateX(0); }
}

footer{
 background:rgba(0,0,0,0.55);
 padding:20px;
}

</style>
</head>
<body>

<h1>やもweb!</h1>

<!-- Discord -->
<div id="discord">
<h2>🎮 Discordスタッツ</h2>
<img src="https://discordstatus.com/api/v1/users/1096056322346197103.png" style="max-width:240px;">
</div>

<!-- メニュー -->
<nav id="toc">
<a href="#intro">👤 自己紹介</a>
<a href="#fn">🔥 フォートナイト</a>
<a href="#mc">⛏️ マインクラフト</a>
<a href="#discord">🎮 スタッツ</a>
<a href="#contact">📩 お問い合わせ</a>
</nav>

<!-- 自己紹介 -->
<section id="intro">
<h2>自己紹介</h2>
<p>名前 : yam0oo</p>
<p>
好きなゲーム :
<a href="https://www.fortnite.com/?lang=ja">フォートナイト</a>、
<a href="https://www.minecraft.net/ja-jp">マインクラフト</a>
</p>
</section>

<!-- フォートナイト -->
<section id="fn">
<h2>フォートナイト</h2>
<p>
フォートナイトは2017年発売のオンラインバトルロイヤルゲームです。
</p>
<p>
ブレインロットやってて<br>
総ドラゴン獲得数は10以上🔥
</p>
</section>

<!-- マインクラフト -->
<section id="mc">
<h2>マインクラフト</h2>
<p>
ブロックを使って建築できる自由度最高ゲーム！
</p>
<p>
サーバーも作っています😊
</p>
</section>

<!-- お問い合わせ -->
<footer id="contact">
📩 お問い合わせ : yamoyamo0224@gmail.com
</footer>

</body>
</html>
