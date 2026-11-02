# 🌟 Sanav & Sanha's 3rd Grade Learning Hub

**Live Web Application:** [https://janar23.github.io/3rdgrade_1/](https://janar23.github.io/3rdgrade_1/)  
**School:** Somtherman Elementary School • Prosper Independent School District (Prosper, TX)  
**Grade Level:** 3rd Grade (Foundational Math & Literacy Curriculum)

---

## 🎯 Purpose & Focus Areas

This lightweight, zero-dependency, tablet-friendly HTML/JS/CSS application is designed for Sanav and Sanha to practice and master their 3rd-grade school curriculum at home on their Android tablets and laptops.

### 1. 🔢 Targeted Math Power-Ups (Perimeter, Elapsed Time, Data Intervals & Place Value to 100,000)
Based on 3rd Grade TX TEKS & Weekly Classroom Focus:
* **This Week's Focus (Nov 2–6):**
  * *Perimeter Architect:* Polygon outer-side addition, opposite equal sides of rectangles, and Missing Side Mysteries.
  * *Elapsed Time Navigator:* Solving start time, end time, and elapsed time interval problems using number-line jumps and clock intervals (TX TEKS 3.7C).
* **Prior Week Review (Oct 26–30):**
  * *Data Intervals Detective:* Scaled bar graphs (counting by `2s`, `4s`, `5s`, and `10s`), reading half-interval bars, and "how many more/fewer" comparisons.
* **Sanav's Booster:** Multiplicative $10\times$ Place-Value Relationships (e.g., in $5,441$, digit in hundreds is $10\times$ greater than tens) and Regrouping whole numbers ($20\text{ tens} = 2\text{ hundreds}$).
* **Sanha's Booster:** Visual Base-10 Blocks identification ($1,000$ Cubes, $100$ Flats, $10$ Rods, $1$ Units).
* **Interactive Games:**
  * *Flyswatter Number Zap:* Identify and swat place value digits up to $100,000$.
  * *5-Digit "Roll-It" Sandbox:* Real-time translation between Standard Form, Expanded Form, Expanded Notation, and Word Form.

### 2. 📖 Built-in Book Reader & Comprehension Quests
* **Integrated e-Reader:** Full page-by-page readable text with paragraph chunking and browser speech synthesis.
* **Animated Video Mode:** Embedded read-aloud players.
* **Evaluation Quizzes:** Tailored higher-order thinking questions on:
  * Non-Fiction Print Features (Table of Contents, Headings, Subheadings, Bold/Italics, Captions, Diagrams, Glossary vs. Index)
  * Everyday Energy (M.E.L.T.S. — Mechanical, Electrical, Light, Thermal, Sound)
  * Poetry Elements (Lines, Stanzas, Rhyme Scheme, Alliteration, Onomatopoeia, Free Verse)
  * Central Lesson & Theme
  * Cause & Effect / Character Motivations
  * Vocabulary in Context
* **Curated Stories & Weekly Units:**
  * *Print Features Detective: Navigating Non-Fiction* (Nov 2–6 ELAR Print Features Focus)
  * *Everyday Energy: M.E.L.T.S. in Action!* (Nov 2–6 Science Energy Focus)
  * *Reflections of Culture in Our Community* (Nov 2–6 Social Studies & Veterans Day Focus)
  * *Poetry Power: Rhythm, Rhyme & Stanzas* (Oct 26–30 ELAR Poetry Review)
  * *Magnetic Forces: Push, Pull & Poles* (Oct 26–30 Science Magnetism Review)
  * *The Empty Pot* by Demi (Honesty Fable)
  * *Enemy Pie* by Derek Munson (Friendship & Empathy)
  * *Earthquakes & Volcanoes* (Level P Non-Fiction Science)

### 3. ✍️ Weekly School Literacy Support (Monday – Friday)
* **Weekly Phonics & Dictation Hub (Multi-Week Selector):**
  * **Nov 2–6 • Print Features & Energy:** Print Features, Everyday Energy (M.E.L.T.S.), Elapsed Time & Perimeter, Prefixes & Suffixes, Culture & Veterans Day (42 target words + 2 decodable sentences).
  * **Oct 26–30 • Poetry & Word Study:** Poetry Elements, Rhyming Families, Sound Words (Onomatopoeia), Academic Vocab (42 target words + 2 decodable sentences).
  * **Unit 1 • Week 3:** Short `/e/`, Short `/o/`, Blends & Digraphs, Multisyllabic Chunking (56 target words + 2 decodable sentences).
  * **Unit 1 • Week 2:** Short `/a/`, Short `/i/`, Plural `-s` & Endings (`-ed`, `-ing`), Multisyllabic Chunking (48 target words + 2 decodable sentences).
* **Wednesday Phonics & Blending Lines Decoder:** Interactive tactile syllable chunk buttons (`[back]` `[pack]`), speech synthesis blending, and phonics rule breakdowns.
* **Thursday Dictation Arena:** Audio-prompted spelling challenge preparing for Friday's Independent Dictation with spelling hints and star rewards.
* **Friday Reading in Context (Decodable Sentences):** Interactive sentence reader where kids can tap individual words to hear them sounded out and practice fluency.
* **Tuesday Vocabulary Detective:** Digital word exploration and personal word vault saved in `localStorage`.

### 4. 🤖 Antigravity AI Detective & Co-Pilot Academy
* **Core Philosophy:** "You are the Captain, AI is your Co-Pilot!"
* **Traffic Light Challenge (When to Use AI):** Interactive scenarios teaching 3rd graders when AI is great (🟢 Green Light), when to think first and verify (🟡 Yellow Light), and when to use brain-only or protect privacy (🔴 Red Light).
* **Catch the Robot Glitch (Hallucination Detective):** Fun error-spotting cases where kids audit confident AI statements to find sneaky place-value, story, or science mistakes.
* **The Captain's Prompt Builder:** Visual 3-part prompt engineering (`[WHO]` Persona + `[WHAT]` Creative Task + `[GUARDRAIL]` Rules) with audio read-aloud.
* **Dual Engine Architecture:** Works 100% offline out-of-the-box with a built-in combinatorial engine, or connects to live Google Gemini 1.5 Flash via a discreet parent settings panel.

---

## 🛠️ Tech Stack & Deployment
* **Client-Side:** Pure HTML5, CSS3, ES6 JavaScript (No backend or framework needed, runs 100% offline).
* **Audio:** Web Audio API synthesizer for sound effects + Web SpeechSynthesis for reading text aloud.
* **AI Integration:** Direct browser-to-API Gemini 1.5 Flash client-side integration + fallback offline simulation engine.
* **Storage:** Browser `localStorage` to persist Stars, caught glitches, completed book missions, and custom vocabulary words.
* **Hosting:** GitHub Pages (`janar23/3rdgrade_1`).

---

## 📅 Weekly Smore Curriculum Updates & Changelog

### Week of November 2–6, 2026
* **Smore Newsletter Source:** [`https://app.smore.com/n/gsh1e`](https://app.smore.com/n/gsh1e)
* **Important November Dates:**
  * **Nov 6:** Veterans Day Program
  * **Nov 13:** World Kindness Day
  * **Nov 20:** Special Friends Day
  * **Nov 23–27:** Thanksgiving Break
* **Modules Added / Updated:**
  1. **🔢 Math (`Perimeter & Elapsed Time`):**
     * Added the `⏱️ Nov 2–6 • Perimeter & Elapsed Time (2)` filter button in `filterMathWeek()` while preserving `📊 Oct 26–30 (2)` and `🔢 Place Value (5)` for review.
     * Added **Elapsed Time Navigator (`#cardElapsedTime`)** with visual number-line jumps and 6 TX TEKS 3.7C word problems (`generateElapsedTimeQuestion()`) alongside **Perimeter Architect (`#cardPerimeter`)**.
  2. **📖 Reading & Quests (`inAppBooks`):**
     * **ELAR (`Print Features`):** Added *Print Features Detective: Navigating Non-Fiction* (4 pages + 5-question quiz covering Table of Contents, Headings/Subheadings, Bold/Italics, Captions, Diagrams, and Glossary vs. Index).
     * **Science (`Everyday Energy`):** Added *Everyday Energy: M.E.L.T.S. in Action!* (4 pages + 5-question quiz covering Mechanical, Electrical, Light, Thermal, and Sound energy).
     * **Social Studies (`Reflection of Culture`):** Updated *Reflections of Culture in Our Community* for Nov 2–6 with a connection to the **November 6th Veterans Day Program**.
     * Preserved last week's *Poetry Power* and *Magnetic Forces* books with `📅 OCT 26–30` review badges.
  3. **✍️ Weekly Literacy (`weeklyPhonicsUnits`):**
     * Added **`Nov 2–6 • Print Features & Energy`** as the default active unit with **42 words** across 6 categories (*Print Features*, *Everyday Energy*, *Time & Perimeter*, *Prefixes & Suffixes*, *Culture & Veterans Day*, and *High-Frequency Heart Words*) plus 2 decodable context sentences.

### Week of October 26–30, 2026
* **Smore Newsletter Source:** [`https://app.smore.com/n/w326z`](https://app.smore.com/n/w326z)
* **Modules Added:**
  * **Math:** *Perimeter Architect* (`#cardPerimeter`) & *Data Intervals Detective* (`#cardDataIntervals`).
  * **Reading & Quests:** *Poetry Power: Rhythm, Rhyme & Stanzas*, *Magnetic Forces: Push, Pull & Poles*, and *Reflections of Culture in Our Community*.
  * **Weekly Literacy:** *Oct 26–30 • Poetry & Word Study* (42 words + 2 decodable sentences).

---

## 🔄 Automated Weekly Homework Update Workflow (`3rdgrade-weekly-homework` Skill)

To update the application for a new school week using the reusable agent skill (`.agents/skills/3rdgrade-weekly-homework/SKILL.md`):

1. **Share the Weekly Smore Link:** Paste the new Smore newsletter URL (`https://app.smore.com/n/...`) and ask the agent to **"Update 3rd grade homework for this week"**.
2. **Automated Execution Steps:**
   * **Step 1 (`git pull`):** Syncs local `/Users/jnarayanassamy/personal/kids/sanav_sanha/3rdgrade/` with `origin/main`.
   * **Step 2 (Smore Extraction):** Fetches the Smore newsletter and parses `MATH`, `ELAR`, `SCIENCE`, `SOCIAL STUDIES`, and `Important Dates`.
   * **Step 3 (Non-Destructive Prepend):**
     * Updates the welcome banner and quick-jump pills.
     * Adds a new weekly Math filter pill & interactive game card while keeping prior weeks accessible.
     * Prepends new ELAR/Science/Social Studies books & 5-question quizzes to `inAppBooks` and re-badges prior weeks as review.
     * Prepends a new 42-word weekly Phonics, Dictation & Word Study unit at index `0` of `weeklyPhonicsUnits`.
   * **Step 4 (Verification & Deployment):** Validates `<script>` syntax via `node`, updates `README.md`, commits, and pushes directly to `origin/main` so [https://janar23.github.io/3rdgrade_1/](https://janar23.github.io/3rdgrade_1/) updates automatically.
