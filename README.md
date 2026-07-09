<div align="center">

<!-- ⚡ Custom hand-built animated neural-network header (lives in /assets) -->
<img src="assets/neural-header.svg" width="100%" alt="Viral Patel — Founder · AI Engineer · Finland"/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=22&pause=900&color=00F0FF&center=true&vCenter=true&width=820&lines=Founder+%40+Ty%C3%B6Hunt+%E2%80%94+AI+that+reads+CVs+and+scores+every+job+in+Finland;LLM+pipelines+%C2%B7+batch+AI+scoring+%C2%B7+multi-agent+systems+in+production;23%2C500%2B+jobs+indexed+%C2%B7+~1%2C200%2Fday+%C2%B7+10+live+sources;B.Eng.+Artificial+Intelligence+%40+SAMK+%C2%B7+Helsinki+%F0%9F%87%AB%F0%9F%87%AE;while+(alive)+%7B+ship()%3B+%7D" alt="Typing intro"/>

<br/><br/>

<a href="https://tyohunt.com"><img src="https://img.shields.io/badge/⚡_TyöHunt-PRODUCTION-00f0ff?style=for-the-badge&labelColor=05070f"/></a>
<a href="https://viralpatelz.com"><img src="https://img.shields.io/badge/🌐_viralpatelz.com-portfolio-7b2fff?style=for-the-badge&labelColor=05070f"/></a>
<a href="https://instagram.com/viralpatelz"><img src="https://img.shields.io/badge/Instagram-@viralpatelz-ff2fb9?style=for-the-badge&logo=instagram&logoColor=white&labelColor=05070f"/></a>
<img src="https://komarev.com/ghpvc/?username=Viralpatelz&style=for-the-badge&color=00f0ff&labelColor=05070f&label=VISITORS"/>

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
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#0a0e1f','primaryBorderColor':'#00f0ff','primaryTextColor':'#c9d1d9','lineColor':'#7b2fff','fontFamily':'Fira Code'}}}%%
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

| ⚙️ TELEMETRY | VALUE |
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
<img src="https://img.shields.io/badge/Multi--Agent_Systems-00f0ff?style=for-the-badge&labelColor=05070f"/>
<img src="https://img.shields.io/badge/Prompt_%26_Cost_Engineering-7b2fff?style=for-the-badge&labelColor=05070f"/>

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

<img src="https://github-readme-stats.vercel.app/api?username=Viralpatelz&show_icons=true&theme=tokyonight&hide_border=true&bg_color=05070f&title_color=00f0ff&icon_color=7b2fff&text_color=c9d1d9&ring_color=00f0ff" height="170"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Viralpatelz&layout=compact&theme=tokyonight&hide_border=true&bg_color=05070f&title_color=00f0ff&text_color=c9d1d9" height="170"/>

<img src="https://streak-stats.demolab.com/?user=Viralpatelz&theme=tokyonight&hide_border=true&background=05070f&ring=00f0ff&fire=ff2fb9&currStreakLabel=00f0ff&sideLabels=7b2fff" height="170"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Viralpatelz&custom_title=Commit%20Signal&bg_color=05070f&color=00f0ff&line=7b2fff&point=ff2fb9&area=true&area_color=0a0e1f&hide_border=true" width="94%"/>

<a href="https://github.com/Viralpatelz"><img src="https://github-profile-trophy.vercel.app/?username=Viralpatelz&theme=discord&no-frame=true&no-bg=true&column=7&title_color=00f0ff" width="94%"/></a>

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

<img src="assets/footer.svg" width="100%" alt="system online — always shipping"/>

<sub>⚡ hand-crafted animated SVGs, zero templates · © Viral Patel · Helsinki, Finland</sub>

</div>
