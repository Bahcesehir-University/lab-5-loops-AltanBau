# Lab: Loops in C++ (while, for, do-while)

## Course Information

| Field | Detail |
|-------|--------|
| **Course** | CMP1001 – Introduction to Programming (C++) |
| **Lab Topic** | Loops: `while`, `for`, `do-while` |
| **Duration** | 60 minutes |
| **Language** | C++ |
| **File** | `MainProgram.cpp` (single file) |

---

## Objective

This lab introduces the three fundamental loop structures in C++: **while**, **for**, and **do-while**. By the end of this lab, you will be able to choose the right loop for a given problem, write loops that process user input, perform calculations, and build simple interactive programs.

---

## Prerequisites

Before starting this lab, you should be comfortable with:

- Declaring and using variables (`int`, `double`, `string`)
- Basic input/output (`cin`, `cout`)
- Simple conditional statements (`if`, `else if`, `else`)
- Compiling and running a C++ program from the terminal

---

## What You Will Learn

- How to write and use a **while** loop for condition-based repetition
- How to write and use a **for** loop for counted repetition
- How to write and use a **do-while** loop for input validation
- How to use **nested loops** to produce patterns
- How to build a **menu-driven program** with a loop
- How to choose the right loop type for a given problem

---

## Lab Structure

The lab is divided into four progressive sections:

### Section 1 — Warm-Up (5–10 min)
Quick review of `cin`/`cout`, variables, and arithmetic. This gets you ready for the main exercises.

### Section 2 — Core Concepts (10–15 min)
Short explanations of `while`, `for`, and `do-while` syntax with examples, followed by one small exercise for each loop type.

### Section 3 — Guided Exercises (25–30 min)
Six hands-on exercises with increasing difficulty: countdown timers, sum calculators, multiplication tables, factorials, a guessing game, and pattern printing with nested loops.

### Section 4 — Challenge (10 min)
Two harder problems that combine multiple concepts: a digit counter using integer division and a menu-driven calculator. These are slightly open-ended and designed to stretch your thinking.

---

## How to Compile & Run

Open a terminal in the directory containing `MainProgram.cpp` and run:

```bash
g++ MainProgram.cpp -o lab
./lab
```

If you are on Windows with MinGW:

```bash
g++ MainProgram.cpp -o lab.exe
lab.exe
```

Compile often as you work through the exercises. It is much easier to fix one error at a time than to debug everything at the end.

---

## Submission Instructions

1. Complete all `// TODO:` sections in `MainProgram.cpp`.
2. Make sure your code **compiles without errors**.
3. Test your program — run it and verify the output for each exercise.
4. Commit and push your changes:

```bash
git add MainProgram.cpp
git commit -m "Completed Loops lab"
git push
```

5. Verify your submission on GitHub before the deadline.

---

## Grading Criteria

| Criteria | Weight | Description |
|----------|--------|-------------|
| **Correctness** | 50% | All exercises produce the expected output for various inputs. |
| **Code Quality** | 20% | Clean formatting, meaningful variable names, no unnecessary code. |
| **Completion** | 20% | All TODO sections in Sections 1–3 are filled in. |
| **Challenge** | 10% | Section 4 exercises are attempted and reasonably implemented. |

**Total: 100%**

---

## Estimated Time Breakdown

| Section | Time |
|---------|------|
| Section 1 — Warm-Up | 5–10 min |
| Section 2 — Core Concepts | 10–15 min |
| Section 3 — Guided Exercises | 25–30 min |
| Section 4 — Challenge | 10 min |
| **Total** | **~60 min** |

---

## Tips for Students

- **Compile after every exercise.** Don't wait until the end — small, frequent compilations make debugging much easier.
- **Watch your loop conditions.** Off-by-one errors (e.g., `<` vs `<=`) are the most common loop bug. Trace through your loop on paper if the output looks wrong.
- **Use `cout` for debugging.** If a loop is not behaving as expected, add a temporary `cout` inside the loop to print the loop variable at each step.
- **`while` vs `for` vs `do-while`:**
  - Use **`for`** when you know how many times to repeat.
  - Use **`while`** when you repeat based on a condition.
  - Use **`do-while`** when the loop body must run at least once (especially for input validation).
- **Don't be afraid to restart an exercise.** If your code gets messy, it's often faster to delete and rewrite than to patch broken logic.
- **The challenge section is worth attempting** even if you don't finish it. Partial solutions still earn marks and help you learn.
