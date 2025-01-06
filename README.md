# Tailwind CSS Gradient Bug

This repository demonstrates a common bug in Tailwind CSS related to gradients.  The issue arises from an incorrect usage of the gradient classes, leading to unexpected visual results.

## Bug Description

The original code uses `from-blue-500` and `to-purple-500` without specifying any intermediary colors.  This results in a gradient that might not be what's intended.  The correct way to define a smooth gradient involves using the `via` class to specify intermediate colors or transitions.

## Solution

The bug is fixed by adding the `via` class to the gradient definition. This makes the transition between the start and end color smoother.  See the corrected code in `bugSolution.js`.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js` and note the incorrect gradient implementation.
3. Open `bugSolution.js` to see the corrected code.
4. Compare the output.  You'll see a smoother, more predictable gradient with the solution.