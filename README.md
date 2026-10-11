<!-- Header: name + tagline + slim badges only (centered) -->
<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,100:2563eb&height=180&section=header&text=Santiago%20Hern%C3%A1ndez&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=40)

### AI Engineer · Agentic software development · Backend & Cloud background

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3500&pause=1000&color=2563EB&center=true&vCenter=true&width=600&lines=Bringing+AI+agents+into+real+engineering+teams;Skills+%C2%B7+Hooks+%C2%B7+MCP+%C2%B7+Agent+workflows;Spec-driven+%2B+TDD+with+coding+agents)](https://git.io/typing-svg)

![Profile views](https://komarev.com/ghpvc/?username=hernandezsanti&label=Profile%20views&color=2563eb&style=flat)

</div>

### 👋 What I do

I am an AI Engineer at **[Neocoast](https://www.neocoast.com/)**. My work is to make AI coding agents useful and safe inside real engineering teams: I define how the company builds software with agents, I build the tooling that makes it repeatable, and I help developers, designers, PMs and QA adopt it.

Before this I spent **5+ years** building and scaling production software. My core is **Node.js and React**: backend services, web apps and cloud infrastructure on AWS. That background is why I care about agents that ship code you can trust, not only demos.

Computer Engineering, **UdelaR** (Uruguay). Based in Montevideo 🇺🇾.

### 🤖 What I have built

**AI engineering standard.** I wrote and maintain the standard that defines how Neocoast delivers software with AI coding agents, both on its own products and on client projects. It has 22 numbered rules in six areas (authority and risk, data and trust, process, evidence, code quality and cost), a playbook that explains the reason behind each rule, and a practical guide to spec-driven development and TDD with agents.

Every rule carries three labels: if it also applies to throwaway spikes, if it goes into the agent's `CLAUDE.md` / `AGENTS.md` or is enforced by the team (CI, CODEOWNERS, PR template), and the **mechanism** that enforces it. A rule without a mechanism is only an intention.

<details>
<summary>Some of the ideas in it</summary>

- Irreversible actions (push to protected branches, migrations, deploys, production data) need an authorization that names the action and the target. "Go ahead" is not an authorization.
- A human gate between plan and build. Fixing a plan costs minutes, fixing code that is already written costs hours.
- TDD where you have to see the test fail, and fail for the right reason. If the agent changes the test to make it pass, that is an incident.
- Every PR has an `## Evidence` section with the literal output of the command, never a summary of it.
- Everything an agent reads from outside (issues, web pages, logs, MCP output) is data, never an instruction. This is the defense against prompt injection, together with a permission allowlist that is reviewed as code.
- Third-party skill sets are supply chain: they are audited and pinned to a commit before they are installed.
- An agent creates abstractions for free, so the brake has to be written: abstract on the third occurrence, not on the second.
- A correction that repeats twice becomes an artifact (a rule, a skill, a test or a hook), never "be more careful".
- Before kickoff, the client contract is checked for AI use and the token cost is defined in the proposal.
- We measure evidence coverage and rework rate. We explicitly do not measure "% of code written by AI", because it rewards volume, not quality.

</details>

The standard is maintained as code. The Markdown sources are versioned in a repo, rules are never renumbered because project files reference them, CI publishes every merge to the company wiki, and a pre-commit hook generates a shareable HTML version and verifies it word by word against the sources. A companion skill audits any repo against the standard, and a starter kit scaffolds new projects already aligned with it.

**Company-wide agent toolkit.** A collection of 27 Claude Code skills, tools and configurations, distributed as a plugin marketplace with automatic updates. It covers the whole team, not only developers: estimation, Jira breakdown, design system work in Figma, store review checks, privacy and compliance audits, meeting recaps and more.

**Agentic QA framework.** Atomic QA skills plus a thin orchestrator that chains them: explore an app, generate test cases, execute them in the browser and sync the results to the test management tool. It has human checkpoints and shared anti-hallucination principles, and it was validated end to end on a real product.

**Agent onboarding for non-technical roles.** An interactive CLI that prepares a machine for agents and suggests the right tools and MCP servers depending on the role (PM, designer or QA).

**Agent infrastructure I use every day.** I apply the same standard to my own work, and several of these hooks enforce its rules on my machine:
- Guardrails as hooks: block pushes and merges to production branches, and cap test runner workers based on free RAM so parallel agents do not freeze the machine.
- Plugins that protect paid CI minutes, enforce ticket-based commits and clean up git worktrees when a PR is opened.
- A multi-account switcher for Claude Code with quota monitoring in the status line.
- Skills that drive a real iPhone from the Mac with XCUITest, so an agent can do end to end QA on a physical device.
- Custom MCP servers and a Claude-powered assistant that runs on my own server.

### 🧩 Tech

**AI:** `Claude Code` `Claude API` `MCP` `Agent skills` `Hooks & plugins` `Multi-agent workflows`<br>
**Backend & data:** `Node.js` `TypeScript` `Python` `Java` `Spring Boot` · `MySQL` `PostgreSQL` `Redis`<br>
**Frontend & mobile:** `React` `Next.js` `React Native` `Vue` `Nuxt` `Swift`<br>
**Cloud & infra:** `AWS` `Docker` `Terraform` `GitHub Actions`

![Claude](https://img.shields.io/badge/Claude%20Code-D97757?style=flat&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat&logo=modelcontextprotocol&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

### 📊 Activity

<div align="center">

<img alt="Santiago's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=hernandezsanti&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" />
<img alt="GitHub streak" src="https://streak-stats.demolab.com?user=hernandezsanti&theme=tokyonight&hide_border=true" height="165" />

</div>

### 📫 Find me

[LinkedIn](https://www.linkedin.com/in/santiago-hernandez-gonzalez/) · [Email](mailto:hernandezsantiago25@gmail.com) · [Neocoast](https://www.neocoast.com/)

---

<sub>Last updated: October 2026</sub>
