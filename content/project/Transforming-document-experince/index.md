---
title: "Modernizing document workflows in a complex transaction platform"
summary: I led a multi-study UX research program that turned fragmented, email-driven document exchange into a structured checklist + document workflow—improving clarity, reducing version risk, and shaping roadmap decisions from early discovery through validation and scale.

tags:  
- UX Research
- Generative Research
- Evaluative Research
- Mixed-Methods Research
- Workflow Design
- Enterprise UX
- Information Architecture
- End-to-End Research
- Systems Thinking


date: 2025-06-01T05:26:35.054Z
draft: false
featured: false

external_link: ""

image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
  caption: 'Image Credit: [**SUMUP Business Guide**](https://www.sumup.com/en-us/business-guide/what-is-a-purchase-order/)'
---

## Problem

### Business & product challenge

![Before: Document coordination lived in email threads and attachments—forcing manual tracking, follow-ups, and low confidence in "what's latest".](problem-visual.png)

In complex, high-stakes transactions, “documents” aren’t a feature—they’re the operating system. Internal teams and external clients must request, collect, verify, and reference dozens of items across multiple parties, deadlines, and handoffs.

The legacy reality looked like this:

- Requirements defined through contracts + back-and-forth Q&A
- Documents arriving in scattered email threads and attachments
- Manual tracking (“what’s missing, who owes what, what changed?”)
- Version confusion and rework (duplicate uploads, wrong file shared, unclear latest)

This is a *product* problem (lack of shared visibility and trusted status), and a *business* problem (time and risk). Industry benchmarks show why this matters: “interaction workers” spend **~28% of time on email** and **~19% searching/gathering information**, and improving collaboration/searchability can create **~20–25% productivity uplift** in the right conditions.

### Users

- **Internal transaction teams** (ops/service/processing): need a reliable source of truth to coordinate work, maintain confidentiality, and avoid errors.
- **External clients/partners**: need clarity on what’s required, what’s outstanding, and confidence that the right version was received.
### Why this was important

Document handling is repeated constantly. If the workflow is unclear, people default to email and personal workarounds—creating compounding cost (minutes lost per document × many users × many transactions) and compounding risk (wrong versions, missed requirements, delayed approvals).

## Strategy

### Research goal

To define a modern document workflow that:

1. makes requirements visible,
2. makes progress trackable,
3. makes document status trustworthy, and
4. scales to high volumes without forcing users back into email or local folders.

### Approach: a program of research, not “one study”

I ran this as a **multi-phase research arc** where each phase answered the next logical question:

1. **Discovery (workflow reality)**: What actually happens today—and where does it break?
2. **Concept shaping (new mental model)**: What structure reduces ambiguity (checklists, status, ownership, visibility)?
3. **Validation (does it work for real users?)**: Can internal and external users understand it quickly, act confidently, and avoid errors?
4. **Scale (second-order constraints)**: Once adoption grows, what breaks next (organization, findability, versioning, automation)?
### Methods

Because the work spanned maturity stages, I matched method to decision:

- **Interviews / workflow mapping** to surface real breakdowns and system constraints
- **Prototype concept testing** to de-risk mental models (terminology, status, ownership, visibility)
- **Design validation** to confirm comprehension and usability before rollout
- **Later-stage discovery** focused on scale issues (high doc counts, search behavior, version control expectations)

## My decision rationale

### Why interviews first

At the start, the users didn’t have a UI problem—we had a **coordination system problem**. Interviews and workflow mapping were the fastest way to:

- uncover the real “jobs to be done” (request → chase → receive → verify → organize → reuse)
- expose hidden constraints (privacy boundaries, handoffs, audit needs)
- identify why “email + attachments” persisted (it filled gaps the product didn’t cover)
**Decision logic**: If we guessed at the workflow, we’d build a beautiful interface around the wrong system.

### Why prototype testing next

Once I saw the breakdown was “tracking + trust,”, I needed to validate whether a checklist/status model could become the shared source of truth. Prototype testing was the right tool because it let us:

- test comprehension of status/ownership (without expensive build)
- test terminology and “professional tone” early (a known adoption lever)
- measure whether users could correctly answer “what’s left?” in seconds
**Decision logic**: We needed behavioral evidence that the model reduced ambiguity—not just opinions about it.

### Why design validation (internal + external)

The workflow had two audiences with different risk profiles. Validation ensured:

- internal users could move fast without creating errors
- external users could act confidently without needing an explainer
- status changes and version cues didn’t create false confidence or confusion
**Decision logic**: In document workflows, clarity is safety—validation is risk management.

### Why organization + versioning later

As the system matured, the next bottleneck wasn’t “can I upload?”—it was “can I find the right thing and trust it?” At scale, long document lists and multiple versions shift the problem from interaction design to **information architecture and reliability**.

**Decision logic**: Once the checklist model reduced “what’s missing,” the system’s limiting factor became “what’s correct and where is it?”—so research pivoted to structure, search behavior, and version control.


## Key decisions

{{< figure src="insight-visual.png" caption="Checklist became the coordination layer that connects requests, uploads, ownerships, status, notifications, and version confidence.">}}

1) **Reframe documents from “file storage” to “workflow tracking”**

**Decision**: Treat document handling as an end-to-end workflow (requirements → request → receipt → verification → history), not a repository.
**Why**: Email persists because it supports coordination and status tracking—so the product had to do that job better.

2) **Use a checklist model as the shared source of truth**

**Decision**: Anchor the experience in a checklist/status structure that answers: what’s needed, what’s in progress, what’s done, what changed, who owns it.
**Why**: This reduces ambiguity for both internal teams and external clients, and creates a consistent foundation for later features (notifications, organization, automation).

3) **Make ownership, visibility, and status explicit (not implied)**

**Decision**: Design for role-based visibility and unambiguous status transitions (with language that users trust).
**Why**: In transaction workflows, unclear “who owns this” creates delays; unclear “status” creates rework and risk.

4) **Standardize organization defaults before adding “more flexibility”**

**Decision**: Provide sensible default structure (folders/tabs/categories, sorting and filtering patterns, and “pin/priority” behaviors) rather than relying on everyone inventing their own system.
**Why**: Ad-hoc organization scales poorly and increases search time and error rates—especially across teams.

5) **Invest in version confidence as a first-class requirement**

**Decision**: Prioritize version history and clear draft/final cues (including stacking, timestamps, and traceability).
**Why**: Version confusion is a trust-breaker; users can’t move fast if they fear sharing the wrong thing.

## What changed

### Roadmap & scope changes

- The roadmap shifted from “improve upload” to “support workflow clarity” (tracking, status, ownership, visibility).
- Document organization and versioning were treated as strategic enablers—not nice-to-haves—because they determine whether the system works at scale.

### Design & UX changes

- Checklist-based experience became the core navigation layer for document work (what’s outstanding, who owes what, what’s completed).
- Status language and interaction patterns were refined through iterative testing to reduce misinterpretation.
- Organization patterns were elevated: default structures, better sorting/filtering, and pathways to reduce scanning and “where did it go?” confusion.
- Version confidence was explicitly designed (history, recency cues, clearer distinctions between draft/final).
### Stakeholder alignment outcomes

- Research artifacts created a shared mental model across product/design/ops/engineering—so decisions could be made faster and with less debate about what users “really do.”

{{< figure src="decision-visual.png" caption="How research translated into action: key inisghts were turned into concrete product decisions and measurable experience changes.">}}

## Impact

Industry research suggests that a large share of knowledge work is consumed by communication and information retrieval:

- ~28% of time is spent managing email (reading/writing/responding)
- ~19% of time is spent searching and gathering information
- Making information more available and searchable can reduce information searching time by as much as ~35% in some contexts

A checklist-driven document system directly targets both buckets:
- fewer emails needed to ask “what’s missing / did you get it?”
- less time spent searching across inbox threads and attachments
- fewer wrong-version loops and duplicate handling
