<p align="center">
  <img src="https://raw.githubusercontent.com/awkoy/awkoy/main/assets/banner.svg" alt="Yaroslav Boiko - Senior Full-Stack AI Engineer" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=awkoy&label=profile%20views&color=0a2540&style=flat" alt="Profile views" />
  <a href="https://github.com/comet-ml/opik/pulls?q=is%3Apr+author%3Aawkoy">
    <img src="https://img.shields.io/badge/OPIK%20PRs-351-0a2540?style=flat" alt="351 public OPIK PRs" />
  </a>
  <a href="https://github.com/comet-ml/opik">
    <img src="https://img.shields.io/github/stars/comet-ml/opik?style=flat&label=OPIK%20stars&color=0a2540" alt="OPIK GitHub stars" />
  </a>
</p>

Senior full-stack AI engineer with 10+ years of shipping products. I'm at [Comet ML](https://www.comet.com/) working on [OPIK](https://github.com/comet-ml/opik), an open-source platform for debugging, evaluating and monitoring LLM applications. Its Python SDK gets about 1.7M downloads a month.

On OPIK I own the frontend. I built the TypeScript SDK from scratch and the Ollie AI assistant end to end, from the streaming UI and tool calls to its Python side. I also own the hosted MCP server, including its OAuth in Java. Most days that means TypeScript, React, Node, Python and PostgreSQL, with OpenTelemetry traces running into the millions of rows.

Barcelona · [yaroslavboiko.com](https://yaroslavboiko.com/) · [LinkedIn](https://www.linkedin.com/in/awkoy/) · [Email](mailto:y.boikodevelop@gmail.com)

---

## Selected work

| Project | What I did | Stars |
| --- | --- | --- |
| [**OPIK**](https://github.com/comet-ml/opik) | Core contributor to Comet ML's LLM evaluation and observability platform, with 351 public PRs across the frontend, the TypeScript SDK, the Ollie assistant and the Java and Python backends. | ![OPIK stars](https://img.shields.io/github/stars/comet-ml/opik?style=flat&label=stars&color=0a2540) |
| [**notion-mcp-server**](https://github.com/awkoy/notion-mcp-server) | MCP server for Notion pages and databases. Dozens of operations behind two public tools, so it doesn't flood the agent's context. | ![notion-mcp-server stars](https://img.shields.io/github/stars/awkoy/notion-mcp-server?style=flat&label=stars&color=0a2540) |
| [**replicate-flux-mcp**](https://github.com/awkoy/replicate-flux-mcp) | Small MCP server for Replicate Flux image generation with inputs and outputs you can inspect. | ![replicate-flux-mcp stars](https://img.shields.io/github/stars/awkoy/replicate-flux-mcp?style=flat&label=stars&color=0a2540) |
| [**OPIK MCP**](https://github.com/comet-ml/opik-mcp) | Comet ML's MCP server that connects OPIK prompts, projects, traces and metrics to coding assistants. I own the hosted version and its OAuth. | ![OPIK MCP stars](https://img.shields.io/github/stars/comet-ml/opik-mcp?style=flat&label=stars&color=0a2540) |
| [**yaroslavboiko.com**](https://yaroslavboiko.com/) | My site and blog. Astro on Cloudflare Workers, plus a Three.js scene that earns its bytes. | |

My two MCP packages get around 3.5K npm downloads a week.

## What I work on

- **AI agents in production.** Streaming, sessions, tool calling, MCP clients, guardrails and the harness around them, built for Ollie.
- **MCP servers.** Tool surfaces that stay small, errors that tell the agent how to fix its next call, and OAuth for hosted servers.
- **TypeScript SDKs and APIs.** Typed contracts, compatibility tradeoffs, and examples people can copy.
- **Evals and LLM cost.** Offline evals, prompt optimization, and tracking what each LLM call costs.
- **Performance.** Trace views over millions of rows, and a week spent on performance during a customer POC that ended with a signed deal.

## Recent writing

- [**MCP Tool Design for AI Agents, Not API Endpoints**](https://yaroslavboiko.com/blog/mcp-tool-surface/): why I expose one execute tool and one describe tool instead of an endpoint per operation.
- [**Stop Using Claude Code on Defaults**](https://yaroslavboiko.com/blog/claude-code-defaults/): five settings I changed in `~/.claude/settings.json` to save tokens and stop approving `ls` for the 400th time.
- [**Agentic UX Primitives**](https://yaroslavboiko.com/blog/agentic-ux-primitives/): streaming, HITL gates, reasoning traces and confidence indicators, the frontend patterns behind Cursor and Claude.
- [**Context Engineering Ate Prompt Engineering**](https://yaroslavboiko.com/blog/context-engineering/): why structured context beats clever prompts, and how much of it to leave out.

Full archive: [yaroslavboiko.com/blog](https://yaroslavboiko.com/blog/)

## How I work

- I write the spec and the tradeoffs down before building anything clever.
- If behavior crosses product boundaries, it gets a typed SDK and examples, not another one-off adapter.
- Agent features ship with traces and offline evals. "Looks good in chat" doesn't count as testing.
- Anything that should feel alive streams. Actions that are expensive to get wrong get a human approval step.
- Agents get a tight working set of context, and prompts live in the repo like any other code.
- TypeScript end to end for product work, Python where eval or ML tooling makes it the better fit.

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
