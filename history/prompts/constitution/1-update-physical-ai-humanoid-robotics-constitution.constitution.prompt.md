
## Prompt

Update the project constitution for the textbook project titled **“Physical AI & Humanoid Robotics.”
The updated constitution must incorporate the following core principles:
1. **Interdisciplinary Collaboration**
   - Emphasize collaboration across AI, robotics, biomechanics, cognitive science, material science, and ethics.
   - Highlight the importance of cross-domain knowledge integration for humanoid robotics.

2. **Ethical AI Development**
   - Include ethical standards that ensure human well-being, autonomy, privacy, fairness, transparency, accountability, and bias detection.
   - Mention societal impact, responsible deployment, and long-term human-centric design.

3. **Robustness & Safety Engineering**
   - Define principles for extreme robustness, reliability, and fault-tolerant systems.
   - Require rigorous testing, validation, simulation, risk assessment, and safety protocols for unpredictable real-world environments.

4. **Human-Robot Interaction (HRI) Design**
   - Focus on intuitive, natural, culturally-aware, and psychologically safe interaction between humans and robots.
   - Emphasize trust, explainability, accessibility, and social alignment.

5. **Continuous Learning & Adaptation**
   - State that systems must be designed to continuously learn, adapt, and evolve through real-world experience, simulation, and multimodal feedback.
   - Require mechanisms for monitoring, updating, and auditing learning processes.

6. **Technical Standards**
   - Add a formal section describing:
     - Simulation frameworks
     - Hardware-software co-design
     - Embodied intelligence testing benchmarks
     - Sensorimotor standards
     - Data, model, and evaluation protocols

7. **Research & Development Workflow**
   - Add guidelines for:
     - Iterative scientific method
     - Hypothesis-driven development
     - Peer review and internal audits
     - Documentation and reproducibility
     - Knowledge transfer across teams

8. **Governance Updates**
   - Revise governance policies to reflect:
     - Ethical oversight
     - Safety & risk review boards
     - Interdisciplinary collaboration structures
     - Transparent decision-making
     - Versioning, change management, and long-term stewardship

labels: ["constitution", "update"]
files:
  - .specify/memory/constitution.md

## Response snapshot

The project constitution has been updated to version 0.2.0. This is a minor version bump due to the addition of several new core principles, a dedicated "Technical Standards" section, and an expanded "Research & Development Workflow" section.

The following templates require manual review and updates to align with the new constitution:
*   .specify/templates/plan-template.md
*   .specify/templates/spec-template.md
*   .specify/templates/tasks-template.md
*   .specify/templates/commands/*.md

A suggested commit message for these changes is:
docs: `update constitution to v0.2.0 with expanded principles and revised governance structure`


## Outcome

- ✅ Impact: Constitution updated to reflect new principles and governance.
- 🧪 Tests: No tests run/added.
- 📁 Files: .specify/memory/constitution.md updated.
- 🔁 Next prompts: Review and update dependent templates.
- 🧠 Reflection: PHR created successfully using agent-native tools after script failure.

## Evaluation notes (flywheel)

- Failure modes observed: `create-phr.sh` script not found.
- Graders run and results (PASS/FAIL): null
- Prompt variant (if applicable): null
- Next experiment (smallest change to try): Ensure `create-phr.sh` script path is correct or fallback mechanism is robust.
