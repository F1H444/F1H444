[snake.yml](https://github.com/user-attachments/files/35494225/snake.yml)

<div align="center">

<img src="https://capsul# Simpan sebagai: .github/workflows/snake.yml  (di repo F1H444/F1H444)
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"   # tiap 12 jam
  workflow_dispatch:          # bisa dijalankan manual
  push:
    branches: [main]

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
e-render.vercel.app/api?type=waving&color=0:0D0221,40:7B2FF7,75:FF2A6D,100:F9C80E&height=150&section=header&animation=fadeIn" width="100%" alt="" />

```text
███████╗██╗██╗  ██╗ █████╗ 
██╔════╝██║██║  ██║██╔══██╗
█████╗  ██║███████║███████║
██╔══╝  ██║██╔══██║██╔══██║
██║     ██║██║  ██║██║  ██║
╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝
```

<img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=12&duration=3000&pause=900&color=05D9E8&center=true&vCenter=true&width=800&height=40&lines=INSERT+COIN...;SOFTWARE+ENGINEERING+STUDENT;WEB+%2B+GAME+%2B+UI%2FUX;SHIPPING+REAL+PROJECTS+FOR+REAL+BUSINESSES;LEARNING+BY+DOING%2C+GROWING+BY+SHARING" alt="Fiha Aridhoi" />

<br/>

<img src="https://img.shields.io/badge/PLAYER-FIHA_ARIDHOI-FF2A6D?style=flat-square&labelColor=0D0221" alt="" />
<img src="https://img.shields.io/badge/CLASS-FULLSTACK_%2B_GAME_DEV-7B2FF7?style=flat-square&labelColor=0D0221" alt="" />
<img src="https://img.shields.io/badge/BASE-SURABAYA-05D9E8?style=flat-square&labelColor=0D0221" alt="" />
<img src="https://img.shields.io/badge/STATUS-OPEN_FOR_COLLAB-F9C80E?style=flat-square&labelColor=0D0221" alt="" />
<img src="https://komarev.com/ghpvc/?username=F1H444&color=7B2FF7&style=flat-square&label=PLAYERS&labelColor=0D0221" alt="" />

</div>

<br/>

## `> boot.sh`

```console
fiha@surabaya:~$ whoami
Fiha Aridhoi · software engineering student · founder @ ProgMan

fiha@surabaya:~$ cat now.txt
> web     React · Next.js · Laravel · Tailwind
> game    Godot · GDScript (2D, prototyping cepat)
> design  Figma (wireframe → prototype → handoff)
> belajar animasi tingkat lanjut, system design, testing

fiha@surabaya:~$ cat skills.log
Frontend    [██████████████░░░░░░]  70%
Backend     [███████████░░░░░░░░░]  55%
Game Dev    [████████████░░░░░░░░]  60%
UI/UX       [█████████████░░░░░░░]  65%
System Des. [██████░░░░░░░░░░░░░░]  30%   << sedang di-grind

fiha@surabaya:~$ cat quests.txt
[x] rilis ProgMan: jasa website & aplikasi untuk bisnis
[x] bikin game pertama di Godot
[~] kuasai animasi UI (Framer Motion, GSAP)
[~] bangun 1 project fullstack end-to-end dengan auth + dashboard
[ ] kontribusi ke open source
[ ] ikut game jam

fiha@surabaya:~$ status
[ OPEN FOR COLLAB ] ▮
```

<br/>

<div align="center">

## ⚔️ INVENTORY

<img src="https://skillicons.dev/icons?i=js,ts,py,php,html,css&theme=dark" alt="Bahasa" />
<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,laravel,vite&theme=dark" alt="Framework" />
<br/>
<img src="https://skillicons.dev/icons?i=mysql,postgres,supabase,firebase&theme=dark" alt="Database" />
<br/>
<img src="https://skillicons.dev/icons?i=godot,figma,git,github,vscode,postman,vercel&theme=dark" alt="Tools" />

<br/><br/>

<table>
<tr>
<td align="center" width="25%"><b><code>WEB</code></b><br/><sub>landing page · dashboard<br/>company profile · e-commerce</sub></td>
<td align="center" width="25%"><b><code>GAME</code></b><br/><sub>2D prototype · mekanik inti<br/>game loop · UI in-game</sub></td>
<td align="center" width="25%"><b><code>DESIGN</code></b><br/><sub>wireframe · design system<br/>prototype interaktif</sub></td>
<td align="center" width="25%"><b><code>BUSINESS</code></b><br/><sub>jasa digital via ProgMan<br/>dari brief sampai deploy</sub></td>
</tr>
</table>

<br/>

<a href="https://progman.is-a.dev/">
  <img src="https://img.shields.io/badge/▶_PROGMAN-jasa_website_%26_aplikasi_untuk_bisnis-FF2A6D?style=for-the-badge&labelColor=0D0221" alt="ProgMan" />
</a>

<br/><br/>

## 🐍 SNAKE.EXE

<img src="https://raw.githubusercontent.com/F1H444/F1H444/output/github-contribution-grid-snake-dark.svg" width="95%" alt="Ular memakan grafik kontribusi" />

<br/><br/>

## 📊 HIGH SCORE

<img height="165" src="https://github-readme-stats.vercel.app/api?username=F1H444&show_icons=true&bg_color=0D0221&title_color=FF2A6D&icon_color=F9C80E&text_color=05D9E8&border_color=7B2FF7&border_radius=0&count_private=true&include_all_commits=true" alt="Statistik" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=F1H444&layout=compact&bg_color=0D0221&title_color=FF2A6D&text_color=05D9E8&border_color=7B2FF7&border_radius=0&hide_border=false" alt="Bahasa teratas" />

<br/>

<img height="165" src="https://streak-stats.demolab.com?user=F1H444&background=0D0221&border=7B2FF7&ring=FF2A6D&fire=F9C80E&currStreakNum=05D9E8&currStreakLabel=F9C80E&sideNums=05D9E8&sideLabels=FF2A6D&dates=7B2FF7&border_radius=0" alt="Streak" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=F1H444&bg_color=0D0221&color=05D9E8&line=FF2A6D&point=F9C80E&area=true&area_color=7B2FF7&hide_border=true&radius=0" width="95%" alt="Grafik aktivitas" />

<br/><br/>

## 🏆 ACHIEVEMENTS

<img src="https://github-profile-trophy.vercel.app/?username=F1H444&theme=onedark&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" alt="Trofi" />

<br/><br/>

## 🎮 LEVEL SELECT

</div>

<!-- Ganti nama repo di bawah dengan repo pilihanmu. Kartu otomatis menampilkan deskripsi, bintang, dan bahasa. -->

<div align="center">

<a href="https://github.com/F1H444/NAMA-REPO-1"><img src="https://github-readme-stats.vercel.app/api/pin/?username=F1H444&repo=NAMA-REPO-1&bg_color=0D0221&title_color=FF2A6D&text_color=05D9E8&icon_color=F9C80E&border_color=7B2FF7&border_radius=0" alt="Project 1" /></a>
<a href="https://github.com/F1H444/NAMA-REPO-2"><img src="https://github-readme-stats.vercel.app/api/pin/?username=F1H444&repo=NAMA-REPO-2&bg_color=0D0221&title_color=FF2A6D&text_color=05D9E8&icon_color=F9C80E&border_color=7B2FF7&border_radius=0" alt="Project 2" /></a>
<br/>
<a href="https://github.com/F1H444/NAMA-REPO-3"><img src="https://github-readme-stats.vercel.app/api/pin/?username=F1H444&repo=NAMA-REPO-3&bg_color=0D0221&title_color=FF2A6D&text_color=05D9E8&icon_color=F9C80E&border_color=7B2FF7&border_radius=0" alt="Project 3" /></a>
<a href="https://github.com/F1H444/NAMA-REPO-4"><img src="https://github-readme-stats.vercel.app/api/pin/?username=F1H444&repo=NAMA-REPO-4&bg_color=0D0221&title_color=FF2A6D&text_color=05D9E8&icon_color=F9C80E&border_color=7B2FF7&border_radius=0" alt="Project 4" /></a>

<br/><br/>

## 🗺️ ROADMAP 2026

</div>

| Level | Misi | Status |
| :---: | :--- | :---: |
| `01` | Rilis & kembangkan **ProgMan**, cari klien pertama sampai berulang | 🟢 jalan |
| `02` | Selesaikan 1 game Godot sampai bisa dimainkan publik (itch.io) | 🟡 proses |
| `03` | Kuasai animasi UI tingkat lanjut untuk portofolio | 🟡 proses |
| `04` | Bangun project fullstack dengan auth, dashboard, dan deploy | 🟡 proses |
| `05` | Pelajari system design dasar: caching, queue, scaling | 🔴 antre |
| `06` | Kontribusi pertama ke open source | 🔴 antre |

<br/>

<div align="center">

## 💬 PLAYER NOTES

<sub><code>"ship small, ship often, learn loudly."</code></sub>

<br/><br/>

<table>
<tr>
<td align="center"><b>🤝 Terbuka untuk</b><br/><sub>kolaborasi project · game jam<br/>freelance web · diskusi UI/UX</sub></td>
<td align="center"><b>🎯 Lagi cari</b><br/><sub>teman belajar · mentor<br/>project open source ramah pemula</sub></td>
<td align="center"><b>⚡ Tanya aku soal</b><br/><sub>React · Next.js · Laravel<br/>Godot · Figma · ProgMan</sub></td>
</tr>
</table>

<br/>

<a href="https://github.com/F1H444"><img src="https://img.shields.io/badge/GitHub-F1H444-7B2FF7?style=for-the-badge&logo=github&logoColor=white&labelColor=0D0221" alt="GitHub" /></a>
<a href="https://progman.is-a.dev/"><img src="https://img.shields.io/badge/Website-ProgMan-05D9E8?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=0D0221" alt="ProgMan" /></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F9C80E,30:FF2A6D,65:7B2FF7,100:0D0221&height=110&section=footer&text=THANKS%20FOR%20PLAYING&fontSize=20&fontColor=FFFFFF&fontAlignY=70&animation=twinkling" width="100%" alt="" />

</div>
