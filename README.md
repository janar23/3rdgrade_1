# 🌟 Sanav & Sanha's 3rd Grade Learning Hub

**Live Web Application:** [https://janar23.github.io/3rdgrade_1/](https://janar23.github.io/3rdgrade_1/)  
**School:** Somtherman Elementary School • Prosper Independent School District (Prosper, TX)  
**Grade Level:** 3rd Grade (Foundational Math & Literacy Curriculum)

---

## 🎯 Purpose & Focus Areas

This lightweight, zero-dependency, tablet-friendly HTML/JS/CSS application is designed for Sanav and Sanha to practice and master their 3rd-grade school curriculum at home on their Android tablets and laptops.

### 1. 🔢 Targeted Math Power-Ups (Place Value to 100,000)
Based on Khan Academy TX TEKS 3rd Grade assessments:
* **Sanav's Booster:** Multiplicative $10\times$ Place-Value Relationships (e.g., in $5,441$, digit in hundreds is $10\times$ greater than tens) and Regrouping whole numbers ($20\text{ tens} = 2\text{ hundreds}$).
* **Sanha's Booster:** Visual Base-10 Blocks identification ($1,000$ Cubes, $100$ Flats, $10$ Rods, $1$ Units).
* **Interactive Games:**
  * *Flyswatter Number Zap:* Identify and swat place value digits up to $100,000$.
  * *5-Digit "Roll-It" Sandbox:* Real-time translation between Standard Form, Expanded Form, Expanded Notation, and Word Form.

### 2. 📖 Built-in Book Reader & Comprehension Quests
* **Integrated e-Reader:** Full page-by-page readable text with paragraph chunking and browser speech synthesis.
* **Animated Video Mode:** Embedded read-aloud players.
* **Evaluation Quizzes:** Tailored higher-order thinking questions on:
  * Central Lesson & Theme
  * Cause & Effect / Character Motivations
  * Vocabulary in Context
  * Non-Fiction Text Features
* **Curated Stories:**
  * *The Empty Pot* by Demi (Honesty Fable)
  * *Enemy Pie* by Derek Munson (Friendship & Empathy)
  * *Earthquakes & Volcanoes* (Level P Non-Fiction Science)
  * *Clark the Shark* by Bruce Hale (Social Skills & Self-Control)

### 3. ✍️ Weekly School Literacy Support (Monday – Friday)
* **Weekly Phonics & Dictation Hub (Multi-Week Selector):**
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
