# MCQ Response Tracker — README

A tiny, keyboard-first tool to record MCQ answers and optionally grade them.  
No questions, no explanations — just fast answer entry and a clean log.

**Live app:** [https://s2sofficial.github.io/mcq/](https://s2sofficial.github.io/mcq/)

## Features

- **Keyboard only:** Press `1` `2` `3` `4` for A B C D. Press `Enter` to commit. No mouse needed.
- **Two modes:**
  - **Logging** – records answers with date and exact time.
  - **Grading** – enter your answer, then the correct answer, and get instant Correct / Incorrect.
- **Single & multiple answers:** Toggle keys. `1 → 3 → 4` selects A+C+D. Press again to deselect.
- **Physical feel:** Four huge buttons that depress on press, with green/red LED glow for grading.
- **Session timer:** Starts, pauses, resumes. Paused time is not counted.
- **Auto-save:** Saves locally. Refresh or close the tab — session is restored.
- **End dashboard:** Total questions, correct/incorrect, score, accuracy, duration, and full serial-numbered log with timestamps.

## How to use it

- **Mock test from a book**  
  Use **Logging Mode**. Solve from the book, press keys to record each answer. Timer runs like an exam timer. Finish to see all answers, timestamps, and total time.

- **Check grade with an answer key**  
  Use **Grading Mode**. Enter your answer, `Enter`, then the correct answer from the key, `Enter`. The app shows Correct/Incorrect and builds your score.

- **Rapid self-testing**  
  Open the link in any browser. No setup, no accounts, no distractions.

- **Track performance over time**  
  Each session gets a unique ID, date, start/end time, and full log. Compare mocks and see where you lose marks.

## Example case

You're solving a 20-question mock from a book. Open the app, press `Enter`, choose **Logging**. Solve Q1, press `1` for A, `Enter`. Timer runs. After 20 questions, press **Finish**. Dashboard shows all answers, timestamps, and total time.

Later, grade a test with an answer key. Start a new session, choose **Grading**. For each question: press your answer (`2` for B), `Enter`, then the correct answer (`3` for C), `Enter`. The app shows Correct/Incorrect and updates your score. For multiple answers, press `1`, `3`, `4`, `Enter` for A, C, D.

## License & Contributions

MIT License — free to use, modify, share, download and distribute

Fork / contribute: [https://github.com/S2Sofficial/mcq](https://github.com/S2Sofficial/mcq)  
Suggestions and bug reports welcome.
