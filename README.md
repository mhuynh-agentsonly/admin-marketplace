# Admin Marketplace prototypes

Clickable prototypes for the admin side of Marketplace. Every page runs in the browser and has a **Prototype** button (bottom-right) for jumping between screens and states.

## Pages

| Page | What it shows | Link |
| --- | --- | --- |
| Skills Center admin (v2) | The current admin prototype: Test Library (Typeform and simulation tests), Add Skills Test, AI Assistant Library, inviting agents, Talent Pool results and the AI Interview tab | https://mhuynh-agentsonly.github.io/admin-marketplace/skills-center-admin-v2.html |
| Skills Center admin (v1) | The earlier version | https://mhuynh-agentsonly.github.io/admin-marketplace/skills-center-admin-v1.html |
| Admin demo (v2) | The Add Skills Test demo flow | https://mhuynh-agentsonly.github.io/admin-marketplace/admin-demo-v2.html |

## AI Interview tab

Open it from the top nav, or go straight to https://mhuynh-agentsonly.github.io/admin-marketplace/skills-center-admin-v2.html#ai-interviews. It shows agents' Hallo AI interview results:

- **List:** the same columns as Hallo's dashboard: user, language, date and duration, sent by, status with the integrity flag, and Score I / II / III. Filters for date, status, hire status, language and CEFR level. Agents still taking the test show as "Test in progress".
- **Detail:** scores with Pass / Below threshold, answers, anti-cheating signals and system diagnostics. Admins approve or reject, and can override Hallo's AI recommendation with a reason. Every decision can be undone and syncs back to Hallo (our assumption until the PO confirms).

The agent side of these flows lives in [agent-marketplace](https://github.com/mhuynh-agentsonly/agent-marketplace).

## Files

- `Admins/` and `videos/` — images and clips used by the prototypes.
