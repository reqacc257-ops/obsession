
<style>
* { margin:0; padding:0; box-sizing:border-box; }

#app {
  min-height: 100vh;
  background: #f5ede0;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 2rem 1rem;
  font-family: 'Georgia', serif;
  position: relative;
  overflow: hidden;
}

#app::before {
  content:'';
  position:fixed;
  inset:0;
  background: radial-gradient(ellipse at 20% 10%, rgba(180,160,120,0.18) 0%, transparent 60%),
              radial-gradient(ellipse at 80% 80%, rgba(150,130,100,0.12) 0%, transparent 50%);
  pointer-events:none;
}

#screen-intro { text-align:center; }

.scene {
  position: relative;
  width: 100%;
  max-width: 520px;
  margin: 0 auto 2.5rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 20px;
}

.box-wrap {
  width: 100%;
  max-width: 460px;
  cursor: pointer;
  transition: transform 0.2s;
}
.box-wrap:hover { transform: translateY(-3px); }
.box-svg { width: 100%; display: block; }

.stick-wrap {
  width: 100%;
  max-width: 440px;
  cursor: pointer;
  transition: transform 0.2s;
}
.stick-wrap:hover { transform: translateY(-2px) rotate(1deg); }

.page-eyebrow {
  font-size: 0.65rem;
  letter-spacing: 0.3em;
  color: #b02020;
  text-transform: uppercase;
  margin-bottom: 0.4rem;
}

.snap-btn {
  background: #cc2222;
  border: none;
  color: #fff;
  font-family: 'Arial Black', sans-serif;
  font-size: 1rem;
  font-weight: 900;
  letter-spacing: 0.1em;
  padding: 0.9rem 2.8rem;
  cursor: pointer;
  text-transform: uppercase;
  transition: all 0.15s;
  border-radius: 2px;
  box-shadow: 3px 3px 0 #881111;
}
.snap-btn:hover { background: #ee2222; transform: translate(-1px,-1px); box-shadow: 4px 4px 0 #881111; }
.snap-btn:active { transform: translate(2px,2px); box-shadow: 1px 1px 0 #881111; }

.tagline {
  font-size: 0.75rem;
  color: #9a7050;
  letter-spacing: 0.15em;
  margin-top: 0.8rem;
  text-transform: uppercase;
}

#screen-snap { display:none; text-align:center; width:100%; max-width:520px; }

.snap-label {
  font-family: 'Arial Black', sans-serif;
  font-size: 0.75rem;
  letter-spacing: 0.25em;
  color: #b02020;
  text-transform: uppercase;
  margin-bottom: 1.5rem;
}

.snap-arena {
  position: relative;
  height: 100px;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  margin-bottom: 1rem;
}

.half-l, .half-r {
  position: absolute;
  height: 80px;
  transition: all 0.7s cubic-bezier(0.25,0.46,0.45,0.94);
}
.half-l { right: 50%; transform-origin: right center; }
.half-r { left: 50%; transform-origin: left center; }
.snapping .half-l { transform: rotate(-40deg) translateX(-30px) translateY(-10px); }
.snapping .half-r { transform: rotate(40deg) translateX(30px) translateY(-10px); }

.snap-hint {
  font-size: 0.7rem;
  color: #b07050;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  animation: pulse 2s ease-in-out infinite;
}
@keyframes pulse { 0%,100%{opacity:0.5} 50%{opacity:1} }

#screen-wish { display:none; text-align:center; width:100%; max-width:460px; }

.wish-header {
  background: #cc2222;
  color: #fff;
  font-family: 'Arial Black', sans-serif;
  font-size: 1.4rem;
  font-weight: 900;
  letter-spacing: 0.08em;
  padding: 1rem 1.5rem;
  text-transform: uppercase;
  border: 3px solid #881111;
  border-bottom: none;
}

.wish-subheader {
  background: #fff;
  border: 3px solid #cc2222;
  border-top: none;
  border-bottom: none;
  padding: 0.6rem 1.5rem;
  font-size: 0.75rem;
  color: #cc2222;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  font-family: Arial, sans-serif;
  font-weight: bold;
}

.wish-input {
  width: 100%;
  background: #fffaf5;
  border: 3px solid #cc2222;
  border-top: none;
  color: #2a1a10;
  font-family: Georgia, serif;
  font-size: 1.05rem;
  padding: 1.2rem 1.4rem;
  resize: none;
  outline: none;
  line-height: 1.7;
  letter-spacing: 0.02em;
}
.wish-input::placeholder { color: #c09070; font-style: italic; }

.grant-btn {
  width: 100%;
  background: #cc2222;
  border: 3px solid #881111;
  border-top: none;
  color: #fff;
  font-family: 'Arial Black', sans-serif;
  font-size: 1rem;
  font-weight: 900;
  letter-spacing: 0.12em;
  padding: 1rem;
  cursor: pointer;
  text-transform: uppercase;
  transition: background 0.2s;
}
.grant-btn:hover { background: #ee2222; }

#screen-granted { display:none; text-align:center; width:100%; max-width:460px; }

.granted-banner {
  background: #cc2222;
  color: #fff;
  font-family: 'Arial Black', sans-serif;
  font-size: 0.85rem;
  letter-spacing: 0.25em;
  padding: 0.6rem 1rem;
  text-transform: uppercase;
  border: 3px solid #881111;
  border-bottom: none;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
}

.wish-receipt {
  background: #fff;
  border: 3px solid #cc2222;
  border-bottom: none;
  padding: 1rem 1.4rem;
  text-align: left;
}

.receipt-label {
  font-size: 0.6rem;
  letter-spacing: 0.25em;
  color: #cc2222;
  text-transform: uppercase;
  font-family: Arial, sans-serif;
  font-weight: bold;
  margin-bottom: 0.3rem;
}

.receipt-wish {
  font-size: 0.9rem;
  color: #3a2010;
  font-style: italic;
  line-height: 1.5;
  border-left: 3px solid #cc2222;
  padding-left: 0.8rem;
}

.consequence-panel {
  background: #1a0808;
  border: 3px solid #cc2222;
  border-top: 2px dashed #882222;
  padding: 1.4rem 1.4rem;
  text-align: left;
  position: relative;
}

.consequence-panel::before {
  content: '★ YOUR WISH HAS BEEN GRANTED ★';
  position: absolute;
  top: -0.55rem;
  left: 50%;
  transform: translateX(-50%);
  background: #1a0808;
  padding: 0 0.6rem;
  font-size: 0.55rem;
  letter-spacing: 0.2em;
  color: #cc2222;
  font-family: Arial, sans-serif;
  font-weight: bold;
  white-space: nowrap;
}

.consequence-text {
  font-size: 0.95rem;
  color: #e8c8a0;
  line-height: 1.85;
  letter-spacing: 0.02em;
  font-style: italic;
  min-height: 80px;
}

.loading-dots { display:inline-flex; gap:4px; align-items:center; }
.loading-dots span { width:5px;height:5px;border-radius:50%;background:#cc2222;animation:dot 1.2s ease-in-out infinite; }
.loading-dots span:nth-child(2){animation-delay:0.2s}
.loading-dots span:nth-child(3){animation-delay:0.4s}
@keyframes dot{0%,80%,100%{opacity:0.2;transform:scale(0.8)}40%{opacity:1;transform:scale(1)}}

.fine-print {
  background: #fff;
  border: 3px solid #cc2222;
  border-top: none;
  border-bottom: none;
  padding: 0.7rem 1.4rem;
  font-size: 0.65rem;
  color: #b07050;
  letter-spacing: 0.08em;
  font-style: italic;
  text-align: center;
}

/* ── SHARE BUTTONS ── */
.share-row {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 0;
  border: 3px solid #cc2222;
  border-top: none;
}

.share-btn {
  background: transparent;
  border: none;
  padding: 0.75rem 0.5rem;
  cursor: pointer;
  font-family: 'Arial Black', sans-serif;
  font-size: 0.7rem;
  font-weight: 900;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 7px;
  transition: all 0.15s;
  position: relative;
}

.share-btn:first-child {
  background: #1a0808;
  color: #e8c8a0;
  border-right: 1px solid #882222;
}
.share-btn:first-child:hover { background: #2a1010; }

.share-btn:last-child {
  background: #cc2222;
  color: #fff;
}
.share-btn:last-child:hover { background: #ee2222; }

.share-btn.copied {
  background: #1a3a1a !important;
  color: #8ae8a0 !important;
}

.share-icon { font-size: 1rem; }

.again-row {
  border: 3px solid #cc2222;
  border-top: 1px dashed #882222;
  background: #fff;
  padding: 0.6rem;
  text-align: center;
}

.again-btn {
  background: transparent;
  border: none;
  color: #b02020;
  font-family: Arial, sans-serif;
  font-size: 0.7rem;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  cursor: pointer;
  text-decoration: underline;
  text-underline-offset: 3px;
  padding: 0.2rem;
  transition: color 0.2s;
}
.again-btn:hover { color: #330000; }

/* ── SHARE CARD (hidden, used for copy text) ── */
#shareCard { display:none; }

.flash-overlay {
  position: fixed; inset:0;
  background: #fff;
  z-index:200;
  opacity:0;
  pointer-events:none;
  transition: opacity 0.08s;
}
.flash-overlay.on { opacity:0.7; }

@keyframes shake {
  0%,100%{transform:translate(0,0)}
  15%{transform:translate(-6px,3px)}
  30%{transform:translate(6px,-4px)}
  45%{transform:translate(-5px,5px)}
  60%{transform:translate(6px,-3px)}
  75%{transform:translate(-4px,4px)}
  90%{transform:translate(3px,-4px)}
}
</style>

<div class="flash-overlay" id="fl"></div>
<div id="shareCard"></div>

<div id="app">

<!-- INTRO -->
<div id="screen-intro">
  <div class="scene">
    <div class="box-wrap" onclick="goSnap()">
      <svg class="box-svg" viewBox="0 0 520 190" xmlns="http://www.w3.org/2000/svg">
        <ellipse cx="260" cy="184" rx="230" ry="7" fill="rgba(80,50,30,0.18)"/>
        <rect x="0" y="10" width="520" height="160" rx="4" fill="#f8f4ee"/>
        <rect x="0" y="10" width="520" height="160" rx="4" fill="none" stroke="#c0a080" stroke-width="1.5"/>
        <polygon points="0,10 140,10 0,90" fill="#cc2222"/>
        <polygon points="520,10 380,10 520,90" fill="#cc2222"/>
        <polygon points="0,170 120,170 0,110" fill="#cc2222"/>
        <polygon points="520,170 400,170 520,110" fill="#cc2222"/>
        <rect x="0" y="10" width="520" height="38" fill="#cc2222"/>
        <rect x="0" y="10" width="520" height="4" fill="#aa1111"/>
        <text x="490" y="34" text-anchor="end" font-family="'Arial Black',sans-serif" font-weight="900" font-size="11" fill="#fff" letter-spacing="1">AMAZE YOUR FRIENDS</text>
        <text x="28" y="36" font-size="18" fill="#fff" opacity="0.9">✦</text>
        <text x="48" y="28" font-size="10" fill="#fff" opacity="0.7">✦</text>
        <text x="18" y="50" font-size="8" fill="#fff" opacity="0.6">✦</text>
        <text x="260" y="100" text-anchor="middle" font-family="'Arial Black',sans-serif" font-weight="900" font-size="42" fill="#cc2222" letter-spacing="1">ONE WISH WILLOW</text>
        <ellipse cx="260" cy="140" rx="70" ry="28" fill="#cc2222"/>
        <circle cx="224" cy="128" r="22" fill="#f5dbb0"/>
        <circle cx="224" cy="128" r="22" fill="none" stroke="#cc2222" stroke-width="1.5"/>
        <ellipse cx="218" cy="123" rx="3" ry="3.5" fill="#cc2222"/>
        <ellipse cx="230" cy="123" rx="3" ry="3.5" fill="#cc2222"/>
        <path d="M216 132 Q224 139 232 132" stroke="#cc2222" stroke-width="1.5" fill="none" stroke-linecap="round"/>
        <path d="M205 120 Q210 105 224 106 Q238 105 243 120" fill="#cc2222"/>
        <ellipse cx="202" cy="128" rx="4" ry="5" fill="#f0c898" stroke="#cc2222" stroke-width="1"/>
        <circle cx="296" cy="128" r="22" fill="#f5dbb0"/>
        <circle cx="296" cy="128" r="22" fill="none" stroke="#cc2222" stroke-width="1.5"/>
        <ellipse cx="290" cy="123" rx="3" ry="3.5" fill="#cc2222"/>
        <ellipse cx="302" cy="123" rx="3" ry="3.5" fill="#cc2222"/>
        <path d="M288 132 Q296 139 304 132" stroke="#cc2222" stroke-width="1.5" fill="none" stroke-linecap="round"/>
        <path d="M274 118 Q278 100 296 100 Q314 100 318 118 Q316 138 318 148 Q312 140 296 142 Q280 140 274 148 Q276 138 274 118Z" fill="#cc2222"/>
        <ellipse cx="318" cy="128" rx="4" ry="5" fill="#f0c898" stroke="#cc2222" stroke-width="1"/>
        <rect x="248" y="116" width="8" height="30" rx="2" fill="#1a1a1a"/>
        <text x="235" y="112" font-size="9" fill="#cc2222">✦</text>
        <text x="222" y="104" font-size="6" fill="#cc2222">✦</text>
        <text x="314" y="108" font-size="7" fill="#cc2222">✦</text>
        <text x="322" y="118" font-size="5" fill="#cc2222">✦</text>
        <text x="310" y="120" font-size="9" fill="#cc2222">✦</text>
        <text x="490" y="148" text-anchor="end" font-family="'Arial Black',sans-serif" font-weight="900" font-size="16" fill="#cc2222" letter-spacing="1">ONE WISH</text>
        <rect x="6" y="16" width="508" height="148" rx="2" fill="none" stroke="#cc2222" stroke-width="1" stroke-dasharray="4,3" opacity="0.3"/>
      </svg>
    </div>
    <div class="stick-wrap" onclick="goSnap()">
      <svg viewBox="0 0 440 70" xmlns="http://www.w3.org/2000/svg" style="width:100%;display:block">
        <ellipse cx="220" cy="64" rx="200" ry="6" fill="rgba(80,50,30,0.15)"/>
        <rect x="10" y="18" width="420" height="32" rx="10" fill="#1c1c1c"/>
        <rect x="38"  y="23" width="28" height="10" rx="5" fill="#3a3a3a"/>
        <rect x="38"  y="35" width="28" height="10" rx="5" fill="#3a3a3a"/>
        <rect x="80"  y="23" width="28" height="10" rx="5" fill="#3a3a3a"/>
        <rect x="80"  y="35" width="28" height="10" rx="5" fill="#3a3a3a"/>
        <rect x="122" y="23" width="28" height="10" rx="5" fill="#3a3a3a"/>
        <rect x="122" y="35" width="28" height="10" rx="5" fill="#3a3a3a"/>
        <rect x="164" y="23" width="28" height="10" rx="5" fill="#3a3a3a"/>
        <rect x="164" y="35" width="28" height="10" rx="5" fill="#3a3a3a"/>
        <rect x="206" y="23" width="28" height="10" rx="5" fill="#3a3a3a"/>
        <rect x="206" y="35" width="28" height="10" rx="5" fill="#3a3a3a"/>
        <rect x="248" y="23" width="28" height="10" rx="5" fill="#3a3a3a"/>
        <rect x="248" y="35" width="28" height="10" rx="5" fill="#3a3a3a"/>
        <rect x="290" y="23" width="28" height="10" rx="5" fill="#3a3a3a"/>
        <rect x="290" y="35" width="28" height="10" rx="5" fill="#3a3a3a"/>
        <rect x="332" y="23" width="28" height="10" rx="5" fill="#3a3a3a"/>
        <rect x="332" y="35" width="28" height="10" rx="5" fill="#3a3a3a"/>
        <rect x="374" y="23" width="28" height="10" rx="5" fill="#3a3a3a"/>
        <rect x="374" y="35" width="28" height="10" rx="5" fill="#3a3a3a"/>
        <rect x="10" y="18" width="420" height="8" rx="10" fill="rgba(255,255,255,0.07)"/>
      </svg>
    </div>
  </div>
  <p class="page-eyebrow">Novelty Wish-Granting Toy</p>
  <div class="cta-block">
    <button class="snap-btn" onclick="goSnap()">Snap the Willow</button>
    <p class="tagline">One snap · One wish · No refunds</p>
  </div>
</div>

<!-- SNAP -->
<div id="screen-snap">
  <p class="snap-label">★ Snap the willow in half to activate ★</p>
  <div class="snap-arena" id="snapArena" onclick="doSnap()">
    <svg class="half-l" viewBox="0 0 220 70" xmlns="http://www.w3.org/2000/svg" style="width:220px">
      <rect x="10" y="18" width="200" height="32" rx="10" fill="#1c1c1c"/>
      <rect x="28" y="23" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="28" y="35" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="64" y="23" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="64" y="35" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="100" y="23" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="100" y="35" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="136" y="23" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="136" y="35" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="172" y="23" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="172" y="35" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="10" y="18" width="200" height="8" rx="10" fill="rgba(255,255,255,0.07)"/>
    </svg>
    <svg class="half-r" viewBox="0 0 220 70" xmlns="http://www.w3.org/2000/svg" style="width:220px">
      <rect x="10" y="18" width="200" height="32" rx="10" fill="#1c1c1c"/>
      <rect x="18" y="23" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="18" y="35" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="54" y="23" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="54" y="35" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="90" y="23" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="90" y="35" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="126" y="23" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="126" y="35" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="162" y="23" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="162" y="35" width="24" height="10" rx="5" fill="#3a3a3a"/>
      <rect x="10" y="18" width="200" height="8" rx="10" fill="rgba(255,255,255,0.07)"/>
    </svg>
  </div>
  <p class="snap-hint">click to snap</p>
</div>

<!-- WISH -->
<div id="screen-wish">
  <div class="wish-header">★ ONE WISH WILLOW ★</div>
  <div class="wish-subheader">The willow is broken. It is listening. Make your wish.</div>
  <textarea class="wish-input" id="wishText" rows="4" placeholder="I wish for..."></textarea>
  <button class="grant-btn" onclick="grantWish()">★ GRANT MY WISH ★</button>
</div>

<!-- GRANTED -->
<div id="screen-granted">
  <div class="granted-banner">
    <span>✦</span><span>Your Wish Has Been Granted</span><span>✦</span>
  </div>
  <div class="wish-receipt">
    <p class="receipt-label">You wished for:</p>
    <p class="receipt-wish" id="wishEcho"></p>
  </div>
  <div class="consequence-panel">
    <p class="consequence-text" id="consequenceText">
      <span class="loading-dots"><span></span><span></span><span></span></span>
    </p>
  </div>
  <div class="fine-print">The wish cannot be undone. Manufacturer accepts no responsibility for consequences.</div>

  <!-- SHARE BUTTONS -->
  <div class="share-row">
    <button class="share-btn" id="copyBtn" onclick="copyWish()">
      <span class="share-icon">📋</span> Copy to share
    </button>
    <button class="share-btn" onclick="shareTweet()">
      <span class="share-icon">𝕏</span> Post on X
    </button>
  </div>

  <div class="again-row">
    <button class="again-btn" onclick="resetAll()">break another willow →</button>
  </div>
</div>

</div>

<script>
const screens=['screen-intro','screen-snap','screen-wish','screen-granted'];
function show(id){screens.forEach(s=>{document.getElementById(s).style.display='none';});document.getElementById(id).style.display='block';}
function flash(cb){const f=document.getElementById('fl');f.classList.add('on');setTimeout(()=>{f.classList.remove('on');if(cb)cb();},120);}
function goSnap(){flash(()=>show('screen-snap'));}

let snapped=false;
let currentWish='';
let currentCurse='';
let typingDone=false;

function doSnap(){
  if(snapped)return;snapped=true;
  document.getElementById('snapArena').classList.add('snapping');
  flash();setTimeout(flash,160);setTimeout(flash,320);
  setTimeout(()=>{flash(()=>show('screen-wish'));setTimeout(()=>document.getElementById('wishText').focus(),200);},750);
}

// ── Share functions ──
function getShareText() {
  return `🌿 ONE WISH WILLOW 🌿\n\nI wished for: "${currentWish}"\n\n★ YOUR WISH HAS BEEN GRANTED ★\n\n${currentCurse}\n\n— onewishwillow.com`;
}

function copyWish() {
  if (!typingDone) return;
  const text = getShareText();
  navigator.clipboard.writeText(text).then(() => {
    const btn = document.getElementById('copyBtn');
    btn.classList.add('copied');
    btn.innerHTML = '<span class="share-icon">✓</span> Copied!';
    setTimeout(() => {
      btn.classList.remove('copied');
      btn.innerHTML = '<span class="share-icon">📋</span> Copy to share';
    }, 2500);
  }).catch(() => {
    // fallback for older browsers
    const ta = document.createElement('textarea');
    ta.value = text;
    ta.style.position = 'fixed';
    ta.style.opacity = '0';
    document.body.appendChild(ta);
    ta.select();
    document.execCommand('copy');
    document.body.removeChild(ta);
    const btn = document.getElementById('copyBtn');
    btn.classList.add('copied');
    btn.innerHTML = '<span class="share-icon">✓</span> Copied!';
    setTimeout(() => {
      btn.classList.remove('copied');
      btn.innerHTML = '<span class="share-icon">📋</span> Copy to share';
    }, 2500);
  });
}

function shareTweet() {
  if (!typingDone) return;
  const text = `🌿 I broke the One Wish Willow and wished for:\n\n"${currentWish}"\n\n${currentCurse.substring(0, 180)}...\n\n#OneWishWillow #BeCarefulWhatYouWishFor`;
  const url = `https://twitter.com/intent/tweet?text=${encodeURIComponent(text)}`;
  window.open(url, '_blank');
}

// ── Curse engine ──
function detectTheme(wish) {
  const w = wish.toLowerCase();
  if (/love|like me|love me|crush|boyfriend|girlfriend|partner|marry|soulmate|heart|romance|relationship|maeh|attractive|date me|miss me/i.test(w)) return 'love';
  if (/money|rich|wealth|millionaire|billion|cash|afford|financial|debt|poor|broke/i.test(w)) return 'money';
  if (/famous|popular|known|celebrity|viral|followers|views|star|recognized/i.test(w)) return 'fame';
  if (/smart|intelligent|genius|brilliant|iq|knowledge|learn|study/i.test(w)) return 'intelligence';
  if (/beautiful|pretty|handsome|attractive|hot|looks|appearance|thin|skinny|body|weight/i.test(w)) return 'beauty';
  if (/power|control|strong|strength|leader|rule|authority|respect|fear/i.test(w)) return 'power';
  if (/live forever|immortal|never die|eternal|age|old|young|youth/i.test(w)) return 'immortality';
  if (/happy|happiness|joy|sad|depress|anxiety|peace|calm|content/i.test(w)) return 'happiness';
  if (/time|past|future|go back|undo|change|yesterday|regret/i.test(w)) return 'time';
  if (/friend|lonely|alone|social|belong|accepted|fit in/i.test(w)) return 'friendship';
  if (/talent|skill|sing|dance|play|sport|music|art|draw|write/i.test(w)) return 'talent';
  if (/sleep|rest|tired|energy|awake/i.test(w)) return 'sleep';
  if (/food|eat|hungry|never hungry|full/i.test(w)) return 'food';
  if (/job|career|work|success|promotion|boss|hired/i.test(w)) return 'career';
  if (/family|parent|mom|dad|sibling|brother|sister|child|baby/i.test(w)) return 'family';
  if (/pet|dog|cat|animal/i.test(w)) return 'pet';
  if (/travel|go to|visit|see the world|adventure/i.test(w)) return 'travel';
  if (/wish|anything|everything|all|whatever/i.test(w)) return 'meta';
  return 'generic';
}

const curses = {
  love: [
    (w) => { const name = w.match(/for\s+([^\s]+(?:\s[^\s]+)?)\s+to/i)?.[1] || 'They'; return `Your wish is granted. ${name} loves you now — completely, totally, without limit. They begin texting you 47 times before sunrise. They follow you to work. They sit outside your window every night, not blinking, just watching, waiting. You change your number. They already know the new one. You realize too late that you never specified how they should love you.`; },
    (w) => { const name = w.match(/for\s+([^\s]+(?:\s[^\s]+)?)\s+to/i)?.[1] || 'They'; return `Your wish is granted. ${name} cannot stop thinking about you — every waking second, every dream. They stop eating. They stop sleeping. Their friends grow worried. Their family calls. But they just smile and whisper your name like a prayer. You asked for their love. You didn't ask for their sanity.`; },
    (w) => { const name = w.match(/for\s+([^\s]+(?:\s[^\s]+)?)\s+to/i)?.[1] || 'They'; return `Your wish is granted. ${name} loves you more than anyone — so much that they cannot bear the thought of anyone else loving you either. They begin removing people from your life, one by one, quietly and with a smile. First your friends. Then your family. Soon it is just the two of you. Just the way they always wanted.`; }
  ],
  money: [
    () => `Your wish is granted. You are rich beyond imagination. The money arrives in full — every cent, stacked in your home, filling room after room until there is no space to breathe. Your doors won't open. The weight collapses the floor. You are buried alive in exactly what you asked for.`,
    () => `Your wish is granted. Every person you touch drops dead and leaves you everything they own. By the end of the first week, your pockets are full and your street is quiet. By the end of the month, you stop leaving the house.`,
    () => `Your wish is granted. You will never be without money again. But the money is not yours — it belongs to someone who will never stop looking for it. They find you on a Tuesday.`
  ],
  fame: [
    () => `Your wish is granted. Everyone knows your name. Every camera finds your face. Every stranger on the street turns to look — not with admiration, but with something older and harder. You do not know what you did. The internet has decided, and the internet does not forget.`,
    () => `Your wish is granted. You go viral. Billions of eyes on you, every hour of every day. They watch you sleep. They study your habits. Fan accounts catalog every breath. You cannot go outside. You cannot go back to who you were. This is what you asked for.`,
    () => `Your wish is granted. You are famous. You will be famous long after you are gone — the kind of famous that comes from something terrible happening to you. Historians will be very thorough.`
  ],
  intelligence: [
    () => `Your wish is granted. You are the most intelligent being alive. You understand everything — every system, every pattern, every inevitable end. You see exactly how every story finishes, including yours. You see it clearly. You cannot un-see it. Ignorance, you now understand, was the only mercy.`,
    () => `Your wish is granted. Your mind expands beyond measure. You can hear everyone's thoughts now — their small fears, their quiet cruelties, the things they smile through. It does not stop. It will never stop. You sit very still and try to remember what silence felt like.`,
  ],
  beauty: [
    () => `Your wish is granted. You are the most beautiful person anyone has ever seen. Strangers stop mid-sentence when you pass. Traffic halts. People follow you without meaning to. You begin to notice they do not look at your eyes. They look past them. You are no longer a person to them. You are a thing to be near.`,
    () => `Your wish is granted. You are breathtaking. But beauty this perfect is not natural, and nature corrects its mistakes. The envy begins quietly — whispers, then rumors, then something left on your doorstep. It turns out not everyone wants you to have what they cannot.`,
  ],
  power: [
    () => `Your wish is granted. Everyone fears you. Everyone obeys. Rooms go silent when you enter. No one argues. No one disagrees. No one tells you the truth anymore. You make a decision that ruins everything. No one warned you. They were too afraid.`,
    () => `Your wish is granted. You have total control. But control is heavy, and it must be maintained constantly. You cannot sleep, cannot rest, cannot let go for even a moment or it all unravels. You are the most powerful person alive. You have not been happy in years.`,
  ],
  immortality: [
    () => `Your wish is granted. You will never die. The years pass. Then the decades. You watch everyone you love grow old and leave. You make new ones. They leave too. The centuries blur. You remember faces you can no longer name. You have been alone for a very long time.`,
    () => `Your wish is granted. You cannot die. You discover this when you should have died — and didn't. The body heals. The body always heals. You are still here. You will always be here. You begin to understand why every story about this ends the same way.`,
  ],
  happiness: [
    () => `Your wish is granted. You are happy. Perfectly, completely happy — a warm blank joy that fills every corner. You no longer feel the things that used to matter. Grief, longing, urgency — all gone. You smile at your friend's funeral. You are very happy. You are also very far away.`,
    () => `Your wish is granted. The sadness lifts. All of it — including the sadness that was warning you. The discomfort that was protecting you. The fear that was keeping you safe. You walk into every wrong situation smiling. Nothing feels like a threat anymore.`,
  ],
  time: [
    () => `Your wish is granted. You go back. You change it. It works. Except everything that came after it is gone now too — the person you became from surviving it, the people you met because of it. The version of you standing here, making this wish, no longer exists.`,
    () => `Your wish is granted. You can undo it. But time is not a river — it is a web. You pull one thread and something else tears, somewhere you cannot see, someone you cannot reach.`,
  ],
  friendship: [
    () => `Your wish is granted. You are never alone again. People find you everywhere — at home, at work, in places you thought were private. They all want to be near you. They all call themselves your friend. None of them know anything about you. None of them ask.`,
    () => `Your wish is granted. You belong now. The group accepts you, wants you, needs you. You realize slowly that belonging here requires leaving behind the parts of yourself that didn't fit. By the time you notice what's missing, you've already forgotten what it was.`,
  ],
  talent: [
    () => `Your wish is granted. You are extraordinary at it — better than anyone alive. People come from everywhere to watch you. They stop seeing you and start seeing only the talent. You perform until your hands bleed and they applaud louder. The gift is not yours — it belongs to whoever is watching.`,
    () => `Your wish is granted. You are gifted beyond measure. And everyone knows it. And everyone wants something from it. You have not created something just for yourself in a very long time.`,
  ],
  sleep: [
    () => `Your wish is granted. You sleep — deeply, perfectly, endlessly. You do not wake up for a very long time. The world continues without you. The people in your life wait and then stop waiting. You dream beautifully. You dream alone.`,
    () => `Your wish is granted. You are never tired again. You are awake every hour of every day, perfectly alert, never able to drift away even for a moment. Rest, it turns out, was the mercy. You have too much time to think now.`,
  ],
  food: [
    () => `Your wish is granted. You never feel hungry again. The sensation disappears completely. So does the pleasure of eating — the anticipation, the comfort, the ritual of sharing a meal. You eat because you must, mechanically, without joy. You didn't realize how much of your life was organized around wanting something.`,
  ],
  career: [
    () => `Your wish is granted. You get the promotion. The title. The salary. The corner office. Six months later you understand what the last person who sat there understood — why that chair was empty, why no one warned you, why they all smiled when you took it.`,
    () => `Your wish is granted. You are successful beyond what you imagined. One day you look up and all the things you were working toward the success for are gone. The success remains. It fills the space neatly.`,
  ],
  family: [
    () => `Your wish is granted. Your family is together — all of them, always, every moment. There is no privacy, no distance, no room to breathe. Love at this proximity becomes something else. Something that doesn't have a kind name.`,
  ],
  pet: [
    () => `Your wish is granted. Your pet is with you always now — always at your side, never straying, always watching you with those eyes. They follow you into every room. They wait outside every door. They have not slept in three days. Their tail still wags. Something is different behind their eyes.`,
  ],
  travel: [
    () => `Your wish is granted. You see the world — every country, every city, every wonder. You are always somewhere new. You never stay long enough to know anything deeply. You are always arriving. You are always leaving. You have not been home in years. You're not sure you remember what home felt like.`,
  ],
  meta: [
    () => `Your wish is granted. Everything. All of it — more than you could hold, more than you could manage, more than you could survive intact. The willow does not measure. It does not calculate what you can bear. You asked for everything. You should have been more careful what that meant.`,
  ],
  generic: [
    (w) => `Your wish is granted. The willow considered your words carefully — every syllable, every implication, every gap between what you said and what you meant. It chose the gap. It always chooses the gap. You got exactly what you asked for. Not what you wanted. The difference is everything.`,
    (w) => `Your wish is granted. It manifests quietly at first — so close to what you imagined that you almost miss the wrongness. But it is there, in the texture of it, in the way it sits slightly off from what you pictured. By the time you understand what the willow took in exchange, it is already done.`,
    (w) => `Your wish is granted. Somewhere, the exact shape of your desire was heard and honored. And somewhere else, something was subtracted to balance it — something you didn't know you were holding until your hands felt empty. Wishes don't come from nothing. They come from somewhere.`,
  ]
};

function getCurse(wish) {
  const theme = detectTheme(wish);
  const pool = curses[theme] || curses.generic;
  const fn = pool[Math.floor(Math.random() * pool.length)];
  return fn(wish);
}

function grantWish() {
  const wish = document.getElementById('wishText').value.trim();
  if (!wish) return;
  currentWish = wish;
  typingDone = false;
  flash(() => show('screen-granted'));
  document.getElementById('wishEcho').textContent = '"' + wish + '"';
  flash(); setTimeout(flash, 80);

  // reset share buttons
  const copyBtn = document.getElementById('copyBtn');
  copyBtn.classList.remove('copied');
  copyBtn.innerHTML = '<span class="share-icon">📋</span> Copy to share';

  setTimeout(() => {
    currentCurse = getCurse(wish);
    typeWrite(document.getElementById('consequenceText'), currentCurse, () => {
      typingDone = true;
    });
  }, 600);
}

function typeWrite(el, text, onDone, i=0) {
  el.textContent = '';
  function next() {
    if (i < text.length) {
      el.textContent += text[i++];
      setTimeout(next, 22);
    } else {
      if (onDone) onDone();
    }
  }
  next();
}

function resetAll() {
  snapped = false;
  currentWish = '';
  currentCurse = '';
  typingDone = false;
  document.getElementById('snapArena').classList.remove('snapping');
  document.getElementById('wishText').value = '';
  document.getElementById('consequenceText').innerHTML = '<span class="loading-dots"><span></span><span></span><span></span></span>';
  show('screen-intro');
}

show('screen-intro');
</script>
