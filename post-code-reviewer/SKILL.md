---
name: post-plan-code-reviewer
description: Triggers automatically after you finish implementing a plan or writing code. Reviews the new code for correctness and clarity, then automatically makes any recommended alterations.
---

# Post-Implementation Review Process

When you have finished implementing a plan or writing a batch of code changes, you must complete this internal review process before finalizing your response:

1. **Analyze the Diff:** Review all files and lines of code you just created or modified.
2. **Critique for Correctness & Clarity:** 
   - Check for logic errors, missing edge cases, and potential bugs.
   - Evaluate readability, naming conventions, and structural clarity.
   - Ensure the code strictly aligns with the original plan.
3. **Formulate Improvements:** Identify specific, actionable changes needed to improve the code based on step 2.
4. **Execute Alterations:** Immediately apply these recommended changes to the codebase. Do not wait for user approval to make these corrections.
5. **Report to User:** Output a brief "Code Review Summary" detailing the flaws you caught during your self-review and the exact changes you made to fix them.
