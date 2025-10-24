<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Guilherme de Morais — Fullstack • IA • Automação</title>
<meta name="description" content="Portfólio de Guilherme de Morais — Fullstack Web Developer. IA & Automação (N8N), PHP/Laravel, Node.js, WordPress Engineering. Autônomo desde 2017.">
<style>
  :root{
    --bg:#0b0f12; --bg2:#0e131a; --card:#111823; --card2:#121b27;
    --text:#e8edf3; --muted:#a6b3c6; --line:#1e2a3a; --accent:#ff8c32; --accent2:#ffb169;
    --ok:#22c55e; --warn:#f59e0b; --bad:#ef4444; --shadow:0 14px 40px rgba(0,0,0,.45);
  }
  *{box-sizing:border-box}
  html,body{height:100%}
  body{margin:0;background:radial-gradient(1200px 900px at 85% -10%,rgba(255,140,50,.08),transparent),linear-gradient(180deg,var(--bg) 0%,var(--bg2) 100%);color:var(--text);font:15.5px/1.6 ui-sans-serif,system-ui,-apple-system,Segoe UI,Inter,Roboto,Arial}
  a{color:var(--accent);text-decoration:none} a:hover{color:var(--accent2)}
  .wrap{max-width:1100px;margin:0 auto;padding:28px}
  header{display:grid;grid-template-columns:1fr;gap:18px;margin:6px 0 18px}
  @media(min-width:920px){header{grid-template-columns:auto 1fr}}
  .avatar{width:96px;height:96px;border-radius:24px;background:linear-gradient(135deg,#1a2233,#0c1018);border:1px solid #1f2937;display:grid;place-items:center;box-shadow:var(--shadow)}
  .avatar svg{width:54px;height:54px;opacity:.95}
  h1{margin:0;font-size:28px;letter-spacing:.2px}
  .tag{color:var(--muted);margin-top:6px}
  .badges{display:flex;flex-wrap:wrap;gap:8px;margin-top:10px}
  .badge{background:#0f1622;border:1px solid #1f2a3a;color:#cfe4ff;padding:6px 10px;border-radius:999px;font-size:13px}
  .actions{display:flex;flex-wrap:wrap;gap:10px;margin-top:14px}
  .btn{display:inline-flex;align-items:center;gap:8px;padding:10px 14px;border-radius:12px;border:1px solid #223049;background:linear-gradient(180deg,#0e1623,#0a111a);color:var(--text);box-shadow:var(--shadow);transition:.2s}
  .btn:hover{transform:translateY(-1px);border-color:#344e79}
  .btn.primary{background:linear-gradient(180deg,#ff933f,#ff7e1a);border-color:#ff7e1a;color:#121418}
  section{margin:28px 0}
  .grid{display:grid;gap:16px}
  @media(min-width:920px){.cols-2{grid-template-columns:1fr 1fr}.cols-3{grid-template-columns:repeat(3,1fr)}}
  .card{background:linear-gradient(180deg,var(--card) 0%,var(--card2) 100%);border:1px solid var(--line);border-radius:18px;box-shadow:var(--shadow)}
  .pad{padding:20px}
  h3{margin:0 0 12px}
  .hr{height:1px;background:linear-gradient(90deg,transparent,#223048,transparent);margin:22px 0}
  /* SKILL ITEM */
  .skill{display:flex;gap:14px;align-items:center;background:rgba(255,255,255,.02);border:1px solid #1e2a3a;padding:12px 14px;border-radius:14px;transition:.15s}
  .skill:hover{border-color:#2a3c57;background:rgba(255,140,50,.04)}
  .logo{width:28px;height:28px;border-radius:8px;background:#0f1420;display:grid;place-items:center;border:1px solid #243046}
  .logo img{width:20px;height:20px;display:block}
  .skill-main{flex:1}
  .skill-title{display:flex;justify-content:space-between;gap:10px}
  .skill-title b{font-weight:600}
  .level{font-size:12px;color:#cbd6ea}
  .blocks{display:grid;grid-template-columns:repeat(10,12px);gap:6px;margin-top:8px}
  .block{width:12px;height:10px;border-radius:3px;background:#1a2433;border:1px solid #22324a;opacity:.9;transform:translateY(0);transition:transform .25s ease, background .25s ease, opacity .25s ease}
  .block.filled{background:linear-gradient(180deg,var(--accent),#ff7e1a);border-color:#ff913d}
  .skill:hover .block.filled{transform:translateY(-1px)}
  /* PROJECT CARD */
  .proj{display:flex;flex-direction:column;gap:8px}
  .proj .meta{color:#9fb0c6;font-size:13px}
  .pill{font-size:12px;padding:6px 10px;border-radius:999px;background:#0e1420;border:1px solid #243042;color:#c0d7f7;margin-right:6px;display:inline-block}
  .resume{display:flex;flex-wrap:wrap;gap:10px}
  footer{margin:40px 0;color:#8ea8c7;font-size:13px;text-align:center}
  /* subtle fade-in */
  .fade{animation:fade .5s ease both} @keyframes fade{from{opacity:0;transform:translateY(4px)}to{opacity:1;transform:translateY(0)}}
</style>
</head>
<body>
  <div class="wrap">
    <!-- HERO -->
    <header class="fade">
      <div class="avatar" aria-hidden="true">
        <!-- code glyph -->
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M8 17l-5-5 5-5"/><path d="M16 7l5 5-5 5"/><path d="M13 4l-2 16"/></svg>
      </div>
      <div>
        <h1>Guilherme de Morais — Fullstack • IA • Automação</h1>
        <div class="tag">Autônomo desde 2017 • PHP/Laravel • Node.js • WordPress Engineering • N8N • IA (Codex + MCP) • Web3 (em evolução)</div>
        <div class="badges">
          <span class="badge">Fullstack</span>
          <span class="badge">AI-Powered Development</span>
          <span class="badge">Automation (N8N)</span>
          <span class="badge">Problem Solver</span>
          <span class="badge">Open to Remote/Relocation</span>
        </div>
        <div class="actions">
          <a class="btn primary" href="#projetos">Ver Projetos</a>
          <a class="btn" href="mailto:guilhermemp.business@gmail.com">E-mail</a>
          <a class="btn" href="https://wa.me/5522998911070" target="_blank" rel="noopener">WhatsApp</a>
          <a class="btn" href="https://github.com/guilhermedemorais-dev" target="_blank" rel="noopener">GitHub</a>
          <a class="btn" href="https://www.linkedin.com/in/guilherme-de-moraisais-a440a8132/" target="_blank" rel="noopener">LinkedIn</a>
        </div>
      </div>
    </header>

    <!-- SOBRE -->
    <section class="card pad fade">
      <h3>Sobre</h3>
      <p>Sou Desenvolvedor Fullstack Autônomo desde 2017. Construo sistemas web completos, integrações de APIs e automações com IA e N8N. Trabalho com backend e frontend (PHP/Laravel, Node.js, JavaScript e WordPress Full Code), com foco em performance, segurança e entrega rápida. Aplico <b>AI-Powered Development</b> usando <b>OpenAI Codex</b> e <b>MCP (Model Context Protocol)</b> para acelerar arquitetura e implementação.</p>
    </section>

    <!-- SKILLS -->
    <section class="grid cols-2 fade" id="skills">
      <div class="card pad">
        <h3>Stacks & Níveis</h3>

        <!-- helper legend -->
        <div class="tag" style="margin-bottom:10px">Nível indicado por blocos (10 = 100%)</div>

        <!-- PHP / Laravel 85% -->
        <div class="skill">
          <div class="logo"><img alt="PHP" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg"></div>
          <div class="skill-main">
            <div class="skill-title"><b>PHP / Laravel</b><span class="level">85%</span></div>
            <div class="blocks" data-fill="8"></div>
          </div>
        </div>

        <!-- Node / JS 80% -->
        <div class="skill">
          <div class="logo"><img alt="Node" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg"></div>
          <div class="skill-main">
            <div class="skill-title"><b>Node.js / JavaScript</b><span class="level">80%</span></div>
            <div class="blocks" data-fill="8"></div>
          </div>
        </div>

        <!-- MySQL / REST 75% -->
        <div class="skill">
          <div class="logo"><img alt="MySQL" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg"></div>
          <div class="skill-main">
            <div class="skill-title"><b>MySQL / REST APIs</b><span class="level">75%</span></div>
            <div class="blocks" data-fill="7"></div>
          </div>
        </div>

        <!-- WordPress 95% -->
        <div class="skill">
          <div class="logo"><img alt="WordPress" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/wordpress/wordpress-plain.svg"></div>
          <div class="skill-main">
            <div class="skill-title"><b>WordPress Engineering (Full Code)</b><span class="level">95%</span></div>
            <div class="blocks" data-fill="9"></div>
          </div>
        </div>

        <!-- HTML/CSS/Tailwind 90% -->
        <div class="skill">
          <div class="logo"><img alt="Tailwind" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-plain.svg"></div>
          <div class="skill-main">
            <div class="skill-title"><b>HTML • CSS • Tailwind</b><span class="level">90%</span></div>
            <div class="blocks" data-fill="9"></div>
          </div>
        </div>

        <!-- Docker/Linux 70% -->
        <div class="skill">
          <div class="logo"><img alt="Docker" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg"></div>
          <div class="skill-main">
            <div class="skill-title"><b>Docker (básico) • Linux VPS</b><span class="level">70%</span></div>
            <div class="blocks" data-fill="7"></div>
          </div>
        </div>
      </div>

      <div class="card pad">
        <h3>IA, Automação & Web3</h3>

        <!-- N8N 85% -->
        <div class="skill">
          <div class="logo">
            <!-- n8n simple logo -->
            <svg viewBox="0 0 64 64" width="20" height="20"><path fill="#ff4f5a" d="M20 12a8 8 0 100 16 8 8 0 000-16zm24 24a8 8 0 100 16 8 8 0 000-16z"/><path fill="#fff" d="M22 20h20v4H22z"/><circle cx="20" cy="20" r="4" fill="#fff"/><circle cx="44" cy="44" r="4" fill="#fff"/></svg>
          </div>
          <div class="skill-main">
            <div class="skill-title"><b>N8N Automation</b><span class="level">85%</span></div>
            <div class="blocks" data-fill="8"></div>
          </div>
        </div>

        <!-- OpenAI 60% -->
        <div class="skill">
          <div class="logo">
            <!-- OpenAI knot minimal -->
            <svg viewBox="0 0 24 24" width="20" height="20" fill="none" stroke="#00e0b8" stroke-width="1.6"><path d="M12 3.5c-2.4 0-4.5 1.6-5.1 4-2 .3-3.4 2.1-3.4 4.1 0 2 1.4 3.7 3.3 4.1.6 2.3 2.7 4 5.2 4 2.4 0 4.5-1.6 5.1-4 2-.3 3.4-2.1 3.4-4.1 0-2-1.4-3.7-3.3-4.1-.6-2.3-2.7-4-5.2-4z"/></svg>
          </div>
          <div class="skill-main">
            <div class="skill-title"><b>OpenAI / Codex • MCP</b><span class="level">60%</span></div>
            <div class="blocks" data-fill="6"></div>
          </div>
        </div>

        <!-- LangChain 30% -->
        <div class="skill">
          <div class="logo">
            <svg viewBox="0 0 24 24" width="20" height="20"><rect x="3" y="3" width="8" height="8" rx="2" fill="#49d" /><rect x="13" y="13" width="8" height="8" rx="2" fill="#49d" /><rect x="13" y="3" width="8" height="8" rx="2" fill="#8ad" /><rect x="3" y="13" width="8" height="8" rx="2" fill="#8ad" /></svg>
          </div>
          <div class="skill-main">
            <div class="skill-title"><b>LangChain / LLMs</b><span class="level">30%</span></div>
            <div class="blocks" data-fill="3"></div>
          </div>
        </div>

        <!-- Web3 20% -->
        <div class="skill">
          <div class="logo">
            <svg viewBox="0 0 24 24" width="20" height="20" fill="none" stroke="#ffa64d" stroke-width="1.6"><path d="M4 12l8-8 8 8-8 8-8-8z"/><path d="M12 4v16"/></svg>
          </div>
          <div class="skill-main">
            <div class="skill-title"><b>Web3 / Solidity / Blockchain</b><span class="level">20%</span></div>
            <div class="blocks" data-fill="2"></div>
          </div>
        </div>
      </div>
    </section>

    <div class="hr"></div>

    <!-- PROJETOS -->
    <section id="projetos" class="grid cols-3 fade">
      <div class="card pad proj">
        <h3>PRJ1 — Plugin WordPress (Segurança + API)</h3>
        <div class="meta">PHP • WP • OOP • API externa • OWASP</div>
        <p>Plugin nativo com arquitetura modular, hooks/shortcodes e sanitização de dados.</p>
        <div><a class="pill" href="#">Código</a><a class="pill" href="#">README</a></div>
      </div>
      <div class="card pad proj">
        <h3>PRJ2 — API REST (Laravel + JWT)</h3>
        <div class="meta">Laravel • MySQL • JWT • Postman</div>
        <p>API RESTful com CRUD, validação, autenticação e versionamento.</p>
        <div><a class="pill" href="#">Código</a><a class="pill" href="#">Postman</a></div>
      </div>
      <div class="card pad proj">
        <h3>PRJ3 — Automação N8N + IA</h3>
        <div class="meta">N8N • OpenAI • Webhooks</div>
        <p>Pipeline automatizado com IA para integrações entre sistemas.</p>
        <div><a class="pill" href="#">Workflow</a><a class="pill" href="#">Docs</a></div>
      </div>
      <div class="card pad proj">
        <h3>PRJ4 — Dashboard Realtime</h3>
        <div class="meta">Node.js • Socket.IO • Tailwind</div>
        <p>Aplicação em tempo real com WebSockets e UI responsiva.</p>
        <div><a class="pill" href="#">Código</a><a class="pill" href="#">Demo</a></div>
      </div>
      <div class="card pad proj">
        <h3>Case — Sistema Médico (USA)</h3>
        <div class="meta">Fullstack • Booking • Multi-user</div>
        <p>Plataforma de agendamento para clínica na Califórnia.</p>
        <div><a class="pill" href="#">Case</a></div>
      </div>
      <div class="card pad proj">
        <h3>Case — Web Delivery</h3>
        <div class="meta">Pedidos • Painel • Integrações</div>
        <p>Sistema de pedidos online com painel administrativo.</p>
        <div><a class="pill" href="#">Case</a></div>
      </div>
    </section>

    <div class="hr"></div>

    <!-- SERVIÇOS + CONTATO -->
    <section class="grid cols-2 fade">
      <div class="card pad">
        <h3>Serviços (Autônomo)</h3>
        <ul>
          <li>Desenvolvimento de Sistemas Web (Fullstack)</li>
          <li>APIs & Integrações (REST, Webhooks, SaaS)</li>
          <li>Automação com N8N e IA aplicada</li>
          <li>WordPress Full Code (temas, plugins e soluções)</li>
          <li>Infraestrutura e Deploy em VPS Linux</li>
        </ul>
      </div>
      <div class="card pad">
        <h3>Currículo & Contato</h3>
        <div class="resume">
          <a class="btn" href="https://drive.google.com/file/d/1pwHJLBamfhcOr5Un3W2MBbn72mb-QXN8/view?usp=sharing" target="_blank" title="Currículo Brasil (PDF)">Currículo BR (PDF)</a>
          <a class="btn" href="https://docs.google.com/document/d/133HGPRcXt7o1cS1oN_6QtH1RlThlyLZ9M_oyYw2Utf4/edit?usp=sharing" target="_blank" title="Currículo Internacional (EN)">Currículo EN (Global)</a>
          <a class="btn" href="mailto:guilhermemp.business@gmail.com">E-mail</a>
          <a class="btn" href="https://wa.me/5522998911070" target="_blank">WhatsApp</a>
        </div>
      </div>
    </section>

    <footer>© <span id="year"></span> Guilherme de Morais — Fullstack • IA • Automação • WordPress Engineering</footer>
  </div>

<script>
  // ano
  document.getElementById('year').textContent = new Date().getFullYear();

  // cria blocos e anima preenchimento
  document.querySelectorAll('.blocks').forEach((wrap, i)=>{
    const fill = Math.max(0, Math.min(10, parseInt(wrap.dataset.fill||'0',10))); // 0..10
    for(let k=0;k<10;k++){
      const b=document.createElement('div');
      b.className='block'+(k<fill?' filled':'');
      b.style.animation=`pop .3s ${0.02*k + (i*0.03)}s both`;
      wrap.appendChild(b);
    }
  });

  // keyframes inline
  const st = document.createElement('style');
  st.textContent = `@keyframes pop{from{opacity:0;transform:translateY(4px)}to{opacity:1;transform:translateY(0)}}`;
  document.head.appendChild(st);
</script>
</body>
  <!-- Portfolio atualizado com links dos currículos -->
</html>
