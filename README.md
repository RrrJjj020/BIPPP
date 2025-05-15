<!DOCTYPE html>
<html>
<head>
  <title>Interaktif</title>
  <style>
    h1, p {
      cursor: pointer;
      font-family: Arial, sans-serif;
    }
    .hidden {
      display: none;
    }
    .link {
      color: blue;
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <h1 onclick="toggleAnda()">anda</h1>
  <div id="andacontent" class="hidden">
    <p onclick="toggleKamu()">kamu</p>
    <p>saya</p>
    <div id="kamuresponse" class="hidden">
      <p><a href="https://example.com" class="link" target="_blank">ya</a></p>
      <p><a href="https://example.com" class="link" target="_blank">tidak</a></p>
    </div>
  </div>
  <script>
    function toggleAnda() {
      const content = document.getElementById("andacontent");
      const kamuResp = document.getElementById("kamuresponse");
      if (content.classList.contains("hidden")) {
        content.classList.remove("hidden");
      } else {
        content.classList.add("hidden");
        kamuResp.classList.add("hidden");
      }
    }
    function toggleKamu() {
      const kamuResp = document.getElementById("kamuresponse");
      kamuResp.classList.toggle("hidden");
    }
  </script>
</body>
</html>
