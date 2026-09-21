<p align="center">
  <img src="./assets/profile-banner.svg" alt="@kunshanyep-beep — open-source engineering" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/deepcoldy/botmux"><img src="https://img.shields.io/badge/Open%20Source-botmux-58A6FF?style=flat-square&logo=github&logoColor=white" alt="Open-source contributor to botmux" /></a>
  <img src="https://img.shields.io/badge/Focus-Developer%20Tooling-8B5CF6?style=flat-square" alt="Focus: developer tooling" />
  <img src="https://img.shields.io/badge/Engineering-Evidence%20Driven-22C55E?style=flat-square" alt="Evidence-driven engineering" />
</p>

## About me

I am an open-source contributor focused on reliable developer tools, terminal workflows, and performance-sensitive systems.

- I turn reproducible problems into focused patches, regression tests, and measurable results.
- I contribute to [deepcoldy/botmux](https://github.com/deepcoldy/botmux), improving terminal input, Lark interactions, dashboard ergonomics, and CI reliability.
- I care about deterministic tests, narrow interfaces, safe fallbacks, and performance evidence.

## Open-source impact

Contributions to [botmux](https://github.com/deepcoldy/botmux): **4 merged PRs · 4 open PRs**. Status verified on September 21, 2026.

| Status | Contribution | Engineering result |
| :---: | --- | --- |
| **Merged** | [botmux #1419 — fail closed without requester identity](https://github.com/deepcoldy/botmux/pull/1419) | Prevented requester-only feedback on cards with no stored requester identity; added a regression test that checks no feedback revision is written. All CI checks passed. |
| **Merged** | [botmux #1312 — add paste protocol support to bare PTY input](https://github.com/deepcoldy/botmux/pull/1312) | Added bracketed-paste handling for long or multiline OpenCode V2 messages on raw PTY while preserving typing behavior for slash commands and short single-line input. |
| **Merged** | [botmux #1314 — optimize TraeX session-recovery lookup](https://github.com/deepcoldy/botmux/pull/1314) | Replaced full-tree recursion with a SQLite-indexed fast path, depth-bounded date traversal, and bounded miss backoff. In a deterministic 200-sidecar fallback fixture, stat calls fell from 204 to 0 with at most 4 directory reads. |
| **Merged** | [botmux #1293 — eliminate a history-ownership test timing race](https://github.com/deepcoldy/botmux/pull/1293) | Replaced fixed-delay test orchestration with an Enter-event happens-before boundary, preserving ownership filtering and retry coverage. |
| **Open · awaiting review** | [botmux #1498 — remove a statusline watchdog CI timing flake](https://github.com/deepcoldy/botmux/pull/1498) | Separated a real watchdog failure from CI scheduling overhead, raised the test-only outer bound from 12s to 15s without changing the production 10s watchdog or 1s kill grace, and verified the boundary under 12-way parallel load. All CI checks passed. |
| **Open · awaiting review** | [botmux #1496 — restore scrolling in the add-bot model picker](https://github.com/deepcoldy/botmux/pull/1496) | Scoped the fix to one onboarding dropdown CSS override so wheel gestures can chain back to the outer form when the model list has no scroll range. Reproduced with Playwright. |
| **Open · awaiting review** | [botmux #1418 — reject stale feedback card callbacks](https://github.com/deepcoldy/botmux/pull/1418) | Added card version checks inside the SQLite write transaction so delayed callbacks cannot restore an older feedback choice or repaint the card. |
| **Open · awaiting review** | [botmux #1417 — serialize live card toggle updates](https://github.com/deepcoldy/botmux/pull/1417) | Routed live-card toggle updates through the existing patch queue to prevent an older in-flight update from restoring stale display state. |

## Toolbox

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white" alt="Bun" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" alt="Vitest" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

## GitHub activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kunshanyep-beep/kunshanyep-beep/main/profile-summary-card-output/github_dark/0-profile-details.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kunshanyep-beep/kunshanyep-beep/main/profile-summary-card-output/github/0-profile-details.svg" />
  <img src="https://raw.githubusercontent.com/kunshanyep-beep/kunshanyep-beep/main/profile-summary-card-output/github/0-profile-details.svg" alt="GitHub profile details" width="100%" />
</picture>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kunshanyep-beep/kunshanyep-beep/main/profile-summary-card-output/github_dark/3-stats.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kunshanyep-beep/kunshanyep-beep/main/profile-summary-card-output/github/3-stats.svg" />
    <img src="https://raw.githubusercontent.com/kunshanyep-beep/kunshanyep-beep/main/profile-summary-card-output/github/3-stats.svg" alt="GitHub statistics" width="49%" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kunshanyep-beep/kunshanyep-beep/main/profile-summary-card-output/github_dark/2-most-commit-language.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kunshanyep-beep/kunshanyep-beep/main/profile-summary-card-output/github/2-most-commit-language.svg" />
    <img src="https://raw.githubusercontent.com/kunshanyep-beep/kunshanyep-beep/main/profile-summary-card-output/github/2-most-commit-language.svg" alt="Languages used in commits" width="49%" />
  </picture>
</p>

## Contribution trail

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kunshanyep-beep/kunshanyep-beep/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kunshanyep-beep/kunshanyep-beep/output/github-contribution-grid-snake.svg" />
  <img src="https://raw.githubusercontent.com/kunshanyep-beep/kunshanyep-beep/output/github-contribution-grid-snake.svg" alt="Contribution graph snake animation" width="100%" />
</picture>

<p align="center">
  <sub>Profile statistics and contribution artwork refresh automatically every day.</sub>
</p>
