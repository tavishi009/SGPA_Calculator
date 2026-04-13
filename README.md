# SGPA Calculator

Built this because I was tired of calculating my SGPA manually every semester. Just enter the subjects, credits, and grades — it does the math instantly.

---

## How to use it

Open `index.html` in your browser. It starts with one empty subject row so you can directly enter your own subjects, then hit **Calculate SGPA**.

---

## What it does
- Add/remove subjects dynamically
- Select your grade (O, A+, A, B, C, D, E, F) and it auto-fills the grade point
- Highlights failed subjects in red
- Shows a performance badge (Outstanding, Excellent, Good, etc.)

---

## Formula used

```
SGPA = Sum of (Credits × Grade Point) ÷ Total Credits
```

---

## Grade scale 

| Grade | Marks | Grade Point |
|-------|-------|-------------|
| O     | 95%+  | 10 |
| A+    | 90%+  | 10 |
| A     | 80–90%| 9  |
| B     | 70–80%| 8  |
| C     | 60–70%| 7  |
| D     | 50–60%| 6  |
| E     | 40–50%| 5  |
| F     | <40%  | 0  |

---

## Built with

Plain HTML, CSS, and JavaScript. No frameworks, no dependencies.

---

