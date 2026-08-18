Hi, I'm Andrew 👋
QA Engineer with three years at Apple, returning to tech after a career break. Currently deepening my test automation skills while also building full-stack projects — open to QA/SDET or junior Software Engineer roles.

### 🍽️ [Table](https://github.com/AndrewDoan/food-app) — live at [food-app-two-sable.vercel.app](https://food-app-two-sable.vercel.app/)

A private, invite-only app for sharing recipes and restaurant reviews within your actual circle of friends — no public profiles, no discoverability, no ads, no strangers.

The core technical bet: friends-only access is enforced at the **database layer** via Postgres Row-Level Security, not just filtered in the app — so even a compromised frontend can't leak data outside your friend graph. Built solo end-to-end:

* **Full-stack:** Next.js (App Router, TypeScript) + Supabase (Postgres, magic-link auth, private Storage)
* **Third-party integrations:** Google Places, Geocoding, and Maps JavaScript APIs for location-aware restaurant search, radius filtering, and a live map with grouped results
* **Real features, not a CRUD demo:** multi-photo uploads with reordering, QR-code friend invites (generate + in-browser camera scan), tag-based search with frequency-sorted suggestions, and a permission model that's been pressure-tested against real edge cases
* **Documented engineering process:** [`ARCHITECTURE.md`](https://github.com/AndrewDoan/food-app/blob/main/ARCHITECTURE.md) is a running log of real bugs hit and root-caused along the way — including an RLS policy that silently hid pending friend requests, and a dev-vs-production build divergence only caught during deployment

Currently working on:

* Building Playwright skills for end-to-end web automation
* Refreshing JavaScript/TypeScript fundamentals through full-stack projects
* Open to remote QA / SDET or junior Software Engineer roles

Tech I work with:

* Languages: JavaScript, TypeScript, Node.js
* Web/Full-stack: Next.js, React, Supabase, PostgreSQL
* Testing: Mocha, Playwright (learning), Jira, Apple Radar
* Tools: Xcode, Charles Proxy, Git
* Background: Manual + automated testing, regression, localization, mobile (iOS) + web

Reach me:

* 📧 [addoan11@gmail.com](mailto:addoan11@gmail.com)
* 💼 [LinkedIn](https://linkedin.com/in/addoan)
