<div align="center">

# 👋 Hey, I'm Bülbül

<img
  src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2500&pause=800&color=2F81F7&center=true&vCenter=true&width=700&lines=Low-Level+Developer;C+%2F+C%2B%2B+Developer;Reverse+Engineering;Windows+Internals;Security+Research;System+Programming"
  alt="Typing SVG"
/>

<br><br>

<a href="https://github.com/bulbul6295?tab=followers">
  <img src="https://img.shields.io/github/followers/bulbul6295?style=for-the-badge&logo=github&label=Followers" alt="Followers">
</a>

<a href="https://github.com/bulbul6295?tab=repositories">
  <img src="https://img.shields.io/badge/Repositories-View-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories">
</a>

<a href="https://github.com/bulbul6295">
  <img src="https://img.shields.io/github/stars/bulbul6295?affiliations=OWNER&style=for-the-badge&logo=github&label=Stars" alt="Stars">
</a>

</div>

---

# 🧠 About Me

```cpp
#include <iostream>
#include <string>
#include <vector>

class Bulbul {
public:
    std::string role = "Low-Level Developer";

    std::vector<std::string> languages = {
        "C",
        "C++"
    };

    std::vector<std::string> interests = {
        "Reverse Engineering",
        "Windows Internals",
        "Kernel Development",
        "Security Research",
        "System Programming"
    };

    void introduce() {
        std::cout << "Building low-level stuff..." << std::endl;
    }
};

int main() {
    Bulbul dev;
    dev.introduce();

    return 0;
}
```

---

# ⚡ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=c,cpp,cmake,visualstudio,vscode,git,github,windows,linux,bash,powershell" />

</div>

---

# 🔬 What I Work On

- ⚙️ Low-Level Development
- 🧠 Reverse Engineering
- 🪟 Windows Internals
- 🔐 Security Research
- 🧩 Kernel / User-Mode Development
- 🛠 C / C++ Tooling
- 🔎 Process & Memory Research
- 💻 System Programming

---

# 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=bulbul6295&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" />

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bulbul6295&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />

</div>

---

# 🔥 GitHub Streak

<div align="center">

<img src="https://streak-stats.demolab.com?user=bulbul6295&theme=tokyonight&hide_border=true" />

</div>

---

# 📈 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=bulbul6295&theme=tokyo-night&hide_border=true&area=true" />

</div>

---

# 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=bulbul6295&theme=tokyonight&no-frame=true&no-bg=true&margin-w=5&row=1" />

</div>

---

# 🚀 Featured Projects

<table>
<tr>
<td width="50%">

## ⚙️ kernel-driver

Kernel-mode experiments and low-level Windows development.

**Focus**

- Windows Kernel
- Drivers
- Low-Level C
- System Research

</td>

<td width="50%">

## 🧪 fake-vgc-emulator

Experimental user-mode project focused on emulation and Windows internals.

**Focus**

- C++
- Windows API
- Reverse Engineering
- Research

</td>
</tr>

<tr>
<td width="50%">

## 💉 cpp-injector

C++ experiments involving process interaction and low-level Windows functionality.

**Focus**

- C++
- Process Research
- Windows Internals

</td>

<td width="50%">

## 🔓 Crackme-for-beginners

Beginner-friendly reverse engineering and crackme practice.

**Focus**

- Reverse Engineering
- C++
- Debugging
- Learning

</td>
</tr>

<tr>
<td width="50%">

## 🖥 imgui-cheat-menu

Modern ImGui interface experimentation.

**Focus**

- ImGui
- C++
- UI Development

</td>

<td width="50%">

## 🚀 advanced-loader

Experimental loader architecture written for low-level research.

**Focus**

- C++
- Windows
- Loaders
- System Programming

</td>
</tr>
</table>

---

# 🐍 Contribution Snake

<div align="center">

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/bulbul6295/bulbul6295/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/bulbul6295/bulbul6295/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution grid snake animation"
    src="https://raw.githubusercontent.com/bulbul6295/bulbul6295/output/github-contribution-grid-snake.svg"
  />
</picture>

</div>

---

# 🧰 Environment

```text
OS          Windows / Linux
Languages   C / C++
IDE         Visual Studio / VS Code
Versioning  Git / GitHub
Focus       Low-Level & Security
```

---

# 🎯 Current Interests

```text
[+] Windows Kernel
[+] Reverse Engineering
[+] Memory Internals
[+] System Programming
[+] Security Research
[+] C / C++
```

---

# 🌐 Connect With Me

<div align="center">

<a href="https://github.com/bulbul6295">
<img src="https://img.shields.io/badge/GitHub-bulbul6295-181717?style=for-the-badge&logo=github&logoColor=white">
</a>

</div>

---

<div align="center">

### `while(alive) { learn(); build(); break_things(); }`

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer" />

</div>


==================================================
.github/workflows/snake.yml
==================================================

name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"

  workflow_dispatch:

  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write

    runs-on: ubuntu-latest

    timeout-minutes: 5

    steps:
      - name: Generate contribution snake
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: bulbul6295

          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push snake to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          build_dir: dist
          branch: output

        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
