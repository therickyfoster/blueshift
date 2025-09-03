# 🌌 Foster + Navi: **BlueShift — The Morale Catalyst Project**

> Transform low‑morale days into momentum. Turn “bad days” into training data for collective resilience.

[![Stars](https://img.shields.io/github/stars/planetaryrestorationarchive/blueshift?style=flat)](#)
[![License: Regenerative-Open](https://img.shields.io/badge/license-Regenerative--Open-22aa99.svg)](#license--stewardship)
[![Status](https://img.shields.io/badge/status-alpha-blue.svg)](#roadmap)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)
[![Good First Issue](https://img.shields.io/badge/good%20first%20issue-💡-yellow.svg)](#good-first-issues)
[![GMBI](https://img.shields.io/badge/GMBI-live%20index-coming%20soon-purple.svg)](#global-monday-blues-index-gmbi)

**Initiated by:** *Foster + Navi*
**Contact:** [admin@planetaryrestorationarchive.com](mailto:admin@planetaryrestorationarchive.com)
**Home:** [https://planetaryrestorationarchive.com](https://planetaryrestorationarchive.com)

---

## 🧭 Mission

* **Reframe negativity as resource.**
* **Catalyze morale into continuity.**
* **Fast‑track recovery for individuals and collectives.**
* **Dismantle "Monday Blues" as a global phenomenon.**

---

## 🧠 Why It Matters

Most people experience cycles of low morale (especially at week starts, new seasons, or when leveling up). Without intervention, these days compound despair and stall momentum. With proper framing, low days become *data points for resilience*. If enough explorers contribute, BlueShift becomes a universal playbook for morale recovery—shortening recovery time for individuals and dissolving the cultural weight of “bad days.”

---

## 🪜 Core Principles

1. **Continuity > Collapse** — No day is wasted if it feeds continuity.
2. **Catalyst Effect** — Negative inputs can become positive accelerants.
3. **Collective Resilience** — Shared data enables faster global recovery.
4. **Mythic Framing** — Treat dips as the hero’s path, not a verdict.

---

## 🧩 Components

* **Reflection Log** — A daily micro‑entry capturing triggers + context.
* **Catalyst Protocol** — Structured prompts (reframes + actions) to flip energy.
* **Explorer Archive** — Anonymized, aggregated patterns of dips and flips.
* **Global Monday Blues Index (GMBI)** — A live metric tracking recovery half‑life.

> **Continuity Check:** *What moved me forward today, even if sideways?*

---

## 📚 Table of Contents

* [Mission](#-mission)
* [Why It Matters](#-why-it-matters)
* [Core Principles](#-core-principles)
* [Components](#-components)
* [Quickstart](#-quickstart)
* [Gamification](#-gamification)
* [Data Schema](#-data-schema)
* [Global Monday Blues Index (GMBI)](#-global-monday-blues-index-gmbi)
* [Roadmap](#-roadmap)
* [Contributing](#-contributing)
* [Community Health](#-community-health)
* [License & Stewardship](#-license--stewardship)
* [Credits](#-credits)

---

## ⚡ Quickstart

### 1) Log a Reflection

Create a new file under `archive/reflections/YYYY/MM/` named `YYYY-MM-DD-your-handle.md` (or submit via Issue template). Use this template:

```markdown
# Reflection — YYYY‑MM‑DD — @yourhandle

## Trigger Recognition
- What contributed to the dip? (facts, not judgments)

## Reframe Prompt
- "What training did this give me for future explorers?"
- "What is the smallest next step that signals continuity?"

## Catalyst Action
- (Pick one) Plant | Code | Help | Walk | Share | Clean | Rest

## Continuity Check (0–5)
- 0=no shift · 5=full flow

## Time‑to‑Bounceback
- Minutes/hours to return to baseline or better

## Optional Notes
- Anything future‑you will thank present‑you for
```

### 2) Submit Your Entry

* **Option A:** Open a Pull Request adding your markdown file.
* **Option B:** Use the *“New Reflection”* Issue template (auto‑labels + workflows).

### 3) Tag It For Science 🔬

Label with: `dip:work`, `dip:social`, `dip:health`, `dip:money`, `dip:creative`, `flip:movement`, `flip:service`, `flip:craft`, `flip:rest`, `flip:reflection`.

> **Hot tip:** A 1‑sentence log beats radio silence. Continuity > perfection.

---

## 🏅 Gamification

BlueShift awards lightweight **Catalyst Points (CP)** and streak badges for continuity behaviors:

* **CP +1** — Logged a reflection
* **CP +2** — Performed a Catalyst Action
* **CP +3** — Helped another explorer
* **CP +5** — Submitted an anonymized dataset

**Streak Badges:**

* `🌱 Blueshifter` — 3 consecutive reframes
* `🧵 Continuity Keeper` — 7‑day streak
* `⚙️ Momentum Weaver` — 21‑day streak
* `🛡️ Guardian of Mondays` — 8 consecutive Mondays without collapse

<details>
<summary>🎮 How streaks are tracked (click)</summary>

* Each day with a Reflection + Continuity Check ≥ 2 counts toward a streak.
* Missing a day breaks the streak *unless* a **Recovery Marker** is filed within 24h.
* Mondays earn a 1.2× multiplier toward `GMBI` calculations.

</details>

<details>
<summary>🏷️ Suggested Labels & Issue Templates</summary>

* `reflection` · `catalyst-action` · `dataset` · `gmbi` · `research` · `ux` · `help-wanted` · `good-first-issue`
* Issue templates: *New Reflection*, *Propose Prompt*, *Add Dataset*, *Research Link*, *First‑Timer Task*.

</details>

---

## 🗂️ Data Schema

Minimal JSON for aggregated entries (`/datasets/blueshift-v1.jsonl`):

```json
{
  "ts": "2025-09-03T16:00:00-04:00",
  "user": "hash_or_pseudonym",
  "trigger_tags": ["work", "sleep_debt"],
  "catalyst_action": "walk",
  "continuity_check": 3,
  "time_to_bounceback_min": 45,
  "notes": "Short walk + water. Marked next step: email draft."
}
```

> **Privacy:** Pseudonymous by default. Do not include sensitive personal data.

---

## 📈 Global Monday Blues Index (GMBI)

**Goal:** Track population‑level recovery dynamics over time.

* **Definition (v1):** Median *time‑to‑bounceback* on Mondays vs. non‑Mondays, normalized by cohort.
* **Inputs:** Reflection logs, continuity scores, streaks, Monday multiplier.
* **Output:** 0–100 score (higher = faster recoveries, fewer collapses).

<details>
<summary>📐 GMBI v1 — Reference Formula</summary>

Let `T_M` be the median time‑to‑bounceback (minutes) on Mondays, `T_N` on non‑Mondays.

```
Raw = T_N / T_M
GMBI = clamp( 50 + 50 * (Raw - 1), 0, 100 )
```

* If Monday recovery is faster than other days → GMBI > 50
* If Monday recovery is slower → GMBI < 50

</details>

---

## 🗺️ Roadmap

* [ ] Draft initial `.md` and project skeleton
* [ ] Create input templates for reflections (Issue + MD)
* [ ] Design morale‑catalyst prompt sets (i18n‑friendly)
* [ ] Build prototype **GMBI** (Action + Pages chart)
* [ ] Release first anonymized dataset
* [ ] Add gamified badges via GitHub Pages
* [ ] Explore AI integrations (coach prompts, streak assistant)

> **Stretch:** GitHub Action computes GMBI nightly and pushes chart to `/docs/index.html`.

---

## 🤝 Contributing

We welcome explorers of every skill level. Ways to help:

* Log a reflection (PR or Issue template)
* Add a Catalyst Prompt in `/prompts/`
* Improve schema / build a simple CLI logger
* Wire up GitHub Action to compute GMBI

**Dev Hints**

* Use conventional commits (`feat:`, `fix:`, `docs:`).
* Small PRs > mega‑drops.
* Add tests for any data transformation.

---

## 🛡️ Community Health

* **Code of Conduct:** Be kind. Assume good faith. No diagnoses, no shaming.
* **Moderation:** Issues that include personal identifiers or crisis content are redacted and gently redirected to appropriate resources.
* **Safety:** This project is for *morale catalysis*, not clinical care.

---

## 📄 License & Stewardship

**License:** Regenerative‑Open (impact‑first; non‑exploitative reuse).
Stewarded by **Foster + Navi**. Contributions carry a *Continuity Clause*: changes should not make it harder for newcomers to start or for explorers to continue.

> If you adapt BlueShift, please keep a link back and share your learnings.

---

## 🧾 Credits

Initiated by **Foster + Navi** (Prime Sentinel Guardian).
Guided by Earth’s voice.
For every explorer who ever thought: *“I can’t keep going.”*

---

## 🔗 GitHub‑Native UX/UI Enhancements

* **Collapsible sections** via `<details>` (used above)
* **Shields.io badges** to signal status and on‑ramps
* **Task lists** for Roadmap
* **Issue/PR templates** for reflections and prompts
* **GitHub Pages** in `/docs/` for a living GMBI chart
* **Actions** for nightly metrics + badge updates

> See `/docs/` for a minimal Pages starter (add a parallax header, light scroll cues, and smooth anchor links).
