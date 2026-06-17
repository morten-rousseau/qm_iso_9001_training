# ML!PA — ISO 9001 QMS Training

> **Audience:** All employees · **Pass mark:** 80%

---

## Table of Contents

1. [Why ISO 9001 Matters](#1-why-iso-9001-matters)
2. [The 7 Principles](#2-the-7-principles)
3. [The Feedback Loop](#3-the-feedback-loop)
4. [Your Role in the QMS](#4-your-role-in-the-qms)
5. [QMS in Action — Case Studies](#5-qms-in-action--case-studies)
6. [Documentation](#6-documentation)
7. [Audits](#7-audits)
8. [Reference — ISO 9001 Clauses & 8D Report](#8-reference--iso-9001-clauses--8d-report)

---

## 1. Why ISO 9001 Matters

### QMS and ISO 9001: What do they mean and how are they related?

A **Quality Management System (QMS)** is how a company organises its work to deliver consistent quality. It is a set of processes, records, procedures, policies, and guidelines that make sure things are done right and problems get fixed properly.

**ISO 9001** is the international standard that defines the requirements for a well-run QMS. Getting certified means an independent auditor has checked our system against those requirements and confirmed it meets them.

> The QMS is what we run every day. ISO 9001 provides the requirements our QMS is built to meet.

Quality problems tend to come from the same places: requirements that were never written down, steps that got skipped under pressure, problems fixed quietly without anyone recording what happened. A QMS is the structure that catches those gaps before they turn expensive.

### What this means in practice

ISO 9001 is sometimes seen as something the Quality team handles before an annual audit. It is actually a framework that shapes how we design, build, test, and deliver. When it is working, you barely notice it. When it breaks down, you see it in rework, in escalations, and in projects that spend weeks reconstructing what someone already knew.

### What actually goes wrong when quality systems fail

**Example 1 — A supplier changes something. Nobody writes it down. Months later, the product fails.**

A supplier quietly adjusts a component specification during an ongoing production run. The engineer who noticed it mentioned it in an email and moved on. It never went into the quality system. Six months later, customers start reporting failures. The investigation tries to trace what changed and when, but there is no record. What should have been a one-day fix becomes a multi-week investigation, and a product recall that damaged the relationship with the customer.

- **What would have helped:** If the change had gone through a documented review — recorded, checked, approved — the investigation would have started and ended in the same afternoon.
- **Lesson:** Informal communication and undocumented changes cause costly failures. Every specification change must be formally recorded, evaluated, approved, and communicated.

**Example 2 — A construction project delivered to the wrong specification**

A structural engineering firm wins a government contract. Requirements are agreed verbally in early meetings and captured informally. Midway through, the client updates the load-bearing specification in a formal amendment. The site team never receives it. Construction continues to the original spec. The error is discovered during final inspection. Demolition and reconstruction of a structural element costs more than the original contract value.

- **What would have helped:** A requirement review process where every change is formally recorded, distributed, and confirmed would have caught this before a brick was laid.
- **Lesson:** Verbal agreements are not agreements. Every requirement change must be formally recorded, distributed, and confirmed before work continues.

**Example 3 — A food manufacturer that could not answer a regulator's question**

A food production company is audited following a customer complaint about a product batch. The regulator asks: which supplier provided the ingredient in that batch, and what was its quality certificate at the time of receipt? The company cannot answer. Supplier records exist in a spreadsheet that was last updated six months ago. Certificates are in a folder on someone's desktop. The regulator issues a formal finding, because the organisation could not demonstrate the product was safe.

- **What would have helped:** Supplier records and certificates kept in a controlled system mean any question about any batch gets answered in minutes.
- **Lesson:** Compliance requires proof. Records are what turn completed work into verifiable fact. Without them, the work cannot be confirmed.

### What certification means for our business

Many enterprise and government customers require ISO 9001 certification from suppliers before signing a contract. Our certification is a commercial prerequisite that opens doors. Keeping it requires everyone's participation, across every team.

---

## 2. The 7 Principles

Seven principles underpin ISO 9001. Each one reflects a different reason why consistent quality needs more than good intentions.

| # | Principle | Core idea | How we apply it |
|---|-----------|-----------|-----------------|
| 1 | **Customer Focus** | Quality is defined by whether it meets customer requirements. | Requirement management · Quality assurance · Monitoring of customer satisfaction |
| 2 | **Leadership** | Leaders at all levels set the tone. Quality follows direction. | Quality Policy · Management commitment to quality objectives · Clear responsibilities and accountabilities · Annual management review |
| 3 | **Engagement of People** | The people doing the work are the people who see problems first. Every contribution counts. | Individual contribution of each employee |
| 4 | **Process Approach** | Connected and standardised processes give consistent, predictable results. | Regularly updated process documentation · Consistent process follow-through across all teams |
| 5 | **Continual Improvement** | Getting better is built into the system. Every lesson from a mistake feeds the next cycle. | Regular improvement meetings in teams · Regular internal audits · Central backlog for nonconformities with consistent follow-up |
| 6 | **Risk-based Thinking** | Identify and address risks early rather than reacting after problems occur. | Risk assessment in project management · SWOT analysis in strategic planning |
| 7 | **Evidence-based Decision Making** | Decisions should be based on data and verified results. | Testing with consistent result documentation · KPI framework and regular trend monitoring |

---

## 3. The Feedback Loop

The whole point of the system is this: when something goes wrong, **log it**, **understand why**, **fix the cause**, and **make sure the next team benefits from what you learned**. Every failure handled that way makes the next one less likely.

> **Logging a problem is not bureaucracy.** When you raise an NC in Azure DevOps, you are telling the system something went wrong and giving it a chance to make sure it does not happen again. Skipping that step means the system has to guess.

> **Logging a problem is not bureaucracy.** When you raise an NC in Azure DevOps, you are telling the system something went wrong and giving it a chance to make sure it does not happen again. Skipping that step means the system has to guess.

<table width="100%" style="border-collapse:separate;border-spacing:6px;text-align:center;font-family:'Segoe UI',sans-serif">
  <tr>
    <td style="background:#FDEAEA;border:1px solid #E8192C;border-radius:8px;padding:10px;font-size:13px;color:#111;width:16.6%"><strong>1 · Detect</strong><br/>Something goes wrong</td>
    <td style="color:#6B7280;font-weight:700">→</td>
    <td style="background:#E8EDF8;border:1px solid #1B3FA0;border-radius:8px;padding:10px;font-size:13px;color:#111;width:16.6%"><strong>2 · Log</strong><br/>Raise it in Azure DevOps</td>
    <td style="color:#6B7280;font-weight:700">→</td>
    <td style="background:#FFFBEB;border:1px solid #D97706;border-radius:8px;padding:10px;font-size:13px;color:#111;width:16.6%"><strong>3 · Analyse</strong><br/>Understand the root cause</td>
  </tr>
  <tr>
    <td colspan="5" style="color:#6B7280;font-weight:700">↓</td>
  </tr>
  <tr>
    <td style="background:#F0FDF4;border:1px solid #16A34A;border-radius:8px;padding:10px;font-size:13px;color:#111"><strong>6 · Learn</strong><br/>Next team benefits</td>
    <td style="color:#6B7280;font-weight:700">←</td>
    <td style="background:#F0FDF4;border:1px solid #16A34A;border-radius:8px;padding:10px;font-size:13px;color:#111"><strong>5 · Evidence</strong><br/>Record proof it worked</td>
    <td style="color:#6B7280;font-weight:700">←</td>
    <td style="background:#E8EDF8;border:1px solid #1B3FA0;border-radius:8px;padding:10px;font-size:13px;color:#111"><strong>4 · Fix</strong><br/>Eliminate the cause</td>
  </tr>
</table>

<p align="center"><em>Every failure handled this way makes the next one less likely.</em></p>

### Real example — Firmware release at ML!PA

| Step | Action |
|------|--------|
| **Plan** | Requirements documented in Azure DevOps before sprint starts |
| **Do** | Code written, reviewed (4-eyes), tested per procedure |
| **Check** | NC raised: release note missing from DevOps Wiki |
| **Act** | Procedure updated: release notes required before merge |

### Plan, Do, Check, Act (PDCA)

The QMS runs on one loop: **Plan → Do → Check → Act**. Every project, every process, every improvement follows this cycle — it never stops.

<table align="center" style="border-collapse:separate;border-spacing:10px;text-align:center;font-family:'Segoe UI',sans-serif">
  <tr>
    <td style="width:140px;height:140px;background:#1B3FA0;border-radius:50%;color:#fff;vertical-align:middle;padding:8px"><span style="font-size:26px;font-weight:800">P</span><br/><strong>PLAN</strong><br/><span style="font-size:11px;color:#e5e9f5">Set goals, owners, risks</span></td>
    <td style="color:#1B3FA0;font-size:26px;font-weight:800">→</td>
    <td style="width:140px;height:140px;background:#E8192C;border-radius:50%;color:#fff;vertical-align:middle;padding:8px"><span style="font-size:26px;font-weight:800">D</span><br/><strong>DO</strong><br/><span style="font-size:11px;color:#fde5e7">Follow procedure. Record evidence.</span></td>
  </tr>
  <tr>
    <td style="color:#16A34A;font-size:26px;font-weight:800">↑</td>
    <td style="background:#F3F4F6;border-radius:12px;color:#111827;vertical-align:middle;padding:10px"><strong>PDCA</strong><br/><span style="font-size:11px;color:#6B7280">↻ continuous loop</span></td>
    <td style="color:#E8192C;font-size:26px;font-weight:800">↓</td>
  </tr>
  <tr>
    <td style="width:140px;height:140px;background:#16A34A;border-radius:50%;color:#fff;vertical-align:middle;padding:8px"><span style="font-size:26px;font-weight:800">A</span><br/><strong>ACT</strong><br/><span style="font-size:11px;color:#dcf5e3">Standardise if fixed. Else back to Plan.</span></td>
    <td style="color:#0F766E;font-size:26px;font-weight:800">←</td>
    <td style="width:140px;height:140px;background:#0F766E;border-radius:50%;color:#fff;vertical-align:middle;padding:8px"><span style="font-size:26px;font-weight:800">C</span><br/><strong>CHECK</strong><br/><span style="font-size:11px;color:#dcefed">Audit. Measure. Review feedback.</span></td>
  </tr>
</table>

<p align="center"><em>↻ The loop never stops — Act feeds straight back into Plan.</em></p>

| Phase | What happens |
|-------|-------------|
| **Plan** | Define measures. Set goals, assign owners, identify risks. |
| **Do** | Implement the correction. Follow procedure. Record evidence. |
| **Check** | Test if it worked. Audit. Measure. Review feedback. |
| **Act** | Fix worked: standardise. Fix failed: back to Plan. |

### Where your records live

| What | Where |
|------|-------|
| Procedures and work instructions | Integrated Management Systems SharePoint. Always use the current version, never a local copy |
| Nonconformities | Azure DevOps — log immediately as a work item |
| Corrective actions | Azure DevOps — owner, due date, and evidence of closure required |
| Training records | HR SharePoint |
| Technical documentation | DevOps Wiki |
| Customer feedback & satisfaction | Customer satisfaction survey — results shared directly with Sales and Quality teams |

---

## 4. Your Role in the QMS

### Our Quality Policy

**Vision:** We transform industries to sustainability.

- Building trustful, long-term relationships with customers through a deep understanding of their needs and requirements
- Operating a Quality Management System based on ISO 9001, committed to continual improvement and compliance with all applicable statutory and regulatory requirements
- Digitalising our management, core, and support processes, combined with agile development methods and automation of quality assurance to minimise errors and maintain high efficiency
- Treating our employees as our most valuable asset, respecting their individual needs, and building inspiring team settings with ongoing opportunities for personal growth

**Mission:** We empower our employees to drive change by leveraging best-in-class technology.

The full Quality Policy is in the Integrated Management Systems SharePoint. You are expected to know what it stands for and be able to explain how it connects to your own work.

### Key terms

| Term | Definition |
|------|-----------|
| **Quality** | Delivering what you agreed with the customer. Reliably, consistently, every time. Quality is about being dependable. |
| **Nonconformity (NC)** | When something fails a defined requirement — a test, a step, a customer expectation. Raising an NC is how the system learns. It is expected. |
| **Corrective action** | An action that eliminates the root cause of a problem so it cannot come back. It has an owner, a due date, and evidence that it actually worked. |
| **Evidence** | In quality work, if it is not recorded, it did not happen. Evidence is what turns a verbal agreement into a verifiable fact, and a closed ticket into a closed problem. Every record you keep is evidence that the work was done right. |

### What is expected of you

Working within the system comes down to three habits:

1. **Use the current version** of procedures from the IMS SharePoint
2. **Keep your records complete**
3. **Report problems when you spot them**

Every NC logged helps the system improve. Raising issues is expected.

When assigned a corrective action, meet the deadline. If something gets in the way, flag it before the date passes.

### Where your responsibility ends

Managing the quality system and writing procedures is the Quality team's job. Your responsibility is your own work: done properly, recorded honestly, and problems flagged when you see them.

### The NC process — 6 steps

<table width="100%" style="border-collapse:separate;border-spacing:4px;text-align:center;font-family:'Segoe UI',sans-serif">
  <tr>
    <td style="background:#1B3FA0;border-radius:8px;padding:12px 6px;color:#fff;width:16.6%"><span style="font-size:20px;font-weight:800">1</span><br/><strong>LOG IT</strong><br/><span style="font-size:11px;color:#e5e9f5">Azure DevOps · now</span></td>
    <td style="background:#E8192C;border-radius:8px;padding:12px 6px;color:#fff;width:16.6%"><span style="font-size:20px;font-weight:800">2</span><br/><strong>CONTAIN</strong><br/><span style="font-size:11px;color:#fde5e7">Stop it spreading</span></td>
    <td style="background:#D97706;border-radius:8px;padding:12px 6px;color:#fff;width:16.6%"><span style="font-size:20px;font-weight:800">3</span><br/><strong>ROOT CAUSE</strong><br/><span style="font-size:11px;color:#fdeccf">Why, not what</span></td>
    <td style="background:#1B3FA0;border-radius:8px;padding:12px 6px;color:#fff;width:16.6%"><span style="font-size:20px;font-weight:800">4</span><br/><strong>FIX IT</strong><br/><span style="font-size:11px;color:#e5e9f5">Owner + due date</span></td>
    <td style="background:#0F766E;border-radius:8px;padding:12px 6px;color:#fff;width:16.6%"><span style="font-size:20px;font-weight:800">5</span><br/><strong>EVIDENCE</strong><br/><span style="font-size:11px;color:#dcefed">Proof it worked</span></td>
    <td style="background:#16A34A;border-radius:8px;padding:12px 6px;color:#fff;width:16.6%"><span style="font-size:20px;font-weight:800">6</span><br/><strong>CLOSE</strong><br/><span style="font-size:11px;color:#dcf5e3">Compliance confirms</span></td>
  </tr>
</table>

| Step | Action | Detail |
|------|--------|--------|
| 1 | **Log it** | Azure DevOps · now |
| 2 | **Contain** | Stop it spreading |
| 3 | **Root cause** | Why, not what |
| 4 | **Fix it** | Owner + due date |
| 5 | **Add evidence** | Proof it worked |
| 6 | **Close** | Compliance team confirms |

---

## 5. QMS in Action — Case Studies

Three situations from real engineering and technology teams. The details have been changed. The patterns are ones you will recognise. Each one shows the same thing: a gap in how the system was set up, and what it took to close it.

---

### Case 1 — The bug that got fixed twice

**Situation:** A developer finds a bug during testing. It is not blocking, the fix is quick, and it is a busy sprint. She fixes it, the tests pass, and the work moves on. No ticket. No root cause. No record. Six months later a different engineer hits the same type of bug in a different part of the codebase. He investigates from scratch — same symptoms, same fix, same two days of work. Nobody connects the dots because there is nothing to connect.

**Immediate response:** The second engineer raised a ticket when he noticed the pattern. The first fix was partially reconstructed from version history, but the original context — why the bug occurred, what the conditions were — was gone.

**Root cause analysis (5 Whys):**

| Why? | Because… |
|------|----------|
| Why did the same bug appear twice? | The first fix was never recorded, so nothing triggered a review of related modules. |
| Why was it not recorded? | Small defects fixed during development were not considered worth logging. |
| Why were they not considered worth logging? | The team had no definition of what required a ticket; individuals filled the gap with their own judgement. |
| Why was there no definition? | The process described how to log a ticket but never defined the threshold for when one was required. |
| **Root cause** | **No shared definition existed for what constitutes a loggable defect, so individual judgement replaced process, and the system learned nothing from the first failure.** |

**Fix:** Any defect fixed during development must have a ticket before the branch is merged, regardless of size. Added to the definition of done, spot-checked at sprint reviews. Verified across two consecutive sprints with 100% compliance.

**Lesson:** A fix without a record is not a fix. It is a delay. The same problem will come back, and next time it will cost more and start from zero.

---

### Case 2 — Both sides were right. That was the problem.

**Situation:** A team spends six weeks building an integration module. The kickoff was thorough, the communication was good, and everyone felt aligned. At delivery, the customer pushes back. The error handling does not match their operational environment and the authentication approach conflicts with their security setup. The team explains what was agreed. The customer explains what they meant. Both are telling the truth. Neither had a signed document. The rework takes three weeks and costs more than the original margin.

**Immediate response:** Work stopped. A joint session was held — not to assign blame but to write down the actual requirements from both sides. It took a full day. There were more gaps than expected. Work resumed only after both parties signed off on a written spec.

**Root cause analysis (5 Whys):**

| Why? | Because… |
|------|----------|
| Why was the delivery disputed? | Acceptance criteria were never written down or agreed before work started. |
| Why not written down? | The team relied on meeting notes and shared confidence as sufficient. |
| Why was shared confidence considered sufficient? | No procedure required a sign-off before development began; kickoff meetings were the de facto gate. |
| Why were kickoff meetings the only gate? | The project initiation process had never been reviewed to include a formal requirements agreement step. |
| **Root cause** | **Work started on the basis of mutual confidence rather than documented agreement, and confidence diverges silently under six weeks of parallel interpretation.** |

**Fix:** A requirements sign-off template now covers scope, constraints, acceptance criteria, and explicit exclusions — filled in during kickoff and signed before work begins. Used on three subsequent projects with no delivery disputes in the 12 months following.

**Lesson:** Alignment in a room disappears the moment people leave it. The document is not bureaucracy — it is the only version of the truth that survives the meeting. The exclusions section is the most important part.

---

### Case 3 — A quick process tweak. Three months of silence. Then a field failure.

**Situation:** Two engineers agree on a small change to a build configuration — a parameter adjustment that improves throughput. It is sensible, they test it, it works. They make the change on a Tuesday and move on. No change request. No quality sign-off. For three months everything is fine. Then a specific edge case starts failing in the field. The investigation takes two weeks and goes through three false leads before the change is traced back to that Tuesday. There is no record of who decided, what the justification was, or what the test coverage included.

**Immediate response:** The parameter was reverted immediately. Recent outputs were reviewed for the affected edge case. One customer was notified of a potential impact. The investigation confirmed no defective outputs had reached them, but the notification was required under the quality procedure.

**Root cause analysis (5 Whys):**

| Why? | Because… |
|------|----------|
| Why was the change not submitted for review? | The engineers believed parameter adjustments were engineering discretion, not subject to change control. |
| Why did they believe that? | The change procedure did not define its own scope — it only described the process for changes already submitted. |
| Why was the scope not defined? | The procedure was written for major changes only; smaller adjustments were never discussed when it was created. |
| Why were smaller adjustments not discussed? | The procedure was authored by the quality function without input from engineering. The types of changes engineers actually make were not on the table. |
| **Root cause** | **The change control procedure had no defined lower boundary — anything below a "major change" was outside it by default, regardless of risk.** |

**Fix:** Change procedure rewritten to define three tiers: major changes requiring full review, minor changes with a one-page form and 24-hour turnaround, and parameter adjustments requiring a log entry and sign-off. Two release cycles completed under the new procedure. Internal audit verified compliance.

**Lesson:** The changes that bypass the process are never the ones that feel risky at the time. They feel obvious, quick, and safe — right up until they are not. And when the first root cause points at a person, keep asking.

---

### Case 4 — Everyone knew. Except the person who needed to.

**Situation:** A team updates their deployment process after a painful incident. The new process is better, cleaner, with an extra validation step that caught the original failure. The team is briefed, habits change, and things improve. Three months later a new engineer joins. She reads the procedure on the documentation system. It describes the old process. She follows it. Her deployment fails in the same way as the original incident. It takes half a day to diagnose. The procedure had not been updated since before the incident that prompted the process change.

**Immediate response:** The procedure was updated the same day. The new engineer was walked through the current process by a senior colleague. A check of other procedures found two more that were similarly out of date — both were updated before the week was out.

**Root cause analysis (5 Whys):**

| Why? | Because… |
|------|----------|
| Why did the new engineer follow the wrong process? | The procedure on the documentation system described the old process. |
| Why was the procedure not updated? | No step in the incident workflow required a procedure update before closure. |
| Why was it not required? | Process change and documentation update were treated as separate activities with no enforced link. |
| Why were they treated as separate? | The incident closure checklist only covered the technical fix — documentation was assumed to follow naturally. |
| **Root cause** | **The incident closure process had no documentation gate, so procedures and practice could silently diverge every time a process improved.** |

**Fix:** A documentation update step was added to the incident closure checklist — no incident ticket can be marked done without confirming the relevant procedure reflects current practice. A quarterly procedure review was introduced with named owners per procedure.

**Lesson:** A process that lives in people's heads is not a process — it is tribal knowledge with an expiry date. The moment someone new joins, it becomes a trap. And if it happened once, check whether it happened elsewhere too.

---

### Case 5 — The ticket was closed. The problem was not.

**Situation:** An NC ticket is raised after a recurring integration failure. The immediate fix works. The failure stops, the customer is satisfied, the sprint moves on. The ticket is marked done. No root cause documented. No corrective action defined. Eight weeks later the same failure class appears in a different project. A second ticket is raised. The second investigation uncovers what the first never completed. By then two projects and two teams have paid for the same root cause, and the quality lead has to explain to the customer why the same issue appeared twice.

**Immediate response:** The second ticket was linked to the first and both were reviewed together. The first ticket was reopened because it had been closed without completing the required steps. The customer was informed that a systemic corrective action was being defined.

**Root cause analysis (5 Whys):**

| Why? | Because… |
|------|----------|
| Why did the same failure recur? | The root cause was never identified or addressed in the first ticket. |
| Why was the root cause not identified? | The ticket was closed once the immediate fix was confirmed; root cause analysis was not required. |
| Why was it not required? | The NC template treated root cause and corrective action as optional fields. |
| Why were they optional? | The template was set up for speed — the assumption was that teams would add depth when they felt it was needed. |
| **Root cause** | **The NC process had no mandatory closure criteria — a ticket could be marked done with only a fix recorded and no systemic learning captured.** |

**Fix:** Required fields were added to the NC template: root cause analysis, corrective action, owner, due date. Optional became mandatory. The process owner defines the corrective action, and the Quality Management team supports the process to make sure the right evidence is in place before the ticket can be closed.

**Lesson:** Closing the ticket and closing the problem are two different things. The ticket tracks the paperwork. The corrective action stops the next one. If the template does not require it, it will not happen consistently.

---

> **The pattern across all cases:** In every case the gap in the system was the problem, not the person. And in every case, the fix was straightforward once someone actually looked.

---

## 6. Documentation

Documentation is complained about a lot. It is also the most misunderstood part of any quality system. The cost of skipping it rarely shows up immediately. It tends to appear months later, when a project stalls, the same bug surfaces twice, or a new joiner follows the wrong procedure.

### Two types that matter most to you

| Type | What it captures | Where it lives |
|------|-----------------|----------------|
| **Procedures** | How a process is carried out, step by step, so everyone does it the same way | Integrated Management Systems SharePoint — always the current version |
| **NC records** | What happened, why, what was done, and evidence it worked | Azure DevOps — every NC ticket, open or closed |

### What good documentation actually answers

Good documentation answers one question: **what would someone need to know to continue this work without me?** If a colleague could pick it up cleanly, it is complete.

### Three situations where poor documentation created real cost

**The paused project**
A developer leaves a project mid-way through. Three months later the work is handed to a new engineer. The DevOps Wiki has not been updated. A critical HW/SW interface change is undocumented. The new engineer assumes the original design. Two weeks of integration work is wasted.
*Impact: 2 weeks of engineering time. Preventable with one hour of documentation.*

**The repeated mistake**
A firmware bug class is fixed quietly. No NC ticket, no root cause, no record. Six months later the same error appears in a different module. Nobody connects the dots. The investigation happens again.
*Impact: Duplicate investigation across two projects. Preventable with one Azure DevOps ticket.*

**The outdated procedure**
A team updates their deployment process but not the SharePoint procedure. A new joiner follows the old procedure. Their deployment fails. Half a day to diagnose why. The answer was in the procedure they had just followed.
*Impact: Half a day of debugging. Preventable with one SharePoint update.*

### When a procedure changes

Let the Quality team know. Updating SharePoint yourself risks creating a version mismatch. A procedure that no longer reflects what you actually do is a nonconformity waiting to be found.

---

## 7. Audits

An audit is a structured check that the quality system is working as intended. Think of it as the Check step in PDCA, applied to the whole organisation.

### Types of audit

<table width="100%" style="border-collapse:separate;border-spacing:6px;text-align:center;font-family:'Segoe UI',sans-serif">
  <tr>
    <td colspan="3" style="background:#1B3FA0;border-radius:10px;padding:12px;color:#fff;font-weight:700;font-size:15px">ML!PA QMS</td>
  </tr>
  <tr>
    <td colspan="3" style="color:#6B7280;font-weight:700">↓</td>
  </tr>
  <tr>
    <td style="background:#E8EDF8;border:1px solid #1B3FA0;border-radius:8px;padding:12px;font-size:13px;color:#111;width:33%"><strong>Internal Audit</strong><br/><span style="font-size:12px;color:#374151">Trained internal colleagues · Planned schedule</span></td>
    <td style="background:#E8EDF8;border:1px solid #1B3FA0;border-radius:8px;padding:12px;font-size:13px;color:#111;width:33%"><strong>External / Surveillance</strong><br/><span style="font-size:12px;color:#374151">Independent certification body · Annual</span></td>
    <td style="background:#E8EDF8;border:1px solid #1B3FA0;border-radius:8px;padding:12px;font-size:13px;color:#111;width:33%"><strong>Customer Audit</strong><br/><span style="font-size:12px;color:#374151">A client · On request</span></td>
  </tr>
  <tr>
    <td style="color:#6B7280;font-weight:700">↓</td>
    <td style="color:#6B7280;font-weight:700">↓</td>
    <td style="color:#6B7280;font-weight:700">↓</td>
  </tr>
  <tr>
    <td style="background:#F0FDF4;border:1px solid #16A34A;border-radius:8px;padding:10px;font-size:12px;color:#111">Process followed?</td>
    <td style="background:#F0FDF4;border:1px solid #16A34A;border-radius:8px;padding:10px;font-size:12px;color:#111">ISO 9001 requirements met?</td>
    <td style="background:#F0FDF4;border:1px solid #16A34A;border-radius:8px;padding:10px;font-size:12px;color:#111">Customer expectations met?</td>
  </tr>
</table>

| Type | Who | Purpose |
|------|-----|---------|
| **Internal audit** | Trained internal colleagues | Check our own processes are followed correctly. Planned schedule. |
| **External / surveillance** | Independent certification body | Verify we still meet ISO 9001 requirements. Annual. |
| **Customer audit** | A client | Confirm we meet their quality expectations. |

### Who auditors actually speak with

External auditors primarily speak with the Quality and Compliance teams. They review records, procedures, and NC tickets — not individual employees. For most people at ML!PA, an external audit means nothing changes in your day.

If you are ever directly involved in an audit conversation, focus on showing the records for your work and explaining how you follow your team's procedures. That is what auditors are looking for.

### What they look for — audit finding types

| Finding type | What it means |
|-------------|---------------|
| **Major NC** | A key requirement is not being met. Urgent corrective action required. |
| **Minor NC** | A smaller or isolated lapse. Corrective action required. |
| **Observation** | Not a formal failure but worth addressing. May become an improvement task. |
| **Positive finding** | Good practice noted. Worth sharing with the team. |

### The simplest way to be audit-ready

**Follow your procedures, keep your records complete, and log problems when you see them.** That covers it.

---

## 8. Reference — ISO 9001 Clauses & 8D Report

> Nothing in this section is needed for the quiz or your day-to-day work. It is provided for reference.

### ISO 9001 — All clauses

#### Introductory clauses (non-operational)

| Clause | Title |
|--------|-------|
| 1 | Scope |
| 2 | Normative references |
| 3 | Terms and definitions |

#### Operational clauses

| Clause | Title | Sub-clauses |
|--------|-------|-------------|
| **4** | Context of the organisation | 4.1 Understanding the organisation and its context · 4.2 Understanding the needs and expectations of interested parties · 4.3 Determining the scope of the QMS · 4.4 QMS and its processes |
| **5** | Leadership | 5.1 Leadership and commitment · 5.2 Quality Policy — must be documented, communicated, and understood by all employees · 5.3 Organisational roles, responsibilities and authorities |
| **6** | Planning | 6.1 Actions to address risks and opportunities · 6.2 Quality objectives and planning to achieve them · 6.3 Planning of changes |
| **7** | Support | 7.1 Resources — people, infrastructure, environment, monitoring and measurement · 7.2 Competence — employees must be competent for their roles · 7.3 Awareness — every employee must know the Quality Policy, their quality objectives, their contribution, and the consequences of not following processes · 7.4 Communication — internal and external · 7.5 Documented information — control and maintenance of records and procedures |
| **8** | Operation | 8.1 Operational planning and control · 8.2 Requirements for products and services, including customer communication and review · 8.3 Design and development · 8.4 Control of externally provided processes, products and services — supplier management · 8.5 Production and service provision, includes 8.5.3 Customer property (traceability, protection) · 8.6 Release of products and services · 8.7 Control of nonconforming outputs — the NC process |
| **9** | Performance evaluation | 9.1 Monitoring, measurement, analysis and evaluation — includes customer satisfaction · 9.2 Internal audit · 9.3 Management review |
| **10** | Improvement | 10.1 General · 10.2 Nonconformity and corrective action — the full NC process · 10.3 Continual improvement |

---

### The 8D Report

When a nonconformity is recurring, customer-facing, or has a complex root cause, ML!PA uses the 8D Report.

<table width="100%" style="border-collapse:separate;border-spacing:5px;text-align:left;font-family:'Segoe UI',sans-serif">
  <tr>
    <td style="background:#1B3FA0;border-radius:8px;padding:10px 12px;color:#fff;font-size:13px;width:50%"><strong>D1 · Form the team</strong><br/><span style="font-size:12px;color:#e5e9f5">Cross-functional is better</span></td>
    <td style="background:#1B3FA0;border-radius:8px;padding:10px 12px;color:#fff;font-size:13px;width:50%"><strong>D2 · Describe the problem</strong><br/><span style="font-size:12px;color:#e5e9f5">Specific, measurable, with evidence</span></td>
  </tr>
  <tr>
    <td style="background:#E8192C;border-radius:8px;padding:10px 12px;color:#fff;font-size:13px"><strong>D3 · Interim containment</strong><br/><span style="font-size:12px;color:#fde5e7">Stop it spreading · Log in Azure DevOps</span></td>
    <td style="background:#D97706;border-radius:8px;padding:10px 12px;color:#fff;font-size:13px"><strong>D4 · Root cause</strong><br/><span style="font-size:12px;color:#fdeccf">5 Whys or Fishbone · stop at the systemic gap</span></td>
  </tr>
  <tr>
    <td style="background:#0F766E;border-radius:8px;padding:10px 12px;color:#fff;font-size:13px"><strong>D5 · Permanent corrective actions</strong><br/><span style="font-size:12px;color:#dcefed">Named owner · real due date</span></td>
    <td style="background:#0F766E;border-radius:8px;padding:10px 12px;color:#fff;font-size:13px"><strong>D6 · Implement and validate</strong><br/><span style="font-size:12px;color:#dcefed">Verify it worked · evidence required</span></td>
  </tr>
  <tr>
    <td style="background:#16A34A;border-radius:8px;padding:10px 12px;color:#fff;font-size:13px"><strong>D7 · Prevent recurrence</strong><br/><span style="font-size:12px;color:#dcf5e3">Update IMS SharePoint procedures</span></td>
    <td style="background:#16A34A;border-radius:8px;padding:10px 12px;color:#fff;font-size:13px"><strong>D8 · Recognise and close</strong><br/><span style="font-size:12px;color:#dcf5e3">Lessons learned · close in Azure DevOps</span></td>
  </tr>
</table>

| Step | Title | What to do |
|------|-------|-----------|
| **D1** | Form the team | Bring together the right people. Cross-functional is better. |
| **D2** | Describe the problem | Specific, measurable, with evidence. Not *"login is broken"* — *"login fails when email contains + symbol on v2.3.1"*. |
| **D3** | Interim containment | Stop the problem spreading immediately. Log in Azure DevOps. |
| **D4** | Root cause | 5 Whys or Fishbone. Stop at the systemic gap, not a person's name. Backed by evidence. |
| **D5** | Permanent corrective actions | Named owner. Real due date. Verification method defined before implementation starts. |
| **D6** | Implement and validate | Do it. Verify it worked. Evidence required before closing. |
| **D7** | Prevent recurrence | Update procedures in Integrated Management Systems SharePoint. Update checklists. Fix the system. |
| **D8** | Recognise and close | Document lessons learned. Share with the team. Close the record in Azure DevOps. |

---

## Quick Reference — Where things live

| Record / Document | System |
|-------------------|--------|
| Procedures & work instructions | IMS SharePoint (always use current version) |
| Nonconformity tickets | Azure DevOps |
| Corrective actions | Azure DevOps |
| Training records | HR SharePoint |
| Technical documentation | DevOps Wiki |
| Customer satisfaction data | Customer satisfaction survey results (shared with Sales & Quality) |

---

*ML!PA · Quality Management System · ISO 9001 Awareness Training*
