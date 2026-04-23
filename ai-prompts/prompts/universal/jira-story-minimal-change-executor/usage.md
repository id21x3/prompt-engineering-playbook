# Usage: Jira Story Executor (.NET, Minimal Change)

## When to Use
- You want an IDE agent (Windsurf/Codex-like) to implement a Jira story end-to-end.
- The repository is large and requires structured investigation before coding.
- You need strict minimal-diff behavior for safer delivery.

## How to Use
1. Copy `prompt_strict.md` into your agent chat.
2. Paste the Jira issue text into the `JIRA_ISSUE` block.
3. Run.

## Optional First-Line Prefix
Use this short prefix before the prompt when needed:

`Apply Minimal Change Mode (Strict) and follow the mandatory workflow exactly.`

## Expected Outcome
- Agent creates a ticket-derived branch first.
- Agent investigates relevant code paths before edits.
- Agent proposes a clear implementation plan mapped to acceptance criteria.
- Agent performs localized code changes and reports validation results.
