<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Withdrawal Status – SafePal</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f6f8;
      margin: 0;
      padding: 0;
      text-align: center;
      color: #333;
    }
    .container {
      max-width: 420px;
      margin: 12vh auto;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 2px 12px rgba(0, 0, 0, 0.08);
      padding: 30px;
    }
    img.logo {
      width: 120px;
      margin-bottom: 20px;
    }
    h1 {
      color: #0050ff;
      font-size: 20px;
    }
    .percent-box {
      margin: 20px auto;
      width: 100%;
      background: #e1e7f0;
      height: 20px;
      border-radius: 10px;
      overflow: hidden;
    }
    .percent-fill {
      height: 100%;
      width: 0%;
      background: linear-gradient(90deg, #0050ff, #00aaff);
      animation: fillBar 6s forwards;
    }
    @keyframes fillBar {
      0% { width: 0%; }
      100% { width: 100%; }
    }
    .msg {
      margin: 20px 0;
      font-size: 15px;
    }
    .note {
      font-size: 12px;
      color: #777;
    }
  </style>
</head>
<body>
  <div class="container">
    <img src="https://assets-global.website-files.com/623a5d89493b5c0a5518eb4d/6282341e7a4df9544c0597ae_safepal%20logo.png" alt="SafePal Logo" class="logo">
    <h1>Withdrawal Pending</h1>
    <div class="percent-box">
      <div class="percent-fill"></div>
    </div>
    <p class="msg">We're very sorry. Your withdrawal is currently pending due to a processing delay on your linked payment method.</p>
    <p class="note">Please ensure that all pending charges and verification steps are completed to avoid cancellation.</p>
  </div>
</body>
</html>