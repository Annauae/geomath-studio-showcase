# Features & workflows

[中文](FEATURES.md) | **English**

GeoMath Studio is a “drag, constrain, and replay” math canvas: build geometry, plot functions, and use AI to turn a problem statement into an interactive diagram.

## Dynamic geometry (drag → instant recompute)

- **Core objects**: points, lines (segments/lines/rays), circles
- **Derived objects**: intersections, midpoints (stay linked as you drag)
- **Explain & verify**: labels, distance/angle measurements
- **What you’ll feel**:
  - Drag any point and everything updates immediately
  - Relationships are preserved by construction, not by “hand-drawing”

## Function graphs (curves as first-class objects)

- **Supported**: common explicit / implicit graphs
- **Typical flow**:
  - Plot a curve
  - Place a point near it and make the point “stick to the curve”
  - Drag the point— it won’t leave the curve

## Constraints & snapping (points stay valid)

If a point is constrained “on an object” (line/segment/circle/curve), dragging it will project it back onto that object so the constraint always holds.

This is great for exploration: you can drag freely to look for invariants without breaking the diagram.

## AI drawing assistant (turn a sentence into steps)

- **You provide**: a short description of the target diagram (text / screenshot scenarios)
- **It returns**: an executable sequence of drawing steps (create objects, pick points on objects, add labels/measurements, plot graphs)
- **You get**:
  - Faster starting point (from “reading” to “having a diagram”)
  - A replayable process (step-by-step, editable, extendable)

