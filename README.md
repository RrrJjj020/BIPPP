<html>
<head>
  <title>Contoh Klik Sederhana</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
    }
    h1 {
      cursor: pointer;
      color: lightgreen;
    }
    h2 {
      cursor: pointer;
      color: lightred;
    }
    button {
      font-size: 18px;
      padding: 10px 20px;
      margin: 10px 0;
      cursor: pointer;
    }

    .pesan {
      display: none;
      margin: 10px 0;
      padding: 10px;
      border-left: 4px solid #007BFF;
      background-color: #f0f8ff;
      cursor: pointer;
      animation: fadeIn 0.5s ease-in-out;
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }
  </style>
</head>
<body>
  <h1 onclick="toggleCoba()">COBALAH</h1>
  <div id="okecontent" class="hidden">
    <p onclick="toggleCara()">MENGERTI</p>
    <p>SEMUA</p>
    <div id="yesresponse" class="hidden">
      <p><a href="https://example.com" class="link" target="_blank">INI</a></p>
      <p><a href="https://example.com" class="link" target="_blank">MENCARI ARTI</a></p>
    </div>
  </div>
  <script>
    function toggleCoba() {
      const content = document.getElementById("okecontent");
      const kamuResp = document.getElementById("yesresponse");
      if (content.classList.contains("hidden")) {
        content.classList.remove("hidden");
      } else {
        content.classList.add("hidden");
        kamuResp.classList.add("hidden");
      }
    }
    function toggleCara() {
      const kamuResp = document.getElementById("yesresponse");
      kamuResp.classList.toggle("hidden");
    }
  </script>
</body>
</html>
