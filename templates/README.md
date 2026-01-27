# Architectural Prompt Template System  
## Template Version Documentation

This repository records the architectural prompt template system developed for façade and floorplan generation from historical reference imagery.

The system evolved through iterative refinement, reverse-prompting, regulation-based testing, and architectural verification.

---

## Template Version Index

- template_v1_Interior (Baseline floorplan generation)
- template_v1_Exterior (Baseline façade generation)
- template_v2_Exterior (Geometry-locked façade control)
- template_v3_Exterior (Descriptive architectural fidelity control)
- template_v4_Exterior (High-detail architectural fidelity control)
- template_v5_Interior (Regulation-based derived interior generation)

---

## Workflow Summary

1. Parallel interior + exterior generation (Template v1)
2. Exterior façade prioritised and geometry-locked (Template v2)
3. Descriptive architectural fidelity control (Template v3–v4)
4. Interior derived directly from façade rhythm, with regulation-based architectural testing (BS8888, IS0 19650) (Template v5)
---


