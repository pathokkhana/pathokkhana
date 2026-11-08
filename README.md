<title>pathok khana Books</title>
<meta name="claude:viewport-fit-sides" content="cover">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Bodoni+Moda:opsz,wght@6..96,500;6..96,700&family=DM+Mono:wght@400;500&family=Figtree:wght@400;500;600;700&display=swap">
<style>
/* Layout concept: full-bleed deep-green hero over a quiet cool-grey shop floor; books are the only strong colour. Square-ish corners, hairline rules, one brass accent. */
:root{
  --bg:#EDEFF1; --surface:#FFFFFF; --surface-2:#E2E6E9; --fg:#12171B; --muted:#58646C; --line:#CED5DA;
  --accent:#0E5A4B; --accent-fg:#FFFFFF; --brass:#A9792B;
  --danger:#B3261E; --ok:#1E7A4A; --warn:#9A6200;
  --hero-bg:#0D2B25; --hero-fg:#EAF3EF; --hero-muted:#9DB8AF;
  --shadow:0 1px 2px rgba(15,25,30,.08),0 8px 24px rgba(15,25,30,.08);
  --display:"Bodoni Moda","Didot","Bodoni 72",Georgia,serif;
  --ui:"Figtree",system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;
  --mono:"DM Mono",ui-monospace,Menlo,Consolas,monospace;
}
@media (prefers-color-scheme: dark){
  :root:not([data-theme="light"]){
    --bg:#0E1311; --surface:#161C19; --surface-2:#1F2723; --fg:#EAEFEC; --muted:#93A099; --line:#2C3631;
    --accent:#4FC3A1; --accent-fg:#06231B; --brass:#D4A650;
    --danger:#F28B82; --ok:#6FD39B; --warn:#E2B04A;
    --hero-bg:#0A1B17; --hero-fg:#EAF3EF; --hero-muted:#8FAEA3;
    --shadow:0 1px 2px rgba(0,0,0,.4),0 8px 24px rgba(0,0,0,.35);
    color-scheme:dark;
  }
}
:root[data-theme="dark"]{
  --bg:#0E1311; --surface:#161C19; --surface-2:#1F2723; --fg:#EAEFEC; --muted:#93A099; --line:#2C3631;
  --accent:#4FC3A1; --accent-fg:#06231B; --brass:#D4A650;
  --danger:#F28B82; --ok:#6FD39B; --warn:#E2B04A;
  --hero-bg:#0A1B17; --hero-fg:#EAF3EF; --hero-muted:#8FAEA3;
  --shadow:0 1px 2px rgba(0,0,0,.4),0 8px 24px rgba(0,0,0,.35);
  color-scheme:dark;
}
*,*::before,*::after{box-sizing:border-box}
body{background:var(--bg);color:var(--fg);font:16px/1.55 var(--ui);-webkit-font-smoothing:antialiased}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);background:var(--surface);z-index:30}
a{color:inherit}
button,input,select,textarea{font:inherit;color:inherit}
img{display:block}
h1,h2,h3,h4,p{margin:0}
h1,h2,h3{text-wrap:balance}
:focus-visible{outline:2px solid var(--accent);outline-offset:2px}
.in{max-width:1180px;margin-inline:auto;padding-left:max(16px,env(safe-area-inset-left,0px));padding-right:max(16px,env(safe-area-inset-right,0px))}
.num{font-variant-numeric:tabular-nums}
.mono{font-family:var(--mono)}
.eyebrow{font:600 12px/1.4 var(--ui);letter-spacing:.14em;text-transform:uppercase;color:var(--muted)}

/* header */
.hdr{position:sticky;top:env(safe-area-inset-top,0px);z-index:20;background:var(--surface);border-bottom:1px solid var(--line)}
.hdr-in{position:relative;display:flex;align-items:center;gap:16px;min-height:64px}
.brand{font:700 26px/1 var(--display);text-decoration:none;letter-spacing:-.01em;margin-right:auto;display:flex;align-items:baseline;gap:8px}
.brand i{font-style:normal;width:7px;height:7px;background:var(--brass);display:inline-block;transform:translateY(-3px)}
.nav{display:flex;gap:4px;align-items:center}
.nav a{padding:8px 12px;text-decoration:none;font-weight:500;font-size:15px;color:var(--muted);border-radius:4px}
.nav a:hover,.nav a[aria-current="page"]{color:var(--fg)}
.nav a[aria-current="page"]{box-shadow:inset 0 -2px 0 var(--brass)}
.icon-btn{position:relative;display:inline-grid;place-items:center;width:44px;height:44px;border:0;background:transparent;border-radius:4px;cursor:pointer;color:var(--fg);text-decoration:none}
.icon-btn:hover{background:var(--surface-2)}
.badge-n{position:absolute;top:4px;right:2px;min-width:18px;height:18px;padding:0 5px;border-radius:9px;background:var(--accent);color:var(--accent-fg);font:600 11px/18px var(--ui);text-align:center}
.menu-btn{display:none}
svg.i{width:22px;height:22px;fill:none;stroke:currentColor;stroke-width:1.7;stroke-linecap:round;stroke-linejoin:round}

/* buttons & forms */
.btn{display:inline-flex;align-items:center;justify-content:center;gap:8px;min-height:44px;padding:0 20px;border-radius:4px;border:1px solid transparent;font:600 15px/1 var(--ui);cursor:pointer;text-decoration:none;white-space:nowrap}
.btn:disabled{opacity:.5;cursor:not-allowed}
.btn-p{background:var(--accent);color:var(--accent-fg)}
.btn-p:hover:not(:disabled){filter:brightness(1.08)}
.btn-o{background:transparent;border-color:var(--line);color:var(--fg)}
.btn-o:hover:not(:disabled){background:var(--surface-2)}
.btn-brass{background:var(--brass);color:#1B1305}
.btn-brass:hover{filter:brightness(1.07)}
.btn-d{background:transparent;border-color:var(--line);color:var(--danger)}
.btn-sm{min-height:36px;padding:0 12px;font-size:14px}
.btn-block{width:100%}
.field{display:grid;gap:6px;min-width:0}
.field>label,.lbl{font:600 13px/1.3 var(--ui);color:var(--muted)}
.inp,select.inp,textarea.inp{width:100%;min-height:44px;padding:10px 12px;background:var(--surface);border:1px solid var(--line);border-radius:4px;color:var(--fg)}
textarea.inp{resize:vertical;min-height:110px;line-height:1.5}
.inp:focus{border-color:var(--accent);outline:none;box-shadow:0 0 0 3px color-mix(in srgb,var(--accent) 25%,transparent)}
.grid2{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:14px}
.grid3{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:14px}
.hint{font-size:13px;color:var(--muted)}

/* covers */
.cover{container-type:inline-size;position:relative;aspect-ratio:2/3;width:100%;max-width:100%;border-radius:2px 6px 6px 2px;overflow:hidden;
  background:linear-gradient(155deg,hsl(var(--h) 42% 30%),hsl(var(--h) 48% 14%));color:hsl(var(--h) 60% 93%);
  box-shadow:0 1px 1px rgba(0,0,0,.25),0 10px 22px -8px rgba(0,0,0,.45)}
.cover::after{content:"";position:absolute;inset:0 auto 0 0;width:5%;background:linear-gradient(90deg,rgba(0,0,0,.4),rgba(255,255,255,.1) 55%,transparent)}
.cover .art{position:absolute;inset:0;opacity:.4}
.pat0 .art{background:repeating-radial-gradient(circle at 72% 80%,transparent 0 5cqw,hsl(var(--h) 60% 72% / .55) 5cqw 5.7cqw)}
.pat1 .art{background:repeating-linear-gradient(115deg,transparent 0 6cqw,hsl(var(--h) 60% 72% / .5) 6cqw 6.6cqw)}
.pat2 .art{background:radial-gradient(circle at 55% 64%,hsl(var(--h) 70% 66% / .6) 0 17cqw,transparent 17.6cqw)}
.pat3 .art{background:linear-gradient(hsl(var(--h) 60% 72% / .4) 1px,transparent 1px) 0 0/100% 9cqw,linear-gradient(90deg,hsl(var(--h) 60% 72% / .4) 1px,transparent 1px) 0 0/9cqw 100%}
.cv{position:absolute;inset:0;display:flex;flex-direction:column;justify-content:space-between;padding:11cqw 9cqw 10cqw 14cqw}
.c-author{font:600 5.4cqw/1.25 var(--ui);letter-spacing:.14em;text-transform:uppercase;opacity:.9}
.c-title{font:700 12cqw/1.04 var(--display);text-wrap:balance;overflow-wrap:anywhere}
.c-mark{display:block;width:11cqw;height:1px;background:currentColor;opacity:.75}
.cover-img img{width:100%;height:100%;object-fit:cover}
.cover-img::after{opacity:.6}

/* hero */
.hero{background:var(--hero-bg);color:var(--hero-fg)}
.hero-in{display:grid;grid-template-columns:minmax(0,1.1fr) minmax(0,.9fr);gap:32px;align-items:center;padding-block:48px}
.hero .eyebrow{color:var(--brass)}
.hero h1{font:700 clamp(38px,6.2vw,72px)/1 var(--display);letter-spacing:-.02em;margin:14px 0 16px}
.hero p.lead{color:var(--hero-muted);max-width:46ch;font-size:17px}
.hero-cta{display:flex;flex-wrap:wrap;gap:12px;margin-top:26px}
.hero .btn-o{border-color:rgba(255,255,255,.28);color:var(--hero-fg)}
.hero .btn-o:hover{background:rgba(255,255,255,.08)}
.fan{position:relative;height:340px;max-width:420px;width:100%;margin-inline:auto}
.fan .cover{position:absolute;width:42%;bottom:6%}
.fan a{position:absolute;display:block;width:42%;bottom:6%;transition:transform .25s}
.fan a .cover{position:static;width:100%}
.fan a:nth-child(1){left:2%;transform:rotate(-9deg) translateY(10px)}
.fan a:nth-child(2){left:29%;transform:translateY(-14px);z-index:2}
.fan a:nth-child(3){right:2%;transform:rotate(8deg) translateY(10px)}
.fan a:hover{transform:translateY(-10px) rotate(0)}
.perks{background:var(--surface);border-bottom:1px solid var(--line)}
.perks-in{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:16px;padding-block:16px}
.perk{display:flex;gap:10px;align-items:center;font-size:14px;color:var(--muted)}
.perk b{color:var(--fg);font-weight:600}
.perk svg.i{flex:none;color:var(--brass);width:20px;height:20px}

/* shop */
.sec{padding-block:36px 56px}
.sec-h{display:flex;align-items:end;justify-content:space-between;gap:16px;flex-wrap:wrap;margin-bottom:18px}
.sec-h h2,.page-h{font:700 clamp(28px,4vw,40px)/1.1 var(--display);letter-spacing:-.01em}
.toolbar{display:grid;grid-template-columns:minmax(0,1fr) auto;gap:12px;margin-bottom:14px}
.search{position:relative}
.search svg.i{position:absolute;left:12px;top:11px;width:20px;height:20px;color:var(--muted)}
.search .inp{padding-left:42px}
.chips{display:flex;gap:8px;overflow-x:auto;padding-bottom:6px;margin-bottom:22px;scrollbar-width:thin}
.chip{flex:none;min-height:36px;padding:0 14px;border:1px solid var(--line);background:var(--surface);border-radius:999px;font:500 14px var(--ui);cursor:pointer}
.chip[aria-pressed="true"]{background:var(--fg);border-color:var(--fg);color:var(--bg)}
.grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(176px,1fr));gap:30px 22px}
.card{display:flex;flex-direction:column;gap:14px;min-width:0}
.card-cover{position:relative;display:block;transition:transform .2s}
.card-cover:hover{transform:translateY(-4px)}
.tag{position:absolute;top:10px;right:-4px;z-index:2;padding:3px 9px;font:700 11px/1.4 var(--ui);letter-spacing:.06em;text-transform:uppercase;background:var(--brass);color:#1B1305;border-radius:2px}
.tag.out{background:var(--fg);color:var(--bg)}
.card-body{display:grid;gap:3px;min-width:0}
.cat{font:600 11px/1.4 var(--ui);letter-spacing:.12em;text-transform:uppercase;color:var(--muted)}
.card h3{font:700 18px/1.2 var(--display)}
.card h3 a{text-decoration:none}
.card h3 a:hover{text-decoration:underline;text-decoration-color:var(--brass);text-underline-offset:3px}
.by{color:var(--muted);font-size:14px}
.card-foot{display:flex;align-items:center;justify-content:space-between;gap:8px;margin-top:8px}
.price{font:600 17px/1 var(--ui);font-variant-numeric:tabular-nums}
.price s{color:var(--muted);font-weight:400;font-size:14px;margin-left:6px}
.add{display:inline-grid;place-items:center;width:42px;height:42px;border-radius:4px;border:1px solid var(--line);background:var(--surface);cursor:pointer}
.add:hover:not(:disabled){background:var(--accent);border-color:var(--accent);color:var(--accent-fg)}
.add:disabled{opacity:.4;cursor:not-allowed}
.empty{display:grid;gap:10px;justify-items:start;padding:40px 28px;background:var(--surface);border:1px dashed var(--line);border-radius:6px}
.empty h3{font:700 24px/1.2 var(--display)}

/* detail */
.crumbs{font-size:14px;color:var(--muted);padding-top:24px}
.crumbs a{text-decoration:none}.crumbs a:hover{color:var(--fg)}
.detail{display:grid;grid-template-columns:minmax(0,380px) minmax(0,1fr);gap:48px;padding-block:24px 48px}
.detail .cover{box-shadow:0 2px 2px rgba(0,0,0,.25),0 24px 40px -14px rgba(0,0,0,.5)}
.detail h1{font:700 clamp(32px,4.5vw,52px)/1.05 var(--display);letter-spacing:-.015em;margin:8px 0 6px}
.detail .by{font-size:18px}
.detail .price{font-size:30px;margin:20px 0 4px}
.detail .price s{font-size:18px}
.stock{font-size:14px;font-weight:600}
.stock.ok{color:var(--ok)}.stock.low{color:var(--warn)}.stock.none{color:var(--danger)}
.desc{max-width:62ch;margin:18px 0;color:var(--fg);font-size:17px;line-height:1.65}
.buy{display:flex;flex-wrap:wrap;gap:12px;align-items:center;margin:22px 0}
.qty{display:inline-flex;align-items:center;border:1px solid var(--line);border-radius:4px;background:var(--surface)}
.qty button{width:40px;height:42px;border:0;background:transparent;cursor:pointer;font-size:18px}
.qty button:hover{background:var(--surface-2)}
.qty span{min-width:30px;text-align:center;font-weight:600;font-variant-numeric:tabular-nums}
.meta{display:grid;grid-template-columns:repeat(auto-fit,minmax(130px,1fr));gap:0;border-top:1px solid var(--line);margin-top:8px}
.meta div{padding:14px 0;border-bottom:1px solid var(--line)}
.meta dt{font:600 11px/1.4 var(--ui);letter-spacing:.12em;text-transform:uppercase;color:var(--muted)}
.meta dd{margin:2px 0 0;font-weight:500;overflow-wrap:anywhere}

/* cart & checkout */
.page{padding-block:36px 64px}
.two{display:grid;grid-template-columns:minmax(0,1fr) 360px;gap:32px;align-items:start;margin-top:22px}
.panel{background:var(--surface);border:1px solid var(--line);border-radius:6px;padding:22px}
.panel h2,.panel h3{font:700 22px/1.2 var(--display);margin-bottom:14px}
.sticky{position:sticky;top:calc(env(safe-area-inset-top,0px) + 84px)}
.line{display:grid;grid-template-columns:64px minmax(0,1fr) auto;gap:16px;padding:16px 0;border-bottom:1px solid var(--line);align-items:center}
.line:first-child{padding-top:0}
.line h3{font:700 17px/1.2 var(--display);margin:0}
.line h3 a{text-decoration:none}
.line .by{font-size:13px}
.line-r{display:grid;gap:8px;justify-items:end}
.link-btn{border:0;background:none;padding:0;color:var(--muted);font-size:13px;cursor:pointer;text-decoration:underline}
.link-btn:hover{color:var(--danger)}
.sum{display:grid;gap:10px}
.sum div{display:flex;justify-content:space-between;gap:12px;font-variant-numeric:tabular-nums}
.sum .tot{font-weight:700;font-size:20px;border-top:1px solid var(--line);padding-top:12px;margin-top:4px}
.opt{display:flex;gap:12px;align-items:flex-start;padding:14px;border:1px solid var(--line);border-radius:4px;cursor:pointer;background:var(--surface)}
.opt:has(input:checked){border-color:var(--accent);box-shadow:inset 0 0 0 1px var(--accent)}
.opt input{margin-top:4px;accent-color:var(--accent)}
.opt b{display:block}
.form{display:grid;gap:14px}
.done{display:grid;gap:14px;justify-items:start;max-width:620px}
.done h1{font:700 clamp(32px,5vw,48px)/1.05 var(--display)}
.note{padding:12px 14px;border-radius:4px;background:color-mix(in srgb,var(--warn) 14%,transparent);border:1px solid color-mix(in srgb,var(--warn) 40%,transparent);font-size:14px}
.ok-note{background:color-mix(in srgb,var(--ok) 12%,transparent);border-color:color-mix(in srgb,var(--ok) 40%,transparent)}
.contact-grid{display:grid;grid-template-columns:minmax(0,.8fr) minmax(0,1.2fr);gap:32px;margin-top:22px;align-items:start}
.info-list{display:grid;gap:0;margin:0}
.info-list div{padding:16px 0;border-bottom:1px solid var(--line)}
.info-list dt{font:600 11px/1.4 var(--ui);letter-spacing:.12em;text-transform:uppercase;color:var(--muted)}
.info-list dd{margin:3px 0 0;font-size:17px;overflow-wrap:anywhere}

/* footer */
.ftr{background:var(--surface);border-top:1px solid var(--line)}
.ftr-in{display:flex;flex-wrap:wrap;gap:16px 32px;justify-content:space-between;align-items:center;padding-block:28px}
.ftr .brand{margin:0;font-size:22px}
.ftr nav{display:flex;flex-wrap:wrap;gap:6px 20px;font-size:14px;color:var(--muted)}
.ftr nav a{text-decoration:none}.ftr nav a:hover{color:var(--fg)}
.copy{font-size:13px;color:var(--muted);width:100%}

/* admin */
.tabs{display:flex;gap:4px;overflow-x:auto;border-bottom:1px solid var(--line);margin:18px 0 22px}
.tab{flex:none;min-height:44px;padding:0 16px;border:0;background:none;font:600 15px var(--ui);color:var(--muted);cursor:pointer;border-bottom:2px solid transparent;margin-bottom:-1px}
.tab[aria-selected="true"]{color:var(--fg);border-bottom-color:var(--brass)}
.stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(170px,1fr));gap:14px;margin-bottom:22px}
.stat{background:var(--surface);border:1px solid var(--line);border-radius:6px;padding:16px 18px}
.stat b{display:block;font:700 30px/1.1 var(--display);margin-top:6px;font-variant-numeric:tabular-nums}
.cols{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:18px}
.rows{display:grid}
.row{display:grid;grid-template-columns:48px minmax(0,1fr) auto auto;grid-template-areas:"t i m a";gap:6px 14px;align-items:center;padding:12px 0;border-bottom:1px solid var(--line)}
.row:last-child{border-bottom:0}
.row .t{grid-area:t}.row .i{grid-area:i;min-width:0}.row .m{grid-area:m;text-align:right}.row .a{grid-area:a;display:flex;gap:8px;justify-content:flex-end;flex-wrap:wrap}
.row .i b{display:block;overflow-wrap:anywhere}
.row .i span{font-size:13px;color:var(--muted)}
.row .m b{display:block;font-variant-numeric:tabular-nums}
.pill{display:inline-flex;align-items:center;padding:1px 10px;border-radius:999px;font:600 12px/1.7 var(--ui);white-space:nowrap}
.s-pending{background:color-mix(in srgb,var(--warn) 16%,transparent);color:var(--warn)}
.s-confirmed{background:color-mix(in srgb,var(--accent) 16%,transparent);color:var(--accent)}
.s-shipped{background:color-mix(in srgb,var(--brass) 20%,transparent);color:var(--brass)}
.s-delivered{background:color-mix(in srgb,var(--ok) 16%,transparent);color:var(--ok)}
.s-cancelled{background:color-mix(in srgb,var(--danger) 14%,transparent);color:var(--danger)}
.s-low{background:color-mix(in srgb,var(--warn) 16%,transparent);color:var(--warn)}
.s-out{background:color-mix(in srgb,var(--danger) 14%,transparent);color:var(--danger)}
.s-ok{background:color-mix(in srgb,var(--ok) 14%,transparent);color:var(--ok)}
.order{border-bottom:1px solid var(--line);padding:16px 0}
.order:last-child{border-bottom:0}
.order-top{display:flex;flex-wrap:wrap;gap:8px 16px;align-items:center;justify-content:space-between}
.order-top .mono{font-weight:500}
.order details{margin-top:10px}
.order summary{cursor:pointer;color:var(--muted);font-size:14px}
.order table{width:100%;border-collapse:collapse;margin-top:10px;font-size:14px}
.order td{padding:6px 0;border-bottom:1px solid var(--line)}
.order td:last-child{text-align:right;font-variant-numeric:tabular-nums}
.order-acts{display:flex;flex-wrap:wrap;gap:8px;align-items:center;margin-top:12px}
.order-acts select{width:auto;min-width:150px}
.msg{padding:16px 0;border-bottom:1px solid var(--line);display:grid;gap:6px}
.msg:last-child{border-bottom:0}
.msg p{white-space:pre-wrap;overflow-wrap:anywhere}
.msg.unread .nm::before{content:"";display:inline-block;width:8px;height:8px;border-radius:50%;background:var(--brass);margin-right:8px}
.banner{display:flex;flex-wrap:wrap;gap:12px 20px;align-items:center;justify-content:space-between;padding:16px 18px;border:1px solid var(--line);border-left:4px solid var(--brass);background:var(--surface);border-radius:4px;margin-bottom:20px}
.banner p{max-width:60ch}
.confirm{display:flex;gap:8px;align-items:center;flex-wrap:wrap;font-size:14px}

/* modal & toast */
.overlay{position:fixed;inset:0;z-index:50;background:rgba(5,10,8,.6);display:grid;place-items:center;padding:max(16px,env(safe-area-inset-top,0px)) max(16px,env(safe-area-inset-right,0px)) max(16px,env(safe-area-inset-bottom,0px)) max(16px,env(safe-area-inset-left,0px))}
.modal{background:var(--surface);border-radius:6px;width:min(720px,100%);max-height:100%;overflow:auto;box-shadow:var(--shadow);border:1px solid var(--line)}
.modal-h{position:sticky;top:0;z-index:2;background:var(--surface);display:flex;justify-content:space-between;align-items:center;padding:14px 20px;border-bottom:1px solid var(--line)}
.modal-h h2{font:700 24px/1.2 var(--display)}
.modal-b{padding:20px}
.pf{display:grid;grid-template-columns:150px minmax(0,1fr);gap:22px;align-items:start}
.pf-side{display:grid;gap:10px}
.pf-main{display:grid;gap:14px;min-width:0}
.modal-f{position:sticky;bottom:0;background:var(--surface);border-top:1px solid var(--line);padding:14px 20px;display:flex;gap:10px;justify-content:flex-end;flex-wrap:wrap}
input[type=range].inp{padding:0;min-height:30px;accent-color:var(--accent)}
.hue-bar{height:8px;border-radius:4px;background:linear-gradient(90deg,hsl(0 50% 35%),hsl(60 50% 35%),hsl(120 50% 35%),hsl(180 50% 35%),hsl(240 50% 35%),hsl(300 50% 35%),hsl(360 50% 35%))}
.check{display:flex;gap:10px;align-items:center;min-height:44px}
.check input{width:20px;height:20px;accent-color:var(--accent)}
.toast{position:fixed;left:50%;bottom:calc(20px + env(safe-area-inset-bottom,0px));transform:translateX(-50%);z-index:60;background:var(--fg);color:var(--bg);padding:12px 18px;border-radius:4px;box-shadow:var(--shadow);font-size:15px;max-width:calc(100% - 32px)}
.sr{position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0 0 0 0);white-space:nowrap}

/* authors, follow, notifications */
.av{display:inline-grid;place-items:center;width:44px;height:44px;border-radius:50%;object-fit:cover;background:var(--surface-2);color:var(--muted);font:700 18px/1 var(--display);flex:none;overflow:hidden}
.av.lg{width:112px;height:112px;font-size:44px}
.av.sm{width:34px;height:34px;font-size:15px}
.author-line{display:flex;align-items:center;gap:12px;flex-wrap:wrap;margin:8px 0}
.author-line a{font-size:18px;text-decoration:none;color:var(--muted)}
.author-line a:hover{color:var(--fg);text-decoration:underline;text-decoration-color:var(--brass);text-underline-offset:3px}
.btn-follow[aria-pressed="true"]{background:var(--surface-2);border-color:var(--line);color:var(--fg)}
.author-hero{display:flex;gap:22px;align-items:center;flex-wrap:wrap;padding-block:28px 4px}
.notif{position:absolute;right:max(16px,env(safe-area-inset-right,0px));top:calc(100% + 6px);width:min(380px,calc(100vw - 32px));background:var(--surface);border:1px solid var(--line);border-radius:6px;box-shadow:var(--shadow);max-height:70vh;overflow:auto;z-index:25}
.notif h3{font:700 18px/1.2 var(--display);padding:14px 16px 8px}
.notif-item{display:grid;grid-template-columns:40px minmax(0,1fr);gap:12px;padding:10px 16px;text-decoration:none;border-top:1px solid var(--line);align-items:center}
.notif-item:hover{background:var(--surface-2)}
.notif-item b{display:block;font-size:14px;line-height:1.3}
.notif-item span{font-size:13px;color:var(--muted)}
.notif p.hint{padding:4px 16px 14px}
.foll{display:flex;flex-wrap:wrap;gap:6px 12px;padding:10px 16px 14px;border-top:1px solid var(--line);font-size:13px;color:var(--muted)}
.pf-side .av.lg{width:84px;height:84px;font-size:32px}
.ab{display:grid;gap:8px;justify-items:start}

/* responsive */
@media (max-width:860px){
  .menu-btn{display:inline-grid}
  .nav{display:none;position:absolute;left:0;right:0;top:100%;flex-direction:column;align-items:stretch;background:var(--surface);border-bottom:1px solid var(--line);padding:8px max(16px,env(safe-area-inset-right,0px)) 12px max(16px,env(safe-area-inset-left,0px))}
  .nav.open{display:flex}
  .nav a{padding:14px 4px;border-bottom:1px solid var(--line);border-radius:0}
  .nav a[aria-current="page"]{box-shadow:none;color:var(--accent);font-weight:700}
  .hero-in{grid-template-columns:minmax(0,1fr);padding-block:36px 28px;gap:18px}
  .fan{height:260px;max-width:340px}
  .perks-in{grid-template-columns:minmax(0,1fr);gap:10px}
  .detail{grid-template-columns:minmax(0,1fr);gap:24px}
  .detail .cover{max-width:260px}
  .two,.contact-grid{grid-template-columns:minmax(0,1fr)}
  .sticky{position:static}
  .cols{grid-template-columns:minmax(0,1fr)}
  .pf{grid-template-columns:minmax(0,1fr)}
  .pf-side{grid-template-columns:110px minmax(0,1fr);align-items:start}
}
@media (max-width:560px){
  .grid{grid-template-columns:repeat(2,minmax(0,1fr));gap:26px 14px}
  .card h3{font-size:16px}
  .toolbar{grid-template-columns:minmax(0,1fr)}
  .grid2,.grid3{grid-template-columns:minmax(0,1fr)}
  .row{grid-template-columns:44px minmax(0,1fr);grid-template-areas:"t i" "m m" "a a"}
  .row .m{text-align:left;display:flex;gap:10px;align-items:center}
  .row .m b{display:inline}
  .row .a{justify-content:flex-start}
  .line{grid-template-columns:52px minmax(0,1fr)}
  .line-r{grid-column:1/-1;grid-template-columns:auto auto;justify-content:space-between;justify-items:start;align-items:center}
  .panel{padding:18px}
  .brand{font-size:23px}
}
@media (prefers-reduced-motion:reduce){*{transition:none!important;animation:none!important}}
</style>

<div id="app"></div>

<script>
(function(){
'use strict';

/* ---------- sample catalogue (shown until the owner imports or replaces it) ---------- */
var SAMPLE=[
 {id:'b-pride',title:'Pride and Prejudice',author:'Jane Austen',category:'Classics',price:12.5,oldPrice:15,stock:14,pages:432,format:'Paperback',isbn:'',hue:345,featured:true,description:'A sharp, funny portrait of manners and money in Regency England, following Elizabeth Bennet as she learns to trust her own judgment over first impressions.'},
 {id:'b-frankenstein',title:'Frankenstein',author:'Mary Shelley',category:'Gothic',price:11,oldPrice:0,stock:9,pages:288,format:'Paperback',isbn:'',hue:150,featured:false,description:'A young scientist builds life and then refuses to answer for it. Shelley\'s novel still asks what creators owe to the things they make.'},
 {id:'b-moby',title:'Moby-Dick',author:'Herman Melville',category:'Adventure',price:16.9,oldPrice:0,stock:0,pages:720,format:'Hardcover',isbn:'',hue:205,featured:false,description:'Captain Ahab\'s pursuit of a single white whale grows into a sprawling meditation on obsession, labour and the sea.'},
 {id:'b-gatsby',title:'The Great Gatsby',author:'F. Scott Fitzgerald',category:'Fiction',price:10.5,oldPrice:0,stock:21,pages:208,format:'Paperback',isbn:'',hue:45,featured:true,description:'A summer on Long Island, a house full of strangers and one man\'s belief that the past can be bought back. Short, glittering and sad.'},
 {id:'b-dracula',title:'Dracula',author:'Bram Stoker',category:'Gothic',price:12,oldPrice:14.5,stock:2,pages:418,format:'Paperback',isbn:'',hue:0,featured:false,description:'Told through letters, diaries and newspaper clippings: a count crosses the sea to England and a small group sets out to stop him.'},
 {id:'b-jane-eyre',title:'Jane Eyre',author:'Charlotte Brontë',category:'Classics',price:13.25,oldPrice:0,stock:11,pages:532,format:'Paperback',isbn:'',hue:275,featured:false,description:'An orphan becomes a governess and meets a master with secrets. A story about self-respect, told in a voice that does not flinch.'},
 {id:'b-meditations',title:'Meditations',author:'Marcus Aurelius',category:'Philosophy',price:9.9,oldPrice:0,stock:30,pages:256,format:'Paperback',isbn:'',hue:30,featured:true,description:'Private notes written by a Roman emperor to himself on duty, temper and the shortness of life. Practical, calm and easy to read a page at a time.'},
 {id:'b-art-of-war',title:'The Art of War',author:'Sun Tzu',category:'Philosophy',price:8.75,oldPrice:0,stock:3,pages:160,format:'Paperback',isbn:'',hue:15,featured:false,description:'Short chapters on strategy, preparation and restraint, written more than two thousand years ago and still quoted in boardrooms.'},
 {id:'b-crime',title:'Crime and Punishment',author:'Fyodor Dostoevsky',category:'Fiction',price:15.4,oldPrice:0,stock:8,pages:576,format:'Paperback',isbn:'',hue:220,featured:false,description:'A student in St Petersburg commits a murder he has argued himself into, then has to live inside the consequences.'},
 {id:'b-wuthering',title:'Wuthering Heights',author:'Emily Brontë',category:'Classics',price:11.8,oldPrice:0,stock:12,pages:384,format:'Paperback',isbn:'',hue:120,featured:false,description:'Two families, one moor and a love that turns into a long act of revenge. Dark, strange and hard to put down.'},
 {id:'b-alice',title:'Alice\'s Adventures in Wonderland',author:'Lewis Carroll',category:'Children\'s',price:9.5,oldPrice:12,stock:17,pages:192,format:'Hardcover',isbn:'',hue:190,featured:false,description:'A girl follows a white rabbit down a hole into a world where logic keeps changing its mind. Funny and odd for readers of any age.'},
 {id:'b-gitanjali',title:'Gitanjali',author:'Rabindranath Tagore',category:'Poetry',price:10.2,oldPrice:0,stock:15,pages:144,format:'Paperback',isbn:'',hue:320,featured:true,description:'Song offerings in prose translation, the collection that brought Tagore the Nobel Prize in Literature in 1913. Quiet, devotional and clear.'},
 {id:'b-odyssey',title:'The Odyssey',author:'Homer',category:'Classics',price:18,oldPrice:0,stock:7,pages:560,format:'Hardcover',isbn:'',hue:250,featured:false,description:'Ten years of storms, monsters and temptations on the way home from Troy, and a household waiting at the other end.'}
];
var DEFAULTS={name:'Marginalia',currency:'$',shipping:4.5,freeOver:40,email:'hello@yourstore.com',phone:'+1 555 0100',address:'12 Folio Lane, Your City',hours:'Sat to Thu, 10:00 to 19:00',catalog:''};
var STATUSES=['pending','confirmed','shipped','delivered','cancelled'];

/* ---------- helpers ---------- */
var app=document.getElementById('app');
function esc(s){return String(s==null?'':s).replace(/[&<>"']/g,function(c){return {'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]})}
var ls={get:function(k,d){try{var v=localStorage.getItem(k);return v?JSON.parse(v):d}catch(e){return d}},set:function(k,v){try{localStorage.setItem(k,JSON.stringify(v))}catch(e){}}};
function hashStr(s){var h=0;s=String(s);for(var i=0;i<s.length;i++)h=(h*31+s.charCodeAt(i))|0;return Math.abs(h)}
function fmtDate(t){try{return new Date(t).toLocaleString([], {dateStyle:'medium',timeStyle:'short'})}catch(e){return ''}}
var IC={
 bag:'<svg class="i" viewBox="0 0 24 24"><path d="M5 8h14l-1 12H6L5 8z"/><path d="M9 8V6a3 3 0 0 1 6 0v2"/></svg>',
 search:'<svg class="i" viewBox="0 0 24 24"><circle cx="11" cy="11" r="6.5"/><path d="M20 20l-4.2-4.2"/></svg>',
 menu:'<svg class="i" viewBox="0 0 24 24"><path d="M4 7h16M4 12h16M4 17h16"/></svg>',
 close:'<svg class="i" viewBox="0 0 24 24"><path d="M6 6l12 12M18 6L6 18"/></svg>',
 plus:'<svg class="i" viewBox="0 0 24 24"><path d="M12 5v14M5 12h14"/></svg>',
 truck:'<svg class="i" viewBox="0 0 24 24"><path d="M3 6h11v10H3zM14 10h4l3 3v3h-7"/><circle cx="7" cy="17.5" r="1.8"/><circle cx="17" cy="17.5" r="1.8"/></svg>',
 cash:'<svg class="i" viewBox="0 0 24 24"><rect x="3" y="7" width="18" height="10" rx="1"/><circle cx="12" cy="12" r="2.5"/></svg>',
 box:'<svg class="i" viewBox="0 0 24 24"><path d="M4 8l8-4 8 4v8l-8 4-8-4V8z"/><path d="M4 8l8 4 8-4M12 12v8"/></svg>',
 bell:'<svg class="i" viewBox="0 0 24 24"><path d="M6 16v-5a6 6 0 0 1 12 0v5l1.5 2h-15L6 16z"/><path d="M10 20.5a2 2 0 0 0 4 0"/></svg>'
};

/* ---------- state ---------- */
var S={
 db:null,uid:null,isAdmin:false,slow:false,dbAuthors:{},follows:ls.get('mg.follows',{authors:{},readAt:0}),followDocs:[],notifOpen:false,notifList:[],
 dbProducts:[],dbSettings:{},loaded:{products:false,settings:false,orders:false,messages:false},
 orders:[],messages:[],
 settings:Object.assign({},DEFAULTS),useDb:false,
 cart:ls.get('mg.cart',{}),
 filter:{q:'',cat:'All',sort:'featured'},
 route:{name:'shop'},menu:false,dq:1,
 lastOrder:null,contactSent:null,busy:false,
 admin:{tab:'overview',confirm:'',q:''},
 modal:null,toast:''
};
var toastTimer=0,slowTimer=0;

function recompute(){
 S.settings=Object.assign({},DEFAULTS,S.dbSettings);
 S.useDb=!!(S.db&&S.loaded.products&&(S.dbProducts.length>0||S.settings.catalog==='custom'));
}
function products(){return S.useDb?S.dbProducts:SAMPLE}
function findP(id){var a=products();for(var i=0;i<a.length;i++)if(a[i].id===id)return a[i];return null}
function money(n){return S.settings.currency+(Math.round((Number(n)||0)*100)/100).toFixed(2)}
function categories(){var m={};products().forEach(function(p){if(p.category)m[p.category]=1});return Object.keys(m).sort()}

/* ---------- authors, follows, notifications ---------- */
function authorId(name){return 'a'+hashStr(String(name||'').trim().toLowerCase()).toString(36)}
function authorName(id){var a=products();for(var i=0;i<a.length;i++)if(a[i].author&&authorId(a[i].author)===id)return a[i].author;return ''}
function authorPhoto(name){var d=S.dbAuthors[authorId(name)];return d&&d.photo?d.photo:''}
function avatar(name,cls,photo){
 var ph=photo!==undefined?photo:authorPhoto(name);
 return ph?'<img class="av '+(cls||'')+'" src="'+esc(ph)+'" alt="">':'<span class="av '+(cls||'')+'" aria-hidden="true">'+esc(String(name||'?').trim().charAt(0).toUpperCase())+'</span>';
}
function isFollowing(name){return !!S.follows.authors[authorId(name)]}
async function saveFollows(){
 if(S.db&&S.uid){try{await S.db.doc('follows/'+S.uid).set(S.follows);return}catch(e){}}
 ls.set('mg.follows',S.follows);
}
function toggleFollow(name){
 var id=authorId(name),f=S.follows;
 if(f.authors[id]){delete f.authors[id];toast('You unfollowed '+name)}
 else{f.authors[id]=Date.now();toast('Following '+name+'. You will be notified about their new books.')}
 saveFollows();
}
function notifs(){
 var f=S.follows;
 return products().filter(function(p){var t=f.authors[authorId(p.author)];return t&&(p.createdAt||0)>t&&(p.createdAt||0)>(f.readAt||0)}).sort(function(a,b){return (b.createdAt||0)-(a.createdAt||0)});
}
function notifHtml(){
 if(!S.notifOpen)return '';
 var items=S.notifList,names=Object.keys(S.follows.authors).map(authorName).filter(Boolean);
 return '<div class="notif" role="dialog" aria-label="Notifications"><h3>New from authors you follow</h3>'
  +(items.length?items.map(function(p){return '<a class="notif-item" href="#book-'+esc(p.id)+'"><div>'+cover(p)+'</div><div><b>'+esc(p.title)+'</b><span>New book by '+esc(p.author)+' &middot; '+fmtDate(p.createdAt)+'</span></div></a>'}).join(''):'<p class="hint">'+(names.length?'No new books yet. We will let you know when one arrives.':'Follow an author from a book page to hear about their new books.')+'</p>')
  +(names.length?'<div class="foll"><span>Following:</span>'+names.map(function(n){return '<button class="link-btn" data-act="unfollow" data-name="'+esc(n)+'">'+esc(n)+' &times;</button>'}).join('')+'</div>':'')+'</div>';
}
function authorLine(name){
 if(!name)return '';
 var on=isFollowing(name);
 return '<div class="author-line">'+avatar(name,'sm')+'<a href="#author-'+authorId(name)+'">'+esc(name)+'</a><button class="btn btn-o btn-sm btn-follow" data-act="follow" data-name="'+esc(name)+'" aria-pressed="'+on+'">'+(on?'Following':'+ Follow')+'</button></div>';
}
function metaHtml(p){
 function m(l,v,c){return v?'<div><dt>'+l+'</dt><dd'+(c?' class="'+c+'"':'')+'>'+esc(v)+'</dd></div>':''}
 return '<dl class="meta">'+m('Publication',p.publisher)+m('Language',p.language)+m('Country',p.country)+m('Edition',p.edition)+m('Format',p.format||'Paperback')+m('Pages',p.pages,'num')+m('Weight',p.weight?p.weight+' g':'','num')+m('Category',p.category)+m('ISBN',p.isbn,'mono')+'</dl>';
}
function viewAuthor(){
 var name=authorName(S.route.id);
 if(!name)return '<div class="in page"><div class="empty"><h3>We could not find that author</h3><a class="btn btn-p" href="#shop">Back to the shop</a></div></div>';
 var list=products().filter(function(p){return p.author&&authorId(p.author)===S.route.id}),on=isFollowing(name);
 return '<div class="in"><p class="crumbs"><a href="#shop">Shop</a> / Authors</p><div class="author-hero">'+avatar(name,'lg')+'<div><span class="eyebrow">Author</span><h1 class="page-h">'+esc(name)+'</h1><p class="by">'+list.length+' title'+(list.length===1?'':'s')+' in the shop</p>'
  +'<div style="margin-top:12px"><button class="btn btn-p btn-follow" data-act="follow" data-name="'+esc(name)+'" aria-pressed="'+on+'">'+(on?'Following':'Follow author')+'</button></div><p class="hint" style="margin-top:8px">Followers are notified when a new book by this author is added.</p></div></div>'
  +'<section class="sec"><div class="grid">'+list.map(card).join('')+'</div></section></div>';
}
function adminAuthors(){
 var by={};
 products().forEach(function(p){if(!p.author)return;var k=authorId(p.author);(by[k]=by[k]||{name:p.author,n:0}).n++});
 var fol={};
 S.followDocs.forEach(function(d){Object.keys(d.authors||{}).forEach(function(k){fol[k]=(fol[k]||0)+1})});
 var ids=Object.keys(by).sort(function(a,b){return (fol[b]||0)-(fol[a]||0)||by[a].name.localeCompare(by[b].name)});
 if(!ids.length)return '<div class="empty"><h3>No authors yet</h3><p class="by">Authors appear here once you add books.</p></div>';
 return '<div class="panel" style="padding:6px 18px"><div class="rows">'+ids.map(function(k){var a=by[k],f=fol[k]||0;
  return '<div class="row" style="grid-template-columns:44px minmax(0,1fr) auto;grid-template-areas:\'t i m\'"><div class="t">'+avatar(a.name,'sm')+'</div><div class="i"><b>'+esc(a.name)+'</b><span>'+a.n+' book'+(a.n===1?'':'s')+'</span></div><div class="m"><b>'+f+'</b><span>follower'+(f===1?'':'s')+'</span></div></div>'}).join('')+'</div></div>'
  +'<p class="hint" style="margin-top:12px">Set an author photo from the Add book or Edit book form. Followers are counted from signed-in customers.</p>';
}

/* ---------- cart ---------- */
function saveCart(){ls.set('mg.cart',S.cart)}
function cartItems(){var out=[];Object.keys(S.cart).forEach(function(id){var p=findP(id);if(p&&S.cart[id]>0)out.push({p:p,qty:Math.min(S.cart[id],Math.max(p.stock,0))||0})});return out.filter(function(x){return x.qty>0})}
function cartCount(){return cartItems().reduce(function(a,x){return a+x.qty},0)}
function totals(){
 var sub=cartItems().reduce(function(a,x){return a+x.p.price*x.qty},0);
 var ship=sub===0?0:(sub>=Number(S.settings.freeOver)?0:Number(S.settings.shipping)||0);
 return {sub:sub,ship:ship,total:sub+ship};
}
function addToCart(id,q){
 var p=findP(id);if(!p)return;
 if(p.stock<=0){toast('Sorry, that title is sold out');return}
 var cur=S.cart[id]||0,nq=Math.min(cur+q,p.stock);
 if(nq===cur){toast('Only '+p.stock+' in stock');return}
 S.cart[id]=nq;saveCart();toast('Added to your cart');
}
function setQty(id,d){
 var p=findP(id);if(!p)return;
 var nq=(S.cart[id]||0)+d;
 if(nq<=0){delete S.cart[id]}else if(nq>p.stock){toast('Only '+p.stock+' in stock');return}else{S.cart[id]=nq}
 saveCart();render();
}

/* ---------- cover ---------- */
function cover(p){
 if(p.image)return '<div class="cover cover-img"><img src="'+esc(p.image)+'" alt="Cover of '+esc(p.title)+'" loading="lazy"></div>';
 var v=hashStr(p.id||p.title)%4;
 return '<div class="cover pat'+v+'" style="--h:'+(Number(p.hue)||160)+'" role="img" aria-label="Cover of '+esc(p.title)+' by '+esc(p.author)+'"><span class="art"></span><div class="cv"><span class="c-author">'+esc(p.author)+'</span><span class="c-title">'+esc(p.title)+'</span><span class="c-mark"></span></div></div>';
}
function priceHtml(p){return '<span class="price">'+money(p.price)+(p.oldPrice>p.price?'<s>'+money(p.oldPrice)+'</s>':'')+'</span>'}
function stockHtml(p){
 if(p.stock<=0)return '<span class="stock none">Sold out</span>';
 if(p.stock<=5)return '<span class="stock low">Only '+p.stock+' left</span>';
 return '<span class="stock ok">In stock</span>';
}

/* ---------- routing ---------- */
function parseRoute(){
 var h=location.hash.replace(/^#/,'');
 if(h.indexOf('book-')===0)return {name:'book',id:h.slice(5)};
 if(h.indexOf('author-')===0)return {name:'author',id:h.slice(7)};
 if(['cart','checkout','contact','admin'].indexOf(h)>-1)return {name:h};
 return {name:'shop'};
}
window.addEventListener('hashchange',function(){
 S.route=parseRoute();S.menu=false;S.notifOpen=false;S.dq=1;
 if(S.route.name!=='checkout')S.lastOrder=null;
 if(S.route.name!=='contact')S.contactSent=null;
 render();window.scrollTo(0,0);
});

/* ---------- views ---------- */
function header(){
 var r=S.route.name,n=cartCount(),nn=notifs().length;
 function a(h,t,k){return '<a href="#'+h+'"'+(r===k?' aria-current="page"':'')+'>'+t+'</a>'}
 return '<header class="hdr"><div class="in hdr-in">'
  +'<a class="brand" href="#shop">'+esc(S.settings.name)+'<i></i></a>'
  +'<nav class="nav'+(S.menu?' open':'')+'" aria-label="Main">'+a('shop','Shop','shop')+a('contact','Contact','contact')+(S.isAdmin?a('admin','Admin','admin'):'')+'</nav>'
  +'<button class="icon-btn" data-act="notif" aria-label="Notifications, '+nn+' new" aria-expanded="'+S.notifOpen+'">'+IC.bell+(nn?'<span class="badge-n">'+nn+'</span>':'')+'</button>'
  +'<a class="icon-btn" href="#cart" aria-label="Cart, '+n+' items">'+IC.bag+(n?'<span class="badge-n">'+n+'</span>':'')+'</a>'
  +'<button class="icon-btn menu-btn" data-act="menu" aria-label="Menu" aria-expanded="'+S.menu+'">'+(S.menu?IC.close:IC.menu)+'</button>'
  +notifHtml()+'</div></header>';
}
function footer(){
 return '<footer class="ftr"><div class="in ftr-in"><a class="brand" href="#shop">'+esc(S.settings.name)+'<i></i></a>'
  +'<nav aria-label="Footer"><a href="#shop">Shop</a><a href="#cart">Cart</a><a href="#contact">Contact</a><a href="#admin">Store admin</a></nav>'
  +'<p class="copy">&copy; '+new Date().getFullYear()+' '+esc(S.settings.name)+'. Prices in '+esc(S.settings.currency)+'.</p></div></footer>';
}

function card(p){
 var tag=p.stock<=0?'<span class="tag out">Sold out</span>':(p.oldPrice>p.price?'<span class="tag">Sale</span>':'');
 return '<article class="card"><a class="card-cover" href="#book-'+esc(p.id)+'" aria-label="'+esc(p.title)+'">'+tag+cover(p)+'</a>'
  +'<div class="card-body"><span class="cat">'+esc(p.category)+'</span><h3><a href="#book-'+esc(p.id)+'">'+esc(p.title)+'</a></h3><p class="by">'+esc(p.author)+'</p>'
  +'<div class="card-foot">'+priceHtml(p)+'<button class="add" data-act="add" data-id="'+esc(p.id)+'" aria-label="Add '+esc(p.title)+' to cart"'+(p.stock<=0?' disabled':'')+'>'+IC.plus+'</button></div></div></article>';
}
function filtered(){
 var q=S.filter.q.trim().toLowerCase(),c=S.filter.cat;
 var a=products().filter(function(p){return (c==='All'||p.category===c)&&(!q||(p.title+' '+p.author+' '+p.category).toLowerCase().indexOf(q)>-1)});
 var s=S.filter.sort;
 if(s==='low')a.sort(function(x,y){return x.price-y.price});
 else if(s==='high')a.sort(function(x,y){return y.price-x.price});
 else if(s==='az')a.sort(function(x,y){return x.title.localeCompare(y.title)});
 else a.sort(function(x,y){return (y.featured?1:0)-(x.featured?1:0)||(y.createdAt||0)-(x.createdAt||0)});
 return a;
}
function viewShop(){
 var all=products(),feat=all.filter(function(p){return p.featured}).concat(all.filter(function(p){return !p.featured})).slice(0,3);
 var list=filtered();
 var fan=feat.length?'<div class="fan" aria-hidden="false">'+feat.map(function(p){return '<a href="#book-'+esc(p.id)+'" tabindex="-1" aria-label="'+esc(p.title)+'">'+cover(p)+'</a>'}).join('')+'</div>':'';
 var cats=['All'].concat(categories());
 var free=Number(S.settings.freeOver);
 return '<section class="hero"><div class="in hero-in"><div><span class="eyebrow">Independent bookshop</span>'
  +'<h1>Books worth keeping.</h1><p class="lead">Well-made editions of the novels, poems and ideas that last, packed carefully and sent to your door.</p>'
  +'<div class="hero-cta"><a class="btn btn-brass" href="#catalogue" data-act="scroll" data-to="catalogue">Browse the collection</a><a class="btn btn-o" href="#contact">Ask us anything</a></div></div>'+fan+'</div></section>'
  +'<section class="perks"><div class="in perks-in">'
  +'<div class="perk">'+IC.truck+'<span><b>'+(free>0?'Free delivery over '+money(free):'Free delivery')+'</b> on every order</span></div>'
  +'<div class="perk">'+IC.cash+'<span><b>Pay on delivery</b> or by bank transfer</span></div>'
  +'<div class="perk">'+IC.box+'<span><b>Packed with care</b> in protective wrap</span></div></div></section>'
  +'<section class="sec" id="catalogue"><div class="in"><div class="sec-h"><h2>The collection</h2><span class="hint num">'+list.length+' of '+all.length+' titles</span></div>'
  +'<div class="toolbar"><div class="search"><label class="sr" for="q">Search books</label>'+IC.search+'<input class="inp" id="q" data-keep type="search" placeholder="Search by title, author or category" value="'+esc(S.filter.q)+'" autocomplete="off"></div>'
  +'<div><label class="sr" for="sort">Sort</label><select class="inp" id="sort" data-keep><option value="featured"'+(S.filter.sort==='featured'?' selected':'')+'>Featured first</option><option value="low"'+(S.filter.sort==='low'?' selected':'')+'>Price, low to high</option><option value="high"'+(S.filter.sort==='high'?' selected':'')+'>Price, high to low</option><option value="az"'+(S.filter.sort==='az'?' selected':'')+'>Title, A to Z</option></select></div></div>'
  +'<div class="chips" role="group" aria-label="Categories">'+cats.map(function(c){return '<button class="chip" data-act="cat" data-cat="'+esc(c)+'" aria-pressed="'+(S.filter.cat===c)+'">'+esc(c)+'</button>'}).join('')+'</div>'
  +(list.length?'<div class="grid">'+list.map(card).join('')+'</div>':'<div class="empty"><h3>'+(all.length?'No books match your search':'The shelves are being stocked')+'</h3><p class="by">'+(all.length?'Try a different word or clear the category filter.':'Check back soon for new arrivals.')+'</p>'+(all.length?'<button class="btn btn-o" data-act="clear">Clear filters</button>':'')+'</div>')
  +'</div></section>';
}

function viewBook(){
 var p=findP(S.route.id);
 if(!p)return '<div class="in page"><div class="empty"><h3>We could not find that book</h3><a class="btn btn-p" href="#shop">Back to the shop</a></div></div>';
 var rel=products().filter(function(x){return x.category===p.category&&x.id!==p.id}).slice(0,4);
 var dq=Math.max(1,Math.min(S.dq,Math.max(p.stock,1)));
 return '<div class="in"><p class="crumbs"><a href="#shop">Shop</a> / '+esc(p.category)+'</p>'
  +'<div class="detail"><div>'+cover(p)+'</div><div>'
  +'<span class="cat">'+esc(p.category)+'</span><h1>'+esc(p.title)+'</h1>'+authorLine(p.author)
  +'<div class="price">'+money(p.price)+(p.oldPrice>p.price?'<s>'+money(p.oldPrice)+'</s>':'')+'</div>'+stockHtml(p)
  +'<p class="desc">'+esc(p.description||'')+'</p>'
  +'<div class="buy"><div class="qty" role="group" aria-label="Quantity"><button data-act="dq" data-d="-1" aria-label="Decrease quantity">&minus;</button><span class="num">'+dq+'</span><button data-act="dq" data-d="1" aria-label="Increase quantity">+</button></div>'
  +'<button class="btn btn-p" data-act="add-detail" data-id="'+esc(p.id)+'"'+(p.stock<=0?' disabled':'')+'>'+IC.bag+' Add to cart</button></div>'
  +metaHtml(p)
  +'</div></div>'
  +(rel.length?'<section class="sec" style="padding-top:8px"><div class="sec-h"><h2>More in '+esc(p.category)+'</h2></div><div class="grid">'+rel.map(card).join('')+'</div></section>':'')
  +'</div>';
}

function viewCart(){
 var items=cartItems(),t=totals();
 if(!items.length)return '<div class="in page"><h1 class="page-h">Your cart</h1><div class="empty" style="margin-top:22px"><h3>Your cart is empty</h3><p class="by">Pick a few books and they will wait for you here.</p><a class="btn btn-p" href="#shop">Browse the collection</a></div></div>';
 var free=Number(S.settings.freeOver);
 return '<div class="in page"><h1 class="page-h">Your cart</h1><div class="two"><div class="panel">'
  +items.map(function(x){var p=x.p;return '<div class="line"><a href="#book-'+esc(p.id)+'" aria-label="'+esc(p.title)+'">'+cover(p)+'</a>'
   +'<div style="min-width:0"><h3><a href="#book-'+esc(p.id)+'">'+esc(p.title)+'</a></h3><p class="by">'+esc(p.author)+'</p><p class="by num">'+money(p.price)+' each</p></div>'
   +'<div class="line-r"><b class="num">'+money(p.price*x.qty)+'</b><div class="qty"><button data-act="qty" data-id="'+esc(p.id)+'" data-d="-1" aria-label="Decrease quantity of '+esc(p.title)+'">&minus;</button><span class="num">'+x.qty+'</span><button data-act="qty" data-id="'+esc(p.id)+'" data-d="1" aria-label="Increase quantity of '+esc(p.title)+'">+</button></div>'
   +'<button class="link-btn" data-act="remove" data-id="'+esc(p.id)+'">Remove</button></div></div>'}).join('')
  +'</div><aside class="panel sticky"><h2>Order summary</h2><div class="sum"><div><span>Subtotal</span><span>'+money(t.sub)+'</span></div><div><span>Delivery</span><span>'+(t.ship?money(t.ship):'Free')+'</span></div>'
  +(t.ship&&free>0?'<p class="hint">Add '+money(free-t.sub)+' more for free delivery.</p>':'')
  +'<div class="tot"><span>Total</span><span>'+money(t.total)+'</span></div></div>'
  +'<a class="btn btn-p btn-block" style="margin-top:18px" href="#checkout">Go to checkout</a><a class="btn btn-o btn-block" style="margin-top:10px" href="#shop">Keep shopping</a></aside></div></div>';
}

function viewCheckout(){
 if(S.lastOrder){
  var o=S.lastOrder;
  return '<div class="in page"><div class="done"><span class="eyebrow">Order received</span><h1>Thank you, '+esc((o.customer.name||'').split(' ')[0])+'.</h1>'
   +'<p>Your order number is <b class="mono">'+esc(o.number)+'</b>. We will contact you on '+esc(o.customer.phone)+' to confirm delivery.</p>'
   +(o.where==='local'?'<p class="note">This is a preview shop, so the order was saved on this device only and the store owner has not received it.</p>':'<p class="note ok-note">The store has your order and will be in touch soon.</p>')
   +'<div class="panel" style="width:100%"><h3>Summary</h3><div class="sum">'+o.items.map(function(i){return '<div><span>'+esc(i.title)+' &times; '+i.qty+'</span><span>'+money(i.price*i.qty)+'</span></div>'}).join('')
   +'<div><span>Delivery</span><span>'+(o.shipping?money(o.shipping):'Free')+'</span></div><div class="tot"><span>Total</span><span>'+money(o.total)+'</span></div></div></div>'
   +'<a class="btn btn-p" href="#shop">Continue shopping</a></div></div>';
 }
 var items=cartItems(),t=totals();
 if(!items.length)return '<div class="in page"><h1 class="page-h">Checkout</h1><div class="empty" style="margin-top:22px"><h3>Nothing to check out yet</h3><a class="btn btn-p" href="#shop">Browse the collection</a></div></div>';
 return '<div class="in page"><h1 class="page-h">Checkout</h1><div class="two">'
  +'<form class="form panel" data-form="checkout" data-keep novalidate><h2>Delivery details</h2>'
  +'<div class="grid2"><div class="field"><label for="c-name">Full name</label><input class="inp" id="c-name" name="name" required autocomplete="name"></div><div class="field"><label for="c-phone">Phone</label><input class="inp" id="c-phone" name="phone" type="tel" required autocomplete="tel"></div></div>'
  +'<div class="field"><label for="c-email">Email</label><input class="inp" id="c-email" name="email" type="email" required autocomplete="email"></div>'
  +'<div class="field"><label for="c-addr">Street address</label><input class="inp" id="c-addr" name="address" required autocomplete="street-address"></div>'
  +'<div class="grid2"><div class="field"><label for="c-city">City</label><input class="inp" id="c-city" name="city" required autocomplete="address-level2"></div><div class="field"><label for="c-note">Delivery note (optional)</label><input class="inp" id="c-note" name="notes"></div></div>'
  +'<h2 style="margin-top:10px">Payment</h2>'
  +'<label class="opt" for="p-cod"><input type="radio" id="p-cod" name="payment" value="Cash on delivery" checked><span><b>Cash on delivery</b><span class="hint">Pay the courier when your books arrive.</span></span></label>'
  +'<label class="opt" for="p-bank"><input type="radio" id="p-bank" name="payment" value="Bank or mobile transfer"><span><b>Bank or mobile transfer</b><span class="hint">We will send transfer details with your confirmation.</span></span></label>'
  +'<p class="hint" id="c-err" role="alert" style="color:var(--danger)"></p>'
  +'<button class="btn btn-p btn-block" type="submit"'+(S.busy?' disabled':'')+'>'+(S.busy?'Placing order…':'Place order &middot; '+money(t.total))+'</button></form>'
  +'<aside class="panel sticky"><h2>Your order</h2>'+items.map(function(x){return '<div class="line" style="grid-template-columns:44px minmax(0,1fr) auto;padding:10px 0"><div>'+cover(x.p)+'</div><div style="min-width:0"><b style="font-size:15px">'+esc(x.p.title)+'</b><p class="by">Qty '+x.qty+'</p></div><b class="num">'+money(x.p.price*x.qty)+'</b></div>'}).join('')
  +'<div class="sum" style="margin-top:14px"><div><span>Subtotal</span><span>'+money(t.sub)+'</span></div><div><span>Delivery</span><span>'+(t.ship?money(t.ship):'Free')+'</span></div><div class="tot"><span>Total</span><span>'+money(t.total)+'</span></div></div></aside></div></div>';
}

function viewContact(){
 var s=S.settings;
 var form=S.contactSent
  ?'<div class="panel done"><h2>Message sent</h2><p>Thank you. We usually reply within one working day.</p>'+(S.contactSent==='local'?'<p class="note">This is a preview shop, so the message was saved on this device only.</p>':'')+'<button class="btn btn-o" data-act="contact-again">Send another message</button></div>'
  :'<form class="form panel" data-form="contact" data-keep novalidate><h2>Send a message</h2><div class="grid2"><div class="field"><label for="m-name">Your name</label><input class="inp" id="m-name" name="name" required autocomplete="name"></div><div class="field"><label for="m-email">Email</label><input class="inp" id="m-email" name="email" type="email" required autocomplete="email"></div></div>'
   +'<div class="field"><label for="m-msg">Message</label><textarea class="inp" id="m-msg" name="message" required placeholder="Looking for a particular edition, or have a question about an order?"></textarea></div><p class="hint" id="m-err" role="alert" style="color:var(--danger)"></p><button class="btn btn-p" type="submit">Send message</button></form>';
 return '<div class="in page"><h1 class="page-h">Contact</h1><div class="contact-grid"><div><p style="font-size:18px;max-width:42ch">Questions about a title, an order or a special request? Write to us or visit the shop.</p>'
  +'<dl class="info-list" style="margin-top:14px"><div><dt>Email</dt><dd>'+esc(s.email)+'</dd></div><div><dt>Phone</dt><dd class="num">'+esc(s.phone)+'</dd></div><div><dt>Address</dt><dd>'+esc(s.address)+'</dd></div><div><dt>Opening hours</dt><dd>'+esc(s.hours)+'</dd></div></dl></div>'+form+'</div></div>';
}

/* ---------- admin ---------- */
function viewAdmin(){
 if(!S.isAdmin)return '<div class="in page"><div class="empty"><span class="eyebrow">Store admin</span><h3>This area is for the store owner</h3><p class="by" style="max-width:52ch">Open this page while signed in to the Claude account that owns it to manage books, orders and messages.</p><a class="btn btn-p" href="#shop">Back to the shop</a></div></div>';
 var tabs=[['overview','Overview'],['products','Products'],['orders','Orders'+(pendingCount()?' ('+pendingCount()+')':'')],['messages','Messages'+(unreadCount()?' ('+unreadCount()+')':'')],['authors','Authors'],['settings','Settings']];
 var body={overview:adminOverview,products:adminProducts,orders:adminOrders,messages:adminMessages,authors:adminAuthors,settings:adminSettings}[S.admin.tab]();
 return '<div class="in page"><span class="eyebrow">Store admin</span><h1 class="page-h">Dashboard</h1>'
  +(S.slow&&!S.loaded.products?'<p class="note" style="margin-top:14px">Still connecting to the store database. Changes will appear once it answers.</p>':'')
  +'<div class="tabs" role="tablist">'+tabs.map(function(t){return '<button class="tab" role="tab" data-act="atab" data-tab="'+t[0]+'" aria-selected="'+(S.admin.tab===t[0])+'">'+t[1]+'</button>'}).join('')+'</div>'+body+'</div>';
}
function pendingCount(){return S.orders.filter(function(o){return o.status==='pending'}).length}
function unreadCount(){return S.messages.filter(function(m){return !m.read}).length}
function sampleBanner(){
 if(S.useDb)return '';
 return '<div class="banner"><p><b>You are looking at sample books.</b> Import them to start editing your own catalogue, or start with an empty shelf and add your titles one by one.</p><div style="display:flex;gap:10px;flex-wrap:wrap"><button class="btn btn-p btn-sm" data-act="import" '+(S.busy||!S.db?'disabled':'')+'>Import sample books</button><button class="btn btn-o btn-sm" data-act="start-empty" '+(S.busy||!S.db?'disabled':'')+'>Start empty</button></div></div>';
}
function adminOverview(){
 var ps=products(),rev=S.orders.filter(function(o){return o.status!=='cancelled'}).reduce(function(a,o){return a+(o.total||0)},0);
 var low=ps.filter(function(p){return p.stock<=3}).sort(function(a,b){return a.stock-b.stock}).slice(0,6);
 var recent=S.orders.slice(0,5);
 return sampleBanner()+'<div class="stats"><div class="stat"><span class="eyebrow">Books</span><b>'+ps.length+'</b></div><div class="stat"><span class="eyebrow">Orders</span><b>'+S.orders.length+'</b></div><div class="stat"><span class="eyebrow">Revenue</span><b>'+money(rev)+'</b></div><div class="stat"><span class="eyebrow">Unread messages</span><b>'+unreadCount()+'</b></div></div>'
  +'<div class="cols"><div class="panel"><h3>Recent orders</h3>'+(recent.length?'<div class="rows">'+recent.map(function(o){return '<div class="row" style="grid-template-columns:minmax(0,1fr) auto auto;grid-template-areas:\'i m a\'"><div class="i"><b class="mono">'+esc(o.number)+'</b><span>'+esc(o.customer&&o.customer.name)+' &middot; '+fmtDate(o.createdAt)+'</span></div><div class="m"><b>'+money(o.total)+'</b></div><div class="a"><span class="pill s-'+esc(o.status)+'">'+esc(o.status)+'</span></div></div>'}).join('')+'</div>':'<p class="hint">Orders will appear here as customers check out.</p>')+'</div>'
  +'<div class="panel"><h3>Low stock</h3>'+(low.length?'<div class="rows">'+low.map(function(p){return '<div class="row" style="grid-template-columns:44px minmax(0,1fr) auto;grid-template-areas:\'t i m\'"><div class="t">'+cover(p)+'</div><div class="i"><b>'+esc(p.title)+'</b><span>'+esc(p.author)+'</span></div><div class="m"><span class="pill '+(p.stock<=0?'s-out':'s-low')+'">'+(p.stock<=0?'Sold out':p.stock+' left')+'</span></div></div>'}).join('')+'</div>':'<p class="hint">Every title has healthy stock.</p>')+'</div></div>';
}
function adminProducts(){
 var q=S.admin.q.trim().toLowerCase();
 var ps=products().filter(function(p){return !q||(p.title+' '+p.author+' '+p.category).toLowerCase().indexOf(q)>-1});
 var ro=!S.useDb;
 return sampleBanner()+'<div class="toolbar"><div class="search"><label class="sr" for="aq">Search products</label>'+IC.search+'<input class="inp" id="aq" data-keep type="search" placeholder="Search products" value="'+esc(S.admin.q)+'" autocomplete="off"></div><button class="btn btn-p" data-act="p-new" '+(S.useDb?'':'disabled')+'>'+IC.plus+' Add book</button></div>'
  +'<div class="panel" style="padding:6px 18px">'+(ps.length?'<div class="rows">'+ps.map(function(p){
   var st=p.stock<=0?'<span class="pill s-out">Sold out</span>':(p.stock<=3?'<span class="pill s-low">'+p.stock+' left</span>':'<span class="pill s-ok">'+p.stock+' in stock</span>');
   var acts=ro?'':(S.admin.confirm===p.id?'<span class="confirm">Delete this book?<button class="btn btn-d btn-sm" data-act="p-del-yes" data-id="'+esc(p.id)+'">Delete</button><button class="btn btn-o btn-sm" data-act="p-del-no">Keep</button></span>':'<button class="btn btn-o btn-sm" data-act="p-edit" data-id="'+esc(p.id)+'">Edit</button><button class="btn btn-d btn-sm" data-act="p-del" data-id="'+esc(p.id)+'">Delete</button>');
   return '<div class="row"><div class="t">'+cover(p)+'</div><div class="i"><b>'+esc(p.title)+'</b><span>'+esc(p.author)+' &middot; '+esc(p.category)+'</span></div><div class="m"><b>'+money(p.price)+'</b>'+st+'</div><div class="a">'+acts+'</div></div>'}).join('')+'</div>':'<div style="padding:24px 0"><p class="hint">'+(products().length?'No products match that search.':'No books yet. Add your first title.')+'</p></div>')+'</div>';
}
function adminOrders(){
 if(!S.loaded.orders)return '<div class="panel"><p class="hint">Loading orders…</p></div>';
 if(!S.orders.length)return '<div class="empty"><h3>No orders yet</h3><p class="by">New orders from the checkout page will show up here live.</p></div>';
 return '<div class="panel" style="padding:6px 20px">'+S.orders.map(function(o){
  var c=o.customer||{};
  return '<div class="order"><div class="order-top"><div><b class="mono">'+esc(o.number)+'</b> <span class="hint">&middot; '+fmtDate(o.createdAt)+'</span></div><div style="display:flex;gap:10px;align-items:center"><b class="num">'+money(o.total)+'</b><span class="pill s-'+esc(o.status)+'">'+esc(o.status)+'</span></div></div>'
   +'<p style="margin-top:6px">'+esc(c.name)+' &middot; <span class="num">'+esc(c.phone)+'</span> &middot; '+esc(c.email)+'</p><p class="hint">'+esc(c.address)+', '+esc(c.city)+(c.notes?' &middot; Note: '+esc(c.notes):'')+'</p>'
   +'<details><summary>'+(o.items||[]).length+' item'+((o.items||[]).length===1?'':'s')+' &middot; '+esc(o.payment)+'</summary><table><tbody>'+(o.items||[]).map(function(i){return '<tr><td>'+esc(i.title)+' &times; '+i.qty+'</td><td>'+money(i.price*i.qty)+'</td></tr>'}).join('')+'<tr><td>Delivery</td><td>'+(o.shipping?money(o.shipping):'Free')+'</td></tr></tbody></table></details>'
   +'<div class="order-acts"><label class="sr" for="st-'+esc(o.id)+'">Status</label><select class="inp" id="st-'+esc(o.id)+'" data-change="order-status" data-id="'+esc(o.id)+'">'+STATUSES.map(function(s){return '<option value="'+s+'"'+(o.status===s?' selected':'')+'>'+s.charAt(0).toUpperCase()+s.slice(1)+'</option>'}).join('')+'</select>'
   +(S.admin.confirm==='o'+o.id?'<span class="confirm">Delete this order?<button class="btn btn-d btn-sm" data-act="o-del-yes" data-id="'+esc(o.id)+'">Delete</button><button class="btn btn-o btn-sm" data-act="p-del-no">Keep</button></span>':'<button class="btn btn-d btn-sm" data-act="o-del" data-id="'+esc(o.id)+'">Delete</button>')+'</div></div>'}).join('')+'</div>';
}
function adminMessages(){
 if(!S.loaded.messages)return '<div class="panel"><p class="hint">Loading messages…</p></div>';
 if(!S.messages.length)return '<div class="empty"><h3>No messages yet</h3><p class="by">Messages sent from the contact page will appear here.</p></div>';
 return '<div class="panel" style="padding:6px 20px">'+S.messages.map(function(m){
  return '<div class="msg'+(m.read?'':' unread')+'"><div style="display:flex;flex-wrap:wrap;justify-content:space-between;gap:6px"><b class="nm">'+esc(m.name)+'</b><span class="hint">'+fmtDate(m.createdAt)+'</span></div><span class="hint">'+esc(m.email)+'</span><p>'+esc(m.message)+'</p>'
   +'<div class="order-acts" style="margin-top:4px"><button class="btn btn-o btn-sm" data-act="m-read" data-id="'+esc(m.id)+'">'+(m.read?'Mark as unread':'Mark as read')+'</button>'
   +(S.admin.confirm==='m'+m.id?'<span class="confirm">Delete this message?<button class="btn btn-d btn-sm" data-act="m-del-yes" data-id="'+esc(m.id)+'">Delete</button><button class="btn btn-o btn-sm" data-act="p-del-no">Keep</button></span>':'<button class="btn btn-d btn-sm" data-act="m-del" data-id="'+esc(m.id)+'">Delete</button>')+'</div></div>'}).join('')+'</div>';
}
function adminSettings(){
 var s=S.settings;
 function f(id,label,val,extra){return '<div class="field"><label for="s-'+id+'">'+label+'</label><input class="inp" id="s-'+id+'" name="'+id+'" value="'+esc(val)+'" '+(extra||'')+'></div>'}
 return '<form class="form panel" data-form="settings" data-keep style="max-width:720px"><h3>Store details</h3>'
  +'<div class="grid2">'+f('name','Store name',s.name,'required')+f('currency','Currency symbol',s.currency,'required maxlength="4"')+'</div>'
  +'<div class="grid2">'+f('shipping','Delivery fee',s.shipping,'type="number" min="0" step="0.01" inputmode="decimal"')+f('freeOver','Free delivery over (0 for always free)',s.freeOver,'type="number" min="0" step="0.01" inputmode="decimal"')+'</div>'
  +'<h3 style="margin-top:8px">Contact page</h3><div class="grid2">'+f('email','Email',s.email)+f('phone','Phone',s.phone)+'</div>'+f('address','Address',s.address)+f('hours','Opening hours',s.hours)
  +'<div><button class="btn btn-p" type="submit" '+(S.db?'':'disabled')+'>Save settings</button></div></form>';
}
function modal(){
 var m=S.modal;if(!m)return '';
 var p=m.p||{},isNew=!m.p;
 var cats=categories().map(function(c){return '<option value="'+esc(c)+'">'}).join('');
 var prev={id:p.id||'preview',title:m.title||'Untitled',author:m.author||'Author',hue:m.hue,image:m.image};
 var ab='<div class="ab"><label class="lbl" for="f-aimg">Author photo (optional)</label>'+avatar(m.author||'Author','lg',m.authorImage||'')
  +'<input class="inp" id="f-aimg" type="file" accept="image/*" data-change="aimg" style="padding:8px">'
  +(m.authorImage?'<button type="button" class="link-btn" data-act="aimg-remove">Remove author photo</button>':'')+'</div>';
 return '<div class="overlay" data-act="overlay"><div class="modal" role="dialog" aria-modal="true" aria-labelledby="mt"><form data-form="product" data-keep novalidate>'
  +'<div class="modal-h"><h2 id="mt">'+(isNew?'Add a book':'Edit book')+'</h2><button type="button" class="icon-btn" data-act="modal-close" aria-label="Close">'+IC.close+'</button></div>'
  +'<div class="modal-b"><div class="pf"><div class="pf-side"><div id="cv-prev">'+cover(prev)+'</div><div style="display:grid;gap:8px;min-width:0">'
  +'<div class="field"><label for="f-hue">Cover colour</label><input class="inp" id="f-hue" name="hue" type="range" min="0" max="360" value="'+m.hue+'"><div class="hue-bar"></div></div>'
  +'<div class="field"><label for="f-img">Cover photo (optional)</label><input class="inp" id="f-img" type="file" accept="image/*" data-change="img" style="padding:8px"></div>'
  +(m.image?'<button type="button" class="link-btn" data-act="img-remove">Remove photo</button>':'')+ab+'</div></div>'
  +'<div class="pf-main"><div class="field"><label for="f-title">Title</label><input class="inp" id="f-title" name="title" required value="'+esc(m.title)+'"></div>'
  +'<div class="grid2"><div class="field"><label for="f-author">Author</label><input class="inp" id="f-author" name="author" value="'+esc(m.author)+'"></div><div class="field"><label for="f-cat">Category</label><input class="inp" id="f-cat" name="category" list="cat-list" value="'+esc(m.category)+'"><datalist id="cat-list">'+cats+'</datalist></div></div>'
  +'<div class="grid3"><div class="field"><label for="f-price">Price</label><input class="inp" id="f-price" name="price" type="number" min="0" step="0.01" inputmode="decimal" required value="'+esc(m.price)+'"></div><div class="field"><label for="f-old">Compare-at price</label><input class="inp" id="f-old" name="oldPrice" type="number" min="0" step="0.01" inputmode="decimal" value="'+esc(m.oldPrice)+'"></div><div class="field"><label for="f-stock">Stock</label><input class="inp" id="f-stock" name="stock" type="number" min="0" step="1" inputmode="numeric" value="'+esc(m.stock)+'"></div></div>'
  +'<div class="grid3"><div class="field"><label for="f-format">Format</label><select class="inp" id="f-format" name="format">'+['Paperback','Hardcover','Ebook','Audiobook'].map(function(x){return '<option'+(m.format===x?' selected':'')+'>'+x+'</option>'}).join('')+'</select></div><div class="field"><label for="f-pages">Pages</label><input class="inp" id="f-pages" name="pages" type="number" min="0" step="1" inputmode="numeric" value="'+esc(m.pages)+'"></div><div class="field"><label for="f-isbn">ISBN</label><input class="inp mono" id="f-isbn" name="isbn" value="'+esc(m.isbn)+'"></div></div>'
  +'<div class="grid3"><div class="field"><label for="f-pub">Publication</label><input class="inp" id="f-pub" name="publisher" value="'+esc(m.publisher)+'"></div><div class="field"><label for="f-lang">Language</label><input class="inp" id="f-lang" name="language" list="lang-list" value="'+esc(m.language)+'"><datalist id="lang-list"><option value="Bengali"><option value="English"><option value="Hindi"><option value="Urdu"><option value="Arabic"></datalist></div><div class="field"><label for="f-country">Country</label><input class="inp" id="f-country" name="country" value="'+esc(m.country)+'"></div></div>'
  +'<div class="grid2"><div class="field"><label for="f-edition">Edition</label><input class="inp" id="f-edition" name="edition" placeholder="e.g. 3rd edition, 2024" value="'+esc(m.edition)+'"></div><div class="field"><label for="f-weight">Weight (grams)</label><input class="inp" id="f-weight" name="weight" type="number" min="0" step="1" inputmode="numeric" value="'+esc(m.weight)+'"></div></div>'
  +'<div class="field"><label for="f-desc">Description</label><textarea class="inp" id="f-desc" name="description">'+esc(m.description)+'</textarea></div>'
  +'<label class="check" for="f-feat"><input type="checkbox" id="f-feat" name="featured"'+(m.featured?' checked':'')+'> Feature on the home page</label>'
  +'<p class="hint" id="f-err" role="alert" style="color:var(--danger)"></p></div></div></div>'
  +'<div class="modal-f"><button type="button" class="btn btn-o" data-act="modal-close">Cancel</button><button type="submit" class="btn btn-p"'+(S.busy?' disabled':'')+'>'+(isNew?'Add to shop':'Save changes')+'</button></div></form></div></div>';
}
function toastHtml(){return S.toast?'<div class="toast" role="status" aria-live="polite">'+esc(S.toast)+'</div>':''}

/* ---------- render ---------- */
function saveInputs(){
 var out={},ae=document.activeElement;
 app.querySelectorAll('[data-keep] input,[data-keep] textarea,[data-keep] select').forEach(function(el){
  if(!el.id||el.type==='file')return;
  out[el.id]={v:el.value,c:el.checked,t:el.type};
 });
 var focus=null;
 if(ae&&ae.id&&app.contains(ae)){focus={id:ae.id,s:null,e:null};try{focus.s=ae.selectionStart;focus.e=ae.selectionEnd}catch(e){}}
 return {vals:out,focus:focus,y:window.scrollY};
}
function restoreInputs(sv){
 Object.keys(sv.vals).forEach(function(id){
  var el=document.getElementById(id),d=sv.vals[id];if(!el)return;
  if(d.t==='checkbox'||d.t==='radio')el.checked=d.c;else el.value=d.v;
 });
 if(sv.focus){var f=document.getElementById(sv.focus.id);if(f){f.focus({preventScroll:true});try{if(sv.focus.s!=null)f.setSelectionRange(sv.focus.s,sv.focus.e)}catch(e){}}}
}
function render(){
 recompute();
 var sv=saveInputs();
 var views={shop:viewShop,book:viewBook,author:viewAuthor,cart:viewCart,checkout:viewCheckout,contact:viewContact,admin:viewAdmin};
 app.innerHTML=header()+'<main id="main">'+views[S.route.name]()+'</main>'+footer()+modal()+toastHtml();
 restoreInputs(sv);
 window.scrollTo(0,sv.y);
}
function toast(msg){S.toast=msg;clearTimeout(toastTimer);render();toastTimer=setTimeout(function(){S.toast='';render()},2400)}

/* ---------- data writes ---------- */
/* Orders and messages are kept one document per customer (coll/<customerId>) holding a list,
   so customers can write their own and only the owner can read everyone's. */
async function saveRecord(coll,rec){
 rec.id='r'+Date.now().toString(36)+Math.random().toString(36).slice(2,6);
 if(S.db&&S.uid){
  try{
   var ref=S.db.doc(coll+'/'+S.uid),snap=await ref.get();
   var list=(snap.exists&&snap.data().list)||[];
   list.push(rec);
   await ref.set({list:list.slice(-100)});
   return 'shared';
  }catch(e){}
 }
 var arr=ls.get('mg.'+coll,[]);arr.unshift(rec);ls.set('mg.'+coll,arr.slice(0,30));
 return 'local';
}
async function mutateRecords(coll,owner,fn){
 var ref=S.db.doc(coll+'/'+owner),snap=await ref.get();
 var list=(snap.exists&&snap.data().list)||[];
 await ref.set({list:fn(list)});
}
function flatten(snap){
 var out=[];
 snap.docs.forEach(function(d){((d.data().list)||[]).forEach(function(r){out.push(Object.assign({},r,{owner:d.id}))})});
 out.sort(function(a,b){return (b.createdAt||0)-(a.createdAt||0)});
 return out;
}
function recOwner(arr,id){var r=arr.filter(function(x){return x.id===id})[0];return r?r.owner:null}
async function ensureCustom(){
 if(S.settings.catalog==='custom'||!S.db)return;
 S.dbSettings=Object.assign({},S.dbSettings,{catalog:'custom'});
 await S.db.doc('settings/store').set(S.dbSettings);
}
function docBody(p){var d=Object.assign({},p);delete d.id;return d}
function fileToDataUrl(file,max){
 return new Promise(function(res,rej){
  var fr=new FileReader();
  fr.onerror=rej;
  fr.onload=function(){
   var img=new Image();
   img.onerror=rej;
   img.onload=function(){
    var sc=Math.min(1,(max||640)/Math.max(img.width,img.height)),c=document.createElement('canvas');
    c.width=Math.round(img.width*sc);c.height=Math.round(img.height*sc);
    c.getContext('2d').drawImage(img,0,0,c.width,c.height);
    res(c.toDataURL('image/jpeg',0.82));
   };
   img.src=fr.result;
  };
  fr.readAsDataURL(file);
 });
}
function openModal(p){
 S.modal={p:p||null,title:p?p.title:'',author:p?p.author:'',category:p?p.category:'',price:p?p.price:'',oldPrice:p&&p.oldPrice?p.oldPrice:'',stock:p?p.stock:10,format:p?p.format:'Paperback',pages:p&&p.pages?p.pages:'',isbn:p?p.isbn:'',description:p?p.description:'',hue:p?(Number(p.hue)||160):Math.floor(Math.random()*360),featured:p?!!p.featured:false,image:p?p.image||'':'',publisher:p?p.publisher||'':'',language:p?p.language||'':'',country:p?p.country||'':'',edition:p?p.edition||'':'',weight:p&&p.weight?p.weight:'',authorImage:p?authorPhoto(p.author):''};
 render();
}

async function submitProduct(form){
 var d=Object.fromEntries(new FormData(form)),err=document.getElementById('f-err');
 var title=(d.title||'').trim(),price=parseFloat(d.price);
 if(!title){err.textContent='Add a title for the book.';return}
 if(!(price>=0)){err.textContent='Enter a price, for example 12.50.';return}
 var old=parseFloat(d.oldPrice),m=S.modal;
 var id=m.p?m.p.id:'b'+Date.now().toString(36);
 var doc={title:title,author:(d.author||'').trim(),category:(d.category||'').trim()||'General',price:price,oldPrice:old>price?old:0,stock:Math.max(0,parseInt(d.stock,10)||0),pages:parseInt(d.pages,10)||0,format:d.format||'Paperback',isbn:(d.isbn||'').trim(),publisher:(d.publisher||'').trim(),language:(d.language||'').trim(),country:(d.country||'').trim(),edition:(d.edition||'').trim(),weight:Math.max(0,parseInt(d.weight,10)||0),description:(d.description||'').trim(),hue:parseInt(d.hue,10)||0,featured:!!d.featured,image:m.image||'',createdAt:m.p&&m.p.createdAt?m.p.createdAt:Date.now()};
 S.busy=true;render();
 try{
  await S.db.collection('products').doc(id).set(doc);
  if(doc.author){
   var aid=authorId(doc.author),ex=S.dbAuthors[aid],np=m.authorImage||'',op=(ex&&ex.photo)||'';
   if(np!==op)await S.db.collection('authors').doc(aid).set({name:doc.author,photo:np});
  }
  await ensureCustom();
  S.modal=null;S.busy=false;toast(m.p?'Changes saved':'Book added to the shop');
 }catch(e){
  S.busy=false;render();
  var er=document.getElementById('f-err');if(er)er.textContent='Could not save: '+((e&&e.message)||'try again in a moment')+'.';
 }
}
async function importSample(){
 S.busy=true;render();
 try{
  for(var i=0;i<SAMPLE.length;i++){var p=SAMPLE[i];await S.db.collection('products').doc(p.id).set(Object.assign(docBody(p),{createdAt:Date.now()-i}))}
  await ensureCustom();S.busy=false;toast('Sample books imported');
 }catch(e){S.busy=false;toast('Import failed: '+((e&&e.message)||'try again'))}
}
async function startEmpty(){
 S.busy=true;render();
 try{await ensureCustom();S.busy=false;toast('Your shelf is empty. Add your first book.')}catch(e){S.busy=false;toast('Could not start: '+((e&&e.message)||'try again'))}
}
async function submitSettings(form){
 var d=Object.fromEntries(new FormData(form));
 var body=Object.assign({},S.dbSettings,{name:(d.name||'').trim()||DEFAULTS.name,currency:(d.currency||'').trim()||'$',shipping:Math.max(0,parseFloat(d.shipping)||0),freeOver:Math.max(0,parseFloat(d.freeOver)||0),email:d.email||'',phone:d.phone||'',address:d.address||'',hours:d.hours||''});
 try{await S.db.doc('settings/store').set(body);S.dbSettings=body;toast('Settings saved')}catch(e){toast('Could not save: '+((e&&e.message)||'try again'))}
}
async function placeOrder(form){
 if(S.busy)return;
 var items=cartItems(),err=document.getElementById('c-err');
 if(!items.length)return;
 var d=Object.fromEntries(new FormData(form));
 var req=['name','phone','email','address','city'];
 for(var i=0;i<req.length;i++){if(!(d[req[i]]||'').trim()){err.textContent='Please fill in your '+req[i]+'.';var el=form.querySelector('[name="'+req[i]+'"]');if(el)el.focus();return}}
 if(!/^\S+@\S+\.\S+$/.test(d.email.trim())){err.textContent='That email address does not look right.';return}
 var t=totals();
 var order={number:'ORD-'+Date.now().toString(36).toUpperCase().slice(-6),items:items.map(function(x){return {id:x.p.id,title:x.p.title,price:x.p.price,qty:x.qty}}),subtotal:t.sub,shipping:t.ship,total:t.total,customer:{name:d.name.trim(),phone:d.phone.trim(),email:d.email.trim(),address:d.address.trim(),city:d.city.trim(),notes:(d.notes||'').trim()},payment:d.payment,status:'pending',createdAt:Date.now()};
 S.busy=true;render();
 var where=await saveRecord('orders',order);
 S.busy=false;S.cart={};saveCart();order.where=where;S.lastOrder=order;render();window.scrollTo(0,0);
}
async function sendMessage(form){
 var d=Object.fromEntries(new FormData(form)),err=document.getElementById('m-err');
 if(!(d.name||'').trim()||!(d.message||'').trim()){err.textContent='Please add your name and a message.';return}
 if(!/^\S+@\S+\.\S+$/.test((d.email||'').trim())){err.textContent='That email address does not look right.';return}
 var where=await saveRecord('messages',{name:d.name.trim(),email:d.email.trim(),message:d.message.trim(),read:false,createdAt:Date.now()});
 S.contactSent=where;render();
}
async function dbDo(fn,okMsg){try{await fn();if(okMsg)toast(okMsg)}catch(e){toast('Could not complete that: '+((e&&e.message)||'try again'))}}

/* ---------- events ---------- */
document.addEventListener('click',function(e){
 if(S.notifOpen&&!e.target.closest('.notif')&&!e.target.closest('[data-act="notif"]')){S.notifOpen=false;render()}
 var el=e.target.closest('[data-act]');if(!el)return;
 var a=el.dataset.act,id=el.dataset.id;
 if(a==='overlay'){if(e.target===el){S.modal=null;render()}return}
 switch(a){
  case 'menu':S.menu=!S.menu;render();break;
  case 'scroll':e.preventDefault();var t=document.getElementById(el.dataset.to);if(t)t.scrollIntoView({behavior:'smooth'});break;
  case 'add':addToCart(id,1);break;
  case 'add-detail':addToCart(id,S.dq);break;
  case 'dq':S.dq=Math.max(1,S.dq+Number(el.dataset.d));var p=findP(S.route.id);if(p&&S.dq>p.stock)S.dq=Math.max(1,p.stock);render();break;
  case 'qty':setQty(id,Number(el.dataset.d));break;
  case 'remove':delete S.cart[id];saveCart();render();break;
  case 'cat':S.filter.cat=el.dataset.cat;render();break;
  case 'clear':S.filter={q:'',cat:'All',sort:S.filter.sort};render();break;
  case 'contact-again':S.contactSent=null;render();break;
  case 'atab':S.admin.tab=el.dataset.tab;S.admin.confirm='';render();break;
  case 'p-new':openModal(null);break;
  case 'p-edit':openModal(findP(id));break;
  case 'p-del':S.admin.confirm=id;render();break;
  case 'p-del-no':S.admin.confirm='';render();break;
  case 'p-del-yes':S.admin.confirm='';dbDo(async function(){await S.db.collection('products').doc(id).delete();await ensureCustom()},'Book deleted');break;
  case 'o-del':S.admin.confirm='o'+id;render();break;
  case 'o-del-yes':S.admin.confirm='';var oo=recOwner(S.orders,id);if(oo)dbDo(function(){return mutateRecords('orders',oo,function(l){return l.filter(function(x){return x.id!==id})})},'Order deleted');break;
  case 'm-del':S.admin.confirm='m'+id;render();break;
  case 'm-del-yes':S.admin.confirm='';var mo=recOwner(S.messages,id);if(mo)dbDo(function(){return mutateRecords('messages',mo,function(l){return l.filter(function(x){return x.id!==id})})},'Message deleted');break;
  case 'm-read':var m=S.messages.filter(function(x){return x.id===id})[0];if(m)dbDo(function(){return mutateRecords('messages',m.owner,function(l){return l.map(function(x){return x.id===id?Object.assign({},x,{read:!m.read}):x})})});break;
  case 'import':importSample();break;
  case 'start-empty':startEmpty();break;
  case 'modal-close':S.modal=null;render();break;
  case 'img-remove':S.modal.image='';render();break;
  case 'aimg-remove':S.modal.authorImage='';render();break;
  case 'follow':toggleFollow(el.dataset.name);break;
  case 'unfollow':delete S.follows.authors[authorId(el.dataset.name)];saveFollows();render();break;
  case 'notif':
   S.notifOpen=!S.notifOpen;
   if(S.notifOpen){S.notifList=notifs();if(S.notifList.length){S.follows.readAt=Date.now();saveFollows()}}
   render();break;
 }
});
document.addEventListener('input',function(e){
 var t=e.target,id=t.id;
 if(id==='q'){S.filter.q=t.value;render()}
 else if(id==='aq'){S.admin.q=t.value;render()}
 else if(S.modal&&(id==='f-title'||id==='f-author'||id==='f-hue')){
  var m=S.modal;
  if(id==='f-title')m.title=t.value;if(id==='f-author')m.author=t.value;if(id==='f-hue')m.hue=Number(t.value);
  var box=document.getElementById('cv-prev');
  if(box)box.innerHTML=cover({id:m.p?m.p.id:'preview',title:m.title||'Untitled',author:m.author||'Author',hue:m.hue,image:m.image});
 }
});
document.addEventListener('change',function(e){
 var t=e.target;
 if(t.id==='sort'){S.filter.sort=t.value;render();return}
 var k=t.dataset&&t.dataset.change;
 if(k==='order-status'){var oid=t.dataset.id,ow=recOwner(S.orders,oid),sv=t.value;if(ow)dbDo(function(){return mutateRecords('orders',ow,function(l){return l.map(function(x){return x.id===oid?Object.assign({},x,{status:sv}):x})})},'Order marked '+sv)}
 else if(k==='img'&&t.files&&t.files[0]){
  fileToDataUrl(t.files[0]).then(function(u){S.modal.image=u;render()}).catch(function(){var er=document.getElementById('f-err');if(er)er.textContent='That file could not be read as an image.'});
 }
 else if(k==='aimg'&&t.files&&t.files[0]){
  fileToDataUrl(t.files[0],320).then(function(u){S.modal.authorImage=u;render()}).catch(function(){var er=document.getElementById('f-err');if(er)er.textContent='That file could not be read as an image.'});
 }
});
document.addEventListener('submit',function(e){
 var f=e.target.closest('form[data-form]');if(!f)return;
 e.preventDefault();
 var k=f.dataset.form;
 if(k==='checkout')placeOrder(f);
 else if(k==='contact')sendMessage(f);
 else if(k==='product'){
  // sync typed values into the modal state so a re-render keeps them
  submitProduct(f);
 }
 else if(k==='settings')submitSettings(f);
});
document.addEventListener('keydown',function(e){if(e.key==='Escape'&&S.modal){S.modal=null;render()}});

/* ---------- boot ---------- */
S.route=parseRoute();
render();

(async function connect(){
 var c=window.claude;if(!c||!c.use)return;
 slowTimer=setTimeout(function(){if(!S.loaded.products){S.slow=true;render()}},10000);
 try{
  var user=await c.use('user');
  S.isAdmin=user?await user.canEdit():false;
  S.uid=user?await user.id():null;
  var db=await c.use('db');
  if(!db){render();return}
  S.db=db;
  db.collection('products').onSnapshot(function(snap){
   var list=snap.docs.map(function(d){return Object.assign({id:d.id},d.data())}),fresh=[];
   if(S.loaded.products){
    var seen={};S.dbProducts.forEach(function(p){seen[p.id]=1});
    fresh=list.filter(function(p){return !seen[p.id]&&p.author&&S.follows.authors[authorId(p.author)]});
   }
   S.dbProducts=list;S.loaded.products=true;clearTimeout(slowTimer);S.slow=false;
   if(fresh.length)toast('New book by '+fresh[0].author+': '+fresh[0].title);else render();
  },function(){S.loaded.products=false;render()});
  db.collection('authors').onSnapshot(function(snap){
   var m={};snap.docs.forEach(function(d){m[d.id]=d.data()});S.dbAuthors=m;render();
  },function(){});
  if(S.uid){
   db.doc('follows/'+S.uid).onSnapshot(function(d){
    if(d.exists){var v=d.data();S.follows={authors:v.authors||{},readAt:v.readAt||0}}
    render();
   },function(){});
  }
  if(S.isAdmin){
   db.collection('follows').onSnapshot(function(snap){
    S.followDocs=snap.docs.map(function(d){return d.data()});render();
   },function(){});
  }
  db.doc('settings/store').onSnapshot(function(d){
   S.dbSettings=d.exists?d.data():{};S.loaded.settings=true;render();
  },function(){});
  if(S.isAdmin){
   db.collection('orders').onSnapshot(function(snap){
    S.orders=flatten(snap);S.loaded.orders=true;render();
   },function(){});
   db.collection('messages').onSnapshot(function(snap){
    S.messages=flatten(snap);S.loaded.messages=true;render();
   },function(){});
  }
  render();
 }catch(e){render()}
})();
})();
</script>
