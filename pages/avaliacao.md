---
layout: default
title: Avaliação de rumores
menu_title: Avaliação de rumores
permalink: /avaliacao/
---

<style>
  .rating-box {
    display: flex;
    align-items: center;
    background-color: rgba(255, 255, 255, 0.05);
    padding: 1rem;
    border-radius: 0.75rem;
    margin-bottom: 1rem;
    border-left: 5px solid;
  }

  .rating-box .emoji {
    font-size: 1.8rem;
    margin-right: 1rem;
    flex-shrink: 0;
  }

  .rating-box h3 {
    margin: 0;
    font-size: 1.05rem;
    color: white;
  }

  .rating-box p {
    margin: 0.25rem 0 0;
    font-size: 0.9rem;
    color: #ccc;
  }

  .rating-confiavel { border-color: #00ffae; }
  .rating-possivel  { border-color: #ffd700; }
  .rating-suspeito  { border-color: #ff9100; }
  .rating-duvidoso  { border-color: #ff4d4d; }
  .rating-desconhecido { border-color: #aaaaaa; }
</style>

<br>

<div class="rating-box rating-confiavel">
  <span class="emoji">✅</span>
  <div>
    <h3>Confiável</h3>
    <p>Confirmado por uma fonte credível ou corroborado por mais do que uma.</p>
  </div>
</div>

<div class="rating-box rating-possivel">
  <span class="emoji">🟡</span>
  <div>
    <h3>Possível</h3>
    <p>Parece plausível e pode ser verdadeira, mas ainda não há confirmação sólida.</p>
  </div>
</div>

<div class="rating-box rating-suspeito">
  <span class="emoji">🟠</span>
  <div>
    <h3>Suspeito</h3>
    <p>A probabilidade de ser falso é relativamente alta, mas não tão óbvia.</p>
  </div>
</div>

<div class="rating-box rating-duvidoso">
  <span class="emoji">🔴</span>
  <div>
    <h3>Duvidoso</h3>
    <p>Há fortes evidências de que é falso ou enganoso.</p>
  </div>
</div>

<div class="rating-box rating-desconhecido">
  <span class="emoji">❔</span>
  <div>
    <h3>Desconhecido</h3>
    <p>Não avaliado ou credibilidade da fonte desconhecida</p>
  </div>
</div>
