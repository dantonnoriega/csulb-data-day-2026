# CSULB Data Day at the Beach (2026)

Materials for Danton Noriega-Goodwin's Breakout Session from Saturday, 2026-03-28.

**Agentic Coding with GitHub Copilot CLI and Squad** — a hands-on workshop introducing CLI-based AI coding agents to a novice audience.

## Artifacts

### Slides

* https://dantonnoriega.github.io/csulb-data-day-2026/slides.html

### Workshop Goals

1. **Install Copilot CLI & log in to GitHub** (minimum goal)
2. Install Squad (multi-agent tool)
3. Ask your Squad to build a snake game

## Quick Start

### Goal 1: Copilot CLI

1. Go to [gh.io/dataday26](https://gh.io/dataday26) and redeem GitHub Copilot via the Student Developer Pack
2. Open a terminal (macOS: Terminal, Windows: PowerShell)
3. Install Copilot CLI:
   - **macOS:** `brew install copilot-cli` or `curl -fsSL https://gh.io/copilot-install | bash`
   - **Windows:** `winget install GitHub.Copilot`
4. Run `copilot`, then type `/login` to authenticate with GitHub

### Goal 2: Squad

1. Install [Node.js](https://nodejs.org/en/download)
2. `npm install -g @anthropic-ai/squad`
3. `squad init`
4. Load Squad via Copilot: `copilot --agent squad`

### Goal 3: Build a Snake Game

```bash
cd ~
mkdir repos && cd repos
mkdir snake-game && cd snake-game
git init
git config user.name "Your Name"
git config user.email "your.email@student.csulb.edu"
copilot --agent squad
```

Then prompt: *"hire a team to create a snake game i can play locally using python. use uv for package management."*

## Resources

### CLI Coding Agents

- [GitHub Copilot CLI](https://docs.github.com/en/copilot/how-tos/copilot-cli/set-up-copilot-cli/install-copilot-cli) — what we use in this workshop
- [Claude Code](https://claude.ai) by Anthropic — created the CLI agent space
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) by Google
- [Codex CLI](https://github.com/openai/codex) by OpenAI
- [Squad](https://github.blog/ai-and-ml/github-copilot/how-squad-runs-coordinated-ai-agents-inside-your-repository/) — multi-agent tool by GitHub

### Programming

-   Software Engineering
    -   AI Coding Agents (CLI)
        - [GitHub Copilot CLI](https://docs.github.com/en/copilot/how-tos/copilot-cli/set-up-copilot-cli/install-copilot-cli)
        - [Claude Code](https://claude.ai)
    -   AI Assistants (Web Chatbots)
        - [Claude AI](https://claude.ai)
        - [ChatGPT](https://chatgpt.com)
        - [Gemini](https://gemini.google.com/app)
    -   [Shell (`bash`) programming](https://datascienceatthecommandline.com)
    -   Open Source scripting languages
        -   [`python`](https://wesmckinney.com/book/)
        -   [`julia`](https://julialang.org)
        -   [`R`](https://r4ds.hadley.nz)
    -   [Version Control](https://happygitwithr.com)
        -   `git`, GitHub or GitLab

### Stay in Touch

- [danton.codes](http://danton.codes)
