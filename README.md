<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Giới thiệu App</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f6f9;
      color: #333;
    }
    header {
      background: linear-gradient(135deg, #4a90e2, #357abd);
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    header p {
      margin: 10px 0 20px;
      font-size: 1.2rem;
    }
    .btn-download {
      display: inline-block;
      padding: 12px 24px;
      background: #ff9800;
      color: white;
      text-decoration: none;
      font-size: 1.1rem;
      border-radius: 8px;
      transition: 0.3s;
    }
    .btn-download:hover {
      background: #e68900;
    }
    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      text-align: center;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #222;
      color: white;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Racine TV</h1>
    <p>Ứng dụng xem tv ,phim ,thể thao</p>
    <a href="link-to-your-app.apk" class="btn-download">Tải ứng dụng</a>
  </header>

  <section>
    <h2>Tính năng nổi bật</h2>
    <div class="features">
      <div class="card">
        <h3>IPTV</h3>
        <p>Xem hơn nghìn kênh trong nước và quốc tế</p>
      </div>
      <div class="card">
        <h3>EPG</h3>
        <p>Lịch phát sóng</p>
      </div>
      <div class="card">
        <h3>Mobile và SmartTV</h3>
        <p>Android và Android TV</p>
      </div>
    </div>
  </section>

  <footer>
    <p>racinetv.app@gmail.com.</p>
  </footer>

</body>
</html>
