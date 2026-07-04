[Uploading guerfi-tourismo (2).html…]()
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Guerfi Tourismo — وكالة سفر وعمرة، معسكر | Agence de voyage & Omra, Mascara</title>
<meta name="description" content="Guerfi Tourismo, وكالة سياحة وأسفار بمعسكر متخصصة في العمرة والرحلات السياحية. Agence de tourisme à Mascara, organisation de voyages Omra et séjours touristiques sur mesure.">
<style>
  @import url('https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,400;9..144,500;9..144,600;9..144,700&family=Manrope:wght@400;500;600;700;800&family=Amiri:wght@400;700&family=Cairo:wght@500;700;800&display=swap');

  :root{
    --bg-0: #05070C;
    --bg-1: #0B0F19;
    --panel: #10151F;
    --panel-2: #151B27;
    --gold: #D4AF37;
    --gold-light: #F1D989;
    --gold-deep: #9C7A24;
    --cream: #F3EEE0;
    --cream-soft: rgba(243,238,224,0.68);
    --line: rgba(212,175,55,0.18);
    --wa-green: #25D366;
  }

  *{ box-sizing:border-box; margin:0; padding:0; }
  html{ scroll-behavior:smooth; }
  body{
    background:var(--bg-0);
    color:var(--cream);
    font-family:'Manrope', sans-serif;
    line-height:1.6;
    -webkit-font-smoothing:antialiased;
    overflow-x:hidden;
  }
  h1,h2,h3,.display{
    font-family:'Fraunces', serif;
    font-weight:600;
    letter-spacing:-0.01em;
    color:var(--cream);
  }
  a{ color:inherit; text-decoration:none; }
  img{ max-width:100%; display:block; }
  .wrap{ max-width:1180px; margin:0 auto; padding:0 32px; }
  .eyebrow{
    font-family:'Manrope', sans-serif;
    font-size:12.5px;
    font-weight:800;
    letter-spacing:0.18em;
    text-transform:uppercase;
    color:var(--gold);
  }
  .arabic{ font-family:'Amiri', serif; direction:rtl; }
  .ar-text{ font-family:'Cairo', sans-serif; direction:rtl; unicode-bidi:isolate; }
  .bi-head .ar-text{ display:block; font-size:1em; color:var(--gold-light); font-weight:800; margin-bottom:4px; }
  .bi-head .fr-text{ display:block; font-family:'Manrope',sans-serif; font-weight:600; font-size:0.42em; letter-spacing:0.06em; text-transform:uppercase; color:var(--cream-soft); }
  p.bi-p{ margin-bottom:2px; }
  p.bi-p .ar-text{ display:block; font-size:1.06em; line-height:1.9; margin-bottom:4px; }
  p.bi-p .fr-text{ display:block; font-size:0.86em; color:var(--cream-soft); font-style:italic; }
  .btn .ar-text{ font-family:'Cairo', sans-serif; direction:rtl; }
  .btn-bi{ display:inline-flex; flex-direction:column; align-items:center; line-height:1.3; gap:2px; padding-top:11px; padding-bottom:11px; }
  .btn-bi .ar-text{ font-size:14px; font-weight:800; }
  .btn-bi .fr-text{ font-size:10.5px; font-weight:600; opacity:0.85; text-transform:uppercase; letter-spacing:0.04em; }
  :focus-visible{ outline:2.5px solid var(--gold); outline-offset:3px; }
  @media (prefers-reduced-motion: reduce){
    *{ animation:none !important; transition:none !important; scroll-behavior:auto !important; }
  }

  /* textured dark background, echoes the card's diagonal facets */
  .textured{
    position:relative;
    background:
      repeating-linear-gradient(115deg, rgba(212,175,55,0.05) 0px, rgba(212,175,55,0.05) 1px, transparent 1px, transparent 68px),
      repeating-linear-gradient(115deg, rgba(255,255,255,0.025) 0px, rgba(255,255,255,0.025) 1px, transparent 1px, transparent 34px),
      radial-gradient(120% 90% at 15% 0%, #131B2C 0%, #0B0F19 45%, #05070C 100%);
  }
  .textured::before{
    content:''; position:absolute; inset:0; pointer-events:none;
    background:radial-gradient(60% 50% at 85% 10%, rgba(212,175,55,0.10), transparent 60%);
  }

  /* ---------- HEADER ---------- */
  header{
    position:sticky; top:0; z-index:50;
    background:rgba(5,7,12,0.86);
    backdrop-filter:blur(12px);
    border-bottom:1px solid var(--line);
  }
  .nav{
    display:flex; align-items:center; justify-content:space-between;
    padding:14px 32px;
    max-width:1180px; margin:0 auto;
  }
  .brand{ display:flex; align-items:center; gap:12px; }
  .brand img{ height:46px; width:46px; border-radius:50%; box-shadow:0 0 0 2px rgba(212,175,55,0.35); }
  .brand-text{ line-height:1.15; }
  .brand-text .name{ font-family:'Fraunces', serif; font-weight:700; font-size:17px; color:var(--cream); letter-spacing:0.02em; }
  .brand-text .tag{ font-size:10px; letter-spacing:0.16em; color:var(--gold); font-weight:800; }
  nav.links{ display:flex; gap:34px; font-size:14.5px; font-weight:600; }
  nav.links a{ color:var(--cream-soft); position:relative; padding-bottom:3px; }
  nav.links a:hover{ color:var(--gold-light); }
  .nav-cta{
    display:flex; align-items:center; gap:8px;
    background:var(--wa-green); color:#06210F;
    padding:10px 18px; border-radius:999px;
    font-size:13.5px; font-weight:800; white-space:nowrap;
  }
  .nav-cta:hover{ filter:brightness(1.08); }

  /* ---------- HERO ---------- */
  .hero{
    position:relative;
    padding:100px 32px 0;
    overflow:hidden;
  }
  .hero-inner{
    max-width:1180px; margin:0 auto;
    display:grid; grid-template-columns:1.1fr 0.9fr; gap:40px;
    align-items:center;
    position:relative; z-index:3;
    padding-bottom:60px;
  }
  .hero h1{
    font-size:clamp(36px, 4.6vw, 58px);
    line-height:1.08;
    margin:16px 0 10px;
  }
  .hero h1 em{ font-style:normal; color:var(--gold-light); }
  .hero .slogan-ar{
    font-family:'Amiri', serif;
    color:var(--gold-light);
    font-size:26px;
    direction:rtl;
    margin:8px 0 22px;
  }
  .hero .slogan-ar span.fr{
    display:block; font-family:'Manrope',sans-serif; direction:ltr;
    font-size:12.5px; letter-spacing:0.04em; color:var(--cream-soft); font-weight:600;
    margin-top:4px; text-transform:none;
  }
  .hero p.lede{
    font-size:16.5px; max-width:480px; color:var(--cream-soft);
    margin-bottom:32px;
  }
  .hero-ctas{ display:flex; gap:14px; flex-wrap:wrap; }
  .btn{
    display:inline-flex; align-items:center; gap:8px;
    padding:14px 26px; border-radius:999px;
    font-weight:700; font-size:14.5px; cursor:pointer; border:none;
  }
  .btn-gold{ background:linear-gradient(135deg, var(--gold-light), var(--gold-deep)); color:#161200; }
  .btn-gold:hover{ filter:brightness(1.06); }
  .btn-wa{ background:var(--wa-green); color:#06210F; }
  .btn-wa:hover{ filter:brightness(1.08); }
  .btn-ghost{ background:transparent; color:var(--cream); border:1.5px solid rgba(243,238,224,0.35); }
  .btn-ghost:hover{ border-color:var(--gold); color:var(--gold-light); }

  .flight-stage{ position:relative; height:420px; }
  .flight-stage svg{ width:100%; height:100%; }
  .flight-dash{
    stroke:rgba(212,175,55,0.75); stroke-width:2; stroke-dasharray:7 8;
    fill:none; stroke-linecap:round; animation:dashmove 3.5s linear infinite;
  }
  @keyframes dashmove{ to{ stroke-dashoffset:-120; } }
  .plane-icon{ animation:fly 3.5s ease-in-out infinite; transform-origin:center; }
  @keyframes fly{ 0%,100%{ transform:translateY(0px);} 50%{ transform:translateY(-6px);} }
  .stage-label{
    font-family:'Manrope', sans-serif; font-size:11px; font-weight:800;
    letter-spacing:0.1em; fill:var(--gold-light); text-transform:uppercase;
  }

  .hairline{ height:1px; background:linear-gradient(90deg, transparent, var(--gold), transparent); opacity:0.5; max-width:1180px; margin:0 auto; }

  /* ---------- DEPARTURE BOARD ---------- */
  .board-section{ padding:52px 32px; }
  .board{
    max-width:1180px; margin:0 auto;
    background:#080B12; border:1px solid var(--line); border-radius:14px;
    overflow:hidden;
  }
  .board-head{
    display:flex; align-items:center; justify-content:space-between;
    padding:16px 22px; border-bottom:1px solid var(--line);
    background:linear-gradient(90deg, rgba(212,175,55,0.08), transparent);
  }
  .board-head .bh-ar{ font-family:'Cairo',sans-serif; font-weight:800; color:var(--gold-light); direction:rtl; font-size:15px; }
  .board-head .bh-fr{ font-size:11px; letter-spacing:0.1em; text-transform:uppercase; color:var(--cream-soft); }
  .board-row{
    display:grid; grid-template-columns:90px 1fr 90px 120px; align-items:center; gap:14px;
    padding:13px 22px; border-bottom:1px solid rgba(212,175,55,0.08);
    font-family:'Manrope', monospace;
  }
  .board-row:last-child{ border-bottom:none; }
  .board-code{ font-family:'Manrope',monospace; font-weight:800; color:var(--gold-light); letter-spacing:0.05em; font-size:13px; }
  .board-dest{ display:flex; align-items:center; gap:10px; }
  .board-dest .ar{ font-family:'Cairo',sans-serif; direction:rtl; font-weight:700; color:var(--cream); font-size:14.5px; }
  .board-dest .fr{ font-size:11.5px; color:var(--cream-soft); }
  .board-status{
    justify-self:start; font-size:10px; font-weight:800; letter-spacing:0.06em;
    padding:4px 10px; border-radius:999px; text-transform:uppercase;
  }
  .board-status.omra{ background:rgba(212,175,55,0.16); color:var(--gold-light); border:1px solid rgba(212,175,55,0.35); }
  .board-status.voyage{ background:rgba(37,211,102,0.12); color:#7FE6A8; border:1px solid rgba(37,211,102,0.3); }
  .board-time{ font-size:12.5px; color:var(--cream-soft); text-align:right; }
  @media (max-width:640px){
    .board-row{ grid-template-columns:60px 1fr 74px; }
    .board-time{ display:none; }
  }

  /* ---------- SERVICES ---------- */
  .services{ padding:90px 32px 100px; }
  .section-head{ max-width:640px; margin-bottom:52px; }
  .section-head h2{ font-size:clamp(28px,3.4vw,40px); margin-top:12px; }
  .section-head p{ color:var(--cream-soft); margin-top:14px; font-size:15.5px; }

  .pillars{ display:grid; grid-template-columns:1fr 1fr; gap:28px; }
  .pillar{
    border-radius:16px; padding:44px 38px; position:relative; overflow:hidden;
    min-height:360px; display:flex; flex-direction:column; justify-content:flex-end;
    background:linear-gradient(165deg, var(--panel-2) 0%, var(--panel) 100%);
    border:1px solid var(--line);
  }
  .pillar-icon{ position:absolute; top:34px; left:38px; width:50px; height:50px; opacity:0.95; }
  .pillar-eyebrow{ font-size:12px; font-weight:800; letter-spacing:0.14em; text-transform:uppercase; color:var(--gold); margin-bottom:10px; }
  .pillar h3{ font-size:28px; margin-bottom:12px; }
  .pillar p{ font-size:14.5px; color:var(--cream-soft); max-width:380px; margin-bottom:22px; }
  .pillar-list{ list-style:none; display:flex; flex-direction:column; gap:8px; margin-bottom:24px; }
  .pillar-list li{ font-size:13.5px; color:var(--cream-soft); display:flex; gap:8px; align-items:flex-start; }
  .pillar-list li:before{ content:'—'; color:var(--gold); }
  .pillar .btn{ align-self:flex-start; background:rgba(212,175,55,0.12); color:var(--gold-light); border:1px solid var(--line); }
  .pillar .btn:hover{ background:rgba(212,175,55,0.2); }

  /* ---------- SLOGAN BAND ---------- */
  .slogan-band{ padding:70px 32px; border-top:1px solid var(--line); border-bottom:1px solid var(--line); }
  .slogan-grid{
    max-width:1180px; margin:0 auto;
    display:grid; grid-template-columns:repeat(3,1fr); gap:36px 28px;
    text-align:center;
  }
  .slogan-item .ar{ font-family:'Amiri', serif; direction:rtl; font-size:22px; color:var(--gold-light); margin-bottom:8px; }
  .slogan-item .fr{ font-size:12.5px; color:var(--cream-soft); letter-spacing:0.02em; }

  /* ---------- TESTIMONIALS / VIDEOS ---------- */
  .testimonials{ padding:90px 32px 100px; }
  .test-head{ max-width:640px; margin-bottom:16px; }
  .test-head .ar-title{ font-family:'Amiri', serif; direction:rtl; font-size:30px; color:var(--gold-light); margin:12px 0 6px; }
  .test-head h2{ font-size:clamp(24px,3vw,34px); }
  .test-head p{ color:var(--cream-soft); margin-top:12px; font-size:15px; }
  .video-grid{
    display:grid; grid-template-columns:repeat(6, 1fr); gap:16px; margin-top:44px;
  }
  .video-thumb{
    position:relative; display:block; border-radius:14px; overflow:hidden;
    border:1px solid var(--line); aspect-ratio:9/16;
    background:
      radial-gradient(120% 90% at 30% 15%, rgba(212,175,55,0.20), transparent 55%),
      linear-gradient(165deg, var(--panel-2) 0%, #0A0D14 100%);
  }
  .video-thumb::before{
    content:''; position:absolute; inset:0;
    background-image:
      repeating-linear-gradient(115deg, rgba(212,175,55,0.06) 0px, rgba(212,175,55,0.06) 1px, transparent 1px, transparent 22px);
  }
  .video-thumb .tag{
    position:absolute; top:10px; left:10px; z-index:3;
    background:rgba(5,7,12,0.75); color:var(--gold-light);
    font-size:10.5px; font-weight:800; letter-spacing:0.06em;
    padding:5px 10px; border-radius:999px; border:1px solid var(--line);
  }
  .play-btn{
    position:absolute; top:50%; left:50%; transform:translate(-50%,-50%);
    width:52px; height:52px; border-radius:50%; z-index:2;
    background:linear-gradient(135deg, var(--gold-light), var(--gold-deep));
    display:flex; align-items:center; justify-content:center;
    box-shadow:0 6px 18px rgba(0,0,0,0.45);
    transition:transform .2s ease;
  }
  .play-btn svg{ width:18px; height:18px; margin-left:2px; }
  .video-thumb:hover .play-btn{ transform:translate(-50%,-50%) scale(1.1); }
  .video-caption{
    position:absolute; left:0; right:0; bottom:0; z-index:3;
    padding:10px 12px 12px; text-align:center;
    background:linear-gradient(0deg, rgba(5,7,12,0.92), transparent);
  }
  .video-caption .ar{ font-family:'Cairo',sans-serif; direction:rtl; font-weight:700; color:var(--cream); font-size:12.5px; display:block; }
  .video-caption .fr{ font-size:10px; color:var(--cream-soft); display:block; margin-top:2px; }
  .fb-mark{
    position:absolute; bottom:10px; right:10px; z-index:3;
    width:20px; height:20px; opacity:0.85;
  }

  .raffle{
    margin-top:56px; border-radius:18px; overflow:hidden;
    border:1px solid var(--line);
    background:linear-gradient(120deg, #171008, var(--panel) 65%);
    display:grid; grid-template-columns:0.95fr 1.05fr; align-items:stretch;
  }
  .raffle-copy{ padding:44px 42px; display:flex; flex-direction:column; justify-content:center; gap:14px; }
  .raffle-copy .eyebrow{ color:var(--gold); }
  .raffle-copy .ar-title{ font-family:'Amiri', serif; direction:rtl; font-size:26px; color:var(--gold-light); }
  .raffle-copy h3{ font-size:24px; }
  .raffle-copy p{ font-size:14.5px; color:var(--cream-soft); max-width:420px; }
  .raffle-video{ position:relative; aspect-ratio:9/16; max-height:520px; }
  .raffle-video iframe{ position:absolute; inset:0; width:100%; height:100%; border:0; }

  @media (max-width:1000px){
    .video-grid{ grid-template-columns:repeat(3, 1fr); }
    .raffle{ grid-template-columns:1fr; }
    .raffle-video{ max-height:440px; }
  }
  @media (max-width:600px){
    .video-grid{ grid-template-columns:repeat(2, 1fr); }
  }

  /* ---------- TRUST STRIP ---------- */
  .trust{ padding:56px 32px; background:var(--panel); border-top:1px solid var(--line); border-bottom:1px solid var(--line); }
  .trust-inner{ max-width:1180px; margin:0 auto; display:grid; grid-template-columns:repeat(4,1fr); gap:32px; }
  .trust-item .num{ font-family:'Fraunces',serif; font-size:30px; color:var(--gold-light); font-weight:600; }
  .trust-item .lbl{ font-size:13px; margin-top:6px; color:var(--cream-soft); }

  /* ---------- WHY ---------- */
  .why{ padding:96px 32px; }

  /* ---------- SUBSCRIBE / INVITATION ---------- */
  .subscribe{ padding:90px 32px; }
  .sub-card{
    max-width:1180px; margin:0 auto; border-radius:20px; overflow:hidden;
    background:linear-gradient(135deg, var(--panel-2), #0A0D14 70%);
    border:1px solid var(--line);
    display:grid; grid-template-columns:1fr 1fr; align-items:stretch;
  }
  .sub-copy{ padding:52px 48px; display:flex; flex-direction:column; justify-content:center; gap:12px; }
  .sub-copy .ar-title{ font-family:'Cairo',sans-serif; direction:rtl; font-weight:800; font-size:24px; color:var(--gold-light); }
  .sub-copy h2{ font-size:clamp(22px,2.8vw,30px); }
  .sub-copy p{ font-size:14.5px; color:var(--cream-soft); max-width:400px; }
  .sub-copy .ar-p{ font-family:'Cairo',sans-serif; direction:rtl; font-size:14px; color:var(--cream); font-weight:600; max-width:400px; }
  .sub-form{
    padding:48px; display:flex; flex-direction:column; justify-content:center; gap:16px;
    background:rgba(212,175,55,0.04); border-inline-start:1px solid var(--line);
  }
  .field-group label{
    display:block; font-size:11.5px; font-weight:800; letter-spacing:0.08em; text-transform:uppercase;
    color:var(--gold); margin-bottom:8px;
  }
  .field-group label .ar{ font-family:'Cairo',sans-serif; direction:rtl; text-transform:none; letter-spacing:0; font-size:12.5px; display:block; margin-bottom:2px; color:var(--gold-light); }
  .field-group input{
    width:100%; padding:13px 16px; border-radius:10px;
    background:#0A0D14; border:1px solid var(--line); color:var(--cream);
    font-family:'Manrope',sans-serif; font-size:14.5px;
  }
  .field-group input::placeholder{ color:rgba(243,238,224,0.35); }
  .field-group input:focus{ outline:none; border-color:var(--gold); }
  .sub-submit{
    margin-top:6px; border:none; cursor:pointer; border-radius:999px;
    padding:15px 26px; font-weight:800; font-size:14.5px;
    background:linear-gradient(135deg, var(--gold-light), var(--gold-deep)); color:#161200;
    display:flex; flex-direction:column; align-items:center; gap:2px;
  }
  .sub-submit:hover{ filter:brightness(1.06); }
  .sub-submit .fr{ font-size:10.5px; font-weight:600; text-transform:uppercase; letter-spacing:0.04em; opacity:.8; }
  .sub-note{ font-size:11.5px; color:var(--cream-soft); text-align:center; }
  .sub-success{
    display:none; margin-top:6px; padding:12px 16px; border-radius:10px;
    background:rgba(37,211,102,0.1); border:1px solid rgba(37,211,102,0.3);
    color:#7FE6A8; font-size:13px; text-align:center;
  }
  .sub-success.show{ display:block; }
  @media (max-width:900px){
    .sub-card{ grid-template-columns:1fr; }
    .sub-form{ border-inline-start:none; border-top:1px solid var(--line); }
  }

  .why-grid{ max-width:1180px; margin:0 auto; display:grid; grid-template-columns:0.85fr 1.15fr; gap:60px; align-items:start; }
  .why-list{ display:flex; flex-direction:column; }
  .why-row{ display:flex; gap:20px; padding:26px 0; border-top:1px solid var(--line); }
  .why-row:last-child{ border-bottom:1px solid var(--line); }
  .why-row .mark{ font-family:'Fraunces',serif; font-size:15px; color:var(--gold); font-weight:700; min-width:26px; }
  .why-row h4{ font-family:'Fraunces',serif; font-size:18px; color:var(--cream); margin-bottom:6px; }
  .why-row p{ font-size:14px; color:var(--cream-soft); max-width:460px; }

  /* ---------- LOCATION ---------- */
  .location{ padding:90px 32px 100px; }
  .loc-grid{ max-width:1180px; margin:0 auto; display:grid; grid-template-columns:1fr 1fr; gap:44px; align-items:stretch; }
  .loc-card{
    background:linear-gradient(165deg, var(--panel-2), var(--panel));
    border:1px solid var(--line); border-radius:16px;
    padding:44px; display:flex; flex-direction:column; gap:24px; justify-content:center;
  }
  .loc-field{ display:flex; gap:16px; align-items:flex-start; }
  .loc-field .ic{
    width:40px; height:40px; border-radius:50%;
    background:rgba(212,175,55,0.1); display:flex; align-items:center; justify-content:center;
    flex-shrink:0; color:var(--gold);
  }
  .loc-field h5{ font-size:11.5px; letter-spacing:0.12em; text-transform:uppercase; color:var(--cream-soft); font-weight:800; margin-bottom:4px; }
  .loc-field p, .loc-field a{ font-size:15px; font-weight:600; color:var(--cream); }
  .loc-field a:hover{ color:var(--gold-light); }
  .issue-note{
    margin-top:6px; padding:16px 18px; border-radius:12px;
    background:rgba(37,211,102,0.08); border:1px solid rgba(37,211,102,0.3);
    font-size:13.5px; color:var(--cream-soft); display:flex; gap:12px; align-items:center;
  }
  .map-panel{ border-radius:16px; overflow:hidden; position:relative; min-height:340px; border:1px solid var(--line); }
  .map-panel iframe{ width:100%; height:100%; min-height:340px; border:0; filter:grayscale(0.3) invert(0.92) contrast(0.9); }

  /* ---------- CTA BAND ---------- */
  .cta-band{
    background:linear-gradient(120deg, #171008, #0B0F19 60%);
    border-top:1px solid var(--line);
    padding:74px 32px; text-align:center;
  }
  .cta-band .slogan-ar{ font-family:'Amiri', serif; direction:rtl; font-size:24px; color:var(--gold-light); margin-bottom:14px; }
  .cta-band h2{ font-size:clamp(26px,3.5vw,38px); margin-bottom:14px; }
  .cta-band p{ color:var(--cream-soft); margin-bottom:30px; font-size:15.5px; }
  .cta-band .btns{ display:flex; gap:14px; justify-content:center; flex-wrap:wrap; }

  /* ---------- FOOTER ---------- */
  footer{ background:#05070C; color:var(--cream-soft); padding:56px 32px 28px; border-top:1px solid var(--line); }
  .foot-grid{ max-width:1180px; margin:0 auto; display:grid; grid-template-columns:1.4fr 1fr 1fr; gap:40px; padding-bottom:36px; border-bottom:1px solid var(--line); }
  .foot-brand{ display:flex; align-items:center; gap:12px; margin-bottom:14px; }
  .foot-brand img{ height:42px; width:42px; border-radius:50%; box-shadow:0 0 0 2px rgba(212,175,55,0.35); }
  .foot-brand span{ font-family:'Fraunces',serif; font-size:17px; color:var(--cream); font-weight:700; }
  footer h6{ font-size:12px; letter-spacing:0.12em; text-transform:uppercase; color:var(--gold); margin-bottom:14px; }
  footer ul{ list-style:none; display:flex; flex-direction:column; gap:10px; font-size:14px; }
  footer ul a:hover{ color:var(--gold-light); }
  .foot-bottom{ max-width:1180px; margin:0 auto; padding-top:22px; display:flex; justify-content:space-between; font-size:12.5px; flex-wrap:wrap; gap:10px; }

  /* ---------- WHATSAPP FLOAT ---------- */
  .wa-float{
    position:fixed; right:22px; bottom:22px; z-index:60;
    width:58px; height:58px; border-radius:50%;
    background:var(--wa-green); display:flex; align-items:center; justify-content:center;
    box-shadow:0 8px 24px rgba(0,0,0,0.4);
  }
  .wa-float:hover{ transform:scale(1.06); }
  .wa-float svg{ width:28px; height:28px; }

  /* ---------- RESPONSIVE ---------- */
  @media (max-width:900px){
    nav.links{ display:none; }
    .hero-inner{ grid-template-columns:1fr; }
    .flight-stage{ height:280px; order:-1; }
    .pillars{ grid-template-columns:1fr; }
    .trust-inner{ grid-template-columns:repeat(2,1fr); }
    .why-grid{ grid-template-columns:1fr; }
    .loc-grid{ grid-template-columns:1fr; }
    .foot-grid{ grid-template-columns:1fr; }
    .slogan-grid{ grid-template-columns:1fr; gap:28px; }
  }
  @media (max-width:520px){
    .wrap, .nav, .hero, .services, .trust, .why, .location, .cta-band, footer, .slogan-band{ padding-left:20px; padding-right:20px; }
  }
</style>
</head>
<body>

<header>
  <div class="nav">
    <a href="#top" class="brand">
      <img src="data:image/png;base64,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" alt="Guerfi Tourismo">
      <div class="brand-text">
        <div class="name">GUERFI TOURISMO</div>
        <div class="tag">وكالة سياحة وأسفار · AGENCE DE VOYAGE</div>
      </div>
    </a>
    <nav class="links">
      <a href="#omra">العمرة <span style="opacity:.6;font-size:12px;">Omra</span></a>
      <a href="#voyages">الرحلات <span style="opacity:.6;font-size:12px;">Voyages</span></a>
      <a href="#temoignages">الشهادات <span style="opacity:.6;font-size:12px;">Témoignages</span></a>
      <a href="#pourquoi">لماذا نحن <span style="opacity:.6;font-size:12px;">Pourquoi</span></a>
      <a href="#invitation">الدعوة <span style="opacity:.6;font-size:12px;">Invitation</span></a>
      <a href="#contact">اتصل بنا <span style="opacity:.6;font-size:12px;">Contact</span></a>
    </nav>
    <a class="nav-cta" href="https://wa.me/213662909518?text=Bonjour%20Guerfi%20Tourismo%2C%20j%27aimerais%20avoir%20des%20informations." target="_blank" rel="noopener">
      WhatsApp
    </a>
  </div>
</header>

<section class="hero textured" id="top">
  <div class="hero-inner">
    <div>
      <div class="eyebrow" dir="rtl" style="font-family:'Cairo',sans-serif;">معسكر · الجزائر <span style="opacity:.6;font-family:'Manrope',sans-serif;">— Mascara, Algérie</span></div>
      <h1>De Mascara, <em>vers La Mecque</em><br>et le monde entier.</h1>
      <p class="ar-text" style="font-size:19px; color:var(--cream); font-weight:700; margin:6px 0 14px;">من معسكر، إلى مكة المكرمة وكل أنحاء العالم.</p>
      <div class="slogan-ar">من معسكر إلى كل العالم
        <span class="fr">« De Mascara vers le monde entier »</span>
      </div>
      <p class="lede">Guerfi Tourismo organise vos séjours Omra et vos voyages touristiques avec un accompagnement complet, du premier appel jusqu'au retour à Mascara.</p>
      <p class="ar-text" style="font-size:14.5px; color:var(--cream-soft); max-width:480px; margin:-18px 0 26px;">تنظم قورفي توريزمو رحلات العمرة والرحلات السياحية مع مرافقة كاملة، من أول اتصال إلى العودة إلى معسكر.</p>
      <div class="hero-ctas">
        <a href="https://wa.me/213662909518?text=Bonjour%20Guerfi%20Tourismo%2C%20j%27aimerais%20un%20devis." target="_blank" rel="noopener" class="btn btn-wa btn-bi">
          <span class="ar-text">اطلب عرض سعر</span>
          <span class="fr-text">Demander un devis</span>
        </a>
        <a href="tel:+213662909518" class="btn btn-ghost btn-bi">
          <span class="ar-text">اتصل بالوكالة</span>
          <span class="fr-text">Appeler l'agence</span>
        </a>
      </div>
    </div>
    <div class="flight-stage">
      <svg viewBox="0 0 460 460" fill="none">
        <!-- radar rings around Mascara hub -->
        <circle cx="380" cy="230" r="34" stroke="rgba(212,175,55,0.35)" stroke-width="1"/>
        <circle cx="380" cy="230" r="58" stroke="rgba(212,175,55,0.22)" stroke-width="1"/>
        <circle cx="380" cy="230" r="84" stroke="rgba(212,175,55,0.12)" stroke-width="1"/>

        <!-- routes: Mascara -> destinations -->
        <path class="flight-dash" d="M380,230 C300,150 190,95 92,66"/>
        <path class="flight-dash" d="M380,230 C280,215 150,200 40,188"/>
        <path class="flight-dash" d="M380,230 C300,272 170,296 70,308"/>
        <path class="flight-dash" d="M380,230 C320,318 250,358 168,380"/>

        <!-- destination planes -->
        <g class="plane-icon" transform="translate(84,60) rotate(-158)">
          <path d="M0 12 L28 12 L40 4 L44 4 L36 12 L48 12 L54 8 L58 8 L52 16 L58 24 L54 24 L48 20 L36 20 L44 28 L40 28 L28 20 L0 20 L6 16 Z" fill="#F1D989"/>
        </g>
        <g class="plane-icon" transform="translate(32,182) rotate(-180)">
          <path d="M0 12 L28 12 L40 4 L44 4 L36 12 L48 12 L54 8 L58 8 L52 16 L58 24 L54 24 L48 20 L36 20 L44 28 L40 28 L28 20 L0 20 L6 16 Z" fill="#F1D989"/>
        </g>
        <g class="plane-icon" transform="translate(62,302) rotate(158)">
          <path d="M0 12 L28 12 L40 4 L44 4 L36 12 L48 12 L54 8 L58 8 L52 16 L58 24 L54 24 L48 20 L36 20 L44 28 L40 28 L28 20 L0 20 L6 16 Z" fill="#F1D989"/>
        </g>
        <g class="plane-icon" transform="translate(160,374) rotate(140)">
          <path d="M0 12 L28 12 L40 4 L44 4 L36 12 L48 12 L54 8 L58 8 L52 16 L58 24 L54 24 L48 20 L36 20 L44 28 L40 28 L28 20 L0 20 L6 16 Z" fill="#F1D989"/>
        </g>

        <!-- destination nodes + labels -->
        <circle cx="92" cy="66" r="5" fill="#F1D989"/>
        <text x="98" y="58" class="stage-label" dir="rtl" style="font-family:'Cairo',sans-serif;">مكة المكرمة</text>
        <text x="98" y="76" class="stage-label" style="font-size:8.5px;opacity:.65;">MAK · Omra</text>

        <circle cx="40" cy="188" r="5" fill="#F1D989"/>
        <text x="46" y="180" class="stage-label" dir="rtl" style="font-family:'Cairo',sans-serif;">إسطنبول</text>
        <text x="46" y="198" class="stage-label" style="font-size:8.5px;opacity:.65;">IST</text>

        <circle cx="70" cy="308" r="5" fill="#F1D989"/>
        <text x="76" y="300" class="stage-label" dir="rtl" style="font-family:'Cairo',sans-serif;">دبي</text>
        <text x="76" y="318" class="stage-label" style="font-size:8.5px;opacity:.65;">DXB</text>

        <circle cx="168" cy="380" r="5" fill="#F1D989"/>
        <text x="174" y="372" class="stage-label" dir="rtl" style="font-family:'Cairo',sans-serif;">باريس</text>
        <text x="174" y="390" class="stage-label" style="font-size:8.5px;opacity:.65;">CDG</text>

        <!-- Mascara hub -->
        <circle cx="380" cy="230" r="7" fill="#F1D989"/>
        <text x="392" y="222" class="stage-label" dir="rtl" style="font-family:'Cairo',sans-serif;font-size:12px;">معسكر</text>
        <rect x="388" y="228" width="44" height="16" rx="8" fill="none" stroke="#D4AF37" stroke-width="1"/>
        <text x="410" y="239" text-anchor="middle" class="stage-label" style="font-size:9px;letter-spacing:0.08em;">MSC</text>

        <text x="200" y="430" class="stage-label" dir="rtl" style="font-family:'Cairo',sans-serif;font-size:10px;opacity:.7;">و وجهات أخرى حول العالم</text>
      </svg>
    </div>
  </div>
  <div class="hairline"></div>
</section>

<section class="board-section textured">
  <div class="board">
    <div class="board-head">
      <span class="bh-ar">رحلاتنا انطلاقا من معسكر</span>
      <span class="bh-fr">✈ Départs — Aéroport de Mascara</span>
    </div>
    <div class="board-row">
      <div class="board-code">MSC → MAK</div>
      <div class="board-dest"><span class="ar">مكة المكرمة</span><span class="fr">Makkah</span></div>
      <div class="board-status omra">عمرة</div>
      <div class="board-time">Groupes réguliers</div>
    </div>
    <div class="board-row">
      <div class="board-code">MSC → MED</div>
      <div class="board-dest"><span class="ar">المدينة المنورة</span><span class="fr">Madinah</span></div>
      <div class="board-status omra">عمرة</div>
      <div class="board-time">Groupes réguliers</div>
    </div>
    <div class="board-row">
      <div class="board-code">MSC → IST</div>
      <div class="board-dest"><span class="ar">إسطنبول</span><span class="fr">Istanbul</span></div>
      <div class="board-status voyage">رحلة</div>
      <div class="board-time">Sur demande</div>
    </div>
    <div class="board-row">
      <div class="board-code">MSC → DXB</div>
      <div class="board-dest"><span class="ar">دبي</span><span class="fr">Dubaï</span></div>
      <div class="board-status voyage">رحلة</div>
      <div class="board-time">Sur demande</div>
    </div>
    <div class="board-row">
      <div class="board-code">MSC → CDG</div>
      <div class="board-dest"><span class="ar">باريس</span><span class="fr">Paris</span></div>
      <div class="board-status voyage">رحلة</div>
      <div class="board-time">Sur demande</div>
    </div>
    <div class="board-row">
      <div class="board-code">MSC → ★★★</div>
      <div class="board-dest"><span class="ar">و كل وجهات العالم</span><span class="fr">Et partout dans le monde</span></div>
      <div class="board-status voyage">رحلة</div>
      <div class="board-time">Contactez-nous</div>
    </div>
  </div>
</section>

<section class="services textured" id="voyages">
  <div class="wrap">
    <div class="section-head">
      <div class="eyebrow" dir="rtl" style="font-family:'Cairo',sans-serif;">خدماتنا <span style="opacity:.6;font-family:'Manrope',sans-serif;">— Nos prestations</span></div>
      <h2>Deux façons de voyager avec nous.</h2>
      <p class="ar-text" style="font-size:16px; color:var(--cream); font-weight:700; margin-top:6px;">طريقتان للسفر معنا.</p>
      <p>Que votre voyage soit spirituel ou touristique, notre équipe à Mascara s'occupe des réservations, des formalités et de l'accompagnement sur place.</p>
      <p class="ar-text" style="font-size:14px; color:var(--cream-soft); margin-top:-8px;">سواء كانت رحلتكم روحية أو سياحية، فريقنا في معسكر يتكفل بالحجز والإجراءات والمرافقة الميدانية.</p>
    </div>

    <div class="pillars">
      <div class="pillar" id="omra">
        <svg class="pillar-icon" viewBox="0 0 48 48" fill="none">
          <path d="M24 4 L28 16 L40 16 L30 23 L34 36 L24 28 L14 36 L18 23 L8 16 L20 16 Z" stroke="#D4AF37" stroke-width="1.6" fill="none"/>
        </svg>
        <div class="pillar-eyebrow" dir="rtl" style="font-family:'Cairo',sans-serif;">رحلة روحية <span style="opacity:.7;font-family:'Manrope',sans-serif;text-transform:none;letter-spacing:0;">— Voyage spirituel</span></div>
        <h3>العمرة <span style="font-size:0.55em; opacity:.7; font-family:'Manrope',sans-serif;">Omra</span></h3>
        <p class="ar-text" style="font-size:15px; color:var(--cream); font-weight:600; margin-bottom:6px;">برامج عمرة منظمة: تذاكر الطيران، الإقامة قرب الأماكن المقدسة، التأشيرات والمرافقة الدينية من الانطلاق إلى العودة.</p>
        <p>Programmes Omra encadrés : vols, hébergement proche des lieux saints, visas et accompagnement religieux du départ jusqu'au retour.</p>
        <ul class="pillar-list">
          <li><span class="ar-text" dir="rtl" style="display:block;">مجموعات مرافقة انطلاقا من الجزائر</span><span style="opacity:.75;">Groupes accompagnés au départ d'Algérie</span></li>
          <li><span class="ar-text" dir="rtl" style="display:block;">فنادق قريبة من المسجد الحرام والمسجد النبوي</span><span style="opacity:.75;">Hôtels proches de la Mosquée Sacrée et de la Mosquée du Prophète</span></li>
          <li><span class="ar-text" dir="rtl" style="display:block;">التكفل بالتأشيرات والإجراءات</span><span style="opacity:.75;">Prise en charge des visas et formalités</span></li>
        </ul>
        <a href="https://wa.me/213662909518?text=Bonjour%2C%20je%20souhaite%20des%20informations%20sur%20l%27Omra." target="_blank" rel="noopener" class="btn btn-bi">
          <span class="ar-text">احجز عمرتي</span>
          <span class="fr-text">Réserver mon Omra</span>
        </a>
      </div>

      <div class="pillar" id="trips">
        <svg class="pillar-icon" viewBox="0 0 48 48" fill="none">
          <path d="M6 30 L42 30 M10 30 L14 14 L18 14 L18 30 M30 30 L30 10 L38 18 L30 22" stroke="#D4AF37" stroke-width="1.6" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
        <div class="pillar-eyebrow" dir="rtl" style="font-family:'Cairo',sans-serif;">سفر واكتشاف <span style="opacity:.7;font-family:'Manrope',sans-serif;text-transform:none;letter-spacing:0;">— Voyage & découverte</span></div>
        <h3>رحلات سياحية <span style="font-size:0.5em; opacity:.7; font-family:'Manrope',sans-serif;">Voyages touristiques</span></h3>
        <p class="ar-text" style="font-size:15px; color:var(--cream); font-weight:600; margin-bottom:6px;">إقامات في الجزائر وخارجها، عائلية أو جماعية: نبني لكم البرنامج الذي يناسبكم.</p>
        <p>Séjours en Algérie et à l'étranger, en famille, entre amis ou en groupe organisé : nous construisons l'itinéraire qui vous correspond.</p>
        <ul class="pillar-list">
          <li><span class="ar-text" dir="rtl" style="display:block;">حجز الطيران، الفنادق والنقل</span><span style="opacity:.75;">Réservation vols, hôtels et transferts</span></li>
          <li><span class="ar-text" dir="rtl" style="display:block;">برامج مخصصة وإقامات جاهزة</span><span style="opacity:.75;">Circuits sur mesure et séjours clé en main</span></li>
          <li><span class="ar-text" dir="rtl" style="display:block;">أسعار جماعية وتسهيلات في الدفع</span><span style="opacity:.75;">Tarifs de groupe et paiement facilité</span></li>
        </ul>
        <a href="https://wa.me/213662909518?text=Bonjour%2C%20je%20souhaite%20des%20informations%20sur%20un%20voyage." target="_blank" rel="noopener" class="btn btn-bi">
          <span class="ar-text">خطط لرحلتي</span>
          <span class="fr-text">Planifier mon voyage</span>
        </a>
      </div>
    </div>
  </div>
</section>

<section class="testimonials textured" id="temoignages">
  <div class="wrap">
    <div class="test-head">
      <div class="eyebrow" dir="rtl" style="font-family:'Cairo',sans-serif;">وثقوا بنا <span style="opacity:.6;font-family:'Manrope',sans-serif;">— Ils nous ont fait confiance</span></div>
      <div class="ar-title">شهادات معتمرينا</div>
      <h2>Témoignages de nos pèlerins</h2>
      <p class="ar-text" style="font-size:14.5px; color:var(--cream); font-weight:600; margin-top:8px;">أصوات صادقة، مباشرة من مجموعاتنا لأداء العمرة — استمعوا إلى تجربتهم مع قورفي توريزمو.</p>
      <p>Des voix authentiques, directement de nos groupes Omra — écoutez leur expérience avec Guerfi Tourismo.</p>
    </div>
    <div class="video-grid">
      <a class="video-thumb" href="https://web.facebook.com/share/v/1CvXrtJ4zH/" target="_blank" rel="noopener">
        <span class="tag">تحضيرات <span style="opacity:.7;">Préparatifs</span></span>
        <span class="play-btn"><svg viewBox="0 0 24 24" fill="#161200"><path d="M8 5v14l11-7z"/></svg></span>
        <span class="video-caption"><span class="ar">فيديو تحضيرات العمرة</span><span class="fr">Préparatifs Omra</span></span>
      </a>
      <a class="video-thumb" href="https://web.facebook.com/share/r/1V7o5BkfQV/" target="_blank" rel="noopener">
        <span class="play-btn"><svg viewBox="0 0 24 24" fill="#161200"><path d="M8 5v14l11-7z"/></svg></span>
        <span class="video-caption"><span class="ar">شهادة معتمر 1</span><span class="fr">Témoignage 1</span></span>
      </a>
      <a class="video-thumb" href="https://web.facebook.com/share/r/18TNL7piyY/" target="_blank" rel="noopener">
        <span class="play-btn"><svg viewBox="0 0 24 24" fill="#161200"><path d="M8 5v14l11-7z"/></svg></span>
        <span class="video-caption"><span class="ar">شهادة معتمر 2</span><span class="fr">Témoignage 2</span></span>
      </a>
      <a class="video-thumb" href="https://web.facebook.com/share/v/19F2za3UTm/" target="_blank" rel="noopener">
        <span class="play-btn"><svg viewBox="0 0 24 24" fill="#161200"><path d="M8 5v14l11-7z"/></svg></span>
        <span class="video-caption"><span class="ar">شهادة معتمر 3</span><span class="fr">Témoignage 3</span></span>
      </a>
      <a class="video-thumb" href="https://web.facebook.com/share/v/14ftoxzmDok/" target="_blank" rel="noopener">
        <span class="play-btn"><svg viewBox="0 0 24 24" fill="#161200"><path d="M8 5v14l11-7z"/></svg></span>
        <span class="video-caption"><span class="ar">شهادة معتمر 4</span><span class="fr">Témoignage 4</span></span>
      </a>
      <a class="video-thumb" href="https://web.facebook.com/share/r/1EzSzaC9xh/" target="_blank" rel="noopener">
        <span class="play-btn"><svg viewBox="0 0 24 24" fill="#161200"><path d="M8 5v14l11-7z"/></svg></span>
        <span class="video-caption"><span class="ar">شهادة معتمر 5</span><span class="fr">Témoignage 5</span></span>
      </a>
    </div>

    <div class="raffle">
      <div class="raffle-copy">
        <div class="eyebrow" dir="rtl" style="font-family:'Cairo',sans-serif;">مسابقة <span style="opacity:.6;font-family:'Manrope',sans-serif;">— Concours</span></div>
        <div class="ar-title">قرعة عمرة مجانية 🎉</div>
        <h3>Tirage au sort — Omra gratuite</h3>
        <p class="ar-text" style="font-size:14px; color:var(--cream); font-weight:600;">تنظم قورفي توريزمو بانتظام قرعات للفوز بعمرة مجانية. تابعوا صفحتنا على فيسبوك وانستغرام حتى لا تفوتكم أي مسابقة.</p>
        <p>Guerfi Tourismo organise régulièrement des tirages au sort pour une Omra offerte. Suivez notre page Facebook et Instagram pour ne rater aucun concours.</p>
        <div class="hero-ctas" style="margin-top:6px;">
          <a href="https://wa.me/213662909518?text=Bonjour%2C%20je%20veux%20participer%20au%20tirage%20au%20sort%20Omra%20gratuite." target="_blank" rel="noopener" class="btn btn-wa btn-bi">
            <span class="ar-text">شارك عبر واتساب</span>
            <span class="fr-text">Participer sur WhatsApp</span>
          </a>
          <a href="https://web.facebook.com/share/r/1G2VP97K8i/" target="_blank" rel="noopener" class="btn btn-ghost btn-bi">
            <span class="ar-text">شاهد على فيسبوك</span>
            <span class="fr-text">Voir sur Facebook</span>
          </a>
        </div>
      </div>
      <a class="video-thumb raffle-video" href="https://web.facebook.com/share/r/1G2VP97K8i/" target="_blank" rel="noopener">
        <span class="tag">🎉 <span style="opacity:.7;">Tirage au sort</span></span>
        <span class="play-btn"><svg viewBox="0 0 24 24" fill="#161200"><path d="M8 5v14l11-7z"/></svg></span>
        <span class="video-caption"><span class="ar">فيديو القرعة</span><span class="fr">Vidéo du tirage au sort</span></span>
      </a>
    </div>
  </div>
</section>

<section class="slogan-band textured">
  <div class="slogan-grid">
    <div class="slogan-item">
      <div class="ar">روح تهنى، الباقي علينا</div>
      <div class="fr">Va te reposer, on s'occupe du reste</div>
    </div>
    <div class="slogan-item">
      <div class="ar">العمرة و السياحة بلا صداع</div>
      <div class="fr">L'Omra et le tourisme, sans prise de tête</div>
    </div>
    <div class="slogan-item">
      <div class="ar">من مسكرة لبيت الله، خطوة بخطوة معاك</div>
      <div class="fr">De Mascara à la Maison de Dieu, pas à pas avec vous</div>
    </div>
    <div class="slogan-item">
      <div class="ar">ثقة، راحة، و سفرة بلا هم</div>
      <div class="fr">Confiance, tranquillité, voyage sans souci</div>
    </div>
    <div class="slogan-item">
      <div class="ar">بيك نسافرو، بيك نرجعو بخير</div>
      <div class="fr">Avec toi on part, avec toi on revient bien</div>
    </div>
  </div>
</section>

<section class="trust">
  <div class="trust-inner">
    <div class="trust-item"><div class="num">عمرة</div><div class="lbl">Omra & séjours touristiques</div></div>
    <div class="trust-item"><div class="num">2</div><div class="lbl">خطان مباشران — lignes directes</div></div>
    <div class="trust-item"><div class="num">100%</div><div class="lbl">مرافقة على المقاس — sur mesure</div></div>
    <div class="trust-item"><div class="num">معسكر</div><div class="lbl">DZ — agence basée à Mascara</div></div>
  </div>
</section>

<section class="why textured" id="pourquoi">
  <div class="why-grid">
    <div class="section-head" style="margin-bottom:0;">
      <div class="eyebrow" dir="rtl" style="font-family:'Cairo',sans-serif;">لماذا قورفي توريزمو <span style="opacity:.6;font-family:'Manrope',sans-serif;">— Pourquoi Guerfi Tourismo</span></div>
      <h2>Un accompagnement du départ jusqu'au retour.</h2>
      <p class="ar-text" style="font-size:15px; color:var(--cream); font-weight:600; margin-top:6px;">مرافقة من الانطلاق إلى العودة.</p>
      <p>Une agence à taille humaine, joignable directement, qui suit votre dossier à chaque étape.</p>
      <p class="ar-text" style="font-size:13.5px; color:var(--cream-soft); margin-top:-8px;">وكالة على المقاس الإنساني، يمكن الاتصال بها مباشرة، تتابع ملفكم في كل مرحلة.</p>
    </div>
    <div class="why-list">
      <div class="why-row">
        <div class="mark">01</div>
        <div><h4>Conseil personnalisé <span class="ar-text" style="font-size:0.7em; opacity:.75; display:block;">استشارة شخصية</span></h4><p>Nous étudions votre budget et vos dates pour vous proposer la meilleure formule, Omra ou voyage touristique.</p></div>
      </div>
      <div class="why-row">
        <div class="mark">02</div>
        <div><h4>Formalités prises en charge <span class="ar-text" style="font-size:0.7em; opacity:.75; display:block;">التكفل بالإجراءات</span></h4><p>Visa, réservation d'hôtel, billets d'avion : nous gérons les démarches administratives pour vous.</p></div>
      </div>
      <div class="why-row">
        <div class="mark">03</div>
        <div><h4>Suivi jusqu'au retour <span class="ar-text" style="font-size:0.7em; opacity:.75; display:block;">متابعة إلى غاية العودة</span></h4><p>Une équipe joignable par téléphone et WhatsApp avant, pendant et après votre séjour.</p></div>
      </div>
      <div class="why-row">
        <div class="mark">04</div>
        <div><h4>Agence locale, à Mascara <span class="ar-text" style="font-size:0.7em; opacity:.75; display:block;">وكالة محلية بمعسكر</span></h4><p>Rencontrez-nous directement à l'agence, Rue Bel Air, pour finaliser votre réservation.</p></div>
      </div>
    </div>
  </div>
</section>

<section class="subscribe textured" id="invitation">
  <div class="sub-card">
    <div class="sub-copy">
      <div class="ar-title">اشترك ليصلك دعوتنا 🎁</div>
      <h2>Inscrivez-vous pour recevoir une invitation</h2>
      <p class="ar-p">اترك اسمك ورقم هاتفك، وسيصلك فريقنا بدعوة لزيارة الوكالة والاستفادة من عروضنا الحصرية.</p>
      <p>Laissez votre nom et votre numéro, notre équipe vous contactera avec une invitation à découvrir l'agence et nos offres exclusives.</p>
    </div>
    <form class="sub-form" id="subscribeForm">
      <div class="field-group">
        <label><span class="ar">الاسم الكامل</span>Nom complet</label>
        <input type="text" id="subName" placeholder="مثال: أحمد بن علي" required>
      </div>
      <div class="field-group">
        <label><span class="ar">رقم الهاتف</span>Numéro de téléphone</label>
        <input type="tel" id="subPhone" placeholder="06XX XX XX XX" required>
      </div>
      <button type="submit" class="sub-submit">
        <span class="ar-text">أرسل طلب الاشتراك</span>
        <span class="fr">Envoyer ma demande</span>
      </button>
      <div class="sub-success" id="subSuccess">✅ تم التحويل إلى واتساب — أكمل الإرسال هناك / Redirection vers WhatsApp effectuée</div>
      <div class="sub-note">📲 <span class="ar-text">يتم إرسال طلبكم مباشرة عبر واتساب</span> — Envoi direct via WhatsApp, aucune donnée n'est stockée sur ce site.</div>
    </form>
  </div>
</section>

<section class="location textured" id="contact">
  <div class="wrap">
    <div class="section-head">
      <div class="eyebrow" dir="rtl" style="font-family:'Cairo',sans-serif;">التواصل والعنوان <span style="opacity:.6;font-family:'Manrope',sans-serif;">— Contact & Adresse</span></div>
      <h2>Passez nous voir à l'agence.</h2>
      <p class="ar-text" style="font-size:15px; color:var(--cream); font-weight:600; margin-top:6px;">تعالوا لزيارتنا في الوكالة.</p>
    </div>
    <div class="loc-grid">
      <div class="loc-card">
        <div class="loc-field">
          <div class="ic">📍</div>
          <div>
            <h5>العنوان — Adresse</h5>
            <p>Rue Bel Air, à côté de Société Générale, 2ème étage — Mascara</p>
          </div>
        </div>
        <div class="loc-field">
          <div class="ic">📞</div>
          <div>
            <h5>الهاتف — Téléphone</h5>
            <a href="tel:+213662909518">0662 90 95 18</a><br>
            <a href="tel:+213666381073">0666 38 10 73</a>
          </div>
        </div>
        <div class="loc-field">
          <div class="ic">✉️</div>
          <div>
            <h5>البريد والشبكات — Email & réseaux</h5>
            <a href="mailto:guerfitourism@gmail.com">guerfitourism@gmail.com</a><br>
            <a href="https://instagram.com/guerfitourism" target="_blank" rel="noopener">@guerfitourism</a>
          </div>
        </div>
        <div class="issue-note">
          <span class="ar-text" style="display:block; margin-bottom:4px;">💬 لديكم سؤال أو مشكل يخص حجزكم؟ راسلونا مباشرة عبر واتساب، سنرد عليكم بسرعة.</span>
          <span style="opacity:.75;">Une question, un souci avec votre réservation ? Écrivez-nous directement sur WhatsApp, on vous répond vite.</span>
        </div>
        <a href="https://wa.me/213662909518" target="_blank" rel="noopener" class="btn btn-wa btn-bi" style="align-self:flex-start;">
          <span class="ar-text">تواصل عبر واتساب</span>
          <span class="fr-text">Contacter sur WhatsApp</span>
        </a>
      </div>
      <div class="map-panel">
        <iframe src="https://www.google.com/maps?q=Cit%C3%A9%20Bel%20Air%2C%20Mascara%2C%20Alg%C3%A9rie&output=embed" loading="lazy" referrerpolicy="no-referrer-when-downgrade" title="Localisation Guerfi Tourismo"></iframe>
      </div>
    </div>
  </div>
</section>

<section class="cta-band">
  <div class="slogan-ar">سفرك يبدا من عندنا</div>
  <h2>Prêt à préparer votre prochain départ ?</h2>
  <p class="ar-text" style="font-size:14.5px; color:var(--cream); font-weight:600; margin-bottom:6px;">مستعدون لتحضير رحلتكم القادمة؟</p>
  <p>Appelez l'agence, écrivez sur WhatsApp ou passez à Rue Bel Air, Mascara.</p>
  <div class="btns">
    <a href="https://wa.me/213662909518" target="_blank" rel="noopener" class="btn btn-wa">WhatsApp — 0662 90 95 18</a>
    <a href="tel:+213666381073" class="btn btn-ghost">📞 0666 38 10 73</a>
  </div>
</section>

<footer>
  <div class="foot-grid">
    <div>
      <div class="foot-brand">
        <img src="data:image/png;base64,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" alt="Guerfi Tourismo">
        <span>GUERFI TOURISMO</span>
      </div>
      <p style="max-width:320px; font-size:14px;">Agence de voyages à Mascara, spécialisée dans l'organisation de l'Omra et des séjours touristiques.</p>
      <p class="ar-text" style="max-width:320px; font-size:13.5px; margin-top:8px; color:var(--cream-soft);">وكالة أسفار بمعسكر، متخصصة في تنظيم العمرة والرحلات السياحية.</p>
    </div>
    <div>
      <h6>التصفح — Navigation</h6>
      <ul>
        <li><a href="#omra">العمرة — Omra</a></li>
        <li><a href="#voyages">الرحلات — Voyages</a></li>
        <li><a href="#pourquoi">لماذا نحن — Pourquoi nous</a></li>
        <li><a href="#contact">اتصل بنا — Contact</a></li>
      </ul>
    </div>
    <div>
      <h6>التواصل — Contact</h6>
      <ul>
        <li>Rue Bel Air, à côté de Société Générale, 2ème étage — Mascara</li>
        <li><a href="tel:+213662909518">0662 90 95 18</a></li>
        <li><a href="tel:+213666381073">0666 38 10 73</a></li>
        <li><a href="mailto:guerfitourism@gmail.com">guerfitourism@gmail.com</a></li>
        <li><a href="https://instagram.com/guerfitourism" target="_blank" rel="noopener">Instagram / Facebook @guerfitourism</a></li>
      </ul>
    </div>
  </div>
  <div class="foot-bottom">
    <span>© 2026 Guerfi Tourismo — جميع الحقوق محفوظة — Tous droits réservés.</span>
    <span>Mascara, Algérie</span>
  </div>
  <div style="max-width:1180px; margin:14px auto 0; text-align:center; font-size:11.5px; color:rgba(212,175,55,0.55); letter-spacing:0.03em;">
    <span class="ar-text" style="display:inline;">تصميم Abidat Walid</span>
    <span style="opacity:.7;"> · Conçu par Abidat Walid</span>
  </div>
</footer>

<a class="wa-float" href="https://wa.me/213662909518" target="_blank" rel="noopener" aria-label="Contacter sur WhatsApp">
  <svg viewBox="0 0 24 24" fill="#06210F"><path d="M12 2C6.48 2 2 6.48 2 12c0 1.85.5 3.58 1.36 5.07L2 22l5.06-1.33A9.94 9.94 0 0 0 12 22c5.52 0 10-4.48 10-10S17.52 2 12 2zm0 18c-1.66 0-3.2-.46-4.52-1.26l-.32-.19-3 .79.8-2.92-.21-.3A7.94 7.94 0 0 1 4 12c0-4.41 3.59-8 8-8s8 3.59 8 8-3.59 8-8 8zm4.4-5.6c-.24-.12-1.43-.7-1.65-.79-.22-.08-.38-.12-.54.12-.16.24-.62.79-.76.95-.14.16-.28.18-.52.06-.24-.12-1.02-.38-1.94-1.2-.72-.64-1.2-1.43-1.34-1.67-.14-.24-.02-.37.1-.49.11-.11.24-.28.36-.42.12-.14.16-.24.24-.4.08-.16.04-.3-.02-.42-.06-.12-.54-1.3-.74-1.78-.2-.47-.4-.4-.54-.41h-.46c-.16 0-.42.06-.64.3-.22.24-.84.82-.84 2s.86 2.32.98 2.48c.12.16 1.7 2.6 4.12 3.64.58.25 1.03.4 1.38.51.58.18 1.11.16 1.53.1.47-.07 1.43-.58 1.63-1.15.2-.56.2-1.04.14-1.15-.06-.1-.22-.16-.46-.28z"/></svg>
</a>

<script>
(function(){
  var form = document.getElementById('subscribeForm');
  if(!form) return;
  form.addEventListener('submit', function(e){
    e.preventDefault();
    var name = document.getElementById('subName').value.trim();
    var phone = document.getElementById('subPhone').value.trim();
    if(!name || !phone){ return; }
    var msg = "مرحبا Guerfi Tourismo، أريد الاشتراك للحصول على دعوة لزيارة الوكالة.\n" +
              "الاسم / Nom: " + name + "\n" +
              "الهاتف / Téléphone: " + phone;
    var url = "https://wa.me/213662909518?text=" + encodeURIComponent(msg);
    var successBox = document.getElementById('subSuccess');
    if(successBox){ successBox.classList.add('show'); }
    window.open(url, '_blank', 'noopener');
    form.reset();
  });
})();
</script>

</body>
</html>
