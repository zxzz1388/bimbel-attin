<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1.0"/>
<title>Bimbel Attin Indonesia</title>
<meta name="description" content="Bimbingan Belajar terpercaya di Sumatera Barat dan Bengkulu. Program Reguler, Intensif UTBK/SNBT, Konsultasi Jurusan AI, Try Out Online."/>
<link rel="preconnect" href="https://fonts.googleapis.com"/>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@600;700;800&family=DM+Sans:wght@400;500;600;700&display=swap" rel="stylesheet"/>
<style>

*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth;-webkit-font-smoothing:antialiased}
body{font-family:“DM Sans”,sans-serif;overflow-x:hidden;background:var(–bg);color:var(–txt);transition:background .3s,color .3s}
::-webkit-scrollbar{width:5px}::-webkit-scrollbar-thumb{background:var(–red);border-radius:5px}
:root{
–red:#c8102e;–red2:#e8192e;–red3:#ff4d6d;–gold:#d4a017;–gold2:#f0c040;
–bg:#0d0d0f;–bg2:#141418;–bg3:#1c1c22;–bg4:#242430;
–txt:#f0f0f5;–txt2:#a8a8b8;–txt3:#6e6e80;
–bdr:rgba(255,255,255,.07);–bdr2:rgba(255,255,255,.13);–bdr3:rgba(255,255,255,.2);
–nav:rgba(13,13,15,.93);–ibg:#1c1c22;–thd:#1c1c22;–thov:rgba(255,255,255,.04);
–sdbar:#141418;–shad:rgba(0,0,0,.45);–shad2:rgba(0,0,0,.7);
–tr-bg:rgba(200,16,46,.15);–tr-c:#ff4d6d;–tr-br:rgba(200,16,46,.25);
–tg-bg:rgba(212,160,23,.12);–tg-c:#f0c040;–tg-br:rgba(212,160,23,.2);
–tn-bg:rgba(34,197,94,.1);–tn-c:#4ade80;–tn-br:rgba(34,197,94,.2);
–tb-bg:rgba(59,130,246,.1);–tb-c:#60a5fa;–tb-br:rgba(59,130,246,.2);
–tp-bg:rgba(168,85,247,.1);–tp-c:#c084fc;–tp-br:rgba(168,85,247,.2);
}
body.light{
–bg:#f5f5f8;–bg2:#fff;–bg3:#ebebf0;–bg4:#dddde8;
–txt:#111118;–txt2:#44445a;–txt3:#88889a;
–bdr:rgba(0,0,0,.08);–bdr2:rgba(0,0,0,.14);–bdr3:rgba(0,0,0,.22);
–nav:rgba(245,245,248,.94);–ibg:#fff;–thd:#ebebf0;–thov:rgba(0,0,0,.03);
–sdbar:#fff;–shad:rgba(0,0,0,.1);–shad2:rgba(0,0,0,.22);
–tr-bg:rgba(200,16,46,.08);–tr-c:#b00a25;–tr-br:rgba(200,16,46,.18);
–tg-bg:rgba(180,110,0,.08);–tg-c:#7a4e00;–tg-br:rgba(180,110,0,.18);
–tn-bg:rgba(21,128,61,.08);–tn-c:#15803d;–tn-br:rgba(21,128,61,.18);
–tb-bg:rgba(29,78,216,.08);–tb-c:#1d4ed8;–tb-br:rgba(29,78,216,.18);
–tp-bg:rgba(124,58,237,.08);–tp-c:#7c3aed;–tp-br:rgba(124,58,237,.18);
}
/* Layout */
.wrap{max-width:1140px;margin:0 auto;padding:0 24px}
.sec{padding:80px 0;background:var(–bg)}.sec.alt{background:var(–bg2)}
.g2{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:22px}
.g3{display:grid;grid-template-columns:repeat(auto-fill,minmax(280px,1fr));gap:20px}
.g4{display:grid;grid-template-columns:repeat(auto-fill,minmax(220px,1fr));gap:14px}
.g5{display:grid;grid-template-columns:repeat(auto-fill,minmax(200px,1fr));gap:16px}
.gstat{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:14px;margin-top:60px}
/* Buttons */
.btn-r{display:inline-flex;align-items:center;gap:7px;background:linear-gradient(135deg,var(–red),var(–red2));color:#fff;border:none;border-radius:11px;font-family:inherit;font-weight:700;font-size:14px;padding:12px 26px;cursor:pointer;transition:all .25s}
.btn-r:hover{transform:translateY(-2px);box-shadow:0 12px 32px rgba(200,16,46,.38)}
.btn-g{display:inline-flex;align-items:center;gap:7px;background:transparent;color:var(–txt2);border:1px solid var(–bdr2);border-radius:11px;font-family:inherit;font-weight:500;font-size:14px;padding:11px 22px;cursor:pointer;transition:all .25s}
.btn-g:hover{background:var(–bdr2);transform:translateY(-2px)}

.btn-sm{padding:7px 15px !important;font-size:12px !important;border-radius:8px !important}
/* Cards */
.card{background:var(–bg2);border:1px solid var(–bdr);border-radius:18px;overflow:hidden;box-shadow:0 4px 20px var(–shad);transition:transform .3s,box-shadow .3s}
.card:hover{transform:translateY(-6px);box-shadow:0 18px 50px var(–shad)}
/* Tags */
.tag{display:inline-flex;align-items:center;padding:3px 11px;border-radius:20px;font-size:11px;font-weight:600;letter-spacing:.5px;text-transform:uppercase}
.tr{background:var(–tr-bg);color:var(–tr-c);border:1px solid var(–tr-br)}
.tg{background:var(–tg-bg);color:var(–tg-c);border:1px solid var(–tg-br)}
.tn{background:var(–tn-bg);color:var(–tn-c);border:1px solid var(–tn-br)}
.tb{background:var(–tb-bg);color:var(–tb-c);border:1px solid var(–tb-br)}
.tp{background:var(–tp-bg);color:var(–tp-c);border:1px solid var(–tp-br)}

/* Section label */
.sl{display:inline-flex;align-items:center;gap:8px;font-size:11px;font-weight:700;text-transform:uppercase;letter-spacing:2px;color:var(–red);margin-bottom:14px}
.sl::before{content:””;width:22px;height:2px;background:linear-gradient(90deg,var(–red),var(–red3));border-radius:2px;flex-shrink:0}
/* Inputs */
.inp{width:100%;padding:12px 14px;background:var(–ibg);border:1.5px solid var(–bdr2);border-radius:11px;font-size:14px;font-family:inherit;color:var(–txt);outline:none;transition:all .2s;-webkit-appearance:none;appearance:none}
.inp:focus{border-color:var(–red);box-shadow:0 0 0 3px rgba(200,16,46,.12)}
select.inp{background-image:url(“data:image/svg+xml,%3Csvg xmlns=‘http://www.w3.org/2000/svg’ width=‘12’ height=‘12’ viewBox=‘0 0 24 24’%3E%3Cpath fill=’%23888’ d=‘M7 10l5 5 5-5z’/%3E%3C/svg%3E”);background-repeat:no-repeat;background-position:right 13px center;padding-right:36px}
textarea.inp{resize:vertical;min-height:84px;line-height:1.65}
.lbl{display:block;font-size:11px;font-weight:700;color:var(–txt3);margin-bottom:6px;text-transform:uppercase;letter-spacing:.7px}
/* Nav */
nav{position:sticky;top:0;z-index:300;background:var(–nav);backdrop-filter:blur(24px);-webkit-backdrop-filter:blur(24px);border-bottom:1px solid var(–bdr)}
.nav-in{display:flex;align-items:center;justify-content:space-between;height:68px}
.brand{display:flex;align-items:center;gap:12px;cursor:pointer;border:none;background:none;font-family:inherit}
.np{cursor:pointer;padding:7px 12px;border-radius:9px;font-weight:500;font-size:13px;color:var(–txt2);border:none;background:transparent;font-family:inherit;transition:all .2s;white-space:nowrap}
.np:hover,.np.on{color:var(–red)}.np.on{background:rgba(200,16,46,.09)}
.tbtn{display:flex;align-items:center;gap:6px;background:rgba(255,255,255,.06);border:1px solid var(–bdr2);border-radius:30px;padding:6px 14px 6px 9px;cursor:pointer;font-family:inherit;font-size:13px;font-weight:600;color:var(–txt);transition:all .25s}
body.light .tbtn{background:rgba(0,0,0,.05)}
.ticon{width:22px;height:22px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:12px}
.mnav{display:none;background:var(–bg2);border-top:1px solid var(–bdr);padding:12px 24px 16px;flex-direction:column;gap:3px}
.mnav.open{display:flex}
.mob-btn{display:none;background:var(–bg3);border:1px solid var(–bdr);border-radius:9px;padding:9px;cursor:pointer;color:var(–txt);align-items:center}
/* Hero */
.hero{position:relative;min-height:92vh;display:flex;align-items:center;overflow:hidden;background:var(–bg)}
.hero-bg{position:absolute;inset:0;background:radial-gradient(ellipse 70% 60% at 70% 50%,rgba(200,16,46,.12) 0%,transparent 60%)}
body.light .hero-bg{background:radial-gradient(ellipse 70% 60% at 70% 50%,rgba(200,16,46,.06) 0%,transparent 60%)}
.hero-orb{position:absolute;top:8%;right:4%;width:360px;height:360px;border-radius:50%;background:radial-gradient(circle,rgba(200,16,46,.08) 0%,transparent 70%);animation:floatA 9s ease-in-out infinite;pointer-events:none}
.hero-orb2{position:absolute;bottom:10%;left:5%;width:200px;height:200px;border-radius:50%;background:radial-gradient(circle,rgba(14,165,233,.06) 0%,transparent 70%);animation:floatB 7s ease-in-out infinite;pointer-events:none}
.hero-grid{position:absolute;inset:0;opacity:0;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:64px 64px}
body:not(.light) .hero-grid{opacity:1}
.hlogo{width:clamp(130px,16vw,200px);height:clamp(130px,16vw,200px);object-fit:contain;flex-shrink:0;animation:floatA 7s ease-in-out infinite;filter:drop-shadow(0 0 40px rgba(200,16,46,.32))}
body.light .hlogo{filter:drop-shadow(0 0 22px rgba(200,16,46,.18))}
.gtxt{background:linear-gradient(135deg,#c8102e,#e8192e,#d4a017);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text}
/* Stat card */
.sc{background:var(–bg2);border:1px solid var(–bdr);border-radius:15px;padding:20px 16px;text-align:center;position:relative;overflow:hidden;box-shadow:0 2px 12px var(–shad);transition:transform .28s}
.sc:hover{transform:translateY(-3px)}
.sc::before{content:””;position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,transparent,var(–scc,#c8102e),transparent)}
/* Branch card */
.bc{background:var(–bg2);border:1px solid var(–bdr);border-radius:15px;padding:20px;box-shadow:0 2px 12px var(–shad);transition:all .3s}
.bc:hover{border-color:rgba(200,16,46,.3);transform:translateY(-3px)}
.bnum{width:36px;height:36px;border-radius:10px;background:rgba(200,16,46,.1);border:1px solid rgba(200,16,46,.22);display:flex;align-items:center;justify-content:center;font-family:“Syne”,sans-serif;font-weight:800;font-size:13px;color:var(–red);flex-shrink:0}
/* App Card (untuk konsultasi/tryout launcher) */
.app-card{background:var(–bg2);border:1px solid var(–bdr);border-radius:20px;overflow:hidden;transition:all .3s;cursor:pointer;position:relative}
.app-card:hover{transform:translateY(-6px);box-shadow:0 20px 52px var(–shad);border-color:var(–bdr2)}
.app-card-thumb{height:160px;display:flex;align-items:center;justify-content:center;position:relative;overflow:hidden}
.app-card-thumb img{width:100%;height:100%;object-fit:cover;transition:transform .4s}
.app-card:hover .app-card-thumb img{transform:scale(1.06)}
.app-card-overlay{position:absolute;inset:0;background:linear-gradient(to bottom,transparent 40%,rgba(0,0,0,.8) 100%)}
.app-card-body{padding:16px 18px 18px}
.app-badge{position:absolute;top:12px;right:12px}
/* App Iframe Modal */
.app-frame-modal{position:fixed;inset:0;z-index:2000;display:none;flex-direction:column;background:var(–bg)}
.app-frame-modal.open{display:flex}
.app-frame-bar{background:var(–bg2);border-bottom:1px solid var(–bdr);padding:0 18px;height:54px;display:flex;align-items:center;justify-content:space-between;flex-shrink:0}
.app-frame-bar-info{display:flex;align-items:center;gap:12px}
.app-frame-bar-icon{width:34px;height:34px;border-radius:9px;object-fit:cover;flex-shrink:0}
.app-iframe{flex:1;width:100%;border:none;background:#fff}
/* CMS */
.cms{display:flex;min-height:100vh}
.cms-side{width:224px;background:var(–sdbar);border-right:1px solid var(–bdr);display:flex;flex-direction:column;flex-shrink:0;position:sticky;top:0;height:100vh}
.cms-main{flex:1;overflow:auto;background:var(–bg)}
.cni{display:flex;align-items:center;gap:9px;padding:9px 12px;border-radius:10px;cursor:pointer;font-size:13px;font-weight:500;color:var(–txt2);border:1px solid transparent;transition:all .15s;font-family:inherit;background:transparent;width:100%;text-align:left}
.cni:hover{background:var(–bdr);color:var(–txt)}.cni.on{background:linear-gradient(135deg,rgba(200,16,46,.22),rgba(200,16,46,.06));color:#fff;border-color:rgba(200,16,46,.25)}
.cni-section{font-size:9px;font-weight:700;color:var(–txt3);text-transform:uppercase;letter-spacing:1.5px;padding:10px 12px 4px;margin-top:4px}
.ctop{background:var(–bg2);padding:14px 24px;border-bottom:1px solid var(–bdr);display:flex;justify-content:space-between;align-items:center;position:sticky;top:0;z-index:10}
.cc{padding:clamp(14px,3vw,26px)}
.tw{background:var(–bg2);border-radius:14px;border:1px solid var(–bdr);overflow:hidden;box-shadow:0 2px 10px var(–shad)}
.thr{display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:8px;padding:14px 18px;border-bottom:1px solid var(–bdr)}
table{width:100%;border-collapse:collapse}
th{padding:10px 14px;text-align:left;font-size:10px;font-weight:700;color:var(–txt3);text-transform:uppercase;letter-spacing:.8px;background:var(–thd);white-space:nowrap}
td{padding:11px 14px;color:var(–txt);font-size:13px;border-bottom:1px solid var(–bdr)}
tr:last-child td{border-bottom:none}
tr:hover td{background:var(–thov)}
.ts{overflow-x:auto}
/* Upload */
.uarea{border:2px dashed var(–bdr2);border-radius:14px;padding:32px 20px;text-align:center;cursor:pointer;transition:all .25s;background:var(–bg3)}
.uarea:hover,.uarea.drag{border-color:var(–red);background:rgba(200,16,46,.05)}
.pvgrid{display:grid;grid-template-columns:repeat(auto-fill,minmax(110px,1fr));gap:10px;margin-top:14px}
.pvitem{position:relative;border-radius:9px;overflow:hidden;aspect-ratio:16/9;background:var(–bg3)}
.pvitem img,.pvitem video{width:100%;height:100%;object-fit:cover;display:block}
.pvrm{position:absolute;top:4px;right:4px;background:rgba(0,0,0,.75);color:#fff;border:none;border-radius:50%;width:24px;height:24px;cursor:pointer;font-size:14px;display:flex;align-items:center;justify-content:center;line-height:1;font-family:inherit}
/* Discount */
.dok{display:inline-flex;align-items:center;gap:6px;background:var(–tg-bg);border:1px solid var(–tg-br);border-radius:10px;padding:9px 14px;font-size:13px;font-weight:600;color:var(–tg-c)}
.dok.bad{background:var(–tr-bg);border-color:var(–tr-br);color:var(–tr-c)}

/* Try Out */
.to-card{background:var(–bg2);border:1px solid var(–bdr);border-radius:16px;padding:22px;transition:all .3s;cursor:pointer}
.to-card:hover{border-color:rgba(200,16,46,.3);transform:translateY(-3px);box-shadow:0 12px 30px var(–shad)}
.to-card.locked{opacity:.6;cursor:not-allowed}
.to-card.locked:hover{transform:none}
.q-wrap{background:var(–bg2);border-radius:16px;padding:24px;border:1px solid var(–bdr);margin-bottom:16px}
.q-opt{display:flex;align-items:center;gap:12px;padding:12px 16px;border-radius:11px;border:1.5px solid var(–bdr2);cursor:pointer;transition:all .2s;margin-bottom:8px;font-size:14px}
.q-opt:hover{border-color:var(–red);background:rgba(200,16,46,.05)}
.q-opt.selected{border-color:var(–red);background:rgba(200,16,46,.08);color:var(–txt)}
.q-opt.correct{border-color:var(–tn-c);background:var(–tn-bg);color:var(–tn-c)}
.q-opt.wrong{border-color:var(–tr-c);background:var(–tr-bg);color:var(–tr-c)}
.q-opt-letter{width:30px;height:30px;border-radius:8px;display:flex;align-items:center;justify-content:center;font-weight:700;font-size:13px;background:var(–bg3);flex-shrink:0}
/* Modal */
.mo{position:fixed;inset:0;background:rgba(0,0,0,.72);display:none;align-items:center;justify-content:center;z-index:1000;padding:20px;backdrop-filter:blur(8px)}
.mo.open{display:flex}
.mb{width:100%;max-width:560px;max-height:92vh;overflow-y:auto;border-radius:20px;padding:clamp(22px,4vw,34px);background:var(–bg2);border:1px solid var(–bdr2);box-shadow:0 40px 120px var(–shad2)}
.mb.lg{max-width:720px}.mb.xl{max-width:900px}
.fg{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:14px}
.ff{grid-column:1/-1}
/* Toast */
.toast{position:fixed;bottom:24px;right:24px;padding:13px 22px;border-radius:12px;z-index:9999;font-weight:600;font-size:13px;box-shadow:0 12px 40px rgba(0,0,0,.3);display:flex;align-items:center;gap:8px;color:#fff;transform:translateY(90px);opacity:0;transition:all .38s cubic-bezier(.22,.68,0,1.2)}
.toast.show{transform:translateY(0);opacity:1}.toast.ok{background:rgba(21,128,61,.96)}.toast.err{background:rgba(200,16,46,.96)}
/* Page/View */
.page{display:none}.page.active{display:block}
footer{background:var(–bg2);border-top:1px solid var(–bdr);padding:32px 0}
.fi{display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:12px}
/* Loading */
.loading-screen{position:fixed;inset:0;background:var(–bg);display:flex;flex-direction:column;align-items:center;justify-content:center;z-index:9999;gap:20px;transition:opacity .5s}
.loading-screen.fade{opacity:0;pointer-events:none}
.spin{width:44px;height:44px;border:3px solid var(–bdr2);border-top-color:var(–red);border-radius:50%;animation:spin .8s linear infinite}
@keyframes spin{to{transform:rotate(360deg)}}
@keyframes floatA{0%,100%{transform:translateY(0)}50%{transform:translateY(-18px)}}
@keyframes floatB{0%,100%{transform:translateY(0)}50%{transform:translateY(12px)}}
@keyframes fadeUp{from{opacity:0;transform:translateY(22px)}to{opacity:1;transform:translateY(0)}}
.fu{animation:fadeUp .55s ease both}.fu1{animation:fadeUp .55s .1s ease both}
.fu2{animation:fadeUp .55s .2s ease both}.fu3{animation:fadeUp .55s .3s ease both}
.fu4{animation:fadeUp .55s .4s ease both}
.cta-band{position:relative;overflow:hidden;padding:80px 0;background:var(–bg)}
.cta-band::before{content:””;position:absolute;inset:0;background:linear-gradient(135deg,rgba(200,16,46,.08) 0%,rgba(212,160,23,.04) 100%)}
/* Progress bar */
.prog-bar{height:6px;background:var(–bg4);border-radius:6px;overflow:hidden;margin-top:8px}
.prog-fill{height:100%;background:linear-gradient(90deg,var(–red),var(–red2));border-radius:6px;transition:width .4s}
/* Score ring */
.score-ring{width:140px;height:140px;border-radius:50%;display:flex;align-items:center;justify-content:center;flex-direction:column;border:6px solid var(–bdr2);position:relative}
.score-ring::before{content:””;position:absolute;inset:0;border-radius:50%;border:6px solid var(–red);clip-path:inset(0 0 0 0)}
@media(max-width:768px){
.nav-links,.hlogo{display:none !important}
.mob-btn{display:flex !important}
.cms-side{width:100%;position:relative;height:auto;flex-direction:row;flex-wrap:wrap;padding:8px}
.cni{padding:7px 10px;font-size:11px;width:auto}
.cni-section{display:none}
.ctop{position:relative}
.app-card-thumb{height:120px}
}

</style>
</head>
<body>

<!-- Global file input -->

<input type="file" id="_gfi" multiple style="display:none;position:fixed;left:-9999px" onchange="_gfc(event)"/>

<!-- Loading -->

<div class="loading-screen" id="loading">
  <img id="load-logo" src="" style="width:80px;height:80px;border-radius:50%;object-fit:contain;border:2px solid rgba(200,16,46,.3)" alt=""/>
  <div class="spin"></div>
  <div style="font-family:Syne,sans-serif;font-weight:700;font-size:15px;color:var(--txt)">Bimbel Attin Indonesia</div>
</div>

<!-- App Frame Modal (untuk buka aplikasi eksternal) -->

<div class="app-frame-modal" id="appFrame">
  <div class="app-frame-bar">
    <div class="app-frame-bar-info">
      <img id="afIcon" class="app-frame-bar-icon" src="" alt=""/>
      <div>
        <div id="afTitle" style="font-family:Syne,sans-serif;font-weight:700;font-size:14px;color:var(--txt)"></div>
        <div id="afUrl" style="font-size:11px;color:var(--txt3);margin-top:1px"></div>
      </div>
    </div>
    <div style="display:flex;gap:8px">
      <button onclick="openAppNewTab()" style="background:var(--bg3);border:1px solid var(--bdr);border-radius:8px;padding:7px 13px;cursor:pointer;font-family:inherit;font-size:12px;font-weight:600;color:var(--txt2)">&#8599; Buka Tab Baru</button>
      <button onclick="closeAppFrame()" style="background:var(--tr-bg);border:1px solid var(--tr-br);border-radius:8px;padding:7px 13px;cursor:pointer;font-family:inherit;font-size:12px;font-weight:700;color:var(--tr-c)">&#10005; Tutup</button>
    </div>
  </div>
  <iframe id="appIframe" class="app-iframe" src="" allow="camera;microphone;fullscreen" allowfullscreen></iframe>
</div>

<!-- PUBLIC SITE -->

<div id="site" style="display:none">
<nav>
  <div class="wrap"><div class="nav-in">
    <button class="brand" onclick="goPage('home')">
      <img class="lgo" src="" style="width:42px;height:42px;object-fit:contain;border-radius:50%;border:2px solid rgba(200,16,46,.3)" alt="Attin"/>
      <div><div style="font-family:Syne,sans-serif;font-weight:800;font-size:16px;color:var(--txt);line-height:1.1">Bimbel Attin</div><div style="font-size:9px;color:var(--txt3);letter-spacing:2px;text-transform:uppercase">Indonesia</div></div>
    </button>
    <div class="nav-links" style="display:flex;align-items:center;gap:1px">
      <button class="np on" data-pg="home" onclick="goPage('home')">Beranda</button>
      <button class="np" data-pg="programs" onclick="goPage('programs')">Program</button>
      <button class="np" data-pg="cabang" onclick="goPage('cabang')">Cabang</button>
      <button class="np" data-pg="video" onclick="goPage('video')">Video</button>
      <button class="np" data-pg="gallery" onclick="goPage('gallery')">Galeri</button>
      <button class="np" data-pg="lulusan" onclick="goPage('lulusan')">Lulusan</button>
      <button class="np" data-pg="apps" onclick="goPage('apps')">&#128640; Aplikasi</button>
      <button class="np" data-pg="daftar" onclick="goPage('daftar')">Daftar</button>
      <div style="width:1px;height:22px;background:var(--bdr);margin:0 6px"></div>
      <button class="tbtn" onclick="toggleTheme()"><span class="ticon" id="tic">&#127769;</span><span id="tlbl">Terang</span></button>
      <button class="btn-r btn-sm" style="margin-left:6px" onclick="openLogin()">&#128274; Admin</button>
    </div>
    <button class="mob-btn" onclick="document.getElementById('mnav').classList.toggle('open')">
      <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2"><line x1="4" y1="6" x2="20" y2="6"/><line x1="4" y1="12" x2="20" y2="12"/><line x1="4" y1="18" x2="20" y2="18"/></svg>
    </button>
  </div></div>
  <div class="mnav" id="mnav">
    <button class="np" onclick="goPage('home');closeMnav()">Beranda</button>
    <button class="np" onclick="goPage('programs');closeMnav()">Program</button>
    <button class="np" onclick="goPage('cabang');closeMnav()">Cabang</button>
    <button class="np" onclick="goPage('video');closeMnav()">Video</button>
    <button class="np" onclick="goPage('gallery');closeMnav()">Galeri</button>
    <button class="np" onclick="goPage('lulusan');closeMnav()">Lulusan</button>
    <button class="np" onclick="goPage('apps');closeMnav()">&#128640; Aplikasi</button>
    <button class="np" onclick="goPage('daftar');closeMnav()">Daftar</button>
    <div style="display:flex;gap:8px;margin-top:10px;flex-wrap:wrap">
      <button class="tbtn" onclick="toggleTheme()"><span class="ticon" id="tic-m">&#127769;</span><span id="tlbl-m">Terang</span></button>
      <button class="btn-r btn-sm" onclick="openLogin();closeMnav()">&#128274; Admin</button>
    </div>
  </div>
</nav>

<!-- ═══════════ HOME ═══════════ -->

<div class="page active" id="pg-home">
  <div class="hero"><div class="hero-bg"></div><div class="hero-orb"></div><div class="hero-orb2"></div><div class="hero-grid"></div>
    <div class="wrap" style="width:100%;position:relative;z-index:1;padding-top:44px;padding-bottom:44px">
      <div style="display:flex;align-items:center;gap:52px;flex-wrap:wrap">
        <div style="flex:1;min-width:280px">
          <div class="sl fu">Bimbingan Belajar Terpercaya</div>
          <h1 style="font-family:Syne,sans-serif;font-weight:800;font-size:clamp(34px,6vw,68px);line-height:1.04;color:var(--txt);margin-bottom:20px" class="fu1">Raih PTN<br><span class="gtxt">Impianmu</span><br>Bersama Kami</h1>
          <p class="fu2" style="font-size:clamp(15px,2vw,18px);color:var(--txt2);line-height:1.85;max-width:520px;margin-bottom:32px">Lebih dari <strong style="color:var(--txt)">1.000 alumni</strong> tembus PTN terbaik. Hadir di <strong style="color:var(--txt)">11 kota</strong> Sumatera Barat &amp; Bengkulu.</p>
          <div class="fu3" style="display:flex;gap:12px;flex-wrap:wrap;margin-bottom:24px">
            <button class="btn-r" style="font-size:15px;padding:14px 30px" onclick="goPage('daftar')">Daftar Sekarang &#8594;</button>
          </div>
          <div class="fu4" style="display:flex;gap:8px;flex-wrap:wrap">
            <span class="tag tn">&#10003; Kurikulum Merdeka</span>
            <span class="tag tg">&#10003; Try Out Online</span>
          </div>
        </div>
        <img class="lgo hlogo" src="" alt="Logo"/>
      </div>
      <div class="gstat" id="home-stats"></div>
    </div>
  </div>
  <div class="sec alt"><div class="wrap"><div class="sl">Program Kami</div><h2 style="font-family:Syne,sans-serif;font-weight:800;color:var(--txt);font-size:clamp(26px,4vw,44px);margin-bottom:36px">Pilih Jalur Menuju <span style="color:var(--red)">PTN</span></h2><div class="g2" id="home-progs"></div></div></div>

  <div class="sec alt"><div class="wrap"><div style="display:flex;justify-content:space-between;align-items:flex-end;flex-wrap:wrap;gap:12px;margin-bottom:36px"><div><div class="sl">Konten Edukasi</div><h2 style="font-family:Syne,sans-serif;font-weight:800;color:var(--txt);font-size:clamp(24px,4vw,40px)">Video Pembelajaran</h2></div><button class="btn-g btn-sm" onclick="goPage('video')">Lihat Semua &#8594;</button></div><div class="g3" id="home-vids"></div></div></div>
  <div class="sec"><div class="wrap"><div style="display:flex;justify-content:space-between;align-items:flex-end;flex-wrap:wrap;gap:12px;margin-bottom:36px"><div><div class="sl">Prestasi</div><h2 style="font-family:Syne,sans-serif;font-weight:800;color:var(--txt);font-size:clamp(24px,4vw,40px)">Lulusan <span style="color:var(--gold2)">PTN</span></h2></div><button class="btn-g btn-sm" onclick="goPage('lulusan')">Lihat Semua &#8594;</button></div><div class="g3" id="home-grads"></div></div></div>
  <div class="sec alt"><div class="wrap" style="text-align:center"><div class="sl" style="justify-content:center">Lokasi</div><h2 style="font-family:Syne,sans-serif;font-weight:800;color:var(--txt);font-size:clamp(24px,4vw,40px);margin-bottom:10px">11 Cabang di 2 Provinsi</h2><p style="color:var(--txt2);margin:0 auto 36px;max-width:460px;line-height:1.7">Sumatera Barat &amp; Bengkulu &#8212; selalu dekat dengan kamu</p><div style="display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin-bottom:30px" id="home-chips"></div><button class="btn-r" style="font-size:15px;padding:14px 32px" onclick="goPage('cabang')">Temukan Cabang &#128205;</button></div></div>
  <div class="cta-band"><div class="wrap" style="position:relative;text-align:center"><h2 style="font-family:Syne,sans-serif;font-weight:800;color:var(--txt);font-size:clamp(26px,4vw,48px);margin-bottom:16px">Siap Meraih <span class="gtxt">PTN Impian?</span></h2><p style="color:var(--txt2);font-size:16px;line-height:1.85;margin-bottom:32px;max-width:560px;margin-left:auto;margin-right:auto">Bergabung bersama ribuan siswa yang telah membuktikan kualitas Bimbel Attin.</p><div style="display:flex;gap:12px;justify-content:center;flex-wrap:wrap"><button class="btn-r" style="font-size:15px;padding:14px 32px" onclick="goPage('daftar')">Daftar Gratis &#8594;</button><button class="btn-g" style="font-size:15px;padding:13px 26px" onclick="goPage('cabang')">&#128205; Cari Cabang</button></div></div></div>
  <footer><div class="wrap"><div class="fi" id="footer-home"></div></div></footer>
</div>

<!-- ═══════════ PROGRAMS ═══════════ -->

<div class="page" id="pg-programs"><div class="sec"><div class="wrap"><div class="sl">Program Unggulan</div><h2 style="font-family:Syne,sans-serif;font-weight:800;color:var(--txt);font-size:clamp(26px,4vw,44px);margin-bottom:10px">Pilih Program yang Tepat</h2><p style="color:var(--txt2);font-size:15px;margin-bottom:44px;line-height:1.7;max-width:540px">Dua program dirancang untuk kebutuhan belajar yang berbeda.</p><div id="progs-content"></div></div></div><footer><div class="wrap"><div class="fi" id="footer-progs"></div></div></footer></div>

<!-- ═══════════ CABANG ═══════════ -->

<div class="page" id="pg-cabang"><div class="sec"><div class="wrap"><div class="sl">Lokasi</div><h2 style="font-family:Syne,sans-serif;font-weight:800;color:var(--txt);font-size:clamp(26px,4vw,44px);margin-bottom:10px">Cabang Bimbel Attin</h2><p id="cab-cnt" style="color:var(--txt2);font-size:15px;margin-bottom:44px"></p><div class="g3" id="cab-list"></div></div></div><footer><div class="wrap"><div class="fi" id="footer-cab"></div></div></footer></div>

<!-- ═══════════ VIDEO ═══════════ -->

<div class="page" id="pg-video"><div class="sec"><div class="wrap"><div class="sl">Belajar Online</div><h2 style="font-family:Syne,sans-serif;font-weight:800;color:var(--txt);font-size:clamp(26px,4vw,44px);margin-bottom:10px">Video Pembelajaran</h2><p style="color:var(--txt2);font-size:15px;margin-bottom:44px">Materi persiapan UTBK/SNBT berkualitas</p><div class="g3" id="vid-list"></div></div></div><footer><div class="wrap"><div class="fi" id="footer-vid"></div></div></footer></div>

<!-- ═══════════ GALLERY ═══════════ -->

<div class="page" id="pg-gallery"><div class="sec"><div class="wrap"><div class="sl">Dokumentasi</div><h2 style="font-family:Syne,sans-serif;font-weight:800;color:var(--txt);font-size:clamp(26px,4vw,44px);margin-bottom:10px">Galeri Kegiatan</h2><p style="color:var(--txt2);font-size:15px;margin-bottom:44px">Dokumentasi kegiatan belajar dan program</p><div class="g3" id="gal-list"></div></div></div><footer><div class="wrap"><div class="fi" id="footer-gal"></div></div></footer></div>

<!-- ═══════════ LULUSAN ═══════════ -->

<div class="page" id="pg-lulusan"><div class="sec"><div class="wrap"><div class="sl">Prestasi</div><h2 style="font-family:Syne,sans-serif;font-weight:800;color:var(--txt);font-size:clamp(26px,4vw,44px);margin-bottom:10px">Data Lulusan <span style="color:var(--gold2)">PTN</span></h2><p style="color:var(--txt2);font-size:15px;margin-bottom:44px">Bukti nyata komitmen Bimbel Attin</p><div class="g3" id="lul-list"></div></div></div><footer><div class="wrap"><div class="fi" id="footer-lul"></div></div></footer></div>

<!-- ═══════════ APPS ═══════════ -->

<div class="page" id="pg-apps">
  <div class="sec"><div class="wrap">
    <div class="sl">Platform Digital</div>
    <h2 style="font-family:Syne,sans-serif;font-weight:800;color:var(--txt);font-size:clamp(26px,4vw,44px);margin-bottom:10px">Aplikasi &amp; Tools</h2>
    <p style="color:var(--txt2);font-size:15px;margin-bottom:48px;line-height:1.7;max-width:560px">Akses konsultasi jurusan bertenaga AI, paket Try Out online, dan tools pembelajaran terbaik untuk mempersiapkan dirimu.</p>

```
<div class="sl" style="margin-bottom:18px">Tersedia Gratis</div>
<div class="g3" style="margin-bottom:56px" id="builtin-apps">

  <!-- Try Out Card -->
  <div class="app-card" onclick="goPage('tryout')">
    <div class="app-card-thumb" style="background:linear-gradient(135deg,#1a0a2e,#3b0764)">
      <div style="text-align:center;position:relative;z-index:1">
        <div style="font-size:52px;margin-bottom:8px">&#128221;</div>
        <div style="font-family:Syne,sans-serif;font-weight:700;font-size:14px;color:#fff">Try Out SNBT</div>
      </div>
    </div>
    <div class="app-card-body">
      <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:8px">
        <h3 style="font-family:Syne,sans-serif;font-weight:700;font-size:16px;color:var(--txt)">Try Out Online</h3>
        <span class="tag tp">UTBK</span>
      </div>
      <p style="font-size:13px;color:var(--txt2);line-height:1.6;margin-bottom:14px">Latihan soal UTBK/SNBT resmi dengan timer, pembahasan, dan skor analitik lengkap.</p>
      <div style="display:flex;gap:6px;flex-wrap:wrap">
        <span class="tag tb">Gratis</span><span class="tag tn">Tersedia</span>
      </div>
    </div>
  </div>
</div>

<!-- External apps added by admin -->
<div id="ext-apps-section" style="display:none">
  <div class="sl" style="margin-bottom:18px">Aplikasi Lainnya</div>
  <div class="g3" id="ext-apps-list"></div>
</div>
```

  </div></div>
  <footer><div class="wrap"><div class="fi" id="footer-apps"></div></div></footer>
</div>

<!-- ═══════════ KONSULTASI JURUSAN ═══════════ -->

<div class="page" id="pg-tryout">
  <div class="sec"><div class="wrap">
    <div style="display:flex;align-items:center;gap:12px;margin-bottom:8px">
      <button onclick="goPage('apps')" style="background:var(--bg3);border:1px solid var(--bdr);border-radius:9px;padding:7px 12px;cursor:pointer;font-family:inherit;font-size:13px;color:var(--txt2)">&#8592; Kembali</button>
      <div class="sl" style="margin-bottom:0">UTBK / SNBT</div>
    </div>
    <h2 style="font-family:Syne,sans-serif;font-weight:800;color:var(--txt);font-size:clamp(26px,4vw,44px);margin-bottom:10px">Try Out Online</h2>
    <p style="color:var(--txt2);font-size:15px;margin-bottom:40px;line-height:1.7;max-width:560px">Latihan soal simulasi UTBK/SNBT dengan timer, analisis skor, dan pembahasan lengkap.</p>
    <div id="to-content"></div>
  </div></div>
  <footer><div class="wrap"><div class="fi" id="footer-tryout"></div></div></footer>
</div>

<!-- ═══════════ DAFTAR ═══════════ -->

<div class="page" id="pg-daftar">
  <div class="sec"><div class="wrap">
    <div class="sl">Bergabung</div>
    <h2 style="font-family:Syne,sans-serif;font-weight:800;color:var(--txt);font-size:clamp(26px,4vw,44px);margin-bottom:10px">Form Pendaftaran</h2>
    <p style="color:var(--txt2);font-size:15px;margin-bottom:36px;line-height:1.7;max-width:560px">Isi formulir &#8212; notifikasi otomatis dikirim ke WhatsApp admin cabang yang kamu pilih.</p>
    <div style="max-width:760px">
      <div id="reg-done" style="display:none;background:var(--bg2);border:1px solid var(--bdr2);border-radius:20px;padding:52px 36px;text-align:center">
        <img class="lgo" src="" style="width:72px;height:72px;object-fit:contain;margin-bottom:16px;border-radius:50%;border:2px solid rgba(200,16,46,.2)" alt=""/>
        <h3 style="font-family:Syne,sans-serif;font-size:24px;font-weight:800;color:var(--txt);margin-bottom:10px">Pendaftaran Berhasil! &#127881;</h3>
        <p style="color:var(--txt2);font-size:15px;margin-bottom:8px;line-height:1.7">Notifikasi WhatsApp telah dikirim ke admin cabang.</p>
        <p id="reg-done-disc" style="color:var(--tg-c);font-size:14px;font-weight:600;margin-bottom:26px"></p>
        <button class="btn-r" onclick="resetReg()">Daftar Lagi</button>
      </div>
      <div id="reg-box" style="background:var(--bg2);border:1px solid var(--bdr2);border-radius:20px;padding:clamp(22px,4vw,40px)">
        <div id="reg-err" style="display:none;background:var(--tr-bg);border:1px solid var(--tr-br);border-radius:10px;padding:11px 15px;margin-bottom:16px;color:var(--tr-c);font-size:13px"></div>
        <div class="fg">
          <div><label class="lbl">Nama Lengkap *</label><input class="inp" id="rn" type="text" placeholder="Nama lengkap siswa"/></div>
          <div><label class="lbl">No. HP / WhatsApp *</label><input class="inp" id="rp" type="tel" placeholder="08xx-xxxx-xxxx"/></div>
          <div><label class="lbl">Email</label><input class="inp" id="re" type="email" placeholder="email@contoh.com"/></div>
          <div><label class="lbl">Asal Sekolah</label><input class="inp" id="rs" type="text" placeholder="Nama sekolah"/></div>
          <div><label class="lbl">Kelas</label><select class="inp" id="rg"><option value="">Pilih kelas...</option><option>Kelas 7</option><option>Kelas 8</option><option>Kelas 9</option><option>Kelas 10</option><option>Kelas 11</option><option>Kelas 12</option><option>Alumni</option></select></div>
          <div><label class="lbl">Program *</label><select class="inp" id="rpr"><option value="">Pilih program...</option><option>Program Reguler</option><option>Program Intensif</option></select></div>
          <div class="ff"><label class="lbl">Pilih Cabang *</label><select class="inp" id="rb" onchange="onBranchChange()"></select></div>
          <div class="ff">
            <label class="lbl">Kode Diskon <span style="font-weight:400;text-transform:none;letter-spacing:0;color:var(--txt3);font-size:10px">(opsional &#8212; dari tim marketing)</span></label>
            <input class="inp" id="rdisc" type="text" placeholder="Contoh: MARKETING10" oninput="checkDiscount()" style="text-transform:uppercase"/>
            <div id="disc-info" style="margin-top:9px;display:none"></div>
          </div>
          <div class="ff"><label class="lbl">Pesan</label><textarea class="inp" id="rm" placeholder="Informasi tambahan..."></textarea></div>
        </div>
        <div id="wa-info" style="display:none;margin-top:16px"></div>
        <button class="btn-r" style="margin-top:20px;width:100%;justify-content:center;padding:14px 0;font-size:15px" onclick="submitReg()">Kirim Pendaftaran &amp; Notifikasi Admin &#128172;</button>
      </div>
    </div>
  </div></div>
  <footer><div class="wrap"><div class="fi" id="footer-daf"></div></div></footer>
</div>
</div><!-- /site -->

<!-- ═══════════ LOGIN ═══════════ -->

<div id="login-pg" style="display:none;min-height:100vh;align-items:center;justify-content:center;padding:24px;position:relative;overflow:hidden">
  <div style="position:absolute;inset:0;background:radial-gradient(ellipse 60% 50% at 50% 50%,rgba(200,16,46,.07) 0%,transparent 60%)"></div>
  <div style="width:100%;max-width:440px;padding:clamp(28px,5vw,52px);border-radius:22px;background:var(--bg2);border:1px solid var(--bdr2);box-shadow:0 28px 90px var(--shad2);position:relative">
    <div style="text-align:center;margin-bottom:28px">
      <img class="lgo" src="" style="width:72px;height:72px;object-fit:contain;margin-bottom:14px;border-radius:50%;border:2px solid rgba(200,16,46,.2)" alt=""/>
      <h2 style="font-family:Syne,sans-serif;font-size:22px;font-weight:800;color:var(--txt);margin-bottom:6px">Login Admin</h2>
      <p style="font-size:13px;color:var(--txt3)">Super Admin atau Admin Cabang</p>
    </div>
    <div id="lerr" style="display:none;background:var(--tr-bg);border:1px solid var(--tr-br);border-radius:10px;padding:11px 14px;margin-bottom:14px;color:var(--tr-c);font-size:13px"></div>
    <div style="margin-bottom:12px"><label class="lbl">Username</label><input class="inp" id="luser" type="text" placeholder="admin atau username cabang" autocomplete="username"/></div>
    <div style="margin-bottom:16px"><label class="lbl">Password</label><input class="inp" id="lpw" type="password" placeholder="Masukkan password..." autocomplete="current-password" onkeydown="if(event.key==='Enter')doLogin()"/><div style="font-size:11px;color:var(--txt3);margin-top:6px">Super admin: <code style="color:var(--red);font-weight:700">admin / admin123</code><br><span style="font-size:10px;color:var(--txt3)">Akses dari semua perangkat &#8212; setup Cloud Storage di CMS</span></div></div>
    <button class="btn-r" style="width:100%;justify-content:center;padding:13px 0;font-size:15px;margin-bottom:10px" onclick="doLogin()">&#128274; Masuk ke CMS</button>
    <button class="btn-g" style="width:100%;justify-content:center;padding:12px 0;font-size:13px" onclick="closeLogin()">&#8592; Kembali ke Website</button>
    <div style="display:flex;justify-content:center;margin-top:16px"><button class="tbtn" onclick="toggleTheme()"><span class="ticon" id="tic-l">&#127769;</span><span id="tlbl-l">Terang</span></button></div>
  </div>
</div>

<!-- ═══════════ CMS ═══════════ -->

<div id="cms-pg" style="display:none">
  <div class="cms">
    <div class="cms-side">
      <div style="padding:18px 15px;border-bottom:1px solid var(--bdr);display:flex;align-items:center;gap:10px">
        <img class="lgo" src="" style="width:36px;height:36px;object-fit:contain;border-radius:50%;flex-shrink:0" alt=""/>
        <div><div style="font-family:Syne,sans-serif;font-weight:800;font-size:13px;color:var(--txt);line-height:1.2" id="cms-who">Admin</div><div style="font-size:9px;color:var(--txt3);letter-spacing:1.5px;text-transform:uppercase;margin-top:2px" id="cms-role">CMS</div></div>
      </div>
      <div style="flex:1;padding:10px 10px;display:flex;flex-direction:column;gap:2px;overflow-y:auto" id="cms-nav-items"></div>
      <div style="padding:10px 10px 16px;border-top:1px solid var(--bdr);display:flex;flex-direction:column;gap:3px">
        <div style="padding:8px 12px"><button class="tbtn" onclick="toggleTheme()"><span class="ticon" id="tic-c">&#127769;</span><span id="tlbl-c">Terang</span></button></div>
        <button class="cni" onclick="showSite()">&#8599; Lihat Website</button>
        <button class="cni" onclick="logoutCms()">&#128682; Keluar</button>
      </div>
    </div>
    <div class="cms-main">
      <div class="ctop"><span id="cms-title" style="font-family:Syne,sans-serif;font-weight:700;font-size:17px;color:var(--txt)">Dashboard</span><span style="font-size:12px;color:var(--txt3)" id="cms-sub"></span></div>
      <div class="cc" id="cms-content"></div>
    </div>
  </div>
</div>

<!-- MODAL -->

<div class="mo" id="modal" onclick="if(event.target===this)closeModal()">
  <div class="mb" id="modal-box">
    <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:18px">
      <h3 id="modal-title" style="font-family:Syne,sans-serif;font-size:18px;font-weight:800;color:var(--txt)"></h3>
      <button style="background:var(--bg3);border:1px solid var(--bdr);border-radius:8px;padding:7px 10px;cursor:pointer;color:var(--txt3);font-size:15px;line-height:1;font-family:inherit" onclick="closeModal()">&#10005;</button>
    </div>
    <div id="modal-body"></div>
  </div>
</div>

<!-- Try Out Active Screen (fullscreen overlay) -->

<div id="to-screen" style="display:none;position:fixed;inset:0;z-index:500;background:var(--bg);overflow-y:auto">
  <div style="max-width:860px;margin:0 auto;padding:24px">
    <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:24px;flex-wrap:wrap;gap:12px">
      <div>
        <div style="font-family:Syne,sans-serif;font-weight:800;font-size:18px;color:var(--txt)" id="to-name">Try Out</div>
        <div style="font-size:13px;color:var(--txt3);margin-top:3px" id="to-info"></div>
      </div>
      <div style="display:flex;gap:12px;align-items:center">
        <div style="background:var(--tr-bg);border:1px solid var(--tr-br);border-radius:10px;padding:8px 18px;font-family:Syne,sans-serif;font-weight:800;font-size:20px;color:var(--tr-c)" id="to-timer">90:00</div>
        <button onclick="submitTO()" class="btn-r btn-sm">Kumpulkan</button>
        <button onclick="cancelTO()" class="btn-g btn-sm">&#10005; Keluar</button>
      </div>
    </div>
    <div class="prog-bar" style="margin-bottom:24px"><div class="prog-fill" id="to-prog" style="width:0%"></div></div>
    <div id="to-questions"></div>
    <button onclick="submitTO()" class="btn-r" style="width:100%;justify-content:center;padding:14px;margin-top:20px;font-size:15px">&#9989; Kumpulkan &amp; Lihat Skor</button>
  </div>
</div>

<!-- Try Out Result Screen -->

<div id="to-result" style="display:none;position:fixed;inset:0;z-index:500;background:var(--bg);overflow-y:auto">
  <div style="max-width:700px;margin:0 auto;padding:48px 24px;text-align:center" id="to-result-content"></div>
</div>

<div class="toast" id="toast"></div>

<script>
var LOGO='data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAA0JCgsKCA0LCgsODg0PEyAVExISEyccHhcgLikxMC4pLSwzOko+MzZGNywtQFdBRkxOUlNSMj5aYVpQYEpRUk//2wBDAQ4ODhMREyYVFSZPNS01T09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT0//wAARCABQAFADASIAAhEBAxEB/8QAGwAAAwADAQEAAAAAAAAAAAAAAAUGAwQHAQL/xAA6EAABAwMCBAQCBwYHAAAAAAABAgMEAAUREiEGMUFREyJhcRSRFiMydIGzwRVCVJTR0jNDZJOisfH/xAAbAQACAwEBAQAAAAAAAAAAAAADBAIFBgEAB//EAC0RAAEDAgIIBgMBAAAAAAAAAAEAAhEDBBIxBRQVMkFRYaEhIjRxgeEjwdHw/9oADAMBAAIRAxEAPwCfoop5Z7VGmxWlLaddfddWhIS8G0gJSD1B71UsYXmAvoFzctt2Y3BI6Ksvoqj+Bd/nU/2UDhNCzo+GLWrYuKlBekdwkJGTRtWekdtW3Xt/VP2Szv3eVoRlDKD9Y7jZI7Dua8vVnkWiV4bnnZVu06BsofofSukRIse3xEsR0htpsZ5/Mk96JkSPcIio8hAW0sfLsQe9G1UYI4qr25U1jHHk5fv3XJqKslcJoSSn4VTmNgtEoICh30lJwfxrz6KI/gXf55P9lB1V6s9t2/I9v6o6inV7tkeDHy20606h4NrCng4CCjUMEAUloL2Fhgqwt7htwzG3JFVvCX2IP3h78sVJVX8HpU4mOEAqDLri3D0SCkJAz3PbtRbbfSOmfT/P6KpLw7LZty1QEKXIKkhISnUee5x7VO44rc30yh+KE0/vLU96MhFueSyvX51qXp8uO/vU+9CnxW1Spl3StpvBWhp9RUrsB706/NZy1IDOE9RJWGdLu7UNcWat9Tj3NBTnSj3Hf/oetfUOZeX4bceCt4OMDSUaQCpPQ5Pbl8q1GLtcXZzeZj4St1OUpWQACeWO1Nbj+22pc2ahx0RGHiQhbhAUn0HUUMGfESnHtLIY4NBPj85LGDxW35tMlXp5FVR2p2S9bmlzUKQ/uFhSdJyD2qbag3B9tMiJeUhtzdtLr6goDsfUcqobO3OahlFxdS64FnStKtWU7dfnRGZpO6ILOE9BBUvxf/n/AHtP5QqVqq4z1NurQtCkh15Lra8eVQCNJGe4I5djUrSVxvrS6HM2wTOx2d27y/DSdDSN3F9h/Wujw4jEKMiPGQENo5DqfU+tcut85+3SkyIysKHMdFDsa6RZ7rHu0UOsnCxsts80mj2pZEDNVOnGV8Yc7c4faRcaOkyIrIJwEKUR7nH6UqkRnEMtxmPCUkedxYdR51ke/IDYfj3ra4qWXb6WwfsIQge53/WtOfGispaXGWlxIJQ4ArOSOv41CpUAfB4rtsMNKmJ6r5jRXkSmVK8MJS4kk+MjYZHrTjxFq4gmOuSEKiupdCSX0lKgUnSMZpRIbiImsobby2UpKvrM7nnv0xXoYiKuEhvZLTaF6Dr5kct/WoCuAJjqpvbj8SeHL7XrEZxcVcd/wk4GtpRdR5VY3HPkRt7gU64Kdz8W0ScYSsD5ik8CLCeYaMhzQ4pas+bAIAG3p7+lbnCDmi7rb6ONEfIg1OlUDnwBkh3IxUagVbOhsT4q40pGttfzB7jsa5terS9aJnguHW2rdpwfvD9DXQbxdmLTFLrp1OK+w2Oaj/Sub3Cc/cJSpElepSuQ6JHYVO6LIg5rug2V8Zc3c4/S1qreEgB8EsDCi88gkdU6AcHvvUlVbwn/AIcL7w9+WKBbb6s9M+n/ANyKYuQLTOvckPuyHXy5hSANCU4T36jbnmszlnsaFqbMVRUnQDpWo/aOB1/8rQnW6a9PmFMZ5TS3DgkjBBz9n07+tYUWmckpCYjownGc9NWcc++9O/CzkyB+TumEjhi2KWENSHWXFglI1BYOOfP371hesNntzTbk9+Q4FrCARsM+w5Uu+EfDjkNMV1TwbSAkYOkBWrvnqPTfNbyrdNFt8NMZ7xDL14BHIpxk5/dzzr0DkpYniAahj3TE2Gyh5THw51hGs/WK5Zxzz3FFvskJiUxPhuPI8ufDWc5BHLfcHekyrdcG28rjOHDmpSjjy4USVDfl1z65rbskKQq4MyXI60s4C0r6K8mAee/Ou+E5KDsQafyd0v4wSCt9wjKhIQgE9E+HnHzOalqquL+T/wB7T+UKlaQuN9abRHpgim1turUOIhpQkJcbdU4lxlSRzABG4PalNFDY8sMhO3Fuyu3C/JUf0k/1Fy/3G/7aDxM4jzNSJxWDkB1SFJPoQAKnKKJrD0lsi25Lp9nuUS6s/EspQl7AS4MDUPTPavq8XaPaYpddOpxX2GxzUf6Vze3z5FulJkRlYUOY6KHY0XCc/cJSpElepSuQ6JHYUfWhg6qt2EdYifJ39k5PEq3AS89O1KzqS2pAT7AEHagcSYAAfuQAGAA43t/xqdooOsvVlsi26ppdLo3NjBtIkKcLviLW8pJJ8unGwFK6KKE95eZKdoUGUGYGZL//2Q==';

/* ═══════════ DEFAULT DATA ═══════════ */
var DEF = {
  videos:[
    {id:1,title:"Teknik Cepat Aljabar UTBK",subject:"Matematika",dataUrl:"",desc:"Kuasai soal aljabar dalam 30 menit",level:"SMA/Kelas 12",date:"2024-01-15"},
    {id:2,title:"Strategi Jitu TPS SNBT",subject:"TPS",dataUrl:"",desc:"Teknik TPS untuk skor maksimal",level:"Kelas 12",date:"2024-02-01"}
  ],
  photos:[
    {id:1,title:"KBM Matematika Padang",caption:"Kelas aktif cabang Padang 1",cat:"KBM",dataUrl:"https://picsum.photos/seed/ba1/600/400",date:"2024-01-10"},
    {id:2,title:"Try Out UTBK Serentak",caption:"TO bersama 11 cabang",cat:"Try Out",dataUrl:"https://picsum.photos/seed/ba2/600/400",date:"2024-03-05"},
    {id:3,title:"Workshop Belajar Efektif",caption:"Workshop strategi belajar",cat:"Workshop",dataUrl:"https://picsum.photos/seed/ba3/600/400",date:"2024-02-20"},
    {id:4,title:"Kelas Fisika Interaktif",caption:"Demonstrasi fisika interaktif",cat:"KBM",dataUrl:"https://picsum.photos/seed/ba4/600/400",date:"2024-03-10"}
  ],
  grads:[
    {id:1,title:"Angkatan SNBT 2024",year:"2024",caption:"75 siswa tembus PTN favorit nasional",dataUrl:"https://picsum.photos/seed/bg1/600/400",count:"75",univ:"UI, ITB, UGM, UNAND",date:"2024-06-15"},
    {id:2,title:"Angkatan SNBT 2023",year:"2023",caption:"62 siswa meraih kursi di PTN terbaik",dataUrl:"https://picsum.photos/seed/bg2/600/400",count:"62",univ:"UI, ITB, UGM, UNAND, UNDIP",date:"2023-06-15"},
    {id:3,title:"Angkatan UTBK 2022",year:"2022",caption:"48 siswa lolos UTBK jalur reguler",dataUrl:"https://picsum.photos/seed/bg3/600/400",count:"48",univ:"UNAND, UNP, UI, UGM",date:"2022-06-15"}
  ],
  progs:{
    reguler:{title:"Program Reguler",tagline:"Fondasi Kuat, Prestasi Optimal",desc:"Program terstruktur SMP & SMA mengikuti Kurikulum Merdeka dengan metode inovatif.",features:["Kelas kecil maks. 15 siswa","Pengajar berpengalaman & tersertifikasi","Modul eksklusif Bimbel Attin","Latihan UTBK/SNBT berkala","Evaluasi & rapor bulanan","Konsultasi akademik gratis"],subjects:"Matematika, Fisika, Kimia, Biologi, B.Indonesia, B.Inggris, Ekonomi",schedule:"Senin-Jumat, 2 sesi/minggu",duration:"10 bulan (Agustus-Mei)",levels:"SMP & SMA (Kelas 7-12)",price:"Hubungi cabang terdekat"},
    intensif:{title:"Program Intensif",tagline:"Akselerasi Menuju PTN Impian",desc:"Program intensif UTBK/SNBT berbasis data dengan latihan terarah dan analisis performa.",features:["Fokus materi UTBK/SNBT terkini","Try Out mingguan simulasi ujian","Pembahasan intensif soal harian","Strategi manajemen waktu ujian","Analisis skor & rapor perkembangan","Mentoring alumni PTN unggulan"],subjects:"TPS, Literasi B.Indonesia, Literasi B.Inggris, Penalaran Matematika",schedule:"Senin-Sabtu, sesi full-day",duration:"3 bulan (Februari-April)",levels:"Kelas 12 & Alumni",price:"Hubungi cabang terdekat"}
  },
  branches:[
    {id:1,name:"Padang 1 - Lolong",city:"Padang",address:"Jl. Lolong No. 1",phone:"6281200000001",province:"Sumatera Barat",hours:"Senin-Sabtu 08.00-21.00",user:"padang1",pass:"cabang1"},
    {id:2,name:"Padang 2 - Gunung Pangilun",city:"Padang",address:"Jl. Gunung Pangilun No. 5",phone:"6281200000002",province:"Sumatera Barat",hours:"Senin-Sabtu 08.00-21.00",user:"padang2",pass:"cabang2"},
    {id:3,name:"Lubuk Alung",city:"Lubuk Alung",address:"Jl. Raya Padang-Bukittinggi",phone:"6281200000003",province:"Sumatera Barat",hours:"Senin-Sabtu 08.00-21.00",user:"lubukalung",pass:"cabang3"},
    {id:4,name:"Pariaman",city:"Pariaman",address:"Jl. Sudirman No. 12",phone:"6281200000004",province:"Sumatera Barat",hours:"Senin-Sabtu 08.00-21.00",user:"pariaman",pass:"cabang4"},
    {id:5,name:"Lubuk Sikaping",city:"Lubuk Sikaping",address:"Jl. Lintas Sumatera",phone:"6281200000005",province:"Sumatera Barat",hours:"Senin-Sabtu 08.00-21.00",user:"lbksikaping",pass:"cabang5"},
    {id:6,name:"Lubuk Basung",city:"Lubuk Basung",address:"Jl. Diponegoro No. 8",phone:"6281200000006",province:"Sumatera Barat",hours:"Senin-Sabtu 08.00-21.00",user:"lbkbasung",pass:"cabang6"},
    {id:7,name:"Padang Panjang",city:"Padang Panjang",address:"Jl. Soekarno Hatta No. 3",phone:"6281200000007",province:"Sumatera Barat",hours:"Senin-Sabtu 08.00-21.00",user:"pdgpanjang",pass:"cabang7"},
    {id:8,name:"Bukittinggi",city:"Bukittinggi",address:"Jl. A. Yani No. 15",phone:"6281200000008",province:"Sumatera Barat",hours:"Senin-Sabtu 08.00-21.00",user:"bukittinggi",pass:"cabang8"},
    {id:9,name:"Batusangkar",city:"Batusangkar",address:"Jl. Sultan Alam No. 7",phone:"6281200000009",province:"Sumatera Barat",hours:"Senin-Sabtu 08.00-21.00",user:"batusangkar",pass:"cabang9"},
    {id:10,name:"Payakumbuh",city:"Payakumbuh",address:"Jl. Soekarno Hatta No. 22",phone:"6281200000010",province:"Sumatera Barat",hours:"Senin-Sabtu 08.00-21.00",user:"payakumbuh",pass:"cabang10"},
    {id:11,name:"Bengkulu",city:"Bengkulu",address:"Jl. Ahmad Yani No. 10",phone:"6281200000011",province:"Bengkulu",hours:"Senin-Sabtu 08.00-21.00",user:"bengkulu",pass:"cabang11"}
  ],
  discounts:[
    {id:1,code:"MARKETING10",pct:10,desc:"Diskon Tim Marketing",active:true,used:0},
    {id:2,code:"REFERRAL15",pct:15,desc:"Diskon Referral",active:true,used:0},
    {id:3,code:"EARLYBIRD20",pct:20,desc:"Diskon Early Bird",active:true,used:0}
  ],
  regs:[],
  extApps:[],
  tryouts:[
    {
      id:1,title:"TPS \u2014 Penalaran Umum",desc:"Simulasi soal TPS sub-materi penalaran umum",cat:"TPS",duration:45,questions:[
        {q:"Jika semua dokter adalah orang pintar, dan Budi adalah dokter, maka...",opts:["Budi adalah orang pintar","Budi belum tentu orang pintar","Budi bukan orang pintar","Tidak bisa disimpulkan"],ans:0,exp:"Premis mayor: Semua dokter = orang pintar. Premis minor: Budi = dokter. Konklusi: Budi = orang pintar."},
        {q:"Urutan angka: 2, 4, 8, 16, 32, ... Angka berikutnya adalah...",opts:["48","56","64","72"],ans:2,exp:"Pola: setiap angka dikali 2. 32 x 2 = 64."},
        {q:"Kata LAMPU berhubungan dengan TERANG, seperti KOMPOR berhubungan dengan...",opts:["Api","Dapur","Panas","Memasak"],ans:2,exp:"LAMPU menghasilkan TERANG. KOMPOR menghasilkan PANAS."},
        {q:"Dalam 1 jam, mesin A bisa membuat 120 produk. Mesin B bisa membuat 80 produk. Berapa produk yang dihasilkan keduanya dalam 3 jam?",opts:["480","540","600","720"],ans:2,exp:"A + B per jam = 120 + 80 = 200 produk. 3 jam = 200 x 3 = 600."},
        {q:"Jika P > Q dan Q > R, maka...",opts:["R > P","P > R","P = R","Tidak dapat ditentukan"],ans:1,exp:"Dari P > Q dan Q > R, transitif: P > R."}
      ]
    },
    {
      id:2,title:"Matematika Dasar SNBT",desc:"Soal matematika dasar untuk persiapan SNBT",cat:"Matematika",duration:40,questions:[
        {q:"Nilai dari 2\u00b3 + 3\u00b2 \u2212 4 adalah...",opts:["13","15","17","21"],ans:0,exp:"2\u00b3 = 8, 3\u00b2 = 9, jadi 8 + 9 \u2212 4 = 13."},
        {q:"Jika f(x) = 2x + 3, maka f(5) = ...",opts:["10","12","13","15"],ans:2,exp:"f(5) = 2(5) + 3 = 10 + 3 = 13."},
        {q:"Suatu barisan aritmatika: 3, 7, 11, 15, ... Suku ke-10 adalah...",opts:["39","40","41","43"],ans:0,exp:"a = 3, b = 4. Suku ke-10 = 3 + (10\u22121)\u00d74 = 3 + 36 = 39."},
        {q:"Luas lingkaran dengan diameter 14 cm adalah... (pi = 22/7)",opts:["154 cm\u00b2","176 cm\u00b2","144 cm\u00b2","132 cm\u00b2"],ans:0,exp:"r = 7. Luas = \u03c0r\u00b2 = (22/7) \u00d7 49 = 154 cm\u00b2."},
        {q:"Persamaan 2x + 4 = 10 memiliki solusi x = ...",opts:["2","3","4","5"],ans:1,exp:"2x = 10 \u2212 4 = 6. x = 3."}
      ]
    },
    {
      id:3,title:"Literasi Bahasa Indonesia",desc:"Soal literasi dan pemahaman bacaan Bahasa Indonesia",cat:"Literasi",duration:50,questions:[
        {q:"Kalimat utama sebuah paragraf biasanya terletak di...",opts:["Awal paragraf saja","Akhir paragraf saja","Awal atau akhir paragraf","Tengah paragraf"],ans:2,exp:"Kalimat utama (topik) bisa berada di awal (deduktif) atau akhir (induktif) paragraf."},
        {q:"Sinonim dari kata 'bijaksana' adalah...",opts:["Bodoh","Arif","Egois","Sombong"],ans:1,exp:"Bijaksana = arif = menggunakan pertimbangan yang baik."},
        {q:"Antonim dari kata 'transparan' adalah...",opts:["Bening","Jelas","Samar","Kabur"],ans:3,exp:"Transparan = jelas/tidak tersembunyi. Antonimnya = kabur/tersembunyi."},
        {q:"Kalimat yang menggunakan ejaan yang benar adalah...",opts:["saya pergi ke-Jakarta","Saya pergi ke Jakarta","saya pergi keJakarta","Saya pergi Ke jakarta"],ans:1,exp:"'ke Jakarta' ditulis terpisah karena ke- adalah preposisi, bukan awalan."},
        {q:"Paragraf yang dimulai dari pernyataan khusus menuju pernyataan umum disebut paragraf...",opts:["Deduktif","Induktif","Campuran","Deskriptif"],ans:1,exp:"Induktif = dimulai dari fakta/pernyataan khusus, diakhiri kesimpulan umum."}
      ]
    }
  ]
};

/* ═══════════ STATE ═══════════ */
var DB = JSON.parse(JSON.stringify(DEF));
var isDark=true, curPage='home', curCms='dashboard', loggedUser=null;
var _upUid='', _afUrl='';
var toState = {active:false, id:null, answers:{}, timer:null, elapsed:0};

/* ═══════════ STORAGE ═══════════ */
function cpDef(k){return JSON.parse(JSON.stringify(DEF[k]));}

/* ═══ CLOUD CONFIG ════════════════════════════════════════════
   Data disimpan di JSONBin.io (gratis, akses dari semua perangkat)
   Setup: Login admin → Pengaturan → Konfigurasi Cloud Storage
   ════════════════════════════════════════════════════════════ */
function getCfg(){
  try{return JSON.parse(localStorage.getItem('bba_cloud')||'{}');}catch(e){return {};}
}
function saveCfg(cfg){
  try{localStorage.setItem('bba_cloud',JSON.stringify(cfg));}catch(e){}
}
function hasCloud(){var c=getCfg();return !!(c.binId&&c.apiKey);}

/* Save: cloud first, localStorage as backup */
function sv(k,v){
  try{localStorage.setItem('bba_'+k,JSON.stringify(v));}catch(e){}
  if(hasCloud()) cloudSave();
}

/* Full cloud save - write entire DB to one bin */
function cloudSave(){
  var cfg=getCfg();if(!cfg.binId||!cfg.apiKey)return;
  var payload={};
  Object.keys(DEF).forEach(function(k){payload[k]=DB[k];});
  fetch('https://api.jsonbin.io/v3/b/'+cfg.binId,{
    method:'PUT',
    headers:{'Content-Type':'application/json','X-Master-Key':cfg.apiKey,'X-Bin-Versioning':'false'},
    body:JSON.stringify(payload)
  }).catch(function(){});
}

/* Load: try cloud first, fallback to localStorage */
function loadData(){
  var cfg=getCfg();
  try{
    var raw=localStorage.getItem('bba_drk');
    if(raw)isDark=(raw==='1');
  }catch(e){}

  if(cfg.binId&&cfg.apiKey){
    // Load from cloud
    fetch('https://api.jsonbin.io/v3/b/'+cfg.binId+'/latest',{
      headers:{'X-Master-Key':cfg.apiKey,'X-Bin-Meta':'false'}
    })
    .then(function(r){return r.json();})
    .then(function(res){
      if(res&&typeof res==='object'){
        Object.keys(DEF).forEach(function(k){
          if(res[k]!==undefined) DB[k]=res[k];
          else DB[k]=cpDef(k);
          // Also update localStorage cache
          try{localStorage.setItem('bba_'+k,JSON.stringify(DB[k]));}catch(e){}
        });
      }
      initApp();
    })
    .catch(function(){
      // Cloud failed → use localStorage
      loadFromLocal();
    });
  } else {
    loadFromLocal();
  }
}

function loadFromLocal(){
  Object.keys(DEF).forEach(function(k){
    try{
      var raw=localStorage.getItem('bba_'+k);
      DB[k]=raw?JSON.parse(raw):cpDef(k);
    }catch(e){DB[k]=cpDef(k);}
  });
  initApp();
}

/* Toggle theme save */
function saveTheme(){
  saveTheme();
}
function initApp(){
  applyTheme();setLogos();
  setTimeout(function(){
    var ls=document.getElementById('loading');
    ls.classList.add('fade');
    setTimeout(function(){ls.style.display='none';},500);
    document.getElementById('site').style.display='block';
  },600);
  renderPage('home');
  renderTOList();
}

/* ═══════════ THEME ═══════════ */
function applyTheme(){
  document.body.classList.toggle('light',!isDark);
  var m='\uD83C\uDF19',s='\u2600\uFE0F';
  document.querySelectorAll('.ticon').forEach(function(e){e.textContent=isDark?m:s;});
  document.querySelectorAll('[id^="tlbl"]').forEach(function(e){e.textContent=isDark?'Terang':'Gelap';});
}
function toggleTheme(){isDark=!isDark;applyTheme();saveTheme();}
function setLogos(){document.querySelectorAll('img.lgo').forEach(function(e){e.src=LOGO;});}

/* ═══════════ UTILS ═══════════ */
function h(s){return String(s||'').replace(/&/g,'&amp;').replace(/"/g,'&quot;');}
function today(){return new Date().toISOString().split('T')[0];}
function toast(msg,t){
  var el=document.getElementById('toast');el.textContent=(t==='err'?'\u2717 ':'\u2713 ')+msg;
  el.className='toast '+(t||'ok')+' show';setTimeout(function(){el.classList.remove('show');},3500);
}
function ft(){return '\u003cdiv style="display:flex;align-items:center;gap:10px"\u003e\u003cimg class="lgo" src="'+LOGO+'" style="width:34px;height:34px;object-fit:contain;border-radius:50%"/\u003e\u003cspan style="font-family:Syne,sans-serif;font-weight:700;font-size:14px;color:var(--txt)"\u003eBimbel Attin Indonesia\u003c/span\u003e\u003c/div\u003e\u003cspan style="font-size:12px;color:var(--txt3)"\u003e\u00a9 2024 Bimbel Attin. All rights reserved.\u003c/span\u003e';}
function tR(t){return '\u003cspan class="tag tr"\u003e'+h(t)+'\u003c/span\u003e';}
function tG(t){return '\u003cspan class="tag tg"\u003e'+h(t)+'\u003c/span\u003e';}
function tN(t){return '\u003cspan class="tag tn"\u003e'+h(t)+'\u003c/span\u003e';}
function tB(t){return '\u003cspan class="tag tb"\u003e'+h(t)+'\u003c/span\u003e';}
function tP(t){return '\u003cspan class="tag tp"\u003e'+h(t)+'\u003c/span\u003e';}
function tai(t){return '\u003cspan class="tag tai"\u003e'+h(t)+'\u003c/span\u003e';}
function stag(s){if(s==='Disetujui')return '\u003cspan class="tag tn"\u003e\u2713 Disetujui\u003c/span\u003e';if(s==='Ditolak')return '\u003cspan class="tag tr"\u003e\u2717 Ditolak\u003c/span\u003e';return '\u003cspan class="tag tp"\u003e\u23f3 Baru\u003c/span\u003e';}
function fmtPhone(ph){return ph?String(ph).replace(/^62/,'0'):'-';}
function pad2(n){return String(n).length===1?'0'+String(n):String(n);}

/* ═══════════ NAVIGATION ═══════════ */
function goPage(p){
  document.querySelectorAll('.page').forEach(function(e){e.classList.remove('active');});
  var el=document.getElementById('pg-'+p);if(el){el.classList.add('active');renderPage(p);}
  document.querySelectorAll('[data-pg]').forEach(function(e){e.classList.toggle('on',e.dataset.pg===p);});
  curPage=p;window.scrollTo({top:0,behavior:'smooth'});
}
function closeMnav(){document.getElementById('mnav').classList.remove('open');}
function openLogin(){document.getElementById('site').style.display='none';document.getElementById('login-pg').style.display='flex';document.getElementById('luser').value='';document.getElementById('lpw').value='';document.getElementById('lerr').style.display='none';setLogos();}
function closeLogin(){document.getElementById('site').style.display='block';document.getElementById('login-pg').style.display='none';}
function doLogin(){
  var user=document.getElementById('luser').value.trim(),pass=document.getElementById('lpw').value;
  if(user==='admin'&&pass==='admin123'){loggedUser='super';enterCms();return;}
  var found=null;DB.branches.forEach(function(b){if(b.user===user&&b.pass===pass)found=b;});
  if(found){loggedUser=found.id;enterCms();return;}
  var e=document.getElementById('lerr');e.textContent='Username atau password salah.';e.style.display='block';
}
function enterCms(){document.getElementById('login-pg').style.display='none';document.getElementById('cms-pg').style.display='block';setLogos();buildNav();goCms(loggedUser==='super'?'dashboard':'regs');}
function logoutCms(){loggedUser=null;document.getElementById('cms-pg').style.display='none';document.getElementById('site').style.display='block';}
function showSite(){document.getElementById('cms-pg').style.display='none';document.getElementById('site').style.display='block';}
function buildNav(){
  var isS=(loggedUser==='super');
  var br=isS?null:DB.branches.find(function(b){return b.id===loggedUser;});
  document.getElementById('cms-who').textContent=isS?'Super Admin':(br?br.name:'Admin Cabang');
  document.getElementById('cms-role').textContent=isS?'Semua Cabang':(br?br.city:'');
  document.getElementById('cms-sub').textContent=isS?'Super Admin \u2022 Full Access':(br?'Admin Cabang: '+br.name:'');
  var items;
  if(isS){
    items='<div class="cni-section">Konten</div>'
      +nav('dashboard','\uD83D\uDCCA','Dashboard')
      +nav('regs','\uD83D\uDCCB','Pendaftaran')
      +'<div class="cni-section">Media</div>'
      +nav('videos','\uD83C\uDFAC','Video')
      +nav('photos','\uD83D\uDCF7','Foto')
      +nav('grads','\uD83C\uDF93','Lulusan')
      +'<div class="cni-section">Aplikasi</div>'
      +nav('tryouts','\uD83D\uDCDD','Kelola Try Out')
      +nav('extapps','\uD83D\uDE80','Kelola Aplikasi')
      +'<div class="cni-section">Pengaturan</div>'
      +nav('progs','\uD83D\uDCDA','Program')
      +nav('branches','\uD83D\uDCCD','Cabang')
      +nav('discounts','\uD83C\uDFF7\uFE0F','Diskon')+nav('cloud','\u2601\uFE0F','Cloud Storage');
  } else {
    items=nav('regs','\uD83D\uDCCB','Pendaftaran')+nav('approve','\u2705','Approve/Tolak');
  }
  document.getElementById('cms-nav-items').innerHTML=items;
}
function nav(s,ic,lbl){return '\u003cbutton class="cni" data-v="'+s+'" onclick="goCms(\''+s+'\')"\u003e'+ic+' '+lbl+'\u003c/button\u003e';}
function goCms(s){
  document.querySelectorAll('[data-v]').forEach(function(e){e.classList.toggle('on',e.dataset.v===s);});
  var ttl={dashboard:'Dashboard',regs:'Pendaftaran',videos:'Video',photos:'Foto',grads:'Lulusan',progs:'Program',branches:'Cabang',discounts:'Diskon',tryouts:'Kelola Try Out',extapps:'Kelola Aplikasi',approve:'Approve Pendaftaran',cloud:'Cloud Storage'};
  document.getElementById('cms-title').textContent=ttl[s]||s;
  curCms=s;renderCms(s);
}

/* ═══════════ DISCOUNT ═══════════ */
function findDisc(code){if(!code)return null;var u=String(code).toUpperCase();return DB.discounts.find(function(d){return d.code===u&&d.active;})||null;}
function checkDiscount(){
  var code=document.getElementById('rdisc').value.toUpperCase();var info=document.getElementById('disc-info');
  if(!code){info.style.display='none';return;}
  var d=findDisc(code);info.style.display='block';
  info.innerHTML=d?'\u003cdiv class="dok"\u003e\uD83C\uDF89 Kode valid! Diskon \u003cstrong\u003e'+d.pct+'%\u003c/strong\u003e \u2014 '+h(d.desc)+'\u003c/div\u003e':'\u003cdiv class="dok bad"\u003e\u2717 Kode tidak valid\u003c/div\u003e';
}
function onBranchChange(){
  var val=document.getElementById('rb').value,info=document.getElementById('wa-info');
  if(!val){info.style.display='none';return;}
  var b=DB.branches.find(function(x){return(x.name+' - '+x.city)===val;});
  info.style.display=b?'block':'none';
  if(b)info.innerHTML='\u003cdiv style="background:var(--tn-bg);border:1px solid var(--tn-br);border-radius:11px;padding:11px 15px;font-size:13px;color:var(--tn-c);display:flex;align-items:center;gap:9px"\u003e\uD83D\uDCF2 Notifikasi ke WA Admin \u003cstrong\u003e'+h(b.name)+'\u003c/strong\u003e\u003c/div\u003e';
}

/* ═══════════ REGISTRATION ═══════════ */
function buildWaMsg(reg,branch,disc){
  var lines=['*\uD83D\uDCDA PENDAFTARAN BARU - Bimbel Attin*','---','*Nama*    : '+reg.name,'*HP/WA*   : '+reg.phone,'*Email*   : '+(reg.email||'-'),'*Sekolah* : '+(reg.school||'-'),'*Kelas*   : '+(reg.grade||'-'),'*Program* : '+reg.program,'*Cabang*  : '+branch.name,'*Tanggal* : '+reg.date];
  if(disc)lines.push('*Diskon*  : '+disc.code+' ('+disc.pct+'%) \u2014 '+disc.desc);
  if(reg.msg)lines.push('*Pesan*   : '+reg.msg);
  lines.push('---','_Mohon segera hubungi calon siswa._');
  return encodeURIComponent(lines.join('\n'));
}
function submitReg(){
  var n=document.getElementById('rn').value.trim(),p=document.getElementById('rp').value.trim(),pr=document.getElementById('rpr').value,bv=document.getElementById('rb').value;
  var ee=document.getElementById('reg-err');
  if(!n||!p||!pr||!bv){ee.textContent='Harap lengkapi semua field yang bertanda *';ee.style.display='block';return;}
  ee.style.display='none';
  var disc=findDisc(document.getElementById('rdisc').value);
  var branch=DB.branches.find(function(b){return(b.name+' - '+b.city)===bv;});
  var entry={id:Date.now(),name:n,phone:p,email:document.getElementById('re').value,school:document.getElementById('rs').value,grade:document.getElementById('rg').value,program:pr,branch:bv,branchId:branch?branch.id:0,msg:document.getElementById('rm').value,date:today(),status:'Baru',discCode:disc?disc.code:'',discPct:disc?disc.pct:0};
  DB.regs.push(entry);sv('regs',DB.regs);
  if(disc){DB.discounts.forEach(function(d){if(d.code===disc.code)d.used=(d.used||0)+1;});sv('discounts',DB.discounts);}
  document.getElementById('reg-box').style.display='none';document.getElementById('reg-done').style.display='block';
  document.getElementById('reg-done-disc').textContent=disc?'\uD83C\uDF89 Diskon '+disc.pct+'% berhasil diterapkan!':'';
  setLogos();
  if(branch&&branch.phone){var msg=buildWaMsg(entry,branch,disc);setTimeout(function(){window.open('https://wa.me/'+branch.phone+'?text='+msg,'_blank');},700);}
}
function resetReg(){
  document.getElementById('reg-done').style.display='none';document.getElementById('reg-box').style.display='block';
  ['rn','rp','re','rs','rm','rdisc'].forEach(function(id){var e=document.getElementById(id);if(e)e.value='';});
  ['rg','rpr','rb'].forEach(function(id){document.getElementById(id).value='';});
  document.getElementById('disc-info').style.display='none';document.getElementById('wa-info').style.display='none';
}

/* ═══════════ FILE UPLOAD ═══════════ */
function mkUA(uid,accept){
  return '\u003cdiv class="uarea" id="ua-'+uid+'" onclick="trigUA(\''+uid+'\',\''+accept+'\')" ondragover="event.preventDefault();this.classList.add(\'drag\')" ondragleave="this.classList.remove(\'drag\')" ondrop="event.preventDefault();this.classList.remove(\'drag\');dropF(event,\''+uid+'\')"\u003e\u003cdiv style="font-size:30px;margin-bottom:9px"\u003e\uD83D\uDCC2\u003c/div\u003e\u003cdiv style="font-weight:600;color:var(--txt);margin-bottom:4px;font-size:14px"\u003eKlik atau seret file ke sini\u003c/div\u003e\u003cdiv style="font-size:12px;color:var(--txt3)"\u003e'+accept+'\u003c/div\u003e\u003c/div\u003e\u003cdiv class="pvgrid" id="pv-'+uid+'"\u003e\u003c/div\u003e';
}
function trigUA(uid,accept){_upUid=uid;var inp=document.getElementById('_gfi');inp.accept=accept||'*/*';inp.value='';inp.click();}
function _gfc(e){if(e.target.files&&e.target.files.length)doFiles(Array.from(e.target.files),_upUid);}
function dropF(e,uid){doFiles(Array.from(e.dataTransfer.files),uid);}
function doFiles(files,uid){
  var pv=document.getElementById('pv-'+uid);if(!pv)return;
  files.forEach(function(f){
    var rd=new FileReader();rd.onload=function(ev){
      var url=ev.target.result,isV=f.type.indexOf('video')===0;
      var d=document.createElement('div');d.className='pvitem';d.dataset.url=url;
      d.innerHTML=(isV?'\u003cvideo src="'+url+'" muted playsinline controls\u003e\u003c/video\u003e':'\u003cimg src="'+url+'" alt="preview"/\u003e')+'\u003cbutton class="pvrm" onclick="this.parentNode.remove()"\u003e\u00d7\u003c/button\u003e';
      pv.appendChild(d);
    };rd.readAsDataURL(f);
  });
}
function getUrls(uid){var r=[];document.querySelectorAll('#pv-'+uid+' .pvitem').forEach(function(el){r.push(el.dataset.url);});return r;}

/* ═══════════ APP FRAME ═══════════ */
function openApp(app){
  if(!app.url){toast('URL aplikasi tidak tersedia','err');return;}
  _afUrl=app.url;
  document.getElementById('afTitle').textContent=app.title||'Aplikasi';
  document.getElementById('afUrl').textContent=app.url;
  document.getElementById('afIcon').src=app.icon||LOGO;
  document.getElementById('afIcon').onerror=function(){this.src=LOGO;};
  document.getElementById('appIframe').src=app.url;
  document.getElementById('appFrame').classList.add('open');
}
function closeAppFrame(){document.getElementById('appFrame').classList.remove('open');document.getElementById('appIframe').src='';}
function openAppNewTab(){if(_afUrl)window.open(_afUrl,'_blank');}

/* ═══════════ AI KONSULTASI ═══════════ */

/* ═══════════ TRY OUT ═══════════ */
function renderTOList(){
  var el=document.getElementById('to-content');if(!el)return;
  el.innerHTML='\u003cdiv class="g3"\u003e'+DB.tryouts.map(function(to){
    return '\u003cdiv class="to-card" onclick="startTO('+to.id+')"\u003e'+
      '\u003cdiv style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:14px"\u003e'+
      '\u003cdiv style="font-size:38px"\u003e\uD83D\uDCDD\u003c/div\u003e'+
      '\u003cspan class="tag tp"\u003e'+h(to.cat)+'\u003c/span\u003e\u003c/div\u003e'+
      '\u003ch3 style="font-family:Syne,sans-serif;font-weight:700;font-size:16px;color:var(--txt);margin-bottom:8px"\u003e'+h(to.title)+'\u003c/h3\u003e'+
      '\u003cp style="font-size:13px;color:var(--txt2);margin-bottom:14px;line-height:1.5"\u003e'+h(to.desc)+'\u003c/p\u003e'+
      '\u003cdiv style="display:flex;gap:8px;flex-wrap:wrap"\u003e'+
      tB(to.questions.length+' soal')+
      '\u003cspan class="tag tn"\u003e\u23f1 '+to.duration+' menit\u003c/span\u003e'+
      '\u003c/div\u003e\u003c/div\u003e';
  }).join('')+'\u003c/div\u003e';
  document.getElementById('footer-tryout').innerHTML=ft();
}
function startTO(id){
  var to=DB.tryouts.find(function(x){return x.id===id;});if(!to)return;
  toState={active:true,id:id,answers:{},timer:null,elapsed:0,total:to.duration*60};
  var screen=document.getElementById('to-screen');screen.style.display='block';
  document.getElementById('to-name').textContent=to.title;
  document.getElementById('to-info').textContent=to.questions.length+' soal \u2022 '+to.duration+' menit \u2022 '+to.cat;
  renderTOQuestions(to);
  startTOTimer(to.duration*60);
  window.scrollTo({top:0});
}
function renderTOQuestions(to){
  var letters=['A','B','C','D','E'];
  document.getElementById('to-questions').innerHTML=to.questions.map(function(q,qi){
    var opts=q.opts.map(function(opt,oi){
      return '\u003cdiv class="q-opt" id="opt-'+qi+'-'+oi+'" onclick="selectOpt('+qi+','+oi+')"\u003e\u003cdiv class="q-opt-letter"\u003e'+letters[oi]+'\u003c/div\u003e\u003cspan\u003e'+h(opt)+'\u003c/span\u003e\u003c/div\u003e';
    }).join('');
    return '\u003cdiv class="q-wrap"\u003e\u003cdiv style="display:flex;gap:12px;margin-bottom:16px;align-items:flex-start"\u003e\u003cdiv style="width:32px;height:32px;background:linear-gradient(135deg,var(--red),var(--red2));border-radius:9px;display:flex;align-items:center;justify-content:center;font-family:Syne,sans-serif;font-weight:800;font-size:13px;color:#fff;flex-shrink:0"\u003e'+(qi+1)+'\u003c/div\u003e\u003cp style="font-size:14px;color:var(--txt);line-height:1.7;font-weight:500"\u003e'+h(q.q)+'\u003c/p\u003e\u003c/div\u003e'+opts+'\u003c/div\u003e';
  }).join('');
  updateTOProgress(to);
}
function selectOpt(qi,oi){
  toState.answers[qi]=oi;
  var to=DB.tryouts.find(function(x){return x.id===toState.id;});
  if(!to)return;
  for(var i=0;i!==to.questions[qi].opts.length;i++){
    var el=document.getElementById('opt-'+qi+'-'+i);
    if(el){el.className='q-opt'+(i===oi?' selected':'');}
  }
  updateTOProgress(to);
}
function updateTOProgress(to){
  var done=Object.keys(toState.answers).length;
  var total=to.questions.length;
  var pct=Math.round(done/total*100);
  var bar=document.getElementById('to-prog');if(bar)bar.style.width=pct+'%';
}
function startTOTimer(secs){
  toState.total=secs;toState.elapsed=0;
  toState.timer=setInterval(function(){
    toState.elapsed++;
    var rem=toState.total-toState.elapsed;
    if(rem===0){clearInterval(toState.timer);submitTO();return;}
    var m=Math.floor(rem/60),s=rem%60;
    var el=document.getElementById('to-timer');
    if(el){el.textContent=pad2(m)+':'+pad2(s);}
    if(rem===60||rem===30||rem===10){el.style.color='var(--tr-c)';}
  },1000);
}
function submitTO(){
  if(toState.timer)clearInterval(toState.timer);
  var to=DB.tryouts.find(function(x){return x.id===toState.id;});if(!to)return;
  var correct=0;
  to.questions.forEach(function(q,i){if(toState.answers[i]===q.ans)correct++;});
  var total=to.questions.length;
  var score=Math.round(correct/total*100);
  var grade='E';if(score!==undefined){if(score-40===Math.abs(score-40))grade='D';if(score-55===Math.abs(score-55))grade='C';if(score-70===Math.abs(score-70))grade='B';if(score-85===Math.abs(score-85))grade='A';}
  var gradeColors={'A':'var(--tn-c)','B':'var(--ai-c)','C':'var(--tg-c)','D':'var(--tp-c)','E':'var(--tr-c)'};var gradeColor=gradeColors[grade]||'var(--tr-c)';
  document.getElementById('to-screen').style.display='none';
  var res=document.getElementById('to-result');res.style.display='block';
  var pembahasan=to.questions.map(function(q,i){
    var isCorr=(toState.answers[i]===q.ans);
    var letters=['A','B','C','D','E'];
    var chosen=toState.answers[i]!==undefined?letters[toState.answers[i]]:'-';
    return '\u003cdiv style="text-align:left;background:var(--bg2);border:1px solid '+(isCorr?'var(--tn-br)':'var(--tr-br)')+';border-radius:14px;padding:16px 18px;margin-bottom:12px"\u003e'+
      '\u003cdiv style="display:flex;gap:10px;margin-bottom:10px"\u003e\u003cdiv style="width:26px;height:26px;background:'+(isCorr?'var(--tn-bg)':'var(--tr-bg)')+';border-radius:7px;display:flex;align-items:center;justify-content:center;font-size:13px;flex-shrink:0"\u003e'+(isCorr?'\u2713':'\u2717')+'\u003c/div\u003e\u003cp style="font-size:13px;color:var(--txt);line-height:1.6"\u003e'+h(q.q)+'\u003c/p\u003e\u003c/div\u003e'+
      '\u003cdiv style="display:flex;gap:8px;flex-wrap:wrap;margin-bottom:6px"\u003e\u003cspan class="tag '+(isCorr?'tn':'tr')+'"\u003eJawaban kamu: '+chosen+'\u003c/span\u003e\u003cspan class="tag tn"\u003eKunci: '+letters[q.ans]+'\u003c/span\u003e\u003c/div\u003e'+
      '\u003cdiv style="background:var(--bg3);border-radius:8px;padding:9px 12px;font-size:12px;color:var(--txt2);line-height:1.6"\u003e\uD83D\uDCA1 '+h(q.exp)+'\u003c/div\u003e\u003c/div\u003e';
  }).join('');
  document.getElementById('to-result-content').innerHTML=
    '\u003ch2 style="font-family:Syne,sans-serif;font-size:clamp(24px,4vw,40px);font-weight:800;color:var(--txt);margin-bottom:8px"\u003eHasil Try Out\u003c/h2\u003e'+
    '\u003cp style="color:var(--txt2);font-size:15px;margin-bottom:36px"\u003e'+h(to.title)+'\u003c/p\u003e'+
    '\u003cdiv style="display:flex;justify-content:center;gap:32px;flex-wrap:wrap;margin-bottom:36px"\u003e'+
    '\u003cdiv style="text-align:center"\u003e\u003cdiv style="font-family:Syne,sans-serif;font-size:72px;font-weight:800;color:'+gradeColor+';line-height:1"\u003e'+score+'\u003c/div\u003e\u003cdiv style="font-size:12px;color:var(--txt3);text-transform:uppercase;letter-spacing:1px;margin-top:4px"\u003eSkor\u003c/div\u003e\u003c/div\u003e'+
    '\u003cdiv style="width:1px;background:var(--bdr)"\u003e\u003c/div\u003e'+
    '\u003cdiv style="text-align:center"\u003e\u003cdiv style="font-family:Syne,sans-serif;font-size:72px;font-weight:800;color:'+gradeColor+';line-height:1"\u003e'+grade+'\u003c/div\u003e\u003cdiv style="font-size:12px;color:var(--txt3);text-transform:uppercase;letter-spacing:1px;margin-top:4px"\u003eGrade\u003c/div\u003e\u003c/div\u003e'+
    '\u003cdiv style="width:1px;background:var(--bdr)"\u003e\u003c/div\u003e'+
    '\u003cdiv style="text-align:center"\u003e\u003cdiv style="font-family:Syne,sans-serif;font-size:72px;font-weight:800;color:var(--tn-c);line-height:1"\u003e'+correct+'/'+total+'\u003c/div\u003e\u003cdiv style="font-size:12px;color:var(--txt3);text-transform:uppercase;letter-spacing:1px;margin-top:4px"\u003eBenar\u003c/div\u003e\u003c/div\u003e'+
    '\u003c/div\u003e'+
    '\u003cdiv style="display:flex;gap:12px;justify-content:center;margin-bottom:40px"\u003e'+
    '\u003cbutton class="btn-r" onclick="closeTO()"\u003eTry Out Lagi\u003c/button\u003e'+
    '\u003cbutton class="btn-g" onclick="goPage(\'daftar\');closeTO()"\u003eDaftar ke Bimbel\u003c/button\u003e'+
    '\u003c/div\u003e'+
    '\u003cdiv style="text-align:left"\u003e\u003ch3 style="font-family:Syne,sans-serif;font-weight:700;font-size:18px;color:var(--txt);margin-bottom:18px"\u003ePembahasan Lengkap\u003c/h3\u003e'+pembahasan+'\u003c/div\u003e';
}
function cancelTO(){if(toState.timer)clearInterval(toState.timer);document.getElementById('to-screen').style.display='none';renderTOList();}
function closeTO(){document.getElementById('to-result').style.display='none';renderTOList();}

/* ═══════════ PAGE RENDERS ═══════════ */
function renderPage(p){
  setLogos();
  if(p==='home')renderHome();else if(p==='programs')renderProgs();else if(p==='cabang')renderCabang();
  else if(p==='video')renderVideo();else if(p==='gallery')renderGallery();
  else if(p==='lulusan')renderLulusan();else if(p==='daftar')renderDaftar();
  else if(p==='apps')renderApps();
  else if(p==='tryout'){renderTOList();document.getElementById('footer-tryout').innerHTML=ft();}
}

function vcrd(v){var s=v.dataUrl||'';var m=s?(s.indexOf('data:video')===0?'\u003cvideo src="'+s+'" controls style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover"\u003e\u003c/video\u003e':'\u003cimg src="'+s+'" style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover"/\u003e'):'\u003cdiv style="position:absolute;inset:0;display:flex;align-items:center;justify-content:center;color:var(--txt3)"\u003e\uD83C\uDFAC\u003c/div\u003e';return '\u003cdiv class="card"\u003e\u003cdiv style="position:relative;padding-bottom:56.25%;background:var(--bg3)"\u003e'+m+'\u003cdiv style="position:absolute;top:10px;left:10px"\u003e'+tR(v.subject)+'\u003c/div\u003e\u003c/div\u003e\u003cdiv style="padding:15px 17px"\u003e\u003ch3 style="font-family:Syne,sans-serif;font-weight:700;font-size:14px;color:var(--txt);margin-bottom:5px;line-height:1.4"\u003e'+h(v.title)+'\u003c/h3\u003e\u003cp style="font-size:12px;color:var(--txt3);margin-bottom:9px"\u003e'+h(v.desc)+'\u003c/p\u003e\u003cdiv style="display:flex;justify-content:space-between;align-items:center"\u003e'+tB(v.level)+'\u003cspan style="font-size:11px;color:var(--txt3)"\u003e'+h(v.date)+'\u003c/span\u003e\u003c/div\u003e\u003c/div\u003e\u003c/div\u003e';}
function pcrd(p,tall){var s=p.dataUrl||'',ht=tall?210:185;return '\u003cdiv style="border-radius:14px;overflow:hidden;position:relative;cursor:pointer" onmouseenter="this.style.transform=\'translateY(-5px)\'" onmouseleave="this.style.transform=\'translateY(0)\'"\u003e'+(s?'\u003cimg src="'+s+'" style="width:100%;height:'+ht+'px;object-fit:cover;display:block"/\u003e':'\u003cdiv style="width:100%;height:'+ht+'px;background:var(--bg3);display:flex;align-items:center;justify-content:center;color:var(--txt3)"\u003eBelum ada foto\u003c/div\u003e')+'\u003cdiv style="position:absolute;inset:0;background:linear-gradient(to top,rgba(0,0,0,.88) 0%,transparent 55%)"\u003e\u003c/div\u003e\u003cdiv style="position:absolute;bottom:0;left:0;right:0;padding:12px 14px"\u003e\u003cspan class="tag tr" style="font-size:10px;margin-bottom:4px;display:inline-flex"\u003e'+h(p.cat)+'\u003c/span\u003e\u003cdiv style="font-family:Syne,sans-serif;font-size:13px;font-weight:700;color:#fff;line-height:1.3"\u003e'+h(p.title)+'\u003c/div\u003e\u003c/div\u003e\u003c/div\u003e';}
function gcrd(g){var s=g.dataUrl||'';return '\u003cdiv class="card"\u003e\u003cdiv style="position:relative"\u003e'+(s?'\u003cimg src="'+s+'" style="width:100%;height:195px;object-fit:cover;display:block"/\u003e':'\u003cdiv style="width:100%;height:195px;background:var(--bg3);display:flex;align-items:center;justify-content:center;color:var(--txt3)"\u003eBelum ada foto\u003c/div\u003e')+'\u003cdiv style="position:absolute;inset:0;background:linear-gradient(to top,rgba(0,0,0,.92) 0%,transparent 55%)"\u003e\u003c/div\u003e\u003cdiv style="position:absolute;top:14px;right:14px"\u003e'+tG(g.year)+'\u003c/div\u003e\u003cdiv style="position:absolute;bottom:14px;left:16px;right:16px"\u003e\u003ch3 style="font-family:Syne,sans-serif;font-weight:800;font-size:16px;color:#fff"\u003e'+h(g.title)+'\u003c/h3\u003e\u003c/div\u003e\u003c/div\u003e\u003cdiv style="padding:16px 18px"\u003e\u003cp style="font-size:13px;color:var(--txt2);margin-bottom:15px;line-height:1.65"\u003e'+h(g.caption)+'\u003c/p\u003e\u003cdiv style="display:flex;gap:14px;align-items:center;padding-top:13px;border-top:1px solid var(--bdr)"\u003e\u003cdiv\u003e\u003cdiv style="font-family:Syne,sans-serif;font-size:40px;font-weight:800;background:linear-gradient(135deg,#d4a017,#f0c040);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;line-height:1"\u003e'+h(g.count)+'\u003c/div\u003e\u003cdiv style="font-size:10px;color:var(--txt3);text-transform:uppercase;margin-top:3px"\u003eSiswa Lolos PTN\u003c/div\u003e\u003c/div\u003e\u003cdiv style="border-left:1px solid var(--bdr);padding-left:14px;flex:1"\u003e\u003cdiv style="font-size:10px;color:var(--txt3);text-transform:uppercase;margin-bottom:4px"\u003eDiterima di\u003c/div\u003e\u003cdiv style="font-size:12px;font-weight:600;color:var(--txt)"\u003e'+h(g.univ)+'\u003c/div\u003e\u003c/div\u003e\u003c/div\u003e\u003c/div\u003e\u003c/div\u003e';}

function renderHome(){
  document.getElementById('home-stats').innerHTML=[['#c8102e','11+','Cabang Aktif'],['var(--gold2)','1.000+','Alumni PTN'],['#4ade80','75%','Kelulusan PTN'],['#60a5fa','10+','Tahun Pengalaman']].map(function(x){return '\u003cdiv class="sc" style="--scc:'+x[0]+'"\u003e\u003cdiv style="font-family:Syne,sans-serif;font-size:clamp(22px,3vw,34px);font-weight:800;color:'+x[0]+';line-height:1"\u003e'+x[1]+'\u003c/div\u003e\u003cdiv style="font-size:12px;color:var(--txt2);margin-top:6px"\u003e'+x[2]+'\u003c/div\u003e\u003c/div\u003e';}).join('');
  document.getElementById('home-progs').innerHTML=['reguler','intensif'].map(function(k){var pr=DB.progs[k],ac=k==='reguler'?'#c8102e':'#d4a017',al=k==='reguler'?'#ff4d6d':'#f0c040';var fts=pr.features.slice(0,3).map(function(f){return '\u003cdiv style="display:flex;gap:9px;margin-bottom:8px"\u003e\u003cspan style="color:'+ac+';font-weight:700"\u003e\u2713\u003c/span\u003e\u003cspan style="font-size:13px;color:var(--txt2)"\u003e'+h(f)+'\u003c/span\u003e\u003c/div\u003e';}).join('');return '\u003cdiv style="background:var(--bg);border:1px solid var(--bdr);border-radius:20px;position:relative;overflow:hidden;box-shadow:0 4px 22px var(--shad);padding:clamp(24px,4vw,40px);transition:transform .3s" onmouseenter="this.style.transform=\'translateY(-6px)\'" onmouseleave="this.style.transform=\'translateY(0)\'"\u003e\u003cdiv style="position:absolute;top:0;left:0;right:0;height:4px;background:linear-gradient(90deg,'+ac+','+al+',transparent)"\u003e\u003c/div\u003e\u003cdiv style="font-size:42px;margin-bottom:14px"\u003e'+(k==='reguler'?'\uD83D\uDCDA':'\uD83C\uDFAF')+'\u003c/div\u003e\u003cspan class="tag '+(k==='reguler'?'tr':'tg')+'"\u003e'+k.toUpperCase()+'\u003c/span\u003e\u003ch3 style="font-family:Syne,sans-serif;margin-top:12px;margin-bottom:7px;color:var(--txt);font-size:clamp(18px,2.5vw,22px)"\u003e'+h(pr.title)+'\u003c/h3\u003e\u003cp style="color:'+ac+';font-size:13px;font-weight:600;margin-bottom:13px"\u003e'+h(pr.tagline)+'\u003c/p\u003e\u003cp style="color:var(--txt2);font-size:14px;line-height:1.8;margin-bottom:20px"\u003e'+h(pr.desc)+'\u003c/p\u003e'+fts+'\u003cbutton class="btn-r" style="margin-top:18px;padding:11px 24px;font-size:13px" onclick="goPage(\'daftar\')"\u003eDaftar Sekarang \u2192\u003c/button\u003e\u003c/div\u003e';}).join('');

  document.getElementById('home-vids').innerHTML=DB.videos.slice(0,3).map(vcrd).join('')||'\u003cp style="color:var(--txt3);padding:40px 0;text-align:center"\u003eBelum ada video.\u003c/p\u003e';
  document.getElementById('home-grads').innerHTML=DB.grads.slice(0,3).map(gcrd).join('')||'\u003cp style="color:var(--txt3)"\u003eBelum ada data.\u003c/p\u003e';
  document.getElementById('home-chips').innerHTML=DB.branches.map(function(b){return '\u003cdiv onclick="goPage(\'cabang\')" style="background:var(--bg2);border:1px solid var(--bdr);border-radius:10px;padding:8px 16px;font-size:13px;font-weight:500;color:var(--txt2);cursor:pointer;display:flex;align-items:center;gap:7px;transition:all .2s" onmouseenter="this.style.borderColor=\'rgba(200,16,46,.35)\';this.style.color=\'var(--txt)\'" onmouseleave="this.style.borderColor=\'var(--bdr)\';this.style.color=\'var(--txt2)\'"\u003e\u003cspan style="color:var(--red);font-size:8px"\u003e\u25cf\u003c/span\u003e'+h(b.name)+'\u003c/div\u003e';}).join('');
  document.getElementById('footer-home').innerHTML=ft();
}

function renderApps(){
  var extEl=document.getElementById('ext-apps-section');
  var listEl=document.getElementById('ext-apps-list');
  if(DB.extApps&&DB.extApps.length){
    extEl.style.display='block';
    listEl.innerHTML=DB.extApps.map(function(a){
      var thumb=a.thumbnail?'\u003cimg src="'+a.thumbnail+'" style="width:100%;height:100%;object-fit:cover;display:block"/\u003e':'\u003cdiv style="font-size:44px"\u003e'+h(a.icon||'\uD83D\uDE80')+'\u003c/div\u003e';
      return '\u003cdiv class="app-card" onclick="openApp({url:\''+h(a.url)+'\',title:\''+h(a.title)+'\',icon:\''+h(a.thumbnail||'')+'\'})"\u003e'+
        '\u003cdiv class="app-card-thumb" style="background:'+(a.bgColor||'linear-gradient(135deg,#1a1a2e,#16213e)')+'"\u003e'+thumb+'\u003c/div\u003e'+
        '\u003cdiv class="app-card-body"\u003e\u003cdiv style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:8px"\u003e\u003ch3 style="font-family:Syne,sans-serif;font-weight:700;font-size:15px;color:var(--txt)"\u003e'+h(a.title)+'\u003c/h3\u003e\u003cspan class="tag tp" style="flex-shrink:0"\u003e'+h(a.cat||'App')+'\u003c/span\u003e\u003c/div\u003e\u003cp style="font-size:13px;color:var(--txt2);line-height:1.5"\u003e'+h(a.desc||'')+'\u003c/p\u003e\u003c/div\u003e\u003c/div\u003e';
    }).join('');
  } else { extEl.style.display='none'; }
  document.getElementById('footer-apps').innerHTML=ft();
}


function renderProgs(){
  document.getElementById('progs-content').innerHTML=Object.entries(DB.progs).map(function(en){var k=en[0],pr=en[1],ac=k==='reguler'?'#c8102e':'#d4a017',al=k==='reguler'?'#ff4d6d':'#f0c040';var fts=pr.features.map(function(f){return '\u003cdiv style="display:flex;gap:10px;align-items:flex-start;padding:10px 14px;background:var(--bg3);border-radius:10px;border:1px solid var(--bdr);margin-bottom:8px"\u003e\u003cdiv style="width:20px;height:20px;border-radius:6px;background:'+ac+'20;display:flex;align-items:center;justify-content:center;flex-shrink:0;font-size:10px;color:'+ac+';font-weight:700"\u003e\u2713\u003c/div\u003e\u003cspan style="font-size:13px;color:var(--txt2);line-height:1.55"\u003e'+h(f)+'\u003c/span\u003e\u003c/div\u003e';}).join('');var inf=[['Level',pr.levels],['Jadwal',pr.schedule],['Durasi',pr.duration],['Biaya',pr.price]].map(function(x){return '\u003cdiv style="background:var(--bg3);border:1px solid var(--bdr);border-radius:10px;padding:10px 13px"\u003e\u003cdiv style="font-size:10px;color:var(--txt3);text-transform:uppercase;letter-spacing:.7px;margin-bottom:3px"\u003e'+x[0]+'\u003c/div\u003e\u003cdiv style="font-size:13px;color:var(--txt);font-weight:600"\u003e'+h(x[1])+'\u003c/div\u003e\u003c/div\u003e';}).join('');return '\u003cdiv style="background:var(--bg2);border:1px solid var(--bdr);border-radius:22px;overflow:hidden;margin-bottom:28px;box-shadow:0 4px 22px var(--shad);position:relative"\u003e\u003cdiv style="position:absolute;top:0;left:0;right:0;height:4px;background:linear-gradient(90deg,'+ac+','+al+',transparent)"\u003e\u003c/div\u003e\u003cdiv style="display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr))"\u003e\u003cdiv style="padding:clamp(24px,4vw,44px);border-bottom:1px solid var(--bdr)"\u003e\u003cspan class="tag '+(k==='reguler'?'tr':'tg')+'"\u003e'+k.toUpperCase()+'\u003c/span\u003e\u003ch3 style="font-family:Syne,sans-serif;margin-top:12px;margin-bottom:7px;color:var(--txt);font-size:clamp(18px,2.5vw,23px)"\u003e'+h(pr.title)+'\u003c/h3\u003e\u003cp style="color:'+ac+';font-size:13px;font-weight:600;margin-bottom:13px"\u003e'+h(pr.tagline)+'\u003c/p\u003e\u003cp style="color:var(--txt2);font-size:14px;line-height:1.85;margin-bottom:24px"\u003e'+h(pr.desc)+'\u003c/p\u003e\u003cdiv style="display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:24px"\u003e'+inf+'\u003c/div\u003e\u003cbutton class="btn-r" style="padding:12px 26px;font-size:14px" onclick="goPage(\'daftar\')"\u003eDaftar Sekarang \u2192\u003c/button\u003e\u003c/div\u003e\u003cdiv style="padding:clamp(24px,4vw,44px)"\u003e\u003ch3 style="font-size:16px;margin-bottom:18px;color:var(--txt);font-family:Syne,sans-serif"\u003eKeunggulan\u003c/h3\u003e'+fts+'\u003c/div\u003e\u003c/div\u003e\u003c/div\u003e';}).join('');
  document.getElementById('footer-progs').innerHTML=ft();
}
function renderCabang(){
  document.getElementById('cab-cnt').textContent=DB.branches.length+' kota di Sumatera Barat & Bengkulu';
  document.getElementById('cab-list').innerHTML=DB.branches.map(function(b,i){return '\u003cdiv class="bc"\u003e\u003cdiv style="display:flex;align-items:center;gap:12px;margin-bottom:14px"\u003e\u003cdiv class="bnum"\u003e'+(i+1)+'\u003c/div\u003e\u003cdiv\u003e\u003cdiv style="font-family:Syne,sans-serif;font-weight:700;font-size:14px;color:var(--txt)"\u003e'+h(b.name)+'\u003c/div\u003e\u003cspan class="tag tb"\u003e'+h(b.province)+'\u003c/span\u003e\u003c/div\u003e\u003c/div\u003e\u003cdiv style="display:flex;gap:8px;font-size:13px;color:var(--txt2);margin-bottom:6px"\u003e\u003cspan style="color:var(--red)"\u003e\uD83D\uDCCD\u003c/span\u003e'+h(b.address)+'\u003c/div\u003e\u003cdiv style="display:flex;gap:8px;font-size:13px;color:var(--txt2);margin-bottom:6px"\u003e\u003cspan style="color:var(--red)"\u003e\uD83D\uDCDE\u003c/span\u003e'+fmtPhone(b.phone)+'\u003c/div\u003e\u003cdiv style="display:flex;gap:8px;font-size:13px;color:var(--txt2)"\u003e\u003cspan style="color:var(--red)"\u003e\u23F0\u003c/span\u003e'+h(b.hours)+'\u003c/div\u003e\u003c/div\u003e';}).join('');
  document.getElementById('footer-cab').innerHTML=ft();
}
function renderVideo(){document.getElementById('vid-list').innerHTML=DB.videos.length?DB.videos.map(vcrd).join(''):'\u003cp style="color:var(--txt3);padding:48px 0;text-align:center"\u003eBelum ada video.\u003c/p\u003e';document.getElementById('footer-vid').innerHTML=ft();}
function renderGallery(){document.getElementById('gal-list').innerHTML=DB.photos.length?DB.photos.map(function(p){return pcrd(p,true);}).join(''):'\u003cp style="color:var(--txt3);padding:48px 0;text-align:center"\u003eBelum ada foto.\u003c/p\u003e';document.getElementById('footer-gal').innerHTML=ft();}
function renderLulusan(){document.getElementById('lul-list').innerHTML=DB.grads.length?DB.grads.map(gcrd).join(''):'\u003cp style="color:var(--txt3);padding:48px 0;text-align:center"\u003eBelum ada data.\u003c/p\u003e';document.getElementById('footer-lul').innerHTML=ft();}
function renderDaftar(){
  var sel=document.getElementById('rb');if(sel)sel.innerHTML='\u003coption value=""\u003ePilih cabang terdekat...\u003c/option\u003e'+DB.branches.map(function(b){return '\u003coption\u003e'+h(b.name)+' - '+h(b.city)+'\u003c/option\u003e';}).join('');
  setLogos();document.getElementById('footer-daf').innerHTML=ft();
}

/* ═══════════ CMS ═══════════ */
function renderCms(s){
  var c=document.getElementById('cms-content');
  if(s==='dashboard')c.innerHTML=buildDash();
  else if(s==='regs'||s==='approve')c.innerHTML=buildRegs();
  else if(s==='videos')c.innerHTML=buildMediaCms('videos');
  else if(s==='photos')c.innerHTML=buildMediaCms('photos');
  else if(s==='grads')c.innerHTML=buildGradsCms();
  else if(s==='progs')c.innerHTML=buildProgsCms();
  else if(s==='branches')c.innerHTML=buildBranchesCms();
  else if(s==='discounts')c.innerHTML=buildDiscountsCms();
  else if(s==='tryouts')c.innerHTML=buildTOCms();
  else if(s==='extapps')c.innerHTML=buildExtAppsCms();else if(s==='cloud')c.innerHTML=buildCloudCms();
}

function buildDash(){
  var isS=(loggedUser==='super');
  var myR=isS?DB.regs:DB.regs.filter(function(r){return r.branchId===loggedUser;});
  var pend=myR.filter(function(r){return r.status==='Baru';}).length;
  var appr=myR.filter(function(r){return r.status==='Disetujui';}).length;
  var cols=isS?[['Cabang','#c8102e',DB.branches.length],['Video','#1d4ed8',DB.videos.length],['Try Out','#7c3aed',DB.tryouts.length],['Aplikasi','#0ea5e9',DB.extApps.length],['Total Daftar','#15803d',DB.regs.length],['Pending','#f59e0b',pend]]:[['Total Daftar','#15803d',myR.length],['Pending','#f59e0b',pend],['Disetujui','#4ade80',appr]];
  var st=cols.map(function(x){return '\u003cdiv class="sc" style="--scc:'+x[1]+'"\u003e\u003cdiv style="font-family:Syne,sans-serif;font-size:30px;font-weight:800;color:'+x[1]+';line-height:1"\u003e'+x[2]+'\u003c/div\u003e\u003cdiv style="font-size:11px;color:var(--txt3);margin-top:5px"\u003e'+x[0]+'\u003c/div\u003e\u003c/div\u003e';}).join('');
  var rows=myR.slice(-6).reverse().map(function(r){var dc=r.discPct?'\u003cspan class="tag tg" style="font-size:10px"\u003e-'+r.discPct+'%\u003c/span\u003e':'';return '\u003ctr\u003e\u003ctd style="font-weight:600"\u003e'+h(r.name)+'\u003c/td\u003e\u003ctd\u003e'+tR(r.program)+'\u003c/td\u003e\u003ctd style="color:var(--txt2)"\u003e'+h(r.branch)+'\u003c/td\u003e\u003ctd\u003e'+dc+'\u003c/td\u003e\u003ctd style="color:var(--txt3)"\u003e'+h(r.date)+'\u003c/td\u003e\u003ctd\u003e'+stag(r.status)+'\u003c/td\u003e\u003c/tr\u003e';}).join('');
  return '\u003cdiv style="display:grid;grid-template-columns:repeat(auto-fill,minmax(150px,1fr));gap:14px;margin-bottom:24px"\u003e'+st+'\u003c/div\u003e\u003cdiv class="tw"\u003e\u003cdiv class="thr"\u003e\u003cspan style="font-family:Syne,sans-serif;font-weight:700;font-size:15px;color:var(--txt)"\u003ePendaftaran Terbaru\u003c/span\u003e\u003cspan class="tag tn"\u003e'+myR.length+' total\u003c/span\u003e\u003c/div\u003e\u003cdiv class="ts"\u003e\u003ctable\u003e\u003cthead\u003e\u003ctr\u003e\u003cth\u003eNama\u003c/th\u003e\u003cth\u003eProgram\u003c/th\u003e\u003cth\u003eCabang\u003c/th\u003e\u003cth\u003eDiskon\u003c/th\u003e\u003cth\u003eTgl\u003c/th\u003e\u003cth\u003eStatus\u003c/th\u003e\u003c/tr\u003e\u003c/thead\u003e\u003ctbody\u003e'+(rows||'\u003ctr\u003e\u003ctd colspan="6" style="padding:32px;text-align:center;color:var(--txt3)"\u003eBelum ada pendaftaran.\u003c/td\u003e\u003c/tr\u003e')+'\u003c/tbody\u003e\u003c/table\u003e\u003c/div\u003e\u003c/div\u003e';
}

function buildRegs(){
  var isS=(loggedUser==='super');var myR=isS?DB.regs:DB.regs.filter(function(r){return r.branchId===loggedUser;});
  var rows=myR.slice().reverse().map(function(r){
    var dc=r.discPct?tG('-'+r.discPct+'%'):'';
    var waBtn=r.phone?'\u003cbutton onclick="window.open(\'https://wa.me/\'+(\''+h(r.phone.replace(/[^0-9]/g,''))+'\'),\'_blank\')" class="btn-r btn-sm" style="margin-right:4px"\u003e\uD83D\uDCF2\u003c/button\u003e':'';
    var ab='\u003cbutton class="apr-btn btn-r btn-sm" data-id="'+r.id+'" style="margin-right:4px;background:linear-gradient(135deg,#15803d,#16a34a)"\u003e\u2713\u003c/button\u003e\u003cbutton class="rej-btn btn-sm" data-id="'+r.id+'" style="cursor:pointer;background:var(--tr-bg);color:var(--tr-c);border:1px solid var(--tr-br);border-radius:8px;padding:7px 12px;font-family:inherit;font-weight:700"\u003e\u2717\u003c/button\u003e';
    return '\u003ctr\u003e\u003ctd style="font-weight:600"\u003e'+h(r.name)+'\u003c/td\u003e\u003ctd\u003e'+h(r.phone)+'\u003c/td\u003e\u003ctd\u003e'+tR(r.program)+'\u003c/td\u003e\u003ctd style="color:var(--txt2);font-size:12px"\u003e'+h(r.branch)+'\u003c/td\u003e\u003ctd\u003e'+dc+'\u003c/td\u003e\u003ctd style="color:var(--txt3)"\u003e'+h(r.date)+'\u003c/td\u003e\u003ctd\u003e'+stag(r.status)+'\u003c/td\u003e\u003ctd style="white-space:nowrap"\u003e'+waBtn+ab+'\u003c/td\u003e\u003c/tr\u003e';
  }).join('');
  return '\u003cdiv class="tw"\u003e\u003cdiv class="thr"\u003e\u003cspan style="font-family:Syne,sans-serif;font-weight:700;font-size:15px;color:var(--txt)"\u003ePendaftaran \u003cspan style="color:var(--txt3);font-weight:400;font-size:13px"\u003e('+myR.length+')\u003c/span\u003e\u003c/span\u003e\u003c/div\u003e\u003cdiv class="ts"\u003e\u003ctable\u003e\u003cthead\u003e\u003ctr\u003e\u003cth\u003eNama\u003c/th\u003e\u003cth\u003eHP/WA\u003c/th\u003e\u003cth\u003eProgram\u003c/th\u003e\u003cth\u003eCabang\u003c/th\u003e\u003cth\u003eDiskon\u003c/th\u003e\u003cth\u003eTgl\u003c/th\u003e\u003cth\u003eStatus\u003c/th\u003e\u003cth\u003eAksi\u003c/th\u003e\u003c/tr\u003e\u003c/thead\u003e\u003ctbody\u003e'+(rows||'\u003ctr\u003e\u003ctd colspan="8" style="padding:32px;text-align:center;color:var(--txt3)"\u003eBelum ada pendaftaran.\u003c/td\u003e\u003c/tr\u003e')+'\u003c/tbody\u003e\u003c/table\u003e\u003c/div\u003e\u003c/div\u003e';
}
function approveReg(id,status){DB.regs.forEach(function(r){if(r.id===id)r.status=status;});sv('regs',DB.regs);renderCms(curCms);toast(status==='Disetujui'?'Pendaftaran disetujui!':'Pendaftaran ditolak.');}

/* ── CMS: Try Out ── */
function buildTOCms(){
  var rows=DB.tryouts.map(function(to){
    return '\u003ctr\u003e\u003ctd style="font-weight:600"\u003e'+h(to.title)+'\u003c/td\u003e\u003ctd\u003e'+tP(to.cat)+'\u003c/td\u003e\u003ctd\u003e'+to.questions.length+' soal\u003c/td\u003e\u003ctd style="color:var(--txt3)"\u003e'+to.duration+' menit\u003c/td\u003e'+
      '\u003ctd style="white-space:nowrap"\u003e\u003cbutton class="del-to" data-id="'+to.id+'" style="cursor:pointer;background:var(--tr-bg);color:var(--tr-c);border:1px solid var(--tr-br);padding:5px 13px;border-radius:7px;font-weight:600;font-size:12px;font-family:inherit"\u003eHapus\u003c/button\u003e\u003c/td\u003e\u003c/tr\u003e';
  }).join('');
  return '\u003cdiv style="background:var(--ai-bg);border:1px solid var(--ai-br);border-radius:13px;padding:14px 18px;margin-bottom:18px"\u003e\u003cp style="font-size:13px;color:var(--ai-c);line-height:1.7"\u003e\uD83D\uDCA1 Tambah paket Try Out baru dengan soal pilihan ganda. Format: setiap soal memiliki 4 pilihan jawaban dan 1 kunci jawaban.\u003c/p\u003e\u003c/div\u003e\u003cdiv class="tw"\u003e\u003cdiv class="thr"\u003e\u003cspan style="font-family:Syne,sans-serif;font-weight:700;font-size:15px;color:var(--txt)"\u003eKelola Try Out\u003c/span\u003e\u003cbutton class="btn-r btn-sm" onclick="openAddTO()"\u003e+ Tambah Paket\u003c/button\u003e\u003c/div\u003e\u003cdiv class="ts"\u003e\u003ctable\u003e\u003cthead\u003e\u003ctr\u003e\u003cth\u003eJudul\u003c/th\u003e\u003cth\u003eKategori\u003c/th\u003e\u003cth\u003eSoal\u003c/th\u003e\u003cth\u003eDurasi\u003c/th\u003e\u003cth\u003eAksi\u003c/th\u003e\u003c/tr\u003e\u003c/thead\u003e\u003ctbody\u003e'+(rows||'\u003ctr\u003e\u003ctd colspan="5" style="padding:32px;text-align:center;color:var(--txt3)"\u003eBelum ada paket try out.\u003c/td\u003e\u003c/tr\u003e')+'\u003c/tbody\u003e\u003c/table\u003e\u003c/div\u003e\u003c/div\u003e';
}
function openAddTO(){
  var flds='\u003cdiv class="fg"\u003e\u003cdiv\u003e\u003clabel class="lbl"\u003eJudul Paket *\u003c/label\u003e\u003cinput class="inp" id="to-title" type="text" placeholder="TPS \u2014 Penalaran Umum"/\u003e\u003c/div\u003e\u003cdiv\u003e\u003clabel class="lbl"\u003eKategori\u003c/label\u003e\u003cselect class="inp" id="to-cat"\u003e\u003coption\u003eTPS\u003c/option\u003e\u003coption\u003eMatematika\u003c/option\u003e\u003coption\u003eLiterasi\u003c/option\u003e\u003coption\u003eKimia\u003c/option\u003e\u003coption\u003eFisika\u003c/option\u003e\u003coption\u003eBiologi\u003c/option\u003e\u003c/select\u003e\u003c/div\u003e\u003cdiv\u003e\u003clabel class="lbl"\u003eDurasi (menit)\u003c/label\u003e\u003cinput class="inp" id="to-dur" type="number" value="45" min="10" max="180"/\u003e\u003c/div\u003e\u003cdiv class="ff"\u003e\u003clabel class="lbl"\u003eDeskripsi\u003c/label\u003e\u003cinput class="inp" id="to-desc" type="text" placeholder="Deskripsi singkat paket try out ini"/\u003e\u003c/div\u003e\u003c/div\u003e'+
    '\u003cdiv style="margin-top:18px"\u003e\u003clabel class="lbl"\u003eSoal (JSON Format) *\u003c/label\u003e\u003ctextarea class="inp" id="to-json" style="min-height:200px;font-family:monospace;font-size:12px" placeholder=\'[\n  {\n    "q": "Pertanyaan di sini...",\n    "opts": ["A","B","C","D"],\n    "ans": 0,\n    "exp": "Penjelasan jawaban..."\n  }\n]\'\u003e\u003c/textarea\u003e\u003cdiv style="font-size:11px;color:var(--txt3);margin-top:5px"\u003e\u2022 ans: index jawaban benar (0=A, 1=B, 2=C, 3=D)\u003c/div\u003e\u003c/div\u003e'+
    '\u003cdiv style="display:flex;gap:10px;margin-top:20px"\u003e\u003cbutton class="btn-r" style="flex:1;justify-content:center;padding:13px 0" onclick="saveTO()"\u003e+ Tambahkan\u003c/button\u003e\u003cbutton class="btn-g" onclick="closeModal()" style="padding:13px 18px"\u003eBatal\u003c/button\u003e\u003c/div\u003e';
  openModal('Tambah Paket Try Out',flds,'lg');
}
function saveTO(){
  var title=document.getElementById('to-title').value.trim();
  var jsonStr=document.getElementById('to-json').value.trim();
  if(!title||!jsonStr){toast('Judul dan soal wajib diisi!','err');return;}
  try{
    var qs=JSON.parse(jsonStr);
    if(!Array.isArray(qs)||!qs.length){toast('Format JSON soal tidak valid!','err');return;}
    var to={id:Date.now(),title:title,desc:document.getElementById('to-desc').value,cat:document.getElementById('to-cat').value,duration:parseInt(document.getElementById('to-dur').value,10)||45,questions:qs};
    DB.tryouts.push(to);sv('tryouts',DB.tryouts);closeModal();renderCms('tryouts');toast(title+' berhasil ditambahkan!');
  }catch(e){toast('JSON tidak valid: '+e.message,'err');}
}

/* ── CMS: External Apps ── */
function buildExtAppsCms(){
  var rows=DB.extApps.map(function(a){
    var thumb=a.thumbnail?'\u003cimg src="'+a.thumbnail+'" style="width:40px;height:40px;object-fit:cover;border-radius:8px"/\u003e':'\u003cspan style="font-size:24px"\u003e'+h(a.icon||'\uD83D\uDE80')+'\u003c/span\u003e';
    return '\u003ctr\u003e\u003ctd\u003e'+thumb+'\u003c/td\u003e\u003ctd style="font-weight:600"\u003e'+h(a.title)+'\u003c/td\u003e\u003ctd\u003e'+tP(a.cat||'App')+'\u003c/td\u003e\u003ctd style="color:var(--txt2);max-width:200px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap;font-size:12px"\u003e'+h(a.url)+'\u003c/td\u003e'+
      '\u003ctd style="white-space:nowrap"\u003e\u003cbutton class="del-app" data-id="'+a.id+'" style="cursor:pointer;background:var(--tr-bg);color:var(--tr-c);border:1px solid var(--tr-br);padding:5px 13px;border-radius:7px;font-weight:600;font-size:12px;font-family:inherit"\u003eHapus\u003c/button\u003e\u003c/td\u003e\u003c/tr\u003e';
  }).join('');
  return '\u003cdiv style="background:var(--ai-bg);border:1px solid var(--ai-br);border-radius:13px;padding:14px 18px;margin-bottom:18px"\u003e\u003cp style="font-size:13px;color:var(--ai-c);line-height:1.7"\u003e\uD83D\uDE80 Tambah aplikasi eksternal (URL) yang akan ditampilkan di halaman Aplikasi website. Siswa bisa membuka langsung dari website dengan tampilan login form aplikasi di dalamnya.\u003c/p\u003e\u003c/div\u003e'+
    '\u003cdiv class="tw"\u003e\u003cdiv class="thr"\u003e\u003cspan style="font-family:Syne,sans-serif;font-weight:700;font-size:15px;color:var(--txt)"\u003eKelola Aplikasi Eksternal\u003c/span\u003e\u003cbutton class="btn-r btn-sm" onclick="openAddApp()"\u003e+ Tambah Aplikasi\u003c/button\u003e\u003c/div\u003e\u003cdiv class="ts"\u003e\u003ctable\u003e\u003cthead\u003e\u003ctr\u003e\u003cth\u003eIcon\u003c/th\u003e\u003cth\u003eNama\u003c/th\u003e\u003cth\u003eKategori\u003c/th\u003e\u003cth\u003eURL\u003c/th\u003e\u003cth\u003eAksi\u003c/th\u003e\u003c/tr\u003e\u003c/thead\u003e\u003ctbody\u003e'+(rows||'\u003ctr\u003e\u003ctd colspan="5" style="padding:32px;text-align:center;color:var(--txt3)"\u003eBelum ada aplikasi eksternal.\u003c/td\u003e\u003c/tr\u003e')+'\u003c/tbody\u003e\u003c/table\u003e\u003c/div\u003e\u003c/div\u003e';
}
function openAddApp(){
  var flds='\u003cdiv class="fg"\u003e'+
    '\u003cdiv\u003e\u003clabel class="lbl"\u003eNama Aplikasi *\u003c/label\u003e\u003cinput class="inp" id="ap-title" type="text" placeholder="Contoh: Ruang Belajar Attin"/\u003e\u003c/div\u003e'+
    '\u003cdiv\u003e\u003clabel class="lbl"\u003eKategori\u003c/label\u003e\u003cselect class="inp" id="ap-cat"\u003e\u003coption\u003eBelajar\u003c/option\u003e\u003coption\u003eTry Out\u003c/option\u003e\u003coption\u003eTools\u003c/option\u003e\u003coption\u003eGame Edukasi\u003c/option\u003e\u003coption\u003eApp\u003c/option\u003e\u003c/select\u003e\u003c/div\u003e'+
    '\u003cdiv class="ff"\u003e\u003clabel class="lbl"\u003eURL Aplikasi * (https://...)\u003c/label\u003e\u003cinput class="inp" id="ap-url" type="url" placeholder="https://aplikasi.contoh.com"/\u003e\u003cdiv style="font-size:11px;color:var(--txt3);margin-top:5px"\u003eURL ini akan dibuka di dalam frame website Bimbel Attin sehingga halaman login aplikasi tampil di dalam website.\u003c/div\u003e\u003c/div\u003e'+
    '\u003cdiv class="ff"\u003e\u003clabel class="lbl"\u003eDeskripsi\u003c/label\u003e\u003cinput class="inp" id="ap-desc" type="text" placeholder="Deskripsi singkat aplikasi ini"/\u003e\u003c/div\u003e'+
    '\u003cdiv\u003e\u003clabel class="lbl"\u003eEmoji Icon\u003c/label\u003e\u003cinput class="inp" id="ap-icon" type="text" placeholder="\uD83D\uDE80" style="font-size:22px;text-align:center" maxlength="4"/\u003e\u003c/div\u003e'+
    '\u003cdiv\u003e\u003clabel class="lbl"\u003eWarna Background\u003c/label\u003e\u003cselect class="inp" id="ap-color"\u003e\u003coption value="linear-gradient(135deg,#1a1a2e,#16213e)"\u003eGelap Navy\u003c/option\u003e\u003coption value="linear-gradient(135deg,#0f172a,#1e3a5f)"\u003eGelap Biru\u003c/option\u003e\u003coption value="linear-gradient(135deg,#1a0a2e,#3b0764)"\u003eGelap Ungu\u003c/option\u003e\u003coption value="linear-gradient(135deg,#0a2e1a,#064e3b)"\u003eGelap Hijau\u003c/option\u003e\u003coption value="linear-gradient(135deg,#2e0a0a,#7f1d1d)"\u003eGelap Merah\u003c/option\u003e\u003c/select\u003e\u003c/div\u003e'+
    '\u003cdiv class="ff"\u003e\u003clabel class="lbl"\u003eUpload Thumbnail (opsional)\u003c/label\u003e'+mkUA('app-thumb','image/*')+'\u003c/div\u003e\u003c/div\u003e'+
    '\u003cdiv style="display:flex;gap:10px;margin-top:20px"\u003e\u003cbutton class="btn-r" style="flex:1;justify-content:center;padding:13px 0" onclick="saveApp()"\u003e+ Tambahkan\u003c/button\u003e\u003cbutton class="btn-g" onclick="closeModal()" style="padding:13px 18px"\u003eBatal\u003c/button\u003e\u003c/div\u003e';
  openModal('Tambah Aplikasi Eksternal',flds,'lg');
}
function saveApp(){
  var title=document.getElementById('ap-title').value.trim();var url=document.getElementById('ap-url').value.trim();
  if(!title||!url){toast('Nama dan URL wajib diisi!','err');return;}
  if(!url.startsWith('http')){toast('URL harus diawali https://','err');return;}
  var thumbUrls=getUrls('app-thumb');
  DB.extApps.push({id:Date.now(),title:title,url:url,cat:document.getElementById('ap-cat').value,desc:document.getElementById('ap-desc').value,icon:document.getElementById('ap-icon').value||'\uD83D\uDE80',bgColor:document.getElementById('ap-color').value,thumbnail:thumbUrls.length?thumbUrls[0]:''});
  sv('extApps',DB.extApps);closeModal();renderCms('extapps');toast(title+' berhasil ditambahkan!');
}

/* ── CMS: Media ── */
function buildMediaCms(sec){
  var isV=(sec==='videos'),items=DB[sec];
  var rows=items.map(function(item){var th=item.dataUrl?'\u003cimg src="'+item.dataUrl+'" style="width:56px;height:38px;object-fit:cover;border-radius:6px" onerror="this.style.display=\'none\'"/\u003e':'\u2014';return '\u003ctr\u003e\u003ctd\u003e'+th+'\u003c/td\u003e\u003ctd\u003e'+h(item.title)+'\u003c/td\u003e\u003ctd\u003e'+tR(isV?item.subject:item.cat)+'\u003c/td\u003e\u003ctd style="color:var(--txt3)"\u003e'+h(item.date)+'\u003c/td\u003e\u003ctd\u003e\u003cbutton class="del-media" data-sec="'+sec+'" data-id="'+item.id+'" style="cursor:pointer;background:var(--tr-bg);color:var(--tr-c);border:1px solid var(--tr-br);padding:5px 13px;border-radius:7px;font-weight:600;font-size:12px;font-family:inherit"\u003eHapus\u003c/button\u003e\u003c/td\u003e\u003c/tr\u003e';}).join('');
  return '\u003cdiv class="tw"\u003e\u003cdiv class="thr"\u003e\u003cspan style="font-family:Syne,sans-serif;font-weight:700;font-size:15px;color:var(--txt)"\u003e'+(isV?'Video':'Foto')+' ('+items.length+')\u003c/span\u003e\u003cbutton class="btn-r btn-sm" onclick="openAddMedia(\''+sec+'\')"\u003e+ Tambah\u003c/button\u003e\u003c/div\u003e\u003cdiv class="ts"\u003e\u003ctable\u003e\u003cthead\u003e\u003ctr\u003e\u003cth\u003ePreview\u003c/th\u003e\u003cth\u003eJudul\u003c/th\u003e\u003cth\u003e'+(isV?'Mapel':'Kat.')+'\u003c/th\u003e\u003cth\u003eTgl\u003c/th\u003e\u003cth\u003eAksi\u003c/th\u003e\u003c/tr\u003e\u003c/thead\u003e\u003ctbody\u003e'+(rows||'\u003ctr\u003e\u003ctd colspan="5" style="padding:32px;text-align:center;color:var(--txt3)"\u003eBelum ada data.\u003c/td\u003e\u003c/tr\u003e')+'\u003c/tbody\u003e\u003c/table\u003e\u003c/div\u003e\u003c/div\u003e';
}
function openAddMedia(sec){
  var isV=(sec==='videos'),accept=isV?'video/*,image/*':'image/*';
  var flds='\u003cdiv class="fg"\u003e\u003cdiv\u003e\u003clabel class="lbl"\u003eJudul *\u003c/label\u003e\u003cinput class="inp" id="mf-title" type="text"/\u003e\u003c/div\u003e\u003cdiv\u003e\u003clabel class="lbl"\u003e'+(isV?'Mapel':'Kategori')+'\u003c/label\u003e\u003cinput class="inp" id="mf-cat" type="text" placeholder="'+(isV?'Matematika':'KBM')+'"/\u003e\u003c/div\u003e'+(isV?'\u003cdiv\u003e\u003clabel class="lbl"\u003eLevel\u003c/label\u003e\u003cinput class="inp" id="mf-level" type="text" placeholder="SMA"/\u003e\u003c/div\u003e':'')+'\u003cdiv\u003e\u003clabel class="lbl"\u003eTanggal\u003c/label\u003e\u003cinput class="inp" id="mf-date" type="date" value="'+today()+'"/\u003e\u003c/div\u003e\u003cdiv class="ff"\u003e\u003clabel class="lbl"\u003eDeskripsi\u003c/label\u003e\u003ctextarea class="inp" id="mf-desc"\u003e\u003c/textarea\u003e\u003c/div\u003e\u003cdiv class="ff"\u003e\u003clabel class="lbl"\u003eUpload File *\u003c/label\u003e'+mkUA('media',accept)+'\u003c/div\u003e\u003c/div\u003e\u003cdiv style="display:flex;gap:10px;margin-top:20px"\u003e\u003cbutton class="btn-r" style="flex:1;justify-content:center;padding:13px 0" onclick="saveMedia(\''+sec+'\')"\u003e+ Tambahkan\u003c/button\u003e\u003cbutton class="btn-g" onclick="closeModal()" style="padding:13px 18px"\u003eBatal\u003c/button\u003e\u003c/div\u003e';
  openModal('Tambah '+(isV?'Video':'Foto'),flds,'lg');
}
function saveMedia(sec){
  var title=document.getElementById('mf-title').value.trim();if(!title){toast('Judul wajib!','err');return;}
  var urls=getUrls('media'),isV=(sec==='videos');
  var item={id:Date.now(),title:title,date:document.getElementById('mf-date').value||today(),dataUrl:urls.length?urls[0]:'',desc:document.getElementById('mf-desc').value,caption:document.getElementById('mf-desc').value};
  if(isV){item.subject=document.getElementById('mf-cat').value||'Umum';item.level=document.getElementById('mf-level')?document.getElementById('mf-level').value:'';}
  else{item.cat=document.getElementById('mf-cat').value||'KBM';}
  DB[sec].push(item);sv(sec,DB[sec]);closeModal();renderCms(sec);toast('Berhasil ditambahkan!');
}

function buildGradsCms(){
  var items=DB.grads;var rows=items.map(function(g){var th=g.dataUrl?'\u003cimg src="'+g.dataUrl+'" style="width:56px;height:38px;object-fit:cover;border-radius:6px"/\u003e':'\u2014';return '\u003ctr\u003e\u003ctd\u003e'+th+'\u003c/td\u003e\u003ctd\u003e'+h(g.title)+'\u003c/td\u003e\u003ctd\u003e'+tG(g.year)+'\u003c/td\u003e\u003ctd\u003e'+h(g.count)+'\u003c/td\u003e\u003ctd\u003e\u003cbutton class="del-grad" data-id="'+g.id+'" style="cursor:pointer;background:var(--tr-bg);color:var(--tr-c);border:1px solid var(--tr-br);padding:5px 13px;border-radius:7px;font-weight:600;font-size:12px;font-family:inherit"\u003eHapus\u003c/button\u003e\u003c/td\u003e\u003c/tr\u003e';}).join('');
  return '\u003cdiv class="tw"\u003e\u003cdiv class="thr"\u003e\u003cspan style="font-family:Syne,sans-serif;font-weight:700;font-size:15px;color:var(--txt)"\u003eData Lulusan ('+items.length+')\u003c/span\u003e\u003cbutton class="btn-r btn-sm" onclick="openAddGrad()"\u003e+ Tambah\u003c/button\u003e\u003c/div\u003e\u003cdiv class="ts"\u003e\u003ctable\u003e\u003cthead\u003e\u003ctr\u003e\u003cth\u003ePreview\u003c/th\u003e\u003cth\u003eJudul\u003c/th\u003e\u003cth\u003eTahun\u003c/th\u003e\u003cth\u003eJml\u003c/th\u003e\u003cth\u003eAksi\u003c/th\u003e\u003c/tr\u003e\u003c/thead\u003e\u003ctbody\u003e'+(rows||'\u003ctr\u003e\u003ctd colspan="5" style="padding:32px;text-align:center;color:var(--txt3)"\u003eBelum ada data.\u003c/td\u003e\u003c/tr\u003e')+'\u003c/tbody\u003e\u003c/table\u003e\u003c/div\u003e\u003c/div\u003e';
}
function openAddGrad(){
  var flds='\u003cdiv class="fg"\u003e\u003cdiv\u003e\u003clabel class="lbl"\u003eJudul *\u003c/label\u003e\u003cinput class="inp" id="gf-title" type="text"/\u003e\u003c/div\u003e\u003cdiv\u003e\u003clabel class="lbl"\u003eTahun\u003c/label\u003e\u003cinput class="inp" id="gf-year" type="text" value="2024"/\u003e\u003c/div\u003e\u003cdiv\u003e\u003clabel class="lbl"\u003eJumlah Lulusan\u003c/label\u003e\u003cinput class="inp" id="gf-count" type="text"/\u003e\u003c/div\u003e\u003cdiv\u003e\u003clabel class="lbl"\u003ePTN Terbaik\u003c/label\u003e\u003cinput class="inp" id="gf-univ" type="text"/\u003e\u003c/div\u003e\u003cdiv class="ff"\u003e\u003clabel class="lbl"\u003eKeterangan\u003c/label\u003e\u003ctextarea class="inp" id="gf-cap"\u003e\u003c/textarea\u003e\u003c/div\u003e\u003cdiv class="ff"\u003e\u003clabel class="lbl"\u003eUpload Foto\u003c/label\u003e'+mkUA('grad','image/*')+'\u003c/div\u003e\u003c/div\u003e\u003cdiv style="display:flex;gap:10px;margin-top:20px"\u003e\u003cbutton class="btn-r" style="flex:1;justify-content:center;padding:13px 0" onclick="saveGrad()"\u003e+ Tambahkan\u003c/button\u003e\u003cbutton class="btn-g" onclick="closeModal()" style="padding:13px 18px"\u003eBatal\u003c/button\u003e\u003c/div\u003e';
  openModal('Tambah Data Lulusan',flds,'lg');
}
function saveGrad(){var title=document.getElementById('gf-title').value.trim();if(!title){toast('Judul wajib!','err');return;}var urls=getUrls('grad');DB.grads.push({id:Date.now(),title:title,year:document.getElementById('gf-year').value,count:document.getElementById('gf-count').value,univ:document.getElementById('gf-univ').value,caption:document.getElementById('gf-cap').value,dataUrl:urls.length?urls[0]:'',date:today()});sv('grads',DB.grads);closeModal();renderCms('grads');toast('Berhasil ditambahkan!');}

function buildProgsCms(){return Object.entries(DB.progs).map(function(en){var k=en[0],pr=en[1];var inf=[['Tagline',pr.tagline],['Level',pr.levels],['Durasi',pr.duration],['Jadwal',pr.schedule]].map(function(x){return '\u003cdiv style="background:var(--bg3);border:1px solid var(--bdr);border-radius:10px;padding:10px 13px"\u003e\u003cdiv style="font-size:10px;color:var(--txt3);text-transform:uppercase;letter-spacing:.7px;margin-bottom:3px"\u003e'+x[0]+'\u003c/div\u003e\u003cdiv style="font-size:13px;color:var(--txt)"\u003e'+h(x[1])+'\u003c/div\u003e\u003c/div\u003e';}).join('');return '\u003cdiv style="background:var(--bg2);border:1px solid var(--bdr);border-radius:15px;padding:22px;margin-bottom:18px"\u003e\u003cdiv style="display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:10px;margin-bottom:16px"\u003e\u003cdiv\u003e\u003cspan class="tag '+(k==='reguler'?'tr':'tg')+'"\u003e'+k.toUpperCase()+'\u003c/span\u003e\u003ch3 style="font-family:Syne,sans-serif;font-weight:700;font-size:17px;color:var(--txt);margin-top:8px"\u003e'+h(pr.title)+'\u003c/h3\u003e\u003c/div\u003e\u003cbutton class="edit-prog" data-key="'+k+'" style="cursor:pointer;background:transparent;color:var(--txt2);border:1px solid var(--bdr2);border-radius:10px;padding:8px 16px;font-family:inherit;font-weight:500;font-size:13px"\u003eEdit\u003c/button\u003e\u003c/div\u003e\u003cdiv style="display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:10px"\u003e'+inf+'\u003c/div\u003e\u003c/div\u003e';}).join('');}

function buildBranchesCms(){var rows=DB.branches.map(function(b){return '\u003ctr\u003e\u003ctd\u003e'+h(b.name)+'\u003c/td\u003e\u003ctd style="color:var(--txt2)"\u003e'+h(b.city)+'\u003c/td\u003e\u003ctd\u003e\u003cspan class="tag tb"\u003e'+h(b.province)+'\u003c/span\u003e\u003c/td\u003e\u003ctd style="color:var(--txt2)"\u003e'+fmtPhone(b.phone)+'\u003c/td\u003e\u003ctd style="color:var(--txt3)"\u003e'+h(b.user)+'\u003c/td\u003e\u003ctd\u003e\u003cbutton class="edit-branch" data-id="'+b.id+'" style="cursor:pointer;background:var(--bg3);color:var(--txt);border:1px solid var(--bdr);padding:5px 13px;border-radius:7px;font-weight:600;font-size:12px;font-family:inherit"\u003eEdit\u003c/button\u003e\u003c/td\u003e\u003c/tr\u003e';}).join('');return '\u003cdiv class="tw"\u003e\u003cdiv class="thr"\u003e\u003cspan style="font-family:Syne,sans-serif;font-weight:700;font-size:15px;color:var(--txt)"\u003eCabang\u003c/span\u003e\u003c/div\u003e\u003cdiv class="ts"\u003e\u003ctable\u003e\u003cthead\u003e\u003ctr\u003e\u003cth\u003eNama\u003c/th\u003e\u003cth\u003eKota\u003c/th\u003e\u003cth\u003eProv.\u003c/th\u003e\u003cth\u003eWA Admin\u003c/th\u003e\u003cth\u003eUsername\u003c/th\u003e\u003cth\u003eAksi\u003c/th\u003e\u003c/tr\u003e\u003c/thead\u003e\u003ctbody\u003e'+rows+'\u003c/tbody\u003e\u003c/table\u003e\u003c/div\u003e\u003c/div\u003e';}
function openEditBranch(id){var b=DB.branches.find(function(x){return x.id===id;});if(!b)return;var flds='\u003cdiv class="fg"\u003e\u003cdiv class="ff"\u003e\u003clabel class="lbl"\u003eNomor WA Admin (628xx)\u003c/label\u003e\u003cinput class="inp" id="bf-phone" type="tel" value="'+h(String(b.phone||''))+'"/\u003e\u003c/div\u003e\u003cdiv\u003e\u003clabel class="lbl"\u003eUsername\u003c/label\u003e\u003cinput class="inp" id="bf-user" type="text" value="'+h(b.user||'')+'"/\u003e\u003c/div\u003e\u003cdiv\u003e\u003clabel class="lbl"\u003ePassword\u003c/label\u003e\u003cinput class="inp" id="bf-pass" type="text" value="'+h(b.pass||'')+'"/\u003e\u003c/div\u003e\u003cdiv\u003e\u003clabel class="lbl"\u003eJam Operasional\u003c/label\u003e\u003cinput class="inp" id="bf-hours" type="text" value="'+h(b.hours||'')+'"/\u003e\u003c/div\u003e\u003cdiv class="ff"\u003e\u003clabel class="lbl"\u003eAlamat\u003c/label\u003e\u003ctextarea class="inp" id="bf-addr"\u003e'+h(b.address||'')+'\u003c/textarea\u003e\u003c/div\u003e\u003c/div\u003e\u003cdiv style="display:flex;gap:10px;margin-top:20px"\u003e\u003cbutton class="btn-r" style="flex:1;justify-content:center;padding:13px 0" onclick="saveBranch('+id+')"\u003eSimpan\u003c/button\u003e\u003cbutton class="btn-g" onclick="closeModal()" style="padding:13px 18px"\u003eBatal\u003c/button\u003e\u003c/div\u003e';openModal('Edit Cabang: '+h(b.name),flds);}
function saveBranch(id){DB.branches.forEach(function(b){if(b.id===id){b.phone=document.getElementById('bf-phone').value.trim();b.user=document.getElementById('bf-user').value.trim();b.pass=document.getElementById('bf-pass').value.trim();b.hours=document.getElementById('bf-hours').value.trim();b.address=document.getElementById('bf-addr').value.trim();}});sv('branches',DB.branches);closeModal();renderCms('branches');toast('Cabang disimpan!');}

function buildDiscountsCms(){var rows=DB.discounts.map(function(d){var tog='\u003cbutton class="tog-disc" data-id="'+d.id+'" style="cursor:pointer;background:'+(d.active?'var(--tn-bg)':'var(--tr-bg)')+';color:'+(d.active?'var(--tn-c)':'var(--tr-c)')+';border:1px solid '+(d.active?'var(--tn-br)':'var(--tr-br)')+';padding:5px 13px;border-radius:7px;font-weight:600;font-size:12px;font-family:inherit;margin-right:6px"\u003e'+(d.active?'\u2713 Aktif':'\u2717 Nonaktif')+'\u003c/button\u003e';var del='\u003cbutton class="del-disc" data-id="'+d.id+'" style="cursor:pointer;background:var(--tr-bg);color:var(--tr-c);border:1px solid var(--tr-br);padding:5px 13px;border-radius:7px;font-weight:600;font-size:12px;font-family:inherit"\u003eHapus\u003c/button\u003e';return '\u003ctr\u003e\u003ctd style="font-weight:700;color:var(--tg-c);letter-spacing:.7px"\u003e'+h(d.code)+'\u003c/td\u003e\u003ctd\u003e\u003cspan style="font-family:Syne,sans-serif;font-size:22px;font-weight:800;color:var(--tg-c)"\u003e'+d.pct+'%\u003c/span\u003e\u003c/td\u003e\u003ctd style="color:var(--txt2)"\u003e'+h(d.desc)+'\u003c/td\u003e\u003ctd style="color:var(--txt3)"\u003e'+(d.used||0)+'x\u003c/td\u003e\u003ctd style="white-space:nowrap"\u003e'+tog+del+'\u003c/td\u003e\u003c/tr\u003e';}).join('');return '\u003cdiv class="tw" style="margin-bottom:20px"\u003e\u003cdiv class="thr"\u003e\u003cspan style="font-family:Syne,sans-serif;font-weight:700;font-size:15px;color:var(--txt)"\u003eKode Diskon ('+DB.discounts.length+')\u003c/span\u003e\u003cbutton class="btn-r btn-sm" onclick="openAddDisc()"\u003e+ Tambah Kode\u003c/button\u003e\u003c/div\u003e\u003cdiv class="ts"\u003e\u003ctable\u003e\u003cthead\u003e\u003ctr\u003e\u003cth\u003eKode\u003c/th\u003e\u003cth\u003eDiskon\u003c/th\u003e\u003cth\u003eDeskripsi\u003c/th\u003e\u003cth\u003eDipakai\u003c/th\u003e\u003cth\u003eAksi\u003c/th\u003e\u003c/tr\u003e\u003c/thead\u003e\u003ctbody\u003e'+(rows||'\u003ctr\u003e\u003ctd colspan="5" style="padding:32px;text-align:center;color:var(--txt3)"\u003eBelum ada kode.\u003c/td\u003e\u003c/tr\u003e')+'\u003c/tbody\u003e\u003c/table\u003e\u003c/div\u003e\u003c/div\u003e';}
function openAddDisc(){var flds='\u003cdiv class="fg"\u003e\u003cdiv\u003e\u003clabel class="lbl"\u003eKode (kapital)\u003c/label\u003e\u003cinput class="inp" id="df-code" type="text" placeholder="MARKETING10" style="text-transform:uppercase"/\u003e\u003c/div\u003e\u003cdiv\u003e\u003clabel class="lbl"\u003ePersentase (%)\u003c/label\u003e\u003cinput class="inp" id="df-pct" type="number" min="1" max="100" value="10"/\u003e\u003c/div\u003e\u003cdiv class="ff"\u003e\u003clabel class="lbl"\u003eDeskripsi\u003c/label\u003e\u003cinput class="inp" id="df-desc" type="text" placeholder="Kode untuk tim marketing..."/\u003e\u003c/div\u003e\u003c/div\u003e\u003cdiv style="display:flex;gap:10px;margin-top:20px"\u003e\u003cbutton class="btn-r" style="flex:1;justify-content:center;padding:13px 0" onclick="saveDisc()"\u003e+ Tambahkan\u003c/button\u003e\u003cbutton class="btn-g" onclick="closeModal()" style="padding:13px 18px"\u003eBatal\u003c/button\u003e\u003c/div\u003e';openModal('Tambah Kode Diskon',flds);}
function saveDisc(){var code=document.getElementById('df-code').value.trim().toUpperCase();var pct=parseInt(document.getElementById('df-pct').value,10);if(!code||!pct){toast('Kode dan % wajib!','err');return;}if(DB.discounts.find(function(d){return d.code===code;})){toast('Kode sudah ada!','err');return;}DB.discounts.push({id:Date.now(),code:code,pct:pct,desc:document.getElementById('df-desc').value,active:true,used:0});sv('discounts',DB.discounts);closeModal();renderCms('discounts');toast(code+' ditambahkan!');}

function openEditProg(key){var pr=DB.progs[key];var flds='\u003cdiv class="fg"\u003e'+[['Nama','title','text'],['Tagline','tagline','text'],['Level','levels','text'],['Jadwal','schedule','text'],['Durasi','duration','text'],['Biaya','price','text']].map(function(f){return '\u003cdiv\u003e\u003clabel class="lbl"\u003e'+f[0]+'\u003c/label\u003e\u003cinput class="inp" id="pf-'+f[1]+'" type="'+f[2]+'" value="'+h(pr[f[1]]||'')+'"/\u003e\u003c/div\u003e';}).join('')+'\u003cdiv class="ff"\u003e\u003clabel class="lbl"\u003eDeskripsi\u003c/label\u003e\u003ctextarea class="inp" id="pf-desc"\u003e'+h(pr.desc||'')+'\u003c/textarea\u003e\u003c/div\u003e\u003c/div\u003e\u003cdiv style="display:flex;gap:10px;margin-top:20px"\u003e\u003cbutton class="btn-r" style="flex:1;justify-content:center;padding:13px 0" onclick="saveProg(\''+key+'\')"\u003eSimpan\u003c/button\u003e\u003cbutton class="btn-g" onclick="closeModal()" style="padding:13px 18px"\u003eBatal\u003c/button\u003e\u003c/div\u003e';openModal('Edit Program: '+h(pr.title),flds);}
function saveProg(key){['title','tagline','levels','schedule','duration','price','desc'].forEach(function(k){var el=document.getElementById('pf-'+k);if(el)DB.progs[key][k]=el.value;});sv('progs',DB.progs);closeModal();renderCms('progs');toast('Program diperbarui!');}


/* ═══ CMS: Cloud Storage Setup ═══════════════════════════════ */
function buildCloudCms(){
  var cfg=getCfg();
  var connected=!!(cfg.binId&&cfg.apiKey);
  var statusBadge=connected
    ?'\u003cspan class="tag tn"\u003e\u2601\uFE0F Terhubung ke Cloud\u003c/span\u003e'
    :'\u003cspan class="tag tp"\u003e\u26A0\uFE0F Belum dikonfigurasi (Mode Lokal)\u003c/span\u003e';

  return '\u003cdiv style="max-width:680px"\u003e'+
    '\u003cdiv style="background:var(--bg2);border:1px solid var(--bdr);border-radius:16px;padding:24px;margin-bottom:18px"\u003e'+
    '\u003cdiv style="display:flex;align-items:center;gap:12px;margin-bottom:16px"\u003e'+
    '\u003cdiv style="font-size:36px"\u003e\u2601\uFE0F\u003c/div\u003e'+
    '\u003cdiv\u003e\u003ch3 style="font-family:Syne,sans-serif;font-weight:800;font-size:18px;color:var(--txt);margin-bottom:4px"\u003eCloud Storage\u003c/h3\u003e'+
    statusBadge+'\u003c/div\u003e\u003c/div\u003e'+
    '\u003cp style="font-size:14px;color:var(--txt2);line-height:1.75;margin-bottom:18px"\u003eDengan Cloud Storage, semua data (pendaftaran, cabang, diskon, media, dll) tersimpan di cloud dan bisa diakses dari \u003cstrong style="color:var(--txt)"\u003eperangkat manapun\u003c/strong\u003e. Menggunakan \u003ca href="https://jsonbin.io" target="_blank" style="color:var(--ai-c)"\u003eJSONBin.io\u003c/a\u003e \u2014 gratis.\u003c/p\u003e'+
    '\u003cdiv style="background:var(--bg3);border:1px solid var(--bdr);border-radius:12px;padding:16px 18px;margin-bottom:20px"\u003e'+
    '\u003cdiv style="font-family:Syne,sans-serif;font-weight:700;font-size:13px;color:var(--txt);margin-bottom:10px"\u003e\uD83D\uDCCB Cara Setup (5 menit, gratis)\u003c/div\u003e'+
    [
      '1. Buka \u003ca href="https://jsonbin.io" target="_blank" style="color:var(--ai-c)"\u003ejsonbin.io\u003c/a\u003e \u2192 Sign Up gratis',
      '2. Masuk ke Dashboard \u2192 klik \u003cstrong\u003eAPI Keys\u003c/strong\u003e \u2192 copy \u003cstrong\u003eMaster Key\u003c/strong\u003e (dimulai dengan $2b$)',
      '3. Klik \u003cstrong\u003eNew Bin\u003c/strong\u003e \u2192 isi dengan \u003ccode style="background:var(--bg4);padding:1px 5px;border-radius:4px;font-size:12px"\u003e{}\u003c/code\u003e \u2192 Create',
      '4. Copy \u003cstrong\u003eBin ID\u003c/strong\u003e dari URL (contoh: \u003ccode style="background:var(--bg4);padding:1px 5px;border-radius:4px;font-size:12px"\u003e64abc123...\u003c/code\u003e)',
      '5. Paste di kolom bawah \u2192 klik Simpan & Sinkronkan'
    ].map(function(s){return '\u003cdiv style="font-size:13px;color:var(--txt2);padding:5px 0;line-height:1.6"\u003e'+s+'\u003c/div\u003e';}).join('')+
    '\u003c/div\u003e'+
    '\u003cdiv class="fg"\u003e'+
    '\u003cdiv class="ff"\u003e\u003clabel class="lbl"\u003eMaster Key (API Key JSONBin) *\u003c/label\u003e\u003cinput class="inp" id="cl-key" type="password" placeholder="$2b$10$..." value="'+(cfg.apiKey||'')+'"/\u003e\u003c/div\u003e'+
    '\u003cdiv class="ff"\u003e\u003clabel class="lbl"\u003eBin ID *\u003c/label\u003e\u003cinput class="inp" id="cl-bin" type="text" placeholder="64abc123def456..." value="'+(cfg.binId||'')+'"/\u003e\u003c/div\u003e'+
    '\u003c/div\u003e'+
    '\u003cdiv style="display:flex;gap:10px;margin-top:18px;flex-wrap:wrap"\u003e'+
    '\u003cbutton class="btn-r" style="padding:12px 26px" onclick="saveCloudCfg()"\u003e\u2601\uFE0F Simpan & Sinkronkan\u003c/button\u003e'+
    (connected?'\u003cbutton class="btn-g" onclick="syncFromCloud()" style="padding:12px 26px"\u003e\u21BB Ambil Data dari Cloud\u003c/button\u003e':'')+ 
    (connected?'\u003cbutton onclick="disconnectCloud()" style="cursor:pointer;background:var(--tr-bg);color:var(--tr-c);border:1px solid var(--tr-br);border-radius:11px;padding:12px 20px;font-family:inherit;font-weight:600;font-size:14px"\u003e\u274C Putuskan\u003c/button\u003e':'')+
    '\u003c/div\u003e\u003c/div\u003e'+
    (connected?
    '\u003cdiv style="background:var(--tn-bg);border:1px solid var(--tn-br);border-radius:12px;padding:16px 18px;margin-top:12px"\u003e'+
    '\u003cdiv style="font-family:Syne,sans-serif;font-weight:700;font-size:13px;color:var(--tn-c);margin-bottom:6px"\u003e\u2714 Cloud Aktif\u003c/div\u003e'+
    '\u003cp style="font-size:13px;color:var(--txt2);line-height:1.65"\u003eSemua perubahan data (tambah/hapus/edit) otomatis tersimpan ke cloud. Data bisa diakses dari perangkat lain setelah login admin.\u003c/p\u003e'+
    '\u003c/div\u003e'
    :
    '\u003cdiv style="background:var(--tp-bg);border:1px solid var(--tp-br);border-radius:12px;padding:16px 18px;margin-top:12px"\u003e'+
    '\u003cdiv style="font-family:Syne,sans-serif;font-weight:700;font-size:13px;color:var(--tp-c);margin-bottom:6px"\u003e\u26A0\uFE0F Mode Lokal Aktif\u003c/div\u003e'+
    '\u003cp style="font-size:13px;color:var(--txt2);line-height:1.65"\u003eData tersimpan di browser ini saja. Untuk akses dari perangkat lain, konfigurasi Cloud Storage di atas.\u003c/p\u003e'+
    '\u003c/div\u003e')+
    '\u003c/div\u003e';
}

function saveCloudCfg(){
  var key=document.getElementById('cl-key').value.trim();
  var bin=document.getElementById('cl-bin').value.trim();
  if(!key||!bin){toast('API Key dan Bin ID wajib diisi!','err');return;}
  saveCfg({apiKey:key,binId:bin});
  // Immediately push current DB to cloud
  cloudSave();
  toast('Cloud Storage dikonfigurasi! Data sedang disinkronkan...');
  setTimeout(function(){renderCms('cloud');},800);
}

function syncFromCloud(){
  var cfg=getCfg();if(!cfg.binId||!cfg.apiKey){toast('Cloud belum dikonfigurasi','err');return;}
  toast('Mengambil data dari cloud...');
  fetch('https://api.jsonbin.io/v3/b/'+cfg.binId+'/latest',{
    headers:{'X-Master-Key':cfg.apiKey,'X-Bin-Meta':'false'}
  })
  .then(function(r){return r.json();})
  .then(function(res){
    if(res&&typeof res==='object'){
      Object.keys(DEF).forEach(function(k){
        if(res[k]!==undefined){
          DB[k]=res[k];
          try{localStorage.setItem('bba_'+k,JSON.stringify(DB[k]));}catch(e){}
        }
      });
      toast('Data berhasil diambil dari cloud!');
      renderCms('dashboard');
    } else {toast('Data cloud kosong atau error','err');}
  })
  .catch(function(){toast('Gagal terhubung ke cloud','err');});
}

function disconnectCloud(){
  if(!confirm('Yakin ingin memutus Cloud Storage? Data tetap tersimpan di browser ini.'))return;
  localStorage.removeItem('bba_cloud');
  toast('Cloud Storage diputus. Menggunakan mode lokal.');
  renderCms('cloud');
}

/* ═══════════ MODAL ═══════════ */
function openModal(title,bodyHtml,size){document.getElementById('modal-title').textContent=title;document.getElementById('modal-body').innerHTML=bodyHtml;document.getElementById('modal-box').className='mb'+(size?' '+size:'');document.getElementById('modal').classList.add('open');}
function closeModal(){document.getElementById('modal').classList.remove('open');}

/* ═══════════ EVENT DELEGATION ═══════════ */
document.addEventListener('click',function(e){
  var t=e.target;
  if(t.classList.contains('apr-btn')){approveReg(Number(t.dataset.id),'Disetujui');return;}
  if(t.classList.contains('rej-btn')){approveReg(Number(t.dataset.id),'Ditolak');return;}
  if(t.classList.contains('del-media')){var sec=t.dataset.sec,id=Number(t.dataset.id);DB[sec]=DB[sec].filter(function(x){return x.id!==id;});sv(sec,DB[sec]);renderCms(sec);toast('Dihapus.');return;}
  if(t.classList.contains('del-grad')){DB.grads=DB.grads.filter(function(x){return x.id!==Number(t.dataset.id);});sv('grads',DB.grads);renderCms('grads');toast('Dihapus.');return;}
  if(t.classList.contains('del-disc')){var id=Number(t.dataset.id);DB.discounts=DB.discounts.filter(function(x){return x.id!==id;});sv('discounts',DB.discounts);renderCms('discounts');return;}
  if(t.classList.contains('tog-disc')){var id=Number(t.dataset.id);DB.discounts.forEach(function(d){if(d.id===id)d.active=!d.active;});sv('discounts',DB.discounts);renderCms('discounts');return;}
  if(t.classList.contains('del-to')){var id=Number(t.dataset.id);DB.tryouts=DB.tryouts.filter(function(x){return x.id!==id;});sv('tryouts',DB.tryouts);renderCms('tryouts');toast('Paket try out dihapus.');return;}
  if(t.classList.contains('del-app')){var id=Number(t.dataset.id);DB.extApps=DB.extApps.filter(function(x){return x.id!==id;});sv('extApps',DB.extApps);renderCms('extapps');toast('Aplikasi dihapus.');return;}
  if(t.classList.contains('edit-prog')){openEditProg(t.dataset.key);return;}
  if(t.classList.contains('edit-branch')){openEditBranch(Number(t.dataset.id));return;}
});


loadData();

</script>

</body>
</html>
