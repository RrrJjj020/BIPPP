<!DOCTYPE html>
<html>
<head>
  <title>Interaktif ANDA KAMU</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }
    p {
      cursor: pointer;
      margin: 5px 0;
      font-size: 18px;
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
  <!-- Bagian yang muncul setelah klik ANDA -->
  <div id="andaContent" class="hidden">
    <p onclick="toggleKamu()">KAMU</p>
    <!-- Bagian yang muncul setelah klik KAMU -->
    <div id="kamuContent" class="hidden">
      <a href="https://google.com" target="_blank" class="ya">YA</a>
      <br>
      <a href="https://google.com" target="_blank" class="ya">TIDAK</a>
    </div>
    </div>
    <p>SAYA</p>
  </div>
  <div style="width: 50%; margin: auto; text-align: center;">
    <p>&copy;2021 Ibip Sayangku. All rights reserved.</p>
  </div>
  <script>
    function toggleAnda() {
      const anda = document.getElementById("andaContent");
      anda.classList.toggle("hidden");
    }
    function toggleKamu() {
      const kamu = document.getElementById("kamuContent");
      kamu.classList.toggle("hidden");
    }
  </script>

</body>
</html>
