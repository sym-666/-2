<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>首页</title>
  <style>
    
    body {
      margin: 0;
      padding: 0;
      font-family:"宋体",Arial,sans-serif;
    }

    header {
      background-color: #333;
      color: white;
      padding: 10px;
      text-align: center;
		
    }

    nav button {
      background-color: transparent;
      color: white;
      border: none;
      padding: 10px 20px;
      margin: 0 10px;
      cursor: pointer;
      font-size: 16px;
      transition: all 0.3s ease; 
		font-family:"宋体",Arial,sans-serif;
    }

    
    nav button:hover {
      background-color: #555;
      transform: scale(1.15); 
    }

    
    nav button:active {
      background-color: #777;
    }

  
    video {
      position: absolute;
      right: 0;
      bottom: 0;
      min-width: 100%;
      min-height: 100%;
      width: auto;
      height: auto;
      z-index: -1;
    }

  
    main {
      padding: 20px;
      color: white;
      position: relative;
      z-index: 1;
      overflow-y: scroll;
      height: 80vh;
		width: 100%;
		margin:auto;
    }nav a {
            color: white;
            text-decoration: none;
            padding: 0px 0px;
            display: inline-block;
        }
	
 
  </style>
</head>

<body>

<header>
 <nav>
     <button><a href="index.html">首页</a></button>
	  <button><a href="新海诚.html">作者介绍</a></button>
      <button><a href="你的名字最新.html">《你的名字》</a></button>
      <button><a href="最新天气之子.html">《天气之子》</a></button>
      <button><a href="铃芽之旅.html">《铃芽之旅》</a></button>
	<button><a href="https://dklsoul.github.io/216/">返回寝室主页</a></button>
  </nav>
</header>
<video autoplay muted loop id="video-background">
  <source src="0003.mp4" type="video/mp4">
  
  </video>
  <main class="main1">
    <h1>欢迎来到我的网站</h1>
    <p>接下来我将向你们介绍著名的动画导演和编剧新海诚和他著名的三个电影</p>
  </main>
</body>

</html>
