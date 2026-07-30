# 6-Month Zero-to-Job-Ready Roadmap: AI-Powered QA / SDET

**Honest framing:** This roadmap gets a complete beginner to *job-ready* for QA/SDET roles (₹6–18 LPA range, higher with strong interviews) in 6 months. It does **not** get you a FANG offer at ₹1 Cr+ in 6 months — nobody goes zero-to-that in half a year. What it does is build the exact foundation FANG-track engineers build in year 1, so you can realistically be FANG/high-comp competitive in 18–36 months if you keep compounding.

---

## Month 1 — Foundations (Manual Testing + SQL + Git + Linux)

**Daily: 4–5 hours**

- **Manual Testing:** SDLC, STLC, Bug Life Cycle, test case writing, test scenarios, exploratory/smoke/regression/sanity testing, UAT, risk-based testing
- **SQL:** SELECT → WHERE → GROUP BY → HAVING → ORDER BY → JOINs → Subqueries → Window Functions → CTEs. Target: 100 solved queries (LeetCode SQL, HackerRank SQL)
- **Git:** clone, commit, branch, merge, PR workflow, rebase, resolving conflicts
- **Linux:** cd, ls, pwd, cat, grep, chmod, ps, kill — enough to be comfortable in a terminal daily

**Milestone:** Write 30+ real test cases for a public app (e.g., an open-source e-commerce demo site). Push to GitHub.

---

## Month 2 — API Testing + Python Fundamentals

**Daily: 4–5 hours**

- **API Testing:** Postman, REST principles, HTTP methods, status codes, JSON, auth (API keys, OAuth basics), collections, environment variables, assertions, Newman CLI
- **Python:** syntax, data structures, functions, OOP basics, file handling, virtual envs, pip

**Milestone:** Full Postman collection (30+ requests) testing a public API (e.g., ReqRes, JSONPlaceholder), with automated assertions and a Newman CI run documented on GitHub.

---

## Month 3 — Automation Testing (Python + Playwright/Selenium)

**Daily: 5–6 hours**

- **Pytest:** fixtures, parametrization, markers, assertions, reporting
- **Playwright (preferred over Selenium for new learners — faster, more modern, in demand)**
- **Page Object Model**
- **Data-driven testing framework**

**Milestone:** Build a Playwright + Pytest UI automation framework (POM structure) for a real website, with 20+ automated test cases and an HTML report. Push to GitHub as a proper repo with README.

---

## Month 4 — API Automation + CI/CD

**Daily: 5–6 hours**

- **API Automation:** Python `requests` + Pytest, reusable API test framework
- **CI/CD:** GitHub Actions (simplest to start), running your automation suite on every push
- **Basic Docker:** containerizing a simple test environment

**Milestone:** A GitHub repo where pushing code auto-triggers your UI + API test suite via GitHub Actions, with a badge showing pass/fail status. This is a genuinely strong portfolio piece — most freshers don't have this.

---

## Month 5 — AI/GenAI Testing (Your Differentiator)

**Daily: 5–6 hours**

This is the highest-leverage phase for you specifically, given your AI/Data Science background — very few QA candidates can speak credibly here.

- **LLM/Prompt testing:** writing test suites for prompt reliability, edge cases, injection resistance
- **RAG testing:** retrieval accuracy, grounding checks
- **Hallucination & bias testing basics:** how to structure eval sets
- **Evaluation metrics:** precision/recall for classification-style evals, human-in-the-loop review patterns
- **AI agent testing:** testing multi-step tool-calling agents for correctness and failure modes

**Milestone:** Build one small but real project — e.g., a test harness that evaluates an LLM-powered feature (even a toy one using a free/low-cost API) for hallucination rate, prompt robustness, and output consistency. Write it up like a case study.

---

## Month 6 — Performance Testing + Portfolio + Interview Prep

**Daily: 6+ hours**

- **Performance testing:** JMeter or k6 basics — load testing, response time, throughput
- **Portfolio consolidation:** clean up all 4 repos (manual test cases, UI automation, API automation + CI/CD, AI testing harness), write strong READMEs
- **Resume + LinkedIn:** tailored specifically to "AI-Aware QA Engineer / SDET"
- **Interview prep:** SQL problems, Python problems (easy-medium DSA — QA interviews at good companies do ask basic DSA now), mock interviews on testing scenarios, STAR-format behavioral answers

**Milestone:** 3–5 solid GitHub repos, a tailored resume, and you're applying/interviewing.

---

## Realistic Salary Expectations by Stage

| Stage | Timeframe | Skills | Realistic Comp (India) |
|---|---|---|---|
| Fresher QA (manual) | Month 6 | Manual + basic API | ₹3–6 LPA |
| QA + API + Automation | Month 6–12 | Full stack above | ₹6–15 LPA |
| SDET | Year 1–2 | + CI/CD, strong automation | ₹12–25 LPA |
| Senior SDET / AI QA | Year 2–4 | + Cloud, GenAI testing depth, real production experience | ₹25–45 LPA |
| Staff/Principal (FANG-tier) | Year 5+ | Deep expertise, leadership, high-signal interview performance | ₹60 LPA–1 Cr+ |

The jump to ₹1 Cr+ is a **senior/staff-level outcome**, not an entry point. The 6-month plan above is what gets you *into the pipeline* — the compounding happens over years, not months.

---

## What To Do After Month 6

1. Get a job (even ₹6–10 LPA) that gives you **real production testing experience** — this matters more than credentials for the next jump.
2. Keep building AI-testing depth — this space is early and will only grow.
3. Target 18–24 months in: start interviewing at FANG/top product companies for SDET-2 roles once you have real experience + a strong GitHub history.
4. Staff-level comp is a 4–8 year game even for very strong engineers. Anyone promising faster than that isn't being straight with you.
