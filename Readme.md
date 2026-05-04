
<style>
@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;600&family=Anybody:wght@800;900&display=swap');
*{box-sizing:border-box;margin:0;padding:0}
.wrap{background:#080c10;color:#cdd6f4;font-family:'IBM Plex Mono',monospace;padding:2.5rem 2rem;min-height:100vh}
.grid-bg{position:absolute;top:0;left:0;width:100%;height:280px;background-image:linear-gradient(#1e2a3a22 1px,transparent 1px),linear-gradient(90deg,#1e2a3a22 1px,transparent 1px);background-size:32px 32px;pointer-events:none}
.hero{position:relative;margin-bottom:2.5rem;padding-bottom:2rem;border-bottom:1px solid #1e2a3a}
.hero-name{font-family:'Anybody',sans-serif;font-size:3.8rem;font-weight:900;line-height:.95;color:#e2e8f0;letter-spacing:-2px;margin-bottom:.4rem}
.hero-name span{color:#4ade80}
.hero-role{font-size:.7rem;color:#4ade80;letter-spacing:.18em;text-transform:uppercase;margin-bottom:1.2rem}
.hero-desc{font-size:.78rem;color:#94a3b8;line-height:1.7;max-width:480px}
.location-line{display:flex;align-items:center;gap:8px;margin-top:.8rem;font-size:.68rem;color:#475569}
.dot-ping{width:7px;height:7px;background:#4ade80;border-radius:50%;display:inline-block;animation:ping 2s ease-in-out infinite}
@keyframes ping{0%,100%{opacity:1;transform:scale(1)}50%{opacity:.4;transform:scale(1.4)}}
.badge-row{display:flex;flex-wrap:wrap;gap:6px;margin-bottom:2rem}
.badge{font-size:.6rem;padding:3px 9px;border-radius:3px;border:1px solid;letter-spacing:.06em;font-weight:600}
.b-g{border-color:#4ade8055;color:#4ade80;background:#4ade8010}
.b-b{border-color:#60a5fa55;color:#60a5fa;background:#60a5fa10}
.b-o{border-color:#fb923c55;color:#fb923c;background:#fb923c10}
.b-p{border-color:#a78bfa55;color:#a78bfa;background:#a78bfa10}
.b-c{border-color:#22d3ee55;color:#22d3ee;background:#22d3ee10}
.sec-label{font-size:.6rem;letter-spacing:.2em;color:#4ade80;text-transform:uppercase;margin-bottom:.75rem;display:flex;align-items:center;gap:8px}
.sec-label::before{content:'//';color:#1e3a5f}
.sec-label::after{content:'';flex:1;height:1px;background:#1e2a3a}
.cards2{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-bottom:2rem}
.cards3{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-bottom:2rem}
.card{background:#0d1520;border:1px solid #1e2a3a;border-radius:6px;padding:12px 14px}
.card:hover{border-color:#4ade8044}
.card-key{font-size:.56rem;color:#475569;text-transform:uppercase;letter-spacing:.12em;margin-bottom:4px}
.card-val{font-size:.75rem;color:#e2e8f0;line-height:1.45}
.card-val a{color:#60a5fa;text-decoration:none}
.stack-card{background:#0d1520;border:1px solid #1e2a3a;border-radius:6px;padding:12px 14px}
.stack-card:hover{border-color:#4ade8044}
.stack-cat{font-size:.57rem;color:#4ade80;letter-spacing:.14em;text-transform:uppercase;margin-bottom:6px}
.stack-vals{font-size:.7rem;color:#64748b;line-height:1.6}
.feat{background:#0d1520;border:1px solid #4ade8040;border-radius:8px;padding:1.3rem 1.5rem;margin-bottom:2rem;position:relative}
.feat-label{position:absolute;top:-1px;left:18px;font-size:.55rem;letter-spacing:.14em;color:#080c10;background:#4ade80;padding:2px 8px;border-radius:0 0 4px 4px;font-weight:600}
.feat-title{font-family:'Anybody',sans-serif;font-size:1.1rem;font-weight:800;color:#e2e8f0;margin-bottom:.4rem;margin-top:.6rem}
.feat-desc{font-size:.72rem;color:#64748b;line-height:1.7;margin-bottom:.9rem}
.feat-pills{display:flex;flex-wrap:wrap;gap:5px}
.pill{font-size:.6rem;padding:2px 8px;background:#1e2a3a;color:#64748b;border-radius:3px}
.stat-row{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-bottom:2rem}
.stat-box{background:#0d1520;border:1px solid #1e2a3a;border-radius:6px;padding:1rem;text-align:center}
.stat-n{font-family:'Anybody',sans-serif;font-size:2rem;font-weight:900;color:#4ade80;line-height:1;display:block}
.stat-l{font-size:.57rem;color:#475569;letter-spacing:.1em;text-transform:uppercase;display:block;margin-top:4px}
.focus-list{display:grid;gap:7px;margin-bottom:2rem}
.focus-item{background:#0d1520;border:1px solid #1e2a3a;border-left:2px solid #1e3a5f;border-radius:0 6px 6px 0;padding:9px 14px;display:flex;align-items:center;gap:10px;font-size:.72rem;color:#94a3b8;transition:border-left-color .15s}
.focus-item:hover{border-left-color:#4ade80}
.fi-num{color:#4ade80;min-width:22px;font-weight:600}
.term{background:#060a0e;border:1px solid #1e2a3a;border-radius:8px;overflow:hidden;margin-bottom:2rem}
.term-top{background:#0d1520;padding:8px 14px;display:flex;align-items:center;gap:6px;border-bottom:1px solid #1e2a3a}
.td{width:10px;height:10px;border-radius:50%}
.td.r{background:#ff5f57}.td.y{background:#ffbd2e}.td.g{background:#28c840}
.term-path{font-size:.62rem;color:#475569;margin-left:8px}
.term-body{padding:1rem 1.25rem;font-size:.72rem;line-height:1.9}
.t-p{color:#4ade80}.t-c{color:#e2e8f0}.t-o{color:#60a5fa}.t-cm{color:#334155}
.t-cursor{display:inline-block;width:8px;height:.85em;background:#4ade80;vertical-align:text-bottom;animation:blink 1.1s step-end infinite}
@keyframes blink{0%,100%{opacity:1}50%{opacity:0}}
.contacts{display:flex;gap:8px;margin-bottom:2rem}
.contact-a{flex:1;background:#0d1520;border:1px solid #1e2a3a;border-radius:6px;padding:10px 14px;display:flex;align-items:center;gap:10px;text-decoration:none;color:#e2e8f0;font-family:'IBM Plex Mono',monospace;transition:border-color .15s}
.contact-a:hover{border-color:#60a5fa}
.ct-icon{width:32px;height:32px;border-radius:4px;background:#0f2033;display:flex;align-items:center;justify-content:center;font-size:13px}
.ct-plat{font-size:.56rem;color:#475569;text-transform:uppercase;letter-spacing:.1em}
.ct-handle{font-size:.75rem;font-weight:600;color:#e2e8f0}
.quote-block{border-left:2px solid #4ade80;padding:.75rem 1rem;background:#0d1520;border-radius:0 6px 6px 0;margin-bottom:1rem}
.quote-block p{font-size:.73rem;color:#64748b;font-style:italic;line-height:1.65}
.quote-block .q-author{font-size:.6rem;color:#4ade80;margin-top:5px;font-style:normal}
.footer{display:flex;justify-content:space-between;align-items:center;padding-top:1.5rem;border-top:1px solid #1e2a3a}
.footer-l{font-size:.62rem;color:#475569}
.views-badge{font-size:.6rem;padding:3px 9px;border:1px solid #1e2a3a;border-radius:3px;color:#475569}
.stack-wide{grid-column:1/-1}
</style>

<div class="wrap">
  <div class="grid-bg"></div>

  <div class="hero">
    <div class="hero-role">system programmer &amp; devops engineer</div>
    <div class="hero-name">sir<span>mir</span><br>25</div>
    <div class="hero-desc">Linux enthusiast who believes understanding your OS is the first step to mastering any infrastructure. Automate everything that can be automated.</div>
    <div class="location-line">
      <span class="dot-ping"></span>
      <span>Billings, Montana, USA</span>
    </div>
  </div>

  <div class="badge-row">
    <span class="badge b-g">Arch Linux</span>
    <span class="badge b-o">Rust</span>
    <span class="badge b-b">Kubernetes</span>
    <span class="badge b-p">Docker</span>
    <span class="badge b-c">eBPF</span>
    <span class="badge b-g">Bash</span>
    <span class="badge b-b">Prometheus</span>
    <span class="badge b-o">AppArmor</span>
    <span class="badge b-p">CI/CD</span>
    <span class="badge b-c">Grafana</span>
  </div>

  <div class="sec-label">about</div>
  <div class="cards2" style="margin-bottom:2rem">
    <div class="card"><div class="card-key">currently building</div><div class="card-val">Cloud architectures &amp; K8s orchestration</div></div>
    <div class="card"><div class="card-key">learning</div><div class="card-val">Advanced K8s operators + eBPF</div></div>
    <div class="card"><div class="card-key">2026 goal</div><div class="card-val">More open-source contributions</div></div>
    <div class="card"><div class="card-key">ask me about</div><div class="card-val">Arch · Rust · Docker · CI/CD · hardening</div></div>
    <div class="card"><div class="card-key">contact</div><div class="card-val"><a href="https://t.me/linuxexex">@linuxexex on Telegram</a></div></div>
    <div class="card"><div class="card-key">fun fact</div><div class="card-val">Daily-drives Arch, unafraid of systemd</div></div>
  </div>

  <div class="sec-label">stack</div>
  <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:8px;margin-bottom:2rem">
    <div class="stack-card"><div class="stack-cat">OS</div><div class="stack-vals">Arch Linux · macOS · Android · iOS</div></div>
    <div class="stack-card"><div class="stack-cat">Languages</div><div class="stack-vals">Rust · C · C++ · Python · Bash · TS · JS</div></div>
    <div class="stack-card"><div class="stack-cat">DevOps</div><div class="stack-vals">Docker · Kubernetes · GH Actions · GitLab CI</div></div>
    <div class="stack-card"><div class="stack-cat">Monitoring</div><div class="stack-vals">Prometheus · Grafana · htop · bpftrace</div></div>
    <div class="stack-card"><div class="stack-cat">Security</div><div class="stack-vals">AppArmor · auditd · SSH · firewalls</div></div>
    <div class="stack-card"><div class="stack-cat">IaC</div><div class="stack-vals">YAML · JSON · Terraform (learning)</div></div>
  </div>

  <div class="sec-label">featured project</div>
  <div class="feat">
    <div class="feat-label">pinned</div>
    <div class="feat-title">Rach — Programming Language</div>
    <div class="feat-desc">A simple, Turing-complete scripting language built in Rust. Static types with a dynamic feel, minimal memory footprint, designed to be easily embedded and extended in any system.</div>
    <div class="feat-pills">
      <span class="pill">Rust</span>
      <span class="pill">Turing-complete</span>
      <span class="pill">scripting</span>
      <span class="pill">embeddable</span>
      <span class="pill">★ 2</span>
    </div>
  </div>

  <div class="sec-label">stats</div>
  <div class="stat-row">
    <div class="stat-box"><span class="stat-n">7</span><span class="stat-l">repos</span></div>
    <div class="stat-box"><span class="stat-n">3</span><span class="stat-l">stars</span></div>
    <div class="stat-box"><span class="stat-n">∞</span><span class="stat-l">automation</span></div>
  </div>

  <div class="sec-label">current focus</div>
  <div class="focus-list">
    <div class="focus-item"><span class="fi-num">01</span>Cloud native — full K8s cluster management beyond Docker</div>
    <div class="focus-item"><span class="fi-num">02</span>Package management — AUR packages and Debian repos</div>
    <div class="focus-item"><span class="fi-num">03</span>Zero-trust security — personal and client infrastructure</div>
    <div class="focus-item"><span class="fi-num">04</span>Automation scripts — reusable, well-documented GitHub tools</div>
  </div>

  <div class="sec-label">terminal</div>
  <div class="term">
    <div class="term-top">
      <div class="td r"></div><div class="td y"></div><div class="td g"></div>
      <span class="term-path">sirmir25@arch  ~  zsh</span>
    </div>
    <div class="term-body">
      <div><span class="t-p">❯ </span><span class="t-c">whoami</span></div>
      <div><span class="t-o">sirilia — systems engineer · devops · Billings, MT</span></div>
      <br>
      <div><span class="t-p">❯ </span><span class="t-c">echo $STACK</span></div>
      <div><span class="t-o">Rust · Docker · K8s · Arch · Bash · eBPF</span></div>
      <br>
      <div><span class="t-p">❯ </span><span class="t-c">cat philosophy.txt</span></div>
      <div><span class="t-cm"># Knowledge of Linux isn't just a skill —</span></div>
      <div><span class="t-cm"># it's a philosophy of efficiency and control.</span></div>
      <br>
      <div><span class="t-p">❯ </span><span class="t-cursor"></span></div>
    </div>
  </div>

  <div class="sec-label">contact</div>
  <div class="contacts">
    <a class="contact-a" href="https://t.me/linuxexex">
      <div class="ct-icon">✈</div>
      <div><div class="ct-plat">Telegram</div><div class="ct-handle">@linuxexex</div></div>
    </a>
    <a class="contact-a" href="https://github.com/sirmir25">
      <div class="ct-icon" style="font-size:16px">◆</div>
      <div><div class="ct-plat">GitHub</div><div class="ct-handle">sirmir25</div></div>
    </a>
  </div>

  <div class="quote-block">
    <p>"Knowledge of Linux isn't just a skill — it's a philosophy of efficiency and control."</p>
    <div class="q-author">— sirmir25</div>
  </div>

  <div class="footer">
    <span class="footer-l">sirmir25 · github.com/sirmir25</span>
    <span class="views-badge">profile · active</span>
  </div>

</div>
