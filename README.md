# <!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>أسعار الذهب اليوم</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<div class="gold-box">
  <h1>أسعار الذهب اليوم</h1>

  <div class="card">
    <span>عيار 24</span>
    <strong id="g24">--</strong>
  </div>

  <div class="card">
    <span>عيار 21</span>
    <strong id="g21">--</strong>
  </div>

  <div class="card">
    <span>عيار 18</span>
    <strong id="g18">--</strong>
  </div>

  <p class="time" id="time"></p>
</div>

<script src="script.js"></script>
</body>
</html>
body {
  font-family: Tahoma;
  background: #111;
  color: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.gold-box {
  background: #1c1c1c;
  padding: 30px;
  border-radius: 12px;
  width: 320px;
  text-align: center;
}

h1 {
  color: gold;
  margin-bottom: 20px;
}

.card {
  background: #000;
  padding: 15px;
  margin: 10px 0;
  border-radius: 8px;
  display: flex;
  justify-content: space-between;
  font-size: 18px;
}

strong {
  color: gold;
}

.time {
  margin-top: 15px;
  font-size: 12px;
  color: #aaa;
}