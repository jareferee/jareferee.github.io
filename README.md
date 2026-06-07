# JAReferee — The Platform

The marketing site for the JAReferee platform — a complete toolkit for the modern referee program.

**Live site:** https://jareferee.com
**Developed by:** JAReferee LLC
**Tagline:** Referees first.

---

## What this is

This repository hosts the source for **jareferee.com**, the public marketing site for the JAReferee platform. It is a single-page site introducing the JAReferee ecosystem — five purpose-built tools for state associations, tournaments, leagues, and ref coaches.

This repository is **not** the source for any of the JAReferee applications themselves. Those are tracked in separate repositories.

---

## The platform

JAReferee is the operating system for the modern referee program. Each tool stands on its own. Together they form the platform every state association, tournament, and league runs on.

| Tool | For | Status |
|---|---|---|
| **Reference Library** | Every referee, every game | Live |
| **Teams** | Leagues, clubs, and tournaments | Live |
| **Ref Coach** | The referee coach behind the whistle | Live |
| **Gameday Command Center** | The platform that ties it all together — assigning, live ops, ref coach feedback loop, payments coming soon | Flagship |
| **Academy** | Lead instructors, teachers, and ref coaches in the classroom | Live |

---

## Architecture

The application is a single-file HTML application with no server, no backend, and no build process.

- Vanilla HTML, CSS, and JavaScript — no frameworks
- Light and dark mode via `prefers-color-scheme`
- Barlow and Barlow Condensed via Google Fonts
- Hosted on GitHub Pages, served at jareferee.com via CNAME

This is a deliberate constraint, not a limitation. The marketing site loads fast, works on any device, and has zero deploy steps beyond a `git push`.

---

## Status

This site is under active development. The toolkit section is updated as new tools come online. Releases deploy automatically to GitHub Pages from the `main` branch.

---

## License & Use

This software is proprietary. See `LICENSE` and `NOTICE.md` for the full terms.

No rights to use, copy, modify, distribute, or derive from this software are granted by virtue of accessing this repository. Use is permitted only under a separate written license agreement from JAReferee LLC.

**Public visibility of source does not imply public license.**

To request a license, schedule a demo, or discuss tournament/league deployments, contact JAReferee LLC directly.

---

## Contact

- **Company:** JAReferee LLC (Colorado)
- **Website:** https://jareferee.com
- **Email:** licensing@jareferee.com
- **Principal:** Jeff Arthurholtz

---

© 2026 JAReferee LLC. All rights reserved.
