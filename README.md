<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Neon Button</title>
  <style>
    body {
      background-color:#111;
      display:flex;
      justify-content:center;
      align-items:center;
      height:100vh;
    }

    .neon-button {
    color:#0ff;
    font-size:20px;
    padding:15px 40px;
    border:2px solid #0ff;
    background:transparent;
    text-transform:uppercase;
    letter-spacing:2px;
    cursor:pointer;
    transition:0.3s;
    border-radius:8px;
    box-shadow: 
    0 0 10px #0ff,
     0 0 20px #0ff,
      0 0 30px #0ff;
    }

.neon-button:hover {
  background-color:#0ff;
  color: #111;
  box-shadow: 0 0 20px #0ff,
  0 0 40px #0ff,
  0 0 60px #0ff;
}
  </style>
</head>
<body>

<button class="neon-button">
  Click Me</button>

</body>
</html>
