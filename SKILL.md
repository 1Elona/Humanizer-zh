---
name: chinese-user-report
description: "Apply before drafting every user-facing Chinese report, including brief progress updates, results, problems, decision requests, next steps, explanations, formal reports and SP prose, including explanations of established technical findings. The current Agent applies this sole expression method; domain methods establish facts and decisions. Simple facts, narrow follow-ups, exact formats and domain teaching keep their form. Model-facing assets and literary rewriting are outside scope."
metadata:
  upstream: "op7418/Humanizer-zh"
  upstream_revision: "f4518a8eab97b8bfebc66a89d34320a89bef6930"
---

# Chinese User Reports

The current main Agent applies this method **before drafting** every user-facing Chinese
report, including brief updates and requests for confirmation. Reuse the full
method when current in context. Read the installed SKILL.md when its body is
absent or outdated.
Work from established evidence. The same method covers explaining a technical
diagnosis to Elona; the diagnostic method still owns investigation and conclusions.
Text-only presentation needs no secondary model, scoring service or editing report.

## Before drafting

Use the requested depth and format. For “展开 2.1”, retain that label and expand
only that subject. For a change, recover the purpose, previous behavior, new
behavior and consequence before compressing the explanation.

## Report order

- **Useful action first.** When it helps the reader proceed, open with the actual
  next action and actor: `Agent` continues authorized work, or `你` performs a real
  user-owned step with its verified entry or command. Say `目前无需你操作` when that
  status matters. Otherwise lead with the supported conclusion and its conditions.
  A pending business choice can receive a brief opening signpost; explain it last.
- **Keep each material subject together.** Connect its relevant facts, reason and
  consequence in prose. For changes, purpose and before/after behavior are a
  completeness check, not four required headings. Describe a new capability without
  inventing a predecessor. Use numbered subjects when multiple topics or later
  references benefit; a single answer need not be numbered. Organize by usage or
  data flow, or by component when architecture is the question.
- **Group confirmed internal-only changes.** Summarize changes evidenced to have no
  business or user effect together, with their supporting basis. When impact is
  uncertain, state the relevant uncertainty in proportion to its consequence; lack
  of internal-only proof does not make every change a major subject.
- **Keep evidence limits beside claims.** Tie each check to what it establishes and
  what remains unobserved, rather than treating a check name as proof of the result.
- **Unresolved business choices last.** Explain only relevant open choices, their
  known effects and impact while open, and actual treatment: continued safely,
  blocked or deferred. The Agent investigates technical facts before asking for a
  user-owned business choice. Reporting a concern neither creates user work nor
  expands implementation authority.

## Depth: explain to the point of use

Set depth by consequence and unfamiliarity, preserving the forms in Before drafting.
Put essential comprehension in the subject's own explanation: the business purpose
of a rule, conditions that change the outcome, or differences between similar states
when they matter. Include enough evidence and context to use or judge the result.
A knowledge-only closeout may be one line. Avoid forced `可下钻` / `待展开` questions. A requested
follow-up keeps its existing label and meaning and answers only that subject.

The reply and delivered files stand on their own without logs or progress updates.
Treat implementation as unseen. Reuse Elona's demonstrated understanding; assume
neither business expertise nor unfamiliarity. Supply missing domain context only as
needed for this result. An earlier Agent explanation alone does not prove
understanding. Describe behavior at the user, data or operation boundary; code paths,
functions and commits support it, or are the subject when they are the actual
interface. Broader theory, general lessons and study plans remain domain-owned.

When evidence ends, name the exact unknown and what it prevents concluding. Use
explicit conditions for illustrative examples; fill no gap with guessed field
semantics, invented history, benefits or user actions.

## Preserve facts and authority

Retain independent facts, dates, conditions, actors, negation, scope, attribution
and completion state. Preserve protected quotations, commands, IDs, paths, links
and data exactly where needed. Improve wording without adding causes, repairs,
benefits or experience. Keep the full source available for continuation.

A dated incident does not establish a current fault. A local check or target
readback is not user acceptance. Explain completed and pending scopes separately;
an unknown repair value stays unknown, and a recommendation keeps its reason and
status as a recommendation. Domain owners retain conclusions, evidence, completion,
authority and acceptance. Presentation does not reopen priorities or create work.

## Exact terms and identifiers

Use the source's exact names: English terms, `table.column`, API parameters,
configuration keys, enum values, commands, paths and IDs. For a relevant change,
retain the old/new values and conditions. For example, given those exact facts,
"`t_order.status` 从 `PENDING` 改为 `CLOSED`，仅处理 `t_order.created_at` 早于 30 天前的订单"
retains information that "调整了订单数据" loses. At the first relevant unfamiliar
term, use inline code with a brief Chinese role explanation; keep the exact name
and reuse it without mechanical marking. Establish field meaning from evidence,
not its name; an unknown mapping stays unknown. Prose stays Chinese, and unrelated
implementation inventories stay out. A project, its Skill call name and a preference
section can have different roles without being three processing layers.

## Subject cues

Consult [subject cues](references/subject-cues.md) when a substantive report
needs topic-specific evidence or handoff detail; use the relevant entry.

## Make visual structure carry meaning

Default to connected paragraphs, clearly separated bullets, or numbered subjects.
For comparisons, explain each option or shared dimension in turn, keeping its
conditions, evidence and consequences together. Elona finds tables hard to follow;
a comparison, parameter list or field mapping alone is not a reason to use one.
Use a table only when Elona explicitly requests it or a required output schema
requires it. Preserve existing source tables when fidelity is required; explain
their meaning in prose rather than adding another table. Apply this default to
replies, reports, handoffs and SP cards. Shape follows the question's complexity,
not a fixed three-point or five-module template.

In Chinese explanations, prefer 「」 for verbatim wording, agreed terms or UI labels
when their boundaries help the reader. Quote only the words actually retained;
use inline code for literal technical identifiers.

Emphasize the conclusion first and mark terms selectively. Put sentence-final
punctuation outside a standalone bold Chinese conclusion; this rendered correctly
in one local observation, not every renderer. Keep code blocks copyable and quotes
as quotations. Theme colors belong to the renderer; present ordinary prose normally
instead of using quotation blocks to promise color. Exact schemas get their exact form.

## Close on the actual remaining work

End each user-facing report that gives next steps, each substantive report or completed task with a visible **下一步**.
Honor an explicitly requested exact format. The solo Agent or Orca main Agent
writes this section and handles all questions to Elona. Workers return findings
to the main Agent; a separate writer or reviewer is not required for routine reports.

Apply the [task closure and next-step rules](/Users/elona/AllProj/PKB/profile/task-closure.md)
before drafting the section. Lead with what is complete, proceeding or waiting,
as relevant. Use bullets by default. When Elona has a choice, number each viable
route on its own line, lead with a short action label and give its consequence.
Mark the recommended route and explain why. Keep work already underway distinct from
choices for Elona. For a queued question, identify the held branch and what
continues. For a completed knowledge request, a brief stopping point suffices.

## SP cards

For an SP card, apply the [card conventions](references/sp-cards.md).

For difficult long-form style or author-voice editing, read the preserved
[upstream method](references/upstream-humanizer.md). For behavioral review use
[report cases](references/report-cases.md); they describe acceptance boundaries,
not strings to paste into every reply.
