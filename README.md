# Big-O Guesser

A timed game to test how well you know time complexity. Read a Python code snippet, guess its worst-case Big-O, and get explained right after if you're wrong.

Inspired by [TeXnique](https://github.com/akshayravikumar/TeXnique).

## How to play

1. Pick **Timed Game** (3 minutes on the clock) or **Zen Mode** (no time limit).
2. For each snippet, choose the correct complexity from four options.
3. Build a streak for bonus points.
4. At the end, review every question you got wrong with a short explanation of the correct answer.

## Coverage

100 snippets spanning `O(1)`, `O(log n)`, `O(n)`, `O(n log n)`, `O(n²)`, `O(n³)`, `O(2ⁿ)`, and `O(n!)`, including a handful of deliberately tricky ones (loops that look worse than they are, and vice versa).

| Complexity | Count |
|---|---|
| O(n) | 28 |
| O(n²) | 17 |
| O(1) | 13 |
| O(log n) | 12 |
| O(n log n) | 11 |
| O(2ⁿ) | 8 |
| O(n³) | 7 |
| O(n!) | 4 |

## Running it

No build step, no dependencies. Just open `index.html` in a browser.
