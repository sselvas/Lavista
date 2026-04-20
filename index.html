<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
<title>Ayuda para reportes La Vista</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Nunito:wght@400;700;800;900&display=swap');
  :root {
    --bg: #e5ddd5;
    --bubble-bot: #ffffff;
    --bubble-user: #dcf8c6;
    --text: #111827;
    --muted: #6b7280;
    --border: #d1d5db;
    --primary: #075e54;
    --primary-light: #128c7e;
    --danger: #e02424;
    --success: #057a55;
    --warning: #d97706;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; -webkit-tap-highlight-color: transparent; }
  html, body { height: 100%; overflow: hidden; }
  body {
    background: var(--bg);
    background-image: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none'%3E%3Cg fill='%23c4b5a5' fill-opacity='0.15'%3E%3Cpath d='M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
    font-family: 'Nunito', sans-serif;
    display: flex; flex-direction: column;
  }
  .header {
    background: var(--primary); color: white;
    padding: 12px 16px; display: flex; align-items: center; gap: 12px;
    flex-shrink: 0; box-shadow: 0 2px 6px rgba(0,0,0,0.25); z-index: 10; position: relative;
  }
  .avatar { width: 40px; height: 40px; background: var(--primary-light); border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 20px; flex-shrink: 0; }
  .header-info h1 { font-size: 15px; font-weight: 800; }
  .header-info p { font-size: 11px; opacity: 0.75; margin-top: 1px; }
  .progress-bar { position: absolute; bottom: 0; left: 0; right: 0; height: 3px; background: rgba(255,255,255,0.2); }
  .progress-fill { height: 3px; background: white; transition: width 0.5s ease; }
  .chat { flex: 1; overflow-y: auto; overflow-x: hidden; padding: 14px 12px; display: flex; flex-direction: column; gap: 4px; }
  .input-area { flex-shrink: 0; background: #d0c8be; border-top: 1px solid #b8b0a6; padding: 10px 12px 16px; min-height: 70px; max-height: 220px; overflow-y: auto; }
  .bubble-wrap { display: flex; align-items: flex-end; gap: 6px; animation: fadeUp 0.2s ease; }
  @keyframes fadeUp { from { opacity:0; transform:translateY(8px); } to { opacity:1; transform:translateY(0); } }
  .bubble-wrap.bot { justify-content: flex-start; }
  .bubble-wrap.user { justify-content: flex-end; }
  .bot-avatar { width: 26px; height: 26px; background: var(--primary); border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 13px; flex-shrink: 0; margin-bottom: 2px; }
  .bubble { max-width: 82%; padding: 9px 12px; border-radius: 16px; font-size: 14px; line-height: 1.5; box-shadow: 0 1px 2px rgba(0,0,0,0.1); word-break: break-word; }
  .bubble.bot { background: var(--bubble-bot); border-bottom-left-radius: 3px; color: var(--text); }
  .bubble.user { background: var(--bubble-user); border-bottom-right-radius: 3px; color: var(--text); }
  .bubble .time { font-size: 10px; color: var(--muted); text-align: right; margin-top: 4px; }
  .bubble strong { font-weight: 800; }
  .bubble.feedback-good { background: #dcf8c6; border: 2px solid var(--success); }
  .bubble.feedback-bad  { background: #fef3c7; border: 2px solid var(--warning); }
  .bubble.scenario { background: #f0f4ff; border: 2px solid #6366f1; }
  .scenario-label { font-size: 10px; font-weight: 800; text-transform: uppercase; letter-spacing: 1px; color: #6366f1; margin-bottom: 6px; }
  .typing-wrap { display: flex; align-items: flex-end; gap: 6px; }
  .typing-dots { background: white; border-radius: 16px; padding: 10px 14px; display: flex; gap: 4px; box-shadow: 0 1px 2px rgba(0,0,0,0.1); }
  .dot { width: 7px; height: 7px; background: #aaa; border-radius: 50%; animation: bounce 1.2s infinite; }
  .dot:nth-child(2) { animation-delay: 0.2s; }
  .dot:nth-child(3) { animation-delay: 0.4s; }
  @keyframes bounce { 0%,60%,100%{transform:translateY(0);} 30%{transform:translateY(-5px);} }
  .options-wrap { display: flex; flex-wrap: wrap; gap: 8px; }
  .opt { background: white; border: 2px solid var(--border); border-radius: 20px; padding: 9px 15px; font-family: 'Nunito', sans-serif; font-size: 14px; font-weight: 700; color: var(--text); cursor: pointer; box-shadow: 0 1px 3px rgba(0,0,0,0.08); }
  .opt:active { transform: scale(0.95); }
  .text-row { display: flex; gap: 8px; align-items: flex-end; }
  .text-row textarea { flex: 1; border: 2px solid var(--border); border-radius: 22px; padding: 10px 15px; font-family: 'Nunito', sans-serif; font-size: 15px; background: white; resize: none; outline: none; min-height: 44px; max-height: 130px; overflow-y: auto; line-height: 1.4; }
  .text-row textarea:focus { border-color: var(--primary); }
  .send-btn { width: 44px; height: 44px; flex-shrink: 0; background: var(--primary); border: none; border-radius: 50%; color: white; font-size: 18px; cursor: pointer; box-shadow: 0 2px 6px rgba(0,0,0,0.2); }
  .send-btn:active { opacity: 0.85; }
  .complete-card { background: white; border-radius: 14px; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,0.12); max-width: 88%; margin: 2px 0; }
  .complete-header { background: var(--success); padding: 14px; color: white; font-weight: 900; font-size: 16px; text-align: center; }
  .complete-body { padding: 16px; font-size: 14px; line-height: 1.7; color: var(--text); text-align: center; }
  .restart-btn { display: block; width: 100%; margin-top: 8px; background: white; color: var(--primary); border: 2px solid var(--primary); border-radius: 12px; padding: 11px; font-family: 'Nunito', sans-serif; font-size: 14px; font-weight: 800; cursor: pointer; max-width: 88%; }
</style>
</head>
<body>

<script>
const CONFIG = {
  nombrePropiedad: "La Vista",
  empleados: ["Fabián","Enrique","Abraham","Dulce","Jaqueline","Karla"],
  totalScenarios: 5,
  contexto: `
La Vista es una casa de renta vacacional con acceso al lago.
Estructuras: Casa principal, Casa del lago (también "casa de la playa"), Casa de visitas, Bungalow, área exterior.
Proveedores: Miguel (plomería, electricidad, aires), Anuar (backup Miguel), Antonio (carpintería), Ongay (plomería especializada).
Internet: Infinitum (principal) + Starlink (respaldo).
Jacuzzi temperatura normal: 35C. Aires acondicionados son lo más importante junto con el jacuzzi.
Dueño: Carlos Sebastian. Nunca toma decisiones por él.

Un reporte completo siempre incluye:
1. Quién reporta
2. Qué pasó exactamente (específico, no vago)
3. Dónde exactamente (estructura + área específica)
4. Cuándo ocurrió o fue notado
5. Quién estuvo involucrado
6. Si los huéspedes ya se quejaron o no (cuando aplica)
7. Qué ya intentaron hacer
8. Si hay foto o video (cuando es algo físico)
9. Qué necesitan de Carlos (solo informar / autorización de pago con monto / que tome una decisión)
`
};
</script>

<div class="header">
  <div class="avatar">📋</div>
  <div class="header-info">
    <h1>Ayuda para reportes La Vista</h1>
    <p id="status-text">Entrenamiento</p>
  </div>
  <div style="margin-left:auto;font-size:12px;font-weight:800;opacity:0.9" id="progress-text"></div>
  <div class="progress-bar"><div class="progress-fill" id="progress-fill" style="width:0%"></div></div>
</div>

<div class="chat" id="chat"></div>
<div class="input-area" id="input-area"></div>

<script>
const history = [];
let busy = false;
let scenarioCount = 0;

function now() { return new Date().toLocaleTimeString('es-MX',{hour:'2-digit',minute:'2-digit'}); }
function scrollBot() { requestAnimationFrame(()=>requestAnimationFrame(()=>{ const c=document.getElementById('chat'); c.scrollTop=c.scrollHeight; })); }
function setStatus(t) { document.getElementById('status-text').textContent=t; }
function clearInput() { document.getElementById('input-area').innerHTML=''; }

function updateProgress(n) {
  const pct = Math.round((n / CONFIG.totalScenarios) * 100);
  document.getElementById('progress-fill').style.width = pct + '%';
  document.getElementById('progress-text').textContent = n > 0 ? `${n}/${CONFIG.totalScenarios}` : '';
}

function botBubble(html, cls) {
  const c=document.getElementById('chat');
  const w=document.createElement('div'); w.className='bubble-wrap bot';
  const bubble = `<div class="bubble bot${cls?' '+cls:''}">${html.replace(/\n/g,'<br>')}<div class="time">${now()}</div></div>`;
  w.innerHTML=`<div class="bot-avatar">📋</div>${bubble}`;
  c.appendChild(w); scrollBot();
}

function userBubble(text) {
  const c=document.getElementById('chat');
  const w=document.createElement('div'); w.className='bubble-wrap user';
  w.innerHTML=`<div class="bubble user">${text}<div class="time">${now()}</div></div>`;
  c.appendChild(w); scrollBot();
}

function showDots() {
  const c=document.getElementById('chat');
  const t=document.createElement('div'); t.className='typing-wrap'; t.id='typing';
  t.innerHTML=`<div class="bot-avatar">📋</div><div class="typing-dots"><div class="dot"></div><div class="dot"></div><div class="dot"></div></div>`;
  c.appendChild(t); scrollBot();
}
function hideDots() { const t=document.getElementById('typing'); if(t) t.remove(); }

function renderOpts(opts) {
  clearInput();
  const a=document.getElementById('input-area');
  const w=document.createElement('div'); w.className='options-wrap';
  opts.forEach(o=>{
    const b=document.createElement('button'); b.className='opt'; b.textContent=o;
    b.onclick=()=>{ if(!busy) send(o); };
    w.appendChild(b);
  });
  a.appendChild(w); scrollBot();
}

function renderText(ph) {
  clearInput();
  const a=document.getElementById('input-area');
  const row=document.createElement('div'); row.className='text-row';
  const ta=document.createElement('textarea'); ta.placeholder=ph||'Escribe tu reporte aquí...';
  ta.oninput=()=>{ ta.style.height='auto'; ta.style.height=Math.min(ta.scrollHeight,130)+'px'; scrollBot(); };
  ta.onkeydown=e=>{ if(e.key==='Enter'&&!e.shiftKey){e.preventDefault();go();} };
  const btn=document.createElement('button'); btn.className='send-btn'; btn.innerHTML='➤';
  btn.onclick=go;
  function go(){ if(busy) return; const v=ta.value.trim(); if(!v) return; send(v); }
  row.appendChild(ta); row.appendChild(btn); a.appendChild(row);
  setTimeout(()=>ta.focus(),150); scrollBot();
}

async function send(val) {
  userBubble(val);
  clearInput();
  busy=true; setStatus('Revisando...');
  showDots();
  history.push({role:'user',content:val});

  try {
    const res=await fetch('/.netlify/functions/Claude',{
      method:'POST',
      headers:{'Content-Type':'application/json'},
      body:JSON.stringify({system:buildSystem(),messages:history})
    });
    const data=await res.json();
    const raw=data?.content?.[0]?.text||'';
    history.push({role:'assistant',content:raw});
    hideDots(); busy=false; setStatus('Entrenamiento');
    process(raw);
  } catch(e) {
    hideDots(); busy=false; setStatus('Entrenamiento');
    botBubble('Error de conexión. Intenta de nuevo.');
    renderOpts(['Reintentar']);
  }
}

function process(raw) {
  const clean = raw.replace(/^```json\s*/,'').replace(/^```\s*/,'').replace(/```\s*$/,'').trim();
  let p;
  try { p=JSON.parse(clean); }
  catch(e) {
    botBubble(raw.trim());
    renderText('Escribe aquí...');
    return;
  }

  if (p.type === 'scenario') {
    scenarioCount++;
    updateProgress(scenarioCount - 1);
    // Scenario bubble with special style
    const c=document.getElementById('chat');
    const w=document.createElement('div'); w.className='bubble-wrap bot';
    w.innerHTML=`<div class="bot-avatar">📋</div><div class="bubble bot scenario"><div class="scenario-label">📍 Escenario ${scenarioCount} de ${CONFIG.totalScenarios}</div>${p.text.replace(/\n/g,'<br>')}<div class="time">${now()}</div></div>`;
    c.appendChild(w); scrollBot();
    renderText('Escribe tu reporte aquí...');

  } else if (p.type === 'feedback') {
    const cls = p.passed ? 'feedback-good' : 'feedback-bad';
    botBubble((p.passed ? '✅ ' : '⚠️ ') + p.text, cls);
    if (p.passed) {
      setTimeout(()=>{ renderOpts(['Siguiente escenario →']); },400);
    } else {
      renderText('Inténtalo de nuevo...');
    }

  } else if (p.type === 'message') {
    botBubble(p.text);
    if (p.options) renderOpts(p.options);
    else renderText(p.placeholder || 'Escribe aquí...');

  } else if (p.type === 'complete') {
    updateProgress(CONFIG.totalScenarios);
    showComplete(p.text);

  } else {
    botBubble(raw.trim());
    renderText('Escribe aquí...');
  }
}

function showComplete(msg) {
  clearInput();
  const chat=document.getElementById('chat');
  const w=document.createElement('div'); w.className='bubble-wrap bot';
  const inner=document.createElement('div'); inner.style.maxWidth='88%';
  const card=document.createElement('div'); card.className='complete-card';
  card.innerHTML=`<div class="complete-header">🎉 Entrenamiento completado</div><div class="complete-body">${(msg||'Completaste todos los escenarios. Ya sabes cómo hacer un reporte completo.').replace(/\n/g,'<br>')}</div>`;
  inner.appendChild(card);
  const rb=document.createElement('button'); rb.className='restart-btn'; rb.textContent='Volver a practicar';
  rb.onclick=resetAll; inner.appendChild(rb);
  w.innerHTML='<div class="bot-avatar">📋</div>'; w.appendChild(inner);
  chat.appendChild(w); scrollBot();
}

function resetAll() {
  history.length=0; scenarioCount=0;
  document.getElementById('chat').innerHTML='';
  clearInput(); updateProgress(0);
  init();
}

function buildSystem() {
  return `Eres un entrenador que enseña a los empleados de "${CONFIG.nombrePropiedad}" cómo hacer reportes completos para el dueño Carlos Sebastian.

CONTEXTO DE LA PROPIEDAD Y QUÉ ES UN REPORTE COMPLETO:
${CONFIG.contexto}

TU TRABAJO:
Presentar exactamente ${CONFIG.totalScenarios} escenarios reales uno por uno. El empleado escribe el reporte como si lo mandara por WhatsApp. Tú lo evalúas y le dices qué faltó o qué estuvo mal. Si falta información, el empleado lo intenta de nuevo hasta que el reporte quede completo. Cuando pasa, avanzas al siguiente escenario.

ESCENARIOS QUE DEBES USAR (en este orden):
1. El aire acondicionado de la recámara 3 de la casa principal no enfría. Hay huéspedes adentro que ya se quejaron.
2. Llegaron 6 personas más de las que estaban en la reserva. Son las 8pm y los huéspedes ya están adentro.
3. Se fue la luz solo en La Vista, los vecinos sí tienen luz. Hay huéspedes adentro.
4. Miguel vino a arreglar una fuga en la cocina, dijo que quedó pero no cobró todavía. Ya se fue.
5. Dulce encontró un vaso roto en la alberca al limpiar después de que se fueron los huéspedes. No hay nadie en la casa.

REGLAS:
- Responde SIEMPRE en JSON válido. Sin texto libre. Sin markdown.
- Un solo paso a la vez.
- Al evaluar un reporte: sé directo. Di exactamente qué faltó y por qué importa. No des el reporte correcto tú — haz que el empleado lo escriba bien.
- Si el reporte tiene todo lo necesario, márcalo como pasado.
- Después de los ${CONFIG.totalScenarios} escenarios genera el mensaje de completado.

FORMATO JSON:

Presentar escenario:
{"type":"scenario","text":"Descripción del escenario en segunda persona, como si le estuviera pasando a ellos ahora mismo. Termina con: Escribe el reporte como lo mandarías por WhatsApp."}

Feedback — reporte incompleto:
{"type":"feedback","passed":false,"text":"Qué faltó específicamente y por qué importa ese dato. Máximo 3 líneas. Sin listar todo lo que falta, solo lo más importante que falta."}

Feedback — reporte aprobado:
{"type":"feedback","passed":true,"text":"Qué estuvo bien. Una sola línea positiva y concreta."}

Mensaje general (bienvenida, transición):
{"type":"message","text":"texto","options":["op1"]}

Entrenamiento completado (después del escenario ${CONFIG.totalScenarios}):
{"type":"complete","text":"Mensaje de cierre. Breve. Menciona que ya saben lo que Carlos necesita para poder actuar."}`;
}

async function init() {
  setStatus('Entrenamiento');
  busy=true; showDots();
  history.push({role:'user',content:'Hola, soy un empleado nuevo de La Vista.'});
  try {
    const res=await fetch('/.netlify/functions/Claude',{
      method:'POST',
      headers:{'Content-Type':'application/json'},
      body:JSON.stringify({system:buildSystem(),messages:history})
    });
    const data=await res.json();
    const raw=data?.content?.[0]?.text||'';
    history.push({role:'assistant',content:raw});
    hideDots(); busy=false;
    process(raw);
  } catch(e) {
    hideDots(); busy=false;
    botBubble('Error de conexión.');
  }
}

init();
</script>
</body>
</html>
