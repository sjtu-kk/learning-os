# Review Protocol

## Ownership

Central reviews in `reviews/` are time-based summaries across Areas and Projects. Area and Project reviews remain local to their owner. A review links to canonical notes and evidence; it does not replace them or duplicate their full text.

## Daily Review

Central daily notes belong in `reviews/daily/YYYY-MM-DD.md`. A daily review records what can be confirmed about that day:

- activity across Areas, Projects, Resources, and personal notes;
- evidence produced or changed;
- questions that appeared, advanced, were answered, deferred, or reopened;
- decisions and insights formed during the day;
- connections between Areas or Projects;
- the smallest valuable next steps.

### Evidence scan

When generating a daily review, inspect today's relevant work before writing the summary:

1. Scan files under `areas/**/notes/`, `projects/**/notes/`, `projects/**/reviews/`, `resources/`, and `inbox/notes/` that contain today's date or were meaningfully changed today.
2. Read the file content, frontmatter, and diff where available. File modification time alone is not sufficient evidence of a learning event.
3. Include a file only when its content shows a real activity, decision, question movement, resource treatment, practice result, or review judgment from that day.
4. Exclude changes caused only by migration, renaming, formatting, link repair, frontmatter normalization, or bulk automation. These are maintenance events, not learning events, unless the maintenance itself was the subject of the work.
5. Include relevant Project or Area README files only to resolve ownership, goals, or next-step context. Do not treat an unchanged README as evidence of activity.
6. If the day's work exists only in the conversation and not in the workspace, use the conversation only when it is available in the current session or has been explicitly supplied as an input. Do not invent activity from absent evidence.

### Writing rules

- Use actual Wikilinks to source notes, Resources, Areas, Projects, and Questions whenever a target exists.
- Summarize; do not paste source-note sections into the daily review.
- Separate confirmed evidence from interpretation. Mark an inference as a candidate or hypothesis.
- A Question Movement entry must link the question and, when possible, the note or resource that changed it.
- A Next Step must be actionable and linked to the owner it belongs to. Do not create a new Area, Project, or Tag merely because a daily review mentions a new concept.
- If no meaningful activity is confirmed, state that clearly instead of producing a speculative summary.
- A daily review normally uses 3-5 tags, reusing existing tags. `review/daily` is the required type tag.

## Monthly Review

Monthly notes in `reviews/monthly/` inspect Area investment, Project portfolio, capability evidence, unresolved strategic questions, and direction candidates. They may propose changing priorities, pausing work, or opening a new investigation. They do not silently change canonical strategy, plans, Areas, Projects, Tags, or learner state.

## Review Outputs

Reviews may produce candidates for canonical updates, but the canonical owner must be updated separately:

```text
daily event or insight
-> monthly pattern candidate
-> repeated and bounded method candidate
-> evidence-backed capability or stable personal rule
```

The review remains an auditable summary of the period in which the observation was made.
