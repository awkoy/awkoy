<p align="center">
  <img src="https://raw.githubusercontent.com/awkoy/awkoy/main/assets/banner.svg" alt="Yaroslav Boiko — AI Engineer" />
</p>

AI Engineer. 10+ years across frontend, backend, and ML tooling — currently at [Comet ML](https://www.comet.com/) on [Opik](https://github.com/comet-ml/opik), keeping LLMs honest with traces, evals, and a healthy dose of skepticism.

📍 Barcelona · ✍️ [yaroslavboiko.com](https://yaroslavboiko.com/) · ✉️ [y.boikodevelop@gmail.com](mailto:y.boikodevelop@gmail.com)

---

## What I'm building

| Project | What it is | |
|---|---|---|
| [**notion-mcp-server**](https://github.com/awkoy/notion-mcp-server) | Production MCP server for Notion. Full read/write for AI assistants — no hand-rolled wrappers required. | ⭐ 149 |
| [**replicate-flux-mcp**](https://github.com/awkoy/replicate-flux-mcp) | Replicate's Flux as an MCP — your IDE generates images and SVGs without leaving the editor. | ⭐ 99 |
| [**gsc-cli**](https://github.com/awkoy/gsc-cli) | LLM-friendly TypeScript CLI and SDK for Google Search Console. JSON in, JSON out, agents happy. | |
| [**yaroslavboiko.com**](https://yaroslavboiko.com/) | Personal site and technical blog. Astro · Cloudflare Workers · a Three.js scene that earns its bytes. | |

## Recent writing

- [**Stop Using Claude Code on Defaults**](https://yaroslavboiko.com/blog/claude-code-defaults/) — five settings I changed in `~/.claude/settings.json` to save tokens and stop approving `ls` for the 400th time.
- [**Agentic UX Primitives**](https://yaroslavboiko.com/blog/agentic-ux-primitives/) — streaming, HITL gates, reasoning traces, confidence indicators: the frontend patterns behind products like Cursor and Claude.
- [**Context Engineering Ate Prompt Engineering**](https://yaroslavboiko.com/blog/context-engineering/) — what's replacing prompt engineering, and how it separates AI-augmented developers from AI-dependent ones.
- [**The Vibe Coding Reckoning**](https://yaroslavboiko.com/blog/vibe-coding-reckoning/) — 92% of devs use AI daily, 41% of code is AI-generated, and the backlash has arrived.

→ Full archive at [yaroslavboiko.com/blog](https://yaroslavboiko.com/blog/).

## How I actually work

- **MCP-native.** Author of [`notion-mcp-server`](https://github.com/awkoy/notion-mcp-server) (149⭐) and [`replicate-flux-mcp`](https://github.com/awkoy/replicate-flux-mcp) (99⭐). TypeScript MCPs are my default surface for anything agents need to touch.
- **SDKs over frameworks.** Anthropic and OpenAI directly. LangChain hides what you actually need to control once you ship past a demo.
- **Evals as a habit.** Every agent feature ships with traces and offline evals via [Opik](https://github.com/comet-ml/opik). "LGTM in chat" is not a gate.
- **Stream everything.** Tokens over SSE, JSON-schema-validated outputs (not regex), HITL gates wherever a mistake costs more than a click — [more on this](https://yaroslavboiko.com/blog/agentic-ux-primitives/).
- **Context engineering > prompt engineering.** Tight working sets, retrieval that earns its tokens, system prompts treated as code — [more](https://yaroslavboiko.com/blog/context-engineering/).
- **TypeScript end to end** (Python when eval pipelines call for it). Node + Postgres for state. `pgvector` when embeddings belong next to the data.
- **Edge-first infra.** Cloudflare Workers for latency, Astro for content, React for apps, Three.js when interactivity earns the weight.

## On GitHub

<p align="center">
  <a href="https://github.com/awkoy">
    <img src="https://github-readme-stats.vercel.app/api?username=awkoy&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&show_icons=true" height="170" alt="GitHub stats" />
  </a>
  <a href="https://github.com/awkoy">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=awkoy&theme=tokyonight&hide_border=true&layout=compact&langs_count=8" height="170" alt="Top languages" />
  </a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/awkoy/awkoy/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/awkoy/awkoy/output/github-snake.svg" />
    <img alt="contribution snake animation" src="https://raw.githubusercontent.com/awkoy/awkoy/output/github-snake.svg" />
  </picture>
</p>

## Elsewhere

[LinkedIn](https://linkedin.com/in/yaroslav-boiko) · [yaroslavboiko.com](https://yaroslavboiko.com/) · [y.boikodevelop@gmail.com](mailto:y.boikodevelop@gmail.com)

> Open to interesting problems in MCP, agent infrastructure, and AI-augmented developer tooling. If you're building something in that space — say hi.
