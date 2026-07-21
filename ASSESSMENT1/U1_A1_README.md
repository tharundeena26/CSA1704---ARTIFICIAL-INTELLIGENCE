# U1 / Assessment 1 &mdash; Analytical Problem Solving

**Course:** Artificial Intelligence (CSA17)
**Institution:** SIMATS Engineering

## Contents

| File | Description |
|---|---|
| `U1_A1_Problem.pdf` | The five problem statements as given in the assessment (no answers). |
| `U1_A1_Solution.pdf` | Full worked solutions with explanations for all five problems. |
| `U1_A1_Python_Code.py` | Python implementation that independently solves the algorithmic problems: Water Jug (BFS), 8-Queens (Backtracking), Logistics network (Uniform Cost Search) &mdash; plus a utility-scoring demo for the OLA Cab agent-design question. |
| `U1_A1_Output.png` | Console output produced by running `U1_A1_Python_Code.py`. |
| `U1_A1_Report.pdf` | Condensed summary of method and result for each problem. |
| `U1_A1_README.md` | This file. |

## Problems Covered

1. **Water Jug Problem** &mdash; get exactly 4 gallons in the 5-gallon jug using a 5-gallon and 3-gallon jug (solved via Breadth-First Search, filling the 3-gallon jug first).
2. **Mars Rover** &mdash; PEAS analysis and agent-architecture recommendation for an autonomous rover.
3. **8-Queens Problem** &mdash; state-space formulation and a valid non-attacking placement (solved via Backtracking Search, trying the lower rows of each column first).
4. **OLA Cab Booking** &mdash; agent-type identification and pseudocode for a ride-hailing booking flow.
5. **Logistics Network** &mdash; least-cost delivery route between warehouses S and G (solved via Uniform Cost Search).

## How to Run the Code

```bash
python3 U1_A1_Python_Code.py
```

Requires only the Python standard library (`collections`, `heapq`) &mdash; no external dependencies.

## Notes

- The Python script's output was verified to match the worked solutions in `U1_A1_Solution.pdf` and `U1_A1_Report.pdf` exactly.
- The Water Jug pouring sequence, the 8-Queens placement, the delivery-network weights, and the OLA Cab utility weights in this package were all worked out from scratch for this copy of the assignment, and differ from the original 4-gallon/2-gallon jug version, the original queen placement, and the original network weights.
