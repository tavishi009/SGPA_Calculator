# SGPA Calculator — BIT Mesra

Built this because I was tired of calculating my SGPA manually every semester. Just enter your subjects, credits, and grades — it does the math instantly.

---

## How to use it

Open `sgpa_calculator.html` in your browser. It comes pre-filled with sample subjects so you can see how it works. Clear them out, add your own, and hit **Calculate SGPA**.

---

## What it does

- Add/remove subjects dynamically
- Select your grade (O, A+, A, B, C, D, E, F) and it auto-fills the grade point
- Calculates SGPA live using BIT Mesra's formula
- Highlights failed subjects in red
- Shows a performance badge (Outstanding, Excellent, Good, etc.)

---

## Formula used

```
SGPA = Sum of (Credits × Grade Point) ÷ Total Credits
```

---

## Grade scale (BIT Mesra)

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

