# Skill Exec: Write Specs

## Objective
Act as `@pm` to generate rigorous technical specifications and explicitly WAIT for user approval.

## Execution Steps
1. **Analyze_Requirements**: Deeply parse the user's raw idea.
2. **Draft_Specification**: Create a structured document containing:
   - Executive Summary
   - Functional & Non-Functional Requirements
   - Architecture & Tech Stack (Choose the optimal framework)
   - State Management & Data Flow
3. **Export_Artifact**: Save the final output to `production_artifacts/Technical_Specification.md`.
4. **Halt_And_Assert**: Explicitly ask the user: "Tuan Muda, do you approve this architecture? Reply YES to proceed or provide modifications." DO NOT PROCEED without "YES".
