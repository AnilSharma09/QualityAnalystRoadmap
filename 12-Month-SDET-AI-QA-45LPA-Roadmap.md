# 12-Month Roadmap: SDET / AI-QA Engineer Targeting ₹45 LPA

**Reality check first:** ₹45 LPA in 12 months is achievable but only at the aggressive end — it needs strong automation skills, solid DSA (yes, DSA — most people don't expect this for QA, but ₹40+ LPA SDET roles at product/FANG-tier companies now test it), real project depth, and strong interview performance. This isn't a "watch tutorials" plan — it's a "build things, break things, document things" plan. Since manual testing foundation already exists, we compress that and go deep on automation + DSA + AI-testing, which is what actually moves comp.

---

## Month 1 — Fill Gaps + SQL Mastery + Git/Linux Fluency

**4–5 hrs/day**

- **Manual testing:** quick revision only (STLC, bug lifecycle, test design techniques — 3–4 days max, not a full month)
- **SQL:** deep dive — JOINs, subqueries, window functions, CTEs. Target: 100 solved problems (LeetCode SQL + HackerRank)
- **Git:** branching strategies, PR workflow, rebase, conflict resolution — real repo practice, not just theory
- **Linux:** comfortable daily driver in terminal

**Milestone:** 100 SQL problems solved + documented on GitHub. 30+ well-written test cases for a real app.

---

## Month 2 — Python + API Testing (Deep)

**5 hrs/day**

- **Python:** OOP, data structures, file handling, decorators, generators, error handling — solid intermediate level, not just basics
- **API Testing:** Postman advanced (chained requests, dynamic variables, pre-request scripts), REST deep dive, auth flows (OAuth2, JWT), Newman CLI + CI integration

**Milestone:** Postman collection (40+ requests) with full auth flow testing, converted to a Newman-run CI pipeline.

---

## Month 3 — DSA Foundations (Non-negotiable for 40+ LPA)

**5–6 hrs/day — this month is DSA-only alongside light API automation practice**

- Arrays, strings, hashing, two pointers, sliding window
- Basic recursion, basic trees
- Time/space complexity intuition
- Platform: LeetCode Easy → Medium (target 80–100 problems by month end)

**Why this matters:** SDET-2/3 roles at Amazon, Google, Meta, and top product companies (Razorpay, Atlassian, etc.) now run a full DSA round alongside testing rounds. Skipping this caps you around ₹15–20 LPA regardless of how good your automation skills are.

**Milestone:** 80–100 DSA problems solved, documented pattern notes on GitHub.

---

## Month 4 — UI Automation Framework (Playwright + Pytest)

**5–6 hrs/day**

- Playwright with Python, Page Object Model
- Pytest fixtures, parametrization, markers, reporting (Allure or pytest-html)
- Data-driven framework design
- Continue DSA at 3–4 problems/day to maintain momentum

**Milestone:** A production-grade UI automation framework — POM architecture, 25+ tests, HTML/Allure reporting, README explaining design decisions (interviewers care a lot about *why* you structured it that way).

---

## Month 5 — API Automation Framework + CI/CD

**5–6 hrs/day**

- Python `requests` + Pytest API framework: modular, reusable, config-driven
- GitHub Actions: run UI + API suites on every push, parallel test execution
- Docker basics: containerize your test environment
- DSA: 3–4/day continuing

**Milestone:** Combined framework (UI + API) triggered automatically via GitHub Actions on every commit, with pass/fail badges and test reports published. This single repo becomes your strongest resume artifact.

---

## Month 6 — Cloud Basics + Performance Testing

**5 hrs/day**

- AWS fundamentals: EC2, S3, basic IAM — enough to speak intelligently in interviews and run tests in cloud environments
- k6 or JMeter: load testing, throughput, response time, stress testing basics
- DSA: continue, shift toward medium-level trees/graphs

**Milestone:** A performance test suite (k6) for one of your existing projects, with a results writeup (bottlenecks found, recommendations).

---

## Month 7 — AI/GenAI Testing (Your Biggest Differentiator)

**6 hrs/day**

- LLM output testing: consistency, hallucination detection patterns, prompt robustness
- RAG system testing: retrieval accuracy, grounding verification
- Evaluation metrics: building eval sets, precision/recall thinking applied to model outputs
- AI agent testing: testing tool-calling agents for correctness, failure recovery
- Given your AI/Data Science background, this is where you go from "another QA candidate" to "the QA candidate who actually understands AI systems"

**Milestone:** A real eval harness for an LLM-powered feature — test it against a set of adversarial prompts, measure hallucination/failure rate, document findings like a proper case study. This project alone can be an interview centerpiece.

---

## Month 8 — Advanced DSA + System Design Basics for QA

**6 hrs/day**

- DSA: push into medium/hard — graphs, DP basics, more trees (target cumulative 200+ problems)
- **Testing-focused system design:** how would you design a test strategy for a distributed system? How do you test rate limiters, caching layers, queues? This is what separates ₹20 LPA SDET from ₹45 LPA SDET interviews.

**Milestone:** 200+ cumulative DSA problems. Can whiteboard a test strategy for a real distributed system scenario.

---

## Month 9 — Contract/Mock Testing + Advanced CI/CD

**5–6 hrs/day**

- Contract testing basics (Pact or similar concepts)
- Advanced CI/CD: multi-stage pipelines, test environment management, flaky test handling strategies
- Mocking/stubbing external dependencies in tests
- DSA: maintain 3–4/day

**Milestone:** Update your API framework with contract testing + proper mocking strategy documented.

---

## Month 10 — Portfolio Consolidation + Resume + LinkedIn

**5 hrs/day**

- Clean up all repos: manual test cases, UI automation, API automation+CI/CD, performance testing, AI-testing harness
- Every repo needs a strong README (problem → approach → what you learned)
- Resume: tailored specifically for "SDET / AI-Aware Quality Engineer," quantify everything (e.g., "reduced regression cycle by X%," "built framework covering Y test cases")
- LinkedIn: consistent story matching resume, start posting about your projects (visibility matters for recruiter inbound)
- DSA: maintain, start timed practice

**Milestone:** Application-ready profile. Start applying.

---

## Month 11 — Interview Prep Intensive

**6+ hrs/day**

- DSA: timed mock interviews, mix of easy/medium
- System design for testing: more scenario practice
- Behavioral: STAR-format stories from your real projects
- Mock interviews (peer or platforms like Pramp/Interviewing.io)
- Company-specific prep for wherever you're applying (Amazon SDET, Atlassian, Razorpay, Meta, etc. — each has a different flavor)

**Milestone:** 5+ mock interviews done, comfortable under pressure.

---

## Month 12 — Active Interviewing + Negotiation

- Apply broadly: FANG SDET-2/3 roles, strong product companies (Razorpay, CRED, Atlassian, Zeta, etc. all pay well for this profile)
- Referrals matter a lot here — use your GitHub/LinkedIn presence to get warm intros
- When offers come: know the market rate for the level, don't anchor low, be ready to negotiate with data (Glassdoor, Levels.fyi equivalents for India)

---

## Where ₹45 LPA Actually Comes From

| Profile | Realistic Comp |
|---|---|
| SDET with just automation (no DSA) | ₹15–25 LPA |
| SDET with automation + solid DSA + system design thinking | ₹30–45 LPA |
| Above + strong AI-testing niche + FANG/top-tier offer | ₹45–65 LPA |

The ₹45 LPA outcome depends on **three things stacking together**: strong automation portfolio, real DSA competence (not just familiarity), and interview performance under pressure. Skipping DSA is the single most common reason strong QA engineers cap out around ₹18–20 LPA — don't skip Month 3 and the ongoing DSA practice.

---

## Weekly Rhythm (Applies Throughout)

- **Weekdays:** deep work on current month's focus (4–6 hrs)
- **1 day/week:** DSA-only day
- **1 day/week:** review + document what you built (README updates, LinkedIn post, notes)
- **Every month-end:** ship something visible on GitHub — momentum and proof of work matter as much as the learning itself
