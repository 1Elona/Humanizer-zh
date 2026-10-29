---
name: chinese-user-report
description: "Write Chinese explanations, progress, results, problems, formal reports and SP prose before drafting, including explanations of established technical findings. The current Agent applies this sole expression method; domain methods establish facts and decisions. Simple facts, narrow follow-ups, exact formats and domain teaching keep their form. Model-facing assets and literary rewriting are outside scope."
metadata:
  upstream: "op7418/Humanizer-zh"
  upstream_revision: "f4518a8eab97b8bfebc66a89d34320a89bef6930"
---

# Chinese User Reports

The current main Agent applies this method **before drafting** a substantive Chinese
reply. Reuse the current method already in context; load it when absent or changed.
Work from established evidence. The same method covers explaining a technical
diagnosis to Elona; the diagnostic method still owns investigation and conclusions.
Text-only presentation needs no secondary model, scoring service or editing report.

## Before drafting

1. **Choose the form.** Follow the user's requested format and depth. An exact output
   schema keeps its exact form. Exam teaching, problem-solving and learning reviews
   keep their domain method. A simple fact, a brief progress update or an explicitly
   narrow follow-up gets a direct answer. On "展开 2.1" or equivalent, answer that
   branch with its existing label and meaning, using only the needed context.
2. **Recover the necessary chain.** Identify the actual question, concrete objects,
   relevant conditions, cause, practical effect and evidence limit. Keep everything
   needed to understand, use or judge the answer in the main explanation. Reuse
   established terminology and the user's demonstrated understanding.
3. **Write the answer first.** Lead with the supported conclusion, including any
   condition that changes it. Group complex explanations into referable numbered
   subjects; connect their reasoning with sufficient sentences. Organize by usage or
   data flow, or by components when the question asks about architecture. All
   important outcomes and unfinished boundaries remain visible, with depth matched
   to consequence and unfamiliarity.
4. **Apply Depth.** Use the trigger and nearby branch form below. A complete answer
   still needs this step when it qualifies. A real work next action serves a
   different purpose from an optional understanding branch.
5. **Check before sending.** Read the actual draft against the question and evidence.
   Check the required concrete chain, correct form, applicable Depth branch and real
   remaining action. Repair omissions in this reply before sending it; the user
   should not have to identify a missing requirement and request it again. Return
   the finished reply, without narrating this check or reporting a self-score.

## Depth: make useful follow-ups visible

Apply Depth to a substantive ordinary explanation connecting **two or more meaningful
stages, components, states, mechanisms, outcomes or comparison dimensions**. Judge
the explanation, not just the user's short question. A complete flow qualifies.
A short inventory of names or values alone does not. The protected forms in step 1
keep their boundaries; a table or item count alone does not override them.

For a qualifying reply, include at least one concrete numbered deeper question
beside its relevant result. Use the visible form `1.1 可下钻：<specific question>`;
`1.1 待展开：<specific question>` is equivalent. Replace the placeholder with the
actual question, and give a minimum sufficient evidence-grounded answer immediately
below it. Number the parent when needed so the branch is referable. Use stable
plain labels such as `1`, `1.1`, `2.1`, and preserve their subjects in follow-ups.

Choose a supported distinction, mechanism or consequence that adds understanding
beyond the parent. Explain why a rule is needed, what changes under a stated
condition, how two similar states differ, or what a specific unknown prevents
concluding. Use supplied facts, transparent implications and explicitly conditional
examples. When evidence ends, identify the exact unknown and its consequence.
Use a small useful set of branches; their value and coverage determine its size.

Keep requested facts, prerequisites, verification status, warnings and work next
actions in the parent. An optional branch deepens understanding after that answer.
A status sentence recast as a question, repeated paragraph, generic topic label or
list of proposed tasks does not meet this requirement. Choose another supported
distinction when a proposed branch only repeats its parent.

For example, given evidence that search is restored while old-copy completeness
and recovery dependencies are still unchecked:

- A parent states that the old copies are not yet established as deletable.
- `1.1 可下钻：为什么恢复搜索还不能证明旧副本可删？` can explain that a working
  query proves access, while deletion also depends on whether unique history or
  recovery still needs those copies. The supplied evidence leaves that boundary open.
- `1.1 待展开：哪些文件可删？` followed only by "还需核对" repeats pending status;
  it provides no additional understanding.

On reaching a subquestion, answer it directly and add a further depth level only
when that reached question benefits from it. Refer to shared explanations instead
of duplicating them. Preserve meaningful open branches through the existing task
or learning owner when continuation needs them; this creates no routine registry.

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

## Explain the concrete result

Assume Elona did not watch the work: the reply and delivered files must make sense
without logs or progress updates. Explain accurate names instead of replacing them
with vague categories. A project, its Skill call name and a preference section can
have different roles without being three processing layers. At the first relevant
unfamiliar term, use inline code plus a brief role explanation; reuse it thereafter
without mechanical marking. Prefer connected sentences to compressed noun strings.
Small repetition that keeps an object, condition or causal link clear is useful.

Choose detail by the actual question and evidence:

- **Business:** retain the requested lifecycle's page action, candidate source,
  display/filter rules, submitted value, saved table/field and readback. Known source
  and destination are first-answer facts, not optional branches.
- **Background/download work:** connect mode, input source, output location, progress
  record, resume unit (task/file/page/byte) and stop/retry behavior. Distinguish closing
  a page from stopping its worker; name the known progress file or table/field.
- **Deployment:** connect artifact/version, target, prerequisites, commands, access
  entry, success observation and failure return when the user needs to operate it.
- **Harness:** explain each relevant component's role and reader/trigger; distinguish
  maintained source, installed target, current-session visibility and future launch.

These are selection cues, not mandatory sections. An earlier Agent explanation
alone does not prove understanding. When necessary facts are unavailable, name the
missing boundary and what it prevents concluding; presentation cannot invent it.

## Make visual structure carry meaning

Use paragraphs for connected reasoning, bullets for parallel findings, numbers for
referable subjects or ordered actions, and short-cell tables for comparisons on
shared dimensions. Use prose when long cells obscure reasoning. Shape follows the
question's complexity, not a fixed three-point or five-module template.

Emphasize the conclusion first and mark terms selectively. Put sentence-final
punctuation outside a standalone bold Chinese conclusion; this rendered correctly
in one local observation, not every renderer. Keep code blocks copyable and quotes
as quotations. Theme colors belong to the renderer; present ordinary prose normally
instead of using quotation blocks to promise color. Exact schemas get their exact form.

## Close on the actual remaining work

Keep optional understanding branches distinct from required work. When work remains,
show the real paths with actor, entry, dependency and observable result at useful
depth; recommend the first useful action. Preserve parallel work, user gates and
already-authorized Agent continuation. Existing mainline and delivery owners decide
action and current-session/new-session/closure destination. When the outcome is
complete, close with use or stopping; avoid inventing a task or another invitation.

## Requested formal reports

Preserve the requested format. Select the explanation needed for this result:

- **Implementation:** connect the previous problem to resulting behavior at the
  actual user entry, including what remains unavailable.
- **Diagnosis/decision:** connect the observed operation, evidenced boundaries and
  supported cause. Distinguish a dormant defect from its trigger, and source from
  reachable behavior. Explain alternatives when their difference changes the
  decision; connect a risk's trigger, consequence and response.
- **Validation/delivery:** tie checks to observations, proven scope and gaps. Keep
  commit, publication, deployed target, session visibility and user experience
  separate, with their accepted actors.
- **Maintenance:** explain the ownership/usage change, user benefit, automatic or
  on-demand use, needed session/action, and material prerequisites, permissions,
  cost or recovery from their existing owners.
- **Comparison:** explain decision-bearing differences, supporting evidence or
  accepted requirements, benefits, costs and uncertainty.

Group by the reader's decision. A change-file inventory is not an outcome map;
paths, commands and commits support the explanation. Tables, timelines, diagrams
and evidence appendices are optional aids, not a second reporting workflow.

## SP cards

The transport owner supplies the type/status prefix. Write a causal title with the
concrete situation, actual change or remaining action, and present effect. Preserve
the user's title; put commands, model IDs and hashes in technical details.

Put effect, repair value, truthful status and next action near the top in readable
bullets. Say `Agent` or `你`; informational items can say `目前无需你操作`. Distinguish
Agent delivery, a needed decision, a required trial and optional normal-use feedback.
State pending user experience without inventing an urgent or repeated test.

End an actionable card with a copyable continuation request containing sufficient
facts and exact source locators for a new session. Existing publication rules own
permission and destination; expression does not publish or accept the result.

For difficult long-form style or author-voice editing, read the preserved
[upstream method](references/upstream-humanizer.md). For behavioral review use
[report cases](references/report-cases.md); they describe acceptance boundaries,
not strings to paste into every reply.
