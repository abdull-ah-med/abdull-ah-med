<h1 align="center">Abdullah Ahmed</h1>

<p align="center">
  <strong>Software Engineer @ CCRIPT Agency</strong>
</p>

<p align="center">
  Full stack systems. Secure auth. Cloud native infra. Production AI agents.
  <br />
  I don't ship prototypes. I ship architecture that survives contact with reality.
</p>

<p align="center">
  <a href="https://abdullahmed.xyz">Portfolio</a> -
  <a href="https://github.com/abdull-ah-med">GitHub</a> -
  <a href="https://www.linkedin.com/in/abdull-ah-med/">LinkedIn</a> -
  <a href="https://ccript.com/">CCRIPT Agency</a>
</p>

---

### Who I Am

Software Engineer at **[CCRIPT Agency](https://ccript.com/)**. I design and ship end to end product systems: APIs, frontends, auth, workers, retrieval pipelines, and the deployment surface that keeps them alive.

Previously Associate Software Engineer at **[Devsinc](https://www.devsinc.com)** (JavaScript, React, Node.js, Express). Before that, Software Engineering Intern at **[DirectFN](https://www.directfn.com)**, contributing to financial systems used across Pakistan and the Gulf.

I operate at the layer where product, security, and applied ML collide. Clean Architecture backends. Hardened AuthN/AuthZ. Azure and cloud native delivery. LLM systems with RAG, vector search, and agent orchestration that are actually wired into production workflows.

---

### Stack I Actually Ship With

| Layer | Weapons |
|---|---|
| **Frontend** | React, Next.js, TypeScript, Tailwind CSS |
| **Backend** | FastAPI, Node.js, Express, ASP.NET Core (Clean Architecture), C#, Python |
| **Auth & Security** | JWT access + rotating refresh cookies, CSRF double submit, OAuth, Origin allowlisting, least privilege scopes |
| **Data** | PostgreSQL, pgvector, MongoDB, Redis (TLS, rate limits, session infra) |
| **AI / Agents** | Claude / Anthropic, RAG, hybrid retrieval, vector search, agent tooling, feedback / learning loops |
| **Integrations** | Microsoft Graph, Entra ID / MSAL, Slack |
| **Cloud & DevOps** | Azure, AWS EC2, Docker Compose, nginx + TLS, GitHub Actions, CI/CD |

---

### Selected Work

**Inbox Triage Automation Agent**  
Production read only AI triage agent for shared Outlook mailboxes.

- Microsoft Graph ingest via change notifications + poll fallback
- Rules + Claude classification, draft generation, multi mailbox review dashboard
- FastAPI workers, PostgreSQL + pgvector retrieval, Redis, Next.js dashboard
- Memory only access JWTs, HttpOnly refresh cookies, CSRF on cookie mutating routes
- Hardened prod posture: TLS Redis, locked down secrets validation, nginx reverse proxy, Dockerized deploy

Human in the loop by design. `Mail.Read` only. The agent never sends mail.

Repo: [Inbox Automation Agent](https://github.com/abdull-ah-med/inbox_automation_agent)

**OneUni**  
Scalable university platform on Clean Architecture.

- ASP.NET Core backend with custom Google OAuth
- Next.js frontend
- Full Azure deployment path

Repo: [OneUniBackend](https://github.com/abdull-ah-med/OneUniBackend)

**Formai**  
Natural language → structured forms. Prompt in. Production form out.

- Live: [formai-frontend-one.vercel.app](https://formai-frontend-one.vercel.app)
- Repo: [Formai Monorepo](https://github.com/abdull-ah-med/Formai)

---

### Operating Principles

- Prefer systems over screenshots
- Security is part of the product, not a checkbox after launch
- AI without retrieval, eval, and audit trails is just vibes
- Clean Architecture when the domain deserves it. Not cargo cult.
- Ship the boring infrastructure that makes the flashy parts reliable

---

### Currently Leveling Up

- Design patterns that earn complexity in AI systems (Façade, Chain of Responsibility, composition heavy agent graphs)
- Cloud native Azure deployment patterns that scale past "it works on my box"
- Production RAG and agent loops with feedback that compounds over time

---
### Find Me

- Portfolio: [abdullahmed.xyz](https://abdullahmed.xyz)
- GitHub: [@abdull-ah-med](https://github.com/abdull-ah-med)
- LinkedIn: [Abdullah Ahmed](https://www.linkedin.com/in/abdull-ah-med/)
- Blogs: [For when I do write](https://www.abdullahmed.xyz/blog)

---

<p align="center">
  <em>Always learning. Always building. Always engineernig the right things.</em>
</p>
