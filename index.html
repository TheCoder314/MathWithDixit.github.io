<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta http-equiv="Content-Security-Policy" content="default-src 'none'; script-src 'self' 'unsafe-inline' https://cdnjs.cloudflare.com; style-src 'self' 'unsafe-inline' https://fonts.googleapis.com; font-src https://fonts.gstatic.com; img-src 'self' data: blob:; connect-src 'self'; frame-src 'self'; child-src 'self' blob:; object-src 'none'; base-uri 'none'; form-action 'self'">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="referrer" content="no-referrer">
<meta name="bank-api" content="">
<title>Problem Bank</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700;900&family=STIX+Two+Text:ital,wght@0,400;0,600;1,400&display=swap" rel="stylesheet">
<style>
:root{
  --paper:#F5F7F6; --surface:#FFFFFF; --ink:#1D2A30; --muted:#56666E; --grid:#D3DDE4; --grid-strong:#B7C6D1;
  --blue:#2E5C8A; --blue-ink:#FFFFFF; --blue-soft:#E3ECF4; --yellow:#E0B23A; --yellow-soft:#FBF1D6;
  --red:#B03A48; --red-soft:#F6E4E6;
  --t1:#DCE7F1; --t2:#B9CFE3; --t3:#8FB0CF; --t4:#5F88B3; --t5:#2E5C8A;
  --sans:"Lato", "Segoe UI", system-ui, -apple-system, "Helvetica Neue", Arial, sans-serif;
  --serif:"STIX Two Text", "STIX Two", "Cambria", "Times New Roman", serif;
  box-sizing:border-box;
  padding-top:env(safe-area-inset-top,0px); padding-bottom:env(safe-area-inset-bottom,0px);
  color-scheme:light;
}
@media (prefers-color-scheme: dark){
  :root:not([data-theme="light"]){
    --paper:#131A1E; --surface:#1A2328; --ink:#E3E9EC; --muted:#9BA9B0; --grid:#2B3940; --grid-strong:#3B4C55;
    --blue:#86ADD4; --blue-ink:#0F1A22; --blue-soft:#20303C; --yellow:#E3B94A; --yellow-soft:#3A3120;
    --red:#E27A86; --red-soft:#3A2328;
    --t1:#22313B; --t2:#2E4A61; --t3:#3E6688; --t4:#5886B0; --t5:#86ADD4; color-scheme:dark;
  }
}
:root[data-theme="dark"]{
  --paper:#131A1E; --surface:#1A2328; --ink:#E3E9EC; --muted:#9BA9B0; --grid:#2B3940; --grid-strong:#3B4C55;
  --blue:#86ADD4; --blue-ink:#0F1A22; --blue-soft:#20303C; --yellow:#E3B94A; --yellow-soft:#3A3120;
  --red:#E27A86; --red-soft:#3A2328;
  --t1:#22313B; --t2:#2E4A61; --t3:#3E6688; --t4:#5886B0; --t5:#86ADD4; color-scheme:dark;
}
*,*::before,*::after{box-sizing:inherit}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
html,body{margin:0}
body{background:var(--paper);color:var(--ink);font:15.5px/1.55 var(--sans);-webkit-text-size-adjust:100%}
*{transition:none!important;animation:none!important}
button,input,select{font:inherit;color:inherit}
:focus-visible{outline:2px solid var(--blue);outline-offset:2px}
.nw{white-space:nowrap}
.sr{position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0 0 0 0);white-space:nowrap}

/* header */
.top{border-bottom:1px solid var(--grid);background:var(--surface)}
.top-in{max-width:1180px;margin:0 auto;padding:14px 20px 0;display:flex;flex-wrap:wrap;align-items:flex-end;gap:8px 28px}
.brand{display:flex;align-items:baseline;gap:12px;padding-bottom:12px}
.brand h1{font:700 22px/1 var(--sans);letter-spacing:-.01em;margin:0;white-space:nowrap}
.brand p{margin:0;color:var(--muted);font-size:13px}
.tabs{display:flex;gap:4px;margin-left:auto}
.tab{appearance:none;background:none;border:0;border-bottom:3px solid transparent;padding:8px 12px 10px;font-weight:700;color:var(--muted);cursor:pointer}
.tab[aria-selected="true"]{color:var(--ink);border-bottom-color:var(--blue)}
.tab .count[hidden]{display:none}
.tab .count{display:inline-block;min-width:20px;padding:0 6px;margin-left:6px;border-radius:10px;background:var(--yellow-soft);color:var(--ink);font-size:12px;line-height:20px;text-align:center}

main{max-width:1180px;margin:0 auto;padding:20px}
.view[hidden]{display:none}

/* browse */
.browse{display:grid;grid-template-columns:230px minmax(0,1fr);gap:32px}
.rail{position:sticky;top:12px;align-self:start;max-height:calc(100vh - 24px);overflow:auto;padding-right:4px}
.rail h2,.panel h2{font:700 13px/1.3 var(--sans);color:var(--muted);margin:18px 0 8px}
.rail h2:first-child{margin-top:0}
.check{display:flex;align-items:center;gap:8px;padding:3px 0;font-size:14px;cursor:pointer}
.cols .check{gap:6px;padding:2px 0}
.check input{width:16px;height:16px;accent-color:var(--blue);margin:0}
.check .n{margin-left:auto;color:var(--muted);font-size:12px;font-variant-numeric:tabular-nums}
.check.off{color:var(--muted)}
.tiers{display:flex;gap:4px}
.tierbtn{flex:1;appearance:none;border:1px solid var(--grid-strong);background:var(--surface);padding:6px 0;border-radius:4px;font-weight:700;cursor:pointer;font-variant-numeric:tabular-nums}
.tierbtn[aria-pressed="true"]{background:var(--blue);border-color:var(--blue);color:var(--blue-ink)}
.search{width:100%;padding:7px 10px;border:1px solid var(--grid-strong);border-radius:4px;background:var(--surface)}
.seg{display:flex;border:1px solid var(--grid-strong);border-radius:4px;overflow:hidden}
.seg button{flex:1;appearance:none;border:0;background:var(--surface);padding:6px 4px;font-size:13px;cursor:pointer}
.seg button+button{border-left:1px solid var(--grid-strong)}
.seg button[aria-pressed="true"]{background:var(--blue-soft);font-weight:700}
.linkbtn{appearance:none;background:none;border:0;padding:0;color:var(--blue);font-weight:700;cursor:pointer;text-decoration:underline;text-underline-offset:3px}
.resultbar{display:flex;align-items:center;gap:12px;padding-bottom:10px;border-bottom:2px solid var(--ink);flex-wrap:wrap}
.resultbar strong{font-size:17px}
.resultbar select{margin-left:auto;padding:5px 8px;border:1px solid var(--grid-strong);border-radius:4px;background:var(--surface)}
.filtertoggle{display:none}

/* problem entry, laid out like a test booklet */
.prob{display:grid;grid-template-columns:46px minmax(0,1fr);gap:0 14px;padding:22px 0;border-bottom:1px solid var(--grid)}
.num{font:700 20px/1 var(--sans);font-variant-numeric:tabular-nums;padding-top:3px;text-align:right}
.src{font-size:13px;color:var(--muted);display:flex;flex-wrap:wrap;gap:4px 14px;align-items:center}
.skill{margin:6px 0 10px;font-size:14px}
.topic{display:inline-block;background:var(--blue-soft);padding:1px 8px;border-radius:3px;font-weight:700;font-size:12.5px;margin-right:8px}
.setup{border-left:3px solid var(--grid-strong);padding:4px 0 4px 12px;margin:0 0 12px;font:16px/1.6 var(--serif);color:var(--ink)}
.stmt{font:17px/1.62 var(--serif);max-width:72ch}
.fig{margin:14px 0 4px;color:var(--ink)}
.fig svg{max-width:100%;height:auto;display:block}
.choices{list-style:none;margin:14px 0 0;padding:0;display:grid;grid-template-columns:repeat(auto-fill,minmax(118px,1fr));gap:8px 16px}
.choices.long{grid-template-columns:1fr}
.choice{display:flex;align-items:center;gap:10px;font:16px/1.4 var(--serif);min-height:30px}
.bub{flex:none;width:26px;height:26px;border-radius:50%;border:1.5px solid var(--grid-strong);display:grid;place-items:center;font:700 12.5px/1 var(--sans);color:var(--muted);background:var(--surface)}
.prob.show .choice.right .bub{background:var(--blue);border-color:var(--blue);color:var(--blue-ink)}
.prob.show .choice.trap .bub{border:2px solid var(--red);color:var(--red);box-shadow:0 0 0 3px var(--red-soft)}
.meta{display:flex;flex-wrap:wrap;align-items:flex-end;gap:12px 24px;margin-top:16px}
.actions{display:flex;gap:8px;margin-left:auto}
.btn{appearance:none;border:1px solid var(--grid-strong);background:var(--surface);padding:7px 12px;border-radius:4px;font-weight:700;font-size:14px;cursor:pointer}
.btn:hover{border-color:var(--ink)}
.btn.primary{background:var(--blue);border-color:var(--blue);color:var(--blue-ink)}
.btn[aria-pressed="true"]{background:var(--yellow-soft);border-color:var(--yellow)}
.btn[disabled]{opacity:.5;cursor:not-allowed}
.answer{margin-top:14px;padding:12px 14px;background:var(--blue-soft);border-radius:4px;font:15.5px/1.6 var(--serif)}
.answer b{font-family:var(--sans);font-size:14px}
.answer .trapnote{margin-top:10px;padding-top:10px;border-top:1px solid var(--grid-strong)}
.answer .trapnote b{color:var(--red)}
.notice{margin-top:10px;font-size:14px;padding:8px 12px;border-left:3px solid var(--yellow);background:var(--yellow-soft)}
.tag{display:inline-block;font-size:12px;font-weight:700;padding:0 7px;border-radius:3px;line-height:20px}
.tag.trap{color:var(--red);border:1px solid var(--red)}
.tag.thrown{color:var(--ink);background:var(--yellow-soft);border:1px solid var(--yellow)}

/* percentile ruler */
.diff{min-width:250px;flex:1;max-width:360px}
.diff-head{display:flex;align-items:baseline;gap:8px;font-size:13px;margin-bottom:5px}
.diff-head strong{font-size:14px}
.diff-head span{color:var(--muted)}
.ruler{position:relative;display:flex;height:14px;border:1px solid var(--grid-strong);border-radius:2px;overflow:visible}
.ruler i{display:block;height:100%}
.ruler i+i{border-left:1px solid var(--surface)}
.notch{position:absolute;top:-5px;bottom:-5px;width:3px;margin-left:-1.5px;background:var(--ink);border-radius:1px}
.notch.beyond{width:9px;margin-left:-3px;background:repeating-linear-gradient(90deg,var(--ink) 0 3px,transparent 3px 6px)}
.ruler-scale{position:relative;height:16px;font-size:11px;color:var(--muted);font-variant-numeric:tabular-nums}
.ruler-scale span{position:absolute;transform:translateX(-50%);top:2px}
.diff-foot{font-size:12.5px;color:var(--muted);font-variant-numeric:tabular-nums}

.empty{padding:40px 0;color:var(--muted)}

/* build */
.build{display:grid;grid-template-columns:minmax(0,340px) minmax(0,1fr);gap:32px}
.panel{background:var(--surface);border:1px solid var(--grid);border-radius:4px;padding:18px 20px 0}
.panel-actions{position:sticky;bottom:0;background:var(--surface);border-top:1px solid var(--grid);margin:0 -20px;padding:12px 20px 16px}
.field{margin-bottom:14px}
.field label.lbl{display:block;font-weight:700;font-size:14px;margin-bottom:6px}
.field input[type=text],.field input[type=number]{width:100%;padding:7px 10px;border:1px solid var(--grid-strong);border-radius:4px;background:var(--paper)}
.cols{columns:2;column-gap:12px;font-size:13.5px}
.cols .check{break-inside:avoid}
.hint{font-size:13px;color:var(--muted);margin:4px 0 0}
.status{font-size:14px;margin:10px 0 0;min-height:21px}
.status.err{color:var(--red)}
.setlist{list-style:none;padding:0;margin:0;counter-reset:s}
.setitem{display:grid;grid-template-columns:34px minmax(0,1fr) auto;gap:10px;padding:14px 0;border-bottom:1px solid var(--grid);align-items:start}
.setitem .num{font-size:16px}
.setitem .stmt{font-size:15.5px}
.setitem .src{margin-top:4px}
.mini{display:flex;flex-direction:column;gap:6px}
.mini .btn{padding:4px 10px;font-size:13px}
.minitier{display:inline-flex;align-items:center;gap:6px}
.minitier i{display:inline-block;width:10px;height:10px;border-radius:2px;border:1px solid var(--grid-strong)}
.set-head{position:sticky;top:0;z-index:2;background:var(--paper);display:flex;flex-wrap:wrap;gap:12px;align-items:center;padding:6px 0 10px;border-bottom:2px solid var(--ink)}
.set-head .actions{margin-left:auto}

/* data */
.data{max-width:760px}
.data h2{font:700 18px/1.3 var(--sans);margin:26px 0 8px}
.data h2:first-child{margin-top:0}
.data p{margin:0 0 10px;max-width:68ch}
table{border-collapse:collapse;width:100%;font-size:14px;font-variant-numeric:tabular-nums}
th,td{text-align:left;padding:7px 10px;border-bottom:1px solid var(--grid)}
th{font-weight:700;color:var(--muted);font-size:13px}
.tablewrap{overflow-x:auto}
.legend{display:flex;flex-wrap:wrap;gap:6px 18px;font-size:13.5px}
.legend span{display:inline-flex;align-items:center;gap:6px}
.legend i{width:14px;height:14px;border-radius:2px;display:inline-block;border:1px solid var(--grid-strong)}

/* pdf staging area: fixed print colors, off screen */
#stage{position:fixed;left:-10000px;top:0;width:720px;background:#fff;color:#1D2A30}
#stage *{color:#1D2A30}
.pb{padding:10px 0 14px;display:grid;grid-template-columns:34px 1fr;gap:0 10px;font:15px/1.55 var(--serif)}
.pb .pn{font:700 15px/1.5 var(--sans)}
.pb .pch{display:flex;flex-wrap:wrap;gap:4px 22px;margin-top:8px}
.pb .pch.long{flex-direction:column}
.pb .ptier{font:12px/1.3 var(--sans);color:#56666E;margin-top:6px}
.pb .psetup{border-left:3px solid #B7C6D1;padding-left:10px;margin-bottom:8px}
.ph{padding:0 0 14px;border-bottom:2px solid #1D2A30;margin-bottom:6px;font-family:var(--sans)}
.ph h1{font:700 24px/1.2 var(--sans);margin:0 0 6px}
.ph p{margin:2px 0;font-size:13px;color:#56666E}
.ph .name{margin-top:14px;font-size:14px;color:#1D2A30}
.kh{font:700 18px/1.3 var(--sans);padding:6px 0 10px;border-bottom:2px solid #1D2A30}
.kb{display:grid;grid-template-columns:34px 30px 1fr;gap:0 10px;padding:7px 0;border-bottom:1px solid #D3DDE4;font:14px/1.5 var(--serif)}
.kb .kn,.kb .ka{font:700 14px/1.5 var(--sans)}
.kb .ks{font:12px/1.4 var(--sans);color:#56666E}

@media (max-width:760px){
  .build{grid-template-columns:1fr}
}
@media (max-width:860px){
  .browse{grid-template-columns:1fr}
  .rail{position:static;max-height:none;display:none;border-bottom:1px solid var(--grid);padding-bottom:12px}
  .rail.open{display:block}
  .filtertoggle{display:inline-block}
  .tabs{margin-left:0;width:100%}
  .prob{grid-template-columns:30px minmax(0,1fr);gap:0 10px}
  .num{font-size:17px}
  .actions{margin-left:0}
  .diff{max-width:none}
}
@media (max-width:480px){ .brand p{display:none} .tab{padding:8px 10px 10px} }
@media print{ .top,.rail,.actions{display:none} }
/* ===== comfort pass: cards, bigger targets, calmer rhythm ===== */
body{font-size:16px;line-height:1.6}
main{padding:28px 24px 64px}
.top-in{padding:16px 24px 0}
.tab{padding:10px 14px 12px;font-size:15px}
.btn{min-height:40px;padding:0 16px;border-radius:8px;font-size:14.5px;display:inline-flex;align-items:center;justify-content:center;gap:6px}
.btn.quiet{background:transparent}
.btn.primary{min-height:44px;padding:0 22px;font-size:15px}
.search,.field input[type=text],.field input[type=number],.resultbar select{min-height:40px;border-radius:8px}
.tierbtn{min-height:38px;border-radius:8px}
.seg{border-radius:8px}

/* filters as a soft panel */
.browse{gap:28px}
.rail{background:var(--surface);border:1px solid var(--grid);border-radius:12px;padding:18px 18px 12px;top:16px}
.rail h2,.panel h2{font-size:12px;letter-spacing:.04em;text-transform:uppercase;margin:20px 0 8px}
.check{padding:4px 0}

.resultbar{border-bottom:0;padding:2px 2px 14px;align-items:baseline}
.resultbar strong{font-size:20px}
.session{font-size:14px;color:var(--muted);background:var(--surface);border:1px solid var(--grid);border-radius:999px;padding:2px 12px}
#list{display:flex;flex-direction:column;gap:16px}

/* problem cards */
.prob{display:block;background:var(--surface);border:1px solid var(--grid);border-radius:12px;padding:22px 26px 18px;border-bottom:1px solid var(--grid)}
.card-head{display:flex;flex-wrap:wrap;align-items:center;gap:6px 12px;margin-bottom:10px}
.qnum{font:700 15px/1 var(--sans);color:var(--ink);background:var(--paper);border:1px solid var(--grid);border-radius:6px;padding:5px 8px;font-variant-numeric:tabular-nums}
.card-head .src{font-size:14px;color:var(--muted)}
.tierchip{margin-left:auto;display:inline-flex;align-items:center;gap:7px;font-size:13px;font-weight:700;color:var(--ink);border:1px solid var(--grid);border-radius:999px;padding:3px 11px 3px 9px}
.tierchip::before{content:"";width:10px;height:10px;border-radius:3px;border:1px solid var(--grid-strong)}
.tierchip.t1::before{background:var(--t1)}.tierchip.t2::before{background:var(--t2)}.tierchip.t3::before{background:var(--t3)}.tierchip.t4::before{background:var(--t4)}.tierchip.t5::before{background:var(--t5)}
.skill{margin:0 0 14px;display:flex;flex-wrap:wrap;align-items:center;gap:6px 10px}
.topic{border-radius:6px;padding:2px 9px;margin:0}
.skilltext{font-size:14.5px;color:var(--muted)}
.stmt{font-size:18px;line-height:1.65}
.setup{border-left:0;background:var(--paper);border-radius:8px;padding:12px 16px;margin:0 0 14px;font-size:16px}

/* answer choices are buttons */
.choices{list-style:none;margin:18px 0 0;padding:0;display:grid;grid-template-columns:repeat(auto-fill,minmax(150px,1fr));gap:10px}
.choices.long{grid-template-columns:1fr}
.choice{appearance:none;display:flex;align-items:center;gap:12px;width:100%;min-height:52px;padding:8px 14px;text-align:left;
  background:var(--paper);border:1px solid var(--grid-strong);border-radius:10px;cursor:pointer;font:17px/1.4 var(--serif);color:var(--ink)}
.choice:hover:not(:disabled){border-color:var(--ink);background:var(--surface)}
.choice:focus-visible{outline:2px solid var(--blue);outline-offset:2px}
.choice:disabled{cursor:default}
.choice .bub{width:30px;height:30px;font-size:13px;flex:none}
.prob.solved .choice:not(.right){opacity:.55}
.choice.selected{border:2px solid var(--ink);padding:7px 13px;background:var(--surface)}
.choice.selected .bub{background:var(--ink);border-color:var(--ink);color:var(--surface)}
.choice.wrong:disabled{cursor:not-allowed}
.submit-row{display:flex;align-items:center;gap:14px;margin-top:14px}
.submit-row[hidden]{display:none}
.submit-row .tries{font-size:14px;color:var(--muted)}
.choice.right,.prob.show .choice.right{border-color:var(--blue);background:var(--blue-soft);opacity:1}
.choice.right .bub,.prob.show .choice.right .bub{background:var(--blue);border-color:var(--blue);color:var(--blue-ink)}
.choice.wrong{border-color:var(--red);background:var(--red-soft);opacity:1}
.choice.wrong .bub{background:var(--red);border-color:var(--red);color:#fff}

.feedback{margin-top:14px;padding:12px 16px;border-radius:10px;font-size:15.5px;border:1px solid var(--grid)}
.feedback.good{background:var(--blue-soft);border-color:var(--blue)}
.feedback.bad{background:var(--red-soft);border-color:var(--red)}
.feedback.neutral{background:var(--yellow-soft);border-color:var(--yellow)}
.feedback .trapline{font-weight:700}
.answer{border-radius:10px;padding:14px 18px;margin-top:12px}
.notice{border-radius:8px;margin-top:12px}

.card-foot{display:flex;flex-wrap:wrap;align-items:flex-end;gap:14px 24px;margin-top:18px;padding-top:14px;border-top:1px solid var(--grid)}
.card-foot .actions{margin-left:auto;display:flex;gap:8px}
.card-foot .diff{max-width:420px}
.filtertoggle{display:none!important}
.stmt,.setup,.answer,.feedback,.ctext,.setitem .stmt{max-width:100%;overflow-x:auto;overflow-y:hidden}
.choice{min-width:0}
mjx-container[display="true"]{max-width:100%;overflow-x:auto;overflow-y:hidden}
.diff-head{font-size:13px}

/* build + data */
.panel{border-radius:12px}
.setitem{background:var(--surface);border:1px solid var(--grid);border-radius:12px;padding:14px 16px;margin-bottom:10px;grid-template-columns:34px minmax(0,1fr) auto}
.setlist{margin-top:12px}
.data{background:var(--surface);border:1px solid var(--grid);border-radius:12px;padding:24px 28px}
#view-admin select,#view-admin input[type=password],#view-admin input[type=number],#view-admin input[type=text]{width:100%;max-width:420px;min-height:40px;padding:6px 10px;border:1px solid var(--grid-strong);border-radius:8px;background:var(--paper)}

@media (max-width:860px){
  .browse,.build{grid-template-columns:minmax(0,1fr)!important}
  .prob,.resultbar,#list{min-width:0;max-width:100%}
  .resultbar select{margin-left:0}
  .filtertoggle{display:inline-flex!important}
  .rail{border-radius:12px;margin-bottom:8px}
  .prob{padding:18px 16px 14px;border-radius:12px}
  .stmt{font-size:17px}
  .choices{grid-template-columns:1fr 1fr}
  .choices.long{grid-template-columns:1fr}
  .card-foot .actions{margin-left:0;width:100%}
  .card-foot .actions .btn{flex:1}
  .card-foot .diff{max-width:none;width:100%}
  main{padding:18px 14px 48px}
  .data{padding:18px 16px}
}

</style>
</head>
<body>
<header class="top">
  <div class="top-in">
    <div class="brand">
      <h1>Problem Bank</h1>
      <p>Past FAMAT tests, sorted by skill and measured difficulty</p>
    </div>
    <nav class="tabs" role="tablist" aria-label="Sections">
      <button class="tab" role="tab" id="tab-browse" aria-controls="view-browse" aria-selected="true">Browse</button>
      <button class="tab" role="tab" id="tab-build" aria-controls="view-build" aria-selected="false">Build a set<span class="count" id="pincount" hidden></span></button>
      <button class="tab" role="tab" id="tab-data" aria-controls="view-data" aria-selected="false">Data</button>
    </nav>
  </div>
</header>

<main>
  <section class="view" id="view-browse" role="tabpanel" aria-labelledby="tab-browse">
    <div class="browse">
      <aside class="rail" id="rail" aria-label="Filters"></aside>
      <div>
        <div class="resultbar">
          <strong id="resultcount"></strong>
          <span class="session" id="session" hidden></span>
          <button class="btn filtertoggle" id="filtertoggle" aria-expanded="false" aria-controls="rail">Filters</button>
          <label class="sr" for="sort">Sort problems</label>
          <select id="sort">
            <option value="test">Test order</option>
            <option value="easy">Easiest first</option>
            <option value="hard">Hardest first</option>
          </select>
        </div>
        <div id="list"></div>
      </div>
    </div>
  </section>

  <section class="view" id="view-build" role="tabpanel" aria-labelledby="tab-build" hidden>
    <div class="build">
      <form class="panel" id="buildform" autocomplete="off" novalidate>
        <div class="field">
          <label class="lbl" for="settitle">Title</label>
          <input type="text" id="settitle" maxlength="80" value="Practice set">
        </div>
        <div class="field">
          <span class="lbl" style="font-weight:700;font-size:14px;display:block;margin-bottom:6px">Divisions</span>
          <div id="b-divs"></div>
        </div>
        <div class="field">
          <span style="font-weight:700;font-size:14px;display:block;margin-bottom:6px">Topics</span>
          <div class="cols" id="b-topics"></div>
          <p class="hint"><button type="button" class="linkbtn" id="b-alltopics">Select all</button> &nbsp; <button type="button" class="linkbtn" id="b-notopics">Clear</button></p>
        </div>
        <div class="field">
          <span style="font-weight:700;font-size:14px;display:block;margin-bottom:6px">Difficulty tiers</span>
          <div class="tiers" id="b-tiers"></div>
          <p class="hint">Tier 1 is solvable by half the field; tier 5 by fewer than 1 in 50.</p>
        </div>
        <div class="field">
          <label class="lbl" for="b-count">Number of problems</label>
          <input type="number" id="b-count" min="1" max="60" value="10" inputmode="numeric">
          <p class="hint" id="b-pool"></p>
        </div>
        <div class="field">
          <span style="font-weight:700;font-size:14px;display:block;margin-bottom:6px">Order</span>
          <div class="seg" id="b-order">
            <button type="button" data-v="easy" aria-pressed="true">Easiest first</button>
            <button type="button" data-v="topic" aria-pressed="false">By topic</button>
            <button type="button" data-v="random" aria-pressed="false">Random</button>
          </div>
        </div>
        <div class="field">
          <label class="check"><input type="checkbox" id="b-spread" checked> Spread evenly across topics</label>
          <label class="check"><input type="checkbox" id="b-traps"> Traps only</label>
          <label class="check"><input type="checkbox" id="b-key" checked> Answer key at the end</label>
          <label class="check"><input type="checkbox" id="b-ideas" checked> Key ideas in the answer key</label>
          <label class="check"><input type="checkbox" id="b-tierlabels"> Show difficulty tiers in the PDF</label>
        </div>
        <div class="panel-actions">
          <button type="submit" class="btn primary">Generate set</button>
          <p class="status" id="b-status" role="status"></p>
        </div>
      </form>
      <div>
        <div class="set-head">
          <strong id="set-title">No set yet</strong>
          <div class="actions">
            <button class="btn" id="set-clear" type="button" disabled>Clear set</button>
            <button class="btn primary" id="set-pdf" type="button" disabled>Download PDF</button>
          </div>
        </div>
        <p class="status" id="pdf-status" role="status"></p>
        <ol class="setlist" id="setlist"></ol>
        <p class="empty" id="set-empty">Pick topics and tiers, then generate a set. Problems you add from Browse appear here first.</p>
      </div>
    </div>
  </section>

  <section class="view data" id="view-data" role="tabpanel" aria-labelledby="tab-data" hidden></section>
</main>

<div id="stage" aria-hidden="true"></div>

<script>
window.MathJax = {
  loader: { load: ['ui/safe'] },
  tex: { inlineMath: [['\\(', '\\)']], displayMath: [['\\[', '\\]']], packages: {'[-]': ['html', 'require']}, maxMacros: 200, maxBuffer: 20 * 1024 },
  svg: { fontCache: 'none' },
  options: { enableMenu: false, safeOptions: { allow: { URLs: 'none', classes: 'none', cssIDs: 'none', styles: 'none' } } },
  startup: { typeset: false, ready() { MathJax.startup.defaultReady(); window.__mathReady && window.__mathReady(); } }
};
</script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/3.2.2/es5/tex-svg.js" async></script>
<script>
"use strict";
const BANK = {"version":1,"fields":{"2026":{"n":0,"mean":0.0},"2025":{"n":0,"mean":0.0},"2024":{"n":0,"mean":0.0}},"setups":{"2024-circleO":{"text":"For Questions 4–6, circle \\(O\\) passes through \\(A=(4,-2)\\), \\(B=(5,-1)\\), and \\(C=(6,2)\\).","fig":null},"2024-p5":{"text":"For Questions 7 and 8, let \\(p\\) be the largest positive integer such that \\(5^p\\) is a factor of \\(2024!\\).","fig":null},"2024-walk":{"text":"For Questions 18 and 19: Oliver begins at point \\(A\\) of the graph shown. Each move, he chooses uniformly at random one of the paths available to him and travels to the point on the other side. Let \\[M_1=\\frac13\\begin{bmatrix}0&1&1&1\\\\1&0&1&0\\\\1&1&0&1\\\\1&0&1&0\\end{bmatrix},\\qquad M_2=\\frac1{10}\\begin{bmatrix}0&4&2&4\\\\5&0&5&0\\\\2&4&0&4\\\\5&0&5&0\\end{bmatrix}.\\]","fig":"graphABCD"},"2026-stat-jurassic":{"text":"For Questions 2–6: the Box Office Gross Sale (in millions of USD) and mean NumberCubed rating of all full-length Jurassic Park films, rounded to the nearest integer. \\[\\begin{array}{l|ccccccc}\\text{Movie}&\\text{JP}&\\text{Lost World}&\\text{JP III}&\\text{JW}&\\text{Fallen Kingdom}&\\text{Dominion}&\\text{Rebirth}\\\\\\hline \\text{Gross (mil)}&1114&619&369&1672&1308&1002&418\\\\ \\text{Mean Rating}&31&29&12&46&34&31&27\\end{array}\\]","fig":null},"2026-stat-ark":{"text":"For Questions 8–11: from 33 randomly sampled dinosaurs, Sihwan fit a least-squares regression line predicting the number of pieces of food needed to tame a dinosaur (\\(y\\)) from its hunger level (\\(x\\)). Assume all conditions for inference are satisfied. \\[\\begin{array}{l|cccc}\\text{Predictor}&\\text{Coef}&\\text{SE Coef}&T&P\\\\\\hline\\text{Constant}&3.05849&0.87423&3.49850&0.00144\\\\ \\text{Hunger Level}&0.03777&0.01541&2.45030&0.02012\\end{array}\\] \\(S=2.52930\\), R-sq \\(=16.2\\%\\), R-sq (adj) \\(=10.6\\%\\).","fig":null},"2026-stat-lila":{"text":"For Questions 14–17: Lila wants to know \\(p\\), the proportion of MAO competitors who know which era the dinosaurs lived in (Mesozoic), and whether it is less than 0.6. She samples \\(n=30\\) competitors and finds \\(\\hat p=0.4\\). Assume all conditions for inference are met.","fig":null},"2026-stat-sam":{"text":"For Questions 18–21: Sam samples competitors at the MAO State Convention and asks which dinosaur show they prefer, The Land Before Time (LBT) or Dinosaur Train (DT), and which geologic era their favorite character is from. \\[\\begin{array}{l|cccc}\\text{Character's Era}&\\text{Triassic}&\\text{Jurassic}&\\text{Cretaceous}&\\text{Total}\\\\\\hline \\text{LBT}&6&11&26&43\\\\ \\text{DT}&7&12&43&62\\\\ \\text{Total}&13&23&69&105\\end{array}\\]","fig":null},"2026-stat-lacko":{"text":"For Questions 22–29: paleontologists ask whether coastal Lackosaurs had wider toes than inland ones, so that the mean coastal fossil toe width would be larger than the mean inland fossil toe width. Only four data values survive. Coastal toe width (in): 2.3, 2.5. Inland toe width (in): 2.4, 2.2.","fig":null},"2026-stat-perm":{"text":"For Questions 23–26: the paleontologists run a permutation test with \\(\\alpha=0.20\\). Its null hypothesis is that all samples come from the same distribution. The data is pooled, then shuffled and split into two groups of the original sizes; the test statistic is the difference in means (Coastal \\(-\\) Inland), computed for every possible grouping. The p-value compares the original test statistic to that distribution.","fig":null},"2026-stat-chisqdist":{"text":"For Questions 27–29: for a sample of size \\(n\\) from a Normal distribution with variance \\(\\sigma^2\\), the quantity \\(\\frac{(n-1)S^2}{\\sigma^2}\\) follows a \\(\\chi^2_{n-1}\\) distribution. Suppose Lackosaur toe widths do not differ by region and are Normal with \\(\\mu=2.25\\) in and \\(\\sigma=0.11\\) in, so the four observations pool into one sample: 2.2, 2.3, 2.4, 2.5.","fig":null},"2026-stat-chitable":{"text":"A \\(\\chi^2\\) table of lower-tail probabilities \\(P(\\chi^2_{df}\\le X)\\) is provided with the test. \\[\\begin{array}{c|ccccccccc}df&0.01&0.05&0.10&0.20&0.50&0.80&0.90&0.95&0.99\\\\\\hline 1&0.0002&0.0039&0.0158&0.0642&0.4549&1.6424&2.7055&3.8415&6.6349\\\\ 2&0.0201&0.1026&0.2107&0.4463&1.3863&3.2189&4.6052&5.9915&9.2103\\\\ 3&0.1148&0.3518&0.5844&1.0052&2.3660&4.6416&6.2514&7.8147&11.3449\\\\ 4&0.2971&0.7107&1.0636&1.6488&3.3567&5.9886&7.7794&9.4877&13.2767\\\\ 5&0.5543&1.1455&1.6103&2.3425&4.3515&7.2893&9.2364&11.0705&15.0863\\end{array}\\] (The full table runs to \\(df=10\\).)","fig":null},"2026-theta-ev":{"text":"For Questions 25–28: the expected value of a random variable with finitely many outcomes is the weighted average of the outcomes, \\(E[X]=\\sum_{i=1}^{n}x_ip_i\\), where each outcome \\(x_i\\) has probability \\(p_i\\).","fig":null}},"problems":[{"id":"2026-states-alpha-ind-01","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":1,"topic":"Number theory","skill":"Counting multiples in an interval","q":"For how many positive integer values of \\(k\\) are both \\(\\frac{k}{3}\\) and \\(3k\\) three-digit integers?","ch":["12","27","33","34"],"a":"A","idea":"\\(\\frac k3\\ge100\\) gives \\(k\\ge300\\); \\(3k\\le999\\) gives \\(k\\le333\\). \\(k\\) must also be a multiple of 3: \\(300,303,\\dots,333\\), which is 12 values.","trap":{"choice":"D","why":"Counted every integer from 300 to 333 without requiring \\(\\frac k3\\) to be an integer."},"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":97,"B":9,"C":24,"D":63,"E":7,"blank":38},"pc":40.8,"pa":84.0,"top":79,"pct":69.9,"tier":2,"disc":0.74,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-alpha-ind-02","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":2,"topic":"Trigonometry","skill":"Counting solutions of sin x = ±c","q":"How many triangles have area 10 and vertices \\((-5,0)\\), \\((5,0)\\), and \\((5\\cos x,\\,5\\sin x)\\) for some \\(x\\in[0,2\\pi)\\)?","ch":["2","3","4","6"],"a":"C","idea":"The base is 10, so the height is 2: \\(|5\\sin x|=2\\). Each of \\(\\sin x=\\pm\\frac25\\) has two solutions, giving 4 triangles.","trap":{"choice":"A","why":"Only used \\(\\sin x=+\\frac25\\), forgetting the triangles below the axis."},"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":55,"B":14,"C":85,"D":6,"E":1,"blank":77},"pc":35.7,"pa":67.6,"top":86,"pct":73.2,"tier":2,"disc":1.03,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-alpha-ind-03","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":3,"topic":"Number theory","skill":"Factoring factorials","q":"The sum of the 3 largest prime divisors of \\(15!-13!\\) is \\(X\\). What is the sum of the digits of \\(X\\)?","ch":["7","8","15","16"],"a":"A","idea":"\\(15!-13!=13!\\,(15\\cdot14-1)=13!\\cdot209=13!\\cdot11\\cdot19\\). The largest primes are 19, 13, 11, so \\(X=43\\) and the digit sum is 7.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":62,"B":41,"C":22,"D":16,"E":8,"blank":89},"pc":26.1,"pa":62.6,"top":89,"pct":84.6,"tier":3,"disc":1.24,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-alpha-ind-04","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":4,"topic":"Counting & probability","skill":"Stopping-rule probability","q":"A bin contains 3 red marbles and 2 green marbles. Marbles are drawn randomly, one at a time without replacement, until all 3 reds are drawn or until both greens are drawn. What is the probability that the 3 reds are drawn?","ch":["\\(\\frac{3}{10}\\)","\\(\\frac25\\)","\\(\\frac12\\)","\\(\\frac35\\)"],"a":"B","idea":"Imagine drawing all 5. The reds finish first exactly when the last marble is green, which has probability \\(\\frac25\\).","trap":{"choice":"A","why":"Only counted the sequence RRR, ignoring orders where a green comes before the third red."},"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":58,"B":66,"C":16,"D":22,"E":17,"blank":59},"pc":27.7,"pa":75.2,"top":57,"pct":96.6,"tier":4,"disc":0.55,"noisy":false,"extrap":false},"kind":"trap"},{"id":"2026-states-alpha-ind-05","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":5,"topic":"Functions & algebra","skill":"Domain of a composition","q":"If \\(g(x)=\\sqrt{\\frac{x}{x-1}}\\) and \\(f(x)=\\log_3(x-1)\\), find the sum of the integers less than or equal to 10 that are in the domain of \\(g(f(x))\\).","ch":["45","47","50","51"],"a":"B","idea":"Need \\(x>1\\) and \\(\\frac{f}{f-1}\\ge0\\): \\(f\\le0\\) or \\(f>1\\), so \\(1<x\\le2\\) or \\(x>4\\). The integers are 2 and 5 through 10, summing to 47.","trap":{"choice":"A","why":"Missed \\(x=2\\): there \\(f(2)=0\\) and \\(g(0)=0\\) is defined."},"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":65,"B":39,"C":33,"D":12,"E":20,"blank":69},"pc":16.4,"pa":71.0,"top":32,"pct":99.9,"tier":5,"disc":0.36,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2026-states-alpha-ind-06","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":6,"topic":"Geometry","skill":"Tangent radius via similar triangles","q":"A semicircle is inscribed in an isosceles triangle with base 16 and height 15 so that the diameter of the semicircle lies on the base of the triangle. What is the radius of the semicircle?","ch":["\\(4\\sqrt3\\)","\\(\\frac{17\\sqrt3}{2}\\)","\\(\\frac{64}{17}\\)","\\(\\frac{120}{17}\\)"],"a":"D","idea":"Half the triangle is an 8-15-17 right triangle. The radius is the distance from the base's midpoint to a leg: \\(r=\\frac{8\\cdot15}{17}=\\frac{120}{17}\\).","trap":null,"note":null,"setup":null,"fig":"semicircle","stats":{"n":238,"dist":{"A":16,"B":25,"C":22,"D":62,"E":10,"blank":103},"pc":26.1,"pa":56.7,"top":89,"pct":79.6,"tier":3,"disc":1.65,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-alpha-ind-07","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":7,"topic":"Trigonometry","skill":"Double-angle compression","q":"Given \\(8\\sin^5 k\\cos k+1-8\\sin k\\cos^5 k=0\\), find the smallest positive angle \\(k\\), in degrees, that satisfies the equation.","ch":["7.5","15","37.5","75"],"a":"A","idea":"\\(8\\sin k\\cos k(\\cos^4k-\\sin^4k)=4\\sin2k\\cos2k=2\\sin4k=1\\), so \\(4k=30^\\circ\\) and \\(k=7.5^\\circ\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":55,"B":18,"C":31,"D":7,"E":6,"blank":121},"pc":23.1,"pa":49.2,"top":82,"pct":85.2,"tier":3,"disc":1.51,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-alpha-ind-08","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":8,"topic":"Conics","skill":"Parabola from focus and directrix","q":"Let \\(\\mathcal L\\) be the locus of points equidistant from the point \\((-1,0)\\) and the line \\(x=3\\). If \\((M,4)\\) is on \\(\\mathcal L\\), compute \\(M\\).","ch":["\\(-3\\)","\\(-1\\)","\\(4\\sqrt2-1\\)","\\(4\\sqrt2+1\\)"],"a":"B","idea":"Set the distances equal: \\((M+1)^2+16=(3-M)^2\\), so \\(8M=-8\\) and \\(M=-1\\). (The parabola opens left, with vertex \\((1,0)\\).)","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":12,"B":78,"C":33,"D":13,"E":5,"blank":97},"pc":32.8,"pa":59.2,"top":86,"pct":73.2,"tier":2,"disc":1.34,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-alpha-ind-09","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":9,"topic":"Trigonometry","skill":"Law of Cosines","q":"One side of a triangle is twice another side, and the third side has length 6. If 6 is the longest side and one angle is \\(120^\\circ\\), the product of the other two sides is \\(\\frac LU\\) in lowest terms. Compute \\(L+U\\).","ch":["41","55","75","79"],"a":"D","idea":"The \\(120^\\circ\\) angle is opposite 6: \\(36=x^2+4x^2+2x^2=7x^2\\). The product is \\(2x^2=\\frac{72}{7}\\), so \\(L+U=79\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":7,"B":11,"C":20,"D":75,"E":9,"blank":116},"pc":31.5,"pa":51.3,"top":93,"pct":68.9,"tier":2,"disc":1.94,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-alpha-ind-10","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":10,"topic":"Polynomials","skill":"Descartes' Rule of Signs","q":"It is known that \\(f(x)=3x^2+x^3-x^7\\) has no negative real roots. How many non-real roots does it have?","ch":["0","2","4","6"],"a":"C","idea":"\\(f=x^2(-x^5+x+3)\\): a double root at 0, and one sign change gives exactly one positive root. That leaves \\(7-2-1=4\\) non-real roots.","trap":{"choice":"D","why":"Ignored the double root at 0 and computed \\(7-1=6\\)."},"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":8,"B":33,"C":62,"D":54,"E":6,"blank":75},"pc":26.1,"pa":68.5,"top":46,"pct":99.6,"tier":5,"disc":0.41,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2026-states-alpha-ind-11","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":11,"topic":"Trigonometry","skill":"Sum/difference identities → tangent equation","q":"Find the smallest positive value of \\(L\\), in degrees, given that \\(\\sin(L-U)+\\cos(L+U)=0\\) and \\(\\tan U=\\frac{1}{2026}\\).","ch":["45","60","120","135"],"a":"D","idea":"Expand and divide by \\(\\cos L\\cos U\\): \\(\\tan L-\\tan U+1-\\tan L\\tan U=0\\), which factors as \\((1+\\tan L)(1-\\tan U)=0\\). So \\(\\tan L=-1\\) and \\(L=135^\\circ\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":19,"B":15,"C":15,"D":60,"E":3,"blank":126},"pc":25.2,"pa":47.1,"top":57,"pct":92.3,"tier":4,"disc":0.86,"noisy":false,"extrap":false},"kind":"hard"},{"id":"2026-states-alpha-ind-12","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":12,"topic":"Counting & probability","skill":"Comparing binomial counts","q":"The Snowman flips 5 fair coins and Jwigs flips 2 fair coins. The probability that Jwigs has more heads than the Snowman is \\(\\frac LU\\) in lowest terms. Compute \\(L+U\\).","ch":["7","17","33","39"],"a":"B","idea":"The cases (Jwigs, Snowman) are (1,0), (2,0), (2,1): \\(\\frac24\\cdot\\frac1{32}+\\frac14\\cdot\\frac1{32}+\\frac14\\cdot\\frac5{32}=\\frac1{16}\\), so the answer is 17.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":11,"B":70,"C":28,"D":20,"E":15,"blank":94},"pc":29.4,"pa":60.5,"top":75,"pct":82.5,"tier":3,"disc":1.08,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-alpha-ind-13","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":13,"topic":"Counting & probability","skill":"Digit counting with casework","q":"How many 4-digit positive integers have four different digits, are multiples of 5, and have 5 as their largest digit?","ch":["48","60","84","108"],"a":"C","idea":"If the last digit is 0, the other three come from 1–5 and must include 5: \\(60-24=36\\). If the last digit is 5, the others come from 0–4 with a nonzero lead: \\(4\\cdot4\\cdot3=48\\). Total: 84.","trap":{"choice":"D","why":"In the case ending in 0, forgot that 5 must still appear, giving \\(60+48=108\\)."},"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":35,"B":22,"C":63,"D":34,"E":9,"blank":75},"pc":26.5,"pa":68.5,"top":46,"pct":99.9,"tier":5,"disc":0.34,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2026-states-alpha-ind-14","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":14,"topic":"Geometry","skill":"Trapezoid midsegment","q":"Trapezoid \\(SNOW\\) has parallel bases \\(\\overline{SN}\\) and \\(\\overline{OW}\\). \\(R\\) is the midpoint of \\(\\overline{SW}\\), and \\(\\angle NOR\\) is a right angle. If \\(SN=NO=7\\) and \\(OW=18\\), what is \\(NR\\)?","ch":["\\(\\sqrt{193}\\)","\\(\\sqrt{130}\\)","\\(\\frac{\\sqrt{674}}{2}\\)","\\(2\\sqrt7\\)"],"a":"A","idea":"The midsegment from \\(R\\) meets \\(\\overline{NO}\\) at its midpoint \\(P\\) and has length \\(\\frac{25}2\\). Right triangle \\(RPO\\) gives \\(RO=\\sqrt{(25/2)^2-(7/2)^2}=12\\), so \\(NR=\\sqrt{12^2+7^2}=\\sqrt{193}\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":11,"B":17,"C":22,"D":19,"E":5,"blank":164},"pc":4.6,"pa":31.1,"top":11,"pct":99.9,"tier":5,"disc":0.7,"noisy":false,"extrap":true},"kind":"hard"},{"id":"2026-states-alpha-ind-15","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":15,"topic":"Complex numbers","skill":"Square roots of a complex number","q":"The two complex numbers whose squares equal \\(5-12i\\) are \\(M+Ri\\) and \\(L+Ui\\) for integers \\(M,R,L,U\\). Compute the product \\(MR\\).","ch":["\\(-12\\)","\\(-6\\)","6","12"],"a":"B","idea":"\\(a^2-b^2=5\\) and \\(ab=-6\\) give roots \\(\\pm(3-2i)\\). Either way \\(MR=-6\\).","trap":null,"note":"The official solutions list C, but the graded key uses B, which is correct.","setup":null,"fig":null,"stats":{"n":238,"dist":{"A":8,"B":72,"C":25,"D":10,"E":4,"blank":119},"pc":30.3,"pa":50.0,"top":79,"pct":73.2,"tier":2,"disc":1.65,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-alpha-ind-16","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":16,"topic":"Functions & algebra","skill":"Substitution and floor bounds","q":"Evaluate \\(\\left\\lfloor \\frac{2027^3}{2025\\cdot2026}-\\frac{2025^3}{2026\\cdot2027}\\right\\rfloor\\).","ch":["2","4","7","8"],"a":"D","idea":"Let \\(x=2026\\). The expression is \\(\\frac{(x+1)^4-(x-1)^4}{(x-1)x(x+1)}=\\frac{8(x^2+1)}{x^2-1}\\), which is slightly more than 8.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":26,"B":29,"C":33,"D":41,"E":1,"blank":108},"pc":17.2,"pa":54.6,"top":50,"pct":97.7,"tier":4,"disc":0.91,"noisy":false,"extrap":false},"kind":"hard"},{"id":"2026-states-alpha-ind-17","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":17,"topic":"Conics","skill":"Hyperbola asymptotes","q":"Find the equation of one asymptote of the hyperbola \\(49y^2-4x^2+98y-48x-291=0\\).","ch":["\\(7x-2y=-40\\)","\\(7x-2y=44\\)","\\(2x-7y=19\\)","\\(2x-7y=-5\\)"],"a":"D","idea":"Completing the square gives \\(\\frac{(y+1)^2}{4}-\\frac{(x+6)^2}{49}=1\\). The asymptotes are \\(\\frac{y+1}{2}=\\pm\\frac{x+6}{7}\\), and the \\(+\\) branch is \\(2x-7y=-5\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":17,"B":20,"C":25,"D":51,"E":5,"blank":120},"pc":21.4,"pa":49.6,"top":75,"pct":91.0,"tier":4,"disc":1.19,"noisy":false,"extrap":false},"kind":"hard"},{"id":"2026-states-alpha-ind-18","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":18,"topic":"Polynomials","skill":"Polynomial from its roots","q":"The roots of the polynomial \\(g(x)\\) are \\(-5,2,3,\\) and \\(7\\). The constant term of \\(g(x)\\) is 105 and the degree of \\(g(x)\\) is minimized. What is the sum of the coefficients of \\(g(x)\\)?","ch":["\\(-42\\)","\\(-36\\)","36","42"],"a":"C","idea":"\\(g=a(x+5)(x-2)(x-3)(x-7)\\) with \\(a\\cdot(-210)=105\\), so \\(a=-\\frac12\\). The sum of the coefficients is \\(g(1)=-\\frac12\\cdot6\\cdot(-1)(-2)(-6)=36\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":16,"B":20,"C":61,"D":11,"E":12,"blank":118},"pc":25.6,"pa":50.4,"top":82,"pct":84.9,"tier":3,"disc":1.25,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-alpha-ind-19","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":19,"topic":"Counting & probability","skill":"Conditional probability by counting","q":"Snow rolls a fair 6-sided die 3 times. He notices that the positive difference between the first 2 rolls equals the third roll. What is the probability that at least one 3 was rolled?","ch":["\\(\\frac5{72}\\)","\\(\\frac7{108}\\)","\\(\\frac7{15}\\)","\\(\\frac8{15}\\)"],"a":"C","idea":"There are 30 ordered pairs of first two rolls with \\(a\\ne b\\), and each fixes the third roll. 10 pairs contain a 3, and 4 more have \\(|a-b|=3\\) without a 3, giving \\(\\frac{14}{30}=\\frac7{15}\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":24,"B":19,"C":53,"D":10,"E":5,"blank":127},"pc":22.3,"pa":46.6,"top":46,"pct":99.6,"tier":5,"disc":0.5,"noisy":false,"extrap":true},"kind":"hard"},{"id":"2026-states-alpha-ind-20","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":20,"topic":"Trigonometry","skill":"Angle difference with quadrants","q":"Given \\(\\sin x=-\\frac5{13}\\) with \\(0<x<\\frac{3\\pi}2\\), and \\(\\csc y=\\frac{\\sqrt{10}}3\\) with \\(\\frac\\pi2<y<\\pi\\), find \\(\\cos(x-y)\\).","ch":["\\(-\\frac{3\\sqrt{10}}{130}\\)","\\(-\\frac{27\\sqrt{10}}{130}\\)","\\(\\frac{27\\sqrt{10}}{130}\\)","\\(\\frac{-120+13\\sqrt{10}}{130}\\)"],"a":"A","idea":"\\(x\\) is in Quadrant III (\\(\\cos x=-\\frac{12}{13}\\)) and \\(y\\) is in Quadrant II (\\(\\cos y=-\\frac1{\\sqrt{10}}\\)). Then \\(\\cos(x-y)=\\frac{12-15}{13\\sqrt{10}}=-\\frac{3\\sqrt{10}}{130}\\).","trap":{"choice":"B","why":"Put \\(x\\) in Quadrant IV, where \\(\\cos x>0\\)."},"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":69,"B":43,"C":16,"D":5,"E":5,"blank":100},"pc":29.0,"pa":58.0,"top":75,"pct":81.3,"tier":3,"disc":1.18,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-alpha-ind-21","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":21,"topic":"Geometry","skill":"Angle bisector + power of a point","q":"Triangle \\(XYZ\\) is inscribed in a circle. The angle bisector from \\(X\\) meets \\(\\overline{YZ}\\) at \\(W\\) and the circle again at \\(K\\). If \\(XY:XZ=4:1\\) and \\(XW\\cdot WK=36\\), what is \\(YZ\\)?","ch":["3","12","15","16"],"a":"C","idea":"By the angle bisector theorem, \\(YW:WZ=4:1\\), so write \\(YW=4a\\) and \\(WZ=a\\). By intersecting chords, \\(4a^2=36\\), so \\(a=3\\) and \\(YZ=15\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":4,"B":19,"C":51,"D":13,"E":0,"blank":151},"pc":21.4,"pa":36.6,"top":68,"pct":92.6,"tier":4,"disc":1.07,"noisy":false,"extrap":false},"kind":"hard"},{"id":"2026-states-alpha-ind-22","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":22,"topic":"Exponents & logarithms","skill":"Logs → quadratic → Vieta's formulas","q":"What is the sum of the solutions to \\(7^{3x^2}\\cdot5^{x}=11\\)?","ch":["\\(\\log_5 7\\)","\\(\\frac{\\log\\frac15}{\\log 7}\\)","\\(\\frac{\\log5}{3\\log7}\\)","\\(-\\frac{\\log5}{3\\log7}\\)"],"a":"D","idea":"Take logs: \\(3\\log7\\,x^2+\\log5\\,x-\\log11=0\\). By Vieta's formulas, the sum is \\(-\\frac{\\log5}{3\\log7}\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":3,"B":14,"C":34,"D":46,"E":2,"blank":139},"pc":19.3,"pa":41.6,"top":82,"pct":91.0,"tier":4,"disc":1.4,"noisy":false,"extrap":false},"kind":"hard"},{"id":"2026-states-alpha-ind-23","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":23,"topic":"Coordinate geometry","skill":"Chord of y = |x|","q":"A line intersects the graph of \\(y=|x|\\) at points \\(L\\) and \\(U\\). The midpoint of \\(\\overline{LU}\\) is \\((3,4)\\). Find \\(LU\\).","ch":["\\(6\\sqrt2\\)","\\(4\\sqrt5\\)","10","\\(8\\sqrt2\\)"],"a":"C","idea":"Write the points as \\((p,p)\\) and \\((-q,q)\\). Then \\(p-q=6\\) and \\(p+q=8\\), so the points are \\((7,7)\\) and \\((-1,1)\\), and \\(LU=10\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":20,"B":10,"C":56,"D":18,"E":4,"blank":130},"pc":23.5,"pa":45.4,"top":68,"pct":90.1,"tier":4,"disc":1.09,"noisy":false,"extrap":false},"kind":"hard"},{"id":"2026-states-alpha-ind-24","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":24,"topic":"Trigonometry","skill":"Trig equation → cubic in sin x","q":"Let \\(\\mathcal S\\) be the set of intersection points of \\(y=5\\sec x+2\\sin2x\\) and \\(y=5\\tan x+8\\cos x\\) on \\([0,2\\pi]\\). Find the product of the \\(y\\)-coordinates of all elements of \\(\\mathcal S\\).","ch":["\\(-\\frac{49}3\\)","\\(-\\frac{25}3\\)","\\(-\\frac{16}3\\)","\\(-\\frac43\\)"],"a":"A","idea":"Clearing \\(\\cos x\\) gives \\((\\sin x-1)(2\\sin x-3)(2\\sin x+1)=0\\). Since \\(\\cos x\\ne0\\), only \\(\\sin x=-\\frac12\\) works, giving \\(y=\\mp\\frac{7}{\\sqrt3}\\) and a product of \\(-\\frac{49}3\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":8,"B":20,"C":21,"D":15,"E":2,"blank":172},"pc":3.4,"pa":27.7,"top":14,"pct":99.9,"tier":5,"disc":1.08,"noisy":false,"extrap":true},"kind":"hard"},{"id":"2026-states-alpha-ind-25","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":25,"topic":"Functions & algebra","skill":"Factoring rational expressions","q":"Simplify \\(\\dfrac{(M^2-3^2-U^2)^2-4(3U)^2}{(M^2-U^2-6M+9)(M^2+3M+3U-U^2)}\\).","ch":["1","\\(\\frac{M+U+3}{M+U}\\)","\\(\\frac{M-U+3}{M-U}\\)","\\(\\frac{M+U-9}{M+U+9}\\)"],"a":"B","idea":"The numerator is \\((M^2-(U+3)^2)(M^2-(U-3)^2)\\). The denominator is \\(((M-3)^2-U^2)\\,(M+U)(M-U+3)\\). Cancel the common factors.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":13,"B":40,"C":20,"D":18,"E":2,"blank":145},"pc":16.8,"pa":39.1,"top":46,"pct":99.4,"tier":5,"disc":0.7,"noisy":false,"extrap":true},"kind":"hard"},{"id":"2026-states-alpha-ind-26","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":26,"topic":"Geometry","skill":"Quadrilateral area with 30-60-90 triangles","q":"In triangle \\(WIG\\), \\(m\\angle WIG=150^\\circ\\), \\(WI=3\\sqrt3\\), and \\(IG=4\\). The line through \\(W\\) perpendicular to \\(\\overline{WI}\\) and the line through \\(G\\) perpendicular to \\(\\overline{IG}\\) meet at \\(J\\). Find the area of quadrilateral \\(JWIG\\).","ch":["\\(13\\sqrt3+21\\)","\\(50\\sqrt3\\)","\\(\\frac{91\\sqrt3}2\\)","\\(\\frac{109\\sqrt3}2\\)"],"a":"C","idea":"Place \\(I\\) at the origin with \\(W=(3\\sqrt3,0)\\), so \\(G=(-2\\sqrt3,2)\\). The perpendiculars meet at \\(J=(3\\sqrt3,17)\\), and the shoelace formula gives \\(\\frac{91\\sqrt3}{2}\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":6,"B":10,"C":32,"D":12,"E":2,"blank":176},"pc":13.4,"pa":26.1,"top":39,"pct":99.9,"tier":5,"disc":0.67,"noisy":false,"extrap":true},"kind":"hard"},{"id":"2026-states-alpha-ind-27","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":27,"topic":"Functions & algebra","skill":"Nonlinear systems by factoring","q":"Let \\(\\mathcal S\\) be the set of intersection points of \\(xy-x+y-1=0\\) and \\(3x^2-y^2-2y=0\\). Find the sum of the ordinates (\\(y\\)-values) of all points in \\(\\mathcal S\\).","ch":["\\(-3\\)","\\(-2\\)","1","2"],"a":"E","idea":"\\((x+1)(y-1)=0\\). If \\(y=1\\), then \\(x=\\pm1\\). If \\(x=-1\\), then \\(y=1\\) or \\(-3\\). The points are \\((1,1),(-1,1),(-1,-3)\\), so the sum is \\(-1\\): NOTA.","trap":{"choice":"B","why":"Summed the distinct \\(y\\)-values \\(1+(-3)\\), counting \\(y=1\\) once even though two points have it."},"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":6,"B":23,"C":23,"D":18,"E":7,"blank":161},"pc":2.9,"pa":32.4,"top":18,"pct":99.9,"tier":5,"disc":1.07,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2026-states-alpha-ind-28","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":28,"topic":"Complex numbers","skill":"De Moivre: when is zⁿ real","q":"What is the smallest positive integer \\(n\\) such that \\((-3+i\\sqrt3)^n\\) is a real number?","ch":["4","6","8","16"],"a":"B","idea":"The argument is \\(150^\\circ\\), and \\(150n\\) must be a multiple of \\(180\\). The smallest such \\(n\\) is 6.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":15,"B":79,"C":19,"D":6,"E":14,"blank":105},"pc":33.2,"pa":55.9,"top":93,"pct":74.1,"tier":2,"disc":1.23,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-alpha-ind-29","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":29,"topic":"Matrices & vectors","skill":"One entry of a 3×3 inverse","q":"What is the entry in the third row, first column of the inverse of \\(\\begin{bmatrix}3&2&4\\\\0&5&1\\\\-2&5&-3\\end{bmatrix}\\)?","ch":["\\(-\\frac5{12}\\)","\\(-\\frac16\\)","\\(\\frac12\\)","\\(\\frac34\\)"],"a":"A","idea":"The entry is \\(\\frac{C_{13}}{\\det}\\). \\(C_{13}=0\\cdot5-5\\cdot(-2)=10\\) and \\(\\det=-24\\), giving \\(-\\frac5{12}\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":50,"B":21,"C":20,"D":20,"E":11,"blank":116},"pc":21.0,"pa":51.3,"top":64,"pct":94.6,"tier":4,"disc":0.96,"noisy":false,"extrap":false},"kind":"hard"},{"id":"2026-states-alpha-ind-30","year":2026,"comp":"State Convention","div":"Alpha","test":"Individual","n":30,"topic":"Sequences & series","skill":"Snake pattern → arithmetic series","q":"The first 102 positive integers are placed in 3 rows, snaking as shown: \\[\\begin{array}{ccccc}1&6&7&\\cdots&102\\\\2&5&8&\\cdots&101\\\\3&4&9&\\cdots&100\\end{array}\\] What is the sum of the numbers in the first row?","ch":["721","1648","1687","1751"],"a":"D","idea":"The first row is \\(1,7,\\dots,97\\) together with \\(6,12,\\dots,102\\), 17 terms each: \\(17\\cdot49+17\\cdot54=1751\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":238,"dist":{"A":5,"B":23,"C":30,"D":86,"E":10,"blank":83},"pc":36.1,"pa":65.1,"top":68,"pct":86.9,"tier":3,"disc":0.53,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-01","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":1,"topic":"Derivatives","skill":"Simplifying with identities before differentiating","q":"Compute \\(\\dfrac{d}{dx}\\left(\\dfrac{\\sin^2x-\\cos^2x}{\\cos^2x+\\sin^2x}\\right)\\Big|_{x=1}\\).","ch":["0","\\(2\\sin2\\)","\\(-2\\sin2\\)","\\(\\sin2\\)"],"a":"B","idea":"The denominator is 1 and the numerator is \\(-\\cos2x\\), so the derivative is \\(2\\sin2x\\), which is \\(2\\sin2\\) at \\(x=1\\).","trap":{"choice":"C","why":"Lost a sign: the expression is \\(-\\cos 2x\\), not \\(\\cos 2x\\)."},"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":37,"B":192,"C":26,"D":6,"E":22,"blank":25},"pc":62.3,"pa":91.9,"top":100,"pct":30.1,"tier":1,"disc":1.98,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-02","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":2,"topic":"Derivatives","skill":"Tangent lines","q":"The line tangent to \\(y=\\frac1x\\) at \\(x=1\\) has the form \\(Ax+By=C\\) where \\(A\\), \\(B\\), \\(C\\) are integers and \\(\\gcd(A,B)=1\\). Find \\(AB+BC\\).","ch":["\\(-1\\)","1","3","2"],"a":"C","idea":"The slope is \\(-1\\), so the line is \\(x+y=2\\): \\(A=B=1\\), \\(C=2\\), and \\(AB+BC=1+2=3\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":15,"B":22,"C":226,"D":16,"E":6,"blank":23},"pc":73.4,"pa":92.5,"top":100,"pct":16.7,"tier":1,"disc":1.57,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-03","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":3,"topic":"Limits & continuity","skill":"Continuity vs. differentiability","q":"Consider \\(f(x)=1-|\\cos x|\\). Which statements are true? I. \\(f\\) is continuous everywhere. II. \\(f\\) is nowhere differentiable. III. \\(f\\) is non-differentiable at infinitely many points.","ch":["I only","I, II only","I, III only","III only"],"a":"C","idea":"\\(f\\) is continuous everywhere, and corners occur exactly at the odd multiples of \\(\\frac\\pi2\\), infinitely many points. So I and III hold.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":39,"B":7,"C":218,"D":19,"E":1,"blank":24},"pc":70.8,"pa":92.2,"top":100,"pct":18.4,"tier":1,"disc":1.42,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-04","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":4,"topic":"Derivatives","skill":"Derivative as a series coefficient","q":"Let \\(f(x)=(-2+x)(1-x^3)(1+x^6)\\). Find \\(f'(0)\\).","ch":["\\(-2\\)","\\(-1\\)","0","1"],"a":"D","idea":"\\(f'(0)\\) is the coefficient of \\(x\\) in the expansion, which comes only from \\(x\\cdot1\\cdot1\\), so \\(f'(0)=1\\).","trap":{"choice":"A","why":"Gave \\(f(0)=-2\\) instead of \\(f'(0)\\)."},"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":26,"B":13,"C":13,"D":243,"E":8,"blank":5},"pc":78.9,"pa":98.4,"top":100,"pct":6.9,"tier":1,"disc":1.1,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-05","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":5,"topic":"Limits & continuity","skill":"L'Hôpital with the Fundamental Theorem of Calculus","q":"Compute \\(\\displaystyle\\lim_{x\\to\\frac\\pi4}\\frac{1}{x^2-\\frac{\\pi^2}{16}}\\int_2^{\\sec^2x}\\cos(t^2)\\,dt\\).","ch":["\\(\\frac8\\pi\\cos 4\\)","\\(\\frac2\\pi\\cos 4\\)","\\(\\frac2\\pi\\cos\\frac14\\)","\\(4\\cos 4\\)"],"a":"A","idea":"It is \\(\\frac00\\). Differentiating both parts: \\(\\frac{\\cos(\\sec^4x)\\cdot2\\sec^2x\\tan x}{2x}\\), which at \\(x=\\frac\\pi4\\) is \\(\\frac{4\\cos4}{\\pi/2}=\\frac8\\pi\\cos4\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":116,"B":64,"C":22,"D":6,"E":13,"blank":87},"pc":37.7,"pa":71.8,"top":93,"pct":65.5,"tier":2,"disc":1.6,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-06","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":6,"topic":"Sequences & series","skill":"Evaluating a power series at a point","q":"It is known that \\(\\sum_{n=0}^{\\infty}a_nx^n=xe^{-x^2}\\) for all real \\(x\\). Compute \\(\\sum_{n=0}^{\\infty}\\frac{(-1)^na_n}{2^{2n}}\\).","ch":["\\(-\\frac14e^{1/16}\\)","\\(-\\frac14e^{-1/16}\\)","\\(-\\frac12e^{1/4}\\)","\\(-\\frac12e^{-1/4}\\)"],"a":"B","idea":"The sum is \\(\\sum a_n\\left(-\\frac14\\right)^n=f\\left(-\\frac14\\right)=-\\frac14e^{-1/16}\\).","trap":{"choice":"A","why":"Dropped the minus sign inside \\(e^{-x^2}\\) when substituting."},"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":27,"B":121,"C":22,"D":15,"E":2,"blank":121},"pc":39.3,"pa":60.7,"top":93,"pct":68.6,"tier":2,"disc":1.03,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-07","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":7,"topic":"Parametric & polar","skill":"Polar curves in rectangular form","q":"A bee starts at the origin and moves along \\(y=x\\) until it reaches the polar curve \\(r=\\cos\\theta\\); it then moves south to \\(\\left(\\frac12,-\\frac12\\right)\\), and finally returns to the origin along a segment. What is the total distance traveled?","ch":["\\(\\sqrt2\\)","\\(2\\sqrt2\\)","\\(\\frac{\\sqrt2}2\\)","\\(1+\\sqrt2\\)"],"a":"D","idea":"\\(r=\\cos\\theta\\) is \\(x^2+y^2=x\\); with \\(y=x\\), \\(2a^2=a\\) gives \\(\\left(\\frac12,\\frac12\\right)\\). The legs are \\(\\frac{\\sqrt2}2\\), 1, and \\(\\frac{\\sqrt2}2\\), totaling \\(1+\\sqrt2\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":8,"B":28,"C":10,"D":137,"E":18,"blank":107},"pc":44.5,"pa":65.3,"top":96,"pct":57.9,"tier":2,"disc":1.14,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-08","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":8,"topic":"Integrals","skill":"Integrating indicator functions","q":"For an interval \\(A\\subseteq\\mathbb R\\), the characteristic function \\(\\chi_A\\) is 1 on \\(A\\) and 0 elsewhere. Compute \\(\\int_{-1}^{5}\\left(\\chi_{[0,2]}(x)-0.5\\,\\chi_{[1,3]}(x)+\\chi_{[2,4]}(x)\\right)dx\\).","ch":["\\(-1\\)","3","2","0"],"a":"B","idea":"Each integral is the length of the interval: \\(2-\\frac12(2)+2=3\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":9,"B":126,"C":21,"D":11,"E":3,"blank":138},"pc":40.9,"pa":55.2,"top":100,"pct":58.7,"tier":2,"disc":1.92,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-09","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":9,"topic":"Limits & continuity","skill":"Limits that are not indeterminate","q":"Evaluate \\(\\displaystyle\\lim_{x\\to0}\\frac{1-\\cos(3x)}{2x}\\).","ch":["\\(\\frac32\\)","\\(\\frac94\\)","\\(\\frac92\\)","DNE"],"a":"E","idea":"By L'Hôpital, \\(\\frac{3\\sin3x}{2}\\to0\\). Since 0 isn't listed, the answer is NOTA.","trap":{"choice":"A","why":"Used the standard limit \\(\\frac{1-\\cos u}{u^2}\\) pattern and answered \\(\\frac32\\), but the denominator here is \\(2x\\), not \\(x^2\\)."},"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":26,"B":5,"C":17,"D":28,"E":216,"blank":16},"pc":70.1,"pa":94.8,"top":93,"pct":18.2,"tier":1,"disc":1.31,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-10","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":10,"topic":"Parametric & polar","skill":"Self-intersections of a parametric curve","q":"The planar curve \\(\\alpha(t)=(t^3-4t,\\;t^2-4)\\) intersects itself at the point \\((x,y)\\). Find the sum of all possible \\(x+y\\).","ch":["0","3","2","\\(-6\\)"],"a":"A","idea":"Both \\(t=2\\) and \\(t=-2\\) give \\((0,0)\\), the only self-intersection, so \\(x+y=0\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":80,"B":22,"C":23,"D":34,"E":5,"blank":144},"pc":26.0,"pa":53.2,"top":96,"pct":83.1,"tier":3,"disc":1.55,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-11","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":11,"topic":"Applications of derivatives","skill":"Optimizing a composite exponential","q":"For \\(a<b\\), a bump function is \\(f_{a,b}(x)=e^{\\frac{1}{(x-a)(x-b)}}\\) for \\(a<x<b\\) and 0 otherwise. Compute the absolute maximum of \\(f_{\\frac12,\\frac32}(x)\\).","ch":["\\(e^{-4}\\)","\\(e^{-2}\\)","\\(e^{-4/3}\\)","\\(e^{4}\\)"],"a":"A","idea":"\\(e^{1/h}\\) is maximized where \\(h=(x-a)(x-b)\\) is at its critical point \\(x=1\\), giving \\(e^{1/(0.5\\cdot(-0.5))}=e^{-4}\\).","trap":{"choice":"D","why":"Missed that the exponent is negative inside the interval."},"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":119,"B":17,"C":29,"D":12,"E":20,"blank":111},"pc":38.6,"pa":64.0,"top":100,"pct":64.4,"tier":2,"disc":1.54,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-12","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":12,"topic":"Applications of derivatives","skill":"Related rates with a volume formula","q":"Luster pours salt into a jar whose volume at height \\(h\\) cm is \\(V(h)=\\frac{5}{18}\\pi h^{3/2}\\) cm\\(^3\\). His pouring rate is \\(r(t)=e^{-t}\\), with \\(t\\) in minutes. After two minutes the salt is 4 cm deep. How rapidly is the height increasing at that moment?","ch":["\\(\\frac{5}{6\\pi e}\\)","\\(\\frac{5}{6\\pi e^2}\\)","\\(\\frac{6}{5\\pi e}\\)","\\(\\frac{6}{5\\pi e^2}\\)"],"a":"D","idea":"\\(\\frac{dV}{dh}=\\frac{5\\pi}{12}\\sqrt h=\\frac{5\\pi}{6}\\) at \\(h=4\\), and \\(\\frac{dV}{dt}=e^{-2}\\), so \\(\\frac{dh}{dt}=\\frac{6}{5\\pi e^2}\\).","trap":{"choice":"B","why":"Inverted the fraction: \\(\\frac{dh}{dt}\\) is \\(\\frac{dV}{dt}\\) divided by \\(\\frac{dV}{dh}\\)."},"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":6,"B":44,"C":19,"D":143,"E":3,"blank":93},"pc":46.4,"pa":69.8,"top":89,"pct":54.3,"tier":2,"disc":1.14,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-13","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":13,"topic":"Integrals","skill":"Orthogonality of sines and cosines","q":"With \\(\\langle f,g\\rangle=\\int_{-\\pi}^{\\pi}f(x)g(x)\\,dx\\), compute \\(\\langle\\sin2x,\\sin3x\\rangle+\\langle\\sin3x,\\cos4x\\rangle-\\langle\\sin4x,\\sin4x\\rangle\\).","ch":["\\(-2\\pi\\)","\\(-\\pi\\)","0","\\(\\pi\\)"],"a":"B","idea":"Distinct sines and any sine-cosine pair integrate to 0, and \\(\\int_{-\\pi}^{\\pi}\\sin^24x\\,dx=\\pi\\), so the value is \\(-\\pi\\).","trap":{"choice":"C","why":"Treated \\(\\langle\\sin4x,\\sin4x\\rangle\\) as 0 like the other two."},"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":11,"B":72,"C":43,"D":32,"E":1,"blank":149},"pc":23.4,"pa":51.6,"top":75,"pct":94.8,"tier":4,"disc":0.83,"noisy":false,"extrap":false},"kind":"hard"},{"id":"2026-states-mu-ind-14","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":14,"topic":"Applications of derivatives","skill":"Increasing and concave up together","q":"The derivative of \\(y=f(x)\\) is \\(f'(x)=\\frac{x}{1+x^2}\\). The interval where \\(f\\) is both concave up and increasing is \\([N,M]\\) for integers \\(N\\) and \\(M\\). Find \\(N+M\\).","ch":["\\(-1\\)","1","0","2"],"a":"B","idea":"\\(f\\) increases on \\([0,\\infty)\\), and \\(f''=\\frac{1-x^2}{(1+x^2)^2}>0\\) on \\((-1,1)\\). The overlap is \\([0,1]\\), so \\(N+M=1\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":10,"B":204,"C":17,"D":10,"E":22,"blank":45},"pc":66.2,"pa":85.4,"top":82,"pct":16.9,"tier":1,"disc":0.83,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-15","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":15,"topic":"Derivatives","skill":"Derivative of an inverse function","q":"Suppose \\(f(x)=x^3-x^2+x\\). Compute \\(\\frac{d}{dx}\\left(f^{-1}(x)\\right)\\) at \\(x=6\\).","ch":["\\(\\frac19\\)","\\(\\frac15\\)","\\(\\frac1{11}\\)","\\(-\\frac19\\)"],"a":"A","idea":"\\(f(2)=6\\), so the value is \\(\\frac{1}{f'(2)}=\\frac{1}{12-4+1}=\\frac19\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":187,"B":18,"C":13,"D":14,"E":10,"blank":66},"pc":60.7,"pa":78.6,"top":100,"pct":31.3,"tier":1,"disc":1.49,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-16","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":16,"topic":"Sequences & series","skill":"Summing integrals into a known series","q":"Define \\(f_n(x)=1\\) when \\(\\frac1{2n}<x\\le\\frac1{2n-1}\\) and 0 otherwise. Compute \\(\\sum_{n=1}^{\\infty}\\int_0^1 f_n(x)\\,dx\\).","ch":["1","\\(\\ln2\\)","\\(\\infty\\)","\\(-\\ln2\\)"],"a":"B","idea":"Each integral is \\(\\frac1{2n-1}-\\frac1{2n}\\), and the sum is the alternating harmonic series \\(\\ln2\\).","trap":{"choice":"A","why":"Assumed the intervals fill \\([0,1]\\), giving 1."},"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":22,"B":120,"C":13,"D":13,"E":4,"blank":136},"pc":39.0,"pa":55.8,"top":100,"pct":64.4,"tier":2,"disc":1.48,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-17","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":17,"topic":"Applications of derivatives","skill":"Counting critical points, discontinuities and inflection points","q":"Let \\(n\\) be the number of critical points, \\(m\\) the number of discontinuities, and \\(s\\) the number of inflection points of \\(f(x)=\\frac{-1}{3+2x^2}\\). Find \\(n^m+m^n+n^s\\).","ch":["2","3","4","5"],"a":"A","idea":"\\(f'=\\frac{4x}{(3+2x^2)^2}\\) gives one critical point; \\(f''=\\frac{12(1-2x^2)}{(3+2x^2)^3}\\) gives two inflection points; there are no discontinuities. So \\(1^0+0^1+1^2=2\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":146,"B":34,"C":30,"D":9,"E":7,"blank":82},"pc":47.4,"pa":73.4,"top":100,"pct":50.7,"tier":2,"disc":1.53,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-18","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":18,"topic":"Integrals","skill":"Substitution written as d(x²)","q":"Evaluate \\(\\displaystyle\\int_0^1\\frac{d(x^2)}{1+x^2}\\).","ch":["\\(\\frac\\pi4\\)","\\(\\ln2\\)","\\(\\frac\\pi2\\)","\\(\\infty\\)"],"a":"B","idea":"With \\(u=x^2\\) this is \\(\\int_0^1\\frac{du}{1+u}=\\ln2\\).","trap":{"choice":"A","why":"Read it as \\(\\int_0^1\\frac{dx}{1+x^2}=\\frac\\pi4\\), missing that the differential is \\(d(x^2)\\)."},"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":11,"B":184,"C":17,"D":6,"E":4,"blank":86},"pc":59.7,"pa":72.1,"top":100,"pct":32.1,"tier":1,"disc":1.32,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-19","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":19,"topic":"Sequences & series","skill":"Absolute vs. conditional convergence","q":"For each series, assign 1 if it converges absolutely, \\(-1\\) if it converges conditionally, and 0 if it diverges: (a) \\(\\sum_{n=2}^{\\infty}\\frac{n^2}{\\sqrt{1+n^5}}\\); (b) \\(\\sum_{n=2}^{\\infty}(-1)^n\\frac{n^2-1}{n^3+1}\\); (c) \\(\\sum_{n=1}^{\\infty}(-1)^n\\left(1-\\cos\\frac1n\\right)\\). Find (a)+(b)+(c).","ch":["2","1","0","\\(-2\\)"],"a":"C","idea":"(a) behaves like \\(\\sum n^{-1/2}\\) and diverges (0); (b) is conditionally convergent (\\(-1\\)); (c) compares to \\(\\sum n^{-2}\\) and converges absolutely (1). The sum is 0.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":15,"B":35,"C":89,"D":33,"E":14,"blank":122},"pc":28.9,"pa":60.4,"top":79,"pct":87.1,"tier":3,"disc":0.93,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-20","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":20,"topic":"Applications of derivatives","skill":"Closest point on a curve","q":"Let \\((a,b)\\) be the closest point on the curve \\(y=\\ln x\\) to the point \\((2,0)\\). Find \\(\\frac{\\ln a}{a}+a\\).","ch":["3","\\(e\\)","2","1"],"a":"C","idea":"Minimizing \\((x-2)^2+(\\ln x)^2\\) gives \\(2(a-2)+\\frac{2\\ln a}{a}=0\\), which rearranges to \\(a+\\frac{\\ln a}{a}=2\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":7,"B":26,"C":108,"D":54,"E":3,"blank":110},"pc":35.1,"pa":64.3,"top":93,"pct":69.0,"tier":2,"disc":1.68,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-21","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":21,"topic":"Derivatives","skill":"Differentiating floor and fractional-part expressions","q":"Compute \\(\\dfrac{d}{dx}\\left(x\\lfloor x\\rfloor\\{x\\}\\right)\\Big|_{x=26/25}\\), where \\(\\{x\\}=x-\\lfloor x\\rfloor\\).","ch":["\\(\\frac{24}{25}\\)","1","\\(\\frac{26}{25}\\)","\\(\\frac{27}{25}\\)"],"a":"D","idea":"On \\((1,2)\\) the expression is \\(x\\cdot1\\cdot(x-1)=x^2-x\\), whose derivative \\(2x-1\\) equals \\(\\frac{27}{25}\\) at \\(x=\\frac{26}{25}\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":6,"B":26,"C":31,"D":89,"E":9,"blank":147},"pc":28.9,"pa":52.3,"top":96,"pct":75.5,"tier":3,"disc":2.14,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-22","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":22,"topic":"Parametric & polar","skill":"Arc length of a polar curve","q":"Compute the perimeter of the polar curve \\(r=\\max(\\sin\\theta,\\cos\\theta)\\) on \\(0\\le\\theta\\le\\pi\\).","ch":["\\(\\pi\\)","\\(\\frac{7\\pi}8\\)","\\(2\\pi\\)","\\(\\frac\\pi2\\)"],"a":"A","idea":"Both pieces are arcs of circles of radius \\(\\frac12\\), and together they trace a full circumference: \\(2\\pi\\cdot\\frac12=\\pi\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":99,"B":26,"C":21,"D":18,"E":7,"blank":137},"pc":32.1,"pa":55.5,"top":96,"pct":74.7,"tier":2,"disc":1.52,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-23","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":23,"topic":"Derivatives","skill":"Implicit differentiation and intercepts","q":"Let \\(A\\) be the \\(x\\)-intercept and \\(B\\) the \\(y\\)-intercept of the tangent line to \\(x^2+y^3=y\\) at \\(\\left(\\frac{\\sqrt6}{4},\\frac12\\right)\\). Find \\(\\frac BA\\).","ch":["\\(-\\sqrt6\\)","\\(-3\\sqrt6\\)","\\(-2\\sqrt6\\)","\\(-2\\sqrt5\\)"],"a":"C","idea":"Implicitly, \\(y'=\\frac{2x}{1-3y^2}=2\\sqrt6\\), so the tangent is \\(y=2\\sqrt6x-\\frac52\\). Then \\(B=-\\frac52\\), \\(A=\\frac{5\\sqrt6}{24}\\), and \\(\\frac BA=-2\\sqrt6\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":14,"B":16,"C":154,"D":7,"E":23,"blank":94},"pc":50.0,"pa":69.5,"top":93,"pct":48.3,"tier":1,"disc":0.97,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-24","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":24,"topic":"Integrals","skill":"Integrating a floor function over a shrinking partition","q":"Evaluate \\(\\displaystyle\\int_0^1\\lfloor\\log_2x\\rfloor\\,dx\\).","ch":["\\(-2\\)","\\(-\\frac1{\\ln2}\\)","2","divergent"],"a":"A","idea":"On \\(\\left[2^{-(n+1)},2^{-n}\\right]\\) the floor is \\(-(n+1)\\), so the integral is \\(-\\sum_{n\\ge0}\\frac{n+1}{2^{n+1}}=-2\\).","trap":{"choice":"D","why":"Assumed the unbounded integrand forces divergence, though the integral converges."},"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":71,"B":39,"C":14,"D":42,"E":2,"blank":140},"pc":23.1,"pa":54.5,"top":93,"pct":84.8,"tier":3,"disc":1.87,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-25","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":25,"topic":"Applications of derivatives","skill":"Related rates with unit conversion","q":"An inverted conical tank whose diameter equals its height leaks oil into a cylindrical tank of height 20 inches and diameter 8 inches. The cone initially holds 5 gallons and leaks at \\(\\frac23\\) gallons per half hour. If the cylinder started empty, how rapidly (in cubic inches per hour) is its level increasing when it holds exactly one gallon? (1 gal = 231 in\\(^3\\).)","ch":["\\(\\frac{77}{8\\pi}\\)","\\(\\frac{77}{4\\pi}\\)","\\(\\frac{231}{8\\pi}\\)","\\(\\frac{231}{4\\pi}\\)"],"a":"BE","idea":"The leak is \\(\\frac43\\) gal/hr \\(=308\\) in\\(^3\\)/hr, and the cylinder's cross-section is \\(16\\pi\\), so the level rises at \\(\\frac{308}{16\\pi}=\\frac{77}{4\\pi}\\) inches per hour.","trap":null,"note":"Dual credit: B and E were both accepted, because the question asks for a level (a length per hour) but states the units as cubic inches per hour.","setup":null,"fig":null,"stats":{"n":308,"dist":{"A":27,"B":73,"C":21,"D":15,"E":8,"blank":164},"pc":26.3,"pa":46.8,"top":75,"pct":87.4,"tier":3,"disc":1.11,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-26","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":26,"topic":"Applications of integration","skill":"Accumulating a step-function rate","q":"A tree throws iguanas at a rate \\(R(t)=\\frac{15}{1+\\lfloor t\\rfloor}\\), where \\(t\\ge0\\) is hours after 6 A.M. Let \\(M\\) be the number of iguanas thrown from 6 A.M. until 9:30 A.M. Find \\(\\lceil M\\rceil\\).","ch":["32","29","30","31"],"a":null,"idea":"\\(M=15+\\frac{15}2+5+\\frac12\\cdot\\frac{15}4=29.375\\), so \\(\\lceil M\\rceil=30\\), which is choice C.","trap":null,"note":"Thrown out at the competition, though the intended answer C does work out. Everyone received credit.","setup":null,"fig":null,"stats":{"n":308,"dist":{"A":18,"B":30,"C":68,"D":18,"E":15,"blank":159},"thrown":true},"kind":null},{"id":"2026-states-mu-ind-27","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":27,"topic":"Sequences & series","skill":"Differentiating a Maclaurin series","q":"Find the sum of the convergent series \\(\\displaystyle\\sum_{n=1}^{\\infty}\\frac{(n+1)(-1)^n}{n!\\,2^n}\\).","ch":["\\(\\frac{1}{2\\sqrt e}\\)","\\(\\frac{1}{2\\sqrt e}-1\\)","\\(1-\\frac{1}{2\\sqrt e}\\)","\\(-\\frac{1}{2\\sqrt e}\\)"],"a":"B","idea":"Differentiating \\(xe^{-x}=\\sum\\frac{(-1)^nx^{n+1}}{n!}\\) gives \\((1-x)e^{-x}=\\sum_{n\\ge0}\\frac{(n+1)(-1)^nx^n}{n!}\\). At \\(x=\\frac12\\) that is \\(\\frac{1}{2\\sqrt e}\\); subtract the \\(n=0\\) term, which is 1.","trap":{"choice":"A","why":"Forgot that the sum starts at \\(n=1\\), so the \\(n=0\\) term (equal to 1) must be removed."},"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":15,"B":82,"C":32,"D":13,"E":4,"blank":162},"pc":26.6,"pa":47.4,"top":75,"pct":88.8,"tier":3,"disc":1.0,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-mu-ind-28","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":28,"topic":"Applications of integration","skill":"Volume by cross-sections","q":"A solid has a triangular base with vertices \\((0,1)\\), \\((-2,0)\\) and \\((3,0)\\), and cross-sections perpendicular to the \\(y\\)-axis are rectangles whose height is twice their width. Find the volume of the solid.","ch":["\\(\\frac{25}{54}\\)","\\(\\frac{10}3\\)","25","\\(\\frac{50}3\\)"],"a":"D","idea":"The width at height \\(y\\) is \\((3-3y)-(2y-2)=5(1-y)\\) and the height is \\(10(1-y)\\), so \\(V=\\int_0^1 50(1-y)^2dy=\\frac{50}3\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":22,"B":33,"C":20,"D":74,"E":14,"blank":145},"pc":24.0,"pa":52.9,"top":86,"pct":91.9,"tier":4,"disc":0.98,"noisy":false,"extrap":false},"kind":"hard"},{"id":"2026-states-mu-ind-29","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":29,"topic":"Limits & continuity","skill":"Limits of trigonometric ratios in a figure","q":"In the figure, \\(b\\) is held constant, with \\(a=x\\cot\\theta\\), \\(b=y\\tan\\theta\\), \\(c=x\\csc\\theta\\) and \\(d=y\\sec\\theta\\). Evaluate \\(\\displaystyle\\lim_{a\\to b}\\left(\\frac{a-b}{c-d}\\right)\\).","ch":["\\(\\frac{\\sqrt2}2\\)","\\(-\\frac{\\sqrt2}2\\)","\\(\\sqrt2\\)","1"],"a":"C","idea":"As \\(a\\to b\\), \\(\\theta\\to\\frac\\pi4\\), so the ratio tends to \\(\\frac{x-y}{\\sqrt2(x-y)}=\\frac{\\sqrt2}2\\), which is choice A.","trap":null,"note":"Answer disputed. The test's printed key and its own solution give A, but the competition graded C, and the statistics here follow the graded key. The figure is not reproduced; the stated relations come from the official solution.","setup":null,"fig":null,"stats":{"n":308,"dist":{"A":46,"B":13,"C":54,"D":21,"E":12,"blank":162},"pc":17.5,"pa":47.4,"top":46,"pct":99.9,"tier":5,"disc":0.45,"noisy":false,"extrap":true},"kind":"hard"},{"id":"2026-states-mu-ind-30","year":2026,"comp":"State Convention","div":"Mu","test":"Individual","n":30,"topic":"Derivatives","skill":"Corners in a sum of absolute values","q":"Find the number of points where \\(f\\) is non-differentiable, for \\(f(x)=\\sum_{n=0}^{2026}|x-n|\\).","ch":["2026","2027","1013","4052"],"a":"B","idea":"Each term \\(|x-n|\\) contributes a corner at \\(x=n\\), and there are 2027 values of \\(n\\) from 0 to 2026.","trap":{"choice":"A","why":"Counted the terms as \\(n=1\\) through 2026, forgetting \\(n=0\\)."},"note":null,"setup":null,"fig":null,"stats":{"n":308,"dist":{"A":34,"B":117,"C":20,"D":11,"E":6,"blank":120},"pc":38.0,"pa":61.0,"top":100,"pct":67.8,"tier":2,"disc":1.28,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-stat-ind-01","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":1,"topic":"Counting & probability","skill":"Permutations of distinct letters","q":"Find the number of distinct permutations of the letters in DINOSAUR.","ch":["40320","20160","5040","2520"],"a":"A","idea":"All 8 letters are distinct, so there are \\(8!=40320\\) permutations.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":133,"dist":{"A":116,"B":4,"C":4,"D":3,"E":1,"blank":5},"pc":87.2,"pa":96.2,"top":100,"pct":5.8,"tier":1,"disc":1.79,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-stat-ind-02","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":2,"topic":"Descriptive statistics","skill":"Population vs. sample standard deviation","q":"What is the sum of the mean and standard deviation of the Box Office Gross Sales, in millions of USD? Round each quantity to 3 decimal places before adding.","ch":["1026.153","1283.271","1377.038","1412.948"],"a":"C","idea":"The mean is \\(\\frac{6502}{7}=928.857\\). This is population data, so divide by 7: \\(\\sigma\\approx448.181\\). The sum is 1377.038.","trap":{"choice":"D","why":"Used the sample standard deviation (dividing by \\(n-1\\)) instead of the population one."},"note":null,"setup":["2026-stat-jurassic"],"fig":null,"stats":{"n":133,"dist":{"A":0,"B":2,"C":97,"D":29,"E":1,"blank":4},"pc":72.9,"pa":97.0,"top":93,"pct":9.7,"tier":1,"disc":0.9,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-stat-ind-03","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":3,"topic":"Descriptive statistics","skill":"The 1.5 IQR outlier rule","q":"Using the 1.5 IQR rule, how many of the Mean Rating values are outliers?","ch":["0","1","2","3"],"a":"C","idea":"\\(Q_1=27\\) and \\(Q_3=34\\), so \\(IQR=7\\) and the fences are 16.5 and 44.5. Both 12 and 46 fall outside, so there are 2.","trap":{"choice":"B","why":"Caught only the high outlier (46) and missed the low one (12), or the reverse."},"note":null,"setup":["2026-stat-jurassic"],"fig":null,"stats":{"n":133,"dist":{"A":26,"B":26,"C":79,"D":1,"E":0,"blank":1},"pc":59.4,"pa":99.2,"top":61,"pct":40.6,"tier":1,"disc":-0.07,"noisy":true,"extrap":true},"kind":"trap"},{"id":"2026-states-stat-ind-04","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":4,"topic":"Study design & data types","skill":"Levels of measurement","q":"Which of the following best describes the type of data of Box Office Gross Sales?","ch":["Ratio","Nominal","Interval","Ordinal"],"a":"A","idea":"Gross sales are quantitative with equal intervals and a true zero, so a film grossing \\$100 million made twice as much as one grossing \\$50 million. That is ratio data.","trap":{"choice":"B","why":"Confused the level of measurement with the variable's role; money is never nominal."},"note":null,"setup":["2026-stat-jurassic"],"fig":null,"stats":{"n":133,"dist":{"A":59,"B":36,"C":10,"D":14,"E":3,"blank":11},"pc":44.4,"pa":91.7,"top":93,"pct":57.0,"tier":2,"disc":1.62,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-stat-ind-05","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":5,"topic":"Study design & data types","skill":"Correlation versus causation","q":"Which of the following can we certainly conclude from the given bivariate data set? (A) Jurassic Park 3 was a bad movie. (B) A higher NumberCubed rating causes higher Gross Sales. (C) A higher NumberCubed rating causes lower Gross Sales. (D) There is no correlation between Gross Sales and rating.","ch":["A","B","C","D"],"a":"E","idea":"'Bad' is subjective, observational data can't establish causation, and the two variables are in fact correlated (\\(r\\approx0.875\\)). All four are false, so NOTA.","trap":{"choice":"B","why":"Read a strong correlation as evidence of causation."},"note":null,"setup":["2026-stat-jurassic"],"fig":null,"stats":{"n":133,"dist":{"A":7,"B":23,"C":0,"D":5,"E":95,"blank":3},"pc":71.4,"pa":97.7,"top":96,"pct":16.0,"tier":1,"disc":1.21,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-stat-ind-06","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":6,"topic":"Random variables & expected value","skill":"Expected value of a maximum","q":"Two distinct Jurassic Park films are selected at random. What is the expected value of the larger Mean Rating of the two? Round to 3 decimal places.","ch":["30.000","34.214","34.816","35.619"],"a":"D","idea":"Average the larger rating over all \\(\\binom72=21\\) pairs: \\(\\frac{748}{21}\\approx35.619\\).","trap":{"choice":"C","why":"Averaged over the wrong set of pairs, for example including a film with itself."},"note":null,"setup":["2026-stat-jurassic"],"fig":null,"stats":{"n":133,"dist":{"A":10,"B":16,"C":23,"D":38,"E":5,"blank":41},"pc":28.6,"pa":69.2,"top":57,"pct":88.8,"tier":3,"disc":0.87,"noisy":false,"extrap":false},"kind":"trap"},{"id":"2026-states-stat-ind-07","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":7,"topic":"Probability","skill":"Hypergeometric probabilities","q":"Of the 40 objects at a site, 27 are fossils and the rest are rocks. If Jack picks up 11 objects, what is the probability he picks up exactly 3 or exactly 6 rocks? Round to 3 decimal places.","ch":["0.275","0.335","0.600","0.774"],"a":"B","idea":"Add two hypergeometric terms: \\(\\frac{\\binom{13}{3}\\binom{27}{8}+\\binom{13}{6}\\binom{27}{5}}{\\binom{40}{11}}\\approx0.335\\).","trap":{"choice":"E","why":"Used the binomial distribution, which assumes replacement, instead of the hypergeometric."},"note":null,"setup":null,"fig":null,"stats":{"n":133,"dist":{"A":8,"B":62,"C":11,"D":3,"E":27,"blank":22},"pc":46.6,"pa":83.5,"top":79,"pct":60.8,"tier":2,"disc":0.52,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-stat-ind-08","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":8,"topic":"Regression","skill":"Reading regression output and notation","q":"Using proper notation, what is the equation of the sample least-squares regression line? (A) \\(y=0.03777\\hat x+3.05849\\) (B) \\(\\hat y=0.03777x+0.01541\\) (C) \\(\\hat y=0.03777x+3.05849\\) (D) \\(\\hat y=0.305849x+0.03777\\)","ch":["A","B","C","D"],"a":"C","idea":"The slope is the Hunger Level coefficient and the intercept is the Constant coefficient, and the hat belongs on the predicted \\(y\\).","trap":null,"note":null,"setup":["2026-stat-ark"],"fig":null,"stats":{"n":133,"dist":{"A":7,"B":4,"C":115,"D":3,"E":0,"blank":4},"pc":86.5,"pa":97.0,"top":93,"pct":0.1,"tier":1,"disc":0.59,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-stat-ind-09","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":9,"topic":"Regression","skill":"The point (x̄, ȳ) lies on the regression line","q":"When the point \\((49,8)\\) is added and the line is refit, the slope does not change. What is the mean number of pieces of food in the original sample? Round to 3 decimal places.","ch":["3.361","4.909","6.376","8.000"],"a":"B","idea":"The slope is unchanged only if the new point sits directly above \\(\\bar x\\), so \\(\\bar x=49\\). Since \\((\\bar x,\\bar y)\\) is on the line, \\(\\bar y=0.03777(49)+3.05849\\approx4.909\\).","trap":{"choice":"D","why":"Took \\(\\bar y\\) to be the new point's \\(y\\)-value, 8."},"note":null,"setup":["2026-stat-ark"],"fig":null,"stats":{"n":133,"dist":{"A":4,"B":28,"C":12,"D":32,"E":4,"blank":53},"pc":21.1,"pa":60.2,"top":18,"pct":78.9,"tier":3,"disc":-0.21,"noisy":true,"extrap":true},"kind":"trap"},{"id":"2026-states-stat-ind-10","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":10,"topic":"Regression","skill":"Interpreting s, the standard deviation of the residuals","q":"Which of the following is a proper interpretation of \\(S\\)? (A) About 2.52930% of variability in the predicted number of pieces of food is accounted for by hunger level. (B) Since \\(2.52930>0.8\\), the association is strong and positive. (C) The actual number of pieces of food differs by 2.52930 from the predicted number. (D) The actual number of pieces of food is typically about 2.52930 away from the predicted number.","ch":["A","B","C","D"],"a":"DE","idea":"\\(S\\) is the standard deviation of the residuals: a typical distance between actual and predicted values, which is D.","trap":{"choice":"C","why":"Dropped the word 'typically': residuals vary, so the gap isn't 2.52930 every time."},"note":"Dual credit: the printed key gives D, but D and E were both accepted when graded, presumably over the wording of D.","setup":["2026-stat-ark"],"fig":null,"stats":{"n":133,"dist":{"A":5,"B":1,"C":30,"D":75,"E":9,"blank":13},"pc":63.2,"pa":90.2,"top":93,"pct":25.2,"tier":1,"disc":1.01,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-stat-ind-11","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":11,"topic":"Hypothesis testing","skill":"t-test for a slope against a non-zero null","q":"Perform the test \\(H_0:\\beta_1=0.01\\) against \\(H_a:\\beta_1\\ne0.01\\). What is the p-value, rounded to 4 decimal places?","ch":["0.0201","0.0406","0.0810","0.0813"],"a":"D","idea":"\\(t=\\frac{0.03777-0.01}{0.01541}\\approx1.8021\\) with \\(n-2=31\\) df. The one-tail area is about 0.04063, so the two-tail p-value is 0.0813.","trap":{"choice":"B","why":"Reported the one-tailed area for a two-sided alternative."},"note":null,"setup":["2026-stat-ark"],"fig":null,"stats":{"n":133,"dist":{"A":16,"B":22,"C":10,"D":30,"E":5,"blank":50},"pc":22.6,"pa":62.4,"top":57,"pct":96.1,"tier":4,"disc":0.79,"noisy":false,"extrap":false},"kind":"trap"},{"id":"2026-states-stat-ind-12","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":12,"topic":"Counting & probability","skill":"Permutations with repeated letters","q":"Which statistical concept is both resistant and unaffected by incorrect assumptions? Find the number of distinct permutations of the letters in that word. (Hint: the word contains the letter 'b'.)","ch":["120","360","720","2520"],"a":"C","idea":"The word is ROBUST, whose 6 letters are distinct: \\(6!=720\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":133,"dist":{"A":6,"B":8,"C":48,"D":14,"E":10,"blank":47},"pc":36.1,"pa":64.7,"top":57,"pct":99.9,"tier":5,"disc":0.16,"noisy":false,"extrap":true},"kind":"hard"},{"id":"2026-states-stat-ind-13","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":13,"topic":"Probability","skill":"Bayes' theorem with a follow-up split","q":"Scientists know 50% of dinosaurs were land herbivores, 10% aquatic herbivores, 30% land carnivores and 10% aquatic carnivores. A test identifies land versus aquatic correctly 70% of the time. A fossil tests as 'aquatic.' What is the probability it actually came from an aquatic carnivore?","ch":["\\(\\frac7{38}\\)","\\(\\frac7{40}\\)","\\(\\frac7{20}\\)","\\(\\frac7{19}\\)"],"a":"A","idea":"By Bayes, \\(P(\\text{aquatic}\\mid\\text{test aquatic})=\\frac{0.7(0.2)}{0.7(0.2)+0.3(0.8)}=\\frac7{19}\\). Aquatic fossils split evenly between carnivores and herbivores, so halve it: \\(\\frac7{38}\\).","trap":{"choice":"D","why":"Stopped at \\(P(\\text{aquatic}\\mid\\text{test})\\) without splitting off the carnivores."},"note":null,"setup":null,"fig":null,"stats":{"n":133,"dist":{"A":24,"B":10,"C":48,"D":12,"E":6,"blank":33},"pc":18.0,"pa":75.2,"top":36,"pct":99.9,"tier":5,"disc":0.47,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2026-states-stat-ind-14","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":14,"topic":"Confidence intervals","skill":"Interpreting a confidence interval","q":"Lila analyzes her results with a 96% confidence interval for \\(p\\). Which is a correct interpretation? (A) If Lila repeats her sample 100 times, \\(\\hat p\\) will lie between 0.256 and 0.544 exactly 96 times. (B) There is a 96% chance that \\(p\\) lies between 0.256 and 0.544. (C) Lila is 96% confident that \\(p\\) lies between 0.253 and 0.547. (D) There is a 96% chance that \\(p\\) lies between 0.253 and 0.547.","ch":["A","B","C","D"],"a":"E","idea":"The interval is \\((0.256,0.544)\\). A and B state it wrongly (a probability statement about \\(p\\), or about future \\(\\hat p\\)); C and D use the wrong endpoints. So NOTA.","trap":{"choice":"C","why":"Right wording, wrong endpoints: 0.253 and 0.547 come from the wrong critical value."},"note":null,"setup":["2026-stat-lila"],"fig":null,"stats":{"n":133,"dist":{"A":4,"B":8,"C":49,"D":13,"E":47,"blank":12},"pc":35.3,"pa":91.0,"top":86,"pct":69.9,"tier":2,"disc":1.68,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-stat-ind-15","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":15,"topic":"Hypothesis testing","skill":"Working backwards from a type II error rate","q":"If Lila runs a left-tailed z-test at \\(\\alpha=0.01\\) and the probability of a type II error is 0.2, what is the true population proportion \\(p\\)? Round to 3 decimal places.","ch":["0.320","0.319","0.318","0.317"],"a":"A","idea":"The test rejects when \\(\\hat p<0.39192512\\). Requiring \\(P(\\hat p>0.39192512)=0.2\\) under the true \\(p\\) gives \\(\\frac{0.39192512-p}{\\sqrt{p(1-p)/30}}=0.8416\\), so \\(p\\approx0.320\\).","trap":{"choice":"B","why":"Rounded intermediate critical values, which shifts the third decimal place."},"note":null,"setup":["2026-stat-lila"],"fig":null,"stats":{"n":133,"dist":{"A":19,"B":14,"C":16,"D":5,"E":6,"blank":73},"pc":14.3,"pa":45.1,"top":43,"pct":97.1,"tier":4,"disc":1.19,"noisy":false,"extrap":true},"kind":"hard"},{"id":"2026-states-stat-ind-16","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":16,"topic":"Hypothesis testing","skill":"Exact binomial p-value","q":"Lila uses the binomial distribution (no normal approximation or continuity correction) to compute her p-value. What is the exact p-value, rounded to 4 decimal places?","ch":["0.0212","0.0402","0.1808","0.5785"],"a":"A","idea":"With \\(n=30\\) and \\(\\hat p=0.4\\) there are 12 successes, so the p-value is \\(P(X\\le12)\\) for \\(X\\sim\\text{Bin}(30,0.6)\\approx0.0212\\).","trap":{"choice":"C","why":"Used the normal approximation instead of the exact binomial."},"note":null,"setup":["2026-stat-lila"],"fig":null,"stats":{"n":133,"dist":{"A":31,"B":12,"C":13,"D":7,"E":2,"blank":68},"pc":23.3,"pa":48.9,"top":68,"pct":88.4,"tier":3,"disc":1.33,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-stat-ind-17","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":17,"topic":"Chi-square tests","skill":"When a p-value cannot be recovered","q":"Jake should have run a \\(\\chi^2\\) two-way test on a table with 3 categories per variable, but he included the row and column totals, making a 4×4 table. If the correct p-value is 0.0500, what p-value did he actually calculate? Round to 4 decimal places.","ch":["0.0020","0.0500","0.3909","0.3935"],"a":"E","idea":"His test statistic comes from his own wrong table, which we can't reconstruct from the correct p-value. With no statistic there is no p-value, so NOTA.","trap":{"choice":"D","why":"Took the correct statistic (from 4 df) and read it against 9 df, as though only the df changed."},"note":"The test's printed header labels this block 'Questions 15 through 19,' but the Lila questions are 14 through 17.","setup":["2026-stat-lila","2026-stat-chitable"],"fig":null,"stats":{"n":133,"dist":{"A":7,"B":8,"C":21,"D":19,"E":6,"blank":72},"pc":4.5,"pa":45.9,"top":14,"pct":99.9,"tier":5,"disc":1.22,"noisy":false,"extrap":true},"kind":"hard"},{"id":"2026-states-stat-ind-18","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":18,"topic":"Probability","skill":"Conditional probability from a two-way table","q":"If a randomly selected respondent prefers Dinosaur Train or has a favorite character from the Jurassic era, what is the probability their favorite character is from the Triassic era?","ch":["\\(\\frac7{73}\\)","\\(\\frac{23}{73}\\)","\\(\\frac{73}{105}\\)","\\(\\frac{23}{105}\\)"],"a":"A","idea":"The union has \\(62+11=73\\) respondents, of whom 7 are DT-Triassic, giving \\(\\frac7{73}\\).","trap":null,"note":null,"setup":["2026-stat-sam"],"fig":null,"stats":{"n":133,"dist":{"A":83,"B":9,"C":9,"D":5,"E":6,"blank":21},"pc":62.4,"pa":84.2,"top":93,"pct":25.8,"tier":1,"disc":0.97,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-stat-ind-19","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":19,"topic":"Confidence intervals","skill":"Largest confidence level excluding a value","q":"Sam is \\(x\\%\\) confident, by a one-proportion z-interval, that the proportion preferring Dinosaur Train is not 0.5. If \\(y=1000(x\\%)\\) is an integer, what is the sum of the digits of the largest possible \\(y\\)?","ch":["13","14","16","18"],"a":"A","idea":"Requiring \\(\\frac{43}{105}+z^*(0.04799)<0.5\\) gives \\(z^*<1.8853\\), so \\(x<0.94062\\) and \\(y=940\\). The digits sum to 13.","trap":null,"note":null,"setup":["2026-stat-sam"],"fig":null,"stats":{"n":133,"dist":{"A":24,"B":15,"C":15,"D":13,"E":13,"blank":53},"pc":18.0,"pa":60.2,"top":57,"pct":93.0,"tier":4,"disc":1.38,"noisy":false,"extrap":false},"kind":"hard"},{"id":"2026-states-stat-ind-20","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":20,"topic":"Chi-square tests","skill":"Choosing among chi-square tests","q":"A \\(\\chi^2\\)-test compares the 'preferred show' responses with the 'favorite character' responses to see whether the two variables are related. Which type of \\(\\chi^2\\)-test is it? (A) Two-Way (B) Goodness of Fit (C) Homogeneity (D) Independence / Association","ch":["A","B","C","D"],"a":"D","idea":"One sample was taken and two categorical variables were recorded on it, which is a test of independence. Homogeneity would need separate samples from each population.","trap":{"choice":"C","why":"Chose homogeneity, which applies when several populations are sampled separately."},"note":null,"setup":["2026-stat-sam"],"fig":null,"stats":{"n":133,"dist":{"A":5,"B":10,"C":10,"D":107,"E":0,"blank":1},"pc":80.5,"pa":99.2,"top":96,"pct":1.8,"tier":1,"disc":0.75,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-stat-ind-21","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":21,"topic":"Chi-square tests","skill":"Degrees of freedom, p-value and cell contributions","q":"What is the sum of the degrees of freedom, the p-value, and the greatest chi-square contribution for the test in the previous question? Round each of the three quantities to 4 decimal places before adding.","ch":["2.1547","2.9030","3.5378","7.2518"],"a":"B","idea":"\\(df=(3-1)(2-1)=2\\), \\(\\chi^2\\approx0.9002\\) gives p \\(\\approx0.6376\\), and the largest cell contribution (LBT, Jurassic) is about 0.2654. The sum is 2.9030.","trap":{"choice":"C","why":"Used the wrong degrees of freedom or the wrong cell as the largest contributor."},"note":null,"setup":["2026-stat-sam","2026-stat-chitable"],"fig":null,"stats":{"n":133,"dist":{"A":3,"B":44,"C":19,"D":4,"E":8,"blank":55},"pc":33.1,"pa":58.6,"top":79,"pct":79.6,"tier":3,"disc":1.03,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-stat-ind-22","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":22,"topic":"Hypothesis testing","skill":"Two-sample t-test on tiny samples","q":"The conditions are blatantly not met, but proceeding anyway, run the appropriate t-test and give the sum of the absolute value of the test statistic and the p-value. Round each to 4 decimal places before adding.","ch":["0.9835","1.2599","2.8812","2.9340"],"a":"A","idea":"\\(t=\\frac{2.4-2.3}{\\sqrt{0.005+0.005}}\\approx0.7071\\), whose one-sided p-value is 0.2764. The sum is 0.9835.","trap":null,"note":null,"setup":["2026-stat-lacko"],"fig":null,"stats":{"n":133,"dist":{"A":75,"B":10,"C":7,"D":3,"E":4,"blank":34},"pc":56.4,"pa":74.4,"top":86,"pct":37.7,"tier":1,"disc":1.15,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-stat-ind-23","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":23,"topic":"Counting & probability","skill":"Counting groupings for a permutation test","q":"Including the unshuffled data, how many distinct ways are there to organize the data into two groups of the original sample sizes? Order within each group does not matter.","ch":["3","6","12","24"],"a":"B","idea":"Choose which 2 of the 4 values are coastal: \\(\\binom42=6\\).","trap":{"choice":"A","why":"Treated the two groups as interchangeable, halving the count to 3."},"note":null,"setup":["2026-stat-lacko","2026-stat-perm"],"fig":null,"stats":{"n":133,"dist":{"A":20,"B":55,"C":17,"D":11,"E":0,"blank":30},"pc":41.4,"pa":77.4,"top":64,"pct":69.7,"tier":2,"disc":0.75,"noisy":false,"extrap":false},"kind":"trap"},{"id":"2026-states-stat-ind-24","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":24,"topic":"Nonparametric methods","skill":"The permutation test statistic","q":"What is the test statistic of the permutation test for this set of data?","ch":["\\(-0.2\\)","\\(-0.1\\)","0.1","0.2"],"a":"C","idea":"It is the observed difference in means: \\(\\frac{2.3+2.5}{2}-\\frac{2.2+2.4}{2}=0.1\\).","trap":{"choice":"D","why":"Used the difference in sums rather than in means."},"note":null,"setup":["2026-stat-lacko","2026-stat-perm"],"fig":null,"stats":{"n":133,"dist":{"A":5,"B":3,"C":34,"D":14,"E":2,"blank":75},"pc":25.6,"pa":43.6,"top":43,"pct":74.4,"tier":2,"disc":0.05,"noisy":true,"extrap":true},"kind":"trap"},{"id":"2026-states-stat-ind-25","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":25,"topic":"Nonparametric methods","skill":"The permutation test p-value","q":"What is the p-value of the permutation test for this set of data?","ch":["\\(\\frac12\\)","\\(\\frac13\\)","\\(\\frac16\\)","\\(\\frac1{12}\\)"],"a":"B","idea":"The six groupings give differences \\(-0.2,-0.1,0,0,0.1,0.2\\). Two are at least as extreme as 0.1, so the p-value is \\(\\frac26=\\frac13\\).","trap":{"choice":"C","why":"Counted only the observed arrangement, giving \\(\\frac16\\)."},"note":null,"setup":["2026-stat-lacko","2026-stat-perm"],"fig":null,"stats":{"n":133,"dist":{"A":8,"B":15,"C":24,"D":8,"E":1,"blank":77},"pc":11.3,"pa":42.1,"top":39,"pct":98.2,"tier":5,"disc":1.25,"noisy":false,"extrap":true},"kind":"hard"},{"id":"2026-states-stat-ind-26","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":26,"topic":"Nonparametric methods","skill":"Stating a conclusion about the null hypothesis","q":"What is a correct interpretation of the test performed over the previous two questions? (A) Sufficient evidence to support the claim that both samples came from the same distribution. (B) Not sufficient evidence to support that claim. (C) Sufficient evidence to reject that claim. (D) Not sufficient evidence to reject that claim.","ch":["A","B","C","D"],"a":"D","idea":"The p-value of about 0.33 exceeds \\(\\alpha=0.20\\), so we fail to reject \\(H_0\\). A null hypothesis is never supported, only not rejected.","trap":{"choice":"C","why":"Reversed the decision: a large p-value means we do not reject."},"note":null,"setup":["2026-stat-lacko","2026-stat-perm"],"fig":null,"stats":{"n":133,"dist":{"A":2,"B":10,"C":28,"D":37,"E":3,"blank":53},"pc":27.8,"pa":60.2,"top":43,"pct":99.0,"tier":5,"disc":0.42,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2026-states-stat-ind-27","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":27,"topic":"Sampling distributions","skill":"Chi-square distribution of the sample variance","q":"Compute the probability that the sample variance of Lackosaur toe widths was what we observed or something larger. Round to 4 decimal places.","ch":["0.2042","0.2475","0.3884","0.4291"],"a":"B","idea":"\\(S^2=\\frac1{60}\\), so \\(\\frac{(n-1)S^2}{\\sigma^2}=\\frac{3/60}{0.11^2}=\\frac{500}{121}\\). The upper-tail area for \\(\\chi^2_3\\) is about 0.2475.","trap":null,"note":null,"setup":["2026-stat-lacko","2026-stat-chisqdist"],"fig":null,"stats":{"n":133,"dist":{"A":4,"B":24,"C":20,"D":7,"E":2,"blank":76},"pc":18.0,"pa":42.9,"top":50,"pct":97.5,"tier":4,"disc":0.9,"noisy":false,"extrap":false},"kind":"hard"},{"id":"2026-states-stat-ind-28","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":28,"topic":"Confidence intervals","skill":"Confidence interval for a standard deviation","q":"If \\(\\sigma\\) were unknown, create a two-sided 90% confidence interval for \\(\\sigma\\), with endpoints rounded to 3 decimal places.","ch":["\\((0.006,0.142)\\)","\\((0.018,0.391)\\)","\\((0.107,0.151)\\)","\\((0.080,0.377)\\)"],"a":"D","idea":"Invert \\(\\frac{(n-1)S^2}{\\sigma^2}\\sim\\chi^2_3\\): \\(L^2=\\frac{3/60}{7.8147}\\) and \\(U^2=\\frac{3/60}{0.3518}\\), giving \\((0.080,0.377)\\).","trap":{"choice":"A","why":"Reported the interval for \\(\\sigma^2\\) without taking square roots."},"note":null,"setup":["2026-stat-lacko","2026-stat-chisqdist","2026-stat-chitable"],"fig":null,"stats":{"n":133,"dist":{"A":6,"B":12,"C":22,"D":11,"E":1,"blank":81},"pc":8.3,"pa":39.1,"top":21,"pct":99.9,"tier":5,"disc":0.34,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2026-states-stat-ind-29","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":29,"topic":"Sampling distributions","skill":"Adding independent chi-square variables","q":"Two independent samples \\(X_1\\), \\(X_2\\) of equal size \\(n\\) come from normal populations with \\(\\sigma_1=\\sigma_2\\). Which gives the distribution of \\(S_1^2+S_2^2\\)?","ch":["\\(\\frac{2\\sigma_1^2\\chi^2_{n-1}}{n-1}\\)","\\(\\frac{\\sigma_1^2\\chi^2_{2n-2}}{n-1}\\)","\\(\\frac{\\sigma_1^2\\chi^2_{n-1}}{2n-2}\\)","\\(\\frac{\\sigma_1^2\\chi^2_{2n-2}}{2n-2}\\)"],"a":"B","idea":"Each \\(S_i^2\\sim\\frac{\\sigma_1^2\\chi^2_{n-1}}{n-1}\\), and independent chi-squares add degrees of freedom, so the sum is \\(\\frac{\\sigma_1^2\\chi^2_{2n-2}}{n-1}\\).","trap":{"choice":"A","why":"Doubled the variance instead of adding the degrees of freedom."},"note":null,"setup":["2026-stat-chisqdist"],"fig":null,"stats":{"n":133,"dist":{"A":18,"B":19,"C":17,"D":12,"E":0,"blank":67},"pc":14.3,"pa":49.6,"top":25,"pct":85.7,"tier":3,"disc":-0.11,"noisy":true,"extrap":true},"kind":"trap"},{"id":"2026-states-stat-ind-30","year":2026,"comp":"State Convention","div":"Statistics","test":"Individual","n":30,"topic":"Study design & data types","skill":"Checking the independence assumption","q":"Three 'Dinosaurs' take turns naming dinosaurs for one minute, and the time remaining at each name is recorded. Is it reasonable to run the three pairwise mean-comparison tests at \\(\\alpha=0.05\\)? (A) Yes, the p-values sum to about 2.31. (B) Yes, they sum to about 2.59. (C) No: we aren't told the distributions are approximately normal and the samples (7, 6, 6) are too small for the Central Limit Theorem. (D) No: we are given the exact times, so the population means can be computed directly.","ch":["A","B","C","D"],"a":"E","idea":"The samples are not independent: once one person names a dinosaur, the others cannot. So A and B fail. C's concern is fixable (permutation tests work here), and D is false because this isn't population data. NOTA.","trap":{"choice":"C","why":"A plausible-sounding normality objection: 54% of the field picked it, but small samples don't rule the tests out, dependence does."},"note":null,"setup":null,"fig":null,"stats":{"n":133,"dist":{"A":3,"B":11,"C":72,"D":10,"E":6,"blank":31},"pc":4.5,"pa":76.7,"top":18,"pct":99.8,"tier":5,"disc":1.34,"noisy":false,"extrap":true},"kind":"hard"},{"id":"2026-states-theta-ind-01","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":1,"topic":"Counting & probability","skill":"Summing overlapping lines in a configuration","q":"The diagram contains circles connected by lines, with 3 circles on each line. The integers 1 through 7 must be placed one per circle so that the three numbers on each line have the same sum. Which number cannot be placed in the lower left circle?","ch":["3","7","2","4"],"a":"D","idea":"With the apex \\(A\\) and line sum \\(S\\): the three lines through the apex give \\(2A+28=3S\\), and the two lines missing it give \\(28-A=2S\\). So \\(A=4\\), and 4 can only sit at the top.","trap":{"choice":"B","why":"Guessed the extreme value 7 rather than solving for the forced apex."},"note":null,"setup":null,"fig":"thetanet","stats":{"n":222,"dist":{"A":16,"B":96,"C":14,"D":36,"E":5,"blank":55},"pc":16.2,"pa":75.2,"top":39,"pct":99.9,"tier":5,"disc":0.52,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2026-states-theta-ind-02","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":2,"topic":"Functions & algebra","skill":"Radical equations and extraneous roots","q":"Solve for the sum of the values of \\(x\\): \\(x+9+4\\sqrt{2x+3}=0\\).","ch":["0","3","11","14"],"a":"A","idea":"Squaring gives \\(x^2-14x+33=0\\), so \\(x=3\\) or \\(11\\). Both make the left side positive, so both are extraneous and the sum over an empty set is 0.","trap":{"choice":"D","why":"Summed the two algebraic roots \\(3+11\\) without checking them in the original equation."},"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":44,"B":8,"C":18,"D":57,"E":43,"blank":52},"pc":19.8,"pa":76.6,"top":50,"pct":99.4,"tier":5,"disc":0.6,"noisy":false,"extrap":false},"kind":"trap"},{"id":"2026-states-theta-ind-03","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":3,"topic":"Geometry","skill":"Central angles and 30-60-90 triangles","q":"Two congruent triangles each have two vertices on a circle and one vertex at the center. Their combined area is \\(5\\sqrt3\\). If \\(m\\overset{\\frown}{BC}=m\\overset{\\frown}{AD}=60^\\circ\\), what is the circumference of the circle?","ch":["\\(5\\pi\\)","\\(\\pi\\sqrt5\\)","\\(2\\pi\\sqrt{10}\\)","\\(\\pi\\sqrt{10}\\)"],"a":"C","idea":"The two remaining arcs total \\(120^\\circ\\), so each central angle is \\(120^\\circ\\). Splitting one triangle into 30-60-90 pieces gives \\(b=\\frac{\\sqrt{10}}2\\) and \\(r=\\sqrt{10}\\), so the circumference is \\(2\\pi\\sqrt{10}\\).","trap":null,"note":"The original prints a figure showing the two triangles with vertices B, A on one side and C, D on the other.","setup":null,"fig":null,"stats":{"n":222,"dist":{"A":8,"B":10,"C":97,"D":22,"E":14,"blank":71},"pc":43.7,"pa":68.0,"top":86,"pct":59.5,"tier":2,"disc":1.02,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-theta-ind-04","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":4,"topic":"Matrices & vectors","skill":"2×2 determinants","q":"Find the determinant of \\(\\begin{bmatrix}4&3\\\\-9&10\\end{bmatrix}\\).","ch":["13","\\(-66\\)","\\(-6\\)","\\(-13\\)"],"a":"E","idea":"\\((4)(10)-(3)(-9)=40+27=67\\), which isn't listed, so NOTA.","trap":{"choice":"A","why":"Subtracted instead of adding the second product: \\(40-27=13\\)."},"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":33,"B":5,"C":10,"D":9,"E":141,"blank":24},"pc":63.5,"pa":89.2,"top":96,"pct":29.5,"tier":1,"disc":2.14,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-theta-ind-05","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":5,"topic":"Functions & algebra","skill":"Functional equations","q":"Suppose \\(f\\) is real-valued with \\(5f\\!\\left(\\frac1x\\right)+\\frac{f(2x)}{x^2}=x\\) for \\(x\\ne0\\). Find \\(f(1)\\).","ch":["\\(\\frac3{10}\\)","\\(\\frac1{21}\\)","\\(\\frac17\\)","\\(\\frac3{14}\\)"],"a":"D","idea":"Substituting \\(x=1\\) gives \\(5f(1)+f(2)=1\\); substituting \\(x=\\frac12\\) gives \\(5f(2)+4f(1)=\\frac12\\). Solving gives \\(f(1)=\\frac3{14}\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":12,"B":12,"C":36,"D":52,"E":2,"blank":108},"pc":23.4,"pa":51.4,"top":71,"pct":85.9,"tier":3,"disc":1.45,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-theta-ind-06","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":6,"topic":"Polynomials","skill":"Factor theorem","q":"If \\(g(x)=x^3-4x^2+ax-12\\) is divisible by \\((x-3)\\), find \\(a^2\\).","ch":["25","49","441","625"],"a":"B","idea":"\\(g(3)=-21+3a=0\\) gives \\(a=7\\), so \\(a^2=49\\).","trap":{"choice":"C","why":"Squared the wrong quantity, using \\(21\\) instead of \\(a=7\\)."},"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":5,"B":170,"C":7,"D":3,"E":7,"blank":30},"pc":76.6,"pa":86.5,"top":100,"pct":12.5,"tier":1,"disc":1.39,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-theta-ind-07","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":7,"topic":"Descriptive statistics","skill":"Mean versus median of a small set","q":"For \\(1<x<y\\), let \\(S=\\{1,x,y,x+y\\}\\). Compute the absolute difference between the mean and the median of \\(S\\).","ch":["\\(\\frac14\\)","\\(\\frac{y-1}{2}\\)","\\(x\\)","1"],"a":"A","idea":"The mean is \\(\\frac{1+2x+2y}{4}=\\frac14+\\frac{x+y}{2}\\) and the median is \\(\\frac{x+y}{2}\\), so the difference is \\(\\frac14\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":109,"B":25,"C":10,"D":8,"E":9,"blank":61},"pc":49.1,"pa":72.5,"top":93,"pct":48.2,"tier":1,"disc":1.3,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-theta-ind-08","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":8,"topic":"Functions & algebra","skill":"Systems with the floor function","q":"Compute the number of first-quadrant ordered pairs \\((x,y)\\) solving \\(x+\\lfloor y\\rfloor=5.3\\) and \\(y+\\lfloor x\\rfloor=5.7\\).","ch":["2","4","5","6"],"a":"D","idea":"Write \\(x=n+0.3\\) and \\(y=m+0.7\\); then \\(m+n=5\\), giving 6 pairs from \\((0,5)\\) to \\((5,0)\\).","trap":{"choice":"C","why":"Counted only 5, forgetting one endpoint of \\(m+n=5\\)."},"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":15,"B":28,"C":25,"D":42,"E":2,"blank":110},"pc":18.9,"pa":50.5,"top":71,"pct":92.1,"tier":4,"disc":1.35,"noisy":false,"extrap":false},"kind":"hard"},{"id":"2026-states-theta-ind-09","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":9,"topic":"Functions & algebra","skill":"Domains with radicals and removable holes","q":"What is the domain of \\(f(x)=\\dfrac{(x^2-4)\\sqrt{9x^2-9}}{x-2}\\)?","ch":["\\((-1,1)\\)","\\((-\\infty,-1]\\cup[1,\\infty)\\)","\\((-\\infty,-1]\\cup[1,2)\\cup(2,\\infty)\\)","\\((1,2)\\cup(2,\\infty)\\)"],"a":"C","idea":"The radical needs \\(|x|\\ge1\\) (endpoints included, since the radicand is 0 there) and the denominator excludes \\(x=2\\).","trap":{"choice":"B","why":"Forgot that \\(x=2\\) must still be excluded even though the factor cancels."},"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":2,"B":20,"C":131,"D":21,"E":12,"blank":36},"pc":59.0,"pa":83.8,"top":100,"pct":34.0,"tier":1,"disc":1.7,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-theta-ind-10","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":10,"topic":"Geometry","skill":"Volumes of cones and spheres","q":"A right cone's ratio of height to radius is \\(8:1\\), and the cone and a sphere have the same volume. What is the ratio of the sphere's radius to the cone's radius?","ch":["\\(\\sqrt[3]{2}\\)","\\(\\sqrt2\\)","\\(\\sqrt[3]{4}\\)","\\(\\frac1{\\sqrt[3]{2}}\\)"],"a":"A","idea":"\\(\\frac83\\pi r^3=\\frac43\\pi R^3\\) gives \\(R^3=2r^3\\), so \\(\\frac Rr=\\sqrt[3]2\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":93,"B":10,"C":16,"D":21,"E":11,"blank":71},"pc":41.9,"pa":68.0,"top":100,"pct":56.4,"tier":2,"disc":1.82,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-theta-ind-11","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":11,"topic":"Polynomials","skill":"Sum of coefficients of a quotient","q":"Let \\(Q(x)\\) be the quotient when \\(20x^{26}-26x^{20}+6\\) is divided by \\(x-1\\). Compute the sum of the coefficients of \\(Q(x)\\).","ch":["6","20","0","520"],"a":"C","idea":"Writing \\(P(x)=20(x^{26}-1)-26(x^{20}-1)\\) and dividing by \\(x-1\\) gives \\(Q(1)=20(26)-26(20)=0\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":27,"B":22,"C":80,"D":19,"E":15,"blank":59},"pc":36.0,"pa":73.4,"top":71,"pct":78.1,"tier":3,"disc":0.8,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-theta-ind-12","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":12,"topic":"Conics","skill":"Lattice points on a parabola","q":"Let \\(P\\) be the parabola with vertex at the origin and directrix \\(y=-1\\). Compute the number of lattice points on \\(P\\) whose distance to \\((0,1)\\) is at most 2026.","ch":["90","46","91","181"],"a":"C","idea":"\\(P\\) is \\(y=\\frac{x^2}4\\), so lattice points are \\((2k,k^2)\\) and the focal distance is \\(k^2+1\\le2026\\), giving \\(-45\\le k\\le45\\): 91 points.","trap":{"choice":"A","why":"Counted only positive \\(k\\), or forgot \\(k=0\\)."},"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":17,"B":11,"C":39,"D":12,"E":5,"blank":138},"pc":17.6,"pa":37.8,"top":46,"pct":99.6,"tier":5,"disc":0.63,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2026-states-theta-ind-13","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":13,"topic":"Sequences & series","skill":"Geometric sequences with a reciprocal condition","q":"Integers \\(a\\), \\(b\\), \\(c\\) satisfy \\(ar=b\\) and \\(br=c\\). If \\(a+b+c=21\\) and \\(\\frac1a+\\frac1b+\\frac1c=\\frac7{12}\\), what is the sum of all possible values of \\(a\\)?","ch":["3","9","12","15"],"a":"D","idea":"Both conditions give \\(\\frac{21}{b}=\\frac{7b}{12}\\), so \\(b=6\\) and \\(r=2\\) or \\(\\frac12\\). Then \\(a=3\\) or \\(12\\), summing to 15.","trap":{"choice":"C","why":"Reported a single value of \\(a\\) instead of the sum of both."},"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":15,"B":22,"C":29,"D":34,"E":5,"blank":117},"pc":15.3,"pa":47.3,"top":25,"pct":99.9,"tier":5,"disc":0.44,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2026-states-theta-ind-14","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":14,"topic":"Geometry","skill":"Chords and concentric circles","q":"A chord of the larger of two concentric circles is trisected by the smaller circle. The chord has length 36, and the sum of the two radii is also 36. Find the smaller radius.","ch":["14","12","16","15"],"a":"A","idea":"With the perpendicular distance \\(a\\): \\(a^2+6^2=r^2\\) and \\(a^2+18^2=R^2\\), so \\(R^2-r^2=288=(R+r)(R-r)=36(R-r)\\), giving \\(R-r=8\\) and \\(r=14\\).","trap":{"choice":"B","why":"Assumed the chord's trisection points split the radii in the same ratio, giving 12."},"note":null,"setup":null,"fig":"thetachord","stats":{"n":222,"dist":{"A":35,"B":41,"C":28,"D":9,"E":20,"blank":89},"pc":15.8,"pa":59.9,"top":46,"pct":99.8,"tier":5,"disc":0.62,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2026-states-theta-ind-15","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":15,"topic":"Exponents & logarithms","skill":"Exponential functions through two points","q":"For \\(f(x)=ab^x\\), it is given that \\(f(3)=6\\) and \\(f(6)=3\\). Find \\(b^{-a}\\).","ch":["4","8","16","32"],"a":"C","idea":"Dividing gives \\(b^3=\\frac12\\), so \\(b=2^{-1/3}\\) and \\(a=12\\). Then \\(b^{-a}=2^{4}=16\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":8,"B":20,"C":98,"D":6,"E":12,"blank":78},"pc":44.1,"pa":64.9,"top":96,"pct":56.5,"tier":2,"disc":1.26,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-theta-ind-16","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":16,"topic":"Number theory","skill":"Arithmetic in other bases","q":"In base \\(n\\), \\(524_n+312_n=1240_n\\). If the same equation in base 10 is \\(a+b=c\\), find the sum of the digits of \\(a\\), \\(b\\) and \\(c\\).","ch":["18","21","24","30"],"a":"D","idea":"Expanding gives \\(n^3-6n^2+n-6=0\\), so \\(n=6\\). Then \\(a=196\\), \\(b=116\\), \\(c=312\\), whose digits sum to \\(16+8+6=30\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":8,"B":17,"C":22,"D":50,"E":7,"blank":118},"pc":22.5,"pa":46.8,"top":82,"pct":86.4,"tier":3,"disc":1.51,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-theta-ind-17","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":17,"topic":"Sequences & series","skill":"Bounding the common difference of an arithmetic progression","q":"The sum of 2027 positive numbers in an increasing arithmetic progression is 1. If the width of the smallest interval containing all possible values of the common difference is \\(\\frac1K\\), find the last two digits of \\(K\\).","ch":["1","51","81","21"],"a":"B","idea":"The mean term gives \\(x+1013d=\\frac1{2027}\\), and positivity forces \\(0<d<\\frac1{2027\\cdot1013}\\). Then \\(K\\equiv27\\cdot13=351\\equiv51\\pmod{100}\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":9,"B":27,"C":18,"D":21,"E":2,"blank":145},"pc":12.2,"pa":34.7,"top":46,"pct":99.5,"tier":5,"disc":0.88,"noisy":false,"extrap":true},"kind":"hard"},{"id":"2026-states-theta-ind-18","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":18,"topic":"Geometry","skill":"Inscribed semicircles and similar triangles","q":"A semicircle with radius \\(DC\\) is inscribed in right triangle \\(ABC\\) and is tangent to \\(\\overline{AB}\\). If \\(AB=10\\) and \\(AC=4\\), find \\(BD-DC\\).","ch":["\\(\\frac67\\sqrt{21}\\)","\\(\\frac76\\sqrt{21}\\)","18","\\(\\frac37\\sqrt{21}\\)"],"a":"A","idea":"\\(BC=2\\sqrt{21}\\), and similar triangles give \\(BD-DC=BC\\cdot\\frac{AB-AC}{AB+AC}=2\\sqrt{21}\\cdot\\frac{6}{14}=\\frac67\\sqrt{21}\\).","trap":null,"note":null,"setup":null,"fig":"thetasemi","stats":{"n":222,"dist":{"A":76,"B":15,"C":5,"D":31,"E":8,"blank":87},"pc":34.2,"pa":60.8,"top":82,"pct":81.5,"tier":3,"disc":0.8,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-theta-ind-19","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":19,"topic":"Functions & algebra","skill":"Nonlinear systems by adding and subtracting","q":"Given \\(xy+9=y^2\\) and \\(xy+7=x^2\\), find the sum of the absolute values of all coordinates of the solutions.","ch":["4","8","\\(\\frac{17}4\\)","0"],"a":"B","idea":"Subtracting gives \\(y^2-x^2=2\\); adding gives \\((x-y)^2=16\\). The solutions are \\(\\left(\\frac74,-\\frac94\\right)\\) and \\(\\left(-\\frac74,\\frac94\\right)\\), whose absolute values sum to 8.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":14,"B":34,"C":25,"D":20,"E":6,"blank":123},"pc":15.3,"pa":44.6,"top":54,"pct":98.9,"tier":5,"disc":0.85,"noisy":false,"extrap":false},"kind":"hard"},{"id":"2026-states-theta-ind-20","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":20,"topic":"Exponents & logarithms","skill":"Logarithmic equations with extraneous roots","q":"Find the product of all solutions to \\(\\sqrt{\\dfrac{\\log\\sqrt{3x}}{\\log x}}\\cdot\\dfrac{\\log x}{\\log 3}=-1\\).","ch":["1","\\(\\frac13\\)","\\(\\frac19\\)","3"],"a":"C","idea":"Setting \\(a=\\frac{\\log3}{\\log x}\\) gives \\(2a^2-a-1=0\\), so \\(a=1\\) or \\(-\\frac12\\), i.e. \\(x=3\\) or \\(\\frac19\\). Only \\(\\frac19\\) survives the square root, so the product is \\(\\frac19\\).","trap":{"choice":"B","why":"Kept both roots and multiplied, or mis-solved the quadratic."},"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":15,"B":34,"C":35,"D":20,"E":6,"blank":112},"pc":15.8,"pa":49.5,"top":39,"pct":99.9,"tier":5,"disc":0.58,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2026-states-theta-ind-21","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":21,"topic":"Polynomials","skill":"Building a quartic from repeated maxima","q":"A quartic \\(P(x)\\) with real coefficients satisfies \\(P(1)=0\\) and attains a maximum value of 3 at both \\(x=2\\) and \\(x=3\\). Compute \\(P(5)\\).","ch":["\\(-24\\)","\\(-21\\)","\\(-12\\)","\\(-6\\)"],"a":"A","idea":"\\(P(x)-3=a(x-2)^2(x-3)^2\\), and \\(P(1)=0\\) gives \\(a=-\\frac34\\). Then \\(P(5)=-\\frac34(9)(4)+3=-24\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":20,"B":17,"C":25,"D":19,"E":3,"blank":138},"pc":9.0,"pa":37.8,"top":21,"pct":99.9,"tier":5,"disc":0.52,"noisy":false,"extrap":true},"kind":"hard"},{"id":"2026-states-theta-ind-22","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":22,"topic":"Geometry","skill":"Tangent circles and similar right triangles","q":"Circles \\(O_1\\) and \\(O_2\\) are tangent to each other, with \\(O_1\\) of radius 1. Points \\(A\\), \\(B\\), \\(P\\) satisfy: \\(P\\) lies on line \\(O_1O_2\\); ray \\(PA\\) is tangent to \\(O_1\\) at \\(A\\) and to \\(O_2\\) at \\(B\\); and \\(A\\) is the midpoint of \\(\\overline{PB}\\). Find the area of quadrilateral \\(AO_1O_2B\\).","ch":["3","\\(2\\sqrt3\\)","\\(3\\sqrt2\\)","\\(2\\sqrt6\\)"],"a":"C","idea":"\\(\\triangle PO_1A\\sim\\triangle PO_2B\\) with ratio 2, so \\(PO_1=O_1O_2=3\\) and \\(PA=2\\sqrt2\\). The trapezoid with bases 1 and 2 and height \\(2\\sqrt2\\) has area \\(3\\sqrt2\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":3,"B":18,"C":57,"D":16,"E":2,"blank":126},"pc":25.7,"pa":43.2,"top":64,"pct":93.2,"tier":4,"disc":0.79,"noisy":false,"extrap":false},"kind":"hard"},{"id":"2026-states-theta-ind-23","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":23,"topic":"Number theory","skill":"Divisibility by 9 and 11","q":"If the number \\(A8640543981270644B\\) is divisible by 99, compute \\(A^2+B^2\\).","ch":["81","82","100","32"],"a":"B","idea":"The alternating-sum rule gives \\(A-B\\equiv8\\pmod{11}\\) and the digit-sum rule gives \\(A+B\\equiv1\\pmod 9\\). The only digits are \\(A=9\\), \\(B=1\\), so \\(A^2+B^2=82\\).","trap":{"choice":"A","why":"Took \\(A=9,B=0\\) (or similar) without satisfying both divisibility rules."},"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":10,"B":63,"C":22,"D":6,"E":9,"blank":112},"pc":28.4,"pa":49.5,"top":71,"pct":90.9,"tier":4,"disc":0.76,"noisy":false,"extrap":false},"kind":"hard"},{"id":"2026-states-theta-ind-24","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":24,"topic":"Functions & algebra","skill":"Symmetric algebraic identities","q":"If \\((a^2+b^2)^3=(a^3+b^3)^2\\) and \\(ab\\ne0\\), find the value of \\(\\frac ab+\\frac ba\\).","ch":["1","\\(\\frac23\\)","\\(\\frac8{27}\\)","Cannot be determined"],"a":"B","idea":"Expanding gives \\(3a^4b^2+3a^2b^4=2a^3b^3\\); dividing by \\(a^2b^2\\) and then by \\(ab\\) gives \\(\\frac ab+\\frac ba=\\frac23\\).","trap":{"choice":"A","why":"Assumed symmetry forces the value 1."},"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":14,"B":30,"C":23,"D":32,"E":4,"blank":119},"pc":13.5,"pa":46.4,"top":46,"pct":98.5,"tier":5,"disc":1.02,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2026-states-theta-ind-25","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":25,"topic":"Random variables & expected value","skill":"Expected value with a cost to play","q":"A lottery costs \\$7 to play. The probability of winning a \\$28 payout is \\(\\frac27\\); otherwise there is no payout. What is the expected value of the lottery?","ch":["\\$0.80","\\$1.00","\\$1.40","\\$3.00"],"a":"B","idea":"The net gain is \\$21 with probability \\(\\frac27\\) and \\(-\\$7\\) with probability \\(\\frac57\\): \\(21\\cdot\\frac27-7\\cdot\\frac57=\\$1.00\\).","trap":{"choice":"D","why":"Used the \\$28 payout without subtracting the \\$7 cost."},"note":null,"setup":["2026-theta-ev"],"fig":null,"stats":{"n":222,"dist":{"A":11,"B":84,"C":29,"D":16,"E":6,"blank":76},"pc":37.8,"pa":65.8,"top":79,"pct":76.4,"tier":3,"disc":0.74,"noisy":false,"extrap":false},"kind":null},{"id":"2026-states-theta-ind-26","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":26,"topic":"Random variables & expected value","skill":"Expected value over a deck of cards","q":"A card is drawn from a standard 52-card deck (no jokers). A face card wins \\$10, a prime-numbered card wins \\$8, and anything else loses \\$12. Find the expected value of the game.","ch":["\\$0","\\(-\\$\\frac{10}{13}\\)","\\(-\\$\\frac5{13}\\)","\\(\\$\\frac8{13}\\)"],"a":"B","idea":"There are 12 face cards, 16 primes (2, 3, 5, 7) and 24 others: \\(\\frac{120+128-288}{52}=-\\frac{10}{13}\\).","trap":{"choice":"C","why":"Miscounted the prime ranks, for example counting only 2, 3, 5 or including 1."},"note":null,"setup":["2026-theta-ev"],"fig":null,"stats":{"n":222,"dist":{"A":7,"B":66,"C":21,"D":15,"E":15,"blank":98},"pc":29.7,"pa":55.9,"top":64,"pct":95.4,"tier":4,"disc":0.54,"noisy":false,"extrap":false},"kind":"trap"},{"id":"2026-states-theta-ind-27","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":27,"topic":"Random variables & expected value","skill":"Expected value by counting favorable cases","q":"A digital watch displays digits 0 through 9 using a subset of seven segments. If a randomly chosen segment fails to light, compute the expected number of digits that can still be displayed.","ch":["3","\\(\\frac{19}7\\)","\\(\\frac{18}7\\)","\\(\\frac{22}7\\)"],"a":"D","idea":"For each digit, count the segments it doesn't use: \\(1,5,2,2,3,2,1,4,0,2\\), summing to 22. Dividing by the 7 equally likely failures gives \\(\\frac{22}7\\).","trap":null,"note":null,"setup":["2026-theta-ev"],"fig":"thetaseg","stats":{"n":222,"dist":{"A":14,"B":25,"C":22,"D":43,"E":6,"blank":112},"pc":19.4,"pa":49.5,"top":36,"pct":99.9,"tier":5,"disc":0.49,"noisy":false,"extrap":true},"kind":"hard"},{"id":"2026-states-theta-ind-28","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":28,"topic":"Random variables & expected value","skill":"Expected number of trials before a repeat","q":"A six-sided die shows \\$12, \\$12, \\$16, \\$16, \\$26, \\$26. The die is rolled repeatedly and the player wins each amount shown until an amount repeats, when the game ends. Compute the expected winnings.","ch":["36","44","52","60"],"a":"C","idea":"Each roll averages \\$18, and the game lasts 2, 3 or 4 rolls with probabilities \\(\\frac13,\\frac49,\\frac29\\), averaging \\(\\frac{26}9\\) rolls. So the expected winnings are \\(\\frac{26}9\\cdot18=52\\).","trap":{"choice":"B","why":"Assumed the game lasts about 2.5 rolls, or added the distinct face values."},"note":null,"setup":["2026-theta-ev"],"fig":null,"stats":{"n":222,"dist":{"A":20,"B":28,"C":44,"D":9,"E":4,"blank":117},"pc":19.8,"pa":47.3,"top":29,"pct":80.2,"tier":3,"disc":0.09,"noisy":true,"extrap":true},"kind":"trap"},{"id":"2026-states-theta-ind-29","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":29,"topic":"Number theory","skill":"Divisibility of products of consecutive integers","q":"What is the greatest integer that always divides \\(n^3(n^2-1)(n^2-4)\\) for every integer \\(n>2026\\)?","ch":["360","180","120","40"],"a":"A","idea":"The expression is \\(n^2(n-2)(n-1)n(n+1)(n+2)\\), a product of five consecutive integers times \\(n^2\\). That guarantees factors of 5, 8 and 9, so 360.","trap":{"choice":"C","why":"Stopped at \\(5!=120\\), missing the extra factors of 2 and 3 from \\(n^2\\)."},"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":23,"B":20,"C":29,"D":13,"E":10,"blank":127},"pc":10.4,"pa":42.8,"top":18,"pct":99.9,"tier":5,"disc":0.4,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2026-states-theta-ind-30","year":2026,"comp":"State Convention","div":"Theta","test":"Individual","n":30,"topic":"Number theory","skill":"Recognizing perfect squares","q":"September 27th, 2025 is a 'perfect square day' because 9,272,025 and 27,092,025 are both perfect squares. What is the sum of the square roots of those numbers?","ch":["8,110","8,250","8,350","9,150"],"a":"B","idea":"\\(\\sqrt{9{,}272{,}025}=3045\\) and \\(\\sqrt{27{,}092{,}025}=5205\\), which sum to 8250.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":222,"dist":{"A":8,"B":45,"C":28,"D":15,"E":6,"blank":120},"pc":20.3,"pa":45.9,"top":25,"pct":99.9,"tier":5,"disc":0.22,"noisy":false,"extrap":true},"kind":"hard"},{"id":"2025-states-alpha-ind-01","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":1,"topic":"Coordinate geometry","skill":"Line intersection + distance","q":"How far from the origin is the intersection point of the lines \\(y=2x+3\\) and \\(y=3x+2\\)?","ch":["\\(2\\sqrt5\\)","\\(\\sqrt{26}\\)","\\(5\\sqrt2\\)","\\(3\\sqrt3\\)"],"a":"B","idea":"The lines meet at \\((1,5)\\), which is \\(\\sqrt{26}\\) from the origin.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":3,"B":205,"C":4,"D":4,"E":1,"blank":13},"pc":89.1,"pa":94.3,"top":100,"pct":8.6,"tier":1,"disc":3.0,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-02","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":2,"topic":"Exponents & logarithms","skill":"Nested radicals as exponents","q":"For real \\(x\\), if \\(\\sqrt{\\sqrt[3]{\\sqrt[4]{x}}}=2\\), what is \\(\\sqrt{\\sqrt{\\sqrt{x}}}\\)?","ch":["4","8","16","64"],"a":"B","idea":"\\(x^{1/24}=2\\), so \\(x^{1/8}=2^3=8\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":2,"B":190,"C":14,"D":11,"E":0,"blank":13},"pc":82.6,"pa":94.3,"top":100,"pct":12.5,"tier":1,"disc":2.46,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-03","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":3,"topic":"Functions & algebra","skill":"Maximum of a quadratic","q":"What is the maximum value of \\(f(x)=8-(2x+1)^2\\)?","ch":["16","9","8","6"],"a":"C","idea":"The squared term is at least 0, so the maximum is 8, at \\(x=-\\frac12\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":2,"B":6,"C":172,"D":8,"E":10,"blank":32},"pc":74.8,"pa":86.1,"top":100,"pct":18.1,"tier":1,"disc":2.08,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-04","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":4,"topic":"Conics","skill":"Ellipse from foci and vertices","q":"An ellipse has foci \\((\\pm6,0)\\) and vertices \\((\\pm10,0)\\). Find the product of its \\(y\\)-intercepts.","ch":["\\(-36\\)","\\(-48\\)","\\(-64\\)","\\(-136\\)"],"a":"C","idea":"\\(b^2=a^2-c^2=64\\), so the \\(y\\)-intercepts are \\(\\pm8\\) and their product is \\(-64\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":16,"B":7,"C":123,"D":5,"E":4,"blank":75},"pc":53.5,"pa":67.4,"top":100,"pct":41.8,"tier":1,"disc":1.99,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-05","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":5,"topic":"Functions & algebra","skill":"Evaluating compositions","q":"For \\(f(x)=x^2-x\\) and \\(g(x)=x+1\\), what is \\((f\\circ g)(2)-(g\\circ f)(2)\\)?","ch":["\\(-3\\)","3","6","0"],"a":"B","idea":"\\(f(g(2))=f(3)=6\\) and \\(g(f(2))=g(2)=3\\), so the difference is 3.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":3,"B":208,"C":3,"D":2,"E":3,"blank":11},"pc":90.4,"pa":95.2,"top":100,"pct":5.2,"tier":1,"disc":2.14,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-06","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":6,"topic":"Trigonometry","skill":"Quadrant from sign conditions","q":"Let \\(\\sin\\theta=\\frac12\\) and \\(\\tan\\theta<0\\). What is the value of \\(\\sec^2\\theta\\)?","ch":["2","\\(\\frac32\\)","\\(\\frac43\\)","3"],"a":"C","idea":"\\(\\theta\\) is in Quadrant II with \\(\\cos\\theta=-\\frac{\\sqrt3}2\\), so \\(\\sec^2\\theta=\\frac43\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":6,"B":7,"C":194,"D":4,"E":2,"blank":17},"pc":84.3,"pa":92.6,"top":100,"pct":11.3,"tier":1,"disc":2.54,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-07","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":7,"topic":"Trigonometry","skill":"Sine graph: amplitude, midline, period","q":"Let \\(a,b,c\\) be positive integers and \\(f(x)=a\\sin(bx)+c\\). If \\(f\\) has range \\([-4,12]\\) and passes through \\(\\left(\\frac\\pi4,12\\right)\\), what is the least possible value of \\(a\\cdot b\\cdot c\\)?","ch":["8","16","32","64"],"a":"D","idea":"From the range, \\(a=8\\) and \\(c=4\\). Then \\(\\sin\\frac{b\\pi}4=1\\) requires \\(b=2+8m\\), so the smallest is \\(b=2\\) and \\(abc=64\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":5,"B":7,"C":17,"D":143,"E":5,"blank":53},"pc":62.2,"pa":77.0,"top":100,"pct":30.6,"tier":1,"disc":1.72,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-08","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":8,"topic":"Matrices & vectors","skill":"Dot product → quadratic","q":"The dot product of \\(\\langle 2t,\\,t+2\\rangle\\) and \\(\\langle -2,\\,t+1\\rangle\\) is 8. What is the product of all possible values of \\(t\\)?","ch":["6","\\(-6\\)","3","\\(-2\\)"],"a":"B","idea":"\\(-4t+(t+2)(t+1)=8\\) simplifies to \\(t^2-t-6=0\\), and by Vieta's formulas the product is \\(-6\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":7,"B":130,"C":8,"D":18,"E":9,"blank":58},"pc":56.5,"pa":74.8,"top":93,"pct":37.5,"tier":1,"disc":1.36,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-09","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":9,"topic":"Coordinate geometry","skill":"Area split by a line","q":"A rectangle has vertices \\((0,0),(0,8),(4,8),(4,0)\\). The line \\(y=kx\\) divides the rectangular region into two regions, where the area to the left of the line is \\(\\frac13\\) the area to the right. What is \\(k\\)?","ch":["\\(\\frac32\\)","3","\\(\\frac52\\)","5"],"a":"E","idea":"The left region must have area 8. If the line exited the right side, we'd need \\(k=3\\), but then it reaches \\(y=12>8\\) at \\(x=4\\), outside the rectangle. So it exits the top at \\(x=\\frac8k\\), and \\(\\frac12\\cdot8\\cdot\\frac8k=8\\) gives \\(k=4\\): NOTA.","trap":{"choice":"B","why":"Assumed the line exits through the right side, which gives \\(k=3\\)."},"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":14,"B":39,"C":16,"D":8,"E":89,"blank":64},"pc":38.7,"pa":72.2,"top":86,"pct":66.1,"tier":2,"disc":1.36,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-10","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":10,"topic":"Trigonometry","skill":"Half-angle with the quadrant of A/2","q":"Given \\(\\sin A=-\\frac{2\\sqrt2}3\\) with \\(\\frac{3\\pi}2<A<2\\pi\\), what is the value of \\(\\cos\\frac A2\\)?","ch":["\\(-\\frac{\\sqrt3}6\\)","\\(\\frac{\\sqrt6}2\\)","\\(-\\frac{\\sqrt6}3\\)","\\(\\frac{\\sqrt3}6\\)"],"a":"C","idea":"\\(\\cos A=\\frac13\\), and \\(\\frac A2\\) is in Quadrant II, so \\(\\cos\\frac A2=-\\sqrt{\\frac{1+1/3}2}=-\\frac{\\sqrt6}3\\).","trap":{"choice":"E","why":"Took the positive root \\(+\\frac{\\sqrt6}3\\), which isn't listed."},"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":17,"B":12,"C":90,"D":14,"E":24,"blank":73},"pc":39.1,"pa":68.3,"top":96,"pct":63.7,"tier":2,"disc":1.6,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-11","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":11,"topic":"Exponents & logarithms","skill":"Solving an exponential equation","q":"Solve \\(\\frac12=\\frac4{1+e^{-x}}\\) for \\(x\\).","ch":["0","\\(\\ln7\\)","\\(\\ln\\frac17\\)","\\(\\ln\\frac13\\)"],"a":"C","idea":"\\(1+e^{-x}=8\\), so \\(e^{-x}=7\\) and \\(x=\\ln\\frac17\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":3,"B":8,"C":176,"D":4,"E":12,"blank":27},"pc":76.5,"pa":88.3,"top":100,"pct":14.7,"tier":1,"disc":1.73,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-12","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":12,"topic":"Exponents & logarithms","skill":"Nested logs + change of base","q":"If \\(\\log_2(\\log_4(\\log_{16}x))=4\\), what is \\(\\log_2(\\log_2x)\\)?","ch":["16","17","32","34"],"a":"D","idea":"\\(\\log_{16}x=4^{16}=2^{32}\\), so \\(\\log_2x=4\\cdot2^{32}=2^{34}\\) and the answer is 34.","trap":{"choice":"C","why":"Stopped at \\(\\log_{16}x=2^{32}\\), forgetting the factor of 4 when converting to base 2."},"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":27,"B":8,"C":33,"D":89,"E":15,"blank":58},"pc":38.7,"pa":74.8,"top":100,"pct":62.9,"tier":2,"disc":1.85,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-13","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":13,"topic":"Sequences & series","skill":"Arithmetic series → quadratic in n","q":"Determine the value of \\(n\\) such that \\(\\sum_{k=1}^{n}(7k-20)=4940\\).","ch":["39","40","41","80"],"a":"B","idea":"\\(\\frac{7n(n+1)}2-20n=4940\\) simplifies to \\(7n^2-33n-9880=0\\), so \\(n=40\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":10,"B":92,"C":21,"D":5,"E":8,"blank":94},"pc":40.0,"pa":59.1,"top":96,"pct":61.5,"tier":2,"disc":1.73,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-14","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":14,"topic":"Functions & algebra","skill":"Vertical asymptotes of ln|p(x)|","q":"What is the product of the \\(x\\)-coordinates of all vertical asymptotes of \\(f(x)=\\ln|x^4-13x^2+36|\\)?","ch":["4","6","36","48"],"a":"C","idea":"\\(x^4-13x^2+36=(x^2-4)(x^2-9)\\) has zeros \\(\\pm2,\\pm3\\), whose product is 36.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":4,"B":15,"C":99,"D":9,"E":8,"blank":95},"pc":43.0,"pa":58.7,"top":100,"pct":57.4,"tier":2,"disc":1.66,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-15","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":15,"topic":"Conics","skill":"Hyperbola asymptote intercept","q":"Consider a hyperbola of the form \\(\\frac{(x-b)^2}{b^2}-\\frac{(y-b)^2}{(b+1)^2}=1\\) where \\(b>0\\). What is the \\(x\\)-coordinate of the \\(x\\)-intercept with negative slope?","ch":["\\(\\frac{b(2b+1)}{b+1}\\)","\\(\\frac{b(2b-1)}{b+1}\\)","\\(\\frac{b(2b+1)}{b-1}\\)","\\(b+1\\)"],"a":null,"idea":"The intended answer is A, the \\(x\\)-intercept of the asymptote with negative slope: \\(b+\\frac{b^2}{b+1}\\).","trap":null,"note":"Thrown out. The question asks about the hyperbola's own x-intercept, but the answer choices only fit the asymptote's x-intercept. As written, the answer is NOTA.","setup":null,"fig":null,"stats":{"n":230,"dist":{"A":51,"B":12,"C":12,"D":4,"E":11,"blank":140},"thrown":true},"kind":null},{"id":"2025-states-alpha-ind-16","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":16,"topic":"Functions & algebra","skill":"Self-inverse rational functions","q":"Let \\(f(x)=\\frac{3x+5}{2x+k}\\). What value of \\(k\\) makes \\(f^{-1}(x)=f(x)\\)?","ch":["\\(-3\\)","\\(-1\\)","1","3"],"a":"A","idea":"\\(\\frac{ax+b}{cx+d}\\) is its own inverse when \\(a+d=0\\), so \\(k=-3\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":128,"B":10,"C":10,"D":10,"E":5,"blank":67},"pc":55.7,"pa":70.9,"top":100,"pct":39.0,"tier":1,"disc":1.43,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-17","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":17,"topic":"Polynomials","skill":"Parabola through three points","q":"A parabola \\(f(x)=ax^2+bx+c\\) passes through \\((3,3)\\), \\((4,15)\\), and \\((-1,35)\\). What is \\(f(2)\\)?","ch":["\\(-1\\)","1","\\(-3\\)","15"],"a":"A","idea":"Subtracting pairs of equations gives \\(7a+b=12\\) and \\(2a+b=-8\\), so \\(a=4\\), \\(b=-16\\), \\(c=15\\), and \\(f(2)=-1\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":101,"B":14,"C":15,"D":14,"E":4,"blank":82},"pc":43.9,"pa":64.3,"top":100,"pct":55.3,"tier":2,"disc":1.84,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-18","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":18,"topic":"Coordinate geometry","skill":"Reflections over lines","q":"The point \\(P(8,1)\\) is reflected about the line \\(y=2x\\) to form \\(P'\\). Point \\(P'\\) is reflected about the line \\(y=4\\) to form \\(P''\\). What is the distance between \\(P\\) and \\(P''\\)?","ch":["12","14","\\(2\\sqrt{37}\\)","\\(2\\sqrt{35}\\)"],"a":"A","idea":"Reflecting over \\(y=2x\\) gives \\(P'=(-4,7)\\), then \\(P''=(-4,1)\\). The distance from \\((8,1)\\) is 12.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":63,"B":13,"C":16,"D":2,"E":6,"blank":130},"pc":27.4,"pa":43.5,"top":96,"pct":79.7,"tier":3,"disc":1.77,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-19","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":19,"topic":"Coordinate geometry","skill":"Symmetry → triangle area","q":"The line \\(y=x\\) is both an angle bisector and a perpendicular bisector for \\(\\triangle ABC\\). If two of the vertices are \\(A(0,0)\\) and \\(B(4,6)\\), what is the area of \\(\\triangle ABC\\)?","ch":["20","12","10","8"],"a":"C","idea":"The triangle is symmetric about \\(y=x\\), so \\(C=(6,4)\\). The area is \\(\\frac12|4\\cdot4-6\\cdot6|=10\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":11,"B":29,"C":87,"D":7,"E":4,"blank":92},"pc":37.8,"pa":60.0,"top":93,"pct":68.1,"tier":2,"disc":1.31,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-20","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":20,"topic":"Trigonometry","skill":"Determinant → sine difference","q":"Find the sum of all \\(\\theta\\) in \\([0,2\\pi)\\) such that \\(\\begin{vmatrix}\\sin2\\theta&\\cos2\\theta\\\\\\sin\\theta&\\cos\\theta\\end{vmatrix}=0\\).","ch":["0","\\(\\frac\\pi2\\)","\\(\\pi\\)","\\(\\frac{3\\pi}4\\)"],"a":"C","idea":"The determinant is \\(\\sin(2\\theta-\\theta)=\\sin\\theta\\), which is 0 at \\(\\theta=0,\\pi\\). The sum is \\(\\pi\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":13,"B":14,"C":113,"D":7,"E":8,"blank":75},"pc":49.1,"pa":67.4,"top":100,"pct":48.4,"tier":1,"disc":1.65,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-21","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":21,"topic":"Functions & algebra","skill":"Repeated composition cycles","q":"Let \\(f(x)=\\frac1{1-x}\\). Which of the following is \\((f\\circ f\\circ f\\circ f)(x)\\)?","ch":["\\(\\frac1{1+x}\\)","\\(-x\\)","\\(\\frac{1-x}x\\)","\\(\\frac1{1-x}\\)"],"a":"D","idea":"\\(f\\circ f\\circ f\\) is the identity, so the fourth composition is \\(f\\) itself.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":16,"B":9,"C":22,"D":99,"E":13,"blank":71},"pc":43.0,"pa":69.1,"top":96,"pct":59.0,"tier":2,"disc":1.38,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-22","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":22,"topic":"Complex numbers","skill":"Powers of 1 − i","q":"Let \\(i=\\sqrt{-1}\\). If \\((1-i)^3\\cdot(-1+i)^6=a+bi\\), find \\(a+b\\).","ch":["\\(-32\\)","\\(-16\\)","0","32"],"a":"C","idea":"\\((-1+i)^6=(1-i)^6\\), so the product is \\((1-i)^9=(1-i)\\cdot(-2i)^4=16-16i\\), and \\(a+b=0\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":13,"B":14,"C":115,"D":13,"E":3,"blank":72},"pc":50.0,"pa":68.7,"top":96,"pct":48.0,"tier":1,"disc":1.28,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-23","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":23,"topic":"Trigonometry","skill":"Double-angle chains","q":"What is the minimum value of \\(f(x)=\\sin x\\cos x\\cos2x\\cos4x\\)?","ch":["\\(-\\frac12\\)","\\(-\\frac14\\)","\\(-\\frac18\\)","\\(-\\frac1{16}\\)"],"a":"C","idea":"Applying the double-angle formula repeatedly gives \\(f=\\frac18\\sin8x\\), so the minimum is \\(-\\frac18\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":10,"B":16,"C":79,"D":5,"E":4,"blank":116},"pc":34.3,"pa":49.6,"top":96,"pct":71.1,"tier":2,"disc":1.58,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-24","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":24,"topic":"Trigonometry","skill":"Sides in arithmetic progression + Law of Cosines","q":"The sides of an obtuse triangle are in arithmetic progression, and the largest angle measures \\(120^\\circ\\). What is the ratio of the length of the largest side to the length of the shortest side?","ch":["7 : 5","7 : 3","5 : 3","7 : 2"],"a":"B","idea":"With sides \\(a-d,a,a+d\\), the Law of Cosines at \\(120^\\circ\\) gives \\(a=\\frac52d\\). The sides are in ratio \\(3:5:7\\), so the answer is \\(7:3\\).","trap":{"choice":"C","why":"Gave the ratio of the middle side to the shortest side, \\(5:3\\)."},"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":7,"B":82,"C":20,"D":10,"E":8,"blank":103},"pc":35.7,"pa":55.2,"top":93,"pct":75.6,"tier":3,"disc":1.0,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-25","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":25,"topic":"Functions & algebra","skill":"Holes and asymptotes of rational functions","q":"A function of the form \\(f(x)=\\frac{x^2+qx+r}{sx^2+tx+u}\\) has these properties: \\(f(0)=-1\\); its only hole is at \\((1,-1)\\); its only vertical asymptote is \\(x=-2\\); its only \\(x\\)-intercept is \\((4,0)\\). What is the value of \\(q\\cdot r\\cdot s\\cdot t\\cdot u\\)?","ch":["\\(-320\\)","\\(-160\\)","160","320"],"a":null,"idea":"Ignoring the hole's \\(y\\)-value, \\(s=2\\) gives \\(f=\\frac{(x-1)(x-4)}{2(x-1)(x+2)}\\) and a product of 320.","trap":null,"note":"Thrown out. The conditions contradict each other: f(0) = −1 forces s = 2, but then the hole is at (1, −1/2), not (1, −1).","setup":null,"fig":null,"stats":{"n":230,"dist":{"A":7,"B":19,"C":22,"D":54,"E":13,"blank":115},"thrown":true},"kind":null},{"id":"2025-states-alpha-ind-26","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":26,"topic":"Functions & algebra","skill":"Parametric equations with domain restrictions","q":"Which of these parametric equations have the same graph in the Cartesian plane as \\(y=x^2+4\\)? I. \\(x=e^{-t},\\ y=4e^{-2t}\\) II. \\(x=2\\cot t,\\ y=4\\csc^2t\\) III. \\(x=\\frac2{\\sqrt t},\\ y=\\frac{4t+4}t\\)","ch":["I only","II only","II and III only","I and III only"],"a":"B","idea":"II: \\(4\\csc^2t=4+4\\cot^2t=4+x^2\\) with all real \\(x\\), so it works. III follows the same equation but only for \\(x>0\\). I is a different curve.","trap":{"choice":"C","why":"Missed that III only covers \\(x>0\\), so it traces just half the parabola."},"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":7,"B":35,"C":53,"D":6,"E":8,"blank":121},"pc":15.2,"pa":47.4,"top":64,"pct":98.7,"tier":5,"disc":0.9,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2025-states-alpha-ind-27","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":27,"topic":"Trigonometry","skill":"Difference identity + excluded values","q":"Find the sum of all solutions on \\([0,4\\pi)\\) to \\(\\frac{\\sin5x\\cos3x-\\sin3x\\cos5x}{\\cos x}=1\\).","ch":["\\(\\pi\\)","\\(2\\pi\\)","\\(3\\pi\\)","\\(5\\pi\\)"],"a":"E","idea":"The numerator is \\(\\sin2x\\), so the equation becomes \\(2\\sin x=1\\) with \\(\\cos x\\ne0\\). The solutions \\(\\frac\\pi6,\\frac{5\\pi}6,\\frac{13\\pi}6,\\frac{17\\pi}6\\) sum to \\(6\\pi\\): NOTA.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":9,"B":20,"C":14,"D":9,"E":68,"blank":110},"pc":29.6,"pa":52.2,"top":100,"pct":77.3,"tier":3,"disc":1.68,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-28","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":28,"topic":"Trigonometry","skill":"Pairing complementary angles","q":"Evaluate \\(\\sum_{n=1}^{90}\\sin^2(n^\\circ)\\).","ch":["44","44.5","45","45.5"],"a":"D","idea":"The pairs \\(n\\) and \\(90-n\\) for \\(n=1,\\dots,44\\) each sum to 1, giving 44. Then \\(\\sin^245^\\circ=\\frac12\\) and \\(\\sin^290^\\circ=1\\), for a total of 45.5.","trap":{"choice":"C","why":"Mishandled either the \\(\\sin^2 45^\\circ\\) term or the \\(\\sin^2 90^\\circ\\) term."},"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":10,"B":19,"C":27,"D":67,"E":1,"blank":106},"pc":29.1,"pa":53.9,"top":86,"pct":78.9,"tier":3,"disc":1.55,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-29","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":29,"topic":"Sequences & series","skill":"Infinite geometric series in sin²x","q":"Find the sum of the solutions in \\([0,2\\pi)\\) to \\(\\sum_{n=1}^{\\infty}\\sin^{2n}x=1\\).","ch":["\\(\\pi\\)","\\(2\\pi\\)","\\(4\\pi\\)","\\(6\\pi\\)"],"a":"C","idea":"\\(\\frac{s}{1-s}=1\\) with \\(s=\\sin^2x\\), so \\(\\sin^2x=\\frac12\\). The four solutions \\(\\frac\\pi4,\\frac{3\\pi}4,\\frac{5\\pi}4,\\frac{7\\pi}4\\) sum to \\(4\\pi\\).","trap":{"choice":"B","why":"Only solved \\(\\sin x=+\\frac{\\sqrt2}2\\)."},"note":null,"setup":null,"fig":null,"stats":{"n":230,"dist":{"A":10,"B":26,"C":60,"D":8,"E":1,"blank":125},"pc":26.1,"pa":45.7,"top":100,"pct":80.7,"tier":3,"disc":1.89,"noisy":false,"extrap":false},"kind":null},{"id":"2025-states-alpha-ind-30","year":2025,"comp":"State Convention","div":"Alpha","test":"Individual","n":30,"topic":"Geometry","skill":"Region area using overlapping circles","q":"Define region \\(S\\) as the set of points \\((x,y)\\) satisfying \\((x-1)^2+y^2\\ge4\\), \\((x+1)^2+y^2\\ge4\\), and \\(x^2+y^2\\le9\\). What is the area of \\(S\\)?","ch":["\\(\\frac{11\\pi}3-2\\sqrt3\\)","\\(\\frac{7\\pi}3+2\\sqrt3\\)","\\(5\\pi\\)","\\(\\frac{10\\pi}3-\\sqrt3\\)"],"a":"A","idea":"Both small circles lie inside the big one, and their overlap has area \\(\\frac{8\\pi}3-2\\sqrt3\\). So \\(S=9\\pi-\\left(8\\pi-\\frac{8\\pi}3+2\\sqrt3\\right)=\\frac{11\\pi}3-2\\sqrt3\\).","trap":null,"note":null,"setup":null,"fig":"regionS","stats":{"n":230,"dist":{"A":56,"B":14,"C":11,"D":2,"E":2,"blank":145},"pc":24.3,"pa":37.0,"top":89,"pct":87.8,"tier":3,"disc":1.27,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-01","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":1,"topic":"Number theory","skill":"Factoring to count integer solutions","q":"Let \\(D\\) be the number of ordered pairs of positive integers \\((x,y)\\) with \\(xy-3x-5y+7=8\\). Find \\(D\\).","ch":["2","3","4","5"],"a":"D","idea":"Factor: \\((x-5)(y-3)=16\\). Only the positive factor pairs work, since \\(x-5\\ge-4\\) and \\(y-3\\ge-2\\) rule out the negative ones. That gives 5.","trap":{"choice":"C","why":"Dropped one of the positive factor pairs of 16."},"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":16,"B":11,"C":20,"D":57,"E":2,"blank":84},"pc":30.0,"pa":55.8,"top":82,"pct":76.7,"tier":3,"disc":1.65,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-02","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":2,"topic":"Trigonometry","skill":"Coterminal angles","q":"Angle \\(\\Theta\\) in standard position measures \\(\\frac{2024\\pi}3\\) radians. In which quadrant is its terminal ray?","ch":["I","II","III","IV"],"a":"B","idea":"\\(\\frac{2024\\pi}3=674\\pi+\\frac{2\\pi}3\\), and \\(674\\pi\\) is a whole number of rotations, so the ray is at \\(\\frac{2\\pi}3\\), in Quadrant II.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":14,"B":138,"C":16,"D":7,"E":1,"blank":14},"pc":72.6,"pa":92.6,"top":100,"pct":15.4,"tier":1,"disc":1.31,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-03","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":3,"topic":"Complex numbers","skill":"Weighted sums of powers of i","q":"If \\(\\sum_{n=1}^{10}n\\,i^n=\\alpha+\\beta i\\) for integers \\(\\alpha\\) and \\(\\beta\\), find \\(\\alpha+\\beta\\).","ch":["\\(-11\\)","\\(-5\\)","\\(-1\\)","1"],"a":"C","idea":"The real part is \\(-2+4-6+8-10=-6\\) and the imaginary part is \\(1-3+5-7+9=5\\), so \\(\\alpha+\\beta=-1\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":6,"B":5,"C":123,"D":3,"E":2,"blank":51},"pc":64.7,"pa":73.2,"top":100,"pct":27.6,"tier":1,"disc":2.19,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-04","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":4,"topic":"Coordinate geometry","skill":"Circle through three points","q":"Find the area of circle \\(O\\).","ch":["\\(10\\pi\\)","\\(13\\pi\\)","\\(18\\pi\\)","\\(20\\pi\\)"],"a":"E","idea":"Equal distances to the three points give the center \\((1,2)\\) and \\(r^2=25\\). The area is \\(25\\pi\\): NOTA.","trap":null,"note":null,"setup":["2024-circleO"],"fig":null,"stats":{"n":190,"dist":{"A":8,"B":10,"C":15,"D":9,"E":67,"blank":81},"pc":35.3,"pa":57.4,"top":100,"pct":64.8,"tier":2,"disc":2.47,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-05","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":5,"topic":"Coordinate geometry","skill":"Lattice points on a circle","q":"Find the number of lattice points that circle \\(O\\) passes through other than \\(A\\), \\(B\\), and \\(C\\).","ch":["0","1","5","9"],"a":"D","idea":"Radius 5 gives 12 lattice points (from \\(3^2+4^2=5^2\\) and \\(5^2+0^2\\)). Excluding \\(A\\), \\(B\\), and \\(C\\) leaves 9.","trap":{"choice":"C","why":"Missed some of the sign and order combinations of \\((\\pm3,\\pm4)\\) and \\((\\pm4,\\pm3)\\)."},"note":null,"setup":["2024-circleO"],"fig":null,"stats":{"n":190,"dist":{"A":4,"B":4,"C":26,"D":52,"E":2,"blank":102},"pc":27.4,"pa":46.3,"top":89,"pct":80.3,"tier":3,"disc":1.68,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-06","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":6,"topic":"Geometry","skill":"Inscribed angle → half-angle tangent","q":"Point \\(D\\) is on circle \\(O\\) at \\((3,k)\\), where \\(k\\) is maximized. Find \\(\\tan\\angle CDA\\).","ch":["\\(-2\\)","\\(-\\frac12\\)","\\(\\frac12\\)","2"],"a":"C","idea":"\\(\\angle CDA\\) is half of the central angle \\(\\angle COA\\), and \\(\\cos\\angle COA=\\frac35\\). So \\(\\tan\\frac{\\angle COA}2=\\frac{4/5}{1+3/5}=\\frac12\\).","trap":{"choice":"D","why":"Gave the reciprocal, \\(2\\)."},"note":null,"setup":["2024-circleO"],"fig":null,"stats":{"n":190,"dist":{"A":2,"B":7,"C":35,"D":12,"E":4,"blank":130},"pc":18.4,"pa":31.6,"top":36,"pct":99.9,"tier":5,"disc":0.47,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2024-states-alpha-ind-07","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":7,"topic":"Number theory","skill":"Legendre's formula","q":"Find the largest positive integer \\(q\\) such that \\(5^q\\) is a factor of \\(p!\\).","ch":["81","83","100","124"],"a":"D","idea":"\\(p=404+80+16+3=503\\), and then \\(q=100+20+4=124\\).","trap":null,"note":null,"setup":["2024-p5"],"fig":null,"stats":{"n":190,"dist":{"A":5,"B":14,"C":9,"D":65,"E":5,"blank":92},"pc":34.2,"pa":51.6,"top":96,"pct":66.1,"tier":2,"disc":2.55,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-08","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":8,"topic":"Number theory","skill":"Legendre's formula across primes","q":"\\(p\\) is also the largest positive integer such that \\(n^p\\) is a factor of \\(2024!\\), where \\(n\\) is a positive integer greater than 5. Determine the number of possible values of \\(n\\).","ch":["3","4","7","19"],"a":"D","idea":"The exponents in \\(2024!\\) are \\(v_2=2017\\), \\(v_3=1006\\), \\(v_5=503\\), and \\(v_7=335<503\\). So \\(n=2^a3^b5^c\\) with \\(a\\le4\\), \\(b\\le2\\), \\(c\\le1\\), and the bound must be tight: \\(b=2\\) or \\(c=1\\). That gives 20 values, minus \\(n=5\\), for 19.","trap":null,"note":null,"setup":["2024-p5"],"fig":null,"stats":{"n":190,"dist":{"A":11,"B":6,"C":17,"D":12,"E":12,"blank":132},"pc":6.3,"pa":30.5,"top":21,"pct":99.9,"tier":5,"disc":0.73,"noisy":false,"extrap":true},"kind":"hard"},{"id":"2024-states-alpha-ind-09","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":9,"topic":"Exponents & logarithms","skill":"Change of base with approximations","q":"If \\(\\log2\\approx0.30\\) and \\(\\log3\\approx0.48\\), which of the following is closest to \\(\\log_{48}27\\)?","ch":["\\(\\frac45\\)","\\(\\frac56\\)","\\(\\frac67\\)","\\(\\frac89\\)"],"a":"C","idea":"\\(\\frac{3(0.48)}{4(0.30)+0.48}=\\frac{1.44}{1.68}=\\frac67\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":14,"B":9,"C":93,"D":10,"E":5,"blank":59},"pc":48.9,"pa":68.9,"top":96,"pct":46.7,"tier":1,"disc":1.99,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-10","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":10,"topic":"Conics","skill":"Identifying a conic after squaring","q":"The graph of \\(\\sqrt x+\\sqrt y=2\\) is shown. What larger conic section is this graph a part of?","ch":["Circle","Ellipse (non-circular)","Hyperbola","Parabola"],"a":"D","idea":"Squaring twice gives \\(x^2-2xy+y^2-8x-8y+16=0\\), and \\(B^2-4AC=4-4=0\\), so it's a parabola.","trap":{"choice":"C","why":"Judged by the picture, where the arc looks like a hyperbola branch."},"note":null,"setup":null,"fig":"sqrtcurve","stats":{"n":190,"dist":{"A":24,"B":24,"C":64,"D":32,"E":4,"blank":42},"pc":16.8,"pa":77.9,"top":39,"pct":99.9,"tier":5,"disc":0.46,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2024-states-alpha-ind-11","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":11,"topic":"Trigonometry","skill":"Rewriting as R cos(2θ + α)","q":"Determine the maximum value of \\(y=\\cos2\\theta-2\\sqrt3\\sin\\theta\\cos\\theta\\).","ch":["1","\\(2\\sqrt3\\)","\\(\\frac{\\sqrt3}2\\)","2"],"a":"D","idea":"\\(y=\\cos2\\theta-\\sqrt3\\sin2\\theta=2\\cos(2\\theta+60^\\circ)\\), so the maximum is 2.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":19,"B":17,"C":16,"D":71,"E":6,"blank":61},"pc":37.4,"pa":67.9,"top":93,"pct":64.9,"tier":2,"disc":1.75,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-12","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":12,"topic":"Functions & algebra","skill":"Periodic functions","q":"\\(f(x)\\) is a periodic function whose roots include 12, 16, and 24. Find the maximum possible period of \\(f(x)\\).","ch":["1","2","4","8"],"a":"E","idea":"Nothing ties the period to the roots. A function with any period can have its roots at 12, 16, and 24, so no maximum period exists: NOTA.","trap":{"choice":"D","why":"Assumed the period must be related to the gaps between the roots."},"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":1,"B":6,"C":29,"D":69,"E":28,"blank":57},"pc":14.7,"pa":70.0,"top":32,"pct":99.5,"tier":5,"disc":0.75,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2024-states-alpha-ind-13","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":13,"topic":"Complex numbers","skill":"Angles between complex numbers","q":"Find the sine of the reflex angle formed by segments drawn in the Argand plane from the origin to \\(z_1=7+i\\) and \\(z_2=-5+5i\\).","ch":["\\(-\\frac45\\)","\\(-\\frac35\\)","\\(\\frac35\\)","\\(\\frac45\\)"],"a":"A","idea":"The dot product gives \\(\\cos\\theta=\\frac{-35+5}{50}=-\\frac35\\), so \\(\\sin\\theta=\\frac45\\). The reflex angle \\(360^\\circ-\\theta\\) has sine \\(-\\frac45\\).","trap":{"choice":"D","why":"Gave the sine of the regular angle instead of the reflex angle."},"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":24,"B":11,"C":16,"D":39,"E":0,"blank":100},"pc":12.6,"pa":47.4,"top":46,"pct":99.0,"tier":5,"disc":0.98,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2024-states-alpha-ind-14","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":14,"topic":"Polynomials","skill":"Vieta's formulas","q":"Find the sum of the roots of \\(8x^3-4x^2+2x-1=0\\).","ch":["4","\\(-4\\)","\\(-\\frac12\\)","\\(\\frac12\\)"],"a":"D","idea":"By Vieta's formulas, the sum is \\(\\frac48=\\frac12\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":3,"B":3,"C":13,"D":132,"E":7,"blank":32},"pc":69.5,"pa":83.2,"top":96,"pct":18.4,"tier":1,"disc":1.25,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-15","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":15,"topic":"Trigonometry","skill":"Law of Cosines → sine","q":"Find the sine of the largest angle in a triangle with sides of length 13, 14, and 15.","ch":["\\(\\frac{21}{29}\\)","\\(\\frac{15}{17}\\)","\\(\\frac{12}{13}\\)","\\(\\frac{24}{25}\\)"],"a":"C","idea":"The largest angle is opposite 15: \\(\\cos=\\frac{169+196-225}{364}=\\frac5{13}\\), so \\(\\sin=\\frac{12}{13}\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":6,"B":7,"C":83,"D":10,"E":10,"blank":74},"pc":43.7,"pa":61.1,"top":93,"pct":55.2,"tier":2,"disc":1.8,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-16","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":16,"topic":"Geometry","skill":"Heron's formula","q":"Find the sum of the digits in the area of a triangle with sides of length 51, 52, and 53.","ch":["9","12","15","18"],"a":"A","idea":"\\(s=78\\), and the area is \\(\\sqrt{78\\cdot27\\cdot26\\cdot25}=1170\\), whose digits sum to 9.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":78,"B":13,"C":21,"D":5,"E":2,"blank":71},"pc":41.1,"pa":62.6,"top":96,"pct":57.5,"tier":2,"disc":2.11,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-17","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":17,"topic":"Sequences & series","skill":"Finding a linear recurrence","q":"A triangle with side lengths \\(n-1\\), \\(n\\), \\(n+1\\) is called nearly-equilateral. A triangle is Heronian if its side lengths and area are all integers. The triangles with sides 13-14-15 and 51-52-53 are Heronian nearly-equilateral triangles, and the fourth-smallest has \\(n=194\\). The values of \\(n\\) follow a recurrence \\(n_k=an_{k-1}+bn_{k-2}\\) for constants \\(a\\) and \\(b\\). Find \\(n\\) for the fifth-smallest Heronian nearly-equilateral triangle.","ch":["720","722","724","728"],"a":"C","idea":"From \\(52a+14b=194\\) and \\(14a+4b=52\\), \\(a=4\\) and \\(b=-1\\). The next value is \\(4\\cdot194-52=724\\).","trap":null,"note":"Adapted: the original refers to the triangles 'in the previous two questions.'","setup":null,"fig":null,"stats":{"n":190,"dist":{"A":3,"B":10,"C":33,"D":6,"E":3,"blank":135},"pc":17.4,"pa":28.9,"top":61,"pct":95.2,"tier":4,"disc":1.2,"noisy":false,"extrap":false},"kind":"hard"},{"id":"2024-states-alpha-ind-18","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":18,"topic":"Matrices & vectors","skill":"Markov chain transition matrices","q":"Which of the following, read left to right, gives the respective probabilities that Oliver is at points \\(A,B,C,D\\) after 2024 moves?","ch":["The first row of \\(M_1^{2024}\\)","The main diagonal of \\(M_1^{2024}\\)","The first row of \\(M_2^{2024}\\)","The main diagonal of \\(M_2^{2024}\\)"],"a":"E","idea":"The true transition matrix has rows \\(A:(0,\\frac13,\\frac13,\\frac13)\\) and \\(B,D:(\\frac12,0,\\frac12,0)\\). Neither \\(M_1\\) nor \\(M_2\\) matches it, so the answer is NOTA.","trap":{"choice":"A","why":"\\(M_1\\) is the adjacency matrix divided by 3, but \\(B\\) and \\(D\\) have only 2 paths each, so their rows don't sum to 1."},"note":null,"setup":["2024-walk"],"fig":null,"stats":{"n":190,"dist":{"A":31,"B":10,"C":20,"D":11,"E":6,"blank":112},"pc":3.2,"pa":41.1,"top":7,"pct":99.9,"tier":5,"disc":0.38,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2024-states-alpha-ind-19","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":19,"topic":"Matrices & vectors","skill":"Matrix products via row sums","q":"Find the sum of the entries of \\(M_1M_2\\).","ch":["1","\\(\\frac52\\)","3","\\(\\frac{10}3\\)"],"a":"D","idea":"Every row of \\(M_2\\) sums to 1, so \\(M_1M_2\\mathbf1=M_1\\mathbf1=\\frac13(3,2,3,2)\\), whose entries sum to \\(\\frac{10}3\\).","trap":null,"note":null,"setup":["2024-walk"],"fig":null,"stats":{"n":190,"dist":{"A":1,"B":7,"C":7,"D":65,"E":7,"blank":103},"pc":34.2,"pa":45.8,"top":79,"pct":74.1,"tier":2,"disc":1.26,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-20","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":20,"topic":"Geometry","skill":"Inscribed angles in a regular polygon","q":"In regular octagon \\(ZLUSATON\\), find \\(m\\angle SNO+m\\angle LUZ+2\\cdot m\\angle SAN+m\\angle TOS\\).","ch":["\\(315^\\circ\\)","\\(337.5^\\circ\\)","\\(360^\\circ\\)","\\(382.5^\\circ\\)"],"a":"A","idea":"Each side subtends \\(45^\\circ\\) of arc, and an inscribed angle is half its arc: \\(67.5+22.5+2(90)+45=315\\).","trap":null,"note":null,"setup":null,"fig":"octagon","stats":{"n":190,"dist":{"A":43,"B":18,"C":15,"D":7,"E":5,"blank":102},"pc":22.6,"pa":46.3,"top":68,"pct":92.1,"tier":4,"disc":1.07,"noisy":false,"extrap":false},"kind":"hard"},{"id":"2024-states-alpha-ind-21","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":21,"topic":"Counting & probability","skill":"Domino tilings → Fibonacci","q":"How many ways can a 2-by-12 rectangular region be completely covered by twelve 1-by-2 dominoes?","ch":["144","191","233","256"],"a":"C","idea":"Tilings of a 2-by-\\(n\\) strip satisfy \\(T_n=T_{n-1}+T_{n-2}\\), the Fibonacci recurrence. So \\(T_{12}=F_{13}=233\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":17,"B":10,"C":33,"D":12,"E":3,"blank":115},"pc":17.4,"pa":39.5,"top":57,"pct":97.5,"tier":4,"disc":0.93,"noisy":false,"extrap":false},"kind":"hard"},{"id":"2024-states-alpha-ind-22","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":22,"topic":"Functions & algebra","skill":"Mixture problems","q":"Gwen mixes 10 liters of a 25% salt solution with \\(\\ell\\) liters of a 60% salt solution to form a 40% salt solution. Find \\(\\ell\\).","ch":["2.5","6.4","7.5","8"],"a":"C","idea":"\\(2.5+0.6\\ell=0.4(10+\\ell)\\), so \\(\\ell=7.5\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":9,"B":10,"C":116,"D":11,"E":4,"blank":40},"pc":61.1,"pa":78.9,"top":100,"pct":31.5,"tier":1,"disc":2.01,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-23","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":23,"topic":"Functions & algebra","skill":"Rational inequalities","q":"Find the number of integers with absolute value at most 6 that satisfy \\(n-2\\le\\frac{2n^2-3n-8}{n+2}\\).","ch":["4","5","8","9"],"a":"A","idea":"The inequality becomes \\(\\frac{(n-4)(n+1)}{n+2}\\ge0\\), which holds on \\((-2,-1]\\cup[4,\\infty)\\). The integers are \\(-1,4,5,6\\), so there are 4.","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":54,"B":18,"C":16,"D":18,"E":5,"blank":79},"pc":28.4,"pa":58.4,"top":75,"pct":89.7,"tier":3,"disc":0.83,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-24","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":24,"topic":"Trigonometry","skill":"Tangent addition via Vieta's formulas","q":"Let the complex roots of \\(z^4-2024z^3+1337z^2-1729z+1111=0\\) be \\(\\tan\\theta_1,\\tan\\theta_2,\\tan\\theta_3,\\tan\\theta_4\\). If \\(\\tan(\\theta_1+\\theta_2+\\theta_3+\\theta_4)=-\\frac AB\\), find \\(A+B\\).","ch":["104","442","689","6202"],"a":"A","idea":"\\(\\tan(\\sum\\theta)=\\frac{e_1-e_3}{1-e_2+e_4}=\\frac{2024-1729}{1-1337+1111}=-\\frac{59}{45}\\), so \\(A+B=104\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":10,"B":9,"C":12,"D":4,"E":3,"blank":152},"pc":5.3,"pa":20.0,"top":25,"pct":99.5,"tier":5,"disc":1.54,"noisy":false,"extrap":true},"kind":"hard"},{"id":"2024-states-alpha-ind-25","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":25,"topic":"Matrices & vectors","skill":"Determinant multiplicativity","q":"For some matrix \\(A\\), \\(A\\begin{bmatrix}3\\\\4\\end{bmatrix}=\\begin{bmatrix}-6\\\\13\\end{bmatrix}\\) and \\(A\\begin{bmatrix}-1\\\\-3\\end{bmatrix}=\\begin{bmatrix}7\\\\-6\\end{bmatrix}\\). Find \\(|A|\\).","ch":["9","11","13","17"],"a":"B","idea":"\\(|A|\\cdot\\begin{vmatrix}3&-1\\\\4&-3\\end{vmatrix}=\\begin{vmatrix}-6&7\\\\13&-6\\end{vmatrix}\\), so \\(|A|\\cdot(-5)=-55\\) and \\(|A|=11\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":8,"B":64,"C":11,"D":2,"E":4,"blank":101},"pc":33.7,"pa":46.8,"top":96,"pct":69.8,"tier":2,"disc":1.88,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-26","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":26,"topic":"Trigonometry","skill":"Maximizing over quadrant choices","q":"If \\(\\tan\\theta=-\\frac34\\) and \\(\\cos\\phi=\\frac{12}{13}\\), find the maximum possible value of \\(\\sin(\\theta-\\phi)\\).","ch":["\\(\\frac{16}{65}\\)","\\(\\frac{33}{65}\\)","\\(\\frac{56}{65}\\)","\\(\\frac{63}{65}\\)"],"a":"C","idea":"Take \\(\\theta\\) in Quadrant II (\\(\\sin\\frac35\\), \\(\\cos-\\frac45\\)) and \\(\\sin\\phi=\\frac5{13}\\): \\(\\frac{36}{65}+\\frac{20}{65}=\\frac{56}{65}\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":7,"B":10,"C":86,"D":8,"E":5,"blank":74},"pc":45.3,"pa":61.1,"top":96,"pct":53.4,"tier":2,"disc":1.65,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-27","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":27,"topic":"Limits & continuity","skill":"Limit → binomial expansion","q":"Evaluate \\(\\displaystyle\\lim_{n\\to\\infty}\\sum_{k=1}^{n}\\left(\\frac1{k!}\\prod_{j=0}^{k-1}\\left(1-\\frac jn\\right)\\right)\\).","ch":["0","1","\\(e-1\\)","\\(e\\)"],"a":"C","idea":"Each term equals \\(\\binom nk\\frac1{n^k}\\), so the sum is \\(\\left(1+\\frac1n\\right)^n-1\\to e-1\\).","trap":{"choice":"D","why":"Forgot that the sum starts at \\(k=1\\), so the \\(k=0\\) term (which is 1) is missing."},"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":11,"B":11,"C":24,"D":18,"E":1,"blank":125},"pc":12.6,"pa":34.2,"top":32,"pct":99.9,"tier":5,"disc":0.59,"noisy":false,"extrap":true},"kind":"trap"},{"id":"2024-states-alpha-ind-28","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":28,"topic":"Exponents & logarithms","skill":"Casework for aᵇ = 1","q":"Find the sum of all values of \\(n\\) such that \\((n^2-5n+5)^{n^2-4n-15}=1\\).","ch":["5","9","12","14"],"a":"C","idea":"Base 1 gives \\(n=1,4\\). Exponent 0 gives \\(n=2\\pm\\sqrt{19}\\), sum 4. Base \\(-1\\) with an even exponent gives \\(n=3\\). Total: \\(1+4+4+3=12\\).","trap":{"choice":"B","why":"Missed the case where the base is \\(-1\\) with an even exponent."},"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":12,"B":29,"C":55,"D":5,"E":14,"blank":75},"pc":28.9,"pa":60.5,"top":89,"pct":78.5,"tier":3,"disc":1.62,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-29","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":29,"topic":"Matrices & vectors","skill":"2×2 determinants","q":"Evaluate \\(\\begin{vmatrix}2023&2024\\\\2024&2025\\end{vmatrix}\\).","ch":["\\(-1\\)","0","1","2024"],"a":"A","idea":"\\(n(n+2)-(n+1)^2=-1\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":132,"B":8,"C":16,"D":5,"E":2,"blank":27},"pc":69.5,"pa":85.8,"top":100,"pct":23.0,"tier":1,"disc":2.2,"noisy":false,"extrap":false},"kind":null},{"id":"2024-states-alpha-ind-30","year":2024,"comp":"State Convention","div":"Alpha","test":"Individual","n":30,"topic":"Polynomials","skill":"Building a polynomial from its roots","q":"Let \\(p(x)=x^{2024}+a_{2023}x^{2023}+\\cdots+a_1x+a_0\\) be a monic polynomial of degree 2024 such that \\(p\\!\\left(\\frac1k\\right)=k^2\\) for all integers \\(k\\) with \\(1\\le|k|\\le1012\\). Find the product of all other real numbers \\(\\ell\\) such that \\(p\\!\\left(\\frac1\\ell\\right)=\\ell^2\\).","ch":["\\(-\\frac1{1012!}\\)","\\(-\\frac1{(1012!)^2}\\)","\\(\\frac1{(1012!)^2}\\)","\\(\\frac1{1012!}\\)"],"a":"B","idea":"\\(x^2p(x)-1=\\prod_k\\left(x^2-\\frac1{k^2}\\right)(x^2-c)\\). The constant term forces \\(c=(1012!)^2\\), so the new roots are \\(x=\\pm1012!\\) and \\(\\ell=\\pm\\frac1{1012!}\\). Their product is \\(-\\frac1{(1012!)^2}\\).","trap":null,"note":null,"setup":null,"fig":null,"stats":{"n":190,"dist":{"A":4,"B":15,"C":13,"D":7,"E":2,"blank":149},"pc":7.9,"pa":21.6,"top":18,"pct":99.9,"tier":5,"disc":0.36,"noisy":false,"extrap":true},"kind":"hard"}]};
const LIBS = {
  h2c: "https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js",
  pdf: "https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"
};
const DIVISIONS = ["Theta", "Alpha", "Mu", "Statistics"];
const TOPICS = ["Trigonometry","Functions & algebra","Polynomials","Exponents & logarithms","Conics","Coordinate geometry","Geometry","Complex numbers","Sequences & series","Counting & probability","Number theory","Matrices & vectors","Limits & continuity","Derivatives","Applications of derivatives","Integrals","Applications of integration","Parametric & polar","Descriptive statistics","Study design & data types","Probability","Random variables & expected value","Sampling distributions","Confidence intervals","Hypothesis testing","Regression","Chi-square tests","Nonparametric methods"];
const FIGS = new Set(["semicircle","regionS","sqrtcurve","graphABCD","octagon","thetanet","thetachord","thetasemi","thetaseg"]);
const IMPORT_KEY = "bank.imported.v1";
const PUBLIC_BUILD = true; // set to true by `bank.cli build-page`: no upload, import or export controls

/* ---------- small helpers ---------- */
function el(tag, props, ...kids) {
  const n = document.createElement(tag);
  if (props) for (const [k, v] of Object.entries(props)) {
    if (v == null || v === false) continue;
    if (k === "text") n.textContent = v;
    else if (k === "class") n.className = v;
    else if (k.startsWith("on")) n.addEventListener(k.slice(2), v);
    else n.setAttribute(k, v === true ? "" : v);
  }
  for (const k of kids.flat()) if (k != null && k !== false) n.append(k);
  return n;
}
const $ = (id) => document.getElementById(id);
let mathReady;
const mathPromise = new Promise((r) => { mathReady = r; window.__mathReady = r; });
if (window.MathJax && window.MathJax.typesetPromise) mathReady();
let typesetChain = Promise.resolve();
function typeset(nodes) {
  typesetChain = typesetChain.then(() => mathPromise).then(() => MathJax.typesetPromise(nodes)).then(() => glue(nodes)).catch(() => {});
  return typesetChain;
}
function glue(nodes) {
  for (const root of nodes) for (const m of root.querySelectorAll("mjx-container:not([display])")) {
    const nx = m.nextSibling;
    if (nx && nx.nodeType === 3 && /^[?.,;:!)]/.test(nx.data)) {
      const k = nx.data.match(/^[?.,;:!)]+/)[0];
      nx.data = nx.data.slice(k.length);
      const w = el("span", { class: "nw" }); m.replaceWith(w); w.append(m, k);
    }
  }
}
function loadScript(src) {
  return new Promise((res, rej) => {
    if (document.querySelector(`script[src="${src}"]`)) return res();
    const s = document.createElement("script");
    s.src = src; s.async = true; s.crossOrigin = "anonymous"; s.referrerPolicy = "no-referrer";
    s.onload = res; s.onerror = () => rej(new Error("Could not load " + src));
    document.head.append(s);
  });
}
function mulberry32(a) { return function () { a |= 0; a = a + 0x6D2B79F5 | 0; let t = Math.imul(a ^ a >>> 15, 1 | a); t = t + Math.imul(t ^ t >>> 7, 61 | t) ^ t; return ((t ^ t >>> 14) >>> 0) / 4294967296; }; }
function shuffle(arr, rnd) { const a = arr.slice(); for (let i = a.length - 1; i > 0; i--) { const j = Math.floor(rnd() * (i + 1)); [a[i], a[j]] = [a[j], a[i]]; } return a; }
function store(key, val) { try { if (val == null) localStorage.removeItem(key); else localStorage.setItem(key, JSON.stringify(val)); return true; } catch (e) { return false; } }
function load(key) { try { const v = localStorage.getItem(key); return v ? JSON.parse(v) : null; } catch (e) { return null; } }

/* ---------- data ---------- */
let imported = (!PUBLIC_BUILD && sanitizeImport(load(IMPORT_KEY))) || { problems: [], setups: {} };
function allProblems() { return BANK.problems.concat(imported.problems); }
function setupsOf(p) {
  const ids = Array.isArray(p.setup) ? p.setup : (p.setup ? [p.setup] : []);
  return ids.map((id) => BANK.setups[id] || imported.setups[id]).filter(Boolean).map((s, i) => Object.assign({ id: ids[i] }, s));
}
function sourceText(p) { return `${p.year} ${p.comp}, ${p.div} ${p.test}, problem ${p.n}`; }
function shortSource(p) { return `${p.year} ${p.comp === "State Convention" ? "States" : p.comp} ${p.div} ${p.test} #${p.n}`; }
function answerText(a) { return a ? a.split("").join(" or ") : ""; }
function capFirst(s) { return s ? s.charAt(0).toUpperCase() + s.slice(1) : s; }
function scored(p) { return p.a && p.stats && typeof p.stats.pct === "number"; }

/* ---------- figures (built-in only; imported data can reference these by id, never supply markup) ---------- */
function figSVG(id, c) {
  // c: {ink, line, fill, bg, font}
  const t = (x, y, s, anchor = "middle", size = 15, ital = true) =>
    `<text x="${x}" y="${y}" text-anchor="${anchor}" style="fill:${c.ink};font:${ital ? "italic " : ""}${size}px ${c.font}">${s}</text>`;
  if (id === "semicircle") {
    return `<svg viewBox="0 0 220 185" width="220" role="img" aria-label="Isosceles triangle with base 16 and height 15, with a semicircle whose diameter lies on the base">
      <path d="M30 160 L110 10 L190 160 Z" style="fill:none;stroke:${c.ink};stroke-width:1.6"/>
      <path d="M39.4 160 A70.6 70.6 0 0 1 180.6 160 Z" style="fill:${c.fill};stroke:${c.line};stroke-width:1.4"/>
      <path d="M110 10 V160" style="stroke:${c.ink};stroke-width:1;stroke-dasharray:4 3"/>
      ${t(118, 92, "15", "start", 13, false)}${t(110, 178, "16", "middle", 13, false)}
    </svg>`;
  }
  if (id === "regionS") {
    return `<svg viewBox="0 0 240 230" width="240" role="img" aria-label="Region inside the circle of radius 3 and outside two circles of radius 2 centered at (1,0) and (−1,0)">
      <circle cx="120" cy="115" r="96" style="fill:${c.fill};stroke:${c.ink};stroke-width:1.4"/>
      <circle cx="88" cy="115" r="64" style="fill:${c.bg};stroke:${c.line};stroke-width:1.2"/>
      <circle cx="152" cy="115" r="64" style="fill:${c.bg};stroke:${c.line};stroke-width:1.2"/>
      <circle cx="88" cy="115" r="64" style="fill:none;stroke:${c.line};stroke-width:1.2"/>
      <path d="M14 115 H226 M120 10 V220" style="stroke:${c.ink};stroke-width:.8;opacity:.55"/>
      ${t(120, 36, "S")}${t(120, 206, "S")}
    </svg>`;
  }
  if (id === "sqrtcurve") {
    let pts = [];
    for (let i = 0; i <= 60; i++) { const a = (Math.PI / 2) * i / 60; const x = 4 * Math.cos(a) ** 4, y = 4 * Math.sin(a) ** 4; pts.push(`${(40 + x * 30).toFixed(1)},${(150 - y * 30).toFixed(1)}`); }
    return `<svg viewBox="0 0 200 175" width="200" role="img" aria-label="Graph of the square root of x plus the square root of y equals 2, an arc from (0,4) to (4,0)">
      <path d="M10 150 H190 M40 172 V8" style="stroke:${c.ink};stroke-width:1"/>
      <path d="M186 146 L190 150 L186 154 M36 12 L40 8 L44 12" style="fill:none;stroke:${c.ink};stroke-width:1"/>
      <polyline points="${pts.join(" ")}" style="fill:none;stroke:${c.line};stroke-width:2"/>
      ${t(186, 166, "x")}${t(52, 16, "y")}
    </svg>`;
  }
  if (id === "graphABCD") {
    const dot = (x, y) => `<circle cx="${x}" cy="${y}" r="4.5" style="fill:${c.ink}"/>`;
    return `<svg viewBox="0 0 180 160" width="180" role="img" aria-label="Graph with points A, B, C, D at the corners of a square; paths AB, BC, CD, DA and the diagonal AC">
      <path d="M40 130 H140 V30 H40 Z M40 130 L140 30" style="fill:none;stroke:${c.ink};stroke-width:1.6"/>
      ${dot(40, 130)}${dot(140, 130)}${dot(140, 30)}${dot(40, 30)}
      ${t(28, 148, "A")}${t(152, 148, "B")}${t(152, 24, "C")}${t(28, 24, "D")}
    </svg>`;
  }
  if (id === "octagon") {
    const L = ["Z","L","U","S","A","T","O","N"]; let pts = [], labels = "";
    for (let i = 0; i < 8; i++) {
      const a = -Math.PI / 2 - Math.PI / 8 + i * Math.PI / 4;
      const x = 110 + 78 * Math.cos(a), y = 105 + 78 * Math.sin(a);
      pts.push(`${x.toFixed(1)},${y.toFixed(1)}`);
      labels += t((110 + 96 * Math.cos(a)).toFixed(1), (110 + 96 * Math.sin(a)).toFixed(1), L[i]);
    }
    return `<svg viewBox="0 0 220 215" width="210" role="img" aria-label="Regular octagon with vertices labeled Z, L, U, S, A, T, O, N in order">
      <polygon points="${pts.join(" ")}" style="fill:none;stroke:${c.ink};stroke-width:1.6"/>${labels}
    </svg>`;
  }
  if (id === "thetanet") {
    const dot = (x, y) => `<circle cx="${x}" cy="${y}" r="13" style="fill:none;stroke:${c.ink};stroke-width:1.6"/>`;
    return `<svg viewBox="0 0 250 165" width="250" role="img" aria-label="Seven circles joined by five lines, three circles to a line: one at the top, three in the middle row, three in the bottom row">
      <path d="M125 30 L45 135 M125 30 L125 135 M125 30 L205 135 M45 85 H205 M45 135 H205" style="stroke:${c.line};stroke-width:1.3"/>
      ${dot(125, 30)}${dot(45, 85)}${dot(125, 85)}${dot(205, 85)}${dot(45, 135)}${dot(125, 135)}${dot(205, 135)}
    </svg>`;
  }
  if (id === "thetachord") {
    return `<svg viewBox="0 0 230 200" width="230" role="img" aria-label="Two concentric circles; a chord of the larger circle is cut into three equal parts by the smaller circle">
      <circle cx="115" cy="100" r="88" style="fill:none;stroke:${c.ink};stroke-width:1.6"/>
      <circle cx="115" cy="100" r="40" style="fill:none;stroke:${c.line};stroke-width:1.4"/>
      <path d="M31 128 H199" style="stroke:${c.ink};stroke-width:1.6"/>
      <path d="M87 122 V134 M143 122 V134" style="stroke:${c.line};stroke-width:1.2"/>
      ${t(59, 150, "12", "middle", 14, false)}${t(115, 150, "12", "middle", 14, false)}${t(171, 150, "12", "middle", 14, false)}
    </svg>`;
  }
  if (id === "thetasemi") {
    return `<svg viewBox="0 0 250 165" width="250" role="img" aria-label="Right triangle ABC with the right angle at C; a semicircle centered at D on side BC is tangent to side AB">
      <path d="M210 130 L210 30 L30 130 Z" style="fill:none;stroke:${c.ink};stroke-width:1.6"/>
      <path d="M198 130 V118 H210" style="fill:none;stroke:${c.ink};stroke-width:1.2"/>
      <path d="M96 130 A57 57 0 0 1 210 130 Z" style="fill:${c.fill};stroke:${c.line};stroke-width:1.3"/>
      ${t(214, 24, "A", "start")}${t(22, 136, "B", "end")}${t(216, 145, "C", "start")}${t(153, 146, "D")}
    </svg>`;
  }
  if (id === "thetaseg") {
    const seg = (d) => `<path d="${d}" style="fill:none;stroke:${c.line};stroke-width:7;stroke-linecap:round"/>`;
    return `<svg viewBox="0 0 90 150" width="80" role="img" aria-label="A seven-segment display showing the digit eight">
      ${seg("M22 18 H62")}${seg("M68 24 V64")}${seg("M68 80 V120")}${seg("M22 126 H62")}${seg("M16 80 V120")}${seg("M16 24 V64")}${seg("M22 72 H62")}
    </svg>`;
  }
  return "";
}
const SCREEN_COLORS = { ink: "var(--ink)", line: "var(--blue)", fill: "var(--blue-soft)", bg: "var(--surface)", font: "var(--serif)" };
const PRINT_COLORS = { ink: "#1D2A30", line: "#2E5C8A", fill: "#E3ECF4", bg: "#FFFFFF", font: "'STIX Two Text', Cambria, serif" };
function figNode(id, colors) {
  if (!id || !FIGS.has(id)) return null;
  const d = el("div", { class: "fig" });
  d.innerHTML = figSVG(id, colors); // markup comes only from the built-in library above
  return d;
}

/* ---------- difficulty ruler ---------- */
const BREAKS = [0, 50, 75, 90, 98, 100];     // field percentile cutoffs for tiers
const POS = [0, 40, 62, 80, 93, 100];        // display positions so tier 5 stays visible
function pctToPos(p) { for (let i = 1; i < BREAKS.length; i++) if (p <= BREAKS[i]) return POS[i - 1] + (p - BREAKS[i - 1]) / (BREAKS[i] - BREAKS[i - 1]) * (POS[i] - POS[i - 1]); return 100; }
function ord(n) { const s = ["th","st","nd","rd"], v = n % 100; return n + (s[(v - 20) % 10] || s[v] || s[0]); }
function ruler(p) {
  const st = p.stats || {};
  if (!scored(p)) return el("div", { class: "diff" }, el("div", { class: "diff-head" }, el("strong", { text: "Not rated" }), el("span", { text: st.thrown ? "Thrown out at the competition" : "No score data" })));
  const pct = Math.round(st.pct);
  const need = `${ord(pct)} percentile`;
  const headline = st.noisy
    ? "approximate: this question didn't separate stronger from weaker students"
    : st.extrap
      ? `nobody reached a 50% solve rate, not even the strongest students`
      : `50% chance at the ${need}`;
  const bar = el("div", { class: "ruler", role: "img", "aria-label": st.extrap
    ? `Tier ${st.tier} of 5. No group of students in this field reached a 50% solve rate.`
    : `Tier ${st.tier} of 5. A student at about the ${need} has a 50% chance of solving it.` });
  for (let i = 1; i <= 5; i++) bar.append(el("i", { style: `width:${POS[i] - POS[i - 1]}%;background:var(--t${i})` }));
  bar.append(el("span", { class: "notch" + (st.extrap ? " beyond" : ""), style: `left:${st.extrap ? 100 : pctToPos(st.pct).toFixed(1)}%` }));
  const scale = el("div", { class: "ruler-scale", "aria-hidden": "true" });
  for (let i = 1; i <= 5; i++) scale.append(el("span", { style: `left:${(POS[i - 1] + POS[i]) / 2}%`, text: String(i) }));
  return el("div", { class: "diff" },
    el("div", { class: "diff-head" }, el("strong", { text: `Tier ${st.tier}` }), el("span", { text: headline })),
    bar, scale,
    el("div", { class: "diff-foot", text: `${Math.round(st.pc)}% correct, ${Math.round(st.pa)}% attempted, top 28 students ${st.top}% (field of ${st.n})` }));
}

/* ---------- problem card (built once per problem, then reused) ---------- */
const cardCache = new Map();
function choiceList(p, forPrint) {
  const letters = ["A","B","C","D","E"];
  const texts = p.ch.slice(0, 4).concat(["NOTA"]);
  const long = texts.some((t) => t.replace(/\\\(|\\\)|\\[a-z]+|[{}]/g, "").length > 22);
  if (forPrint) {
    return el("div", { class: "pch" + (long ? " long" : "") }, texts.map((t, i) => el("span", { text: `(${letters[i]}) ${t}` })));
  }
  const box = el("div", { class: "choices" + (long ? " long" : ""), role: "group", "aria-label": "Answer choices" });
  texts.forEach((t, i) => {
    box.append(el("button", { type: "button", class: "choice", "data-letter": letters[i], "aria-pressed": "false", "aria-label": `Answer ${letters[i]}` },
      el("span", { class: "bub", "aria-hidden": "true", text: letters[i] }), el("span", { class: "ctext", text: t })));
  });
  return box;
}
const session = { solved: 0, firstTry: 0 };
function updateSession() {
  const s = $("session"); if (!s) return;
  s.hidden = !session.solved;
  s.textContent = `${session.solved} solved this visit, ${session.firstTry} on the first try`;
}
function card(p) {
  if (cardCache.has(p.id)) return cardCache.get(p.id);
  const setups = setupsOf(p);
  const art = el("article", { class: "prob", "aria-labelledby": "h-" + p.id });
  const revealBtn = el("button", { class: "btn quiet", type: "button", "aria-expanded": "false", text: p.a ? "Show answer" : "Show notes" });
  const pinBtn = el("button", { class: "btn", type: "button", "aria-pressed": state.pinned.includes(p.id) ? "true" : "false", text: state.pinned.includes(p.id) ? "In set" : "Add to set" });
  const submitBtn = el("button", { class: "btn primary", type: "button", disabled: true, text: "Submit" });
  const feedback = el("div", { class: "feedback", role: "status", "aria-live": "polite", hidden: true });
  const answer = el("div", { class: "answer", hidden: true });
  if (p.a) answer.append(el("div", {}, el("b", { text: `Answer: ${answerText(p.a)}. ` }), el("span", { text: p.idea || "" })));
  else answer.append(el("div", {}, el("b", { text: "No answer counted. " }), el("span", { text: p.idea || "" })));
  if (p.trap) answer.append(el("div", { class: "trapnote" }, el("b", { text: `Common trap: ${p.trap.choice}. ` }), el("span", { text: p.trap.why })));
  const tier = scored(p) ? el("span", { class: `tierchip t${p.stats.tier}`, text: `Tier ${p.stats.tier}` }) : null;
  const head = el("header", { class: "card-head" },
    el("span", { class: "qnum", text: `#${p.n}` }),
    el("span", { class: "src", id: "h-" + p.id, text: `${p.year} ${p.comp === "State Convention" ? "States" : p.comp}, ${p.div} ${p.test}` }),
    p.kind === "trap" ? el("span", { class: "tag trap", text: "Trap" }) : null,
    p.stats && p.stats.thrown ? el("span", { class: "tag thrown", text: "Thrown out" }) : null,
    tier);
  const choices = choiceList(p, false);
  const submitRow = el("div", { class: "submit-row" }, submitBtn, el("span", { class: "tries", hidden: true }));
  const put = (...kids) => { for (const k of kids.flat()) if (k != null && k !== false && k !== "") art.append(k); };
  put(
    head,
    el("div", { class: "skill" }, el("span", { class: "topic", text: p.topic }), el("span", { class: "skilltext", text: p.skill })),
    setups.map((s) => el("div", { class: "setup", text: s.text })),
    setups.map((s) => (s.fig ? figNode(s.fig, SCREEN_COLORS) : null)),
    el("div", { class: "stmt", text: p.q }),
    figNode(p.fig, SCREEN_COLORS),
    choices,
    submitRow,
    feedback,
    p.note ? el("div", { class: "notice", text: p.note }) : null,
    answer,
    el("footer", { class: "card-foot" }, ruler(p), el("div", { class: "actions" }, revealBtn, pinBtn)));

  const st = { selected: null, tries: 0, solved: false, revealed: false };
  const buttons = () => [...choices.querySelectorAll(".choice")];
  const say = (kind, bold, rest) => {
    feedback.hidden = false; feedback.className = "feedback " + kind; feedback.textContent = "";
    feedback.append(el("b", { text: bold }), rest ? " " + rest : "");
  };
  const lock = () => { buttons().forEach((b) => { b.disabled = true; }); submitBtn.disabled = true; };
  const showAnswer = (open) => {
    answer.hidden = !open; art.classList.toggle("show", open);
    revealBtn.setAttribute("aria-expanded", String(open));
    revealBtn.textContent = open ? (p.a ? "Hide answer" : "Hide notes") : (p.a ? "Show answer" : "Show notes");
    buttons().forEach((b) => { if (p.a && p.a.includes(b.dataset.letter)) b.classList.toggle("right", open || st.solved); });
  };
  choices.addEventListener("click", (e) => {
    const btn = e.target.closest(".choice"); if (!btn || btn.disabled || st.solved) return;
    buttons().forEach((b) => { b.classList.toggle("selected", b === btn); b.setAttribute("aria-pressed", String(b === btn)); });
    st.selected = btn.dataset.letter; submitBtn.disabled = false;
  });
  submitBtn.addEventListener("click", () => {
    if (!st.selected || st.solved) return;
    const L = st.selected, btn = buttons().find((b) => b.dataset.letter === L);
    st.tries++;
    if (!p.a) {
      st.solved = true; lock(); submitRow.hidden = true;
      say("neutral", "This question was thrown out,", "so no answer counted. The notes below explain why.");
      showAnswer(true); return;
    }
    if (p.a.includes(L)) {
      st.solved = true; btn.classList.remove("selected"); btn.classList.add("right"); art.classList.add("solved"); lock();
      submitRow.hidden = true;
      say("good", "Correct.", st.tries === 1 ? "" : `Solved in ${st.tries} tries.`);
      if (!st.revealed) { session.solved++; if (st.tries === 1) session.firstTry++; updateSession(); }
      const again = el("button", { type: "button", class: "linkbtn", text: "Start over" });
      again.addEventListener("click", () => reset());
      feedback.append(" ", again);
      showAnswer(true);
    } else {
      btn.classList.remove("selected"); btn.classList.add("wrong"); btn.disabled = true; btn.setAttribute("aria-pressed", "false");
      st.selected = null; submitBtn.disabled = true;
      say("bad", "Incorrect, try again.");
      const tries = submitRow.querySelector(".tries"); tries.hidden = false; tries.textContent = `${st.tries} ${st.tries === 1 ? "try" : "tries"} so far`;
    }
  });
  const reset = () => {
    Object.assign(st, { selected: null, tries: 0, solved: false, revealed: false });
    art.classList.remove("solved");
    buttons().forEach((b) => { b.classList.remove("selected", "right", "wrong"); b.disabled = false; b.setAttribute("aria-pressed", "false"); });
    submitBtn.disabled = true; submitRow.hidden = false; feedback.hidden = true; feedback.textContent = "";
    const tries = submitRow.querySelector(".tries"); tries.hidden = true; tries.textContent = "";
    showAnswer(false);
  };
  revealBtn.addEventListener("click", () => {
    const open = answer.hidden;
    if (open && !st.solved) st.revealed = true;   // solving after peeking doesn't count toward the visit tally
    showAnswer(open);
  });
  pinBtn.addEventListener("click", () => { togglePin(p.id); });
  art._pin = pinBtn;
  cardCache.set(p.id, art);
  typeset([art]);
  return art;
}

/* ---------- state ---------- */
const state = {
  divs: new Set(["Alpha"]), years: new Set(), topics: new Set(), tiers: new Set([1,2,3,4,5]),
  show: "all", q: "", sort: "test", pinned: [], set: [], order: "easy", seed: Date.now() >>> 0
};
function years() { return [...new Set(allProblems().map((p) => p.year))].sort((a, b) => b - a); }
state.years = new Set(years());

function matchesBrowse(p) {
  if (!state.divs.has(p.div) || !state.years.has(p.year)) return false;
  if (state.topics.size && !state.topics.has(p.topic)) return false;
  if (scored(p)) { if (!state.tiers.has(p.stats.tier)) return false; }
  else if (state.show !== "thrown" && state.show !== "all") return false;
  if (state.show === "traps" && p.kind !== "trap") return false;
  if (state.show === "thrown" && !(p.stats && p.stats.thrown)) return false;
  if (state.q) { const q = state.q.toLowerCase(); if (!(p.skill.toLowerCase().includes(q) || p.topic.toLowerCase().includes(q) || p.q.toLowerCase().includes(q))) return false; }
  return true;
}
function sortProblems(list, how) {
  const byTest = (a, b) => b.year - a.year || a.n - b.n;
  const pv = (p) => scored(p) ? p.stats.pct : 101;
  if (how === "easy") return list.sort((a, b) => pv(a) - pv(b) || byTest(a, b));
  if (how === "hard") return list.sort((a, b) => (scored(b) ? b.stats.pct : -1) - (scored(a) ? a.stats.pct : -1) || byTest(a, b));
  return list.sort(byTest);
}

/* ---------- browse view ---------- */
function renderRail() {
  const rail = $("rail"); rail.textContent = "";
  const all = allProblems();
  const countBy = (fn) => { const m = new Map(); for (const p of all) { const k = fn(p); m.set(k, (m.get(k) || 0) + 1); } return m; };
  const divCounts = countBy((p) => p.div);
  const yearCounts = new Map(); for (const p of all) if (state.divs.has(p.div)) yearCounts.set(p.year, (yearCounts.get(p.year) || 0) + 1);
  rail.append(el("h2", { text: "Division" }));
  for (const d of DIVISIONS) {
    const n = divCounts.get(d) || 0;
    const cb = el("input", { type: "checkbox", checked: state.divs.has(d), disabled: !n, "data-div": d });
    cb.addEventListener("change", () => {
      cb.checked ? state.divs.add(d) : state.divs.delete(d);
      // keep only topic ticks that still exist in the chosen divisions, then redraw the topic list
      const live = new Set(allProblems().filter((p) => state.divs.has(p.div)).map((p) => p.topic));
      for (const tp of [...state.topics]) if (!live.has(tp)) state.topics.delete(tp);
      renderRail(); renderList();
      const again = document.querySelector(`#rail input[data-div="${d}"]`); if (again) again.focus();
    });
    rail.append(el("label", { class: "check" + (n ? "" : " off") }, cb, d, el("span", { class: "n", text: n ? String(n) : "no tests yet" })));
  }
  rail.append(el("h2", { text: "Year" }));
  for (const y of years()) {
    const cb = el("input", { type: "checkbox", checked: state.years.has(y) });
    cb.addEventListener("change", () => { cb.checked ? state.years.add(y) : state.years.delete(y); renderList(); });
    rail.append(el("label", { class: "check" }, cb, `${y} States`, el("span", { class: "n", text: String(yearCounts.get(y) || 0) })));
  }
  rail.append(el("h2", { text: "Difficulty tier" }));
  const tiers = el("div", { class: "tiers", role: "group", "aria-label": "Difficulty tiers" });
  for (let t = 1; t <= 5; t++) {
    const b = el("button", { class: "tierbtn", type: "button", "aria-pressed": String(state.tiers.has(t)), text: String(t), "aria-label": `Tier ${t}` });
    b.addEventListener("click", () => { state.tiers.has(t) ? state.tiers.delete(t) : state.tiers.add(t); b.setAttribute("aria-pressed", String(state.tiers.has(t))); renderList(); });
    tiers.append(b);
  }
  rail.append(tiers);
  rail.append(el("h2", { text: "Show" }));
  const seg = el("div", { class: "seg", role: "group", "aria-label": "Which problems" });
  for (const [v, label] of [["all", "All"], ["traps", "Traps"], ["thrown", "Thrown out"]]) {
    const b = el("button", { type: "button", "aria-pressed": String(state.show === v), text: label });
    b.addEventListener("click", () => { state.show = v; [...seg.children].forEach((c) => c.setAttribute("aria-pressed", String(c === b))); renderList(); });
    seg.append(b);
  }
  rail.append(seg);
  rail.append(el("h2", { text: "Topic" }));
  const inDivs = all.filter((p) => state.divs.has(p.div));
  const tCounts = new Map(); for (const p of inDivs) tCounts.set(p.topic, (tCounts.get(p.topic) || 0) + 1);
  if (!state.divs.size) rail.append(el("p", { class: "hint", text: "Pick a division to see its topics." }));
  for (const tp of TOPICS) {
    const n = tCounts.get(tp) || 0; if (!n) continue;
    const cb = el("input", { type: "checkbox", checked: state.topics.has(tp) });
    cb.addEventListener("change", () => { cb.checked ? state.topics.add(tp) : state.topics.delete(tp); renderList(); });
    rail.append(el("label", { class: "check" }, cb, tp, el("span", { class: "n", text: String(n) })));
  }
  if (state.divs.size) rail.append(el("p", { class: "hint" }, "No topic ticked means every topic in the chosen divisions."));
  rail.append(el("h2", {}, el("label", { for: "q", text: "Search skills and text" })));
  const q = el("input", { class: "search", id: "q", type: "search", maxlength: "60", value: state.q, placeholder: "e.g. Vieta" });
  q.addEventListener("input", () => { state.q = q.value.trim(); renderList(); });
  rail.append(q);
  rail.append(el("p", { class: "hint" }, el("button", { class: "linkbtn", type: "button", text: "Reset filters", onclick: () => {
    state.divs = new Set(["Alpha"]); state.years = new Set(years()); state.topics.clear(); state.tiers = new Set([1,2,3,4,5]); state.show = "all"; state.q = ""; renderRail(); renderList();
  } })));
}
function renderList() {
  const list = $("list");
  const items = sortProblems(allProblems().filter(matchesBrowse), state.sort);
  $("resultcount").textContent = items.length === 1 ? "1 problem" : `${items.length} problems`;
  list.textContent = "";
  if (!items.length) { list.append(el("p", { class: "empty", text: "No problems match these filters. Widen the tiers or tick more topics." })); return; }
  for (const p of items) list.append(card(p));
}

/* ---------- pins and set building ---------- */
function togglePin(id) {
  const i = state.pinned.indexOf(id);
  if (i >= 0) { state.pinned.splice(i, 1); state.set = state.set.filter((x) => x !== id); }
  else { state.pinned.push(id); if (!state.set.includes(id)) state.set.unshift(id); }
  const c = cardCache.get(id);
  if (c) { c._pin.setAttribute("aria-pressed", String(i < 0)); c._pin.textContent = i < 0 ? "In set" : "Add to set"; }
  updatePinCount(); renderSet();
}
function updatePinCount() {
  const pc = $("pincount"); const n = state.set.length;
  pc.hidden = !n; pc.textContent = String(n);
}
const bstate = { divs: new Set(["Alpha"]), off: new Set(), tiers: new Set([1,2,3]), order: "easy" };
function bVisibleTopics() { return TOPICS.filter((tp) => allProblems().some((p) => scored(p) && bstate.divs.has(p.div) && p.topic === tp)); }
function bTopics() { return new Set(bVisibleTopics().filter((tp) => !bstate.off.has(tp))); }
function buildPool(excludeIds) {
  const traps = $("b-traps").checked;
  const topics = bTopics();
  return allProblems().filter((p) => scored(p) && bstate.divs.has(p.div) && topics.has(p.topic) && bstate.tiers.has(p.stats.tier) && (!traps || p.kind === "trap") && !(excludeIds && excludeIds.has(p.id)));
}
function renderBuildForm() {
  const all = allProblems();
  const divBox = $("b-divs"); divBox.textContent = "";
  for (const d of DIVISIONS) {
    const n = all.filter((p) => p.div === d && scored(p)).length;
    const cb = el("input", { type: "checkbox", checked: bstate.divs.has(d), disabled: !n, "data-div": d });
    cb.addEventListener("change", () => {
      cb.checked ? bstate.divs.add(d) : bstate.divs.delete(d);
      renderBuildForm();
      const again = document.querySelector(`#b-divs input[data-div="${d}"]`); if (again) again.focus();
    });
    divBox.append(el("label", { class: "check" + (n ? "" : " off") }, cb, d, el("span", { class: "n", text: n ? String(n) : "no tests yet" })));
  }
  const tb = $("b-topics"); tb.textContent = "";
  const vis = bVisibleTopics();
  if (!vis.length) tb.append(el("p", { class: "hint", text: "Pick a division to see its topics." }));
  for (const tp of vis) {
    const n = all.filter((p) => p.topic === tp && scored(p) && bstate.divs.has(p.div)).length;
    const cb = el("input", { type: "checkbox", checked: !bstate.off.has(tp), "data-topic": tp });
    cb.addEventListener("change", () => { cb.checked ? bstate.off.delete(tp) : bstate.off.add(tp); updatePoolHint(); });
    tb.append(el("label", { class: "check" }, cb, tp, el("span", { class: "n", text: String(n) })));
  }
  const tiers = $("b-tiers"); tiers.textContent = "";
  for (let t = 1; t <= 5; t++) {
    const b = el("button", { class: "tierbtn", type: "button", "aria-pressed": String(bstate.tiers.has(t)), text: String(t), "aria-label": `Tier ${t}` });
    b.addEventListener("click", () => { bstate.tiers.has(t) ? bstate.tiers.delete(t) : bstate.tiers.add(t); b.setAttribute("aria-pressed", String(bstate.tiers.has(t))); updatePoolHint(); });
    tiers.append(b);
  }
  updatePoolHint();
}
function updatePoolHint() {
  const n = buildPool().length;
  $("b-pool").textContent = n === 1 ? "1 problem matches these choices." : `${n} problems match these choices.`;
}
function generate() {
  const status = $("b-status"); status.className = "status";
  let count = parseInt($("b-count").value, 10);
  if (!Number.isFinite(count) || count < 1 || count > 60) { status.className = "status err"; status.textContent = "Choose between 1 and 60 problems."; return; }
  if (!bstate.divs.size) { status.className = "status err"; status.textContent = "Pick at least one division."; return; }
  if (!bTopics().size) { status.className = "status err"; status.textContent = "Tick at least one topic."; return; }
  if (!bstate.tiers.size) { status.className = "status err"; status.textContent = "Pick at least one difficulty tier."; return; }
  const pinned = state.pinned.filter((id) => allProblems().some((p) => p.id === id));
  const need = Math.max(0, count - pinned.length);
  state.seed = (state.seed * 1664525 + 1013904223) >>> 0;
  const rnd = mulberry32(state.seed);
  const pool = buildPool(new Set(pinned));
  let chosen = [];
  if ($("b-spread").checked) {
    const byTopic = new Map();
    for (const p of shuffle(pool, rnd)) { if (!byTopic.has(p.topic)) byTopic.set(p.topic, []); byTopic.get(p.topic).push(p); }
    const queues = shuffle([...byTopic.values()], rnd);
    while (chosen.length < need && queues.some((q) => q.length)) for (const q of queues) { if (chosen.length >= need) break; if (q.length) chosen.push(q.shift()); }
  } else chosen = shuffle(pool, rnd).slice(0, need);
  let ids = pinned.concat(chosen.map((p) => p.id));
  state.set = orderIds(ids, rnd);
  updatePinCount(); renderSet();
  const short = count - state.set.length;
  if (!state.set.length) {
    status.className = "status err";
    status.textContent = "No problems match these choices. Tick more topics or tiers, or turn off Traps only.";
    return;
  }
  status.textContent = short > 0 ? `Generated ${state.set.length} problems. That's all that match; widen the tiers or topics for more.` : `Generated ${state.set.length} problems.`;
  const head = document.querySelector(".set-head");
  const seen = head.getBoundingClientRect();
  if (seen.top < 4 || seen.bottom > window.innerHeight - 40) head.scrollIntoView({ block: "start" });
}
function orderIds(ids, rnd) {
  const byId = new Map(allProblems().map((p) => [p.id, p]));
  const ps = ids.map((id) => byId.get(id)).filter(Boolean);
  if (bstate.order === "easy") ps.sort((a, b) => a.stats.pct - b.stats.pct);
  else if (bstate.order === "topic") ps.sort((a, b) => TOPICS.indexOf(a.topic) - TOPICS.indexOf(b.topic) || a.stats.pct - b.stats.pct);
  else return shuffle(ps, rnd || Math.random).map((p) => p.id);
  return ps.map((p) => p.id);
}
function swapProblem(id) {
  const rnd = mulberry32((state.seed = (state.seed * 1664525 + 1013904223) >>> 0));
  const cur = allProblems().find((p) => p.id === id); if (!cur) return;
  const inSet = new Set(state.set);
  let pool = buildPool(inSet); const same = pool.filter((p) => p.topic === cur.topic);
  if (same.length) pool = same;
  if (!pool.length) { $("b-status").textContent = "No other problem matches these choices."; return; }
  const next = pool[Math.floor(rnd() * pool.length)];
  state.set = state.set.map((x) => (x === id ? next.id : x));
  const pi = state.pinned.indexOf(id); if (pi >= 0) togglePin(id); else renderSet();
}
function removeFromSet(id) {
  if (state.pinned.includes(id)) togglePin(id);
  else { state.set = state.set.filter((x) => x !== id); updatePinCount(); renderSet(); }
}
function renderSet() {
  const ol = $("setlist"); ol.textContent = "";
  const byId = new Map(allProblems().map((p) => [p.id, p]));
  const ps = state.set.map((id) => byId.get(id)).filter(Boolean);
  $("set-empty").hidden = !!ps.length;
  $("set-pdf").disabled = !ps.length; $("set-clear").disabled = !ps.length;
  $("set-title").textContent = ps.length ? `${$("settitle").value.trim() || "Practice set"}: ${ps.length} problem${ps.length > 1 ? "s" : ""}` : "No set yet";
  ps.forEach((p, i) => {
    const li = el("li", { class: "setitem" },
      el("div", { class: "num", text: String(i + 1) }),
      el("div", {},
        setupsOf(p).map((s) => el("div", { class: "setup", style: "font-size:14.5px", text: s.text })),
        el("div", { class: "stmt", text: p.q }),
        el("div", { class: "src" },
          el("span", { text: shortSource(p) }),
          el("span", { class: "minitier" }, el("i", { style: `background:var(--t${p.stats.tier})`, "aria-hidden": "true" }), `Tier ${p.stats.tier}`),
          el("span", { text: p.topic }),
          state.pinned.includes(p.id) ? el("span", { text: "Added from Browse" }) : null)),
      el("div", { class: "mini" },
        el("button", { class: "btn", type: "button", text: "Swap", "aria-label": `Swap problem ${i + 1} for another`, onclick: () => swapProblem(p.id) }),
        el("button", { class: "btn", type: "button", text: "Remove", "aria-label": `Remove problem ${i + 1}`, onclick: () => removeFromSet(p.id) })));
    ol.append(li);
  });
  typeset([ol]);
}

/* ---------- saving files ---------- */
let downloadsNS = null;
if (window.claude && typeof window.claude.use === "function") {
  window.claude.use("downloads").then((d) => { downloadsNS = d; }).catch(() => {});
}
async function saveFile(filename, blob) {
  if (downloadsNS) {
    try { await downloadsNS.save({ filename, data: blob }); return "saved"; }
    catch (e) { if (e && e.code === "declined") return "declined"; throw e; }
  }
  const url = URL.createObjectURL(blob);
  const a = el("a", { href: url, download: filename }); document.body.append(a); a.click(); a.remove();
  setTimeout(() => URL.revokeObjectURL(url), 4000);
  return "saved";
}

/* A small, isolated document for rasterizing PDF blocks, so each capture copies only one block instead of the whole page. */
async function makeRenderFrame() {
  try {
    const old = document.getElementById("renderframe"); if (old) old.remove();
    const f = el("iframe", { id: "renderframe", title: "PDF renderer", "aria-hidden": "true", tabindex: "-1",
      style: "position:fixed;left:-10000px;top:0;width:760px;height:1200px;border:0;visibility:hidden" });
    document.body.append(f);
    const doc = f.contentDocument; if (!doc) throw new Error("no frame document");
    const styles = [...document.querySelectorAll("style")].map((s) => s.textContent).join("\n");
    const fontLink = document.querySelector('link[href*="fonts.googleapis.com/css2"]');
    doc.open();
    doc.write('<!DOCTYPE html><html><head><meta charset="utf-8"><meta name="viewport" content="width=760"></head><body style="margin:0;background:#fff;width:760px;-webkit-text-size-adjust:100%;text-size-adjust:100%"><div id="stage" style="position:static;left:auto;width:720px"></div></body></html>');
    doc.close();
    const st = doc.createElement("style"); st.textContent = styles + "\n#stage{position:static!important;left:auto!important;width:720px!important}\nmjx-assistive-mml{display:none!important}\n#stage>*{width:720px;box-sizing:border-box;overflow-wrap:anywhere}"; doc.head.append(st);
    if (fontLink) { const l = doc.createElement("link"); l.rel = "stylesheet"; l.href = fontLink.href; doc.head.append(l); await new Promise((r) => { l.onload = r; l.onerror = r; setTimeout(r, 4000); }); }
    if (doc.fonts && doc.fonts.ready) await Promise.race([doc.fonts.ready, new Promise((r) => setTimeout(r, 4000))]);
    return { doc, box: doc.getElementById("stage") };
  } catch (e) { return null; }
}

/* ---------- PDF ---------- */
async function makePDF() {
  const btn = $("set-pdf"), status = $("pdf-status");
  let parked = null;
  const byId = new Map(allProblems().map((p) => [p.id, p]));
  const ps = state.set.map((id) => byId.get(id)).filter(Boolean);
  if (!ps.length) return;
  btn.disabled = true; status.className = "status"; status.textContent = "Building the PDF…";
  try {
    await Promise.all([loadScript(LIBS.h2c), loadScript(LIBS.pdf)]);
    await mathPromise;
    if (document.fonts && document.fonts.ready) await Promise.race([document.fonts.ready, new Promise((r) => setTimeout(r, 4000))]);
    const title = $("settitle").value.trim() || "Practice set";
    const stage = $("stage"); stage.textContent = "";
    const showTier = $("b-tierlabels").checked;
    const blocks = [];
    const topics = [...new Set(ps.map((p) => p.topic))];
    const header = el("div", { class: "ph" },
      el("h1", { text: title }),
      el("p", { text: `${ps.length} problems from FAMAT State Convention tests. Topics: ${topics.join(", ")}.` }),
      el("p", { text: "Answer choice E is always NOTA (none of these answers)." }),
      el("div", { class: "name", text: "Name ______________________________    Score ________" }));
    blocks.push(header);
    let lastSetups = new Set();
    ps.forEach((p, i) => {
      const setups = setupsOf(p);
      const fresh = setups.filter((s) => !lastSetups.has(s.id));
      const body = el("div", {},
        fresh.map((s) => el("div", { class: "psetup", text: capFirst(s.text.replace(/^For Questions? [^:,]+[:,]\s*/i, "")) })),
        fresh.map((s) => (s.fig ? figNode(s.fig, PRINT_COLORS) : null)),
        el("div", { text: p.q }),
        figNode(p.fig, PRINT_COLORS),
        choiceList(p, true),
        el("div", { class: "ptier", text: showTier ? `${shortSource(p)}. Tier ${p.stats.tier}.` : shortSource(p) }));
      lastSetups = new Set(setups.map((s) => s.id));
      blocks.push(el("div", { class: "pb" }, el("div", { class: "pn", text: `${i + 1}.` }), body));
    });
    const keyBlocks = [];
    if ($("b-key").checked) {
      keyBlocks.push(el("div", { class: "kh", text: "Answer key" }));
      const ideas = $("b-ideas").checked;
      ps.forEach((p, i) => keyBlocks.push(el("div", { class: "kb" },
        el("div", { class: "kn", text: `${i + 1}.` }), el("div", { class: "ka", text: answerText(p.a) }),
        el("div", {}, ideas ? el("div", { text: p.idea }) : null, el("div", { class: "ks", text: `${shortSource(p)}. Tier ${p.stats.tier}. ${p.skill}.` })))));
    }
    for (const b of blocks.concat(keyBlocks)) stage.append(b);
    await MathJax.typesetPromise([stage]);
    glue([stage]);
    // MathJax also writes each formula as hidden MathML for screen readers. iPhone Safari draws that hidden copy
    // into the canvas too, which doubles every formula on top of itself, so the print copy drops it.
    stage.querySelectorAll("mjx-assistive-mml").forEach((n) => n.remove());
    parked = document.createDocumentFragment();
    const listEl = $("list"); while (listEl.firstChild) parked.append(listEl.firstChild);
    const frame = await makeRenderFrame();
    const { jsPDF } = window.jspdf;
    const doc = new jsPDF({ unit: "pt", format: "letter", compress: true });
    const W = 612, H = 792, M = 54, CW = W - 2 * M, footer = 28;
    let y = M;
    const addBlock = async (node, forceNewPage) => {
      let target = node;
      if (frame) { target = frame.doc.adoptNode(node); frame.box.append(target); }
      const canvas = await html2canvas(target, { scale: 2, backgroundColor: "#ffffff", logging: false, useCORS: false, removeContainer: true,
        windowWidth: 760, width: target.offsetWidth,
        onclone: (d) => d.querySelectorAll("mjx-assistive-mml").forEach((n) => n.remove()) });
      if (frame) target.remove();
      const h = canvas.height * (CW / canvas.width);
      if (forceNewPage || (y + h > H - M - footer && y > M)) { doc.addPage(); y = M; }
      doc.addImage(canvas.toDataURL("image/png"), "PNG", M, y, CW, Math.min(h, H - M - footer - y), undefined, "FAST");
      y += h + 4;
    };
    for (const b of blocks) await addBlock(b, false);
    for (let i = 0; i < keyBlocks.length; i++) await addBlock(keyBlocks[i], i === 0);
    const pages = doc.getNumberOfPages();
    for (let i = 1; i <= pages; i++) {
      doc.setPage(i); doc.setFontSize(9); doc.setTextColor(86, 102, 110);
      doc.text(`${title}`, M, H - 30); doc.text(`Page ${i} of ${pages}`, W - M, H - 30, { align: "right" });
    }
    stage.textContent = "";
    const blob = doc.output("blob");
    const safeName = (title.replace(/[^A-Za-z0-9 _-]+/g, "").trim().replace(/\s+/g, "-") || "practice-set").slice(0, 60) + ".pdf";
    const r = await saveFile(safeName, blob);
    status.textContent = r === "declined" ? "Download canceled." : `PDF ready: ${safeName}, ${pages} page${pages > 1 ? "s" : ""}.`;
  } catch (e) {
    status.className = "status err";
    status.textContent = "The PDF couldn't be built. Check your connection (the PDF tools load when first used) and try again.";
  } finally {
    const f = document.getElementById("renderframe"); if (f) f.remove();
    if (parked) $("list").append(parked);
    $("stage").textContent = "";
    btn.disabled = false;
  }
}

/* ---------- data view, import/export ---------- */
function sanitizeImport(raw) {
  if (!raw || typeof raw !== "object" || !Array.isArray(raw.problems)) return null;
  const str = (v, max) => (typeof v === "string" && v.length <= max ? v : null);
  const out = { problems: [], setups: {} };
  const setups = raw.setups && typeof raw.setups === "object" ? raw.setups : {};
  for (const [k, v] of Object.entries(setups)) {
    if (!/^[A-Za-z0-9-]{1,60}$/.test(k) || !v) continue;
    const text = str(v.text, 3000); if (!text) continue;
    out.setups[k] = { text, fig: FIGS.has(v.fig) ? v.fig : null };
  }
  const baseIds = new Set(BANK.problems.map((p) => p.id));
  for (const r of raw.problems.slice(0, 5000)) {
    if (!r || typeof r !== "object") continue;
    const id = str(r.id, 80); if (!id || !/^[a-z0-9-]+$/.test(id) || baseIds.has(id)) continue;
    const q = str(r.q, 4000); const ch = Array.isArray(r.ch) ? r.ch.slice(0, 4).map((c) => str(c, 400)) : null;
    if (!q || !ch || ch.length !== 4 || ch.some((c) => c == null)) continue;
    const year = Number.isInteger(r.year) && r.year > 1980 && r.year < 2100 ? r.year : null;
    const n = Number.isInteger(r.n) && r.n > 0 && r.n < 100 ? r.n : null;
    const div = DIVISIONS.includes(r.div) ? r.div : null;
    const topic = str(r.topic, 60); const skill = str(r.skill, 120);
    if (!year || !n || !div || !topic || !skill) continue;
    const s = r.stats && typeof r.stats === "object" ? r.stats : {};
    const num = (v, lo, hi) => (typeof v === "number" && isFinite(v) && v >= lo && v <= hi ? v : null);
    const stats = { n: num(s.n, 1, 100000), pc: num(s.pc, 0, 100), pa: num(s.pa, 0, 100), top: num(s.top, 0, 100), pct: num(s.pct, 0, 100), tier: num(s.tier, 1, 5), thrown: s.thrown === true, noisy: s.noisy === true, extrap: s.extrap === true };
    if (stats.pct == null || stats.tier == null) { delete stats.pct; delete stats.tier; }
    out.problems.push({
      id, year, n, div, topic, skill, q, ch,
      comp: str(r.comp, 60) || "Competition", test: str(r.test, 40) || "Individual",
      a: typeof r.a === "string" && /^[A-E]{1,2}$/.test(r.a) && new Set(r.a).size === r.a.length ? r.a : null,
      idea: str(r.idea, 2000) || "", note: str(r.note, 600),
      trap: r.trap && ["A","B","C","D","E"].includes(r.trap.choice) && str(r.trap.why, 600) ? { choice: r.trap.choice, why: r.trap.why } : null,
      setup: (Array.isArray(r.setup) ? r.setup : r.setup ? [r.setup] : []).slice(0, 4).filter((s) => typeof s === "string" && (out.setups[s] || BANK.setups[s])),
      fig: FIGS.has(r.fig) ? r.fig : null, kind: r.kind === "trap" || r.kind === "hard" ? r.kind : null, stats
    });
  }
  return out;
}
function renderData() {
  const v = $("view-data"); v.textContent = "";
  const all = allProblems();
  const tests = new Map();
  for (const p of all) {
    const k = `${p.year}|${p.comp}|${p.div}|${p.test}`;
    if (!tests.has(k)) tests.set(k, { p, count: 0, rated: 0 });
    const t = tests.get(k); t.count++; if (scored(p)) t.rated++;
  }
  const rows = [...tests.values()].sort((a, b) => b.p.year - a.p.year);
  const tbl = el("table", {}, el("thead", {}, el("tr", {}, ["Test", "Division", "Students", "Mean score", "Problems", "Rated"].map((h) => el("th", { scope: "col", text: h })))),
    el("tbody", {}, rows.map(({ p, count, rated }) => {
      const f = BANK.fields[p.id.replace(/-\d+$/, "")];
      return el("tr", {}, el("td", { text: `${p.year} ${p.comp}, ${p.test}` }), el("td", { text: p.div }),
        el("td", { text: f ? String(f.n) : "–" }), el("td", { text: f ? `${f.mean} of 150` : "–" }),
        el("td", { text: String(count) }), el("td", { text: String(rated) }));
    })));
  v.append(
    el("h2", { text: "What's in the bank" }),
    el("p", { text: `${all.length} problems, ${all.filter(scored).length} with difficulty ratings. Every answer key was checked by hand, and each score report was reconstructed and matched against every student total and every per-question total.` }),
    el("div", { class: "tablewrap" }, tbl),
    el("h2", { text: "How difficulty is measured" }),
    el("p", { text: "For each problem, the rating is the percentile of the field a student needs to reach to have a 50% chance of solving it, estimated from how students of every score did on the other questions. Blanks count as not solved, so a question most people skipped rates as hard." }),
    el("div", { class: "legend" }, [["1", "under 50th percentile"], ["2", "50th to 75th"], ["3", "75th to 90th"], ["4", "90th to 98th"], ["5", "above 98th"]].map(([t, d]) => el("span", {}, el("i", { style: `background:var(--t${t})` }), `Tier ${t}: ${d}`))),
    el("p", { style: "margin-top:10px", text: "A Trap tag means strong students confidently picked the same wrong answer, not that most people skipped it. Comparing years assumes each year's States field is about equally strong." }),
    el("p", { text: "A few questions don't separate stronger students from weaker ones at all. Their ratings come from the plain correct rate instead and are marked approximate; that pattern usually points at wording or at a disputed answer." }),
    el("p", { text: "On the hardest problems no group of students, not even the strongest, reaches a 50% solve rate. There the 50% point sits past the top of the field, so no percentile is shown and the ruler's marker is drawn open at the end. Those problems are still ranked by the fit, but the exact position is an extrapolation." }),
    el("h2", { text: "Privacy" }),
    el("p", { text: "This page contains no student names, schools, or individual results, only per-question totals. It sends nothing anywhere, and nothing you do here is seen by anyone else: answers you click and sets you build stay in your own browser. Its only outside requests load the fonts and the math and PDF tools." }));
  if (!PUBLIC_BUILD) v.append(el("p", { text: "Use a problem file exported by your bank server. Files are checked field by field: anything that isn't a problem field is dropped, including any names, and figures can only point to the built-in figure set." }));
  if (PUBLIC_BUILD) {
    v.append(el("h2", { text: "Diagnostics" }), el("p", { style: "font-size:13px;color:var(--muted)", text:
      `${allProblems().length} problems loaded · math renderer ${window.MathJax && window.MathJax.typesetPromise ? "ready" : "not loaded"} · ${navigator.userAgent.slice(0, 110)}` }));
    return;
  }
  const input = el("input", { type: "file", accept: "application/json,.json", id: "importfile" });
  const status = el("p", { class: "status", role: "status" });
  input.addEventListener("change", async () => {
    status.className = "status";
    const f = input.files && input.files[0]; if (!f) return;
    if (f.size > 5 * 1024 * 1024) { status.className = "status err"; status.textContent = "That file is over 5 MB. Export a smaller set."; return; }
    let raw; try { raw = JSON.parse(await f.text()); } catch (e) { status.className = "status err"; status.textContent = "That file isn't valid JSON."; return; }
    const clean = sanitizeImport(raw);
    if (!clean || !clean.problems.length) { status.className = "status err"; status.textContent = "No usable problems found. Each needs an id, year, division, topic, skill, statement, and four choices."; return; }
    const merged = { problems: imported.problems.filter((p) => !clean.problems.some((c) => c.id === p.id)).concat(clean.problems), setups: Object.assign({}, imported.setups, clean.setups) };
    imported = merged;
    const saved = store(IMPORT_KEY, merged);
    state.years = new Set(years());
    renderRail(); renderList(); renderBuildForm(); renderData();
    $("view-data").querySelector(".status").textContent = `Added ${clean.problems.length} problems.${saved ? "" : " This browser blocked storage, so they'll be gone after you close the page."}`;
  });
  const exportBtn = el("button", { class: "btn", type: "button", text: "Download the bank as JSON" });
  exportBtn.addEventListener("click", async () => {
    const data = JSON.stringify({ version: 1, setups: Object.assign({}, BANK.setups, imported.setups), problems: allProblems() }, null, 1);
    try { const r = await saveFile("problem-bank.json", new Blob([data], { type: "application/json" })); status.className = "status"; status.textContent = r === "declined" ? "Download canceled." : "Bank downloaded."; }
    catch (e) { status.className = "status err"; status.textContent = "The download couldn't start here."; }
  });
  const removeBtn = el("button", { class: "btn", type: "button", text: `Remove added problems (${imported.problems.length})`, disabled: !imported.problems.length });
  removeBtn.addEventListener("click", () => {
    for (const p of imported.problems) cardCache.delete(p.id);
    imported = { problems: [], setups: {} }; store(IMPORT_KEY, null);
    state.set = state.set.filter((id) => BANK.problems.some((p) => p.id === id)); state.pinned = state.pinned.filter((id) => BANK.problems.some((p) => p.id === id));
    state.years = new Set(years()); renderRail(); renderList(); renderBuildForm(); renderSet(); updatePinCount(); renderData();
  });
  const diag = [
    `${allProblems().length} problems loaded`,
    `math renderer ${window.MathJax && window.MathJax.typesetPromise ? "ready" : "not loaded"}`,
    `downloads ${downloadsNS ? "via this app" : "via the browser"}`,
    `storage ${store("bank.selftest", 1) ? "available" : "blocked"}`,
    navigator.userAgent.slice(0, 120),
  ].join(" · ");
  v.append(el("h2", { text: "Diagnostics" }),
    el("p", { style: "font-size:13px;color:var(--muted)", text: diag }),
    el("h2", { text: "Add problems from a file" }));
  v.append(el("div", { class: "field" }, el("label", { class: "lbl", for: "importfile", text: "Problem file (.json)" }), input),
    el("div", { style: "display:flex;gap:8px;flex-wrap:wrap" }, exportBtn, removeBtn), status);
}

/* ---------- tabs ---------- */
function showView(name) {
  for (const t of ["browse", "build", "data", "admin"]) {
    if (!$("tab-" + t)) continue;
    $("tab-" + t).setAttribute("aria-selected", String(t === name));
    $("view-" + t).hidden = t !== name;
  }
  if (name === "build") renderSet();
}
document.querySelector(".tabs").addEventListener("click", (e) => { const b = e.target.closest(".tab"); if (b) showView(b.id.slice(4)); });
document.querySelector(".tabs").addEventListener("keydown", (e) => {
  const tabs = [...document.querySelectorAll(".tab")]; const i = tabs.indexOf(document.activeElement);
  if (i < 0 || (e.key !== "ArrowRight" && e.key !== "ArrowLeft")) return;
  const n = tabs[(i + (e.key === "ArrowRight" ? 1 : tabs.length - 1)) % tabs.length]; n.focus(); showView(n.id.slice(4));
});
$("sort").addEventListener("change", (e) => { state.sort = e.target.value; renderList(); });
$("filtertoggle").addEventListener("click", () => { const r = $("rail"); const open = !r.classList.contains("open"); r.classList.toggle("open", open); $("filtertoggle").setAttribute("aria-expanded", String(open)); });
$("buildform").addEventListener("submit", (e) => {
  e.preventDefault();
  try { generate(); }
  catch (err) {
    const s = $("b-status"); s.className = "status err";
    s.textContent = "Couldn't build the set: " + (err && err.message ? err.message : String(err));
  }
});
$("buildform").addEventListener("click", (e) => { if (e.target.closest('button[type="submit"]')) $("buildform").requestSubmit ? null : generate(); });
$("b-order").addEventListener("click", (e) => {
  const b = e.target.closest("button"); if (!b) return;
  bstate.order = b.dataset.v; [...$("b-order").children].forEach((c) => c.setAttribute("aria-pressed", String(c === b)));
  if (state.set.length) { state.set = orderIds(state.set); renderSet(); }
});
$("b-traps").addEventListener("change", updatePoolHint);
$("b-alltopics").addEventListener("click", () => { bstate.off.clear(); renderBuildForm(); });
$("b-notopics").addEventListener("click", () => { bVisibleTopics().forEach((tp) => bstate.off.add(tp)); renderBuildForm(); });
$("settitle").addEventListener("input", renderSetTitleOnly);
function renderSetTitleOnly() { if (state.set.length) $("set-title").textContent = `${$("settitle").value.trim() || "Practice set"}: ${state.set.length} problem${state.set.length > 1 ? "s" : ""}`; }
$("set-clear").addEventListener("click", () => {
  for (const id of state.pinned.slice()) togglePin(id);
  state.set = []; updatePinCount(); renderSet(); $("b-status").textContent = "";
});
$("set-pdf").addEventListener("click", makePDF);


/* ---------- owner admin (only when this page is served by your own bank server with web admin switched on) ---------- */
const admin = { csrf: null };
async function api(path, opts) {
  const r = await fetch(path, Object.assign({ credentials: "same-origin" }, opts || {}));
  let body = null; try { body = await r.clone().json(); } catch (e) { /* not json */ }
  if (!r.ok) throw new Error((body && body.detail) || `Request failed (${r.status})`);
  return { r, body };
}
function addAdminTab() {
  if ($("tab-admin")) return;
  const tab = el("button", { class: "tab", role: "tab", id: "tab-admin", "aria-controls": "view-admin", "aria-selected": "false", text: "Admin" });
  document.querySelector(".tabs").append(tab);
  const view = el("section", { class: "view data", id: "view-admin", role: "tabpanel", "aria-labelledby": "tab-admin", hidden: true });
  document.querySelector("main").append(view);
  renderAdmin();
}
function renderAdmin() {
  const v = $("view-admin"); if (!v) return; v.textContent = "";
  const status = el("p", { class: "status", role: "status" });
  if (!admin.csrf) {
    const pw = el("input", { type: "password", id: "adminpw", autocomplete: "current-password", maxlength: "256" });
    const form = el("form", { class: "field", autocomplete: "on" },
      el("label", { class: "lbl", for: "adminpw", text: "Admin password" }), pw,
      el("div", { style: "margin-top:12px" }, el("button", { class: "btn primary", type: "submit", text: "Sign in" })), status);
    form.addEventListener("submit", async (e) => {
      e.preventDefault(); status.className = "status";
      try {
        const { body } = await api("/api/admin/login", { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ password: pw.value }) });
        admin.csrf = body.csrf; pw.value = ""; renderAdmin();
      } catch (err) { status.className = "status err"; status.textContent = err.message; }
    });
    v.append(el("h2", { text: "Owner sign-in" }),
      el("p", { text: "Only you see this tab: it appears only on your own bank server, never on the public copy." }), form);
    return;
  }
  // signed in
  const year = el("input", { type: "number", id: "ad-year", min: "1990", max: "2099", value: String(new Date().getFullYear()) });
  const div = el("select", { id: "ad-div" }, DIVISIONS.map((d) => el("option", { value: d, text: d })));
  const comp = el("input", { type: "text", id: "ad-comp", value: "State Convention", maxlength: "60" });
  const test = el("input", { type: "text", id: "ad-test", value: "Individual", maxlength: "40" });
  const tid = el("input", { type: "text", id: "ad-id", maxlength: "80" });
  const slug = (s) => s.toLowerCase().replace(/state convention/, "states").replace(/[^a-z0-9]+/g, "-").replace(/^-|-$/g, "");
  const syncId = () => { tid.value = [year.value, slug(comp.value), slug(div.value === "Statistics" ? "stat" : div.value), slug(test.value === "Individual" ? "ind" : test.value)].filter(Boolean).join("-"); };
  [year, div, comp, test].forEach((x) => x.addEventListener("input", syncId)); syncId();
  const probs = el("input", { type: "file", id: "ad-probs", accept: ".json,application/json" });
  const report = el("input", { type: "file", id: "ad-report", accept: ".txt,text/plain" });
  const force = el("input", { type: "checkbox", id: "ad-force" });
  const up = el("form", {},
    el("div", { class: "field" }, el("label", { class: "lbl", for: "ad-year", text: "Year" }), year),
    el("div", { class: "field" }, el("label", { class: "lbl", for: "ad-div", text: "Division" }), div),
    el("div", { class: "field" }, el("label", { class: "lbl", for: "ad-comp", text: "Competition" }), comp),
    el("div", { class: "field" }, el("label", { class: "lbl", for: "ad-test", text: "Test" }), test),
    el("div", { class: "field" }, el("label", { class: "lbl", for: "ad-id", text: "Test id (filled in for you)" }), tid),
    el("div", { class: "field" }, el("label", { class: "lbl", for: "ad-probs", text: "Problems file (.json)" }), probs),
    el("div", { class: "field" }, el("label", { class: "lbl", for: "ad-report", text: "Score report (.txt, exactly as FAMAT exports it)" }), report),
    el("label", { class: "check" }, force, "Import even if the score report doesn't add up"),
    el("div", { style: "margin-top:12px" }, el("button", { class: "btn primary", type: "submit", text: "Add test" })), status);
  up.addEventListener("submit", async (e) => {
    e.preventDefault(); status.className = "status"; status.textContent = "Checking the files…";
    if (!probs.files[0] || !report.files[0]) { status.className = "status err"; status.textContent = "Choose both files first."; return; }
    const fd = new FormData();
    fd.append("meta", JSON.stringify({ id: tid.value, year: parseInt(year.value, 10), div: div.value, comp: comp.value, test: test.value }));
    fd.append("problems", probs.files[0]); fd.append("report", report.files[0]); fd.append("force", force.checked ? "true" : "false");
    try {
      const { body } = await api("/api/admin/tests", { method: "POST", headers: { "X-CSRF-Token": admin.csrf }, body: fd });
      status.textContent = `Added ${body.test}: ${body.students} students, ${body.problems} problems.` + (body.report_issues.length ? ` ${body.report_issues.length} report issues were overridden.` : " The report checked out.");
      await refreshFromServer(); listTests();
    } catch (err) { status.className = "status err"; status.textContent = err.message; }
  });
  const list = el("div", { class: "tablewrap", id: "ad-list" });
  const dl = el("button", { class: "btn primary", type: "button", text: "Download the public site file (index.html)" });
  const dlStatus = el("p", { class: "status", role: "status" });
  dl.addEventListener("click", async () => {
    dlStatus.className = "status"; dlStatus.textContent = "Building…";
    try {
      const { r } = await api("/api/admin/site");
      await saveFile("index.html", await r.blob());
      dlStatus.textContent = "Saved index.html. Upload it to your GitHub repository to update the public site.";
    } catch (err) { dlStatus.className = "status err"; dlStatus.textContent = err.message; }
  });
  const out = el("button", { class: "btn", type: "button", text: "Sign out" });
  out.addEventListener("click", async () => { try { await api("/api/admin/logout", { method: "POST" }); } catch (e) {} admin.csrf = null; renderAdmin(); });
  v.append(el("h2", { text: "Add a test" }),
    el("p", { text: "The problems file is the one Claude writes from the test and its solutions. The import stops and lists every mismatch if any student's score or any per-question total doesn't reconcile." }),
    up, el("h2", { text: "Tests in the bank" }), list,
    el("h2", { text: "Publish" }), el("p", { text: "The public copy carries the problems inside it, so after adding a test, download a fresh site file and upload it to GitHub in place of the old index.html." }),
    dl, dlStatus, el("div", { style: "margin-top:24px" }, out));
  listTests();
}
async function listTests() {
  const box = $("ad-list"); if (!box) return;
  try {
    const { body } = await api("/api/admin/tests");
    box.textContent = "";
    box.append(el("table", {}, el("thead", {}, el("tr", {}, ["Test", "Students", "Mean", ""].map((h) => el("th", { text: h })))),
      el("tbody", {}, body.map((t) => {
        const del = el("button", { class: "btn", type: "button", text: "Delete" });
        del.addEventListener("click", async () => {
          if (!confirm(`Delete ${t.id} and all its problems from the bank?`)) return;
          try { await api(`/api/admin/tests/${encodeURIComponent(t.id)}`, { method: "DELETE", headers: { "X-CSRF-Token": admin.csrf } }); await refreshFromServer(); listTests(); }
          catch (err) { alert(err.message); }
        });
        return el("tr", {}, el("td", { text: t.id }), el("td", { text: String(t.n_students) }), el("td", { text: String(t.mean) }), el("td", {}, del));
      }))));
  } catch (err) { if (/Sign in|expired/.test(err.message)) { admin.csrf = null; renderAdmin(); } else box.textContent = err.message; }
}
async function refreshFromServer() {
  await maybeLoadFromServer();
  renderRail(); renderList(); renderBuildForm(); renderSet(); renderData();
}

/* ---------- optional: load from a bank server when this page is served by one ---------- */
async function maybeLoadFromServer() {
  const meta = document.querySelector('meta[name="bank-api"]');
  const url = meta && meta.content;
  if (PUBLIC_BUILD || !url || !url.startsWith("/")) return; // the public copy never looks for a server
  try {
    const r = await fetch(url, { credentials: "same-origin", headers: { "Accept": "application/json" } });
    if (!r.ok) return;
    const data = await r.json();
    if (data && Array.isArray(data.problems)) { BANK.problems = data.problems; BANK.setups = data.setups || {}; BANK.fields = data.fields || BANK.fields; cardCache.clear(); state.years = new Set(years()); }
  } catch (e) { /* keep the embedded bank */ }
}

window.addEventListener("error", (e) => {
  if (document.getElementById("jserr")) return;
  const m = document.querySelector("main"); if (!m) return;
  m.prepend(el("div", { class: "notice", id: "jserr", role: "alert", style: "margin:0 0 14px", text:
    "Something in this page failed: " + (e.message || "unknown error") + (e.filename ? ` (line ${e.lineno})` : "") +
    ". Tell whoever maintains the bank, with your browser name and version." }));
});

function warnIfMathMissing() {
  setTimeout(() => {
    if (window.MathJax && window.MathJax.typesetPromise) return;
    const bar = el("div", { class: "notice", role: "status", style: "margin:0 0 14px", text:
      "Math isn't rendering: the page couldn't reach the math library, so formulas show as plain TeX. Everything else works. Reconnect and reload to fix it." });
    document.querySelector("main").prepend(bar);
  }, 12000);
}

(async function init() {
  await maybeLoadFromServer();
  const meta = document.querySelector('meta[name="bank-api"]');
  if (!PUBLIC_BUILD && meta && meta.content) {
    try { const r = await fetch("/api/admin/status", { credentials: "same-origin" }); if (r.ok && (await r.json()).enabled) addAdminTab(); } catch (e) { /* no admin */ }
  }
  renderRail(); renderList(); renderBuildForm(); renderSet(); renderData(); updatePinCount(); warnIfMathMissing();
})();
</script>
</body>
</html>
