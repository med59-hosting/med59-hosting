<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>README Preview — ahmedrana603</title>
<style>
  :root{
    --bg:#0d1117; --bg-secondary:#161b22; --border:#30363d;
    --text:#e6edf3; --text-muted:#8b949e; --link:#58a6ff;
    --header-bg:#161b22; --canvas:#0d1117; --code-bg:#161b22;
  }
  [data-theme="light"]{
    --bg:#ffffff; --bg-secondary:#f6f8fa; --border:#d0d7de;
    --text:#1f2328; --text-muted:#59636e; --link:#0969da;
    --header-bg:#f6f8fa; --canvas:#ffffff; --code-bg:#f6f8fa;
  }
  *{box-sizing:border-box;}
  body{
    margin:0; background:var(--canvas); color:var(--text);
    font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Helvetica,Arial,sans-serif;
    transition:background .25s ease,color .25s ease;
  }
  .topbar{
    position:sticky; top:0; z-index:10;
    background:var(--header-bg); border-bottom:1px solid var(--border);
    padding:12px 24px; display:flex; align-items:center; justify-content:space-between;
  }
  .topbar .repo{
    font-size:14px; color:var(--text-muted); display:flex; align-items:center; gap:8px;
  }
  .repo b{color:var(--text);}
  .toggle-btn{
    background:var(--bg-secondary); border:1px solid var(--border); color:var(--text);
    padding:6px 14px; border-radius:6px; font-size:13px; cursor:pointer;
    display:flex; align-items:center; gap:6px;
  }
  .toggle-btn:hover{border-color:var(--link);}
  .note{
    max-width:900px; margin:18px auto 0; padding:10px 16px;
    background:var(--bg-secondary); border:1px solid var(--border); border-radius:8px;
    font-size:13px; color:var(--text-muted);
  }
  .wrapper{
    max-width:900px; margin:0 auto; padding:24px;
    background:var(--bg); border:1px solid var(--border); border-radius:10px;
    margin-top:16px; margin-bottom:60px;
  }
  img{max-width:100%;}
  .markdown-body h2{
    border-bottom:1px solid var(--border); padding-bottom:8px; margin-top:36px;
    font-size:22px;
  }
  .badges-row{display:flex; flex-wrap:wrap; gap:6px; margin:10px 0;}
  details{
    border:1px solid var(--border); border-radius:8px; margin:12px 0; padding:10px 14px;
    background:var(--bg-secondary);
  }
  summary{cursor:pointer; font-weight:600; font-size:15px;}
  a{color:var(--link); text-decoration:none;}
  a:hover{text-decoration:underline;}
  .center{text-align:center;}
  .about-list{line-height:2;}
  .clearfix::after{content:""; display:table; clear:both;}
  .float-right{float:right; width:280px; margin:0 0 12px 20px; border-radius:10px;}
  @media(max-width:600px){ .float-right{float:none; width:100%; margin:12px 0;} }
  footer.mock{
    text-align:center; color:var(--text-muted); font-size:12px; padding:20px;
  }
</style>
</head>
<body data-theme="dark">

<div class="topbar">
  <div class="repo">📄 <b>README.md</b> preview &nbsp;·&nbsp; mimics github.com rendering</div>
  <button class="toggle-btn" onclick="toggleTheme()">🌗 Toggle light / dark</button>
</div>

<div class="note center">
  This is a visual mockup so you can sanity-check the layout before pasting into your actual <b>github.com/ahmedrana603/ahmedrana603</b> repo. Badge/stat images load live from shields.io &amp; vercel — GitHub will render them identically once the file is committed.
</div>

<div class="wrapper markdown-body">

  <div class="center">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:2C5364,100:00C9A7&height=220&section=header&text=Ahmed%20Ghaffar&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Data%20Science%20Undergraduate%20%40%20FAST-NUCES&descAlignY=58&descSize=18" width="100%"/>
    <br/><br/>
    <a href="#"><img src="https://readme-typing-svg.demolab.com/?lines=Turning+raw+data+into+decisions;Building+AI+%2F+ML+systems+that+ship;Automating+the+boring+stuff+away;Final-Year+Data+Science+Undergrad;FAST-NUCES+Islamabad&font=Fira+Code&center=true&width=560&height=50&color=00C9A7&vCenter=true&size=22&pause=1200"/></a>
  </div>

  <br/>

  <div class="clearfix">
    <img class="float-right" src="https://raw.githubusercontent.com/gist/Anmol-Baranwal/6a671d3fd12d13d55954bb0e7fca27f8/raw/469a37c1e3037c7c78f6feb9e7c9adcb2fac89c6/AI.gif" />

    <h2>🧠 About Me</h2>
    <ul class="about-list">
      <li>🎓 Final-year <b>Data Science</b> undergraduate at <b>FAST-NUCES, Islamabad</b></li>
      <li>🔍 Deep in <b>audio deepfake detection &amp; source-tracing research</b></li>
      <li>⚙️ Doing hands-on <b>QA / automation</b> work on production dashboards</li>
      <li>🤖 Fascinated by <b>neural networks</b>, applied ML, and how to make models actually useful</li>
      <li>📊 Love turning messy data into dashboards and decisions</li>
      <li>⚡ Big believer in <b>automating repetitive work</b> — if I do it twice, I script it</li>
      <li>🌱 Currently exploring: open-set source tracing, gated-fusion architectures, multi-agent AI systems</li>
    </ul>
  </div>

  <h2>🌐 Connect With Me</h2>
  <div class="center badges-row" style="justify-content:center;">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </div>

  <h2>🛠️ Tech &amp; Tools</h2>

  <details open>
    <summary>💬 Languages</summary>
    <div class="badges-row">
      <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/>
      <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white"/>
      <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
      <img src="https://img.shields.io/badge/AssemblyScript-000000?style=for-the-badge&logo=assemblyscript&logoColor=white"/>
    </div>
  </details>

  <details open>
    <summary>🤖 AI / ML &amp; Deep Learning</summary>
    <div class="badges-row">
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white"/>
      <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
      <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
      <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
      <img src="https://img.shields.io/badge/SciPy-0C55A5?style=for-the-badge&logo=scipy&logoColor=white"/>
    </div>
  </details>

  <details open>
    <summary>📊 Data Analytics &amp; Visualization</summary>
    <div class="badges-row">
      <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white"/>
      <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
      <img src="https://img.shields.io/badge/Matplotlib-ffffff?style=for-the-badge&logo=Matplotlib&logoColor=black"/>
      <img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white"/>
    </div>
  </details>

  <details open>
    <summary>⚡ Automation &amp; Workflow</summary>
    <div class="badges-row">
      <img src="https://img.shields.io/badge/Asana-273347?style=for-the-badge&logo=asana&logoColor=F06A6A"/>
      <img src="https://img.shields.io/badge/Trello-026AA7?style=for-the-badge&logo=Trello&logoColor=white"/>
      <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
      <img src="https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=Twilio&logoColor=white"/>
    </div>
  </details>

  <details open>
    <summary>🧩 Frameworks &amp; Backend</summary>
    <div class="badges-row">
      <img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi"/>
      <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
    </div>
  </details>

  <details open>
    <summary>🎨 Design &amp; Creative</summary>
    <div class="badges-row">
      <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/>
      <img src="https://img.shields.io/badge/Illustrator-FF9A00?style=for-the-badge&logo=adobe%20illustrator&logoColor=white"/>
      <img src="https://img.shields.io/badge/After_Effects-9999FF?style=for-the-badge&logo=Adobe%20After%20Effects&logoColor=white"/>
      <img src="https://img.shields.io/badge/Lightroom-31A8FF?style=for-the-badge&logo=Adobe%20Lightroom&logoColor=white"/>
      <img src="https://img.shields.io/badge/SASS-CC6699?style=for-the-badge&logo=SASS&logoColor=white"/>
    </div>
  </details>

  <details open>
    <summary>🧰 Dev Tools &amp; Environment</summary>
    <div class="badges-row">
      <img src="https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white"/>
      <img src="https://img.shields.io/badge/Anaconda-44A833?style=for-the-badge&logo=anaconda&logoColor=white"/>
    </div>
  </details>

  <h2>📈 GitHub Analytics</h2>
  <div class="center">
    <img height="165" src="https://github-readme-stats.vercel.app/api?username=ahmedrana603&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true"/>
    <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=ahmedrana603&theme=tokyonight&hide_border=true"/>
    <br/><br/>
    <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ahmedrana603&layout=compact&theme=tokyonight&hide_border=true"/>
  </div>

  <h2>🔥 Contribution Activity</h2>
  <div class="center">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=ahmedrana603&theme=tokyo-night&hide_border=true&area=true" width="100%"/>
  </div>

  <h2>🐍 Contribution Snake</h2>
  <div class="note">
    ⚠️ Snake animation only appears after you run the one-time GitHub Action setup described below — it can't be previewed here since it depends on your live contribution graph.
  </div>

  <div class="center" style="margin-top:24px;">
    <h3>✍️ Random Dev Quote</h3>
    <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight"/>
    <br/><br/>
    <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9A7,100:0F2027&height=120&section=footer" width="100%"/>
    <br/>
    <img src="https://visitcount.itsvg.in/api?id=ahmedrana603&icon=0&color=2"/>
    <p><b>Thanks for stopping by — let's build something intelligent together.</b></p>
  </div>

</div>

<footer class="mock">Mockup preview generated for review purposes — not part of the committed README.</footer>

<script>
function toggleTheme(){
  const body=document.body;
  const cur=body.getAttribute('data-theme');
  body.setAttribute('data-theme', cur==='dark' ? 'light':'dark');
}
</script>

</body>
</html>
