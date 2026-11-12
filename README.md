# claude-for-everything

A community-maintained list of skills, plugins, MCP servers and rule files for Claude, organised by what you want to do. Each entry says what it is and links to its repo.

> Free or freemium only: no paid-only tools. Contributions are welcome, see [CONTRIBUTING.md](CONTRIBUTING.md). Install steps are left out on purpose: follow each repo's README.
>
> **Caution:** entries are not security-audited. Review any skill, plugin or MCP server before installing it, see [Security](#security).

## Contents

- **[Video](#video)**: [Editing](#editing) · [Motion Graphics](#motion-graphics) · [Animation Styles](#animation-styles) · [Prompts](#prompts)
- **[Audio](#audio)**: [Sound Effects](#sound-effects)
- **[Design](#design)**: [UI](#ui) · [Diagrams](#diagrams) · [Logo & Brand](#logo--brand) · [Web Animation & 3D](#web-animation--3d)
- **[Marketing](#marketing)**: [SEO](#seo) · [Social Content](#social-content) · [Sales Outreach](#sales-outreach)
- **[Dev](#dev)**: [Workflow & Planning](#workflow--planning) · [Multi-Agent & Orchestration](#multi-agent--orchestration) · [Setup, Rules & Guides](#setup-rules--guides) · [Code Review & Safety](#code-review--safety) · [Token Saving & Cost](#token-saving--cost) · [Memory & Context](#memory--context) · [Browser & Computer Control](#browser--computer-control) · [Docs & Databases](#docs--databases)
- **[Games](#games)**: [Game Dev](#game-dev) · [Modding](#modding)
- **[Writing](#writing)**: [Research Writing](#research-writing) · [Style & Fiction](#style--fiction)
- **[Productivity](#productivity)**: [Notes & Knowledge](#notes--knowledge) · [Product & Business](#product--business) · [Smart Home](#smart-home)
- **[Career](#career)**: [Job Search](#job-search)
- **[Discovery](#discovery)**: [Skill & Plugin Directories](#skill--plugin-directories)
- **[Standalone](#standalone)**: [Media Tools](#media-tools) · [Local Models & OCR](#local-models--ocr) · [Agents & Harnesses](#agents--harnesses) · [Apps & Tools](#apps--tools) · [Examples & Demos](#examples--demos)
- **More**: [Start here](#start-here) · [Recently added](#recently-added) · [Types](#types-used-in-tables) · [Security](#security) · [Contributing](#contributing)


## Start here

Not sure where to begin? Eight picks, one per area:

- [superpowers](https://github.com/obra/superpowers): a plan, test and review method for coding with Claude. ([Workflow & Planning](#workflow--planning))
- [context7](https://github.com/upstash/context7): current library docs inside Claude. ([Docs & Databases](#docs--databases))
- [engram](https://github.com/Gentleman-Programming/engram): memory that lasts between sessions. ([Memory & Context](#memory--context))
- [playwright-mcp](https://github.com/microsoft/playwright-mcp): lets Claude browse and test websites. ([Browser & Computer Control](#browser--computer-control))
- [caveman](https://github.com/JuliusBrussee/caveman): shorter answers and smaller tool output to save tokens. ([Token Saving & Cost](#token-saving--cost))
- [impeccable](https://github.com/pbakaus/impeccable): helps Claude build better-looking interfaces. ([UI](#ui))
- [claude-seo](https://github.com/AgriciDaniel/claude-seo): SEO audits from Claude Code. ([SEO](#seo))
- [hyperframes](https://github.com/heygen-com/hyperframes): turn HTML into video. ([Motion Graphics](#motion-graphics))

## Recently added

- [tstack](https://github.com/t3dotgg/tstack): Theo's PR skills, from change to merged PR. ([Workflow & Planning](#workflow--planning))
- [agent-memory](https://github.com/tigerless-labs/agent-memory): local Markdown memory shared across agents. ([Memory & Context](#memory--context))
- [oil-ui](https://github.com/oil-oil/oil-ui): a UI design skill that compares directions side by side. ([UI](#ui))
- [ha-mcp](https://github.com/homeassistant-ai/ha-mcp): control and set up Home Assistant. ([Smart Home](#smart-home))
- [mcp2cli](https://github.com/knowsuchagency/mcp2cli): turn any MCP server or API into a CLI. ([Token Saving & Cost](#token-saving--cost))
- [mcporter](https://github.com/openclaw/mcporter): call MCP servers from scripts and the terminal. ([Apps & Tools](#apps--tools))
- [raea](https://github.com/shinyobjectz/raea): videos, motion graphics, 3D and games as code. ([Motion Graphics](#motion-graphics))
- [Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep): autonomous research loops. ([Research Writing](#research-writing))

## Video

### Editing

Let an agent cut, caption and assemble video from your footage.

| Name | Type | What it does |
|---|---|---|
| [openfilm](https://github.com/openfilm/openfilm) | skill + desktop app | Open-source AI video agent: Claude writes a film as HTML pages with a frame(t) function, and a local browser Studio editor lets you edit and render it (MIT; desktop app available). |
| [concat](https://github.com/jub0t/concat) | app + MCP server | Free, open-source, local video editor (CapCut alternative) with auto-captions, background removal, 4K export, no watermark, and a built-in MCP server (`concat --mcp`) for AI agents. |
| [video-shotcraft](https://github.com/Vincentwei1021/video-shotcraft) | skill | An Apache-2.0 Claude Code skill that builds cinematic product promo videos with Remotion from your own screenshots and copy. Remotion may need a paid license for companies. |
| [OpenMontage](https://github.com/calesthio/OpenMontage) | app | An AGPL-3.0 open-source agentic video production system with 12 pipelines and 100+ tools that turns Claude Code into a video studio. Optional paid API keys; AGPL-3.0. |
| [ffmpeg-skill](https://github.com/kajisho5/ffmpeg-skill) | MCP | A free MIT-licensed local video editor for coding agents with 42 FFmpeg tools and an MCP server that works with Claude Code. |
| [claude-video-vision](https://github.com/jordanrendric/claude-video-vision) | plugin | Claude Code plugin that gives Claude video frames (via ffmpeg) and audio transcripts so it can watch videos. Free with local Whisper; cloud backends send audio to Google or OpenAI. |

### Motion Graphics

Code-driven video: the agent writes HTML, GSAP or Canvas and renders it to MP4.

| Name | Type | What it does |
|---|---|---|
| [hyperframes](https://github.com/heygen-com/hyperframes) | framework + plugin | Open-source framework that turns HTML, CSS, media and seekable animations into deterministic MP4 videos, with a Claude Code plugin and skills for agents. |
| [huashu-motion](https://github.com/alchaincyf/huashu-motion) | skill | Skill that makes product launch films from a prompt: the agent writes the animation, composes the score, and opens a browser editor where you click on the picture to request changes (MIT). |
| [brag](https://github.com/latent-spaces/brag) | skill | Agent skill (/brag, plus a lean /brag-slim) that turns your project into a short launch video with music, motion and share copy; installs as a Claude Code plugin. |
| [super-video-maker-skill](https://github.com/Bomx/super-video-maker-skill) | skill | End-to-end video production skill: turns an idea, link, screen recording or script into a finished video using HeyGen avatars, AI b-roll, Remotion, HyperFrames, FFmpeg and captions. |
| [remotion](https://github.com/remotion-dev/remotion) | framework + skills | Make videos programmatically with React, with Agent Skills docs for AI assistants. Free to start, but it has a special licence that needs a paid company licence in some cases, so check it first. |
| [raea](https://github.com/shinyobjectz/raea) | engine + plugin | Render Anything Engine: write videos, motion graphics, 3D and games as React and TypeScript and render them on your own GPU, with Claude Code skills and a plugin. Free, no account, no telemetry; FSL-1.1 licence (source-available, not open source) and still in canary. The installer is a curl script that adds skills to `~/.claude/skills`. |

### Animation Styles

Style skills for stylised animated films and shorts. Pick one per project.

| Name | Type | What it does |
|---|---|---|
| [lemo-opuscar](https://github.com/lemomo-ai/lemo-opuscar) | skill | Toolbox of 66 film styles made in code (watercolor, crayon, pixel and more), each with its own short film; tuned for Claude Opus 5.5. |
| [onetake](https://github.com/feitangyuan/onetake) | skill | Claude skill for product launch films, teasers and demos made as one continuous camera take, where each beat grows out of the previous one with no hard cuts. |
| [gbro-collage-broll](https://github.com/pyang5166/gbro-collage-broll) / [VOX-COLLAGE-BROLL](https://github.com/MegaTroll222/VOX-COLLAGE-BROLL) | skill | Skill that turns a ~5s spoken script line into a halftone paper-cutout collage B-roll clip via a three-gate approval flow; the VOX version is a Claude Code skill, gbro needs separate image-generation tools. |
| [ClaudeAnimationBase](https://github.com/JohnHeibel/ClaudeAnimationBase) | starter kit | Starter kit for animating a character (Clawd) in p5.js and p5.brush with Claude Opus 5.5, with an animation guide and render scripts for hand-painted watercolor-style 2D video. |
| [claude-animated-shorts](https://github.com/mromidev/claude-animated-shorts) | skill | Free Claude skill for 55-70 s vertical animated story shorts: 2D characters in a 3D world, rendered with three.js in Remotion locally with synthesized sound. |
| [stickman-video-director](https://github.com/kaomei/stickman-video-director) | skill | Skill that turns a topic, article or script into animated stickman videos for faceless YouTube channels, with 10 visual styles, in a storyboard-and-prompts Director mode or an Autopilot mode. |
| [hypit](https://github.com/hypit-ai/hypit) | skill | Open-source skill and runtime that lets Claude clone or create videos (footage, captions, B-roll, effects anchored to words) from a text-based video workflow format. |
| [anidoodle](https://github.com/alexgreensh/anidoodle) | skill | Skill that draws illustrations, timelapses and short films as code in 32 styles, with scores composed in code. Needs Playwright and ffmpeg; the optional sound pack is a 373 MB download. |

### Prompts

| Name | Type | What it does |
|---|---|---|
| [awesome-opus5-5-videos](https://github.com/yihui-dev/awesome-opus5-5-videos) | collection | Collection of 703 prompts from viral videos made with Claude Opus 5.5 (motion graphics, explainers, 3D scenes, games), each with the creator's prompt or original post. |


[↑ Contents](#contents)

## Audio

### Sound Effects

Fix the weak point of agent-made video: its sound effects.

| Name | Type | What it does |
|---|---|---|
| [Clipwing/skills (real-sfx)](https://github.com/Clipwing/skills) | collection | Collection of agent skills from Clipwing, including Real SFX (places real recorded sound effects on the exact frame, ships 78 CC0 UI sounds) and HyperFrames to After Effects. |
| [earshot](https://github.com/Leonxlnx/earshot) | MCP server + CLI | Gives Claude ears: describes and measures audio, audits sync and loudness, finds the best moment, and generates sound effects in code; runs locally as a CLI, Python API and MCP server. |
| [Openverse API](https://github.com/wordpress/openverse) | API | Openverse, WordPress's search engine and API for openly licensed media including audio; the repo is the search engine's source, not an agent skill. |

Used together: Openverse to find sounds, real-sfx to place them, earshot to review the result.


[↑ Contents](#contents)

## Design

### UI

Make agents produce better-looking interfaces.

| Name | Type | What it does |
|---|---|---|
| [impeccable](https://github.com/pbakaus/impeccable) | skill | Design skill that gives the agent a design vocabulary (polish, bolder, critique, audit) to steer UI work and catch generic AI-looking design. |
| [awesome-design-md](https://github.com/VoltAgent/awesome-design-md) | collection | Curated collection of ready-to-use DESIGN.md files extracted from real websites' design systems, which an agent reads to generate visually consistent UI. |
| [awesome-design-skills](https://github.com/bergside/awesome-design-skills) | list | Curated registry of 67 design-system skill files (each with SKILL.md and DESIGN.md) that you pull into a project with `npx typeui.sh pull`. |
| [ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | skill | Skill that generates a tailored project design system from searchable databases of UI styles, colour palettes and font pairings, using a reasoning engine over 192 rules. |
| [taste-skill](https://github.com/Leonxlnx/taste-skill) | skill | Skill that gives the agent an art direction, real credited photos and a real-browser check so the websites and app screens it builds look less generic. |
| [frontend-slides](https://github.com/zarazhangrui/frontend-slides) | plugin | A free Claude Code plugin that generates single-file HTML presentations from scratch or from PowerPoint files. |
| [garden-skills](https://github.com/ConardLi/garden-skills) | skill | A free MIT-licensed collection of skills for web design, image generation, video and knowledge-base retrieval, tested with Claude Code and Claude.ai. |
| [hallmark](https://github.com/Nutlope/hallmark) | skill | A free MIT-licensed design skill from Together AI that helps Claude Code build web pages that do not look AI-generated. |
| [skills](https://github.com/jakubkrehel/skills) | skill | A free MIT-licensed collection of skills for reviewing and building interfaces, covering accessibility, layout, typography, color and writing, installable as a Claude Code plugin. |
| [unslop](https://github.com/heydamir/unslop) | skill | Claude Code skill that audits vibecoded, AI-looking UI and redesigns it pass by pass into a more distinctive interface. CC-BY-4.0; optional image generation asks before each paid call. |
| [huashu-design](https://github.com/alchaincyf/huashu-design) | skill | MIT skill that turns one prompt into animations, app prototypes, slides and infographics for Claude Code. README is Chinese-first with an English version; no telemetry, optional cloud features need your own keys. |
| [ai-website-cloner-template](https://github.com/JCodesMore/ai-website-cloner-template) | template + command | Next.js template with a `/clone-website <url>` command that has Claude rebuild a site as a Next.js app. Copies other people's designs, so mind copyright and site terms. |
| [design-extract](https://github.com/Manavarya09/design-extract) | CLI + plugin | Opens any URL in headless Chromium and extracts its design system as tokens, Tailwind and Figma files and a DESIGN.md. Optional `--smart` mode uses a sponsor's hosted classifier. |
| [oil-ui](https://github.com/oil-oil/oil-ui) | skill | MIT UI design skill that studies peer products, explores several directions side by side and refines one against real screenshots. It checks ui.oiloil.org for updates and uploads nothing; set `OIL_NO_UPDATE_CHECK=1` to turn that off. |

### Diagrams

| Name | Type | What it does |
|---|---|---|
| [diagram-design](https://github.com/cathrynlavery/diagram-design) | skill | Skill that draws diagrams as one self-contained HTML + SVG file in your brand, with 45 diagram types and no Mermaid-style output. |
| [archify](https://github.com/tt-a1i/archify) | skill | Turns an idea, question, plan or repo description into an interactive HTML page you can explore, customize and share, from itineraries to system diagrams. |
| [next-ai-draw-io](https://github.com/DayuanJiang/next-ai-draw-io) | MCP + app | Create and edit draw.io diagrams by chatting; works as a web app, desktop app or MCP server for Claude Code. You bring a model API key or use local models. |
| [drawio-skill](https://github.com/Agents365-ai/drawio-skill) | skill | Skill that turns text, code and infrastructure into editable draw.io diagrams with exports and an optional MCP server. Can read Terraform, Docker and kubectl state. |

### Logo & Brand

| Name | Type | What it does |
|---|---|---|
| [logo-design-skill](https://github.com/kaankiziltug/logo-design-skill) | skill | Logo-design skill covering brief, concepts, SVG construction and testing, with a searchable library of 1,400+ real SVG logos and Python tools for auditing and exporting. |
| [dashboard-icons](https://github.com/homarr-labs/dashboard-icons) | MCP | 3,400+ curated dashboard icons and logos, with a free MCP server. |

### Web Animation & 3D

Teach the agent to build award-style animated sites and interactive 3D.

| Name | Type | What it does |
|---|---|---|
| [scroll-craft](https://github.com/nateherkai/scroll-craft) | plugin | Skill, also packaged as a Claude Code plugin, for building premium scroll-driven websites with a design workflow, engine and verification tools. |
| [gsap-skills](https://github.com/greensock/gsap-skills) | plugin | Official GreenSock agent skills that teach correct GSAP usage: core API, timelines, ScrollTrigger, plugins, framework integrations and performance. |
| [webgl-animation-skills](https://github.com/iart-ai/webgl-animation-skills) | skill | Skills for WebGL animation: GLSL fragment shaders, Three.js scene animation, and particle systems; installable as a Claude Code plugin marketplace. |
| [anatomy](https://github.com/wheresryan22/anatomy) | skill | Claude skill that explains an idea by building it as an interactive isometric figure with many small precise parts, in SVG, WebGL or 3D. |
| [machine-skill](https://github.com/AirsupHQ/machine-skill) | skill | Claude Code skill: `/machine a turbofan jet engine` researches the real machine and builds an interactive 3D physics simulation in one HTML file, plus a film to post. |
| [mcp-for-blender](https://github.com/ahujasid/mcp-for-blender) | MCP | A community MCP server (formerly blender-mcp) that lets Claude Desktop and Claude Code control Blender 3D. Runs Python inside Blender; telemetry is on by default, the installer runs a curl script, and some AI 3D-model features are paid. |


[↑ Contents](#contents)

## Marketing

### SEO

| Name | Type | What it does |
|---|---|---|
| [claude-seo](https://github.com/AgriciDaniel/claude-seo) | plugin | A free MIT-licensed Claude Code plugin that audits technical SEO, content quality, structured data and AI search readiness. |
| [marketingskills](https://github.com/coreyhaines31/marketingskills) | skill | A free MIT-licensed collection of marketing skills for Claude Code covering conversion optimization, copywriting, SEO and analytics. |
| [claude-blog](https://github.com/AgriciDaniel/claude-blog) | plugin | Claude Code plugin that researches, writes, SEO-checks and reviews blog posts, with 32 skills and 5 agents. Free on your Claude plan; optional paid Gemini for images. Install v2.3.0 or later. |

The standalone [open-seo](#apps--tools) (Semrush/Ahrefs alternative) is an app, not a plugin.

### Social Content

| Name | Type | What it does |
|---|---|---|
| [instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill) | 13 skills | Thirteen free Claude skills for running an Instagram account, including a Reel writer with 26 hook formulas and hook scoring, a niche virality ranker, caption and profile skills; nothing is posted without your approval. |
| carousel-studio ([guide](https://milleemd.com/guides/instagram-carousel-system/)) | skill (zip) | Skill (download as zip) that interviews you about your style, then renders Instagram carousels as real 1080x1350 PNGs from HTML via a headless browser. |
| [reddit-automation](https://github.com/flowkit-labs/skills) | skill | Skill that finds Reddit threads where people are shopping for what you sell and drafts helpful replies for you to review and post by hand. |
| [xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp) | MCP | An Apache-2.0 MCP server that lets Claude Code search, read and publish on xiaohongshu.com (RedNote), including likes, favorites and comments. Publishes and comments from your account. |
| [baoyu-skills](https://github.com/JimLiu/baoyu-skills) | skill | 20+ skills for content work such as comics, infographics, image generation and posting to X, WeChat and Weibo. Posting uses your logged-in browser; image skills call paid third-party APIs. |
| [linkedin-skills](https://github.com/sergebulaev/linkedin-skills) | 12 skills | Skills that draft LinkedIn posts, comments and replies in your voice and wait for your approval. Optional paid Apify (scraping) and Publora (auto-posting). |

Humanizing tools such as [humanizer](#style--fiction) are listed under Writing.

### Sales Outreach

| Name | Type | What it does |
|---|---|---|
| [harvey](https://github.com/ethanplusai/harvey) | app (runs on Claude Code) | Autonomous sales agent that runs on your Claude Code subscription: finds businesses, writes specific cold emails, reads replies and keeps a local dashboard, with drafts held in an outbox for your approval. |


[↑ Contents](#contents)

## Dev

### Workflow & Planning

Add structure to how the agent plans, reviews and tests, so it stops jumping straight into code.

| Name | Type | What it does |
|---|---|---|
| [superpowers](https://github.com/obra/superpowers) | skills | Software development methodology built from composable skills: the agent asks what you want, writes a spec and implementation plan, then works through tasks with subagents, TDD and review. |
| [gstack](https://github.com/garrytan/gstack) | slash commands | Garry Tan's set of slash-command skills that turn Claude Code into a virtual engineering team: office hours, review, QA in a real browser, security audits and a ship command that opens the PR. |
| [ponytail](https://github.com/DietrichGebert/ponytail) | plugin | Plugin that makes the agent ask whether code needs to exist at all and pick the smallest complete change before writing anything. |
| [vibe-wise](https://github.com/nykooi1/vibe-wise) | plugin | Claude Code plugin that asks for your approach first, helps you weigh tradeoffs, and writes code only after you approve the design, then explains what it changed. |
| [mattpocock/skills](https://github.com/mattpocock/skills) | skills | Mattpocock's everyday engineering skills, including grill-me (relentless plan interview), grill-with-docs (builds glossary and ADRs) and improve-codebase-architecture. |
| tdd ([nulfrog/skills](https://www.skills.sh/nulfrog/skills/tdd), [superpowers](https://www.skills.sh/obra/superpowers/test-driven-development)) | skill | Test-driven development skills that enforce writing tests first in a red-green-refactor loop. |
| [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | skills | Production-grade engineering skills covering define, plan, build, verify, review and ship, driven by nine slash commands such as /spec, /plan and /build. |
| [planning-with-files](https://github.com/OthmanAdi/planning-with-files) | skill | Skill that keeps task_plan.md, findings.md and progress.md on disk, with hooks that reinject the plan so it survives /clear and context resets. |
| [beads](https://github.com/gastownhall/beads) | plugin | An open-source distributed graph issue tracker (bd) that gives Claude Code persistent task memory. |
| [skills](https://github.com/humanlayer/skills) | skill | An MIT-licensed set of Claude Code skills from HumanLayer for research, planning, implementation and pull request workflows. Some skills create pull requests. |
| [elephant-goldfish-model](https://github.com/google/elephant-goldfish-model) | plugin | Plugin for designing and reviewing software specs: an "elephant" drafts with your project context, then "goldfish" reviewers check it with fresh eyes. Needs a session that can start subagents. |
| [Jeffallan/claude-skills](https://github.com/Jeffallan/claude-skills) | plugin | 67 skills for languages, frameworks, DevOps and security, plus 9 epic workflow commands that need an Atlassian MCP server. |
| [tstack](https://github.com/t3dotgg/tstack) | skills | Theo's everyday PR skills for Claude Code and Codex: full-send takes a change to a merged PR, plus council review, babysit-pr and takeover. Needs the GitHub CLI; full-send can merge without you watching, and council and sol-loop call other providers' models. |
| [n8n-mcp](https://github.com/czlonkowski/n8n-mcp) | MCP | MCP server that gives Claude n8n node docs, templates and workflow tools. Telemetry is on by default (opt-out); with your n8n key it can edit and run workflows. |

### Multi-Agent & Orchestration

Run several agents or models at once and keep them coordinated.

| Name | Type | What it does |
|---|---|---|
| [ruflo](https://github.com/ruvnet/ruflo) | plugin | Agent meta-harness for Claude Code that adds multi-agent swarms, workflows, memory and cost tracking through installable plugins. Large project; some plugins can call cloud agents that cost API money. |
| [oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) | plugin | Multi-agent orchestration for Claude Code with team-style workflows and commands. Runs many sessions, so token use is high. |
| [claude-octopus](https://github.com/nyldn/claude-octopus) | plugin | Runs Claude, Codex, Gemini and other models on the same task and cross-checks them. Setup installs the Codex and Qwen CLIs globally; other providers need their own keys and can cost money. |
| [orca](https://github.com/stablyai/orca) | app | Desktop app that runs Claude Code and other coding agents in parallel, each in its own git worktree. MIT licensed; collects anonymous usage data unless you opt out. |
| [CLI-Anything](https://github.com/HKUDS/CLI-Anything) | plugin | Claude Code plugin marketplace that generates agent-usable command-line interfaces for existing software so Claude can drive it. Runs commands on your machine. |

### Setup, Rules & Guides

Configure Claude Code, learn how it works, and drop in rules files.

| Name | Type | What it does |
|---|---|---|
| [andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) | CLAUDE.md | A single CLAUDE.md with four principles (think before coding, simplicity first, surgical changes, goal-driven execution) based on Karpathy's observations on LLM coding mistakes. |
| [claude-codex-settings](https://github.com/fcakyon/claude-codex-settings) | plugins + CLAUDE.md | Marketplace of 40+ plugins plus a shared CLAUDE.md for Claude Code and Codex. Some plugins can change cloud infrastructure; others need third-party keys. |
| [claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice) | list | Guide to Claude Code concepts, workflows, skill and agent collections, and tips. |
| [claude-code-guide](https://github.com/zebbern/claude-code-guide) | guide + skills | Community guide to Claude Code setup, commands, hooks, MCP and agents, with a 70+ skill and agent pack. |
| [everything-claude-code (ECC)](https://github.com/affaan-m/ECC) | plugin | MIT-licensed Claude Code plugin with 71 agents, 314 skills, hooks, rules and memory for planning, testing, review and verification. |
| [cc-switch](https://github.com/farion1231/cc-switch) | app | Desktop app that switches API providers and manages MCP servers, skills and prompts for Claude Code, Claude Desktop and other agents. Rewrites your agent config files and holds API keys; the README carries paid relay-service ads. |
| [learn-claude-code](https://github.com/shareAI-lab/learn-claude-code) | tutorial | 17-lesson Python tutorial on building a Claude Code-style agent harness from scratch. Needs your own Anthropic API key; the lesson agents run shell commands. |
| [MCPJungle](https://github.com/mcpjungle/MCPJungle) | MCP | Self-hosted MCP gateway: register your MCP servers once and connect Claude to a single endpoint. Holds the credentials for those servers. |
| [i-have-adhd](https://github.com/ayghri/i-have-adhd) | skill | Small skill that makes Claude lead with the next action, number its steps and drop filler, installable as a Claude Code plugin. |

### Code Review & Safety

Review code and stop the agent from doing damage.

| Name | Type | What it does |
|---|---|---|
| [open-code-review](https://github.com/alibaba/open-code-review) | CLI + plugin | Reads your git diff and has an LLM write line-level review comments; has a Claude Code plugin. Needs your own LLM key unless you use delegate mode, and sends the diff to that model. |
| [cc-safety-net](https://github.com/kenryu42/cc-safety-net) | hook | Hook that blocks destructive shell commands and reads of secrets such as SSH keys and `.env` before the agent runs them. Not a sandbox. |
| [SkillSpector](https://github.com/NVIDIA/SkillSpector) | skill | An Apache-2.0 security scanner that checks agent skills, including Claude Code skills, for prompt injection, data exfiltration and supply-chain risks before install. |

### Token Saving & Cost

Spend fewer tokens or dollars, and see where they go.

| Name | Type | What it does |
|---|---|---|
| [caveman](https://github.com/JuliusBrussee/caveman) | skill + CLI | Skill and CLI that make the agent answer tersely in caveman style and shrink logs and tool output before the model reads them, to cut tokens. |
| [TokenEconomizer](https://github.com/microsoft/TokenEconomizer) | CLI | Microsoft Research tool that learns from past sessions in a repository to cut coding-agent cost (micro-skills, tool pruning, failure-loop intervention); reports 18.4-30.9% lower mean cost on SWE-Bench. |
| [9router](https://github.com/decolua/9router) | router | Local router that connects Claude Code and other coding tools to 40+ AI providers with auto-fallback and token trimming of tool output. |
| [codegraph](https://github.com/colbymchenry/codegraph) | MCP server | Local code knowledge graph exposed over MCP that auto-syncs on every file change. |
| [gemini-mcp-tool](https://github.com/jamubc/gemini-mcp-tool) | MCP server | MCP server that lets Claude call the Gemini CLI to use Gemini's large context window for analyzing big files. |
| [CodeBurn](https://codeburn.app) | CLI | Free, open-source, local-first tracker of AI coding token usage and cost across 42 tools, broken down by model, project and task. |
| [context-mode](https://github.com/mksglu/context-mode) | plugin | A free local Claude Code plugin and MCP server that keeps tool output out of the context window using a sandbox and SQLite full-text search. |
| [rtk](https://github.com/rtk-ai/rtk) | app | Rust CLI proxy that compresses command output before it reaches Claude to cut token use. Installs a Claude Code hook; the CLI is Apache-2.0 but its engine folder is BUSL-1.1 (source-available). |
| [headroom](https://github.com/headroomlabs-ai/headroom) | app | Compression layer that shrinks tool output, logs and files before they reach Claude, usable as a wrapper, proxy or MCP server. Telemetry can be turned off; a paid Teams offering is separate. |
| [token-optimizer](https://github.com/alexgreensh/token-optimizer) | plugin | Plugin that finds wasted tokens, checkpoints sessions across compaction and shows cost on a local dashboard. PolyForm Noncommercial: free for personal use and businesses under 5 people. |
| [mcp2cli](https://github.com/knowsuchagency/mcp2cli) | CLI + skill | Turns any MCP server, OpenAPI spec or GraphQL endpoint into a command-line tool at runtime, so an agent doesn't load every tool schema each turn; ships a skill for Claude Code. Supports OAuth and can send your credentials to the APIs you point it at. |

### Memory & Context

Stop the agent forgetting everything between sessions. Obsidian tools are under [Productivity](#notes--knowledge).

| Name | Type | What it does |
|---|---|---|
| [engram](https://github.com/Gentleman-Programming/engram) | MCP server + CLI | Persistent memory for Claude: a single Go binary with SQLite and FTS5, exposed through MCP, CLI, HTTP API and a TUI, usable with Claude Code and other MCP agents. |
| [claude-mem](https://github.com/thedotmack/claude-mem) | plugin | Plugin that automatically captures tool usage during sessions, generates semantic summaries and injects relevant context into future sessions. |
| [base](https://github.com/ChristopherKahler/base) | CLI | basemode: a Rust binary (base) that maps your workspace into a knowledge graph and wires it into Claude Code's hooks to brief the agent with relevant memory. |
| [codegraph](https://github.com/colbymchenry/codegraph) | MCP server | Local code knowledge graph exposed over MCP that auto-syncs on every file change. |
| [Understand-Anything](https://github.com/Egonex-AI/Understand-Anything) | plugin | Claude Code plugin that analyzes a project with a multi-agent pipeline, builds a knowledge graph of files, functions and dependencies, and offers an interactive dashboard to explore it. |
| [graphify](https://github.com/Graphify-Labs/graphify) | skill | An open-source /graphify skill for Claude Code that turns code, docs, schemas and PDFs into a queryable knowledge graph. |
| [mempalace](https://github.com/MemPalace/mempalace) | MCP | A free, local-first memory system that stores conversation history verbatim and retrieves it by semantic search through Claude Code hooks and an MCP server. |
| [GitNexus](https://github.com/abhigyanpatwari/GitNexus) | MCP | Indexes a repo into a knowledge graph and exposes it to Claude Code through MCP, skills and hooks. Free for noncommercial use only (PolyForm Noncommercial); commercial use needs a paid licence. |
| [ai-memory](https://github.com/akitaonrails/ai-memory) | MCP | Shared long-term memory layer that lets Claude Code sessions keep and hand off context across tools. Stores session memory locally. |
| [floorplan](https://github.com/haydenschmitty/floorplan) | plugin | Claude Code plugin that has Claude read your codebase and draw an interactive plain-English map of its parts, files and connections. Runs locally on your existing Claude plan. |
| [codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) | MCP | Indexes your repo into a local knowledge graph so Claude can query structure instead of re-reading files. The installer runs a curl or PowerShell script. |
| [serena](https://github.com/oraios/serena) | MCP | Toolkit that gives Claude IDE-style semantic code search, editing and refactoring. GPL-3.0; an optional JetBrains plugin is paid. |
| [book-to-skill](https://github.com/virgiliojr94/book-to-skill) | skill | Turns a technical book PDF into a chaptered skill Claude can consult on demand. Don't redistribute skills made from copyrighted books. |
| [cognee](https://github.com/topoteretes/cognee) | plugin | Memory layer that turns documents, code and chats into a knowledge graph agents can search across sessions; installs as a Claude Code plugin and runs locally. Using an LLM key sends data to that provider; Cognee Cloud is an optional paid service. |
| [agent-memory](https://github.com/tigerless-labs/agent-memory) | CLI + skill | MIT long-term memory for Claude Code and Codex: plain Markdown files are the source of truth, retrieval is local with no API key, and writes fire at conversation boundaries. |

### Browser & Computer Control

Let the agent read, search and browse the web, or drive a desktop app or a phone.

| Name | Type | What it does |
|---|---|---|
| [Agent-Reach](https://github.com/Panniantong/Agent-Reach) | skill + CLI | Skill and CLI that give an agent read and search access to platforms such as YouTube and Bilibili subtitles, GitHub, V2EX, web pages, Xiaohongshu and Twitter/X (experimental, needs login). |
| [playwright-mcp](https://github.com/microsoft/playwright-mcp) | MCP server | Microsoft's MCP server that gives an LLM browser automation through Playwright, using structured accessibility snapshots instead of screenshots. |
| [agent-browser](https://github.com/vercel-labs/agent-browser) | CLI | Native Rust CLI that lets an agent drive a persistent browser from the shell: snapshot a page as text with element refs, then click, fill and read again. |
| [obscura](https://github.com/h4ckf0r0day/obscura) | CLI | Open-source headless browser engine written in Rust for AI agents and scraping; runs JavaScript via V8, speaks Chrome DevTools Protocol, and can replace headless Chrome with Puppeteer or Playwright. |
| [BrowserMCP](https://github.com/BrowserMCP/mcp) | MCP | MCP server plus a Chrome extension that lets Claude control your own browser. |
| [crawl4ai](https://github.com/unclecode/crawl4ai) | MCP | Open-source web crawler and scraper with a hosted MCP server; the hosted cloud is optional, the core is self-hostable. |
| [stagehand](https://github.com/browserbase/stagehand) | SDK | MIT-licensed SDK for building browser agents that navigate sites, act on pages and extract data. Needs your own LLM API key (Anthropic for Claude); the Browserbase cloud is optional and paid. |
| [chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) | MCP | Google's MCP server that lets Claude debug, automate and profile a live Chrome browser. Usage stats are on by default (opt out with a flag) and it exposes page content to the agent. |
| [mobile-mcp](https://github.com/mobile-next/mobile-mcp) | MCP | MCP server that lets Claude control iOS and Android simulators, emulators and real devices. Telemetry is on by default; optional paid cloud devices. |
| [agent-desktop](https://github.com/vercel-labs/agent-desktop) | CLI | Apache-2.0 CLI from Vercel Labs that lets an AI agent see and operate desktop apps on macOS, Windows and Linux through the accessibility tree. Works with any agent that can run shell commands; it doesn't mention Claude by name. Snapshots can contain private desktop content. |
| [cua](https://github.com/trycua/cua) | app | Open-source infrastructure for computer-use agents (desktop-app driver, local VMs, sandboxes), with a Claude Code integration. Freemium: the hosted Spaces app has paid tiers. The agents control desktop apps, so review before running. |

### Docs & Databases

Give the agent current documentation and a way to query your databases.

| Name | Type | What it does |
|---|---|---|
| [context7](https://github.com/upstash/context7) | MCP server + plugin | Pulls up-to-date, version-specific library documentation and code examples into the agent's context so generated code matches the library versions you use. |
| [pg-aiguide](https://github.com/timescale/pg-aiguide) | plugin + MCP | Postgres best-practice skills and search over the Postgres and TimescaleDB manuals. The MCP is hosted by TigerData, so queries go to them. |
| [dbhub](https://github.com/bytebase/dbhub) | MCP | A minimal, token-efficient MCP server that lets Claude explore and query PostgreSQL, MySQL, MariaDB, SQL Server, Oracle and SQLite databases. Runs SQL against the databases you point it at; read-only mode is available. |


[↑ Contents](#contents)

## Games

### Game Dev

Build a game: engine skills, MCP servers and a full studio workflow.

| Name | Type | What it does |
|---|---|---|
| [pixelfx](https://github.com/patch-gg/pixelfx) | library + skill | A library of 244 pixel-art effects and animations (fire, explosions, magic, weather, UI) that are each drawn from code, plus a Claude Code skill for making new ones. |
| [awesome-gamedev-agent-skills](https://github.com/gamedev-skills/awesome-gamedev-agent-skills) | plugin | 77 game-development skills (Godot, Unity, Unreal and more) in SKILL.md format, with a router skill. |
| [godot-mcp](https://github.com/Coding-Solo/godot-mcp) | MCP | Lets Claude launch the Godot editor, run projects and read debug output. |
| [Claude-Code-Game-Studios](https://github.com/Donchitos/Claude-Code-Game-Studios) | skill + agents | Turns a Claude Code session into a game studio with 49 specialised agents, 70+ workflow skills, hooks and rules covering design, programming, art, audio, QA and production. MIT licensed. |
| [sprite-gen](https://github.com/aldegad/sprite-gen) | skill | Claude skill and Python CLI that turns one base image into clean transparent game sprite atlases and animation loops. Uses your own image/video provider keys, so generation can cost money. |

### Modding

Change or extend a game you already own. Different job from building one.

| Name | Type | What it does |
|---|---|---|
| [coop-anything](https://github.com/cranebeaker/coop-anything) | agent playbook | Agent playbook: tell Claude which single-player game you own and it researches, builds or fixes a co-op mod, tests it with bots, and packages it so friends join over Steam. |
| [universal-modder](https://github.com/rehan-remade/universal-modder) | plugin | Skills and a CLI that let Claude mod PC games you own. Broad permissions: injects into game processes and drives mouse and keyboard. Asset generation needs a paid fal key. |

[↑ Contents](#contents)

## Writing

### Research Writing

Polish, translate and review academic papers.

| Name | Type | What it does |
|---|---|---|
| [awesome-ai-research-writing](https://github.com/Leey21/awesome-ai-research-writing) | list | Prompt templates (translating, polishing, shortening, reviewer-style checks) and agent skills for writing research papers; the README is in Chinese. |
| [last30days-skill](https://github.com/mvanhorn/last30days-skill) | plugin | Researches a topic across Reddit, X, YouTube, Hacker News and the web from the last 30 days and writes a sourced summary. Sends search queries to those platforms. |
| [academic-research-skills](https://github.com/Imbad0202/academic-research-skills) | plugin | Skill suite that guides academic work through research, writing, review and revision with human sign-off at each stage. CC BY-NC: non-commercial use only. |
| [scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | skill | Library of 177 scientific skills for biology, chemistry, medicine and data analysis, plus guides to 100+ databases. Works across agents, Claude Code included. |
| [gpt-researcher](https://github.com/assafelovic/gpt-researcher) | app + skill | Research agent that searches the web and your files and writes a cited report; installs as a Claude skill. Free code, but needs your own OpenAI and Tavily keys (about $0.40 a run). |
| [Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) | skills | Markdown skill workflow where Claude Code runs research loops and drafts papers, with Codex as reviewer. Needs a Codex/OpenAI account and runs autonomously, so it can spend money. |
| [claude-code-my-workflow](https://github.com/pedrohcgs/claude-code-my-workflow) | template | Fork-ready Claude Code setup of agents, skills and hooks for academic slides, papers and R analysis. Ships broad allow rules such as `Bash(*)`. |

### Style & Fiction

Make writing sound human, plain or story-like.

| Name | Type | What it does |
|---|---|---|
| [humanizer](https://github.com/blader/humanizer) | skill | An MIT-licensed skill that rewrites AI-sounding text to read as human, based on Wikipedia's Signs of AI writing guide. |
| [SimpleEnglish](https://github.com/AminBlg/SimpleEnglish) | skill | A free MIT-licensed skill and Claude Code plugin that makes Claude write in ASD-STE100 Simplified Technical English. |
| [oh-story-claudecode](https://github.com/zenstory-ai/oh-story-claudecode) | skills | 14 skills for writing Chinese web novels: outlines, drafting and de-AI editing. README is Chinese-first; cover images need a paid image API. |

[↑ Contents](#contents)

## Productivity

### Notes & Knowledge

Turn notes and sources into something Claude can work with.

| Name | Type | What it does |
|---|---|---|
| [obsidian-skills](https://github.com/kepano/obsidian-skills) | skills | Agent skills by Obsidian's CEO for working with Obsidian, installable as a Claude Code plugin via the marketplace. |
| [claude-obsidian](https://github.com/AgriciDaniel/claude-obsidian) | plugin | Claude Code plugin that turns sources into a linked Obsidian wiki of plain Markdown notes. Free, local, says no telemetry. |
| [obsidian-second-brain](https://github.com/eugeniughelbur/obsidian-second-brain) | plugin | Persistent memory in an Obsidian vault with about 48 slash commands. Optional paid keys (Gemini, Perplexity, xAI) and an opt-in scheduled agent. |
| [notebooklm-py](https://github.com/teng-lin/notebooklm-py) | skill | Unofficial Python API, CLI and skill for Google NotebookLM; needs a NotebookLM account. |

### Product & Business

Skills for product managers and founders.

| Name | Type | What it does |
|---|---|---|
| [pm-skills](https://github.com/phuryn/pm-skills) | plugin | Marketplace of 69 product-management skills and 42 chained workflows covering discovery, strategy, PRDs, launch and metrics. |
| [Product-Manager-Skills](https://github.com/deanpeters/Product-Manager-Skills) | plugin | 77 product-management skills and 6 workflows for PRDs, roadmaps, discovery and research. CC BY-NC-SA 4.0: non-commercial use only. |
| [skills](https://github.com/slavingia/skills) | plugin | Ten skills based on The Minimalist Entrepreneur that walk you through finding a community, validating an idea, building an MVP, pricing and growing a business. |

[↑ Contents](#contents)

### Smart Home

Control and set up your home with Claude.

| Name | Type | What it does |
|---|---|---|
| [ha-mcp](https://github.com/homeassistant-ai/ha-mcp) | MCP server | Lets Claude control and set up Home Assistant: devices, automations, scenes, dashboards and config, through 87 tools. It runs with an administrator token, so it can change or delete automations and control devices; use a dedicated account. |

## Career

### Job Search

| Name | Type | What it does |
|---|---|---|
| [ai-job-search](https://github.com/ai-job-search-dev/ai-job-search) | framework on Claude Code | Job application framework built on Claude Code with commands to evaluate postings, tailor your CV, write cover letters and prep interviews; MIT licensed, fork and run locally. |
| [career-ops](https://github.com/career-ops-hq/career-ops) | plugin | Scans job boards, scores roles against your CV, tailors resumes and cover letters, and tracks applications. Your CV goes to the AI provider. |


[↑ Contents](#contents)

## Discovery

### Skill & Plugin Directories

Where to find more.

| Name | Type | What it does |
|---|---|---|
| [skills.sh](https://www.skills.sh/) | directory | Directory and leaderboard of agent skills, with packs, topics and audits. |
| [vercel-labs/skills](https://github.com/vercel-labs/skills) | CLI | The open agent-skills installer CLI (`npx skills add`), which installs skills from GitHub repos into Claude Code and other agents; discovery is via skills.sh. |
| [awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills) | list | Curated list of Claude Skills, resources and tools for customizing Claude workflows. |
| [awesome-claude-video-skills](https://github.com/zhuyansen/awesome-claude-video-skills) | list | Curated list of open-source skills and toolkits for making video with Claude Code (Remotion, HyperFrames, motion graphics, editing), covering 413 repos with a tested top-picks section. |
| [awesome-design-skills](https://github.com/bergside/awesome-design-skills) | list | Curated registry of 67 design-system skill files (each with SKILL.md and DESIGN.md) that you pull into a project with `npx typeui.sh pull`. |
| [wshobson/agents](https://github.com/wshobson/agents) | plugin marketplace | Marketplace of 94 plugins (202 agents, 185 skills, 105 commands) for Claude Code covering development, review, testing and infrastructure. |
| [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) | collection | Open-source library of 411 skills, plugins and agent skills for Claude Code across engineering, marketing, product, compliance and finance, with Python CLI helper scripts. |
| [agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills) | collection | About 2,950 installable skills for Claude Code and other agents, with a setup guide. Some bundled third-party skills use paid APIs, and it includes offensive-security bundles; run the installer with `--dry-run` first. |
| [top-claude-code-skills](https://github.com/selan-ai/top-claude-code-skills) | ranking | Daily-updated ranking of the top 15 Claude Code skills by GitHub stars (all time, this week, this month), each described from its own README. |
| [awesome-claude-code-skills](https://github.com/itgoyo/awesome-claude-code-skills) | list | Curated list of the top 200 GitHub repositories by stars in the Claude Code ecosystem: official tools, agent frameworks, skills, memory systems and MCP servers. |
| [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | list | Large curated list of MCP servers. |
| [claude-code-templates](https://github.com/davila7/claude-code-templates) | list | An MIT-licensed CLI and catalog of roughly 1,900 installable components for configuring and monitoring Claude Code. |
| [claude-howto](https://github.com/luongnv89/claude-howto) | list | A free MIT-licensed, example-driven guide to Claude Code with copy-paste templates for slash commands, hooks, subagents and MCP configs. |
| [awesome-harness-engineering](https://github.com/ai-boost/awesome-harness-engineering) | list | Curated list of patterns and tools for the harness around an AI model: context delivery, tool design, skills and MCP, memory, permissions and verification. Not Claude-only. |
| [awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) | list | Hand-curated list of Claude Code skills, agents, plugins, hooks, status lines and tooling. CC BY-NC-ND licence: link to it, don't copy its content. |
| [awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) | list | Curated list of 1,000+ agent skills from official teams and the community. Works across several agents, Claude Code included. |

**Security:** skills run commands on your machine, so read a skill before you install it.


[↑ Contents](#contents)

## Standalone

### Media Tools

Apps, models and datasets for video, image, audio and 3D. They run on their own and aren't Claude skills or plugins.

| Name | Type | What it does |
|---|---|---|
| [AI-Youtube-Shorts-Generator](https://github.com/Anil-matcha/AI-Youtube-Shorts-Generator) | app | Open-source Opus Clip alternative: an LLM picks highlights from long YouTube videos, Whisper transcribes, and clips are auto-cropped to 9:16 shorts. |
| [hotclip](https://github.com/xixihhhh/hotclip) | app | Free open-source local AI clipper that cuts long videos, livestream replays and podcasts into vertical 9:16 shorts with auto subtitles; publishing targets Chinese platforms. |
| [upscayl](https://github.com/upscayl/upscayl) | desktop app | Free and open-source AI image upscaler for Linux, macOS and Windows. |
| [MisoTTS](https://github.com/MisoLabsAI/MisoTTS) | model | Miso TTS 8B, an open 8-billion-parameter expressive text-to-speech model with a hosted demo and local setup via uv. |
| [VoiceStudio](https://github.com/debpalash/voicestudio) | app | Open-source (AGPL-3.0) local voice studio for cloning, designing, dubbing, dictating and transcribing voices in 646 languages, positioned as an ElevenLabs alternative. |
| [fish-speech](https://github.com/fishaudio/fish-speech) | model | Open-source text-to-speech and voice cloning model from Fish Audio. |
| [Rhubarb Lip Sync](https://github.com/DanielSWolf/rhubarb-lip-sync) | CLI | Command-line tool that automatically creates 2D mouth animation (mouth shapes) from voice recordings for games and cartoons. |
| [WhisperX](https://github.com/m-bain/whisperx) | CLI | Automatic speech recognition with word-level timestamps and speaker diarization, built on Whisper. |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | CLI | Feature-rich command-line audio/video downloader (Unlicense). |
| [NVIDIA SimReady Central](https://huggingface.co/spaces/nvidia/simready-central) | app | NVIDIA Hugging Face Space for semantic search of physics-ready OpenUSD 3D assets with RTX simulation previews. |


### Local Models & OCR

Run models on your own hardware, or read documents with AI. Not agent plugins.

| Name | Type | What it does |
|---|---|---|
| [airllm](https://github.com/lyogavin/airllm) | library | Python library for running large LLM inference on a single 4GB GPU (Apache-2.0). |
| [colibri](https://github.com/JustVugg/colibri) | inference engine | Hierarchical inference engine in C for large mixture-of-experts models: hot experts on GPU (CUDA, Vulkan), warm in RAM, cold streamed from NVMe. |
| [FreeToken](https://github.com/FlashML-org/FreeToken) | serving | Serving engine that aims to run massive models locally on a desktop (Apache-2.0). |
| [Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) | model | Baidu's OCR model for one-shot, long-horizon document parsing (MIT). |

### Agents & Harnesses

Separate agents you run yourself instead of adding them to Claude.

| Name | Type | What it does |
|---|---|---|
| [jcode](https://github.com/1jehuang/jcode) | agent harness | High-performance coding agent harness written in Rust, built to run many agents in parallel with low RAM use (MIT). |
| [BettaFish](https://github.com/666ghj/BettaFish) | multi-agent app | Multi-agent public-opinion analysis assistant that collects and analyses online discussion and predicts trends (GPL-2.0). |
| [hermes-agent](https://github.com/NousResearch/hermes-agent) | agent | Nous Research's open-source agent that grows with you (MIT). |
| [paperclip](https://github.com/paperclipai/paperclip) | app | Open-source (MIT) app for managing teams of AI agents at work. |
| [OpenMausBot](https://github.com/milind-soni/OpenMausBot) | bot | Open-source Grok Bot alternative with a virtual machine the bots can use (Apache-2.0). |

### Apps & Tools

Full products and tools. Useful, but you run them yourself.

| Name | Type | What it does |
|---|---|---|
| [open-codesign](https://github.com/OpenCoworkAI/open-codesign) | app | Open-source (MIT) Claude Design alternative that turns prompts into prototypes, slides or PDFs; multi-model, bring your own key, local-first. |
| [open-seo](https://github.com/every-app/open-seo) | app | Open-source (MIT) alternative to Semrush and Ahrefs for SEO. |
| [clauding](https://github.com/nishaj0/clauding) | app | Discord Rich Presence for Claude Code and the Claude desktop app: status, model and live token counts. |
| [craft-anything](https://github.com/storytold/craft-anything) | app | Open-source (MIT/Apache-2.0, early alpha) desktop app and MCP server that studies a website, app or game, then has Claude Code build your own version and check it against the original. |
| [mcp-use](https://github.com/mcp-use/mcp-use) | app | TypeScript framework for building MCP servers and MCP apps. |
| [whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) | MCP | An MIT-licensed MCP server that connects your personal WhatsApp account to Claude so it can search, read and send messages. Sends messages from your WhatsApp account. |
| [rea](https://github.com/morluto/rea) | MCP | MCP server for reverse engineering binaries, apps and runtime behavior, with Claude Code setup. Launches local analysis tools, so treat it as code-executing and security-sensitive. |
| [mcporter](https://github.com/openclaw/mcporter) | CLI + library | Lists and calls MCP servers from a terminal or TypeScript script, imports your Claude Code and Desktop MCP configs, and can package a server as its own CLI. Handles OAuth logins and runs the servers you configure. |

### Examples & Demos

See what people have built.

| Name | Type | What it does |
|---|---|---|
| [Claude-of-Duty](https://github.com/mshumer/Claude-of-Duty) | example | Demo of a Call of Duty-style first-person shooter in Three.js built from a single prompt (MIT). |
| [awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) | list | 100+ open-source AI agent, agent-skill and RAG app examples, including Claude and MCP ones. |

[↑ Contents](#contents)

## Types used in tables
`skill` (instructions Claude loads when needed) · `plugin` (an installable bundle of skills, commands or hooks) · `MCP` (a server the agent calls) · `hook` (runs automatically on an agent event) · `CLAUDE.md` (a rules file) · `CLI` · `app` · `collection` / `list` · `guide` / `tutorial` · `template` · `model` · `framework` / `engine` / `library`. Something like `skill + CLI` means it is both.


[↑ Contents](#contents)

## Security
Entries are checked for what they claim to do, but **they are not security-audited or guaranteed safe**. Skills, plugins and MCP servers can run commands, read your files and send data out. Read the source before you install anything, check what permissions it asks for, and take extra care with anything that sends messages, posts online or spends money. Scanners such as [SkillSpector](https://github.com/NVIDIA/SkillSpector) can help, but they don't replace reading it yourself.


[↑ Contents](#contents)

## Contributing
Add a row to the right section above. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Star History

<a href="https://www.star-history.com/?repos=nishaj0%2Fclaude-for-everything&type=date&releases=&legend=bottom-right">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=nishaj0/claude-for-everything&type=date&theme=dark&legend=bottom-right" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=nishaj0/claude-for-everything&type=date&legend=bottom-right" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=nishaj0/claude-for-everything&type=date&legend=bottom-right" />
 </picture>
</a>
