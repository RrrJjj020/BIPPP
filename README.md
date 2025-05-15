<html>
<head>
  <title>Interaktif ANDA KAMU</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }
    p, a {
      cursor: pointer;
      margin: 5px 0;
      font-size: 18px;
      text-decoration: none;
    }
    .hidden {
      display: none;
    }
    .ya {
      cursor: pointer;
      color: green;
      font-weight: bold;
    }
    .tidak {
      cursor: not-allowed;
      color: red;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <!-- Menu utama -->
  <p onclick="toggleAnda()">ANDA</p>
  <!-- Konten setelah klik ANDA -->
  <div id="andaContent" class="hidden">
    <p onclick="toggleKamu()">KAMU</p>
    <!-- Konten setelah klik KAMU -->
    <div id="kamuContent" class="hidden">
      <a href="https://google.com" target="_blank" class="ya">YA</a>
      <br>
      <a href="https://contoh-link-tidak.com" target="_blank" class="tidak">TIDAK</a>
    </div>
    <p>SAYA</p>
  </div>
  <div style="width: 50%; margin: auto; text-align: center;">
    <p>&copy;2021 Ibippp Sayangkuu. All rights reserved.</p>
  </div>
  <script>
    function toggleAnda() {
      document.getElementById("andaContent").classList.toggle("hidden");
    }
    function toggleKamu() {
      document.getElementById("kamuContent").classList.toggle("hidden");
    }
  </script>
</body>
</html>
