<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e293b,100:334155&height=180&section=header&text=Nick%20%7C%20Bosify&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=40" />

<div style="display: flex; justify-content: center; gap: 20px; margin: 20px 0;">
  <img src="https://komarev.com/ghpvc/?username=nicksel010&label=Profile%20Views&color=0ea5e9&style=flat" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/nicksel010?label=Followers&color=0ea5e9&style=flat" alt="Followers" />
  <img src="https://img.shields.io/github/stars/nicksel010?label=Total%20Stars&color=0ea5e9&style=flat" alt="Total Stars" />
</div>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2200&pause=800&center=true&vCenter=true&width=680&color=0ea5e9&lines=Web+Designer+%26+Developer;FiveM+Scripts+from+Scratch;Windows+Apps+for+Fun;Always+Building+Something" />

---

## 🧠 What I Build

<div style="background: #1e293b; padding: 20px; border-radius: 12px; border: 1px solid #334155; max-width: 700px; margin: 30px auto;">
<p style="color: #94a3b8; font-style: italic; margin: 0; text-align: center;">
"I build web experiences, custom FiveM scripts, Windows applications, and creative experiments.<br/>
I start a lot of projects. I learn from all of them. Some accidentally become really good."
</p>
</div>

---

## 📊 GitHub Stats

Here's a working, modern alternative to the original github-readme-stats card for your GitHub profile README (for user nicksel010). The classic public instance often suffers from rate limiting or downtime in 2026, so we'll use one of the most reliable and up-to-date approaches.
Option 1: Self-hosted via GitHub Actions (Recommended – No Rate Limits, Fully Private Stats, Automatic Updates)
This generates static SVG files in your repo using GitHub Actions → no external server needed, updates daily (or on push), and shows private contributions if you add a PAT.

Create a new repo called nicksel010/nicksel010 (your profile repo) if you don't have one yet.
Add this workflow file: .github/workflows/profile-stats.yml

YAMLname: Generate GitHub Stats

on:
  schedule:
    - cron: '0 0 * * *'  # Daily at midnight UTC
  workflow_dispatch:     # Manual trigger

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4

      - name: Generate Stats
        uses: anuraghazra/github-readme-stats@master
        with:
          username: nicksel010
          token: ${{ secrets.PAT }}           # Optional: for private repos
          output: stats.svg                   # Or multiple files
          config: |
            theme: tokyonight
            show_icons: true
            hide_border: true
            hide: issues,prs                    # Customize as needed

      - name: Commit files
        run: |
          git config --global user.name 'GitHub Actions'
          git config --global user.email 'actions@github.com'
          git add .
          git commit -m "Update GitHub Stats" || echo "No changes"
          git push

(Optional but recommended) Add a GitHub PAT for private repo stats:
Go to https://github.com/settings/tokens → Generate new classic token (scopes: repo, read:org)
In repo Settings → Secrets and variables → Actions → New repository secret named PAT

Add to your README.md (centered like your original):

Markdown

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=nicksel010&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

---

## ⚡ Tech Stack

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 10px; max-width: 700px; margin: 30px auto;">
<img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,tailwind,nodejs,cs,python,lua,mysql,git,vscode,github&theme=dark&perline=8" />
</div>

---

## 🌍 Find Me

<div style="display: flex; justify-content: center; gap: 15px; margin: 30px 0;">

<a href="https://bosify.nl">
  <img src="https://img.shields.io/badge/Website-bosify.nl-0f172a?style=for-the-badge&logo=vercel&logoColor=white&color=0ea5e9" alt="Website" />
</a>

<a href="https://github.com/nicksel010">
  <img src="https://img.shields.io/badge/GitHub-0f172a?style=for-the-badge&logo=github&logoColor=white&color=0ea5e9" alt="GitHub" />
</a>

</div>

</div>
