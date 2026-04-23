<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
<title>うわさのゲームセンター</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=DotGothic16&family=Press+Start+2P&display=swap');
:root{
  --pink:#FF2D78; --cyan:#00F5FF; --yellow:#FFE600;
  --green:#39FF14; --purple:#BF00FF;
  --dark:#060410; --darker:#030208;
}
*{margin:0;padding:0;box-sizing:border-box;-webkit-tap-highlight-color:transparent;}
html,body{
  background:var(--darker);width:100%;min-height:100vh;
  font-family:'Press Start 2P',monospace;
  overflow-x:hidden;color:#fff;touch-action:manipulation;
}
/* CRT */
body::before{content:'';position:fixed;inset:0;pointer-events:none;z-index:9999;
  background:repeating-linear-gradient(0deg,transparent,transparent 2px,rgba(0,0,0,.15) 2px,rgba(0,0,0,.15) 4px);}
body::after{content:'';position:fixed;inset:0;pointer-events:none;z-index:9998;
  background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.8) 100%);}
.wrap{
  max-width:480px;margin:0 auto;min-height:100vh;
  display:flex;flex-direction:column;align-items:center;
  background:
    radial-gradient(ellipse at 20% 0%,rgba(191,0,255,.18) 0%,transparent 55%),
    radial-gradient(ellipse at 80% 20%,rgba(0,245,255,.12) 0%,transparent 55%),
    var(--dark);
}

/* MARQUEE */
.marquee{width:100%;background:var(--pink);padding:5px 0;overflow:hidden;box-shadow:0 0 18px var(--pink);}
.marquee-in{display:inline-block;white-space:nowrap;animation:mq 22s linear infinite;font-size:8px;color:#000;letter-spacing:2px;}
@keyframes mq{from{transform:translateX(100vw)}to{transform:translateX(-100%)}}

/* TOP BAR */
.topbar{width:100%;background:#000;padding:6px 14px;
  display:flex;justify-content:space-between;align-items:center;
  border-bottom:1px solid #1a1a1a;}
.tb-txt{font-size:7px;color:var(--yellow);text-shadow:0 0 6px var(--yellow);}
.tb-val{font-size:9px;color:var(--green);text-shadow:0 0 8px var(--green);}

/* TITLE SIGN */
.sign{margin-top:20px;text-align:center;padding:0 12px;}
.sign-en{font-family:'DotGothic16',sans-serif;font-size:10px;color:var(--cyan);
  letter-spacing:6px;text-shadow:0 0 12px var(--cyan);margin-bottom:5px;
  animation:flicker 4s infinite;}
.sign-ja{font-family:'DotGothic16',sans-serif;font-size:clamp(26px,7vw,34px);
  font-weight:900;line-height:1.2;letter-spacing:3px;
  background:linear-gradient(180deg,#fff 0%,var(--yellow) 45%,var(--pink) 100%);
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;
  filter:drop-shadow(0 0 18px rgba(255,230,0,.8)) drop-shadow(0 0 36px rgba(255,45,120,.5));
  animation:tp 2.5s ease-in-out infinite;}
.sign-stars{font-size:13px;color:var(--yellow);text-shadow:0 0 10px var(--yellow);
  margin-top:4px;letter-spacing:4px;}
@keyframes tp{
  0%,100%{filter:drop-shadow(0 0 14px rgba(255,230,0,.7)) drop-shadow(0 0 30px rgba(255,45,120,.5))}
  50%{filter:drop-shadow(0 0 28px rgba(255,230,0,1)) drop-shadow(0 0 56px rgba(255,45,120,.9))}}
@keyframes flicker{0%,19%,21%,23%,25%,54%,56%,100%{opacity:1}20%,22%,24%,55%{opacity:.3}}

/* DECO LIGHTS */
.lights{width:100%;display:flex;gap:5px;padding:0 12px;margin:12px 0 0;
  justify-content:center;flex-wrap:wrap;}
.ld{width:8px;height:8px;border-radius:50%;animation:lc 1.2s steps(1) infinite;}
.ld:nth-child(4n+1){background:var(--pink);  box-shadow:0 0 6px var(--pink);  animation-delay:0s}
.ld:nth-child(4n+2){background:var(--yellow);box-shadow:0 0 6px var(--yellow);animation-delay:.3s}
.ld:nth-child(4n+3){background:var(--cyan);  box-shadow:0 0 6px var(--cyan);  animation-delay:.6s}
.ld:nth-child(4n+4){background:var(--green); box-shadow:0 0 6px var(--green); animation-delay:.9s}
@keyframes lc{0%,49%{opacity:1}50%,100%{opacity:.15}}

/* COIN INSERT */
.coin-insert{margin:12px 0 6px;display:flex;align-items:center;gap:10px;
  animation:blink 1s steps(1) infinite;font-size:8px;
  color:var(--yellow);text-shadow:0 0 10px var(--yellow);}
.ci{font-size:18px;animation:cs .8s steps(4) infinite;}
@keyframes blink{0%,49%{opacity:1}50%,100%{opacity:0}}
@keyframes cs{0%{transform:rotateY(0)}100%{transform:rotateY(360deg)}}

/* ── SECTION TITLES ── */
.section-title{
  width:calc(100% - 24px);margin:16px 12px 8px;
  font-size:9px;letter-spacing:3px;
  display:flex;align-items:center;gap:10px;
}
.section-title::before,.section-title::after{
  content:'';flex:1;height:1px;
}
.section-title.games{color:var(--pink);}
.section-title.games::before,.section-title.games::after{background:var(--pink);}
.section-title.rank{color:var(--yellow);}
.section-title.rank::before,.section-title.rank::after{background:var(--yellow);}

/* ── GAME CARDS ── */
.game-list{width:100%;padding:0 12px;display:flex;flex-direction:column;gap:10px;}

.game-card{
  background:#0a0818;border-radius:10px;overflow:hidden;
  cursor:pointer;display:flex;align-items:stretch;
  transition:transform .15s,box-shadow .15s;
  -webkit-user-select:none;
}
.game-card:active{transform:scale(.97)}
.game-card.uwasa{border:2px solid var(--pink);  box-shadow:0 0 16px rgba(255,45,120,.5)}
.game-card.soon {border:2px solid #333;         opacity:.55;cursor:default}
.game-card:hover.uwasa{box-shadow:0 0 28px rgba(255,45,120,.9),inset 0 0 20px rgba(255,45,120,.08)}

/* Screen thumb */
.gc-screen{
  width:90px;flex-shrink:0;display:flex;align-items:center;
  justify-content:center;font-size:36px;position:relative;overflow:hidden;
}
.gc-screen::after{
  content:'';position:absolute;inset:0;pointer-events:none;
  background:repeating-linear-gradient(0deg,transparent,transparent 3px,rgba(0,0,0,.12) 3px,rgba(0,0,0,.12) 4px);}
.game-card.uwasa .gc-screen{background:linear-gradient(135deg,#1a0020,#2a0010)}
.game-card.soon  .gc-screen{background:linear-gradient(135deg,#0a0a0a,#111)}
.gc-emoji{filter:drop-shadow(0 0 12px currentColor);animation:sf 2s ease-in-out infinite;}
.game-card.uwasa .gc-emoji{color:var(--pink)}
@keyframes sf{0%,100%{transform:translateY(0)}50%{transform:translateY(-4px)}}

/* Pixel runner */
.px-runner{position:absolute;bottom:6px;left:50%;transform:translateX(-50%);display:flex;gap:5px;}
.px-runner span{width:6px;height:6px;border-radius:1px;animation:rb .4s steps(2) infinite;}
.px-runner span:nth-child(1){background:var(--pink)}
.px-runner span:nth-child(2){background:var(--cyan);animation-delay:.2s}
.px-runner span:nth-child(3){background:var(--yellow);animation-delay:.1s}
@keyframes rb{0%{transform:translateY(0)}100%{transform:translateY(-5px)}}

/* Card info */
.gc-info{flex:1;padding:12px 14px;display:flex;flex-direction:column;justify-content:center;}
.gc-title{font-size:11px;margin-bottom:5px;line-height:1.4;}
.game-card.uwasa .gc-title{color:var(--pink);text-shadow:0 0 8px var(--pink)}
.game-card.soon  .gc-title{color:#444}
.gc-desc{font-family:'DotGothic16',sans-serif;font-size:11px;color:rgba(255,255,255,.5);line-height:1.5;}
.gc-tags{margin-top:6px;display:flex;gap:6px;flex-wrap:wrap;}
.tag{font-family:'DotGothic16',sans-serif;font-size:9px;padding:2px 6px;border-radius:3px;}
.tag.hot {background:var(--pink); color:#fff;animation:badgep .6s steps(2) infinite}
.tag.new {background:var(--green);color:#000}
.tag.soon{background:#222;       color:#555}
@keyframes badgep{0%{opacity:1}100%{opacity:.4}}

/* ── OVERALL RANKING ── */
.ranking-box{
  width:calc(100% - 24px);margin:0 12px;
  background:#0a0a0a;border:2px solid var(--yellow);border-radius:8px;
  padding:12px 14px;box-shadow:0 0 18px rgba(255,230,0,.3);
}
.rank-header{
  display:flex;justify-content:space-between;align-items:center;
  margin-bottom:10px;
}
.rank-label{font-size:8px;color:var(--yellow);text-shadow:0 0 8px var(--yellow);letter-spacing:2px;}
.rank-period{font-family:'DotGothic16',sans-serif;font-size:10px;color:rgba(255,255,255,.35);}
/* GAME TABS */
.rank-tabs{display:flex;gap:6px;margin-bottom:10px;flex-wrap:wrap;}
.rtab{
  font-family:'DotGothic16',sans-serif;font-size:10px;
  padding:4px 10px;border-radius:4px;border:1px solid #333;
  color:rgba(255,255,255,.4);background:#111;cursor:pointer;
  transition:all .15s;
}
.rtab.active.uwasa{border-color:var(--pink);  color:var(--pink);  background:rgba(255,45,120,.12);  box-shadow:0 0 8px rgba(255,45,120,.4)}
.rtab.active.total{border-color:var(--yellow);color:var(--yellow);background:rgba(255,230,0,.1);   box-shadow:0 0 8px rgba(255,230,0,.3)}
.rank-list{font-family:'DotGothic16',sans-serif;font-size:13px;min-height:120px;}
.rank-row{display:flex;justify-content:space-between;align-items:center;
  padding:7px 2px;border-bottom:1px solid rgba(255,255,255,.05);}
.rank-empty{color:rgba(255,255,255,.3);font-size:11px;text-align:center;padding:20px 0;line-height:1.8;}
.prize-note{
  margin-top:10px;padding:10px;border-radius:6px;
  border:1px dashed rgba(255,230,0,.3);
  font-family:'DotGothic16',sans-serif;font-size:10px;
  color:rgba(255,255,255,.45);text-align:center;line-height:1.9;
}

/* USB FOOTER */
.footer{margin-top:16px;text-align:center;padding:0 16px 34px;}
.footer-logo{font-family:'DotGothic16',sans-serif;font-size:13px;color:var(--cyan);
  text-shadow:0 0 12px var(--cyan);letter-spacing:4px;margin-bottom:4px;}
.footer-sub{font-family:'DotGothic16',sans-serif;font-size:10px;color:rgba(255,255,255,.28);letter-spacing:2px;}

/* ── GAME MODAL (iframe) ── */
#gm{display:none;position:fixed;inset:0;background:#000;z-index:5000;flex-direction:column;}
#gm.open{display:flex}
#gm-close{
  position:absolute;top:10px;left:10px;z-index:5100;
  background:rgba(0,0,0,.88);border:2px solid var(--pink);
  color:var(--pink);font-family:'Press Start 2P',monospace;
  font-size:9px;padding:8px 12px;border-radius:6px;cursor:pointer;
  box-shadow:0 0 12px rgba(255,45,120,.5);letter-spacing:1px;
}
#gm-close:active{transform:scale(.95)}
#gm-frame{width:100%;height:100%;border:none;display:block;}
</style>
</head>
<body>
<div class="wrap">

  <!-- MARQUEE -->
  <div class="marquee">
    <span class="marquee-in">★ うわさのゲームセンター ★ UWASA GAME CENTER ★ 金沢市 片町 ★ U.wasano Shisha Bar presents ★ UWASA BROTHERS 稼働中！ ★ コイン数でランキング決定！ ★ 今週1位はシーシャ1台フリー！ ★</span>
  </div>

  <!-- TOP BAR -->
  <div class="topbar">
    <span class="tb-txt">CREDIT</span>
    <span class="tb-val">● FREE PLAY ●</span>
    <span class="tb-txt" id="clk">--:--</span>
  </div>

  <!-- TITLE -->
  <div class="sign">
    <div class="sign-en">U . W A S A N O</div>
    <div class="sign-ja">うわさの<br>ゲームセンター</div>
    <div class="sign-stars">★ ★ ★ ★ ★</div>
  </div>

  <!-- DECO LIGHTS -->
  <div class="lights">
    <div class="ld"></div><div class="ld"></div><div class="ld"></div><div class="ld"></div>
    <div class="ld"></div><div class="ld"></div><div class="ld"></div><div class="ld"></div>
    <div class="ld"></div><div class="ld"></div><div class="ld"></div><div class="ld"></div>
    <div class="ld"></div><div class="ld"></div><div class="ld"></div><div class="ld"></div>
  </div>
  <div class="coin-insert">
    <span class="ci">🪙</span><span>PUSH START</span><span class="ci">🪙</span>
  </div>

  <!-- ── GAMES SECTION ── -->
  <div class="section-title games">🕹 GAMES</div>

  <div class="game-list">

    <!-- UWASA BROTHERS -->
    <div class="game-card uwasa" onclick="openGame('uwasa-brothers-final.html')">
      <div class="gc-screen">
        <span class="gc-emoji">🎮</span>
        <div class="px-runner"><span></span><span></span><span></span></div>
      </div>
      <div class="gc-info">
        <div class="gc-title">UWASA BROTHERS</div>
        <div class="gc-desc">石川縦断30ステージ！<br>ボス6体を倒せ！</div>
        <div class="gc-tags">
          <span class="tag hot">★ HOT</span>
          <span class="tag new">RANKING</span>
        </div>
      </div>
    </div>

    <!-- COMING SOON 1 -->
    <div class="game-card soon">
      <div class="gc-screen">
        <span class="gc-emoji" style="font-size:32px;color:#333">❓</span>
      </div>
      <div class="gc-info">
        <div class="gc-title">NEW GAME #2</div>
        <div class="gc-desc">近日公開予定...</div>
        <div class="gc-tags"><span class="tag soon">COMING SOON</span></div>
      </div>
    </div>

    <!-- COMING SOON 2 -->
    <div class="game-card soon">
      <div class="gc-screen">
        <span class="gc-emoji" style="font-size:32px;color:#333">❓</span>
      </div>
      <div class="gc-info">
        <div class="gc-title">NEW GAME #3</div>
        <div class="gc-desc">近日公開予定...</div>
        <div class="gc-tags"><span class="tag soon">COMING SOON</span></div>
      </div>
    </div>

  </div>

  <!-- ── RANKING SECTION ── -->
  <div class="section-title rank">🏆 RANKING</div>

  <div class="ranking-box">
    <div class="rank-header">
      <span class="rank-label">WEEKLY TOP 10</span>
      <span class="rank-period" id="rank-period">今週</span>
    </div>

    <!-- GAME TABS -->
    <div class="rank-tabs">
      <div class="rtab active uwasa" onclick="switchTab('uwasa')" id="tab-uwasa">UWASA BROTHERS</div>
      <div class="rtab total"        onclick="switchTab('total')" id="tab-total">TOTAL</div>
    </div>

    <div class="rank-list" id="rank-list">
      <div class="rank-empty">読み込み中...</div>
    </div>

    <div class="prize-note">
      <span style="color:var(--yellow)">🪙 コイン数</span>でランキング決定！<br>
      ゲームオーバー時に名前を入力すると自動登録。<br>
      <span style="color:var(--pink)">毎週月曜0時リセット</span><br>
      <b>今週1位はシーシャ1台フリー！🎮</b>
    </div>
  </div>

  <!-- USB FOOTER -->
  <div class="footer">
    <div class="footer-logo">U.wasano Shisha Bar</div>
    <div class="footer-sub">KANAZAWA × KATAMACHI</div>
  </div>

</div><!-- /wrap -->

<!-- GAME MODAL -->
<div id="gm">
  <button id="gm-close" onclick="closeGame()">✕ CLOSE</button>
  <iframe id="gm-frame" src="" allowfullscreen></iframe>
</div>

<script>
// ── Supabase ──
const SUPABASE_URL = '';  // ← ここに貼る
const SUPABASE_KEY = '';  // ← ここに貼る

// ── Clock ──
function tick(){
  const n=new Date();
  document.getElementById('clk').textContent=
    String(n.getHours()).padStart(2,'0')+':'+String(n.getMinutes()).padStart(2,'0');
}
tick(); setInterval(tick,10000);

// ── Period label ──
(function(){
  const n=new Date();
  const mon=new Date(n);
  mon.setDate(n.getDate()-((n.getDay()+6)%7));
  mon.setHours(0,0,0,0);
  const fmt=d=>`${d.getMonth()+1}/${d.getDate()}`;
  const sun=new Date(mon); sun.setDate(mon.getDate()+6);
  document.getElementById('rank-period').textContent=fmt(mon)+'〜'+fmt(sun);
})();

// ── Coin SFX ──
function playCoin(){
  try{
    const ac=new(window.AudioContext||window.webkitAudioContext)();
    const o=ac.createOscillator(),g=ac.createGain();
    o.type='square';
    o.frequency.setValueAtTime(800,ac.currentTime);
    o.frequency.exponentialRampToValueAtTime(1400,ac.currentTime+.06);
    o.frequency.exponentialRampToValueAtTime(700,ac.currentTime+.18);
    g.gain.setValueAtTime(.25,ac.currentTime);
    g.gain.exponentialRampToValueAtTime(.001,ac.currentTime+.22);
    o.connect(g); g.connect(ac.destination);
    o.start(); o.stop(ac.currentTime+.22);
  }catch(e){}
}

// ── Open game in iframe ──
function openGame(src){
  playCoin();
  const fl=document.createElement('div');
  fl.style.cssText='position:fixed;inset:0;background:#fff;z-index:99999;opacity:.7;pointer-events:none;transition:opacity .25s';
  document.body.appendChild(fl);
  setTimeout(()=>fl.style.opacity='0',40);
  setTimeout(()=>{
    fl.remove();
    document.getElementById('gm-frame').src=src;
    document.getElementById('gm').classList.add('open');
    document.body.style.overflow='hidden';
  },260);
}
function closeGame(){
  document.getElementById('gm').classList.remove('open');
  document.getElementById('gm-frame').src='';
  document.body.style.overflow='';
  loadRanking(currentTab);
}

// ── Ranking ──
let currentTab='uwasa';

function switchTab(tab){
  currentTab=tab;
  document.querySelectorAll('.rtab').forEach(t=>t.classList.remove('active','uwasa','total'));
  const el=document.getElementById('tab-'+tab);
  el.classList.add('active',tab);
  loadRanking(tab);
}

function getMonday(){
  const n=new Date();
  const d=new Date(n);
  d.setDate(n.getDate()-((n.getDay()+6)%7));
  d.setHours(0,0,0,0);
  return d.toISOString();
}

async function fetchRanking(game, limit=10){
  if(!SUPABASE_URL||!SUPABASE_KEY) return null;
  try{
    // game フィルター: 'uwasa_brothers' か 全ゲーム合算
    let url=SUPABASE_URL+'/rest/v1/scores?select=player_name,coins,score,stage,game&created_at=gte.'+getMonday()+'&order=coins.desc&limit='+limit;
    if(game!=='total') url+='&game=eq.'+game;
    const r=await fetch(url,{headers:{apikey:SUPABASE_KEY,Authorization:'Bearer '+SUPABASE_KEY}});
    return r.ok?await r.json():null;
  }catch(e){return null;}
}

async function loadRanking(tab){
  const el=document.getElementById('rank-list');
  el.innerHTML='<div class="rank-empty">読み込み中...</div>';

  const game = tab==='uwasa'?'uwasa_brothers':'total';
  const data = await fetchRanking(game);

  if(!data){
    el.innerHTML=`<div class="rank-empty">⚠ Supabase未設定<br>URLとAPIキーを入力すると<br>ランキングが表示されます</div>`;
    return;
  }
  if(!data.length){
    el.innerHTML='<div class="rank-empty">まだ記録がありません！<br>最初のプレイヤーになろう 🎮</div>';
    return;
  }

  const medals=['🥇','🥈','🥉'];
  const colors=['var(--yellow)','#C0C0C0','#CD7F32','rgba(255,255,255,.65)'];

  el.innerHTML=data.map((row,i)=>{
    const medal = i<3 ? medals[i] : (i+1)+'位';
    const col   = colors[Math.min(i,3)];
    const name  = (row.player_name||'???').substring(0,8);
    const stage = (row.stage||0)+1;
    return `<div class="rank-row">
      <span style="font-size:15px;width:28px">${medal}</span>
      <span style="font-family:'DotGothic16',sans-serif;font-size:13px;color:${col};flex:1;margin-left:6px">${name}</span>
      <span style="color:var(--yellow);font-family:'DotGothic16',sans-serif;font-size:13px">🪙 ${row.coins||0}</span>
      <span style="color:rgba(255,255,255,.3);font-family:'DotGothic16',sans-serif;font-size:10px;margin-left:7px">ST${stage}</span>
    </div>`;
  }).join('');
}

// ── Keyboard ──
document.addEventListener('keydown',e=>{
  const open=document.getElementById('gm').classList.contains('open');
  if(!open&&(e.code==='Space'||e.code==='Enter')){e.preventDefault();openGame('uwasa-brothers-final.html');}
  if(e.code==='Escape'&&open)closeGame();
});

// ── Init ──
loadRanking('uwasa');
</script>
</body>
</html>
