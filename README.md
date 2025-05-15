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

    #gambarSayang {
      display: none;
      margin-top: 10px;
      max-width: 100%;
    }
    .container {
      width: 50%;
      margin: auto;
      text-align: center;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <p onclick="toggleAnda()" style="text-align: center;">IBIPPP SAYANGGG</p>
  <!-- Konten setelah klik ANDA -->
  <div id="andaContent" class="hidden">
    <p onclick="toggleKamu()" style="text-align: center;">SAYANG BANGET SAMA AKU.....</p>
    
    <div id="kamuContent" class="hidden">
      <a href="https://drive.google.com/file/d/1vqIRdmYWDaRfXFIDpYZdPcBPx_hHuhfu/view?usp=sharing" target="_blank" class="ya">YA</a>
      <br>
      <a href="https://contoh-tidak-baik-tidak-sayang-pacar/suami.com" target="_blank" class="tidak">TIDAK</a>
    </div>
    
    <p onclick="errorSaya()" style="text-align: center;">Cukup Sayang</p>
  </div>
  <div class="container" onclick="tampilkanGambar()">
    <p>&copy;2021 Ibippp Sayangkuu. All for Ibippp.</p>
    <img id="Sayang.jpg" src="https://via.placeholder.com/300x200.png?text=Ibippp+Image" alt="Gambar Ibippp">
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
    function tampilkanGambar() {
      const gambar = document.getElementById("gambarSayang");
      // Toggle: jika hidden maka tampil, jika tampil maka sembunyi
      if (gambar.style.display === "none") {
        gambar.style.display = "block";
      } else {
        gambar.style.display = "none";
      }
    }
  </script>
</body>
</html>
