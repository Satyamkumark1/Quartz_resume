## Application Building Context

Read the following files in order before implementing or making any architectural decision:

1. `context/project-overview.md`
2. `context/architecture-overview.md`
3. `context/architecture-invariants.md`
4. `context/code-standards-general.md`
5. `context/code-standards-nextjs-styling.md`
6. `context/ui-context.md`
7. `context/ai-workflow-rules.md`
8. `context/progress-tracker.md`

Then read the relevant spec file(s) for the unit you are working on.

Update `context/progress-tracker.md` after each meaningful implementation change.

If implementation changes the architecture, scope, or standards documented in the context files, update the relevant file before continuing.

**Testing after each spec file:** Each spec file ends with a “Testing” section. Run those tests and ensure they pass before moving to the next file.