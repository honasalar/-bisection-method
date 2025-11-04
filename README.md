README.md (Improved)
📌 Bisection Method — Numerical Analysis Extra Work

This project demonstrates the Bisection Method for finding roots of nonlinear equations.
It was completed as extra work for our Numerical Analysis course.

✨ What is the Bisection Method?

The Bisection Method is a numerical technique used to approximate the root of a continuous function.
It works by repeatedly cutting an interval in half and checking which side of the midpoint contains a root.

For the method to work:

The function must be continuous

The values at the interval endpoints must have opposite signs
(meaning: 
𝑓
(
𝑎
)
⋅
𝑓
(
𝑏
)
<
0
f(a)⋅f(b)<0)

This ensures there is at least one root between a and b.

📐 Equation Used
𝑓
(
𝑥
)
=
𝑥
3
−
2
𝑥
−
5
f(x)=x
3
−2x−5

This equation has a real root between 1 and 3.

🔁 Method Steps

Choose interval 
[
𝑎
,
𝑏
]
[a,b] such that 
𝑓
(
𝑎
)
⋅
𝑓
(
𝑏
)
<
0
f(a)⋅f(b)<0

Compute midpoint:

𝑚
=
𝑎
+
𝑏
2
m=
2
a+b
	​


Check the sign of 
𝑓
(
𝑚
)
f(m)

Replace either a or b based on sign

Repeat until the result is accurate enough

📊 Google Sheet Implementation

The calculations were implemented in Google Sheets to show each iteration step-by-step:

📎 Sheet link: https://docs.google.com/spreadsheets/d/1H97BeV_K5wUNrh4Zn6ALq3rsQpocfjzKyoVZcZaWyZQ/edit?usp=sharing

🐍 Python Code

The Bisection Method was also implemented using Python in Google Colab.

📎 Colab Notebook: https://colab.research.google.com/drive/1GwqOH5FuZk5-J-9AhMn8jAm_ahj7qpCo?usp=sharing

💾 Files Included

bisection.ipynb — Python implementation

Google Sheet link in README

Explanation of the method

✅ Result

The Bisection Method converged to a root approximately near:
x≈2.09


By:Hona salar mahmmud
stage:2 
Topic:Numerical Analysis
