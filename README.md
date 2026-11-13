# Özgür Çetintaş

Senior QA engineer who builds things. Eight years of making software trustworthy, from payment flows to video engines to AI features. Based near Rotterdam.

[Portfolio](https://ozgurcetintas.dev) · [LinkedIn](https://www.linkedin.com/in/ozgurcetintas/)

---

## At work

I own release quality for a portfolio of 20+ iOS, Android and web apps at Pixery: about 1,000 automated tests and the CI quality gates in front of every release. The code below is private; the details are on [my portfolio](https://ozgurcetintas.dev/#work).

- **AI-driven end-to-end tester**: an LLM agent drives a real headless browser through our payment funnels like a customer, then checks the confirmation email, the purchase in the back end and the analytics events. *Playwright · LLM agents · MCP*
- **Video engine regression suite**: with one colleague, a Robot Framework suite that compares every rendered frame of a C/C++ video engine with a golden reference and checks timing. It runs in a Jenkins pipeline I set up and has been in use since 2021. *Python · Robot Framework · Jenkins*
- **Build and deployment platform**: replaced Bitrise for 10 mobile apps, cut build times from 40 to 13 minutes and avoided an estimated $24K a year in tooling costs. *Java · Jenkins · Docker · Node.js · React · MongoDB*
- **Testing AI image generation**: Promptfoo regression tests that check the prompts behind AI image features keep the user's requirements. *Promptfoo · LLM evaluation*
- **Mobile, web and API automation framework** (Pixery, 2019 – 2022): as the first dedicated QA hire, one Java codebase for Appium, Selenium and REST Assured tests, with the Jenkins CI/CD pipeline that runs it. It became the base of today's ~1,000-test regression suite. *Java · Appium · Selenium · REST Assured · Cucumber · TestNG · Maven · Jenkins*
- **3-D Secure 2.0 payment authentication** (Finartz, 2018 – 2019): 10,000+ data-driven Cucumber scenarios against the EMVCo, Mastercard and Visa specifications, plus API and JMeter performance tests. The server passed certification. *Java · REST Assured · Cucumber · TestNG · JMeter*

---

## Open source

### [TestLease](https://github.com/testlease/testlease)
Stops parallel test runs from colliding on shared test accounts: exclusive, expiring leases with crash recovery, Playwright fixtures, a REST API and an MCP server so AI agents can borrow test resources too. Built for a problem I hit at work.
**TypeScript · REST API · Playwright · MCP · Docker**

### [Trident](https://github.com/cozgur/trident)
An open-source rebuild of the kind of Java framework I built at Finartz and Pixery, consumed from Maven Central rather than forked: one Cucumber runner with REST Assured API and Selenium 4 web layers, and a Maven archetype that takes a new project to a green suite in seconds. Developed against a 2005 JSP banking app with no test hooks; a [separate showcase](https://github.com/cozgur/trident-showcase) adopts it from Central against an unrelated API, which found two gaps that were fixed in the framework. Every decision is recorded as an [ADR](https://github.com/cozgur/trident/tree/main/docs/adr).
**Java 21 · Maven · Cucumber · Selenium 4 · REST Assured · Testcontainers**

### [Kafka Ledger Lab](https://github.com/cozgur/kafka-ledger-lab-java)
Testing Kafka event-streaming guarantees for a payments → ledger flow: a Java and Spring Kafka service tested against real Kafka, PostgreSQL and Schema Registry through Testcontainers. Covers ordering, idempotency, dead-lettering, replay, consumer rebalances, a SIGKILL inside the at-least-once loss window, and database and broker outages. A personal learning lab, not production experience.
**Java 21 · Spring Kafka · Testcontainers · PostgreSQL**

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

**Tools I use most:** TypeScript · Java · Python · Playwright · Selenium · Appium · Maestro · REST Assured · Cucumber · GitHub Actions · Jenkins · Docker · Claude Code
