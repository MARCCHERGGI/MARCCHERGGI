# Marco Hergi

Solo builder in NYC. I run autonomous AI agent systems in production — and build the verification layer that checks what they actually did versus what they claimed.

![Python](https://img.shields.io/badge/Python-111.svg?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-111.svg?logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-111.svg?logo=node.js&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-111.svg?logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-111.svg?logo=modelcontextprotocol&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-111.svg?logo=opencv&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-111.svg?logo=vercel&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-111.svg?logo=supabase&logoColor=white)

**Now:** shipping the agent fleet that runs a one-person company, and documenting the whole thing on [A New York Diary](https://www.youtube.com/@MarcoHergi).

**Open to Applied AI / agent-infrastructure roles — New York, NY or remote.**
[Resume (PDF)](https://marco-apply-now.vercel.app/Marco-Hergi-Resume.pdf) · [Book a 30-min call](https://calendly.com/hergienterprises/intro-call-30-min)

### Selected work

| | |
|---|---|
| [**reflex**](https://github.com/MARCCHERGGI/reflex) | Demonstrate a GUI workflow once → compile it to a visual state machine → replay with **zero LLM calls** against moved windows, shuffled rows, changed themes. 100/100 mock + 29/29 unattended real-Chrome benchmark runs. |
| [**truth-layer**](https://github.com/MARCCHERGGI/truth-layer) | A 69-day field study: do autonomous agents faithfully report their own work? 7,186 claim records across 4,330 sessions, witnessed against ground truth. |
| [**orrery**](https://github.com/MARCCHERGGI/orrery) | A live star-map of an AI company — every star is a real scheduled agent. Zero deps, one HTML file, bring your own `fleet.json`. |
| [**promptforge**](https://github.com/MARCCHERGGI/promptforge) | A Claude Code hook that sharpens every prompt before Claude acts on it — adaptive depth, capability routing, learns your own commands. Zero deps, zero API calls. |
| [**creator-baseline**](https://github.com/MARCCHERGGI/creator-baseline) | Score social posts against a time-local baseline. Kills the growth artifact that makes fake levers look real. |
| [**indie-metrics-mcp**](https://github.com/MARCCHERGGI/indie-metrics-mcp) | MCP server for Stripe business intelligence — query revenue, customers, subscriptions from Claude or any AI assistant. |

Also: [jarvis-home](https://github.com/MARCCHERGGI/jarvis-home) (cinematic AI desktop UI) · [aura](https://github.com/MARCCHERGGI/aura) (33-script autonomous agent system, 24/7) · [linkshield](https://github.com/MARCCHERGGI/linkshield) (9-layer link protection)

### Field notes from running agents 24/7

Five short repos, written from an agent fleet that has been running continuously on one
laptop for months. Every pattern names the failure that produced it and the measurement that
caught it — these are not designs, they are scar tissue. 92 tests between them, each one a
regression for a bug that actually shipped.

| | |
|---|---|
| [**always-on-agent-patterns**](https://github.com/MARCCHERGGI/always-on-agent-patterns) | 14 patterns for running an agent on a machine you also use. Why watchers are timers and not daemons; how a FIFO dedup cap made the busiest lane forget fastest. |
| [**evidence-gates**](https://github.com/MARCCHERGGI/evidence-gates) | A self-improving agent cannot grade its own homework. Ladder gates that open only on external evidence and fail closed on outage. |
| [**agent-authority**](https://github.com/MARCCHERGGI/agent-authority) | Letting an agent act without asking, and still sleeping. Standing authority + a short gated list + kill files that outrank instructions. |
| [**honest-funnel-metrics**](https://github.com/MARCCHERGGI/honest-funnel-metrics) | Your analytics are probably counting you. Six ways a growth metric measures your own activity — and all six inflate it, which is not a coincidence. |
| [**windows-agent-ops**](https://github.com/MARCCHERGGI/windows-agent-ops) | The half nobody writes: 24/7 agents on Windows. Twelve silent-failure modes, plus a preflight checker for your task fleet. |

### Elsewhere

[marco-hergi.vercel.app](https://marco-hergi.vercel.app) · [Resume (PDF)](https://marco-apply-now.vercel.app/Marco-Hergi-Resume.pdf) · [Book a 30-min call](https://calendly.com/hergienterprises/intro-call-30-min) · [LinkedIn](https://www.linkedin.com/in/marcohergi/) · [Instagram](https://www.instagram.com/marcohergi) · [YouTube](https://www.youtube.com/@MarcoHergi) · [X](https://x.com/MarcoHergi)
