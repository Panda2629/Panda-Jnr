<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Join Our WhatsApp Channel</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: white;
      text-align: center;
    }

    /* Top Join Tab */
    .top-tab {
      background: #25D366;
      color: white;
      padding: 15px;
      font-size: 18px;
      text-decoration: none;
      display: block;
      font-weight: bold;
    }

    /* Main Card */
    .card {
      max-width: 430px;
      background: #ffffff;
      margin: 40px auto;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.1);
    }

    .logo {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      margin-bottom: 20px;
    }

    .join-btn {
      background: #25D366;
      color: white;
      padding: 15px 25px;
      font-size: 20px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      width: 100%;
      margin-top: 20px;
    }

    .join-btn:hover {
      opacity: 0.9;
    }

    .qr-box img {
      margin-top: 15px;
      width: 180px;
      height: 180px;
    }

    footer {
      margin-top: 40px;
      padding: 15px;
      color: #666;
      font-size: 14px;
    }
  </style>
</head>

<body>

  <!-- Top Join Tab -->
  <a class="top-tab" href="https://chat.whatsapp.com/Loep9UtliNbGl1NQxXSMLk" target="_blank">
    Join WhatsApp Channel
  </a>

  <!-- Main Card -->
  <div class="card">
    <img class="logo" src="https://via.placeholder.com/100" alt="Channel Logo">

    <h2>Join Our WhatsApp Channel</h2>
    <p>
      Stay updated with announcements, events, news, and important updates.
      Tap the button below or scan the QR code to join instantly.
    </p>

    <!-- JOIN BUTTON -->
    <a href="https://chat.whatsapp.com/Loep9UtliNbGl1NQxXSMLk" target="_blank">
      <button class="join-btn">Join Now</button>
    </a>

    <!-- QR Code -->
    <div class="qr-box">
      <h3>Scan to Join</h3>
      <img id="qrCode" src="" alt="QR Code">
    </div>
  </div>

  <footer>
    © 2025 Your Brand — All Rights Reserved
  </footer>

  <!-- Script to Auto-Generate QR -->
  <script>
    const link = "https://chat.whatsapp.com/Loep9UtliNbGl1NQxXSMLk";
    const qrUrl = "https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=" + encodeURIComponent(link);
    document.getElementById("qrCode").src = qrUrl;
  </script>

</body>
</html>
