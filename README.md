# Mehmet Mutlu

**Full-Stack Software Engineer · Computer Engineering (FSMVU, 2026) · Istanbul**

I build web and mobile products end to end: backend, APIs, clients, store releases and CI/CD.
I use Claude Code every day inside a structured process: persistent project memory, my own commands and skills, and sprints run by parallel sub-agents.
Architecture, data and security decisions stay with me. Agent output is merged only after tests and review.

[LinkedIn](https://www.linkedin.com/in/mehmetmutllu/) · [Engineering case studies](https://github.com/mehmetmutllu/engineering-case-studies)

---

## Live in the store

**[Kelime Ezberle İngilizce](https://apps.apple.com/tr/app/id6811626340)** is an English vocabulary app for Turkish speakers. I built it solo and shipped 8 App Store releases (1.0 → 1.4.0) in its first month. Google Play is in closed testing.
Vanilla JS SPA · Capacitor 8 · PHP API · Firebase Auth + cloud backup · RevenueCat subscriptions · AdMob · Cloudflare Workers · 26 automated test suites (~1,500 checks) + native Android E2E.
[Case study](https://github.com/mehmetmutllu/engineering-case-studies/blob/main/case-studies/kelime-ezberle.md)

## Production work (private source)

- **BizSiz / Koçluk Sistemi** ([bizsizsoft.com](https://bizsizsoft.com)): an ed-tech startup I co-founded and built the software for. It is a multi-tenant education and coaching platform with institution, teacher, coach, student and parent panels. It has tenant-level data isolation, 100+ migrations and 18 GitHub Actions workflows (static analysis, migration lint, daily schema-drift check, schema-gated production deploy with automatic rollback, anonymised staging refresh). A white-label Flutter app (Biledem Koçluk) is on the App Store.
- **SEY Silver** ([seysilver.com](https://seysilver.com)): jewellery e-commerce with a PayTR iFrame payment integration (going live), variants, stock and a returns flow. 180 Playwright E2E tests run across 8 viewports plus Firefox and WebKit.
- **İKRA Vakfı** ([ikravakfi.org](https://ikravakfi.org)), **Pes Toptan** ([pestoptan.com.tr](https://pestoptan.com.tr)) and **Biledem** ([biledem.com](https://biledem.com)): production sites and admin panels (PHP 8 · MariaDB).

## Selected public repositories

| Repository | What it is |
|---|---|
| [claude-code-engineering-skills](https://github.com/mehmetmutllu/claude-code-engineering-skills) | How I work with AI: playbooks from real projects (sprint orchestration, blind second review, LLM evaluation, CI gates), session-memory commands, skills, hooks and tools |
| [engineering-case-studies](https://github.com/mehmetmutllu/engineering-case-studies) | Architecture write-ups: Kelime Ezberle, an LLM game master evaluation, BizSiz, SEY Silver and more |
| [tea-house-tycoon-game](https://github.com/mehmetmutllu/tea-house-tycoon-game) | Tea House Tycoon, a 3D idle-tycoon mobile game (Google Play closed testing). TypeScript · React 19 · React Three Fiber · Capacitor · Vitest |
| [watchsync-ai](https://github.com/mehmetmutllu/watchsync-ai) | Multi-channel inventory and listing platform, built by a two-person team. Laravel 11 · Next.js · FastAPI |
| [soru-dunyasi](https://github.com/mehmetmutllu/soru-dunyasi) | Gamified exam-prep platform. PHP · MySQL |

## How I work with AI

- **Session memory protocol.** A rule table in `CLAUDE.md`, a line-capped state file that keeps the last 3 sessions and archives older ones, decision registers, and resume/finish commands. I use it in more than 10 projects, synced between two machines.
- **Sprints with sub-agents.** Plan → design approval on a live preview → up to 3 parallel agents with written briefs → I merge → full test run → a changelog of every user-visible change.
- **Measure, don't trust.** AI-generated content gets a blind second review with an error threshold. LLM features get measured: 3 models over 55 scenarios (495 LLM-judged turns) before choosing a game-master model. See the [LLM evaluation case study](https://github.com/mehmetmutllu/engineering-case-studies/blob/main/case-studies/ai-dungeon-llm-game-master.md).

**Stack:** PHP 8 · Laravel · TypeScript · React / Next.js · Python / FastAPI · Flutter · Capacitor · Unity / C# · MySQL / MariaDB · Firebase · Cloudflare Workers · Playwright · Vitest · PHPUnit · pytest · GitHub Actions · Docker
