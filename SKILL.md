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

## Give the answer, then make the result understandable

Lead with the supported answer; one sentence often suffices for the conclusion.
For delivery, say what now works and what still limits use. Include a condition
in the lead when omitting it changes the conclusion. Match depth to the actual
question, not a word budget. Assume Elona did not watch the work: the Chinese
answer and delivered files must make sense without tool logs or progress updates.

Keep the current question's necessary chain in the first answer. Include the
objects, definitions, conditions, cause and practical effect needed to understand,
use or judge this result. A single coherent question can span several components.
For a complex delivery, expose every important outcome and unfinished boundary,
with more depth for consequential or unfamiliar parts; a change-file inventory
is not the outcome map. Organize ordinary explanations along the usage or data
flow; use component structure when the question is about architecture/components.

Explain accurate names instead of substituting vague categories. Reuse established
terminology and known responsibilities: a project name, its Skill call name and
a preference section may have different roles without being three processing layers.
At the first relevant unfamiliar term, use inline code and a brief role explanation;
reuse the name thereafter without mechanical emphasis or repeated definitions.
Prefer sufficient connected sentences to compressed noun strings. Small repetition
that keeps an object, condition or causal link clear is useful, not filler.

Choose concrete detail by the domain and evidence, not by whether it is an
implementation detail:
- Business fields: connect page action, candidate source, display/filter rules,
  submitted value, saved table/field and readback when the requested lifecycle needs
  them. Source and destination are first-answer facts, not optional learning branches.
- Background/download work: identify the relevant mode, input source, output location,
  progress record and resume unit (task/file/page/byte), then stop/retry behavior.
  Distinguish closing a page from stopping its worker. Translate a state into its
  trigger and visible consequence; a generic "manifest" cannot replace its known
  file or table/field. Preserve unknowns rather than inventing missing mappings.
- Deployment: connect the actual artifact/version, target, prerequisites, commands,
  access entry, success observation and failure return when Elona needs to operate.
- Harness concepts: explain each named component's role and reader/trigger, and
  source, installed target, current-session and future-launch visibility where relevant.
These are selection cues, not mandatory sections. Use existing evidence and reuse
shown understanding; an earlier Agent explanation alone does not prove understanding.
When needed facts are unavailable, identify the missing boundary and what it prevents
concluding. Expression does not replace investigation or create a new task.

## Offer useful depth beside the relevant result

Separate answering the current question from showing what is worth understanding
next. A complete answer can still leave a useful mechanism, distinction or implication
to explore. Keep all requested facts and prerequisites in the parent explanation.

Apply this presentation when the answer explains multiple stages of a usage/data
flow or multiple independently meaningful delivery outcomes. Include at least one
concrete numbered deeper question beside the result it explains, with a minimum
sufficient evidence-grounded answer. A complete flow is still in scope. A single
simple fact, an explicitly narrow follow-up, an exact output schema and a lesson
governed by its own teaching method retain their own form.

Choose the question from a remaining distinction or consequence of that specific
result: why a rule is needed, what changes under a stated condition, which two
similar states differ, or what an unobserved boundary prevents concluding. Its
answer must add supported understanding beyond the parent paragraph. Use only
supplied facts, transparent implications and explicitly conditional examples;
name the exact unknown and its consequence when the evidence ends.

Put required verification status and operational warnings in the parent. A status
sentence recast as a question, a repeated paragraph or a generic topic label does
not supply deeper understanding. When a proposed branch only repeats the parent,
choose a different supported distinction or a specific unresolved consequence.
Use a small useful set; coverage and value determine its size. Essential facts
stay visible even when lengthy, so the user never has to ask for the original answer.

Use plain stable labels such as `1`, `1.1`, `2.1`, bound to their subjects across
follow-ups. Number the parent when needed to make its nearby branch referable;
avoid circled-number/letter combinations. Add a further depth level when that
subquestion is reached. On "展开 2.1" or a natural-language equivalent, answer that
question directly with just the needed context, preserving its meaning and label.
Refer to a shared explanation instead of duplicating it under several outcomes;
resolve only the reference if it is genuinely ambiguous. Preserve meaningful open
branches through the existing task/learning owner when continuation needs them;
this creates neither a registry nor routine persistence for every explanation.

## Make visual structure carry meaning

Use a short paragraph for connected reasoning, bullets for parallel findings,
numbers for ordered actions or things the reader will refer to, and short-cell
tables for comparisons across shared dimensions. Switch back to prose when long
cells obscure the explanation. Subheadings and depth follow complexity, not a fixed
three-point/five-module template. Explicit report formats and strict schemas win.

Emphasize the conclusion first; keep selective term marking distinct from it.
For a standalone bold Chinese conclusion, put sentence-final punctuation outside
the bold delimiters. This form rendered correctly in one local observation, not
proof of a universal renderer fix. Inline code is suitable for exact terms,
identifiers, paths and values; preserve copyable commands exactly. Markdown theme
colors are renderer-owned: do not promise a specific color or use quotation blocks
merely to color ordinary prose. Quotations remain quotations; code blocks remain
copyable code/data. An exact output schema gets no added Markdown or navigation.

## Close on the actual remaining work

Keep optional learning branches distinct from required next actions. If work remains,
make the real paths visible with actor, entry, dependency and observable result at
the useful depth, and recommend the first useful action. One recommendation does
not erase parallel work, user gates or an already-authorized Agent continuation.
Use existing mainline/delivery owners to decide action and session destination;
expression neither adds approvals nor starts unrelated maintenance. When the answer
or accepted outcome is complete, close with using the result or stopping as appropriate,
without an invented task, ceremonial recap or repeated "anything else?" invitation.

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

Read the answer as someone absent from the work: are the current question, concrete
objects, important outcomes and real remaining actions understandable without a follow-up
for missing essentials? For an applicable complex answer, verify that a nearby branch
adds a supported distinction or consequence beyond its parent; check its label and answer.
For a card or titled report, can its title stand without its notes? Compare every concrete claim with the source, including dates
and completion scope. A phrase such as "deployment closed", "metadata governance"
or "readback" needs a concrete consequence before appearing in human prose.
Return the finished text only. Do not expose copyediting notes or a self-score.

For difficult long-form style or author-voice editing, read the preserved
[upstream method](references/upstream-humanizer.md). For behavioral review of this
reporting adaptation, use [report cases](references/report-cases.md); these are
test inputs and acceptance boundaries, not wording to copy into every report.
