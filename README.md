<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0f0c29,50:302b63,100:24243e&height=220&section=header&text=Bhavya%20Jain&fontSize=60&fontColor=c4b5fd&fontAlignY=55&desc=Software%20Engineer%20%E2%80%A2%20Blockchain%20%E2%80%A2%20AI%20%2F%20ML&descSize=18&descAlignY=75&animation=twinkling" width="100%"/>

<br/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=16&duration=2800&pause=1200&color=818CF8&center=true&vCenter=true&width=600&lines=third-year+CSE+%40+SRM+University+Delhi-NCR;building+things+that+work+in+production;blockchain+%7C+full+stack+%7C+applied+AI;open+to+internships+%E2%80%94+let's+build+something+real)](https://git.io/typing-svg)

</div>

<br/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/-bhavya%20jain-1e1b4b?style=flat-square&logo=linkedin&logoColor=818cf8)](https://www.linkedin.com/in/bhavya-jain-28a89a311/)&nbsp;
[![Gmail](https://img.shields.io/badge/-bhavyajainfeb19@gmail.com-1e1b4b?style=flat-square&logo=gmail&logoColor=818cf8)](mailto:bhavyajainfeb19@gmail.com)&nbsp;
[![GitHub](https://img.shields.io/badge/-bhavya--tec-1e1b4b?style=flat-square&logo=github&logoColor=818cf8)](https://github.com/bhavya-tec)&nbsp;
![Views](https://komarev.com/ghpvc/?username=bhavya-tec&style=flat-square&color=1e1b4b&label=profile+views&labelColor=1e1b4b)

</div>

---

### &nbsp;`$ whoami`

```ts
const bhavya = {
  university : "SRM University Delhi-NCR",
  degree     : "B.Tech — Computer Science & Engineering",
  cgpa       : "8.97 / 10",
  year       : "3rd Year (2024–2028)",
  location   : "Modinagar, India",

  stack      : ["TypeScript", "React", "Node.js", "Flask", "PostgreSQL", "MongoDB"],
  interests  : ["Blockchain Systems", "Full Stack Products", "AI / Pathfinding", "AR"],
  currently  : "looking for SWE internships where I can own and ship real features",
};
```

I care about building complete systems — not just features. Whether it's a cryptographic ledger that makes fraud structurally impossible, an AI agent that outperforms humans at Snake, or a national hackathon from scratch — I see things through.

---

### &nbsp;`$ ls ./stack`

<div align="center">

<table>
<tr>
<td align="center" width="96"><sub><b>Languages</b></sub></td>
<td>
  <img src="https://skillicons.dev/icons?i=cpp,ts,python,js,html,css&theme=dark" />
</td>
</tr>
<tr>
<td align="center"><sub><b>Frontend</b></sub></td>
<td>
  <img src="https://skillicons.dev/icons?i=react,tailwind,nextjs&theme=dark" />
</td>
</tr>
<tr>
<td align="center"><sub><b>Backend</b></sub></td>
<td>
  <img src="https://skillicons.dev/icons?i=nodejs,express,flask,django&theme=dark" />
</td>
</tr>
<tr>
<td align="center"><sub><b>Databases</b></sub></td>
<td>
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,supabase&theme=dark" />
</td>
</tr>
<tr>
<td align="center"><sub><b>AI / ML</b></sub></td>
<td>
  <img src="https://skillicons.dev/icons?i=tensorflow,sklearn,opencv&theme=dark" />
</td>
</tr>
<tr>
<td align="center"><sub><b>Tooling</b></sub></td>
<td>
  <img src="https://skillicons.dev/icons?i=git,github,vercel,aws,unity,vscode&theme=dark" />
</td>
</tr>
</table>

</div>

---

### &nbsp;`$ cat ./projects`

<details>
<summary>&nbsp;<b>⬡ &nbsp;Blockchain-Based Academic Ledger</b>&nbsp;&nbsp;<code>Flask · PostgreSQL · JavaScript · SHA-256</code></summary>

<br/>

> Credential fraud shouldn't be possible by design. This system makes it structurally impossible.

Academic records are hashed with SHA-256 at issuance and stored immutably. Verification doesn't require contacting the issuing institution — the hash is the proof. External parties (employers, universities) authenticate instantly via QR code without needing portal access.

```
verification latency   →  < 1.3s end-to-end
concurrent queries     →  500+ (PostgreSQL indexing)
verification method    →  QR-encoded signed payload
fraud surface          →  eliminated at the data layer
```

**The hard part** wasn't the blockchain integration — it was designing a verification UX that works for non-technical stakeholders (HR teams, admissions offices) while keeping the cryptographic guarantees intact under the hood.

[![Repo](https://img.shields.io/badge/view%20repository-1e1b4b?style=flat-square&logo=github&logoColor=818cf8)](https://github.com/bhavya-tec)

</details>

<details>
<summary>&nbsp;<b>⬡ &nbsp;Snake AI — BFS Pathfinding Agent</b>&nbsp;&nbsp;<code>TypeScript · React · C++</code></summary>

<br/>

> An AI that plays Snake better than most humans — and lets you watch it think in real time.

Built a BFS pathfinding agent from scratch and benchmarked it against human players across three difficulty levels. The agent finds the shortest path to each food item deterministically; the interesting challenge was making the *visualization* legible at 60fps without frame drops.

```
path efficiency    →  91% (BFS agent)  vs  63% (avg human baseline)
render performance →  60fps, real-time path overlay
architecture       →  render loop decoupled from pathfinding compute
difficulty modes   →  3 levels, each with separate benchmarking
```

**The insight**: BFS guarantees shortest paths but not survival. The real engineering was the collision lookahead — the agent simulates N steps ahead to avoid paths that trap it, not just paths that are currently blocked.

[![Repo](https://img.shields.io/badge/view%20repository-1e1b4b?style=flat-square&logo=github&logoColor=818cf8)](https://github.com/bhavya-tec)

</details>

<details>
<summary>&nbsp;<b>⬡ &nbsp;AR Cultural Heritage Platform</b>&nbsp;&nbsp;<code>Unity · ARCore · ARKit · HTML · CSS · JS</code>&nbsp;&nbsp;<code>SIH</code></summary>

<br/>

> Heritage sites with an invisible layer of context — surfaced the moment you point your camera at them.

Built with a team of 6 for Smart India Hackathon. The platform overlays historical and cultural information onto real-world landmarks in AR. Selected top 3 of 17 institute-level submissions.

```
page load improvement  →  28% faster via progressive asset delivery
platform support       →  iOS (ARKit) + Android (ARCore)
team size              →  6 engineers
result                 →  top 3 / 17 — institute-level SIH
```

**The performance win**: 3D AR assets are large. The 28% load time improvement came from lazy-loading — low-poly anchor meshes load first, high-fidelity models stream in progressively as the user holds focus on a recognized site. Critical for heritage locations with poor connectivity.

[![Repo](https://img.shields.io/badge/view%20repository-1e1b4b?style=flat-square&logo=github&logoColor=818cf8)](https://github.com/bhavya-tec)

</details>

---

### &nbsp;`$ cat ./experience`

**Graphics Lead &nbsp;·&nbsp; Genesis — Web3 Society of SRM** &nbsp;&nbsp;`Aug 2025 – Present`

Owning visual identity for SRM's Web3 chapter. Everything that goes out — event creatives, campaigns, social posts — goes through me.

- 23+ assets designed across 4 events; ~1,400 student reach via Instagram & LinkedIn
- 34% engagement growth over 3 months through consistent visual branding
- Established design guidelines adopted across all society communications

<br/>

**Organizer &nbsp;·&nbsp; 0xGenIgnite National Hackathon** &nbsp;&nbsp;`May – Oct 2025` &nbsp;&nbsp;`NIT Goa`

End-to-end ownership of a national-scale hackathon — from outreach to logistics to execution day.

- 214 registered participants across 11 states; managed full event execution
- Outreach campaigns drove 83% of total registrations across 7 colleges
- Single point of contact between organizing team, venue, and participants

---

### &nbsp;`$ cat ./achievements`

<div align="center">

| &nbsp; | What | Result |
|:---:|:---|:---|
| 🏆 | Smart India Hackathon | Top 3 of 17 institute submissions |
| 🎯 | 0xGenIgnite Hackathon | National organizer · 214 participants · 11 states |
| 📈 | Genesis Web3 Society | 34% social engagement growth in 3 months |
| 🎓 | SRM University | CGPA 8.97 / 10 |
| 🤝 | Community | Campaigns reaching 1,400+ students |
| 🚀 | Outreach | 83% hackathon registrations driven across 7 colleges |

</div>

---

### &nbsp;`$ ls ./certifications`

<div align="center">

[![Tata](https://img.shields.io/badge/Tata%20Group%20×%20Forage-GenAI%20Powered%20Data%20Analytics-1e1b4b?style=for-the-badge&logo=tata&logoColor=818cf8)](https://www.theforage.com)&nbsp;
[![JPM](https://img.shields.io/badge/JPMorgan%20Chase%20×%20Forage-Software%20Engineering%20Simulation-1e1b4b?style=for-the-badge&logo=jpmorgan&logoColor=818cf8)](https://www.theforage.com)

[![Udemy](https://img.shields.io/badge/Udemy-Complete%20AI%20Engineer%20Bootcamp%202026-1e1b4b?style=for-the-badge&logo=udemy&logoColor=818cf8)](https://udemy.com)

</div>

---

### &nbsp;`$ cat ./analytics`

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=bhavya-tec&show_icons=true&hide_border=true&bg_color=0f0c29&title_color=c4b5fd&icon_color=818cf8&text_color=a5b4fc&ring_color=6d28d9&include_all_commits=true&count_private=true"/>
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bhavya-tec&layout=compact&hide_border=true&bg_color=0f0c29&title_color=c4b5fd&text_color=a5b4fc&langs_count=8"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=bhavya-tec&hide_border=true&background=0f0c29&stroke=302b63&ring=818cf8&fire=c4b5fd&currStreakNum=c4b5fd&sideNums=a5b4fc&currStreakLabel=c4b5fd&sideLabels=a5b4fc&dates=6d5acd" width="55%"/>

</div>

---

### &nbsp;`$ cat ./trophies`

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=bhavya-tec&theme=darkhub&no-frame=true&no-bg=true&margin-w=10&margin-h=10&column=6&rank=SECRET,SSS,SS,S,AAA,AA,A,B,C)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

### &nbsp;`$ git log --graph`

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=bhavya-tec&bg_color=0f0c29&color=c4b5fd&line=6d28d9&point=a5b4fc&area=true&area_color=302b63&hide_border=true&custom_title=contribution+activity)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

### &nbsp;`$ watch contribution-snake`

<div align="center">

<!--
  Snake is self-hosted in YOUR repo.
  Once you run the GitHub Action (see comment below analytics section),
  replace the src below with:
  https://raw.githubusercontent.com/bhavya-tec/bhavya-tec/output/github-contribution-grid-snake-dark.svg
-->

![Snake animation](https://raw.githubusercontent.com/bhavya-tec/bhavya-tec/output/github-contribution-grid-snake-dark.svg)

</div>

<!-- 
  ── SNAKE SETUP (one-time) ──────────────────────────────────────────────────
  1. In your bhavya-tec/bhavya-tec repo → Settings → Actions → General
     → set "Workflow permissions" to "Read and write permissions" → Save

  2. Create file: .github/workflows/snake.yml  with this content:

  name: Snake
  on:
    schedule:
      - cron: "0 0 * * *"
    workflow_dispatch:
  jobs:
    snake:
      runs-on: ubuntu-latest
      steps:
        - uses: Platane/snk@v3
          with:
            github_user_name: bhavya-tec
            outputs: |
              dist/github-contribution-grid-snake.svg
              dist/github-contribution-grid-snake-dark.svg?palette=github-dark
        - uses: crazy-max/ghaction-github-pages@v3
          with:
            target_branch: output
            build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

  3. Go to Actions tab → select "Snake" → click "Run workflow"
     The SVG will appear at the raw URL above within ~30 seconds.
  ────────────────────────────────────────────────────────────────────────── 
-->

---

### &nbsp;`$ cat ./now.yaml`

```yaml
# june 2026

learning:
  - advanced DSA + competitive programming in C++
  - system design for backend-heavy products
  - deep learning (TensorFlow → PyTorch transition)

building:
  - multi-institution support for the blockchain ledger
  - AI-assisted tools for student dev communities
  - end-to-end projects, not just MVPs

exploring:
  - LLM integration in full-stack web apps
  - smart contracts and dApp architecture
  - AR pipelines with Unity + ARCore

open_to:
  - SWE internships (full-stack / backend / AI)
  - open source — especially blockchain and dev tooling
  - hackathon teams building for real-world impact
```

---

### &nbsp;`$ ping ./connect`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/-connect%20on%20linkedin-1e1b4b?style=for-the-badge&logo=linkedin&logoColor=818cf8)](https://www.linkedin.com/in/bhavya-jain-28a89a311/)&nbsp;
[![Gmail](https://img.shields.io/badge/-send%20me%20an%20email-1e1b4b?style=for-the-badge&logo=gmail&logoColor=818cf8)](mailto:bhavyajainfeb19@gmail.com)&nbsp;
[![GitHub](https://img.shields.io/badge/-follow%20on%20github-1e1b4b?style=for-the-badge&logo=github&logoColor=818cf8)](https://github.com/bhavya-tec)

</div>

<br/>

<div align="center">
<sub><i>ship things that work &nbsp;·&nbsp; measure what matters &nbsp;·&nbsp; build systems you'd be proud to maintain a year from now</i></sub>
</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:24243e,50:302b63,100:0f0c29&height=140&section=footer&animation=twinkling" width="100%"/>
