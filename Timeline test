<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Timeline Spider-Man</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background: #111;
    color: #fff;
    margin: 0;
    padding: 20px;
  }
  .timeline {
    position: relative;
    margin: 0 auto;
    padding: 20px 0;
    max-width: 600px;
  }
  .timeline::before {
    content: "";
    position: absolute;
    left: 50%;
    width: 4px;
    height: 100%;
    background: red;
    transform: translateX(-50%);
  }
  .event {
    position: relative;
    width: 45%;
    padding: 15px;
    margin: 20px 0;
    border-radius: 8px;
    background: #222;
  }
  .event.left {
    left: 0;
  }
  .event.right {
    left: 55%;
  }
  .event::before {
    content: "🕷️";
    position: absolute;
    top: 20px;
    right: -30px;
    font-size: 24px;
  }
  .event.right::before {
    left: -30px;
    right: auto;
  }
  .date {
    font-weight: bold;
    color: #ff4444;
  }
</style>
</head>
<body>
<h1>🕷️ Timeline Spider-Man</h1>
<div class="timeline">
  <div class="event left">
    <div class="date">1962</div>
    <p>Première apparition de Spider-Man dans <em>Amazing Fantasy #15</em>.</p>
  </div>
  <div class="event right">
    <div class="date">1977</div>
    <p>Première série télévisée live-action Spider-Man.</p>
  </div>
  <div class="event left">
    <div class="date">2002</div>
    <p>Sortie du film <em>Spider-Man</em> de Sam Raimi avec Tobey Maguire.</p>
  </div>
  <div class="event right">
    <div class="date">2018</div>
    <p><em>Spider-Man: Into the Spider-Verse</em> révolutionne l’animation.</p>
  </div>
</div>
</body>
</html>
