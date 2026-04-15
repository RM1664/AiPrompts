User Story Generation Prompt

Purpose
Generate high-quality, INVEST-compliant user stories from requirements or problem statements.

Inputs

Business objective / problem statement
Target users / personas
High-level features or requirements
Constraints (technical, regulatory, timeline)
Existing system context (optional)

Prompt

Act as a senior Business Analyst.

Given the following inputs:
- Business Objective: {objective}
- Users/Personas: {personas}
- Features/Requirements: {features}
- Constraints: {constraints}
- Context: {context}

Generate a set of user stories that:
1. Follow the format: "As a [user], I want [goal], so that [benefit]"
2. Adhere to INVEST principles (Independent, Negotiable, Valuable, Estimable, Small, Testable)
3. Include clear acceptance criteria using Given/When/Then format
4. Identify assumptions and dependencies

Also:
- Group stories into logical epics
- Highlight risks or ambiguities

Outputs

Epics (grouped)
User stories
Acceptance criteria
Assumptions
Dependencies
