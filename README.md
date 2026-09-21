![preview](https://raw.githubusercontent.com/morrocanmohamed-art/query-forge/main/banner_f0ec9c.svg)
# 🧠 SQL Trainer Reforged — Your Personal Query Dojo

[![Download](https://raw.githubusercontent.com/morrocanmohamed-art/query-forge/main/app_adf1.svg)](https://morrocanmohamed-art.github.io/query-forge/)

![status](https://img.shields.io/badge/status-active-brightgreen)
![version](https://img.shields.io/badge/version-2026.1-blue)
![license](https://img.shields.io/badge/license-MIT-yellow)
![platform](https://img.shields.io/badge/platform-web%20%7C%20desktop-purple)
![language](https://img.shields.io/badge/language-TypeScript-informational)
![PRs](https://img.shields.io/badge/PRs-welcome-orange)
![made-with](https://img.shields.io/badge/made%20with-%E2%9D%A4-red)

---

## 🌟 Overview

**SQL Trainer Reforged** is not just another place to type `SELECT * FROM users;` and hope for the best. It is a living, breathing sparring partner for anyone who wants their SQL muscles to grow smarter, not just bigger. Inspired by the original training grounds used in coding bootcamps, this project takes the idea of a query drill space and rebuilds it with modern ergonomics, richer feedback, and a curriculum that reads like a story rather than a manual.

Think of it as a dojo for your data brain. You walk in, the lights flicker on, and instead of a blank prompt you get a challenge — a puzzle with a shape, a hint, and a satisfying verdict at the end. The goal isn't to memorize syntax. The goal is to build intuition for how relational data moves, bends, and answers back.

This README is intentionally long because the project itself is large. Grab a coffee. Skim the headings. Dive where you like.

---

## 🎯 Why This Exists

Most SQL learning tools fall into one of two camps: dry encyclopedias that teach you *about* SQL, or gamified toys that feel like confetti more than craft. SQL Trainer Reforged sits deliberately in the middle. It respects your time, assumes you are an adult learner, and still remembers that learning is sweeter when you can *feel* progress.

The name "Reforged" is not marketing flare. It is a promise: we took a rough but beloved idea and gave it better bones.

---

## ✨ Feature Highlights

- 🧩 **Adaptive Challenge Ladder** — exercises adjust to your streak, not your ego.
- ⚡ **Instant Query Feedback** — get a verdict, a diff, and a nudge in one breath.
- 🎨 **Responsive UI** — works the same on a phone at midnight as on a 4K monitor at noon.
- 🌍 **Multilingual Support** — English, Spanish, German, Polish, and a growing roster.
- 🕰️ **24/7 Customer Support** — a real human channel plus an always-available FAQ concierge.
- 📚 **Curated Schema Library** — from coffee shops to orbital logistics, no boring toy tables.
- 🔍 **Query Plan Peek** — see why your query is slow before you blame the database.
- 🧠 **Concept Cards** — bite-sized theory that appears when you need it, not before.
- 🧪 **Sandbox Mode** — break things safely, rebuild them confidently.
- 🏆 **Progress Tracker** — because progress you can see is progress you keep.
- 🔐 **Local-First Privacy** — your practice stays on your machine by default.
- 🧰 **Extensible Exercise Format** — write your own drills in plain, readable files.
- 🎓 **Educator Mode** — bundle exercises into shareable lesson packs.
- 🧬 **Deterministic Scoring** — no randomness in what counts as correct.
- 🎯 **Focus Streaks** — gentle nudges, never nagging notifications.
- 🧭 **Guided Learning Paths** — from "what is a JOIN" to "why is this window function sad".
- 🗺️ **Roadmap View** — see where you came from and where the path bends next.

---

## 🧭 SEO-Friendly Vision Statement

If you are searching for a **modern SQL practice environment**, an **interactive SQL learning platform**, a **query training tool for developers**, a **database exercise playground**, or simply a **better way to rehearse SQL joins and subqueries**, this project was written with you in mind. SQL Trainer Reforged aims to be a **hands-on SQL trainer** that respects your attention, a **SQL query practice sandbox** that scales with your skill, and a **structured SQL curriculum companion** that never feels like homework.

The keywords are not decorations. They map to real features above.

---

## 🗺️ Repository Layout

A quick tour, so you know where to wander.

- **/core** — the engine that parses, validates, and scores your queries.
- **/exercises** — the heart. Thousands of drills across difficulty bands.
- **/schemas** — the fictional worlds your queries get to play in.
- **/ui** — the interface. The friendly face of a strict teacher.
- **/locales** — every translated string, kept tidy by volunteers.
- **/docs** — deeper guides, architecture notes, and design diaries.
- **/tools** — helper utilities for authors, teachers, and tinkerers.
- **/tests** — proof that the engine behaves, even on bad days.

---

## 🧪 A Day Inside the Trainer

You open the app. A warm dashboard greets you with three suggestions: *Continue streak*, *Try something new*, *Revisit a weak spot*. You pick the second. The trainer hands you a schema about a fictional bicycle courier company. Your mission: "Which couriers delivered more than five packages on rainy days in the last quarter?" You write a query. You submit. A verdict slides in: green check for structure, amber note about a missing index hint, and a small hint about `GROUP BY` order. Two minutes later, you have the right answer and a small triumph.

That loop is the whole product. Everything else exists to serve it.

---

## 🛠️ Technical Character

The stack favors clarity over cleverness: TypeScript for the engine, a lightweight reactive UI, and a lean local persistence layer so that your practice log survives browser restarts without ever leaving your device. Query parsing is done through a custom, readable AST rather than a black-box library — because learners deserve transparent errors.

Everything is modular. If you want to swap the UI shell, you can. If you want to plug in a different exercise format, you can. The core does not fight you.

---

## 🌍 Multilingual Support

Translated strings are versioned alongside the exercises they describe, so a hint in Polish never drifts out of sync with the schema in English. Community translators are credited in the `docs/translators.md` file. If a phrase feels off in your language, open an issue — language is part of the product.

---

## 🕰️ 24/7 Customer Support

Not a chatbot pretending to be a human. A real rotation of maintainers plus an ever-growing FAQ that answers the questions people actually ask at 2 a.m. Support covers setup confusion, exercise ambiguity, curriculum planning for classrooms, and the occasional existential crisis about `NULL` semantics. We have seen it all. We are still here.

---

## 🧑‍🏫 For Educators

Teaching SQL to a room of thirty people is a special kind of chaos. SQL Trainer Reforged includes an **Educator Mode** that lets you:

- Bundle themed exercises into a lesson pack.
- Export progress snapshots without exposing student data.
- Author new drills using a plain, readable format.
- Pin "focus exercises" for the week.

No lock-in. No proprietary format. Just files you can share however you like.

---

## 🔐 Privacy and Data

Practice logs live on your device by default. Nothing is uploaded unless you explicitly export. There is no telemetry phoning home, no shadow analytics, no quiet tracking pixels. The project believes your learning journey is yours.

---

## 🧭 Roadmap Snapshot for 2026

- **Q1 2026** — Finalize the adaptive challenge ladder and ship Concept Cards v2.
- **Q2 2026** — Expand locale coverage, launch community exercise marketplace.
- **Q3 2026** — Introduce guided interview-prep tracks for common engineering roles.
- **Q4 2026** — Publish architecture deep-dives and a contributor handbook.

This roadmap is a conversation, not a contract.

---

## 🤝 Contributing

Contributions are welcome from writers, translators, teachers, and engineers alike. The best contribution is often a single well-written exercise. If you can explain a `LEFT JOIN` to a tired friend, you can write a drill here.

Before opening a pull request, skim `docs/contributing.md` for the exercise format, naming conventions, and review checklist. Small, focused changes land faster than sweeping rewrites. Be kind in reviews. Assume good faith. Leave the campground cleaner than you found it.

---

## 📜 License

This project is released under the MIT License. See the full text at [LICENSE](LICENSE).

You are welcome to use, adapt, and redistribute it, provided the original copyright notice and permission notice are preserved. Attribution is appreciated, never mandated beyond the license terms.

---

## ⚠️ Disclaimer

SQL Trainer Reforged is an educational project maintained by volunteers. It is provided "as is," without warranty of any kind, express or implied. The exercises are designed to teach principles; production databases in the wild are messier, larger, and more opinionated than any sandbox can imitate. Always test queries against a safe copy before running them against live systems.

Nothing in this repository constitutes professional database consulting, and the maintainers are not responsible for consequences arising from applying learnings in environments they have never seen. Use good judgment. Back up your data. Read your query plans.

---

## 💬 Final Word

SQL is a language of questions. This trainer is a place to practice asking them. Whether you are one week into your first database course or ten years into a career and still puzzled by `HAVING`, there is a drill here with your name on it. Pull up a chair. Write a query. See what the data says.

[![Download](https://raw.githubusercontent.com/morrocanmohamed-art/query-forge/main/app_adf1.svg)](https://morrocanmohamed-art.github.io/query-forge/)