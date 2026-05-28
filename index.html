<!DOCTYPE html>
<html lang="sr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<meta name="theme-color" content="#07071a">
<meta name="mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="Moj Budžet">
<meta name="description" content="Ultra premium lična finansijska aplikacija">
<link rel="manifest" href="data:application/json,%7B%22name%22%3A%22Moj+Bud%C5%BEet%22%2C%22short_name%22%3A%22Bud%C5%BEet%22%2C%22description%22%3A%22Ultra+premium+finansijska+aplikacija%22%2C%22start_url%22%3A%22.%2F%22%2C%22display%22%3A%22standalone%22%2C%22background_color%22%3A%22%2307071a%22%2C%22theme_color%22%3A%22%237c6cff%22%2C%22orientation%22%3A%22portrait%22%2C%22icons%22%3A%5B%7B%22src%22%3A%22data%3Aimage%2Fsvg%2Bxml%2C%253Csvg+xmlns%3D'http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg'+viewBox%3D'0+0+512+512'%253E%253Crect+width%3D'512'+height%3D'512'+rx%3D'100'+fill%3D'%237c6cff'%2F%253E%253Ctext+x%3D'50%25'+y%3D'55%25'+text-anchor%3D'middle'+dominant-baseline%3D'middle'+font-size%3D'300'%253E%F0%9F%92%8E%253C%2Ftext%253E%253C%2Fsvg%253E%22%2C%22sizes%22%3A%22512x512%22%2C%22type%22%3A%22image%2Fsvg%2Bxml%22%2C%22purpose%22%3A%22any+maskable%22%7D%5D%7D">
<title>Moj Budžet 💎</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;500;600;700;800&family=DM+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #07071a;
    --bg2: #0d0d24;
    --card: #0f0f2a;
    --card2: #141438;
    --acc1: #7c6cff;
    --acc2: #a78bfa;
    --acc3: #38bdf8;
    --green: #22d3ee;
    --pink: #f472b6;
    --text: #e2e8f0;
    --muted: #6b7a99;
    --border: rgba(255,255,255,0.08);
    --glow: #7c6cff;
    --nav-bg: rgba(10,10,28,0.92);
    --sh: 8px;
    --sb: 24px;
    --glass: 18px;
    --float-speed: 3s;
    --glow-pulse: 2s;
    --anim-speed: 1;
    --avatar-w: 82px;
    --avatar-h: 82px;
    --avatar-opacity: 1;
    --avatar-glow: rgba(124,108,255,0.7);
    --avatar-glow-size: 60px;
    --ambient-color: #7c6cff;
    --ambient-size: 180px;
    --ambient-blur: 70px;
    --ambient-intensity: 0.45;
  }
  *{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent}
  html,body{height:100%;overflow:hidden;background:var(--bg);font-family:'DM Sans',sans-serif;color:var(--text)}
  ::-webkit-scrollbar{width:0;height:0}
  input,select,button,textarea{font-family:'DM Sans',sans-serif}

  /* ANIMATIONS */
  @keyframes float{0%,100%{transform:translateY(0)}50%{transform:translateY(calc(var(--fi,8px) * -1))}}
  @keyframes ambientPulse{0%,100%{opacity:var(--ambient-intensity);transform:translate(-50%,-50%) scale(1)}50%{opacity:calc(var(--ambient-intensity)*1.6);transform:translate(-50%,-50%) scale(1.12)}}
  @keyframes glowPulse{0%,100%{box-shadow:0 0 20px var(--glow)55}50%{box-shadow:0 0 45px var(--glow)cc,0 0 70px var(--acc2)44}}
  @keyframes bounce{0%,60%,100%{transform:translateY(0)}30%{transform:translateY(-7px)}}
  @keyframes slideUp{from{transform:translateY(22px);opacity:0}to{transform:translateY(0);opacity:1}}
  @keyframes fadeIn{from{opacity:0}to{opacity:1}}
  @keyframes spin{to{transform:rotate(360deg)}}
  @keyframes ripple{0%{transform:scale(0);opacity:0.6}100%{transform:scale(4);opacity:0}}
  @keyframes shimmer{0%{background-position:-200% 0}100%{background-position:200% 0}}

  /* LAYOUT */
  #app{position:fixed;inset:0;display:flex;flex-direction:column;max-width:430px;margin:0 auto;overflow:hidden;background:linear-gradient(160deg,var(--bg) 0%,var(--bg2) 100%)}
  #ambient-bg{position:fixed;inset:0;pointer-events:none;z-index:0;background:radial-gradient(ellipse at 15% 15%, rgba(124,108,255,0.06) 0%, transparent 55%), radial-gradient(ellipse at 85% 85%, rgba(56,189,248,0.04) 0%, transparent 55%)}
  .page{position:absolute;inset:0;top:0;bottom:80px;overflow-y:auto;overflow-x:hidden;padding:0 16px 20px;z-index:1;display:none;animation:fadeIn 0.25s ease}
  .page.active{display:block}

  /* CARDS */
  .card{background:linear-gradient(135deg,rgba(15,15,42,0.95) 0%,rgba(20,20,56,0.85) 100%);border:1px solid var(--border);border-radius:20px;backdrop-filter:blur(var(--glass));box-shadow:0 var(--sh) var(--sb) rgba(0,0,0,0.5),inset 0 1px 0 rgba(255,255,255,0.06),0 0 30px rgba(124,108,255,0.08)}
  .card-glow{box-shadow:0 var(--sh) var(--sb) rgba(0,0,0,0.5),inset 0 1px 0 rgba(255,255,255,0.07),0 0 35px rgba(124,108,255,0.15)}

  /* BUTTONS */
  .btn{border:none;border-radius:14px;padding:13px 26px;font-weight:700;font-size:14px;cursor:pointer;transition:all 0.18s ease;letter-spacing:0.4px;position:relative;overflow:hidden}
  .btn:active{transform:scale(0.96)}
  .btn-primary{background:linear-gradient(135deg,var(--acc1)dd,var(--acc2)99);color:#fff;border:1px solid rgba(124,108,255,0.5);box-shadow:0 4px 20px rgba(124,108,255,0.4),inset 0 1px 0 rgba(255,255,255,0.2)}
  .btn-green{background:linear-gradient(135deg,rgba(34,211,238,0.85),rgba(34,211,238,0.5));color:#fff;border:1px solid rgba(34,211,238,0.5);box-shadow:0 4px 18px rgba(34,211,238,0.3)}
  .btn-pink{background:linear-gradient(135deg,rgba(244,114,182,0.85),rgba(244,114,182,0.5));color:#fff;border:1px solid rgba(244,114,182,0.5);box-shadow:0 4px 18px rgba(244,114,182,0.3)}
  .btn-danger{background:linear-gradient(135deg,rgba(239,68,68,0.85),rgba(239,68,68,0.5));color:#fff;border:1px solid rgba(239,68,68,0.5);box-shadow:0 4px 18px rgba(239,68,68,0.3)}
  .btn-sm{padding:7px 15px;font-size:12px;border-radius:11px}
  .btn-ghost{background:rgba(15,15,42,0.7);border:1px solid var(--border);color:var(--muted)}
  .btn-full{width:100%}

  /* INPUTS */
  .input{width:100%;padding:11px 15px;background:rgba(15,15,42,0.8);border:1px solid var(--border);border-radius:13px;color:var(--text);font-size:14px;outline:none;transition:border-color 0.2s}
  .input:focus{border-color:rgba(124,108,255,0.5)}
  .input-big{font-size:24px;font-weight:800;text-align:center;padding:16px}
  select.input{cursor:pointer}

  /* GRADIENT TEXT */
  .grad-text{background:linear-gradient(135deg,var(--acc2),var(--acc3));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text}
  .grad-text2{background:linear-gradient(135deg,var(--text),var(--acc2));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text}

  /* RANGE SLIDERS */
  input[type=range]{-webkit-appearance:none;height:4px;border-radius:2px;background:var(--border);width:100%}
  input[type=range]::-webkit-slider-thumb{-webkit-appearance:none;width:19px;height:19px;border-radius:50%;background:var(--acc1);cursor:pointer;box-shadow:0 0 10px var(--acc1)}
  input[type=color]{width:46px;height:32px;border-radius:9px;border:none;cursor:pointer;background:none;padding:0}

  /* BOTTOM NAV */
  #bottom-nav{position:absolute;bottom:0;left:0;right:0;z-index:100;padding:0 12px 14px}
  .nav-inner{display:flex;align-items:center;justify-content:space-around;padding:9px 6px;background:var(--nav-bg);backdrop-filter:blur(24px);border-radius:24px;border:1px solid var(--border);box-shadow:0 -4px 28px rgba(124,108,255,0.15),0 8px 40px rgba(0,0,0,0.5)}
  .nav-btn{display:flex;flex-direction:column;align-items:center;gap:2px;padding:6px 10px;border-radius:14px;border:none;background:transparent;cursor:pointer;transition:all 0.2s;min-width:44px}
  .nav-btn.active{background:rgba(124,108,255,0.2)}
  .nav-btn .icon{font-size:20px;transition:filter 0.2s}
  .nav-btn.active .icon{filter:drop-shadow(0 0 7px var(--glow))}
  .nav-btn .label{font-size:9px;color:var(--muted);font-weight:500}
  .nav-btn.active .label{color:var(--acc2);font-weight:700}
  .nav-add{background:linear-gradient(135deg,var(--acc1),var(--acc2));border-radius:50%;width:46px;height:46px;display:flex;align-items:center;justify-content:center;font-size:22px;border:none;cursor:pointer;box-shadow:0 0 18px rgba(124,108,255,0.6);transition:all 0.2s}
  .nav-add:active{transform:scale(0.92)}

  /* OVERLAY */
  .overlay{position:fixed;inset:0;background:rgba(0,0,0,0.7);z-index:500;display:none;animation:fadeIn 0.2s ease}
  .overlay.show{display:flex;flex-direction:column;justify-content:flex-end}
  .sheet{background:linear-gradient(180deg,var(--card),var(--bg));border-radius:26px 26px 0 0;max-height:92vh;overflow-y:auto;box-shadow:0 -10px 50px rgba(124,108,255,0.2);animation:slideUp 0.3s ease}
  .sheet-header{padding:18px 20px;display:flex;justify-content:space-between;align-items:center;border-bottom:1px solid var(--border)}
  .sheet-title{font-size:17px;font-weight:800;font-family:'Syne',sans-serif}
  .close-btn{background:var(--card);border:1px solid var(--border);border-radius:10px;padding:6px 13px;color:var(--text);cursor:pointer;font-size:15px}

  /* TX ITEM */
  .tx-item{display:flex;align-items:center;gap:13px;padding:13px 15px;margin-bottom:9px;background:rgba(15,15,42,0.8);border-radius:15px;border:1px solid var(--border);backdrop-filter:blur(10px);transition:all 0.2s}
  .tx-icon{width:42px;height:42px;border-radius:13px;display:flex;align-items:center;justify-content:center;font-size:20px;flex-shrink:0}
  .tx-info{flex:1;min-width:0}
  .tx-name{font-size:13px;font-weight:600;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
  .tx-meta{font-size:11px;color:var(--muted);margin-top:2px}
  .tx-amount{font-size:14px;font-weight:800;flex-shrink:0}

  /* CATEGORY GRID */
  .cat-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:8px}
  .cat-btn{padding:11px 4px;border-radius:13px;border:1px solid var(--border);background:var(--card);cursor:pointer;text-align:center;transition:all 0.18s}
  .cat-btn.selected{box-shadow:0 0 12px currentColor}
  .cat-emoji{font-size:20px}
  .cat-name{font-size:9px;color:var(--muted);margin-top:3px}
  .cat-btn.selected .cat-name{font-weight:700}

  /* PROGRESS BAR */
  .progress-wrap{height:7px;border-radius:4px;background:var(--border);overflow:hidden}
  .progress-bar{height:100%;border-radius:4px;transition:width 0.8s cubic-bezier(0.34,1.56,0.64,1)}

  /* DONUT */
  .chart-wrap{display:flex;align-items:center;gap:18px}
  .legend-item{display:flex;justify-content:space-between;align-items:center;margin-bottom:7px}
  .legend-dot{width:9px;height:9px;border-radius:50%;flex-shrink:0}

  /* GOAL CIRCLE */
  .goal-card{display:flex;align-items:center;gap:15px;padding:15px;margin-bottom:11px}
  .goal-circle{position:relative;width:82px;height:82px;flex-shrink:0}
  .goal-inner{position:absolute;top:50%;left:50%;transform:translate(-50%,-50%);text-align:center}

  /* FLOATING AVATAR */
  #float-avatar{position:fixed;z-index:9999;cursor:grab;user-select:none;touch-action:none;left:18px;top:420px;transition:width 0.3s,height 0.3s}
  #float-avatar:active{cursor:grabbing}
  .avatar-ambient{position:absolute;left:50%;top:50%;transform:translate(-50%,-50%);border-radius:50%;pointer-events:none;animation:ambientPulse var(--glow-pulse) ease-in-out infinite}
  .avatar-body{border-radius:50%;display:flex;align-items:center;justify-content:center;overflow:hidden;animation:float var(--float-speed) ease-in-out infinite;transition:all 0.3s ease;position:relative;z-index:2}
  .avatar-body img{width:100%;height:100%;object-fit:contain;border-radius:50%}
  .avatar-body.custom-img img{border-radius:0 !important;object-fit:contain}
  .avatar-status{position:absolute;bottom:3px;right:3px;width:11px;height:11px;border-radius:50%;border:2px solid var(--bg);z-index:3}
  .avatar-mini-toggle{position:absolute;top:-9px;right:-9px;width:20px;height:20px;border-radius:50%;background:var(--acc1);border:none;color:#fff;font-size:11px;cursor:pointer;display:flex;align-items:center;justify-content:center;z-index:4;box-shadow:0 0 8px var(--acc1)}

  /* SETTINGS TABS */
  .stab-row{display:flex;gap:7px;padding:12px 16px;overflow-x:auto;border-bottom:1px solid var(--border)}
  .stab{padding:7px 15px;border-radius:12px;border:1px solid var(--border);background:var(--card);color:var(--muted);font-weight:600;font-size:12px;cursor:pointer;white-space:nowrap;flex-shrink:0;transition:all 0.18s}
  .stab.active{border-color:var(--acc1);background:rgba(124,108,255,0.2);color:var(--acc2)}
  .stab-content{display:none;padding:16px 16px 36px}
  .stab-content.active{display:block}

  /* SECTION LABEL */
  .slabel{font-size:11px;color:var(--muted);letter-spacing:1.2px;font-weight:700;margin:18px 0 10px}

  /* STATUS BADGE */
  .status-badge{display:flex;align-items:center;gap:9px;padding:11px 15px;background:var(--card);border-radius:14px;border:1px solid var(--border);margin-bottom:16px}
  .status-dot{width:10px;height:10px;border-radius:50%;flex-shrink:0}

  /* AI CHAT */
  #ai-panel .sheet{max-height:88vh;height:88vh;display:flex;flex-direction:column;border-radius:26px 26px 0 0}
  .chat-area{flex:1;overflow-y:auto;padding:16px}
  .chat-msg{display:flex;margin-bottom:13px;animation:slideUp 0.2s ease}
  .chat-msg.user{justify-content:flex-end}
  .chat-bubble{max-width:82%;padding:11px 15px;border-radius:16px;font-size:13px;line-height:1.55}
  .chat-bubble.ai{background:rgba(15,15,42,0.9);border:1px solid var(--border);border-radius:16px 16px 16px 4px;backdrop-filter:blur(10px)}
  .chat-bubble.user{background:linear-gradient(135deg,rgba(124,108,255,0.8),rgba(167,139,250,0.6));border:1px solid rgba(124,108,255,0.5);border-radius:16px 16px 4px 16px;box-shadow:0 0 14px rgba(124,108,255,0.25)}
  .typing-dot{width:8px;height:8px;border-radius:50%;background:var(--acc1);animation:bounce 0.8s ease-in-out infinite;display:inline-block}
  .quick-cmds{display:flex;gap:7px;padding:0 16px 8px;overflow-x:auto}
  .quick-cmd{padding:5px 13px;border-radius:20px;border:1px solid rgba(124,108,255,0.35);background:rgba(124,108,255,0.08);color:var(--acc2);font-size:11px;cursor:pointer;white-space:nowrap;flex-shrink:0;transition:all 0.15s}
  .quick-cmd:active{background:rgba(124,108,255,0.25)}
  .chat-input-row{display:flex;gap:9px;padding:9px 16px 26px}
  .chat-input{flex:1;padding:11px 15px;background:rgba(15,15,42,0.85);border:1px solid var(--border);border-radius:15px;color:var(--text);font-size:13px;outline:none}
  .mic-btn{width:46px;height:46px;border-radius:14px;border:1px solid var(--border);background:var(--card);cursor:pointer;font-size:19px;display:flex;align-items:center;justify-content:center;flex-shrink:0;transition:all 0.2s}
  .mic-btn.listening{border-color:rgba(244,114,182,0.6);background:rgba(244,114,182,0.15);animation:glowPulse 0.5s ease-in-out infinite}
  .send-btn{width:46px;height:46px;border-radius:14px;border:1px solid rgba(124,108,255,0.5);background:linear-gradient(135deg,var(--acc1)cc,var(--acc2)77);color:#fff;cursor:pointer;font-size:18px;display:flex;align-items:center;justify-content:center;flex-shrink:0;box-shadow:0 0 14px rgba(124,108,255,0.4)}

  /* NOTIFICATION */
  #notif{position:fixed;top:22px;left:50%;transform:translateX(-50%);padding:10px 22px;border-radius:15px;color:#fff;font-size:13px;font-weight:700;z-index:9997;display:none;animation:slideUp 0.3s ease;white-space:nowrap;backdrop-filter:blur(20px);max-width:90%;text-align:center}

  /* MINI CHART */
  .mini-chart-wrap{overflow:visible}

  /* FILTER TABS */
  .filter-tabs{display:flex;gap:7px;margin-bottom:15px}
  .ftab{flex:1;padding:8px 0;border-radius:13px;border:1px solid var(--border);background:var(--card);color:var(--muted);font-weight:600;font-size:12px;cursor:pointer;transition:all 0.18s}
  .ftab.active{border-color:var(--acc3);background:rgba(56,189,248,0.15);color:var(--acc3)}

  /* AVATAR UPLOAD */
  .avatar-upload-area{border:2px dashed var(--border);border-radius:16px;padding:20px;text-align:center;cursor:pointer;transition:all 0.2s;position:relative}
  .avatar-upload-area:hover{border-color:var(--acc1);background:rgba(124,108,255,0.05)}
  .avatar-preview-wrap{display:flex;justify-content:center;margin-bottom:16px}
  .avatar-preview{width:90px;height:90px;border-radius:50%;overflow:hidden;border:2px solid var(--border);display:flex;align-items:center;justify-content:center;font-size:36px;background:radial-gradient(circle at 35% 35%,var(--acc1)cc,var(--acc2)55);box-shadow:0 0 20px rgba(124,108,255,0.4)}
  .avatar-preview img{width:100%;height:100%;object-fit:contain}
  #avatar-file-input{display:none}

  /* REMOVE BG CANVAS */
  #remove-bg-canvas{display:none}

  /* GRID 2 */
  .grid2{display:grid;grid-template-columns:1fr 1fr;gap:11px}
  .row-between{display:flex;justify-content:space-between;align-items:center}

  /* PROFILE SCORE */
  .score-bar{height:9px;border-radius:5px;background:var(--border);overflow:hidden;margin-top:8px}
  .score-fill{height:100%;border-radius:5px;background:linear-gradient(90deg,var(--acc1),var(--acc2),var(--green));box-shadow:0 0 14px rgba(124,108,255,0.6);transition:width 1.2s cubic-bezier(0.34,1.56,0.64,1)}
  .reminder-item{display:flex;align-items:center;gap:13px;padding:12px 15px;margin-bottom:9px;background:rgba(15,15,42,0.8);border-radius:15px;border:1px solid var(--border)}
  .reminder-check{width:30px;height:30px;border-radius:9px;border:none;cursor:pointer;font-size:14px;display:flex;align-items:center;justify-content:center;flex-shrink:0;transition:all 0.2s}
  
  /* PAGE HEADER */
  .ph{padding:18px 0 13px;font-size:21px;font-weight:800;font-family:'Syne',sans-serif}

  /* DATE GROUP */
  .date-label{font-size:10px;color:var(--muted);letter-spacing:1px;font-weight:700;margin-bottom:8px;padding-left:4px}

  /* LIGHT THEME */
  body.light{
    --bg:#f0f0fa;--bg2:#e8e8f5;--card:rgba(255,255,255,0.95);--card2:#f5f5ff;
    --text:#1e1b4b;--muted:#6b7280;--border:rgba(124,108,255,0.15);
    --nav-bg:rgba(240,240,250,0.94);
  }
  body.light #ambient-bg{background:radial-gradient(ellipse at 15% 15%,rgba(124,108,255,0.08) 0%,transparent 55%),radial-gradient(ellipse at 85% 85%,rgba(56,189,248,0.06) 0%,transparent 55%)}
  body.light .card{background:rgba(255,255,255,0.95);box-shadow:0 4px 20px rgba(124,108,255,0.12),inset 0 1px 0 rgba(255,255,255,0.9)}
  body.light .input{background:rgba(240,240,250,0.9);color:var(--text)}
  body.light .cat-btn{background:rgba(240,240,250,0.9)}
  body.light .chat-bubble.ai{background:rgba(240,240,250,0.95);color:var(--text)}
  body.light #app{background:linear-gradient(160deg,var(--bg),var(--bg2))}
</style>
</head>
<body>

<div id="ambient-bg"></div>

<!-- NOTIFICATION -->
<div id="notif"></div>

<!-- FLOATING AVATAR -->
<div id="float-avatar">
  <div class="avatar-ambient" id="avatar-ambient" style="width:var(--avatar-glow-size);height:var(--avatar-glow-size);background:radial-gradient(circle,var(--avatar-glow) 0%,transparent 70%);filter:blur(20px)"></div>
  <div class="avatar-body" id="avatar-body" style="width:var(--avatar-w);height:var(--avatar-h);background:radial-gradient(circle at 35% 35%,var(--acc1)cc,var(--acc2)66);box-shadow:0 0 var(--avatar-glow-size) var(--avatar-glow),inset 0 1px 0 rgba(255,255,255,0.3);border:2px solid rgba(124,108,255,0.5);font-size:38px">
    🤖
  </div>
  <div class="avatar-status" id="avatar-status" style="background:#fb923c;box-shadow:0 0 8px #fb923c"></div>
  <button class="avatar-mini-toggle" id="avatar-mini-toggle" onclick="toggleAvatarMini()">−</button>
</div>

<!-- REMOVE BG CANVAS (hidden) -->
<canvas id="remove-bg-canvas"></canvas>

<!-- APP -->
<div id="app">
  <!-- HOME -->
  <div class="page active" id="page-home">
    <div style="display:flex;justify-content:space-between;align-items:center;padding:18px 0 12px">
      <div>
        <div style="font-size:11px;color:var(--muted);letter-spacing:1.5px">DOBRO JUTRO</div>
        <div style="font-size:21px;font-weight:800;font-family:'Syne',sans-serif" class="grad-text" id="home-username">Šefe</div>
      </div>
      <div style="display:flex;gap:9px">
        <button class="btn btn-ghost btn-sm" onclick="openSettings()" style="padding:9px 11px;font-size:17px">⚙️</button>
        <button class="btn btn-primary btn-sm" onclick="openAI()" style="padding:9px 11px;font-size:17px">🤖</button>
      </div>
    </div>

    <!-- BALANCE CARD -->
    <div class="card card-glow" style="padding:24px;margin-bottom:16px;position:relative;overflow:hidden">
      <div style="position:absolute;top:-35px;right:-35px;width:130px;height:130px;border-radius:50%;background:radial-gradient(circle,rgba(124,108,255,0.18),transparent 70%);pointer-events:none"></div>
      <div style="font-size:11px;color:var(--muted);letter-spacing:2px;margin-bottom:7px">UKUPAN SALDO</div>
      <div style="font-size:38px;font-weight:900;letter-spacing:-1px;margin-bottom:5px" class="grad-text2" id="home-balance">145.000 RSD</div>
      <div style="font-size:12px;color:var(--green);margin-bottom:22px;display:flex;align-items:center;gap:5px" id="home-trend">
        <span>↗</span><span>+12.4% ovaj mesec</span>
      </div>
      <div style="display:flex;gap:14px">
        <div onclick="openAddTx('income')" style="flex:1;padding:13px 15px;background:rgba(34,211,238,0.08);border-radius:13px;border:1px solid rgba(34,211,238,0.2);cursor:pointer;active:opacity:0.7;transition:all 0.15s" ontouchstart="this.style.background='rgba(34,211,238,0.18)'" ontouchend="this.style.background='rgba(34,211,238,0.08)'">
          <div style="font-size:10px;color:var(--green);letter-spacing:1px;margin-bottom:4px;display:flex;justify-content:space-between;align-items:center">
            <span>PRIHODI</span><span style="font-size:16px">＋</span>
          </div>
          <div style="font-size:16px;font-weight:800;color:var(--green)" id="home-income">145.000</div>
          <div style="font-size:10px;color:rgba(34,211,238,0.5);margin-top:3px">Klikni da dodaš</div>
        </div>
        <div onclick="openAddTx('expense')" style="flex:1;padding:13px 15px;background:rgba(244,114,182,0.08);border-radius:13px;border:1px solid rgba(244,114,182,0.2);cursor:pointer;transition:all 0.15s" ontouchstart="this.style.background='rgba(244,114,182,0.18)'" ontouchend="this.style.background='rgba(244,114,182,0.08)'">
          <div style="font-size:10px;color:var(--pink);letter-spacing:1px;margin-bottom:4px;display:flex;justify-content:space-between;align-items:center">
            <span>RASHODI</span><span style="font-size:16px">＋</span>
          </div>
          <div style="font-size:16px;font-weight:800;color:var(--pink)" id="home-expense">10.610</div>
          <div style="font-size:10px;color:rgba(244,114,182,0.5);margin-top:3px">Klikni da dodaš</div>
        </div>
      </div>
    </div>

    <!-- MINI CHART -->
    <div class="card" style="padding:16px;margin-bottom:16px">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:12px">
        <span style="font-size:13px;font-weight:700" id="home-chart-label">Maj 2026</span>
        <span style="font-size:11px;color:var(--acc3);cursor:pointer" onclick="showPage('stats')">Vidi sve →</span>
      </div>
      <svg id="home-chart" width="100%" height="55" viewBox="0 0 300 55" preserveAspectRatio="none" style="overflow:visible"></svg>
      <div style="display:flex;gap:16px;margin-top:9px">
        <span style="font-size:11px;color:var(--green)">● Prihodi</span>
        <span style="font-size:11px;color:var(--pink)">● Rashodi</span>
      </div>
    </div>

    <!-- CATEGORIES -->
    <div style="margin-bottom:16px">
      <div style="font-size:13px;font-weight:700;margin-bottom:11px">Top kategorije</div>
      <div id="home-cats" style="display:flex;gap:9px;overflow-x:auto;padding-bottom:4px"></div>
    </div>

    <!-- AI INSIGHT -->
    <div class="card" style="padding:15px;margin-bottom:16px;background:linear-gradient(135deg,rgba(124,108,255,0.15),rgba(56,189,248,0.06));border-color:rgba(124,108,255,0.3)">
      <div style="display:flex;align-items:center;gap:9px;margin-bottom:7px">
        <span style="font-size:19px">🤖</span>
        <span style="font-size:11px;font-weight:800;color:var(--acc2);letter-spacing:1px">AI UVID</span>
      </div>
      <p style="font-size:13px;line-height:1.55" id="home-ai-insight">Učitavam uvid...</p>
    </div>

    <!-- RECENT TXs -->
    <div>
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:11px">
        <span style="font-size:13px;font-weight:700">Nedavne transakcije</span>
        <span style="font-size:11px;color:var(--acc3);cursor:pointer" onclick="showPage('transactions')">Sve →</span>
      </div>
      <div id="home-recent-txs"></div>
    </div>
  </div>

  <!-- TRANSACTIONS -->
  <div class="page" id="page-transactions">
    <div class="ph">Transakcije</div>
    <div style="position:relative;margin-bottom:12px">
      <input class="input" id="tx-search" placeholder="Pretraži transakcije..." oninput="renderTransactions()" style="padding-left:40px">
      <span style="position:absolute;left:13px;top:50%;transform:translateY(-50%);font-size:17px">🔍</span>
    </div>
    <div class="filter-tabs">
      <button class="ftab active" onclick="setTxFilter('all',this)">Sve</button>
      <button class="ftab" onclick="setTxFilter('income',this)">Prihodi</button>
      <button class="ftab" onclick="setTxFilter('expense',this)">Rashodi</button>
    </div>
    <div id="tx-list"></div>
  </div>

  <!-- STATS -->
  <div class="page" id="page-stats">
    <div class="ph">Statistika</div>
    <div class="filter-tabs">
      <button class="ftab active" onclick="setStatsFilter('monthly',this)">Mesečno</button>
      <button class="ftab" onclick="setStatsFilter('weekly',this)">Nedeljno</button>
      <button class="ftab" onclick="setStatsFilter('yearly',this)">Godišnje</button>
    </div>
    <div class="grid2" style="margin-bottom:16px" id="stats-cards"></div>

    <!-- DONUT -->
    <div class="card" style="padding:17px;margin-bottom:16px">
      <div style="font-size:13px;font-weight:700;margin-bottom:13px">Raspodela rashoda</div>
      <div class="chart-wrap">
        <svg id="donut-svg" width="115" height="115" style="flex-shrink:0;filter:drop-shadow(0 0 10px rgba(124,108,255,0.3))"></svg>
        <div id="donut-legend" style="flex:1"></div>
      </div>
    </div>

    <!-- BAR CHART -->
    <div class="card" style="padding:17px;margin-bottom:16px">
      <div style="font-size:13px;font-weight:700;margin-bottom:13px">Prihodi vs Rashodi</div>
      <div id="bar-chart" style="display:flex;align-items:flex-end;gap:7px;height:90px"></div>
      <div style="display:flex;gap:16px;margin-top:9px">
        <span style="font-size:11px;color:var(--green)">● Prihodi</span>
        <span style="font-size:11px;color:var(--pink)">● Rashodi</span>
      </div>
    </div>

    <!-- BUDGETS -->
    <div style="margin-bottom:16px">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:11px">
        <span style="font-size:13px;font-weight:700">Budžeti</span>
        <button class="btn btn-sm" style="background:rgba(56,189,248,0.2);border:1px solid rgba(56,189,248,0.4);color:var(--acc3)" onclick="openAddBudget()">+ Dodaj</button>
      </div>
      <div id="budgets-list"></div>
    </div>

    <!-- GOALS -->
    <div>
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:11px">
        <span style="font-size:13px;font-weight:700">Ciljevi štednje</span>
        <button class="btn btn-sm" style="background:rgba(124,108,255,0.2);border:1px solid rgba(124,108,255,0.4);color:var(--acc2)" onclick="openAddGoal()">+ Dodaj</button>
      </div>
      <div id="goals-list"></div>
    </div>
  </div>

  <!-- PROFILE -->
  <div class="page" id="page-profile">
    <div class="ph">Profil</div>
    <div class="card card-glow" style="padding:26px;margin-bottom:16px;text-align:center;position:relative;overflow:hidden">
      <div style="position:absolute;top:0;left:0;right:0;height:42%;background:linear-gradient(135deg,rgba(124,108,255,0.2),rgba(56,189,248,0.07))"></div>
      <div style="width:72px;height:72px;border-radius:50%;background:linear-gradient(135deg,var(--acc1),var(--acc2));display:flex;align-items:center;justify-content:center;font-size:32px;margin:0 auto 13px;box-shadow:0 0 22px rgba(124,108,255,0.5);position:relative">
        👤
      </div>
      <div style="font-size:23px;font-weight:800;font-family:'Syne',sans-serif;margin-bottom:4px" id="prof-name">Šefe</div>
      <div style="font-size:13px;color:var(--muted)">Personalni budžet</div>
    </div>
    <div class="grid2" style="margin-bottom:16px" id="profile-stats"></div>
    <div class="card" style="padding:17px;margin-bottom:16px">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:5px">
        <span style="font-size:13px;font-weight:700">Finansijski skor</span>
        <span style="font-size:13px;font-weight:800;color:var(--acc2)" id="score-val">0/100</span>
      </div>
      <div class="score-bar"><div class="score-fill" id="score-fill" style="width:0%"></div></div>
      <div style="font-size:11px;color:var(--muted);margin-top:7px" id="score-msg"></div>
    </div>
    <div>
      <div style="font-size:13px;font-weight:700;margin-bottom:11px">Podsetnici</div>
      <div id="reminders-list"></div>
    </div>
  </div>

  <!-- BOTTOM NAV -->
  <div id="bottom-nav">
    <div class="nav-inner">
      <button class="nav-btn active" id="nav-home" onclick="showPage('home')">
        <span class="icon">🏠</span><span class="label">Početna</span>
      </button>
      <button class="nav-btn" id="nav-transactions" onclick="showPage('transactions')">
        <span class="icon">💳</span><span class="label">Transakcije</span>
      </button>
      <button class="nav-add" onclick="openAddTx('expense')">➕</button>
      <button class="nav-btn" id="nav-stats" onclick="showPage('stats')">
        <span class="icon">📊</span><span class="label">Statistika</span>
      </button>
      <button class="nav-btn" id="nav-profile" onclick="showPage('profile')">
        <span class="icon">👤</span><span class="label">Profil</span>
      </button>
    </div>
  </div>
</div>

<!-- ADD TX SHEET -->
<div class="overlay" id="add-tx-overlay">
  <div class="sheet">
    <div class="sheet-header">
      <span class="sheet-title" id="add-tx-title">➕ Novi Rashod</span>
      <button class="close-btn" onclick="closeOverlay('add-tx-overlay')">✕</button>
    </div>
    <div style="padding:16px 20px 32px">
      <div style="display:flex;gap:9px;margin-bottom:16px">
        <button class="btn btn-pink btn-sm" id="add-type-exp" onclick="setAddType('expense')" style="flex:1;padding:11px">💸 Rashod</button>
        <button class="btn btn-ghost btn-sm" id="add-type-inc" onclick="setAddType('income')" style="flex:1;padding:11px">💰 Prihod</button>
      </div>
      <div style="margin-bottom:15px">
        <div style="font-size:11px;color:var(--muted);letter-spacing:1px;margin-bottom:7px">IZNOS (RSD)</div>
        <input class="input input-big" id="add-amount" type="number" placeholder="0">
      </div>
      <div style="margin-bottom:15px">
        <div style="font-size:11px;color:var(--muted);letter-spacing:1px;margin-bottom:9px">KATEGORIJA</div>
        <div class="cat-grid" id="add-cat-grid"></div>
      </div>
      <div style="margin-bottom:14px">
        <input class="input" id="add-desc" placeholder="Opis (opcionalno)...">
      </div>
      <div style="display:flex;gap:9px;margin-bottom:20px">
        <input class="input" id="add-date" type="date" style="flex:1">
        <input class="input" id="add-time" type="time" style="flex:1">
      </div>
      <button class="btn btn-full btn-primary" onclick="saveTransaction()" id="add-save-btn">✓ Sačuvaj transakciju</button>
    </div>
  </div>
</div>

<!-- SETTINGS SHEET -->
<div class="overlay" id="settings-overlay">
  <div class="sheet" style="max-height:94vh">
    <div class="sheet-header">
      <span class="sheet-title">⚙️ Podešavanja</span>
      <button class="close-btn" onclick="closeOverlay('settings-overlay')">✕</button>
    </div>
    <div class="stab-row">
      <button class="stab active" onclick="switchStab('theme',this)">🎨 Tema</button>
      <button class="stab" onclick="switchStab('ai',this)">🤖 AI</button>
      <button class="stab" onclick="switchStab('avatar',this)">👾 Avatar</button>
      <button class="stab" onclick="switchStab('profile',this)">👤 Profil</button>
    </div>

    <!-- THEME TAB -->
    <div class="stab-content active" id="stab-theme">
      <div class="slabel">TEMA MOD</div>
      <div style="display:flex;gap:9px;margin-bottom:16px">
        <button class="btn btn-sm" id="tm-dark" onclick="setThemeMode('dark')" style="flex:1;padding:10px">🌙 Tamna</button>
        <button class="btn btn-sm btn-ghost" id="tm-light" onclick="setThemeMode('light')" style="flex:1;padding:10px">☀️ Svetla</button>
        <button class="btn btn-sm btn-ghost" id="tm-auto" onclick="setThemeMode('auto')" style="flex:1;padding:10px">🔄 Auto</button>
      </div>
      <div class="slabel">BOJE</div>
      <div id="color-pickers"></div>
      <div class="slabel">NEUMORPHISM</div>
      <div id="neu-sliders"></div>
      <div class="slabel">GLASSMORPHISM</div>
      <div id="glass-sliders"></div>
      <div class="slabel">ANIMACIJE</div>
      <div id="anim-sliders"></div>
      <button class="btn btn-danger btn-full" style="margin-top:12px" onclick="resetTheme()">🔄 Reset na default</button>
    </div>

    <!-- AI TAB -->
    <div class="stab-content" id="stab-ai">
      <div class="slabel">GROQ AI API</div>
      <div class="status-badge" id="ai-status-badge">
        <div class="status-dot" id="ai-status-dot" style="background:#fb923c;box-shadow:0 0 8px #fb923c"></div>
        <span id="ai-status-text" style="font-size:13px;font-weight:600">📡 Offline AI Mode</span>
      </div>
      <div style="margin-bottom:13px">
        <div style="font-size:11px;color:var(--muted);margin-bottom:6px;letter-spacing:1px">GROQ API KLJUČ</div>
        <input class="input" id="groq-key-input" type="password" placeholder="gsk_...">
      </div>
      <div style="display:flex;gap:8px;margin-bottom:18px">
        <button class="btn btn-green btn-sm" onclick="saveGroqKey()" style="flex:1">💾 Sačuvaj</button>
        <button class="btn btn-sm" onclick="testGroq()" style="flex:1;background:rgba(56,189,248,0.2);border:1px solid rgba(56,189,248,0.4);color:var(--acc3)">🔌 Test</button>
        <button class="btn btn-danger btn-sm" onclick="resetGroq()" style="flex:1">🗑️ Reset</button>
      </div>
      <div class="slabel">AI MODEL</div>
      <select class="input" id="ai-model-sel" style="margin-bottom:16px">
        <option value="llama3-8b-8192">Llama 3 8B (brz)</option>
        <option value="llama3-70b-8192">Llama 3 70B (moćan)</option>
        <option value="mixtral-8x7b-32768">Mixtral 8x7B</option>
        <option value="gemma-7b-it">Gemma 7B</option>
      </select>
      <div class="slabel">AI PERSONALITY</div>
      <div class="grid2" style="margin-bottom:16px" id="personality-btns"></div>
      <div class="slabel">GLAS SEKRETARICE</div>
      <div style="display:flex;gap:8px;margin-bottom:16px" id="voice-btns"></div>
      <div class="slabel">WAKE WORD</div>
      <div style="display:flex;gap:9px;margin-bottom:9px">
        <input class="input" id="wake-word-input" value="Hej Budžet" style="flex:1">
        <button id="wake-word-toggle" onclick="toggleWakeWord()" style="padding:10px 16px;border-radius:13px;border:1px solid var(--border);background:var(--card);color:var(--muted);cursor:pointer;font-weight:700">OFF</button>
      </div>
      <div style="display:flex;gap:7px;flex-wrap:wrap">
        <button class="quick-cmd" onclick="document.getElementById('wake-word-input').value='Hej Budžet'">Hej Budžet</button>
        <button class="quick-cmd" onclick="document.getElementById('wake-word-input').value='Hej AI'">Hej AI</button>
        <button class="quick-cmd" onclick="document.getElementById('wake-word-input').value='Hej Sekretarice'">Hej Sekretarice</button>
      </div>
    </div>

    <!-- AVATAR TAB -->
    <div class="stab-content" id="stab-avatar">
      <div class="slabel">AVATAR SLIKA</div>

      <!-- Preview -->
      <div class="avatar-preview-wrap">
        <div class="avatar-preview" id="settings-avatar-preview">
          <span style="font-size:36px">🤖</span>
        </div>
      </div>

      <!-- 
        ANDROID NATIVE FIX:
        Input je VIDLJIV i pokriven labelom koja je prozirna.
        Ovo je jedini način koji radi u svim slučajevima.
      -->

      <!-- GALERIJA — vidljiv input ispod stajlovanog overlay-a -->
      <div style="position:relative;height:64px;border-radius:16px;margin-bottom:10px;overflow:hidden">
        <!-- Pozadina dugmeta -->
        <div style="position:absolute;inset:0;background:linear-gradient(135deg,rgba(124,108,255,0.85),rgba(167,139,250,0.6));border:1px solid rgba(124,108,255,0.5);border-radius:16px;display:flex;align-items:center;justify-content:center;gap:10px;pointer-events:none">
          <span style="font-size:24px">🖼️</span>
          <span style="font-size:14px;font-weight:700;color:#fff">Učitaj iz galerije</span>
        </div>
        <!-- Native input pokriva ceo div — jedini element koji prima touch -->
        <input type="file" accept="image/*"
          style="position:absolute;inset:0;width:100%;height:100%;opacity:0;cursor:pointer;font-size:100px"
          onchange="processAvatarFile(this.files[0])">
      </div>

      <!-- KAMERA -->
      <div style="position:relative;height:64px;border-radius:16px;margin-bottom:14px;overflow:hidden">
        <div style="position:absolute;inset:0;background:rgba(56,189,248,0.15);border:1px solid rgba(56,189,248,0.5);border-radius:16px;display:flex;align-items:center;justify-content:center;gap:10px;pointer-events:none">
          <span style="font-size:24px">📷</span>
          <span style="font-size:14px;font-weight:700;color:#38bdf8">Slikaj kamerom</span>
        </div>
        <input type="file" accept="image/*" capture="environment"
          style="position:absolute;inset:0;width:100%;height:100%;opacity:0;cursor:pointer;font-size:100px"
          onchange="processAvatarFile(this.files[0])">
      </div>

      <!-- Status -->
      <div id="upload-status" style="display:none;padding:11px 15px;border-radius:13px;font-size:13px;margin-bottom:12px;text-align:center;font-weight:600"></div>

      <!-- Ukloni pozadinu -->
      <div id="remove-bg-section" style="display:none;margin-bottom:12px">
        <label onclick="removeBackground()" style="display:block;padding:13px;border-radius:14px;background:rgba(56,189,248,0.12);border:1px solid rgba(56,189,248,0.4);color:var(--acc3);font-weight:700;font-size:13px;text-align:center;cursor:pointer">
          🪄 Ukloni pozadinu automatski
        </label>
        <div style="font-size:11px;color:var(--muted);margin-top:5px;text-align:center">Radi lokalno · Bez interneta</div>
      </div>

      <!-- Reset -->
      <label onclick="resetAvatar()" style="display:block;padding:12px;border-radius:14px;background:rgba(255,255,255,0.04);border:1px solid var(--border);color:var(--muted);font-weight:600;font-size:13px;text-align:center;cursor:pointer;margin-bottom:16px">
        🗑️ Ukloni sliku (vrati emoji)
      </label>

      <div class="slabel">DIMENZIJE</div>
      <div id="avatar-sliders"></div>
      <div class="slabel">AMBIENT SVETLO</div>
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:13px">
        <span style="font-size:13px">Boja ambient svetla</span>
        <input type="color" id="ambient-color-pick" value="#7c6cff" onchange="updateAmbientColor(this.value)">
      </div>
      <div id="ambient-sliders"></div>
      <div style="display:flex;justify-content:space-between;align-items:center;margin-top:4px">
        <span style="font-size:13px">Ambient puls</span>
        <button id="ambient-pulse-btn" onclick="toggleAmbientPulse()" style="padding:7px 18px;border-radius:11px;border:1px solid var(--green);background:rgba(34,211,238,0.15);color:var(--green);cursor:pointer;font-weight:700">ON</button>
      </div>
    </div>

    <!-- PROFILE TAB -->
    <div class="stab-content" id="stab-profile">
      <div class="slabel">KAKO TE AI OSLOVLJAVA?</div>
      <input class="input" id="username-input" placeholder="Šefe, Boss, Legendo..." style="margin-bottom:10px">
      <div style="display:flex;gap:7px;flex-wrap:wrap;margin-bottom:16px">
        <button class="quick-cmd" onclick="document.getElementById('username-input').value='Šefe'">Šefe</button>
        <button class="quick-cmd" onclick="document.getElementById('username-input').value='Boss'">Boss</button>
        <button class="quick-cmd" onclick="document.getElementById('username-input').value='Legendo'">Legendo</button>
        <button class="quick-cmd" onclick="document.getElementById('username-input').value='Marko'">Marko</button>
        <button class="quick-cmd" onclick="document.getElementById('username-input').value='Saša'">Saša</button>
      </div>
      <button class="btn btn-green btn-full" onclick="saveUsername()">💾 Sačuvaj ime</button>
      <div class="card" style="padding:17px;margin-top:20px">
        <div style="font-size:14px;font-weight:800;font-family:'Syne',sans-serif;margin-bottom:9px">💎 Moj Budžet v2.0</div>
        <div style="font-size:12px;color:var(--muted);line-height:1.7">Ultra premium fintech aplikacija.<br>🚀 Futuristički UI · 🤖 Groq AI · 📊 Live statistika<br>💾 Radi offline · 📱 Optimizovano za Android</div>
      </div>
    </div>
  </div>
</div>

<!-- AI PANEL -->
<div class="overlay" id="ai-panel">
  <div class="sheet" style="max-height:88vh;height:88vh;display:flex;flex-direction:column">
    <div class="sheet-header" style="flex-shrink:0">
      <div style="display:flex;align-items:center;gap:11px">
        <span style="font-size:23px">🤖</span>
        <div>
          <div style="font-size:15px;font-weight:800;font-family:'Syne',sans-serif">AI Asistent</div>
          <div style="display:flex;align-items:center;gap:6px;font-size:11px">
            <div id="ai-chat-dot" style="width:7px;height:7px;border-radius:50%;background:#fb923c;box-shadow:0 0 6px #fb923c;flex-shrink:0"></div>
            <span style="color:var(--muted)" id="ai-chat-status">Offline AI</span>
          </div>
        </div>
      </div>
      <button class="close-btn" onclick="closeOverlay('ai-panel')">✕</button>
    </div>
    <div class="chat-area" id="chat-area"></div>
    <div class="quick-cmds" style="flex-shrink:0">
      <button class="quick-cmd" onclick="sendQuickCmd('Koliko imam novca?')">Koliko imam?</button>
      <button class="quick-cmd" onclick="sendQuickCmd('Koliko sam potrošio danas?')">Potrošnja danas</button>
      <button class="quick-cmd" onclick="openAddTxFromAI('expense')">Dodaj trošak</button>
      <button class="quick-cmd" onclick="sendQuickCmd('Prikaži mi statistiku rashoda')">Statistika</button>
      <button class="quick-cmd" onclick="sendQuickCmd('Daj mi savete za štednju')">Saveti</button>
    </div>
    <div class="chat-input-row" style="flex-shrink:0">
      <button class="mic-btn" id="mic-btn" onclick="startListening()">🎤</button>
      <input class="chat-input" id="chat-input" placeholder="Pitaj me nešto..." onkeydown="if(event.key==='Enter')sendMessage()">
      <button class="send-btn" onclick="sendMessage()">▶</button>
    </div>
  </div>
</div>

<!-- ADD GOAL MODAL -->
<div class="overlay" id="add-goal-overlay" style="align-items:center;padding:20px">
  <div class="sheet" style="width:100%;max-width:360px;border-radius:22px;animation:slideUp 0.3s ease">
    <div class="sheet-header">
      <span class="sheet-title">🎯 Novi Cilj</span>
      <button class="close-btn" onclick="closeOverlay('add-goal-overlay')">✕</button>
    </div>
    <div style="padding:16px 20px 28px">
      <input class="input" id="goal-name" placeholder="Naziv cilja..." style="margin-bottom:10px">
      <input class="input" id="goal-icon" placeholder="Ikonica (emoji)..." value="🎯" style="margin-bottom:10px">
      <input class="input" id="goal-target" type="number" placeholder="Ciljani iznos (RSD)..." style="margin-bottom:10px">
      <input class="input" id="goal-saved" type="number" placeholder="Već uštedeo (RSD)..." value="0" style="margin-bottom:10px">
      <div style="display:flex;align-items:center;gap:12px;margin-bottom:18px">
        <span style="font-size:13px">Boja:</span>
        <input type="color" id="goal-color" value="#7c6cff">
      </div>
      <div style="display:flex;gap:9px">
        <button class="btn btn-green" onclick="saveGoal()" style="flex:1">✓ Dodaj</button>
        <button class="btn btn-danger" onclick="closeOverlay('add-goal-overlay')" style="flex:1">Otkaži</button>
      </div>
    </div>
  </div>
</div>

<!-- ADD BUDGET MODAL -->
<div class="overlay" id="add-budget-overlay" style="align-items:center;padding:20px">
  <div class="sheet" style="width:100%;max-width:360px;border-radius:22px;animation:slideUp 0.3s ease">
    <div class="sheet-header">
      <span class="sheet-title">💰 Novi Budžet</span>
      <button class="close-btn" onclick="closeOverlay('add-budget-overlay')">✕</button>
    </div>
    <div style="padding:16px 20px 28px">
      <select class="input" id="budget-cat" style="margin-bottom:10px"></select>
      <input class="input" id="budget-limit" type="number" placeholder="Limit (RSD)..." style="margin-bottom:18px">
      <div style="display:flex;gap:9px">
        <button class="btn btn-green" onclick="saveBudget()" style="flex:1">✓ Dodaj</button>
        <button class="btn btn-danger" onclick="closeOverlay('add-budget-overlay')" style="flex:1">Otkaži</button>
      </div>
    </div>
  </div>
</div>

<script>
// ===================================================================
// DATA
// ===================================================================
const CATS = [
  {id:'food',label:'Hrana',icon:'🍔',color:'#f472b6'},
  {id:'fuel',label:'Gorivo',icon:'⛽',color:'#fb923c'},
  {id:'bills',label:'Računi',icon:'📄',color:'#60a5fa'},
  {id:'fun',label:'Zabava',icon:'🎮',color:'#a78bfa'},
  {id:'shop',label:'Kupovina',icon:'🛍️',color:'#34d399'},
  {id:'health',label:'Zdravlje',icon:'❤️',color:'#f87171'},
  {id:'travel',label:'Putovanje',icon:'✈️',color:'#38bdf8'},
  {id:'salary',label:'Plata',icon:'💼',color:'#22d3ee'},
  {id:'other',label:'Ostalo',icon:'💡',color:'#94a3b8'},
];

const DEFAULT_TXS = [
  {id:1,type:'income',amount:120000,category:'salary',desc:'Plata - maj 2026',date:'2026-05-01',time:'08:00'},
  {id:2,type:'expense',amount:2500,category:'food',desc:'Maxi prodavnica',date:'2026-05-20',time:'14:22'},
  {id:3,type:'expense',amount:3500,category:'fuel',desc:'Gorivo NIS',date:'2026-05-19',time:'18:30'},
  {id:4,type:'expense',amount:1890,category:'shop',desc:'Online kupovina',date:'2026-05-18',time:'11:30'},
  {id:5,type:'expense',amount:620,category:'health',desc:'Apoteka Benu',date:'2026-05-18',time:'16:40'},
  {id:6,type:'expense',amount:1750,category:'fun',desc:'Restoran Toro',date:'2026-05-17',time:'20:11'},
  {id:7,type:'expense',amount:350,category:'bills',desc:'Kafić Time',date:'2026-05-20',time:'12:19'},
  {id:8,type:'income',amount:25000,category:'other',desc:'Bonus',date:'2026-05-15',time:'09:00'},
];

let transactions = load('mb_txs', DEFAULT_TXS);
// Auto-reset ako postoje stari 2024 podaci
if(transactions.some(t=>t.date&&t.date.startsWith('2024'))){
  transactions = DEFAULT_TXS;
  save('mb_txs', DEFAULT_TXS);
}

let budgets = load('mb_budgets', [
  {id:1,category:'food',limit:20000,spent:2500},
  {id:2,category:'fuel',limit:10000,spent:3500},
  {id:3,category:'bills',limit:8000,spent:350},
]);
let goals = load('mb_goals', [
  {id:1,name:'Telefon',icon:'📱',target:80000,saved:32000,color:'#7c6cff'},
  {id:2,name:'Putovanje',icon:'✈️',target:150000,saved:45000,color:'#38bdf8'},
  {id:3,name:'Auto',icon:'🚗',target:800000,saved:120000,color:'#22d3ee'},
]);
let reminders = load('mb_reminders', [
  {id:1,name:'Struja',amount:3500,dueDate:'2026-06-01',done:false},
  {id:2,name:'Internet',amount:1200,dueDate:'2026-06-05',done:false},
]);

let groqKey = load('mb_groq_key', '');
let userName = load('mb_username', 'Šefe');
let aiPersonality = load('mb_personality', 'futuristic');
let voiceGender = load('mb_voice', 'female');
let aiModel = load('mb_model', 'llama3-8b-8192');
let wakeWordEnabled = false;
let wakeWord = 'Hej Budžet';
let avatarImg = load('mb_avatar_img', null);
let aiStatus = 'offline';
let addType = 'expense';
let addCat = 'food';
let txFilter = 'all';
let chatMessages = [];
let isSpeaking = false;
let isListening = false;
let avatarMini = false;
let ambientPulse = true;
let themeMode = load('mb_theme_mode', 'dark');

const CSS_VARS = load('mb_css_vars', {
  '--acc1':'#7c6cff','--acc2':'#a78bfa','--acc3':'#38bdf8',
  '--green':'#22d3ee','--pink':'#f472b6','--glow':'#7c6cff',
  '--sh':'8px','--sb':'24px','--glass':'18px',
  '--avatar-glow-size':'60px',
  '--float-speed':'3s','--glow-pulse':'2s','--anim-speed':'1',
  '--avatar-opacity':'1',
  '--ambient-color':'#7c6cff',
  '--ambient-intensity':'0.45',
  '--fi':'8px',
});

// ===================================================================
// STORAGE
// ===================================================================
function load(k,def){try{const v=localStorage.getItem(k);return v?JSON.parse(v):def;}catch{return def;}}
function save(k,v){try{localStorage.setItem(k,JSON.stringify(v));}catch{}}

// ===================================================================
// CSS VARS ENGINE
// ===================================================================
function applyCSSVars(){
  const r = document.documentElement;
  Object.entries(CSS_VARS).forEach(([k,v])=>r.style.setProperty(k,v));
}
function setCSSVar(k,v){CSS_VARS[k]=v;document.documentElement.style.setProperty(k,v);save('mb_css_vars',CSS_VARS);}

// ===================================================================
// FMT
// ===================================================================
function fmt(n){return Number(n).toLocaleString('sr-RS')+' RSD';}
function fmtS(n){return Number(n).toLocaleString('sr-RS');}

// ===================================================================
// NOTIFY
// ===================================================================
function notify(msg,type='info'){
  const el=document.getElementById('notif');
  el.textContent=msg;
  const colors={success:'rgba(34,211,238,0.85)',error:'rgba(239,68,68,0.85)',info:'rgba(124,108,255,0.85)'};
  el.style.background=colors[type]||colors.info;
  el.style.display='block';
  clearTimeout(el._t);
  el._t=setTimeout(()=>el.style.display='none',3000);
}

// ===================================================================
// PAGES
// ===================================================================
function showPage(name){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.querySelectorAll('.nav-btn').forEach(b=>b.classList.remove('active'));
  document.getElementById('page-'+name).classList.add('active');
  const nb=document.getElementById('nav-'+name);
  if(nb)nb.classList.add('active');
  if(name==='home')renderHome();
  if(name==='transactions')renderTransactions();
  if(name==='stats')renderStats();
  if(name==='profile')renderProfile();
}

// ===================================================================
// OVERLAYS
// ===================================================================
function openOverlay(id){document.getElementById(id).classList.add('show');}
function closeOverlay(id){document.getElementById(id).classList.remove('show');}

// ===================================================================
// CALCS
// ===================================================================
function calcTotals(){
  const income=transactions.filter(t=>t.type==='income').reduce((s,t)=>s+t.amount,0);
  const expense=transactions.filter(t=>t.type==='expense').reduce((s,t)=>s+t.amount,0);
  return {income,expense,balance:income-expense};
}

// ===================================================================
// HOME
// ===================================================================
function renderHome(){
  const {income,expense,balance}=calcTotals();
  const now=new Date();
  const months=['Januar','Februar','Mart','April','Maj','Jun','Jul','Avgust','Septembar','Oktobar','Novembar','Decembar'];
  const lbl=document.getElementById('home-chart-label');
  if(lbl)lbl.textContent=months[now.getMonth()]+' '+now.getFullYear();
  document.getElementById('home-username').textContent=userName;
  document.getElementById('home-balance').textContent=fmt(balance);
  const incEl=document.getElementById('home-income');
  const expEl=document.getElementById('home-expense');
  if(incEl){incEl.textContent=fmtS(income)+' RSD';incEl.style.fontSize=income>=1000000?'12px':income>=100000?'13px':'15px';}
  if(expEl){expEl.textContent=fmtS(expense)+' RSD';expEl.style.fontSize=expense>=1000000?'12px':expense>=100000?'13px':'15px';}
  document.getElementById('home-trend').innerHTML=balance>=0?'<span>↗</span><span>Pozitivno stanje</span>':'<span>↘</span><span>Negativno stanje</span>';
  document.getElementById('home-trend').style.color=balance>=0?'var(--green)':'var(--pink)';
  document.getElementById('home-ai-insight').innerHTML=getAIInsight(income,expense,balance);
  renderHomeChart(income,expense);
  renderHomeCats();
  renderRecentTxs();
}

function getAIInsight(income,expense,balance){
  const pct=income>0?Math.round((expense/income)*100):0;
  if(pct>80)return `${userName}, rashodi su ${pct}% od prihoda! ⚠️ Preporučujem smanjenje troškova zabave.`;
  if(pct>50)return `${userName}, rashodi su ${pct}% od prihoda. Solidno, ali ima prostora za poboljšanje 📊`;
  return `${userName}, super štediš! Rashodi su samo ${pct}% od prihoda. Uštedeo si ${fmt(balance)} 🎉`;
}

function renderHomeChart(income,expense){
  const svg=document.getElementById('home-chart');
  const w=300,h=55;
  const incPts=[0.3,0.45,0.6,0.75,0.85,0.9,1.0].map(f=>Math.round(income*f*0.9));
  const expPts=[0.2,0.35,0.5,0.6,0.7,0.8,1.0].map(f=>Math.round(expense*f*0.9));
  function polyline(data,color){
    const max=Math.max(...data,1);
    const pts=data.map((v,i)=>`${(i/(data.length-1))*w},${h-(v/max)*(h-6)}`).join(' ');
    return `<defs><linearGradient id="g${color.replace('#','')}" x1="0" x2="0" y1="0" y2="1"><stop offset="0%" stop-color="${color}" stop-opacity="0.4"/><stop offset="100%" stop-color="${color}" stop-opacity="0.02"/></linearGradient></defs>
    <polyline points="${pts}" fill="none" stroke="${color}" stroke-width="2.5" stroke-linejoin="round" stroke-linecap="round"/>`;
  }
  svg.innerHTML=polyline(incPts,'#22d3ee')+polyline(expPts,'#f472b6');
}

function renderHomeCats(){
  const byCat=CATS.map(c=>({...c,val:transactions.filter(t=>t.type==='expense'&&t.category===c.id).reduce((s,t)=>s+t.amount,0)})).filter(c=>c.val>0).sort((a,b)=>b.val-a.val);
  const el=document.getElementById('home-cats');
  el.innerHTML=byCat.slice(0,5).map(c=>`
    <div style="min-width:80px;padding:13px 10px;background:${c.color}11;border:1px solid ${c.color}33;border-radius:17px;text-align:center;flex-shrink:0;backdrop-filter:blur(8px)">
      <div style="font-size:22px">${c.icon}</div>
      <div style="font-size:10px;color:var(--muted);margin-top:4px">${c.label}</div>
      <div style="font-size:12px;font-weight:800;color:${c.color};margin-top:2px">${fmtS(c.val)}</div>
    </div>`).join('');
}

function renderRecentTxs(){
  const el=document.getElementById('home-recent-txs');
  el.innerHTML=transactions.slice(0,5).map(tx=>txHTML(tx)).join('');
}

function txHTML(tx){
  const cat=CATS.find(c=>c.id===tx.category)||CATS[CATS.length-1];
  return `<div class="tx-item">
    <div class="tx-icon" style="background:${cat.color}18;border:1px solid ${cat.color}33">${cat.icon}</div>
    <div class="tx-info">
      <div class="tx-name">${tx.desc}</div>
      <div class="tx-meta">${cat.label} · ${tx.date} ${tx.time}</div>
    </div>
    <div style="text-align:right">
      <div class="tx-amount" style="color:${tx.type==='income'?'var(--green)':'var(--pink)'}">${tx.type==='income'?'+':'-'}${fmt(tx.amount)}</div>
      <button onclick="deleteTx(${tx.id})" style="background:none;border:none;color:rgba(239,68,68,0.4);font-size:11px;cursor:pointer;margin-top:3px">✕ obriši</button>
    </div>
  </div>`;
}

// ===================================================================
// TRANSACTIONS
// ===================================================================
function setTxFilter(f,btn){
  txFilter=f;
  document.querySelectorAll('.ftab').forEach(b=>b.classList.remove('active'));
  btn.classList.add('active');
  renderTransactions();
}

function renderTransactions(){
  const search=(document.getElementById('tx-search')?.value||'').toLowerCase();
  const filtered=transactions.filter(t=>{
    if(txFilter==='income'&&t.type!=='income')return false;
    if(txFilter==='expense'&&t.type!=='expense')return false;
    if(search&&!t.desc.toLowerCase().includes(search))return false;
    return true;
  });
  const grouped=filtered.reduce((acc,tx)=>{
    if(!acc[tx.date])acc[tx.date]=[];
    acc[tx.date].push(tx);return acc;
  },{});
  const sorted=Object.keys(grouped).sort((a,b)=>new Date(b)-new Date(a));
  const el=document.getElementById('tx-list');
  if(filtered.length===0){el.innerHTML='<div style="text-align:center;color:var(--muted);margin-top:50px;font-size:14px">Nema transakcija 🤷</div>';return;}
  el.innerHTML=sorted.map(d=>`<div class="date-label">${d}</div>${grouped[d].map(tx=>txHTML(tx)).join('')}`).join('');
}

function deleteTx(id){
  transactions=transactions.filter(t=>t.id!==id);
  save('mb_txs',transactions);
  renderTransactions();
  renderHome();
  notify('Transakcija obrisana','info');
}

// ===================================================================
// ADD TRANSACTION
// ===================================================================
function openAddTx(type){
  addType=type||'expense';
  addCat='food';
  document.getElementById('add-amount').value='';
  document.getElementById('add-desc').value='';
  document.getElementById('add-date').value=new Date().toISOString().slice(0,10);
  document.getElementById('add-time').value='12:00';
  setAddType(addType);
  buildCatGrid();
  openOverlay('add-tx-overlay');
}

function openAddTxFromAI(type){
  closeOverlay('ai-panel');
  setTimeout(()=>openAddTx(type),200);
}

function setAddType(t){
  addType=t;
  const expBtn=document.getElementById('add-type-exp');
  const incBtn=document.getElementById('add-type-inc');
  document.getElementById('add-tx-title').textContent=t==='expense'?'➕ Novi Rashod':'➕ Novi Prihod';
  if(t==='expense'){
    expBtn.className='btn btn-pink btn-sm';expBtn.style.flex='1';expBtn.style.padding='11px';
    incBtn.className='btn btn-ghost btn-sm';incBtn.style.flex='1';incBtn.style.padding='11px';
    document.getElementById('add-save-btn').className='btn btn-full btn-pink';
  } else {
    incBtn.className='btn btn-green btn-sm';incBtn.style.flex='1';incBtn.style.padding='11px';
    expBtn.className='btn btn-ghost btn-sm';expBtn.style.flex='1';expBtn.style.padding='11px';
    document.getElementById('add-save-btn').className='btn btn-full btn-green';
  }
}

function buildCatGrid(){
  const grid=document.getElementById('add-cat-grid');
  grid.innerHTML=CATS.map(c=>`
    <button class="cat-btn${addCat===c.id?' selected':''}" onclick="selectCat('${c.id}')" style="${addCat===c.id?'border-color:'+c.color+';background:'+c.color+'18;color:'+c.color:''}">
      <div class="cat-emoji">${c.icon}</div>
      <div class="cat-name">${c.label}</div>
    </button>`).join('');
}

function selectCat(id){
  addCat=id;
  buildCatGrid();
}

function saveTransaction(){
  const amount=parseFloat(document.getElementById('add-amount').value);
  if(!amount||isNaN(amount)){notify('Unesite validan iznos','error');return;}
  const tx={
    id:Date.now(),type:addType,amount,category:addCat,
    desc:document.getElementById('add-desc').value||(CATS.find(c=>c.id===addCat)?.label||'Transakcija'),
    date:document.getElementById('add-date').value,
    time:document.getElementById('add-time').value,
  };
  transactions.unshift(tx);
  if(tx.type==='expense'){
    budgets=budgets.map(b=>b.category===tx.category?{...b,spent:b.spent+tx.amount}:b);
    save('mb_budgets',budgets);
  }
  save('mb_txs',transactions);
  closeOverlay('add-tx-overlay');
  renderHome();
  notify(`✅ ${addType==='expense'?'Rashod':'Prihod'} sačuvan!`,'success');
}

// ===================================================================
// STATS
// ===================================================================
function renderStats(){
  const {income,expense,balance}=calcTotals();
  const score=Math.min(100,Math.round((balance/Math.max(income,1))*100));
  const sc=document.getElementById('stats-cards');
  sc.innerHTML=[
    {label:'Prihodi',val:fmt(income),color:'var(--green)',icon:'📈'},
    {label:'Rashodi',val:fmt(expense),color:'var(--pink)',icon:'📉'},
    {label:'Saldo',val:fmt(balance),color:'var(--acc2)',icon:'💰'},
    {label:'Transakcija',val:transactions.length,color:'var(--acc3)',icon:'📋'},
  ].map(s=>`<div class="card" style="padding:16px"><div style="font-size:20px;margin-bottom:7px">${s.icon}</div><div style="font-size:13px;font-weight:800;color:${s.color};margin-bottom:3px">${s.val}</div><div style="font-size:11px;color:var(--muted)">${s.label}</div></div>`).join('');
  renderDonut();
  renderBarChart();
  renderBudgets();
  renderGoals();
}

function renderDonut(){
  const byCat=CATS.map(c=>({...c,val:transactions.filter(t=>t.type==='expense'&&t.category===c.id).reduce((s,t)=>s+t.amount,0)})).filter(c=>c.val>0);
  const total=byCat.reduce((s,c)=>s+c.val,0);
  const svg=document.getElementById('donut-svg');
  const leg=document.getElementById('donut-legend');
  if(!total){svg.innerHTML='<text x="57" y="63" text-anchor="middle" fill="#6b7a99" font-size="11">Nema podataka</text>';leg.innerHTML='';return;}
  const cx=57,cy=57,r=42,inner=26;
  let angle=-90;
  let paths='';
  byCat.slice(0,6).forEach(c=>{
    const sweep=(c.val/total)*360;
    const sa=angle,ea=angle+sweep-1;
    angle+=sweep;
    const rad=a=>({x:cx+r*Math.cos(a*Math.PI/180),y:cy+r*Math.sin(a*Math.PI/180)});
    const ri=a=>({x:cx+inner*Math.cos(a*Math.PI/180),y:cy+inner*Math.sin(a*Math.PI/180)});
    const s=rad(sa),e=rad(ea),is=ri(sa);
    const lg=sweep>180?1:0;
    paths+=`<path d="M${s.x} ${s.y} A${r} ${r} 0 ${lg} 1 ${e.x} ${e.y} A${inner} ${inner} 0 ${lg} 0 ${is.x} ${is.y} Z" fill="${c.color}" opacity="0.88" style="filter:drop-shadow(0 0 4px ${c.color}66)"/>`;
  });
  paths+=`<circle cx="${cx}" cy="${cy}" r="${inner-2}" fill="var(--card)" opacity="0.96"/>`;
  svg.innerHTML=paths;
  leg.innerHTML=byCat.slice(0,5).map(c=>`
    <div class="legend-item">
      <span style="display:flex;align-items:center;gap:6px;font-size:12px;color:var(--muted)">
        <span class="legend-dot" style="background:${c.color}"></span>
        ${c.icon} ${c.label}
      </span>
      <span style="font-size:12px;font-weight:700;color:${c.color}">${((c.val/total)*100).toFixed(0)}%</span>
    </div>`).join('');
}

function renderBarChart(){
  const {income:mi,expense:me}=calcTotals();
  const months=[{label:'Mar',income:85000,expense:60000},{label:'Apr',income:95000,expense:67000},{label:'Maj',income:mi,expense:me}];
  const max=Math.max(...months.flatMap(m=>[m.income,m.expense]),1);
  const H=80;
  const el=document.getElementById('bar-chart');
  el.innerHTML=months.map(m=>`
    <div style="flex:1;display:flex;flex-direction:column;align-items:center;gap:3px">
      <div style="width:100%;display:flex;gap:3px;align-items:flex-end">
        <div style="flex:1;height:${Math.max(2,(m.income/max)*(H-18))}px;background:linear-gradient(0deg,rgba(34,211,238,0.7),rgba(34,211,238,0.25));border-radius:5px 5px 0 0;box-shadow:0 0 8px rgba(34,211,238,0.3);min-height:2px"></div>
        <div style="flex:1;height:${Math.max(2,(m.expense/max)*(H-18))}px;background:linear-gradient(0deg,rgba(244,114,182,0.7),rgba(244,114,182,0.25));border-radius:5px 5px 0 0;box-shadow:0 0 8px rgba(244,114,182,0.3);min-height:2px"></div>
      </div>
      <span style="font-size:9px;color:var(--muted)">${m.label}</span>
    </div>`).join('');
}

function renderBudgets(){
  const el=document.getElementById('budgets-list');
  el.innerHTML=budgets.map(b=>{
    const cat=CATS.find(c=>c.id===b.category)||CATS[0];
    const pct=Math.min((b.spent/b.limit)*100,100);
    const over=b.spent>b.limit;
    return `<div class="card" style="padding:15px;margin-bottom:10px">
      <div style="display:flex;justify-content:space-between;margin-bottom:9px">
        <span style="font-size:13px;font-weight:600">${cat.icon} ${cat.label}</span>
        <span style="font-size:12px;color:${over?'var(--pink)':'var(--muted)'}">${fmt(b.spent)} / ${fmt(b.limit)}</span>
      </div>
      <div class="progress-wrap">
        <div class="progress-bar" style="width:${pct}%;background:${over?'linear-gradient(90deg,#ef4444,#fca5a5)':'linear-gradient(90deg,'+cat.color+','+cat.color+'88)'};box-shadow:0 0 10px ${cat.color}55"></div>
      </div>
      ${over?'<div style="font-size:11px;color:var(--pink);margin-top:5px">⚠️ Limit prekoračen!</div>':''}
    </div>`;
  }).join('');
}

function renderGoals(){
  const el=document.getElementById('goals-list');
  el.innerHTML=goals.map(g=>{
    const pct=Math.min((g.saved/g.target)*100,100);
    const r=35,circ=2*Math.PI*r;
    return `<div class="card goal-card" style="margin-bottom:11px">
      <div class="goal-circle">
        <svg width="82" height="82">
          <circle cx="41" cy="41" r="${r}" fill="none" stroke="${g.color}22" stroke-width="7"/>
          <circle cx="41" cy="41" r="${r}" fill="none" stroke="${g.color}" stroke-width="7"
            stroke-dasharray="${circ}" stroke-dashoffset="${circ*(1-pct/100)}"
            stroke-linecap="round" transform="rotate(-90 41 41)"
            style="filter:drop-shadow(0 0 5px ${g.color});transition:stroke-dashoffset 1s ease"/>
        </svg>
        <div class="goal-inner">
          <div style="font-size:17px">${g.icon}</div>
          <div style="font-size:10px;color:${g.color};font-weight:700">${pct.toFixed(0)}%</div>
        </div>
      </div>
      <div style="flex:1">
        <div style="font-size:14px;font-weight:700;margin-bottom:4px">${g.name}</div>
        <div style="font-size:12px;color:var(--muted)">${fmt(g.saved)} / ${fmt(g.target)}</div>
        <div style="font-size:11px;color:${g.color};margin-top:5px">Još ${fmt(g.target-g.saved)} do cilja</div>
      </div>
    </div>`;
  }).join('');
}

function setStatsFilter(f,btn){
  document.querySelectorAll('#page-stats .ftab').forEach(b=>b.classList.remove('active'));
  btn.classList.add('active');
}

// ===================================================================
// PROFILE
// ===================================================================
function renderProfile(){
  const {income,expense,balance}=calcTotals();
  const score=Math.min(100,Math.max(0,Math.round((balance/Math.max(income,1))*100)));
  document.getElementById('prof-name').textContent=userName;
  document.getElementById('score-val').textContent=score+'/100';
  document.getElementById('score-fill').style.width=score+'%';
  document.getElementById('score-msg').textContent=score>=70?'✨ Odlično finansijsko upravljanje!':score>=40?'📊 Dobro, ima prostora za napredak':'⚠️ Pazi na troškove';
  const ps=document.getElementById('profile-stats');
  ps.innerHTML=[
    {label:'Fin. skor',val:score+'/100',color:'var(--acc2)',icon:'📊'},
    {label:'Transakcija',val:transactions.length,color:'var(--acc3)',icon:'💳'},
    {label:'Ukupni prihodi',val:fmt(income),color:'var(--green)',icon:'📈'},
    {label:'Ukupni rashodi',val:fmt(expense),color:'var(--pink)',icon:'📉'},
  ].map(s=>`<div class="card" style="padding:16px"><div style="font-size:20px;margin-bottom:7px">${s.icon}</div><div style="font-size:13px;font-weight:800;color:${s.color};margin-bottom:3px">${s.val}</div><div style="font-size:11px;color:var(--muted)">${s.label}</div></div>`).join('');
  renderReminders();
}

function renderReminders(){
  const el=document.getElementById('reminders-list');
  el.innerHTML=reminders.map(r=>`
    <div class="reminder-item" style="border-color:${r.done?'var(--border)':'rgba(244,114,182,0.3)'}">
      <div style="width:38px;height:38px;border-radius:12px;background:rgba(244,114,182,0.1);display:flex;align-items:center;justify-content:center;font-size:18px;flex-shrink:0">📄</div>
      <div style="flex:1">
        <div style="font-size:13px;font-weight:600;text-decoration:${r.done?'line-through':''};color:${r.done?'var(--muted)':'var(--text)'}">${r.name}</div>
        <div style="font-size:11px;color:var(--muted)">Rok: ${r.dueDate} · ${fmt(r.amount)}</div>
      </div>
      <button class="reminder-check" onclick="toggleReminder(${r.id})" style="background:${r.done?'rgba(34,211,238,0.15)':'var(--card)'};border:1px solid ${r.done?'var(--green)':'var(--border)'};color:${r.done?'var(--green)':'var(--muted)'}">
        ${r.done?'✓':'○'}
      </button>
    </div>`).join('');
}

function toggleReminder(id){
  reminders=reminders.map(r=>r.id===id?{...r,done:!r.done}:r);
  save('mb_reminders',reminders);
  renderReminders();
}

// ===================================================================
// BUDGET & GOAL MODALS
// ===================================================================
function openAddGoal(){openOverlay('add-goal-overlay');}
function openAddBudget(){
  const sel=document.getElementById('budget-cat');
  sel.innerHTML=CATS.map(c=>`<option value="${c.id}">${c.icon} ${c.label}</option>`).join('');
  openOverlay('add-budget-overlay');
}

function saveGoal(){
  const name=document.getElementById('goal-name').value;
  const target=parseFloat(document.getElementById('goal-target').value);
  if(!name||!target){notify('Popunite sva polja','error');return;}
  goals.push({id:Date.now(),name,icon:document.getElementById('goal-icon').value||'🎯',target,saved:parseFloat(document.getElementById('goal-saved').value)||0,color:document.getElementById('goal-color').value});
  save('mb_goals',goals);
  closeOverlay('add-goal-overlay');
  renderGoals();
  notify('✅ Cilj dodat!','success');
}

function saveBudget(){
  const limit=parseFloat(document.getElementById('budget-limit').value);
  if(!limit){notify('Unesite limit','error');return;}
  const cat=document.getElementById('budget-cat').value;
  const spent=transactions.filter(t=>t.type==='expense'&&t.category===cat).reduce((s,t)=>s+t.amount,0);
  budgets.push({id:Date.now(),category:cat,limit,spent});
  save('mb_budgets',budgets);
  closeOverlay('add-budget-overlay');
  renderBudgets();
  notify('✅ Budžet dodat!','success');
}

// ===================================================================
// SETTINGS
// ===================================================================
function openSettings(){
  document.getElementById('username-input').value=userName;
  document.getElementById('groq-key-input').value=groqKey;
  document.getElementById('ai-model-sel').value=aiModel;
  buildPersonalityBtns();
  buildVoiceBtns();
  buildColorPickers();
  buildNeuSliders();
  buildGlassSliders();
  buildAnimSliders();
  buildAvatarSliders();
  buildAmbientSliders();
  updateAvatarPreviewInSettings();
  setThemeModeUI();
  openOverlay('settings-overlay');
}

function switchStab(name,btn){
  document.querySelectorAll('.stab').forEach(b=>b.classList.remove('active'));
  document.querySelectorAll('.stab-content').forEach(c=>c.classList.remove('active'));
  btn.classList.add('active');
  document.getElementById('stab-'+name).classList.add('active');
}

function setThemeMode(m){
  themeMode=m;
  save('mb_theme_mode',m);
  if(m==='dark')document.body.classList.remove('light');
  else if(m==='light')document.body.classList.add('light');
  else{const dark=window.matchMedia('(prefers-color-scheme: dark)').matches;document.body.classList.toggle('light',!dark);}
  setThemeModeUI();
}

function setThemeModeUI(){
  ['dark','light','auto'].forEach(m=>{
    const btn=document.getElementById('tm-'+m);
    if(!btn)return;
    if(m===themeMode){btn.className='btn btn-primary btn-sm';btn.style.flex='1';btn.style.padding='10px';}
    else{btn.className='btn btn-ghost btn-sm';btn.style.flex='1';btn.style.padding='10px';}
  });
}

function buildColorPickers(){
  const items=[
    {key:'--acc1',label:'Primarna boja'},
    {key:'--acc2',label:'Sekundarna boja'},
    {key:'--acc3',label:'Tercijarna boja'},
    {key:'--green',label:'Prihod boja'},
    {key:'--pink',label:'Rashod boja'},
    {key:'--glow',label:'Glow boja'},
  ];
  document.getElementById('color-pickers').innerHTML=items.map(i=>`
    <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:12px">
      <span style="font-size:13px">${i.label}</span>
      <input type="color" value="${CSS_VARS[i.key]||'#7c6cff'}" onchange="setCSSVar('${i.key}',this.value)">
    </div>`).join('');
}

function buildSliders(containerId,items){
  document.getElementById(containerId).innerHTML=items.map(i=>`
    <div style="margin-bottom:15px">
      <div style="display:flex;justify-content:space-between;margin-bottom:5px">
        <span style="font-size:12px;color:var(--muted)">${i.label}</span>
        <span style="font-size:12px;color:var(--acc2)" id="sv-${i.key.replace(/[^a-z0-9]/gi,'')}">${CSS_VARS[i.key]?.replace(i.unit||'','')||i.def}</span>
      </div>
      <input type="range" min="${i.min}" max="${i.max}" step="${i.step||1}" value="${parseFloat(CSS_VARS[i.key])||i.def}"
        oninput="setCSSVar('${i.key}',this.value+(${JSON.stringify(i.unit||'')}));document.getElementById('sv-${i.key.replace(/[^a-z0-9]/gi,'')}').textContent=this.value">
    </div>`).join('');
}

function buildNeuSliders(){
  buildSliders('neu-sliders',[
    {key:'--sh',label:'Visina senke',min:0,max:20,def:8,unit:'px'},
    {key:'--sb',label:'Blur senke',min:0,max:60,def:24,unit:'px'},
  ]);
}
function buildGlassSliders(){
  buildSliders('glass-sliders',[
    {key:'--glass',label:'Glass blur',min:0,max:40,def:18,unit:'px'},
  ]);
}
function buildAnimSliders(){
  buildSliders('anim-sliders',[
    {key:'--fi',label:'Float intenzitet',min:0,max:25,def:8,unit:'px'},
  ]);
}
function buildAvatarSliders(){
  document.getElementById('avatar-sliders').innerHTML=[
    {key:'--avatar-w',label:'Širina avatara',min:30,max:180,def:82,unit:'px'},
    {key:'--avatar-h',label:'Visina avatara',min:30,max:180,def:82,unit:'px'},
    {key:'--avatar-opacity',label:'Providnost',min:10,max:100,def:100,unit:''},
    {key:'--avatar-glow-size',label:'Glow veličina',min:20,max:200,def:60,unit:'px'},
  ].map(i=>`
    <div style="margin-bottom:15px">
      <div style="display:flex;justify-content:space-between;margin-bottom:5px">
        <span style="font-size:12px;color:var(--muted)">${i.label}</span>
        <span style="font-size:12px;color:var(--acc2)" id="avs-${i.key.replace(/[^a-z]/gi,'')}">${parseFloat(CSS_VARS[i.key])||i.def}</span>
      </div>
      <input type="range" min="${i.min}" max="${i.max}" step="1" value="${parseFloat(CSS_VARS[i.key])||i.def}"
        oninput="updateAvatarSlider('${i.key}',this.value,'${i.unit}');document.getElementById('avs-${i.key.replace(/[^a-z]/gi,'')}').textContent=this.value">
    </div>`).join('');
}

function updateAvatarSlider(key,val,unit){
  const v=val+unit;
  setCSSVar(key,v);
  const body=document.getElementById('avatar-body');
  const ambient=document.getElementById('avatar-ambient');
  if(key==='--avatar-w'){body.style.width=v;}
  if(key==='--avatar-h'){body.style.height=v;}
  if(key==='--avatar-opacity'){body.style.opacity=val/100;setCSSVar('--avatar-opacity',val/100);}
  if(key==='--avatar-glow-size'){ambient.style.width=v;ambient.style.height=v;}
}

function buildAmbientSliders(){
  document.getElementById('ambient-color-pick').value=CSS_VARS['--ambient-color']||'#7c6cff';
  document.getElementById('ambient-sliders').innerHTML=[
    {key:'--ambient-size',label:'Veličina',min:50,max:400,def:180,unit:'px'},
    {key:'--ambient-blur',label:'Blur',min:10,max:150,def:70,unit:'px'},
    {key:'--ambient-intensity',label:'Intenzitet (×10)',min:1,max:10,def:4.5,unit:''},
  ].map(i=>`
    <div style="margin-bottom:15px">
      <div style="display:flex;justify-content:space-between;margin-bottom:5px">
        <span style="font-size:12px;color:var(--muted)">${i.label}</span>
        <span style="font-size:12px;color:var(--acc2)" id="ams-${i.key.replace(/[^a-z]/gi,'')}">${parseFloat(CSS_VARS[i.key])||i.def}</span>
      </div>
      <input type="range" min="${i.min}" max="${i.max}" step="0.1" value="${parseFloat(CSS_VARS[i.key])||i.def}"
        oninput="updateAmbientSlider('${i.key}',this.value,'${i.unit}');document.getElementById('ams-${i.key.replace(/[^a-z]/gi,'')}').textContent=parseFloat(this.value).toFixed(1)">
    </div>`).join('');
}

function updateAmbientSlider(key,val,unit){
  setCSSVar(key,val+unit);
  const ambient=document.getElementById('avatar-ambient');
  if(key==='--ambient-size'){ambient.style.width=val+'px';ambient.style.height=val+'px';}
  if(key==='--ambient-blur'){ambient.style.filter='blur('+val+'px)';}
  if(key==='--ambient-intensity'){setCSSVar('--ambient-intensity',val/10);ambient.style.setProperty('--ambient-intensity',val/10);}
}

function updateAmbientColor(c){
  CSS_VARS['--ambient-color']=c;
  save('mb_css_vars',CSS_VARS);
  document.getElementById('avatar-ambient').style.background='radial-gradient(circle,'+c+'bb 0%,transparent 70%)';
  document.getElementById('avatar-status').style.boxShadow='0 0 8px '+c;
}

function toggleAmbientPulse(){
  ambientPulse=!ambientPulse;
  const btn=document.getElementById('ambient-pulse-btn');
  const ambient=document.getElementById('avatar-ambient');
  if(ambientPulse){btn.textContent='ON';btn.style.borderColor='var(--green)';btn.style.color='var(--green)';btn.style.background='rgba(34,211,238,0.15)';ambient.style.animationPlayState='running';}
  else{btn.textContent='OFF';btn.style.borderColor='var(--border)';btn.style.color='var(--muted)';btn.style.background='var(--card)';ambient.style.animationPlayState='paused';}
}

function buildPersonalityBtns(){
  const personalities={friendly:'😊 Prijateljski',professional:'💼 Profesionalni',funny:'😂 Šaljivi',futuristic:'🤖 Futuristički'};
  document.getElementById('personality-btns').innerHTML=Object.entries(personalities).map(([k,l])=>`
    <button onclick="setPersonality('${k}')" style="padding:10px 8px;border-radius:13px;border:1px solid ${aiPersonality===k?'var(--acc1)':'var(--border)'};background:${aiPersonality===k?'rgba(124,108,255,0.2)':'var(--card)'};color:${aiPersonality===k?'var(--acc2)':'var(--muted)'};font-weight:600;font-size:12px;cursor:pointer">${l}</button>`).join('');
}

function setPersonality(p){aiPersonality=p;save('mb_personality',p);buildPersonalityBtns();}

function buildVoiceBtns(){
  const voices={female:'👩 Ženski',male:'👨 Muški',robot:'🤖 Robot'};
  document.getElementById('voice-btns').innerHTML=Object.entries(voices).map(([k,l])=>`
    <button onclick="setVoice('${k}')" style="flex:1;padding:9px 0;border-radius:13px;border:1px solid ${voiceGender===k?'var(--acc2)':'var(--border)'};background:${voiceGender===k?'rgba(167,139,250,0.2)':'var(--card)'};color:${voiceGender===k?'var(--acc2)':'var(--muted)'};font-weight:600;font-size:12px;cursor:pointer">${l}</button>`).join('');
}

function setVoice(v){voiceGender=v;save('mb_voice',v);buildVoiceBtns();}

function resetTheme(){
  const def={
    '--acc1':'#7c6cff','--acc2':'#a78bfa','--acc3':'#38bdf8',
    '--green':'#22d3ee','--pink':'#f472b6','--glow':'#7c6cff',
    '--sh':'8px','--sb':'24px','--glass':'18px',
    '--avatar-glow-size':'60px','--float-speed':'3s','--glow-pulse':'2s',
    '--avatar-opacity':'1','--ambient-color':'#7c6cff','--ambient-intensity':'0.45','--fi':'8px',
  };
  Object.assign(CSS_VARS,def);
  save('mb_css_vars',CSS_VARS);
  applyCSSVars();
  notify('✅ Tema resetovana','info');
}

function saveUsername(){
  const val=document.getElementById('username-input').value.trim();
  if(!val){notify('Unesite ime','error');return;}
  userName=val;
  save('mb_username',userName);
  document.getElementById('home-username').textContent=userName;
  document.getElementById('prof-name').textContent=userName;
  notify(`✅ Zdravo, ${userName}!`,'success');
}

function saveGroqKey(){
  groqKey=document.getElementById('groq-key-input').value.trim();
  save('mb_groq_key',groqKey);
  notify('✅ API ključ sačuvan','success');
}

async function testGroq(){
  if(!groqKey){notify('Unesite API ključ','error');return;}
  try{
    const r=await fetch('https://api.groq.com/openai/v1/models',{headers:{'Authorization':'Bearer '+groqKey}});
    if(r.ok){setAIStatus('connected');notify('✅ Groq Connected!','success');}
    else{setAIStatus('error');notify('❌ Nevažeći API ključ','error');}
  }catch{setAIStatus('offline');notify('📡 Offline mode','info');}
}

function resetGroq(){
  groqKey='';
  save('mb_groq_key','');
  document.getElementById('groq-key-input').value='';
  setAIStatus('offline');
  notify('API resetovan','info');
}

function toggleWakeWord(){
  wakeWordEnabled=!wakeWordEnabled;
  const btn=document.getElementById('wake-word-toggle');
  if(wakeWordEnabled){btn.textContent='ON';btn.style.borderColor='var(--green)';btn.style.color='var(--green)';}
  else{btn.textContent='OFF';btn.style.borderColor='var(--border)';btn.style.color='var(--muted)';}
}

function setAIStatus(s){
  aiStatus=s;
  const colors={connected:'#22d3ee',offline:'#fb923c',error:'#ef4444'};
  const texts={connected:'✅ Groq Connected',offline:'📡 Offline AI Mode',error:'❌ AI Error'};
  const c=colors[s]||colors.offline;
  ['avatar-status','ai-status-dot','ai-chat-dot'].forEach(id=>{
    const el=document.getElementById(id);
    if(el){el.style.background=c;el.style.boxShadow='0 0 8px '+c;}
  });
  ['ai-status-text','ai-chat-status'].forEach(id=>{
    const el=document.getElementById(id);
    if(el)el.textContent=texts[s]||texts.offline;
  });
}

// ===================================================================
// AVATAR IMAGE UPLOAD — POPRAVLJEN ZA ANDROID/iOS
// ===================================================================

// Kreira novi file input svaki put (zaobilazi Android bug gde se onchange ne okida drugi put)
function triggerFileInput(useCamera){
  // Ukloni stari input ako postoji
  const old = document.getElementById('avatar-file-input');
  if(old) old.remove();

  // Napravi novi input
  const inp = document.createElement('input');
  inp.type = 'file';
  inp.id = 'avatar-file-input';
  inp.accept = 'image/*';
  if(useCamera) inp.setAttribute('capture','environment');
  inp.style.cssText = 'position:fixed;top:-9999px;left:-9999px;width:1px;height:1px;opacity:0';

  inp.addEventListener('change', function(e){
    const file = e.target.files && e.target.files[0];
    if(!file){ showUploadStatus('Nije odabrana slika','error'); return; }
    processAvatarFile(file);
  });

  document.body.appendChild(inp);

  // Mora biti van setTimeout na iOS, direktan click
  try {
    inp.click();
  } catch(err){
    // fallback
    inp.dispatchEvent(new MouseEvent('click',{bubbles:true,cancelable:true,view:window}));
  }
}

// Drag & drop handler
function handleDrop(event){
  event.preventDefault();
  event.stopPropagation();
  document.getElementById('drop-zone').style.borderColor = 'var(--border)';
  const file = event.dataTransfer && event.dataTransfer.files && event.dataTransfer.files[0];
  if(!file){ showUploadStatus('Nije pronađen fajl','error'); return; }
  if(!file.type.startsWith('image/')){ showUploadStatus('Molim odaberite sliku','error'); return; }
  processAvatarFile(file);
}

// Obrada fajla — zajednička za sve metode
function processAvatarFile(file){
  showUploadStatus('⏳ Učitavam sliku...','info');

  // Provera veličine (max 10MB)
  if(file.size > 10 * 1024 * 1024){
    showUploadStatus('❌ Slika je prevelika (max 10MB)','error');
    return;
  }

  const reader = new FileReader();

  reader.onerror = function(){
    showUploadStatus('❌ Greška pri čitanju fajla','error');
  };

  reader.onload = function(e){
    const dataUrl = e.target.result;
    if(!dataUrl || dataUrl.length < 100){
      showUploadStatus('❌ Fajl nije validan','error');
      return;
    }

    // Testiraj da li se slika može prikazati
    const testImg = new Image();
    testImg.onerror = function(){
      showUploadStatus('❌ Slika ne može biti prikazana','error');
    };
    testImg.onload = function(){
      const isPng = file.type === 'image/png';
      applyAvatar(dataUrl, isPng);
      if(isPng){
        showUploadStatus('✅ PNG učitan — prozirna pozadina sačuvana!','success');
        document.getElementById('remove-bg-section').style.display = 'none';
      } else {
        showUploadStatus('✅ Slika učitana! Možeš ukloniti pozadinu ispod.','success');
        document.getElementById('remove-bg-section').style.display = 'block';
      }
    };
    testImg.src = dataUrl;
  };

  reader.readAsDataURL(file);
}

function showUploadStatus(msg, type){
  const el = document.getElementById('upload-status');
  if(!el) return;
  const colors = {
    success: 'rgba(34,211,238,0.15)',
    error:   'rgba(239,68,68,0.15)',
    info:    'rgba(124,108,255,0.15)'
  };
  const borders = {
    success: 'rgba(34,211,238,0.4)',
    error:   'rgba(239,68,68,0.4)',
    info:    'rgba(124,108,255,0.4)'
  };
  el.style.display = 'block';
  el.style.background = colors[type] || colors.info;
  el.style.border = '1px solid ' + (borders[type] || borders.info);
  el.style.color = 'var(--text)';
  el.textContent = msg;
}

function applyAvatar(dataUrl, isPng){
  avatarImg = dataUrl;

  // Sačuvaj u localStorage (proba — ako je preveliko, preskoči)
  try {
    save('mb_avatar_img', dataUrl);
  } catch(e){
    console.warn('Slika prevelika za localStorage, koristim samo u memoriji');
  }

  // Ažuriraj lebdeći avatar
  const body = document.getElementById('avatar-body');
  body.className = 'avatar-body' + (isPng ? ' custom-img' : '');
  body.style.background = 'transparent';
  body.style.border = 'none';
  body.style.boxShadow = 'none';
  body.style.fontSize = '';
  body.style.filter = isPng
    ? 'drop-shadow(0 0 18px var(--acc1)) drop-shadow(0 0 35px rgba(124,108,255,0.35))'
    : '';
  body.innerHTML = `<img src="${dataUrl}" alt="avatar" style="width:100%;height:100%;object-fit:contain;display:block;${isPng?'border-radius:0':'border-radius:50%'}">`;

  updateAvatarPreviewInSettings();
}

function updateAvatarPreviewInSettings(){
  const prev = document.getElementById('settings-avatar-preview');
  if(!prev) return;
  if(avatarImg){
    prev.style.background = 'transparent';
    prev.style.border = '2px dashed var(--acc1)';
    prev.style.boxShadow = '0 0 16px rgba(124,108,255,0.3)';
    prev.innerHTML = `<img src="${avatarImg}" alt="avatar" style="width:100%;height:100%;object-fit:contain;display:block;border-radius:50%">`;
  } else {
    prev.innerHTML = '<span style="font-size:36px">🤖</span>';
    prev.style.background = 'radial-gradient(circle at 35% 35%,var(--acc1)cc,var(--acc2)55)';
    prev.style.border = '2px solid var(--border)';
    prev.style.boxShadow = '';
  }
}

// Uklanjanje pozadine — lokalno, canvas algoritam
function removeBackground(){
  if(!avatarImg){ notify('Nema učitane slike','error'); return; }
  showUploadStatus('🪄 Uklanjam pozadinu...','info');

  const img = new Image();
  img.onerror = function(){ showUploadStatus('❌ Greška','error'); };
  img.onload = function(){
    const canvas = document.getElementById('remove-bg-canvas');
    const MAX = 800;
    let w = img.width, h = img.height;
    if(w > MAX || h > MAX){
      const r = Math.min(MAX/w, MAX/h);
      w = Math.round(w*r); h = Math.round(h*r);
    }
    canvas.width = w;
    canvas.height = h;
    const ctx = canvas.getContext('2d');
    ctx.drawImage(img, 0, 0, w, h);

    const imageData = ctx.getImageData(0, 0, w, h);
    const d = imageData.data;

    // Uzorak boje pozadine iz uglova
    const pts = [
      [0,0],[w-1,0],[0,h-1],[w-1,h-1],
      [Math.floor(w/2),0],[0,Math.floor(h/2)],[w-1,Math.floor(h/2)],[Math.floor(w/2),h-1]
    ];
    let rS=0,gS=0,bS=0;
    pts.forEach(([x,y])=>{
      const i=(y*w+x)*4;
      rS+=d[i]; gS+=d[i+1]; bS+=d[i+2];
    });
    const bgR=rS/pts.length, bgG=gS/pts.length, bgB=bS/pts.length;

    // Tolerancija za uklanjanje
    const tol = 55;
    for(let i=0; i<d.length; i+=4){
      const dr=Math.abs(d[i]-bgR), dg=Math.abs(d[i+1]-bgG), db=Math.abs(d[i+2]-bgB);
      if(dr<tol && dg<tol && db<tol) d[i+3]=0;
    }
    ctx.putImageData(imageData,0,0);

    const result = canvas.toDataURL('image/png');
    applyAvatar(result, true);
    document.getElementById('remove-bg-section').style.display = 'none';
    showUploadStatus('✅ Pozadina uklonjena! Figura lebdi bez okvira 🎉','success');
  };
  img.src = avatarImg;
}

function resetAvatar(){
  avatarImg = null;
  try{ localStorage.removeItem('mb_avatar_img'); }catch{}
  const body = document.getElementById('avatar-body');
  body.innerHTML = '🤖';
  body.className = 'avatar-body';
  body.style.background = 'radial-gradient(circle at 35% 35%,var(--acc1)cc,var(--acc2)66)';
  body.style.boxShadow = '0 0 var(--avatar-glow-size) var(--avatar-glow),inset 0 1px 0 rgba(255,255,255,0.3)';
  body.style.border = '2px solid rgba(124,108,255,0.5)';
  body.style.fontSize = '38px';
  body.style.filter = '';
  document.getElementById('remove-bg-section').style.display = 'none';
  const st = document.getElementById('upload-status');
  if(st) st.style.display = 'none';
  updateAvatarPreviewInSettings();
  notify('Avatar resetovan','info');
}

// ===================================================================
// DRAGGABLE AVATAR
// ===================================================================
(function(){
  const el=document.getElementById('float-avatar');
  let isDragging=false,startX,startY,origX,origY;
  
  function getPos(){
    const s=el.style;
    return{x:parseInt(s.left)||20,y:parseInt(s.top)||420};
  }
  
  el.addEventListener('mousedown',e=>{
    const p=getPos();isDragging=true;startX=e.clientX;startY=e.clientY;origX=p.x;origY=p.y;e.preventDefault();
  });
  el.addEventListener('touchstart',e=>{
    const t=e.touches[0],p=getPos();isDragging=true;startX=t.clientX;startY=t.clientY;origX=p.x;origY=p.y;
  },{passive:true});
  
  window.addEventListener('mousemove',e=>{
    if(!isDragging)return;
    el.style.left=(origX+e.clientX-startX)+'px';
    el.style.top=(origY+e.clientY-startY)+'px';
  });
  window.addEventListener('touchmove',e=>{
    if(!isDragging)return;
    const t=e.touches[0];
    el.style.left=(origX+t.clientX-startX)+'px';
    el.style.top=(origY+t.clientY-startY)+'px';
  },{passive:true});
  
  let didDrag=false;
  const onEnd=()=>{
    const dx=Math.abs(parseInt(el.style.left)-origX);
    const dy=Math.abs(parseInt(el.style.top)-origY);
    didDrag=dx>5||dy>5;
    isDragging=false;
  };
  window.addEventListener('mouseup',onEnd);
  window.addEventListener('touchend',onEnd);
  
  el.addEventListener('click',()=>{if(!didDrag)openAI();});
})();

function toggleAvatarMini(){
  avatarMini=!avatarMini;
  const body=document.getElementById('avatar-body');
  const toggle=document.getElementById('avatar-mini-toggle');
  const ambient=document.getElementById('avatar-ambient');
  if(avatarMini){
    body.style.width='44px';body.style.height='44px';body.style.fontSize='22px';
    ambient.style.width='55px';ambient.style.height='55px';
    toggle.textContent='+';
  } else {
    body.style.width='var(--avatar-w)';body.style.height='var(--avatar-h)';body.style.fontSize='38px';
    ambient.style.width='var(--avatar-glow-size)';ambient.style.height='var(--avatar-glow-size)';
    toggle.textContent='−';
  }
}

// ===================================================================
// AI CHAT
// ===================================================================
function openAI(){openOverlay('ai-panel');if(chatMessages.length===0)addAIMsg(getGreeting());}

function getGreeting(){
  const greets={friendly:`Zdravo ${userName}! 😊 Kako mogu da pomognem?`,professional:`Poštovani ${userName}, spreman sam za finansijsku analizu.`,funny:`Yo ${userName}! 🎉 Što potrošio danas?`,futuristic:`Sistemska inicijalizacija... 🤖 Zdravo, ${userName}. Spreman za akciju.`};
  return greets[aiPersonality]||greets.futuristic;
}

function addAIMsg(text){
  chatMessages.push({role:'assistant',content:text});
  renderChat();
  speak(text);
}

function renderChat(){
  const area=document.getElementById('chat-area');
  area.innerHTML=chatMessages.map(m=>`
    <div class="chat-msg ${m.role}">
      <div class="chat-bubble ${m.role==='user'?'user':'ai'}">${m.content}</div>
    </div>`).join('');
  area.scrollTop=area.scrollHeight;
}

function sendQuickCmd(cmd){
  document.getElementById('chat-input').value=cmd;
  sendMessage();
}

async function sendMessage(){
  const input=document.getElementById('chat-input');
  const msg=input.value.trim();
  if(!msg)return;
  input.value='';
  chatMessages.push({role:'user',content:msg});
  renderChat();
  
  // Handle commands
  handleVoiceCmd(msg);
  
  // Show typing
  const area=document.getElementById('chat-area');
  const typing=document.createElement('div');
  typing.className='chat-msg';typing.id='typing-indicator';
  typing.innerHTML=`<div class="chat-bubble ai" style="padding:12px 16px"><span class="typing-dot" style="animation-delay:0s"></span><span class="typing-dot" style="animation-delay:0.15s;margin:0 4px"></span><span class="typing-dot" style="animation-delay:0.3s"></span></div>`;
  area.appendChild(typing);area.scrollTop=area.scrollHeight;
  
  const reply=await getAIReply(msg);
  document.getElementById('typing-indicator')?.remove();
  addAIMsg(reply);
}

function handleVoiceCmd(msg){
  const m=msg.toLowerCase();
  if(m.includes('dodaj trošak')||m.includes('dodaj rashod')){setTimeout(()=>openAddTxFromAI('expense'),800);}
  else if(m.includes('dodaj prihod')){setTimeout(()=>openAddTxFromAI('income'),800);}
  else if(m.includes('statistika')||m.includes('grafikon')){setTimeout(()=>{closeOverlay('ai-panel');showPage('stats');},600);}
  else if(m.includes('transakcij')){setTimeout(()=>{closeOverlay('ai-panel');showPage('transactions');},600);}
}

async function getAIReply(msg){
  const {income,expense,balance}=calcTotals();
  const sysPrompt=`Ti si AI finansijski asistent za aplikaciju "Moj budžet". Personality: ${aiPersonality}. Ime korisnika: ${userName}. Oslovljavaj ga sa "${userName}". Stanje: Prihodi: ${fmt(income)}, Rashodi: ${fmt(expense)}, Saldo: ${fmt(balance)}. Broj transakcija: ${transactions.length}. Odgovaraj kratko, max 2 rečenice, na srpskom.`;
  
  if(groqKey){
    try{
      const r=await fetch('https://api.groq.com/openai/v1/chat/completions',{
        method:'POST',
        headers:{'Content-Type':'application/json','Authorization':'Bearer '+groqKey},
        body:JSON.stringify({model:aiModel,messages:[{role:'system',content:sysPrompt},{role:'user',content:msg}],max_tokens:150,temperature:0.7}),
      });
      if(r.ok){
        const d=await r.json();
        setAIStatus('connected');
        return d.choices?.[0]?.message?.content||offlineReply(msg);
      }
    }catch{}
    setAIStatus('offline');
  }
  return offlineReply(msg);
}

function offlineReply(msg){
  const {income,expense,balance}=calcTotals();
  const m=msg.toLowerCase();
  if(m.includes('saldo')||m.includes('koliko imam')||m.includes('novca'))return`${userName}, tvoj saldo je ${fmt(balance)}.`;
  if(m.includes('potrošio')||m.includes('rashod'))return`${userName}, ukupni rashodi su ${fmt(expense)}.`;
  if(m.includes('prihod')||m.includes('zaradio'))return`${userName}, ukupni prihodi su ${fmt(income)}.`;
  if(m.includes('statistika')||m.includes('analiza'))return`${userName}, otvaram statistiku za tebe 📊`;
  if(m.includes('savet')||m.includes('štednja'))return`${userName}, preporučujem da smanjite troškove kategorije sa najvećim rashodima 💡`;
  if(m.includes('zdravo')||m.includes('bok')||m.includes('cao'))return getGreeting();
  if(m.includes('hvala'))return`Nema na čemu, ${userName}! 😊`;
  return`${userName}, saldo: ${fmt(balance)}. Ukupno ${transactions.length} transakcija. Šta još trebaš?`;
}

// ===================================================================
// SPEECH
// ===================================================================
function speak(text){
  if(!window.speechSynthesis)return;
  window.speechSynthesis.cancel();
  const utt=new SpeechSynthesisUtterance(text);
  utt.lang='sr-RS';
  utt.rate=1.0;
  utt.pitch=voiceGender==='female'?1.3:voiceGender==='robot'?0.6:0.85;
  const voices=window.speechSynthesis.getVoices();
  const v=voices.find(v=>v.lang.startsWith('sr')||v.lang.startsWith('hr')||v.lang.startsWith('bs'));
  if(v)utt.voice=v;
  const body=document.getElementById('avatar-body');
  utt.onstart=()=>{isSpeaking=true;body.style.animation='float var(--float-speed) ease-in-out infinite, glowPulse 0.4s ease-in-out infinite';};
  utt.onend=()=>{isSpeaking=false;body.style.animation='float var(--float-speed) ease-in-out infinite';};
  window.speechSynthesis.speak(utt);
}

function startListening(){
  if(!('webkitSpeechRecognition' in window||'SpeechRecognition' in window)){notify('Govorni unos nije podržan u ovom browseru','error');return;}
  if(isListening){window.recognitionRef?.stop();setListeningUI(false);return;}
  const SR=window.SpeechRecognition||window.webkitSpeechRecognition;
  const r=new SR();
  r.lang='sr-RS';r.continuous=false;r.interimResults=false;
  r.onresult=e=>{
    document.getElementById('chat-input').value=e.results[0][0].transcript;
    setListeningUI(false);
  };
  r.onerror=()=>setListeningUI(false);
  r.onend=()=>setListeningUI(false);
  window.recognitionRef=r;
  r.start();
  setListeningUI(true);
}

function setListeningUI(on){
  isListening=on;
  const btn=document.getElementById('mic-btn');
  if(btn){btn.textContent=on?'🔴':'🎤';btn.classList.toggle('listening',on);}
}

// ===================================================================
// INIT
// ===================================================================
let _initDone = false;
function init(){
  if(_initDone) return;
  _initDone = true;

  applyCSSVars();
  setThemeMode(themeMode);

  // Restore avatar safely
  if(avatarImg){
    try {
      applyAvatar(avatarImg, true);
    } catch(e){
      avatarImg = null;
    }
  }

  setAIStatus('offline');
  renderHome();
  buildCatGrid();

  // Popuni polja u settings
  setTimeout(()=>{
    const kf = document.getElementById('groq-key-input');
    if(kf) kf.value = groqKey;
    const un = document.getElementById('username-input');
    if(un) un.value = userName;
  }, 150);
}

document.addEventListener('DOMContentLoaded', init);
window.addEventListener('load', init);
</script>

<!-- PWA INSTALL BANNER -->
<div id="pwa-banner" style="display:none;position:fixed;bottom:96px;left:12px;right:12px;z-index:9990;background:linear-gradient(135deg,rgba(124,108,255,0.95),rgba(56,189,248,0.9));border-radius:18px;padding:14px 16px;box-shadow:0 8px 32px rgba(124,108,255,0.5);backdrop-filter:blur(20px)">
  <div style="display:flex;align-items:center;gap:12px">
    <span style="font-size:28px">💎</span>
    <div style="flex:1">
      <div style="font-size:14px;font-weight:800;color:#fff">Instaliraj Moj Budžet</div>
      <div style="font-size:11px;color:rgba(255,255,255,0.8)">Dodaj na početni ekran kao pravu aplikaciju</div>
    </div>
    <div style="display:flex;gap:7px">
      <button onclick="installPWA()" style="background:#fff;color:#7c6cff;border:none;border-radius:10px;padding:8px 14px;font-weight:800;font-size:13px;cursor:pointer">Instaliraj</button>
      <button onclick="document.getElementById('pwa-banner').style.display='none'" style="background:rgba(255,255,255,0.2);color:#fff;border:none;border-radius:10px;padding:8px 10px;font-size:13px;cursor:pointer">✕</button>
    </div>
  </div>
</div>

<!-- iOS INSTALL INSTRUCTIONS -->
<div id="ios-banner" style="display:none;position:fixed;bottom:96px;left:12px;right:12px;z-index:9990;background:linear-gradient(135deg,rgba(124,108,255,0.95),rgba(56,189,248,0.9));border-radius:18px;padding:14px 16px;box-shadow:0 8px 32px rgba(124,108,255,0.5)">
  <div style="display:flex;justify-content:space-between;align-items:flex-start">
    <div>
      <div style="font-size:14px;font-weight:800;color:#fff;margin-bottom:5px">💎 Instaliraj na iPhone</div>
      <div style="font-size:12px;color:rgba(255,255,255,0.9);line-height:1.6">
        1. Klikni <b>Podeli</b> dugme (□↑) dole<br>
        2. Izaberi <b>"Dodaj na početni ekran"</b><br>
        3. Klikni <b>Dodaj</b>
      </div>
    </div>
    <button onclick="document.getElementById('ios-banner').style.display='none'" style="background:rgba(255,255,255,0.2);color:#fff;border:none;border-radius:10px;padding:6px 10px;font-size:13px;cursor:pointer;flex-shrink:0;margin-left:10px">✕</button>
  </div>
</div>

<script>
// ===================================================================
// PWA SERVICE WORKER
// ===================================================================
const SW_CODE = `
const CACHE = 'moj-budzet-v1';
self.addEventListener('install', e => {
  self.skipWaiting();
});
self.addEventListener('activate', e => {
  e.waitUntil(clients.claim());
});
self.addEventListener('fetch', e => {
  e.respondWith(fetch(e.request).catch(() => caches.match(e.request)));
});
`;

if('serviceWorker' in navigator){
  const blob = new Blob([SW_CODE], {type:'application/javascript'});
  const swUrl = URL.createObjectURL(blob);
  navigator.serviceWorker.register(swUrl).catch(()=>{});
}

// PWA Install prompt
let deferredPrompt = null;
window.addEventListener('beforeinstallprompt', e => {
  e.preventDefault();
  deferredPrompt = e;
  // Pokaži banner nakon 2 sekunde
  setTimeout(() => {
    document.getElementById('pwa-banner').style.display = 'block';
  }, 2000);
});

function installPWA(){
  if(deferredPrompt){
    deferredPrompt.prompt();
    deferredPrompt.userChoice.then(()=>{
      deferredPrompt = null;
      document.getElementById('pwa-banner').style.display = 'none';
    });
  }
}

// iOS detekcija
const isIOS = /iPad|iPhone|iPod/.test(navigator.userAgent) && !window.MSStream;
const isInStandaloneMode = window.matchMedia('(display-mode: standalone)').matches || window.navigator.standalone;
if(isIOS && !isInStandaloneMode){
  setTimeout(() => {
    document.getElementById('ios-banner').style.display = 'block';
  }, 2500);
}

// ===================================================================
// FORCE CLEAR OLD 2024 LOCALSTORAGE DATA
// ===================================================================
(function(){
  try {
    const raw = localStorage.getItem('mb_txs');
    if(raw && raw.includes('2024')){
      localStorage.removeItem('mb_txs');
      localStorage.removeItem('mb_reminders');
      console.log('Obrisani stari 2024 podaci');
    }
  } catch(e){}
})();
</script>
</body>
</html>
