# AI-Use Log

- Student: Andrew Haralambous
- Course: SWE 525
- Assignment: Lab 8 - GitHub Issues
- Assistant: OpenAI Codex
- Date of the interactions recorded below: September 24, 2026
- Status: Draft; personal reflections and unconfirmed decisions remain to be completed by the student.

This log was drafted by Codex from the actual conversation at my request. Related follow-up questions are grouped with their original task. Prompts labeled as summaries are faithful summaries rather than exact quotations. AI assistance included explanations, drafting, review, and authorized Git operations. AI checks are identified separately from my own verification.

## Interaction 1 - Repository Setup and Issue Drafting

- Date: September 24, 2026
- Assistant: OpenAI Codex
- Purpose: Get step-by-step guidance for the lab and define observable acceptance criteria.
- Prompt or summary: Guide me through Lab 8 under Week 5, including repository setup, the README, and the GitHub issue.
- Useful output: Suggested repository name and description, initial README content, an issue goal and scope, nine acceptance criteria, and a task checklist.
- Accepted: Used the suggested issue structure and initial documentation guidance.
- Changed: The README title combines the repository name with the descriptive title. Student identification was filled in.
- Rejected: No explicit rejection was recorded in the conversation.
- Decision: Accepted with edits.
- Reason: The structure connects the lab's work to observable verification steps. Any additional personal rationale should be confirmed by the student.
- Related GitHub URL: https://github.com/aharalam/swe325_525-github-ai-practice/issues/1

## Interaction 2 - Review of the Issue and README Commit

- Date: September 24, 2026
- Assistant: OpenAI Codex
- Purpose: Review the issue against the lab requirements and check the README change.
- Prompt or summary: "Can you verify that I did it correctly?" followed by requests to recheck the issue formatting and README commit.
- Useful output: Codex checked the saved issue, confirmed its required content, and identified excessive leading spaces that prevented normal Markdown rendering. It later checked that the README change was on the feature branch.
- Accepted: Followed the formatting correction guidance and requested another review.
- Changed: Adjusted the issue's indentation and line wrapping. The final version retains valid two-space indentation in places.
- Rejected: No explicit rejection was recorded. Questions about tabs and verification-line placement were clarification requests.
- Decision: Accepted; formatting was revised during follow-up.
- Reason: Correct Markdown makes the headings and task checkboxes usable. The feature-branch check confirms where the README change was recorded.
- Verification performed by AI: Read the issue through the GitHub connection and compared main with the feature branch. These checks are not being claimed as independent student verification.
- Related issue: https://github.com/aharalam/swe325_525-github-ai-practice/issues/1
- Related commit: https://github.com/aharalam/swe325_525-github-ai-practice/commit/49e9bbc92de3d5757f34e5c483d6c537fe5919ee

## Interaction 3 - Explanation of GitHub Concepts

- Date: September 24, 2026
- Assistant: OpenAI Codex
- Purpose: Understand repositories, issues, branches, commits, pull requests, and the default branch.
- Prompt or summary: Explain the differences between those GitHub objects and how they connect in this lab. Follow-up requests asked where the explanation belongs and for complete workflow-notes content in a text file.
- Useful output: An explanation of each concept and the sequence from an issue to feature-branch commits, pull-request review, and a merge into main. Codex also drafted workflow-notes.md with known links and clearly marked pending entries.
- Accepted: Used the concept explanations and workflow-notes draft.
- Changed: The saved notes have some spacing changes. No substantive correction to the explanations was recorded.
- Rejected: No explicit rejection was recorded.
- Decision: Accepted.
- Reason: The explanation connects the GitHub concepts to the actual lab workflow. Any additional personal rationale should be confirmed by the student.
- Related GitHub URL: https://github.com/aharalam/swe325_525-github-ai-practice/commit/6e38f28c5cf3fb4c0f56149c829324af024de00d

## Interaction 4 - Correcting an Accidental Commit to Main

- Date: September 24, 2026
- Assistant: OpenAI Codex
- Purpose: Identify and correct where the workflow notes were saved.
- Prompt or summary: I reported that I pushed to main, asked Codex to check, and then asked it to run the local commands to make the correction. I subsequently authorized removing the accidental file from main.
- Useful output: Codex found that the notes were committed directly to main under the name workflow-notes, without the .md extension. It proposed adding the correctly named file to the feature branch and removing the accidental file through a new cleanup commit.
- Accepted: Explicitly authorized the feature-branch correction and the cleanup on main.
- Changed: Execution switched from the GitHub connection, which rejected the write, to local Git commands using my configured Git access.
- Rejected: No explicit rejection of a suggestion was recorded. The GitHub write failed because of integration permissions; that was a tool failure, not a student rejection.
- Decision: Accepted.
- Reason: The correction restores the intended file location and filename while preserving the history of the mistake and cleanup.
- Actions performed by AI: Cloned the repository, created and pushed workflow-notes.md on feature/github-ai-workflow, removed workflow-notes from main in a separate commit, and returned the local checkout to the feature branch.
- Limitation: The original direct-to-main commit remains in history; the correction does not erase that deviation from the lab's requested workflow.
- Corrected file commit: https://github.com/aharalam/swe325_525-github-ai-practice/commit/6e38f28c5cf3fb4c0f56149c829324af024de00d
- Cleanup commit: https://github.com/aharalam/swe325_525-github-ai-practice/commit/54ec6e5aa9eab7366f253b02e7589c84db55e252

## Interaction 5 - Proposed README Improvement

- Date: September 24, 2026
- Assistant: OpenAI Codex
- Purpose: Request a proposed improvement that would help visitors use the README.
- Prompt or summary: After discussing the proposed README-review prompt, I asked Codex to do that next step for me.
- Useful output: Replace the plain documentation list with a clickable workflow-notes.md link, omit the unnecessary README self-reference, and label ai-log.md as coming soon until it exists.
- Accepted: Explicitly approved the suggestion by replying, "Go ahead and do that."
- Changed: No additional student revision to the proposed section was recorded.
- Rejected: None recorded for this suggestion.
- Decision: Accepted.
- Reason: The proposed improvement lets readers navigate directly to the workflow notes and avoids linking to an AI log that does not yet exist.
- Actions performed by AI: Edited README.md, checked that the workflow-notes link target exists, and committed and pushed the change on the feature branch.
- Related GitHub URL: https://github.com/aharalam/swe325_525-github-ai-practice/commit/145bcab2206acbc80af51cf6e1fa116e98c615be

## Interaction 6 - Drafting This AI Log

- Date: September 24, 2026
- Assistant: OpenAI Codex
- Purpose: Consolidate the actual AI interactions, decisions, and supporting links.
- Prompt: "Go ahead and create ai-log.md"
- Useful output: This log, with the explanation, review, and proposed-improvement interactions identified and additional assistance disclosed.
- Accepted: Authorized creation of the draft. Final review of its content is pending.
- Changed: Pending student review.
- Rejected: Pending student review; none invented.
- Decision: Draft requested; final content approval pending.
- Reason: Keep a traceable record of AI assistance without inventing personal reflections or decisions.
- Related GitHub URL: https://github.com/aharalam/swe325_525-github-ai-practice/blob/feature/github-ai-workflow/ai-log.md

## Required Prompt Categories

- Explanation: Interaction 3.
- Proposed improvement: Interaction 5.
- Review or checklist: Interaction 2.

## Reflection - Student Responses Still Required

### 1. Which GitHub action or object was most useful to you, and why?

Pending: Write your own answer based on your experience.

### 2. Which AI suggestion did you accept, and what made it useful?

Pending: The README navigation improvement is a documented accepted suggestion. Explain in your own words what made it useful to you.

### 3. Which AI suggestion did you revise or reject, and why?

Pending: No explicit rejection or substantive revision of an AI suggestion has been confirmed. Formatting edits are documented above, but do not invent a rejected suggestion. Identify an actual decision and explain it, or evaluate a suggestion before completing this answer.

### 4. What did you verify yourself instead of trusting the AI?

Pending: Record checks you personally performed. The repository and link checks carried out by Codex are AI checks, not independent student verification.

### 5. What would you change in your GitHub workflow next time?

Pending: Write your own answer based on the workflow you practiced.

## Remaining Work

- Review the factual summaries and confirm or revise the decision reasons.
- Complete all five personal reflections.
- Record an actual revised or rejected suggestion if needed to satisfy the lab's decision documentation.
- Add later AI interactions and pull-request links when applicable.
- Complete the pull-request review and merge before claiming the lab is finished.
