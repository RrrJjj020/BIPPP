<html>
<head>
  <title>Contoh Toggle</title>
  <script>
    function togglePesan() {
      const pesan = document.getElementById('pesan');
      if (pesan.style.display === 'none') {
        pesan.style.display = 'block';
      } else {
        pesan.style.display = 'none';
      }
    }
  </script>
</head>
<body>
  <button onclick="togglePesan()">Klik Saya</button>
  <p id="pesan" style="display: none;">Halo! Ini pesan tersembunyi.</p>
</body>
</html>
