<html>
<head>
  <title>Contoh Klik Kata</title>
  <script>
    function tampilkanKata() {
      document.getElementById("kata-lain").style.display = "block";
    }
  </script>
</head>
<body>

  <p onclick="tampilkanKata()" style="cursor: pointer; color: blue;">Klik di sini</p>
  <p id="kata-lain" style="display: none; color: green;">Ini kata yang muncul!</p>

</body>
</html>
