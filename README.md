# Welcome to the DynamicWeb Community Hub

Here you can help shape the future of DynamicWeb. Go to the **Issues** tab to report bugs or suggest new functionality for DynamicWeb or Swift.

## Choosing a template
New issues use one of two templates:

- **Bug report**: something behaves incorrectly.
- **Feature request**: suggest a change or a new capability.

Pick the one that fits, fill in the sections that apply, and delete any section you have nothing to write in.

## Before submitting
Check the [DynamicWeb documentation](https://doc.dynamicweb.dev) to see whether the functionality already exists.

Search the **Issues** tab to see whether someone has already reported the bug or suggested the idea. If they have, add a 👍 to that issue instead of opening a new one.

## Keep it short
Keep reports short and to the point. A few clear sentences get looked at faster than a long write-up. The summary sections in the templates are for the person deciding what to do with the issue. They should be readable in under a minute.

## Using AI to write reports
You are welcome to use AI tools to help write a report. The templates are written so that both people and AI can fill them in. However:

- **You are responsible for what you post.** Read the whole report before submitting it, and make sure you understand it and agree with it.
- **Check the facts.** Only include steps, error messages and root causes that you have confirmed. AI tools often invent file names, settings and explanations that sound plausible but are wrong.
- **Cut the padding.** Remove repetition, filler and generic advice. If the AI wrote five paragraphs, the issue probably fits in five lines.

Reports that are long, unverified or clearly unread by their author may be closed without review.

## Up-voting
If you see a bug or feature request that matters to you, upvote it with the 👍 reaction on the issue description. We use upvotes to decide what to look into and what to add to the backlog.

## How to write a report with AI
1. **Give the AI the template.** Point it at the raw template file, or paste the template in, so that it follows the structure and the writing rules at the top of the file:
   - Bug report: https://raw.githubusercontent.com/dynamicweb/DynamicWeb/main/.github/ISSUE_TEMPLATE/bug_report.md
   - Feature request: https://raw.githubusercontent.com/dynamicweb/DynamicWeb/main/.github/ISSUE_TEMPLATE/feature_request.md
2. **Give it the facts.** Include the DynamicWeb version, what you did, what you expected, what happened, and the exact error message or log line. For a feature request, describe the problem you are trying to solve, not only the solution you have in mind.
3. **Point it at the documentation.** Ask it to check https://doc.dynamicweb.dev so that it does not suggest something that already exists.
4. **Remove anything private.** Do not share customer data, connection strings, API keys, passwords or internal URLs with the AI or in the issue.
5. **Review the result.** Read it through, correct or delete anything you cannot confirm, and shorten it. Then paste it into the matching template on GitHub.

Example prompt:

```text
Write a GitHub bug report for DynamicWeb using this template:
https://raw.githubusercontent.com/dynamicweb/DynamicWeb/main/.github/ISSUE_TEMPLATE/bug_report.md
Follow the writing rules in the template's comment block. Keep it short.
Only include facts from my description below. Do not guess root causes or file names.
If something important is missing, ask me instead of making it up.

My description:
<what happened, version, steps, error message>
```
