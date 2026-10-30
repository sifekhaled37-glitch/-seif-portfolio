<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Maloka - عيد ميلاد سعيد</title>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;600;800&family=Great+Vibes&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box}
body{font-family:'Cairo',sans-serif;background:#0a0a0a;color:#fff;overflow-x:hidden}
.great{font-family:'Great Vibes',cursive}
#entry{position:fixed;inset:0;background:radial-gradient(circle at 50% 30%, #2a0a1a, #000);display:flex;flex-direction:column;align-items:center;justify-content:center;z-index:100;transition:1s}
#entry.hide{transform:translateY(-100%);opacity:0}
.heart-beat{font-size:80px;animation:beat 1s infinite}
@keyframes beat{0%,100%{transform:scale(1)}50%{transform:scale(1.2)}}
#entry h1{font-size:2.2rem;margin:20px 0 10px}
#entry p{opacity:.7;margin-bottom:30px}
#entry input{background:rgba(255,255,255,.08);border:1px solid rgba(255,255,255,.2);padding:14px 20px;border-radius:30px;color:#fff;text-align:center;width:220px;font-size:18px;letter-spacing:3px}
#entry button{margin-top:20px;background:linear-gradient(135deg,#ff2a6d,#ff7a9e);border:none;padding:14px 40px;border-radius:30px;color:#fff;font-weight:800;font-size:16px;cursor:pointer;box-shadow:0 10px 30px rgba(255,42,109,.4)}
.hero{min-height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:40px 20px;background:radial-gradient(circle at 50% 0%, #2a1020 0%, #000 70%)}
.hero h1{font-size:4rem;background:linear-gradient(135deg,#fff,#ff8fb5);-webkit-background-clip:text;-webkit-text-fill-color:transparent;margin-bottom:10px}
.hero h2{font-size:1.3rem;opacity:.8;font-weight:300;max-width:500px;line-height:1.8}
.count{margin-top:30px;display:flex;gap:12px}
.count div{background:rgba(255,255,255,.06);border:1px solid rgba(255,255,255,.1);padding:15px 20px;border-radius:20px;min-width:80px}
.count b{font-size:1.8rem;display:block;color:#ff6b9d}
.count span{font-size:.75rem;opacity:.6}
.section{padding:80px 20px;max-width:900px;margin:0 auto}
.title{font-size:2rem;text-align:center;margin-bottom:40px}
.title em{color:#ff6b9d;font-style:normal}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:20px}
.card{background:linear-gradient(180deg,rgba(255,255,255,.08),rgba(255,255,255,.02));border:1px solid rgba(255,255,255,.08);border-radius:24px;padding:30px;backdrop-filter:blur(10px)}
.card h3{margin-bottom:10px;color:#ff9ebc}
.timeline{position:relative;border-right:2px solid rgba(255,107,157,.3);padding-right:30px;margin-right:20px}
.timeline-item{margin-bottom:40px;position:relative}
.timeline-item::before{content:'';position:absolute;right:-37px;top:5px;width:12px;height:12px;background:#ff2a6d;border-radius:50%;box-shadow:0 0 0 6px rgba(255,42,109,.2)}
.timeline-item small{color:#ff7a9e;font-weight:800}
.timeline-item h4{margin:6px 0}
.timeline-item p{opacity:.7;font-size:.9rem;line-height:1.7}
.letter{background:#fff;color:#111;border-radius:30px;padding:40px 30px;transform:rotate(-1deg);box-shadow:0 30px 60px rgba(0,0,0,.5);position:relative}
.letter::before{content:'💌';position:absolute;top:-20px;right:30px;font-size:40px}
.letter p{line-height:2;font-size:1.05rem}
.final{text-align:center;padding:100px 20px;background:radial-gradient(circle at 50% 100%, #3a1020, transparent 60%)}
.final h2{font-size:3rem;margin-bottom:20px}
.btn-gift{background:#fff;color:#000;padding:18px 50px;border-radius:40px;border:none;font-weight:800;font-size:18px;cursor:pointer;margin-top:20px}
.hearts{position:fixed;inset:0;pointer-events:none;overflow:hidden}
.hearts span{position:absolute;animation:float 6s linear infinite;font-size:20px}
@keyframes float{0%{transform:translateY(100vh) rotate(0)}100%{transform:translateY(-10vh) rotate(360deg)}}
</style>
</head>
<body>
<div class="hearts" id="hearts"></div>
<div id="entry">
<div class="heart-beat">💖</div>
<h1 class="great" style="font-size:3rem">For Maloka</h1>
<p>اكتبي تاريخ ميلادك السحري 30/10</p>
<input id="code" placeholder="30/10" inputmode="numeric">
<button onclick="enter()">افتحي هديتك 🎁</button>
<p style="margin-top:15px;font-size:12px;opacity:.5">تلميح: اليوم اللي اتحسب من 9 سنين</p>
</div>
<div class="hero">
<h1 class="great">Happy Birthday</h1>
<h1 style="font-size:3rem;margin-top:-20px">MALOKA 👸</h1>
<h2>من 9 سنين والدنيا أحلى بوجودك - من يوم 30/10/2017 لحد النهاردة 30/10/2026 وانتي أجمل حاجة حصلتلي</h2>
<div class="count">
<div><b>9</b><span>سنين</span></div>
<div><b>3284</b><span>يوم حب</span></div>
<div><b>∞</b><span>ذكريات</span></div>
</div>
</div>
<div class="section">
<h2 class="title">ليه انتي <em>مختلفة</em>؟</h2>
<div class="cards">
<div class="card"><h3>👑 ضحكتك</h3><p>بتخليني انسى أي زعل في ثانية</p></div>
<div class="card"><h3>💙 قلبك</h3><p>أطيب قلب شفته، بتحبي الكل بجد</p></div>
<div class="card"><h3>✨ وجودك</h3><p>معاكي كل يوم عيد مش بس النهاردة</p></div>
</div>
</div>
<div class="section">
<h2 class="title">رحلتنا من <em>30/10/2017</em></h2>
<div class="timeline">
<div class="timeline-item"><small>30 Oct 2017</small><h4>اليوم اللي نورتي فيه الدنيا 🌟</h4><p>من هنا بدأت الحكاية الحلوة</p></div>
<div class="timeline-item"><small>بعدها بشوية</small><h4>أول مرة شفتك فيها</h4><p>ومن ساعتها وانا مش عارف أنساكي</p></div>
<div class="timeline-item"><small>كل يوم</small><h4>بقع في حبك أكتر</h4><p>وكل سنة وانتي بتكبري بتحلوي أكتر</p></div>
<div class="timeline-item"><small>30 Oct 2026</small><h4>النهاردة - 9 سنين 🎂</h4><p>عيد ميلاد ملكة قلبي، ولسه اللي جاي أحلى</p></div>
</div>
</div>
<div class="section">
<div class="letter">
<h3 style="margin-bottom:20px;font-size:1.5rem">إلى ملوكتي...</h3>
<p>
يا ملوكة،<br><br>
لو كنت أعرف أهديكي نجمة من السما كنت هديتك، بس انتي أصلاً نجمة.<br>
9 سنين عدوا وانتي بتكبري وبتحلوي، وكل سنة بتثبتيلي إن اختياري ليكي كان أحلى قرار.<br><br>
عايزك تعرفي إنك مش بس حبيبتي، انتي صاحبتي وأختي وكل دنيتي.<br>
في عيد ميلادك ده بتمنالك سنة كلها فرح، تحققي كل اللي نفسك فيه، وتفضلي دايماً بتضحكي الضحكة اللي بحبها.<br><br>
كل سنة وانتي طيبة يا ملكة قلبي 👑💙<br>
بحبك أكتر من 3284 يوم اللي فاتوا، وهحبك قد اللي جايين.<br><br>
<strong> - حبيبك</strong>
</p>
</div>
</div>
<div class="final">
<h2 class="great">هديتك مستنياكي</h2>
<p style="opacity:.7">دوسي هنا وشوفي المفاجأة</p>
<button class="btn-gift" onclick="gift()">افتحي المفاجأة 🎀</button>
<p id="gift-msg" style="margin-top:30px;font-size:1.2rem;display:none">أنا هديتك الحقيقية... وطول ما انا معاكي هتفضلي أسعد واحدة في الدنيا 💖<br><br> قوليلي موافقة تكملي معايا 90 سنة كمان؟</p>
</div>
<script>
function enter(){
 const v=document.getElementById('code').value.trim();
 if(v.includes('30') && v.includes('10')){
  document.getElementById('entry').classList.add('hide');
  setTimeout(()=>document.getElementById('entry').style.display='none',1000);
  createHearts();
 }else{ alert('جربي 30/10 😉'); }
}
function createHearts(){
 const c=document.getElementById('hearts');
 setInterval(()=>{
  const s=document.createElement('span');
  s.textContent=['💖','💙','💘','👑'][Math.floor(Math.random()*4)];
  s.style.left=Math.random()*100+'%';
  s.style.animationDuration=(4+Math.random()*4)+'s';
  c.appendChild(s);
  setTimeout(()=>s.remove(),6000);
 },300);
}
function gift(){
 document.getElementById('gift-msg').style.display='block';
 createHearts();
 window.scrollTo({top:document.body.scrollHeight,behavior:'smooth'});
}
document.getElementById('code').addEventListener('keypress',e=>{if(e.key==='Enter')enter()});
</script>
</body>
</html>
