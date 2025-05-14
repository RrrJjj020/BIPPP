<html>
<head>
  <title>Happy Aniversary</title>
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
  <p onclick="toggleKata()" style="cursor: pointer; color: blue;">Kalo Sayang Aku... klik ini ya</p>
  <p id="kata-lain" style="display: none;">
    <a href="https://drive.google.com/file/d/1vqIRdmYWDaRfXFIDpYZdPcBPx_hHuhfu/view?usp=sharing" target="_blank" style="color: blue;">beneran sayang kan? klik lagi ya</a>
  </p>
</body>
</html>
