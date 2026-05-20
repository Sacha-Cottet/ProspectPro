<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MRR — Suivi Prospects</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700&family=Outfit:wght@300;400;500;600;700&display=swap');

:root {
  --bg: #080810;
  --s1: #0f0f1a;
  --s2: #161625;
  --s3: #1e1e30;
  --accent: #6c63ff;
  --accent-dim: rgba(108,99,255,0.15);
  --pink: #ff6b9d;
  --pink-dim: rgba(255,107,157,0.12);
  --green: #00f5a0;
  --green-dim: rgba(0,245,160,0.1);
  --yellow: #ffd60a;
  --yellow-dim: rgba(255,214,10,0.1);
  --text: #ececf4;
  --muted: #5a5a78;
  --border: #1f1f35;
  --border2: #2a2a42;
  --mono: 'JetBrains Mono', monospace;
  --sans: 'Outfit', sans-serif;
}

* { box-sizing: border-box; margin: 0; padding: 0; }
body { background: var(--bg); color: var(--text); font-family: var(--sans); min-height: 100vh; overflow-x: hidden; }
::-webkit-scrollbar { width: 3px; height: 3px; }
::-webkit-scrollbar-thumb { background: var(--border2); border-radius: 2px; }

/* ── TABS ── */
.tab-nav {
  display: flex; background: var(--s1);
  border-bottom: 1px solid var(--border);
  position: sticky; top: 0; z-index: 200;
}
.tab-btn {
  flex: 1; background: none; border: none;
  border-bottom: 2px solid transparent;
  color: var(--muted); cursor: pointer;
  font-family: var(--mono); font-size: 8px;
  letter-spacing: 0.5px; padding: 11px 2px 9px;
  text-transform: uppercase; transition: all 0.2s;
}
.tab-btn .ico { display: block; font-size: 14px; margin-bottom: 3px; }
.tab-btn.active { border-bottom-color: var(--accent); color: var(--accent); }
.tab-content { display: none; padding: 14px 13px 100px; }
.tab-content.active { display: block; animation: fu 0.2s ease; }
@keyframes fu { from { opacity:0; transform:translateY(5px); } to { opacity:1; transform:translateY(0); } }

/* ── BASE ── */
.ph-title { font-family: var(--mono); font-size: 15px; color: var(--accent); margin-bottom: 2px; }
.ph-sub { color: var(--muted); font-size: 12px; margin-bottom: 14px; }
label { color: var(--muted); font-family: var(--mono); font-size: 9px; letter-spacing: 0.6px; text-transform: uppercase; display: block; margin-bottom: 4px; }

input, select, textarea {
  background: var(--s2); border: 1px solid var(--border2);
  border-radius: 7px; color: var(--text); font-family: var(--sans);
  font-size: 13px; padding: 8px 10px; width: 100%;
  outline: none; transition: border-color 0.15s; -webkit-appearance: none;
}
input:focus, select:focus, textarea:focus { border-color: var(--accent); }
select option { background: var(--s2); }
textarea { font-size: 12px; min-height: 60px; resize: vertical; line-height: 1.5; }

.btn-primary {
  background: var(--accent); border: none; border-radius: 9px;
  color: white; cursor: pointer; font-family: var(--mono);
  font-size: 12px; font-weight: 700; letter-spacing: 0.8px;
  padding: 11px; width: 100%;
  box-shadow: 0 4px 16px rgba(108,99,255,0.28);
  transition: opacity 0.15s, transform 0.1s;
}
.btn-primary:active { transform: scale(0.98); opacity: 0.85; }

.btn-sm {
  background: var(--s3); border: 1px solid var(--border2);
  border-radius: 5px; color: var(--muted); cursor: pointer;
  font-size: 11px; padding: 4px 8px; transition: all 0.15s;
}
.btn-sm:hover { border-color: var(--accent); color: var(--text); }
.btn-sm.danger { background: none; border: none; }
.btn-sm.danger:hover { color: var(--pink); }

/* ══════════════════════════
   TAB 1 — AJOUT
══════════════════════════ */
.stats-strip {
  display: grid; grid-template-columns: repeat(4,1fr);
  gap: 7px; margin-bottom: 14px;
}
.sstat {
  background: var(--s1); border: 1px solid var(--border);
  border-radius: 10px; padding: 9px 5px; text-align: center;
}
.sstat-val { font-family: var(--mono); font-size: 20px; font-weight: 700; line-height: 1; }
.sstat-lbl { color: var(--muted); font-size: 9px; margin-top: 3px; text-transform: uppercase; }

.quick-add {
  background: var(--s1); border: 1px solid var(--border);
  border-radius: 12px; padding: 12px; margin-bottom: 14px;
}
.qa-row { display: flex; gap: 7px; margin-bottom: 7px; align-items: flex-end; }
.fg { flex: 1; } .fg-sm { flex: 0 0 88px; }

/* paypal toggle */
.pp-toggle {
  display: flex; background: var(--s2);
  border: 1px solid var(--border2); border-radius: 7px;
  overflow: hidden; margin-bottom: 7px;
}
.pp-opt {
  flex: 1; background: none; border: none; cursor: pointer;
  font-family: var(--mono); font-size: 10px; color: var(--muted);
  padding: 7px 3px; transition: all 0.15s;
}
.pp-opt.on-yes { background: var(--green-dim); color: var(--green); }
.pp-opt.on-no  { background: var(--pink-dim);  color: var(--pink);  }
.pp-opt.on-unk { background: var(--s3); color: var(--muted); }

/* qualif */
.qtoggle-row { display: flex; gap: 6px; margin-bottom: 7px; }
.qtoggle {
  flex: 1; background: var(--s2); border: 1px solid var(--border2);
  border-radius: 7px; cursor: pointer; padding: 7px 3px;
  text-align: center; transition: all 0.15s; user-select: none;
}
.qtoggle .qi { font-size: 13px; display: block; }
.qtoggle .ql { font-family: var(--mono); font-size: 9px; color: var(--muted); margin-top: 2px; }
.qtoggle.on { background: var(--accent-dim); border-color: var(--accent); }
.qtoggle.on .ql { color: var(--accent); }

/* mini cards (ajout tab) */
.filters {
  display: flex; gap: 6px; overflow-x: auto;
  padding-bottom: 3px; margin-bottom: 9px; scrollbar-width: none;
}
.filters::-webkit-scrollbar { display: none; }
.fbtn {
  background: var(--s1); border: 1px solid var(--border);
  border-radius: 20px; color: var(--muted); cursor: pointer;
  font-size: 11px; padding: 5px 11px; white-space: nowrap; transition: all 0.15s;
}
.fbtn.active { background: var(--accent); border-color: var(--accent); color: white; }

.mini-list { display: flex; flex-direction: column; gap: 6px; }

.mcard {
  background: var(--s1); border: 1px solid var(--border);
  border-radius: 10px; overflow: hidden; display: flex;
  flex-direction: column; transition: border-color 0.15s;
}
.mcard:hover { border-color: var(--border2); }
.mcard-top {
  display: flex; align-items: center; gap: 0;
}
.mcard-stripe { width: 3px; align-self: stretch; flex-shrink: 0; }
.mcard[data-s="en cours"] .mcard-stripe { background: var(--blue); }
.mcard[data-s="intéressé"] .mcard-stripe { background: var(--accent); }
.mcard[data-s="vendu"] .mcard-stripe { background: var(--green); }
.mcard[data-s="perdu"] .mcard-stripe { background: var(--pink); }

.mcard-body { flex: 1; padding: 8px 9px; display: flex; align-items: center; gap: 7px; min-width: 0; }
.mcard-pseudo { font-family: var(--mono); font-size: 12px; font-weight: 700; flex: 1; min-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: nowrap; }
.mcard-right { display: flex; align-items: center; gap: 5px; padding-right: 9px; flex-shrink: 0; }
.mcard-days { font-size: 10px; color: var(--muted); white-space: nowrap; }
.mcard-days.warn { color: var(--yellow); }

/* qdots mini */
.qdots { display: flex; gap: 3px; }
.qdot { width: 6px; height: 6px; border-radius: 50%; background: var(--border2); flex-shrink: 0; }
.qdot.on { background: var(--green); }

.select-sm {
  background: var(--s2); border: 1px solid var(--border2);
  border-radius: 5px; color: var(--text); font-size: 11px;
  padding: 3px 5px; cursor: pointer; width: auto;
}

/* expandable detail row */
.mcard-detail {
  border-top: 1px solid var(--border);
  padding: 9px 13px 10px 16px;
  display: none;
  flex-direction: column;
  gap: 8px;
}
.mcard-detail.open { display: flex; }

.detail-row { display: flex; gap: 8px; align-items: flex-start; }
.detail-row .fg { flex: 1; }

.detail-label { font-family: var(--mono); font-size: 9px; color: var(--muted); letter-spacing: 0.6px; text-transform: uppercase; margin-bottom: 4px; }

/* inline pp toggle (in detail) */
.pp-inline {
  display: flex; gap: 0; background: var(--s2);
  border: 1px solid var(--border2); border-radius: 6px; overflow: hidden;
}
.pp-inline-opt {
  flex: 1; background: none; border: none; cursor: pointer;
  font-family: var(--mono); font-size: 10px; color: var(--muted);
  padding: 6px 3px; transition: all 0.15s;
}
.pp-inline-opt.on-yes { background: var(--green-dim); color: var(--green); }
.pp-inline-opt.on-no  { background: var(--pink-dim);  color: var(--pink);  }
.pp-inline-opt.on-unk { background: var(--s3); color: var(--muted); }

/* inline qualif */
.q-inline { display: flex; gap: 5px; }
.q-inline-btn {
  flex: 1; background: var(--s2); border: 1px solid var(--border2);
  border-radius: 6px; cursor: pointer; padding: 5px 3px;
  text-align: center; transition: all 0.15s; user-select: none;
  font-family: var(--mono); font-size: 9px; color: var(--muted);
}
.q-inline-btn.on { background: var(--accent-dim); border-color: var(--accent); color: var(--accent); }

.notes-input {
  font-size: 12px; padding: 7px 9px;
  background: var(--s2); border: 1px solid var(--border2);
  border-radius: 6px; color: var(--text); width: 100%;
  outline: none; transition: border-color 0.15s;
}
.notes-input:focus { border-color: var(--accent); }

.expand-btn {
  background: none; border: none; color: var(--muted);
  cursor: pointer; font-size: 11px; padding: 4px 7px;
  transition: color 0.15s;
}
.expand-btn:hover { color: var(--text); }

/* relance msg in card */
.rmsg-card {
  background: var(--s2); border: 1px solid rgba(108,99,255,0.2);
  border-radius: 6px; font-size: 11px; line-height: 1.6;
  padding: 8px 10px; margin-top: 4px;
}
.rmsg-card-lbl {
  font-family: var(--mono); font-size: 9px; color: var(--accent);
  letter-spacing: 0.8px; text-transform: uppercase;
  margin-bottom: 5px; display: flex; align-items: center; justify-content: space-between;
}
.copy-btn {
  background: none; border: none; color: var(--muted);
  cursor: pointer; font-size: 12px; padding: 0; transition: color 0.15s;
}
.copy-btn:hover { color: var(--text); }

/* pulse */
.pulse { width: 6px; height: 6px; background: var(--pink); border-radius: 50%; display: inline-block; animation: p 1.5s infinite; }
@keyframes p { 0%,100%{opacity:1;transform:scale(1)} 50%{opacity:0.4;transform:scale(0.6)} }

.section-label {
  font-family: var(--mono); font-size: 9px; color: var(--muted);
  letter-spacing: 1px; text-transform: uppercase;
  margin-bottom: 8px; display: flex; align-items: center; gap: 6px;
}
.empty { color: var(--muted); padding: 28px 16px; text-align: center; font-size: 13px; }

/* ══════════════════════════
   TAB 2 — TABLEAU
══════════════════════════ */
.table-wrap { overflow-x: auto; border: 1px solid var(--border); border-radius: 11px; }
table { border-collapse: collapse; min-width: 780px; width: 100%; }
thead { background: var(--s2); }
th { color: var(--muted); font-family: var(--mono); font-size: 9px; letter-spacing: 0.7px; padding: 10px 11px; text-align: left; text-transform: uppercase; white-space: nowrap; }
td { border-top: 1px solid var(--border); font-size: 12px; padding: 8px 11px; vertical-align: middle; }
tr:hover td { background: rgba(108,99,255,0.03); }

.pill { border-radius: 20px; display: inline-block; font-family: var(--mono); font-size: 9px; font-weight: 700; padding: 2px 8px; }
.pill-encours { background: var(--blue-dim); color: var(--blue); }
.pill-intéressé { background: var(--accent-dim); color: var(--accent); }
.pill-vendu    { background: var(--green-dim);  color: var(--green);  }
.pill-perdu    { background: var(--pink-dim);   color: var(--pink);   }

.bar-wrap { display: flex; align-items: center; gap: 5px; }
.bar { background: var(--s3); border-radius: 2px; height: 4px; width: 38px; overflow: hidden; }
.bar-fill { background: var(--accent); border-radius: 2px; height: 100%; }
.bar-fill.max { background: var(--pink); }

/* table editable selects */
.tsel {
  background: var(--s2); border: 1px solid var(--border2);
  border-radius: 5px; color: var(--text); font-size: 11px;
  padding: 3px 5px; cursor: pointer; width: auto;
}

/* inline note in table */
.tnote {
  background: transparent; border: 1px solid transparent;
  border-radius: 5px; color: var(--muted); font-size: 11px;
  padding: 3px 5px; width: 130px; cursor: text;
  font-family: var(--sans);
}
.tnote:focus { background: var(--s2); border-color: var(--accent); color: var(--text); outline: none; }

/* table pp/qualif toggles */
.t-pp { cursor: pointer; font-size: 14px; user-select: none; }
.t-qdot { width: 8px; height: 8px; border-radius: 50%; display: inline-block; cursor: pointer; margin-right: 3px; transition: all 0.15s; }
.t-qdot.on { background: var(--green); box-shadow: 0 0 4px rgba(0,245,160,0.5); }
.t-qdot.off { background: var(--border2); }

/* ══════════════════════════
   TAB 3 — RELANCES
══════════════════════════ */
.rq-item {
  background: var(--s1); border: 1px solid rgba(255,107,157,0.2);
  border-left: 3px solid var(--pink);
  border-radius: 10px; padding: 10px 12px;
  display: flex; align-items: center; gap: 10px;
  margin-bottom: 7px;
}
.rq-num {
  font-family: var(--mono); font-size: 10px; color: var(--pink);
  background: rgba(255,107,157,0.1); border-radius: 5px;
  padding: 2px 6px; flex-shrink: 0; white-space: nowrap;
}
.rq-info { flex: 1; min-width: 0; }
.rq-pseudo { font-family: var(--mono); font-size: 13px; font-weight: 700; }
.rq-meta { color: var(--muted); font-size: 11px; margin-top: 2px; }
.rq-actions { display: flex; gap: 5px; flex-shrink: 0; }

.rmsg-block {
  background: var(--s2); border: 1px solid rgba(108,99,255,0.2);
  border-radius: 7px; font-size: 12px; line-height: 1.7;
  padding: 9px 11px; margin: 4px 0 12px 0;
}
.rmsg-lbl {
  font-family: var(--mono); font-size: 9px; color: var(--accent);
  letter-spacing: 0.8px; text-transform: uppercase;
  margin-bottom: 5px; display: flex; align-items: center; justify-content: space-between;
}

.wait-item {
  background: var(--s1); border: 1px solid var(--border);
  border-left: 3px solid var(--border2);
  border-radius: 9px; padding: 9px 12px;
  display: flex; align-items: center; gap: 10px;
  margin-bottom: 6px; opacity: 0.65;
}
.wait-num {
  font-family: var(--mono); font-size: 10px; color: var(--muted);
  background: var(--s3); border-radius: 5px;
  padding: 2px 6px; flex-shrink: 0; white-space: nowrap;
}

/* ══════════════════════════
   TAB 4 — SCRIPTS
══════════════════════════ */
.msg-block { background: var(--s1); border: 1px solid var(--border); border-radius: 11px; margin-bottom: 10px; overflow: hidden; }
.msg-hdr { background: var(--s2); border-bottom: 1px solid var(--border); display: flex; align-items: center; justify-content: space-between; padding: 9px 13px; }
.msg-day-tag { font-family: var(--mono); font-size: 11px; color: var(--accent); font-weight: 700; }
.msg-day-sub { color: var(--muted); font-size: 11px; }
.msg-conseil { padding: 11px 13px; border-bottom: 1px solid var(--border); background: rgba(108,99,255,0.04); }
.msg-conseil-lbl { font-family: var(--mono); font-size: 9px; color: var(--accent); letter-spacing: 1px; text-transform: uppercase; margin-bottom: 5px; display: flex; align-items: center; justify-content: space-between; }
.msg-text { font-size: 13px; line-height: 1.7; white-space: pre-line; }
.msg-perso { padding: 10px 13px; }
.msg-perso-lbl { font-family: var(--mono); font-size: 9px; color: var(--muted); letter-spacing: 1px; text-transform: uppercase; margin-bottom: 6px; }
.save-btn { background: var(--accent-dim); border: 1px solid rgba(108,99,255,0.3); border-radius: 6px; color: var(--accent); cursor: pointer; font-family: var(--mono); font-size: 9px; letter-spacing: 0.5px; margin-top: 6px; padding: 6px 12px; transition: all 0.15s; }
.save-btn.saved { color: var(--green); border-color: var(--green); background: var(--green-dim); }

/* ══════════════════════════
   TAB 5 — STATS
══════════════════════════ */
.kpi-grid { display: grid; grid-template-columns: repeat(2,1fr); gap: 9px; margin-bottom: 16px; }
.kpi-card { background: var(--s1); border: 1px solid var(--border); border-radius: 11px; padding: 13px; text-align: center; }
.kpi-val { font-family: var(--mono); font-size: 28px; font-weight: 700; line-height: 1; margin-bottom: 5px; }
.kpi-lbl { color: var(--muted); font-size: 11px; line-height: 1.4; }
.chart-card { background: var(--s1); border: 1px solid var(--border); border-radius: 11px; padding: 14px; margin-bottom: 11px; }
.chart-title { font-family: var(--mono); font-size: 9px; color: var(--muted); letter-spacing: 0.8px; text-transform: uppercase; margin-bottom: 12px; }
.bar-chart { display: flex; align-items: flex-end; gap: 5px; height: 85px; }
.bcol { flex: 1; display: flex; flex-direction: column; align-items: center; gap: 3px; }
.bcol-bar { width: 100%; border-radius: 3px 3px 0 0; min-height: 2px; }
.bcol-lbl { font-size: 8px; color: var(--muted); font-family: var(--mono); white-space: nowrap; }
.bcol-val { font-size: 10px; color: var(--text); font-family: var(--mono); }
.donut-wrap { background: var(--s1); border: 1px solid var(--border); border-radius: 11px; padding: 16px 13px; margin-bottom: 11px; text-align: center; }
.donut-title { font-family: var(--mono); font-size: 9px; color: var(--muted); letter-spacing: 0.8px; text-transform: uppercase; margin-bottom: 12px; }
.donut-legend { display: flex; justify-content: center; gap: 10px; flex-wrap: wrap; margin-top: 11px; }
.leg-item { display: flex; align-items: center; gap: 5px; font-size: 11px; color: var(--muted); }
.leg-dot { width: 7px; height: 7px; border-radius: 50%; flex-shrink: 0; }
.no-data { color: var(--muted); font-size: 13px; padding: 18px; text-align: center; }
</style>
</head>
<body>

<nav class="tab-nav">
  <button class="tab-btn active" onclick="switchTab('ajout',this)"><span class="ico">⚡</span>Ajout</button>
  <button class="tab-btn" onclick="switchTab('tableau',this)"><span class="ico">📋</span>Tableau</button>
  <button class="tab-btn" onclick="switchTab('relances',this)"><span class="ico">🔥</span>Relances</button>
  <button class="tab-btn" onclick="switchTab('scripts',this)"><span class="ico">💬</span>Scripts</button>
  <button class="tab-btn" onclick="switchTab('stats',this)"><span class="ico">📈</span>Stats</button>
</nav>

<!-- ══════════ TAB 1 — AJOUT ══════════ -->
<div class="tab-content active" id="tab-ajout">
  <div class="ph-title">// AJOUT RAPIDE</div>
  <div class="ph-sub">Saisie rapide · clique sur une carte pour modifier</div>

  <div class="stats-strip">
    <div class="sstat"><div class="sstat-val" id="s-total" style="color:var(--accent)">0</div><div class="sstat-lbl">Total</div></div>
    <div class="sstat"><div class="sstat-val" id="s-encours" style="color:var(--blue)">0</div><div class="sstat-lbl">En cours</div></div>
    <div class="sstat"><div class="sstat-val" id="s-vendu" style="color:var(--green)">0</div><div class="sstat-lbl">Vendus</div></div>
    <div class="sstat"><div class="sstat-val" id="s-relancer" style="color:var(--pink)">0</div><div class="sstat-lbl">À relancer</div></div>
  </div>

  <div class="quick-add">
    <div style="font-family:var(--mono);font-size:9px;color:var(--muted);letter-spacing:1px;text-transform:uppercase;margin-bottom:10px">+ Nouveau prospect</div>

    <div class="qa-row">
      <div class="fg"><label>Pseudo</label><input type="text" id="inp-pseudo" placeholder="@pseudo" autocomplete="off"></div>
      <div class="fg-sm"><label>Date</label><input type="date" id="inp-date"></div>
    </div>
    <div class="qa-row">
      <div class="fg"><label>Statut</label>
        <select id="inp-statut" onchange="togglePerduInp()">
          <option value="en cours">En cours 💬</option>
          <option value="intéressé">Intéressé</option>
          <option value="vendu">Vendu ✅</option>
          <option value="perdu">Perdu ❌</option>
        </select>
      </div>
      <div class="fg"><label>Pays</label>
        <select id="inp-pays">
          <option value="">Pays</option>
          <option>🇫🇷 France</option><option>🇧🇪 Belgique</option>
          <option>🇨🇭 Suisse</option><option>🇨🇦 Canada</option>
          <option>🇲🇦 Maroc</option><option>🇹🇳 Tunisie</option>
          <option>🌍 Autre</option>
        </select>
      </div>
    </div>

    <label>PayPal vérifié ?</label>
    <div class="pp-toggle" style="margin-bottom:7px">
      <button class="pp-opt on-unk" id="fpp-?" onclick="setFPP('?')">❔ Inconnu</button>
      <button class="pp-opt" id="fpp-oui" onclick="setFPP('oui')">✅ Oui</button>
      <button class="pp-opt" id="fpp-non" onclick="setFPP('non')">❌ Non</button>
    </div>

    <label>Qualifié sur…</label>
    <div class="qtoggle-row">
      <div class="qtoggle" id="fq-motivation" onclick="toggleFQ('motivation')"><span class="qi">🔥</span><span class="ql">Motivation</span></div>
      <div class="qtoggle" id="fq-maturité" onclick="toggleFQ('maturité')"><span class="qi">🧠</span><span class="ql">Maturité</span></div>
      <div class="qtoggle" id="fq-finances" onclick="toggleFQ('finances')"><span class="qi">💶</span><span class="ql">Finances</span></div>
    </div>

    <div id="perdu-wrap" style="display:none;margin-bottom:7px">
      <label>Pourquoi perdu ?</label>
      <select id="inp-perdu">
        <option value="">— Sélectionner —</option>
        <option>Pas de budget</option><option>Pas intéressé</option>
        <option>Pas de PayPal</option><option>Ghosté</option>
        <option>Trop jeune</option><option>Autre</option>
      </select>
    </div>

    <label style="margin-bottom:4px">Notes</label>
    <input type="text" id="inp-notes" placeholder="Ex: veut revenus passifs, étudiante..." style="margin-bottom:8px">

    <button class="btn-primary" onclick="addProspect()">AJOUTER →</button>
  </div>

  <div class="filters">
    <button class="fbtn active" onclick="setFilter('tous',this)">Tous</button>
    <button class="fbtn" onclick="setFilter('en cours',this)">En cours 💬</button>
    <button class="fbtn" onclick="setFilter('intéressé',this)">Intéressés</button>
    <button class="fbtn" onclick="setFilter('vendu',this)">Vendus</button>
    <button class="fbtn" onclick="setFilter('perdu',this)">Perdus</button>
  </div>

  <div class="mini-list" id="mini-list"></div>
</div>

<!-- ══════════ TAB 2 — TABLEAU ══════════ -->
<div class="tab-content" id="tab-tableau">
  <div class="ph-title">// TABLEAU</div>
  <div class="ph-sub">Tout modifier directement dans les cellules</div>
  <div class="table-wrap">
    <table>
      <thead>
        <tr>
          <th>#</th><th>Pseudo</th><th>Statut</th><th>Pays</th>
          <th>PayPal</th><th>Motiv.</th><th>Matur.</th><th>Fin.</th>
          <th>Jours</th><th>Relances</th><th>Notes / Raison perdu</th><th></th>
        </tr>
      </thead>
      <tbody id="table-body"></tbody>
    </table>
  </div>
</div>

<!-- ══════════ TAB 3 — RELANCES ══════════ -->
<div class="tab-content" id="tab-relances">
  <div class="ph-title">// FILE DE RELANCE</div>
  <div class="ph-sub">Ordonnés par urgence</div>
  <div id="relance-queue"></div>
</div>

<!-- ══════════ TAB 4 — SCRIPTS ══════════ -->
<div class="tab-content" id="tab-scripts">
  <div class="ph-title">// SCRIPTS</div>
  <div class="ph-sub">Messages de relance par jour</div>
  <div id="messages-container"></div>
</div>

<!-- ══════════ TAB 5 — STATS ══════════ -->
<div class="tab-content" id="tab-stats">
  <div class="ph-title">// STATS</div>
  <div class="ph-sub">Ta progression</div>
  <div id="stats-container"></div>
</div>

<script>
// ── DATA ────────────────────────────────────────────────
let P = JSON.parse(localStorage.getItem('mrr5') || '[]');
let M = JSON.parse(localStorage.getItem('mrr5_msgs') || '{}');
let currentFilter = 'tous';
let fpp = '?';
let fq = { motivation:false, maturité:false, finances:false };

const SL = { 'en cours':'En cours 💬', intéressé:'Intéressé', vendu:'Vendu ✅', perdu:'Perdu ❌' };
const SCHED = [2,4,6,9,12,16,21];
const COLORS = { 'en cours':'#38bdf8', intéressé:'#6c63ff', vendu:'#00f5a0', perdu:'#ff6b9d' };
const PAYS_OPTS = ['','🇫🇷 France','🇧🇪 Belgique','🇨🇭 Suisse','🇨🇦 Canada','🇲🇦 Maroc','🇹🇳 Tunisie','🌍 Autre'];
const PERDU_OPTS = ['','Pas de budget','Pas intéressé','Pas de PayPal','Ghosté','Trop jeune','Autre'];

const CONSEILS = [
  { label:'J+2',  msg:`Hey [pseudo] ! Tu as eu le temps de réfléchir depuis notre échange ?\n\nJe posais la question parce que j'ai vu des profils similaires au tien vraiment bien s'en sortir avec ce que je propose 👀` },
  { label:'J+4',  msg:`Salut [pseudo] ! Je voulais juste te partager quelque chose — un de mes contacts a commencé il y a 3 semaines et il vient de faire sa première vente à 300€.\n\nJe me suis dit que ça pourrait t'intéresser vu notre échange 🙌` },
  { label:'J+6',  msg:`[pseudo] t'es encore là ? 😄\n\nJe te relance parce que le timing est vraiment bon en ce moment. Les gens qui commencent maintenant auront 2 mois d'avance. Si t'as 15 min cette semaine on peut en parler ?` },
  { label:'J+9',  msg:`Hey [pseudo] ! Je voulais prendre de tes nouvelles — comment ça se passe de ton côté ?\n\nT'as avancé sur ton projet de revenus en ligne ?` },
  { label:'J+12', msg:`Salut [pseudo] ! Question directe : t'as mis le projet de côté ou t'es encore en train d'y réfléchir ?\n\nPas de pression, je veux juste savoir si ça vaut le coup qu'on reste en contact 🙂` },
  { label:'J+16', msg:`[pseudo] je ferme mes accompagnements ce mois-ci pour me concentrer sur mes clients actuels.\n\nSi t'as envie d'en savoir plus avant, c'est maintenant ou jamais 😉` },
  { label:'J+21', msg:`Hey [pseudo] ! C'est ma dernière relance, je ne veux pas te saouler 😄\n\nSi un jour t'as envie de lancer quelque chose en ligne, tu sais où me trouver. Bonne continuation 🙌` },
];

// ── UTILS ────────────────────────────────────────────────
const save = () => localStorage.setItem('mrr5', JSON.stringify(P));
const saveMsgs = () => localStorage.setItem('mrr5_msgs', JSON.stringify(M));
const days = d => Math.max(0, Math.floor((Date.now() - new Date(d)) / 86400000));

function shouldRelance(p) {
  if (p.status === 'vendu' || p.status === 'perdu' || p.status === 'en cours') return false;
  const r = p.relances || 0;
  return r < 7 && days(p.date) >= (SCHED[r] || 999);
}

function daysUntilR(p) {
  const r = p.relances || 0;
  if (r >= 7) return Infinity;
  return Math.max(0, SCHED[r] - days(p.date));
}

function getWeekKey(d) {
  const dt = new Date(d);
  const jan1 = new Date(dt.getFullYear(), 0, 1);
  const w = Math.ceil(((dt - jan1) / 86400000 + jan1.getDay() + 1) / 7);
  return `S${String(w).padStart(2,'0')}`;
}

function ppIcon(v) { return v==='oui'?'✅':v==='non'?'❌':'❔'; }

function copyText(text, btn) {
  navigator.clipboard.writeText(text).then(() => {
    const o = btn.innerHTML; btn.innerHTML = '✓';
    setTimeout(() => btn.innerHTML = o, 1500);
  });
}

// ── FORM STATE ───────────────────────────────────────────
function setFPP(val) {
  fpp = val;
  ['?','oui','non'].forEach(v => {
    const b = document.getElementById('fpp-'+v);
    b.className = 'pp-opt' + (v===val ? (v==='oui'?' on-yes':v==='non'?' on-no':' on-unk') : '');
  });
}

function toggleFQ(k) {
  fq[k] = !fq[k];
  document.getElementById('fq-'+k).classList.toggle('on', fq[k]);
}

function togglePerduInp() {
  const v = document.getElementById('inp-statut').value;
  document.getElementById('perdu-wrap').style.display = v==='perdu'?'block':'none';
}

// ── TAB SWITCH ───────────────────────────────────────────
function switchTab(tab, btn) {
  document.querySelectorAll('.tab-content').forEach(t => t.classList.remove('active'));
  document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
  document.getElementById('tab-'+tab).classList.add('active');
  btn.classList.add('active');
  if (tab==='tableau') renderTable();
  if (tab==='relances') renderRelances();
  if (tab==='scripts') renderScripts();
  if (tab==='stats') renderStats();
}

// ── ADD ──────────────────────────────────────────────────
function addProspect() {
  const pseudo = document.getElementById('inp-pseudo').value.trim();
  const date = document.getElementById('inp-date').value;
  if (!pseudo || !date) { alert('Pseudo et date requis !'); return; }
  const status = document.getElementById('inp-statut').value;
  P.unshift({
    id: Date.now(), pseudo, date, status,
    pays: document.getElementById('inp-pays').value,
    paypal: fpp,
    qualif: { ...fq },
    perduRaison: status==='perdu' ? document.getElementById('inp-perdu').value : '',
    notes: document.getElementById('inp-notes').value.trim(),
    relances: 0,
  });
  save();
  // reset
  document.getElementById('inp-pseudo').value = '';
  document.getElementById('inp-pays').value = '';
  document.getElementById('inp-perdu').value = '';
  document.getElementById('inp-notes').value = '';
  document.getElementById('inp-statut').value = 'en cours';
  document.getElementById('perdu-wrap').style.display = 'none';
  fpp = '?'; setFPP('?');
  fq = { motivation:false, maturité:false, finances:false };
  ['motivation','maturité','finances'].forEach(k => document.getElementById('fq-'+k).classList.remove('on'));
  render();
  document.getElementById('inp-pseudo').focus();
}

// ── UPDATE FIELD ─────────────────────────────────────────
function upField(id, field, val) {
  const p = P.find(p=>p.id===id);
  if (!p) return;
  if (field === 'qualif.motivation') p.qualif.motivation = val;
  else if (field === 'qualif.maturité') p.qualif.maturité = val;
  else if (field === 'qualif.finances') p.qualif.finances = val;
  else p[field] = val;
  if (field === 'status' && val !== 'perdu') p.perduRaison = '';
  save(); render();
}

function upNotes(id, val) {
  const p = P.find(p=>p.id===id); if (!p) return;
  p.notes = val; save();
}

function upPerduRaison(id, val) {
  const p = P.find(p=>p.id===id); if (!p) return;
  p.perduRaison = val; save();
}

function toggleQualif(id, key) {
  const p = P.find(p=>p.id===id); if (!p) return;
  p.qualif[key] = !p.qualif[key];
  save(); render(); renderTable();
}

function cyclePP(id) {
  const p = P.find(p=>p.id===id); if (!p) return;
  const cycle = {'?':'oui','oui':'non','non':'?'};
  p.paypal = cycle[p.paypal] || '?';
  save(); render(); renderTable();
}

function markR(id) {
  const p = P.find(p=>p.id===id); if (!p) return;
  p.relances = Math.min((p.relances||0)+1, 7);
  save(); render(); renderRelances();
}

function delP(id) {
  if (!confirm('Supprimer ce prospect ?')) return;
  P = P.filter(p=>p.id!==id);
  save(); render(); renderTable();
}

function setFilter(f, btn) {
  currentFilter = f;
  document.querySelectorAll('.fbtn').forEach(b=>b.classList.remove('active'));
  btn.classList.add('active');
  render();
}

function toggleDetail(id) {
  const el = document.getElementById('detail-'+id);
  if (el) el.classList.toggle('open');
}

// ── RENDER AJOUT ─────────────────────────────────────────
function render() {
  const toR = P.filter(shouldRelance);
  document.getElementById('s-total').textContent = P.length;
  document.getElementById('s-encours').textContent = P.filter(p=>p.status==='en cours').length;
  document.getElementById('s-vendu').textContent = P.filter(p=>p.status==='vendu').length;
  document.getElementById('s-relancer').textContent = toR.length;

  let list = currentFilter==='tous' ? P : P.filter(p=>p.status===currentFilter);
  const el = document.getElementById('mini-list');
  if (!list.length) { el.innerHTML=`<div class="empty">Aucun prospect ici</div>`; return; }

  el.innerHTML = list.map(p => {
    const d = days(p.date);
    const r = p.relances||0;
    const q = p.qualif||{};
    const rel = shouldRelance(p);
    const msg = (M[r]&&M[r].trim()) ? M[r] : CONSEILS[r]?.msg||'';
    const esc = msg.replace(/`/g,'\\`').replace(/\n/g,'\\n');
    const qd = ['motivation','maturité','finances'].map(k=>`<div class="qdot ${q[k]?'on':''}"></div>`).join('');
    const ppI = ppIcon(p.paypal);

    return `
    <div class="mcard" data-s="${p.status}">
      <div class="mcard-top">
        <div class="mcard-stripe"></div>
        <div class="mcard-body">
          <div>
            <div class="mcard-pseudo">${p.pseudo}${rel?` <span style="color:var(--pink)">🔥</span>`:''}</div>
            <div style="font-size:10px;color:var(--muted);margin-top:2px;display:flex;gap:6px;align-items:center">
              ${p.pays?`<span>${p.pays}</span>`:''}
              <span>PP ${ppI}</span>
              <div class="qdots">${qd}</div>
            </div>
          </div>
        </div>
        <div class="mcard-right">
          <select class="select-sm" onchange="upField(${p.id},'status',this.value)">
            ${Object.entries(SL).map(([v,l])=>`<option value="${v}" ${p.status===v?'selected':''}>${l}</option>`).join('')}
          </select>
          <div class="mcard-days ${d>=2&&p.status!=='vendu'&&p.status!=='perdu'&&p.status!=='en cours'?'warn':''}">${d}j</div>
          <button class="expand-btn" onclick="toggleDetail(${p.id})" title="Modifier">✎</button>
          <button class="btn-sm danger" onclick="delP(${p.id})">✕</button>
        </div>
      </div>

      <!-- DETAIL ROW -->
      <div class="mcard-detail" id="detail-${p.id}">
        <div class="detail-row">
          <div class="fg">
            <div class="detail-label">Pays</div>
            <select class="select-sm" style="width:100%" onchange="upField(${p.id},'pays',this.value)">
              ${PAYS_OPTS.map(o=>`<option ${p.pays===o?'selected':''}>${o}</option>`).join('')}
            </select>
          </div>
          <div class="fg">
            <div class="detail-label">PayPal</div>
            <div class="pp-inline">
              <button class="pp-inline-opt ${p.paypal==='?'?'on-unk':''}" onclick="upField(${p.id},'paypal','?');render()">❔</button>
              <button class="pp-inline-opt ${p.paypal==='oui'?'on-yes':''}" onclick="upField(${p.id},'paypal','oui');render()">✅</button>
              <button class="pp-inline-opt ${p.paypal==='non'?'on-no':''}" onclick="upField(${p.id},'paypal','non');render()">❌</button>
            </div>
          </div>
        </div>

        <div>
          <div class="detail-label">Qualification</div>
          <div class="q-inline">
            <div class="q-inline-btn ${q.motivation?'on':''}" onclick="toggleQualif(${p.id},'motivation')">🔥 Motivation</div>
            <div class="q-inline-btn ${q.maturité?'on':''}" onclick="toggleQualif(${p.id},'maturité')">🧠 Maturité</div>
            <div class="q-inline-btn ${q.finances?'on':''}" onclick="toggleQualif(${p.id},'finances')">💶 Finances</div>
          </div>
        </div>

        ${p.status==='perdu'?`
        <div>
          <div class="detail-label">Pourquoi perdu ?</div>
          <select class="select-sm" style="width:100%" onchange="upField(${p.id},'perduRaison',this.value)">
            ${PERDU_OPTS.map(o=>`<option ${p.perduRaison===o?'selected':''}>${o}</option>`).join('')}
          </select>
        </div>`:''}

        <div>
          <div class="detail-label">Notes</div>
          <input class="notes-input" type="text" value="${(p.notes||'').replace(/"/g,'&quot;')}" placeholder="Notes libres..." onchange="upNotes(${p.id},this.value)" oninput="upNotes(${p.id},this.value)">
        </div>

        ${rel && msg ? `
        <div class="rmsg-card">
          <div class="rmsg-card-lbl">
            💬 Message relance ${r+1} · ${CONSEILS[r]?.label||''}
            <span>
              <button class="copy-btn" onclick="copyText(\`${esc}\`,this)">📋 Copier</button>
              <button class="btn-sm" style="margin-left:5px;font-size:10px" onclick="markR(${p.id})">✓ Relancé</button>
            </span>
          </div>
          <div>${msg.replace(/\n/g,'<br>')}</div>
        </div>` : ''}
      </div>
    </div>`;
  }).join('');
}

// ── RENDER TABLE ─────────────────────────────────────────
function renderTable() {
  const tb = document.getElementById('table-body');
  if (!P.length) { tb.innerHTML=`<tr><td colspan="12" style="text-align:center;color:var(--muted);padding:20px">Aucun prospect</td></tr>`; return; }

  tb.innerHTML = P.map((p,i) => {
    const d = days(p.date);
    const r = p.relances||0;
    const q = p.qualif||{};
    const pct = Math.round(r/7*100);

    const mkQDot = (key) =>
      `<span class="t-qdot ${q[key]?'on':'off'}" title="${key}" onclick="toggleQualif(${p.id},'${key}');renderTable()"></span>`;

    return `<tr>
      <td style="color:var(--muted);font-family:var(--mono);font-size:11px">${i+1}</td>
      <td style="font-family:var(--mono);font-weight:700;font-size:12px">${p.pseudo}</td>
      <td>
        <select class="tsel" onchange="upField(${p.id},'status',this.value);renderTable();render()">
          ${Object.entries(SL).map(([v,l])=>`<option value="${v}" ${p.status===v?'selected':''}>${l}</option>`).join('')}
        </select>
      </td>
      <td>
        <select class="tsel" onchange="upField(${p.id},'pays',this.value);render()">
          ${PAYS_OPTS.map(o=>`<option ${p.pays===o?'selected':''}>${o||'—'}</option>`).join('')}
        </select>
      </td>
      <td>
        <span class="t-pp" onclick="cyclePP(${p.id});renderTable();render()" title="Cliquer pour changer">${ppIcon(p.paypal)}</span>
      </td>
      <td>${mkQDot('motivation')}</td>
      <td>${mkQDot('maturité')}</td>
      <td>${mkQDot('finances')}</td>
      <td style="font-family:var(--mono);color:${d>=3&&p.status!=='vendu'&&p.status!=='perdu'&&p.status!=='en cours'?'var(--yellow)':'var(--muted)'};font-size:11px">${d}j</td>
      <td>
        <div class="bar-wrap">
          <div class="bar"><div class="bar-fill ${r>=6?'max':''}" style="width:${pct}%"></div></div>
          <span style="font-size:10px;color:var(--muted);font-family:var(--mono)">${r}/7</span>
        </div>
      </td>
      <td>
        <input class="tnote" type="text"
          value="${((p.status==='perdu'&&p.perduRaison ? p.perduRaison+' · ' : '')+(p.notes||'')).replace(/"/g,'&quot;')}"
          placeholder="${p.status==='perdu'?'Raison perdu...':'Notes...'}"
          onchange="upTableNote(${p.id},this.value,'${p.status}')"
          oninput="upTableNote(${p.id},this.value,'${p.status}')">
      </td>
      <td><button class="btn-sm danger" onclick="delP(${p.id});renderTable()">✕</button></td>
    </tr>`;
  }).join('');
}

function upTableNote(id, val, status) {
  const p = P.find(p=>p.id===id); if (!p) return;
  // Si perdu, ce champ pilote perduRaison, sinon notes
  if (status === 'perdu') p.perduRaison = val;
  else p.notes = val;
  save();
}

// ── RENDER RELANCES ──────────────────────────────────────
function renderRelances() {
  const el = document.getElementById('relance-queue');
  const toR = P.filter(shouldRelance).sort((a,b)=>daysUntilR(a)-daysUntilR(b));
  const waiting = P.filter(p=>p.status!=='vendu'&&p.status!=='perdu'&&p.status!=='en cours'&&!shouldRelance(p)&&(p.relances||0)<7)
    .sort((a,b)=>daysUntilR(a)-daysUntilR(b));

  if (!toR.length && !waiting.length) { el.innerHTML=`<div class="empty">🎉 Rien à relancer pour l'instant</div>`; return; }

  let html = '';

  if (toR.length) {
    html += `<div class="section-label"><span class="pulse"></span> À relancer maintenant (${toR.length})</div>`;
    toR.forEach(p => {
      const r = p.relances||0;
      const msg = (M[r]&&M[r].trim()) ? M[r] : CONSEILS[r]?.msg||'';
      const esc = msg.replace(/`/g,'\\`').replace(/\n/g,'\\n');
      html += `
        <div class="rq-item">
          <div class="rq-num">R${r+1}/7 · ${CONSEILS[r]?.label||''}</div>
          <div class="rq-info">
            <div class="rq-pseudo">${p.pseudo}</div>
            <div class="rq-meta">${days(p.date)}j · ${p.pays||'—'} · PP ${ppIcon(p.paypal)}</div>
          </div>
          <div class="rq-actions">
            <button class="copy-btn" style="font-size:17px" onclick="copyText(\`${esc}\`,this)" title="Copier">📋</button>
            <button class="btn-sm" onclick="markR(${p.id})">✓ Relancé</button>
          </div>
        </div>
        ${msg?`<div class="rmsg-block">
          <div class="rmsg-lbl">Message <button class="copy-btn" onclick="copyText(\`${esc}\`,this)">📋</button></div>
          <div>${msg.replace(/\n/g,'<br>')}</div>
        </div>`:''}`;
    });
  }

  if (waiting.length) {
    html += `<div class="section-label" style="margin-top:18px">⏳ En attente (${waiting.length})</div>`;
    waiting.slice(0,25).forEach(p => {
      const r = p.relances||0;
      html += `
        <div class="wait-item">
          <div class="wait-num">dans ${daysUntilR(p)}j</div>
          <div class="rq-info">
            <div class="rq-pseudo" style="color:var(--muted)">${p.pseudo}</div>
            <div class="rq-meta">Relance ${r+1}/7 · ${p.pays||'—'}</div>
          </div>
        </div>`;
    });
    if (waiting.length>25) html+=`<div class="empty">+${waiting.length-25} autres…</div>`;
  }

  el.innerHTML = html;
}

// ── RENDER SCRIPTS ───────────────────────────────────────
function renderScripts() {
  document.getElementById('messages-container').innerHTML = CONSEILS.map((c,i) => {
    const saved = M[i]||'';
    const esc = c.msg.replace(/`/g,'\\`');
    return `
      <div class="msg-block">
        <div class="msg-hdr">
          <div class="msg-day-tag">RELANCE ${i+1}/7</div>
          <div class="msg-day-sub">${c.label}</div>
        </div>
        <div class="msg-conseil">
          <div class="msg-conseil-lbl">💡 Conseillé
            <button class="copy-btn" onclick="copyText(\`${esc}\`,this)">📋 Copier</button>
          </div>
          <div class="msg-text">${c.msg.replace(/\n/g,'<br>')}</div>
        </div>
        <div class="msg-perso">
          <div class="msg-perso-lbl">✏️ Ton script perso</div>
          <textarea id="msg-${i}" placeholder="Ton propre message...">${saved}</textarea>
          <button class="save-btn" id="sb-${i}" onclick="saveMsg(${i})">Sauvegarder</button>
        </div>
      </div>`;
  }).join('');
}

function saveMsg(i) {
  M[i] = document.getElementById('msg-'+i).value;
  saveMsgs();
  const b = document.getElementById('sb-'+i);
  b.textContent='✓ Sauvegardé'; b.classList.add('saved');
  setTimeout(()=>{ b.textContent='Sauvegarder'; b.classList.remove('saved'); },2000);
}

// ── RENDER STATS ─────────────────────────────────────────
function renderStats() {
  const total = P.length;
  const vendus = P.filter(p=>p.status==='vendu').length;
  const interesses = P.filter(p=>['intéressé','vendu'].includes(p.status)).length;
  const totalR = P.reduce((s,p)=>s+(p.relances||0),0);
  const txC = interesses>0 ? Math.round(vendus/interesses*100) : 0;
  const txA = total>0 ? Math.round(interesses/total*100) : 0;

  const weekMap={}, relMap={};
  P.forEach(p=>{ const w=getWeekKey(p.date); weekMap[w]=(weekMap[w]||0)+1; relMap[w]=(relMap[w]||0)+(p.relances||0); });
  const weeks = Object.keys(weekMap).sort().slice(-8);

  const counts = { 'en cours':0, intéressé:0, vendu:0, perdu:0 };
  P.forEach(p=>{ if(counts[p.status]!==undefined) counts[p.status]++; });

  const kpiHTML = `<div class="kpi-grid">
    <div class="kpi-card"><div class="kpi-val" style="color:var(--green)">${txC}%</div><div class="kpi-lbl">Taux de closing<br>intéressés → vendus</div></div>
    <div class="kpi-card"><div class="kpi-val" style="color:var(--accent)">${txA}%</div><div class="kpi-lbl">Taux d'intérêt<br>total prospects</div></div>
    <div class="kpi-card"><div class="kpi-val" style="color:var(--yellow)">${totalR}</div><div class="kpi-lbl">Relances<br>effectuées</div></div>
    <div class="kpi-card"><div class="kpi-val" style="color:var(--pink)">${vendus}</div><div class="kpi-lbl">Ventes 💰</div></div>
  </div>`;

  const tot2 = Object.values(counts).reduce((a,b)=>a+b,0);
  let donutHTML = '';
  if (tot2>0) {
    const r=54,cx=70,cy=70,sw=18,circ=2*Math.PI*r; let off=0;
    const segs = Object.entries(counts).filter(([,v])=>v>0).map(([k,v])=>{
      const dash=(v/tot2)*circ; const s={k,v,dash,off,color:COLORS[k]}; off+=dash; return s;
    });
    const paths = segs.map(s=>`<circle cx="${cx}" cy="${cy}" r="${r}" fill="none" stroke="${s.color}" stroke-width="${sw}" stroke-dasharray="${s.dash} ${circ-s.dash}" stroke-dashoffset="${-s.off+circ/4}" opacity="0.85"/>`).join('');
    const legend = Object.entries(counts).filter(([,v])=>v>0).map(([k,v])=>`<div class="leg-item"><div class="leg-dot" style="background:${COLORS[k]}"></div>${SL[k]} (${v})</div>`).join('');
    donutHTML = `<div class="donut-wrap">
      <div class="donut-title">RÉPARTITION</div>
      <svg width="140" height="140" viewBox="0 0 140 140" style="display:block;margin:0 auto">
        <circle cx="${cx}" cy="${cy}" r="${r}" fill="none" stroke="var(--s3)" stroke-width="${sw}"/>
        ${paths}
        <text x="${cx}" y="${cy}" text-anchor="middle" dominant-baseline="middle" font-family="JetBrains Mono" font-size="16" fill="var(--text)" font-weight="700">${tot2}</text>
      </svg>
      <div class="donut-legend">${legend}</div>
    </div>`;
  }

  const mkBar = (wks,vals,color,title) => {
    if (!wks.length) return `<div class="no-data">Pas assez de données</div>`;
    const mx=Math.max(...vals,1);
    return `<div class="chart-card"><div class="chart-title">${title}</div>
      <div class="bar-chart">${wks.map((w,i)=>`<div class="bcol">
        <div class="bcol-val" style="color:${color}">${vals[i]||''}</div>
        <div class="bcol-bar" style="height:${Math.round(vals[i]/mx*80)}px;background:${color};opacity:0.8"></div>
        <div class="bcol-lbl">${w}</div>
      </div>`).join('')}</div></div>`;
  };

  document.getElementById('stats-container').innerHTML =
    kpiHTML + donutHTML +
    mkBar(weeks, weeks.map(w=>weekMap[w]||0), 'var(--accent)', 'PROSPECTS / SEMAINE') +
    mkBar(weeks, weeks.map(w=>relMap[w]||0), 'var(--yellow)', 'RELANCES / SEMAINE');
}

// ── INIT ─────────────────────────────────────────────────
document.getElementById('inp-date').valueAsDate = new Date();
setFPP('?');
render();
</script>
</body>
</html>
