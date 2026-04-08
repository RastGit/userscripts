<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>RastHub — Script Library</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;900&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --bg:#0a0a0f;--bg2:#0f0f18;--bg3:#13131f;
  --surface:#16162a;--surface2:#1c1c33;
  --border:rgba(120,80,255,0.15);--border2:rgba(120,80,255,0.3);
  --purple:#7c3aed;--purple2:#9d6fff;--purple3:#c4a3ff;
  --neon:#a855f7;--neon2:#c084fc;
  --text:#f0eeff;--text2:#a89cc8;--text3:#6b5f8a;
  --font:'Inter',sans-serif;--mono:'JetBrains Mono',monospace;
}
html{scroll-behavior:smooth}
body{background:var(--bg);color:var(--text);font-family:var(--font);min-height:100vh;overflow-x:hidden}
body::before{content:'';position:fixed;inset:0;background-image:url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.85' numOctaves='4'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");pointer-events:none;z-index:0;opacity:.35}
.blob{position:fixed;border-radius:50%;filter:blur(120px);pointer-events:none;z-index:0}
.b1{width:700px;height:700px;background:rgba(124,58,237,.11);top:-250px;right:-150px}
.b2{width:450px;height:450px;background:rgba(168,85,247,.07);bottom:10%;left:-150px}
.b3{width:350px;height:350px;background:rgba(59,7,100,.14);top:45%;left:38%}

/* NAV */
nav{position:fixed;top:0;left:0;right:0;z-index:100;padding:0 2rem;height:64px;display:flex;align-items:center;justify-content:space-between;background:rgba(10,10,15,.75);backdrop-filter:blur(24px) saturate(1.6);-webkit-backdrop-filter:blur(24px) saturate(1.6);border-bottom:1px solid var(--border)}
.nav-logo{display:flex;align-items:center;gap:10px;text-decoration:none}
.logo-mark{width:34px;height:34px;background:linear-gradient(135deg,#7c3aed,#a855f7);border-radius:9px;display:flex;align-items:center;justify-content:center;font-weight:900;font-size:15px;color:#fff;box-shadow:0 0 18px rgba(124,58,237,.55);position:relative;overflow:hidden}
.logo-mark::after{content:'';position:absolute;inset:0;background:linear-gradient(135deg,rgba(255,255,255,.22),transparent)}
.logo-text{font-size:18px;font-weight:700;letter-spacing:-.5px;color:var(--text)}
.logo-text span{color:var(--neon2)}
.nav-tabs{display:flex;gap:2px;background:rgba(255,255,255,.04);border-radius:10px;padding:3px;border:1px solid var(--border)}
.nav-tab{padding:6px 18px;border-radius:7px;font-size:13px;font-weight:500;color:var(--text2);cursor:pointer;transition:all .2s;border:none;background:transparent;font-family:var(--font)}
.nav-tab:hover{color:var(--text);background:rgba(255,255,255,.05)}
.nav-tab.active{background:linear-gradient(135deg,rgba(124,58,237,.4),rgba(168,85,247,.28));color:var(--purple3);box-shadow:0 0 14px rgba(124,58,237,.2),inset 0 1px 0 rgba(255,255,255,.1)}
.nav-badge{font-size:12px;color:var(--text3);font-family:var(--mono)}

/* HERO */
.hero{position:relative;z-index:1;padding:160px 2rem 100px;text-align:center;max-width:900px;margin:0 auto}
.hero-tag{display:inline-flex;align-items:center;gap:7px;padding:5px 15px;background:rgba(124,58,237,.1);border:1px solid rgba(124,58,237,.25);border-radius:100px;font-size:12px;font-weight:500;color:var(--purple3);margin-bottom:28px;letter-spacing:.5px;text-transform:uppercase}
.hero-tag::before{content:'';width:6px;height:6px;background:var(--neon);border-radius:50%;box-shadow:0 0 7px var(--neon);animation:pulse 2s ease-in-out infinite}
@keyframes pulse{0%,100%{opacity:1;transform:scale(1)}50%{opacity:.4;transform:scale(.8)}}
.hero h1{font-size:clamp(52px,9vw,92px);font-weight:900;line-height:1;letter-spacing:-3px;margin-bottom:24px;background:linear-gradient(140deg,#f0eeff 0%,#c4a3ff 50%,#7c3aed 100%);-webkit-background-clip:text;background-clip:text;-webkit-text-fill-color:transparent}
.hero p{font-size:18px;color:var(--text2);line-height:1.75;max-width:540px;margin:0 auto 40px;font-weight:300}
.hero-stats{display:flex;justify-content:center;gap:52px;margin-top:56px;padding-top:40px;border-top:1px solid var(--border)}
.stat{text-align:center}
.stat-num{font-size:34px;font-weight:700;color:var(--purple3);display:block}
.stat-label{font-size:11px;color:var(--text3);text-transform:uppercase;letter-spacing:1.2px;margin-top:4px}

/* SECTION */
section{position:relative;z-index:1;max-width:1120px;margin:0 auto;padding:0 2rem 80px}
.section-header{display:flex;align-items:baseline;justify-content:space-between;margin-bottom:32px}
.section-title{font-size:22px;font-weight:600;letter-spacing:-.5px}
.section-count{font-size:13px;color:var(--text3);font-family:var(--mono)}

/* SEARCH */
.search-wrap{position:relative;margin-bottom:28px}
.si{position:absolute;left:16px;top:50%;transform:translateY(-50%);color:var(--text3);pointer-events:none;display:flex}
.search-input{width:100%;padding:13px 16px 13px 44px;background:var(--surface);border:1px solid var(--border);border-radius:12px;color:var(--text);font-size:14px;font-family:var(--font);outline:none;transition:border .2s,box-shadow .2s}
.search-input::placeholder{color:var(--text3)}
.search-input:focus{border-color:var(--border2);box-shadow:0 0 0 3px rgba(124,58,237,.12)}

/* CHIPS */
.filters{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:32px}
.chip{padding:6px 15px;background:rgba(255,255,255,.03);border:1px solid var(--border);border-radius:100px;font-size:12px;font-weight:500;color:var(--text2);cursor:pointer;transition:all .2s;font-family:var(--font)}
.chip:hover{border-color:var(--border2);color:var(--purple3)}
.chip.active{background:rgba(124,58,237,.15);border-color:rgba(124,58,237,.4);color:var(--purple3);box-shadow:0 0 12px rgba(124,58,237,.15)}

/* GRID */
.scripts-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(310px,1fr));gap:16px}

/* CARD */
.script-card{background:var(--surface);border:1px solid var(--border);border-radius:16px;padding:24px;cursor:pointer;transition:all .3s cubic-bezier(.4,0,.2,1);position:relative;overflow:hidden}
.script-card::before{content:'';position:absolute;inset:0;background:linear-gradient(135deg,rgba(124,58,237,.05),transparent 60%);opacity:0;transition:opacity .3s}
.script-card::after{content:'';position:absolute;top:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,rgba(168,85,247,.5),transparent);opacity:0;transition:opacity .3s}
.script-card:hover{border-color:var(--border2);transform:translateY(-3px);box-shadow:0 12px 40px rgba(0,0,0,.35),0 0 36px rgba(124,58,237,.1)}
.script-card:hover::before,.script-card:hover::after{opacity:1}
.card-top{display:flex;align-items:flex-start;justify-content:space-between;margin-bottom:16px}
.card-icon{width:48px;height:48px;border-radius:12px;background:linear-gradient(135deg,rgba(124,58,237,.2),rgba(168,85,247,.1));border:1px solid rgba(124,58,237,.2);display:flex;align-items:center;justify-content:center;font-size:22px;flex-shrink:0;overflow:hidden}
.card-icon img{width:28px;height:28px;border-radius:6px;object-fit:contain}
.card-badge{padding:3px 10px;border-radius:100px;font-size:11px;font-weight:600;text-transform:uppercase;letter-spacing:.5px}
.bu{background:rgba(124,58,237,.15);color:var(--purple3);border:1px solid rgba(124,58,237,.25)}
.bt{background:rgba(245,158,11,.1);color:#fcd34d;border:1px solid rgba(245,158,11,.2)}
.bg{background:rgba(34,197,94,.1);color:#86efac;border:1px solid rgba(34,197,94,.2)}
.card-name{font-size:16px;font-weight:600;color:var(--text);margin-bottom:6px;letter-spacing:-.3px}
.card-desc{font-size:13px;color:var(--text2);line-height:1.65;margin-bottom:20px}
.card-meta{display:flex;align-items:center;justify-content:space-between;padding-top:16px;border-top:1px solid var(--border)}
.card-link{font-size:12px;color:var(--text3);font-family:var(--mono);display:flex;align-items:center;gap:5px}
.btn-primary{padding:6px 14px;background:linear-gradient(135deg,rgba(124,58,237,.6),rgba(168,85,247,.48));border:1px solid rgba(124,58,237,.4);border-radius:8px;font-size:12px;font-weight:600;color:#e9d5ff;cursor:pointer;transition:all .2s;font-family:var(--font);display:flex;align-items:center;gap:5px;box-shadow:0 0 12px rgba(124,58,237,.2)}
.btn-primary:hover{box-shadow:0 0 22px rgba(124,58,237,.4);transform:translateY(-1px)}

/* MARQUEE */
.mq-section{position:relative;z-index:1;padding:0 0 80px;overflow:hidden}
.mq-label{text-align:center;font-size:11px;text-transform:uppercase;letter-spacing:2px;color:var(--text3);margin-bottom:28px}
.mq-wrap{display:flex;overflow:hidden;mask-image:linear-gradient(90deg,transparent,black 10%,black 90%,transparent);-webkit-mask-image:linear-gradient(90deg,transparent,black 10%,black 90%,transparent)}
.mq-track{display:flex;gap:14px;animation:mq 28s linear infinite;width:max-content}
@keyframes mq{0%{transform:translateX(0)}100%{transform:translateX(-50%)}}
.mq-item{display:flex;align-items:center;gap:10px;padding:9px 18px;background:var(--surface);border:1px solid var(--border);border-radius:100px;white-space:nowrap;cursor:pointer;transition:border-color .2s}
.mq-item:hover{border-color:var(--border2)}
.mq-icon{width:22px;height:22px;border-radius:5px;background:rgba(124,58,237,.2);display:flex;align-items:center;justify-content:center;font-size:12px;overflow:hidden}
.mq-icon img{width:16px;height:16px;border-radius:3px;object-fit:contain}
.mq-name{font-size:13px;font-weight:500;color:var(--text2)}

/* FOOTER */
footer{position:relative;z-index:1;border-top:1px solid var(--border);padding:48px 2rem;text-align:center}
.footer-logo{font-size:26px;font-weight:900;letter-spacing:-1px;margin-bottom:12px;background:linear-gradient(135deg,#f0eeff,#9d6fff);-webkit-background-clip:text;background-clip:text;-webkit-text-fill-color:transparent}
.footer-text{font-size:13px;color:var(--text3);margin-bottom:24px}
.footer-links{display:flex;justify-content:center;gap:28px;flex-wrap:wrap}
.footer-link{font-size:13px;color:var(--text3);text-decoration:none;transition:color .2s}
.footer-link:hover{color:var(--purple3)}

/* MODAL */
.modal-overlay{position:fixed;inset:0;z-index:200;background:rgba(5,5,10,.88);backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px);display:flex;align-items:center;justify-content:center;padding:24px;opacity:0;pointer-events:none;transition:opacity .25s}
.modal-overlay.open{opacity:1;pointer-events:all}
.modal{background:var(--bg2);border:1px solid var(--border2);border-radius:20px;width:100%;max-width:640px;max-height:82vh;overflow-y:auto;box-shadow:0 28px 72px rgba(0,0,0,.55),0 0 56px rgba(124,58,237,.18);transform:translateY(12px) scale(.97);transition:transform .28s cubic-bezier(.4,0,.2,1);position:relative}
.modal::before{content:'';position:absolute;top:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent 8%,rgba(168,85,247,.55) 50%,transparent 92%)}
.modal-overlay.open .modal{transform:translateY(0) scale(1)}
.modal-head{display:flex;align-items:center;justify-content:space-between;padding:24px 24px 20px;border-bottom:1px solid var(--border)}
.modal-tg{display:flex;align-items:center;gap:14px}
.modal-icon{width:44px;height:44px;border-radius:11px;background:rgba(124,58,237,.15);border:1px solid rgba(124,58,237,.25);display:flex;align-items:center;justify-content:center;font-size:21px;overflow:hidden}
.modal-icon img{width:27px;height:27px;border-radius:5px;object-fit:contain}
.modal-name{font-size:18px;font-weight:600;letter-spacing:-.4px}
.modal-sub{font-size:12px;color:var(--text3);font-family:var(--mono);margin-top:2px}
.modal-close{width:32px;height:32px;background:rgba(255,255,255,.05);border:1px solid var(--border);border-radius:8px;cursor:pointer;display:flex;align-items:center;justify-content:center;color:var(--text2);font-size:16px;transition:all .2s}
.modal-close:hover{background:rgba(255,255,255,.09);color:var(--text)}
.modal-body{padding:24px}
.modal-tabs{display:flex;gap:2px;background:rgba(255,255,255,.03);border-radius:10px;padding:3px;border:1px solid var(--border);margin-bottom:20px}
.modal-tab{flex:1;padding:8px;border-radius:7px;font-size:13px;font-weight:500;color:var(--text2);cursor:pointer;transition:all .2s;border:none;background:transparent;font-family:var(--font);text-align:center}
.modal-tab.active{background:linear-gradient(135deg,rgba(124,58,237,.35),rgba(168,85,247,.25));color:var(--purple3);box-shadow:inset 0 1px 0 rgba(255,255,255,.08)}
.tab-content{display:none}
.tab-content.active{display:block}
.code-block{background:rgba(5,5,10,.85);border:1px solid var(--border);border-radius:12px;padding:20px;font-family:var(--mono);font-size:13px;color:#c4a3ff;line-height:1.75;overflow-x:auto;position:relative;white-space:pre}
.code-block .cm{color:var(--text3)}
.code-block .kw{color:#818cf8}
.code-block .sv{color:#86efac}
.modal-actions{display:flex;gap:10px;margin-top:16px}
.btn-copy{flex:1;padding:11px;background:rgba(255,255,255,.04);border:1px solid var(--border);border-radius:10px;font-size:14px;font-weight:500;color:var(--text2);cursor:pointer;transition:all .2s;font-family:var(--font);display:flex;align-items:center;justify-content:center;gap:8px}
.btn-copy:hover{border-color:var(--border2);color:var(--text);background:rgba(255,255,255,.07)}
.btn-copy.copied{border-color:rgba(34,197,94,.3);color:#86efac;background:rgba(34,197,94,.05)}
.btn-install{flex:2;padding:11px;background:linear-gradient(135deg,rgba(124,58,237,.58),rgba(168,85,247,.46));border:1px solid rgba(124,58,237,.42);border-radius:10px;font-size:14px;font-weight:600;color:#e9d5ff;cursor:pointer;transition:all .2s;font-family:var(--font);display:flex;align-items:center;justify-content:center;gap:8px;box-shadow:0 0 22px rgba(124,58,237,.22)}
.btn-install:hover{box-shadow:0 0 36px rgba(124,58,237,.42);transform:translateY(-1px)}
.install-note{margin-top:14px;padding:12px 16px;background:rgba(124,58,237,.06);border:1px solid rgba(124,58,237,.13);border-radius:10px;font-size:12px;color:var(--text3);line-height:1.65}
.install-note strong{color:var(--purple3);font-weight:500}
.empty-state{grid-column:1/-1;text-align:center;padding:80px 20px;color:var(--text3)}
.empty-state p{font-size:15px;margin-top:16px}

/* ABOUT/DOCS */
.prose h2{font-size:28px;font-weight:700;margin-bottom:20px;letter-spacing:-.5px}
.prose p{color:var(--text2);line-height:1.8;margin-bottom:18px}
.prose code{background:var(--surface);padding:2px 8px;border-radius:5px;font-family:var(--mono);font-size:13px;color:var(--purple3)}
.step-card{background:var(--surface);border:1px solid var(--border);border-radius:14px;padding:20px 24px;display:flex;gap:16px;align-items:flex-start;margin-bottom:14px}
.step-num{width:28px;height:28px;background:rgba(124,58,237,.2);border-radius:8px;display:flex;align-items:center;justify-content:center;font-size:13px;font-weight:700;color:var(--purple3);flex-shrink:0}
.step-title{font-weight:600;margin-bottom:5px}
.step-desc{font-size:13px;color:var(--text2)}
.step-desc strong{color:var(--purple3);font-weight:500}

::-webkit-scrollbar{width:5px;height:5px}
::-webkit-scrollbar-track{background:transparent}
::-webkit-scrollbar-thumb{background:rgba(124,58,237,.3);border-radius:3px}
::-webkit-scrollbar-thumb:hover{background:rgba(124,58,237,.5)}

@media(max-width:640px){.nav-tabs{display:none}.hero h1{letter-spacing:-2px}.hero-stats{gap:24px}.scripts-grid{grid-template-columns:1fr}}
</style>
</head>
<body>

<div class="blob b1"></div>
<div class="blob b2"></div>
<div class="blob b3"></div>

<nav>
  <a class="nav-logo" href="#">
    <div class="logo-mark">R</div>
    <span class="logo-text">Rast<span>Hub</span></span>
  </a>
  <div class="nav-tabs">
    <button class="nav-tab active" onclick="setTab('scripts',this)">Scripts</button>
    <button class="nav-tab" onclick="setTab('about',this)">About</button>
    <button class="nav-tab" onclick="setTab('docs',this)">Docs</button>
  </div>
  <span class="nav-badge" id="total-count">0 scripts</span>
</nav>

<div class="hero">
  <div class="hero-tag">Open Source Script Library</div>
  <h1>RastHub</h1>
  <p>Kolekcja userscriptów i narzędzi. Instaluj jednym kliknięciem, używaj od razu.</p>
  <div class="hero-stats">
    <div class="stat"><span class="stat-num" id="stat-n">0</span><span class="stat-label">Skryptów</span></div>
    <div class="stat"><span class="stat-num">∞</span><span class="stat-label">Możliwości</span></div>
    <div class="stat"><span class="stat-num">100%</span><span class="stat-label">Open Source</span></div>
  </div>
</div>

<section id="sec-scripts">
  <div class="section-header">
    <span class="section-title">Wszystkie skrypty</span>
    <span class="section-count" id="showing">0 wyników</span>
  </div>
  <div class="search-wrap">
    <span class="si"><svg width="16" height="16" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.35-4.35"/></svg></span>
    <input class="search-input" id="search" type="text" placeholder="Szukaj skryptów..." oninput="render()">
  </div>
  <div class="filters" id="chips"></div>
  <div class="scripts-grid" id="grid"></div>
</section>

<section id="sec-about" style="display:none">
  <div class="prose" style="max-width:640px">
    <h2>Co to jest RastHub?</h2>
    <p>RastHub to osobista biblioteka skryptów i userscriptów. Każdy skrypt jest hostowany na GitHubie i można go zainstalować jednym kliknięciem przez Tampermonkey lub Greasemonkey.</p>
    <p>Żeby dodać nowy skrypt — edytuj <code>index.html</code> i wrzuć wpis do tablicy <code>scripts</code> na dole pliku w formacie komentarza.</p>
    <div class="code-block"><span class="cm">// Skrypty //</span>
<span class="kw">Link</span>: https://raw.githubusercontent.com/user/repo/main/script.user.js
<span class="kw">Name</span>: NazwaSkryptu
<span class="kw">Icon</span>: https://github.com/user/icon.png
<span class="kw">Desc</span>: Krótki opis tego co skrypt robi
<span class="kw">Tag</span>: userscript</div>
  </div>
</section>

<section id="sec-docs" style="display:none">
  <div style="max-width:640px">
    <div class="prose"><h2>Jak zainstalować?</h2></div>
    <div class="step-card"><div class="step-num">1</div><div><div class="step-title">Zainstaluj menedżer skryptów</div><div class="step-desc">Pobierz <strong>Tampermonkey</strong> lub <strong>Greasemonkey</strong> dla swojej przeglądarki ze sklepu z rozszerzeniami.</div></div></div>
    <div class="step-card"><div class="step-num">2</div><div><div class="step-title">Kliknij "Zainstaluj"</div><div class="step-desc">Na karcie każdego skryptu kliknij przycisk <strong>Zainstaluj Skrypt</strong> — otworzy się dialog potwierdzenia.</div></div></div>
    <div class="step-card"><div class="step-num">3</div><div><div class="step-title">Gotowe!</div><div class="step-desc">Skrypt zainstaluje się automatycznie. Odśwież stronę docelową żeby zobaczyć efekty.</div></div></div>
  </div>
</section>

<div class="mq-section" id="mq-section">
  <p class="mq-label">Dostępne skrypty</p>
  <div class="mq-wrap"><div class="mq-track" id="mq-track"></div></div>
</div>

<footer>
  <div class="footer-logo">RastHub</div>
  <p class="footer-text">Zbudowane z ♥ i fioletowym neonem</p>
  <div class="footer-links">
    <a href="#" class="footer-link">GitHub</a>
    <a href="#" class="footer-link">Skrypty</a>
    <a href="#" class="footer-link">Docs</a>
    <a href="#" class="footer-link">O projekcie</a>
  </div>
</footer>

<!-- MODAL -->
<div class="modal-overlay" id="modal" onclick="closeOv(event)">
  <div class="modal" id="mbox">
    <div class="modal-head">
      <div class="modal-tg">
        <div class="modal-icon" id="m-icon">📜</div>
        <div><div class="modal-name" id="m-name">Script</div><div class="modal-sub" id="m-link">github.com/...</div></div>
      </div>
      <button class="modal-close" onclick="closeModal()">✕</button>
    </div>
    <div class="modal-body">
      <div class="modal-tabs">
        <button class="modal-tab active" onclick="mtab('install',this)">Instalacja</button>
        <button class="modal-tab" onclick="mtab('code',this)">Kod instalacyjny</button>
      </div>
      <div class="tab-content active" id="tab-install">
        <div class="modal-actions">
          <button class="btn-copy" id="cp1" onclick="cp1()">
            <svg width="14" height="14" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><rect x="9" y="9" width="13" height="13" rx="2"/><path d="M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1"/></svg>
            Kopiuj link
          </button>
          <button class="btn-install" id="inst" onclick="inst()">
            <svg width="14" height="14" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
            Zainstaluj Skrypt
          </button>
        </div>
        <div class="install-note">Wymagany <strong>Tampermonkey</strong> lub <strong>Greasemonkey</strong>. Po kliknięciu "Zainstaluj" przeglądarka zapyta o potwierdzenie.</div>
      </div>
      <div class="tab-content" id="tab-code">
        <div class="code-block" id="m-code">// kod</div>
        <div class="modal-actions">
          <button class="btn-copy" id="cp2" onclick="cp2()">
            <svg width="14" height="14" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><rect x="9" y="9" width="13" height="13" rx="2"/><path d="M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1"/></svg>
            Kopiuj kod
          </button>
        </div>
      </div>
    </div>
  </div>
</div>

<script>
// ================================================================
//  SKRYPTY — dodaj tutaj swoje skrypty
//  Format komentarza (informacyjny):
//  Link: URL_do_.user.js  Name: Nazwa  Icon: URL_ikony
//  Desc: Opis  Tag: userscript | utility | tool
// ================================================================
const scripts = [
  {
    link: "https://raw.githubusercontent.com/example/scripts/main/example.user.js",
    name: "ExampleScript",
    icon: "https://raw.githubusercontent.com/github/explore/main/topics/javascript/javascript.png",
    desc: "Przykładowy skrypt demonstracyjny. Zastąp swoim własnym skryptem edytując tablicę scripts.",
    tag: "userscript"
  }
  // ---- DODAJ KOLEJNE SKRYPTY PONIŻEJ ----
  // {
  //   link: "https://raw.githubusercontent.com/TWOJ_USER/REPO/main/SKRYPT.user.js",
  //   name: "NazwaSkryptu",
  //   icon: "https://github.com/TWOJ_USER/IKONA.png",
  //   desc: "Opis co robi skrypt",
  //   tag: "userscript"
  // },
];
// ================================================================

let activeTag = 'all', cur = null;

const ic = s => s.icon?.startsWith('http')
  ? `<img src="${s.icon}" alt="${s.name}" onerror="this.style.display='none';this.parentElement.textContent='📜'">`
  : '📜';

const installCode = s =>
`// ==UserScript==
// @name         ${s.name}
// @namespace    rasthub
// @version      1.0
// @description  ${s.desc||''}
// @match        *://*/*
// @grant        none
// ==/UserScript==
// Instalacja: ${s.link}`;

function getTags(){
  const t = new Set(['all']);
  scripts.forEach(s=>s.tag&&t.add(s.tag));
  return [...t];
}

function renderChips(){
  document.getElementById('chips').innerHTML = getTags().map(t =>
    `<button class="chip${t===activeTag?' active':''}" onclick="setFilter('${t}')">${t==='all'?'Wszystkie':t}</button>`
  ).join('');
}

function setFilter(t){ activeTag=t; renderChips(); render(); }

function filtered(){
  const q = document.getElementById('search').value.toLowerCase();
  return scripts.filter(s=>{
    const mt = activeTag==='all'||s.tag===activeTag;
    const mq = !q||s.name.toLowerCase().includes(q)||(s.desc||'').toLowerCase().includes(q);
    return mt&&mq;
  });
}

function render(){
  const f = filtered();
  document.getElementById('showing').textContent = f.length+' wyników';
  const grid = document.getElementById('grid');
  if(!f.length){
    grid.innerHTML = `<div class="empty-state"><svg width="40" height="40" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.35-4.35"/></svg><p>Brak skryptów dla tego zapytania</p></div>`;
    return;
  }
  grid.innerHTML = f.map(s=>{
    const i = scripts.indexOf(s);
    const tc = s.tag==='tool'?'bt':s.tag==='utility'?'bg':'bu';
    const lnk = (s.link||'').replace(/https?:\/\//,'').split('/').slice(0,4).join('/');
    return `<div class="script-card" onclick="openModal(${i})">
      <div class="card-top">
        <div class="card-icon">${ic(s)}</div>
        <span class="card-badge ${tc}">${s.tag||'script'}</span>
      </div>
      <div class="card-name">${s.name}</div>
      <div class="card-desc">${s.desc||'Brak opisu.'}</div>
      <div class="card-meta">
        <span class="card-link"><svg width="12" height="12" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"/></svg>${lnk}</span>
        <button class="btn-primary" onclick="event.stopPropagation();openModal(${i})"><svg width="12" height="12" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>Instaluj</button>
      </div>
    </div>`;
  }).join('');
}

function renderMarquee(){
  const t = document.getElementById('mq-track');
  const d = [...scripts,...scripts];
  t.innerHTML = d.map((s,i)=>`
    <div class="mq-item" onclick="openModal(${i%scripts.length})">
      <div class="mq-icon">${ic(s)}</div>
      <span class="mq-name">${s.name}</span>
    </div>`).join('');
}

function updateStats(){
  const n=scripts.length;
  document.getElementById('stat-n').textContent=n;
  document.getElementById('total-count').textContent=`${n} skrypt${n===1?'':n<5?'y':'ów'}`;
}

function openModal(i){
  const s=scripts[i]; if(!s) return; cur=s;
  document.getElementById('m-icon').innerHTML = ic(s);
  document.getElementById('m-name').textContent = s.name;
  document.getElementById('m-link').textContent = (s.link||'').replace(/https?:\/\//,'').split('/').slice(0,4).join('/');
  const raw = installCode(s);
  document.getElementById('m-code').innerHTML = raw
    .replace(/\/\/ ==UserScript==/g,'<span class="cm">// ==UserScript==</span>')
    .replace(/\/\/ ==/g,'<span class="cm">// ==</span>')
    .replace(/@(\w+)/g,'<span class="kw">@$1</span>')
    .replace(/(\/\/ Instalacja:.*)/g,'<span class="sv">$1</span>');
  document.getElementById('inst').dataset.url = s.link||'';
  document.getElementById('modal').classList.add('open');
  document.body.style.overflow='hidden';
  mtab('install', document.querySelector('.modal-tab'));
}

function closeOv(e){ if(e.target===document.getElementById('modal')) closeModal(); }
function closeModal(){ document.getElementById('modal').classList.remove('open'); document.body.style.overflow=''; }

function mtab(tab, btn){
  document.querySelectorAll('.modal-tab').forEach(t=>t.classList.remove('active'));
  document.querySelectorAll('.tab-content').forEach(t=>t.classList.remove('active'));
  btn.classList.add('active');
  document.getElementById('tab-'+tab).classList.add('active');
}

function inst(){ const u=document.getElementById('inst').dataset.url; if(u) window.open(u,'_blank'); }

function cp1(){
  if(!cur) return;
  navigator.clipboard.writeText(cur.link||'').then(()=>{
    const b=document.getElementById('cp1');
    b.classList.add('copied'); b.textContent='✓ Skopiowano!';
    setTimeout(()=>{ b.classList.remove('copied'); b.innerHTML='<svg width="14" height="14" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><rect x="9" y="9" width="13" height="13" rx="2"/><path d="M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1"/></svg> Kopiuj link'; },2200);
  });
}

function cp2(){
  if(!cur) return;
  navigator.clipboard.writeText(installCode(cur)).then(()=>{
    const b=document.getElementById('cp2');
    b.classList.add('copied'); b.textContent='✓ Skopiowano!';
    setTimeout(()=>{ b.classList.remove('copied'); b.innerHTML='<svg width="14" height="14" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><rect x="9" y="9" width="13" height="13" rx="2"/><path d="M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1"/></svg> Kopiuj kod'; },2200);
  });
}

function setTab(tab, btn){
  document.querySelectorAll('.nav-tab').forEach(t=>t.classList.remove('active'));
  btn.classList.add('active');
  ['scripts','about','docs'].forEach(s=>{
    document.getElementById('sec-'+s).style.display = s===tab?'':'none';
  });
  document.getElementById('mq-section').style.display = tab==='scripts'?'':'none';
}

renderChips(); render(); renderMarquee(); updateStats();
document.addEventListener('keydown', e=>{ if(e.key==='Escape') closeModal(); });
</script>
</body>
</html>
