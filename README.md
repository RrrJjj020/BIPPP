<html>
<head>
  <title>Contoh Toggle Kata</title>
  <script>
    function toggleKata() {
      const kata = document.getElementById("kata-lain");
      if (kata.style.display === "none") {
        kata.style.display = "block";
      } else {
        kata.style.display = "none";
      }
    }
  </script>
</head>
<body>
  <p onclick="toggleKata()" style="cursor: pointer; color: blue;">Klik di sini</p>
  <p id="kata-lain" style="display: none; color: green;">Ini kata yang muncul!</p>
</body>
</html>
