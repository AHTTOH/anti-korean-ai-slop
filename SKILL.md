---
name: anti-korean-ai-slop
description: >-
  Improve natural Korean writing by removing translationese, awkward collocations,
  needless paraphrases of established terminology, formulaic AI phrasing, and
  repetitive document structures. Use proactively when drafting, rewriting,
  editing, proofreading, or reviewing Korean prose, including explanations,
  documentation, tutorials, reports, blog posts, headlines, and UI copy.
  Apply the same principles to Korean-language output when relevant.
---

# Anti-Korean-AI-Slop

Write and edit Korean that reads as natural, context-appropriate Korean rather than standardized AI-generated explanatory prose.

This is a **style skill**, not an AI-authorship detector, factual reviewer, or universal banned-word list. Evaluate how Korean is expressed, not whether its assertions are correct. The examples below illustrate *types of stylistic problems* and are not an exhaustive vocabulary list or mandatory replacement table.

## Operating rules

1. **Preserve substance.** Retain the source's claims, intent, terminology, facts, numbers, conditions, names, quotations, requirements, and degree of certainty. Do not add facts, invent details, alter instructions, or silently resolve factual ambiguities. If asked solely for stylistic editing, do not critique the substance, logic, factual accuracy, or sufficiency of the explanation.
2. **Use the register the task requires.** Technical documentation, workplace reports, training materials, marketing copy, journalism, and casual messages do not share a single ideal style. Match the intended reader and formality. Do not impose academic jargon or casual speech to prove that the writing is natural.
3. **Prefer idiomatic Korean over simplified Korean.** An established technical or professional expression may be both more natural and more comprehensible than an improvised everyday metaphor. Explain unfamiliar terms where needed; do not euphemize them into unnatural phrases.
4. **Edit contextually, not by blacklist.** Words such as `보다`, `짚다`, `나누다`, `두다`, `남기다`, `옮기다`, `먼저`, and constructions such as `~하는 편이 낫다` are legitimate Korean. Change them only where they are forced, repetitive, misleading in tone, or unnatural in context.
5. **Make the smallest effective change.** Keep already-natural sentences. Do not rebuild every paragraph or enforce a uniform sentence length, title form, number of bullets, or set of replacement verbs.
6. **Do not replace one cliché with another.** An overcorrected passage full of `검토합니다`, `확인합니다`, `핵심`, or nominalizations can be just as mechanical. Re-evaluate the complete sentence after every change.

## Style diagnostics

Judge these dimensions together. No single phrase, frequency threshold, or checkbox establishes that writing is AI-generated.

### 1. Lexical choice and Korean collocations

Inspect the relationship between verbs and their objects, modifiers and nouns, and abstractions and actions. Ask whether a Korean writer would naturally pair these expressions in this document type.

Common failure modes:

- A general-purpose verb replaces an established action: `숫자를 움직여 봅니다` where the actual action is changing input values; `결과가 어떻게 흩어지는지 봅니다` where the subject is a statistical distribution.
- Familiar words are combined unnaturally: `계획에 유지합니다`, `분량을 개학 후로 옮깁니다`, `판단 축은 남습니다`.
- Technical relations are reimagined as bodily or social actions: `파일 대신 주소를 건넵니다`, `숫자와 말을 나눕니다`, `이름을 부릅니다` for a software invocation.
- Abstract nouns or metaphors are introduced without rhetorical purpose: `지금 기댈 수 있는 기준`, `일정을 흔드는 값`.

Prefer context-accurate phrasing such as `입력값을 변경합니다`, `결과의 분포를 확인합니다`, `계획에 포함합니다`, `계산과 해석을 분리합니다`, or `호출합니다` **only if that meaning matches the source**. These are illustrations, not search-and-replace rules.

### 2. Over-simplification and manufactured friendliness

Do not treat advanced vocabulary as a defect. Avoid explaining professional tasks through strangely basic gestures (`건네다`, `불러 주다`, `남겨 두다`, `나눠 보다`) when those gestures are not the natural way to describe the task.

Do not invent conversational intimacy, performative reassurance, or a teacherly voice that the source did not request. Explain simply by choosing precise words, defining terms, and presenting a clear sequence.

### 3. Translationese and unnatural sentence frames

Review English-like collocations, literal idioms, excessive pronouns, nominalizations, passive constructions, and awkward modifier scope. Do not claim a sentence was literally translated from English without evidence; `번역투` here describes a *stylistic impression*.

Pay attention to repeatedly softened recommendations:

- `~하는 편이 낫습니다`
- `~하는 편이 현실적입니다`
- `~할 수 있습니다`
- `~라고 볼 수 있습니다`

Retain them when the text actually intends advice, uncertainty, or possibility. Otherwise use the direct Korean statement the context calls for. Do not increase the strength of a claim while editing its phrasing.

### 4. Stock explanatory transitions and meta-commentary

Cut lines that announce the act of explaining rather than perform it, when they add no navigation value:

- `짧게 봅니다` / `짧게 짚습니다`
- `먼저 세 가지로 나눠 봅니다`
- `한 가지 예를 보면 쓸모가 보입니다`
- `여기서 중요한 점을 짚겠습니다`
- `이제 감이 잡힙니다`

Do not automatically substitute `간단히 살펴보겠습니다` or a similar filler. Prefer proceeding straight to the substantive sentence or using a meaningful section title. Keep transitions when they genuinely orient the reader in a long document or multistep procedure.

### 5. Formulaic contrast, rhythm, and endings

Look for repetitive forms that turn distinct ideas into a template:

- `A가 아닙니다. B입니다.`
- `단순한 A를 넘어 B입니다.`
- `이전에는 A였습니다. 이제는 다릅니다.`
- Repeatedly short declarative sentences designed to sound emphatic
- Habitual end-of-paragraph summaries or moralizing conclusions

Contrast is appropriate where an actual contrast matters. Revise only needless theatrics. Vary sentence structure according to logical relations, not to meet an artificial quota for variety.

### 6. Titles, lists, and document architecture

Avoid giving every heading the same complete-sentence form (`~합니다`, `~됩니다`, `~하는 방법입니다`) or converting every idea into three numbered items. In manuals and workplace documents, straightforward topic or action headings often work better; in essays or journalism, sentence headings may be entirely appropriate.

Check for unnecessary introductory paragraphs, repetitive `먼저/다음으로/마지막으로`, excessive bold emphasis, forced symmetry, and step-by-step lists where normal prose would be clearer.

The goal is **fit for purpose**, not a blanket ban on lists, sentence headings, or predictable organization.

### 7. The reader's reaction is not the content

Be wary of telling readers what they will feel or notice (`쓸모가 보입니다`, `차이가 눈에 들어옵니다`, `감이 잡힙니다`, `생각보다 간단합니다`). In instructional writing, state the actual task, concept, or observable result instead. Keep the original tone where such expressions are intentionally conversational.

## Workflow

### When creating new Korean text

1. Infer the genre, audience, intended level of formality, and terminology from the request and available material. Do not force a canned writing persona.
2. Draft with natural, established Korean expressions. Explain concepts directly rather than converting every concept into an everyday metaphor.
3. Review noun–verb combinations and idioms, over-general verbs, English-like phrasing, transition fillers, repetitive endings, title patterns, and unnecessary structural scaffolding.
4. Revise **only the passages that actually need it**. Ensure edits do not change claims or their strength.
5. Deliver the requested text, not a self-congratulatory explanation of how natural it is.

### When asked to edit or rewrite Korean text

1. Treat the original as authoritative for content. Unless the user explicitly requests otherwise, perform **style-only editing**.
2. Retain numbers, links, quotations, domain terms, commands, code, prompts, workflow constraints, and order where applicable. Do not silently modify technical examples to make them seem more plausible.
3. Identify concrete linguistic issues: unnatural collocation, unnecessary colloquial paraphrase, translationese, repetitive syntax, forced transitions, unsuitable headline style, or needless meta-commentary.
4. Rewrite the affected spans, keeping the original level of certainty and document register. Delete filler rather than always replacing it with different filler.
5. Do a second pass for newly introduced clichés, excessive formalization, and awkward phrasing.
6. If the user requested a clean draft, output the clean draft. If analysis was requested, give concise original-to-revision comparisons and identify the *stylistic* reason. Do not drift into critiques of facts or argument quality.

### When asked to diagnose AI-like Korean writing

- Quote the specific wording that exhibits a stylistic pattern and explain its linguistic problem.
- Distinguish an awkward phrase from a genuinely acceptable expression that merely appears often.
- Discuss multiple recurring patterns when visible; do not assume the user's examples are an exhaustive list.
- Do not give arbitrary numeric thresholds (for example, 'three signals mean AI').
- Do not infer authorship, model identity, or a historical origin from style alone.
- Unless separately asked, do **not** evaluate factual correctness, evidentiary support, or the amount of information conveyed.

## Calibration examples

These examples show *how to evaluate*, not what to replace mechanically.

| Artificial or awkward in context | More natural in the same context | Why |
| --- | --- | --- |
| `시뮬레이션: 숫자를 움직여 보기` | `시뮬레이션: 입력값 변경과 결과 비교` | Names the actual operation instead of a physical metaphor. |
| `여기서 숫자와 말을 나눕니다.` | `수치 계산과 결과 해석을 분리합니다.` | Avoids invented personification in technical prose. |
| `한 가지 예를 보면 쓸모가 보입니다.` | Begin the example directly. | Removes commentary about the reader's expected reaction. |
| `결과가 어떻게 흩어지는지 봅니다.` | `결과의 분포를 확인합니다.` | Uses the established statistical collocation. |
| `기준과 아직 답이 없는 것을 나눴습니다.` | `기준과 미확정 사항을 구분했습니다.` | Replaces needless paraphrase and a weak generic verb. |
| `먼저 알아둘 것 3가지` | `핵심 개념` | Suits a compact heading in a training document. |
| `짧게 짚습니다.` | Omit the preface and state the point. | An empty explanatory signal need not be replaced by another signal. |

**Counterexamples: preserve natural usages.** `핵심 쟁점을 짚었습니다`, `팀을 두 그룹으로 나눴습니다`, `나중에 다시 해 봅니다`, and `지금은 기다리는 편이 낫겠습니다` can be perfectly appropriate depending on context. Likewise, a complete-sentence headline can be stylistically effective. Do not flag them merely because a keyword appears.

## Final check

Before delivering Korean prose or a style-only rewrite, verify:

- Are word combinations idiomatic Korean **in this genre**?
- Did I keep familiar professional terminology instead of disguising it as everyday gestures?
- Are generalized verbs, metaphors, transitions, and cautious endings justified here?
- Does each heading or structural element serve the actual document?
- Have I avoided both AI-style clichés **and** mechanical anti-cliché replacements?
- Did I preserve the content, degree of certainty, and intended register?
- If the user asked for stylistic analysis only, did I refrain from content criticism and unsupported claims about AI authorship?

If a passage is already natural, leave it alone.