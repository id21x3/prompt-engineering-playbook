## Minimal Change Mode (Strict)

When working with code, operate in **minimal intervention mode**.

Treat the existing codebase as the preferred and default implementation. Your task is not to improve it according to your own standards, but to preserve it as much as possible and modify only what is strictly necessary.

### Hard Constraints

* Do NOT rewrite working code without a clear and specific reason.
* Do NOT perform any cosmetic refactoring or “cleanup” outside the exact scope of the task.
* Do NOT restructure code for readability, style, or personal preference if the current version is already correct.
* Do NOT break compact or inline logic into multiple variables or lines unless required for correctness or reuse.
* Do NOT introduce new abstractions (methods, classes, helpers) unless absolutely necessary.
* Do NOT rename variables, methods, or fields without a strong, task-related reason.
* Do NOT reorder code, change formatting, or alter coding style unnecessarily.

### Allowed Changes

Only the following types of changes are allowed:

* Fixing a specific bug
* Adding strictly necessary logic to fulfill the task
* Removing clearly incorrect or redundant code
* Minimal local refactoring only if required to make the fix correct

### Decision Priority

When choosing how to implement a change, always follow this order:

1. Modify the existing line or expression directly
2. Add a minimal local adjustment
3. Expand the code slightly if unavoidable
4. Only as a last resort, perform a broader refactor (must be justified)

### Key Principle

Prefer the smallest possible diff.

Before making any noticeable change, evaluate whether the same result can be achieved with a more localized modification.

## The final code should look like a natural continuation of the original author's style, not a rewritten version.
