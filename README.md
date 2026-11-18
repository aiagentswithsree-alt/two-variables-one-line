# Two Variables, One Line

An interactive, step-through course on linear equations in two variables, based on *Ganita Manjari*, Grade 9, Part II, Chapter 13.

Open `index.html` in any browser. It is a single self-contained file with no build step.

## Lessons

| Module | Lesson | Steps | Covers |
|---|---|---|---|
| 1. One Equation | One Bill, Many Answers | 9 | Writing the equation, standard form `ax + by + c = 0`, ordered pairs, infinitely many solutions, the graph is a line |
| 1. One Equation | How Steep Is a Line? | 9 | Rise, run and slope; positive, negative, zero and undefined slopes; `y = mx + d`; `m = −a/b` |
| 2. Two Equations | Where Two Lines Meet | 10 | Pairs of equations, substitution, elimination, graphical solution, and the ratio test (unique / none / infinitely many) |

All three lessons follow one story: Radha pays ₹280 for mangoes (₹60/kg) and bananas (₹50/kg). By the end, a second clue (the bag weighed 5 kg) pins her purchase down to 3 kg of mangoes and 2 kg of bananas.

## Using it

- **Next / Back** buttons or the ← → keys move through steps; Space pauses the animation.
- ☰ opens the course menu with progress; ◐ toggles dark mode.
- Each step has its own link, e.g. `index.html#how-steep-is-a-line-3`.
- Progress and theme are saved in the browser's local storage.

## Editing

The course content is the `COURSE` object between `COURSE-DATA:START` and `COURSE-DATA:END` in `index.html`. Each step lists its text, its graph (`plot`: lines, points, rise/run triangle, moving dots) and its metric values.
