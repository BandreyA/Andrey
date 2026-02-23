<!-- Верхняя бегущая строка (движется слева направо) -->
<div class="marquee-container">
  <div class="marquee-content">
    ★ Код в тёмной теме ★ Чистые линии ★ React + Tailwind ★ Node.js ★ Git ★ VS Code ★ Postgres ★ MongoDB ★ Frontend / Fullstack ★ Андрей Developer ★ 
    <!-- Дублируем текст для seamless loop -->
    ★ Код в тёмной теме ★ Чистые линии ★ React + Tailwind ★ Node.js ★ Git ★ VS Code ★ Postgres ★ MongoDB ★ Frontend / Fullstack ★ Андрей Developer ★
  </div>
</div>

<!-- Твой приветственный текст (можно оставить typing или рамку) -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=28&duration=4000&pause=1000&color=DDDDDD&center=true&vCenter=true&width=500&lines=Привет!+Я+Андрей;Frontend+%2F+Fullstack+Developer;Чистый+код+и+тёмная+тема" alt="Typing SVG" />
</p>

<!-- Нижняя бегущая строка (движется справа налево — для разнообразия) -->
<div class="marquee-container reverse">
  <div class="marquee-content">
    ☕ Кофе + lo-fi ☕ Баги фиксятся ночью ☕ Open to projects ☕ Краснодар / Россия ☕ andrey109092git@gmail.com ☕ 
    <!-- Дублируем для loop -->
    ☕ Кофе + lo-fi ☕ Баги фиксятся ночью ☕ Open to projects ☕ Краснодар / Россия ☕ andrey109092git@gmail.com ☕
  </div>
</div>

<!-- CSS для анимации (вставь в конец README или в <style> если GitHub позволяет) -->
<style>
  .marquee-container {
    overflow: hidden;
    white-space: nowrap;
    background: #0F0F0F;
    border-top: 1px solid #333;
    border-bottom: 1px solid #333;
    margin: 20px 0;
    padding: 12px 0;
  }

  .marquee-content {
    display: inline-block;
    animation: marquee 25s linear infinite;
    color: #AAAAAA;
    font-family: 'Courier New', monospace;
    font-size: 16px;
    letter-spacing: 1px;
  }

  .reverse .marquee-content {
    animation-direction: reverse; /* обратное направление */
  }

  @keyframes marquee {
    0%   { transform: translateX(0); }
    100% { transform: translateX(-50%); } /* -50% потому что текст дублирован */
  }
</style>
