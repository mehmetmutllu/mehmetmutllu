# Mehmet Mutlu

**Full-Stack Software Engineer · Computer Engineering (FSMVU, 2026) · Istanbul**

I build web and mobile products end to end and run them in production: backend, APIs, clients, store releases, CI/CD.
I work with Claude Code inside a structured process: persistent project memory, my own skills and commands, sprints run by parallel sub-agents.
Agent output ships only after it passes automated tests and an independent review.

🌐 [mutlumehmet.com](https://mutlumehmet.com) · [LinkedIn](https://www.linkedin.com/in/mehmetmutllu/)

---

## Live in the stores

| App | What it is | Stack |
|---|---|---|
| [Kelime Ezberle İngilizce](https://apps.apple.com/tr/app/id6811626340) | English vocabulary app for Turkish speakers. Solo-built; 8 App Store releases in its first month (Google Play: closed testing) | Vanilla JS SPA · Capacitor 8 · PHP API · Firebase Auth · RevenueCat IAP · AdMob · Cloudflare Workers · ~1,500 Playwright checks |
| Biledem Koçluk | White-label mobile client of the BizSiz platform for an education institution | Flutter · PHP · MariaDB |

## Production work (private source)

- **BizSiz** ([bizsizsoft.com](https://bizsizsoft.com)): multi-tenant education and coaching platform with institution, teacher, coach, student and parent panels. Tenant-level data isolation, 120+ versioned migrations, 20 GitHub Actions workflows (static analysis, migration lint, daily schema-drift check, gated production deploy with automatic rollback, anonymised staging refresh).
- **SEY Silver** ([seysilver.com](https://seysilver.com)): e-commerce with iyzico 3D Secure and three shipping APIs. 180 Playwright E2E tests across 5 viewports and 3 browser engines run on every push.
- **İKRA Vakfı**, **Pes Toptan**, **Biledem**: production portals and catalogs (PHP 8 · MariaDB).

Write-ups: [engineering-case-studies](https://github.com/mehmetmutllu/engineering-case-studies)

## Selected public repositories

| Repository | What it is |
|---|---|
| [claude-code-engineering-skills](https://github.com/mehmetmutllu/claude-code-engineering-skills) | My Claude Code commands and skills: session memory protocol, quality gates, content pipelines |
| [kiraathane-tycoon](https://github.com/mehmetmutllu/kiraathane-tycoon) | 3D idle-tycoon mobile game. TypeScript · React 19 · React Three Fiber · Capacitor · 1,600+ Vitest tests |
| [watchsync-ai](https://github.com/mehmetmutllu/watchsync-ai) | Multi-channel inventory and listing platform. Laravel 11 · Next.js · FastAPI |
| [soru-dunyasi](https://github.com/mehmetmutllu/soru-dunyasi) | Gamified exam-prep platform. PHP · MySQL |
| [mehmetportfolio](https://github.com/mehmetmutllu/mehmetportfolio) | Portfolio site. Next.js · Supabase |

## How I work with AI

- **Session memory protocol.** A rule table in `CLAUDE.md`, a line-capped `activeContext.md` that keeps the last 3 sessions and archives older ones automatically, decision registers, and `/devam` / `/bitir` (resume / finish) commands. I use it across more than 10 projects, synced between two machines.
- **Sprints with sub-agents.** Plan → design approval on a live preview → up to 3 parallel agents with written briefs → I merge → full test run → a changelog of every user-visible change.
- **Verification over trust.** Generated content gets a blind second review with an error threshold. LLM features get measured: 495 blind-judged turns across 3 models before choosing a game-master model.

**Stack:** PHP 8 · Laravel · TypeScript · React / Next.js · Python / FastAPI · Flutter · Capacitor · Unity / C# · MySQL / MariaDB · PostgreSQL · Firebase · Cloudflare Workers · Playwright · Vitest · PHPUnit · GitHub Actions · Docker
