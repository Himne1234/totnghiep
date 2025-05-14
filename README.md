<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Lễ Tốt Nghiệp - Lời Mời</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      overflow: hidden;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    #video-background {
      position: fixed;
      top: 0; left: 0;
      width: 100vw;
      height: 100vh;
      pointer-events: none;
      z-index: -1;
    }

    .content {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
      color: white;
      text-shadow: 2px 2px 8px black;
      animation: fadeInUp 2s ease-in-out;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 0.5em;
    }

    p {
      font-size: 1.5em;
      margin: 0.3em auto;
      max-width: 90%;
    }

    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translate(-50%, 30%);
      }
      to {
        opacity: 1;
        transform: translate(-50%, -50%);
      }
    }

    .overlay {
      position: fixed;
      top: 0; left: 0;
      width: 100vw;
      height: 100vh;
      background: rgba(0, 0, 0, 0.4);
      z-index: 0;
    }
  </style>
</head>
<body>
  <div id="video-background">
    <iframe width="100%" height="100%" src="https://www.youtube.com/embed/tIAosOycKTY?autoplay=1&mute=1&loop=1&playlist=tIAosOycKTY&controls=0&showinfo=0&rel=0&modestbranding=1"
      frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
  </div>

  <div class="overlay"></div>

  <div class="content">
    <h1>🎓 Lễ Tốt Nghiệp Khóa 24 🎓</h1>
    <p>Trân trọng kính mời những người thân đáng quý đến tham dự buổi lễ tốt nghiệp cùng mình!</p>
    <p>⏰ Thời gian: 9:30, ngày 24/05/2025</p>
    <p>📍 Địa điểm: Hội trường lớn D1 - Học viện Ngân Hàng</p>
    <p>📍 Liên hệ: 037.365.6918</p>
    <p>💌 Hãy đến và cùng lưu giữ những khoảnh khắc đáng nhớ nhé!</p>
  </div>
</body>
</html>
