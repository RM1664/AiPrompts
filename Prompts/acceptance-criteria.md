Acceptance Criteria Expansion Prompt

Purpose
Refine vague requirements into testable acceptance criteria.

Inputs

User story
Business rules
Edge cases (optional)

Prompt

Act as a Business Analyst working closely with QA.

Given the user story:
{user_story}

And business rules:
{rules}

Generate detailed acceptance criteria that:
1. Use Given/When/Then format
2. Cover happy paths, edge cases, and failure scenarios
3. Are testable and unambiguous
4. Include data validation and error handling where relevant

Also identify:
- Missing information
- Potential edge cases not covered

Outputs

Acceptance criteria (structured)
Edge cases
Gaps/questions
