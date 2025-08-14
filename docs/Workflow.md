# SDLC Workflow

1. Feed vision to ProductManager.md prompt in Claude → Save output to docs/pm-output.md.
2. PM output → Architect.md prompt → docs/arch-output.md.
3. Architect output → Engineer.md prompt → Generate code in backend/frontend folders; commit to Git.
4. Engineer output → QATester.md prompt → docs/qa-output.md; fix bugs in Cursor.
5. Post-race: Upload results to DB/UI, run Reviewer.md → Iterate back to PM.
Use Claude for generations, Cursor for edits/reviews on your machine. Git push triggers CI/CD.x`