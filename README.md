<p align="center">
  <img src="https://raw.githubusercontent.com/awkoy/awkoy/main/assets/banner.svg" alt="Yaroslav Boiko — AI Engineer" />
</p>

AI Engineer building developer tools for the agent era. 10+ years shipping production software across frontend, backend, and ML eval infra. Currently on agent observability at [Comet ML](https://www.comet.com/) / [Opik](https://github.com/comet-ml/opik).

📍 Barcelona · ✍️ [yaroslavboiko.com](https://yaroslavboiko.com/) · ✉️ [y.boikodevelop@gmail.com](mailto:y.boikodevelop@gmail.com)

---

## What I'm building

| Project | What it is | |
|---|---|---|
| [**notion-mcp-server**](https://github.com/awkoy/notion-mcp-server) | Production-ready MCP server giving AI assistants full Notion API access | ⭐ 149 |
| [**replicate-flux-mcp**](https://github.com/awkoy/replicate-flux-mcp) | MCP for Replicate's Flux — generate images & SVGs from inside your IDE | ⭐ 99 |
| [**gsc-cli**](https://github.com/awkoy/gsc-cli) | LLM-friendly TypeScript CLI/SDK for the Google Search Console API | |
| [**yaroslavboiko.com**](https://yaroslavboiko.com/) | Personal site + technical blog. Astro · Cloudflare Workers · Three.js | |

## Recent writing

- [**Stop Using Claude Code on Defaults**](https://yaroslavboiko.com/blog/claude-code-defaults/) — five settings I changed in `~/.claude/settings.json` to save tokens and stop approving `ls` for the 400th time
- [**Agentic UX Primitives**](https://yaroslavboiko.com/blog/agentic-ux-primitives/) — streaming, HITL gates, reasoning traces, confidence indicators: the actual frontend patterns behind Cursor and Claude
- [**Context Engineering Ate Prompt Engineering**](https://yaroslavboiko.com/blog/context-engineering/) — the skill replacing prompt engineering, and what separates AI-augmented developers from AI-dependent ones
- [**The Vibe Coding Reckoning**](https://yaroslavboiko.com/blog/vibe-coding-reckoning/) — 92% of devs use AI daily, 41% of code is AI-generated, and the backlash has arrived

→ Full archive at [yaroslavboiko.com/blog](https://yaroslavboiko.com/blog/)

## How I actually work

- **MCP-native.** Author of [`notion-mcp-server`](https://github.com/awkoy/notion-mcp-server) (149⭐) and [`replicate-flux-mcp`](https://github.com/awkoy/replicate-flux-mcp) (99⭐). TypeScript MCPs are my default tool surface for agents.
- **SDKs over frameworks.** Anthropic and OpenAI directly. LangChain costs more in abstraction than it saves once you ship past a demo.
- **Eval as discipline.** Every agent feature gets traces and offline evals via [Opik](https://github.com/comet-ml/opik) before it ships. "LGTM in chat" isn't a gate.
- **Stream everything.** SSE for tokens, structured outputs over regex, HITL gates where mistakes are expensive — [more on this](https://yaroslavboiko.com/blog/agentic-ux-primitives/).
- **Context engineering > prompt engineering.** Working set discipline, retrieval that earns its tokens, system prompts as code — [more](https://yaroslavboiko.com/blog/context-engineering/).
- **TypeScript end to end** (Python when eval pipelines need it). Node + Postgres for state, `pgvector` when embeddings belong near the data they describe.
- **Edge-first.** Cloudflare Workers for latency, Astro for content, React for apps, Three.js when interactivity earns the weight.

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

> Open to interesting problems in MCP, agent infrastructure, and AI-augmented developer tooling — drop me a line.
