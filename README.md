<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For Sanjana ❤️</title>

<style>
body {
  font-family: 'Segoe UI', sans-serif;
  background: linear-gradient(to right, #ff758c, #ff7eb3);
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
}

.card {
  background: white;
  padding: 35px;
  border-radius: 22px;
  text-align: center;
  box-shadow: 0 15px 40px rgba(0,0,0,0.25);
  width: 320px;
}

h1 {
  color: #ff4d6d;
}

p {
  font-size: 15px;
  color: #444;
}

button {
  padding: 12px 26px;
  border: none;
  border-radius: 25px;
  font-size: 16px;
  cursor: pointer;
  margin: 12px;
}

.yes {
  background: #ff4d6d;
  color: white;
}

.no {
  background: #ddd;
}
</style>
</head>

<body>

<div class="card">
  <h1>Hey Sanjana 💕</h1>

  <p>
    I don’t know the perfect words,  
    but I know how I feel when I think about you.
  </p>

  <h2>Will you be my Valentine? 🌹</h2>

  <button class="yes" onclick="yesClick()">Yes ❤️</button>
  <button class="no" onclick="noClick()">No 🙈</button>
</div>

<script>
let noClicks = 0;

function yesClick() {
  document.body.innerHTML = `
    <h1 style="color:white;text-align:center;">
      YAYYYY 💖💖<br><br>
      You just made me very happy, Sanjana ❤️
    </h1>
  `;
}

function noClick() {
  noClicks++;

  if (noClicks === 1) {
    alert("Are you sure? 🤔");
  } else {
    alert("Not an optionnn 😌❤️");
  }
}
</script>

</body>
</html>