<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Expense Tracker</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Noto+Color+Emoji&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#f5f6f8; --card:#ffffff; --ink:#1a2233; --muted:#667085; --line:#e4e7ec; --accent:#1d4ed8; --accent-ink:#ffffff; --danger:#b42318; --hover:#f9fafb;
  --c-Food:#c2410c; --c-Transport:#1d4ed8; --c-Bills:#6d28d9; --c-Shopping:#be185d; --c-Health:#047857; --c-Other:#64748b;
  box-sizing:border-box; padding-top:env(safe-area-inset-top,0px); padding-bottom:env(safe-area-inset-bottom,0px);
}
@media (prefers-color-scheme:dark){
  :root:not([data-theme="light"]){--bg:#0e1420;--card:#161e2e;--ink:#e8ecf4;--muted:#98a2b3;--line:#273247;--accent:#6b9bff;--accent-ink:#0a1020;--danger:#ff8a7a;--hover:#1a2336;
    --c-Food:#fb923c;--c-Transport:#6b9bff;--c-Bills:#a78bfa;--c-Shopping:#f472b6;--c-Health:#34d399;--c-Other:#94a3b8}
}
:root[data-theme="dark"]{--bg:#0e1420;--card:#161e2e;--ink:#e8ecf4;--muted:#98a2b3;--line:#273247;--accent:#6b9bff;--accent-ink:#0a1020;--danger:#ff8a7a;--hover:#1a2336;
  --c-Food:#fb923c;--c-Transport:#6b9bff;--c-Bills:#a78bfa;--c-Shopping:#f472b6;--c-Health:#34d399;--c-Other:#94a3b8}
*{box-sizing:border-box}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;background:var(--bg);color:var(--ink);font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;font-size:.9375rem;line-height:1.5;-webkit-font-smoothing:antialiased}
.wrap{max-width:calc(920px * var(--ts,1));margin:0 auto;padding:0 20px}
header{background:var(--card);border-bottom:1px solid var(--line)}
header .wrap{display:flex;align-items:center;justify-content:space-between;gap:16px;flex-wrap:wrap;padding-top:16px;padding-bottom:16px}
h1{font-size:1.15rem;font-weight:700;margin:0;letter-spacing:-.01em}
h2{font-size:1rem;font-weight:600;margin:0 0 14px}
.controls{display:flex;gap:10px;align-items:center;flex-wrap:wrap}
input,select,button{font:inherit;color:inherit}
input,select{background:var(--card);border:1px solid var(--line);border-radius:8px;padding:9px 12px;width:100%;min-width:0}
.controls input{width:auto}
.controls .cur{width:64px;text-align:center}
input:focus-visible,select:focus-visible,button:focus-visible{outline:2px solid var(--accent);outline-offset:2px}
main{padding:24px 0 56px}
.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-bottom:16px}
.card{background:var(--card);border:1px solid var(--line);border-radius:12px;padding:20px}
.stat .k{color:var(--muted);font-size:.85rem;margin:0 0 6px}
.stat .v{font-size:clamp(1.35rem,5vw,1.7rem);font-weight:700;letter-spacing:-.02em;font-variant-numeric:tabular-nums;margin:0;white-space:nowrap;unicode-bidi:isolate;direction:ltr}
.stat.main .v{color:var(--accent)}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:16px;margin-bottom:16px}
form{display:grid;grid-template-columns:1fr 1fr;gap:12px}
form .wide{grid-column:1/-1}
form label{font-size:.85rem;font-weight:500;color:var(--muted);display:flex;flex-direction:column;gap:5px}
.btn{background:var(--accent);color:var(--accent-ink);border:0;border-radius:8px;padding:10px 16px;font-weight:600;cursor:pointer}
.btn:hover{filter:brightness(1.08)}
.btn.ghost{background:transparent;color:var(--ink);border:1px solid var(--line);font-weight:500;padding:7px 12px;font-size:.9rem}
.btn.ghost:hover{background:var(--hover);filter:none}
.err{grid-column:1/-1;color:var(--danger);font-size:.88rem;margin:0;min-height:1.2em}
.cats{list-style:none;margin:0;padding:0;display:flex;flex-direction:column;gap:14px}
.cats .row{display:flex;justify-content:space-between;gap:8px;font-size:.9rem;margin-bottom:6px}
.cats .row b{font-weight:500}
.cats .row span{color:var(--muted);font-variant-numeric:tabular-nums;white-space:nowrap;unicode-bidi:isolate;direction:ltr}
.track{height:6px;background:var(--line);border-radius:3px;overflow:hidden}
.track i{display:block;height:100%;border-radius:3px}
.head{display:flex;justify-content:space-between;align-items:center;margin-bottom:6px}
.head h2{margin:0}
.tx{list-style:none;margin:0;padding:0}
.tx li{display:grid;grid-template-columns:92px 1fr 110px 110px 36px 36px;gap:12px;align-items:center;padding:12px 4px;border-top:1px solid var(--line)}
.tx li.th{color:var(--muted);font-size:.8rem;font-weight:500;border-top:0;padding-top:6px;padding-bottom:6px}
.tx li:not(.th):not(.empty):hover{background:var(--hover)}
.tx .date{color:var(--muted);font-variant-numeric:tabular-nums;font-size:.9rem}
.tx .desc{font-weight:500;overflow-wrap:anywhere}
.pill{display:inline-flex;align-items:center;gap:6px;font-size:.82rem;color:var(--ink)}
.pill i{width:8px;height:8px;border-radius:50%}
.amt{text-align:right;font-weight:600;font-variant-numeric:tabular-nums;white-space:nowrap;unicode-bidi:isolate;direction:ltr}
.th .amt{font-weight:500}
.del{background:none;border:0;border-radius:6px;width:32px;height:32px;cursor:pointer;color:var(--muted);font-size:1.1rem}
.del:hover{color:var(--danger);background:var(--hover)}
.empty{display:block!important;color:var(--muted);padding:28px 4px!important;text-align:center}
.donutwrap{display:flex;gap:24px;align-items:center;flex-wrap:wrap}
.donut{width:150px;height:150px;flex:none}
.donutwrap .cats{flex:1;min-width:190px}
.dk{fill:var(--muted);font-size:8px}.dv{fill:var(--ink);font-size:13px;font-weight:700}
.seg{display:inline-flex;border:1px solid var(--line);border-radius:8px;overflow:hidden}
.seg button{background:transparent;border:0;padding:6px 14px;font-size:.88rem;cursor:pointer;color:var(--muted)}
.seg button[aria-pressed="true"]{background:var(--accent);color:var(--accent-ink);font-weight:600}
.chart{margin-top:8px}.chart svg{display:block}
.ax{fill:var(--muted);font-size:11px}.bv{fill:var(--ink);font-size:11px;font-weight:600}
.none{color:var(--muted);text-align:center;padding:40px 0}
[hidden]{display:none!important}
:root{--good:#047857;--bad:#b42318}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--good:#34d399;--bad:#ff8a7a}}
:root[data-theme="dark"]{--good:#34d399;--bad:#ff8a7a}
.authwrap{min-height:100vh;display:grid;place-items:center;padding:24px 16px}
.authcard{width:100%;max-width:400px}
.authcard h1{font-size:1.4rem;margin:0 0 4px}
.authcard form{grid-template-columns:1fr}
.muted{color:var(--muted);margin:0 0 16px}
.seg.full{display:flex;width:100%;margin-bottom:16px}.seg.full button{flex:1}
.or{display:flex;align-items:center;gap:12px;color:var(--muted);font-size:.82rem;margin:18px 0 12px}
.or:before,.or:after{content:"";flex:1;height:1px;background:var(--line)}
.social{display:grid;grid-template-columns:repeat(3,1fr);gap:8px}
.social .btn:disabled{opacity:.55;cursor:not-allowed}
.note{color:var(--muted);font-size:.8rem;margin:12px 0 0}
.av{width:36px;height:36px;border-radius:50%;border:0;color:#fff;font-weight:700;cursor:pointer}
.tgrid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.tile{border:1px solid var(--line);border-radius:10px;padding:16px}
.tile .k{color:var(--muted);font-size:.85rem;margin:0 0 4px}
.tile .v{font-size:1.45rem;font-weight:700;margin:0;font-variant-numeric:tabular-nums;white-space:nowrap}
.tile .s{font-size:.88rem;margin:6px 0 0;color:var(--muted)}
.tile .s.good{color:var(--good)}.tile .s.bad{color:var(--bad)}
.tile .track{margin-top:10px}
.linkbtn{background:none;border:0;padding:0;color:var(--accent);cursor:pointer;font:inherit;text-decoration:underline}
form .lab{font-size:.85rem;font-weight:500;color:var(--muted);display:flex;flex-direction:column;gap:5px}
.swatches{display:flex;gap:8px;flex-wrap:wrap;padding-top:4px}
.swatches button{width:28px;height:28px;border-radius:50%;border:2px solid transparent;cursor:pointer}
.swatches button[aria-pressed="true"]{border-color:var(--ink);box-shadow:inset 0 0 0 2px var(--card)}
.ok{grid-column:1/-1;color:var(--good);font-size:.88rem;margin:0;min-height:1.2em}
.btn.danger{background:var(--danger);color:#fff}
#pwForm{grid-template-columns:1fr}
:root{--c-Salary:#047857;--c-Allowance:#0e7490;--c-Business:#4d7c0f;--c-Gift:#c026d3;--c-Debt:#b45309}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--c-Salary:#34d399;--c-Allowance:#22d3ee;--c-Business:#a3e635;--c-Gift:#e879f9;--c-Debt:#fbbf24}}
:root[data-theme="dark"]{--c-Salary:#34d399;--c-Allowance:#22d3ee;--c-Business:#a3e635;--c-Gift:#e879f9;--c-Debt:#fbbf24}
.amt.in{color:var(--good)}
.tile .v{overflow:hidden;text-overflow:ellipsis}
.hint{font-weight:400;font-size:.82rem;color:var(--muted)}
select{font-family:Inter,"Noto Color Emoji",system-ui,-apple-system,"Segoe UI",Roboto,sans-serif}
.fl{font-family:"Noto Color Emoji","Apple Color Emoji","Segoe UI Emoji",sans-serif;font-size:1.05em;line-height:1}
.chip{background:var(--hover);border:1px solid var(--line);border-radius:999px;padding:5px 12px;cursor:pointer;font-size:.88rem;white-space:nowrap;display:inline-flex;align-items:center;gap:6px}
.chip:hover{border-color:var(--accent)}
.mwrap{display:flex;gap:4px;align-items:center}.mwrap input{width:auto}.mnav{padding:7px 10px}
.toast{position:fixed;left:50%;bottom:calc(20px + env(safe-area-inset-bottom,0px));transform:translateX(-50%);background:var(--ink);color:var(--bg);padding:10px 16px;border-radius:10px;z-index:60;display:flex;gap:14px;align-items:center;max-width:90vw;box-shadow:0 6px 24px rgba(0,0,0,.3)}
.toast .linkbtn{color:var(--bg);font-weight:600}
.fbar{display:flex;gap:8px;flex-wrap:wrap;margin:10px 0 4px;align-items:center}
.fbar input{flex:1 1 180px;width:auto}.fbar select{width:auto}
.rform{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin:16px 0;align-items:end}
.rform .span2{grid-column:span 2}.rform .btn,.rform .err{grid-column:1/-1}
@media (max-width:720px){.rform{grid-template-columns:1fr}.rform .span2{grid-column:auto}}
.alerts{list-style:none;margin:0;padding:0}
.alerts li{padding:10px 12px;border-left:4px solid var(--line);background:var(--hover);border-radius:6px;margin-bottom:8px}
.alerts li:last-child{margin-bottom:0}
.alerts .bad{border-color:var(--bad)}.alerts .warn{border-color:#eab308}.alerts .info{border-color:var(--accent)}
textarea{background:var(--card);border:1px solid var(--line);border-radius:8px;padding:10px 12px;width:100%;font:inherit;color:inherit;resize:vertical}
input[type=file]{padding:8px}
:root{--ts:1;--font:Inter,"Noto Color Emoji",system-ui,-apple-system,"Segoe UI",Roboto,sans-serif}
html{font-size:calc(16px * var(--ts,1))}
body{font-family:var(--font)}
select,.theme-toggle{font-family:var(--font)}
.ax,.bv{font-size:calc(11px * var(--ts,1))}
.fontgrid{display:grid;grid-template-columns:repeat(auto-fill,minmax(210px,1fr));gap:12px;margin-top:14px}
.fontopt{text-align:left;background:var(--card);border:2px solid var(--line);border-radius:10px;padding:14px;cursor:pointer;display:flex;flex-direction:column;gap:4px;color:var(--ink)}
.fontopt:hover{border-color:var(--muted)}
.fontopt[aria-pressed="true"]{border-color:var(--accent);background:var(--hover)}
.fontopt .fn{font-size:1.15rem;font-weight:600}
.fontopt .fs{font-size:.95rem}
.fontopt .fc{font-size:.78rem;color:var(--muted);font-family:var(--font)}
.prevbig{font-size:2rem;font-weight:700;margin:4px 0;font-variant-numeric:tabular-nums}
.prevh{font-size:1.1rem;font-weight:600;margin:0}
.prevp{margin:6px 0}
:root{color-scheme:light dark}
:root[data-theme="light"]{color-scheme:light}
:root[data-theme="dark"]{color-scheme:dark}
.theme-toggle{font-family:Inter,"Noto Color Emoji",system-ui,sans-serif;white-space:nowrap}
.authwrap{position:relative}
.theme-float{position:absolute;top:calc(16px + env(safe-area-inset-top,0px));right:16px}
.gmeta.good{color:var(--good)}.gmeta.bad{color:var(--bad)}
.conf{font-size:.85rem;color:var(--muted)}
.aih{font-weight:600;margin:18px 0 6px}
.aisum{font-weight:500;margin:0}
.ailist{margin:0;padding-left:20px}.ailist li{margin:5px 0}
.aibusy{color:var(--muted)}
.chartopts{display:flex;gap:14px;align-items:center;flex-wrap:wrap;margin:10px 0 4px}
.chk{display:flex;align-items:center;gap:8px;font-size:.9rem;color:var(--muted);cursor:pointer}
.chk input{width:auto;margin:0}
.lg{display:flex;gap:16px;font-size:.85rem;color:var(--muted);margin-top:6px}
.lg i{display:inline-block;width:20px;height:0;border-top:3px solid var(--accent);vertical-align:middle;margin-right:6px}
.lg i.dash{border-top:3px dashed var(--muted)}
header .wrap{max-width:none}
.brand{display:flex;align-items:center;gap:10px}
.navbtn{display:none;padding:6px 12px;font-size:1.1rem}
.shell{display:grid;grid-template-columns:calc(240px * var(--ts,1)) minmax(0,1fr);align-items:start}
.content{min-width:0}
.side{position:sticky;top:0;align-self:start;height:100vh;overflow-y:auto;background:var(--card);border-right:1px solid var(--line);padding:16px 12px;display:flex;flex-direction:column;gap:4px}
.nav{display:flex;align-items:center;gap:10px;width:100%;text-align:left;background:none;border:0;border-radius:8px;padding:10px 12px;cursor:pointer;color:var(--ink);font-weight:500}
.nav:hover{background:var(--hover)}
.nav .fl{width:1.5em;text-align:center}
.nav[aria-current="page"]{background:var(--accent);color:var(--accent-ink);font-weight:600}
.navgap{flex:1}
.scrim{position:fixed;inset:0;background:rgba(0,0,0,.45);z-index:40}
@media (max-width:860px){
  .shell{grid-template-columns:1fr}
  .navbtn{display:inline-flex}
  .side{position:fixed;top:0;left:0;bottom:0;width:min(86vw,calc(260px * var(--ts,1)));height:auto;z-index:50;transform:translateX(-100%);transition:transform .25s ease;padding-top:calc(16px + env(safe-area-inset-top,0px))}
  .side.open{transform:none;box-shadow:0 0 40px rgba(0,0,0,.3)}
}
.tipbox{background:var(--hover);border:1px solid var(--line);border-radius:10px;padding:16px;margin-bottom:12px}
.tipbox.alt{margin-bottom:0}
.tiplabel{color:var(--muted);font-size:.85rem;margin:0 0 8px}
.tipcat{display:inline-block;font-size:.75rem;font-weight:600;border:1px solid var(--line);border-radius:999px;padding:1px 10px;color:var(--muted);margin-bottom:8px;background:var(--card)}
.tiptext{font-size:1.05rem;font-weight:500;margin:0}
.tipbtns{display:flex;gap:8px;flex-wrap:wrap;margin:0 0 14px}
.streak{font-size:.9rem;font-weight:600;color:var(--muted)}
.track i{transition:width .7s ease,background-color .7s ease}
.quote{margin:0 0 16px;padding:12px 14px;border-left:3px solid var(--accent);background:var(--hover);border-radius:6px;font-weight:500}
.gform{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin:16px 0;align-items:end}
.gform .span2{grid-column:span 2}
.gform .btn,.gform .err{grid-column:1/-1}
.goals{list-style:none;margin:0;padding:0}
.goals li{border-top:1px solid var(--line);padding:16px 0}
.goals li.empty{padding:24px 4px}
.gtop{display:flex;justify-content:space-between;align-items:baseline;gap:12px;flex-wrap:wrap}
.gname{font-weight:600;font-size:1.02rem;overflow-wrap:anywhere}
.gname .fl{margin-right:8px;font-size:1.3em}
.gname .badge{font-weight:600}
.gbar{height:12px;background:var(--line);border-radius:6px;overflow:hidden;margin-top:12px}
.gbar i{display:block;height:100%;border-radius:6px;transition:width .7s ease,background-color .7s ease}
.gmsg{margin:10px 0 0;font-weight:500}
.gmeta{font-size:.85rem;color:var(--muted);margin:4px 0 0}
.gact{display:flex;gap:8px;margin-top:12px;align-items:center;flex-wrap:wrap}
.gact input{max-width:150px}
.gact .grow{flex:1}
@media (max-width:720px){.gform{grid-template-columns:1fr}.gform .span2{grid-column:auto}}
.cform{display:grid;grid-template-columns:2fr 1.3fr auto;gap:10px;margin:16px 0;align-items:end}
.cform .err{grid-column:1/-1}
.cprices{list-style:none;margin:10px 0 0;padding:0;max-height:340px;overflow-y:auto;border-top:1px solid var(--line)}
.crow{display:grid;grid-template-columns:64px 1fr auto;gap:12px;align-items:center;padding:10px 4px;border-bottom:1px solid var(--line)}
.crow .cs{font-weight:700}.crow .cn{color:var(--muted);overflow-wrap:anywhere}
.crow .cp{font-variant-numeric:tabular-nums;font-weight:600;white-space:nowrap;text-align:right}
@media (max-width:720px){.cform{grid-template-columns:1fr}}
.srch{margin:0}
select[size]{padding:4px;overflow-y:auto}
.cv{display:grid;grid-template-columns:1.1fr 1.7fr auto 1.7fr 1.4fr;gap:10px;align-items:end}
.cv label{font-size:.85rem;font-weight:500;color:var(--muted);display:flex;flex-direction:column;gap:5px}
.cvswap{padding:9px 12px}
.cvout{margin:18px 0 6px}
.cvbig{font-size:1.7rem;font-weight:700;font-variant-numeric:tabular-nums;overflow-wrap:anywhere;margin:2px 0}
.cvsub{color:var(--muted);font-size:.9rem}
@media (max-width:720px){.cv{grid-template-columns:1fr}.cvswap{justify-self:start}}
.frow{margin-bottom:14px}
.frow .row{display:flex;justify-content:space-between;gap:8px;font-size:.9rem;margin-bottom:6px}
.frow .row span{font-variant-numeric:tabular-nums;white-space:nowrap}
.net{margin:4px 0 0;font-weight:600}.net.good{color:var(--good)}.net.bad{color:var(--bad)}
.dform{display:grid;grid-template-columns:2fr 1fr 1fr 1fr auto;gap:10px;margin:16px 0}
.dform .err{grid-column:1/-1}
.debts{list-style:none;margin:0;padding:0}
.debts li{border-top:1px solid var(--line);padding:14px 0}
.debts li.empty{padding:24px 4px}
.dtop{display:flex;justify-content:space-between;gap:12px;align-items:baseline;flex-wrap:wrap}
.dname{font-weight:600;overflow-wrap:anywhere}
.badge{font-size:.75rem;border:1px solid var(--line);border-radius:999px;padding:1px 8px;margin-left:8px;color:var(--muted);white-space:nowrap;font-weight:500}
.dmeta{font-size:.85rem;color:var(--muted);margin:6px 0 0;display:flex;justify-content:space-between;gap:8px;flex-wrap:wrap}
.dmeta .bad{color:var(--bad);font-weight:600}
.dact{display:flex;gap:8px;margin-top:10px;align-items:center}
.dact input{max-width:150px}
.dact .grow{flex:1}
@media (max-width:720px){.dform{grid-template-columns:1fr 1fr}.dform input:first-child{grid-column:1/-1}}
.av{display:grid;place-items:center;overflow:hidden;padding:0}
.av svg{width:100%;height:100%;display:block}
.avhead{display:flex;gap:16px;align-items:center;margin-bottom:16px}
.avprev{width:84px;height:84px;border-radius:50%;overflow:hidden;flex:none;display:grid;place-items:center;color:#fff;font-weight:700;font-size:2rem}
.avprev svg{width:100%;height:100%;display:block}
.avgrid{display:grid;grid-template-columns:repeat(auto-fill,minmax(76px,1fr));gap:12px}
.avgrid button{aspect-ratio:1;border-radius:50%;border:3px solid transparent;padding:0;background:var(--hover);cursor:pointer;overflow:hidden;display:grid;place-items:center;color:#fff;font-weight:700;font-size:1.3rem}
.avgrid button svg{width:100%;height:100%;display:block}
.avgrid button[aria-pressed="true"]{border-color:var(--accent);box-shadow:inset 0 0 0 2px var(--card)}
@media (max-width:720px){.tgrid{grid-template-columns:1fr}}
@media (max-width:720px){
  .stats{grid-template-columns:1fr}
  .grid{grid-template-columns:1fr}
  .tx li.th{display:none}
  .tx li{grid-template-columns:1fr auto 32px 32px;grid-template-areas:"d a e x" "m m m m";row-gap:2px}
  .tx .desc{grid-area:d}.tx .amt{grid-area:a}.tx .del{grid-area:x}.tx .edit{grid-area:e}
  .tx .meta{grid-area:m;display:flex;gap:10px;color:var(--muted);font-size:.85rem}
  .tx > .date,.tx > .pill{display:none}
}
@media (min-width:721px){.tx .meta{display:none}}

/* ===== dashboard skin ===== */
:root{--frame:#fff;--lcol:#f2f3ff;--mcol:#f8f9ff;--rcol:#f2f3ff;--card:#fff;--field:#f0f1ff;--hover:#eceeff;--ink:#1d2046;--muted:#6f74a3;--line:#dfe2f6;--accent:#4d7cff;--accent-ink:#fff;--danger:#e5435b;--good:#13a56b;--bad:#e5435b;--shadow:0 10px 26px rgba(60,70,160,.12);--pg1:#eceeff;--pg2:#cfd4fb;--font:Poppins,"Noto Color Emoji",system-ui,sans-serif}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--frame:#1f2147;--lcol:#1b1d3f;--mcol:#212450;--rcol:#1b1d3f;--card:#2b2e5e;--field:#252850;--hover:#34376e;--ink:#eceeff;--muted:#8a8fc6;--line:#3b3f7a;--accent:#4d7cff;--accent-ink:#fff;--danger:#ff6b81;--good:#3ddc97;--bad:#ff6b81;--shadow:0 10px 26px rgba(8,10,38,.4);--pg1:#c6cbf7;--pg2:#9a9fea}}
:root[data-theme="dark"]{--frame:#1f2147;--lcol:#1b1d3f;--mcol:#212450;--rcol:#1b1d3f;--card:#2b2e5e;--field:#252850;--hover:#34376e;--ink:#eceeff;--muted:#8a8fc6;--line:#3b3f7a;--accent:#4d7cff;--accent-ink:#fff;--danger:#ff6b81;--good:#3ddc97;--bad:#ff6b81;--shadow:0 10px 26px rgba(8,10,38,.4);--pg1:#c6cbf7;--pg2:#9a9fea}
body{background:linear-gradient(135deg,var(--pg1),var(--pg2)) fixed;min-height:100vh;padding:24px;color:var(--ink)}
.frame{display:grid;grid-template-columns:300px minmax(0,1fr) 340px;max-width:1380px;height:calc(100vh - 48px);min-height:640px;margin:0 auto;background:var(--frame);border-radius:28px;overflow:hidden;box-shadow:0 30px 80px rgba(30,32,90,.35)}
.lcol,.rcol,.mscroll{overflow-y:auto;scrollbar-width:thin;scrollbar-color:var(--line) transparent}
.lcol{background:var(--lcol);padding:22px 20px 24px;position:relative}
.mcol{background:var(--mcol);display:flex;flex-direction:column;min-width:0;min-height:0}
.rcol{background:var(--rcol);display:flex;flex-direction:column;padding:20px 0 0;min-height:0}
.mscroll{flex:1;min-height:0;padding:6px 28px 28px}
.mscroll main.wrap{max-width:none;padding:0;margin:0}
.card{border:0;border-radius:20px;box-shadow:var(--shadow)}
.tile,.tipbox,.fontopt{border:0;background:var(--field);border-radius:16px}
.fontopt{border:2px solid transparent}.fontopt[aria-pressed="true"]{border-color:var(--accent)}
input,select,textarea{background:var(--field);border:1px solid transparent;border-radius:12px}
input:focus-visible,select:focus-visible,textarea:focus-visible{border-color:var(--accent)}
.btn{background:linear-gradient(135deg,#5b86ff,#3d63ff);border-radius:999px;box-shadow:0 6px 16px rgba(77,124,255,.35)}
.btn.ghost,.pill-out{background:transparent;color:var(--ink);border:1.5px solid var(--accent);box-shadow:none;border-radius:999px}
.btn.ghost:hover,.pill-out:hover{background:rgba(77,124,255,.14)}
.btn.danger{background:var(--danger);box-shadow:none}
.seg{background:var(--field);border:0;border-radius:999px;padding:3px}
.seg button{border-radius:999px;padding:6px 14px}.seg button[aria-pressed="true"]{background:linear-gradient(135deg,#5b86ff,#3d63ff)}
.pill-out{padding:8px 18px;cursor:pointer;font:inherit;font-weight:600}
h3.sec{margin:0;font-size:1rem;font-weight:600;color:var(--muted)}
.icbtn{width:36px;height:36px;border-radius:50%;display:inline-grid;place-items:center;background:var(--field);border:0;color:var(--ink);cursor:pointer;padding:0;font-size:.85rem;position:relative;flex:none}
.icbtn:hover{background:var(--hover)}
.icbtn svg,.wallet svg,.rc-head svg{width:18px;height:18px;stroke:currentColor;fill:none;stroke-width:1.8;stroke-linecap:round;stroke-linejoin:round}
.dot{position:absolute;top:6px;right:7px;width:8px;height:8px;border-radius:50%;background:#3ddc97;box-shadow:0 0 0 2px var(--field)}
.dot[hidden]{display:none}
.sq{display:inline-grid;place-items:center;width:40px;height:40px;border-radius:12px;background:var(--hover);flex:none;font-size:1.2rem}
/* left column */
.lc-top{display:flex;justify-content:flex-end;gap:10px;margin-bottom:16px}
.lc-chart{position:relative;background:var(--card);border-radius:22px;padding:10px 6px 4px;box-shadow:var(--shadow)}
.lc-chart svg{display:block;width:100%;height:auto}
.lc-big{position:absolute;right:16px;top:34%;font-weight:700;font-size:1.05rem}
.lc-chips{display:flex;gap:8px;flex-wrap:wrap;margin:16px 0}
.lchip{background:transparent;color:var(--ink);border:1.5px solid #7b3ff2;border-radius:12px;padding:6px 12px;font:inherit;font-size:.78rem;font-weight:600;cursor:pointer}
.lc-last{background:var(--card);border-radius:22px;padding:16px;box-shadow:var(--shadow)}
.ll-top{display:flex;gap:10px;align-items:center}.ll-top small,.lc-bal small{display:block;color:var(--muted);font-size:.72rem}
.ll-top b{display:block;max-width:150px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.ll-art{font-size:3.2rem;text-align:center;margin:6px 0;filter:drop-shadow(0 10px 12px rgba(0,0,0,.35))}
.ll-bot{display:flex;justify-content:space-between;align-items:flex-end}.ll-meta{text-align:right}.ll-meta b{display:block}.ll-meta span{font-size:.72rem;color:var(--muted)}
.lc-bal{display:flex;justify-content:space-between;align-items:flex-end;margin:18px 2px 12px}.lc-bal b{font-size:1.15rem}
.lc-all{color:var(--muted);font-size:.8rem;border:1px solid var(--line);border-radius:8px;padding:2px 10px}
.lc-cats{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.citem{background:var(--card);border-radius:18px;padding:12px;position:relative;box-shadow:var(--shadow);display:flex;flex-direction:column;gap:2px}
.citem small{color:var(--muted);font-size:.72rem}.citem .ca{font-size:2rem;text-align:center;margin:4px 0;filter:drop-shadow(0 8px 8px rgba(0,0,0,.35))}
.citem b{font-size:.95rem}.citem .cd{position:absolute;right:10px;bottom:12px;width:8px;height:8px;border-radius:50%}
.lc-fabs{position:sticky;bottom:0;display:flex;gap:10px;margin-top:-6px;padding-top:6px}
.fab{width:44px;height:44px;border-radius:14px;border:0;display:grid;place-items:center;cursor:pointer;color:#fff;box-shadow:0 8px 20px rgba(0,0,0,.35)}
.fab svg{width:20px;height:20px;stroke:#fff;fill:none;stroke-width:2;stroke-linecap:round;stroke-linejoin:round}
.fab.cyan{background:linear-gradient(135deg,#2fd4ff,#18a9f5)}.fab.blue{background:linear-gradient(135deg,#5b86ff,#3d63ff)}
/* top bar + icon nav */
.topbar{display:flex;align-items:center;gap:16px;padding:24px 28px 12px;flex-wrap:wrap}
.navicons{display:flex;gap:4px;align-items:center;min-width:0;flex:1 1 auto;overflow-x:auto;padding:6px 2px;scrollbar-width:none}
.nav{position:relative;width:38px;height:38px;border-radius:12px;display:grid;place-items:center;background:none;border:0;color:var(--muted);cursor:pointer;padding:0;flex:none;font-weight:400}
.nav svg{width:20px;height:20px;stroke:currentColor;fill:none;stroke-width:1.8;stroke-linecap:round;stroke-linejoin:round}
.nav:hover{background:var(--field);color:var(--ink)}
.nav[aria-current="page"]{background:none;color:var(--accent)}
.nav[aria-current="page"]::after{content:"";position:absolute;left:11px;right:11px;bottom:-1px;height:3px;border-radius:3px;background:var(--accent);box-shadow:0 0 12px var(--accent)}
.tb-right{display:flex;gap:12px;align-items:center;margin-left:auto}
.wallet{display:flex;align-items:center;gap:8px;color:var(--muted)}.wallet b{color:var(--ink);font-size:1.02rem;white-space:nowrap}
.mnav{width:30px;height:30px;font-size:.6rem}
/* hero + feature cards + statistic */
.hero{display:grid;grid-template-columns:230px 1fr;gap:20px;align-items:center;margin:8px 0 28px}
.hero-art{position:relative;width:210px;height:210px;margin:0 auto}
.hero-art svg{position:absolute;inset:0;width:100%;height:100%}
.ring-bg{fill:none;stroke:var(--field);stroke-width:7}.ring-fg{fill:none;stroke-width:7;stroke-linecap:round;transition:stroke-dasharray .8s ease,stroke .8s ease}
.coins{inset:34px!important;width:calc(100% - 68px)!important;height:calc(100% - 68px)!important;filter:drop-shadow(0 14px 16px rgba(0,0,0,.35))}
.hero-nums{display:flex;gap:16px;align-items:center;margin:14px 0}
.hero-nums b{display:block;font-size:1.7rem;font-weight:700;white-space:nowrap;font-variant-numeric:tabular-nums}.hero-nums small{color:var(--muted);font-size:.72rem}
.dbl{color:var(--accent);font-size:1.3rem}
.hero-pills{display:flex;gap:12px;flex-wrap:wrap}.pill-dark{background:var(--field);border-radius:14px;padding:11px 18px;font-weight:600;font-size:.9rem}
.hero-pills .pill-out{border-radius:14px;padding:10px 18px}.hero-pills .pill-out b{margin-left:6px;color:var(--accent)}
.feat{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-bottom:30px}
.fc{position:relative;height:150px;border:0;border-radius:22px;padding:16px;text-align:left;color:#fff;cursor:pointer;overflow:hidden;display:flex;align-items:flex-end;font:inherit;box-shadow:0 14px 28px rgba(0,0,0,.35)}
.fc p{margin:0;font-size:.78rem;line-height:1.35;font-weight:500;max-width:88%;display:-webkit-box;-webkit-line-clamp:4;-webkit-box-orient:vertical;overflow:hidden}
.fc .glyph{position:absolute;top:-4px;left:50%;transform:translateX(-35%) rotate(8deg);font-size:6.5rem;font-weight:800;line-height:1;color:rgba(255,255,255,.34);text-shadow:0 14px 18px rgba(0,0,0,.28)}
.fc .arr{position:absolute;right:14px;bottom:12px;font-style:normal;opacity:.8}
.fc-blue{background:linear-gradient(160deg,#5c8bff,#3f67f2)}.fc-purple{background:linear-gradient(160deg,#8a4dff,#5c28d8)}.fc-coral{background:linear-gradient(160deg,#ff6a7d,#f0425c)}
.fc:hover{transform:translateY(-3px);transition:transform .15s}
.statbox .head{display:flex;justify-content:space-between;align-items:center;margin-bottom:12px}
.stat-meta{display:flex;gap:16px;color:var(--muted);font-size:.78rem}
.srow{display:grid;grid-template-columns:44px minmax(0,1.2fr) 56px auto auto;gap:14px;align-items:center;background:var(--card);border-radius:20px;padding:14px 18px;margin-bottom:14px;box-shadow:var(--shadow)}
.srow small{display:block;color:var(--muted);font-size:.72rem}.srow b{font-size:.95rem;font-variant-numeric:tabular-nums;white-space:nowrap}
.srow .sa{font-size:2rem;text-align:center;filter:drop-shadow(0 8px 8px rgba(0,0,0,.35))}
.spill{border:1.5px solid var(--line);border-radius:12px;padding:6px 14px;font-size:.78rem;font-weight:600;color:var(--muted);white-space:nowrap}
.spill.in{border-color:var(--good);color:var(--good)}.spill.rec{border-color:var(--accent);color:var(--accent)}
.srow .sd{text-align:right;max-width:150px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.statbox .pill-out{margin-top:2px;margin-bottom:24px}
/* right column: user + feed + quick add */
.rc-user{display:flex;align-items:center;gap:12px;padding:0 22px 14px}
.rc-name{font-weight:600;flex:1;min-width:0;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.rc-feed{flex:1;min-height:0;display:flex;flex-direction:column;background:var(--mcol);margin-top:4px}
.rc-head{display:flex;justify-content:space-between;align-items:center;padding:14px 22px;color:var(--muted)}
.rc-count{display:flex;align-items:center;gap:6px;font-size:.8rem}.rc-count svg{width:16px;height:16px}
.feed{flex:1;overflow-y:auto;padding:0 22px 12px;scrollbar-width:thin;scrollbar-color:var(--line) transparent}
.msg{display:flex;gap:12px;padding:14px 0}
.msg .sq{width:36px;height:36px;font-size:1.05rem;border-radius:11px}
.mh{display:flex;gap:6px;align-items:baseline}.mh b{font-size:.85rem}.mh i{font-style:normal;color:var(--muted);font-size:.72rem}.mh time{margin-left:auto;color:var(--muted);font-size:.72rem}
.msg p{margin:4px 0 0;color:var(--muted);font-size:.8rem;line-height:1.4;overflow-wrap:anywhere}.msg p em{font-style:normal;color:var(--ink);font-weight:600}.msg p em.in{color:var(--good)}
.msg>div{min-width:0;flex:1}
.rc-input{background:var(--mcol);padding:14px 22px 18px;border-top:1px solid var(--line)}
.rc-input input{background:transparent;border:0;border-radius:0;padding:4px 0 12px;font-size:.85rem}
.rc-tools{display:flex;gap:10px;align-items:center}
.rc-tools select{width:auto;flex:1;min-width:0;padding:8px 10px;font-size:.8rem}
.tool{width:34px;height:34px;border-radius:50%;border:0;background:var(--field);color:var(--ink);font-weight:700;font-size:1.1rem;cursor:pointer}
.send{width:44px;height:44px;border-radius:14px;border:0;background:linear-gradient(135deg,#5b86ff,#3d63ff);cursor:pointer;display:grid;place-items:center;box-shadow:0 8px 18px rgba(77,124,255,.45)}
.send svg{width:20px;height:20px;fill:#fff;stroke:#fff;stroke-width:1;stroke-linejoin:round}
/* system message toast */
.toast{left:auto;right:calc(40px + env(safe-area-inset-right,0px));transform:none;bottom:calc(120px + env(safe-area-inset-bottom,0px));background:var(--card);color:var(--ink);border-radius:22px;padding:16px 20px;gap:14px;align-items:flex-start;min-width:280px;max-width:min(360px,90vw);box-shadow:0 18px 40px rgba(0,0,0,.4);border:1px solid var(--line)}
.toast .ti{width:44px;height:44px;border-radius:14px;background:var(--field);display:grid;place-items:center;flex:none}.toast .ti svg{width:20px;height:20px;stroke:#3ddc97;fill:none;stroke-width:2;stroke-linejoin:round}
.toast .tb{flex:1;min-width:0}.toast .tt{display:flex;justify-content:space-between;gap:10px}.toast .tt time{color:var(--muted);font-size:.72rem}
.toast #toastMsg{color:var(--muted);font-size:.82rem;margin-top:4px}.toast .linkbtn{color:var(--accent);font-weight:600}
@media (max-width:1180px){
  body{padding:0}
  .frame{display:flex;flex-direction:column;height:auto;min-height:100vh;border-radius:0;max-width:none}
  .mcol{order:1}.lcol{order:2}.rcol{order:3}
  .lcol,.rcol{display:none}
  .frame[data-pane="overview"] .lcol{display:block}.frame[data-pane="overview"] .rcol{display:flex;min-height:420px}
  .mscroll{overflow:visible;padding:6px 18px 24px}.lcol{overflow:visible}
  .topbar{padding:18px 18px 8px}
  .lc-fabs{position:static;margin-top:14px}
  .toast{right:12px;bottom:calc(16px + env(safe-area-inset-bottom,0px))}
}
@media (max-width:760px){
  .hero{grid-template-columns:1fr}.feat{grid-template-columns:1fr}.fc{height:120px}
  .srow{grid-template-columns:44px minmax(0,1fr) auto;row-gap:8px}.srow .sa,.srow .spill{display:none}
  .tb-right{width:100%;justify-content:space-between}
}
</style>
</head>
<body>
<section id="auth" class="authwrap" hidden>
  <button class="btn ghost theme-toggle theme-float" id="themeBtn2" type="button"></button>
  <div class="card authcard">
    <h1>Expense Tracker</h1>
    <p class="muted" id="authsub">Sign in to your account</p>
    <div class="seg full" role="group" aria-label="Account">
      <button type="button" data-m="login" aria-pressed="true">Sign in</button>
      <button type="button" data-m="register" aria-pressed="false">Create account</button>
    </div>
    <form id="authForm" novalidate>
      <label id="nameRow" hidden>Full name<input id="aName" autocomplete="name" maxlength="60"></label>
      <label id="countryRow" hidden>Country<select id="aCountry"></select></label>
      <label>Email<input id="aEmail" type="email" autocomplete="email"></label>
      <label>Password<input id="aPass" type="password" autocomplete="current-password" placeholder="At least 8 characters"></label>
      <p class="err" id="aErr" role="alert"></p>
      <button class="btn" id="aGo" type="submit">Sign in</button>
    </form>
    <div class="or"><span>or continue with</span></div>
    <div class="social">
      <button class="btn ghost" type="button" disabled>Google</button>
      <button class="btn ghost" type="button" disabled>Apple</button>
      <button class="btn ghost" type="button" disabled>X</button>
    </div>
    <p class="note">Google, Apple and X sign-in need a server and developer credentials, so they can't work from a standalone page. Email accounts are stored in this browser only.</p>
  </div>
</section>

<div id="app" hidden>
<div class="frame" id="frame" data-pane="overview">
  <aside class="lcol" id="lcol">
    <div class="lc-top">
      <button class="icbtn" id="lcBell" type="button" aria-label="Alerts"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M6 17h12l-1.5-2.2V10a4.5 4.5 0 0 0-9 0v4.8z"/><path d="M10 20a2 2 0 0 0 4 0"/></svg><i class="dot" id="lcDot" hidden></i></button>
      <button class="icbtn theme-toggle" id="themeBtn" type="button"></button>
    </div>
    <div class="lc-chart"><svg id="lcChart" viewBox="0 0 260 140" aria-label="Spending this month"></svg><div class="lc-big" id="lcBig"></div></div>
    <div class="lc-chips" id="lcChips"></div>
    <div class="lc-last">
      <div class="ll-top"><span class="sq fl" id="llAv"></span><div><small>Latest entry</small><b id="llName"></b></div></div>
      <div class="ll-art fl" id="llArt"></div>
      <div class="ll-bot"><button class="pill-out" id="lcAdd" type="button">Add</button><div class="ll-meta"><b id="lcCount"></b><span id="lcN"></span></div></div>
    </div>
    <div class="lc-bal"><div><small>Net this month</small><b id="lcBal"></b></div><span class="lc-all">All</span></div>
    <div class="lc-cats" id="lcCats"></div>
    <div class="lc-fabs"><button class="fab cyan" id="fabAdd" type="button" aria-label="Add transaction"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12 5v14M5 12h14"/></svg></button><button class="fab blue" id="fabConv" type="button" aria-label="Currency converter"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M4 8h14l-3.5-3.5M20 16H6l3.5 3.5"/></svg></button></div>
  </aside>

  <div class="mcol">
    <div class="topbar">
      <nav class="navicons" aria-label="Sections">
      <button class="nav" type="button" data-nav="overview" aria-label="Overview" title="Overview"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M3 11.5 12 4l9 7.5"/><path d="M5.5 10v9.5h13V10"/></svg></button>
      <button class="nav" type="button" data-nav="transactions" aria-label="Transactions" title="Transactions"><svg viewBox="0 0 24 24" aria-hidden="true"><rect x="3" y="6" width="18" height="13" rx="3"/><path d="M3 10.5h18"/></svg></button>
      <button class="nav" type="button" data-nav="recurring" aria-label="Recurring" title="Recurring"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M4 12a7 7 0 0 1 12-4.9L18 9"/><path d="M18 4v5h-5"/><path d="M20 12a7 7 0 0 1-12 4.9L6 15"/><path d="M6 20v-5h5"/></svg></button>
      <button class="nav" type="button" data-nav="spending" aria-label="Spending" title="Spending"><svg viewBox="0 0 24 24" aria-hidden="true"><circle cx="12" cy="12" r="8.5"/><path d="M12 3.5V12h8.5"/></svg></button>
      <button class="nav" type="button" data-nav="forecast" aria-label="Forecast" title="Forecast"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12 3l2.2 6.3L21 12l-6.8 2.7L12 21l-2.2-6.3L3 12l6.8-2.7z"/></svg></button>
      <button class="nav" type="button" data-nav="goals" aria-label="Goals" title="Goals"><svg viewBox="0 0 24 24" aria-hidden="true"><circle cx="12" cy="12" r="8.5"/><circle cx="12" cy="12" r="4.5"/><circle cx="12" cy="12" r=".8"/></svg></button>
      <button class="nav" type="button" data-nav="debts" aria-label="Debts" title="Debts"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M3 9.5 12 4l9 5.5"/><path d="M5 10v8M9.7 10v8M14.3 10v8M19 10v8"/><path d="M3 20h18"/></svg></button>
      <button class="nav" type="button" data-nav="tips" aria-label="Saving tips" title="Saving tips"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M9 18h6M10 21h4"/><path d="M12 3a6 6 0 0 0-3.5 10.9c.6.5 1 1.2 1 2v.1h5v-.1c0-.8.4-1.5 1-2A6 6 0 0 0 12 3z"/></svg></button>
      <button class="nav" type="button" data-nav="converter" aria-label="Currency converter" title="Currency converter"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M4 8h14l-3.5-3.5M20 16H6l3.5 3.5"/></svg></button>
      <button class="nav" type="button" data-nav="crypto" aria-label="Crypto" title="Crypto"><svg viewBox="0 0 24 24" aria-hidden="true"><circle cx="12" cy="12" r="8.5"/><path d="M9.5 8v8M9.5 9h3.6a1.7 1.7 0 0 1 0 3.4H9.5m0 0h4.2a1.7 1.7 0 0 1 0 3.4H9.5"/></svg></button>
      <button class="nav" type="button" data-nav="appearance" aria-label="Appearance" title="Appearance"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12 3.5a8.5 8.5 0 1 0 0 17c1.3 0 2-.9 2-1.9 0-1.4-1-1.6-1-2.6 0-.9.7-1.5 1.7-1.5H17a3.5 3.5 0 0 0 3.5-3.5C20.5 6.7 16.7 3.5 12 3.5z"/><circle cx="8" cy="11" r="1"/><circle cx="11" cy="7.5" r="1"/><circle cx="15.5" cy="8.5" r="1"/></svg></button>
      </nav>
      <div class="tb-right">
        <div class="mwrap" id="mwrap">
          <button class="icbtn mnav" id="mPrev" type="button" aria-label="Previous month">&#9664;</button>
          <input type="month" id="month" aria-label="Month">
          <button class="icbtn mnav" id="mNext" type="button" aria-label="Next month">&#9654;</button>
        </div>
        <button class="pill-out" id="tbAdd" type="button">Add</button>
        <div class="wallet"><svg viewBox="0 0 24 24" aria-hidden="true"><rect x="3" y="6" width="18" height="13" rx="3"/><path d="M16 12.5h5M3 9.5h13"/></svg><b id="tbBal"></b></div>
      </div>
    </div>
    <div class="mscroll" id="mscroll">
<main class="wrap" id="dash">

  <div class="pane" data-pane="overview">
  <section class="hero">
    <div class="hero-art">
      <svg class="ring" viewBox="0 0 120 120" aria-hidden="true"><circle cx="60" cy="60" r="52" class="ring-bg"/><circle cx="60" cy="60" r="52" id="ringFg" class="ring-fg" transform="rotate(-90 60 60)"/></svg>
      <svg class="coins" viewBox="0 0 120 120" aria-hidden="true">
        <defs><linearGradient id="cg1" x1="0" y1="0" x2="1" y2="1"><stop offset="0" stop-color="#ffd166"/><stop offset="1" stop-color="#ff8a4c"/></linearGradient><linearGradient id="cg2" x1="0" y1="0" x2="1" y2="1"><stop offset="0" stop-color="#ff5470"/><stop offset="1" stop-color="#b3203f"/></linearGradient></defs>
        <ellipse cx="60" cy="88" rx="30" ry="9" fill="#0b0d2a" opacity=".35"/>
        <rect x="32" y="70" width="56" height="14" rx="7" fill="url(#cg2)"/><ellipse cx="60" cy="70" rx="28" ry="8" fill="#ff7a90"/>
        <rect x="36" y="54" width="48" height="14" rx="7" fill="url(#cg1)"/><ellipse cx="60" cy="54" rx="24" ry="7" fill="#ffe29a"/>
        <rect x="40" y="38" width="40" height="14" rx="7" fill="url(#cg2)"/><ellipse cx="60" cy="38" rx="20" ry="6" fill="#ff7a90"/>
        <text x="60" y="42" text-anchor="middle" font-size="9" font-weight="700" fill="#fff" id="coinSym"></text>
      </svg>
    </div>
    <div class="hero-info">
      <h3 class="sec">Information</h3>
      <div class="hero-nums"><div><b id="hSpent"></b><small>Spent so far</small></div><span class="dbl">&raquo;</span><div><b id="hProj"></b><small id="hProjL">Projected</small></div></div>
      <div class="hero-pills"><span class="pill-dark" id="hBudget"></span><button class="pill-out" id="hSaved" type="button"></button></div>
    </div>
  </section>

  <div class="feat">
    <button class="fc fc-blue" type="button" data-go="goals"><span class="glyph">&#9678;</span><p id="fcA"></p></button>
    <button class="fc fc-purple" type="button" data-go="tips"><span class="glyph">&#10022;</span><p id="fcB"></p><i class="arr">&rarr;</i></button>
    <button class="fc fc-coral" type="button" data-go="spending" id="fcCBtn"><span class="glyph">%</span><p id="fcC"></p></button>
  </div>

  <section class="statbox">
    <div class="head"><h3 class="sec">Statistic</h3><div class="stat-meta"><span id="stN"></span><span id="stT"></span><span id="stG"></span></div></div>
    <div id="statList"></div>
    <button class="pill-out" id="stAll" type="button">View all transactions</button>
  </section>


  <section class="card" id="alertCard" style="margin-bottom:16px" hidden>
    <h2>Heads up</h2>
    <ul class="alerts" id="alerts"></ul>
  </section>

  <section class="stats" aria-label="Summary">
    <div class="card stat main"><p class="k">Total spent</p><p class="v" id="total">0.00</p></div>
    <div class="card stat"><p class="k">Expenses</p><p class="v" id="count">0</p></div>
    <div class="card stat"><p class="k">Average per day</p><p class="v" id="avg">0.00</p></div>
  </section>

  <section class="card" style="margin-bottom:16px">
    <h2>Money in vs money out</h2>
    <div id="flow"></div>
  </section>

  <section class="card" style="margin-bottom:16px">
    <h2>Progress</h2>
    <div class="tgrid" id="tgrid"></div>
  </section>
  </div>

  <div class="pane" data-pane="transactions" hidden>
    <section class="card" style="margin-bottom:16px">
      <div class="head" style="margin-bottom:12px">
        <h2 style="margin:0" id="txTitle">New transaction</h2>
        <div class="seg" id="txSeg" role="group" aria-label="Transaction type">
          <button type="button" data-t="out" aria-pressed="true">Money out</button>
          <button type="button" data-t="in" aria-pressed="false">Money in</button>
        </div>
      </div>
      <form id="form" novalidate>
        <label class="wide">Description
          <input id="desc" maxlength="80" placeholder="e.g. Groceries" autocomplete="off">
        </label>
        <label>Amount<span class="hint" id="amtCur"></span>
          <input id="amount" type="number" inputmode="decimal" min="0" step="0.01" placeholder="0.00">
        </label>
        <label>Category
          <select id="cat">
            <option>Food</option><option>Transport</option><option>Bills</option>
            <option>Shopping</option><option>Health</option><option>Other</option>
          </select>
        </label>
        <label class="wide">Date
          <input id="date" type="date">
        </label>
        <p class="err" id="err" role="alert"></p>
        <button class="btn wide" id="txGo" type="submit">Add expense</button>
        <button class="btn ghost wide" id="txCancel" type="button" hidden>Cancel editing</button>
      </form>
    </section>

  <section class="card">
    <div class="head">
      <h2>Transactions</h2>
    </div>
    <div class="fbar">
      <input id="fQ" type="search" placeholder="Search description or category\u2026" aria-label="Search transactions" autocomplete="off">
      <select id="fType" aria-label="Type"><option value="">All types</option><option value="out">Money out</option><option value="in">Money in</option></select>
      <select id="fCat" aria-label="Category"></select>
      <div class="seg" id="fScope" role="group" aria-label="Range">
        <button type="button" data-sc="month" aria-pressed="true">This month</button>
        <button type="button" data-sc="all" aria-pressed="false">All time</button>
      </div>
    </div>
    <p class="note" id="fSum"></p>
    <ul class="tx" id="list"></ul>
  </section>
  </div>

  <div class="pane" data-pane="spending" hidden>
    <section class="card" style="margin-bottom:16px">
      <div class="head" style="margin-bottom:14px">
        <h2 style="margin:0">Spending by category</h2>
        <div class="seg" role="group" aria-label="Category chart type">
          <button type="button" data-pt="donut" aria-pressed="true">Donut</button>
          <button type="button" data-pt="pie" aria-pressed="false">Pie</button>
          <button type="button" data-pt="bars" aria-pressed="false">Bars</button>
        </div>
      </div>
      <div class="donutwrap">
        <svg id="donut" class="donut" viewBox="0 0 120 120" role="img" aria-label="Pie chart of spending by category"></svg>
        <ul class="cats" id="cats"></ul>
      </div>
    </section>

  <section class="card" style="margin-bottom:16px">
    <div class="head">
      <h2 id="bt">Daily spending</h2>
      <div class="seg" role="group" aria-label="Chart view">
        <button type="button" data-v="daily" aria-pressed="true">Daily</button>
        <button type="button" data-v="monthly" aria-pressed="false">Monthly</button>
      </div>
    </div>
    <div class="chartopts">
      <div class="seg" role="group" aria-label="Chart type">
        <button type="button" data-ct="bar" aria-pressed="true">Bar</button>
        <button type="button" data-ct="line" aria-pressed="false">Line</button>
        <button type="button" data-ct="area" aria-pressed="false">Area</button>
        <button type="button" data-ct="cumulative" aria-pressed="false">Cumulative</button>
      </div>
      <label class="chk" id="cmpRow"><input type="checkbox" id="cmpPrev"> Compare with last month</label>
    </div>
    <div class="chart" id="bars"></div>
    <div class="lg" id="barLegend"></div>
  </section>

  <section class="card" style="margin-bottom:16px">
    <h2>Category budgets</h2>
    <p class="muted" style="margin:0">Set a monthly limit for a category. The bar fills as you spend (green is safe, red is over), and you get an alert on the Overview when you're close.</p>
    <form id="bForm" class="cform" novalidate>
      <label>Category<select id="bCat"></select></label>
      <label>Monthly limit<input id="bAmt" type="number" min="0" step="0.01" inputmode="decimal" placeholder="0.00"></label>
      <button class="btn" type="submit">Set budget</button>
      <p class="err" id="bErr" role="alert"></p>
    </form>
    <ul class="debts" id="bList"></ul>
  </section>
  </div>

  <div class="pane" data-pane="recurring" hidden>
  <section class="card" style="margin-bottom:16px">
    <h2>Recurring transactions</h2>
    <p class="muted" style="margin:0">Rent, salary, subscriptions and other repeats. They are added automatically on their due dates whenever you open the app. If the first date is in the past, the missed ones are added right away.</p>
    <form id="rForm" class="rform" novalidate>
      <label class="span2">Description<input id="rDesc" maxlength="60" placeholder="e.g. Rent" autocomplete="off"></label>
      <label>Type<select id="rType"><option value="out">Money out</option><option value="in">Money in</option></select></label>
      <label>Category<select id="rCat"></select></label>
      <label>Amount<input id="rAmt" type="number" min="0" step="0.01" inputmode="decimal" placeholder="0.00"></label>
      <label>Repeats<select id="rFreq"><option value="weekly">Every week</option><option value="biweekly">Every 2 weeks</option><option value="monthly" selected>Every month</option><option value="yearly">Every year</option></select></label>
      <label>First date<input id="rStart" type="date"></label>
      <label>End date (optional)<input id="rEnd" type="date"></label>
      <p class="err" id="rErr" role="alert"></p>
      <button class="btn" type="submit">Add recurring</button>
    </form>
    <ul class="debts" id="rList"></ul>
  </section>
  </div>

  <div class="pane" data-pane="forecast" hidden>
  <section class="card" style="margin-bottom:16px">
    <div class="head" style="margin-bottom:6px"><h2 style="margin:0">Forecast</h2><span class="conf" id="fConf"></span></div>
    <p class="muted" id="fHead" style="margin:0 0 14px"></p>
    <div class="tgrid" id="fTiles"></div>
    <p class="note" id="fNote"></p>
  </section>

  <section class="card" style="margin-bottom:16px">
    <h2>Category outlook</h2>
    <ul class="debts" id="fCats"></ul>
  </section>

  <section class="card" style="margin-bottom:16px">
    <h2>When will you get there?</h2>
    <ul class="debts" id="fEta"></ul>
  </section>

  <section class="card" style="margin-bottom:16px">
    <div class="head" style="margin-bottom:6px"><h2 style="margin:0">AI insights</h2><span class="conf" id="aiWhen"></span></div>
    <p class="muted" style="margin:0 0 12px">Claude reads your category totals, goals and debts (not your transaction descriptions) and writes a prediction and a plan. AI can make mistakes, and this isn't financial advice.</p>
    <div class="tipbtns">
      <button class="btn" id="aiGo" type="button">Generate AI insights</button>
      <button class="btn ghost" id="aiStop" type="button" hidden>Stop</button>
    </div>
    <div id="aiOut" aria-live="polite"></div>
  </section>
  </div>

  <div class="pane" data-pane="appearance" hidden>
  <section class="card" style="margin-bottom:16px">
    <h2>Font</h2>
    <p class="muted" style="margin:0">Pick a typeface for the whole app. Your choice is saved on this device.</p>
    <div class="fontgrid" id="fontGrid" role="group" aria-label="Font"></div>
  </section>
  <section class="card" style="margin-bottom:16px">
    <h2>Text size</h2>
    <div class="seg" id="sizeSeg" role="group" aria-label="Text size">
      <button type="button" data-sz="0.9" aria-pressed="false">Small</button>
      <button type="button" data-sz="1" aria-pressed="true">Default</button>
      <button type="button" data-sz="1.15" aria-pressed="false">Large</button>
      <button type="button" data-sz="1.3" aria-pressed="false">Extra large</button>
    </div>
  </section>
  <section class="card" style="margin-bottom:16px">
    <h2>Theme</h2>
    <div class="seg" role="group" aria-label="Theme">
      <button type="button" data-th="auto" aria-pressed="true">Auto</button>
      <button type="button" data-th="light" aria-pressed="false">Light</button>
      <button type="button" data-th="dark" aria-pressed="false">Dark</button>
    </div>
    <p class="note">Auto follows your device's setting.</p>
  </section>
  <section class="card">
    <h2>Preview</h2>
    <p class="prevh">Your month at a glance</p>
    <p class="prevbig" id="apAmt"></p>
    <p class="prevp">The quick brown fox jumps over the lazy dog. 0123456789</p>
    <p class="note">Small print looks like this.</p>
    <button class="btn ghost" id="apReset" type="button">Reset font and size</button>
  </section>
  </div>

  <div class="pane" data-pane="goals" hidden>
  <section class="card" style="margin-bottom:16px">
    <h2>Goals</h2>
    <p class="quote" id="gQuote"></p>
    <div class="tgrid" id="gSum"></div>
    <form id="gForm" class="gform" novalidate>
      <label class="span2">Goal<input id="gName" maxlength="50" placeholder="e.g. New car" autocomplete="off"></label>
      <label>Icon
        <select id="gIcon">
          <option value="🚗">🚗 Car</option><option value="🏠">🏠 Home</option><option value="📱">📱 Phone</option><option value="💻">💻 Laptop</option>
          <option value="✈️">✈️ Trip</option><option value="🎓">🎓 Education</option><option value="💍">💍 Wedding</option><option value="🏍️">🏍️ Motorbike</option>
          <option value="🛠️">🛠️ Business</option><option value="🎁">🎁 Gift</option><option value="🎯">🎯 Other</option>
        </select>
      </label>
      <label>Target amount<input id="gTarget" type="number" min="0" step="0.01" inputmode="decimal" placeholder="0.00"></label>
      <label>Saved so far<input id="gSaved" type="number" min="0" step="0.01" inputmode="decimal" placeholder="0.00"></label>
      <label>Target date (optional)<input id="gDate" type="date"></label>
      <p class="err" id="gErr" role="alert"></p>
      <button class="btn" type="submit">Add goal</button>
    </form>
    <ul class="goals" id="gList"></ul>
  </section>
  </div>

  <div class="pane" data-pane="debts" hidden>
  <section class="card" style="margin-bottom:16px">
    <h2>Debts</h2>
    <div class="tgrid" id="dsum"></div>
    <form id="dform" class="dform" novalidate>
      <input id="dName" maxlength="60" placeholder="Who or what (e.g. Student loan)" aria-label="Debt name" autocomplete="off">
      <select id="dKind" aria-label="Debt type"><option value="owe">I owe</option><option value="owed">Owed to me</option></select>
      <input id="dTotal" type="number" min="0" step="0.01" inputmode="decimal" placeholder="Total amount" aria-label="Total amount">
      <input id="dDue" type="date" aria-label="Due date (optional)">
      <button class="btn" type="submit">Add debt</button>
      <p class="err" id="dErr" role="alert"></p>
    </form>
    <ul class="debts" id="dlist"></ul>
  </section>
  </div>

  <div class="pane" data-pane="tips" hidden>
  <section class="card" style="margin-bottom:16px">
    <div class="head" style="margin-bottom:12px">
      <h2 style="margin:0">Daily saving tips</h2>
      <span class="streak" id="tStreak"></span>
    </div>
    <div class="tipbox" id="tipMain"></div>
    <div class="tipbtns">
      <button class="btn ghost" id="tPrev" type="button">Previous tip</button>
      <button class="btn ghost" id="tNext" type="button">Next tip</button>
      <button class="btn" id="tDone" type="button">Mark today's tip as done</button>
    </div>
    <div class="tipbox alt" id="tipFor"></div>
  </section>
  </div>

  <div class="pane" data-pane="converter" hidden>
  <section class="card" style="margin-bottom:16px">
    <h2>Currency converter</h2>
    <div class="cv">
      <label>Amount<input id="cvAmt" type="number" min="0" step="any" inputmode="decimal" value="100"></label>
      <label>From<select id="cvFrom"></select></label>
      <button class="btn ghost cvswap" id="cvSwap" type="button" aria-label="Swap currencies">&#8644;</button>
      <label>To<select id="cvTo"></select></label>
      <label>Your own rate (optional)<input id="cvRate" type="number" min="0" step="any" inputmode="decimal" placeholder="1 From = ? To"></label>
    </div>
    <div class="cvout" id="cvOut" aria-live="polite"></div>
    <p class="note" id="cvNote"></p>
    <button class="linkbtn" id="cvUse" type="button">Use this month's spending as the amount</button>
  </section>
  </div>

  <div class="pane" data-pane="crypto" hidden>
  <section class="card" style="margin-bottom:16px">
    <h2>Crypto</h2>
    <div class="tgrid" id="cSum"></div>
    <form id="cForm" class="cform" novalidate>
      <label>Coin<select id="cCoin"></select></label>
      <label>Amount held<input id="cAmt" type="number" min="0" step="any" inputmode="decimal" placeholder="e.g. 0.05"></label>
      <button class="btn" type="submit">Add holding</button>
      <p class="err" id="cErr" role="alert"></p>
    </form>
    <ul class="debts" id="cList"></ul>
    <h2 style="margin-top:24px">Market prices</h2>
    <input id="cFind" type="search" placeholder="Search coins…" aria-label="Search coins" autocomplete="off">
    <ul class="cprices" id="cPrices"></ul>
    <p class="note" id="cNote"></p>
  </section>

  <section class="card" style="margin-bottom:16px">
    <h2>Crypto converter</h2>
    <div class="cv">
      <label>Amount<input id="cxAmt" type="number" min="0" step="any" inputmode="decimal" value="1"></label>
      <label>From<select id="cxFrom"></select></label>
      <button class="btn ghost cvswap" id="cxSwap" type="button" aria-label="Swap assets">&#8644;</button>
      <label>To<select id="cxTo"></select></label>
      <label>Your own rate (optional)<input id="cxRate" type="number" min="0" step="any" inputmode="decimal" placeholder="1 From = ? To"></label>
    </div>
    <div class="cvout" id="cxOut" aria-live="polite"></div>
    <p class="note" id="cxNote"></p>
  </section>
  </div>

</main>

<main class="wrap" id="profileView" hidden>
  <div class="head" style="margin-bottom:16px">
    <h2 style="font-size:1.3rem;margin:0">Profile</h2>
    <button class="btn ghost" id="back" type="button">Back to dashboard</button>
  </div>
  <section class="card" style="margin-bottom:16px">
    <h2>Avatar</h2>
    <div class="avhead">
      <div class="avprev" id="avPrev"></div>
      <p class="muted" style="margin:0">Pick the avatar that represents you. Your choice applies instantly.</p>
    </div>
    <div class="avgrid" id="avGrid" role="group" aria-label="Choose an avatar"></div>
  </section>

  <div class="grid">
    <section class="card">
      <h2>Account details</h2>
      <form id="pForm" novalidate>
        <label class="wide">Full name<input id="pName" maxlength="60"></label>
        <label class="wide">Email<input id="pEmail" type="email"></label>
        <label class="wide">Country<select id="pCountry"></select><span class="hint" id="pCurHint"></span></label>
        <div class="lab wide">Initials color<div class="swatches" id="pColors"></div></div>
        <label>Monthly budget (used if no money in is logged)<input id="pBudget" type="number" min="0" step="0.01" inputmode="decimal"></label>
        <label>Monthly savings goal<input id="pGoal" type="number" min="0" step="0.01" inputmode="decimal"></label>
        <p class="err" id="pErr" role="alert"></p>
        <p class="ok" id="pOk" role="status"></p>
        <button class="btn wide" type="submit">Save changes</button>
      </form>
    </section>
    <section class="card">
      <h2>Change password</h2>
      <form id="pwForm" novalidate>
        <label>Current password<input id="wCur" type="password" autocomplete="current-password"></label>
        <label>New password<input id="wNew" type="password" autocomplete="new-password" placeholder="At least 8 characters"></label>
        <p class="err" id="wErr" role="alert"></p>
        <p class="ok" id="wOk" role="status"></p>
        <button class="btn" type="submit">Update password</button>
      </form>
      <h2 style="margin-top:28px">Delete account</h2>
      <p class="muted" style="margin-bottom:12px">Removes your profile and every expense stored for it in this browser.</p>
      <button class="btn danger" id="delAcc" type="button">Delete account</button>
    </section>
  </div>

  <section class="card" style="margin-top:16px">
    <h2>Your data</h2>
    <p class="muted" style="margin:0 0 12px">Your data lives in this browser only. Download a backup now and then, or use it to move to another device.</p>
    <div class="tipbtns">
      <button class="btn ghost" id="exCsv" type="button">Export transactions (CSV)</button>
      <button class="btn ghost" id="exJson" type="button">Download full backup (JSON)</button>
    </div>
    <label class="chk" style="display:block;margin:6px 0">Restore from a backup file<input id="imFile" type="file" accept=".json,application/json"></label>
    <textarea id="imText" rows="4" placeholder="...or paste backup text here, then press Restore" aria-label="Backup text"></textarea>
    <div class="tipbtns" style="margin-top:10px">
      <button class="btn ghost" id="imGo" type="button">Restore from backup</button>
      <button class="btn danger" id="clrData" type="button">Clear all my data</button>
    </div>
    <p class="err" id="dmErr" role="alert"></p>
    <p class="ok" id="dmOk" role="status"></p>
  </section>
</main>
    </div>
  </div>

  <aside class="rcol" id="rcol">
    <div class="rc-user">
      <button class="av" id="avBtn" type="button" aria-label="Profile"></button>
      <span class="rc-name" id="rcName"></span>
      <button class="chip" id="curChip" type="button"></button>
      <button class="icbtn" id="signOut" type="button" aria-label="Sign out" title="Sign out"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M9 4H5.5A1.5 1.5 0 0 0 4 5.5v13A1.5 1.5 0 0 0 5.5 20H9"/><path d="M16 8l4 4-4 4M20 12H9"/></svg></button>
    </div>
    <div class="rc-feed">
      <div class="rc-head"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M5 12h14M13 6l6 6-6 6M4 5v14"/></svg><span class="rc-count"><svg viewBox="0 0 24 24" aria-hidden="true"><circle cx="10" cy="8" r="3.2"/><path d="M4 19c0-3 2.7-5 6-5s6 2 6 5"/></svg><b id="rcCount"></b></span></div>
      <div class="feed" id="feed"></div>
    </div>
    <div class="rc-input">
      <input id="qaText" placeholder="Quick add, e.g. lunch 25" autocomplete="off" aria-label="Quick add a transaction">
      <div class="rc-tools">
        <button class="tool" id="qaType" type="button" aria-label="Money out" title="Money out / money in">&minus;</button>
        <select id="qaCat" aria-label="Category"></select>
        <button class="send" id="qaSend" type="button" aria-label="Add"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M4 12 20 4l-4.5 16-3.5-6.5z"/></svg></button>
      </div>
    </div>
  </aside>
</div>
</div>

<div class="toast" id="toast" role="status" hidden>
  <span class="ti"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M13 3 5 13.5h5.5L10 21l8-10.5h-5.5z"/></svg></span>
  <div class="tb"><div class="tt"><b>System Message</b><time id="toastTime"></time></div><div id="toastMsg"></div></div>
  <button class="linkbtn" id="toastUndo" type="button" hidden>Undo</button>
</div>

<script>
(function(){
  var state = {items:[], debts:[], holdings:[], goals:[], tipsDone:[], recurring:[], budgets:{}, cur:"$", code:"", budget:0, goal:0};
  var lastTotal = 0;
  var $ = function(id){return document.getElementById(id)};
  var themeBtns = document.querySelectorAll(".theme-toggle");
  function curTheme(){
    var t = document.documentElement.getAttribute("data-theme");
    if(t === "dark" || t === "light") return t;
    return window.matchMedia && window.matchMedia("(prefers-color-scheme: dark)").matches ? "dark" : "light";
  }
  function paintTheme(){
    var dark = curTheme() === "dark"; markThemeSeg();
    Array.prototype.forEach.call(themeBtns, function(b){
      b.textContent = dark ? "\u2600\uFE0F" : "\uD83C\uDF19";
      b.setAttribute("aria-label", dark ? "Switch to light mode" : "Switch to dark mode");
    });
  }
  try{ var savedTheme = localStorage.getItem("et-theme"); if(savedTheme === "dark" || savedTheme === "light") document.documentElement.setAttribute("data-theme", savedTheme); else if(savedTheme !== "auto") document.documentElement.setAttribute("data-theme", "dark"); }catch(e){ document.documentElement.setAttribute("data-theme", "dark"); }
  paintTheme();
  Array.prototype.forEach.call(themeBtns, function(b){
    b.addEventListener("click", function(){
      var t = curTheme() === "dark" ? "light" : "dark";
      document.documentElement.setAttribute("data-theme", t);
      try{ localStorage.setItem("et-theme", t); }catch(e){}
      paintTheme();
    });
  });
  try{ if(window.matchMedia) window.matchMedia("(prefers-color-scheme: dark)").addEventListener("change", paintTheme); }catch(e){}

  function markThemeSeg(){
    var mode = document.documentElement.getAttribute("data-theme"); if(mode !== "dark" && mode !== "light") mode = "auto";
    Array.prototype.forEach.call(document.querySelectorAll("[data-th]"), function(b){ b.setAttribute("aria-pressed", b.getAttribute("data-th") === mode ? "true" : "false"); });
  }
  Array.prototype.forEach.call(document.querySelectorAll("[data-th]"), function(b){
    b.addEventListener("click", function(){
      var mode = b.getAttribute("data-th");
      if(mode === "auto"){ document.documentElement.removeAttribute("data-theme"); try{ localStorage.setItem("et-theme", "auto"); }catch(e){} }
      else { document.documentElement.setAttribute("data-theme", mode); try{ localStorage.setItem("et-theme", mode); }catch(e){} }
      paintTheme();
    });
  });
  markThemeSeg();

  /* ---------- appearance: fonts and text size (saved on this device) ---------- */
  var EMO = ',"Noto Color Emoji"';
  var FONTS = [
    {id:"inter", name:"Inter", cap:"Clean and modern", g:null, stack:'Inter' + EMO + ',system-ui,-apple-system,"Segoe UI",Roboto,sans-serif'},
    {id:"system", name:"System default", cap:"Your device's own font", g:null, stack:'system-ui' + EMO + ',-apple-system,"Segoe UI",Roboto,sans-serif'},
    {id:"poppins", name:"Poppins", cap:"Geometric and bold (default)", g:"Poppins:wght@400;500;600;700", stack:'Poppins' + EMO + ',system-ui,sans-serif'},
    {id:"nunito", name:"Nunito", cap:"Soft and rounded", g:"Nunito:wght@400;500;600;700", stack:'Nunito' + EMO + ',system-ui,sans-serif'},
    {id:"source", name:"Source Sans 3", cap:"Calm and readable", g:"Source Sans 3:wght@400;500;600;700", stack:'"Source Sans 3"' + EMO + ',system-ui,sans-serif'},
    {id:"lexend", name:"Lexend", cap:"Made for easy reading", g:"Lexend:wght@400;500;600;700", stack:'Lexend' + EMO + ',system-ui,sans-serif'},
    {id:"atkinson", name:"Atkinson Hyperlegible", cap:"Designed for low vision", g:"Atkinson Hyperlegible:wght@400;700", stack:'"Atkinson Hyperlegible"' + EMO + ',system-ui,sans-serif'},
    {id:"merri", name:"Merriweather", cap:"Classic serif", g:"Merriweather:wght@400;700", stack:'Merriweather' + EMO + ',Georgia,serif'},
    {id:"lora", name:"Lora", cap:"Elegant serif", g:"Lora:wght@400;500;600;700", stack:'Lora' + EMO + ',Georgia,serif'},
    {id:"mono", name:"Roboto Mono", cap:"Monospace: numbers line up", g:"Roboto Mono:wght@400;500;600;700", stack:'"Roboto Mono"' + EMO + ',ui-monospace,Menlo,Consolas,monospace'},
    {id:"comic", name:"Comic Neue", cap:"Casual and friendly", g:"Comic Neue:wght@400;700", stack:'"Comic Neue"' + EMO + ',"Comic Sans MS",system-ui,sans-serif'}
  ];
  var ap = {font:"poppins", size:1};
  try{ var rawAp = JSON.parse(localStorage.getItem("et-appearance")); if(rawAp){ if(FONTS.some(function(f){ return f.id === rawAp.font; })) ap.font = rawAp.font; if([0.9,1,1.15,1.3].indexOf(+rawAp.size) > -1) ap.size = +rawAp.size; } }catch(e){}
  function loadFont(f){
    if(!f.g || f.loaded) return; f.loaded = true;
    var l = document.createElement("link"); l.rel = "stylesheet";
    l.href = "https://fonts.googleapis.com/css2?family=" + f.g.replace(/ /g, "+") + "&display=swap"; document.head.appendChild(l);
  }
  function loadAllFonts(){ FONTS.forEach(loadFont); }
  function markAppearance(){
    Array.prototype.forEach.call(document.querySelectorAll("#fontGrid .fontopt"), function(b){ b.setAttribute("aria-pressed", b.getAttribute("data-f") === ap.font ? "true" : "false"); });
    Array.prototype.forEach.call(document.querySelectorAll("[data-sz]"), function(b){ b.setAttribute("aria-pressed", +b.getAttribute("data-sz") === ap.size ? "true" : "false"); });
  }
  function applyAppearance(){
    var f = FONTS.filter(function(x){ return x.id === ap.font; })[0] || FONTS[0]; loadFont(f);
    document.documentElement.style.setProperty("--font", f.stack); document.documentElement.style.setProperty("--ts", String(ap.size));
    markAppearance();
  }
  function saveAppearance(){ try{ localStorage.setItem("et-appearance", JSON.stringify(ap)); }catch(e){} }
  FONTS.forEach(function(f){
    var b = el("button","fontopt"); b.type = "button"; b.setAttribute("data-f", f.id);
    var n = el("span","fn", f.name); n.style.fontFamily = f.stack;
    var sm = el("span","fs","Aa  1,234.56  \u20ac \u00a3 \u20b5 \u20a6"); sm.style.fontFamily = f.stack;
    b.appendChild(n); b.appendChild(sm); b.appendChild(el("span","fc", f.cap));
    b.addEventListener("click", function(){ ap.font = f.id; saveAppearance(); applyAppearance(); });
    $("fontGrid").appendChild(b);
  });
  Array.prototype.forEach.call(document.querySelectorAll("[data-sz]"), function(b){
    b.addEventListener("click", function(){ ap.size = +b.getAttribute("data-sz"); saveAppearance(); applyAppearance(); try{ drawBars(); }catch(e){} });
  });
  $("apReset").addEventListener("click", function(){ ap = {font:"poppins", size:1}; saveAppearance(); applyAppearance(); try{ drawBars(); }catch(e){} });
  applyAppearance();
  var shown = [];
  var view = "daily";
  var NS = "http://www.w3.org/2000/svg";
  function svg(tag, attrs){
    var e = document.createElementNS(NS, tag);
    for(var k in attrs) e.setAttribute(k, attrs[k]);
    return e;
  }
  function compact(n){
    return Number(n).toLocaleString("en-US",{notation:"compact",maximumFractionDigits:1});
  }
  function niceMax(v){
    var pw = Math.pow(10, Math.floor(Math.log10(v))), f = [1,2,2.5,5,10];
    for(var i=0;i<f.length;i++){ if(f[i]*pw >= v) return f[i]*pw; }
    return 10*pw;
  }

  function drawDonut(by, keys, total){
    var s = $("donut"); s.innerHTML = "";
    var pie = pieType === "pie", r = pie ? 21 : 42, sw = pie ? 42 : 16, C = 2*Math.PI*r, off = 0;
    if(pieType === "bars") s.setAttribute("hidden",""); else s.removeAttribute("hidden");
    var base = svg("circle",{cx:60,cy:60,r:r,fill:"none","stroke-width":sw});
    base.style.stroke = "var(--line)"; s.appendChild(base);
    keys.forEach(function(c){
      var len = by[c]/total*C;
      var seg = svg("circle",{cx:60,cy:60,r:r,fill:"none","stroke-width":sw,
        "stroke-dasharray":len+" "+(C-len),"stroke-dashoffset":-off,transform:"rotate(-90 60 60)"});
      seg.style.stroke = "var(--c-" + c + ")";
      var t = svg("title",{}); t.textContent = c + ": " + fmt(by[c]);
      seg.appendChild(t); s.appendChild(seg); off += len;
    });
    var a = svg("text",{x:60,y:57,"text-anchor":"middle","class":"dk"}); a.textContent = "Total";
    var b = svg("text",{x:60,y:73,"text-anchor":"middle","class":"dv"}); b.textContent = sym().trim() + compact(total);
    if(!pie){ s.appendChild(a); s.appendChild(b); }
  }

  var chartType = "bar", pieType = "donut", cmpOn = false;
  function cum(arr){ var t = 0; return arr.map(function(v){ if(v === null) return null; t += v; return t; }); }
  function drawBars(){
    var host = $("bars"); host.innerHTML = ""; var lg = $("barLegend"); lg.innerHTML = "";
    var month = $("month").value, p = month.split("-"), y = +p[0], m = +p[1], i;
    var daily = view === "daily", labels = [], vals = [], tips = [], prev = null, ptips = [];
    $("cmpRow").hidden = !daily;
    if(daily){
      var dim = new Date(y, m, 0).getDate(), live = month === today().slice(0,7), last = live ? new Date().getDate() : dim;
      for(i = 1; i <= dim; i++){ labels.push(i === 1 || i % 5 === 0 ? String(i) : ""); vals.push(0); }
      shown.forEach(function(x){ vals[+x.date.slice(8,10) - 1] += x.amount; });
      if(cmpOn){
        var pk = prevKey(month), pdim = new Date(y, m - 1, 0).getDate(); prev = [];
        for(i = 0; i < dim; i++) prev.push(i < pdim ? 0 : null);
        state.items.forEach(function(x){
          if(x.type !== "in" && x.date.slice(0,7) === pk){ var dd = +x.date.slice(8,10) - 1; if(dd < dim) prev[dd] += x.amount; }
        });
      }
      if(chartType !== "bar" && live) for(i = last; i < dim; i++) vals[i] = null;
      if(chartType === "cumulative"){ vals = cum(vals); if(prev) prev = cum(prev); }
      vals.forEach(function(v, k){ tips.push(month + "-" + pad(k + 1) + ": " + (v === null ? "\u2014" : fmt(v))); });
      if(prev) prev.forEach(function(v, k){ ptips.push("Last month, day " + (k + 1) + ": " + (v === null ? "\u2014" : fmt(v))); });
    } else {
      for(i = 5; i >= 0; i--){
        var dt = new Date(y, m - 1 - i, 1), key = dt.getFullYear() + "-" + pad(dt.getMonth() + 1);
        var sum = state.items.filter(function(x){return x.date.slice(0,7) === key && x.type !== "in"})
          .reduce(function(t,x){return t + x.amount},0);
        labels.push(dt.toLocaleString(undefined,{month:"short"})); vals.push(sum);
      }
      if(chartType === "cumulative") vals = cum(vals);
      vals.forEach(function(v, k){ tips.push(labels[k] + ": " + fmt(v)); });
    }
    $("bt").textContent = daily ? (chartType === "cumulative" ? "Cumulative spending" : "Daily spending")
      : (chartType === "cumulative" ? "Monthly spending, running total" : "Monthly spending");
    var all = vals.concat(prev || []).filter(function(v){ return v !== null; });
    var max = all.length ? Math.max.apply(null, all) : 0;
    if(!(max > 0)){ host.appendChild(el("div","none","No spending to chart yet.")); return; }
    var top = niceMax(max);
    var W = Math.max(300, host.clientWidth || 600), H = 220, pl = 44, pr = 6, pt = 14, pb = 26;
    var iw = W - pl - pr, ih = H - pt - pb, n = vals.length, slot = iw / n, bw = Math.min(40, slot * 0.68);
    var base = pt + ih, cx = function(k){ return pl + slot * k + slot / 2; }, yy = function(v){ return base - v / top * ih; };
    var g = svg("svg",{width:W,height:H,viewBox:"0 0 " + W + " " + H,role:"img","aria-label":"Spending chart"});
    [0,0.5,1].forEach(function(f){
      var y0 = base - f * ih;
      var ln = svg("line",{x1:pl,x2:W-pr,y1:y0,y2:y0}); ln.style.stroke = "var(--line)"; g.appendChild(ln);
      var tx = svg("text",{x:pl-6,y:y0+4,"text-anchor":"end","class":"ax"}); tx.textContent = compact(f*top); g.appendChild(tx);
    });
    function tip(node, text){ var t = svg("title",{}); t.textContent = text; node.appendChild(t); }
    if(chartType === "bar"){
      if(prev) prev.forEach(function(v, k){
        if(v > 0){ var gr = svg("rect",{x:cx(k)-bw/2,y:yy(v),width:bw,height:base-yy(v),rx:3}); gr.style.fill = "var(--muted)"; gr.style.opacity = ".35"; tip(gr, ptips[k]); g.appendChild(gr); }
      });
      var cw = prev ? bw * 0.6 : bw;
      vals.forEach(function(v, k){
        if(v > 0){
          var rc = svg("rect",{x:cx(k)-cw/2,y:yy(v),width:cw,height:base-yy(v),rx:3}); rc.style.fill = "var(--accent)"; tip(rc, tips[k]); g.appendChild(rc);
          if(!daily && !prev){ var vt = svg("text",{x:cx(k),y:yy(v)-5,"text-anchor":"middle","class":"bv"}); vt.textContent = compact(v); g.appendChild(vt); }
        }
      });
    } else {
      var pts = function(arr){ var o = []; arr.forEach(function(v, k){ if(v !== null) o.push([cx(k), yy(v), k, v]); }); return o; };
      var path = function(q){ return q.map(function(c, j){ return (j ? "L" : "M") + c[0].toFixed(1) + " " + c[1].toFixed(1); }).join(" "); };
      var series = function(arr, tt, color, dashed, fill, labelPts){
        var q = pts(arr); if(!q.length) return;
        if(fill){
          var ar = svg("path",{d:path(q) + " L" + q[q.length-1][0].toFixed(1) + " " + base + " L" + q[0][0].toFixed(1) + " " + base + " Z"});
          ar.style.fill = color; ar.style.opacity = ".15"; g.appendChild(ar);
        }
        var ln = svg("path",{d:path(q),fill:"none","stroke-width":dashed ? 2 : 2.5,"stroke-linejoin":"round","stroke-linecap":"round"});
        ln.style.stroke = color; if(dashed) ln.setAttribute("stroke-dasharray","5 4"); g.appendChild(ln);
        q.forEach(function(c){
          var dot = svg("circle",{cx:c[0],cy:c[1],r:q.length <= 12 && !dashed ? 3.5 : 7});
          if(q.length <= 12 && !dashed){ dot.style.fill = color; } else { dot.style.fill = "transparent"; }
          tip(dot, tt[c[2]]); g.appendChild(dot);
          if(labelPts && q.length <= 7){ var vt = svg("text",{x:c[0],y:c[1]-9,"text-anchor":"middle","class":"bv"}); vt.textContent = compact(c[3]); g.appendChild(vt); }
        });
      };
      var filled = chartType === "area" || chartType === "cumulative";
      if(prev) series(prev, ptips, "var(--muted)", true, false, false);
      series(vals, tips, "var(--accent)", false, filled, !prev);
    }
    labels.forEach(function(lbl, k){
      if(lbl){ var lb = svg("text",{x:cx(k),y:H-8,"text-anchor":"middle","class":"ax"}); lb.textContent = lbl; g.appendChild(lb); }
    });
    host.appendChild(g);
    if(prev){
      var a1 = el("span"), a2 = el("span"), i1 = el("i"), i2 = el("i","dash");
      a1.appendChild(i1); a1.appendChild(document.createTextNode("This month")); a2.appendChild(i2); a2.appendChild(document.createTextNode("Last month"));
      lg.appendChild(a1); lg.appendChild(a2);
    }
  }

  function pressSeg(attr, val){
    Array.prototype.forEach.call(document.querySelectorAll("[" + attr + "]"), function(b){ b.setAttribute("aria-pressed", b.getAttribute(attr) === val ? "true" : "false"); });
  }
  function savePrefs(){ try{ localStorage.setItem("et-prefs-" + uid, JSON.stringify({ct:chartType, pt:pieType, cmp:cmpOn, v:view})); }catch(e){} }
  function loadPrefs(){
    var r = {}; try{ r = JSON.parse(localStorage.getItem("et-prefs-" + uid)) || {}; }catch(e){}
    chartType = ["bar","line","area","cumulative"].indexOf(r.ct) > -1 ? r.ct : "bar";
    pieType = ["donut","pie","bars"].indexOf(r.pt) > -1 ? r.pt : "donut";
    cmpOn = !!r.cmp; view = r.v === "monthly" ? "monthly" : "daily";
    pressSeg("data-ct", chartType); pressSeg("data-pt", pieType); pressSeg("data-v", view); $("cmpPrev").checked = cmpOn;
  }
  Array.prototype.forEach.call(document.querySelectorAll("[data-ct]"), function(b){
    b.addEventListener("click", function(){ chartType = b.getAttribute("data-ct"); pressSeg("data-ct", chartType); savePrefs(); drawBars(); });
  });
  Array.prototype.forEach.call(document.querySelectorAll("[data-pt]"), function(b){
    b.addEventListener("click", function(){ pieType = b.getAttribute("data-pt"); pressSeg("data-pt", pieType); savePrefs(); render(); });
  });
  Array.prototype.forEach.call(document.querySelectorAll("[data-v]"), function(b){
    b.addEventListener("click", function(){ setTimeout(savePrefs, 0); });
  });
  $("cmpPrev").addEventListener("change", function(){ cmpOn = this.checked; savePrefs(); drawBars(); });

  function save(){ try{ localStorage.setItem("et-data-" + uid, JSON.stringify({items:state.items, debts:state.debts, holdings:state.holdings, goals:state.goals, tipsDone:state.tipsDone, recurring:state.recurring, budgets:state.budgets})); }catch(e){} }
  function today(){
    var d = new Date(); d.setMinutes(d.getMinutes() - d.getTimezoneOffset());
    return d.toISOString().slice(0,10);
  }
  function sym(){
    var c = (state.cur || "").trim();
    return c.length > 1 && /\p{L}$/u.test(c) ? c + " " : c;
  }
  function fmt(n){
    var v = Number(n);
    return (v < 0 ? "-" : "") + sym() + Math.abs(v).toLocaleString("en-US",{minimumFractionDigits:2,maximumFractionDigits:2});
  }
  function pad(n){ return ("0" + n).slice(-2); }
  function prevKey(month){
    var p = month.split("-"), d = new Date(+p[0], +p[1]-2, 1);
    return d.getFullYear() + "-" + pad(d.getMonth()+1);
  }
  function sumTo(key, cut, type){
    return state.items.filter(function(x){
      return x.date.slice(0,7) === key && +x.date.slice(8,10) <= cut && (type === "in" ? x.type === "in" : x.type !== "in");
    }).reduce(function(t,x){return t + x.amount},0);
  }
  function cmp(cur, prev, hasPrev, higherIsGood, ref){
    if(!hasPrev) return {t:"No data for last month yet", c:""};
    var diff = cur - prev;
    if(Math.abs(diff) < 0.005) return {t:"Same as " + ref, c:""};
    var more = diff > 0;
    var txt = prev > 0 ? Math.round(Math.abs(diff)/prev*100) + "% " : fmt(Math.abs(diff)) + " ";
    txt += (more ? "more" : "less") + " than " + ref;
    return {t:(more ? "\u25b2 " : "\u25bc ") + txt, c:(more === higherIsGood) ? "good" : "bad"};
  }
  function tile(title, value, sub, cls){
    var t = el("div","tile");
    t.appendChild(el("p","k",title));
    t.appendChild(el("p","v",value));
    var s = el("p","s" + (cls ? " " + cls : ""));
    if(typeof sub === "string") s.textContent = sub; else s.appendChild(sub);
    t.appendChild(s);
    return t;
  }
  function setPrompt(what){
    var f = document.createDocumentFragment();
    var b = el("button","linkbtn","Open your profile");
    b.type = "button"; b.addEventListener("click", openProfile);
    f.appendChild(document.createTextNode("Set " + what + " to see this. ")); f.appendChild(b);
    return f;
  }
  function drawTrackers(month){
    var host = $("tgrid"); host.innerHTML = "";
    var live = month === today().slice(0,7), cut = live ? new Date().getDate() : 31;
    var pk = prevKey(month), ref = live ? "at this point last month" : "last month";
    var hasPrev = state.items.some(function(x){return x.date.slice(0,7) === pk});
    var spent = sumTo(month,31,"out"), prevSpent = sumTo(pk,cut,"out");
    var inNow = sumTo(month,31,"in"), inPrev = sumTo(pk,cut,"in");
    var fromIncome = inNow > 0, base = fromIncome ? inNow : state.budget;
    var prevBase = inPrev > 0 ? inPrev : state.budget, saved = base - spent;

    var t1;
    if(base > 0){
      var c1 = cmp(saved, prevBase - prevSpent, hasPrev, true, ref);
      t1 = tile("Saved this month" + (fromIncome ? " (money in \u2212 out)" : " (budget \u2212 out)"), fmt(saved), c1.t, c1.c);
    } else t1 = tile("Saved this month", "\u2014", setPrompt("a monthly budget or log money in"));
    host.appendChild(t1);

    var t2;
    if(state.goal > 0 && base > 0){
      var pct = Math.max(0, Math.min(100, saved/state.goal*100));
      var sub = saved < 0 ? "Spent " + fmt(-saved) + " more than came in"
        : saved >= state.goal ? "Goal reached: " + fmt(saved) + " of " + fmt(state.goal)
        : fmt(saved) + " of " + fmt(state.goal) + " (" + fmt(state.goal - saved) + " to go)";
      t2 = tile("Savings goal", Math.round(pct) + "%", sub, saved >= state.goal ? "good" : "");
      var tr = el("div","track"), fl = el("i");
      fl.style.display = "block"; fl.style.height = "100%"; setBar(fl, pct);
      tr.appendChild(fl); t2.insertBefore(tr, t2.lastChild);
    } else t2 = tile("Savings goal", "\u2014", setPrompt(state.goal > 0 ? "a monthly budget or log money in" : "a savings goal"));
    host.appendChild(t2);

    var c3 = cmp(spent, prevSpent, hasPrev, false, ref);
    host.appendChild(tile("Spending vs last month", fmt(spent), c3.t, c3.c));
  }

  function drawFlow(out, inn){
    var host = $("flow"); host.innerHTML = "";
    var max = Math.max(out, inn, 1);
    [["Money in", inn, "var(--good)"], ["Money out", out, "var(--bad)"]].forEach(function(r){
      var row = el("div","frow"), top = el("div","row");
      top.appendChild(el("b","",r[0])); top.appendChild(el("span","",fmt(r[1])));
      var tr = el("div","track"), f = el("i");
      f.style.width = (r[1]/max*100) + "%"; f.style.background = r[2];
      tr.appendChild(f); row.appendChild(top); row.appendChild(tr); host.appendChild(row);
    });
    var net = inn - out, msg;
    if(inn <= 0 && out <= 0) msg = "Nothing recorded for this month yet.";
    else if(inn <= 0) msg = "No money in recorded for this month.";
    else if(net >= 0) msg = "Net +" + fmt(net) + " \u00b7 you kept " + Math.round(net/inn*100) + "% of what came in";
    else msg = "Net " + fmt(net) + " \u00b7 you spent more than came in";
    host.appendChild(el("p","net" + (inn > 0 ? (net >= 0 ? " good" : " bad") : ""), msg));
  }

  function dueInfo(d){
    if(!d.due) return null;
    var days = Math.round((new Date(d.due + "T00:00:00") - new Date(today() + "T00:00:00")) / 86400000);
    var lead = d.kind === "owed" ? "Expected " : "Due ";
    if(days < 0) return {t:"Overdue by " + (-days) + (days === -1 ? " day" : " days"), bad:true, days:days};
    if(days === 0) return {t:lead + "today", bad:false, days:days};
    if(days <= 14) return {t:lead + "in " + days + (days === 1 ? " day" : " days"), bad:false, days:days};
    return {t:lead + d.due, bad:false, days:days};
  }
  function drawDebts(){
    var sum = $("dsum"), list = $("dlist"); sum.innerHTML = ""; list.innerHTML = "";
    var owe = 0, oweTotal = 0, owed = 0, oweCount = 0, active = [];
    state.debts.forEach(function(d){
      var left = Math.max(0, d.total - d.paid);
      if(d.kind === "owed") owed += left; else { owe += left; oweTotal += d.total; if(left > 0.004) oweCount++; }
      if(left > 0.004) active.push(d);
    });
    var paidPct = oweTotal > 0 ? Math.round((oweTotal - owe)/oweTotal*100) : 0;
    sum.appendChild(tile("You owe", fmt(owe),
      oweTotal > 0 ? paidPct + "% paid off \u00b7 " + oweCount + (oweCount === 1 ? " active debt" : " active debts") : "No debts recorded",
      oweTotal > 0 && owe <= 0.004 ? "good" : ""));
    sum.appendChild(tile("Owed to you", fmt(owed), owed > 0 ? "Still to be repaid" : "Nobody owes you right now", ""));
    var next = null;
    active.forEach(function(d){ var i = dueInfo(d); if(i && (!next || i.days < next.i.days)) next = {d:d, i:i}; });
    sum.appendChild(next ? tile("Next due", next.d.name, next.i.t, next.i.bad ? "bad" : "") : tile("Next due", "\u2014", "No due dates set", ""));

    if(!state.debts.length){ list.appendChild(el("li","empty","No debts yet. Add one above to start tracking repayments.")); return; }
    var sorted = state.debts.slice().sort(function(a,b){
      return ((a.total - a.paid > 0.004) ? 0 : 1) - ((b.total - b.paid > 0.004) ? 0 : 1) || b.id - a.id;
    });
    sorted.forEach(function(d){
      var left = Math.max(0, d.total - d.paid), done = left <= 0.004;
      var pct = d.total > 0 ? Math.min(100, d.paid/d.total*100) : 0, owedKind = d.kind === "owed";
      var li = el("li"), top = el("div","dtop"), nm = el("span","dname", d.name);
      nm.appendChild(el("span","badge", owedKind ? "Owed to me" : "I owe"));
      top.appendChild(nm); top.appendChild(el("span","amt", done ? "Paid off" : fmt(left) + " left"));
      li.appendChild(top);
      var tr = el("div","track"), f = el("i");
      tr.style.marginTop = "10px"; setBar(f, done ? 100 : pct);
      tr.appendChild(f); li.appendChild(tr);
      var meta = el("div","dmeta");
      meta.appendChild(el("span","", fmt(d.paid) + " of " + fmt(d.total) + (owedKind ? " received" : " paid") + " (" + Math.round(pct) + "%)"));
      var di = done ? null : dueInfo(d);
      if(di) meta.appendChild(el("span", di.bad ? "bad" : "", di.t));
      li.appendChild(meta);
      var act = el("div","dact");
      if(!done){
        var inp = el("input"); inp.type = "number"; inp.min = "0"; inp.step = "0.01"; inp.placeholder = owedKind ? "Amount received" : "Payment";
        inp.setAttribute("inputmode","decimal"); inp.setAttribute("aria-label","Payment amount for " + d.name);
        var go = el("button","btn ghost", owedKind ? "Log repayment" : "Log payment"); go.type = "button";
        var pay = function(){
          var v = parseFloat(inp.value);
          if(!(v > 0)){ inp.focus(); return; }
          v = Math.min(Math.round(v*100)/100, left);
          d.paid = Math.round((d.paid + v)*100)/100;
          state.items.push({id:Date.now(), desc:(owedKind ? "Repayment from " : "Debt payment: ") + d.name, amount:v, cat:"Debt", date:today(), type:owedKind ? "in" : "out", debt:d.id});
          save(); render();
        };
        go.addEventListener("click", pay);
        inp.addEventListener("keydown", function(e){ if(e.key === "Enter"){ e.preventDefault(); pay(); } });
        act.appendChild(inp); act.appendChild(go);
      }
      act.appendChild(el("span","grow"));
      var del = el("button","btn ghost","Delete"); del.type = "button";
      del.setAttribute("aria-label","Delete debt " + d.name);
      del.addEventListener("click", function(){
        var gone = d; state.debts = state.debts.filter(function(x){return x.id !== d.id}); save(); render(); toast("Debt removed.", function(){ state.debts.push(gone); save(); render(); });
      });
      act.appendChild(del); li.appendChild(act);
      list.appendChild(li);
    });
  }
  function el(tag, cls, text){
    var e = document.createElement(tag);
    if(cls) e.className = cls;
    if(text != null) e.textContent = text;
    return e;
  }
  function pill(cat){
    var p = el("span","pill");
    var d = el("i"); d.style.background = "var(--c-" + cat + ")";
    p.appendChild(d); p.appendChild(document.createTextNode(cat));
    return p;
  }

  function render(){
    var month = $("month").value;
    var monthAll = state.items.filter(function(x){return x.date.slice(0,7) === month})
      .sort(function(a,b){return b.date.localeCompare(a.date) || b.id - a.id});
    shown = monthAll.filter(function(x){return x.type !== "in"});
    var moneyIn = monthAll.filter(function(x){return x.type === "in"}).reduce(function(t,x){return t + x.amount},0);
    var total = shown.reduce(function(s,x){return s + x.amount},0);

    var parts = month.split("-"), y = +parts[0], m = +parts[1];
    var dim = new Date(y, m, 0).getDate();
    var now = new Date(), days = (now.getFullYear() === y && now.getMonth() + 1 === m) ? now.getDate() : dim;

    $("total").textContent = fmt(total); lastTotal = total;
    $("count").textContent = shown.length;
    $("avg").textContent = fmt(total / days);

    var by = {};
    shown.forEach(function(x){by[x.cat] = (by[x.cat]||0) + x.amount});
    var cats = $("cats"); cats.innerHTML = "";
    var keys = Object.keys(by).sort(function(a,b){return by[b]-by[a]});
    if(!keys.length){ cats.appendChild(el("li","", "No spending recorded for this month.")).style.color = "var(--muted)"; }
    keys.forEach(function(c){
      var pct = by[c] / total * 100;
      var li = el("li");
      var row = el("div","row");
      var left = el("b"); left.appendChild(pill(c));
      row.appendChild(left);
      row.appendChild(el("span","", fmt(by[c]) + "  (" + pct.toFixed(0) + "%)"));
      var tr = el("div","track"), fill = el("i");
      fill.style.width = pct + "%"; fill.style.background = "var(--c-" + c + ")";
      tr.appendChild(fill);
      li.appendChild(row); li.appendChild(tr);
      cats.appendChild(li);
    });

    drawFlow(total, moneyIn);
    drawTrackers(month);
    drawDebts();
    drawCrypto();
    drawGoals();
    drawTips(by);
    drawForecast();
    drawRecurring(); drawBudgets(month, by); drawAlerts(month, total, by);
    drawDash(month, total, by, monthAll, moneyIn);
    drawDonut(by, keys, total);
    drawBars();

    var list = $("list"); list.innerHTML = "";
    var th = el("li","th");
    ["Date","Description","Category"].forEach(function(t){th.appendChild(el("span","",t))});
    th.appendChild(el("span","amt","Amount")); th.appendChild(el("span")); th.appendChild(el("span"));
    list.appendChild(th);

    var q = norm($("fQ").value.trim()), ft = $("fType").value, fc = $("fCat").value;
    var base = fScope === "all" ? state.items.slice().sort(function(a, b){ return b.date.localeCompare(a.date) || b.id - a.id; }) : monthAll;
    var rows = base.filter(function(x){
      return (!q || norm(x.desc + " " + x.cat).indexOf(q) > -1) && (!ft || (ft === "in") === (x.type === "in")) && (!fc || x.cat === fc);
    });
    var sIn = 0, sOut = 0; rows.forEach(function(x){ if(x.type === "in") sIn += x.amount; else sOut += x.amount; });
    $("fSum").textContent = rows.length + (rows.length === 1 ? " transaction" : " transactions") + " \u00b7 in " + fmt(sIn) + " \u00b7 out " + fmt(sOut) + (fScope === "all" ? " (all time)" : "");
    if(!base.length){
      list.appendChild(el("li","empty","No transactions yet. Add money in or an expense to get started."));
      return;
    }
    if(!rows.length){ list.appendChild(el("li","empty","No transactions match your filters.")); return; }
    rows.forEach(function(x){
      var li = el("li");
      li.appendChild(el("span","date", x.date));
      li.appendChild(el("span","desc", x.desc + (x.rec ? " \u21bb" : "")));
      li.appendChild(pill(x.cat));
      li.appendChild(el("span","amt" + (x.type === "in" ? " in" : ""), (x.type === "in" ? "+" : "") + fmt(x.amount)));
      var eb = el("button","del edit","\u270e"); eb.type = "button"; eb.setAttribute("aria-label","Edit " + x.desc);
      if(x.debt){ eb.disabled = true; eb.title = "Debt payments can't be edited here. Delete it and log the payment again from the debt."; }
      eb.addEventListener("click", function(){ startEdit(x); });
      li.appendChild(eb);
      var b = el("button","del","\u00d7"); b.type = "button";
      b.setAttribute("aria-label","Delete " + x.desc);
      b.addEventListener("click", function(){ deleteTx(x); });
      li.appendChild(b);
      var meta = el("span","meta"); meta.appendChild(el("span","", x.date)); meta.appendChild(pill(x.cat));
      li.appendChild(meta);
      list.appendChild(li);
    });
  }

  $("form").addEventListener("submit", function(ev){
    ev.preventDefault();
    var desc = $("desc").value.trim(), amount = parseFloat($("amount").value), date = $("date").value, err = $("err");
    if(!desc){ err.textContent = "Enter a description."; $("desc").focus(); return; }
    if(!(amount > 0)){ err.textContent = "Enter an amount greater than 0."; $("amount").focus(); return; }
    if(!date){ err.textContent = "Select a date."; $("date").focus(); return; }
    err.textContent = "";
    if(editId){
      var it = state.items.filter(function(i){ return i.id === editId; })[0];
      if(it){ it.desc = desc; it.amount = Math.round(amount*100)/100; it.cat = $("cat").value; it.date = date; it.type = txType; }
      cancelEdit(); toast("Transaction updated.");
    } else state.items.push({id:Date.now(), desc:desc, amount:Math.round(amount*100)/100, cat:$("cat").value, date:date, type:txType});
    save();
    $("month").value = date.slice(0,7);
    $("desc").value = ""; $("amount").value = "";
    $("desc").focus();
    render();
  });

  $("month").addEventListener("change", render);
  Array.prototype.forEach.call(document.querySelectorAll("[data-v]"), function(b){
    b.addEventListener("click", function(){
      view = b.getAttribute("data-v");
      Array.prototype.forEach.call(document.querySelectorAll("[data-v]"), function(o){
        o.setAttribute("aria-pressed", o === b ? "true" : "false");
      });
      drawBars();
    });
  });
  var rt; window.addEventListener("resize", function(){ clearTimeout(rt); rt = setTimeout(drawBars, 120); });

  /* ---------- countries, currencies and converter ---------- */
  // Units of currency per 1 USD. Indicative mid-market snapshot, 10-11 Oct 2026 (source: currencyrate.today).
  var RATES_DATE = "11 Oct 2026";
  var RATES = {USD:1,EUR:0.894,GBP:0.756,CHF:0.83,NOK:9.56,SEK:10,DKK:6.67,PLN:3.92,CZK:21.76,HUF:325.76,RON:4.77,TRY:49.22,RUB:85.16,UAH:44.92,ISK:122.15,BGN:1.75,RSD:104.68,BAM:1.75,ALL:81.76,
    CAD:1.43,MXN:18.41,BRL:4.99,ARS:1517.83,CLP:976.97,COP:3214.03,PEN:3.43,JMD:158.72,TTD:6.79,UYU:40.17,BOB:11.02,DOP:60.61,GTQ:7.64,CRC:456.3,PYG:5737.73,VES:875.7,XCD:2.7,BSD:1,PAB:1,BBD:2,
    AUD:1.43,NZD:1.78,AED:3.67,SAR:3.76,QAR:3.65,KWD:0.311,BHD:0.378,OMR:0.385,ILS:3.06,JOD:0.709,LBP:89557.81,KZT:454.44,UZS:11900.81,TND:2.98,YER:236.2,
    CNY:6.69,JPY:158.29,SGD:1.28,PKR:276.93,HKD:7.85,KRW:1340.44,THB:33.57,INR:96.78,BDT:123.31,LKR:330.89,NPR:154.69,MYR:4.09,IDR:17891.4,PHP:62.74,VND:25896.68,TWD:31.96,MMK:2099.95,KHR:4060.67,MNT:3599,
    NGN:1329.93,GHS:11.75,KES:129.7,ZAR:16.55,EGP:52.41,ETB:162.48,TZS:2640,UGX:4088.74,RWF:1474.11,XOF:586.25,XAF:586.25,MAD:9.82,ZMW:19.88,BWP:13.76,NAD:16.55,AOA:913,MZN:63.91,MWK:1734.11,GMD:73.5,LRD:171.13,SLE:20.97,DZD:134.72,LYD:6.43,MUR:47.46,GNF:8797.74,CDF:2314.63,BIF:2992.18,LSL:16.55,SZL:16.54,SCR:14.69,SOS:571.49,ZWG:26.69,MGA:4459.51};
  var ISO = {};
  ("Ghana:GH,Nigeria:NG,Kenya:KE,South Africa:ZA,Egypt:EG,Ethiopia:ET,Tanzania:TZ,Uganda:UG,Rwanda:RW,C\u00f4te d'Ivoire:CI,Senegal:SN,Cameroon:CM,Morocco:MA,Tunisia:TN,Algeria:DZ,Libya:LY,Zambia:ZM,Botswana:BW,Namibia:NA,Angola:AO,Mozambique:MZ,Malawi:MW,Zimbabwe:ZW,Sierra Leone:SL,Liberia:LR,Gambia:GM,Mauritius:MU,DR Congo:CD,Eswatini:SZ,Madagascar:MG,Somalia:SO,Guinea:GN,"
   + "United States:US,Canada:CA,Mexico:MX,Brazil:BR,Argentina:AR,Chile:CL,Colombia:CO,Peru:PE,Uruguay:UY,Bolivia:BO,Paraguay:PY,Venezuela:VE,Costa Rica:CR,Guatemala:GT,Panama:PA,Dominican Republic:DO,Jamaica:JM,Trinidad and Tobago:TT,Bahamas:BS,Barbados:BB,"
   + "Germany:DE,France:FR,Spain:ES,Italy:IT,Netherlands:NL,Ireland:IE,Portugal:PT,Belgium:BE,Austria:AT,Finland:FI,Greece:GR,United Kingdom:GB,Switzerland:CH,Norway:NO,Sweden:SE,Denmark:DK,Iceland:IS,Poland:PL,Czechia:CZ,Hungary:HU,Romania:RO,Bulgaria:BG,Serbia:RS,Turkey:TR,Russia:RU,Ukraine:UA,"
   + "India:IN,Pakistan:PK,Bangladesh:BD,Sri Lanka:LK,Nepal:NP,China:CN,Japan:JP,South Korea:KR,Singapore:SG,Malaysia:MY,Indonesia:ID,Philippines:PH,Thailand:TH,Vietnam:VN,Hong Kong:HK,Taiwan:TW,Myanmar:MM,Cambodia:KH,Kazakhstan:KZ,"
   + "United Arab Emirates:AE,Saudi Arabia:SA,Qatar:QA,Kuwait:KW,Bahrain:BH,Oman:OM,Israel:IL,Jordan:JO,Lebanon:LB,Australia:AU,New Zealand:NZ").split(",").forEach(function(p){ var k = p.split(":"); ISO[k[0]] = k[1]; });
  // Flag shown for each currency: shared currencies use a shared flag (euro = EU flag).
  var CURFLAG = {};
  ("USD:US,EUR:EU,GBP:GB,CHF:CH,NOK:NO,SEK:SE,DKK:DK,PLN:PL,CZK:CZ,HUF:HU,RON:RO,TRY:TR,RUB:RU,UAH:UA,ISK:IS,BGN:BG,RSD:RS,BAM:BA,ALL:AL,CAD:CA,MXN:MX,BRL:BR,ARS:AR,CLP:CL,COP:CO,PEN:PE,JMD:JM,TTD:TT,UYU:UY,BOB:BO,DOP:DO,GTQ:GT,CRC:CR,PYG:PY,VES:VE,XCD:AME,BSD:BS,PAB:PA,BBD:BB,"
   + "AUD:AU,NZD:NZ,AED:AE,SAR:SA,QAR:QA,KWD:KW,BHD:BH,OMR:OM,ILS:IL,JOD:JO,LBP:LB,KZT:KZ,UZS:UZ,TND:TN,YER:YE,CNY:CN,JPY:JP,SGD:SG,PKR:PK,HKD:HK,KRW:KR,THB:TH,INR:IN,BDT:BD,LKR:LK,NPR:NP,MYR:MY,IDR:ID,PHP:PH,VND:VN,TWD:TW,MMK:MM,KHR:KH,MNT:MN,"
   + "NGN:NG,GHS:GH,KES:KE,ZAR:ZA,EGP:EG,ETB:ET,TZS:TZ,UGX:UG,RWF:RW,XOF:AFR,XAF:AFR,MAD:MA,ZMW:ZM,BWP:BW,NAD:NA,AOA:AO,MZN:MZ,MWK:MW,GMD:GM,LRD:LR,SLE:SL,DZD:DZ,LYD:LY,MUR:MU,GNF:GN,CDF:CD,BIF:BI,LSL:LS,SZL:SZ,SCR:SC,SOS:SO,ZWG:ZW,MGA:MG").split(",").forEach(function(p){ var k = p.split(":"); CURFLAG[k[0]] = k[1]; });
  var SPECIAL = {AFR:"\ud83c\udf0d", AME:"\ud83c\udf0e"};
  function flag(iso){
    if(SPECIAL[iso]) return SPECIAL[iso];
    if(!iso || iso.length !== 2) return "";
    return String.fromCodePoint(127397 + iso.charCodeAt(0), 127397 + iso.charCodeAt(1));
  }
  var COUNTRIES = [
    ["Ghana","GHS","GH\u20b5"],["Nigeria","NGN","\u20a6"],["Kenya","KES","KSh"],["South Africa","ZAR","R"],["Egypt","EGP","E\u00a3"],["Ethiopia","ETB","Br"],["Tanzania","TZS","TSh"],["Uganda","UGX","USh"],["Rwanda","RWF","FRw"],
    ["C\u00f4te d'Ivoire","XOF","CFA"],["Senegal","XOF","CFA"],["Cameroon","XAF","FCFA"],["Morocco","MAD","MAD"],["Tunisia","TND","DT"],["Algeria","DZD","DA"],["Libya","LYD","LD"],["Zambia","ZMW","ZK"],["Botswana","BWP","P"],
    ["Namibia","NAD","N$"],["Angola","AOA","Kz"],["Mozambique","MZN","MT"],["Malawi","MWK","MK"],["Zimbabwe","ZWG","ZiG"],["Sierra Leone","SLE","Le"],["Liberia","LRD","L$"],["Gambia","GMD","D"],["Mauritius","MUR","Rs"],
    ["DR Congo","CDF","FC"],["Eswatini","SZL","E"],["Madagascar","MGA","Ar"],["Somalia","SOS","Sh"],["Guinea","GNF","FG"],
    ["United States","USD","$"],["Canada","CAD","CA$"],["Mexico","MXN","MX$"],["Brazil","BRL","R$"],["Argentina","ARS","AR$"],["Chile","CLP","CL$"],["Colombia","COP","CO$"],["Peru","PEN","S/"],["Uruguay","UYU","$U"],
    ["Bolivia","BOB","Bs"],["Paraguay","PYG","\u20b2"],["Venezuela","VES","Bs.S"],["Costa Rica","CRC","\u20a1"],["Guatemala","GTQ","Q"],["Panama","PAB","B/."],["Dominican Republic","DOP","RD$"],["Jamaica","JMD","J$"],
    ["Trinidad and Tobago","TTD","TT$"],["Bahamas","BSD","B$"],["Barbados","BBD","Bds$"],
    ["Germany","EUR","\u20ac"],["France","EUR","\u20ac"],["Spain","EUR","\u20ac"],["Italy","EUR","\u20ac"],["Netherlands","EUR","\u20ac"],["Ireland","EUR","\u20ac"],["Portugal","EUR","\u20ac"],["Belgium","EUR","\u20ac"],
    ["Austria","EUR","\u20ac"],["Finland","EUR","\u20ac"],["Greece","EUR","\u20ac"],["United Kingdom","GBP","\u00a3"],["Switzerland","CHF","CHF"],["Norway","NOK","kr"],["Sweden","SEK","kr"],["Denmark","DKK","kr"],
    ["Iceland","ISK","kr"],["Poland","PLN","z\u0142"],["Czechia","CZK","K\u010d"],["Hungary","HUF","Ft"],["Romania","RON","lei"],["Bulgaria","BGN","\u043b\u0432"],["Serbia","RSD","din"],["Turkey","TRY","\u20ba"],
    ["Russia","RUB","\u20bd"],["Ukraine","UAH","\u20b4"],
    ["India","INR","\u20b9"],["Pakistan","PKR","Rs"],["Bangladesh","BDT","\u09f3"],["Sri Lanka","LKR","Rs"],["Nepal","NPR","Rs"],["China","CNY","CN\u00a5"],["Japan","JPY","\u00a5"],["South Korea","KRW","\u20a9"],
    ["Singapore","SGD","S$"],["Malaysia","MYR","RM"],["Indonesia","IDR","Rp"],["Philippines","PHP","\u20b1"],["Thailand","THB","\u0e3f"],["Vietnam","VND","\u20ab"],["Hong Kong","HKD","HK$"],["Taiwan","TWD","NT$"],
    ["Myanmar","MMK","K"],["Cambodia","KHR","\u17db"],["Kazakhstan","KZT","\u20b8"],
    ["United Arab Emirates","AED","AED"],["Saudi Arabia","SAR","SAR"],["Qatar","QAR","QAR"],["Kuwait","KWD","KD"],["Bahrain","BHD","BD"],["Oman","OMR","OMR"],["Israel","ILS","\u20aa"],["Jordan","JOD","JD"],["Lebanon","LBP","L\u00a3"],
    ["Australia","AUD","A$"],["New Zealand","NZD","NZ$"]
  ].map(function(a){ return {n:a[0], c:a[1], s:a[2], i:ISO[a[0]]}; });
  var curNames = null;
  try{ curNames = new Intl.DisplayNames(["en"], {type:"currency"}); }catch(e){}
  function curName(c){ try{ return curNames ? curNames.of(c) : c; }catch(e){ return c; } }
  function findCountry(n){ for(var i=0;i<COUNTRIES.length;i++){ if(COUNTRIES[i].n === n) return COUNTRIES[i]; } return null; }
  function fillCountries(){
    var sorted = COUNTRIES.slice().sort(function(a,b){ return a.n.localeCompare(b.n); });
    ["aCountry","pCountry"].forEach(function(id){
      var sel = $(id); sel.innerHTML = "";
      var o = el("option","","Select your country"); o.value = ""; sel.appendChild(o);
      sorted.forEach(function(c){ var op = el("option","", flag(c.i) + " " + c.n + " (" + c.c + ")"); op.value = c.n; op.setAttribute("data-s", c.n + " " + c.c + " " + curName(c.c)); sel.appendChild(op); });
    });
  }
  function showCur(){
    var c = findCountry($("pCountry").value);
    var h = $("pCurHint"); h.innerHTML = "";
    if(!c){ h.textContent = "Pick your country and the app will use its currency symbol automatically."; return; }
    h.appendChild(el("span","fl", flag(CURFLAG[c.c]))); h.appendChild(document.createTextNode(" " + curName(c.c) + " (" + c.c + "), symbol " + c.s));
  }
  function nf(n){ return Number(n).toLocaleString("en-US",{minimumFractionDigits:2,maximumFractionDigits:2}); }
  function nr(r){ return Number(r.toPrecision(6)).toLocaleString("en-US",{maximumFractionDigits:8}); }
  function fillConv(){
    var codes = Object.keys(RATES).sort();
    ["cvFrom","cvTo"].forEach(function(id){
      var sel = $(id); sel.innerHTML = "";
      codes.forEach(function(c){ var o = el("option","", flag(CURFLAG[c]) + " " + c + " \u2014 " + curName(c)); o.value = c;
        o.setAttribute("data-s", c + " " + curName(c) + " " + COUNTRIES.filter(function(x){ return x.c === c; }).map(function(x){ return x.n; }).join(" "));
        sel.appendChild(o); });
    });
  }
  function runConv(){
    var out = $("cvOut"); out.innerHTML = "";
    var amt = parseFloat($("cvAmt").value), f = $("cvFrom").value, t = $("cvTo").value, own = parseFloat($("cvRate").value);
    if(!(amt >= 0)){ out.appendChild(el("div","cvsub","Enter an amount to convert.")); return; }
    var rate = own > 0 ? own : RATES[t] / RATES[f];
    out.appendChild(el("div","cvsub", nf(amt) + " " + f + " ="));
    out.appendChild(el("div","cvbig", nf(amt * rate) + " " + t));
    out.appendChild(el("div","cvsub", "1 " + f + " = " + nr(rate) + " " + t + "  \u00b7  1 " + t + " = " + nr(1 / rate) + " " + f));
    $("cvNote").textContent = own > 0 ? "Using your own rate."
      : "Indicative mid-market rates as of " + RATES_DATE + ". Banks and transfer services add a margin, so the rate you actually get will differ.";
  }
  function syncConv(){
    clearSearch("cvFrom"); clearSearch("cvTo");
    var code = RATES[state.code] ? state.code : "USD";
    $("cvFrom").value = code; $("cvTo").value = code === "USD" ? "EUR" : "USD"; $("cvRate").value = ""; runConv(); cxSync();
  }
  ["cvAmt","cvRate"].forEach(function(id){ $(id).addEventListener("input", runConv); });
  ["cvFrom","cvTo"].forEach(function(id){ $(id).addEventListener("change", runConv); });
  $("cvSwap").addEventListener("click", function(){
    clearSearch("cvFrom"); clearSearch("cvTo"); var f = $("cvFrom").value; $("cvFrom").value = $("cvTo").value; $("cvTo").value = f; $("cvRate").value = ""; runConv();
  });
  $("cvUse").addEventListener("click", function(){
    if(!RATES[state.code]){ $("cvNote").textContent = "Pick your country in your profile so the converter knows your currency."; return; }
    clearSearch("cvFrom"); clearSearch("cvTo"); $("cvFrom").value = state.code; if($("cvTo").value === state.code) $("cvTo").value = state.code === "USD" ? "EUR" : "USD";
    $("cvAmt").value = lastTotal.toFixed(2); $("cvRate").value = ""; runConv();
  });
  function applyCountry(){
    showCur();
    var c = findCountry($("pCountry").value); if(!c) return;
    var us = users(), u = us[myKey()]; if(!u) return;
    u.country = c.n; u.code = c.c; u.cur = c.s; putUsers(us);
    state.cur = c.s; state.code = c.c; paintHeader(u); render(); syncConv();
  }
  $("pCountry").addEventListener("change", applyCountry);

  function norm(t){ return String(t).normalize("NFD").replace(/[\u0300-\u036f]/g, "").toLowerCase(); }
  function clearSearch(id){ var x = $(id); if(x && x._reset) x._reset(); }
  function addSearch(id, what){
    var sel = $(id), all = [], inp = el("input","srch");
    Array.prototype.forEach.call(sel.options, function(o){
      all.push({v:o.value, t:o.text, s:norm(o.getAttribute("data-s") || o.text)});
    });
    inp.type = "search"; inp.placeholder = "Search " + what + "\u2026"; inp.autocomplete = "off";
    inp.setAttribute("aria-label", "Search " + what);
    sel.parentNode.insertBefore(inp, sel);
    function filter(){
      var q = norm(inp.value.trim()), cur = sel.value;
      var list = all;
      if(q){
        var rank = function(x){ return x.s.indexOf(q) === 0 ? 0 : (x.s.indexOf(" " + q) > -1 ? 1 : 2); };
        list = all.filter(function(x){ return x.v && x.s.indexOf(q) > -1; })
          .map(function(x, i){ return {x:x, i:i, r:rank(x)}; })
          .sort(function(a, b){ return a.r - b.r || a.i - b.i; })
          .map(function(m){ return m.x; });
      }
      sel.innerHTML = "";
      if(q && !list.length){ var n = el("option","","No matches"); n.value = ""; n.disabled = true; sel.appendChild(n); }
      list.forEach(function(x){ var o = el("option","",x.t); o.value = x.v; sel.appendChild(o); });
      if(q){ sel.size = Math.min(6, Math.max(2, list.length)); sel.selectedIndex = -1; }
      else { sel.removeAttribute("size"); sel.value = cur; }
      return list;
    }
    inp.addEventListener("input", filter);
    inp.addEventListener("keydown", function(e){
      if(e.key === "Enter"){
        e.preventDefault();
        var list = filter();
        if(inp.value.trim() && list.length){ sel.value = list[0].v; sel.dispatchEvent(new Event("change", {bubbles:true})); }
      } else if(e.key === "ArrowDown"){ e.preventDefault(); sel.focus(); }
      else if(e.key === "Escape"){ inp.value = ""; filter(); }
    });
    sel.addEventListener("change", function(){ if(inp.value){ inp.value = ""; filter(); } });
    sel._reset = function(){ inp.value = ""; filter(); };
  }

  /* ---------- dashboard widgets: left column, hero, statistic, feed, quick add ---------- */
  var CAT_EMOJI = {Food:"\ud83c\udf54", Transport:"\ud83d\ude8c", Bills:"\ud83d\udca1", Shopping:"\ud83d\udecd\ufe0f", Health:"\ud83d\udc8a", Other:"\u2728", Salary:"\ud83d\udcbc", Allowance:"\ud83c\udf92", Business:"\ud83c\udfea", Gift:"\ud83c\udf81", Debt:"\ud83c\udfe6"};
  var CHIP_COLORS = ["#7b3ff2", "#ff8a4c", "#4d7cff", "#7b3ff2"];
  function emo(c){ return CAT_EMOJI[c] || "\u2728"; }
  function goPane(name){ curPane = name; showView("dash"); }
  function drawMini(sv, pts, dim){
    sv.innerHTML = "";
    var W = 260, H = 140, pl = 44, pr = 14, pt = 16, pb = 16, iw = W - pl - pr, ih = H - pt - pb, top = niceMax(Math.max.apply(null, pts.concat([1])));
    var df = svg("defs", {}), g1 = svg("linearGradient", {id:"lcg", x1:0, y1:0, x2:0, y2:1});
    g1.appendChild(svg("stop", {offset:0, "stop-color":"#4d7cff", "stop-opacity":".5"})); g1.appendChild(svg("stop", {offset:1, "stop-color":"#4d7cff", "stop-opacity":"0"}));
    df.appendChild(g1); sv.appendChild(df);
    for(var i = 0; i < 4; i++){
      var yy = pt + ih * i / 3, ln = svg("line", {x1:pl, x2:W - pr, y1:yy, y2:yy}); ln.style.stroke = "var(--line)"; ln.style.opacity = ".7"; sv.appendChild(ln);
      var tx = svg("text", {x:pl - 8, y:yy + 3, "text-anchor":"end", "class":"ax"}); tx.textContent = compact(top * (1 - i / 3)); sv.appendChild(tx);
    }
    for(i = 0; i <= 6; i++){ var xx = pl + iw * i / 6, vl = svg("line", {x1:xx, x2:xx, y1:pt, y2:pt + ih}); vl.style.stroke = "var(--line)"; vl.style.opacity = ".45"; sv.appendChild(vl); }
    var P = pts.map(function(v, k){ return [pl + iw * (pts.length > 1 ? k / (dim - 1) : 0), pt + ih - v / top * ih]; });
    if(P.length < 2) P = [[pl, pt + ih], [pl + iw * 0.02, pt + ih]];
    var path = P.map(function(c, j){ return (j ? "L" : "M") + c[0].toFixed(1) + " " + c[1].toFixed(1); }).join(" ");
    sv.appendChild(svg("path", {d:path + " L" + P[P.length - 1][0].toFixed(1) + " " + (pt + ih) + " L" + P[0][0].toFixed(1) + " " + (pt + ih) + " Z", fill:"url(#lcg)"}));
    var ln2 = svg("path", {d:path, fill:"none", "stroke-width":2.5, "stroke-linecap":"round", "stroke-linejoin":"round"}); ln2.style.stroke = "#4d7cff"; sv.appendChild(ln2);
  }
  function drawDash(month, total, by, monthAll, moneyIn){
    var live = month === today().slice(0,7), now = new Date(), y = +month.slice(0,4), m = +month.slice(5,7), dim = new Date(y, m, 0).getDate(), last = live ? now.getDate() : dim, i;
    var daily = []; for(i = 0; i < dim; i++) daily.push(0);
    monthAll.forEach(function(x){ if(x.type !== "in") daily[+x.date.slice(8,10) - 1] += x.amount; });
    var cv = [], t = 0; for(i = 0; i < last; i++){ t += daily[i]; cv.push(t); }
    drawMini($("lcChart"), cv, dim); $("lcBig").textContent = fmt(total);
    var keys = Object.keys(by).sort(function(a, b){ return by[b] - by[a]; }).slice(0, 4), chips = $("lcChips"); chips.innerHTML = "";
    keys.forEach(function(c, k){
      var b = el("button","lchip", c + " " + Math.round(by[c] / total * 100) + "%"); b.type = "button"; b.style.borderColor = CHIP_COLORS[k];
      b.addEventListener("click", function(){ $("fCat").value = c; fScope = "month"; pressSeg("data-sc","month"); goPane("transactions"); render(); });
      chips.appendChild(b);
    });
    var all = state.items.slice().sort(function(a, b){ return b.date.localeCompare(a.date) || b.id - a.id; }), lt = all[0];
    $("llAv").textContent = lt ? emo(lt.cat) : "\u2728"; $("llName").textContent = lt ? lt.desc : "Nothing yet"; $("llArt").textContent = lt ? emo(lt.cat) : "\ud83d\udc8e";
    if(live){ var ms = new Date(y, m, 1) - now, dd = Math.floor(ms / 864e5), hh = Math.floor(ms % 864e5 / 36e5); $("lcCount").textContent = dd + "d : " + pad(hh) + "h"; } else $("lcCount").textContent = "Closed";
    $("lcN").textContent = monthAll.length + (monthAll.length === 1 ? " entry" : " entries");
    $("lcBal").textContent = fmt(moneyIn - total);
    var allIn = 0, allOut = 0; state.items.forEach(function(x){ if(x.type === "in") allIn += x.amount; else allOut += x.amount; });
    $("tbBal").textContent = fmt(allIn - allOut);
    var cats = $("lcCats"); cats.innerHTML = "";
    keys.forEach(function(c){
      var bud = state.budgets[c], pct = bud ? by[c] / bud * 100 : null, card = el("div","citem");
      card.appendChild(el("small","", c)); card.appendChild(el("div","ca fl", emo(c))); card.appendChild(el("small","", bud ? "of " + fmt(bud) : "No budget")); card.appendChild(el("b","", fmt(by[c])));
      var dot = el("i","cd"); dot.style.background = pct === null ? "var(--c-" + c + ", var(--accent))" : (pct >= 100 ? "var(--bad)" : (pct >= 80 ? "#eab308" : "var(--good)")); card.appendChild(dot); cats.appendChild(card);
    });
    $("lcDot").hidden = $("alertCard").hidden;
    // hero
    var F = live ? calcForecast() : null, proj = F ? F.proj : total, inc = moneyIn > 0 ? moneyIn : state.budget, saved = inc > 0 ? inc - total : null;
    $("coinSym").textContent = state.cur ? String(state.cur).slice(0, 3) : "$";
    $("hSpent").textContent = fmt(total); $("hProj").textContent = fmt(proj); $("hProjL").textContent = live ? "Projected" : "Final";
    $("hBudget").textContent = "Budget " + (state.budget > 0 ? fmt(state.budget) : "not set");
    $("hSaved").textContent = "Saved "; $("hSaved").appendChild(el("b","", saved === null ? "\u2014" : fmt(saved)));
    var gT = 0, gS = 0; state.goals.forEach(function(g){ gT += g.target; gS += Math.min(g.saved, g.target); });
    var rp = (state.goal > 0 && saved !== null) ? Math.max(0, Math.min(100, saved / state.goal * 100)) : (gT > 0 ? gS / gT * 100 : 0), C = 2 * Math.PI * 52, rf = $("ringFg");
    rf.style.strokeDasharray = (C * rp / 100) + " " + C; rf.style.stroke = progColor(rp);
    // feature cards
    var best = null; state.goals.forEach(function(g){ var q = g.saved / g.target; if(g.saved < g.target && (!best || q > best.q)) best = {g:g, q:q}; });
    $("fcA").textContent = best ? best.g.name + " is at " + Math.floor(best.q * 100) + "%. " + fmt(best.g.target - best.g.saved) + " to go, keep it up!" : (state.goals.length ? "All your goals are reached. Time to set a new one!" : "Set a goal like a car or a phone and watch the bar fill up.");
    $("fcB").textContent = TIP_ALL[dayIdx() % TIP_ALL.length].t;
    var na = $("alerts").children.length; $("fcC").textContent = na ? na + (na === 1 ? " thing needs" : " things need") + " your attention. Tap to review." : "Set a category budget and stay in control of your spending.";
    $("fcCBtn").setAttribute("data-go", na ? "overview" : "spending");
    // statistic
    $("stN").textContent = monthAll.length + " entries"; $("stT").textContent = fmt(total) + " out"; $("stG").textContent = state.goals.length + (state.goals.length === 1 ? " goal" : " goals");
    var sl = $("statList"); sl.innerHTML = "";
    if(!monthAll.length) sl.appendChild(el("p","muted","No transactions this month yet. Use quick add on the right or the Add button."));
    monthAll.slice(0, 5).forEach(function(x){
      var r = el("div","srow"); r.appendChild(el("span","sq fl", emo(x.cat)));
      var nm = el("div"); nm.appendChild(el("small","", x.cat + " \u00b7 " + x.date)); nm.appendChild(el("b","", (x.type === "in" ? "+" : "") + fmt(x.amount))); r.appendChild(nm);
      r.appendChild(el("span","sa fl", emo(x.cat)));
      r.appendChild(el("span","spill" + (x.type === "in" ? " in" : (x.rec ? " rec" : "")), x.type === "in" ? "Money in" : (x.rec ? "Recurring" : (x.debt ? "Debt" : "Money out"))));
      r.appendChild(el("span","sd", x.desc)); sl.appendChild(r);
    });
    // feed on the right
    var feed = $("feed"); feed.innerHTML = ""; $("rcCount").textContent = state.items.length;
    var cm = monthStats(month);
    var coach = el("div","msg"); coach.appendChild(el("span","sq fl","\ud83d\udca1"));
    var cb = el("div"), ch = el("div","mh"); ch.appendChild(el("b","","Coach")); ch.appendChild(el("i","","[tip]")); ch.appendChild(el("time","","today")); cb.appendChild(ch); cb.appendChild(el("p","", TIP_ALL[dayIdx() % TIP_ALL.length].t)); coach.appendChild(cb); feed.appendChild(coach);
    all.slice(0, 14).forEach(function(x){
      var mg = el("div","msg"); mg.appendChild(el("span","sq fl", emo(x.cat)));
      var bd = el("div"), hd = el("div","mh"); hd.appendChild(el("b","", x.cat)); hd.appendChild(el("i","", "[" + (cm.cat[x.cat] ? monthAll.filter(function(q){ return q.cat === x.cat; }).length : 1) + "]")); hd.appendChild(el("time","", x.date === today() ? "today" : x.date.slice(5)));
      bd.appendChild(hd); var p = el("p"); p.appendChild(document.createTextNode(x.desc + " ")); p.appendChild(el("em", x.type === "in" ? "in" : "", (x.type === "in" ? "+" : "-") + fmt(x.amount))); bd.appendChild(p); mg.appendChild(bd); feed.appendChild(mg);
    });
  }
  Array.prototype.forEach.call(document.querySelectorAll("[data-go]"), function(b){
    b.addEventListener("click", function(){ goPane(b.getAttribute("data-go")); if(b.getAttribute("data-go") === "overview" && !$("alertCard").hidden){ try{ $("alertCard").scrollIntoView({behavior:"smooth", block:"start"}); }catch(e){} } });
  });
  function goAdd(){ goPane("transactions"); $("desc").focus(); }
  ["tbAdd","lcAdd","fabAdd"].forEach(function(id){ $(id).addEventListener("click", goAdd); });
  $("fabConv").addEventListener("click", function(){ goPane("converter"); });
  $("stAll").addEventListener("click", function(){ goPane("transactions"); });
  $("lcBell").addEventListener("click", function(){ goPane("overview"); try{ if(!$("alertCard").hidden) $("alertCard").scrollIntoView({behavior:"smooth", block:"start"}); }catch(e){} });
  var qaType = "out";
  var QA_KEYS = {Food:/lunch|dinner|breakfast|food|grocer|snack|meal|rice|restaurant|coffee|drink|chop/i, Transport:/taxi|bus|fare|uber|bolt|fuel|petrol|transport|trotro|ride/i, Bills:/rent|electric|water|airtime|data|wifi|internet|bill|subscription|utility/i, Shopping:/shop|cloth|shoe|market|mall|gadget/i, Health:/pharm|clinic|doctor|medic|hospital|gym|health/i};
  function fillQa(){
    var sel = $("qaCat"); sel.innerHTML = ""; var a = el("option","","Auto category"); a.value = ""; sel.appendChild(a);
    CATS[qaType].forEach(function(c){ var o = el("option","",c); o.value = c; sel.appendChild(o); });
    $("qaType").textContent = qaType === "in" ? "+" : "\u2212"; $("qaType").setAttribute("aria-label", qaType === "in" ? "Money in" : "Money out");
    $("qaText").placeholder = qaType === "in" ? "Quick add money in, e.g. salary 3000" : "Quick add, e.g. lunch 25";
  }
  $("qaType").addEventListener("click", function(){ qaType = qaType === "in" ? "out" : "in"; fillQa(); });
  function quickAdd(){
    var text = $("qaText").value.trim(), mt = text.match(/(\d[\d,]*\.?\d*)/);
    if(!mt){ toast("Include an amount, for example: lunch 25"); $("qaText").focus(); return; }
    var amt = parseFloat(mt[1].replace(/,/g, ""));
    if(!(amt > 0)){ toast("The amount must be greater than 0."); return; }
    var desc = text.replace(mt[0], " ").replace(/\s+/g, " ").trim().slice(0, 80), cat = $("qaCat").value;
    if(!cat){
      cat = qaType === "in" ? (/salary|pay|wage/i.test(desc) ? "Salary" : (/gift/i.test(desc) ? "Gift" : "Other")) : "Other";
      if(qaType === "out") Object.keys(QA_KEYS).forEach(function(k){ if(cat === "Other" && QA_KEYS[k].test(desc)) cat = k; });
    }
    if(!desc) desc = cat;
    state.items.push({id:nid(), desc:desc.charAt(0).toUpperCase() + desc.slice(1), amount:r2(amt), cat:cat, date:today(), type:qaType});
    save(); $("qaText").value = ""; $("month").value = today().slice(0,7); render();
    toast("Added " + (qaType === "in" ? "money in" : "an expense") + ": " + desc + " " + fmt(amt) + " (" + cat + ").");
  }
  $("qaSend").addEventListener("click", quickAdd);
  $("qaText").addEventListener("keydown", function(e){ if(e.key === "Enter"){ e.preventDefault(); quickAdd(); } });

  /* ---------- toast, undo, edit, filters, month arrows ---------- */
  var toastTimer, undoFn = null, editId = null, fScope = "month", idSeed = Date.now();
  function nid(){ return ++idSeed; }
  function toast(msg, undo){
    $("toastMsg").textContent = msg; $("toastTime").textContent = new Date().toLocaleTimeString([], {hour:"2-digit", minute:"2-digit"}); undoFn = undo || null; $("toastUndo").hidden = !undo; $("toast").hidden = false;
    clearTimeout(toastTimer); toastTimer = setTimeout(function(){ $("toast").hidden = true; undoFn = null; }, undo ? 7000 : 3500);
  }
  $("toastUndo").addEventListener("click", function(){ var f = undoFn; undoFn = null; $("toast").hidden = true; if(f) f(); });
  function deleteTx(x){
    var debt = x.debt ? state.debts.filter(function(d){ return d.id === x.debt; })[0] : null;
    state.items = state.items.filter(function(i){ return i.id !== x.id; });
    if(debt) debt.paid = Math.max(0, r2(debt.paid - x.amount));
    if(editId === x.id) cancelEdit();
    save(); render();
    toast("Transaction deleted.", function(){ state.items.push(x); if(debt) debt.paid = r2(debt.paid + x.amount); save(); render(); });
  }
  function startEdit(x){
    editId = x.id; txType = x.type === "in" ? "in" : "out"; pressSeg("data-t", txType); fillCats();
    var sel = $("cat"); sel.value = x.cat;
    if(sel.value !== x.cat){ var o = el("option","",x.cat); o.value = x.cat; sel.appendChild(o); sel.value = x.cat; }
    $("desc").value = x.desc; $("amount").value = x.amount; $("date").value = x.date;
    $("txTitle").textContent = "Edit transaction"; $("txGo").textContent = "Save changes"; $("txCancel").hidden = false; setMsg("err","");
    try{ $("form").scrollIntoView({behavior:"smooth", block:"center"}); }catch(e){}
    $("desc").focus();
  }
  function cancelEdit(){
    editId = null; $("txTitle").textContent = "New transaction"; $("txCancel").hidden = true; fillCats();
    $("desc").value = ""; $("amount").value = ""; $("date").value = today(); setMsg("err","");
  }
  $("txCancel").addEventListener("click", cancelEdit);
  function fillFilterCats(){
    var all = [], seen = {}; CATS.out.concat(CATS["in"], ["Debt"]).forEach(function(c){ if(!seen[c]){ seen[c] = 1; all.push(c); } });
    var sel = $("fCat"); sel.innerHTML = ""; var o0 = el("option","","All categories"); o0.value = ""; sel.appendChild(o0);
    all.forEach(function(c){ var o = el("option","",c); o.value = c; sel.appendChild(o); });
  }
  $("fQ").addEventListener("input", render); $("fType").addEventListener("change", render); $("fCat").addEventListener("change", render);
  Array.prototype.forEach.call(document.querySelectorAll("[data-sc]"), function(b){
    b.addEventListener("click", function(){ fScope = b.getAttribute("data-sc"); pressSeg("data-sc", fScope); render(); });
  });
  function shiftMonth(n){
    var p = $("month").value.split("-"), d = new Date(+p[0], +p[1] - 1 + n, 1);
    $("month").value = d.getFullYear() + "-" + pad(d.getMonth() + 1); render();
  }
  $("mPrev").addEventListener("click", function(){ shiftMonth(-1); });
  $("mNext").addEventListener("click", function(){ shiftMonth(1); });

  /* ---------- recurring transactions ---------- */
  function fillRecCats(){
    var sel = $("rCat"); sel.innerHTML = "";
    CATS[$("rType").value === "in" ? "in" : "out"].forEach(function(c){ var o = el("option","",c); o.value = c; sel.appendChild(o); });
  }
  $("rType").addEventListener("change", fillRecCats);
  function advanceDate(r, ds){
    var d = new Date(ds + "T00:00:00Z"), Y = d.getUTCFullYear(), M = d.getUTCMonth(), dom = r.dom || d.getUTCDate();
    if(r.freq === "weekly") d.setUTCDate(d.getUTCDate() + 7);
    else if(r.freq === "biweekly") d.setUTCDate(d.getUTCDate() + 14);
    else if(r.freq === "yearly") d = new Date(Date.UTC(Y + 1, M, Math.min(dom, new Date(Date.UTC(Y + 1, M + 1, 0)).getUTCDate())));
    else d = new Date(Date.UTC(Y, M + 1, Math.min(dom, new Date(Date.UTC(Y, M + 2, 0)).getUTCDate())));
    return d.toISOString().slice(0,10);
  }
  function runRecurring(quiet){
    var t = today(), n = 0, guard = 0;
    state.recurring.forEach(function(r){
      if(!r.active) return;
      while(r.next <= t && (!r.end || r.next <= r.end) && guard++ < 600){
        state.items.push({id:nid(), desc:r.desc, amount:r.amt, cat:r.cat, date:r.next, type:r.type, rec:r.id}); n++;
        r.next = advanceDate(r, r.next);
      }
      if(r.end && r.next > r.end) r.active = false;
    });
    if(n){ save(); if(!quiet) toast("Added " + n + " recurring transaction" + (n === 1 ? "" : "s") + "."); }
    return n;
  }
  document.addEventListener("visibilitychange", function(){ if(!document.hidden && uid && runRecurring(true)){ render(); toast("Recurring transactions were added."); } });
  var FREQ = {weekly:"Every week", biweekly:"Every 2 weeks", monthly:"Every month", yearly:"Every year"};
  function drawRecurring(){
    var list = $("rList"); list.innerHTML = "";
    if(!state.recurring.length){ list.appendChild(el("li","empty","No recurring transactions yet. Add rent, salary or a subscription above.")); return; }
    state.recurring.slice().sort(function(a, b){ return (b.active ? 1 : 0) - (a.active ? 1 : 0) || a.next.localeCompare(b.next); }).forEach(function(r){
      var li = el("li"), top = el("div","dtop"), nm = el("span","dname", r.desc);
      nm.appendChild(el("span","badge", FREQ[r.freq] || r.freq)); nm.appendChild(el("span","badge", r.cat));
      top.appendChild(nm); top.appendChild(el("span","amt" + (r.type === "in" ? " in" : ""), (r.type === "in" ? "+" : "") + fmt(r.amt))); li.appendChild(top);
      li.appendChild(el("p","gmeta", r.active ? "Next: " + r.next + (r.end ? " \u00b7 ends " + r.end : "") : (r.end && r.next > r.end ? "Finished on " + r.end : "Paused")));
      var act = el("div","dact"); act.appendChild(el("span","grow"));
      if(!(r.end && r.next > r.end)){
        var tg = el("button","btn ghost", r.active ? "Pause" : "Resume"); tg.type = "button";
        tg.addEventListener("click", function(){ r.active = !r.active; if(r.active) runRecurring(); save(); render(); });
        act.appendChild(tg);
      }
      var del = el("button","btn ghost","Remove"); del.type = "button"; del.setAttribute("aria-label","Remove " + r.desc);
      del.addEventListener("click", function(){ state.recurring = state.recurring.filter(function(x){ return x.id !== r.id; }); save(); render(); toast("Recurring transaction removed. Past entries are kept.", function(){ state.recurring.push(r); save(); render(); }); });
      act.appendChild(del); li.appendChild(act); list.appendChild(li);
    });
  }
  $("rForm").addEventListener("submit", function(ev){
    ev.preventDefault(); setMsg("rErr","");
    var desc = $("rDesc").value.trim(), amt = parseFloat($("rAmt").value), start = $("rStart").value, end = $("rEnd").value;
    if(!desc){ setMsg("rErr","Enter a description."); $("rDesc").focus(); return; }
    if(!(amt > 0)){ setMsg("rErr","Enter an amount greater than 0."); $("rAmt").focus(); return; }
    if(!start){ setMsg("rErr","Pick the first date."); $("rStart").focus(); return; }
    if(end && end < start){ setMsg("rErr","The end date must be after the first date."); return; }
    state.recurring.push({id:nid(), desc:desc, amt:r2(amt), type:$("rType").value, cat:$("rCat").value, freq:$("rFreq").value, start:start, next:start, end:end || "", dom:+start.slice(8,10), active:true});
    var n = runRecurring(); save(); $("rDesc").value = ""; $("rAmt").value = ""; $("rEnd").value = ""; render();
    toast(n ? "Added. " + n + " past occurrence" + (n === 1 ? " was" : "s were") + " added to your transactions." : "Recurring transaction added.");
  });

  /* ---------- category budgets and alerts ---------- */
  function fillBudgetCats(){
    var sel = $("bCat"); sel.innerHTML = "";
    CATS.out.concat(["Debt"]).forEach(function(c){ var o = el("option","",c); o.value = c; sel.appendChild(o); });
  }
  $("bForm").addEventListener("submit", function(ev){
    ev.preventDefault(); setMsg("bErr","");
    var lim = parseFloat($("bAmt").value);
    if(!(lim > 0)){ setMsg("bErr","Enter a limit greater than 0."); $("bAmt").focus(); return; }
    state.budgets[$("bCat").value] = r2(lim); save(); $("bAmt").value = ""; render();
  });
  function drawBudgets(month, by){
    var list = $("bList"); list.innerHTML = "";
    var cats = Object.keys(state.budgets).sort();
    if(!cats.length){ list.appendChild(el("li","empty","No budgets yet. Pick a category and set a monthly limit.")); return; }
    cats.forEach(function(c){
      var lim = state.budgets[c], sp = by[c] || 0, pct = lim > 0 ? sp / lim * 100 : 0;
      var li = el("li"), top = el("div","dtop"), nm = el("span","dname", c);
      nm.appendChild(el("span","badge", Math.round(pct) + "%"));
      top.appendChild(nm); top.appendChild(el("span","amt", fmt(sp) + " of " + fmt(lim))); li.appendChild(top);
      var tr = el("div","track"), f = el("i"); tr.style.marginTop = "10px"; setBar(f, Math.min(100, pct), true); tr.appendChild(f); li.appendChild(tr);
      li.appendChild(el("p","gmeta " + (pct >= 100 ? "bad" : (pct >= 80 ? "bad" : "good")), pct >= 100 ? "Over budget by " + fmt(sp - lim) : fmt(lim - sp) + " left this month"));
      var act = el("div","dact"); act.appendChild(el("span","grow"));
      var del = el("button","btn ghost","Remove"); del.type = "button"; del.setAttribute("aria-label","Remove " + c + " budget");
      del.addEventListener("click", function(){ var was = state.budgets[c]; delete state.budgets[c]; save(); render(); toast(c + " budget removed.", function(){ state.budgets[c] = was; save(); render(); }); });
      act.appendChild(del); li.appendChild(act); list.appendChild(li);
    });
  }
  function drawAlerts(month, spent, by){
    var out = [], live = month === today().slice(0,7);
    state.debts.forEach(function(d){
      var left = Math.max(0, d.total - d.paid), di = left > 0.004 ? dueInfo(d) : null; if(!di) return;
      if(d.kind === "owed"){ if(di.bad) out.push({c:"warn", t:d.name + " was expected to repay " + fmt(left) + " (" + di.t.toLowerCase() + ")."}); }
      else if(di.bad) out.push({c:"bad", t:"Debt overdue: " + d.name + ", " + fmt(left) + " left (" + di.t.toLowerCase() + ")."});
      else if(di.days <= 7) out.push({c:"warn", t:d.name + ": " + fmt(left) + " " + di.t.toLowerCase() + "."});
    });
    if(live){
      Object.keys(state.budgets).forEach(function(c){
        var lim = state.budgets[c], sp = by[c] || 0, pct = sp / lim * 100;
        if(pct >= 100) out.push({c:"bad", t:c + " budget exceeded: " + fmt(sp) + " of " + fmt(lim) + "."});
        else if(pct >= 80) out.push({c:"warn", t:c + " budget is at " + Math.round(pct) + "% (" + fmt(lim - sp) + " left)."});
      });
      if(state.budget > 0){
        var bp = spent / state.budget * 100;
        if(bp >= 100) out.push({c:"bad", t:"You've spent more than your monthly budget (" + fmt(spent) + " of " + fmt(state.budget) + ")."});
        else if(bp >= 80) out.push({c:"warn", t:"You've used " + Math.round(bp) + "% of your monthly budget."});
      }
    }
    state.recurring.forEach(function(r){
      if(!r.active) return;
      var days = Math.round((new Date(r.next + "T00:00:00") - new Date(today() + "T00:00:00")) / 86400000);
      if(days >= 0 && days <= 3) out.push({c:"info", t:r.desc + " (" + fmt(r.amt) + ") will be added " + (days === 0 ? "today" : "on " + r.next) + "."});
    });
    state.goals.forEach(function(g){
      if(g.date && g.saved < g.target && g.date < today()) out.push({c:"warn", t:"The target date for " + g.name + " has passed and it's at " + Math.round(g.saved / g.target * 100) + "%."});
    });
    var ul = $("alerts"); ul.innerHTML = "";
    out.forEach(function(a){ ul.appendChild(el("li", a.c, a.t)); });
    $("alertCard").hidden = !out.length;
  }

  /* ---------- your data: export, restore, clear ---------- */
  var dlCap = null;
  try{ if(window.claude && window.claude.use) window.claude.use("downloads").then(function(f){ dlCap = f; }, function(){}); }catch(e){}
  function saveFile(name, text, label){
    setMsg("dmErr",""); setMsg("dmOk","");
    if(!dlCap){ var ta = $("imText"); ta.value = text; ta.focus(); ta.select(); setMsg("dmOk","Downloads aren't available here, so the " + label + " is in the box below. Copy it and save it as a file."); return; }
    dlCap.save({filename:name, data:text}).then(function(){ setMsg("dmOk", label + " saved."); }, function(e){ if(!e || e.code !== "declined") setMsg("dmErr","Couldn't save the file (" + ((e && e.code) || "error") + ")."); });
  }
  function csvCell(v){ v = String(v); if(/^[=+\-@\t\r]/.test(v)) v = "'" + v; return '"' + v.replace(/"/g, '""') + '"'; }
  $("exCsv").addEventListener("click", function(){
    if(!state.items.length){ setMsg("dmErr","There are no transactions to export yet."); return; }
    var rows = ["Date,Type,Category,Description,Amount," + csvCell(state.code || "Currency")];
    state.items.slice().sort(function(a, b){ return a.date.localeCompare(b.date) || a.id - b.id; }).forEach(function(x){
      rows.push([x.date, x.type === "in" ? "Money in" : "Money out", csvCell(x.cat), csvCell(x.desc), x.amount.toFixed(2), ""].join(","));
    });
    saveFile("expenses-" + today() + ".csv", rows.join("\r\n"), "CSV");
  });
  function backupObject(){
    var u = users()[myKey()] || {};
    return {app:"expense-tracker", version:1, exported:new Date().toISOString(),
      profile:{country:u.country || "", budget:state.budget, goal:state.goal},
      data:{items:state.items, debts:state.debts, holdings:state.holdings, goals:state.goals, tipsDone:state.tipsDone, recurring:state.recurring, budgets:state.budgets}};
  }
  $("exJson").addEventListener("click", function(){ saveFile("expense-tracker-backup-" + today() + ".json", JSON.stringify(backupObject(), null, 1), "backup"); });
  $("imFile").addEventListener("change", function(){
    var f = this.files && this.files[0]; if(!f) return;
    var rd = new FileReader();
    rd.onload = function(){ $("imText").value = String(rd.result || ""); setMsg("dmErr",""); setMsg("dmOk","File loaded. Press Restore from backup."); };
    rd.onerror = function(){ setMsg("dmErr","Couldn't read that file."); };
    rd.readAsText(f);
  });
  function parseBackup(text){
    var o; try{ o = JSON.parse(text); }catch(e){ throw "That isn't a valid backup."; }
    if(!o || o.app !== "expense-tracker" || !o.data || typeof o.data !== "object") throw "That doesn't look like an Expense Tracker backup.";
    var d = o.data, okD = /^\d{4}-\d{2}-\d{2}$/, A = function(v){ return Array.isArray(v) ? v : []; }, S = function(v, n){ return String(v == null ? "" : v).slice(0, n); };
    var items = A(d.items).filter(function(x){ return x && typeof x.desc === "string" && +x.amount > 0 && okD.test(x.date) && typeof x.cat === "string"; }).map(function(x){
      var y = {id:+x.id || nid(), desc:S(x.desc, 80), amount:r2(+x.amount), cat:S(x.cat, 30), date:x.date, type:x.type === "in" ? "in" : "out"}; if(x.debt) y.debt = +x.debt; if(x.rec) y.rec = +x.rec; return y; });
    var debts = A(d.debts).filter(function(x){ return x && typeof x.name === "string" && +x.total > 0 && isFinite(+x.paid); }).map(function(x){
      return {id:+x.id || nid(), name:S(x.name, 60), kind:x.kind === "owed" ? "owed" : "owe", total:r2(+x.total), paid:r2(+x.paid), due:okD.test(x.due) ? x.due : ""}; });
    var goals = A(d.goals).filter(function(x){ return x && typeof x.name === "string" && +x.target > 0 && +x.saved >= 0; }).map(function(x){
      return {id:+x.id || nid(), name:S(x.name, 50), icon:S(x.icon, 8) || "\ud83c\udfaf", target:r2(+x.target), saved:r2(+x.saved), date:okD.test(x.date) ? x.date : ""}; });
    var holdings = A(d.holdings).filter(function(x){ return x && CRYPTO[x.sym] && +x.amt > 0; }).map(function(x){ return {id:+x.id || nid(), sym:x.sym, amt:+x.amt}; });
    var recurring = A(d.recurring).filter(function(x){ return x && typeof x.desc === "string" && +x.amt > 0 && FREQ[x.freq] && okD.test(x.next); }).map(function(x){
      return {id:+x.id || nid(), desc:S(x.desc, 60), amt:r2(+x.amt), type:x.type === "in" ? "in" : "out", cat:S(x.cat, 30), freq:x.freq, start:okD.test(x.start) ? x.start : x.next, next:x.next, end:okD.test(x.end) ? x.end : "", dom:+x.dom || +x.next.slice(8,10), active:!!x.active}; });
    var budgets = {}; if(d.budgets && typeof d.budgets === "object") Object.keys(d.budgets).forEach(function(c){ if(+d.budgets[c] > 0) budgets[S(c, 30)] = r2(+d.budgets[c]); });
    return {items:items, debts:debts, goals:goals, holdings:holdings, recurring:recurring, budgets:budgets, tipsDone:A(d.tipsDone).filter(function(x){ return okD.test(x); }), profile:o.profile || {}};
  }
  var restoreArmed = false, restoreTimer;
  $("imGo").addEventListener("click", function(){
    setMsg("dmErr",""); setMsg("dmOk","");
    var b; try{ b = parseBackup($("imText").value.trim()); }catch(e){ setMsg("dmErr", String(e)); return; }
    var btn = this;
    if(!restoreArmed){
      restoreArmed = true; btn.textContent = "Click again to replace my data";
      setMsg("dmOk","Found " + b.items.length + " transactions, " + b.debts.length + " debts, " + b.goals.length + " goals, " + b.recurring.length + " recurring. This replaces what's here now.");
      restoreTimer = setTimeout(function(){ restoreArmed = false; btn.textContent = "Restore from backup"; }, 6000); return;
    }
    clearTimeout(restoreTimer); restoreArmed = false; btn.textContent = "Restore from backup";
    state.items = b.items; state.debts = b.debts; state.goals = b.goals; state.holdings = b.holdings; state.recurring = b.recurring; state.budgets = b.budgets; state.tipsDone = b.tipsDone;
    var us = users(), u = us[myKey()];
    if(u){
      if(+b.profile.budget >= 0) u.budget = state.budget = +b.profile.budget || 0;
      if(+b.profile.goal >= 0) u.goal = state.goal = +b.profile.goal || 0;
      var c = findCountry(b.profile.country); if(c){ u.country = c.n; u.code = c.c; u.cur = c.s; state.cur = c.s; state.code = c.c; }
      putUsers(us); paintHeader(u);
    }
    save(); $("imText").value = ""; render(); syncConv(); setMsg("dmOk","Backup restored."); toast("Backup restored.");
  });
  var clrArmed = false, clrTimer;
  $("clrData").addEventListener("click", function(){
    var btn = this;
    if(!clrArmed){ clrArmed = true; btn.textContent = "Click again to erase everything"; clrTimer = setTimeout(function(){ clrArmed = false; btn.textContent = "Clear all my data"; }, 5000); return; }
    clearTimeout(clrTimer); clrArmed = false; btn.textContent = "Clear all my data";
    state.items = []; state.debts = []; state.goals = []; state.holdings = []; state.recurring = []; state.budgets = {}; state.tipsDone = [];
    save(); render(); setMsg("dmOk","All your data was cleared. Your account and settings are unchanged.");
  });

  /* ---------- forecast (local maths) + AI insights ---------- */
  function monthKey(off){ var d = new Date(+today().slice(0,4), +today().slice(5,7) - 1 + off, 1); return d.getFullYear() + "-" + pad(d.getMonth() + 1); }
  function addMonths(n){ return new Date(+today().slice(0,4), +today().slice(5,7) - 1 + n, 1).toLocaleString("en-US",{month:"short", year:"numeric"}); }
  function monthStats(key, cut){
    var r = {out:0, inn:0, cat:{}, n:0};
    state.items.forEach(function(x){
      if(x.date.slice(0,7) !== key || (cut && +x.date.slice(8,10) > cut)) return;
      r.n++;
      if(x.type === "in") r.inn += x.amount; else { r.out += x.amount; r.cat[x.cat] = (r.cat[x.cat] || 0) + x.amount; }
    });
    return r;
  }
  function mean(a){ return a.length ? a.reduce(function(t, v){ return t + v; }, 0) / a.length : 0; }
  function calcForecast(){
    var tk = today().slice(0,7), y = +tk.slice(0,4), m = +tk.slice(5,7), day = +today().slice(8,10);
    var dim = new Date(y, m, 0).getDate(), rem = dim - day, cur = monthStats(tk), prev = [], i;
    for(i = 1; i <= 6; i++){ var k = monthKey(-i), st = monthStats(k); st.key = k; if(st.n) prev.push(st); }
    var byDay = {}, first = null;
    state.items.forEach(function(x){
      if(x.type !== "in") byDay[x.date] = (byDay[x.date] || 0) + x.amount;
      if(!first || x.date < first) first = x.date;
    });
    var series = [], t = new Date(today() + "T00:00:00Z"), lim = new Date(t); lim.setUTCDate(lim.getUTCDate() - 59);
    var start = first ? new Date(first + "T00:00:00Z") : t; if(start < lim) start = lim;
    for(var d = new Date(start); d <= t; d.setUTCDate(d.getUTCDate() + 1)) series.push(byDay[d.toISOString().slice(0,10)] || 0);
    var n = series.length, mu = mean(series);
    var sd = n > 1 ? Math.sqrt(series.reduce(function(a, v){ return a + (v - mu) * (v - mu); }, 0) / (n - 1)) : 0;
    var curAvg = day ? cur.out / day : 0, prevAvg = mean(prev.map(function(s){ return s.out; })) / 30.4;
    var w = prev.length ? Math.min(0.85, day / 15) : 1, mub = w * curAvg + (1 - w) * prevAvg;
    var mid = mub * rem, band = sd * Math.sqrt(rem);
    var proj = cur.out + mid, low = cur.out + Math.max(0, mid - band), high = cur.out + mid + band;
    var incAvg = mean(prev.filter(function(s){ return s.inn > 0; }).map(function(s){ return s.inn; }));
    var income = Math.max(cur.inn, incAvg), basis = "income"; if(!(income > 0)){ income = state.budget; basis = "budget"; }
    var hist = prev.filter(function(s){ return s.out > 0; }).map(function(s){ return s.out; }).reverse(), next, trend = 0;
    if(hist.length >= 3){
      var hn = hist.length, hx = (hn - 1) / 2, hm = mean(hist), num = 0, den = 0;
      hist.forEach(function(v, j){ num += (j - hx) * (v - hm); den += (j - hx) * (j - hx); });
      var slope = den ? num / den : 0; trend = hm ? slope / hm : 0;
      next = Math.min(hm * 1.4, Math.max(hm * 0.6, hm + slope * (hn - hx)));
    } else next = hist.length ? mean(hist) : proj;
    var paces = [];
    prev.slice(0,3).forEach(function(s){ var b = s.inn > 0 ? s.inn : state.budget; if(b > 0) paces.push(b - s.out); });
    var rate = paces.length ? mean(paces) : (income > 0 ? income - proj : 0);
    var pays = [cur].concat(prev.slice(0,3)).map(function(s){ return s.cat.Debt || 0; }).filter(function(v){ return v > 0; });
    return {tk:tk, day:day, dim:dim, rem:rem, cur:cur, prev:prev, days:n, proj:proj, low:low, high:high, income:income, basis:basis,
      saved:income - proj, savedLow:income - high, savedHigh:income - low, next:next, trend:trend, rate:rate, payAvg:mean(pays),
      conf: (hist.length >= 3 && n >= 45) ? "High" : (n >= 14 ? "Medium" : "Low")};
  }
  function etaText(mo){ return mo > 120 ? "10+ years" : mo + (mo === 1 ? " month" : " months") + " (" + addMonths(mo) + ")"; }
  function fRow(list, name, right, meta, cls){
    var li = el("li"), top = el("div","dtop");
    top.appendChild(typeof name === "string" ? el("span","dname", name) : name); top.appendChild(el("span","amt", right)); li.appendChild(top);
    if(meta) li.appendChild(el("p","gmeta" + (cls ? " " + cls : ""), meta));
    list.appendChild(li);
  }
  function drawForecast(){
    var F = calcForecast(), tiles = $("fTiles"), cats = $("fCats"), eta = $("fEta");
    tiles.innerHTML = ""; cats.innerHTML = ""; eta.innerHTML = "";
    $("fConf").textContent = "Confidence: " + F.conf + " (" + F.days + (F.days === 1 ? " day" : " days") + " of data, " + F.prev.length + " earlier " + (F.prev.length === 1 ? "month" : "months") + ")";
    $("fNote").textContent = "Estimates use your spending pace and history. Big one-off or early-month bills (like rent) can push the projection up, and more history makes it better.";
    if(!state.items.length){
      $("fHead").textContent = "Log some transactions and your forecast will appear here.";
      cats.appendChild(el("li","empty","Nothing to forecast yet.")); eta.appendChild(el("li","empty","Add a goal or a debt to see when you'll get there.")); return;
    }
    var last = F.prev.length && F.prev[0].key === monthKey(-1) ? F.prev[0] : null, head = "At your current pace you'll spend about " + fmt(F.proj) + " this month";
    if(last && last.out > 0){ var df = (F.proj - last.out) / last.out; head += Math.abs(df) < 0.03 ? ", about the same as last month." : ", " + Math.round(Math.abs(df) * 100) + "% " + (df > 0 ? "more" : "less") + " than last month."; } else head += ".";
    $("fHead").textContent = head;
    tiles.appendChild(tile("Projected spending this month", fmt(F.proj), "Likely " + fmt(F.low) + " to " + fmt(F.high) + " \u00b7 " + fmt(F.cur.out) + " so far", ""));
    if(F.income > 0){
      var gap = state.goal > 0 ? F.saved - state.goal : null;
      tiles.appendChild(tile("Projected savings this month", fmt(F.saved),
        (state.goal > 0 ? (gap >= 0 ? "Meets your goal of " + fmt(state.goal) : "Short of your goal by " + fmt(-gap)) : "Based on your " + F.basis) + " \u00b7 likely " + fmt(F.savedLow) + " to " + fmt(F.savedHigh),
        state.goal > 0 ? (gap >= 0 ? "good" : "bad") : ""));
    } else tiles.appendChild(tile("Projected savings this month", "\u2014", setPrompt("a monthly budget or log money in")));
    var tr = Math.abs(F.trend) >= 0.03 ? (F.trend > 0 ? "Trending up about " : "Trending down about ") + Math.round(Math.abs(F.trend) * 100) + "% a month" : (F.prev.length >= 3 ? "Fairly steady month to month" : "Based on limited history");
    tiles.appendChild(tile("Next month's spending", fmt(F.next), tr + (F.income > 0 ? " \u00b7 saving about " + fmt(F.income - F.next) : ""), F.trend >= 0.03 ? "bad" : (F.trend <= -0.03 ? "good" : "")));

    var keys = Object.keys(F.cur.cat).sort(function(a, b){ return F.cur.cat[b] - F.cur.cat[a]; }).slice(0, 6);
    if(!keys.length) cats.appendChild(el("li","empty","No spending recorded this month yet."));
    var pt = F.prev.slice(0,3).map(function(s){ return monthStats(s.key, F.day); });
    keys.forEach(function(c){
      var now = F.cur.cat[c], usual = pt.length ? mean(pt.map(function(s){ return s.cat[c] || 0; })) : null, txt, cls = "";
      if(usual === null) txt = "No earlier months to compare yet.";
      else if(usual < 0.005) txt = "New this month.";
      else { var dv = (now - usual) / usual;
        if(Math.abs(dv) < 0.1) txt = "In line with your usual for this point in the month.";
        else { txt = (dv > 0 ? "\u25b2 " : "\u25bc ") + Math.round(Math.abs(dv) * 100) + "% " + (dv > 0 ? "above" : "below") + " your usual for this point in the month."; cls = dv > 0 ? "bad" : "good"; } }
      var nm = el("span","dname", c); nm.appendChild(el("span","badge", Math.round(now / F.cur.out * 100) + "% of spending"));
      fRow(cats, nm, fmt(now), txt, cls);
    });

    var any = false, goalsLeft = 0;
    state.goals.forEach(function(g){
      any = true; var left = Math.max(0, g.target - g.saved), nm = el("span","dname"); nm.appendChild(el("span","fl", g.icon || "\ud83c\udfaf")); nm.appendChild(document.createTextNode(" " + g.name));
      if(left <= 0.004){ fRow(eta, nm, "Reached \ud83c\udf89", "", ""); return; }
      goalsLeft += left;
      if(F.rate <= 0){ fRow(eta, nm, "Not on pace", fmt(left) + " to go. Your recent months show little or no savings, so try a saving tip to get moving.", "bad"); return; }
      var mo = Math.ceil(left / F.rate), meta = fmt(left) + " to go at about " + fmt(F.rate) + " a month (if all your savings go to this goal).", cls = "";
      if(g.date){
        var days = Math.ceil((new Date(g.date + "T00:00:00") - new Date(today() + "T00:00:00")) / 86400000), tm = Math.max(1, Math.round(days / 30.4));
        if(days > 0){ if(mo <= tm){ meta += " Ahead of your target date."; cls = "good"; } else { meta += " Behind your target date: you'd need about " + fmt(left / tm) + " a month."; cls = "bad"; } }
      }
      fRow(eta, nm, etaText(mo), meta, cls);
    });
    if(state.goals.length > 1 && goalsLeft > 0 && F.rate > 0) fRow(eta, "All goals together", etaText(Math.ceil(goalsLeft / F.rate)), fmt(goalsLeft) + " in total at about " + fmt(F.rate) + " a month.", "");
    var oweLeft = state.debts.filter(function(d){ return d.kind !== "owed"; }).reduce(function(t, d){ return t + Math.max(0, d.total - d.paid); }, 0);
    if(oweLeft > 0.004){
      any = true;
      if(F.payAvg > 0) fRow(eta, "Debt-free date", etaText(Math.ceil(oweLeft / F.payAvg)), fmt(oweLeft) + " owed at about " + fmt(F.payAvg) + " a month in payments.", "");
      else fRow(eta, "Debt-free date", "\u2014", fmt(oweLeft) + " owed. Log a debt payment and an estimate will appear.", "");
    }
    if(!any) eta.appendChild(el("li","empty","Add a goal or a debt to see when you'll get there."));
  }

  /* AI insights (asks Claude through the page's sample capability) */
  var aiSample = null, aiCtl = null;
  try{
    if(window.claude && window.claude.use) window.claude.use("sample").then(function(f){ aiSample = f; paintAI(); }, function(){ aiSample = null; paintAI(); });
  }catch(e){}
  function paintAI(){
    var b = $("aiGo"), out = $("aiOut");
    Array.prototype.forEach.call(out.querySelectorAll(".aina"), function(n){ n.parentNode.removeChild(n); });
    if(!aiSample){ b.disabled = true; if(!out.firstChild) out.appendChild(el("p","aibusy aina","AI insights work when this page is opened in Claude. The forecast above works everywhere.")); }
    else b.disabled = false;
  }
  function r2(n){ return Math.round(n * 100) / 100; }
  function rc(o){ var q = {}; Object.keys(o).forEach(function(k){ q[k] = r2(o[k]); }); return q; }
  function aiPrompt(){
    var F = calcForecast(), months = [{month:F.tk + " (so far, day " + F.day + " of " + F.dim + ")", spent:r2(F.cur.out), income:r2(F.cur.inn), spentByCategory:rc(F.cur.cat)}];
    F.prev.forEach(function(s){ months.push({month:s.key, spent:r2(s.out), income:r2(s.inn), spentByCategory:rc(s.cat)}); });
    var data = {currency:state.code || state.cur || "USD", today:today(), monthlyBudget:state.budget, monthlySavingsGoal:state.goal, months:months,
      localForecast:{projectedSpendThisMonth:r2(F.proj), likelyRange:[r2(F.low), r2(F.high)], incomeOrBudgetUsed:r2(F.income), basis:F.basis, projectedSavedThisMonth:r2(F.saved), nextMonthSpend:r2(F.next), confidence:F.conf},
      goals:state.goals.map(function(g){ return {name:g.name, target:g.target, saved:g.saved, targetDate:g.date || null}; }),
      debts:state.debts.map(function(d){ return {name:d.name, type:d.kind === "owed" ? "owed to the user" : "the user owes", total:d.total, paid:d.paid, due:d.due || null}; })};
    return "You are a careful, encouraging personal-finance coach inside an expense-tracker app. Analyse the user's data below and predict their spending and saving. "
      + "Use only the numbers provided and do not invent figures. If there is little history (few months), say so and keep predictions modest. Amounts are in " + data.currency + ". "
      + "Respond with ONLY a JSON object, no markdown fences, with exactly this shape: "
      + '{"summary": string (2-3 sentences), "predictions": [{"title": string, "detail": string}] (3-4 items covering this month, next month, saving, and goal or debt timing), '
      + '"risks": [string] (0-3 items), "opportunities": [string] (2-4 items specific to their categories), "next_steps": [string] (3-5 concrete actions for this week)}. '
      + "Keep every string under 220 characters. Do not recommend specific investments or products. This is general information, not financial advice.\n\nDATA:\n" + JSON.stringify(data);
  }
  function aiClean(o){
    var str = function(v){ return String(v == null ? "" : v).slice(0, 320); }, arr = function(v){ return Array.isArray(v) ? v.slice(0, 6).map(str).filter(Boolean) : []; };
    return {summary:str(o && o.summary), predictions:Array.isArray(o && o.predictions) ? o.predictions.slice(0, 5).map(function(p){ return {title:str(p && p.title), detail:str(p && p.detail)}; }) : [],
      risks:arr(o && o.risks), opportunities:arr(o && o.opportunities), next_steps:arr(o && o.next_steps)};
  }
  function aiShow(r, at){
    var out = $("aiOut"); out.innerHTML = "";
    if(r.summary) out.appendChild(el("p","aisum", r.summary));
    var block = function(title, items, ordered){
      if(!items.length) return;
      out.appendChild(el("p","aih", title)); var l = el(ordered ? "ol" : "ul","ailist");
      items.forEach(function(t){ l.appendChild(el("li","",t)); }); out.appendChild(l);
    };
    if(r.predictions.length){
      out.appendChild(el("p","aih","Predictions")); var pl = el("ul","ailist");
      r.predictions.forEach(function(p){ var li = el("li"); li.appendChild(el("b","", p.title + (p.detail ? ": " : ""))); li.appendChild(document.createTextNode(p.detail)); pl.appendChild(li); });
      out.appendChild(pl);
    }
    block("Watch out for", r.risks, false); block("Opportunities", r.opportunities, false); block("Next steps this week", r.next_steps, true);
    $("aiWhen").textContent = at ? "Generated " + new Date(at).toLocaleString(undefined,{dateStyle:"medium", timeStyle:"short"}) : "";
    $("aiGo").textContent = "Refresh AI insights";
  }
  function aiLoad(){
    $("aiOut").innerHTML = ""; $("aiWhen").textContent = ""; $("aiGo").textContent = "Generate AI insights";
    try{ var r = JSON.parse(localStorage.getItem("et-ai-" + uid)); if(r && r.data) aiShow(aiClean(r.data), r.at); }catch(e){}
    paintAI();
  }
  function aiBusy(on){ $("aiGo").disabled = on || !aiSample; $("aiStop").hidden = !on; }
  $("aiStop").addEventListener("click", function(){ if(aiCtl) aiCtl.abort(); });
  $("aiGo").addEventListener("click", async function(){
    if(!aiSample) return;
    var out = $("aiOut");
    if(!state.items.length){ out.innerHTML = ""; out.appendChild(el("p","aibusy","Log some transactions first so there is something to analyse.")); return; }
    aiCtl = new AbortController(); aiBusy(true);
    var keep = out.innerHTML; out.innerHTML = ""; out.appendChild(el("p","aibusy","Thinking\u2026 this can take up to a minute."));
    try{
      var data = await aiSample.json(aiPrompt(), {signal:aiCtl.signal, modelTier:"default"});
      var res = aiClean(data);
      if(!res.summary && !res.predictions.length) throw {code:"bad_format"};
      var at = new Date().toISOString();
      try{ localStorage.setItem("et-ai-" + uid, JSON.stringify({at:at, data:res})); }catch(e){}
      aiShow(res, at);
    }catch(e){
      var code = e && e.code, msg = code === "not_granted" ? "You chose not to allow this. You can try again and allow it when asked."
        : code === "rate_limited" ? "Too many requests right now. Please try again in a minute."
        : code === "cancelled" ? "Stopped."
        : "Couldn't get insights right now. Please try again.";
      out.innerHTML = keep || ""; if(!keep) out.appendChild(el("p","aibusy",msg)); else out.insertBefore(el("p","aibusy",msg), out.firstChild);
    }finally{ aiBusy(false); }
  });

  /* ---------- daily saving tips ---------- */
  var TIPS = {
    Food:["Plan your meals for the week before you shop, and buy only what is on the list.","Cook a bigger batch and eat the leftovers tomorrow: two meals for one cooking session.","Carry a snack and a bottle of water so you are not tempted by pricey on-the-go buys.","Compare the price per kilo or per litre, not just the sticker price. Bigger is not always cheaper.","Eat before you go shopping. Hungry shoppers spend more.","Buy fruit and vegetables when they are in season. They are usually fresher and cheaper.","Before you throw food out, ask what meal it could become. Wasted food is wasted money.","Try a no-takeaway week and see how much you keep."],
    Transport:["Combine your errands into one trip to save on fuel or fares.","Walk or cycle short trips. If it takes under 20 minutes, your legs are free.","Share rides with friends or colleagues who travel the same route.","Keep your tyres properly inflated. It helps fuel use and makes them last longer.","Compare fares or fuel prices before long trips. Small differences add up over a month.","Travel outside peak hours when fares or ride prices are lower.","Keep up with basic maintenance. A small fix now often prevents a big repair bill later.","Before buying a vehicle, add up fuel, insurance and servicing, not just the purchase price."],
    Bills:["Switch off lights and unplug chargers and devices you are not using.","Review your subscriptions this week and cancel the ones you have not used in a month.","Set reminders a few days before due dates so you never pay late fees.","Ask your providers whether a cheaper plan fits how you actually use the service.","Check your data and airtime use. Many people pay for more than they need.","Fix small leaks and drips. They quietly add to the water bill.","Pay your bills on payday so the money is set aside before you can spend it.","Compare providers once a year instead of renewing without looking."],
    Shopping:["Wait 24 hours before buying anything that is not a need. Often the urge fades.","Write a list and stick to it.","Ask yourself how many hours of work this costs. Is it still worth it?","Check whether you can buy it second-hand or borrow it first.","Unsubscribe from shop promotions that tempt you to buy.","Compare prices in two or three places before any big purchase.","For things you use every day, choose quality. Cheap items that break cost more over time.","Set a monthly fun-money limit so small treats do not become overspending."],
    Health:["Staying well is cheaper than getting treated. Protect your sleep, water and movement.","Ask your pharmacist or doctor whether a lower-cost equivalent is suitable for you.","Keep up with routine check-ups. Catching problems early usually costs less.","Cook at home more often. It is often healthier and cheaper than eating out.","Use free exercise: walking, bodyweight workouts and community sports.","Review whether you really use that gym membership.","Set aside a small health emergency fund so a surprise does not derail your budget.","Rest when you are unwell. Avoidable sick days can cost you income."],
    Debt:["List every debt with its balance and interest. You cannot beat what you have not measured.","Pay the minimum on every debt, then put each extra amount on one target debt.","Paying the highest-interest debt first saves the most money. Paying the smallest first gives quick wins. Pick the one you will stick with.","Avoid taking on new debt while you are paying off old debt.","When extra money arrives (a bonus or gift), put part of it toward debt straight away.","Ask your lender whether a lower rate or a different repayment plan is available.","Celebrate every debt you clear. Motivation keeps you paying.","Borrow only for things that grow your income or hold their value, and only what you can repay."],
    Savings:["Pay yourself first: move money into savings on payday before you spend.","Start with a small emergency fund goal, such as one week of expenses, then build it up.","Round up purchases in your head and save the difference.","Save windfalls like gifts, bonuses and refunds instead of spending them all.","Automate it: a standing transfer is a habit you never have to remember.","Keep savings separate from spending money so it is harder to touch.","Raise your savings by a small percentage every time your income rises.","Give every goal a name and a date. Money with a purpose lasts longer."],
    Mindset:["Track every expense for a week. Awareness alone changes behaviour.","Aim for progress, not perfection. One overspend does not ruin a month.","Tell a friend about your goal. Accountability helps.","Compare your spending to your goals, not to other people's lifestyles.","Spend 10 minutes each week reviewing your money. Small habit, big payoff.","Swap \"I can't afford it\" for \"Is it a priority?\" and decide on purpose.","Celebrate milestones with something free or low cost.","Remember why you are saving, and keep your biggest goal where you can see it."]
  };
  var TIP_CATS = ["Savings","Food","Mindset","Transport","Bills","Debt","Shopping","Health"], TIP_ALL = [];
  for(var ti = 0; ti < 8; ti++){ TIP_CATS.forEach(function(c){ TIP_ALL.push({c:c, t:TIPS[c][ti]}); }); }
  var tipOffset = 0, lastBy = {};
  function dayIdx(){
    var y = +today().slice(0,4);
    return Math.floor((new Date(today() + "T00:00:00Z") - Date.UTC(y, 0, 0)) / 86400000);
  }
  function tipStreak(){
    var set = {}; state.tipsDone.forEach(function(d){ set[d] = 1; });
    var cur = new Date(today() + "T00:00:00Z");
    if(!set[cur.toISOString().slice(0,10)]) cur.setUTCDate(cur.getUTCDate() - 1);
    var n = 0;
    while(set[cur.toISOString().slice(0,10)]){ n++; cur.setUTCDate(cur.getUTCDate() - 1); }
    return n;
  }
  function tipBox(host, label, cat, text){
    host.innerHTML = "";
    host.appendChild(el("p","tiplabel", label)); host.appendChild(el("span","tipcat", cat)); host.appendChild(el("p","tiptext", text));
  }
  function drawTips(by){
    lastBy = by || lastBy;
    var d = dayIdx(), n = TIP_ALL.length, i = (((d + tipOffset) % n) + n) % n, t = TIP_ALL[i];
    tipBox($("tipMain"), tipOffset === 0 ? "Tip of the day" : "Browsing tips", t.c, t.t);
    var top = null;
    Object.keys(lastBy).forEach(function(c){ if(!top || lastBy[c] > lastBy[top]) top = c; });
    var cat = top ? (TIPS[top] ? top : "Savings") : "Mindset", arr = TIPS[cat];
    tipBox($("tipFor"), top ? "Picked for you: " + top + " is your biggest spending this month" : "Picked for you: log some expenses and this tip will match your spending", cat, arr[d % arr.length]);
    var done = state.tipsDone.indexOf(today()) > -1, streak = tipStreak(), st = $("tStreak"); st.innerHTML = "";
    if(streak > 0){ st.appendChild(el("span","fl","\ud83d\udd25")); st.appendChild(document.createTextNode(" " + streak + (streak === 1 ? "-day streak" : "-day streak"))); }
    else st.textContent = "Start your streak today";
    $("tDone").textContent = tipOffset !== 0 ? "Back to today's tip" : (done ? "Done today \u2713 (tap to undo)" : "Mark today's tip as done");
  }
  $("tPrev").addEventListener("click", function(){ tipOffset--; drawTips(); });
  $("tNext").addEventListener("click", function(){ tipOffset++; drawTips(); });
  $("tDone").addEventListener("click", function(){
    if(tipOffset !== 0){ tipOffset = 0; drawTips(); return; }
    var k = state.tipsDone.indexOf(today());
    if(k > -1) state.tipsDone.splice(k, 1); else state.tipsDone.push(today());
    save(); drawTips();
  });

  /* ---------- progress colours + goals ---------- */
  // Red (0%) -> yellow (50%) -> green (100%), with every mixture in between.
  function progColor(p){
    p = Math.max(0, Math.min(100, p));
    var a = [220,38,38], b = [234,179,8], c = [22,163,74], from, to, f;
    if(p <= 50){ from = a; to = b; f = p / 50; } else { from = b; to = c; f = (p - 50) / 50; }
    return "rgb(" + from.map(function(v, i){ return Math.round(v + (to[i] - v) * f); }).join(",") + ")";
  }
  var raf = window.requestAnimationFrame ? function(fn){ window.requestAnimationFrame(fn); } : function(fn){ setTimeout(fn, 16); };
  function setBar(fill, pct, invert){
    pct = Math.max(0, Math.min(100, pct));
    fill.style.background = progColor(invert ? 100 - pct : pct); fill.style.width = "0%";
    raf(function(){ raf(function(){ fill.style.width = pct + "%"; }); });
  }
  var QUOTES = ["Small savings today become big wins tomorrow.", "A goal with a plan is a promise to your future self. Keep going.", "Progress, not perfection. Every contribution counts.",
    "The best time to start saving was yesterday. The next best time is now.", "Little by little, a little becomes a lot.", "Discipline today is freedom tomorrow.",
    "You don't have to save it all at once. Just don't stop.", "Your future self will thank you for every deposit.", "Dream big, save steadily, celebrate often.", "Consistency beats intensity. Show up for your goals."];
  function goalMsg(g, pct, left){
    if(pct >= 100) return "\ud83c\udf89 Goal reached! Enjoy your " + g.name + ". You earned it.";
    if(pct >= 75) return "So close! Only " + fmt(left) + " to go for " + g.name + ".";
    if(pct >= 50) return "Past the halfway mark. The finish line for " + g.name + " is in sight.";
    if(pct >= 25) return "A quarter of the way there. Keep the momentum going.";
    if(pct > 0) return "Great start! Every contribution brings " + g.name + " closer.";
    return "Every big goal starts with a first step. Add your first savings today.";
  }
  function drawGoals(){
    var day = Math.floor((new Date() - new Date(new Date().getFullYear(), 0, 0)) / 86400000);
    $("gQuote").textContent = "\u201c" + QUOTES[day % QUOTES.length] + "\u201d";
    var sum = $("gSum"), list = $("gList"); sum.innerHTML = ""; list.innerHTML = "";
    var gs = state.goals, saved = 0, target = 0, done = 0;
    gs.forEach(function(g){ saved += Math.min(g.saved, g.target); target += g.target; if(g.saved >= g.target) done++; });
    var overall = target > 0 ? saved / target * 100 : 0;
    sum.appendChild(tile("Saved toward goals", fmt(saved), gs.length ? "of " + fmt(target) + " in total" : "Add your first goal below", ""));
    var t2 = tile("Overall progress", Math.round(overall) + "%", gs.length ? (overall >= 100 ? "Every goal reached!" : fmt(target - saved) + " still to go") : "No goals yet", "");
    var tr = el("div","track"), fl = el("i"); fl.style.display = "block"; fl.style.height = "100%"; setBar(fl, overall);
    tr.appendChild(fl); t2.insertBefore(tr, t2.lastChild); sum.appendChild(t2);
    sum.appendChild(tile("Goals reached", done + " of " + gs.length, gs.length ? (done === gs.length ? "All done. Time to set a new one!" : "Keep going") : "Nothing yet", done > 0 && done === gs.length ? "good" : ""));
    if(!gs.length){ list.appendChild(el("li","empty","No goals yet. Pick an icon, name your goal and set a target to begin.")); return; }
    gs.slice().sort(function(a, b){ return b.id - a.id; }).forEach(function(g){
      var pct = g.target > 0 ? Math.min(100, g.saved / g.target * 100) : 0, left = Math.max(0, g.target - g.saved);
      var li = el("li"), top = el("div","gtop"), nm = el("span","gname");
      nm.appendChild(el("span","fl", g.icon || "\ud83c\udfaf")); nm.appendChild(document.createTextNode(g.name));
      nm.appendChild(el("span","badge", Math.floor(pct) + "%"));
      top.appendChild(nm); top.appendChild(el("span","amt", fmt(g.saved) + " of " + fmt(g.target)));
      li.appendChild(top);
      var bar = el("div","gbar"), fill = el("i");
      bar.setAttribute("role","progressbar"); bar.setAttribute("aria-valuemin","0"); bar.setAttribute("aria-valuemax","100"); bar.setAttribute("aria-valuenow", String(Math.floor(pct)));
      bar.setAttribute("aria-label", "Progress toward " + g.name);
      setBar(fill, pct); bar.appendChild(fill); li.appendChild(bar);
      li.appendChild(el("p","gmsg", goalMsg(g, pct, left)));
      if(left > 0.004){
        var info = fmt(left) + " to go";
        if(g.date){
          var days = Math.ceil((new Date(g.date + "T00:00:00") - new Date(today() + "T00:00:00")) / 86400000);
          if(days <= 0) info += " \u00b7 Target date has passed. Pick a new date or keep going.";
          else { var months = Math.max(1, Math.round(days / 30.4)); info += " \u00b7 Save about " + fmt(left / months) + " a month to reach it by " + g.date + " (" + months + (months === 1 ? " month" : " months") + " left)"; }
        }
        li.appendChild(el("p","gmeta", info));
      }
      var act = el("div","gact");
      var inp = el("input"); inp.type = "number"; inp.min = "0"; inp.step = "0.01"; inp.placeholder = "Amount"; inp.setAttribute("inputmode","decimal");
      inp.setAttribute("aria-label", "Amount for " + g.name);
      var add = el("button","btn ghost","Add savings"), wd = el("button","btn ghost","Withdraw"), del = el("button","btn ghost","Remove goal");
      add.type = wd.type = del.type = "button";
      var apply = function(sign){
        var v = parseFloat(inp.value);
        if(!(v > 0)){ inp.focus(); return; }
        g.saved = Math.max(0, Math.round((g.saved + sign * v) * 100) / 100); save(); render();
      };
      add.addEventListener("click", function(){ apply(1); });
      wd.addEventListener("click", function(){ apply(-1); });
      inp.addEventListener("keydown", function(e){ if(e.key === "Enter"){ e.preventDefault(); apply(1); } });
      del.addEventListener("click", function(){ var gone = g; state.goals = state.goals.filter(function(x){ return x.id !== g.id; }); save(); render(); toast("Goal removed.", function(){ state.goals.push(gone); save(); render(); }); });
      act.appendChild(inp); act.appendChild(add); act.appendChild(wd); act.appendChild(el("span","grow")); act.appendChild(del);
      li.appendChild(act); list.appendChild(li);
    });
  }
  $("gForm").addEventListener("submit", function(ev){
    ev.preventDefault(); setMsg("gErr","");
    var name = $("gName").value.trim(), target = parseFloat($("gTarget").value), saved = parseFloat($("gSaved").value) || 0;
    if(!name){ setMsg("gErr","Name your goal, for example New car."); $("gName").focus(); return; }
    if(!(target > 0)){ setMsg("gErr","Enter a target amount greater than 0."); $("gTarget").focus(); return; }
    if(saved < 0){ setMsg("gErr","Saved so far can't be negative."); return; }
    state.goals.push({id:Date.now(), name:name, icon:$("gIcon").value, target:Math.round(target * 100) / 100, saved:Math.round(saved * 100) / 100, date:$("gDate").value || ""});
    save(); $("gName").value = ""; $("gTarget").value = ""; $("gSaved").value = ""; $("gDate").value = ""; render();
  });

  /* ---------- crypto ---------- */
  // USD prices, indicative snapshot around 11 Oct 2026 (source: CoinDesk price list).
  var CRYPTO_DATE = "11 Oct 2026";
  var CRYPTO_LIST = [["BTC","Bitcoin",82985.25],["ETH","Ethereum",2544.67],["USDT","Tether",0.999],["BNB","BNB",755.32],["XRP","XRP",1.39],["USDC","USD Coin",0.9999],["SOL","Solana",109.45],["TRX","TRON",0.3313],
    ["HYPE","Hyperliquid",84.98],["ZEC","Zcash",1286.26],["DOGE","Dogecoin",0.08738],["XMR","Monero",538.38],["LINK","Chainlink",12.87],["ADA","Cardano",0.2551],["XLM","Stellar Lumens",0.2047],["NEAR","NEAR Protocol",5.24],
    ["BCH","Bitcoin Cash",278.3],["LTC","Litecoin",64.71],["UNI","Uniswap",7.84],["AVAX","Avalanche",10.32],["DAI","Dai",0.9997],["SUI","Sui",1.1],["HBAR","Hedera",0.09168],["SHIB","Shiba Inu",0.055388],["AAVE","Aave",167.49],["DOT","Polkadot",1.25]];
  var CRYPTO = {};
  CRYPTO_LIST.forEach(function(c){ CRYPTO[c[0]] = {n:c[1], p:c[2]}; });
  function usdOf(code){ return CRYPTO[code] ? CRYPTO[code].p : 1 / RATES[code]; }
  function fmtAsset(n, code){
    var a = Math.abs(n);
    if(a === 0) return "0";
    if(CRYPTO[code]) return n.toLocaleString("en-US",{maximumFractionDigits: a >= 1000 ? 4 : a >= 1 ? 6 : 8});
    if(a >= 1) return nf(n);
    return n.toLocaleString("en-US",{maximumSignificantDigits:4});
  }
  // USD amount shown in the user's own currency (or in USD if their country isn't set)
  function moneyUSD(usd){
    var r = RATES[state.code];
    if(!r) return "$" + (usd >= 1 ? nf(usd) : usd.toLocaleString("en-US",{maximumSignificantDigits:3}));
    var v = usd * r;
    return v >= 1 ? fmt(v) : sym() + v.toLocaleString("en-US",{maximumSignificantDigits:3});
  }
  function fillCrypto(){
    var c = $("cCoin"); c.innerHTML = "";
    CRYPTO_LIST.forEach(function(x){ var o = el("option","", x[0] + " \u2014 " + x[1]); o.value = x[0]; o.setAttribute("data-s", x[0] + " " + x[1]); c.appendChild(o); });
    ["cxFrom","cxTo"].forEach(function(id){
      var sel = $(id); sel.innerHTML = "";
      CRYPTO_LIST.forEach(function(x){ var o = el("option","", x[0] + " \u2014 " + x[1]); o.value = x[0]; o.setAttribute("data-s", x[0] + " " + x[1] + " crypto coin"); sel.appendChild(o); });
      Array.prototype.forEach.call($("cvFrom").options, function(src){
        var o = el("option","", src.text); o.value = src.value; o.setAttribute("data-s", src.getAttribute("data-s") || src.text); sel.appendChild(o);
      });
    });
  }
  function drawPrices(){
    var host = $("cPrices"); host.innerHTML = "";
    var q = norm($("cFind").value.trim());
    var rows = CRYPTO_LIST.filter(function(c){ return !q || norm(c[0] + " " + c[1]).indexOf(q) > -1; });
    if(!rows.length) host.appendChild(el("li","empty","No coins match your search."));
    rows.forEach(function(c){
      var li = el("li","crow");
      li.appendChild(el("span","cs", c[0])); li.appendChild(el("span","cn", c[1])); li.appendChild(el("span","cp", moneyUSD(c[2])));
      host.appendChild(li);
    });
    $("cNote").textContent = "Indicative prices around " + CRYPTO_DATE + ", shown in " + (RATES[state.code] ? state.code : "USD")
      + ". Crypto prices move constantly, so check a live price before you trade.";
  }
  function drawCrypto(){
    var sum = $("cSum"), list = $("cList"); sum.innerHTML = ""; list.innerHTML = "";
    var total = 0, best = null, hs = state.holdings;
    hs.forEach(function(h){ var v = h.amt * CRYPTO[h.sym].p; total += v; if(!best || v > best.v) best = {h:h, v:v}; });
    sum.appendChild(tile("Portfolio value", moneyUSD(total), hs.length ? "Indicative, at " + CRYPTO_DATE + " prices" : "Add a holding below", ""));
    sum.appendChild(tile("Coins held", String(hs.length), hs.length ? hs.map(function(h){ return h.sym; }).join(", ") : "Nothing yet", ""));
    sum.appendChild(best ? tile("Largest holding", best.h.sym, Math.round(best.v / total * 100) + "% of portfolio", "") : tile("Largest holding", "\u2014", "Nothing yet", ""));
    if(!hs.length) list.appendChild(el("li","empty","No crypto holdings yet. Add the coins you hold above."));
    hs.slice().sort(function(a, b){ return b.amt * CRYPTO[b.sym].p - a.amt * CRYPTO[a.sym].p; }).forEach(function(h){
      var c = CRYPTO[h.sym], li = el("li"), top = el("div","dtop"), nm = el("span","dname", c.n);
      nm.appendChild(el("span","badge", h.sym));
      top.appendChild(nm); top.appendChild(el("span","amt", moneyUSD(h.amt * c.p)));
      li.appendChild(top);
      var meta = el("div","dmeta"); meta.appendChild(el("span","", fmtAsset(h.amt, h.sym) + " " + h.sym + " at " + moneyUSD(c.p) + " each")); li.appendChild(meta);
      var act = el("div","dact"); act.appendChild(el("span","grow"));
      var del = el("button","btn ghost","Remove"); del.type = "button"; del.setAttribute("aria-label","Remove " + c.n);
      del.addEventListener("click", function(){ state.holdings = state.holdings.filter(function(x){ return x.id !== h.id; }); save(); render(); });
      act.appendChild(del); li.appendChild(act); list.appendChild(li);
    });
    drawPrices();
  }
  function cxRun(){
    var out = $("cxOut"); out.innerHTML = "";
    var amt = parseFloat($("cxAmt").value), f = $("cxFrom").value, t = $("cxTo").value, own = parseFloat($("cxRate").value);
    if(!(amt >= 0)){ out.appendChild(el("div","cvsub","Enter an amount to convert.")); return; }
    var rate = own > 0 ? own : usdOf(f) / usdOf(t);
    out.appendChild(el("div","cvsub", fmtAsset(amt, f) + " " + f + " ="));
    out.appendChild(el("div","cvbig", fmtAsset(amt * rate, t) + " " + t));
    out.appendChild(el("div","cvsub", "1 " + f + " = " + fmtAsset(rate, t) + " " + t + "  \u00b7  1 " + t + " = " + fmtAsset(1 / rate, f) + " " + f));
    $("cxNote").textContent = own > 0 ? "Using your own rate."
      : "Indicative prices around " + CRYPTO_DATE + ". Crypto prices move constantly, and exchanges add fees and spreads, so the amount you actually get will differ.";
  }
  function cxSync(){
    clearSearch("cxFrom"); clearSearch("cxTo");
    $("cxFrom").value = "BTC"; $("cxTo").value = RATES[state.code] ? state.code : "USD"; $("cxRate").value = ""; cxRun();
  }
  ["cxAmt","cxRate"].forEach(function(id){ $(id).addEventListener("input", cxRun); });
  ["cxFrom","cxTo"].forEach(function(id){ $(id).addEventListener("change", cxRun); });
  $("cxSwap").addEventListener("click", function(){
    clearSearch("cxFrom"); clearSearch("cxTo");
    var f = $("cxFrom").value; $("cxFrom").value = $("cxTo").value; $("cxTo").value = f; $("cxRate").value = ""; cxRun();
  });
  $("cFind").addEventListener("input", drawPrices);
  $("cForm").addEventListener("submit", function(ev){
    ev.preventDefault(); setMsg("cErr","");
    var coin = $("cCoin").value, amt = parseFloat($("cAmt").value);
    if(!CRYPTO[coin]){ setMsg("cErr","Choose a coin."); return; }
    if(!(amt > 0)){ setMsg("cErr","Enter an amount greater than 0."); $("cAmt").focus(); return; }
    var ex = state.holdings.filter(function(h){ return h.sym === coin; })[0];
    if(ex) ex.amt = Math.round((ex.amt + amt) * 1e8) / 1e8; else state.holdings.push({id:Date.now(), sym:coin, amt:amt});
    save(); $("cAmt").value = ""; render();
  });

  /* ---------- accounts (stored in this browser only) ---------- */
  var USERS = "et-users", SESS = "et-session", uid = null, authMode = "login", pickedColor = "#1d4ed8";
  var AV_COLORS = ["#1d4ed8","#047857","#6d28d9","#be185d","#c2410c","#475569"];
  function users(){ try{ return JSON.parse(localStorage.getItem(USERS)) || {}; }catch(e){ return {}; } }
  function putUsers(u){ try{ localStorage.setItem(USERS, JSON.stringify(u)); }catch(e){} }
  function myKey(){ var us = users(); for(var k in us){ if(us[k].id === uid) return k; } return null; }
  function b64(buf){ var a = new Uint8Array(buf), s = ""; for(var i=0;i<a.length;i++) s += String.fromCharCode(a[i]); return btoa(s); }
  function unb64(s){ var b = atob(s), a = new Uint8Array(b.length); for(var i=0;i<b.length;i++) a[i] = b.charCodeAt(i); return a; }
  async function hashPw(pw, salt){
    var key = await crypto.subtle.importKey("raw", new TextEncoder().encode(pw), "PBKDF2", false, ["deriveBits"]);
    return b64(await crypto.subtle.deriveBits({name:"PBKDF2", salt:salt, iterations:150000, hash:"SHA-256"}, key, 256));
  }
  function okEmail(e){ return /^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(e); }
  function setMsg(id, msg){ $(id).textContent = msg || ""; }

  var AVATARS = [
    {id:"a1",skin:"#f0c4a0",hair:"short",hc:"#2b2320",cloth:"#c2410c",bg:"#fde68a"},
    {id:"a2",skin:"#e2a97e",hair:"long",hc:"#1f1a18",cloth:"#475569",bg:"#bfdbfe"},
    {id:"a3",skin:"#b8754a",hair:"curly",hc:"#241a14",cloth:"#eab308",bg:"#e5e7eb",glasses:1},
    {id:"a4",skin:"#7a4a2b",hair:"short",hc:"#17120f",cloth:"#047857",bg:"#fbcfe8"},
    {id:"a5",skin:"#f3cfb0",hair:"bun",hc:"#7a4a2a",cloth:"#6d28d9",bg:"#ddd6fe"},
    {id:"a6",skin:"#5c3a21",hair:"curly",hc:"#120e0c",cloth:"#be185d",bg:"#fed7aa"},
    {id:"a7",skin:"#e8b48a",hair:"bald",hc:"#2b2320",cloth:"#1d4ed8",bg:"#bbf7d0",glasses:1,beard:1},
    {id:"a8",skin:"#c98a5e",hair:"long",hc:"#c9a15a",cloth:"#0f766e",bg:"#fef3c7"},
    {id:"a9",skin:"#f7d7bd",hair:"short",hc:"#c9a15a",cloth:"#334155",bg:"#fecaca"},
    {id:"a10",skin:"#9a6238",hair:"bun",hc:"#1a1411",cloth:"#c2410c",bg:"#c7d2fe"},
    {id:"a11",skin:"#3f2616",hair:"short",hc:"#0d0907",cloth:"#7c3aed",bg:"#fde68a",beard:1},
    {id:"a12",skin:"#edbf98",hair:"curly",hc:"#8b4a2b",cloth:"#be123c",bg:"#a7f3d0",glasses:1}
  ];
  function findAv(id){ for(var i=0;i<AVATARS.length;i++){ if(AVATARS[i].id === id) return AVATARS[i]; } return null; }
  function initial(u){ return (u.name || u.email).trim().charAt(0).toUpperCase(); }
  function avatarSVG(a){
    var hc = a.hc, sk = a.skin, back = "", top = "";
    if(a.hair === "long") back = '<path d="M27 46C25 20 75 20 73 46L76 84H24Z" fill="' + hc + '"/>';
    if(a.hair === "curly") back = '<g fill="' + hc + '"><circle cx="29" cy="40" r="11"/><circle cx="36" cy="27" r="11"/><circle cx="50" cy="22" r="12"/><circle cx="64" cy="27" r="11"/><circle cx="71" cy="40" r="11"/></g>';
    if(a.hair === "bun") back = '<circle cx="50" cy="13" r="9" fill="' + hc + '"/>';
    if(a.hair !== "bald") top = '<path d="M30 46C27 24 40 17 50 17C61 17 73 24 70 46C67 36 60 31 50 31C40 31 33 36 30 46Z" fill="' + hc + '"/>';
    return '<svg viewBox="0 0 100 100" aria-hidden="true">'
      + '<rect width="100" height="100" fill="' + a.bg + '"/>' + back
      + '<path d="M16 100C16 82 31 75 50 75C69 75 84 82 84 100Z" fill="' + a.cloth + '"/>'
      + '<rect x="43" y="60" width="14" height="20" rx="6" fill="' + sk + '"/>'
      + '<rect x="43" y="60" width="14" height="20" rx="6" fill="#000" fill-opacity=".1"/>'
      + '<path d="M41 76L50 88L59 76Z" fill="' + sk + '"/>'
      + '<circle cx="31" cy="49" r="4" fill="' + sk + '"/><circle cx="69" cy="49" r="4" fill="' + sk + '"/>'
      + '<ellipse cx="50" cy="47" rx="19" ry="22" fill="' + sk + '"/>'
      + (a.beard ? '<path d="M31 54C33 74 67 74 69 54C66 60 58 63 50 63C42 63 34 60 31 54Z" fill="' + hc + '"/>' : "")
      + top
      + '<path d="M38 40Q42 37.5 46 40M54 40Q58 37.5 62 40" stroke="' + hc + '" stroke-width="2" stroke-linecap="round" fill="none"/>'
      + '<circle cx="42" cy="46" r="2.3" fill="#2a1d1a"/><circle cx="58" cy="46" r="2.3" fill="#2a1d1a"/>'
      + '<path d="M50 48Q48.5 53 50.5 53" stroke="#000" stroke-opacity=".2" stroke-width="1.6" stroke-linecap="round" fill="none"/>'
      + '<path d="M42 56Q50 65 58 56Z" fill="#fff" stroke="#3a2420" stroke-width="1.6" stroke-linejoin="round"/>'
      + (a.glasses ? '<g fill="none" stroke="#1f2937" stroke-width="1.8"><circle cx="42" cy="46" r="6.5"/><circle cx="58" cy="46" r="6.5"/><path d="M48.5 46h3"/></g>' : "")
      + '</svg>';
  }
  function drawAvatars(u){
    var g = $("avGrid"); g.innerHTML = "";
    var ini = el("button", "", initial(u)); ini.type = "button";
    ini.style.background = u.color || AV_COLORS[0];
    ini.setAttribute("aria-label", "Use my initials");
    ini.setAttribute("aria-pressed", findAv(u.avatar) ? "false" : "true");
    ini.addEventListener("click", function(){ setAvatar(""); });
    g.appendChild(ini);
    AVATARS.forEach(function(a, i){
      var b = el("button"); b.type = "button"; b.innerHTML = avatarSVG(a);
      b.setAttribute("aria-label", "Avatar " + (i + 1));
      b.setAttribute("aria-pressed", u.avatar === a.id ? "true" : "false");
      b.addEventListener("click", function(){ setAvatar(a.id); });
      g.appendChild(b);
    });
    var pv = $("avPrev"), cur = findAv(u.avatar);
    if(cur){ pv.innerHTML = avatarSVG(cur); pv.style.background = "transparent"; }
    else { pv.textContent = initial(u); pv.style.background = u.color || AV_COLORS[0]; }
  }
  function setAvatar(id){
    var us = users(), u = us[myKey()]; if(!u) return;
    u.avatar = id; putUsers(us); paintHeader(u); drawAvatars(u);
  }
  function paintChip(u){
    var b = $("curChip"); b.innerHTML = "";
    if(u.code && RATES[u.code]){
      b.appendChild(el("span","fl", flag(CURFLAG[u.code]))); b.appendChild(document.createTextNode(u.code + " \u00b7 " + (u.cur || "")));
      b.title = "Currency symbol is set from your country" + (u.country ? " (" + u.country + ")" : "") + ". Click to change.";
    } else { b.textContent = "Set your country"; b.title = "Choose your country to set the currency symbol"; }
    $("amtCur").textContent = u.cur ? " (" + String(u.cur).trim() + ")" : "";
  }
  function paintHeader(u){
    var b = $("avBtn");
    var av = findAv(u.avatar);
    if(av){ b.innerHTML = avatarSVG(av); b.style.background = "transparent"; }
    else { b.textContent = initial(u); b.style.background = u.color || AV_COLORS[0]; }
    b.title = u.name + " (" + u.email + ")";
    paintChip(u); $("rcName").textContent = u.name;
  }
  var curPane = "overview", MONTH_PANES = ["overview","transactions","spending","tips"];
  function closeNav(){}
  function showView(v){
    var prof = v === "profile";
    $("dash").hidden = prof; $("profileView").hidden = !prof;
    Array.prototype.forEach.call(document.querySelectorAll(".pane"), function(p){ p.hidden = p.getAttribute("data-pane") !== curPane; });
    Array.prototype.forEach.call(document.querySelectorAll(".nav"), function(n){
      if(n.getAttribute("data-nav") === (prof ? "profile" : curPane)) n.setAttribute("aria-current","page"); else n.removeAttribute("aria-current");
    });
    $("mwrap").hidden = prof || MONTH_PANES.indexOf(curPane) < 0;
    closeNav();
    if(!prof && curPane === "spending") drawBars();
    if(!prof && curPane === "appearance"){ loadAllFonts(); $("apAmt").textContent = fmt(1234.56); }
    $("frame").setAttribute("data-pane", prof ? "profile" : curPane); $("mscroll").scrollTop = 0; window.scrollTo(0,0);
  }
  Array.prototype.forEach.call(document.querySelectorAll(".nav"), function(n){
    n.addEventListener("click", function(){
      var t = n.getAttribute("data-nav");
      if(t === "profile"){ openProfile(); } else { curPane = t; showView("dash"); }
    });
  });
  document.addEventListener("keydown", function(e){ if(e.key === "Escape") closeNav(); });
  function drawSwatches(){
    var host = $("pColors"); host.innerHTML = "";
    AV_COLORS.forEach(function(c){
      var b = el("button"); b.type = "button"; b.style.background = c;
      b.setAttribute("aria-label","Avatar color " + c);
      b.setAttribute("aria-pressed", c === pickedColor ? "true" : "false");
      b.addEventListener("click", function(){ pickedColor = c; drawSwatches(); });
      host.appendChild(b);
    });
  }
  function openProfile(){
    var u = users()[myKey()]; if(!u) return;
    $("pName").value = u.name; $("pEmail").value = u.email; clearSearch("pCountry"); $("pCountry").value = u.country || ""; showCur();
    $("pBudget").value = u.budget || ""; $("pGoal").value = u.goal || "";
    pickedColor = u.color || AV_COLORS[0]; drawSwatches(); drawAvatars(u);
    ["pErr","pOk","wErr","wOk"].forEach(function(i){ setMsg(i,""); });
    showView("profile");
  }
  function enter(u){
    uid = u.id; state.cur = u.cur || "$"; state.code = u.code || ""; state.budget = +u.budget || 0; state.goal = +u.goal || 0; state.items = []; state.debts = []; state.holdings = []; state.goals = []; state.tipsDone = []; state.recurring = []; state.budgets = {};
    try{ var r = JSON.parse(localStorage.getItem("et-data-" + uid)); if(r && Array.isArray(r.items)) state.items = r.items; if(r && Array.isArray(r.debts)) state.debts = r.debts; if(r && Array.isArray(r.holdings)) state.holdings = r.holdings.filter(function(h){ return CRYPTO[h.sym]; }); if(r && Array.isArray(r.goals)) state.goals = r.goals; if(r && Array.isArray(r.tipsDone)) state.tipsDone = r.tipsDone; if(r && Array.isArray(r.recurring)) state.recurring = r.recurring; if(r && r.budgets && typeof r.budgets === "object") state.budgets = r.budgets; }catch(e){}
    try{ localStorage.setItem(SESS, uid); }catch(e){}
    loadPrefs(); aiLoad(); runRecurring();
    $("auth").hidden = true; $("app").hidden = false;
    paintHeader(u); showView("dash"); render(); syncConv();
  }
  function leave(){
    try{ localStorage.removeItem(SESS); }catch(e){}
    uid = null; state.items = []; state.debts = []; state.holdings = []; state.goals = []; state.tipsDone = []; state.recurring = []; state.budgets = {};
    $("app").hidden = true; $("auth").hidden = false;
    $("aPass").value = ""; setMsg("aErr","");
  }

  Array.prototype.forEach.call(document.querySelectorAll("#auth .seg button"), function(b){
    b.addEventListener("click", function(){
      authMode = b.getAttribute("data-m");
      Array.prototype.forEach.call(document.querySelectorAll("#auth .seg button"), function(o){
        o.setAttribute("aria-pressed", o === b ? "true" : "false");
      });
      var reg = authMode === "register";
      $("nameRow").hidden = !reg; $("countryRow").hidden = !reg;
      $("aGo").textContent = reg ? "Create account" : "Sign in";
      $("authsub").textContent = reg ? "Create your account" : "Sign in to your account";
      $("aPass").setAttribute("autocomplete", reg ? "new-password" : "current-password");
      setMsg("aErr","");
    });
  });

  $("authForm").addEventListener("submit", async function(ev){
    ev.preventDefault(); setMsg("aErr","");
    var name = $("aName").value.trim(), email = $("aEmail").value.trim().toLowerCase(), pw = $("aPass").value;
    if(!(window.crypto && crypto.subtle)){ setMsg("aErr","This browser can't create secure accounts here."); return; }
    if(authMode === "register" && !name){ setMsg("aErr","Enter your name."); $("aName").focus(); return; }
    if(authMode === "register" && !findCountry($("aCountry").value)){ setMsg("aErr","Select your country so the app can use your currency."); $("aCountry").focus(); return; }
    if(!okEmail(email)){ setMsg("aErr","Enter a valid email address."); $("aEmail").focus(); return; }
    if(pw.length < 8){ setMsg("aErr","Password must be at least 8 characters."); $("aPass").focus(); return; }
    var us = users(), u;
    if(authMode === "register"){
      if(us[email]){ setMsg("aErr","An account with this email already exists. Try signing in."); return; }
      var salt = crypto.getRandomValues(new Uint8Array(16));
      var ct = findCountry($("aCountry").value);
      u = {id:"u" + Date.now().toString(36) + Math.random().toString(36).slice(2,6), name:name, email:email,
        salt:b64(salt), hash:await hashPw(pw, salt), provider:"email", cur:ct ? ct.s : "$", code:ct ? ct.c : "", country:ct ? ct.n : "", budget:0, goal:0, color:AV_COLORS[0]};
      if(!Object.keys(us).length){
        try{
          var lg = JSON.parse(localStorage.getItem("expense-tracker-v1"));
          if(lg && Array.isArray(lg.items)){ localStorage.setItem("et-data-" + u.id, JSON.stringify({items:lg.items})); if(lg.cur && !ct) u.cur = lg.cur; }
        }catch(e){}
      }
      us[email] = u; putUsers(us);
    } else {
      u = us[email];
      if(!u || (await hashPw(pw, unb64(u.salt))) !== u.hash){ setMsg("aErr","Incorrect email or password."); return; }
    }
    $("aPass").value = ""; enter(u);
  });

  $("pForm").addEventListener("submit", function(ev){
    ev.preventDefault(); setMsg("pErr",""); setMsg("pOk","");
    var us = users(), k = myKey(), u = us[k]; if(!u) return;
    var name = $("pName").value.trim(), email = $("pEmail").value.trim().toLowerCase();
    var ctry = findCountry($("pCountry").value), cur = ctry ? ctry.s : (u.cur || "$"), budget = parseFloat($("pBudget").value) || 0, goal = parseFloat($("pGoal").value) || 0;
    if(!name){ setMsg("pErr","Enter your name."); return; }
    if(!okEmail(email)){ setMsg("pErr","Enter a valid email address."); return; }
    if(budget < 0 || goal < 0){ setMsg("pErr","Budget and goal can't be negative."); return; }
    if(email !== k){
      if(us[email]){ setMsg("pErr","Another account already uses that email."); return; }
      delete us[k]; us[email] = u; u.email = email;
    }
    u.name = name; u.cur = cur; if(ctry){ u.country = ctry.n; u.code = ctry.c; } u.budget = budget; u.goal = goal; u.color = pickedColor;
    putUsers(us);
    state.cur = cur; state.code = u.code || ""; state.budget = budget; state.goal = goal; syncConv();
    paintHeader(u); drawAvatars(u); render(); setMsg("pOk","Profile saved.");
  });

  $("pwForm").addEventListener("submit", async function(ev){
    ev.preventDefault(); setMsg("wErr",""); setMsg("wOk","");
    var us = users(), u = us[myKey()]; if(!u) return;
    var cur = $("wCur").value, nw = $("wNew").value;
    if((await hashPw(cur, unb64(u.salt))) !== u.hash){ setMsg("wErr","Current password is incorrect."); return; }
    if(nw.length < 8){ setMsg("wErr","New password must be at least 8 characters."); return; }
    var salt = crypto.getRandomValues(new Uint8Array(16));
    u.salt = b64(salt); u.hash = await hashPw(nw, salt); putUsers(us);
    $("wCur").value = ""; $("wNew").value = ""; setMsg("wOk","Password updated.");
  });

  var delTimer;
  $("delAcc").addEventListener("click", function(){
    var b = this;
    if(b.getAttribute("data-armed") !== "1"){
      b.setAttribute("data-armed","1"); b.textContent = "Click again to permanently delete";
      delTimer = setTimeout(function(){ b.removeAttribute("data-armed"); b.textContent = "Delete account"; }, 5000);
      return;
    }
    clearTimeout(delTimer); b.removeAttribute("data-armed"); b.textContent = "Delete account";
    var us = users(), k = myKey(); if(k){ delete us[k]; putUsers(us); }
    try{ localStorage.removeItem("et-data-" + uid); }catch(e){}
    leave();
  });

  $("avBtn").addEventListener("click", openProfile);
  $("curChip").addEventListener("click", openProfile);
  $("back").addEventListener("click", function(){ showView("dash"); });
  $("signOut").addEventListener("click", leave);

  var txType = "out";
  var CATS = {out:["Food","Transport","Bills","Shopping","Health","Other"], "in":["Salary","Allowance","Business","Gift","Other"]};
  function fillCats(){
    var sel = $("cat"); sel.innerHTML = "";
    CATS[txType].forEach(function(c){ var o = el("option","",c); o.value = c; sel.appendChild(o); });
    $("txGo").textContent = editId ? "Save changes" : (txType === "in" ? "Add money in" : "Add expense");
    $("desc").placeholder = txType === "in" ? "e.g. Salary" : "e.g. Groceries";
  }
  Array.prototype.forEach.call(document.querySelectorAll("#txSeg button"), function(b){
    b.addEventListener("click", function(){
      txType = b.getAttribute("data-t");
      Array.prototype.forEach.call(document.querySelectorAll("#txSeg button"), function(o){
        o.setAttribute("aria-pressed", o === b ? "true" : "false");
      });
      fillCats();
    });
  });
  $("dform").addEventListener("submit", function(ev){
    ev.preventDefault(); setMsg("dErr","");
    var name = $("dName").value.trim(), total = parseFloat($("dTotal").value);
    if(!name){ setMsg("dErr","Enter who or what the debt is for."); $("dName").focus(); return; }
    if(!(total > 0)){ setMsg("dErr","Enter a total amount greater than 0."); $("dTotal").focus(); return; }
    state.debts.push({id:Date.now(), name:name, kind:$("dKind").value, total:Math.round(total*100)/100, paid:0, due:$("dDue").value || ""});
    save(); $("dName").value = ""; $("dTotal").value = ""; $("dDue").value = ""; render();
  });
  fillCats(); fillCountries(); fillConv(); fillCrypto(); fillQa(); fillFilterCats(); fillRecCats(); fillBudgetCats(); $("rStart").value = today();
  addSearch("aCountry","countries"); addSearch("pCountry","countries"); addSearch("cvFrom","currencies"); addSearch("cvTo","currencies");
  addSearch("cCoin","coins"); addSearch("cxFrom","assets"); addSearch("cxTo","assets");

  $("date").value = today();
  $("month").value = today().slice(0,7);
  var sid = null, boot = null;
  try{ sid = localStorage.getItem(SESS); }catch(e){}
  if(sid){ var all = users(); for(var kk in all){ if(all[kk].id === sid) boot = all[kk]; } }
  if(boot) enter(boot); else $("auth").hidden = false;
})();
</script>
</body>
</html>
