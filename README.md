# Santiago Hernández

I help engineering teams use AI coding agents without lowering the bar for what reaches production.

Tech Lead at Neocoast · Montevideo, Uruguay

## What I do

I lead engineering for a K-12 EdTech platform that teaches and measures Spanish reading, used by schools across the United States and Latin America.

I am responsible for the architecture, new features, DevOps, and production support. I make the technical decisions and live with their consequences.

The system is a microservices platform across nearly twenty repositories, with NestJS and Java services, React, React Native, and Vue frontends, and AWS infrastructure. I migrated its legacy Spring Boot gateway to NestJS with no customer downtime.

My work also includes school ecosystem integrations: single sign-on and rostering with leading K-12 identity providers, plus the payment gateway used by families. I built the reading analytics that turns student recordings into progress teachers and districts can use.

Since 2023, I have also led engineering for a US-based training company. That includes its Meteor and React learning platform, as well as a second product I built from scratch for engineering calculations used by industrial teams.

## AI-assisted engineering

I wrote and maintain Neocoast's AI engineering standard: how we deliver software with AI agents across our own products and client work.

It includes 22 numbered rules across six areas: authority and risk, data and trust, process, evidence, code quality, and cost. It is supported by a playbook explaining the reasoning behind each rule, plus guidance for spec-driven development and TDD with agents.

The central idea is simple: every rule needs an enforcement mechanism. A hook, CI check, review step, or PR template. Without one, a rule is only an intention.

Examples from the standard:

- Irreversible actions require authorization that names both the action and its target.
- A human gate sits between planning and building.
- Pull requests include a `## Evidence` section with literal command output.
- Anything an agent reads from outside the system is data, never instruction, as a defense against prompt injection.
- Third-party skill sets are audited and pinned to a commit.
- We do not measure "percentage of code written by AI."

The standard is maintained as code. Its Markdown sources are versioned, CI publishes every merge to the company wiki, and a hook generates an HTML version and verifies it word for word against the sources.

I built Neocoast's internal toolkit: 27 Claude Code skills distributed as an auto-updating plugin marketplace for developers, designers, PMs, and QA. For QA, I built an agent framework with atomic skills and an orchestrator that explores an application, generates test cases, and runs them in the browser with human checkpoints. It has been validated end to end in a real product.

I apply the same standard to my own work: hooks block pushes and merges to production branches, test workers are limited based on available RAM so parallel agents do not freeze the machine, CI minutes are treated carefully, and skills can drive a real iPhone from a Mac through XCUITest for end-to-end QA.

## Stack

NestJS, Node.js, TypeScript, React, React Native, Vue, Java / Spring Boot, AWS, MySQL, PostgreSQL. AI tooling: Claude Code, MCP, skills, hooks, and plugins. Previous production experience with Meteor, MongoDB, and Ruby on Rails.

## Education and contact

Computer Engineering, Universidad de la República, Uruguay.

LinkedIn: https://www.linkedin.com/in/santiago-hernandez-gonzalez/ · Email: hernandezsantiago25@gmail.com

Most of this work lives in private Neocoast and client repositories, so the contribution graph includes private contributions.
