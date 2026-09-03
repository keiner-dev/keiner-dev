<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="720" viewBox="0 0 1200 720">
  <defs>
    <filter id="glow">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Particle stream 1 with extended trails -->
  <!-- Trail 1 - Multiple layers for longer trail effect -->
  <circle cx="150" cy="450" r="2.5" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.05">
    <animate attributeName="cy" from="450" to="-70" dur="4s" repeatCount="indefinite" />
  </circle>
  <circle cx="150" cy="440" r="2.8" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.1">
    <animate attributeName="cy" from="440" to="-60" dur="4s" repeatCount="indefinite" />
  </circle>
  <circle cx="150" cy="430" r="3" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.15">
    <animate attributeName="cy" from="430" to="-50" dur="4s" repeatCount="indefinite" />
  </circle>
  <circle cx="150" cy="420" r="3" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.2">
    <animate attributeName="cy" from="420" to="-40" dur="4s" repeatCount="indefinite" />
  </circle>
  <circle cx="150" cy="410" r="2.8" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.25">
    <animate attributeName="cy" from="410" to="-30" dur="4s" repeatCount="indefinite" />
  </circle>
  <circle cx="150" cy="400" r="2" fill="#00d4ff">
    <animate attributeName="cy" from="400" to="0" dur="4s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0;1;1;0" dur="4s" repeatCount="indefinite" />
    <animate attributeName="r" values="2;2;1;0" dur="4s" repeatCount="indefinite" />
  </circle>

  <!-- Trail 2 -->
  <circle cx="200" cy="455" r="2.5" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.05">
    <animate attributeName="cy" from="455" to="-85" dur="5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="200" to="238" dur="5s" repeatCount="indefinite" />
  </circle>
  <circle cx="200" cy="445" r="2.8" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.1">
    <animate attributeName="cy" from="445" to="-75" dur="5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="200" to="237" dur="5s" repeatCount="indefinite" />
  </circle>
  <circle cx="200" cy="430" r="3" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.15">
    <animate attributeName="cy" from="430" to="-60" dur="5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="200" to="236" dur="5s" repeatCount="indefinite" />
  </circle>
  <circle cx="200" cy="420" r="3" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.2">
    <animate attributeName="cy" from="420" to="-50" dur="5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="200" to="235" dur="5s" repeatCount="indefinite" />
  </circle>
  <circle cx="200" cy="410" r="2.8" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.25">
    <animate attributeName="cy" from="410" to="-40" dur="5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="200" to="234" dur="5s" repeatCount="indefinite" />
  </circle>
  <circle cx="200" cy="400" r="2" fill="#00d4ff">
    <animate attributeName="cy" from="400" to="-20" dur="5s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0;1;1;0" dur="5s" repeatCount="indefinite" />
    <animate attributeName="r" values="2;2;1;0" dur="5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="200" to="230" dur="5s" repeatCount="indefinite" />
  </circle>

  <!-- Trail 3 -->
  <circle cx="300" cy="450" r="2.5" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.05">
    <animate attributeName="cy" from="450" to="-65" dur="4.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="300" cy="440" r="2.8" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.1">
    <animate attributeName="cy" from="440" to="-55" dur="4.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="300" cy="430" r="3" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.15">
    <animate attributeName="cy" from="430" to="-45" dur="4.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="300" cy="420" r="3" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.2">
    <animate attributeName="cy" from="420" to="-35" dur="4.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="300" cy="410" r="2.8" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.25">
    <animate attributeName="cy" from="410" to="-25" dur="4.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="300" cy="400" r="2" fill="#00d4ff">
    <animate attributeName="cy" from="400" to="0" dur="4.5s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0;1;1;0" dur="4.5s" repeatCount="indefinite" />
    <animate attributeName="r" values="2;2;1;0" dur="4.5s" repeatCount="indefinite" />
  </circle>

  <!-- Trail 4 -->
  <circle cx="450" cy="455" r="2.5" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.05">
    <animate attributeName="cy" from="455" to="-90" dur="5.5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="450" to="488" dur="5.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="450" cy="445" r="2.8" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.1">
    <animate attributeName="cy" from="445" to="-80" dur="5.5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="450" to="487" dur="5.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="450" cy="432" r="3" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.15">
    <animate attributeName="cy" from="432" to="-67" dur="5.5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="450" to="486" dur="5.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="450" cy="420" r="3" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.2">
    <animate attributeName="cy" from="420" to="-55" dur="5.5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="450" to="485" dur="5.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="450" cy="410" r="2.8" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.25">
    <animate attributeName="cy" from="410" to="-45" dur="5.5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="450" to="484" dur="5.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="450" cy="400" r="2" fill="#00d4ff">
    <animate attributeName="cy" from="400" to="-30" dur="5.5s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0;1;1;0" dur="5.5s" repeatCount="indefinite" />
    <animate attributeName="r" values="2;2;1;0" dur="5.5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="450" to="480" dur="5.5s" repeatCount="indefinite" />
  </circle>

  <!-- Particle stream 2 with extended trails -->
  <!-- Trail 5 -->
  <circle cx="850" cy="450" r="2.5" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.05">
    <animate attributeName="cy" from="450" to="-75" dur="6s" repeatCount="indefinite" />
    <animate attributeName="cx" from="850" to="812" dur="6s" repeatCount="indefinite" />
  </circle>
  <circle cx="850" cy="440" r="2.8" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.1">
    <animate attributeName="cy" from="440" to="-65" dur="6s" repeatCount="indefinite" />
    <animate attributeName="cx" from="850" to="813" dur="6s" repeatCount="indefinite" />
  </circle>
  <circle cx="850" cy="430" r="3" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.15">
    <animate attributeName="cy" from="430" to="-55" dur="6s" repeatCount="indefinite" />
    <animate attributeName="cx" from="850" to="814" dur="6s" repeatCount="indefinite" />
  </circle>
  <circle cx="850" cy="420" r="3" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.2">
    <animate attributeName="cy" from="420" to="-45" dur="6s" repeatCount="indefinite" />
    <animate attributeName="cx" from="850" to="815" dur="6s" repeatCount="indefinite" />
  </circle>
  <circle cx="850" cy="410" r="2.8" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.25">
    <animate attributeName="cy" from="410" to="-35" dur="6s" repeatCount="indefinite" />
    <animate attributeName="cx" from="850" to="816" dur="6s" repeatCount="indefinite" />
  </circle>
  <circle cx="850" cy="400" r="2" fill="#00d4ff">
    <animate attributeName="cy" from="400" to="0" dur="6s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0;1;1;0" dur="6s" repeatCount="indefinite" />
    <animate attributeName="r" values="2;2;1;0" dur="6s" repeatCount="indefinite" />
    <animate attributeName="cx" from="850" to="820" dur="6s" repeatCount="indefinite" />
  </circle>

  <!-- Trail 6 -->
  <circle cx="950" cy="455" r="2.5" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.05">
    <animate attributeName="cy" from="455" to="-80" dur="5.5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="950" to="912" dur="5.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="950" cy="445" r="2.8" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.1">
    <animate attributeName="cy" from="445" to="-70" dur="5.5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="950" to="913" dur="5.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="950" cy="432" r="3" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.15">
    <animate attributeName="cy" from="432" to="-57" dur="5.5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="950" to="914" dur="5.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="950" cy="420" r="3" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.2">
    <animate attributeName="cy" from="420" to="-45" dur="5.5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="950" to="915" dur="5.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="950" cy="410" r="2.8" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.25">
    <animate attributeName="cy" from="410" to="-35" dur="5.5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="950" to="916" dur="5.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="950" cy="400" r="2" fill="#00d4ff">
    <animate attributeName="cy" from="400" to="-20" dur="5.5s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0;1;1;0" dur="5.5s" repeatCount="indefinite" />
    <animate attributeName="r" values="2;2;1;0" dur="5.5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="950" to="920" dur="5.5s" repeatCount="indefinite" />
  </circle>

  <!-- Trail 7 -->
  <circle cx="1050" cy="450" r="2.5" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.05">
    <animate attributeName="cy" from="450" to="-75" dur="6.5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="1050" to="1012" dur="6.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="1050" cy="440" r="2.8" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.1">
    <animate attributeName="cy" from="440" to="-65" dur="6.5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="1050" to="1013" dur="6.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="1050" cy="430" r="3" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.15">
    <animate attributeName="cy" from="430" to="-55" dur="6.5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="1050" to="1014" dur="6.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="1050" cy="420" r="3" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.2">
    <animate attributeName="cy" from="420" to="-45" dur="6.5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="1050" to="1015" dur="6.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="1050" cy="410" r="2.8" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.25">
    <animate attributeName="cy" from="410" to="-35" dur="6.5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="1050" to="1016" dur="6.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="1050" cy="400" r="2" fill="#00d4ff">
    <animate attributeName="cy" from="400" to="0" dur="6.5s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0;1;1;0" dur="6.5s" repeatCount="indefinite" />
    <animate attributeName="r" values="2;2;1;0" dur="6.5s" repeatCount="indefinite" />
    <animate attributeName="cx" from="1050" to="1020" dur="6.5s" repeatCount="indefinite" />
  </circle>

  <!-- Next.js Logo (left side) - Static with official Next.js N design -->
  <g>
    <circle cx="320" cy="135" r="82" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.3" />
    <circle cx="320" cy="135" r="58" fill="none" stroke="#ffffff" stroke-width="3" />
    <text x="320" y="152" font-size="52" font-weight="bold" fill="#cbd5e1" text-anchor="middle">N</text>
  </g>

  <!-- React Logo (right side) - Static with proper design -->
  <g>
    <!-- Outer circles for reference -->
    <circle cx="880" cy="135" r="82" fill="none" stroke="#61dafb" stroke-width="1" opacity="0.24" />
    <!-- Orbital paths - three ellipses at 45 degree angles -->
    <ellipse cx="880" cy="135" rx="48" ry="20" fill="none" stroke="#61dafb" stroke-width="3.5" opacity="0.9" />
    <ellipse cx="880" cy="135" rx="48" ry="20" fill="none" stroke="#61dafb" stroke-width="3.5" opacity="0.9" transform="rotate(60 880 135)" />
    <ellipse cx="880" cy="135" rx="48" ry="20" fill="none" stroke="#61dafb" stroke-width="3.5" opacity="0.9" transform="rotate(120 880 135)" />
    <!-- Electron dots on orbits -->
    <circle cx="928" cy="135" r="5" fill="#61dafb" />
    <circle cx="844" cy="165" r="5" fill="#61dafb" />
    <circle cx="910" cy="99" r="5" fill="#61dafb" />
    <!-- Center nucleus -->
    <circle cx="880" cy="135" r="10" fill="#61dafb" />
  </g>

  <!-- Main title -->
  <text x="600" y="356" font-size="66" font-weight="bold" fill="#cbd5e1" text-anchor="middle" letter-spacing="2">KEINER RAMIREZ</text>

  <!-- Subtitle -->
  <text x="600" y="414" font-size="26" fill="#cbd5e1" text-anchor="middle" letter-spacing="1">Software Developer</text>

  <!-- Supporting line -->
  <text x="600" y="448" font-size="15" fill="#9fb7c8" text-anchor="middle" letter-spacing="1.5">Clean architecture • Team collaboration • Scrum</text>

  <!-- Bottom accent line -->
  <line x1="300" y1="480" x2="900" y2="480" stroke="#00d4ff" stroke-width="3" opacity="0.5">
    <animate attributeName="opacity" values="0.5;0.8;0.5" dur="2s" repeatCount="indefinite" />
  </line>

  <!-- Tech keywords -->
  <text x="600" y="520" font-size="16" fill="#00d4ff" text-anchor="middle" letter-spacing="3" filter="url(#glow)">REACT • TYPESCRIPT • NEXTJS</text>
</svg>

---

### 🛠️ Tech Stack 

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/javascript-yellow?style=for-the-badge&logo=javascript" alt=javascript/>
</p>

---


<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:001220,50:004e89,100:001220&height=100&section=footer" />



## Hi there 👋
my name is keiner ramirez
Passionate about technology, programming, and open-source development.
I enjoy learning new tools, building useful projects, and collaborating with developers around the world.


Here are some ideas to get you started:

- 🔭 I’m currently working on ... improving my programming and Linux skills
- 🌱 I’m currently learning ... software development, open source, and system administration
- 👯 I’m looking to collaborate on ... open source projects and beginner-friendly development projects
- 🤔 I’m looking for help with ...  advanced programming concepts and large-scale projects
- 💬 Ask me about ...Linux, programming basics, and technology
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
