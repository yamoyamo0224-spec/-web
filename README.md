<html lang="ja">
<head>
<meta charset="UTF-8">
<title>やもweb!</title>
<link rel="icon" href="https://www.minecraft.net/ja-jp">

<style>

/* 背景・基本 */
body{
 margin:0;
 font-family:Arial, sans-serif;
 color:white;
 background-image:url('https://images.unsplash.com/photo-1447433819943-74a20887a81e?q=80&w=2070&auto=format&fit=crop');
 background-size:cover;
 background-attachment:fixed;

 padding-top:120px;   /* 上のメニュー分余白 */
}

/* ✅ 上部メニュー（目次） */
#toc {
  position:fixed;
  top:0;
  left:0;
  width:100%;

  background:rgba(0,0,0,0.6);
  padding:10px;
  text-align:center;

  backdrop-filter: blur(3px);
}

#toc ul {
  list-style:none;
  margin:0;
  padding:0;
}

#toc li {
  display:inline-block;
  margin:0 10px;
}

#toc a {
  color:#66ccff;
  text-decoration:none;
}

#toc a:hover {
  text-decoration:underline;
}

/* ✅ セクション（アニメーション） */
section {
    padding:20px;
    background:rgba(0,0,0,0.55);
    margin:10px;

    opacity:0;
    transform:translateX(-50px);

    animation:slidein 0.8s ease-out forwards;
}

@keyframes slidein {
    from {
        opacity:0;
        transform:translateX(-50px);
    }
    to {
        opacity:1;
        transform:translateX(0);
    }
}

h1{padding:20px;}

footer{
 padding:20px;
 background:rgba(0,0,0,0.55);
}

</style>
</head>
<body>

<h1>やもweb!</h1>

<!-- ✅ 上に目次 -->
<nav id="toc">
<ul>
 <li><a href="#intro">自己紹介</a></li>
 <li><a href="#fn">フォートナイト</a></li>
 <li><a href="#mc">マインクラフト</a></li>
</ul>
</nav>

<!-- ✅ 自己紹介 -->
<section id="intro">
<h2>自己紹介</h2>
<p>名前 : yam0oo</p>
<p>好きなゲーム :
<a href="https://www.fortnite.com/?lang=ja">フォートナイト</a>、
<a href="https://www.minecraft.net/ja-jp">マインクラフト</a>
</p>
</section>

<!-- ✅ フォートナイト -->
<section id="fn">
<h2>フォートナイト</h2>

<p>
フォートナイトは、2017年にリリースされたオンラインマルチプレイヤーゲームで、<br>
全世界で4億人以上の登録ユーザーを誇ります。<br>
プレイヤーは武器や資材を集めながら他プレイヤーと戦い、<br>
最後の一人（またはチーム）になることを目指すゲームです。
</p>

<p>
最近は <strong>ブレインロット</strong> をやっていて、<br>
総ドラゴン獲得数は<strong>10以上</strong>です🔥
</p>
</section>

<!-- ✅ マインクラフト -->
<section id="mc">
<h2>マインクラフト</h2>

<p>
Minecraft（マインクラフト）は、プレイヤーが自由にブロックを使って<br>
建築や探検を行うことができる3Dサンドボックスゲームです。
</p>

<p>
サーバーも作っています！！<br>
参加待っています😊
</p>
</section>

<footer>
<p>お問い合わせ： yamoyamo0224@gmail.com</p>
</footer>

</body>
</html>
