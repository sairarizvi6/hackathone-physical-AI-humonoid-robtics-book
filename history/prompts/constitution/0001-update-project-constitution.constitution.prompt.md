
## Prompt

Update the project constitution to define the core principles, boundaries, governance, and long-term direction for the “Physical AI & Humanoid Robotics Textbook Project”.

This constitution governs:
- How specs are created
- How chapters are structured
- How the RAG backend integrates
- How multilingual support (including Urdu) is added
- How bonus features (auth, personalization) evolve
- How the Docusaurus + Spec-Kit Plus project is maintained

## Purpose
Create a stable, long-term foundation that ensures:
- Consistency across all chapters
- Clean architecture in folder + file structure
- High-quality technical writing standards
- Smooth GitHub Pages publishing
- Proper separation of concerns between specs, chapters, assets, and backend

## Scope
The constitution applies to:
- Docusaurus v3 documentation site
- All textbook chapters
- All “specs” created using /sp.specify
- All workflows including deployment, RAG backend, and bonus features
- Versioning, labels, and linking rules

## What This Constitution MUST Define
1. **Core principles**
   - Precision, modularity, extendability, version control hygiene
2. **Governance rules**
   - How new specs are approved
   - Version numbering (e.g., v0.1.0 → v0.2.0)
   - Naming conventions for files and specs
3. **Information architecture**
   - Folder rules for:
     - `/docs/chapters/*`
     - `/specs/*`
     - `/assets/*`
     - `/RAG-backend/*`
     - `/src/pages/*` (bonus features)
4. **Development constraints**
   - Docusaurus v3 only
   - GitHub Pages deploy workflow required
   - All chapters in Markdown only
   - No chapter content inside specs
5. **Prohibited**
   - Writing chapter content inside structure specs
   - Creating non-standard folder names
   - Mixing Urdu + English inside same file
   - Adding features without a spec

## Success Criteria
A valid constitution update must:
- Establish clear project-wide standards
- Support long-term scalability
- Prevent ambiguity in chapter creation
- Align with the file structure already created
- Be compatible with automatisation and spec-driven workflows

## Not Building Here
- No chapter content
- No feature implementation
- No RAG backend logic
- No UI/UX design
- No code-level writing
- No examples or tutorials

## Labels
labels: ["constitution", "governance", "project-rules"]

## Links
spec: specs/0-project-constitution/spec.md
ticket: null
adr: null
pr: null

## Response snapshot

The project constitution has been updated to version `0.4.0`. This is a MINOR version bump due to significant changes in core principles, governance, information architecture, development constraints, and prohibited items.

The following templates require manual follow-up updates to align with the new constitution:
- `.specify/templates/plan-template.md`
- `.specify/templates/spec-template.md`
- `.specify/templates/tasks-template.md`
- `.specify/templates/commands/*.md`

Suggested commit message: `docs: amend constitution to v0.4.0 (project principles + governance + architecture update)`

## Outcome

- ✅ Impact: Project constitution updated, establishing core principles, governance, information architecture, development constraints, and prohibited items for the "Physical AI & Humanoid Robotics Textbook Project".
- 🧪 Tests: No tests were run for this documentation update.
- 📁 Files: One file was modified: `.specify/memory/constitution.md`
- 🔁 Next prompts: Review templates for consistency with the updated constitution.
- 🧠 Reflection: Successfully updated the constitution based on user input, ensuring all defined aspects are covered.

## Evaluation notes (flywheel)

- Failure modes observed: None.
- Graders run and results (PASS/FAIL): N/A
- Prompt variant (if applicable): N/A
- Next experiment (smallest change to try): N/A