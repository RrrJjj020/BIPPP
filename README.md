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
  <h1 onclick="toggle('pesan1')">Ibippkuu Sayang sama aku gak?</h1>
  <p id="pesan1" class="pesan" onclick="window.open('https://drive.google.com/file/d/1vqIRdmYWDaRfXFIDpYZdPcBPx_hHuhfu/view?usp=sharing', '_blank')">
    tuh kan sayang sama aku....heheheehehe 😘😘😘
  </p>
  <h2 onclick="toggle('pesan1')">Gak sayang lagi nih sama aku?</h2>
  <p id="pesan1" class="pesan" onclick="window.open('https://www.google.com/search?q=sayang+ibipp&rlz=1C1GCEU_enKH1161KH1161&oq=sayang+ibipp&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIHCAEQIRiPAjIHCAIQIRiPAtIBBjg3ajBqMagCALACAA&sourceid=chrome&ie=UTF-8', '_blank')">
    tuh kan sayang sama aku....heheheehehe 😘😘😘
  </p>
  <script>
    function toggle(id) {
      const el = document.getElementById(id);
      el.style.display = (el.style.display === "none") ? "block" : "none";
    }
  </script>
</body>
</html>
