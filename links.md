---
layout: none
title: Underground Residence
---

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Underground Residence</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    @font-face {
      font-family: 'PermanentMarker';
      src: url('{{ "/assets/font/PermanentMarker-Regular.ttf" | relative_url }}') format('truetype');
      font-weight: normal;
      font-style: normal;
    }

    html, body {
      background-color: #000000;
      margin: 0;
      padding: 0;
      width: 100%;
      height: 100%;
    }

.underground-container {
  background-color: #000000;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 40px 20px;
}

.header-image {
  max-width: 800px;
  width: 100%;
  height: auto;
  margin-bottom: 60px;
}

.links-list {
  list-style: none;
  padding: 0;
  margin: 0;
  text-align: center;
}

.links-list li {
  margin: 25px 0;
}

.links-list a {
  font-family: 'PermanentMarker', cursive;
  font-size: 48px;
  color: #b9b8b8;
  text-decoration: none;
  transition: color 0.3s ease;
}

.links-list a:hover {
  color: #ffffff;
  text-shadow: 0 0 10px rgba(255, 255, 255, 0.5);
}

.email-image {
  height: 48px;
  width: auto;
  transition: filter 0.3s ease;
}

.email-image:hover {
  filter: brightness(1.2) drop-shadow(0 0 10px rgba(255, 255, 255, 0.5));
}
  </style>
</head>
<body>

<div class="underground-container">
  <img src="{{ '/assets/images/Underground-Residence.png' | relative_url }}" alt="Underground Residence" class="header-image">
  
  <ul class="links-list">
    <li><a href="https://undergrndresident.tumblr.com/">TUMBLR</a></li>
    <li><a href="https://www.instagram.com/undergrndresident/">INSTAGRAM</a></li>
    <li><a href="https://undergroundresident.newgrounds.com/">NEWGROUNDS</a></li>
    <li><a href="https://t.me/UndergroundResident">TELEGRAM</a></li>
    <li><a href="https://discord.com/users/undergroundresident">DISCORD</a></li>
    <li><a href="/index">BLOG</a></li>
    <li><img src="{{ '/assets/images/email.png' | relative_url }}" alt="Email" class="email-image"></li>
  </ul>
</div>

</body>
</html>
