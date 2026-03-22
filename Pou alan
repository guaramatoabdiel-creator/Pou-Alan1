<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pou Deluxe ✨</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Fredoka+One&family=Nunito:wght@600;700;800;900&display=swap');
:root{
  --bg:#0d0820;--room:#1a0d38;--floor:#231550;
  --pou:#c8860a;--poul:#e8a020;--poud:#9a640a;
  --accent:#c084fc;--gold:#ffd700;--green:#4ade80;
  --blue:#60a5fa;--pink:#f472b6;--red:#f87171;--orange:#fb923c;
  --text:#f0e6ff;--muted:rgba(240,230,255,0.5);
  --card:rgba(255,255,255,0.05);--border:rgba(255,255,255,0.09);
}
*{margin:0;padding:0;box-sizing:border-box;}
body{
  background:radial-gradient(ellipse at 40% 20%,#2a1558,#0d0820 65%);
  font-family:'Nunito',sans-serif;
  display:flex;justify-content:center;align-items:center;
  min-height:100vh;overflow:hidden;user-select:none;
}
.phone{
  width:358px;
  background:linear-gradient(160deg,#1c0f38,#0d0820);
  border-radius:44px;padding:13px;
  box-shadow:0 0 70px rgba(180,80,255,0.3),0 0 140px rgba(100,50,200,0.12),
             inset 0 1px 0 rgba(255,255,255,0.07);
  border:1.5px solid rgba(180,100,255,0.2);
}
.screen{border-radius:32px;overflow:hidden;background:var(--room);}
.header{background:linear-gradient(180deg,#100525,#1a0d38);padding:12px 14px 10px;}
.header-top{display:flex;align-items:center;justify-content:space-between;margin-bottom:8px;}
.logo{font-family:'Fredoka One',cursive;font-size:1.2rem;color:var(--poul);text-shadow:0 0 18px rgba(232,160,32,.6);letter-spacing:.5px;}
.coins{display:flex;align-items:center;gap:5px;background:rgba(255,215,0,.1);border:1px solid rgba(255,215,0,.3);border-radius:20px;padding:3px 10px;font-size:.72rem;font-weight:800;color:var(--gold);}
.lvl-row{display:flex;align-items:center;gap:8px;margin-bottom:6px;}
.lvl-badge{background:linear-gradient(135deg,#7c3aed,#a855f7);border-radius:8px;padding:2px 8px;font-size:.6rem;font-weight:900;color:#fff;letter-spacing:.5px;white-space:nowrap;}
.xp-bg{flex:1;height:7px;background:rgba(255,255,255,.08);border-radius:10px;overflow:hidden;}
.xp-fill{height:100%;background:linear-gradient(90deg,#7c3aed,#c084fc);border-radius:10px;transition:width .6s ease;}
.xp-txt{font-size:.58rem;font-weight:800;color:var(--muted);white-space:nowrap;}
.stats{display:flex;flex-direction:column;gap:4px;}
.stat-row{display:flex;align-items:center;gap:7px;}
.stat-label{font-size:.6rem;font-weight:800;width:55px;color:var(--text);opacity:.75;text-transform:uppercase;letter-spacing:.4px;}
.stat-bg{flex:1;height:9px;background:rgba(255,255,255,.08);border-radius:10px;overflow:hidden;}
.stat-fill{height:100%;border-radius:10px;transition:width .5s ease;}
.fh{background:linear-gradient(90deg,#f97316,#fbbf24);}
.fm{background:linear-gradient(90deg,#ec4899,#f472b6);}
.fe{background:linear-gradient(90deg,#3b82f6,#60a5fa);}
.fc{background:linear-gradient(90deg,#10b981,#4ade80);}
.stat-num{font-size:.6rem;font-weight:800;color:var(--text);width:24px;text-align:right;opacity:.65;}
/* ROOM */
.room{position:relative;height:265px;background:linear-gradient(180deg,#1a0d38 58%,#231550 58%);display:flex;justify-content:center;align-items:flex-end;padding-bottom:18px;overflow:hidden;}
.stars-layer{position:absolute;top:0;left:0;width:100%;height:58%;pointer-events:none;}
.star{position:absolute;width:2px;height:2px;background:#fff;border-radius:50%;animation:twinkle var(--d,2s) ease-in-out infinite var(--delay,0s);}
@keyframes twinkle{0%,100%{opacity:.15;transform:scale(1)}50%{opacity:1;transform:scale(1.7)}}
.deco-win{position:absolute;top:16px;right:26px;width:50px;height:50px;background:linear-gradient(135deg,#1e3a5f,rgba(37,99,235,.2));border:2.5px solid #475569;border-radius:8px;display:grid;grid-template-columns:1fr 1fr;gap:3px;padding:5px;}
.deco-win::before{content:'🌙';position:absolute;top:-13px;right:5px;font-size:.7rem;}
.wp{background:rgba(96,165,250,.18);border-radius:2px;}
.deco-lamp{position:absolute;top:0;left:36px;}
.lhead{width:26px;height:13px;background:#4a2d8a;border-radius:4px 4px 0 0;margin-left:-11px;}
.lpole{width:4px;height:44px;background:#3a1e60;margin:0 auto;}
.lglow{width:0;height:0;border-left:20px solid transparent;border-right:20px solid transparent;border-top:32px solid rgba(255,220,100,.06);margin-left:-31px;}
.age-badge{position:absolute;top:9px;left:50%;transform:translateX(-50%);background:rgba(255,255,255,.06);color:rgba(255,255,255,.4);font-size:.56rem;font-weight:800;padding:2px 9px;border-radius:10px;letter-spacing:.8px;text-transform:uppercase;white-space:nowrap;}
/* POU */
.pou-wrap{position:relative;cursor:pointer;z-index:10;animation:pouFloat 3s ease-in-out infinite;transition:filter .3s;}
@keyframes pouFloat{0%,100%{transform:translateY(0)}50%{transform:translateY(-8px)}}
.pou-wrap.eating{animation:pouEat .3s ease-in-out infinite;}
@keyframes pouEat{0%,100%{transform:translateY(0)scaleY(1)}50%{transform:translateY(3px)scaleY(.93)}}
.pou-wrap.playing{animation:pouPlay .35s ease-in-out infinite;}
@keyframes pouPlay{0%,100%{transform:translateY(0)rotate(0)}25%{transform:translateY(-14px)rotate(-6deg)}75%{transform:translateY(-14px)rotate(6deg)}}
.pou-wrap.sleeping{animation:pouSleep 2s ease-in-out infinite;}
@keyframes pouSleep{0%,100%{transform:translateY(0)scaleX(1)}50%{transform:translateY(3px)scaleX(1.04)}}
.pou-wrap.bathing{animation:pouBath .45s ease-in-out infinite;}
@keyframes pouBath{0%,100%{transform:rotate(-3deg)}50%{transform:rotate(3deg)}}
.pou-wrap.bounce{animation:pouBounce .22s ease-in-out 6;}
@keyframes pouBounce{0%,100%{transform:scale(1)}50%{transform:scale(1.13)translateY(-6px)}}
.pou-wrap.spin{animation:pouSpin .4s ease-in-out 4;}
@keyframes pouSpin{0%{transform:rotate(0)}100%{transform:rotate(360deg)}}
.pou-svg{width:104px;height:123px;filter:drop-shadow(0 8px 22px rgba(0,0,0,.55));}
.zzz{position:absolute;top:-16px;right:-6px;font-size:1rem;display:none;animation:floatZ 1.5s ease-in-out infinite;}
@keyframes floatZ{0%{opacity:0;transform:translate(0,0)scale(.5)}50%{opacity:1;transform:translate(5px,-10px)scale(1)}100%{opacity:0;transform:translate(10px,-20px)scale(.5)}}
.hat-layer{position:absolute;top:-28px;left:50%;transform:translateX(-50%);font-size:1.7rem;display:none;pointer-events:none;}
.hat-layer.on{display:block;}
.bubbles-wrap{position:absolute;bottom:-3px;display:none;gap:3px;}
.pou-wrap.bathing .bubbles-wrap{display:flex;}
.bub{width:10px;height:10px;background:rgba(96,165,250,.35);border:1px solid rgba(96,165,250,.6);border-radius:50%;animation:bub .8s ease-out infinite;}
.bub:nth-child(2){animation-delay:.2s;width:7px;height:7px;}
.bub:nth-child(3){animation-delay:.4s;width:13px;height:13px;}
@keyframes bub{0%{opacity:.8;transform:scale(.5)translateY(0)}100%{opacity:0;transform:scale(1.5)translateY(-18px)}}
/* FX */
.fitem{position:absolute;font-size:1.7rem;pointer-events:none;z-index:20;animation:fup 1s ease-out forwards;}
@keyframes fup{0%{opacity:1;transform:translateY(0)scale(1)}100%{opacity:0;transform:translateY(-55px)scale(1.4)}}
.fheart{position:absolute;font-size:1rem;pointer-events:none;z-index:20;animation:hup 1.1s ease-out forwards;}
@keyframes hup{0%{opacity:1;transform:translate(0,0)scale(.5)}50%{opacity:1;transform:translate(var(--dx),-28px)scale(1.2)}100%{opacity:0;transform:translate(calc(var(--dx)*1.5),-55px)scale(.5)}}
.fcoin{position:absolute;font-size:1.1rem;pointer-events:none;z-index:20;animation:cup 1.2s ease-out forwards;}
@keyframes cup{0%{opacity:1;transform:translateY(0)scale(.8)}100%{opacity:0;transform:translateY(-50px)scale(1.3)}}
.smsg{position:absolute;top:26px;left:50%;transform:translateX(-50%);background:rgba(13,8,32,.93);color:var(--text);font-family:'Fredoka One',cursive;font-size:.8rem;padding:5px 14px;border-radius:20px;white-space:nowrap;animation:fade 2.3s ease-out forwards;pointer-events:none;z-index:30;border:1px solid rgba(255,255,255,.1);box-shadow:0 4px 20px rgba(0,0,0,.4);}
@keyframes fade{0%{opacity:0;transform:translateX(-50%)translateY(6px)}20%{opacity:1;transform:translateX(-50%)translateY(0)}70%{opacity:1}100%{opacity:0;transform:translateX(-50%)translateY(-8px)}}
/* LEVEL UP */
.lvlup{position:absolute;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.75);display:flex;flex-direction:column;justify-content:center;align-items:center;gap:10px;z-index:50;animation:lvlFade 3s ease-out forwards;pointer-events:none;}
@keyframes lvlFade{0%{opacity:0}15%{opacity:1}75%{opacity:1}100%{opacity:0}}
.lvlup-text{font-family:'Fredoka One',cursive;font-size:2rem;color:var(--gold);text-shadow:0 0 30px rgba(255,215,0,.8);animation:lvlP .4s ease-in-out infinite alternate;}
@keyframes lvlP{0%{transform:scale(1)}100%{transform:scale(1.08)}}
/* TABS */
.tabs{background:#100525;display:flex;border-top:1px solid var(--border);}
.tab{flex:1;padding:8px 4px;cursor:pointer;display:flex;flex-direction:column;align-items:center;gap:2px;font-size:.52rem;font-weight:800;text-transform:uppercase;letter-spacing:.4px;color:var(--muted);transition:all .18s;border-top:2px solid transparent;}
.tab.active{color:var(--accent);border-top-color:var(--accent);}
.tab-icon{font-size:1.1rem;}
/* PANELS */
.panel{display:none;background:linear-gradient(180deg,#100525,#0d0820);padding:12px;}
.panel.active{display:block;}
/* BUTTONS */
.actions{display:grid;grid-template-columns:1fr 1fr;gap:7px;}
.btn{background:var(--card);border:1.5px solid var(--border);border-radius:16px;padding:10px 6px;cursor:pointer;display:flex;flex-direction:column;align-items:center;gap:3px;transition:all .18s;color:var(--text);font-family:'Nunito',sans-serif;font-weight:800;font-size:.65rem;text-transform:uppercase;letter-spacing:.4px;}
.btn:hover{transform:translateY(-2px);border-color:var(--accent);}
.btn:active{transform:scale(.95);}
.btn:disabled{opacity:.3;cursor:not-allowed;transform:none;}
.btn-icon{font-size:1.45rem;}
.btn.feed{border-color:rgba(249,115,22,.35);background:linear-gradient(135deg,rgba(124,45,18,.6),rgba(67,20,7,.8));}
.btn.feed:hover{box-shadow:0 5px 18px rgba(249,115,22,.3);border-color:#f97316;}
.btn.play{border-color:rgba(236,72,153,.35);background:linear-gradient(135deg,rgba(131,24,67,.6),rgba(80,7,36,.8));}
.btn.play:hover{box-shadow:0 5px 18px rgba(236,72,153,.3);border-color:#ec4899;}
.btn.sleep{border-color:rgba(59,130,246,.35);background:linear-gradient(135deg,rgba(30,58,138,.6),rgba(23,37,84,.8));}
.btn.sleep:hover{box-shadow:0 5px 18px rgba(59,130,246,.3);border-color:#3b82f6;}
.btn.bath{border-color:rgba(16,185,129,.35);background:linear-gradient(135deg,rgba(6,78,59,.6),rgba(2,44,34,.8));}
.btn.bath:hover{box-shadow:0 5px 18px rgba(16,185,129,.3);border-color:#10b981;}
/* SHOP */
.shop-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:7px;max-height:165px;overflow-y:auto;padding-right:2px;}
.shop-grid::-webkit-scrollbar{width:3px;}
.shop-grid::-webkit-scrollbar-thumb{background:var(--accent);border-radius:3px;}
.shop-item{background:var(--card);border:1.5px solid var(--border);border-radius:14px;padding:8px 4px;cursor:pointer;display:flex;flex-direction:column;align-items:center;gap:4px;transition:all .18s;}
.shop-item:hover{transform:translateY(-2px);border-color:var(--gold);}
.shop-item.owned{border-color:var(--green);background:rgba(74,222,128,.07);}
.shop-item.equipped{border-color:var(--accent);background:rgba(192,132,252,.1);box-shadow:0 0 12px rgba(192,132,252,.3);}
.si-em{font-size:1.6rem;}
.si-name{font-size:.55rem;font-weight:800;color:var(--text);text-align:center;}
.si-price{font-size:.58rem;font-weight:800;color:var(--gold);}
.si-tag{font-size:.5rem;font-weight:800;padding:1px 5px;border-radius:6px;}
/* MINIGAMES */
.mg-grid{display:grid;grid-template-columns:1fr 1fr;gap:8px;}
.mg-card{background:var(--card);border:1.5px solid var(--border);border-radius:16px;padding:12px 8px;cursor:pointer;display:flex;flex-direction:column;align-items:center;gap:5px;transition:all .2s;}
.mg-card:hover{transform:translateY(-2px);border-color:var(--accent);box-shadow:0 6px 20px rgba(192,132,252,.2);}
.mg-icon{font-size:1.9rem;}
.mg-name{font-size:.65rem;font-weight:800;color:var(--text);text-align:center;}
.mg-reward{font-size:.55rem;font-weight:800;color:var(--gold);}
/* STATS */
.stat-card{background:var(--card);border:1px solid var(--border);border-radius:14px;padding:10px 12px;margin-bottom:7px;display:flex;justify-content:space-between;align-items:center;}
.sc-label{font-size:.68rem;font-weight:800;color:var(--muted);text-transform:uppercase;letter-spacing:.5px;}
.sc-val{font-family:'Fredoka One',cursive;font-size:1rem;color:var(--text);}
.ach{display:flex;align-items:center;gap:8px;padding:6px 0;border-bottom:1px solid var(--border);}
.ach-icon{font-size:1.3rem;}
.ach-name{font-size:.67rem;font-weight:800;color:var(--text);}
.ach-desc{font-size:.57rem;color:var(--muted);}
.ach.locked{opacity:.3;filter:grayscale(1);}
/* GAME OVERLAY */
.mg-overlay{display:none;position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.88);z-index:100;justify-content:center;align-items:center;}
.mg-overlay.open{display:flex;}
.mg-box{background:linear-gradient(145deg,#1c0f38,#0d0820);border:2px solid var(--accent);border-radius:28px;padding:20px;width:314px;max-width:95vw;box-shadow:0 0 60px rgba(192,132,252,.3);position:relative;}
.mg-close{position:absolute;top:10px;right:14px;background:none;border:none;color:var(--muted);font-size:1.3rem;cursor:pointer;}
.mg-header{font-family:'Fredoka One',cursive;font-size:1.1rem;color:var(--poul);text-align:center;margin-bottom:12px;}
.mg-info{display:flex;justify-content:space-between;align-items:center;margin-bottom:10px;}
.mg-score-lbl{font-family:'Fredoka One',cursive;font-size:.9rem;color:var(--gold);}
.mg-timer-lbl{font-family:'Fredoka One',cursive;font-size:.9rem;color:var(--accent);}
.mg-result{text-align:center;font-family:'Fredoka One',cursive;font-size:.95rem;display:none;margin-top:10px;}
/* MEMORY */
.mem-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:6px;margin-bottom:10px;}
.mem-card{aspect-ratio:1;background:linear-gradient(135deg,#2d1b5e,#1a0d38);border:2px solid var(--border);border-radius:10px;display:flex;justify-content:center;align-items:center;font-size:1.25rem;cursor:pointer;transition:all .2s;}
.mem-card.flipped{background:linear-gradient(135deg,#3d2870,#2d1b5e);border-color:var(--accent);}
.mem-card.matched{background:linear-gradient(135deg,rgba(74,222,128,.2),rgba(16,185,129,.15));border-color:var(--green);}
.mem-card.face-down{font-size:0;}
/* REACTION */
.react-area{height:95px;background:var(--card);border-radius:14px;display:flex;justify-content:center;align-items:center;cursor:pointer;border:2px solid var(--border);margin-bottom:10px;transition:all .2s;font-size:1.8rem;}
.react-area.go{background:rgba(74,222,128,.15);border-color:var(--green);}
.react-area.wait{background:rgba(248,113,113,.1);border-color:var(--red);}
/* MATH */
.math-q{font-family:'Fredoka One',cursive;font-size:1.7rem;color:var(--text);text-align:center;margin-bottom:12px;}
.math-opts{display:grid;grid-template-columns:1fr 1fr;gap:7px;}
.math-btn{background:var(--card);border:1.5px solid var(--border);border-radius:12px;padding:10px;cursor:pointer;font-family:'Fredoka One',cursive;font-size:1.2rem;color:var(--text);transition:all .18s;}
.math-btn:hover{border-color:var(--accent);}
.math-btn.correct{border-color:var(--green);background:rgba(74,222,128,.15);}
.math-btn.wrong{border-color:var(--red);background:rgba(248,113,113,.1);}
/* CATCH */
.catch-area{height:115px;background:var(--card);border-radius:14px;position:relative;overflow:hidden;border:2px solid var(--border);margin-bottom:10px;cursor:none;}
.catch-item{position:absolute;font-size:1.3rem;pointer-events:none;animation:fall var(--spd,2s) linear forwards;}
@keyframes fall{0%{top:-10%}100%{top:110%}}
.catch-basket{position:absolute;bottom:3px;font-size:1.4rem;transform:translateX(-50%);pointer-events:none;}
/* PANEL TITLES */
.panel-title{font-family:'Fredoka One',cursive;font-size:1rem;color:var(--poul);margin-bottom:10px;text-align:center;}
</style>
</head>
<body>

<div class="phone"><div class="screen">

<!-- HEADER -->
<div class="header">
  <div class="header-top">
    <div class="logo">🍫 POU DELUXE</div>
    <div class="coins">🪙 <span id="coins-val">0</span></div>
  </div>
  <div class="lvl-row">
    <div class="lvl-badge" id="lvl-badge">LVL 1</div>
    <div class="xp-bg"><div class="xp-fill" id="xp-fill" style="width:0%"></div></div>
    <div class="xp-txt" id="xp-txt">0/100 XP</div>
  </div>
  <div class="stats">
    <div class="stat-row"><span class="stat-label">🍔 Hambre</span><div class="stat-bg"><div class="stat-fill fh" id="bh" style="width:70%"></div></div><span class="stat-num" id="vh">70</span></div>
    <div class="stat-row"><span class="stat-label">😊 Humor</span><div class="stat-bg"><div class="stat-fill fm" id="bm" style="width:60%"></div></div><span class="stat-num" id="vm">60</span></div>
    <div class="stat-row"><span class="stat-label">⚡ Energía</span><div class="stat-bg"><div class="stat-fill fe" id="be" style="width:80%"></div></div><span class="stat-num" id="ve">80</span></div>
    <div class="stat-row"><span class="stat-label">🚿 Limpieza</span><div class="stat-bg"><div class="stat-fill fc" id="bc" style="width:90%"></div></div><span class="stat-num" id="vc">90</span></div>
  </div>
</div>

<!-- ROOM -->
<div class="room" id="room">
  <div class="stars-layer" id="stars"></div>
  <div class="deco-win"><div class="wp"></div><div class="wp"></div><div class="wp"></div><div class="wp"></div></div>
  <div class="deco-lamp"><div class="lhead"></div><div class="lpole"></div><div class="lglow"></div></div>
  <div class="age-badge" id="age">Bebé · Día 1</div>
  <div class="pou-wrap" id="pou" onclick="petPou()">
    <div class="zzz" id="zzz">💤</div>
    <div class="hat-layer" id="hat-layer"></div>
    <div class="bubbles-wrap"><div class="bub"></div><div class="bub"></div><div class="bub"></div></div>
    <svg class="pou-svg" viewBox="0 0 110 130" xmlns="http://www.w3.org/2000/svg">
      <ellipse cx="55" cy="126" rx="33" ry="5" fill="rgba(0,0,0,.3)"/>
      <ellipse cx="35" cy="44" rx="14" ry="17" fill="#c8860a"/>
      <ellipse cx="55" cy="39" rx="14" ry="17" fill="#c8860a"/>
      <ellipse cx="75" cy="44" rx="14" ry="17" fill="#c8860a"/>
      <ellipse cx="55" cy="82" rx="42" ry="44" fill="#c8860a"/>
      <ellipse cx="50" cy="73" rx="16" ry="20" fill="rgba(255,200,80,.17)"/>
      <ellipse cx="17" cy="74" rx="10" ry="13" fill="#b8760a"/>
      <ellipse cx="93" cy="74" rx="10" ry="13" fill="#b8760a"/>
      <ellipse cx="17" cy="74" rx="6" ry="8" fill="#c8860a"/>
      <ellipse cx="93" cy="74" rx="6" ry="8" fill="#c8860a"/>
      <ellipse cx="55" cy="80" rx="30" ry="27" fill="#e89818"/>
      <ellipse cx="43" cy="71" rx="9" ry="10" fill="white"/>
      <ellipse cx="67" cy="71" rx="9" ry="10" fill="white"/>
      <g id="g-pupils"><ellipse cx="44" cy="72" rx="5" ry="6" fill="#1a1a2e"/><ellipse cx="68" cy="72" rx="5" ry="6" fill="#1a1a2e"/><ellipse cx="46" cy="70" rx="2" ry="2.4" fill="white"/><ellipse cx="70" cy="70" rx="2" ry="2.4" fill="white"/></g>
      <g id="g-eyes-sleep" display="none"><path d="M34 71 Q43 64 52 71" stroke="#7a5a0a" stroke-width="2.5" fill="none" stroke-linecap="round"/><path d="M58 71 Q67 64 76 71" stroke="#7a5a0a" stroke-width="2.5" fill="none" stroke-linecap="round"/></g>
      <g id="g-eyes-happy" display="none"><path d="M34 73 Q43 63 52 73" stroke="#1a1a2e" stroke-width="3" fill="none" stroke-linecap="round"/><path d="M58 73 Q67 63 76 73" stroke="#1a1a2e" stroke-width="3" fill="none" stroke-linecap="round"/></g>
      <g id="g-eyes-angry" display="none"><line x1="34" y1="65" x2="52" y2="70" stroke="#7a5a0a" stroke-width="2.5" stroke-linecap="round"/><line x1="76" y1="65" x2="58" y2="70" stroke="#7a5a0a" stroke-width="2.5" stroke-linecap="round"/><ellipse cx="44" cy="73" rx="5" ry="6" fill="#1a1a2e"/><ellipse cx="68" cy="73" rx="5" ry="6" fill="#1a1a2e"/></g>
      <
