# 3陸特 Reviewer

A study app for the **第三級陸上特殊無線技士** (3rd Class Land Special Radio Operator) exam in Japan.

## Features

- **132 practice questions**, split into 無線工学 (technical, 60) and 法規 (radio law, 72), with questions and answer choices shuffled
- **Mock exams scored like the real exam:** 12 questions per subject at 5 points each (60 total), pass mark 40 per subject; the exam is passed when both subjects pass
- **Instant feedback:** the correct answer plus Japanese and English explanations
- **English translation** of every question and answer choice
- **Hover popups** showing furigana and English meanings for kanji, in questions, choices and explanations
- **Vocabulary list** of 544 words in three categories (Technical 137, Law 167, General 240), with search and a self-quiz mode

## Running it

It's a static site with no build step. Open `index.html` in a browser, or serve the folder with any static host (GitHub Pages serves it as-is).

Progress is saved in your browser's local storage.

## Sources

- Questions, answer keys, Japanese explanations and diagrams: [そうだったのか！わかる無線通信技術](https://funfun-wireless-communication.com/category/3riku_exercise/) (past exams from R3.6, R3.10 and R4.2, and practice sets No.1–3)
- Exam format and passing standards: [日本無線協会 試験科目・合格基準等](https://www.nichimu.or.jp/kshiken/shiryou/index.html)

English translations, English explanations for questions without one, and the vocabulary lists were added for this reviewer. They are study aids, not official wording.
