---
name: Bug report
about: Something behaves incorrectly
labels: Bug
---
<!--
Writing rules (for the author, AI or human; comments are not rendered):
- Two audiences: Summary, Impact and Expected vs actual are for the human approver. The collapsed section is for the implementer (usually an AI).
- State each fact once. Do not repeat the steps in the summary or the causes in prose.
- Summary: max 3 sentences, plain language, no file paths or type names.
- Steps must be reproducible from a clean install or a named test solution. Include exact input values.
- Only state a root cause you have verified in code. Otherwise leave it out, and list suspects under "Suspected area".
- Omit any section or field with nothing to say. Never write "N/A".
- No greetings or sign-off.
-->

## Summary
<!-- What breaks, where, and under which condition. -->

## Impact
<!-- Who is affected and how badly: data loss, blocked workflow, workaround exists, cosmetic. One or two lines. -->

## Expected vs actual
- **Expected:**
- **Actual:**

<details>
<summary>Technical details</summary>

**Version:**
**Regression:** <!-- yes, last working version X / no / unknown -->
**Feature flag / config:**
**Environment:** <!-- only if relevant: DB, hosting, browser, integration -->

**Steps to reproduce**
1.

**Error output**
<!-- Exact exception, stack trace (trimmed to the relevant frames) or log line in a code block. -->

**Root cause**
<!-- Verified only. `file:line` — what it does, why that breaks it. One bullet per cause. -->
-

**Suspected area**
<!-- Unverified leads, one line each. -->
-

**Proposed fix**
<!-- Numbered to match the causes. -->
1.

**Workaround**
-

</details>
