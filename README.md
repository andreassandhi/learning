<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NKP Discovery & Qualifying Questions — Logicalis Indonesia</title>
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --bg: #ffffff;
    --bg2: #f7f7f5;
    --bg3: #f1efe8;
    --text: #1a1a18;
    --text2: #5f5e5a;
    --text3: #888780;
    --border: rgba(0,0,0,0.12);
    --border2: rgba(0,0,0,0.22);
    --radius: 8px;
    --radius-lg: 12px;
  }

  @media (prefers-color-scheme: dark) {
    :root {
      --bg: #1c1c1a;
      --bg2: #252523;
      --bg3: #2e2e2b;
      --text: #f0ede6;
      --text2: #a8a59e;
      --text3: #6e6c67;
      --border: rgba(255,255,255,0.1);
      --border2: rgba(255,255,255,0.2);
    }
  }

  body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    background: var(--bg);
    color: var(--text);
    font-size: 14px;
    line-height: 1.6;
  }

  header {
    border-bottom: 0.5px solid var(--border2);
    padding: 20px 32px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 16px;
    flex-wrap: wrap;
    background: var(--bg);
    position: sticky;
    top: 0;
    z-index: 10;
  }

  .logo-block { display: flex; align-items: center; gap: 12px; }

  .logo-icon {
    width: 36px; height: 36px;
    background: #185FA5;
    border-radius: 8px;
    display: flex; align-items: center; justify-content: center;
  }

  .logo-icon svg { width: 20px; height: 20px; }

  .header-title { font-size: 15px; font-weight: 600; color: var(--text); letter-spacing: -0.01em; }
  .header-sub { font-size: 12px; color: var(--text2); margin-top: 1px; }

  .header-badge {
    font-size: 11px;
    padding: 4px 10px;
    border-radius: 20px;
    background: #E6F1FB;
    color: #0C447C;
    font-weight: 500;
  }
  @media (prefers-color-scheme: dark) {
    .header-badge { background: #0C447C; color: #B5D4F4; }
  }

  main { max-width: 1200px; margin: 0 auto; padding: 24px 32px 60px; }

  .intro { margin-bottom: 24px; }
  .intro h1 { font-size: 22px; font-weight: 600; color: var(--text); margin-bottom: 6px; letter-spacing: -0.02em; }
  .intro p { font-size: 13.5px; color: var(--text2); max-width: 680px; line-height: 1.7; }

  .use-case-pills {
    display: flex; flex-wrap: wrap; gap: 6px; margin: 16px 0 24px;
  }

  .uc-pill {
    font-size: 11.5px;
    padding: 4px 10px;
    border-radius: 20px;
    font-weight: 500;
    cursor: pointer;
    border: 0.5px solid transparent;
    transition: opacity 0.15s;
  }
  .uc-pill:hover { opacity: 0.8; }
  .uc-pill.active { border-color: var(--border2); }

  .controls {
    display: flex; flex-wrap: wrap; gap: 10px; margin-bottom: 14px; align-items: center;
  }

  .search-wrap { flex: 1; min-width: 200px; position: relative; }
  .search-wrap svg {
    position: absolute; left: 10px; top: 50%; transform: translateY(-50%);
    width: 14px; height: 14px; color: var(--text3);
  }

  input[type=text] {
    width: 100%;
    padding: 8px 12px 8px 32px;
    border: 0.5px solid var(--border2);
    border-radius: var(--radius);
    background: var(--bg);
    color: var(--text);
    font-size: 13px;
    outline: none;
  }
  input[type=text]:focus { border-color: #378ADD; box-shadow: 0 0 0 2px rgba(55,138,221,0.15); }

  select {
    padding: 8px 10px;
    border: 0.5px solid var(--border2);
    border-radius: var(--radius);
    background: var(--bg);
    color: var(--text);
    font-size: 13px;
    outline: none;
    cursor: pointer;
  }

  .stats {
    font-size: 12px; color: var(--text3); margin-bottom: 12px;
  }

  .tbl-wrap { overflow-x: auto; border-radius: var(--radius-lg); border: 0.5px solid var(--border); }

  table { width: 100%; border-collapse: collapse; table-layout: fixed; }

  col.c0 { width: 36px; }
  col.c1 { width: 27%; }
  col.c2 { width: 26%; }
  col.c3 { width: 22%; }
  col.c4 { width: 15%; }

  th {
    background: var(--bg3);
    color: var(--text2);
    font-weight: 500;
    font-size: 10.5px;
    text-transform: uppercase;
    letter-spacing: 0.05em;
    padding: 10px 12px;
    text-align: left;
    border-bottom: 0.5px solid var(--border2);
  }

  td {
    padding: 10px 12px;
    border-bottom: 0.5px solid var(--border);
    vertical-align: top;
    color: var(--text);
    font-size: 12.5px;
    line-height: 1.55;
  }

  tr:last-child td { border-bottom: none; }
  tr:hover td { background: var(--bg2); }

  .num { font-size: 11px; color: var(--text3); font-weight: 600; }

  .q { font-weight: 500; color: var(--text); margin-bottom: 0; }

  .ans { color: var(--text2); font-size: 11.5px; margin-top: 4px; }

  .badge {
    display: inline-block;
    font-size: 10.5px;
    font-weight: 500;
    padding: 3px 8px;
    border-radius: 4px;
    line-height: 1.4;
  }

  .persona-wrap { display: flex; flex-wrap: wrap; gap: 4px; }
  .p-tag {
    font-size: 10px;
    padding: 2px 6px;
    border-radius: 3px;
    border: 0.5px solid var(--border2);
    color: var(--text2);
    white-space: nowrap;
  }

  .u1  { background: #EEEDFE; color: #3C3489; }
  .u2  { background: #E1F5EE; color: #085041; }
  .u3  { background: #FAEEDA; color: #633806; }
  .u4  { background: #EAF3DE; color: #27500A; }
  .u5  { background: #FAECE7; color: #712B13; }
  .u6  { background: #FBEAF0; color: #72243E; }
  .u7  { background: #E6F1FB; color: #0C447C; }
  .u8  { background: #F1EFE8; color: #444441; }
  .u9  { background: #FCEBEB; color: #791F1F; }
  .u10 { background: #FAEEDA; color: #412402; }

  @media (prefers-color-scheme: dark) {
    .u1  { background: #3C3489; color: #CECBF6; }
    .u2  { background: #085041; color: #9FE1CB; }
    .u3  { background: #633806; color: #FAC775; }
    .u4  { background: #27500A; color: #C0DD97; }
    .u5  { background: #712B13; color: #F5C4B3; }
    .u6  { background: #72243E; color: #F4C0D1; }
    .u7  { background: #0C447C; color: #B5D4F4; }
    .u8  { background: #444441; color: #D3D1C7; }
    .u9  { background: #791F1F; color: #F7C1C1; }
    .u10 { background: #412402; color: #FAC775; }
  }

  .no-results {
    text-align: center; padding: 48px 24px;
    color: var(--text3); font-size: 13px;
  }

  footer {
    text-align: center; padding: 24px;
    font-size: 11.5px; color: var(--text3);
    border-top: 0.5px solid var(--border);
    margin-top: 48px;
  }

  @media (max-width: 640px) {
    header { padding: 14px 16px; }
    main { padding: 16px 12px 48px; }
    col.c2 { display: none; }
    td:nth-child(3) { display: none; }
    th:nth-child(3) { display: none; }
  }
</style>
</head>
<body>

<header>
  <div class="logo-block">
    <div class="logo-icon">
      <svg viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
        <rect x="2" y="2" width="7" height="7" rx="1.5" fill="white" opacity="0.9"/>
        <rect x="11" y="2" width="7" height="7" rx="1.5" fill="white" opacity="0.6"/>
        <rect x="2" y="11" width="7" height="7" rx="1.5" fill="white" opacity="0.6"/>
        <rect x="11" y="11" width="7" height="7" rx="1.5" fill="white" opacity="0.3"/>
      </svg>
    </div>
    <div>
      <div class="header-title">NKP Discovery Questions</div>
      <div class="header-sub">PT. Packet Systems Indonesia — Logicalis</div>
    </div>
  </div>
  <span class="header-badge">50 Questions · 10 Use Cases</span>
</header>

<main>
  <div class="intro">
    <h1>Nutanix Kubernetes Platform — Sales Discovery Guide</h1>
    <p>Qualifying and discovery questions mapped to NKP use cases and target personas. Use these to identify pain points, qualify opportunities, and align platform value to customer challenges across banking, government, and enterprise sectors.</p>
  </div>

  <div class="use-case-pills" id="ucPills"></div>

  <div class="controls">
    <div class="search-wrap">
      <svg viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.5">
        <circle cx="6.5" cy="6.5" r="4"/>
        <path d="M10 10l3 3"/>
      </svg>
      <input type="text" id="search" placeholder="Search questions or answers..." oninput="filter()">
    </div>
    <select id="personaFilter" onchange="filter()">
      <option value="">All personas</option>
      <option value="C-Level">C-Level</option>
      <option value="Infra & Ops">Infra &amp; Ops</option>
      <option value="Developer">Developer</option>
      <option value="System Architect">System Architect</option>
      <option value="DB Admin">DB Admin / Data Scientist</option>
      <option value="Business User">Business User</option>
    </select>
  </div>

  <div class="stats" id="stats">Showing 50 of 50 questions</div>

  <div class="tbl-wrap">
    <table>
      <colgroup>
        <col class="c0"><col class="c1"><col class="c2"><col class="c3"><col class="c4">
      </colgroup>
      <thead>
        <tr>
          <th>#</th>
          <th>Discovery question</th>
          <th>Possible answers</th>
          <th>Use case</th>
          <th>Target persona</th>
        </tr>
      </thead>
      <tbody id="tbody"></tbody>
    </table>
  </div>
</main>

<footer>
  Logicalis Indonesia · PT. Packet Systems Indonesia · NKP Presales Enablement · 2025
</footer>

<script>
const data = [
  {q:"Do you build applications in-house, outsource, or purchase off-the-shelf?",a:"In-house / Outsourced / Mixed / Purchased SaaS",uc:"Build & Deploy Secure App",ucClass:"u1",p:["System Architect","C-Level","Business User"]},
  {q:"Are your current applications monolithic or microservices-based?",a:"Monolithic / Mixed / Microservices / Serverless",uc:"Build & Deploy Secure App",ucClass:"u1",p:["System Architect","Developer"]},
  {q:"Are your workloads running on VMs, containers, or bare metal today?",a:"VMs only / Containers / Mixed / Bare metal",uc:"Build & Deploy Secure App",ucClass:"u1",p:["Infra & Ops","System Architect"]},
  {q:"Do you have a DevSecOps culture applied in your organization?",a:"Yes, fully / Partially / No / Planned",uc:"Build & Deploy Secure App",ucClass:"u1",p:["System Architect","Developer","C-Level"]},
  {q:"How do you enforce security policies across containerized workloads?",a:"Manual review / OPA / Kyverno / None",uc:"Build & Deploy Secure App",ucClass:"u1",p:["Infra & Ops","System Architect"]},
  {q:"How do you manage and scan container images for vulnerabilities before deployment?",a:"No scanning / Registry scanning / CI-integrated SAST / External tool",uc:"Build & Deploy Secure App",ucClass:"u1",p:["Developer","Infra & Ops"]},
  {q:"How do you control which teams can deploy to which environments and namespaces?",a:"No control / Manual approval / RBAC defined / Automated policy enforcement",uc:"Build & Deploy Secure App",ucClass:"u1",p:["System Architect","Infra & Ops"]},
  {q:"How do you currently monitor your Kubernetes workloads and cluster health?",a:"None / Prometheus+Grafana / 3rd-party APM / Cloud-native tooling",uc:"Infrastructure & App Observability",ucClass:"u2",p:["Infra & Ops","Developer"]},
  {q:"How do you aggregate and correlate logs across your distributed applications?",a:"None / ELK Stack / Splunk / Loki / Cloud logging",uc:"Infrastructure & App Observability",ucClass:"u2",p:["Infra & Ops","Developer"]},
  {q:"Do you have end-to-end distributed tracing across your microservices?",a:"Yes / No / Planned / Using Jaeger or Zipkin",uc:"Infrastructure & App Observability",ucClass:"u2",p:["Developer","System Architect"]},
  {q:"How do you detect and alert on application anomalies or SLA breaches in real time?",a:"No alerting / Manual checks / Alert rules / AIOps",uc:"Infrastructure & App Observability",ucClass:"u2",p:["Infra & Ops","Business User"]},
  {q:"How do you present application health and uptime data to business stakeholders?",a:"No reporting / Manual Excel / Dashboard / Automated SLA report",uc:"Infrastructure & App Observability",ucClass:"u2",p:["C-Level","Business User"]},
  {q:"How many teams need platform visibility, and how do you isolate their observability views?",a:"Single team / Multiple teams shared view / Per-team dashboards / None",uc:"Infrastructure & App Observability",ucClass:"u2",p:["Infra & Ops","System Architect"]},
  {q:"How many Kubernetes clusters do you currently manage or plan to operate?",a:"1 / 2–5 / 6–20 / 20+ clusters",uc:"Lifecycle & Fleet Management",ucClass:"u3",p:["Infra & Ops","System Architect"]},
  {q:"How do you upgrade Kubernetes versions across your cluster fleet today?",a:"Manual per-cluster / Automated pipeline / No process / Ad hoc",uc:"Lifecycle & Fleet Management",ucClass:"u3",p:["Infra & Ops"]},
  {q:"How do you ensure consistent node OS and Kubernetes configuration across all sites?",a:"Manual drift / GitOps / Config management tool / None",uc:"Lifecycle & Fleet Management",ucClass:"u3",p:["Infra & Ops","System Architect"]},
  {q:"How do you manage cluster provisioning and node scaling today?",a:"Manual / Cloud autoscaler / Custom scripting / None",uc:"Lifecycle & Fleet Management",ucClass:"u3",p:["Infra & Ops"]},
  {q:"Do you manage Kubernetes clusters across multiple clouds or on-premises sites?",a:"On-prem only / Single cloud / Hybrid / Multi-cloud",uc:"Lifecycle & Fleet Management",ucClass:"u3",p:["System Architect","C-Level","Infra & Ops"]},
  {q:"How do you audit and enforce compliance posture across your entire Kubernetes fleet?",a:"No audit / Manual quarterly / Automated scanning / Policy-as-code",uc:"Lifecycle & Fleet Management",ucClass:"u3",p:["Infra & Ops","C-Level"]},
  {q:"How many change requests or deployments occur per week across your applications?",a:"< 5 / 5–20 / 20–50 / 50+ per week",uc:"Software Development & Engineering",ucClass:"u4",p:["Developer","C-Level","System Architect"]},
  {q:"What CI/CD tools and pipelines are you currently using?",a:"Jenkins / GitLab CI / GitHub Actions / Azure DevOps / None",uc:"Software Development & Engineering",ucClass:"u4",p:["Developer","System Architect"]},
  {q:"How do you manage application secrets and sensitive configuration across environments?",a:"Hardcoded / ConfigMaps / HashiCorp Vault / Secret manager",uc:"Software Development & Engineering",ucClass:"u4",p:["Developer","Infra & Ops"]},
  {q:"How do you perform static (SAST) and dynamic (DAST) testing in your release process?",a:"No testing / Manual QA / SAST only / Full SAST+DAST in pipeline",uc:"Software Development & Engineering",ucClass:"u4",p:["Developer","System Architect"]},
  {q:"How do you package, version, and distribute application releases to target environments?",a:"Manual copy / Helm charts / Custom scripts / GitOps-based",uc:"Software Development & Engineering",ucClass:"u4",p:["Developer"]},
  {q:"How do you manage API versioning and ensure backward compatibility across services?",a:"No strategy / Manual versioning / API Gateway / Service mesh",uc:"Software Development & Engineering",ucClass:"u4",p:["Developer","System Architect"]},
  {q:"What types of databases are you currently running, and from which vendors?",a:"Oracle / MySQL / PostgreSQL / MongoDB / SQL Server / Mixed",uc:"DB Standardization & Automation",ucClass:"u5",p:["DB Admin","System Architect","C-Level"]},
  {q:"How do you provision new database instances for development or production workloads?",a:"Manual DBA request / Script-based / Cloud DBaaS / No standard process",uc:"DB Standardization & Automation",ucClass:"u5",p:["DB Admin","Developer"]},
  {q:"How do you enforce consistent database configuration and security standards across teams?",a:"No standard / Manual guidelines / Automated operator / Audited policies",uc:"DB Standardization & Automation",ucClass:"u5",p:["DB Admin","Infra & Ops"]},
  {q:"How do you manage database credentials, rotation, and access control across environments?",a:"Shared credentials / Manual rotation / Vault integration / No process",uc:"DB Standardization & Automation",ucClass:"u5",p:["DB Admin","Infra & Ops"]},
  {q:"Do you have or plan a Database-as-a-Service model for internal teams?",a:"No / Under consideration / Partially in place / Fully operational",uc:"DB Standardization & Automation",ucClass:"u5",p:["DB Admin","System Architect","C-Level"]},
  {q:"How do your applications perform during peak traffic or batch processing windows?",a:"Significantly degrades / Minor impact / Stable / Unpredictable",uc:"Performance Consistency",ucClass:"u6",p:["Infra & Ops","Business User","C-Level"]},
  {q:"How do you size and allocate compute resources to your workloads today?",a:"Static manual sizing / Fixed reservations / Dynamic / Overprovisioned",uc:"Performance Consistency",ucClass:"u6",p:["Infra & Ops","System Architect"]},
  {q:"Do you experience noisy neighbor issues in your shared infrastructure?",a:"Yes, frequently / Occasionally / Rarely / No isolation concerns",uc:"Performance Consistency",ucClass:"u6",p:["Infra & Ops","Developer"]},
  {q:"How do you guarantee and enforce SLAs for mission-critical workloads?",a:"No SLA / Best effort / SLA defined but not enforced / Automated SLO enforcement",uc:"Performance Consistency",ucClass:"u6",p:["C-Level","Business User","System Architect"]},
  {q:"Are your databases deployed as single instances or clustered for HA?",a:"Single instance / Active-passive / Active-active cluster / Unknown",uc:"DB Efficiency & Consolidation",ucClass:"u7",p:["DB Admin","System Architect"]},
  {q:"How do you consolidate underutilized database instances to reduce infrastructure cost?",a:"No consolidation effort / Ad hoc / Active consolidation program / Fully consolidated",uc:"DB Efficiency & Consolidation",ucClass:"u7",p:["DB Admin","C-Level"]},
  {q:"What is your database licensing cost model, and how does it scale with demand?",a:"Per-core commercial / Open source / Per-socket / Subscription / Unclear",uc:"DB Efficiency & Consolidation",ucClass:"u7",p:["C-Level","DB Admin"]},
  {q:"How long does it take to provision a new development or test environment from request to ready?",a:"Hours / Days / Weeks / No standard process",uc:"Dev/Test & CI/CD Acceleration",ucClass:"u8",p:["Developer","Business User","C-Level"]},
  {q:"How do developers request infrastructure resources for new projects today?",a:"Ticket to Ops / Direct provisioning / Self-service portal / No formal process",uc:"Dev/Test & CI/CD Acceleration",ucClass:"u8",p:["Developer","Infra & Ops"]},
  {q:"Do you have isolated and consistent environments for dev, test, staging, and production?",a:"No separation / Dev+Prod only / Dev/Test/Prod / Full 4-tier separation",uc:"Dev/Test & CI/CD Acceleration",ucClass:"u8",p:["Developer","System Architect"]},
  {q:"How do you promote application builds through environments from dev to production?",a:"Manual deploy / Script-based / GitOps pipeline / Fully automated CD",uc:"Dev/Test & CI/CD Acceleration",ucClass:"u8",p:["Developer","Infra & Ops"]},
  {q:"What are your current RTO and RPO targets for containerized and Kubernetes workloads?",a:"RTO >4h / RTO 1–4h / RTO <1h / No defined RTO/RPO",uc:"Disaster Ready, Resilience & Security",ucClass:"u9",p:["C-Level","System Architect","Infra & Ops"]},
  {q:"How do you currently back up and restore application state and persistent volumes in Kubernetes?",a:"No backup / Manual snapshot / Velero / CSI snapshot / 3rd-party",uc:"Disaster Ready, Resilience & Security",ucClass:"u9",p:["Infra & Ops","DB Admin"]},
  {q:"How do you detect and respond to security threats inside your running clusters?",a:"None / SIEM alerts / Runtime security tool (Falco) / Full SOAR",uc:"Disaster Ready, Resilience & Security",ucClass:"u9",p:["Infra & Ops","System Architect"]},
  {q:"How do you segment and isolate network traffic between workloads within your clusters?",a:"No segmentation / Firewall-level / Kubernetes NetworkPolicy / Service mesh mTLS",uc:"Disaster Ready, Resilience & Security",ucClass:"u9",p:["Infra & Ops","System Architect"]},
  {q:"Are there regulatory or compliance requirements applied to your workloads (OJK, BI, PCI-DSS, GDPR)?",a:"None applicable / Yes, partially addressed / Yes, fully addressed / Under assessment",uc:"Disaster Ready, Resilience & Security",ucClass:"u9",p:["C-Level","Business User","System Architect"]},
  {q:"Do you have a multi-site or multi-cluster disaster recovery strategy for Kubernetes today?",a:"No DR plan / Manual failover / Automated failover / Tested and documented DR",uc:"Disaster Ready, Resilience & Security",ucClass:"u9",p:["C-Level","Infra & Ops","System Architect"]},
  {q:"Are you running AI/ML workloads today, or actively planning to in the next 12 months?",a:"Running now / Planning within 12 months / Evaluating / No plans",uc:"AI & Data Driven Decision Support",ucClass:"u10",p:["C-Level","System Architect","DB Admin"]},
  {q:"How do you manage and share GPU resources for AI/ML training and inference workloads?",a:"Dedicated per-team / Time-sliced / No GPU / Cloud burst only",uc:"AI & Data Driven Decision Support",ucClass:"u10",p:["Infra & Ops","DB Admin"]},
  {q:"How do you store, version, and access training datasets and model artifacts for AI pipelines?",a:"Local disk / NFS / Object storage / MLflow / No standard",uc:"AI & Data Driven Decision Support",ucClass:"u10",p:["DB Admin","Developer"]},
  {q:"How do you measure and report the business ROI of your AI/ML investments to leadership?",a:"No measurement / Anecdotal / KPI-tracked dashboard / Formal ROI reporting",uc:"AI & Data Driven Decision Support",ucClass:"u10",p:["C-Level","Business User"]}
];

const ucList = [...new Set(data.map(d => d.uc))];
const ucClassMap = {};
data.forEach(d => { ucClassMap[d.uc] = d.ucClass; });

let activeUC = '';

function buildPills() {
  const wrap = document.getElementById('ucPills');
  const all = document.createElement('span');
  all.className = 'uc-pill active';
  all.style.cssText = 'background:#F1EFE8;color:#444441;border-color:var(--border2)';
  all.textContent = 'All';
  all.onclick = () => { activeUC = ''; setPillActive(all); filter(); };
  wrap.appendChild(all);

  ucList.forEach(uc => {
    const cl = ucClassMap[uc];
    const pill = document.createElement('span');
    pill.className = `uc-pill ${cl}`;
    pill.textContent = uc;
    pill.dataset.uc = uc;
    pill.onclick = () => { activeUC = uc; setPillActive(pill); filter(); };
    wrap.appendChild(pill);
  });
}

function setPillActive(el) {
  document.querySelectorAll('.uc-pill').forEach(p => p.classList.remove('active'));
  el.classList.add('active');
}

function filter() {
  const s = document.getElementById('search').value.toLowerCase();
  const persona = document.getElementById('personaFilter').value;
  const tbody = document.getElementById('tbody');
  tbody.innerHTML = '';

  const filtered = data.filter(d => {
    const matchS = !s || d.q.toLowerCase().includes(s) || d.a.toLowerCase().includes(s);
    const matchUC = !activeUC || d.uc === activeUC;
    const matchP = !persona || d.p.some(p => p.includes(persona));
    return matchS && matchUC && matchP;
  });

  if (!filtered.length) {
    tbody.innerHTML = `<tr><td colspan="5"><div class="no-results">No questions match your filters.</div></td></tr>`;
  } else {
    filtered.forEach((d, i) => {
      const tr = document.createElement('tr');
      tr.innerHTML = `
        <td><span class="num">${String(data.indexOf(d)+1).padStart(2,'0')}</span></td>
        <td><div class="q">${d.q}</div></td>
        <td><div class="ans">${d.a}</div></td>
        <td><span class="badge ${d.ucClass}">${d.uc}</span></td>
        <td><div class="persona-wrap">${d.p.map(p=>`<span class="p-tag">${p}</span>`).join('')}</div></td>
      `;
      tbody.appendChild(tr);
    });
  }

  document.getElementById('stats').textContent = `Showing ${filtered.length} of ${data.length} questions`;
}

buildPills();
filter();
</script>
</body>
</html>
