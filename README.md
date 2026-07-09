<div align="center">

<!-- ⟡ Aurora Intelligence — hand-built animated SVG, northern lights as neural pathways -->
<img src="assets/neural-header.svg" width="100%" alt="Viral Patel — Founder · AI Engineer · Suomi"/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=22&pause=900&color=3DFFB8&center=true&vCenter=true&width=820&lines=Founder+%40+Ty%C3%B6Hunt+%E2%80%94+AI+that+reads+CVs+and+scores+every+job+in+Finland;LLM+pipelines+%C2%B7+batch+AI+scoring+%C2%B7+multi-agent+systems+in+production;23%2C500%2B+jobs+indexed+%C2%B7+~1%2C200%2Fday+%C2%B7+10+live+sources;B.Eng.+Artificial+Intelligence+%40+SAMK+%C2%B7+Helsinki+%F0%9F%87%AB%F0%9F%87%AE;while+(alive)+%7B+ship()%3B+%7D" alt="Typing intro"/>

<br/><br/>

<a href="https://tyohunt.com"><img src="https://img.shields.io/badge/⟡_TyöHunt-PRODUCTION-3dffb8?style=for-the-badge&labelColor=02030a"/></a>
<a href="https://viralpatelz.com"><img src="https://img.shields.io/badge/🌌_viralpatelz.com-portfolio-7ee7ff?style=for-the-badge&labelColor=02030a"/></a>
<a href="https://instagram.com/viralpatelz"><img src="https://img.shields.io/badge/Instagram-@viralpatelz-b593ff?style=for-the-badge&logo=instagram&logoColor=white&labelColor=02030a"/></a>
<img src="https://komarev.com/ghpvc/?username=Viralpatelz&style=for-the-badge&color=3dffb8&labelColor=02030a&label=VISITORS"/>

</div>

<br/>

## `$ system.boot()`

```console
[ 0.000001 ]  KERNEL .......... viral_patel v2026.7 — Helsinki, Finland 🇫🇮
[ 0.000002 ]  ROLE ............ solo founder · full-stack AI engineer
[ 0.000003 ]  MOUNTING ........ /tyohunt ..................... [ LIVE ✓ ]
[ 0.000004 ]  STRIPE .......... live mode, real revenue ...... [ OK ✓ ]
[ 0.000005 ]  AI CORE ......... GPT + Claude, batch-scored ... [ ONLINE ✓ ]
[ 0.000006 ]  EDUCATION ....... B.Eng. AI @ SAMK ............. [ RUNNING ]
[ 0.000007 ]  MISSION ......... first 100 paying customers ... [ EXECUTING ]
[ 0.000008 ]  FAILSAFE ........ "if one way fails, find another"
[ 0.000009 ]  boot complete. nothing is impossible. █
```

<br/>

## `$ tyohunt --architecture`

> **[TyöHunt](https://tyohunt.com)** — an AI employment engine I designed, built and run alone: scrapers → dedup → LLM scoring → matching → payments. Every box below is production code.

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#0a1224','primaryBorderColor':'#3dffb8','primaryTextColor':'#cfe8ff','lineColor':'#7ee7ff','fontFamily':'Fira Code'}}}%%
flowchart LR
    A["🕷️ 10 scrapers<br/>~1,200 jobs/day"] --> B["🧹 Cross-source<br/>dedup engine"]
    B --> C[("🗄️ PostgreSQL<br/>23,500+ jobs")]
    D["📄 User CV"] --> E["🧠 LLM parser<br/>skills · seniority · langs"]
    C --> F{"⚡ Batch AI<br/>scoring core"}
    E --> F
    F --> G["🎯 Ranked matches<br/>+ reasoning"]
    G --> H["📊 Salary insights<br/>📝 CV builder<br/>🎤 Interview prep"]
    H --> I["💳 Stripe<br/>LIVE"]
    J["🛰️ Celery + Redis<br/>async pipelines"] -.-> A & F
    K["🚨 Sentry + CI gates<br/>staging → main"] -.-> F & I
```

<div align="center">

| ⟡ TELEMETRY | VALUE |
|---|---|
| Jobs indexed | **23,500+** and counting |
| Ingestion rate | **~1,200 / day**, 10 live sources |
| AI matching | LLM-scored, CV-aware, cost-optimized batching |
| Security audit | **A−** — zero exploitable vulns |
| Team size | **1** (me, and an army of AI agents) |

</div>

<br/>

## `$ stack --loadout`

<div align="center">

**🧠 AI & Intelligence**

<img src="https://img.shields.io/badge/OpenAI_GPT-412991?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Anthropic_Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/Multi--Agent_Systems-3dffb8?style=for-the-badge&labelColor=02030a"/>
<img src="https://img.shields.io/badge/Prompt_%26_Cost_Engineering-b593ff?style=for-the-badge&labelColor=02030a"/>

**⚙️ Engine Room**

<img src="https://skillicons.dev/icons?i=python,fastapi,postgres,redis,nextjs,react,ts,tailwind&theme=dark"/>

**🛰️ Ops & Delivery**

<img src="https://skillicons.dev/icons?i=docker,nginx,linux,git,github,githubactions,vscode,sentry&theme=dark"/>

<img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white"/>
<img src="https://img.shields.io/badge/Stripe_LIVE-635BFF?style=for-the-badge&logo=stripe&logoColor=white"/>
<img src="https://img.shields.io/badge/Lighthouse_CI-F44B21?style=for-the-badge&logo=lighthouse&logoColor=white"/>

</div>

<br/>

## `$ ls ~/lab` <sub>— open-source AI tooling</sub>

<table align="center">
<tr>
<td width="50%">

### 🔮 [Repo2Prompt](https://github.com/Viralpatelz/Repo2Prompt)
`Python` — Compresses an entire codebase into one LLM-ready context prompt. Feed your repo to any model.

</td>
<td width="50%">

### 🔥 [TokenBurn](https://github.com/Viralpatelz/TokenBurn)
`Python` — Watches your LLM token spend in real time before it watches your wallet burn.

</td>
</tr>
<tr>
<td width="50%">

### 🌲 [AgentTree](https://github.com/Viralpatelz/AgentTree)
`Python` — Experiments in orchestrating trees of AI agents that plan, delegate and verify.

</td>
<td width="50%">

### 🧰 [mcphub-cli](https://github.com/Viralpatelz/mcphub-cli)
`CLI` — Command-line gateway into the Model Context Protocol ecosystem.

</td>
</tr>
</table>

<br/>

## `$ telemetry --live`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Viralpatelz&show_icons=true&theme=tokyonight&hide_border=true&bg_color=02030a&title_color=3dffb8&icon_color=7ee7ff&text_color=cfe8ff&ring_color=3dffb8" height="170"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Viralpatelz&layout=compact&theme=tokyonight&hide_border=true&bg_color=02030a&title_color=3dffb8&text_color=cfe8ff" height="170"/>

<img src="https://streak-stats.demolab.com/?user=Viralpatelz&theme=tokyonight&hide_border=true&background=02030a&ring=3dffb8&fire=b593ff&currStreakLabel=3dffb8&sideLabels=7ee7ff" height="170"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Viralpatelz&custom_title=Aurora%20Signal&bg_color=02030a&color=3dffb8&line=7ee7ff&point=b593ff&area=true&area_color=0a1224&hide_border=true" width="94%"/>

<a href="https://github.com/Viralpatelz"><img src="https://github-profile-trophy.vercel.app/?username=Viralpatelz&theme=discord&no-frame=true&no-bg=true&column=7&title_color=3dffb8" width="94%"/></a>

<!-- 🐍 generated daily by .github/workflows/snake.yml -->
<img src="https://raw.githubusercontent.com/Viralpatelz/Viralpatelz/output/github-snake-dark.svg" width="94%" alt="contribution snake"/>

</div>

<br/>

## `$ cat /etc/principles`

```yaml
ship_daily:        "a feature in staging helps no one"
verify_first:      "never claim untested work works — run it, prove it"
ai_is_leverage:    "one founder + agents > a slow team of ten"
cost_awareness:    "every LLM call is a line item — batch it, cache it"
failure_protocol:  "if one way fails, find another. always ship."
```

<div align="center">

<br/>

<img src="assets/footer.svg" width="100%" alt="aurora online — always shipping"/>

<sub>⟡ Aurora Intelligence — hand-crafted animated SVGs, zero templates · © Viral Patel · Helsinki, Finland</sub>

</div>
