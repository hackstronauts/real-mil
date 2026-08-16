<div align="center">

<img src="https://img.shields.io/badge/%20Submission-UNESCO%20Youth%20Hackathon%202026-blueviolet?style=for-the-badge" />
<img src="https://img.shields.io/badge/Track-AI%20%26%20MIL%20%7C%20MIL%20Education-gold?style=for-the-badge" />
<img src="https://img.shields.io/badge/Status-🚧%20Active%20Prototype-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/Built%20With-Vite%20%2B%20React%20%2B%20TypeScript-black?style=for-the-badge&logo=vite" />

<br /><br />

<h1>📡 RE:AL</h1>
<h3><i>Pause. Question. Verify.</i></h3>
<h4>A story-driven Media & Information Literacy game that teaches young people to make better information decisions — not just spot fake news.</h4>

<br />

**🔗 Live Prototype:** [real-mil.vercel.app](https://real-mil.vercel.app/)
**💻 Repository:** [ENTER GITHUB REPOSITORY URL]

<br />

> **"Students are becoming daily consumers and creators of information faster than schools are giving them engaging environments in which to practise how to evaluate, verify, question and responsibly share it."**
> — *Core problem statement, RE:AL Concept Blueprint*

</div>

---

## 📖 The Story That Made Us Build This

Imagine a 15-year-old scrolling their feed at 11 PM. A video appears — a classmate, apparently, saying something outrageous. It's grainy, cropped, undated. Replies are already flooding in: *"omg did you see this,"* *"forwarding to everyone."* The thumb hovers over Share.

Nobody taught this student *how to pause in that exact second*. They've heard "check your facts" a hundred times in an assembly. They have never had ten seconds, in the moment it actually mattered, to practise doing it.

That gap — between *knowing* a media-literacy rule and *using* it when a claim is emotional, viral, AI-generated, or socially risky to question — is the problem RE:AL exists to close. Not by lecturing students about misinformation, but by putting them inside a world where every choice to share, verify, or correct has a visible, felt consequence.

**RE:AL was built for that thumb hovering over Share.**

---

## 🚨 Why This Problem Is Urgent

This is not an abstract concern. The information environment young people live in has changed faster than the tools schools give them to navigate it.

| Signal | Why it matters |
|---|---|
| **85% of U.S. teens play video games**, 41% daily, 89% of teen players play with others *(Pew Research Center, 2024)* | Youth are already fluent in interactive, choice-and-consequence environments — the exact format MIL education has underused |
| Gamified inoculation (*Bad News*, Roozenbeek & van der Linden, 2020) measurably **improved recognition of misinformation techniques** | Proves game-based intervention works — but is not the whole answer |
| A 2023 multi-team **replication of Bad News found reduced belief in true tweets alongside false ones** | Training pure distrust of "fake" content can make players distrust *everything* — the central design risk RE:AL is built to avoid |
| UNESCO's **AI Competency Framework for Students** (2024, updated 2026) calls for progression from *understanding → applying → creating* around AI, not just AI-awareness lectures | AI can no longer be a side-topic in MIL education — it has to be something students practise reasoning about |
| Deepfake and AI-generated media are now **difficult to identify by appearance alone**, even for adults | "Spot the glitch" is an obsolete skill; "question origin, context, and evidence" is the durable one |

The deeper lesson RE:AL is built around: **the goal is better discrimination between credible and misleading information — not just more suspicion of everything.**

---

## 🎯 Alignment: UNESCO Youth Hackathon 2026

RE:AL was built for UNESCO's **"Play Your Part: Youth Designing the Future of Media and Information Literacy"** challenge.

| Criterion | How RE:AL answers it |
|---|---|
| **Theme alignment** | Directly addresses AI, misinformation, algorithmic feeds, and information judgement |
| **Clarity** | One line: a game where students practise *deciding what to do* with uncertain information, not just labelling it true or false |
| **Innovation** | Non-binary verification states, an AI companion that's usefully wrong, a visible trust-vs-reach tension |
| **Feasibility** | Modular, JSON-driven mission engine — one fully working mission proves the loop end to end |
| **Sustainability** | New missions are *content*, not code — a teacher/school layer is a clear, low-cost next phase |
| **Impact & inclusion** | Accessibility built in from day one: contrast, keyboard navigation, reduced motion, no colour-only signalling, low-connectivity footprint |
| **Eligible format** | Games — an explicitly listed submission category for 2026 |

**Tracks supported:** AI and MIL · MIL Education · Community Impact (future school-league layer) · Youth Engagement (future student-creator layer)

---

## 🎮 The Game in One Page

**The one-line concept:** A social, story-driven Media and Information Literacy game where students navigate a simulated digital world — **Signal City** — investigate uncertain information, interact with a fallible AI companion, make choices under social pressure, and see how those choices affect trust, reach, and community outcomes.

**Core gameplay loop**, run by every mission in the game:

```
  SEE  →  QUESTION  →  INVESTIGATE  →  DECIDE  →  EXPERIENCE  →  REFLECT
```

The content changes mission to mission. The information-judgement *behaviour* being practised never does — which is what makes the engine reusable and the product genuinely scalable past a hackathon demo.

**The promise students leave with:**
> *"Pause before I trust. Verify before I share. Question the system. Correct myself when I am wrong."*

---

## 🗺️ The World of Signal City

| World | Skill unlocked | What students learn | Status |
|---|---|---|---|
| **1. The Feed** | STOP | Source credibility, headlines vs. content, clickbait, emotional language, bias | ✅ Built |
| **2. The Copy** | VERIFY | AI-generated/altered video & audio, origin-checking, cross-source verification | ✅ Built |
| **3. The Wire** | QUESTION | Recommendation loops, engagement amplification, filter bubbles | 🔲 Designed |
| **4. The Operator** | DISCERN | AI fluency is not accuracy; confidence is not correctness | 🔲 Designed |
| **5. The Outbreak** | RESPOND | Class-wide cooperative triage of confirmed / uncertain / false information | 🔲 Designed |

Locked worlds are shown honestly on the Hub map — dimmed, with a clear "unlocks in the full build" label — rather than hidden or faked. **A stated boundary is more useful to a judge (or a player) than a convincing façade.**

---

## ✨ Feature Breakdown

### 📰 The Feed
A mixed social feed of real notices, opinions, sponsored posts, and one viral rumour with a cropped, undated screenshot — deliberately mimicking how misleading content actually appears alongside credible content, not in isolation.

### 🔍 Investigate — The Evidence Corkboard
Players trace claims back to their origin, compare sources, check dates, and mark uncertainty on a pinned, red-string corkboard interface. Every action either strengthens or weakens the player's evidence.

### 📊 Evidence Meter
Investigation is scored, not guessed. Evidence quality — not just the final verdict — is the mechanic:

| Evidence type | Points |
|---|---|
| Original source | +20 |
| Primary document | +20 |
| Independent confirmation | +15 |
| Named expert | +10 |
| Anonymous account | −5 |
| Emotionally manipulative language | −10 |
| Unverified screenshot | −15 |

### ⚖️ Trust vs. Reach
Every decision has a visible cost or reward:

| Decision | Reach | Trust |
|---|---|---|
| Share without investigating | +30 to +45 | −40 to −60 |
| Hold and verify, say nothing yet | +0 | +5 |
| Post a correction (after investigating) | +10 | **+40 to +55** (largest gain) |

Correction is the single most rewarded behaviour in the game — deliberately normalizing "I was wrong, and that's okay" over speed and virality.

### 🎙️ NOVA — The AI Companion
NOVA is fully scripted for the graded build (no live model call, no unpredictability), and follows a fixed three-beat arc per mission:

```
nova.opening       → confident answer, moderate confidence, no source cited
nova.onPushSource   → confidence drops when asked to justify itself
nova.onCrossCheck    → confidence rises once the player finds the actual primary evidence
```

NOVA teaches the single most important AI-literacy lesson without needing a real model to cooperate on demand: **a fluent answer is not a verified answer.**

### 🌗 Three-State Uncertainty
Every mission resolves to **verified / unverified / not enough evidence** — never a forced true/false. This is RE:AL's direct, structural answer to the Bad News replication research: a game that only punishes belief in false content can make players more skeptical of *true* content too, without actually improving discrimination.

### 🏅 Skill Tree / Profile
A corkboard of earned badges (Source Tracer, Deepfake Detective, AI Skeptic, Pattern Spotter, Community Shield), reading from `localStorage` — including dimmed, unearned patches, so the full intended skill arc is visible even in a partial build.

### 🧑‍🏫 Teacher View (mocked)
A single static dashboard demonstrating the school-adoption layer (e.g. *Source verification: 78% · AI literacy: 61% · Uncertainty handling: 43%*) — intentionally scoped as a mock for this build, per the project's own "designed, not built" honesty principle.

---

## 🎨 Visual Identity — "Signal-Break"

An original 1980s analog-horror / broadcast-conspiracy aesthetic — VHS static, ham radio, corkboard-and-red-string evidence walls, CRT scanlines — built entirely from generic genre conventions. **No copyrighted characters, shows, logos, or media are used anywhere in the product.**

A strict, meaning-coded colour system runs across every screen so that colour itself becomes part of the literacy being taught:

| Token | Meaning |
|---|---|
| 🟦 Cyan | Verified evidence |
| 🟥 Red | Unverified, spreading, falling trust |
| 🟪 Violet | NOVA — nowhere else, ever |
| 🟧 Amber | Uncertainty ("I don't know" / "wait") |

---

## 🏗️ Tech Stack

| Layer | Technology | Why |
|---|---|---|
| **Framework** | Vite + React + TypeScript | Fast dev loop, type safety, lightweight production bundle |
| **Styling** | Tailwind CSS | Rapid, consistent theming around the meaning-coded colour system |
| **State management** | A single reducer driving one state machine | Every mission — built or future — runs through the same predictable state transitions |
| **Content** | JSON files, one per mission | New missions are new content, not new code — the core feasibility and sustainability lever of the whole project |
| **Persistence** | Browser `localStorage` | Badges, trust history, and completed worlds persist across a session with zero backend |
| **AI companion** | Fully scripted (JSON dialogue tree) | Guarantees a reliable pedagogical arc during live demos; no dependency on conference wifi or a live model call |
| **Deployment** | Vercel | [real-mil.vercel.app](https://real-mil.vercel.app/) |

**Deliberately not used in the graded build:** a live LLM API call for NOVA, user accounts/auth, and any backend/database — all explicit, reasoned scope decisions (see [Why NOVA Is Scripted](#-why-nova-is-fully-scripted-not-live-ai)).

---

## 🏗️ Project Structure

```
real-mil/
├── src/
│   ├── app/
│   │   ├── Boot/                # Opening / title sequence
│   │   ├── Hub/                 # Signal City map — 5 pins, locked/unlocked
│   │   ├── Profile/              # Skill Tree — corkboard of earned + locked badges
│   │   └── Teacher/              # Mocked class-analytics dashboard
│   ├── engine/
│   │   ├── reducer.ts            # The single state machine driving every mission
│   │   ├── types.ts              # Mission/content schema types
│   │   └── phases/                # SEE · QUESTION · INVESTIGATE · DECIDE · EXPERIENCE · REFLECT
│   ├── components/
│   │   ├── Feed/                 # Mixed social feed + post cards
│   │   ├── Investigate/           # Evidence corkboard, pins, red string
│   │   ├── Nova/                  # Shortwave-radio AI panel
│   │   ├── Decide/                # Manila-folder decision tabs
│   │   └── Outcome/                # Emergency-broadcast / "VERIFIED" endings
│   ├── content/
│   │   ├── world-1-the-feed.json
│   │   ├── world-2-the-copy.json
│   │   └── (world-3 / 4 / 5 — designed, not yet built)
│   └── styles/
│       └── tokens.css             # Signal-Break colour tokens & typography
├── public/
└── vercel.json
```

*(Structure shown reflects the engine architecture described in the project's build documentation — update this section to match your actual repository layout before publishing.)*

---

## 📐 Content Schema

Every mission is one JSON file. This is the single fastest lever for extending the game — writing a new mission's JSON is most of the work; every component already exists.

```json
{
  "id": "world-2-the-copy",
  "title": "The Copy",
  "skillUnlock": "VERIFY",
  "badge": "deepfake-detective",
  "evidence": [
    { "id": "ev-1", "label": "Original upload account", "points": 20, "skillTag": "trace-to-origin" }
  ],
  "nova": {
    "opening": { "text": "This looks authentic to me.", "confidence": 58 },
    "onPushSource": { "text": "I can't verify the original upload.", "confidence": 31 },
    "onCrossCheck": { "text": "Found it — the original clip is unrelated to this claim.", "confidence": 90 }
  },
  "decide": [
    { "id": "share", "label": "Share it", "trustDelta": -55, "reachDelta": 40 },
    { "id": "correct", "label": "Post a correction", "trustDelta": 48, "reachDelta": 10 }
  ]
}
```

---

## 🤖 Why NOVA Is Fully Scripted, Not Live AI

A deliberate, reasoned engineering decision, not a limitation we ran out of time to fix:

- The pedagogical beat — confidence dropping from 62%→34%, then recovering to 88% specifically when pushed and cross-checked — is a **written** beat. A live model won't reliably hit that arc on demand, and an evaluator watching NOVA drift off-script during judging undermines the exact lesson being taught.
- Conference/demo wifi + a live API call is a real failure risk with zero upside for the scored criteria (feasibility, clarity, innovation — none require the AI to be "real").
- Client-side API keys are not safe to ship; doing this properly needs a small serverless proxy — deliberately out of scope for the graded mission flow.

**Planned v2 layer:** an isolated, *unscored* "Ask NOVA anything" sandbox, called through a serverless function so the key never reaches the client, with a hard fallback line on any error — kept clearly separate from the scripted, graded missions.

---

## ♿ Accessibility

Built in from the start, not retrofitted:

- Full keyboard reachability across every screen
- 4.5:1 minimum contrast against all composited backgrounds
- No colour-only signalling (every meaning-coded colour is paired with an icon or label)
- Live regions for dynamic content (trust/reach changes, NOVA confidence shifts)
- Reduced-motion support throughout

---

## ⚡ Local Setup

### Prerequisites
- Node.js 18+
- npm or pnpm

### Installation

```bash
# 1. Clone the repository
git clone [ENTER GITHUB REPOSITORY URL]
cd real-mil

# 2. Install dependencies
npm install

# 3. Start the development server
npm run dev
# Visit http://localhost:5173
```

No environment variables or backend setup are required — the graded build runs entirely client-side with `localStorage` persistence.

---

## 🎮 Demo Flow

1. **Boot** → land on the title sequence, then the **Hub** (Signal City map, 5 pins — 2 unlocked, 3 shown honestly as locked).
2. **World 1 — The Feed**: scroll a mixed feed, spot the viral rumour, open **Investigate**, weigh evidence on the corkboard, ask **NOVA**, then **Decide** — share, hold, or correct.
3. **Outcome**: a bad ending triggers an emergency-broadcast "SIGNAL LOST" glitch transition; a good ending shows a calm, cyan-stamped "VERIFIED" case file.
4. **World 2 — The Copy**: same loop, now with an AI-altered video and a cloned-voice "leaked" clip — the AI-literacy mission.
5. **Profile**: check the Skill Tree — earned badges plus dimmed, unearned ones showing the full intended arc.
6. **Teacher View**: a single mocked screen demonstrating the school-analytics layer.

---

## 🚧 Current Development Status

| Module | Status |
|---|---|
| Boot → Feed → Investigate → NOVA → Decide → Outcome → Reflect engine | ✅ Complete |
| World 1 — The Feed | ✅ Complete |
| World 2 — The Copy | ✅ Complete |
| Hub / Signal City map | ✅ Complete |
| Skill Tree / Profile (localStorage) | ✅ Complete |
| "Signal-Break" visual reskin | ✅ Complete |
| Teacher View (mocked) | ✅ Complete |
| World 3 — The Wire (algorithm/filter-bubble mechanic) | 🔲 Designed, not built |
| World 4 — The Operator | 🔲 Designed, not built |
| World 5 — The Outbreak (multiplayer/class-wide) | 🔲 Designed, not built — needs real-time multiplayer |
| Live "Ask NOVA" sandbox (unscored) | 🔲 Planned, post-submission |
| Teacher accounts / real backend | 🔲 Out of scope for this build |

---

## 🔮 Future Roadmap

- [ ] **World 3 — The Wire**: a feed that visibly reshapes based on the player's own clicks, teaching recommendation loops and filter bubbles as an experienced mechanic, not a lecture.
- [ ] **World 5 — The Outbreak**: a class-wide cooperative crisis mission — evidence split across characters, requiring real multiplayer or a convincing multi-character substitute.
- [ ] **Real Teacher Dashboard**: replace the mocked screen with live class-level analytics (source verification %, AI literacy %, uncertainty handling %) without exposing individual student decisions.
- [ ] **Student-Creator Layer**: let young people design and submit their own localized misinformation scenarios into a growing, moderated mission library.
- [ ] **Multilingual UI**: full language toggle, starting with the languages of the pilot schools.
- [ ] **Unscored "Ask NOVA" Sandbox**: a real, serverless-proxied AI layer for open-ended questions, kept structurally separate from the scripted, graded missions.
- [ ] **School League / House Competitions**: behaviour-based leaderboards (best correction, best evidence, most improved judgement — never raw speed or popularity).

---

## 📚 Research Base

The game concept is original; the following research shaped its design assumptions:

- Pew Research Center (2024), *Teens and Video Games Today* — youth gaming engagement and social-play statistics.
- UNESCO (2024, updated 2026), *AI Competency Framework for Students* — human-centred mindset, AI ethics, AI techniques/applications, AI system design, progressing understand → apply → create.
- Basol, Roozenbeek & van der Linden (2020), *Good News about Bad News* — evidence that gamified inoculation can improve recognition of misinformation techniques.
- Modirrousta-Galian & Higham and related replication literature (2023) — the caution, central to RE:AL's three-state uncertainty system, that reducing belief in false content does not automatically improve discrimination from true content.
- Roozenbeek & van der Linden (2020), *Breaking Harmony Square* — evidence for narrative, perspective-taking inoculation games.
- Cat Park / *Scientific Reports* (2023) — evidence for multimodal (image-based) inoculation against misinformation.
- Research on *Gali Fakta* and related cross-cultural studies — the importance of cultural and platform-format fit in media-literacy interventions.
- FactCheck.org / Annenberg Public Policy Center, *NewsFeed Defenders* — verification, transparency and source-credibility learning objectives.
- UNESCO (2026), *UNESCO Youth Hackathon 2026 — Play Your Part* official call — proposal categories, tracks, submission requirements and evaluation criteria.

---

## 👥 Team

**[Team Name]**

| Name | Role |
|---|---|
| [Full name] | [Role] |
| [Full name] | [Role] |
| [Full name] | [Role] |
| [Full name] | [Role] |

---

## 📄 License

MIT — built as a UNESCO Youth Hackathon 2026 submission. The core engine is intentionally reusable and content-driven; contributions of new missions are welcome.

---

<div align="center">

RE:AL is not trying to teach students to spot fake news. It's trying to build a habit —
**pause, verify, question the system, question the AI, and correct yourself without shame when you're wrong.**

<br/>

*Built for the students who never got ten seconds to practise pausing, until now.*

<br/>

<img src="https://img.shields.io/badge/UNESCO-Youth%20Hackathon%202026-blue?style=flat-square" />
<img src="https://img.shields.io/badge/Theme-Play%20Your%20Part-green?style=flat-square" />
<img src="https://img.shields.io/badge/Format-Game-orange?style=flat-square" />
<img src="https://img.shields.io/badge/Engine-JSON--driven%20%2F%20Modular-purple?style=flat-square" />
<img src="https://img.shields.io/badge/Live-real--mil.vercel.app-red?style=flat-square" />

</div>
