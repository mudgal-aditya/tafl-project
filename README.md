# CFG Simplifier Web App

This project is a simple web-based tool built to help understand how context-free grammars (CFGs) are simplified step by step.

Instead of just giving the final result, the app focuses on showing the transformation process clearly so that the logic behind each step is visible.

---

## What this project does

The application takes a grammar as input and applies three core simplification steps:

1. **Remove Useless Symbols**
   - Eliminates symbols that never produce terminal strings
   - Removes symbols that are not reachable from the start symbol

2. **Remove Null (ε) Productions**
   - Identifies nullable variables
   - Rewrites productions by considering all possible combinations

3. **Remove Unit Productions**
   - Removes rules like `A → B`
   - Replaces them with actual productions of the referenced variable

Each step runs independently so you can observe how the grammar changes at every stage.

---
