<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Virada dos 30 — E-book</title>
<style>
  :root{
    --cream:#FAF6EE;
    --cream-dark:#F0E8D8;
    --ink:#1A1712;
    --ink-soft:#57503f;
    --gold:#B5793A;
    --gold-light:#E7AB5F;
    --green:#4B5842;
  }
  * { margin:0; padding:0; box-sizing:border-box; }
  body {
    font-family: 'Georgia','Times New Roman',serif;
    background: var(--cream);
    color: var(--ink);
    line-height: 1.6;
  }
  .wrap { max-width: 880px; margin: 0 auto; padding: 0 24px; }
  .eyebrow {
    font-family:'Helvetica','Arial',sans-serif;
    letter-spacing: 3px;
    text-transform: uppercase;
    font-size: 13px;
    color: var(--gold);
    font-weight: 700;
  }
  h1,h2,h3 { font-weight:400; color:var(--ink); }
  a.btn {
    display:inline-block;
    font-family:'Helvetica','Arial',sans-serif;
    font-weight:700;
    text-decoration:none;
    letter-spacing:0.5px;
  }

  /* HERO */
  header.hero {
    padding: 70px 0 60px;
    text-align:center;
    position:relative;
    overflow:hidden;
  }
  .hero h1 {
    font-size: 56px;
    line-height: 1.05;
    margin: 18px 0 10px;
  }
  .hero h1 .accent { color: var(--gold); font-style: italic; }
  .hero .sub {
    font-family:'Helvetica','Arial',sans-serif;
    font-size: 19px;
    color: var(--ink-soft);
    max-width: 560px;
    margin: 0 auto 34px;
  }
  .sunrise {
    width: 190px; height: 190px;
    margin: 0 auto 30px;
    position:relative;
  }
  .sunrise .sun {
    position:absolute; top:0; left:0; right:0;
    width:190px; height:190px;
    border-radius:50%;
    background: radial-gradient(circle at 38% 32%, var(--gold-light) 0%, var(--gold) 55%, #8a5a24 100%);
    clip-path: inset(0 0 40% 0);
  }
  .sunrise .line {
    position:absolute; top:114px; left:-30px; right:-30px;
    height:3px; background:var(--ink);
  }
  .cta-primary {
    background: var(--ink);
    color: var(--cream);
    padding: 18px 46px;
    border-radius: 40px;
    font-size: 18px;
  }
  .price-tag {
    font-family:'Helvetica','Arial',sans-serif;
    font-size: 15px;
    color: var(--ink-soft);
    margin-top: 14px;
  }
  .price-tag b { color:var(--ink); font-size:20px; }

  /* PAIN SECTION */
  section.pain {
    background: var(--ink);
    color: var(--cream);
    padding: 70px 0;
  }
  section.pain h2 {
    color: var(--cream);
    font-size: 32px;
    text-align:center;
    margin-bottom: 40px;
  }
  .pain-grid {
    display:grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
  }
  .pain-item {
    font-family:'Helvetica','Arial',sans-serif;
    font-size: 16px;
    padding: 20px 22px;
    border: 1px solid #ffffff22;
    border-radius: 8px;
    color: #ECE6D8;
  }
  .pain-item b { color: var(--gold-light); }

  /* SOLUTION */
  section.solution { padding: 80px 0; text-align:center; }
  section.solution h2 { font-size: 34px; margin: 14px 0 20px; }
  section.solution p.lead {
    font-family:'Helvetica','Arial',sans-serif;
    font-size: 18px;
    color: var(--ink-soft);
    max-width: 620px;
    margin: 0 auto;
  }

  /* STRUCTURE */
  section.structure { background: var(--cream-dark); padding: 80px 0; }
  section.structure h2 { text-align:center; font-size:32px; margin-bottom:10px; }
  section.structure .eyebrow { display:block; text-align:center; margin-bottom:10px;}
  .chapters {
    margin-top: 40px;
    display:grid;
    grid-template-columns: 1fr 1fr;
    gap: 14px;
  }
  .chapter-card {
    background: var(--cream);
    border: 1px solid #e6dcc4;
    border-radius: 8px;
    padding: 18px 20px;
    font-family:'Helvetica','Arial',sans-serif;
  }
  .chapter-card .num {
    font-family:'Georgia',serif;
    font-style:italic;
    color: var(--gold);
    font-size: 22px;
  }
  .chapter-card .name { font-size:15px; margin-top:4px; }

  /* PILLARS */
  section.pillars { padding: 80px 0; text-align:center; }
  section.pillars h2 { font-size: 32px; margin-bottom: 40px; }
  .pillar-grid {
    display:grid;
    grid-template-columns: repeat(4,1fr);
    gap: 18px;
  }
  .pillar {
    padding: 26px 14px;
    border-radius: 10px;
    background: var(--cream-dark);
  }
  .pillar .icon-word {
    font-family:'Helvetica','Arial',sans-serif;
    font-weight:800;
    font-size: 13px;
    letter-spacing:1px;
    color: var(--gold);
    text-transform:uppercase;
    margin-bottom: 8px;
  }
  .pillar p {
    font-family:'Helvetica','Arial',sans-serif;
    font-size: 14px;
    color: var(--ink-soft);
  }

  /* BONUS */
  section.bonus { background: var(--ink); color: var(--cream); padding: 80px 0; }
  section.bonus h2 { color: var(--cream); text-align:center; font-size:32px; margin-bottom: 10px;}
  section.bonus .eyebrow { display:block; text-align:center; }
  .bonus-list { margin-top: 40px; }
  .bonus-item {
    display:flex;
    gap: 18px;
    padding: 18px 0;
    border-bottom: 1px solid #ffffff22;
    font-family:'Helvetica','Arial',sans-serif;
  }
  .bonus-item .n {
    font-family:'Georgia',serif;
    font-style:italic;
    font-size: 26px;
    color: var(--gold-light);
    min-width: 40px;
  }
  .bonus-item .t { font-weight:700; margin-bottom:4px; color:var(--cream);}
  .bonus-item .d { font-size:14px; color:#CFC7B4; }

  /* PRICE */
  section.price { padding: 90px 0; text-align:center; }
  .price-box {
    max-width: 420px;
    margin: 0 auto;
    background: var(--cream-dark);
    border: 2px solid var(--gold);
    border-radius: 16px;
    padding: 40px 30px;
  }
  .price-box .old-price {
    font-family:'Helvetica','Arial',sans-serif;
    color: var(--ink-soft);
    text-decoration: line-through;
    font-size: 16px;
  }
  .price-box .new-price {
    font-size: 52px;
    color: var(--ink);
    margin: 6px 0 4px;
  }
  .price-box .new-price small { font-size: 22px; }
  .price-box .installments {
    font-family:'Helvetica','Arial',sans-serif;
    font-size: 14px;
    color: var(--ink-soft);
    margin-bottom: 24px;
  }
  .price-box .cta-primary { width:100%; }
  .price-box .guarantee {
    margin-top: 20px;
    font-family:'Helvetica','Arial',sans-serif;
    font-size: 13px;
    color: var(--ink-soft);
  }

  /* FAQ */
  section.faq { background: var(--cream-dark); padding: 80px 0; }
  section.faq h2 { text-align:center; font-size:32px; margin-bottom:40px; }
  .faq-item { border-bottom: 1px solid #e6dcc4; padding: 20px 0; }
  .faq-item .q {
    font-family:'Helvetica','Arial',sans-serif;
    font-weight:700;
    font-size: 16px;
    margin-bottom: 8px;
  }
  .faq-item .a {
    font-family:'Helvetica','Arial',sans-serif;
    font-size: 15px;
    color: var(--ink-soft);
  }

  /* FINAL CTA */
  section.final-cta {
    padding: 90px 0;
    text-align:center;
  }
  section.final-cta h2 { font-size: 36px; margin-bottom: 16px; }
  section.final-cta p {
    font-family:'Helvetica','Arial',sans-serif;
    color: var(--ink-soft);
    font-size: 17px;
    max-width: 500px;
    margin: 0 auto 30px;
  }

  footer {
    text-align:center;
    padding: 30px 0;
    font-family:'Helvetica','Arial',sans-serif;
    font-size: 12px;
    color: var(--ink-soft);
    background: var(--ink);
  }
  footer span { color: #CFC7B4; }

  @media (max-width: 640px) {
    .hero h1 { font-size: 38px; }
    .pain-grid, .chapters { grid-template-columns: 1fr; }
    .pillar-grid { grid-template-columns: 1fr 1fr; }
  }
</style>
</head>
<body>

<header class="hero">
  <div class="wrap">
    <div class="sunrise"><div class="sun"></div><div class="line"></div></div>
    <span class="eyebrow">E-book · Desenvolvimento pessoal</span>
    <h1>Virada dos <span class="accent">30</span></h1>
    <p class="sub">Saia da crise da década, recupere o controle da sua vida e construa, de forma prática, a vida que você realmente quer — sem terapia de 5 anos, sem fórmula mágica.</p>
    <a href="#comprar" class="btn cta-primary">Quero minha virada agora</a>
    <div class="price-tag">Apenas <b>R$ 29,99</b> · acesso imediato em PDF</div>
  </div>
</header>

<section class="pain">
  <div class="wrap">
    <h2>Isso parece com você?</h2>
    <div class="pain-grid">
      <div class="pain-item">Sensação de estar <b>"atrasado"</b> na vida, mesmo sem saber bem em relação a quê</div>
      <div class="pain-item">Cansaço que não é só físico — é de <b>decidir, se cobrar e comparar</b> o tempo todo</div>
      <div class="pain-item">Vontade de <b>mudar tudo de uma vez</b> (trabalho, cidade, relacionamento)</div>
      <div class="pain-item">Medo de estar <b>desperdiçando</b> os seus melhores anos sem perceber</div>
    </div>
  </div>
</section>

<section class="solution">
  <div class="wrap">
    <span class="eyebrow">A virada começa aqui</span>
    <h2>Um guia prático pra sair do modo sobrevivência</h2>
    <p class="lead">Nada de "pensar positivo" ou mantra no espelho. Virada dos 30 é um passo a passo real — com autoanálise, motivação, reconstrução de autoconfiança e propósito — pra você entender por que essa fase pesa tanto e o que fazer, na prática, ainda essa semana.</p>
  </div>
</section>

<section class="structure">
  <div class="wrap">
    <span class="eyebrow">O que tem dentro</span>
    <h2>50 páginas de conteúdo direto ao ponto</h2>
    <div class="chapters">
      <div class="chapter-card"><div class="num">01–02</div><div class="name">O que é a crise dos 30 &amp; as 4 comparações que mais doem</div></div>
      <div class="chapter-card"><div class="num">03–04</div><div class="name">Autoanálise guiada &amp; o plano prático de 5 passos</div></div>
      <div class="chapter-card"><div class="num">05–07</div><div class="name">Carreira, relacionamentos, corpo e energia</div></div>
      <div class="chapter-card"><div class="num">08–10</div><div class="name">Motivação, autoconfiança, fé e propósito</div></div>
      <div class="chapter-card"><div class="num">11–13</div><div class="name">Rotina de manutenção, histórias reais &amp; perguntas frequentes</div></div>
      <div class="chapter-card"><div class="num">14</div><div class="name">Diário guiado de 21 dias, pronto para preencher</div></div>
    </div>
  </div>
</section>

<section class="pillars">
  <div class="wrap">
    <span class="eyebrow">Os 4 pilares do método</span>
    <h2>Não é só motivação. É estrutura.</h2>
    <div class="pillar-grid">
      <div class="pillar"><div class="icon-word">Autoanálise</div><p>Entenda com clareza onde você está, sem filtro e sem se enganar</p></div>
      <div class="pillar"><div class="icon-word">Motivação</div><p>Sistemas simples pra manter o ritmo mesmo nos dias sem vontade</p></div>
      <div class="pillar"><div class="icon-word">Autoconfiança</div><p>Reconstrua a crença de que você é capaz de mudar sua história</p></div>
      <div class="pillar"><div class="icon-word">Propósito e fé</div><p>Sentido pra seguir em frente, mesmo sem ver o caminho inteiro</p></div>
    </div>
  </div>
</section>

<section class="bonus">
  <div class="wrap">
    <span class="eyebrow">Bônus inclusos, sem custo extra</span>
    <h2>Você não leva só um e-book</h2>
    <div class="bonus-list">
      <div class="bonus-item"><div class="n">01</div><div><div class="t">Planilha "Raio-X da Vida"</div><div class="d">Pra mapear as 5 áreas da sua vida e acompanhar suas microametas semanais</div></div></div>
      <div class="bonus-item"><div class="n">02</div><div><div class="t">Checklist semanal de microametas</div><div class="d">Modelo pronto pra imprimir ou usar no celular toda semana</div></div></div>
      <div class="bonus-item"><div class="n">03</div><div><div class="t">Mini-guia "Como identificar metas herdadas"</div><div class="d">10 perguntas pra aplicar em qualquer área da sua vida</div></div></div>
      <div class="bonus-item"><div class="n">04</div><div><div class="t">Roteiro de áudio motivacional</div><div class="d">Pronto pra narrar e ouvir nos dias em que a motivação faltar</div></div></div>
      <div class="bonus-item"><div class="n">05</div><div><div class="t">Guia da comunidade fechada</div><div class="d">Modelo pronto pra criar seu grupo de apoio no Telegram ou WhatsApp</div></div></div>
    </div>
  </div>
</section>

<section class="price" id="comprar">
  <div class="wrap">
    <span class="eyebrow">Oferta de lançamento</span>
    <h2 style="margin: 10px 0 30px;">Comece sua virada hoje</h2>
    <div class="price-box">
      <div class="new-price"><small>R$</small> 29,99</div>
      <div class="installments">Pagamento único · acesso imediato</div>
      <a href="#" class="btn cta-primary">Quero acessar agora</a>
      <div class="guarantee">Ajuste aqui os termos de garantia e reembolso da sua oferta</div>
    </div>
  </div>
</section>

<section class="faq">
  <div class="wrap">
    <h2>Perguntas frequentes</h2>
    <div class="faq-item"><div class="q">Como recebo o material depois de comprar?</div><div class="a">O e-book e os bônus chegam em PDF, com acesso imediato após a confirmação do pagamento.</div></div>
    <div class="faq-item"><div class="q">Funciona mesmo se eu não estiver exatamente "na crise dos 30"?</div><div class="a">Sim. Os princípios do método valem pra qualquer fase de transição de vida — os 30 são só o gatilho mais comum.</div></div>
    <div class="faq-item"><div class="q">Precisa de fé religiosa pra aproveitar o capítulo sobre propósito?</div><div class="a">Não. O capítulo trata fé de forma ampla — espiritual, religiosa ou apenas confiança pessoal na vida. Use do jeito que fizer sentido pra você.</div></div>
    <div class="faq-item"><div class="q">Em quanto tempo eu leio e aplico o material?</div><div class="a">A leitura completa leva poucas horas. A aplicação prática (diário de 21 dias e plano de 90 dias) é desenhada pra caber numa rotina cheia.</div></div>
  </div>
</section>

<section class="final-cta">
  <div class="wrap">
    <h2>A virada já pode começar agora</h2>
    <p>Você não precisa ter todas as respostas hoje. Só precisa dar o próximo passo.</p>
    <a href="#comprar" class="btn cta-primary">Garantir meu e-book por R$ 29,99</a>
  </div>
</section>

<footer>
  <div class="wrap">
    <span>Virada dos 30</span> — Material digital de desenvolvimento pessoal. Consumo individual.
  </div>
</footer>

</body>
</html>
