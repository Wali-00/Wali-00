<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9A7,100:0077B5&height=220&section=header&text=Hi%20there,%20I'm%20Wali%20👋&fontSize=45&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=CSE%20Undergrad%20@%20United%20International%20University&descAlignY=55&descSize=18" alt="Header Banner" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00C9A7&center=true&vCenter=true&width=500&lines=Web+Developer;UI%2FUX+with+Figma;MySQL+%7C+Database+Design;Competitive+Programmer;Always+Learning+Something+New" alt="Typing SVG" />

<br>

<a href="https://www.linkedin.com/in/wali-ullah-7a4985378" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="mailto:waliu4574@gmail.com" target="_blank">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="https://www.facebook.com/people/Wali-Ullah-Al-Hafiz/pfbid0yPQMaMLVTp2s6dhQPdJdZrdNGPCqJhuN3aNeoXkVRxe8C5LmRsV9f1sbdbWpXkTYl/" target="_blank">
  <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook" />
</a>
<a href="https://www.instagram.com/wali_archive?igsh=ZWYydmp6emM3Zm5x" target="_blank">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
</a>
<a href="https://www.codechef.com/users/wali_69" target="_blank">
  <img src="https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white" alt="CodeChef" />
</a>

</div>

<br>

## 👨‍💻 About Me

<img align="right" width="320" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif" alt="Coding Animation">

```yaml
name: Wali
role: CSE Undergrad @ UIU
focus: Web Development, UI/UX Design, Databases
currently_learning: JavaScript (JS)
currently_building: Eco Tracking System
fun_fact: I love solving problems and writing clean code!
```

- 🎓 Studying **Computer Science and Engineering (CSE)** at **United International University**
- 💻 Exploring the world of **Web Development**
- 🎨 Recently picked up **Figma** for UI/UX design
- 🗄️ Learning **MySQL** and database design
- 🌱 Currently learning: **JavaScript (JS)**
- 🔭 Currently working on: **Eco Tracking System**
- ⚡ Fun fact: I love solving problems and writing clean code!

<br>

## 🛠️ Languages & Tools

<p align="left">
  <img src="https://skillicons.dev/icons?i=html,css,js,c,cpp,java,mysql,figma,git,github&theme=dark" alt="Wali's Skills" />
</p>

<br clear="right">

## 🐍 Contribution Graph

<p align="center">
  <img src="https://raw.githubusercontent.com/Wali-00/Wali-00/output/github-contribution-grid-snake.svg" alt="Snake animation eating my contributions" width="100%" />
</p>

> ⚙️ **Setup note:** this snake animation needs a one-time GitHub Actions workflow to generate itself daily. I've added the exact steps at the bottom of this file — just enable it once and it'll animate automatically.

<br>

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Wali-00&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Wali's GitHub Stats" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Wali-00&theme=tokyonight&hide_border=true" alt="Wali's Streak Stats" width="48%" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Wali-00&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="48%" />
</p>

<br>

## 🏆 GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Wali-00&theme=tokyonight&no-frame=true&row=1&column=7" alt="Trophies" />
</p>

<br>

<div align="center">

### 🤝 Let's Connect

*Always open to collaborating on interesting projects — feel free to reach out!* 🚀

<img src="https://komarev.com/ghpvc/?username=Wali-00&style=for-the-badge&color=00C9A7" alt="Profile Views" />

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0077B5,100:00C9A7&height=120&section=footer" alt="Footer Banner" width="100%" />

<br>

<details>
<summary>⚙️ One-time setup for the snake animation (click to expand)</summary>

<br>

The snake graph above needs a small GitHub Actions workflow to generate itself. Do this once:

1. In this repo (`Wali-00/Wali-00`), go to **Settings → Actions → General** and make sure "Read and write permissions" is enabled under Workflow permissions.
2. Create a new file at `.github/workflows/snake.yml` with this content:

```yaml
name: Generate Snake Animation
on:
  schedule:
    - cron: "0 0 * * *"
  push:
    branches: [ main ]
  workflow_dispatch: {}

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: Wali-00
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

3. Commit it, then run the workflow once manually from the **Actions** tab. After that it regenerates daily on its own.

</details>
