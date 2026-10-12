# Santiago Hernández

I lead product engineering and build systems for responsible AI adoption.

Tech Lead experienced in production platform architecture across web, mobile, and AWS. I contributed to an organizational standard for working with AI in production software.

## What I bring to a team

Projects change, but the skills I bring to each one travel with me.

- **Responsible AI adoption.** I contributed to a 22-rule organizational standard across six areas. Each rule has a hook, CI check, review, or PR template behind it.
- **Architecture and migration.** I moved a legacy Spring Boot API gateway to NestJS while preserving its client contract. Customers experienced no downtime.
- **Product design and validation.** Before building, I explore solution options and their tradeoffs, validate product decisions with the PM, and ask the agent to list its assumptions so I can challenge them before writing code. I write a spec for almost everything.
- **Quality and evidence.** I believe nothing is ready without evidence, and the agent that wrote the code does not certify it. I use TDD and check edge cases before calling work done.
- **Estimation and delivery.** I estimate AI-assisted work in parallel waves, with human review points and explicit assumptions when questions remain open.
- **Technical leadership and hiring.** I use stack-independent interviews to assess reasoning, system design, and the ability to review generated code. I lead engineering and set practices for AI adoption across development, design, product, and QA.

## Key decisions

- **Gateway migration.** I moved the gateway to NestJS while preserving the same contract for clients. Customers experienced no downtime.
- **Enforced AI standard.** I contributed 22 rules with hooks, CI checks, reviews, or PR templates. I chose not to measure the percentage of code written by AI. CI publishes each change to the wiki, and a hook checks the HTML version against the sources.
- **Shared skills.** I chose a plugin marketplace and a desktop app that prepares the setup for each role. The 27 skills update automatically, and a hook proposes a PR when someone changes a skill.

## Principles

- Product decisions belong to a person, not the agent.
- A rule without a mechanism is only an intention.
- Every failure becomes a control.
- Design validation takes minutes; code rework takes hours.
- Nothing is ready without evidence.
- The agent that wrote the code does not certify it.

## Public engineering controls

- [claude-code-guardrails](https://github.com/hernandezsanti/claude-code-guardrails): Blocks pushes and merges to main without human approval and limits test workers based on available RAM.
- [claude-code-mods](https://github.com/hernandezsanti/claude-code-mods): Requires a ticket in every commit, protects paid CI minutes, and closes worktrees when a PR opens.
- [ccuse](https://github.com/hernandezsanti/ccuse): Switches Claude Code accounts when one runs out of quota.
- [tupase-mcp](https://github.com/hernandezsanti/tupase-mcp): Provides an MCP server for booking classes.

## A lab for testing ideas with real products

I make the design, backend, and app for each product, then use it to test ideas before bringing them to teams.

- [TorneosPadelUy](https://torneospadel.uy/): Covers amateur padel tournaments across Uruguay, with one Expo and React Native codebase for iPhone and web.
- PadelBump: Brings live professional padel to iPhone through Live Activities, with a backend that checks matches every 10 seconds.
- Pila: Reads Apple Health and recommends how much to train based on your own history, calculated on the phone rather than against averages.

## Compare notes on AI adoption in engineering

I am open to conversations about AI adoption, architecture, and technical leadership. [hernandezsanti.dev](https://hernandezsanti.dev) · [hi@hernandezsanti.dev](mailto:hi@hernandezsanti.dev) · [LinkedIn](https://www.linkedin.com/in/santiago-hernandez-gonzalez/)

Most of my work lives in private client repositories.
