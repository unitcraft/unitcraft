[🇷🇺 Русский](README.ru.md) | **🇬🇧 English**

# 👋 Hi, I'm Evgeny Golovin

**Engineering Manager · Author of Nova Lang · Banking & Fintech · Remote across Russia**

Started as a developer — 3D mobile games in C++, web services in Java, Go, C#, TypeScript, PHP, React, full stack.
Moved into management and have been leading IT product development for 10+ years — from idea to production.
Currently working in banking, heading distributed teams remotely,
designing my own programming language Nova and using AI agents as part of everyday work.

| 10+ years | 5+ years | 5+ years |
|---|---|---|
| engineering management | web development · Java · Go · C# · TS · PHP · React | 3D mobile games · C++ |

---

## 🚀 Nova — a programming language for the AI era

> **«LLM writes the code — human reviews it».**
> The first language designed for this era.

Algebraic effects make side effects **visible right in the function signature**.
Reading a single line, a reviewer knows whether the function hits the DB, the network, reads the clock, or can fail — **without reading the body**.
This changes the game for reviewing AI-generated code.

```nova
fn process_order(o Order) Db Net Time Fail -> Receipt
```

The signature alone says: the function uses the **database**, makes **network requests**, reads **the clock**, and **can fail** — and nothing else.

### What makes Nova special

- ⚡ **Effects + handlers** — tests without mocks, the exact same code in production and tests
- 🔀 **No `async`/`await`** — structured concurrency, no «function colour»
- 🛡️ **Contracts from Go to F\*** — a gradient from script to verified code in one language
- 🎯 **Capability security** — `forbid Net, Fs` blocks an effect at compile time
- ⏱️ **Realtime blocks** — the compiler guarantees no GC pauses for audio/trading/embedded
- 🔄 **Time-travel debugging** — a natural consequence of handlers

🔗 [GitHub](https://github.com/unitcraft/nova-lang) · [GitVerse](https://gitverse.ru/unitcraft/nova-lang)

### 🤝 Grow Nova together

Looking for partner companies for contribution, sponsorship and joint research.
Happy to discuss any format of collaboration — from one-off patches to a dedicated team.

### 💼 Hiring

Open to engineering leader roles — especially with teams where AI tools
and modern engineering practices are already part of the culture.

✉️ **unitcraft@inbox.ru**

---

## 🤖 AI agents in practice

### ✍️ Writing code
- Scaffolding new services from scratch
- Refactoring legacy code without breaking business logic
- AI code review: SOLID violations, vulnerabilities, code smells
- **Tools:** Claude Code, Cursor, GitHub Copilot

### 🧪 Testing
- Generating unit and integration tests directly from code
- Building test cases and checklists from requirements and user stories
- Edge-case and boundary condition discovery
- Generating test data, mocks and stubs

### 🏗️ Architecture
- Designing microservice solutions with explicit trade-off analysis
- AI as a second voice in architecture sessions
- Writing Architecture Decision Records (ADR) with the agent
- Load analysis, bottleneck and failure point detection

### 📐 System analysis
- Breaking down business requirements into technical tasks
- API contracts, integration diagrams and data flows
- Generating documentation: README, runbooks, API descriptions
- Risk analysis and system degradation scenario planning

### 💡 IT solution design
- Analysing existing systems and making improvement recommendations
- Comparing tech stacks with banking and CII compliance in mind
- Preparing technical presentations for stakeholders
- Forming vendor and off-the-shelf solution evaluation criteria

---

## 🛠️ Stack

**AI agents:** Claude Code · Cursor · GitHub Copilot
**Languages:** Java · Go · C# · TypeScript · PHP · C++ · Rust · SQL
**Frontend:** React · TypeScript
**Databases:** PostgreSQL · MSSQL · MySQL · Oracle · Kafka
**Frameworks:** Spring Boot · Spring Cloud · Hibernate
**DevOps:** Docker · Kubernetes · OpenShift · GitLab CI · Jenkins
**Processes:** Scrum · Agile · Code Review · CI/CD · SDLC

---

## 🏆 Results

| Metric | Before | After |
|---|---|---|
| Release cadence | 3 per year | 4 per quarter |
| Contact centre load | baseline | −20% |
| Time-to-Market | baseline | −20% |
| Critical bugs in prod | recurring | 0 |

---

📧 **unitcraft@inbox.ru**
