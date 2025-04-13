<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>波のアニメーション</title>
  <style>
    body, html {
      margin: 0;
      padding: 0;
      overflow: hidden;
      height: 100vh;
      background: #0f2027;
    }

    canvas {
      display: block;
    }
  </style>
</head>
<body>
  <canvas id="waveCanvas"></canvas>

  <script>
    const canvas = document.getElementById("waveCanvas");
    const ctx = canvas.getContext("2d");

    function resizeCanvas() {
      canvas.width = window.innerWidth;
      canvas.height = window.innerHeight;
    }
    window.addEventListener("resize", resizeCanvas);
    resizeCanvas();

    let waveOffset = 0;

    function drawWave() {
      ctx.clearRect(0, 0, canvas.width, canvas.height);

      ctx.fillStyle = "#33ccff";
      ctx.beginPath();
      ctx.moveTo(0, canvas.height / 2);

      for (let x = 0; x < canvas.width; x++) {
        const y = Math.sin((x + waveOffset) * 0.02) * 20 + canvas.height / 2;
        ctx.lineTo(x, y);
      }

      ctx.lineTo(canvas.width, canvas.height);
      ctx.lineTo(0, canvas.height);
      ctx.closePath();
      ctx.fill();

      waveOffset += 1;
      requestAnimationFrame(drawWave);
    }

    drawWave();
  </script>
</body>
</html>
