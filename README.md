<!DOCTYPE html>
<html>
<head>
  <title>ANDA & KAMU</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }
    h1 {
      cursor: pointer;
      color: DeepSkyBlue;
      margin: 5px 0;
    p {
      cursor: pointer;
      color: LightSlateGray;
      margin: 5px 0;
    }
    .hidden {
      display: none;
    }
    .ya {
      color: green;
      font-weight: bold;
    }
    .tidak {
      color: red;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <h1 onclick="toggleAnda()">ANDA</h1>
  <div id="andaContent" class="hidden">
    <p onclick="toggleKamu()">KAMU</p>
    <div id="kamuContent" class="hidden">
      <p>YA</p>
      <p>TIDAK</p>
    </div>
    <p>SAYA</p>
  </div>
  <script>
    function toggleAnda() {
      const andaContent = document.getElementById("andaContent");
      andaContent.classList.toggle("hidden");
    }
    function toggleKamu() {
      const kamuContent = document.getElementById("kamuContent");
      kamuContent.classList.toggle("hidden");
    }
  </script>
</body>
</html>
