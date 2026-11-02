# LocalShift documentation rules

{/* Living rulebook for AI-generated and AI-edited docs. Add a rule whenever you correct the same thing twice. Keep each rule to one line. */}

## About this project

- This is the LocalShift Help Center, built on Mintlify and published at help.localshift.io.
- LocalShift lists a dealership's vehicle inventory on Facebook Marketplace and keeps listings in sync. Buyers message sales reps through Facebook Messenger.
- Pages are MDX files with YAML frontmatter. Navigation and site settings live in `docs.json`.

## Audience

- Readers are car dealership staff: sales reps, managers, and admins. Most are not technical.
- Write for someone completing a task on the job. Lead with what to do, not background.

## Terminology

- "LocalShift" (never "Local Shift" or "Localshift").
- "Chrome extension" or "the extension" for the browser extension.
- "dashboard" for the web app at app.localshift.io.
- "Facebook Marketplace" on first mention, then "Marketplace".

## Style

- Use active voice and second person ("you").
- One idea per sentence. Keep sentences short.
- Use sentence case for headings.
- Bold UI elements: click **Settings**.
- Use code formatting for file names, URLs, and paths.
- No marketing language or filler ("simply", "easily", "seamlessly").

## Page structure

- Every page needs frontmatter with `title`, `description`, and `keywords`.
- Task pages use `<Steps>`. Troubleshooting pages list symptom, cause, then fix.
- End troubleshooting pages with a pointer to [Contact support](/contact-support).
- Use `<Note>`, `<Tip>`, and `<Warning>` sparingly, at most one or two per page.

## Accuracy

- Never invent features, settings, menu names, prices, limits, or support hours. If a fact is unknown, leave a TODO comment and flag it for review.
- Support contact details: [support@localshift.io](mailto:support@localshift.io) and (435) 291-1432. Do not add other channels.

## Content boundaries

- Do not document internal admin tools or LocalShift-only processes.
- Do not document pricing or contract terms.
- Do not make claims about how Facebook ranks, approves, or restricts listings.
