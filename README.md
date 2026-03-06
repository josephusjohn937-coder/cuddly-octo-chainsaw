# cuddly-octo-chainsaw
<!DOCTYPE html><html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MoneyHub - Earn Online</title>
<style>
body{margin:0;font-family:Arial;background:#0f172a;color:white}
header{background:#020617;padding:20px;text-align:center}
nav{display:flex;justify-content:center;gap:20px;margin-top:10px}
nav a{color:#38bdf8;text-decoration:none;font-weight:bold}
.hero{padding:80px 20px;text-align:center}
.hero h1{font-size:42px}
.container{max-width:1100px;margin:auto;padding:20px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px}
.card{background:#1e293b;padding:20px;border-radius:10px}
.card h3{margin-top:0}
button{background:#22c55e;border:none;padding:10px 20px;border-radius:6px;color:black;font-weight:bold;cursor:pointer}
footer{background:#020617;padding:20px;text-align:center;margin-top:40px}
.ad{background:#334155;padding:25px;text-align:center;border-radius:8px;margin:30px 0}
</style>
</head><body><header>
<h2>MoneyHub</h2>
<p>Simple Ways To Make Money Online</p>
<nav>
<a href="#home">Home</a>
<a href="#tools">Tools</a>
<a href="#guides">Guides</a>
<a href="#apps">Apps</a>
</nav>
</header><section class="hero" id="home">
<h1>Start Earning Online</h1>
<p>Discover tools, apps, and strategies to make money online.</p>
<button onclick="alert('Join our newsletter soon!')">Get Started</button>
</section><div class="container"><div class="ad">
Ad Space (Place Ad Network Code Here)
</div><h2 id="tools">Free Online Tools</h2>
<div class="grid"><div class="card">
<h3>Username Generator</h3>
<p>Create unique gaming or social media names.</p>
<button onclick="generateName()">Generate</button>
<p id="nameResult"></p>
</div><div class="card">
<h3>Side Hustle Ideas</h3>
<p>Click to get random online business ideas.</p>
<button onclick="idea()">Get Idea</button>
<p id="ideaResult"></p>
</div></div><h2 id="guides">Money Guides</h2>
<div class="grid"><div class="card">
<h3>Start Freelancing</h3>
<p>Learn how beginners earn money online.</p>
<button>Read</button>
</div><div class="card">
<h3>Social Media Growth</h3>
<p>Turn followers into income.</p>
<button>Read</button>
</div></div><h2 id="apps">Recommended Apps</h2>
<div class="grid"><div class="card">
<h3>Survey Apps</h3>
<p>Earn small cash completing surveys.</p>
<button>Open</button>
</div><div class="card">
<h3>Freelance Platforms</h3>
<p>Sell your skills online.</p>
<button>Explore</button>
</div></div><div class="ad">
Affiliate Product Banner
</div></div><footer>
<p>© 2026 MoneyHub</p>
<p>Contact | Privacy | Terms</p>
</footer><script>

function generateName(){
const names=["ShadowNova","IronClash","DarkPulse","AlphaStrike","NightFury","GhostByte","StormEdge"]
const r=Math.floor(Math.random()*names.length)
document.getElementById("nameResult").innerText=names[r]
}

function idea(){
const ideas=[
"Start a TikTok niche page",
"Sell digital templates",
"Create a small blog with ads",
"Affiliate marketing",
"Freelance graphic design",
"Start a gaming YouTube channel"
]

const r=Math.floor(Math.random()*ideas.length)
document.getElementById("ideaResult").innerText=ideas[r]
}

</script></body>
</html>
