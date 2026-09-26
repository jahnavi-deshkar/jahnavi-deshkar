<div align="center">

<!-- Animated Header: Name with Glowing Dracula Orbs -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 130" width="100%">
  <defs>
    <!-- Dracula Gradient -->
    <linearGradient id="draculaGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#bd93f9" />
      <stop offset="50%" stop-color="#ff79c6" />
      <stop offset="100%" stop-color="#8be9fd" />
    </linearGradient>
    
    <radialGradient id="orbGlow1" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ff79c6" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#282a36" stop-opacity="0"/>
    </radialGradient>
    
    <radialGradient id="orbGlow2" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#8be9fd" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#282a36" stop-opacity="0"/>
    </radialGradient>
    
    <radialGradient id="orbGlow3" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#bd93f9" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#282a36" stop-opacity="0"/>
    </radialGradient>

    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="4" result="blur" />
      <feComposite in="SourceGraphic" in2="blur" operator="over" />
    </filter>
  </defs>

  <style>
    .bg { fill: #282a36; rx: 15px; }
    .name-text {
      font-family: 'Segoe UI', Ubuntu, 'Helvetica Neue', sans-serif;
      font-weight: 900;
      font-size: 52px;
      fill: url(#draculaGrad);
      letter-spacing: 2px;
    }
    .orb {
      animation: float 4s ease-in-out infinite alternate;
    }
    .orb-1 { animation-delay: 0s; }
    .orb-2 { animation-delay: -1.3s; }
    .orb-3 { animation-delay: -2.6s; }

    @keyframes float {
      0% { transform: translateY(0px) scale(1); }
      50% { transform: translateY(-10px) scale(1.1); }
      100% { transform: translateY(8px) scale(0.95); }
    }
  </style>

  <rect class="bg" width="100%" height="100%" />

  <!-- Animated Thinking Orbs Background -->
  <g filter="url(#glow)">
    <circle class="orb orb-1" cx="120" cy="40" r="35" fill="url(#orbGlow1)" />
    <circle class="orb orb-2" cx="780" cy="90" r="45" fill="url(#orbGlow2)" />
    <circle class="orb orb-3" cx="450" cy="25" r="30" fill="url(#orbGlow3)" />
    <circle class="orb orb-1" cx="820" cy="30" r="25" fill="url(#orbGlow1)" />
    <circle class="orb orb-2" cx="80" cy="95" r="30" fill="url(#orbGlow3)" />
  </g>

  <!-- Name Text -->
  <text x="50%" y="55%" dominant-baseline="middle" text-anchor="middle" class="name-text" filter="url(#glow)">
    Jahnavi Deshkar
  </text>
</svg>

<!-- Morphing Subtitle Animation -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 60" width="100%">
  <style>
    .sub-text {
      font-family: 'Segoe UI', Ubuntu, sans-serif;
      font-weight: 600;
      font-size: 20px;
      text-anchor: middle;
      dominant-baseline: middle;
    }
    
    .phrase1 { animation: cycle1 9s infinite ease-in-out; }
    .phrase2 { animation: cycle2 9s infinite ease-in-out; }
    .phrase3 { animation: cycle3 9s infinite ease-in-out; }

    @keyframes cycle1 {
      0%, 28% { opacity: 1; transform: translateY(0px); fill: #50fa7b; }
      33%, 100% { opacity: 0; transform: translateY(-10px); fill: #50fa7b; }
    }

    @keyframes cycle2 {
      0%, 31% { opacity: 0; transform: translateY(10px); fill: #8be9fd; }
      34%, 61% { opacity: 1; transform: translateY(0px); fill: #8be9fd; }
      66%, 100% { opacity: 0; transform: translateY(-10px); fill: #8be9fd; }
    }

    @keyframes cycle3 {
      0%, 64% { opacity: 0; transform: translateY(10px); fill: #ffb86c; }
      67%, 94% { opacity: 1; transform: translateY(0px); fill: #ffb86c; }
      98%, 100% { opacity: 0; transform: translateY(-10px); fill: #ffb86c; }
    }
  </style>

  <rect width="100%" height="100%" fill="#282a36" rx="10"/>
  
  <g id="morph-container">
    <text x="50%" y="50%" class="sub-text phrase1">Solving Problems</text>
    <text x="50%" y="50%" class="sub-text phrase2">Creating Balance</text>
    <text x="50%" y="50%" class="sub-text phrase3">Experiencing Reality</text>
  </g>
</svg>

</div>

---

### 🎓 About Me

* 🎓 **First-year BTech CSE** student at **MIT-World Peace University, Pune**
* 🧠 Currently learning **Advanced Python**, **Python frameworks**, **C++**, and **HTML**
* 🔭 Working on a bunch of Projects and making them for the hell of it!
  * 🔧 **ArmourKit** — A real-time, vision-based Mask & PPE-kit detection system.
  * 🔧 **StudyPod** — An interactive Student-Parent-Teacher collaborative learning platform.
* 🎬 **A Connoisseur** — Love-n-Respect Cinema, Music, and Books.
* 🤝 Interested in collaborating on **Python projects** and interesting ideas.

---

### 🐍 My Contribution Snake

<div align="center">
  <img src="https://raw.githubusercontent.com/jahnavi-deshkar/jahnavi-deshkar/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
</div>

---

### 📊 GitHub Statistics

<div align="center">

<a href="https://github.com/jahnavi-deshkar">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=jahnavi-deshkar&show_icons=true&theme=dracula&bg_color=282a36&title_color=bd93f9&text_color=f8f8f2&icon_color=ff79c6&border_color=44475a&hide_border=false" alt="GitHub Stats" />
</a>
<a href="https://github.com/jahnavi-deshkar">
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jahnavi-deshkar&layout=compact&theme=dracula&bg_color=282a36&title_color=bd93f9&text_color=f8f8f2&border_color=44475a&hide_border=false" alt="Top Languages" />
</a>

<br/><br/>

<a href="https://github.com/jahnavi-deshkar">
  <img src="https://github-profile-trophy.vercel.app/?username=jahnavi-deshkar&theme=dracula&column=6&margin-w=15&margin-h=15&no-bg=false&no-frame=false" alt="GitHub Trophies" />
</a>

</div>

---

### 🛠️ Tech Stack

<div align="center">

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=postgresql&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

### 🌱 Currently Learning

<div align="center">

| Area | Focus Topics |
| :--- | :--- |
| **Artificial Intelligence** | Foundations, Neural Networks |
| **Computer Vision** | OpenCV, Image Processing, Object Detection |
| **Data Science** | Pandas, NumPy, Data Analysis |
| **Generative AI** | LLM Architectures, Prompt Engineering |
| **Cloud Technologies** | AWS / Cloud Fundamentals |

</div>

---

### 🎯 Goals

- [ ] 🚀 Build meaningful AI/ML projects
- [ ] 🧠 Improve problem-solving skills
- [ ] 🤖 Learn more about Deep Learning
- [ ] 🌐 Contribute to Open Source
- [ ] 💼 Build a strong project portfolio
- [ ] 📚 Keep learning every day!

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=bd93f9&height=100&section=footer" width="100%"/>
</div>
