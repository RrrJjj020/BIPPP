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
      font-size: 35px;
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

    #kamuContent {
      text-align: center;
    }
  </style>
</head>
<body>
  <p onclick="toggleAnda()" style="text-align: center;">IBIPPP SAYANGGG</p>
  <!-- Konten setelah klik ANDA -->
  <div id="andaContent" class="hidden">
    <p onclick="toggleKamu()" style="text-align: center;">SAYANG BANGET SAMA AKU.....</p>
    
    <div id="kamuContent" class="hidden">
      <a href="https://drive.google.com/file/d/1vqIRdmYWDaRfXFIDpYZdPcBPx_hHuhfu/view?usp=sharing" target="_blank" class="ya" style="display: block; text-align: center;">YA</a>
      <br>
      <a href="https://contoh-tidak-baik-tidak-sayang-pacar/suami.com" target="_blank" class="tidak" style="display: block; text-align: center;">TIDAK</a>
    </div>
    
    <p onclick="errorSaya()" style="text-align: center;">Cukup Sayang</p>
  </div>
  <div style="width: 50%; margin: auto; text-align: center;">
    <p>&copy;2021 Ibippp Sayangkuu. All for Ibippp.</p>
  </div>
  <script>
    function toggleAnda() {
      document.getElementById("andaContent").classList.toggle("hidden");
    }
    function toggleKamu() {
      document.getElementById("kamuContent").classList.toggle("hidden");
    }
    function errorSaya() {
      alert("❌ Terjadi Error! Ibip tidak boleh klik Cukup Sayang.");
    }
  </script>
</body>
</html>
