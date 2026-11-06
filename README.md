<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>[Your Name] – Portfolio</title>
<meta name="description" content="Portfolio of [Your Name], [Major] student at [University].">
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@600;700&family=Public+Sans:wght@400;500;600&display=swap">
<style>
:root{--bg:#f3f5f9;--surface:#fff;--ink:#14213d;--muted:#55607a;--line:#d5dbe8;--accent:#2742d6;--on-accent:#fff;color-scheme:light;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0f1424;--surface:#171d33;--ink:#eef1fb;--muted:#a3adc8;--line:#2b3352;--accent:#8da2ff;--on-accent:#0b1030;color-scheme:dark}}
:root[data-theme="dark"]{--bg:#0f1424;--surface:#171d33;--ink:#eef1fb;--muted:#a3adc8;--line:#2b3352;--accent:#8da2ff;--on-accent:#0b1030;color-scheme:dark}
html{scroll-padding-top:calc(env(safe-area-inset-top,0px) + 6rem)}
@media (prefers-reduced-motion:no-preference){html{scroll-behavior:smooth}}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font:400 1.02rem/1.65 "Public Sans",system-ui,-apple-system,"Segoe UI",sans-serif}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);z-index:10;background:var(--bg)}
h1,h2,h3{font-family:"Bricolage Grotesque","Arial Black",system-ui,sans-serif;font-weight:700;line-height:1.1;margin:0;letter-spacing:-.01em}
a{color:var(--accent)}
:focus-visible{outline:3px solid var(--accent);outline-offset:3px}
.wrap{max-width:62rem;margin:0 auto;padding:0 1.25rem}
.top{position:sticky;top:env(safe-area-inset-top,0px);z-index:20;background:var(--bg);border-bottom:1px solid var(--line)}
.bar{display:flex;align-items:center;gap:1rem;flex-wrap:wrap;padding-top:.7rem;padding-bottom:.7rem}
.brand{font:700 1.15rem "Bricolage Grotesque","Arial Black",system-ui,sans-serif;color:var(--ink);text-decoration:none;margin-right:auto}
.links{display:flex;gap:1.3rem;overflow-x:auto;scrollbar-width:none}
.links a{color:var(--muted);text-decoration:none;font-weight:500;white-space:nowrap}
.links a:hover{color:var(--accent)}
#theme{width:2.2rem;height:2.2rem;border-radius:50%;border:2px solid var(--ink);background:none;color:var(--ink);cursor:pointer;font-size:1rem}
@media (max-width:640px){.links{order:3;width:100%}}
section{padding-top:4.5rem}
.sec{border-top:2px solid var(--ink);padding-top:1rem;margin:0 0 1.6rem;font-size:clamp(1.6rem,4vw,2.1rem)}
.hero{display:grid;grid-template-columns:1fr auto;gap:3rem;align-items:center;padding-top:3.5rem}
.hero h1{font-size:clamp(2.3rem,6.5vw,3.9rem);line-height:1.04;letter-spacing:-.025em}
.lead{font-size:1.15rem;color:var(--muted);max-width:34rem;margin:1.3rem 0 1.8rem}
.btn{display:inline-block;padding:.8rem 1.3rem;border-radius:.6rem;font-weight:600;text-decoration:none;border:2px solid var(--ink);color:var(--ink);margin:0 .6rem .6rem 0}
.btn.primary{background:var(--accent);border-color:var(--accent);color:var(--on-accent)}
.id{width:16rem;background:var(--surface);border:2px solid var(--ink);border-radius:1.1rem;overflow:hidden;text-align:center;padding-bottom:1.3rem;transform:rotate(-2deg);box-shadow:7px 7px 0 var(--ink);justify-self:center}
@media (prefers-reduced-motion:no-preference){.id{animation:swing .9s ease-out}}
@keyframes swing{from{transform:rotate(-9deg) translateY(-14px)}to{transform:rotate(-2deg)}}
.id-top{background:#ffe14d;color:#14213d;font-weight:600;padding:.7rem 1rem;border-bottom:2px solid var(--ink)}
.avatar{width:6.5rem;height:6.5rem;border-radius:50%;margin:1.3rem auto .8rem;display:grid;place-items:center;background:var(--bg);border:2px solid var(--ink);font:700 2.2rem "Bricolage Grotesque","Arial Black",system-ui,sans-serif}
.id-name{font:700 1.3rem "Bricolage Grotesque","Arial Black",system-ui,sans-serif;margin:0}
.id-line{margin:.15rem 0;color:var(--muted);font-size:.92rem}
.id-open{margin:.9rem 0 0;font-weight:600;font-size:.9rem}
.dot{display:inline-block;width:.6rem;height:.6rem;border-radius:50%;background:#2fbf71;margin-right:.45rem}
@media (max-width:700px){.hero{grid-template-columns:1fr}}
.two{display:grid;gap:2.5rem;grid-template-columns:repeat(auto-fit,minmax(min(100%,19rem),1fr))}
.two p{margin:0 0 1rem;max-width:34rem}
.facts{margin:0}
.facts div{display:grid;grid-template-columns:7rem 1fr;gap:1rem;padding:.65rem 0;border-bottom:1px solid var(--line)}
.facts dt{color:var(--muted)}
.facts dd{margin:0;font-weight:500}
.skills{display:grid;gap:2.5rem;grid-template-columns:repeat(auto-fit,minmax(min(100%,19rem),1fr))}
.skills h3{font-size:1.2rem}
.chips{display:flex;flex-wrap:wrap;gap:.5rem;list-style:none;margin:.9rem 0 0;padding:0}
.chips li{border:1px solid var(--line);background:var(--surface);border-radius:.4rem;padding:.25rem .7rem;font-size:.92rem}
.row{display:grid;grid-template-columns:12rem 1fr;gap:1.5rem;padding:1.7rem 0;border-top:1px solid var(--line)}
.rows .row:last-child{border-bottom:1px solid var(--line)}
.kind strong{display:inline-block;background:#ffe14d;color:#14213d;padding:.15rem .6rem;border-radius:.3rem}
.kind span{display:block;color:var(--muted);font-size:.9rem;margin-top:.3rem}
.body h3{font-size:1.4rem;margin-bottom:.5rem}
.body p{margin:0;max-width:38rem}
.body dl{display:grid;grid-template-columns:7rem 1fr;gap:.4rem 1rem;margin:1rem 0 0}
.body dt{font-weight:600}
.body dd{margin:0}
.go{display:flex;gap:1.3rem;margin:1rem 0 0;font-weight:600}
@media (max-width:700px){.row{grid-template-columns:1fr;gap:.8rem}}
.line{list-style:none;margin:0;padding:0 0 0 1.5rem;border-left:2px solid var(--ink)}
.line li{position:relative;margin:0 0 1.7rem}
.line li::before{content:"";position:absolute;left:calc(-1.5rem - 1px);top:.35rem;width:.8rem;height:.8rem;border-radius:50%;background:var(--accent);transform:translateX(-50%)}
.line time{font-weight:700;color:var(--accent)}
.line h3{font-size:1.15rem;margin:.1rem 0 .2rem}
.line p{margin:0;color:var(--muted)}
footer{padding:4rem 0 2rem;color:var(--muted);font-size:.92rem}
</style>
</head>
<body>
<!-- TEMPLATE GUIDE: replace every [bracketed text]; change colors in :root; copy an <article class="row"> block to add more projects; swap the .avatar initials for <img src="your-photo.jpg" alt="Your name"> once you host the file. -->

<header class="top">
  <div class="wrap bar">
    <a class="brand" href="#top">[Your Name]</a>
    <nav class="links" aria-label="Sections">
      <a href="#about">About</a><a href="#skills">Skills</a><a href="#projects">Projects</a><a href="#journey">Journey</a><a href="#contact">Contact</a>
    </nav>
    <button id="theme" type="button" aria-label="Switch light or dark mode">◐</button>
  </div>
</header>

<main>
<section id="top" style="padding-top:0">
  <div class="wrap hero">
    <div>
      <h1>Hi, I’m [Your Name], a [Major] student who builds and documents real projects.</h1>
      <p class="lead">[Two sentences: what you study, what you are good at, and the role or internship you want next.]</p>
      <a class="btn primary" href="#projects">See my projects</a><a class="btn" href="#contact">Contact me</a>
    </div>
    <aside class="id" aria-label="Student card">
      <div class="id-top">[University]</div>
      <div class="avatar" role="img" aria-label="Profile photo placeholder">YN</div>
      <p class="id-name">[Your Name]</p>
      <p class="id-line">[Major], class of [Year]</p>
      <p class="id-line">Student ID [Your NIM]</p>
      <p class="id-open"><span class="dot"></span>Open to internships</p>
    </aside>
  </div>
</section>

<section id="about">
  <div class="wrap">
    <h2 class="sec">About me</h2>
    <div class="two">
      <div>
        <p>[Paragraph 1: how you got into your field and what you enjoy building or solving.]</p>
        <p>[Paragraph 2: what you are learning now, your strengths, and what you want to do after graduation.]</p>
      </div>
      <dl class="facts">
        <div><dt>Based in</dt><dd>[City, Country]</dd></div>
        <div><dt>Studying</dt><dd>[Degree] at [University]</dd></div>
        <div><dt>Interests</dt><dd>[Topic 1], [Topic 2], [Topic 3]</dd></div>
        <div><dt>Open to</dt><dd>[Internships, freelance, collaboration]</dd></div>
      </dl>
    </div>
  </div>
</section>

<section id="skills">
  <div class="wrap">
    <h2 class="sec">Skills</h2>
    <div class="skills">
      <div>
        <h3>Technical skills</h3>
        <ul class="chips"><li>[Programming language]</li><li>[Framework]</li><li>[Database]</li><li>[Design tool]</li><li>[Data or office tool]</li><li>Git</li></ul>
      </div>
      <div>
        <h3>Non-technical skills</h3>
        <ul class="chips"><li>Communication</li><li>Teamwork</li><li>Time management</li><li>Problem solving</li><li>Presentation</li><li>[Language skills]</li></ul>
      </div>
    </div>
  </div>
</section>

<section id="projects">
  <div class="wrap">
    <h2 class="sec">Projects and case studies</h2>
    <div class="rows">
      <article class="row">
        <div class="kind"><strong>Project Based</strong><span>[Course name]</span><span>[Semester, Year]</span><span>Team of [N]</span></div>
        <div class="body">
          <h3>[Project title]</h3>
          <p>[One sentence on the problem you solved and what you built.]</p>
          <dl>
            <dt>My role</dt><dd>[For example: front-end developer, team lead]</dd>
            <dt>Process</dt><dd>[Methods and tools, for example Scrum, Figma, Laravel]</dd>
            <dt>Result</dt><dd>[Outcome, grade, or a number that proves it worked]</dd>
          </dl>
          <ul class="chips"><li>[Tool 1]</li><li>[Tool 2]</li><li>[Tool 3]</li></ul>
          <p class="go"><a href="#">Live demo</a><a href="#">Repository</a></p>
        </div>
      </article>
      <article class="row">
        <div class="kind"><strong>Case Based</strong><span>[Course name]</span><span>[Semester, Year]</span><span>[Individual or team]</span></div>
        <div class="body">
          <h3>[Case title]</h3>
          <p>[One sentence describing the case and who it was about.]</p>
          <dl>
            <dt>Problem</dt><dd>[What was going wrong or unclear]</dd>
            <dt>Analysis</dt><dd>[Methods or frameworks you used to study it]</dd>
            <dt>Solution</dt><dd>[What you recommended and why]</dd>
            <dt>Outcome</dt><dd>[Result, feedback, or what you learned]</dd>
          </dl>
          <p class="go"><a href="#">Read the full case</a></p>
        </div>
      </article>
      <article class="row">
        <div class="kind"><strong>Personal</strong><span>[Optional]</span><span>[Year]</span></div>
        <div class="body">
          <h3>[Side project, competition, or volunteer work]</h3>
          <p>[Two sentences on what it is and what you contributed.]</p>
          <p class="go"><a href="#">View details</a></p>
        </div>
      </article>
    </div>
  </div>
</section>

<section id="journey">
  <div class="wrap">
    <h2 class="sec">Education and experience</h2>
    <ol class="line">
      <li><time>[Year] to present</time><h3>[Degree], [University]</h3><p>GPA [x.xx]. Relevant courses: [Course 1], [Course 2], [Course 3].</p></li>
      <li><time>[Year]</time><h3>[Organization, internship, or competition]</h3><p>[Your role and what you achieved.]</p></li>
      <li><time>[Year]</time><h3>[Certificate or award]</h3><p>[Issuer and what it proves.]</p></li>
    </ol>
  </div>
</section>

<section id="contact">
  <div class="wrap">
    <h2 class="sec">Let’s talk</h2>
    <p class="lead" style="margin-top:0">[Say what you are looking for. For example: I’m looking for a [role] internship starting [month, year]. Email is the fastest way to reach me.]</p>
    <a class="btn primary" href="mailto:you@example.com">you@example.com</a><a class="btn" href="#">LinkedIn</a><a class="btn" href="#">GitHub</a>
  </div>
</section>
</main>

<footer>
  <div class="wrap">© <span id="yr">2026</span> [Your Name]. All rights reserved.</div>
</footer>

<script>
var root=document.documentElement;
document.getElementById('theme').addEventListener('click',function(){
  var dark=root.dataset.theme?root.dataset.theme==='dark':matchMedia('(prefers-color-scheme: dark)').matches;
  root.dataset.theme=dark?'light':'dark';
});
document.getElementById('yr').textContent=new Date().getFullYear();
</script>
</body>
</html>
