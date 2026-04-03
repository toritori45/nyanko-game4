<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
<title>にゃんこ合体！</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{display:flex;flex-direction:column;align-items:center;padding:16px;min-height:100vh;background:#fff8f0;font-family:sans-serif;background-image:radial-gradient(circle at 20% 20%,#ffe0b2 0%,transparent 50%),radial-gradient(circle at 80% 80%,#ffccbc 0%,transparent 50%);user-select:none;-webkit-user-select:none}
h1{font-size:1.6rem;font-weight:900;color:#ff7043;margin-bottom:2px;text-shadow:2px 2px 0 #ffb300}
.sub{font-size:0.75rem;color:#a07050;margin-bottom:10px}
.bar{display:flex;gap:8px;margin-bottom:12px;align-items:center}
.sb{background:#ff7043;color:white;border-radius:10px;padding:4px 14px;text-align:center}
.bb{background:#ffb300;color:white;border-radius:10px;padding:4px 14px;text-align:center}
.lb{font-size:0.55rem;font-weight:700;letter-spacing:.1em}
.vl{font-size:1.2rem;font-weight:900}
.rbtn{background:white;border:2px solid #ff7043;color:#ff7043;border-radius:10px;padding:5px 12px;font-size:0.8rem;font-weight:700;cursor:pointer}
.gw{background:#f0d9c0;border-radius:14px;padding:8px;box-shadow:0 6px 0 #c8a882;position:relative}
.grid{display:grid;grid-template-columns:repeat(4,72px);grid-template-rows:repeat(4,72px);gap:8px;position:relative;width:320px;height:320px}
.cell{background:#e8c9a8;border-radius:10px}
.tile{position:absolute;width:72px;height:72px;border-radius:10px;display:flex;flex-direction:column;align-items:center;justify-content:center;font-size:1.7rem;z-index:2;transition:top .08s,left .08s}
.tnm{font-size:0.42rem;font-weight:700;opacity:.85;margin-top:1px}
.t2{background:#fff9c4;color:#5d4037}
.t4{background:#ffe082;color:#4a2f1a}
.t8{background:#ffb74d;color:white}
.t16{background:#ff8a65;color:white}
.t32{background:#f06292;color:white}
.t64{background:#ba68c8;color:white}
.t128{background:#7986cb;color:white}
.t256{background:#4db6ac;color:white}
.t512{background:#81c784;color:white}
.t1024{background:#4caf50;color:white}
.t2048{background:linear-gradient(135deg,#ff6f00,#ffd54f);color:white}
.ov{position:absolute;inset:0;background:rgba(255,248,240,.93);border-radius:14px;display:none;flex-direction:column;align-items:center;justify-content:center;gap:8px;z-index:10}
.ov.show{display:flex}
.ov h2{font-size:1.5rem;font-weight:900;color:#ff7043}
.ov p{font-size:.85rem;color:#a07050}
.arrbtn{display:flex;flex-direction:column;align-items:center;margin-top:10px;gap:4px}
.arow{display:flex;gap:4px}
.ab{width:44px;height:44px;background:white;border:2px solid #ff7043;color:#ff7043;border-radius:10px;font-size:1.2rem;cursor:pointer;display:flex;align-items:center;justify-content:center;font-weight:700}
.ab:active{background:#fff0eb}
.clog{margin-top:12px;background:white;border-radius:10px;padding:8px 12px;width:320px;box-shadow:0 3px 0 #e8c9a8}
.clog h3{font-size:.65rem;font-weight:700;color:#a07050;letter-spacing:.1em;margin-bottom:5px}
.clist{display:flex;flex-wrap:wrap;gap:4px}
.cb{background:#e8c9a8;border-radius:6px;padding:2px 6px;font-size:.62rem;opacity:.3;transition:opacity .3s}
.cb.on{opacity:1}
.hint{margin-top:8px;font-size:.65rem;color:#b09070}
.nya{position:fixed;pointer-events:none;font-size:1.8rem;font-weight:900;color:#ff7043;text-shadow:2px 2px 0 #ffb300;animation:nyafly 0.8s ease-out forwards;z-index:999}
@keyframes nyafly{0%{opacity:1;transform:translateY(0) scale(1)}100%{opacity:0;transform:translateY(-60px) scale(1.4)}}
</style>
</head>
<body>
<h1>🐱 にゃんこ合体！</h1>
<p class="sub">同じ猫をぶつけて進化させよう！神猫を目指せ</p>
<div class="bar">
  <div class="sb"><div class="lb">スコア</div><div class="vl" id="sc">0</div></div>
  <div class="bb"><div class="lb">ベスト</div><div class="vl" id="bs">0</div></div>
  <button class="rbtn" id="rbtn">リセット</button>
</div>
<div class="gw" id="gw">
  <div class="grid" id="grid">
    <div class="cell"></div><div class="cell"></div><div class="cell"></div><div class="cell"></div>
    <div class="cell"></div><div class="cell"></div><div class="cell"></div><div class="cell"></div>
    <div class="cell"></div><div class="cell"></div><div class="cell"></div><div class="cell"></div>
    <div class="cell"></div><div class="cell"></div><div class="cell"></div><div class="cell"></div>
  </div>
  <div class="ov" id="ov">
    <h2 id="ovT"></h2><p id="ovM"></p>
    <button class="rbtn" id="ovbtn">もう一度！</button>
  </div>
</div>
<div class="arrbtn">
  <div class="arow"><button class="ab" id="bu">↑</button></div>
  <div class="arow">
    <button class="ab" id="bl">←</button>
    <button class="ab" id="bd">↓</button>
    <button class="ab" id="br">→</button>
  </div>
</div>
<div class="clog">
  <h3>🐾 図鑑</h3>
  <div class="clist" id="clist"></div>
</div>
<p class="hint">ボタンまたはキーボード矢印キーで操作 / スワイプも対応</p>

<script>
const CATS=[
  {v:2,e:'🐱',n:'チビ猫'},{v:4,e:'😺',n:'普通猫'},{v:8,e:'😸',n:'デブ猫'},
  {v:16,e:'😹',n:'ながい猫'},{v:32,e:'😻',n:'おじさん猫'},{v:64,e:'🙀',n:'武士猫'},
  {v:128,e:'😾',n:'社長猫'},{v:256,e:'😼',n:'仙人猫'},{v:512,e:'🐯',n:'王様猫'},
  {v:1024,e:'🦁',n:'宇宙猫'},{v:2048,e:'✨',n:'神猫'}
];
const SZ=72,GAP=8;
function px(i){return i*(SZ+GAP);}
let B,sc,best,unlocked,dead;
let audioCtx=null;

function getAudioCtx(){
  if(!audioCtx) audioCtx=new(window.AudioContext||window.webkitAudioContext)();
  return audioCtx;
}

// ニャーの鳴き声を合成音で生成
function playNya(val){
  try{
    const ctx=getAudioCtx();
    // 合体レベルに応じて音程を変える
    const level=Math.log2(val||2);
    const baseFreq=300+level*40;

    // オシレーター1（メイン音）
    const osc1=ctx.createOscillator();
    const gain1=ctx.createGain();
    osc1.connect(gain1);
    gain1.connect(ctx.destination);
    osc1.type='sine';
    // 音程をニャーっぽく変化させる
    osc1.frequency.setValueAtTime(baseFreq*0.8, ctx.currentTime);
    osc1.frequency.linearRampToValueAtTime(baseFreq*1.3, ctx.currentTime+0.08);
    osc1.frequency.linearRampToValueAtTime(baseFreq*0.9, ctx.currentTime+0.2);
    gain1.gain.setValueAtTime(0.3, ctx.currentTime);
    gain1.gain.linearRampToValueAtTime(0.0, ctx.currentTime+0.3);
    osc1.start(ctx.currentTime);
    osc1.stop(ctx.currentTime+0.3);

    // オシレーター2（ハーモニクス）
    const osc2=ctx.createOscillator();
    const gain2=ctx.createGain();
    osc2.connect(gain2);
    gain2.connect(ctx.destination);
    osc2.type='triangle';
    osc2.frequency.setValueAtTime(baseFreq*1.6, ctx.currentTime);
    osc2.frequency.linearRampToValueAtTime(baseFreq*2.0, ctx.currentTime+0.06);
    osc2.frequency.linearRampToValueAtTime(baseFreq*1.4, ctx.currentTime+0.18);
    gain2.gain.setValueAtTime(0.15, ctx.currentTime);
    gain2.gain.linearRampToValueAtTime(0.0, ctx.currentTime+0.25);
    osc2.start(ctx.currentTime);
    osc2.stop(ctx.currentTime+0.25);
  }catch(e){}
}

// 神猫達成時の特別な音
function playKaminekoSound(){
  try{
    const ctx=getAudioCtx();
    const notes=[523,659,784,1047];
    notes.forEach((freq,i)=>{
      const osc=ctx.createOscillator();
      const gain=ctx.createGain();
      osc.connect(gain);
      gain.connect(ctx.destination);
      osc.type='sine';
      osc.frequency.value=freq;
      const t=ctx.currentTime+i*0.12;
      gain.gain.setValueAtTime(0.3,t);
      gain.gain.linearRampToValueAtTime(0.0,t+0.25);
      osc.start(t);
      osc.stop(t+0.25);
    });
  }catch(e){}
}

// ニャーのテキストエフェクト
const NYA_WORDS=['ニャー！','にゃ！','ニャ♪','にゃ～','ﾆｬ!'];
function showNyaEffect(val){
  const word=NYA_WORDS[Math.floor(Math.random()*NYA_WORDS.length)];
  const el=document.createElement('div');
  el.className='nya';
  el.textContent=word;
  const gw=document.getElementById('gw');
  const rect=gw.getBoundingClientRect();
  el.style.left=(rect.left+Math.random()*rect.width*0.6+rect.width*0.2)+'px';
  el.style.top=(rect.top+rect.height*0.3+Math.random()*rect.height*0.3)+'px';
  document.body.appendChild(el);
  setTimeout(()=>el.remove(),800);
}

function init(){
  B=[[0,0,0,0],[0,0,0,0],[0,0,0,0],[0,0,0,0]];
  sc=0;dead=false;
  try{unlocked=new Set(JSON.parse(localStorage.getItem('nk_u')||'[]'));}catch(e){unlocked=new Set();}
  try{best=parseInt(localStorage.getItem('nk_b')||'0');}catch(e){best=0;}
  spawn();spawn();draw();
  document.getElementById('ov').classList.remove('show');
}

function spawn(){
  const e=[];
  B.forEach((row,r)=>row.forEach((v,c)=>{if(!v)e.push([r,c]);}));
  if(!e.length)return null;
  const [r,c]=e[Math.floor(Math.random()*e.length)];
  B[r][c]=Math.random()<0.9?2:4;
  return[r,c];
}

function draw(){
  document.getElementById('sc').textContent=sc;
  document.getElementById('bs').textContent=best;
  const g=document.getElementById('grid');
  g.querySelectorAll('.tile').forEach(t=>t.remove());
  B.forEach((row,r)=>row.forEach((v,c)=>{
    if(!v)return;
    const cat=CATS.find(x=>x.v===v)||{e:'?',n:'?'};
    const d=document.createElement('div');
    d.className='tile t'+v;
    d.style.top=px(r)+'px';
    d.style.left=px(c)+'px';
    d.innerHTML=cat.e+'<span class="tnm">'+cat.n+'</span>';
    g.appendChild(d);
    unlocked.add(v);
  }));
  try{localStorage.setItem('nk_u',JSON.stringify([...unlocked]));}catch(e){}
  const cl=document.getElementById('clist');
  cl.innerHTML='';
  CATS.forEach(cat=>{
    const b=document.createElement('div');
    b.className='cb'+(unlocked.has(cat.v)?' on':'');
    b.textContent=cat.e+' '+cat.n;
    cl.appendChild(b);
  });
}

function slideRow(row){
  let a=row.filter(v=>v);
  let merged=false;
  for(let i=0;i<a.length-1;i++){
    if(a[i]===a[i+1]){
      a[i]*=2;sc+=a[i];
      if(sc>best){best=sc;try{localStorage.setItem('nk_b',best);}catch(e){}}
      a[i+1]=0;i++;
      merged=true;
      // 合体音とエフェクト
      playNya(a[i-1]||a[i]);
      showNyaEffect(a[i-1]||a[i]);
    }
  }
  a=a.filter(v=>v);
  while(a.length<4)a.push(0);
  return a;
}

function move(dir){
  if(dead)return;
  const snap=JSON.stringify(B);
  if(dir==='l')B=B.map(r=>slideRow(r));
  else if(dir==='r')B=B.map(r=>slideRow([...r].reverse()).reverse());
  else if(dir==='u'){for(let c=0;c<4;c++){let col=B.map(r=>r[c]);col=slideRow(col);col.forEach((v,r)=>B[r][c]=v);}}
  else if(dir==='d'){for(let c=0;c<4;c++){let col=B.map(r=>r[c]).reverse();col=slideRow(col);col.reverse().forEach((v,r)=>B[r][c]=v);}}
  if(JSON.stringify(B)===snap)return;
  spawn();draw();
  if(B.some(r=>r.some(v=>v===2048))){
    dead=true;
    playKaminekoSound();
    setTimeout(()=>over('✨ 神猫誕生！','おめでとう！神猫を作ったよ'),300);
    return;
  }
  if(isFull()){dead=true;setTimeout(()=>over('😿 ゲームオーバー','もう動けないにゃ…'),200);}
}

function isFull(){
  for(let r=0;r<4;r++)for(let c=0;c<4;c++){
    if(!B[r][c])return false;
    if(r<3&&B[r][c]===B[r+1][c])return false;
    if(c<3&&B[r][c]===B[r][c+1])return false;
  }
  return true;
}

function over(t,m){
  document.getElementById('ovT').textContent=t;
  document.getElementById('ovM').textContent=m;
  document.getElementById('ov').classList.add('show');
}

document.getElementById('rbtn').onclick=init;
document.getElementById('ovbtn').onclick=init;
document.getElementById('bu').onclick=()=>move('u');
document.getElementById('bd').onclick=()=>move('d');
document.getElementById('bl').onclick=()=>move('l');
document.getElementById('br').onclick=()=>move('r');

window.addEventListener('keydown',function(e){
  const m={ArrowLeft:'l',ArrowRight:'r',ArrowUp:'u',ArrowDown:'d'};
  if(m[e.key]){e.preventDefault();move(m[e.key]);}
});

let sx=0,sy=0;
document.addEventListener('touchstart',function(e){sx=e.touches[0].clientX;sy=e.touches[0].clientY;},{passive:true});
document.addEventListener('touchend',function(e){
  const dx=e.changedTouches[0].clientX-sx;
  const dy=e.changedTouches[0].clientY-sy;
  if(Math.abs(dx)<25&&Math.abs(dy)<25)return;
  if(Math.abs(dx)>Math.abs(dy))move(dx>0?'r':'l');
  else move(dy>0?'d':'u');
},{passive:true});

init();
</script>
</body>
</html>
