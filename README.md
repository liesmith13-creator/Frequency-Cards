<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Manifesting Cards</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #111;
      color: #fff;
      text-align: center;
      padding: 50px 20px;
    }

    h1 {
      font-size: 1.8rem;
      margin-bottom: 20px;
    }

    button {
      padding: 10px 20px;
      background-color: #8a2be2;
      color: white;
      border: none;
      border-radius: 6px;
      font-size: 1rem;
      cursor: pointer;
      margin-top: 10px;
    }

    #card-result {
      margin-top: 40px;
      font-size: 1.2rem;
      color: #00e0d3;
      line-height: 1.8;
      white-space: pre-wrap;
    }
  </style>
</head>
<body>
  <h1>🪐 Pull a Manifesting Card</h1>
  <button onclick="pullCard()">Pull</button>
  <div id="card-result"></div>

  <script>
    const cards = [
      "🜁 MC-001 · Silent Anchor\n“I still hold the world, even in pause.”",
      "🜂 MC-013 · Flame of Will\n“I burn through what no longer holds me.”",
      "🜄 MC-024 · No Rush · 441Hz\n“I still move. But not to catch up. I move to stay in sync with myself.”",
      "🜃 MC-005 · Emotional Alchemy\n“I transmute. I do not suppress.”",
      "🕯️ MC-019 · 言之未形 · 472Hz\n“My tongue is a thread the world is trying to pull.\nI vow by vibration.”"
    ];

    function pullCard() {
      const result = cards[Math.floor(Math.random() * cards.length)];
      document.getElementById("card-result").textContent = result;
    }
  </script>
</body>
</html>
