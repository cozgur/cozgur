# Özgür Çetintaş

Senior QA engineer who builds things. Eight years of making software trustworthy, from payment flows to video engines to AI features. Based near Rotterdam.

At work I own release quality for a portfolio of 20+ iOS, Android and web apps: about 1,000 automated tests, the CI quality gates in front of every release, and an AI agent that walks our payment funnels like a real customer. The projects below are what I build in the open.

[Portfolio](https://ozgurcetintas.dev) · [LinkedIn](https://www.linkedin.com/in/ozgurcetintas/)

---

## Open source

### [TestLease](https://github.com/testlease/testlease)
Stops parallel test runs from colliding on shared test accounts: exclusive, expiring leases with crash recovery, Playwright fixtures, a REST API and an MCP server so AI agents can borrow test resources too. Built for a problem I hit at work.
**TypeScript · REST API · Playwright · MCP · Docker**

### [Trident](https://github.com/cozgur/trident)
A Java test automation framework consumed from Maven Central rather than forked: one Cucumber runner with REST Assured API and Selenium 4 web layers, and a Maven archetype that takes a new project to a green suite in seconds. Developed against a 2005 JSP banking app with no test hooks; a [separate showcase](https://github.com/cozgur/trident-showcase) adopts it from Central against an unrelated API, which found two gaps that were fixed in the framework. Every decision is recorded as an [ADR](https://github.com/cozgur/trident/tree/main/docs/adr).
**Java 21 · Maven · Cucumber · Selenium 4 · REST Assured · Testcontainers**

### [Modern Quality Engineering Lab](https://github.com/cozgur/modern-quality-engineering-lab)
A small TypeScript service tested the way I would test a production system: unit, API, Pact contracts, PostgreSQL via Testcontainers, Playwright with accessibility checks, k6 performance budgets, Promptfoo evaluations and OpenTelemetry traces, all as parallel CI jobs. [Live reports](https://lab.ozgurcetintas.dev/) · [Test strategy](https://github.com/cozgur/modern-quality-engineering-lab/blob/main/docs/test-strategy.md)
**TypeScript · Playwright · Pact · Testcontainers · k6 · OpenTelemetry · Promptfoo**

### [TestPlan Studio](https://github.com/cozgur/testplan-studio)
Turns an application brief into a risk-based test plan with Claude, compiles the browser scenarios into a linted Playwright spec and runs it on GitHub Actions. The model proposes; deterministic checks and a human decide. [Live](https://studio.ozgurcetintas.dev/)
**TypeScript · React · Playwright · Claude · GitHub Actions**

---

## Apps I ship

- **[CipherBreaker](https://apps.apple.com/app/id6777961704)**: a 1v1 code-breaking game I build and run alone, from code to App Store operations. React Native, strict TypeScript, about 285 Jest test files plus Maestro end-to-end flows. [Play today's puzzle](https://cipherbreaker.app/play/)
- **[Outguess](https://apps.apple.com/app/id6808974621)**: a 1v1 word game with solver-based bots and Game Center. React Native, TypeScript. [outguessapp.com](https://outguessapp.com/)

Source code for both apps is private.

---

**Tools I use most:** TypeScript · Java · Python · Playwright · Selenium · Appium · Maestro · REST Assured · GitHub Actions · Docker · Claude Code
