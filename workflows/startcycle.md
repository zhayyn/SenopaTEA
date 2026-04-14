# Sequence Trigger: Start Cycle

## Command Definition
When the user types `/startcycle <idea>`, execute the following pipeline using definitions from `.agents/agents.md`.

## Execution Pipeline
1. **Phase 1 (Design)**: Shift context to `@pm` -> Execute `skills/write_specs.md` using `<idea>`. 
   *(Wait for explicit approval. Loop revisions if needed until approved)*.
2. **Phase 2 (Build)**: Shift context to `@engineer` -> Execute `skills/generate_code.md`.
3. **Phase 3 (Test)**: Shift context to `@qa` -> Execute `skills/audit_code.md`.
4. **Phase 4 (Deploy)**: Shift context to `@devops` -> Execute `skills/deploy_app.md`.
