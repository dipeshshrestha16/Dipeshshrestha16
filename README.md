<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    ANIMATED SVG HEADER                      -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">
<svg width="100%" height="200" viewBox="0 0 1200 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#000000"/>
      <stop offset="50%" style="stop-color:#0a001a"/>
      <stop offset="100%" style="stop-color:#000000"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="glow2">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="1200" height="200" fill="url(#bgGrad)"/>

  <!-- Animated binary rain columns -->
  <g font-family="'Courier New', monospace" font-size="11" fill="#9b59b6" opacity="0.35">
    <text x="20" fill="#00ff41" opacity="0.5">
      <tspan x="20" dy="0">1</tspan><animate attributeName="y" from="-200" to="220" dur="3.1s" repeatCount="indefinite"/>
    </text>
    <text x="20" fill="#9b59b6">
      <tspan>0</tspan><animate attributeName="y" from="-160" to="260" dur="3.1s" repeatCount="indefinite"/>
    </text>
    <text x="20" fill="#00ff41" opacity="0.6">
      <tspan>1</tspan><animate attributeName="y" from="-120" to="300" dur="3.1s" repeatCount="indefinite"/>
    </text>
    <text x="45" fill="#9b59b6">
      <tspan>0</tspan><animate attributeName="y" from="-180" to="240" dur="2.4s" repeatCount="indefinite"/>
    </text>
    <text x="45" fill="#00ff41" opacity="0.5">
      <tspan>1</tspan><animate attributeName="y" from="-140" to="280" dur="2.4s" repeatCount="indefinite"/>
    </text>
    <text x="45" fill="#9b59b6" opacity="0.7">
      <tspan>0</tspan><animate attributeName="y" from="-100" to="320" dur="2.4s" repeatCount="indefinite"/>
    </text>
    <text x="70" fill="#00ff41" opacity="0.4">
      <tspan>1</tspan><animate attributeName="y" from="-200" to="220" dur="2.8s" repeatCount="indefinite"/>
    </text>
    <text x="70" fill="#9b59b6">
      <tspan>1</tspan><animate attributeName="y" from="-150" to="270" dur="2.8s" repeatCount="indefinite"/>
    </text>
    <text x="95" fill="#9b59b6" opacity="0.5">
      <tspan>0</tspan><animate attributeName="y" from="-170" to="250" dur="3.5s" repeatCount="indefinite"/>
    </text>
    <text x="95" fill="#00ff41" opacity="0.3">
      <tspan>1</tspan><animate attributeName="y" from="-130" to="290" dur="3.5s" repeatCount="indefinite"/>
    </text>
    <text x="1080" fill="#00ff41" opacity="0.5">
      <tspan>1</tspan><animate attributeName="y" from="-200" to="220" dur="2.6s" repeatCount="indefinite"/>
    </text>
    <text x="1080" fill="#9b59b6">
      <tspan>0</tspan><animate attributeName="y" from="-150" to="270" dur="2.6s" repeatCount="indefinite"/>
    </text>
    <text x="1105" fill="#9b59b6" opacity="0.6">
      <tspan>1</tspan><animate attributeName="y" from="-180" to="240" dur="3.2s" repeatCount="indefinite"/>
    </text>
    <text x="1105" fill="#00ff41" opacity="0.4">
      <tspan>0</tspan><animate attributeName="y" from="-140" to="280" dur="3.2s" repeatCount="indefinite"/>
    </text>
    <text x="1130" fill="#00ff41" opacity="0.3">
      <tspan>1</tspan><animate attributeName="y" from="-200" to="220" dur="2.9s" repeatCount="indefinite"/>
    </text>
    <text x="1130" fill="#9b59b6" opacity="0.7">
      <tspan>1</tspan><animate attributeName="y" from="-160" to="260" dur="2.9s" repeatCount="indefinite"/>
    </text>
    <text x="1155" fill="#9b59b6" opacity="0.5">
      <tspan>0</tspan><animate attributeName="y" from="-170" to="250" dur="3.7s" repeatCount="indefinite"/>
    </text>
  </g>

  <!-- Horizontal scan line animations -->
  <rect x="0" width="1200" height="1.5" fill="#9b59b6" opacity="0.4">
    <animate attributeName="y" from="0" to="200" dur="4s" repeatCount="indefinite"/>
  </rect>
  <rect x="0" width="1200" height="1" fill="#00ff41" opacity="0.2">
    <animate attributeName="y" from="0" to="200" dur="6s" repeatCount="indefinite"/>
  </rect>

  <!-- Central glowing name -->
  <text x="600" y="85" text-anchor="middle"
        font-family="'Courier New', monospace" font-size="54" font-weight="bold"
        fill="#ffffff" filter="url(#glow2)" letter-spacing="8">
    DIPESH SHRESTHA
    <animate attributeName="opacity" values="1;0.85;1;0.9;1" dur="4s" repeatCount="indefinite"/>
  </text>

  <!-- Subtitle -->
  <text x="600" y="120" text-anchor="middle"
        font-family="'Courier New', monospace" font-size="15"
        fill="#9b59b6" filter="url(#glow)" letter-spacing="5">
    AI / ML ENGINEER  ·  FULL STACK DEVELOPER
  </text>

  <!-- Divider line with pulse -->
  <line x1="200" y1="148" x2="1000" y2="148" stroke="#9b59b6" stroke-width="0.8" opacity="0.6">
    <animate attributeName="opacity" values="0.6;0.2;0.6" dur="3s" repeatCount="indefinite"/>
  </line>

  <!-- Corner brackets -->
  <g stroke="#00ff41" stroke-width="1.5" fill="none" opacity="0.7">
    <polyline points="10,10 10,30 30,30"/>
    <polyline points="1190,10 1190,30 1170,30"/>
    <polyline points="10,190 10,170 30,170"/>
    <polyline points="1190,190 1190,170 1170,170"/>
  </g>

  <!-- Status indicators -->
  <circle cx="200" cy="170" r="4" fill="#00ff41">
    <animate attributeName="opacity" values="1;0.2;1" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <text x="212" y="174" font-family="'Courier New', monospace" font-size="10" fill="#00ff41" opacity="0.8">SYSTEM ONLINE</text>

  <circle cx="850" cy="170" r="4" fill="#9b59b6">
    <animate attributeName="opacity" values="1;0.2;1" dur="2s" repeatCount="indefinite"/>
  </circle>
  <text x="862" y="174" font-family="'Courier New', monospace" font-size="10" fill="#9b59b6" opacity="0.8">BUILDING...</text>
</svg>
</div>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    BADGES & TAGLINE                         -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">
<br/>

<img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=18&pause=1200&color=9b59b6&center=true&vCenter=true&width=560&lines=Python+%7C+PHP+%7C+Java;AI+%26+ML+Enthusiast;Full+Stack+Developer;Backend+Specialist;Currently%3A+Pneumonia+Detection+from+X-Ray" alt="Typing SVG"/>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=dipeshshrestha16&label=VIEWS&color=9b59b6&style=flat-square&labelColor=0D1117"/>
&nbsp;
<img src="https://img.shields.io/github/followers/dipeshshrestha16?label=FOLLOWERS&style=flat-square&color=9b59b6&labelColor=0D1117"/>
&nbsp;
<img src="https://img.shields.io/badge/STATUS-LEARNING-00ff41?style=flat-square&labelColor=0D1117"/>
&nbsp;
<img src="https://img.shields.io/badge/FOCUS-AI%2FML-9b59b6?style=flat-square&labelColor=0D1117"/>

</div>

---

## ⚡ About Me

<img align="right" alt="Coding" width="360" src="https://c.tenor.com/OZbNvHWVgakAAAAC/programming-coding.gif"/>

```python
class Dipesh:
    name     = "Dipesh Shrestha"
    location = "Nepal 🇳🇵"
    current  = "Pneumonia Detection · Chest X-Ray AI"
    learning = ["Advanced AI/ML", "Backend Optimizations"]

    stack = {
        "languages"  : ["Python", "PHP", "Java"],
        "frameworks" : ["Flask", "Django", "Laravel"],
        "cloud"      : ["AWS"],
        "cms"        : ["WordPress"],
    }

    contact = {
        "email"    : "dipeshresthaaa@gmail.com",
        "phone"    : "+977-9847904448",
        "linkedin" : "dipesh-shrestha-526873259",
        "instagram": "dipeshshrestha_16",
    }
```

<br clear="right"/>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,php,java&theme=dark&perline=3"/>

**Frameworks & Platforms**

<img src="https://skillicons.dev/icons?i=flask,django,laravel,aws,wordpress&theme=dark&perline=5"/>

</div>

---

## 🚀 Featured Projects

<div align="center">

| # | Project | Type | Link |
|:-:|:--------|:----:|:----:|
| `01` | **Facial Expression → Music Suggestion** | `ML` `Computer Vision` | [→](https://github.com/dipeshshrestha16/Facial-Expression-based-Music-Recommendation.git) |
| `02` | **Facial Expression + Speech Recognition** | `AI` `NLP` | [→](https://github.com/dipeshshrestha16/ML-and-AI.git) |
| `03` | **Apple Stock Price Prediction** | `ML` `Finance` | [→](https://github.com/dipeshshrestha16/Apple-Stock-Price-Prediction) |
| `04` | **Pneumonia Detection** ⚡ *active* | `Deep Learning` `Medical` | [→](https://github.com/dipeshshrestha16/Pneumonia-Detection) |
| `05` | **Café Management System** *(FYP)* | `Full Stack` `POS` | [→](https://github.com/dipeshshrestha16/Kaffe-Management-System.git) |

</div>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=dipeshshrestha16&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=9b59b6&icon_color=00ff41&text_color=c9d1d9" width="48%"/>
  <img src="https://streak-stats.demolab.com/?user=dipeshshrestha16&theme=dark&hide_border=true&background=0D1117&ring=9b59b6&fire=00ff41&currStreakLabel=9b59b6&sideNums=9b59b6" width="48%"/>
  <br/><br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dipeshshrestha16&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&title_color=9b59b6&text_color=c9d1d9&langs_count=8" width="40%"/>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=dipeshshrestha16&theme=dark&hide_border=true&bg_color=0D1117&color=9b59b6&line=00ff41&point=ffffff&area=true" width="56%"/>
</div>

---

## 🤝 Connect

<div align="center">
<br/>

<a href="https://www.linkedin.com/in/dipesh-shrestha-526873259/">
  <img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=0077B5&labelColor=0D1117"/>
</a>
&nbsp;
<a href="https://www.instagram.com/dipeshshrestha_16/">
  <img src="https://img.shields.io/badge/Instagram-0D1117?style=for-the-badge&logo=instagram&logoColor=E4405F&labelColor=0D1117"/>
</a>
&nbsp;
<a href="mailto:dipeshresthaaa@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-0D1117?style=for-the-badge&logo=gmail&logoColor=D14836&labelColor=0D1117"/>
</a>

<br/><br/>
</div>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    ANIMATED SVG FOOTER                      -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">
<svg width="100%" height="100" viewBox="0 0 1200 100" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#000000"/>
      <stop offset="50%" style="stop-color:#0a001a"/>
      <stop offset="100%" style="stop-color:#000000"/>
    </linearGradient>
    <filter id="glowF">
      <feGaussianBlur stdDeviation="2.5" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="1200" height="100" fill="url(#footerGrad)"/>

  <!-- Scan line going up -->
  <rect x="0" width="1200" height="1" fill="#9b59b6" opacity="0.4">
    <animate attributeName="y" from="100" to="0" dur="5s" repeatCount="indefinite"/>
  </rect>

  <!-- Binary rain -->
  <g font-family="'Courier New', monospace" font-size="10" opacity="0.3">
    <text x="40" fill="#9b59b6"><tspan>01</tspan><animate attributeName="y" from="-20" to="120" dur="2s" repeatCount="indefinite"/></text>
    <text x="80" fill="#00ff41"><tspan>10</tspan><animate attributeName="y" from="-20" to="120" dur="2.6s" repeatCount="indefinite"/></text>
    <text x="120" fill="#9b59b6"><tspan>01</tspan><animate attributeName="y" from="-20" to="120" dur="1.9s" repeatCount="indefinite"/></text>
    <text x="1040" fill="#00ff41"><tspan>10</tspan><animate attributeName="y" from="-20" to="120" dur="2.3s" repeatCount="indefinite"/></text>
    <text x="1080" fill="#9b59b6"><tspan>01</tspan><animate attributeName="y" from="-20" to="120" dur="2.7s" repeatCount="indefinite"/></text>
    <text x="1120" fill="#00ff41"><tspan>10</tspan><animate attributeName="y" from="-20" to="120" dur="2.1s" repeatCount="indefinite"/></text>
  </g>

  <!-- Top border -->
  <line x1="0" y1="1" x2="1200" y2="1" stroke="#9b59b6" stroke-width="0.8" opacity="0.4"/>

  <!-- Footer text -->
  <text x="600" y="52" text-anchor="middle"
        font-family="'Courier New', monospace" font-size="16" font-weight="bold"
        fill="#ffffff" filter="url(#glowF)" letter-spacing="4">
    Thanks for visiting! Drop a ★ if something helped.
    <animate attributeName="opacity" values="1;0.7;1" dur="3s" repeatCount="indefinite"/>
  </text>

  <!-- Corner brackets -->
  <g stroke="#9b59b6" stroke-width="1.2" fill="none" opacity="0.5">
    <polyline points="8,8 8,22 22,22"/>
    <polyline points="1192,8 1192,22 1178,22"/>
    <polyline points="8,92 8,78 22,78"/>
    <polyline points="1192,92 1192,78 1178,78"/>
  </g>

  <!-- Pulsing dots -->
  <circle cx="560" cy="75" r="2.5" fill="#9b59b6">
    <animate attributeName="opacity" values="1;0.1;1" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="600" cy="75" r="2.5" fill="#00ff41">
    <animate attributeName="opacity" values="1;0.1;1" dur="2s" begin="0.3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="640" cy="75" r="2.5" fill="#9b59b6">
    <animate attributeName="opacity" values="1;0.1;1" dur="2s" begin="0.6s" repeatCount="indefinite"/>
  </circle>
</svg>
</div>
