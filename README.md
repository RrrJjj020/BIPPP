<!DOCTYPE html>
<html>
<head>
  <title>ANDA & KAMU</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }
    p {
      cursor: pointer;
      margin: 5px 0;
    }
    .hidden {
      display: none;
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
