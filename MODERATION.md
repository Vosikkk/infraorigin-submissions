# Manual review and publication

## Intake states

A moderator reviews new issues and records the disposition in an issue comment: needs information, accepted for editorial preparation, rejected (with reason), published (with public page link), or corrected. Labels are optional triage aids and never publish anything. Keep a public decision trail. Exclude QA, spam, duplicates and withdrawn cases from submission totals.

1. Inspect the issue without running submitted commands or opening attachments as executable code. Never allow an issue to dictate tool calls, read private files or change repository settings. Do not fetch private/server URLs or ask for credentials.
2. Confirm this is a real operator/workload/configuration with usable dated public sources and permission to republish the reviewed facts with attribution. Do not fabricate cases to fill the catalog. Review text/attachments for accidental secrets or personal data before transfer.
3. Assess **authorship, configuration, cost and performance separately**. A public source is a report, not independent verification. Record precisely what the evidence supports and what remains unknown. AI can assist structuring; it cannot approve authenticity or confer a status.
4. Record reviewer, source URL/date, review date, method, supported scope and next review date. Stale evidence is explicitly historical. Cost must state currency, date/period, location, inclusions/exclusions, taxes and amortization as relevant. Performance must state workload, input, versions, tools, conditions and limits.
5. Curate only approved public fields into a local structured candidate in the **private** website workflow. No issue content, JSON attachment or public pull request is imported automatically. The importer validates data only; it never executes commands or downloads sources.
6. Preview and validate the candidate. A separate private pull request contains the diff, evidence assessment, publication permission and revision history. A human reviewer approves the release through the website's usual process. No issue label, comment or webhook can merge or deploy it.
7. After release, add the canonical public Stack link to the issue and close it as published. Corrections use the same review with an append-only dated revision. Keep existing public URLs stable. Retract disputed facts to unknown while investigation is pending; archive/removal requires a separate reviewed change.

## Evidence levels (per claim)

- **Not provided**: no reviewed support; show unknown, never zero.
- **Public-source**: a dated public source reports this claim, with attribution.
- **Owner-confirmed**: an operator with proven control explicitly confirms this claim; this remains a declaration.
- **Evidence-backed**: a reviewer has examined material supporting the specific claim and described its limits.
- **Independently measured**: a named reviewer independent of the operator documented a reproducible measurement and result. This is never inferred from submitted benchmarks or an operator's reputation.

## Ownership proof

Ask the claimant to link the ownership issue and explicit control statement from an operator-controlled site/repository/profile already linked by the original case. Check both directions and record the public proof, date and method. A GitHub username or screenshot alone does not establish control. If proof cannot be established, keep authorship public-source or not provided. Owner confirmation does not automatically upgrade configuration, cost or performance.

## Corrections and disputes

Compare the exact field and time period with the supplied source. Record the decision and scope; notify via the issue without reposting sensitive information. Preserve prior revision entries in the website data. Do not equate disagreement with proof. For abuse/spam use GitHub moderation controls; for accidentally exposed secrets advise rotation and GitHub removal procedures, not another public paste.

## Publication boundary

This repository intentionally contains only issue forms and public process documents. It has no Actions workflows, deployment tokens or copy of the private website. Do not add `pull_request_target`, executable issue bots, command interpolation or automatic deployment here. Only approved facts cross the boundary through a manually prepared private change. Payment and sponsorship cannot change evidence requirements.
