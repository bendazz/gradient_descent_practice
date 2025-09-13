# Gradient Descent Practice

Front-end only exercises to practice gradient descent steps using exact fraction arithmetic.

Quick start
-----------

Open `index.html` directly in your browser or use a simple static server.

Using Python (if installed):

```bash
python3 -m http.server 8000
```

Then open:

```
http://localhost:8000/index.html
```

What’s included
---------------

- `index.html`: Three independent questions.
	- Question 1: compute one gradient descent step, $x_1 = x_0 - \eta\, f'(x_0)$.
	- Question 2: compute two steps from $x_0$, i.e., $x_1 = x_0 - \eta\, f'(x_0)$ and $x_2 = x_1 - \eta\, f'(x_1)$.
	- Question 3: compute three steps from $x_0$ to $x_3$.
	- All math is kept as exact fractions and rendered via MathJax (TeX).

Notes
-----

- Students solve offline; expand the worked solutions to check the steps and final answers.
- Math rendering uses MathJax from a CDN. An internet connection is required for TeX rendering. If offline, the page still works but formulas will render as plain text.
