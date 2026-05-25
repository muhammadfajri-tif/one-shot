# 'Single-Shot' SRS and SDD, I hope

> [!WARNING]
> Great power comes with Great responsibility.

> [!NOTE]
> Always DO your own Research AND **take your own risk & responsibility**

## Pre-Requisite

- [Github Copilot Student Plan](https://docs.github.com/en/copilot/how-tos/copilot-on-github/set-up-copilot/enable-copilot/set-up-for-students) or any other AI/LLM Provider.
- Install [OpenCode](https://opencode.ai/) on Linux or Claude Code, or any other **AI Coding Agent** that **support multi-agent AI**.
- Connect Github Copilot (or any AI/LLM provider) to OpenCode. [Read here](https://opencode.ai/docs/providers/#github-copilot).
- Choose your fav/trusted model.

## Setup

1. Paste all your diagrams (png only!) inside [`diagrams/`](./diagrams/).

> [!TIP]
> Put your diagrams in here, including:
>
> - domain model
> - use case diagram
> - system sequence diagram
> - ERD / model data
> - Model Proses
> - Deployment Architecture
> - Wireframe
> - or others

2. Paste all your references (\*support txt, markdown, PDF) inside [`ref/`](./ref/).

> [!TIP]
> Put your docs/ref in here, including:
>
> - Requirement Functional
> - Requirement Non-Functional
> - Goals
> - Stakeholder
> - Business Rules
> - Operation Environment
> - Organization Environment
> - Use Case Fully Dressed
> - Operation Contract
> - or others

3. (optional) adjust your [`template/`](./template/), although it's ready to use.
4. Start OpenCode, change to `Build` mode, and then prompt: "selesaikan SRS sesuai context yang ada, make no mistake"
5. Check the result in [`SRS.md`](./SRS.md) (or [`SDD.md`](./SDD.md) if you prompt about SDD)

## FAQ

Q: Kenapa bikin ini? </br>
A: I believe the **good analysis and design aren't built in less than one week**. So, we only have 'one' choice: **let the clankers do their works**.

Q: Ada alesan lain kenapa bikin ini? </br>
A: Kalau disuruh buat hal yang complex pake AI dari web (misal [gemini.google.com](https://gemini.google.com), atau [chatgpt.com](https://chatgpt.com)), biasanya keseringan dapet limit.

Q: any tips? </br>
A: Convert tabel-tabel excel/sheet jadi tabel markdown karena bisa mempermudah (sekaligus memperkecil token yang dipakai). Convert juga PDF yang singkat-singkat jadi TXT atau markdown. Kalau gambar, lebih enak pakai PNG.

Q: Kok AI gw ga bisa baca PDF? </br>
A: Coba install Agent Skills buat baca [PDF](https://github.com/anthropics/skills/blob/main/skills/pdf/SKILL.md), atau baca [docx juga bisa kok.](https://github.com/anthropics/skills/blob/main/skills/docx/SKILL.md) Tutorial cara install di OpenCode ada [disini](https://opencode.ai/docs/skills/#place-files)

Q: Hasilnya jelek! Scam! </br>
A: Skill issue. Tunning your own model. Tunning your own config and tools. OpenCode/Claude Code/atau AI Coding Agent itu canggih dan banyak fitur. Pake model bego aja hasilnya bisa bagus kalau maksimalin tools + fitur yang ada dan prompt nya bagus

Q: Ribet ah! </br>
A: This is my workflow. I'm just sharing. Dipake ya syukur bisa bermanfaat, ga dipake gweh jg ga peduli jir 😹. Kalau mau simple, bikin aja workflow & boilerplate sendiri, atau suruh AmbaAI (AI dari Ngawi) yang kerjain 😹
