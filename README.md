<!DOCTYPE html>
<html>
<head>
  <title>ANDA & KAMU</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }
    h1 {
      curdor: pointer;
      color: Tomato;
    p {
      cursor: pointer;
      color: LightGreen;
      margin: 5px 0;
    }
    .hidden {
      display: none;
    }
  </style>
</head>
<body>
  <h1 onclick="toggleSayang()">SAYANG IBIPPP</h1>
  <div id="sayangContent" class="hidden">
    <p onclick="toggleIbippp()">IBIP SAYANG AKU?</p>
    <div id="ibipppContent" class="hidden">
      <p>YA</p>
      <p>TIDAK</p>
    </div>
    <p>SAYA</p>
  </div>
  <script>
    function toggleSayang() {
      const andaContent = document.getElementById("sayangContent");
      andaContent.classList.toggle("hidden");
    }
    function toggleIbippp() {
      const kamuContent = document.getElementById("ibipppContent");
      kamuContent.classList.toggle("hidden");
    }
  </script>
</body>
</html>
