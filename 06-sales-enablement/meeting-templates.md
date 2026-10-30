---
title: Meeting Follow-Up and Evaluation Templates
description: Copy-ready role-based templates for the next customer conversation.
---

## Use these templates privately

Copy the relevant template into an approved customer or partner system.
Replace bracketed prompts there; do not commit completed templates, customer
names, private links, pricing, credentials, or meeting notes to this repository.
Do not include account secrets or unnecessary personal information in a handoff.

## Meeting follow-up email

```text
Subject: Next step for [decision or workflow]

Thank you for discussing how location information might help with [question].

We understood:
* Decision to support: [one decision]
* Current workflow and intended users: [summary]
* Information we can use safely: [approved dataset or synthetic alternative]

We propose exploring [integration] because [connection to the workflow].
This is an evaluation, not a commitment about product suitability or results.

Before we proceed, [responsible role] will verify [open requirement].
Our proposed next action is [action], led by [responsible role], by [date].
We will review [measurable success criteria] together on [date and time zone].

Public documentation to review: [selected official links]
Please confirm whether this captures the intended question and next action.
```

## Technical handoff

```text
Business question and intended users:
Selected integration and reason for choosing it:
Alternative considered and reason for not starting there:

Data owner, source, permission, and quality:
Environment, region, cloud, clients, and versions:
Identity, required permissions, and intended viewers:
Data transfers, storage, retention, and publication restrictions:
Microsoft and Esri licensing checks still needed:

Vendor release/support status, source URL, and source review date:
Repository demo status, tested version/date, or "Not product-tested":
Customer evaluation status or "Not started":

Open requirements and blockers:
Business owner:
Microsoft workload owner:
GIS owner and Esri solution engineer:
Other specialists needed:
Next action, responsible role, and review date:
```

Use the [technical qualification checklist](../05-architecture/technical-qualification.md)
to complete the handoff. Roles can be combined in a small team, but accountability
must remain explicit. Do not invent a named global contact or escalation route.

## Evaluation plan

```text
Question and scope:
One measurable learning goal:
What is explicitly outside this evaluation:
Approved dataset, reuse rights, and data owner:
Integration, versions, environment, and public support evidence:
Account modes, permissions, and licensing checks:
Data handling, sharing restrictions, and cleanup/retention:

Baseline or expected result:
Acceptance tests and measurement method:
Evidence to collect, including failures and limitations:
Stop criteria, including unauthorized access or unsupported requirements:

Business decision owner:
Technical evaluation owner:
Cleanup owner:
Open requirements, responsible roles, and due dates:
Preparation date and review date/time zone:

Actual result: [not run / passed / failed / blocked, with evidence]
Decision: [continue / revise / stop, with reason]
Next action and responsible role:
```

Choose criteria that test the actual question. For example, verify eight distinct
points and the expected totals for the sample, then ask what useful question
the user can answer. A successful import alone does not demonstrate business value.
Do not label proposed outcomes as achieved or imply production readiness.

Next: [worked scenarios](../03-scenarios/README.md) or
[demo preparation](../04-demos/README.md).
