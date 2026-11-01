# Awesome-Personal-Productivity-Board-Enhancement

# Top Personal Productivity & Board Enhancement Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Task Management, Kanban Boards & Self-Hosted Personal Productivity*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Personal Productivity & Board Enhancement**. These tools enable individuals and small teams to organize tasks, visualize workflows on boards, build habits, and manage their day—turning scattered to-dos into a coherent personal system.

**Examples** include Trello Gold, Notion, Todoist, TickTick, Any.do, Things 3, Microsoft To Do, Omnifocus, Habitica, and Sunsama (the category leaders).

**Open-source emphasis**: Personal Productivity is a domain where open-source tooling is **genuinely abundant but fragmented across philosophies**—from Trello-style boards to local-first personal operating systems. The strongest active projects are **Kan-ductor** (an AGPLv3-licensed Trello alternative with Trello imports and Docker deployment) , **Werkyn** (a Notion-like project management platform with Kanban boards, wiki, and real-time collaboration, though it is a development preview) , and **NeumanOS** (a privacy-first, local-only personal OS combining notes, tasks, habit tracking, and calendar in a single browser-based application) . For Trello-in-Obsidian workflows, **Kanux** provides Markdown-backed kanban boards with card templates and dependency tracking . The critical caveat: **no open-source project matches the polish and mobile ecosystem** of Things 3 or TickTick—open-source tools excel at self-hosting and data ownership but require you to accept web-first interfaces and occasional development-preview instability .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Trello Gold](https://trello.com/)**  
  Premium tier of Trello's kanban board platform; adds custom backgrounds, stickers, larger attachments, and advanced Power-Ups for personal productivity enhancement.

- **[Notion](https://www.notion.com/)**  
  All-in-one workspace combining wikis, docs, databases, and project management with flexible block-based pages and template ecosystem.

- **[Todoist](https://todoist.com/)**  
  Task management platform known for natural language input and cross-platform sync; focused on personal task capture and project organization.

- **[TickTick](https://ticktick.com/)**  
  Task management with built-in Pomodoro timer, habit tracking, and calendar view; positioned as an all-in-one personal productivity app.

- **[Any.do](https://www.any.do/)**  
  Simple task management with daily planner and calendar integration; focused on personal organization.

- **[Things 3](https://culturedcode.com/things/)**  
  Apple-exclusive task manager known for its polished design and thoughtful workflow; focused on individual productivity rather than team collaboration.

- **[Microsoft To Do](https://to-do.office.com/)**  
  Task management integrated with Microsoft 365; syncs with Outlook tasks and supports shared lists.

- **[Omnifocus](https://www.omnigroup.com/omnifocus/)**  
  Power-user task management for Apple platforms; built on GTD (Getting Things Done) methodology with perspectives, defer dates, and review workflows.

- **[Habitica](https://habitica.com/)**  
  Gamified habit tracker and task manager; turns personal goals into an RPG where completing tasks earns XP and gold.

- **[Sunsama](https://www.sunsama.com/)**  
  Daily planning tool that combines calendar, tasks, and time-blocking into a focused daily workflow; inspired by the "daily shutdown" ritual.

## Open-Source GitHub Projects

### Trello-Style Kanban Boards

- **[Kan-ductor](https://github.com/pdurlej/kan)**  
  Open-source **Trello alternative** (AGPLv3) with board visibility controls, workspace members, **Trello imports**, labels, filters, comments, and activity log . Features reusable board templates and self-hosting via Docker Compose or Railway one-click deployment . **Best for individuals and small teams** wanting a focused Trello-style board with data ownership—but it is board-focused rather than a full personal productivity suite.

- **[Atlantisboard](https://github.com/walster001/atlantisboard)**  
  Self-hosted **Kanban-style board** (Bun/React/MongoDB) with workspaces, lists, cards, permissions, invites, **Trello-style JSON import**, and live collaboration via WebSocket . Features rich cards with descriptions, assignees, labels, dates, checklists, comments, attachments, and reminders . **Licensing caveat**: "Proprietary — All Rights Reserved" despite being publicly available on GitHub—verify terms before adoption . **Best for teams wanting a Trello-like board with real-time collaboration**—but the proprietary license is a significant consideration.

- **[RestyaBoard](https://github.com/pointprevalence/restyaboard)**  
  Open-source **Trello-like kanban board** based on the Restya platform (dual OSL 3.0 & Commercial License) . Features boards for task organization, chat, email-to-card integration, and plugin support . Active development with Docker deployment . **Best for users wanting a mature Trello alternative**—but the dual licensing may require review for commercial use.

### Personal Operating Systems (All-in-One)

- **[NeumanOS](https://github.com/travisjneuman/neumanos)**  
  The most comprehensive open-source **personal productivity OS** (React 19/TypeScript/IndexedDB) . Features: **Kanban boards** with drag-and-drop, dependencies, subtasks, and Gantt view; **notes** with wiki-style links and graph view; **habit tracking** with streaks and heatmaps; **time tracking** with invoice generation; **calendar** with two-way ICS sync; **Pomodoro timer**; **AI terminal** (bring your own API keys for 9 providers); **office suite** with documents, spreadsheets (390+ formulas), and presentations; and **60+ dashboard widgets** . **All data stored locally in IndexedDB**—no account, no server, no data leaving your device . **Best for privacy-focused individuals** wanting an all-in-one personal system—but it is browser-only and requires you to manage your own backups.

- **[Werkyn](https://github.com/rackstead/werkyn)**  
  Open-source **project management and collaboration platform** (React 19/TanStack Router/PostgreSQL) . Features: **Kanban boards**, list view, calendar view, task properties (priorities, assignees, dependencies, subtasks), **Notion-like wiki editor** (BlockNote), team files, multi-workspace support, command palette, and real-time WebSocket updates . **Critical caveat**: it is a **development preview**—the README explicitly warns "Do not use in production" and "There may be security flaws in the current state" . **Best for developers** wanting to explore a Notion-like open-source platform—but not ready for personal daily use without accepting instability.

- **[Jotter](https://pypi.org/project/jotter-app/3.10.4/)**  
  Open-source **local-first task manager** modeled as a Markdown Kanban board (Python/React) . Features: tasks stored as **human-readable Markdown files** (OKF format) with SQLite index for speed; **Kanban, list, Eisenhower Matrix, and time views**; selective per-project **Git sync**; **Git-backed time machine** for rollback; **MCP support** for AI assistants; Excel/CSV import/export; **Obsidian compatibility** (project directories include `index.md`) . **Android app available** with offline sync via Syncthing/Git . **Best for privacy-focused users** wanting Markdown-based tasks with Git sync—the local-first architecture is a standout for data ownership.

### Habit Tracking & Gamification

- **HabitForge** — Open-source **gamified habit tracker** (React/Node.js/MongoDB) with **AI coaching**, forgiveness tokens (for missed days), and community features . Built with Amazon Kiro's AI-assisted development workflow . **Best for users wanting a Habitica alternative** with AI coaching—but it is a newer project (November 2025) and requires MongoDB infrastructure .

### Additional Strong Open-Source Options

- **Kanux** — Open-source **Trello-style board for Obsidian** (Markdown-backed cards) with checklists, labels, table view, drag-and-drop organization, and per-board appearance settings . Supports card templates with incremental codes (e.g., `BUG-001`) and dependencies . **Best for Obsidian users** wanting kanban boards inside their vault—not a standalone productivity platform, but excellent for PKM workflows .
- **Seeder** — Open-source **personal project manager** (Cloudflare Workers/Next.js) with Kanban tasks, client request queues, public client boards, and a **built-in MCP server** for AI assistants . White-labeling and role-based access included . **Best for freelancers and small teams** wanting a lightweight project manager with client-facing views—but it requires Cloudflare Workers or a Node VM .

**Frameworks for building custom systems**: For a **focused Trello-style board with self-hosting**, Kan-ductor provides the cleanest AGPLv3 option with Trello imports . For an **all-in-one local-first personal OS**, NeumanOS combines notes, tasks, habits, calendar, and time tracking in one browser-based application . For **Markdown-based tasks with Git sync**, Jotter provides local-first ownership with an Android app . For **Obsidian users**, Kanux integrates boards directly into the vault . **Avoid Atlantisboard's proprietary license** unless terms are acceptable . **Werkyn is not production-ready**—it is a development preview with security warnings .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Personal productivity platforms handling task and habit data must comply with applicable privacy regulations (GDPR, CCPA) and data governance policies; **local-first tools like NeumanOS and Jotter place full responsibility for backups on the user**—no cloud sync means no recovery if the device fails.
- **Open-source personal productivity is abundant but differentiated by philosophy**—Kan-ductor provides a clean Trello alternative , NeumanOS provides an all-in-one local-first OS , and Jotter provides Markdown-based tasks with Git sync . However, **no open-source project matches the polish and mobile ecosystem** of Things 3 or TickTick. **Atlantisboard's proprietary license** and **Werkyn's development-preview status** are significant caveats. Choose based on whether you prioritize board simplicity (Kan-ductor), all-in-one integration (NeumanOS), or data ownership via Markdown (Jotter).
- Verify license terms for commercial use; Kan-ductor uses AGPLv3 , NeumanOS is open-source (check repository), Jotter is open-source (check repository), and Atlantisboard is proprietary .

---

**Made for individuals, small teams, and anyone building their personal productivity stack.**  
Let's make personal productivity more open, but with clear eyes about the polish and mobile ecosystem gaps that commercial apps still fill.
