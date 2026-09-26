# MCQ Response Tracker — README

A tiny, keyboard-first tool to record MCQ answers and optionally grade them.  

**Live app:** [https://s2sofficial.github.io/mcq/](https://s2sofficial.github.io/mcq/)

[<img width="1672" height="941" alt="Poster" src="https://github.com/user-attachments/assets/ca79f5ae-1a22-4c47-9a10-a56e40f094a4" />](https://s2sofficial.github.io/mcq/)

## Features

- **Keyboard only:** Press `1` `2` `3` `4` for A B C D. Press `Enter` to commit. No mouse needed.
- **Two modes:**
  - **Logging** – records answers with date and exact time.
  - **Grading** – enter your answer, then the correct answer, and get instant Correct / Incorrect.
- **Blind grading:** Hide feedback until the session report. Good for exam simulation.
- **Single & multiple answers:** Toggle keys. `1 → 3 → 4` selects A+C+D. Press again to deselect.
- **Physical feel:** Four huge buttons that depress on press, with green/red LED glow for grading.
- **Session timer:** Starts, pauses, resumes. Paused time is not counted.
- **Per-question timing:** Tracks how long each question took. Shows avg, median, fastest, slowest.
- **Mark & confidence:** Flag questions with `M`. Rate confidence `7` / `8` / `9` (low / med / high).
- **Skip:** Press `S` to skip a question without answering.
- **Edit log:** Press `E` to fix any response, correct answer, mark, confidence, or renumber questions.
- **Session history:** Last 50 sessions stored. View, compare, delete, or re-open any past session.
- **Compare sessions:** Pick 2–5 sessions and compare side by side.
- **Export:** JSON and CSV per session. Backup all data as a single JSON.
- **Import:** Restore a backup file with `I`.
- **Dark / light theme:** Toggle with `T`.
- **Auto-save:** Refresh or close the tab — session is restored.
- **PWA:** Installable when served over HTTPS with `sw.js` present.

## How to use it

- **Mock test from a book**  
  Use **Logging Mode**. Solve from the book, press keys to record each answer. Timer runs like an exam timer. Finish to see all answers, timestamps, and total time.

- **Check grade with an answer key**  
  Use **Grading Mode**. Enter your answer, `Enter`, then the correct answer from the key, `Enter`. The app shows Correct/Incorrect and builds your score.

- **Blind exam simulation**  
  Toggle **Blind Grading** (`B`) before starting Grading Mode. No feedback shown during the test — only in the final report.

- **Rapid self-testing**  
  Open the link in any browser. No setup, no accounts, no distractions.

- **Track performance over time**  
  Each session gets a unique ID, date, start/end time, and full log. Open History (`H`) to compare mocks and see where you lose marks.

## Example case

You're solving a 20-question mock from a book. Open the app, press `Enter`, choose **Logging**. Solve Q1, press `1` for A, `Enter`. Timer runs. After 20 questions, press **Finish**. Dashboard shows all answers, timestamps, per-question time, and total time.

Later, grade a test with an answer key. Start a new session, choose **Grading**. For each question: press your answer (`2` for B), `Enter`, then the correct answer (`3` for C), `Enter`. The app shows Correct/Incorrect and updates your score. For multiple answers, press `1`, `3`, `4`, `Enter` for A, C, D.

Open **History** (`H`) anytime to compare this session with previous ones.

## License & Contributions

MIT License — free to use, modify, share, and distribute. Just keep the copyright notice.

Fork / contribute: [https://github.com/S2Sofficial/mcq](https://github.com/S2Sofficial/mcq)  
Suggestions and bug reports welcome.

---

# Keyboard Shortcuts

## Start Screen

| Key | Action |
|-----|--------|
| `1` | Start Logging Mode |
| `2` | Start Grading Mode |
| `B` | Toggle Blind Grading |
| `T` | Toggle Theme |
| `H` | Session History |
| `I` | Import Backup |

## Active Session

| Key | Action |
|-----|--------|
| `1` `2` `3` `4` | Toggle A / B / C / D |
| `Enter` | Commit selection / progress |
| `S` | Skip question |
| `M` | Mark question |
| `7` `8` `9` | Confidence: Low / Med / High |
| `E` | Edit response log |
| `T` | Toggle Theme |
| `Esc` | Pause session |

## Paused

| Key | Action |
|-----|--------|
| `Space` | Resume |
| `E` | Edit response log |
| `F` | Finish session |
| `N` | New session |

## Dashboard

| Key | Action |
|-----|--------|
| `N` | New session |
| `J` | Export session JSON |
| `C` | Export session CSV |
| `H` | Session History |
| `Esc` | Back (from history view) |

## Edit Log Overlay

| Key | Action |
|-----|--------|
| `↑` `↓` | Select row |
| `Home` / `End` | First / last row |
| `1` `2` `3` `4` | Toggle answer / correct answer |
| `Tab` | Switch field (response ↔ key) |
| `R` | Toggle mark |
| `7` `8` `9` | Set confidence |
| `X` | Renumber question |
| `Esc` | Close |

## History Overlay

| Key | Action |
|-----|--------|
| `↑` `↓` | Select session |
| `Enter` | View report |
| `Space` | Pick for compare |
| `C` | Compare picked sessions |
| `D` | Delete session |
| `J` | Export all JSON |
| `U` | Backup all data |
| `Esc` | Close |

## Confirm Dialog

| Key | Action |
|-----|--------|
| `Y` | Yes |
| `N` / `Esc` | No |

## Anywhere

| Key | Action |
|-----|--------|
| `T` | Toggle Theme |
