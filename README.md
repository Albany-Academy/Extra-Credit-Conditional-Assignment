# Extra-Credit-Conditional-Assignment
# 🎩 Lab Extension: The Ultimate Sorting Quiz

**Time Allotted:** 45 Minutes  
**Pairs:** 2-Person Collaboration  
**Concepts Covered:** `Scanner`, Variables & Operators, Compound Conditionals (`if` / `else if` / `else`), String methods (`equalsIgnoreCase`)

---

## 📋 Overview
Your task is to build an interactive, multiple-choice classification quiz (e.g., Hogwarts House, Superhero Archetype, Gaming Class, or Faction). Your program will ask the user 4–5 questions, tally their points across distinct personality traits, and use conditional logic to assign them their final result!

---

## 🛠️ Technical Requirements

### 1. Setup & Variables
* Initialize **4 category score variables** (e.g., `int gryffindor = 0; int ravenclaw = 0; ...`).
* Set up a `Scanner` to read user responses (String or integer choices).

### 2. Quiz Questions (At least 4 Questions)
* Each question must display 3–4 multiple-choice options (A, B, C, D).
* Evaluate the user's answer using `if`/`else if` conditionals (use `equalsIgnoreCase` for letter inputs).
* Increment the appropriate trait counter based on their selection.

### 3. Final Evaluation (Conditional Logic)
* After the final question, compare the score totals using conditional statements (`if` / `else if` / `else`) with comparison operators (`>`, `>=`).
* Determine which score is highest and print a custom result summary for that character type.

---

## ⭐ Bonus Challenges (Finish Early?)
1. **Tie-Breaker Logic:** Add an `if` condition to handle a tie between two top categories (e.g., print a special "Hybrid Class" result!).
2. **Input Validation:** Add an `else` branch to questions so if the user types an invalid choice (like "Z"), you print a warning message and default their score point to 0.

---

## 🧪 Pre-Submission Test Cases
Add a comment block at the top of your Java file showing **two test runs**:

```java
/*
 * TEST CASE 1:
 * Inputs: A, B, A, C
 * Expected Output: Gryffindor
 * Actual Output: Gryffindor (PASSED)
 * 
 * TEST CASE 2:
 * Inputs: C, C, D, C
 * Expected Output: Slytherin
 * Actual Output: Slytherin (PASSED)
 */
