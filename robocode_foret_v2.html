<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>RoboCode Kids 🌿 La Forêt des Robots</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Fredoka+One&family=Nunito:wght@400;600;700;800&display=swap');
:root {
  --vf: #1a5c2a; --vm: #2d8a45; --vc: #5cba6e;
  --mar: #6b3a1f; --jau: #f9e04b; --ora: #f4854a;
  --bg: #0f3318; --bleu: #2b7de9; --vio: #9b2be9; --rou: #cc3333;
}
* { box-sizing: border-box; margin: 0; padding: 0; }
body {
  background: var(--bg);
  font-family: 'Nunito', sans-serif;
  min-height: 100vh;
  background-image: radial-gradient(ellipse at 20% 80%, #0d2a10 0%, transparent 55%),
                    radial-gradient(ellipse at 80% 20%, #1a4020 0%, transparent 55%);
}

/* ── TITLE ── */
#screen-title {
  display: flex; flex-direction: column; align-items: center; justify-content: center;
  min-height: 100vh; padding: 20px; text-align: center;
}
.title-forest { font-size: 4em; animation: sway 3s ease-in-out infinite; margin-bottom: 6px; }
@keyframes sway { 0%,100%{transform:rotate(-3deg)} 50%{transform:rotate(3deg)} }
.robot-hero { font-size: 7em; animation: float 2.5s ease-in-out infinite; margin-bottom: 16px;
  filter: drop-shadow(0 10px 20px rgba(0,0,0,0.5)); }
@keyframes float { 0%,100%{transform:translateY(0)} 50%{transform:translateY(-14px)} }
.title-main { font-family:'Fredoka One',cursive; font-size:clamp(2.2em,7vw,4em);
  color:var(--jau); text-shadow:4px 4px 0 var(--mar),0 0 40px rgba(249,224,75,.4);
  line-height:1.1; margin-bottom:6px; }
.title-sub { font-size:1.1em; color:var(--vc); font-weight:700; margin-bottom:32px; letter-spacing:1px; }

.level-select-grid {
  display: grid; grid-template-columns: repeat(2,1fr);
  gap: 12px; max-width: 620px; width: 100%; margin-bottom: 28px;
}
.level-card {
  background: linear-gradient(135deg,var(--vf),#0f2e18);
  border: 3px solid var(--vm); border-radius: 18px;
  padding: 18px 14px; cursor: pointer; transition: all .2s; position: relative; overflow: hidden;
}
.level-card:hover { transform:translateY(-4px) scale(1.02); border-color:var(--jau);
  box-shadow:0 10px 30px rgba(249,224,75,.2); }
.level-card .emoji { font-size:2.4em; display:block; margin-bottom:6px; }
.level-card .lv-name { font-family:'Fredoka One',cursive; font-size:1.1em; color:var(--jau); margin-bottom:3px; }
.level-card .lv-desc { font-size:.75em; color:var(--vc); line-height:1.3; }
.level-card .lv-badge { position:absolute; top:9px; right:9px;
  background:var(--vm); color:white; font-size:.65em; font-weight:800;
  padding:3px 8px; border-radius:20px; }
.level-card .lv-steps { position:absolute; bottom:9px; right:9px;
  color:rgba(255,255,255,.4); font-size:.65em; font-weight:700; }

.btn-start {
  background: linear-gradient(135deg,var(--vc),var(--vm));
  color:white; font-family:'Fredoka One',cursive; font-size:1.3em;
  border:none; border-radius:50px; padding:14px 44px; cursor:pointer;
  box-shadow:0 6px 20px rgba(0,0,0,.4); transition:all .2s;
}
.btn-start:hover { transform:translateY(-3px); }

/* ── GAME ── */
#screen-game { display:none; min-height:100vh; padding:14px; max-width:860px; margin:0 auto; }

.game-header {
  display:flex; align-items:center; justify-content:space-between;
  background:rgba(0,0,0,.3); border-radius:14px; padding:10px 18px; margin-bottom:12px;
}
.game-level-name { font-family:'Fredoka One',cursive; color:var(--jau); font-size:1.2em; }
.stars-row { display:flex; gap:4px; }
.star { font-size:1.6em; filter:grayscale(1) brightness(.4); transition:all .3s; }
.star.earned { filter:none; animation:star-pop .4s cubic-bezier(.34,1.56,.64,1) forwards; }
@keyframes star-pop { 0%{transform:scale(0) rotate(-20deg)} 100%{transform:scale(1) rotate(0)} }
.btn-menu {
  background:rgba(255,255,255,.1); border:2px solid rgba(255,255,255,.2);
  color:white; border-radius:10px; padding:5px 12px; cursor:pointer;
  font-family:'Nunito',sans-serif; font-size:.82em; font-weight:700; transition:all .2s;
}
.btn-menu:hover { background:rgba(255,255,255,.2); }

.step-indicator { display:flex; gap:5px; justify-content:center; margin-bottom:10px; flex-wrap:wrap; }
.step-dot {
  width:26px; height:26px; border-radius:50%;
  background:rgba(255,255,255,.08); border:2px solid rgba(255,255,255,.15);
  display:flex; align-items:center; justify-content:center;
  font-size:.65em; font-weight:800; color:rgba(255,255,255,.3); transition:all .3s;
}
.step-dot.current { background:var(--jau); border-color:var(--jau); color:var(--mar); box-shadow:0 0 10px rgba(249,224,75,.5); }
.step-dot.done    { background:var(--vc); border-color:var(--vc); color:white; }

.mission-box {
  background:linear-gradient(135deg,#1e4a28,#122e18);
  border:2px solid var(--vm); border-radius:16px; padding:12px 18px;
  margin-bottom:12px; text-align:center;
}
.mission-label { font-size:.7em; color:var(--vc); font-weight:800; text-transform:uppercase; letter-spacing:2px; margin-bottom:3px; }
.mission-text { font-size:1em; color:white; font-weight:700; line-height:1.4; }

.debug-hint {
  background:rgba(204,51,51,.15); border:2px solid var(--rou);
  border-radius:12px; padding:9px 14px; color:#ff9999;
  font-size:.82em; font-weight:700; margin-bottom:10px; text-align:center; display:none;
}
.debug-hint.visible { display:block; }

/* ── GRILLE ── */
.grid-wrapper { display:flex; justify-content:center; margin-bottom:12px; }
.grid {
  display:grid; border-radius:14px; overflow:hidden;
  border:3px solid var(--vm); box-shadow:0 8px 30px rgba(0,0,0,.5);
}
.cell {
  width:72px; height:72px;
  display:flex; align-items:center; justify-content:center;
  font-size:2em; position:relative; transition:background .3s;
}
.cell-grass  { background:#2d5a1e; }
.cell-grass:nth-child(odd) { background:#2a5520; }
.cell-wall   { background:#1a2e12; }
.cell-target { background:radial-gradient(circle,#3a6e25,#1f3d12); }
.robot-emoji {
  font-size:1.9em; z-index:2;
  filter:drop-shadow(0 4px 8px rgba(0,0,0,.5));
  transition: transform .35s cubic-bezier(.34,1.56,.64,1);
}
.robot-emoji.hop { animation:hop .32s ease; }
@keyframes hop { 0%{transform:scale(1)} 50%{transform:scale(1.3) translateY(-7px)} 100%{transform:scale(1)} }
.pulse-target { animation:pulse 1.5s ease-in-out infinite; }
@keyframes pulse { 0%,100%{filter:drop-shadow(0 0 4px gold)} 50%{filter:drop-shadow(0 0 16px gold)} }

/* ── PROG AREA ── */
.prog-area {
  background:linear-gradient(135deg,#0d2010,#0a1a0c);
  border:2px solid var(--vm); border-radius:16px; padding:14px; margin-bottom:12px;
}
.prog-title { font-family:'Fredoka One',cursive; color:var(--vc); font-size:.95em; margin-bottom:8px; }

.blocks-palette { display:flex; flex-wrap:wrap; gap:7px; margin-bottom:10px; }
.block-btn {
  display:flex; align-items:center; gap:5px; padding:8px 12px;
  border-radius:11px; border:none; cursor:pointer;
  font-family:'Nunito',sans-serif; font-weight:800; font-size:.85em;
  transition:all .15s; box-shadow:0 4px 0 rgba(0,0,0,.3);
}
.block-btn:active { transform:translateY(2px); box-shadow:0 2px 0 rgba(0,0,0,.3); }
.block-btn:hover  { filter:brightness(1.1); transform:translateY(-2px); }
.bb-arr { background:var(--bleu); color:white; }
.bb-lp  { background:var(--ora); color:white; }
.bb-cd  { background:var(--vio); color:white; }
.bb-del { background:var(--rou); color:white; }

.program-queue {
  min-height:54px; background:rgba(0,0,0,.3);
  border-radius:11px; padding:8px; display:flex; flex-wrap:wrap; gap:5px; align-items:center;
  border:2px dashed rgba(92,186,110,.25);
}
.program-queue:empty::before {
  content:"➕  Ajoute des blocs ici !";
  color:rgba(255,255,255,.2); font-size:.85em; width:100%; text-align:center;
}

.prog-block {
  display:inline-flex; align-items:center; gap:3px;
  padding:5px 11px; border-radius:9px;
  font-weight:800; font-size:.82em; cursor:pointer; position:relative;
  animation:pop-in .2s cubic-bezier(.34,1.56,.64,1);
  user-select:none;
}
@keyframes pop-in { from{transform:scale(0)} to{transform:scale(1)} }
.prog-block:hover::after {
  content:'✕'; position:absolute; top:-6px; right:-6px;
  background:var(--rou); color:white; width:15px; height:15px;
  border-radius:50%; font-size:.55em; display:flex; align-items:center; justify-content:center;
}
.pb-arr  { background:var(--bleu); color:white; }
.pb-lp   { background:var(--ora); color:white; }
.pb-cd   { background:var(--vio); color:white; }
.pb-bug  { background:var(--rou); color:white; border:3px solid #ff6b6b; }
.pb-ok   { background:var(--bleu); color:white; }

/* Loop inline counter */
.loop-inline { display:flex; align-items:center; gap:4px; background:var(--ora); color:white;
  padding:5px 10px; border-radius:9px; font-weight:800; font-size:.82em; }
.loop-count-btn {
  background:rgba(0,0,0,.25); border:none; color:white; width:22px; height:22px;
  border-radius:50%; cursor:pointer; font-size:1em; display:flex; align-items:center; justify-content:center;
  font-family:'Fredoka One',cursive; transition:all .15s;
}
.loop-count-btn:hover { background:rgba(0,0,0,.5); }
.loop-count-display { font-family:'Fredoka One',cursive; font-size:1.1em; min-width:18px; text-align:center; }

/* ── ACTIONS ── */
.action-row { display:flex; gap:10px; justify-content:center; margin-bottom:8px; flex-wrap:wrap; }
.btn-run {
  background:linear-gradient(135deg,var(--jau),#f4a52a);
  color:var(--mar); font-family:'Fredoka One',cursive; font-size:1.15em;
  border:none; border-radius:50px; padding:11px 34px; cursor:pointer;
  box-shadow:0 5px 0 #a06010,0 8px 20px rgba(0,0,0,.4); transition:all .15s;
}
.btn-run:hover { transform:translateY(-2px); }
.btn-run:active { transform:translateY(3px); box-shadow:0 2px 0 #a06010; }
.btn-run:disabled { opacity:.5; cursor:not-allowed; transform:none; }
.btn-reset {
  background:rgba(255,255,255,.1); border:2px solid rgba(255,255,255,.2);
  color:white; font-family:'Nunito',sans-serif; font-weight:800; font-size:.95em;
  border-radius:50px; padding:11px 22px; cursor:pointer; transition:all .15s;
}
.btn-reset:hover { background:rgba(255,255,255,.2); }

/* ── FEEDBACK ── */
.feedback-overlay {
  display:none; position:fixed; inset:0; background:rgba(0,0,0,.75);
  z-index:100; align-items:center; justify-content:center; backdrop-filter:blur(6px);
}
.feedback-overlay.visible { display:flex; }
.feedback-box {
  background:linear-gradient(135deg,#1e4a28,#0f2e18);
  border:4px solid var(--vm); border-radius:28px; padding:36px 44px;
  text-align:center; max-width:400px; width:90%;
  animation:bounce-in .4s cubic-bezier(.34,1.56,.64,1);
}
@keyframes bounce-in { from{transform:scale(.5) translateY(40px);opacity:0} to{transform:scale(1) translateY(0);opacity:1} }
.fb-emoji { font-size:4.5em; margin-bottom:12px; display:block; }
.fb-title { font-family:'Fredoka One',cursive; font-size:1.9em; margin-bottom:7px; }
.fb-title.success { color:var(--jau); } .fb-title.fail { color:var(--ora); }
.fb-msg { color:rgba(255,255,255,.85); margin-bottom:20px; font-size:.95em; line-height:1.5; }
.fb-stars { display:flex; gap:6px; justify-content:center; margin-bottom:20px; }
.fb-star { font-size:1.9em; filter:grayscale(1) brightness(.4); }
.fb-star.earned { filter:none; animation:star-pop .4s cubic-bezier(.34,1.56,.64,1) forwards; }
.feedback-btn {
  background:linear-gradient(135deg,var(--vc),var(--vm));
  color:white; font-family:'Fredoka One',cursive; font-size:1.15em;
  border:none; border-radius:50px; padding:12px 36px; cursor:pointer;
  box-shadow:0 5px 0 var(--vf); transition:all .15s;
}
.feedback-btn:hover { transform:translateY(-2px); }

/* Sparkles */
.sparkle { position:fixed; pointer-events:none; z-index:200; animation:sparkle-fly 1.1s forwards; }
@keyframes sparkle-fly { 0%{opacity:1;transform:translateY(0) scale(1)} 100%{opacity:0;transform:translateY(-130px) scale(0)} }

/* Toast */
.toast {
  position:fixed; bottom:28px; left:50%; transform:translateX(-50%);
  background:rgba(0,0,0,.88); color:white; padding:11px 22px; border-radius:50px;
  font-weight:800; z-index:999; font-family:'Nunito',sans-serif;
  border:2px solid rgba(255,255,255,.15); animation:pop-in .25s; pointer-events:none;
}

@media(max-width:600px){
  .cell{width:56px;height:56px;font-size:1.5em;}
  .robot-emoji{font-size:1.5em;}
  .level-select-grid{grid-template-columns:1fr 1fr;}
  .feedback-box{padding:24px 20px;}
  .block-btn{padding:6px 9px;font-size:.78em;}
}
</style>
</head>
<body>

<!-- ═══════════════════════════ TITRE ═══════════════════════════ -->
<div id="screen-title">
  <div class="title-forest">🌿🌲🌿</div>
  <div class="robot-hero">🤖</div>
  <div class="title-main">La Forêt des Robots</div>
  <div class="title-sub">RoboCode Kids · Aventure 2</div>
  <div class="level-select-grid" id="level-cards"></div>
  <button class="btn-start" onclick="startGame(0)">🌲 Commencer l'aventure !</button>
</div>

<!-- ═══════════════════════════ JEU ═══════════════════════════ -->
<div id="screen-game">
  <div class="game-header">
    <div class="game-level-name" id="lv-name"></div>
    <div class="stars-row" id="header-stars">
      <span class="star" id="hs1">⭐</span><span class="star" id="hs2">⭐</span><span class="star" id="hs3">⭐</span>
    </div>
    <button class="btn-menu" onclick="goMenu()">🏠 Menu</button>
  </div>
  <div class="step-indicator" id="step-dots"></div>
  <div class="mission-box">
    <div class="mission-label">🎯 Mission</div>
    <div class="mission-text" id="mission-text"></div>
  </div>
  <div class="debug-hint" id="debug-hint">🐛 Le programme est cassé ! Clique sur le mauvais bloc pour le supprimer.</div>
  <div class="grid-wrapper"><div class="grid" id="game-grid"></div></div>
  <div class="prog-area">
    <div class="prog-title">🧩 Ton programme</div>
    <div class="blocks-palette" id="blocks-palette"></div>
    <div class="program-queue" id="program-queue"></div>
  </div>
  <div class="action-row">
    <button class="btn-reset" onclick="resetLevel()">🔄 Recommencer</button>
    <button class="btn-run" id="btn-run" onclick="runProgram()">▶️ Lancer !</button>
  </div>
</div>

<!-- ═══════════════════════════ FEEDBACK ═══════════════════════════ -->
<div class="feedback-overlay" id="feedback-overlay">
  <div class="feedback-box">
    <span class="fb-emoji" id="fb-emoji"></span>
    <div class="fb-title" id="fb-title"></div>
    <div class="fb-msg"   id="fb-msg"></div>
    <div class="fb-stars" id="fb-stars"></div>
    <button class="feedback-btn" id="fb-btn"></button>
  </div>
</div>

<script>
/* ═══════════════════════════════════════════════════════════════════
   NIVEAUX — conventions :
     grid : taille N×N
     start : [row, col]  (row 0 = haut)
     target : [row, col]
     obstacles : [[row,col], ...]  (cases avec 🌳)
     Tous les chemins ont été vérifiés manuellement.

   MODE arrows  → blocs flèche libre
   MODE loop    → blocs flèche + boucle avec compteur intégré
   MODE cond    → blocs flèche + bloc condition Si-obstacle→action
   MODE debug   → programme pré-chargé avec 1 ou 2 bugs, cliquer dessus

   Pour les CONDITIONS :
     Le bloc "Si obstacle devant → action_alt" est résolu ainsi :
       • à chaque étape, si la case devant (dir_default) est bloquée → on applique action_alt
       • sinon on avance dans dir_default
     La solution est donc juste le nombre de fois qu'on place ce bloc.
═══════════════════════════════════════════════════════════════════ */

const LEVELS = [

  /* ══════════════ NIVEAU 1 : FLÈCHES ══════════════
     Grilles 3×3→4×4→5×5, obstacles clairs, chemins libres.
     Robot : 🤖  Cible : 🍎/🍄/🌸
  */
  {
    id: 0,
    name: "🦊 Renard Rouillé",
    mode: "arrows",
    desc: "Apprends les <strong>flèches</strong> ! Guide le robot jusqu'à la cible.",
    steps: [
      // ── 1a ──  3×3, start[2,0] → target[2,2], 2 droites
      // . . .
      // . . .
      // R . T    chemin: → →
      {
        mission: "Appuie sur ➡️ deux fois pour avancer jusqu'à la pomme 🍎 !",
        grid:3, start:[2,0], target:[2,2], obstacles:[],
        target_emoji:"🍎",
        solution:["→","→"], maxBlocks:4,
        successMsg:"Super ! Le robot a mangé la pomme 🍎🤖"
      },
      // ── 1b ──  3×3, start[2,0] → target[0,2]
      // . . T
      // . . .
      // R . .    chemin: ↑ ↑ → →  (ou → → ↑ ↑)
      {
        mission: "La fleur 🌸 est en haut à droite ! Guide le robot.",
        grid:3, start:[2,0], target:[0,2], obstacles:[],
        target_emoji:"🌸",
        solution:["↑","↑","→","→"], maxBlocks:6,
        successMsg:"Bravo ! Tu utilises ↑ et → ensemble ! 🌸"
      },
      // ── 1c ──  4×4, start[3,0] → target[0,3], obstacle [1,1]
      // . . . T
      // . X . .
      // . . . .
      // R . . .  chemin: ↑ ↑ ↑ → → →  (col 0, ligne 2→1→0, puis → → →)
      {
        mission: "Attention à l'arbre 🌳 ! Contourne-le pour atteindre le champignon 🍄.",
        grid:4, start:[3,0], target:[0,3], obstacles:[[1,1]],
        target_emoji:"🍄",
        solution:["↑","↑","↑","→","→","→"], maxBlocks:9,
        successMsg:"Excellent ! Tu sais éviter les obstacles 🌳 !"
      },
      // ── 1d ──  4×4, start[0,0] → target[3,3], obstacles [1,2],[2,1]
      // R . . .
      // . . X .
      // . X . .
      // . . . T  chemin: → ↓ → ↓ → ↓   (col0→col1, row0→row1, col1→col2, row1→row2... nope)
      // Vérifions: R=[0,0]. → [0,1]. ↓ [1,1]. → [1,2] = obstacle! Non.
      // Chemin sûr: ↓ → ↓ → ↓ →   [0,0]→[1,0]→[1,1]→[2,1]=obst? Oui.
      // Obstacles [1,2] et [2,1]. Chemin : [0,0]→[1,0]→[2,0]→[3,0]→[3,1]→[3,2]→[3,3]
      // = ↓ ↓ ↓ → → →   ✓
      {
        mission: "Deux arbres bloquent le chemin ! Trouve la route jusqu'au miel 🍯.",
        grid:4, start:[0,0], target:[3,3], obstacles:[[1,2],[2,1]],
        target_emoji:"🍯",
        solution:["↓","↓","↓","→","→","→"], maxBlocks:9,
        successMsg:"Parfait ! Tu trouves toujours un chemin ! 🍯✨"
      },
      // ── 1e ──  5×5, start[0,0] → target[4,4], obstacles [1,1],[2,2],[3,3]
      // R . . . .
      // . X . . .
      // . . X . .
      // . . . X .
      // . . . . T  chemin le long du bord bas puis droite :
      // [0,0]→[1,0]→[2,0]→[3,0]→[4,0]→[4,1]→[4,2]→[4,3]→[4,4]  = ↓↓↓↓→→→→  ✓
      {
        mission: "La diagonale est barrée ! Va par le bord pour atteindre l'étoile ⭐.",
        grid:5, start:[0,0], target:[4,4], obstacles:[[1,1],[2,2],[3,3]],
        target_emoji:"⭐",
        solution:["↓","↓","↓","↓","→","→","→","→"], maxBlocks:11,
        successMsg:"Incroyable ! Tu traverses toute la forêt ! 🌲🌲"
      },
      // ── 1f ──  5×5, start[2,0] → target[2,4], obstacles [2,2]
      // . . . . .
      // . . . . .
      // R . X . T
      // . . . . .
      // . . . . .  chemin: ↑ → → → ↓  ou  ↓ → → → ↑
      // [2,0]→[1,0]→[1,1]→[1,2]→[1,3]→[1,4]→[2,4]  = ↑→→→→↓  ✓
      {
        mission: "Un arbre bloque la route directe ! Passe par le dessus ou le dessous.",
        grid:5, start:[2,0], target:[2,4], obstacles:[[2,2]],
        target_emoji:"🌺",
        solution:["↑","→","→","→","→","↓"], maxBlocks:9,
        successMsg:"Bravo ! Tu contournes les obstacles comme un pro ! 🌺"
      }
    ]
  },

  /* ══════════════ NIVEAU 2 : BOUCLES ══════════════
     Le robot a besoin de répéter plusieurs fois la même direction.
     On utilise des blocs boucle avec compteur ajustable inline.
     Chaque step a un "loopGoal" qui décrit la solution optimale.
  */
  {
    id: 1,
    name: "🐸 Grenouille Gonflée",
    mode: "loop",
    desc: "Utilise les <strong>boucles</strong> pour répéter sans te fatiguer !",
    steps: [
      // ── 2a ──  4×4, start[2,0] → target[2,3]   chemin: → × 3
      {
        mission: "Le robot doit avancer 3 fois à droite. Utilise 'Répéter' !",
        grid:4, start:[2,0], target:[2,3], obstacles:[],
        target_emoji:"🍎",
        loopGoal:"Répéter [ → ] 3 fois",
        solution:[{type:"loop",count:3,dir:"→"}], maxBlocks:3,
        successMsg:"Les boucles c'est magique ! 3 cases en 1 bloc ! 🔁✨"
      },
      // ── 2b ──  5×5, start[0,0] → target[4,0]   chemin: ↓ × 4
      {
        mission: "Descends tout en bas ! 4 cases vers le bas, utilise une boucle.",
        grid:5, start:[0,0], target:[4,0], obstacles:[],
        target_emoji:"🍄",
        loopGoal:"Répéter [ ↓ ] 4 fois",
        solution:[{type:"loop",count:4,dir:"↓"}], maxBlocks:4,
        successMsg:"Tu descends comme une grenouille qui plonge ! 🐸"
      },
      // ── 2c ──  5×5, start[4,0] → target[0,4]   chemin: ↑×4 puis →×4
      {
        mission: "Monte 4 fois, puis va à droite 4 fois. Deux boucles !",
        grid:5, start:[4,0], target:[0,4], obstacles:[],
        target_emoji:"🌸",
        loopGoal:"Répéter [ ↑ ] 4 fois + Répéter [ → ] 4 fois",
        solution:[{type:"loop",count:4,dir:"↑"},{type:"loop",count:4,dir:"→"}], maxBlocks:6,
        successMsg:"Super codeur ! Tu utilises 2 boucles ! 💪🔁"
      },
      // ── 2d ──  5×5, start[0,2] → target[4,2]   chemin: ↓×4, obstacles [1,0],[1,4]
      // Ces obstacles ne bloquent pas le chemin col=2
      {
        mission: "Descends en ligne droite 4 fois. Attention aux arbres sur les côtés !",
        grid:5, start:[0,2], target:[4,2], obstacles:[[1,0],[1,4],[3,0],[3,4]],
        target_emoji:"🍯",
        loopGoal:"Répéter [ ↓ ] 4 fois",
        solution:[{type:"loop",count:4,dir:"↓"}], maxBlocks:5,
        successMsg:"Droit dans la cible ! 🎯🍯"
      },
      // ── 2e ──  5×5, start[2,0] → target[2,4], obstacles [0,2],[4,2]
      // Chemin direct: →×4 libre car obstacles ne sont pas sur row=2
      {
        mission: "Avance à droite 4 fois pour traverser la forêt !",
        grid:5, start:[2,0], target:[2,4], obstacles:[[0,2],[4,2]],
        target_emoji:"⭐",
        loopGoal:"Répéter [ → ] 4 fois",
        solution:[{type:"loop",count:4,dir:"→"}], maxBlocks:5,
        successMsg:"Traversée de forêt réussie ! 🌲⭐"
      },
      // ── 2f ──  5×5, start[4,4] → target[0,0]
      // chemin: ↑×4 + ←×4
      {
        mission: "Remonte en haut à gauche ! 4 fois en haut, 4 fois à gauche.",
        grid:5, start:[4,4], target:[0,0], obstacles:[[2,2]],
        target_emoji:"🏆",
        loopGoal:"Répéter [ ↑ ] 4 fois + Répéter [ ← ] 4 fois",
        solution:[{type:"loop",count:4,dir:"↑"},{type:"loop",count:4,dir:"←"}], maxBlocks:7,
        successMsg:"Champion ! Tu maîtrises toutes les boucles ! 🏆🔁"
      }
    ]
  },

  /* ══════════════ NIVEAU 3 : CONDITIONS ══════════════
     Bloc spécial : "Si arbre devant → [action_alt] / Sinon → [dir_default]"
     Le robot avance automatiquement dans dir_default sauf si obstacle → action_alt.
     On place autant de blocs "Si" que nécessaire.

     Implémentation : chaque bloc "cond" consomme 1 pas :
       - si la case (pos + dir_default) est obstacle → applique action_alt
       - sinon → applique dir_default
  */
  {
    id: 2,
    name: "🦉 Hibou Malin",
    mode: "cond",
    desc: "Réfléchis avec les <strong>conditions</strong> Si… Alors… !",
    steps: [
      // ── 3a ──  4×4, start[2,0] → target[2,3]
      // Obstacle [2,1]. Dir_default=→, action_alt=↑ puis il faudra contourner
      // Mais une seule condition n'est pas suffisante pour tout le chemin.
      // On simplifie : le bloc cond gère 1 étape.
      // Chemin manuel avec conditions: on a assez de blocs manuels + 1 cond
      // Chemin: [2,0]→[2,1]=obst → fléchit ↑ → [1,0], puis →[1,1]→[1,2]→[1,3]→[2,3]
      // = cond(→|↑) → → → ↓   ✓
      {
        mission: "Si un arbre bloque la route ➡️, monte ⬆️ pour l'éviter ! Puis continue.",
        grid:4, start:[2,0], target:[2,3], obstacles:[[2,1]],
        target_emoji:"🍎",
        cond_default:"→", cond_alt:"↑",
        condLabel:"Si arbre → ⬆️, sinon ➡️",
        // solution = séquence de blocs à placer dans la queue
        // cond(→|↑) résout [2,0]→[1,0]. Puis →[1,1]→[1,2]→[1,3]→ ↓[2,3]
        solution:["cond","→","→","→","↓"], maxBlocks:7,
        successMsg:"Waouh ! Tu penses comme un vrai programme ! 🦉💡"
      },
      // ── 3b ──  4×4, start[0,0] → target[3,3], obstacle [1,0],[2,0]
      // La route ↓ est bloquée en [1,0] et [2,0].
      // Cond(↓|→): [0,0] voit [1,0]=obst → va →[0,1]. Puis ↓[1,1]↓[2,1]↓[3,1]→[3,2]→[3,3]
      // = cond(↓|→) ↓ ↓ ↓ → →   ✓
      {
        mission: "Si le chemin vers le bas est barré, va à droite ! Puis descends.",
        grid:4, start:[0,0], target:[3,3], obstacles:[[1,0],[2,0]],
        target_emoji:"🍄",
        cond_default:"↓", cond_alt:"→",
        condLabel:"Si arbre → ➡️, sinon ⬇️",
        solution:["cond","↓","↓","↓","→","→"], maxBlocks:8,
        successMsg:"Excellent ! Le hibou est fier de toi 🦉✨"
      },
      // ── 3c ──  5×5, start[0,0] → target[4,4], obstacles [0,1],[0,2],[0,3]
      // La route → est bloquée dès [0,1].
      // Cond(→|↓): [0,0] voit [0,1]=obst → va ↓[1,0]. Puis → → → → ↓↓↓
      // [1,0]→[1,1]→[1,2]→[1,3]→[1,4]→[2,4]→[3,4]→[4,4]
      // = cond(→|↓) → → → → ↓ ↓ ↓   ✓
      {
        mission: "La rangée du haut est bloquée ! Si arbre devant → descends, sinon avance !",
        grid:5, start:[0,0], target:[4,4], obstacles:[[0,1],[0,2],[0,3]],
        target_emoji:"🌸",
        cond_default:"→", cond_alt:"↓",
        condLabel:"Si arbre → ⬇️, sinon ➡️",
        solution:["cond","→","→","→","→","↓","↓","↓"], maxBlocks:10,
        successMsg:"Magnifique logique ! Tu es un vrai hibou malin 🦉"
      },
      // ── 3d ──  5×5, start[4,0] → target[0,4], obstacles [3,0],[2,0]
      // Chemin ↑ barré en [3,0]. Cond(↑|→): [4,0]→[3,0]=obst → →[4,1].
      // [4,1]↑[3,1]↑[2,1]↑[1,1]↑[0,1]→[0,2]→[0,3]→[0,4]
      // = cond(↑|→) ↑ ↑ ↑ ↑ → → →   ✓
      {
        mission: "Le chemin vers le haut est barré ! Contourne par la droite.",
        grid:5, start:[4,0], target:[0,4], obstacles:[[3,0],[2,0]],
        target_emoji:"⭐",
        cond_default:"↑", cond_alt:"→",
        condLabel:"Si arbre → ➡️, sinon ⬆️",
        solution:["cond","↑","↑","↑","↑","→","→","→"], maxBlocks:10,
        successMsg:"Fantastique ! 4 niveaux de conditions réussis ! 🏆🦉"
      }
    ]
  },

  /* ══════════════ NIVEAU 4 : DEBUG ══════════════
     Programme pré-chargé avec bugs (blocs rouges clignotants).
     L'enfant doit cliquer sur le(s) mauvais bloc(s).
     bugIndices = tableau des indices des blocs incorrects.
     On vérifie que correctProgram mène bien à la cible.
  */
  {
    id: 3,
    name: "🐛 Chasseur de Bugs",
    mode: "debug",
    desc: "<strong>Débuggue</strong> le programme cassé du robot !",
    steps: [
      // ── 4a ──  4×4, start[0,0] → target[0,3]
      // Correct: → → →
      // Buggué: → ↓ → →   bug=[1]=↓
      {
        mission: "Le robot doit aller à droite 3 fois. Il y a un bug 🐛 ! Trouve-le et clique dessus.",
        grid:4, start:[0,0], target:[0,3], obstacles:[],
        target_emoji:"🍎",
        buggyProgram:["→","↓","→","→"],
        correctProgram:["→","→","→"],
        bugIndices:[1],
        successMsg:"Bug trouvé et écrasé ! 🐛💥 Super débogueur !"
      },
      // ── 4b ──  4×4, start[3,0] → target[0,3]
      // Correct: ↑ ↑ ↑ → → →
      // Buggué:  ↑ → ↑ ↑ → → →   bug=[1]=→
      // Sans le bug: ↑↑↑→→→ = [3,0]→[2,0]→[1,0]→[0,0]→[0,1]→[0,2]→[0,3] ✓
      {
        mission: "Le robot doit monter puis aller à droite. Un bloc est au mauvais endroit 🐛 !",
        grid:4, start:[3,0], target:[0,3], obstacles:[],
        target_emoji:"🍄",
        buggyProgram:["↑","→","↑","↑","→","→","→"],
        correctProgram:["↑","↑","↑","→","→","→"],
        bugIndices:[1],
        successMsg:"Excellent ! Le robot retrouve son chemin ! 🗺️"
      },
      // ── 4c ──  5×5, start[0,0] → target[4,4], obstacle [2,2]
      // Correct: ↓ ↓ → → ↓ ↓ → →  (passe à droite de l'obstacle)
      // [0,0]→[1,0]→[2,0]→[2,1]→[2,2]=obst NON
      // Correct: ↓ ↓ → → → → ↓ ↓  [0,0]→[1,0]→[2,0]→[2,1]→... [2,2]=obst NON
      // Prenons: ↓ → ↓ → → ↓ → ↓  [0,0]→[1,0]→[1,1]→[2,1]→... [2,2] non touché
      // Correct: → → ↓ ↓ → → ↓ ↓ [0,0]→[0,1]→[0,2]→[1,2]→[2,2]=obst NON
      // Correct simple: ↓ ↓ ↓ ↓ → → → →  [row0→4, col0→4], [2,2] n'est PAS sur ce chemin ✓
      // Buggué: ↓ ↓ ← ↓ ↓ → → → →   bug=[2]=←
      {
        mission: "2 bugs se sont glissés dans ce programme ! Trouve-les tous les deux ! 🔍",
        grid:5, start:[0,0], target:[4,4], obstacles:[[1,2],[3,2]],
        target_emoji:"⭐",
        // Correct: ↓ ↓ ↓ ↓ → → → →  (obstacles sur col 2, chemin passe col 0→4 row 4→4, puis → → → → )
        // Vérifions: [0,0]↓[1,0]↓[2,0]↓[3,0]↓[4,0]→[4,1]→[4,2]→[4,3]→[4,4] ✓ obstacles [1,2][3,2] non touchés ✓
        // Buggué:    ↓ ↑ ↓ ↓ ↓ → → ← → →   bugs=[1]=↑, [7]=←
        buggyProgram:["↓","↑","↓","↓","↓","→","→","←","→","→"],
        correctProgram:["↓","↓","↓","↓","→","→","→","→"],
        bugIndices:[1,7],
        successMsg:"CHAMPION ! 2 bugs trouvés d'un coup ! 🏆🌟"
      },
      // ── 4d ──  4×4, start[1,0] → target[1,3], obstacles [1,1]
      // Correct: ↑ → → → ↓    [1,0]→[0,0]→[0,1]→[0,2]→[0,3]→[1,3] ✓
      // Buggué:  ↑ → ↓ → → ↓  bug=[2]=↓  (↓ depuis [0,1] → [1,1]=obst, bloqué)
      {
        mission: "Le robot doit contourner l'arbre 🌳. Un bug l'envoie dedans ! Trouve-le.",
        grid:4, start:[1,0], target:[1,3], obstacles:[[1,1]],
        target_emoji:"🌺",
        buggyProgram:["↑","→","↓","→","→","↓"],
        correctProgram:["↑","→","→","→","↓"],
        bugIndices:[2],
        successMsg:"Parfait ! Tu protèges le robot des arbres 🌳 !"
      },
      // ── 4e ──  5×5, start[4,4] → target[0,0]
      // Correct: ↑ ↑ ↑ ↑ ← ← ← ←  [4,4]→[0,4]→[0,0] ✓
      // Buggué:  ↑ ↑ → ↑ ↑ ← ← ← ←  bug=[2]=→
      {
        mission: "Le robot part du coin bas-droit et doit aller au coin haut-gauche. Bug caché !",
        grid:5, start:[4,4], target:[0,0], obstacles:[[2,2],[1,3]],
        target_emoji:"🏆",
        // Chemin correct sans toucher [2,2] et [1,3]:
        // ↑↑↑↑ = [4,4]→[3,4]→[2,4]→[1,4]→[0,4] puis ←←←← = [0,3]→[0,2]→[0,1]→[0,0] ✓
        buggyProgram:["↑","↑","↑","→","↑","←","←","←","←"],
        correctProgram:["↑","↑","↑","↑","←","←","←","←"],
        bugIndices:[3],
        successMsg:"Génial ! Tu retrouves tous les bugs ! 🐛🔍🏆"
      }
    ]
  }
];

/* ═══════════════════════════════════════════════════════════════════
   ÉTAT
═══════════════════════════════════════════════════════════════════ */
let currentLevel = 0;
let currentStep  = 0;
let robotPos     = [0,0];
let program      = [];   // blocs dans la queue
let bugsFound    = [];   // indices de bugs trouvés (mode debug)
let isRunning    = false;
let currentTargetEmoji = "🍎";

const getLv   = () => LEVELS[currentLevel];
const getStep = () => LEVELS[currentLevel].steps[currentStep];

/* ── Génération des cartes menu ── */
function buildMenuCards() {
  const container = document.getElementById('level-cards');
  container.innerHTML = '';
  LEVELS.forEach((lv, i) => {
    const card = document.createElement('div');
    card.className = 'level-card';
    card.onclick = () => startGame(i);
    card.innerHTML = `
      <span class="lv-badge">Niveau ${i+1}</span>
      <span class="emoji">${lv.name.split(' ')[0]}</span>
      <div class="lv-name">${lv.name.slice(3)}</div>
      <div class="lv-desc">${lv.desc}</div>
      <span class="lv-steps">${lv.steps.length} étapes</span>`;
    container.appendChild(card);
  });
}
buildMenuCards();

/* ═══════════════════════════════════════════════════════════════════
   NAVIGATION
═══════════════════════════════════════════════════════════════════ */
function goMenu() {
  document.getElementById('screen-title').style.display = 'flex';
  document.getElementById('screen-game').style.display  = 'none';
  document.getElementById('feedback-overlay').classList.remove('visible');
}

function startGame(lvIdx) {
  currentLevel = lvIdx;
  currentStep  = 0;
  document.getElementById('screen-title').style.display = 'none';
  document.getElementById('screen-game').style.display  = 'block';
  loadStep();
}

function nextOrMenu() {
  document.getElementById('feedback-overlay').classList.remove('visible');
  const lv = getLv();
  if (currentStep + 1 < lv.steps.length) {
    currentStep++;
    loadStep();
  } else {
    goMenu();
  }
}

function resetLevel() {
  program = [];
  bugsFound = [];
  isRunning = false;
  loadStep();
}

/* ═══════════════════════════════════════════════════════════════════
   CHARGEMENT STEP
═══════════════════════════════════════════════════════════════════ */
function loadStep() {
  const lv   = getLv();
  const step = getStep();
  program    = [];
  bugsFound  = [];
  isRunning  = false;

  robotPos = [...step.start];
  currentTargetEmoji = step.target_emoji || "🍎";

  document.getElementById('lv-name').textContent    = lv.name;
  document.getElementById('mission-text').textContent = step.mission;
  document.getElementById('debug-hint').classList.toggle('visible', lv.mode === 'debug');
  document.getElementById('btn-run').disabled = false;

  // Stars reset
  ['hs1','hs2','hs3'].forEach(id => document.getElementById(id).classList.remove('earned'));

  // Step dots
  const dots = document.getElementById('step-dots');
  dots.innerHTML = '';
  lv.steps.forEach((_,i) => {
    const d = document.createElement('div');
    d.className = 'step-dot' + (i < currentStep ? ' done' : i === currentStep ? ' current' : '');
    d.textContent = i + 1;
    dots.appendChild(d);
  });

  buildGrid(step);
  buildPalette(lv, step);
  renderQueue();
}

/* ═══════════════════════════════════════════════════════════════════
   GRILLE
═══════════════════════════════════════════════════════════════════ */
function buildGrid(step) {
  const el = document.getElementById('game-grid');
  const G  = step.grid;
  el.style.gridTemplateColumns = `repeat(${G},1fr)`;
  el.innerHTML = '';

  for (let r = 0; r < G; r++) {
    for (let c = 0; c < G; c++) {
      const cell = document.createElement('div');
      cell.id = `cell-${r}-${c}`;

      const isObs    = (step.obstacles||[]).some(([or,oc]) => or===r && oc===c);
      const isTarget = step.target[0]===r && step.target[1]===c;
      const isRobot  = step.start[0]===r  && step.start[1]===c;

      cell.className = 'cell ' + (isObs ? 'cell-wall' : isTarget ? 'cell-target' : 'cell-grass');

      if (isObs)    cell.innerHTML = '<span style="font-size:1.7em">🌳</span>';
      if (isTarget) cell.innerHTML += `<span class="pulse-target" style="font-size:1.7em">${currentTargetEmoji}</span>`;
      if (isRobot)  cell.innerHTML += '<span class="robot-emoji" id="robot">🤖</span>';

      el.appendChild(cell);
    }
  }
}

function placeRobot(r, c) {
  document.querySelectorAll('#robot').forEach(e => e.remove());
  const cell = document.getElementById(`cell-${r}-${c}`);
  if (!cell) return;
  const span = document.createElement('span');
  span.className = 'robot-emoji hop';
  span.id = 'robot';
  span.textContent = '🤖';
  cell.appendChild(span);
  setTimeout(() => span.classList.remove('hop'), 350);
}

/* ═══════════════════════════════════════════════════════════════════
   PALETTE
═══════════════════════════════════════════════════════════════════ */
function buildPalette(lv, step) {
  const palette = document.getElementById('blocks-palette');
  palette.innerHTML = '';

  if (lv.mode === 'debug') {
    // Programme pré-chargé, pas de palette
    program = [...step.buggyProgram];
    renderDebugQueue(step);
    return;
  }

  const dirs = [
    {label:'⬆️ Haut', d:'↑'}, {label:'⬇️ Bas',  d:'↓'},
    {label:'⬅️ Gche', d:'←'}, {label:'➡️ Drte', d:'→'}
  ];

  if (lv.mode === 'arrows') {
    dirs.forEach(({label,d}) => {
      const b = mkBtn(label,'bb-arr',() => addArrow(d));
      palette.appendChild(b);
    });
  }

  if (lv.mode === 'loop') {
    dirs.forEach(({label,d}) => {
      const b = mkBtn(label,'bb-lp',() => addLoop(d));
      palette.appendChild(b);
    });
    if (step.loopGoal) {
      const hint = document.createElement('div');
      hint.style.cssText = 'color:rgba(255,255,255,.45);font-size:.75em;font-weight:700;width:100%;margin-top:4px;';
      hint.textContent = '💡 ' + step.loopGoal;
      palette.appendChild(hint);
    }
  }

  if (lv.mode === 'cond') {
    // Flèches normales
    dirs.forEach(({label,d}) => {
      const b = mkBtn(label,'bb-arr',() => addArrow(d));
      palette.appendChild(b);
    });
    // Bloc condition
    const cb = mkBtn('🤔 ' + step.condLabel, 'bb-cd', () => addCond(step));
    palette.appendChild(cb);
  }

  // Supprimer dernier
  palette.appendChild(mkBtn('🗑️ Effacer', 'bb-del', removeLastBlock));
}

function mkBtn(label, cls, fn) {
  const b = document.createElement('button');
  b.className = `block-btn ${cls}`;
  b.innerHTML = label;
  b.onclick = fn;
  return b;
}

/* ═══════════════════════════════════════════════════════════════════
   GESTION PROGRAMME
═══════════════════════════════════════════════════════════════════ */
function addArrow(dir) {
  const step = getStep();
  if (program.length >= (step.maxBlocks || 12)) { showToast('❌ Programme trop long !'); return; }
  program.push(dir);
  renderQueue();
}

function addLoop(dir) {
  const step = getStep();
  if (program.length >= (step.maxBlocks || 12)) { showToast('❌ Programme trop long !'); return; }
  program.push({type:'loop', count:2, dir});
  renderQueue();
}

function addCond(step) {
  if (program.length >= (step.maxBlocks || 12)) { showToast('❌ Programme trop long !'); return; }
  program.push({type:'cond', def:step.cond_default, alt:step.cond_alt});
  renderQueue();
}

function removeLastBlock() {
  if (program.length > 0) { program.pop(); renderQueue(); }
}

function removeBlockAt(i) {
  program.splice(i, 1);
  renderQueue();
}

function changeLoopCount(i, delta) {
  if (program[i] && program[i].type === 'loop') {
    program[i].count = Math.max(1, Math.min(9, program[i].count + delta));
    renderQueue();
  }
}

/* ═══════════════════════════════════════════════════════════════════
   RENDER QUEUE
═══════════════════════════════════════════════════════════════════ */
function renderQueue() {
  const lv = getLv();
  if (lv.mode === 'debug') return;

  const q = document.getElementById('program-queue');
  q.innerHTML = '';

  program.forEach((b, i) => {
    if (typeof b === 'string') {
      const sp = document.createElement('span');
      sp.className = 'prog-block pb-arr';
      sp.innerHTML = dirEmoji(b) + ' ' + dirName(b);
      sp.title = 'Clique pour supprimer';
      sp.onclick = () => removeBlockAt(i);
      q.appendChild(sp);

    } else if (b.type === 'loop') {
      const wrap = document.createElement('span');
      wrap.className = 'loop-inline';
      wrap.innerHTML = `🔁`;

      const minus = document.createElement('button');
      minus.className = 'loop-count-btn'; minus.textContent = '−';
      minus.onclick = (e) => { e.stopPropagation(); changeLoopCount(i, -1); };

      const count = document.createElement('span');
      count.className = 'loop-count-display'; count.textContent = b.count + '×';

      const plus = document.createElement('button');
      plus.className = 'loop-count-btn'; plus.textContent = '+';
      plus.onclick = (e) => { e.stopPropagation(); changeLoopCount(i, +1); };

      const label = document.createElement('span');
      label.textContent = dirEmoji(b.dir);

      const del = document.createElement('button');
      del.className = 'loop-count-btn'; del.textContent = '✕';
      del.style.background = 'rgba(204,51,51,.5)';
      del.onclick = (e) => { e.stopPropagation(); removeBlockAt(i); };

      wrap.appendChild(minus); wrap.appendChild(count); wrap.appendChild(plus);
      wrap.appendChild(label); wrap.appendChild(del);
      q.appendChild(wrap);

    } else if (b.type === 'cond') {
      const sp = document.createElement('span');
      sp.className = 'prog-block pb-cd';
      sp.innerHTML = `🤔 Si obs→${dirEmoji(b.alt)} sinon ${dirEmoji(b.def)}`;
      sp.title = 'Clique pour supprimer';
      sp.onclick = () => removeBlockAt(i);
      q.appendChild(sp);
    }
  });
}

/* ── DEBUG queue ── */
function renderDebugQueue(step) {
  const q = document.getElementById('program-queue');
  q.innerHTML = '';
  document.getElementById('blocks-palette').innerHTML = '';

  const bugIdx = step.bugIndices || [];

  program.forEach((b, i) => {
    const isBug = bugIdx.includes(i);
    const sp = document.createElement('span');
    sp.className = 'prog-block ' + (isBug ? 'pb-bug' : 'pb-ok');
    sp.innerHTML = (isBug ? '🐛 ' : '') + dirEmoji(b) + ' ' + dirName(b);
    sp.title = 'Clique pour supprimer';
    sp.onclick = () => debugClick(i, step);
    q.appendChild(sp);
  });
}

function debugClick(clickedIdx, step) {
  const bugIdx = step.bugIndices || [];
  if (bugIdx.includes(clickedIdx)) {
    // Bon bug !
    bugsFound.push(clickedIdx);
    program.splice(clickedIdx, 1);

    // Recalcule les indices restants (décaler après suppression)
    const remaining = bugIdx
      .filter(bi => !bugsFound.includes(bi) && bi !== clickedIdx)
      .map(bi => bi > clickedIdx ? bi - 1 : bi);
    step.bugIndices = remaining;

    if (remaining.length === 0) {
      // Tous les bugs trouvés → simuler
      setTimeout(() => runDebugSimulation(step), 300);
    } else {
      showToast(`🎯 Bug trouvé ! Il en reste ${remaining.length}…`);
      renderDebugQueue(step);
    }
  } else {
    showToast('❌ Ce bloc est correct ! Cherche encore 🐛');
    // Animation shake du bloc
    const blocks = document.querySelectorAll('.prog-block');
    if (blocks[clickedIdx]) {
      blocks[clickedIdx].style.animation = 'none';
      blocks[clickedIdx].offsetHeight;
      blocks[clickedIdx].style.animation = 'shake .3s';
    }
  }
}

async function runDebugSimulation(step) {
  robotPos = [...step.start];
  placeRobot(...robotPos);
  document.getElementById('btn-run').disabled = true;
  const instructions = [...program];
  for (const d of instructions) {
    await moveRobot(d, step);
  }
  document.getElementById('btn-run').disabled = false;
  checkWin(step);
}

/* ═══════════════════════════════════════════════════════════════════
   EXÉCUTION
═══════════════════════════════════════════════════════════════════ */
async function runProgram() {
  if (isRunning) return;
  const lv   = getLv();
  const step = getStep();

  if (lv.mode === 'debug') {
    showToast('🐛 Clique sur les blocs rouges pour les supprimer !');
    return;
  }
  if (program.length === 0) { showToast('➕ Ajoute des blocs !'); return; }

  isRunning = true;
  document.getElementById('btn-run').disabled = true;
  robotPos = [...step.start];
  placeRobot(...robotPos);

  const instructions = expandProgram(program, step);
  for (const instr of instructions) {
    await moveRobot(instr, step);
  }

  isRunning = false;
  document.getElementById('btn-run').disabled = false;
  checkWin(step);
}

function expandProgram(prog, step) {
  const out = [];
  for (const b of prog) {
    if (typeof b === 'string') out.push(b);
    else if (b.type === 'loop')  { for (let i=0;i<b.count;i++) out.push(b.dir); }
    else if (b.type === 'cond')  out.push({type:'cond', def:b.def, alt:b.alt});
  }
  return out;
}

async function moveRobot(instr, step) {
  const G = step.grid;
  let [r,c] = robotPos;
  let nr=r, nc=c;

  if (instr && instr.type === 'cond') {
    // Calcule la case devant (direction default)
    const [dr,dc] = dirDelta(instr.def);
    const frontR = r+dr, frontC = c+dc;
    const blocked = isObstacle(frontR, frontC, step) || outOfBounds(frontR, frontC, G);
    const dir = blocked ? instr.alt : instr.def;
    const [ar,ac] = dirDelta(dir);
    nr = r+ar; nc = c+ac;
  } else {
    const [dr,dc] = dirDelta(instr);
    nr = r+dr; nc = c+dc;
  }

  // Hors grille ou obstacle → on ne bouge pas
  if (outOfBounds(nr, nc, G) || isObstacle(nr, nc, step)) return;

  robotPos = [nr, nc];
  placeRobot(nr, nc);
  await sleep(400);
}

function isObstacle(r, c, step) {
  return (step.obstacles||[]).some(([or,oc]) => or===r && oc===c);
}
function outOfBounds(r, c, G) { return r<0||r>=G||c<0||c>=G; }

function dirDelta(d) {
  return d==='↑'?[-1,0] : d==='↓'?[1,0] : d==='←'?[0,-1] : [0,1];
}

/* ═══════════════════════════════════════════════════════════════════
   VICTOIRE
═══════════════════════════════════════════════════════════════════ */
function checkWin(step) {
  const [r,c] = robotPos;
  const [tr,tc] = step.target;
  if (r===tr && c===tc) {
    // Calcul étoiles
    const lv = getLv();
    let stars = 1;
    if (lv.mode === 'debug') {
      stars = 3; // Debug = toujours 3 étoiles si réussi
    } else {
      const solLen = flatLen(step.solution);
      const userLen = flatLen(program);
      const ratio = userLen / solLen;
      stars = ratio <= 1.1 ? 3 : ratio <= 1.6 ? 2 : 1;
    }
    spawnSparkles();
    setTimeout(() => showFeedback(true, step, stars), 400);
  } else {
    showFeedback(false, step, 0);
  }
}

function flatLen(prog) {
  let n = 0;
  (prog||[]).forEach(b => {
    if (typeof b === 'string') n++;
    else if (b.type === 'loop') n += b.count;
    else n++;
  });
  return n;
}

function showFeedback(success, step, stars) {
  const lv = getLv();
  document.getElementById('fb-emoji').textContent = success ? '🎉' : '😅';
  const title = document.getElementById('fb-title');
  title.textContent = success ? 'Bravo !' : 'Presque !';
  title.className = 'fb-title ' + (success ? 'success' : 'fail');
  document.getElementById('fb-msg').textContent = success
    ? step.successMsg
    : 'Essaie encore ! Regarde bien le chemin 🌿';

  const fbStars = document.getElementById('fb-stars');
  fbStars.innerHTML = '';
  if (success) {
    for (let i=0;i<3;i++) {
      const s = document.createElement('span');
      s.className = 'fb-star' + (i < stars ? ' earned' : '');
      s.style.animationDelay = `${i*.15}s`;
      s.textContent = '⭐';
      fbStars.appendChild(s);
    }
  }

  const hasNext = currentStep + 1 < lv.steps.length;
  const btn = document.getElementById('fb-btn');
  if (success) {
    btn.textContent = hasNext ? '➡️ Étape suivante !' : '🏠 Retour menu';
    btn.onclick = nextOrMenu;
  } else {
    btn.textContent = '🔄 Réessayer';
    btn.onclick = () => {
      document.getElementById('feedback-overlay').classList.remove('visible');
      resetLevel();
    };
  }

  document.getElementById('feedback-overlay').classList.add('visible');
}

/* ═══════════════════════════════════════════════════════════════════
   UTILITAIRES
═══════════════════════════════════════════════════════════════════ */
function sleep(ms) { return new Promise(r => setTimeout(r, ms)); }

function dirEmoji(d) {
  return d==='↑'?'⬆️' : d==='↓'?'⬇️' : d==='←'?'⬅️' : '➡️';
}
function dirName(d) {
  return d==='↑'?'Haut' : d==='↓'?'Bas' : d==='←'?'Gauche' : 'Droite';
}

function showToast(msg) {
  document.querySelectorAll('.toast').forEach(t => t.remove());
  const t = document.createElement('div');
  t.className = 'toast';
  t.textContent = msg;
  document.body.appendChild(t);
  setTimeout(() => t.remove(), 2000);
}

function spawnSparkles() {
  const emojis = ['⭐','✨','🌟','💫','🎊','🎉','🌸','🍀'];
  for (let i=0; i<14; i++) {
    const s = document.createElement('div');
    s.className = 'sparkle';
    s.textContent = emojis[Math.floor(Math.random()*emojis.length)];
    s.style.left   = Math.random()*100 + 'vw';
    s.style.top    = Math.random()*100 + 'vh';
    s.style.animationDelay = Math.random()*.6 + 's';
    s.style.fontSize = (1.4+Math.random()*2) + 'em';
    document.body.appendChild(s);
    setTimeout(() => s.remove(), 1400);
  }
}
</script>
</body>
</html>
