## Full Stack Product Engineer & Indie Founder | Ex-Google | ITA

<div align="right">

[![Site](https://img.shields.io/badge/Site-marcelo.land-blue)](https://marcelo.land)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2)](https://linkedin.com/in/marcelocra)

</div>

My name is Marcelo. I'm a Computer Engineer from **ITA**[^ita] and a former **Google** engineer (Search, Data Pipelines / Dataflow, Chromium) with 15+ years of experience. I quit Big Tech to build **AI-native tools, browser extensions, and micro-SaaS products**.

Currently, I operate as a Full Stack Product Engineer, using AI agents as force multipliers to ship code rapidly without sacrificing architectural quality or maintainability.

[^ita]: Widely regarded as one of Brazil's top engineering institutes (Top 1%), known for its extremely rigorous entry and high academic standards.

## What I'm Building

I am actively building products with **AI Agents**, studying their impact on **Developer Experience (DX)**, and testing with self-hosted infrastructure.

In DX, I'm developing and testing a 4-step AI-assisted workflow to automate many parts of the development workflow. The goal is to achieve better results faster while reducing the cost of development.

### 🏢 Acerto AI

An automated collection and notification system built for B2B.

- **Why it matters:** Demonstrates the ability to solve concrete business problems using event-driven workflows and the simplest tools that allow one to validate the idea: the MVP was built using **n8n** and the **Evolution API** (running on my custom infra), with no custom code or complex deployments. Once the idea is validated (we are onboarding our first client), we can consider the next steps.

### 🌐 Override.sh

A browser extension for custom CSS/JS modifications, featuring an integrated AI panel for real-time DOM manipulation.

- **Why it matters:** Honestly, I'm just building this to scratch my own itch using tech I already know well. The fun part is bridging the gap between browser extensions and LLMs: instead of me having to inspect elements and manually write Greasemonkey-like scripts, the AI gets direct access to the DOM to write and apply visual or functional patches on the fly.

### ⌨️ ghostkeys (AutoHotkey v2 & Rust)

A system-wide keyboard remapping utility that allows typing Brazilian Portuguese and English on a physical US-layout keyboard without having to change the system layout. No more `win+space`!

- **Why it matters:** I built this leveraging AI to deploy complex, low-level system logic in languages I had zero prior experience with, proving that strong fundamentals translate across any syntax.
  - **v1**: Rust. A functional desktop tray application built in just a couple of days with **zero prior Rust experience**. The goal was to test if my ideas would port well to a strictly typed language using a spec-driven AI workflow. Built using Kiro (kiro.dev). [Code here](https://github.com/marcelocra/ghostkeys).
  - **v2**: AutoHotkey v2. The complete version that achieves my goal. I use it every day, all the time, and it saves me from a lot of frustrating typing mistakes. Brazilian coders will understand.

### ⚙️ Self-Hosted AI & Automation Infrastructure

Custom VPS setup orchestrated with Coolify.

- **Why it matters:** I set this up to learn more about infrastructure and, eventually, have the actual knowledge to decide if it is worth moving away from PaaS or not. I had never managed a server before and it has been an interesting experience, especially because it opens many self-hosting options that I didn't know about. I learned the practical basics of server management and Docker orchestration. It currently hosts my LLM router (LiteLLM) and n8n pipelines.

### 🧠 [concept-compass](https://github.com/marcelocra/concept-compass)

An infinite mind-map generator powered by OpenAI's OSS models.

- **Why it matters:** This started as my first attempt at hosting **LLMs** locally. It proved unfeasible, as my hardware couldn't handle even the 20b model efficiently. This constraint pushed me to discover OpenRouter. Today, I use OpenRouter daily to power not just apps like this, but many parts of my toolchain (Zed, OpenCode, Roo Code, Continue).

### 🤖 Solo Founder AI Engine

My conceptual framework for AI-assisted development, designed to optimize the "Engineer in the Loop" workflow.

- **Why it matters:** It allowed me to develop a **3-Phase Workflow** that matches model capability to task complexity, leveraging **Frontier Models**, **Top Models** and **Cheap/Weak Models**.

### ⚡ [vscode-improved](https://github.com/marcelocra/vscode-improved)

A VS Code extension bundling quality-of-life improvements.

- **Why it matters:** My first hands-on experience using the VS Code Extension API to optimize my own workflow.

## Other Projects & Achievements

- **Adapta AI Challenge:** **Top 3 Finalist** in Brazil's largest AI hackathon. Built an OOH analytics MVP using Next.js and AI APIs in ~24h.
- **[devmagic](https://github.com/marcelocra/devmagic):** A devcontainer setup that solves the "works on my machine" problem.
- **[Viralei](https://viralei.com.br):** Hackathon MVP built in 4 days that turns legislative bills into engaging videos.
- To be made open source when I finish the initial write up and websites:
  - **Fair Pricing Works:** Initiative advocating for Purchasing Power Parity (PPP).
  - **Do I Need A License?** Project that I created when answering that question for myself.

## Tech Stack

I choose tools that mix personal preference, velocity, and leverage.

- **Core Languages:** TypeScript, JavaScript, Python.
- **Main Stack:** React, Next.js, Node.js, Tailwind CSS, shadcn/ui, Zustand, Zod, Extensions API.
- **Main Dev Tools:** Cursor, Zed, OpenCode/CLI agents, VS Code + GitHub Copilot, DevContainers.
- **Infra & Tooling:** Docker, Podman, Coolify, n8n, LiteLLM, PostgreSQL/Supabase, OpenRouter, Tailscale, Cloudflare.

## What I Believe

- **Solid foundations matter:** Algorithms and system design are essential to use AI effectively. _How will I know the AI gave me a good solution if I don't understand the bounds?_
- **AI as a teammate:** LLMs are multipliers, but human judgment on architecture is non-negotiable.
- **Ship fast, maintain well:** High velocity should not come at the cost of messy code.

Feel free to [read my full story](https://bit.ly/40PMqDO) or check out my [learnings](https://bit.ly/40PVYPg).

<div align="center">
<sub>Education: B.S. Computer Engineering, ITA | Exchange: University of Twente (Netherlands)</sub>
</div>
