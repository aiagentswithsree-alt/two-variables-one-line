# Two Variables, One Line

An interactive, step-through course on linear equations in two variables, based on *Ganita Manjari*, Grade 9, Part II, Chapter 13.

Open `index.html` in any browser. It is a single self-contained file with no build step.

## Lessons

| Module | Lesson | Steps | Covers |
|---|---|---|---|
| 1. One Equation | One Bill, Many Answers | 9 | Writing the equation, standard form `ax + by + c = 0`, ordered pairs, infinitely many solutions, the graph is a line |
| 1. One Equation | How Steep Is a Line? | 9 | Rise, run and slope; positive, negative, zero and undefined slopes; `y = mx + d`; `m = −a/b` |
| 2. Two Equations | Where Two Lines Meet | 10 | Pairs of equations, substitution, elimination, graphical solution, and the ratio test (unique / none / infinitely many) |
| 3. Exam Practice | Exercise 13.1 · Writing equations | 5 | Every question, solved line by line |
| 3. Exam Practice | Exercise 13.2 · Solutions and graphs | 13 | Every question, solved line by line |
| 3. Exam Practice | Exercise 13.3 · Slope | 8 | Every question, solved line by line |
| 3. Exam Practice | Exercise 13.4 · Framing pairs | 4 | Every question, solved line by line |
| 3. Exam Practice | Exercise 13.5 · Word problems (Q1) | 11 | All ten word problems, solved line by line |
| 3. Exam Practice | Exercise 13.5 · Graphs, ratios and more (Q2–Q9) | 12 | Every question, solved line by line |

All three lessons follow one story: Radha pays ₹280 for mangoes (₹60/kg) and bananas (₹50/kg). By the end, a second clue (the bag weighed 5 kg) pins her purchase down to 3 kg of mangoes and 2 kg of bananas.

## Daily practice (the page opens here)

The page opens on **Today**, a 5–7 minute routine that keeps the chapter in long-term memory:

- **Today's review (active recall):** 10 mixed questions from a bank of 52, in six formats: multiple choice, fill in the blank, true/false with a reason, match the following, put in order, and spot the mistake. Eight of them generate fresh numbers every time.
- **Spaced repetition:** each question sits in a box. A right answer moves it up (1 → 3 → 7 → 14 → 30 days); a wrong one sends it back to tomorrow, with a link to the lesson step that explains it.
- **Kumon sheet:** 5 fresh-number problems a day, timed.
- **Brain dump:** once a week, write everything you remember in 60 seconds, then tick it against a checklist.
- **Tracker:** a main streak (one rest day per week), a streak for each technique, a 4-week heatmap, mastery by topic, weak spots, and this week vs last week.

Progress syncs to your claude.ai account when the page is opened from claude.ai. Opened from GitHub Pages or a local file, it is saved in that browser only; use **Copy backup code** to move it.

## Lesson tabs: Before, Understand, After

Every lesson has three tabs:

1. **Before:** a 3-question warm-up. The first time, you guess before learning (guessing first helps the lesson stick); later, it asks what you remember. It never changes the review schedule.
2. **Understand:** the step-by-step lesson.
3. **After:** 5 practice questions on that lesson, picked from what's due, then weak spots, then new questions. These count towards the spaced-repetition schedule.

From the menu, a lesson you haven't finished opens on **Before**; a finished one opens on **After**. Finishing the last step of a lesson leads to After.

## Exam practice

Each exercise question shows **In simple words**, **Given** and **To find**. Pressing **Next line** then reveals the working one line at a time, each with a short reason. After the last line come a **Check** and the final answer to **write in the exam**. Try each step in your notebook before revealing it.

## Using it

- **Next line / Next** button or the ← → keys move through steps; Space pauses the animation.
- ☰ opens the course menu with progress; ◐ toggles dark mode.
- Each step has its own link, e.g. `index.html#how-steep-is-a-line-3`.
- Progress and theme are saved in the browser's local storage.

## Editing

The course content is the `COURSE` object between `COURSE-DATA:START` and `COURSE-DATA:END` in `index.html`. Each step lists its text, its graph (`plot`: lines, points, rise/run triangle, moving dots) and its metric values.

## Reusing the engine for another chapter

`index.html` is a reusable engine plus one course's data. To build a new chapter, copy it and replace only the block between `/* COURSE-DATA:START */` and `/* COURSE-DATA:END */`. That block holds `COURSE` (modules, lessons, steps), the exam-practice lessons, the recall bank (`TOPICS`, `BANK`, `GEN`, `KUMON_GENS`, `DUMPS`) and the course settings (`COURSE.subject`, `COURSE.recallKey`, `COURSE.lessonTopic`). The `interactive-lesson-builder-v2` skill describes the full schema and build steps.
