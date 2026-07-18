<h1 align="center">Hi there, I'm Ittesaf</h1>

<p align="center">
  I like to build, optimize, and automate solutions.  
</p>

---

### About Me

- **Background:** Software Engineering Sophomore at Islamic University of Technology (IUT), Bangladesh
- **Experience:** Product Intern @ Pathao, working on Parcel-related products
- **Interest:** Venture Capital, long-term
- **Building:** Shiplog, an open-source helper for Product Managers to perform post-prod push tasks easily.

---

### Featured Projects

| Project | What it is | Stack |
|---|---|---|
| [MatrixCanvas](https://github.com/ithun-y-ittesaf/MatrixCanvas) | Interactive, Desmos-like tool for learning linear algebra — built as a university project | TypeScript, Three.js |
| [findyourpath](https://github.com/ithun-y-ittesaf/findyourpath) | A Q-learning agent that finds the shortest path between two nodes, benchmarked against BFS and Dijkstra | Python |
| [practicepsql](https://github.com/ithun-y-ittesaf/practicepsql) | A learning platform for practicing PostgreSQL queries from basics to advanced | TypeScript |
| [Shiplog](https://github.com/ithun-y-ittesaf/shiplog)           | An opensource helper for Product Managers to perform post-prod push tasks easily | A bit of everything | 


---

### Languages & Tools

<p align="left">
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" />
  <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/three.js-black?style=for-the-badge&logo=three.js&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://img.shields.io/badge/raspberry_pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white" alt="Raspberry Pi" />
  <img src="https://img.shields.io/badge/obsidian-483699?style=for-the-badge&logo=obsidian&logoColor=white" alt="Obsidian" />
  <img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

---

### GitHub Stats

name: GitHub-Profile-Summary-Cards

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch: {}

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest
    name: generate-github-profile-summary-cards
    steps:
      - uses: actions/checkout@v3
      - uses: vn7n24fzkq/github-profile-summary-cards@release
        env:
          GITHUB_TOKEN: ${{ secrets.SUMMARY_GITHUB_TOKEN }}
        with:
          USERNAME: ithun-y-ittesaf
---

### Connect

<p align="center">
  <a href="https://www.linkedin.com/in/ittesafithun/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>
