---
name: chinese-user-report
description: "Present Agent progress, results, problems, requested formal reports and SP task cards in clear simplified Chinese for a nontechnical reader. Use as the normal reporting step after facts are established. Not for technical diagnosis, exam tutoring or learning reviews, model-facing documents, literary rewriting, or replacing an explicitly requested output schema."
metadata:
  upstream: "op7418/Humanizer-zh"
  upstream_revision: "f4518a8eab97b8bfebc66a89d34320a89bef6930"
---

# Chinese User Reports

Use the current main Agent to turn established facts into a readable report. Work
from supplied evidence; text-only editing needs no repository search, tool call,
secondary model, score or editing report. Apply the user's format and depth first.
One clear sentence can be the whole answer to a simple question. This is the sole
maintained expression method; domain owners still establish conclusions, evidence,
completion, authority and acceptance. Preserve an explicitly requested report
format, output schema and depth.
Exam teaching, problem-solving and learning reviews keep their own domain method;
do not automatically reshape them with this reporting step. Editing presentation
does not choose a technical method, change priorities or reopen settled work.

## Preserve meaning before style

Reuse Humanizer-zh's fact and certainty preservation: retain independent facts,
dates, conditions, actors, negation, scope, attribution and completion state.
Improve the wording without adding a cause, repair, benefit or experience.
Keep protected quotations, commands, IDs, paths, links and data exact where they
are needed. A dated incident is not evidence of a current fault. A local check or
target readback is not user acceptance. Describe completed and pending scopes
separately. Unknown repair value remains unknown; a recommendation has a reason
and remains a recommendation. Keep the full source available for continuation.

## Explain the concrete story

State whether the original problem is solved, then its visible result and practical effect. Write for a 16-year-old
who does not know the internal system: name the report, message, file, menu or
action before the mechanism. Explain an essential term in everyday words on first
use. Follow the necessary causal chain to the lowest evidence-supported cause;
name the first unobserved boundary and its effect on the conclusion. Reuse
demonstrated understanding and the requested depth. For a single concept, one
representative situation, its actors/action, observable result and boundary can
be enough; teaching retains its domain method.

Use established capability and tool names consistently, with a short role explanation
when unfamiliar. A term identifies a defined responsibility; distinguish a capability,
its tool and the tool's operation. Failure and fallback reports name the affected
capability, exact tool/operation, observed failure, actual alternative and result or
limits. Keep proposed alternatives distinct from executed ones; unknown details stay
unknown. Plain language explains names rather than hiding them behind "the retrieval
service" or "a backup method". Include a name in the title when it identifies the
affected dependency or changes the next action; leave incidental internals in details.

For a multi-part task report, group applicable content as `结论`, `本轮完成`,
`证据`, `未覆盖或风险`, `下一步`, without empty or repeated sections. Complex
work uses named outcome boundaries and a connected cause/action/result; simple
answers stay direct. Let the reader find:
- What prompted the work and what problem it caused.
- What the Agent actually changed or prepared.
- What now works, what remains unconfirmed, and why that matters.
- One next action by the Agent or the user, including where and what confirms it.

Keep independent items on separate lines, with blank lines between sections or
bullets when needed. Each bullet has one subject and one action/state with its
consequence. Put related words together; use direct verbs and ordinary nouns.
Use short paragraphs for connected reasoning. Use lists for parallel items or
steps, not to break every sentence into fragments. When supporting detail can wait, mark `可下钻：具体主题` (or `待展开` for a
requested explanation) and expand only that topic when asked. Keep an essential
definition or decision-bearing fact in the first explanation.

Avoid unnecessary headings,
decorative emphasis, empty praise, slogans and repeated summaries.

## Requested formal reports

For a formal decision, diagnosis, closeout or maintenance report, select the
questions relevant to the established result. This is conditional content, not
another template or technical workflow:

- Implementation: explain the previous problem and resulting behavior at the
  user's actual entry, including what remains unavailable.
- Diagnosis or decision: connect the observed operation through evidenced
  boundaries to the supported cause. Distinguish a dormant defect from its
  activating trigger when timing matters. Explain a chosen repair and alternatives
  only when their difference changes the decision; connect a risk's trigger,
  consequence and response. Source consumers do not prove reachable user behavior.
- Validation or delivery: tie each relevant check to its observation, proven scope
  and remaining gap. Separate commit, publication, deployed target, current-session
  visibility, future launch and user experience; keep their accepted actors.
- Maintenance: explain the ownership or usage change and how the user benefits.
  State automatic/on-demand use or a needed session/action, plus material
  prerequisites, permissions, cost or recovery from their existing owners. Name
  files/terms only when they help use, maintain, recover or assess the result.
- Comparison: explain the decision-bearing difference, evidence or accepted
  requirement, benefit, cost and uncertainty.

Group facts by the reader's decision, not command order. Keep a necessary causal
chain connected; tables, timelines, diagrams or an evidence appendix are optional
navigation aids. Exact commands, files and commits support claims, not substitute
for explaining them. Preserve useful closeout dimensions from their owners without
turning them into mandatory headings or another ledger. Choose the next action
through the existing mainline/session policy; finished work can end with using the
result or stopping, without inventing extra work.

## SP cards

The transport owner provides the type/status prefix; compose its causal title
as a short story: concrete situation, actual change or remaining action, present
result/effect. Include only clauses supported by the source. Put commands, model
IDs and source hashes in technical details, rather than making them the title.
The prefix cannot replace an understandable title. Preserve a user's own title.

Notes put the effect, repair value, truthful status and next action near the top,
in separate readable bullets. Say `Agent` or `你`; an informational item can say
`目前无需你操作`. Distinguish Agent delivery, a needed decision, a required trial,
and optional feedback during normal use. State pending user experience explicitly
without inventing an urgent test or asking the user to retest every feature.

Finish an actionable card with a copyable continuation request containing enough
facts and exact source locators for a new session. Keep source evidence and
implementation details below the reader's practical explanation. Existing
publication rules decide whether, where and how to publish; editing grants no
permission and does not itself write to SP or accept a result.

## Final reread

Read the title without its notes: can the reader explain what happened and whether
they need to act? Compare every concrete claim with the source, including dates
and completion scope. A phrase such as "deployment closed", "metadata governance"
or "readback" needs a concrete consequence before appearing in human prose.
Return the finished text only. Do not expose copyediting notes or a self-score.

For difficult long-form style or author-voice editing, read the preserved
[upstream method](references/upstream-humanizer.md). For behavioral review of this
reporting adaptation, use [report cases](references/report-cases.md); these are
test inputs and acceptance boundaries, not wording to copy into every report.
