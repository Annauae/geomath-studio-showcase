# FAQ

[中文](FAQ.md) | **English**

## 1) What is it best for?

- **Teaching & live demos**: explain by dragging—students can see how quantities and shapes change together
- **Practice & self-check**: build helper diagrams quickly and validate intuition
- **Explainer content**: interactive diagrams instead of static screenshots

## 2) Will AI “finish the whole diagram in one click”?

AI is closer to a drawing assistant: it returns an executable **sequence of drawing steps** (create points, connect lines, take intersections, add labels/measurements…).

This makes the process inspectable—you can verify each step and adjust anytime.

## 3) Why does a dragged point snap back to a line/circle/curve?

Because the point is constrained “on an object”. While dragging, the system projects it back onto that object so the constraint always holds.

That way you can explore invariants without accidentally breaking the construction.

## 4) What objects/operations are supported?

Common geometry objects (points/lines/circles, intersections/midpoints), labels & measurements, plus typical function graphs.

## 5) What if the result isn’t what I want?

- Manually create the key objects first (e.g. the circle or the curve)
- Then let AI fill in the remaining steps (points on objects, connections, labels/measurements)

The closer the starting setup is, the more reliable AI completion becomes.

