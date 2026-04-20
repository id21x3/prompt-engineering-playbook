# Usage: Minimal Change Mode (Strict)

## When to Use
- You need a targeted fix in an existing codebase.
- You must preserve the current implementation style and structure.
- The task requires minimal risk and minimal diff.

## How to Attach It to Other Prompts
- Add this prompt as a mandatory constraint block after the main task description.
- Keep domain context separate (requirements, business rules, edge cases).
- If needed, prepend: "Apply Minimal Change Mode (Strict) to all code edits."

## Good vs Bad Usage

### Good
- "Fix the null-check bug in `parseUser()` without refactoring surrounding logic."
- "Add support for one new enum value with localized code changes only."

### Bad
- "Refactor this module for readability while fixing one typo."
- "Rewrite the function in your preferred style and optimize it."
