<!DOCTYPE html><html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Puding Caramel Kampus</title>
  <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Fredoka', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fff7ec;
      color: #4b2e1d;
    }
    header {
      background-color: #ffb347;
      color: white;
      padding: 20px;
      text-align: center;
      border-bottom-left-radius: 30px;
      border-bottom-right-radius: 30px;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      background-color: #fff0d9;
      padding: 12px;
      border-bottom: 2px dashed #ffb347;
    }
    nav a {
      color: #d2691e;
      text-decoration: none;
      font-weight: 600;
      font-size: 16px;
    }
    .hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 40px 20px;
      text-align: center;
    }
    .hero img {
      width: 240px;
      border-radius: 20px;
      box-shadow: 0 5px 10px rgba(0,0,0,0.1);
    }
    .hero p {
      max-width: 450px;
      margin: 20px auto;
      font-size: 18px;
    }
    .btn {
      background-color: #ff914d;
      color: white;
      padding: 12px 24px;
      border: none;
      border-radius: 25px;
      text-decoration: none;
      font-size: 16px;
      margin-top: 10px;
    }
    section {
      padding: 40px 20px;
    }
    h2 {
      color: #d2691e;
      font-size: 24px;
      text-align: center;
    }
    footer {
      background-color: #ffe5b4;
      padding: 20px;
      text-align: center;
      color: #4b2e1d;
    }
    form textarea, form input {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #e0b27a;
      border-radius: 10px;
      font-size: 14px;
    }
    form button {
      background-color: #ff914d;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 20px;
      font-size: 15px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>Puding Caramel Kampus</h1>
  </header>  <nav>
    <a href="#beranda">Beranda</a>
    <a href="#produk">Produk</a>
    <a href="#kontak">Kontak</a>
    <a href="#saran">Saran</a>
  </nav>  <section class="hero" id="beranda">
    <img src="puding-image.jpg" alt="Puding Caramel">
    <p>Puding karamel terbuat dari susu full cream yang gurih dan manis. Cocok untuk mahasiswa yang suka dengan rasa manis!</p>
    <a class="btn" href="https://wa.me/6281234567890" target="_blank">Pesan via WhatsApp</a>
  </section>  <section id="produk">
    <h2>Produk</h2>
    <p style="text-align:center;">Puding karamel ukuran cup, cocok untuk camilan atau oleh-oleh. Bisa dipesan satuan atau dalam paket hemat.</p>
  </section>  <section id="kontak">
    <h2>Kontak</h2>
    <p style="text-align:center;">Hubungi kami melalui WhatsApp untuk informasi lebih lanjut:</p>
    <p style="text-align:center;"><a class="btn" href="https://wa.me/6289630546751" target="_blank">Chat Sekarang</a></p>
  </section>  <section id="saran">
    <h2>Berikan Saran</h2>
    <form action="#">
      <input type="text" placeholder="Nama Anda" required>
      <textarea rows="4" placeholder="Tulis saran atau pesan Anda..." required></textarea>
      <button type="submit">Kirim</button>
    </form>
  </section>  <footer>
    &copy; 2025 Puding Caramel Kampus
  </footer>
</body>
</html>
