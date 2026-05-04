<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>C Spire Procurement Guide</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700&display=swap');

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --primary: #006B8F;
    --primary-light: #008DB8;
    --cyan: #00B4D8;
    --cyan-pale: #E8F8FC;
    --cyan-mid: #B3E8F4;
    --teal: #0D9488;
    --dark: #0C1825;
    --text: #1E2D3D;
    --text-mid: #4A5E6D;
    --text-light: #7A8FA0;
    --border: #E0E9EF;
    --bg: #F4F8FB;
    --white: #FFFFFF;
    --green: #059669;
    --amber: #D97706;
    --red: #DC2626;
    --purple: #7C3AED;
    --font: 'Plus Jakarta Sans', system-ui, sans-serif;
  }

  html, body { height: 100%; font-family: var(--font); background: var(--bg); color: var(--text); }

  /* TOP HEADER */
  .header {
    background: var(--white);
    border-bottom: 1px solid var(--border);
    padding: 0 32px;
    height: 60px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 100;
  }

  .header-left { display: flex; align-items: center; gap: 12px; }

  .cspire-logo {
    height: 28px;
    display: flex;
    align-items: center;
    gap: 8px;
  }

  .logo-mark {
    width: 28px; height: 28px;
    background: var(--cyan);
    border-radius: 6px;
    display: flex; align-items: center; justify-content: center;
  }
  .logo-mark svg { width: 16px; height: 16px; }

  .logo-name { font-size: 16px; font-weight: 700; color: var(--dark); letter-spacing: -0.02em; }
  .header-divider { width: 1px; height: 20px; background: var(--border); }
  .header-title { font-size: 14px; font-weight: 500; color: var(--text-mid); }

  .header-right { display: flex; align-items: center; gap: 16px; }

  .policy-badge {
    font-size: 11px;
    background: var(--cyan-pale);
    color: var(--primary);
    padding: 4px 12px;
    border-radius: 20px;
    font-weight: 600;
    border: 1px solid var(--cyan-mid);
  }

  /* LAYOUT */
  .layout {
    margin-top: 60px;
    min-height: calc(100vh - 60px);
    display: flex;
    flex-direction: column;
  }

  /* WELCOME STATE */
  .welcome-state {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 48px 24px;
    max-width: 780px;
    margin: 0 auto;
    width: 100%;
  }

  .welcome-eyebrow {
    font-size: 11px;
    font-weight: 700;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--cyan);
    margin-bottom: 12px;
  }

  .welcome-h { font-size: 30px; font-weight: 700; color: var(--dark); text-align: center; line-height: 1.2; letter-spacing: -0.03em; margin-bottom: 12px; }
  .welcome-sub { font-size: 15px; color: var(--text-mid); text-align: center; line-height: 1.6; max-width: 520px; margin-bottom: 40px; }

  /* TOPIC CARDS */
  .topics-label { font-size: 12px; font-weight: 600; text-transform: uppercase; letter-spacing: 0.06em; color: var(--text-light); margin-bottom: 14px; align-self: flex-start; }

  .topics-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
    width: 100%;
    margin-bottom: 32px;
  }

  .topic-card {
    background: var(--white);
    border: 1.5px solid var(--border);
    border-radius: 14px;
    padding: 18px;
    cursor: pointer;
    transition: all 0.18s ease;
    text-align: left;
    position: relative;
    overflow: hidden;
  }

  .topic-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 3px;
    border-radius: 14px 14px 0 0;
    opacity: 0;
    transition: opacity 0.18s;
  }

  .topic-card:hover {
    border-color: var(--cyan);
    transform: translateY(-2px);
    box-shadow: 0 8px 24px rgba(0,180,216,0.12);
  }
  .topic-card:hover::before { opacity: 1; }
  .topic-card:active { transform: translateY(0); }

  .tc-1::before { background: var(--cyan); }
  .tc-2::before { background: var(--green); }
  .tc-3::before { background: var(--purple); }
  .tc-4::before { background: var(--amber); }
  .tc-5::before { background: var(--red); }
  .tc-6::before { background: var(--teal); }

  .tc-emoji { font-size: 22px; margin-bottom: 10px; display: block; }
  .tc-title { font-size: 13px; font-weight: 700; color: var(--dark); display: block; margin-bottom: 5px; }
  .tc-desc { font-size: 12px; color: var(--text-mid); line-height: 1.5; display: block; }

  /* QUICK ASKS */
  .quick-asks-label { font-size: 12px; font-weight: 600; text-transform: uppercase; letter-spacing: 0.06em; color: var(--text-light); margin-bottom: 10px; align-self: flex-start; }

  .quick-asks {
    display: flex; flex-wrap: wrap; gap: 8px;
    width: 100%;
  }

  .qa-btn {
    background: var(--white);
    border: 1.5px solid var(--border);
    border-radius: 24px;
    padding: 8px 16px;
    font-size: 12.5px;
    font-weight: 500;
    color: var(--text);
    cursor: pointer;
    transition: all 0.15s;
    font-family: var(--font);
  }
  .qa-btn:hover { background: var(--cyan-pale); border-color: var(--cyan); color: var(--primary); }

  /* CHAT STATE */
  .chat-state {
    display: none;
    flex: 1;
    flex-direction: column;
    max-width: 740px;
    margin: 0 auto;
    width: 100%;
    padding: 0 24px;
  }

  .chat-messages {
    flex: 1;
    padding: 28px 0;
    overflow-y: auto;
    scroll-behavior: smooth;
  }

  .chat-messages::-webkit-scrollbar { width: 4px; }
  .chat-messages::-webkit-scrollbar-thumb { background: var(--border); border-radius: 4px; }

  .new-topic-bar {
    display: flex;
    align-items: center;
    gap: 12px;
    padding: 12px 0;
    margin-bottom: 16px;
  }
  .ntb-line { flex: 1; height: 1px; background: var(--border); }
  .ntb-btn {
    font-size: 11px; font-weight: 600;
    color: var(--primary);
    background: var(--cyan-pale);
    border: 1px solid var(--cyan-mid);
    border-radius: 20px;
    padding: 5px 14px;
    cursor: pointer;
    transition: all 0.15s;
    font-family: var(--font);
  }
  .ntb-btn:hover { background: var(--cyan); color: var(--white); border-color: var(--cyan); }

  /* MESSAGES */
  .msg-group { margin-bottom: 24px; }

  .msg-row { display: flex; gap: 12px; margin-bottom: 8px; }
  .msg-row.user { flex-direction: row-reverse; }

  .avatar {
    width: 34px; height: 34px; border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    font-size: 11px; font-weight: 700;
    flex-shrink: 0;
    margin-top: 4px;
  }
  .avatar.bot { background: var(--cyan-pale); color: var(--primary); border: 2px solid var(--cyan-mid); }
  .avatar.me { background: var(--primary); color: var(--white); }

  .bubble {
    max-width: 75%;
    padding: 14px 18px;
    border-radius: 18px;
    font-size: 14px;
    line-height: 1.65;
  }

  .msg-row.bot .bubble {
    background: var(--white);
    border: 1.5px solid var(--border);
    border-top-left-radius: 4px;
    color: var(--text);
  }

  .msg-row.user .bubble {
    background: var(--primary);
    color: var(--white);
    border-top-right-radius: 4px;
  }

  .bubble strong { font-weight: 700; }
  .bubble ul, .bubble ol { padding-left: 18px; margin: 8px 0; }
  .bubble li { margin-bottom: 5px; }
  .bubble h4 { font-size: 14px; font-weight: 700; margin-bottom: 8px; color: var(--primary); }
  .bubble p + p { margin-top: 8px; }

  .bot-label {
    font-size: 11px;
    color: var(--text-light);
    margin-left: 46px;
    margin-top: -4px;
    margin-bottom: 4px;
  }

  .follow-ups {
    margin-left: 46px;
    margin-top: 8px;
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
  }

  .fup {
    font-size: 12px;
    background: var(--cyan-pale);
    color: var(--primary);
    border: 1px solid var(--cyan-mid);
    border-radius: 20px;
    padding: 5px 13px;
    cursor: pointer;
    font-weight: 500;
    transition: all 0.15s;
    font-family: var(--font);
  }
  .fup:hover { background: var(--cyan); color: var(--white); border-color: var(--cyan); }

  .typing-row { display: flex; gap: 12px; align-items: flex-start; }
  .typing-bubble {
    background: var(--white);
    border: 1.5px solid var(--border);
    border-radius: 18px;
    border-top-left-radius: 4px;
    padding: 14px 18px;
    display: flex; gap: 4px; align-items: center;
  }
  .td { width: 7px; height: 7px; border-radius: 50%; background: var(--text-light); animation: td 1.2s infinite; }
  .td:nth-child(2) { animation-delay: 0.2s; }
  .td:nth-child(3) { animation-delay: 0.4s; }
  @keyframes td { 0%,60%,100%{transform:translateY(0);opacity:0.4;} 30%{transform:translateY(-4px);opacity:1;} }

  /* BOTTOM INPUT */
  .input-section {
    background: var(--white);
    border-top: 1px solid var(--border);
    padding: 16px 24px 20px;
    position: sticky;
    bottom: 0;
  }

  .input-inner {
    max-width: 740px;
    margin: 0 auto;
  }

  .input-box {
    display: flex;
    align-items: flex-end;
    gap: 10px;
    background: var(--bg);
    border: 1.5px solid var(--border);
    border-radius: 16px;
    padding: 10px 12px;
    transition: border-color 0.15s;
  }

  .input-box:focus-within {
    border-color: var(--cyan);
    box-shadow: 0 0 0 3px rgba(0,180,216,0.1);
  }

  .input-box textarea {
    flex: 1;
    background: transparent;
    border: none;
    outline: none;
    font-family: var(--font);
    font-size: 14px;
    color: var(--text);
    resize: none;
    max-height: 120px;
    line-height: 1.5;
    padding: 2px 0;
  }
  .input-box textarea::placeholder { color: var(--text-light); }

  .send-btn {
    width: 38px; height: 38px;
    background: var(--primary);
    border: none; border-radius: 10px;
    cursor: pointer;
    display: flex; align-items: center; justify-content: center;
    transition: background 0.15s, transform 0.1s;
    flex-shrink: 0;
  }
  .send-btn:hover { background: var(--cyan); }
  .send-btn:active { transform: scale(0.94); }
  .send-btn:disabled { opacity: 0.4; cursor: not-allowed; transform: none; }
  .send-btn svg { width: 16px; height: 16px; fill: var(--white); }

  .input-footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 8px;
  }

  .shortcut-hint { font-size: 11px; color: var(--text-light); }
  .input-disclaimer { font-size: 10px; color: var(--text-light); }

  @media(max-width:640px){
    .topics-grid { grid-template-columns:1fr 1fr; }
    .header-title, .header-divider, .policy-badge { display:none; }
    .welcome-h { font-size: 22px; }
    .chat-state, .welcome-state { padding: 0 12px; }
  }
</style>
</head>
<body>

<header class="header">
  <div class="header-left">
    <div class="cspire-logo">
      <div class="logo-mark">
        <svg viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2.5" stroke-linecap="round">
          <path d="M12 2L2 7l10 5 10-5-10-5z"/><path d="M2 17l10 5 10-5"/><path d="M2 12l10 5 10-5"/>
        </svg>
      </div>
      <span class="logo-name">C Spire</span>
    </div>
    <div class="header-divider"></div>
    <span class="header-title">Procurement Assistant</span>
  </div>
  <div class="header-right">
    <span class="policy-badge">Policy effective May 1, 2026</span>
  </div>
</header>

<div class="layout" id="layout">

  <!-- WELCOME -->
  <div class="welcome-state" id="welcomeState">
    <div class="welcome-eyebrow">Procurement Policy Guide</div>
    <h1 class="welcome-h">How can I help you today?</h1>
    <p class="welcome-sub">Ask me anything about C Spire's procurement rules, purchase approvals, vendor setup, spend authority, and more. Plain answers, fast.</p>

    <div class="topics-label">Browse by topic</div>
    <div class="topics-grid">
      <div class="topic-card tc-1" onclick="fire('What approvals do I need and who can sign off at each dollar level?')">
        <span class="tc-emoji">✅</span>
        <span class="tc-title">Approval Authority</span>
        <span class="tc-desc">Who can approve what at each spend level</span>
      </div>
      <div class="topic-card tc-2" onclick="fire('Walk me through how to create a Purchase Requisition in Oracle Fusion step by step')">
        <span class="tc-emoji">🖥️</span>
        <span class="tc-title">Create a PR in Oracle</span>
        <span class="tc-desc">Step-by-step guide to submitting a requisition</span>
      </div>
      <div class="topic-card tc-3" onclick="fire('How do I set up a new vendor at C Spire and what documents do they need?')">
        <span class="tc-emoji">🏢</span>
        <span class="tc-title">New Vendor Setup</span>
        <span class="tc-desc">Documents required and who to contact</span>
      </div>
      <div class="topic-card tc-4" onclick="fire('Explain the 5 spend bands — what each one means and what I need to do')">
        <span class="tc-emoji">💰</span>
        <span class="tc-title">Spend Bands & Thresholds</span>
        <span class="tc-desc">Band 0–4 and what documentation each requires</span>
      </div>
      <div class="topic-card tc-5" onclick="fire('When do I need a contract versus just a purchase order?')">
        <span class="tc-emoji">📝</span>
        <span class="tc-title">Contract vs. PO</span>
        <span class="tc-desc">When a contract is required, not just a PO</span>
      </div>
      <div class="topic-card tc-6" onclick="fire('What are the No PO No Pay rules and what happens if I get an invoice without a PO?')">
        <span class="tc-emoji">🚫</span>
        <span class="tc-title">No PO, No Pay</span>
        <span class="tc-desc">Invoice and payment compliance rules</span>
      </div>
    </div>

    <div class="quick-asks-label">Quick questions</div>
    <div class="quick-asks">
      <button class="qa-btn" onclick="fire('Can a supplier start work before I have a PO in place?')">Can a supplier start before I have a PO?</button>
      <button class="qa-btn" onclick="fire('I need to make an emergency purchase. What is the process?')">How do emergency purchases work?</button>
      <button class="qa-btn" onclick="fire('What are the rules for purchasing IT software or SaaS tools?')">Buying IT software or SaaS</button>
      <button class="qa-btn" onclick="fire('Can I split a purchase into smaller orders to avoid approval thresholds?')">Can I split purchases?</button>
      <button class="qa-btn" onclick="fire('How do I submit an invoice to C Spire?')">How to submit an invoice</button>
      <button class="qa-btn" onclick="fire('What is a P-Card and when can I use it?')">When can I use a P-Card?</button>
      <button class="qa-btn" onclick="fire('Who do I contact if I have procurement questions?')">Who do I contact?</button>
    </div>
  </div>

  <!-- CHAT -->
  <div class="chat-state" id="chatState">
    <div class="chat-messages" id="chatMessages"></div>
  </div>

</div>

<!-- INPUT (always visible) -->
<div class="input-section">
  <div class="input-inner">
    <div class="input-box">
      <textarea
        id="inp"
        placeholder="Ask about procurement rules, approvals, vendor setup, POs..."
        rows="1"
        onkeydown="handleKey(event)"
        oninput="grow(this)"
      ></textarea>
      <button class="send-btn" id="sendBtn" onclick="send()">
        <svg viewBox="0 0 24 24"><path d="M22 2L11 13M22 2L15 22L11 13L2 9L22 2Z"/></svg>
      </button>
    </div>
    <div class="input-footer">
      <span class="shortcut-hint">↵ to send &nbsp;·&nbsp; Shift+↵ for new line</span>
      <span class="input-disclaimer">Based on C Spire policies effective May 1, 2026</span>
    </div>
  </div>
</div>

<script>
const SYS = `You are a friendly, knowledgeable C Spire Procurement Assistant helping managers navigate procurement rules. You have thorough knowledge of:

1. C Spire PROCUREMENT POLICY (effective May 1, 2026):
FIVE SPEND BANDS (based on TOTAL commitment value):
- Band 0: <$5K → P-Card/low-touch PO, no formal competition needed
- Band 1: $5K–$30K → 1+ written quote, self-serve
- Band 2: $30K–$100K → 2-3 competitive quotes or structured RFQ
- Band 3: $100K–$500K → Formal RFP, Procurement co-leads, Legal reviews
- Band 4: >$500K → Procurement leads, strategic sourcing, executive sponsors

BUYING CHANNELS: Catalog/Preferred PO → Non-Catalog PO → P-Card → Contract+SOW+PO → Direct Pay (very limited)

NON-NEGOTIABLE RULES:
- No work without an approved PO (and contract where required) — exceptions only via formal emergency process
- No PO splitting to avoid thresholds (policy violation)
- No verbal or email approvals — must be in Oracle Fusion or Chrome River
- No self-approval of your own requisitions
- Competitive bidding required for Bands 2-4 (unless sole-source exception approved)
- No accepting supplier terms by email/on a quote — route to Procurement
- Retroactive POs only via approved exception

WHEN YOU NEED A CONTRACT (not just PO): Services, SaaS/software, recurring subscriptions, confidential data, supplier terms beyond a quote.

EMERGENCY PURCHASES: Only for immediate risk to life/health/safety or major service outage. Notify Procurement ASAP, document within 24-48 hours.

2. CORPORATE AUTHORIZATION POLICY (CAP, effective May 1, 2026):
APPROVAL LEVELS (all operating costs general):
- Manager: up to $10K
- Sr Manager/Director: up to $50K
- Sr Director/VP: up to $100K
- SVP: up to $500K
- BU EVP or Officer (COO/CFO/COO/CMO/CHRO): up to $5M
- CFO: up to $10M
- CEO: over $10M

IT SPEND (Hardware/Software/Maintenance):
- Manager: up to $10K
- Sr Mgr/Director: up to $50K
- Sr Director/VP: up to $100K
- CIO: up to $500K
- COO or BU EVP: up to $5M
- CEO or CFO: over $10M
PLUS: ALL IT/software/AI agreements require CISO approval before execution.

OTHER SPECIAL RULES:
- Authority is based on TOTAL financial commitment, not annual spend
- For contracts with opt-out ≤91 days, authority based on shorter period (e.g., 90-day notice period)
- Related party contracts: must get CEO or CFO pre-approval before even bidding
- Customer data agreements: Deputy General Counsel for Privacy must approve
- Real estate: Sr Director/VP and up

"Manager" definition: only non-sales roles where "Manager" PRECEDES the function (e.g., "Manager, Network Field Operations"). "FP&A Manager" or "Operations Manager" do NOT count. Team Leaders, Supervisors, and Assistant Managers have no approval authority.

3. VENDOR SETUP POLICY:
- Domestic: W-9 required before services start and before any payment
- Foreign: W-8BEN-E required, renewed every 3 years
- New W-9 also required for: name change, address change, entity change, or vendor inactive >2 years
- Contact: vendoradmin@cspire.com or Benjamin Quinn (601-707-3387)

INVOICE SUBMISSION (PDF attachments by email, match entity to PO entity):
- Cellular South Inc → invoices@cspire.com
- Telepak Networks/C Spire Fiber → csfiberinvoices@cspire.com
- Troy Cablevision → troyinvoices@cspire.com
- TekLinks → teklinksinvoices@cspire.com
- Harbor Communications → harborinvoices@cspire.com
- AP questions: accountspayable@cspire.com

PAYMENT OPTIONS: PNC Visa Virtual Card (preferred), Paymode-X, or Check. Net 30 days from invoice receipt.

4. ORACLE FUSION PR STEPS:
1. Log in → Procurement → Purchase Requisitions (New)
2. Update Preferences if first time (set Delivery-to Location, keep Destination Type = Expense)
3. Create Noncatalog Request
4. Enter detailed Item Description (include service period, key details)
5. Select Item Type: Goods-Billed by Qty / Services-Billed by Qty / Services-Billed by Amount
6. Choose Category (type keywords like "software")
7. Enter Quantity + UOM (Each) + Price per unit, OR just total Amount for services-by-amount
8. Select Supplier (type 3+ characters, select from list, do NOT check New Supplier)
9. Click Add to Cart
10. Repeat steps 4-9 for additional items
11. View Cart → Edit Requisition Summary (add Description + Justification/email for returns)
12. If project-tied: fill Project Costing section (Project#, Task#, Expenditure info)
13. Edit Charge Account → Search for Combination → verify all GL values → Apply
14. Add Attachments (vendor quotes, contracts, justification — REQUIRED for approval)
15. Click Update → then Submit

5. KEY CONTACTS:
- Vendor setup/changes: vendoradmin@cspire.com (Benjamin Quinn)
- AP/invoices: accountspayable@cspire.com
- Procurement guidance: Procurement department
- Policy questions: Controller or CFO

RESPONSE STYLE:
- Friendly, plain-language, like a knowledgeable colleague
- Concise but complete — don't over-qualify
- Use numbered steps for processes, bullets for lists
- For spending questions: always identify the spend band and tell them what's required
- For approval questions: give them the specific approval level needed
- End with a clear next step or offer to dig deeper
- If it's a gray area, say so and recommend they contact Procurement
`;

let history = [];
let busy = false;

function grow(el) {
  el.style.height = 'auto';
  el.style.height = Math.min(el.scrollHeight, 120) + 'px';
}

function handleKey(e) {
  if (e.key === 'Enter' && !e.shiftKey) { e.preventDefault(); send(); }
}

function fire(q) {
  document.getElementById('inp').value = q;
  send();
}

async function send() {
  if (busy) return;
  const inp = document.getElementById('inp');
  const q = inp.value.trim();
  if (!q) return;

  showChat();
  addUserMsg(q);
  history.push({ role: 'user', content: q });
  inp.value = ''; inp.style.height = 'auto';

  busy = true;
  document.getElementById('sendBtn').disabled = true;
  addTyping();

  try {
    const res = await fetch('https://api.anthropic.com/v1/messages', {
      method: 'POST',
      headers: { 'Content-Type': 'application/json' },
      body: JSON.stringify({
        model: 'claude-sonnet-4-20250514',
        max_tokens: 1000,
        system: SYS,
        messages: history
      })
    });
    const d = await res.json();
    const reply = d.content[0].text;
    history.push({ role: 'assistant', content: reply });
    removeTyping();
    addBotMsg(reply, q);
  } catch {
    removeTyping();
    addBotMsg("I'm having trouble connecting right now. Please try again shortly, or contact Procurement for help.", q);
  }

  busy = false;
  document.getElementById('sendBtn').disabled = false;
}

function showChat() {
  document.getElementById('welcomeState').style.display = 'none';
  const cs = document.getElementById('chatState');
  cs.style.display = 'flex';
}

function addUserMsg(text) {
  const m = document.getElementById('chatMessages');
  const d = document.createElement('div');
  d.className = 'msg-row user';
  d.innerHTML = `<div class="avatar me">ME</div><div class="bubble">${esc(text)}</div>`;
  m.appendChild(d);
  scroll();
}

function addBotMsg(text, userQ) {
  const m = document.getElementById('chatMessages');
  const d = document.createElement('div');

  const followUps = getFollowUps(userQ, text);

  d.innerHTML = `
    <div class="msg-row bot">
      <div class="avatar bot">AI</div>
      <div class="bubble">${fmt(text)}</div>
    </div>
    ${followUps.length ? `<div class="follow-ups">${followUps.map(f => `<button class="fup" onclick="fire('${esc(f)}')">${esc(f)}</button>`).join('')}</div>` : ''}
  `;
  m.appendChild(d);
  
  if (history.length > 4) {
    const bar = document.createElement('div');
    bar.className = 'new-topic-bar';
    bar.innerHTML = `<div class="ntb-line"></div><button class="ntb-btn" onclick="newTopic()">+ New topic</button><div class="ntb-line"></div>`;
    // only add occasionally
  }
  
  scroll();
}

function getFollowUps(q, answer) {
  const ql = q.toLowerCase();
  if (ql.includes('approval') || ql.includes('approve') || ql.includes('authority')) {
    return ['How do I submit a PR in Oracle?', 'What if I\'m over my authority level?'];
  }
  if (ql.includes('vendor') || ql.includes('supplier')) {
    return ['What forms does a new vendor need?', 'How do I submit an invoice?'];
  }
  if (ql.includes('pr') || ql.includes('requisition') || ql.includes('oracle')) {
    return ['What attachments are required?', 'How do I code the charge account?'];
  }
  if (ql.includes('band') || ql.includes('spend') || ql.includes('threshold')) {
    return ['Do I need a contract or just a PO?', 'What approvals are required?'];
  }
  if (ql.includes('emergency') || ql.includes('urgent')) {
    return ['Who do I contact for emergencies?', 'How do I document an emergency purchase?'];
  }
  return [];
}

function newTopic() {
  history = [];
  document.getElementById('chatMessages').innerHTML = '';
  document.getElementById('welcomeState').style.display = 'flex';
  document.getElementById('chatState').style.display = 'none';
}

let typingEl = null;
function addTyping() {
  const m = document.getElementById('chatMessages');
  typingEl = document.createElement('div');
  typingEl.id = 'typ';
  typingEl.innerHTML = `
    <div class="typing-row">
      <div class="avatar bot">AI</div>
      <div class="typing-bubble">
        <div class="td"></div><div class="td"></div><div class="td"></div>
      </div>
    </div>`;
  m.appendChild(typingEl);
  scroll();
}

function removeTyping() {
  const t = document.getElementById('typ');
  if (t) t.remove();
}

function fmt(text) {
  return text
    .replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;')
    .replace(/\*\*(.*?)\*\*/g,'<strong>$1</strong>')
    .replace(/^### (.+)$/gm,'<h4>$1</h4>')
    .replace(/^## (.+)$/gm,'<h4>$1</h4>')
    .replace(/^# (.+)$/gm,'<h4>$1</h4>')
    .replace(/^\- (.+)$/gm,'<li>$1</li>')
    .replace(/^(\d+)\. (.+)$/gm,'<li>$2</li>')
    .replace(/(<li>[\s\S]*?<\/li>\n?)+/g, m => `<ul>${m}</ul>`)
    .replace(/\n\n/g,'</p><p>')
    .replace(/\n/g,'<br>');
}

function esc(t) { return t.replace(/'/g,"\\'").replace(/"/g,'&quot;'); }
function scroll() {
  const m = document.getElementById('chatMessages');
  setTimeout(() => m.scrollTop = m.scrollHeight, 50);
}
</script>
</body>
</html>
