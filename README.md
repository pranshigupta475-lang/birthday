<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Happy Birthday Bestie 🎉</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: 'Poppins', sans-serif;
    }

    body{
      height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      overflow:hidden;
    }

    .card{
      background:white;
      width:350px;
      padding:30px;
      border-radius:25px;
      text-align:center;
      box-shadow:0 10px 30px rgba(0,0,0,0.2);
      animation: pop 1s ease;
    }

    @keyframes pop{
      from{
        transform:scale(0.5);
        opacity:0;
      }
      to{
        transform:scale(1);
        opacity:1;
      }
    }

    h1{
      color:#ff4b7d;
      margin-bottom:15px;
      font-size:32px;
    }

    p{
      color:#555;
      font-size:18px;
      line-height:1.6;
      margin-bottom:20px;
    }

    .btn{
      display:inline-block;
      padding:12px 25px;
      background:#ff4b7d;
      color:white;
      text-decoration:none;
      border-radius:50px;
      transition:0.3s;
      font-weight:bold;
    }

    .btn:hover{
      background:#ff1f5a;
      transform:scale(1.05);
    }

    .emoji{
      font-size:50px;
      margin-bottom:15px;
      animation: float 2s infinite ease-in-out;
    }

    @keyframes float{
      0%,100%{
        transform:translateY(0);
      }
      50%{
        transform:translateY(-10px);
      }
    }

    .footer{
      margin-top:20px;
      color:#999;
      font-size:14px;
    }
  </style>
</head>

<body>

  <div class="card">
    <div class="emoji">🎂✨</div>

    <h1>Happy Birthday Bestie!</h1>

    <p>
      Wishing you endless happiness, crazy memories,
      lots of success, and all the love in the world 💖
    </p>

    <p>
      Thanks for always being my partner in crime 😎
    </p>

    <a href="#" class="btn">Enjoy Your Day 🎉</a>

    <div class="footer">
      Made with ❤️ for my best friend
    </div>
  </div>

</body>
</html># birthday
