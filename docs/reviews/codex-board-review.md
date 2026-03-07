# Codex Board Review

Date: 2026-03-07
Scope: `main.tex` only.

## Global non-section issues

- The abstract is still `TODO`. Any submission-level evaluation is provisional until the paper has an actual entry point.
- The acknowledgements still contain placeholder model-language. That will look unfinished in any circulated draft.

## 1. Karen Neander

### Pass/flag

| Section | Judgment |
|---|---|
| Introduction | Flag |
| The target argument | Pass |
| Groundedness as a cluster property | Flag |
| Communicative calibration | Flag |
| The octopus test revisited | Flag |
| Adjacent accounts | Flag |
| Conclusion | Flag |

### Specific concerns

- `"Referential grounding isn't a single threshold to cross. It's a cluster property with degree structure, where teleosemantic selection history is one stabilizer among several."` Issue: this demotes selection history from a constitutive condition on content to one contributory factor among others. That is not a mild extension of teleosemantics. It is a different theory unless you explain how the other factors generate content rather than merely improve performance.
- `"Selection history raises parallel questions... The analogy is strongest for post-training... It's weaker for pre-training... And it's weaker still for in-context learning..."` Issue: selected-effects teleosemantics is not obviously scalar in the way you need here. A state either has the relevant proper function or it does not. If you want graded function-possession, you need to say how that works.
- `"Correctness conditions don't vanish -- they're distributed across dimensions. A system can misrepresent along one dimension while performing well along another."` Issue: this is where normativity leaks. What is misrepresentation along communicative calibration? What is misrepresentation along inferential-role structure? Those look like coordination failures or reasoning failures, not semantic failure conditions.
- `"Novel contents might be stabilised primarily through communicative calibration and inferential-role structure rather than through selection history narrowly conceived."` Issue: if primary grounding work can be done without selection history, then the paper has abandoned the teleosemantic claim it says it preserves.
- `"Reference, on this view, isn't established once and then communicated. It's stabilised through the communicative process."` Issue: Clark's point concerns how already contentful speakers jointly secure successful reference in conversation. That does not by itself show how a model acquires original representational content.
- `"In profile terms, the octopus scores near zero on every dimension."` Issue: this simply assumes the dimensions already carry semantic weight. That is precisely what still needs argument, especially for the non-teleosemantic dimensions.
- `"They're also right that teleosemantics provides the normative resources the problem demands: correctness conditions require selection history, and selection history is what distinguishes representations from mere correlations."` Issue: this sits badly with the earlier claim that correctness conditions are distributed across dimensions. The conclusion reasserts a stricter teleosemantic line than the body actually defends.

### Suggested focus

- Decide whether teleosemantic selection is necessary for content or just one contributor to stronger/weaker grounding.
- If the view is genuinely pluralist, specify which dimensions independently support satisfaction conditions and how misrepresentation is possible on each.
- Separate semantic normativity from mere reliability, coordination success, and inferential competence.
- Clarify whether pre-training, post-training, and in-context learning instantiate different kinds of function or merely different evidential bases for attributing the same function.

## 2. Raphaël Millière

### Pass/flag

| Section | Judgment |
|---|---|
| Introduction | Flag |
| The target argument | Pass |
| Groundedness as a cluster property | Flag |
| Communicative calibration | Flag |
| The octopus test revisited | Flag |
| Adjacent accounts | Flag |
| Conclusion | Flag |

### Specific concerns

- `"But the framework invites a binary verdict -- grounded or not -- that obscures what's actually at stake."` Issue: this is the hinge of the paper, and it is underargued. `Invites` is vague. You need textual evidence that the target view really commits itself to an all-or-nothing verdict rather than to context-sensitive satisfaction of two already gradable conditions.
- `"The framework, in other words, already contains the resources for a graded analysis. The binary presentation obscures this."` Issue: if the target already contains those resources, then your contribution may be a reinterpretation of our framework rather than a substantive alternative to it. The paper currently wants both claims at once.
- `"The move I'm proposing is to replace the threshold question ... with a profile question ..."` Issue: why replace rather than supplement? If the teleosemantic conditions still matter, the threshold question has not disappeared. The paper overstates the distance between the two views.
- `"This doesn't solve the VGP by itself. But it provides a stabiliser that the binary framework systematically undercounts."` Issue: the target paper already distinguishes communicative grounding and denies that it suffices. Showing that feedback improves calibration does not yet show that communicative grounding belongs inside the constitutive account of referential grounding.
- `"Suppose the octopus were trained on messages from thousands of speakers with feedback correcting its errors... At some point the intuitions waver..."` Issue: that is no longer the octopus case. You have added the very extra-worldly constraints the original thought experiment withholds. That does not rebut the claim that form alone is insufficient.
- `"Contemporary LLMs differ from the octopus in exactly these ways."` Issue: `exactly` is too strong. Some of the listed differences are matters of scale and deployment ecology, not clear semantic differences of the kind the target dispute concerns.
- `"The disagreement here is about the architecture of the answer, not its foundations."` Issue: then state the residual disagreement with precision. As written, the paper alternates between charging the target with binarism and borrowing its core teleosemantic machinery. The distinct thesis stays blurry.

### Suggested focus

- Quote the exact places where the target paper commits to a thresholded or binary verdict, or soften the claim to `extension` or `reframing`.
- Delimit what the profile framework adds beyond the target paper's talk of appropriate causal-informational relations and extra-linguistic selection.
- Separate constitutive grounding conditions from downstream stabilizers that improve reliability or social uptake.
- Rebuild the octopus section so it answers the form-only challenge without changing the case so drastically that the target objection no longer applies.

## 3. Richard Boyd

### Pass/flag

| Section | Judgment |
|---|---|
| Introduction | Flag |
| The target argument | Pass |
| Groundedness as a cluster property | Flag |
| Communicative calibration | Flag |
| The octopus test revisited | Flag |
| Adjacent accounts | Flag |
| Conclusion | Flag |

### Specific concerns

- `"The structure here is that of a homeostatic property cluster (HPC): a category defined not by necessary and sufficient conditions but by a cluster of properties held together by causal mechanisms..."` Issue: the paper states the schema, then immediately blurs the key distinction. Teleosemantic selection, causal-informational coupling, communicative calibration, and inferential-role structure are introduced as `stabilising mechanisms` but then used as the profile dimensions themselves. Are these the clustered properties, the sustaining mechanisms, or both?
- `"The dimensions of a system's groundedness profile ... are causally linked ... but can come apart. The profile is projectible, not merely descriptive."` Issue: this is assertion, not demonstration. `Projectible` is an earned label. You need an actual inductive payoff or at least a worked prediction schema, not a promissory sentence.
- `"These dimensions can come apart. A system might score high ... Another might score high..."` Issue: dissociation can be informative, but too much dissociation destroys the rationale for treating the case as a single cluster kind. The paper uses separability to buy nuance without paying the price it imposes on the HPC claim.
- `"At least four stabilising mechanisms are visible in the existing literature."` Issue: `visible in the existing literature` is not a homeostatic story. Where are the maintenance relations? What keeps the cluster together under perturbation? What are the feedback loops?
- `"Across successive models, the cumulative effect of millions of corrective exchanges pushes the population of models toward more reliable worldly reference."` Issue: this might be one candidate mechanism, but the paper presents it by analogy rather than by mechanism. You need a causal pathway from correction practices to clustered semantic properties, not just a training-ecology sketch.
- `"But 'solve versus circumvent' is a binary verdict applied to an HPC kind -- like asking whether a borderline species is or isn't a natural kind..."` Issue: this analogy is sloppy. Borderline cases do not by themselves vindicate an HPC analysis, and the species comparison reads like borrowed authority rather than disciplined transfer.
- `"These are questions we can investigate, and their answers will determine whether groundedness profiles are genuinely projectible..."` Issue: exactly. Until those answers are in hand, projectibility is a research agenda, not a result. The paper currently writes as if the HPC classification has already been earned.

### Suggested focus

- Separate the cluster properties from the mechanisms that allegedly stabilize them.
- Name one or two concrete homeostatic mechanisms and spell out how they maintain co-occurrence across cases.
- State what empirical regularities would count as evidence that `groundedness profile` is genuinely projectible.
- If the evidence base is not there yet, scale the claim down from `HPC kind` to `multidimensional heuristic` or `research program`.

## 4. Randy Harris

### Pass/flag

| Section | Judgment |
|---|---|
| Introduction | Flag |
| The target argument | Pass |
| Groundedness as a cluster property | Flag |
| Communicative calibration | Pass |
| The octopus test revisited | Flag |
| Adjacent accounts | Flag |
| Conclusion | Flag |

### Specific concerns

- `"This is a productive contribution, and it's worth being explicit about what it gets right."` Issue: the concession is well-intentioned but generic. If you want the audience to believe the critique is fair, name the target paper's strongest achievement in a way the target authors themselves would endorse, not just in a tone of civility.
- `"But the framework invites a binary verdict -- grounded or not -- that obscures what's actually at stake."` Issue: the attack arrives before the reader has seen enough evidence that the target really deserves it. The rhetoric shifts from charitable to adversarial too fast.
- `"The move I'm proposing is to replace the threshold question ... with a profile question ..."` Issue: this is the core move, and it is delivered in abstraction. The reader needs a concrete before-and-after case here, not a pile of nouns.
- `"The structure here is that of a homeostatic property cluster (HPC)... The move is compatible with deflationary approaches ... What makes HPC kinds scientifically useful is their projectibility..."` Issue: this paragraph tries to define the framework, locate it in philosophy of science, invoke another literature, and claim empirical payoff in one sweep. It is overcompressed and rhetorically top-heavy.
- `"Language produced before widespread LLM deployment is something like low-background steel manufactured before atmospheric nuclear testing..."` Issue: this analogy pulls attention away from the argument. It is vivid, but not clarifying, and many readers will have to stop to decode it.
- `"The profile framework sits between positions in the current debate. Five recent accounts illustrate the space."` Issue: the section that follows reads like a sequence of mini book reports. The same paragraph rhythm repeats five times: state a view, translate it into profile terms, note the limit. It feels dutiful rather than strategically argued.
- `"The metaphysical overpressure lifts."` Issue: stylish line, weak payoff. The paper should end by saying in plain language what the reader can now do or see that was blocked before.

### Suggested focus

- Make the charitable reconstruction more exact before you pivot to criticism.
- Introduce the profile framework with one concrete case, then generalize.
- Unstack the jargon in the HPC section; define one thing at a time.
- Cut analogies that do not carry argumentative weight.
- Make the adjacent-accounts section selective and strategic rather than comprehensive and repetitive.

## 5. Carl Zimmer

### Pass/flag

| Section | Judgment |
|---|---|
| Introduction | Flag |
| The target argument | Flag |
| Groundedness as a cluster property | Flag |
| Communicative calibration | Pass |
| The octopus test revisited | Flag |
| Adjacent accounts | Flag |
| Conclusion | Flag |

### Specific concerns

- `"TODO: Write abstract (max 200 words per PhiMiSci guidelines)."` Issue: there is no front door. A reader outside the immediate dispute has no quick way to understand the claim, the stakes, or the result.
- `"Referential grounding isn't a single threshold to cross. It's a cluster property with degree structure, where teleosemantic selection history is one stabilizer among several."` Issue: this is insider language stacked on insider language. A first-read audience has to decode `cluster property`, `degree structure`, `teleosemantic selection history`, and `stabilizer` before it knows what the paper actually claims.
- `"The structure here is that of a homeostatic property cluster (HPC)... What makes HPC kinds scientifically useful is their projectibility..."` Issue: this is where the prose becomes punishing. You are asking readers to swallow a framework definition, a philosophy-of-science import, and a methodological promise before you have shown them one concrete example that makes the move feel necessary.
- `"A vision system with direct sensory transduction scores higher here..."` and `"In profile terms, the octopus scores near zero on every dimension."` Issue: the paper keeps slipping into scorecard language. That makes the argument sound mechanical and thin, as if the framework were already measured and validated when it is still only being proposed.
- `"Language produced before widespread LLM deployment is something like low-background steel manufactured before atmospheric nuclear testing..."` Issue: this analogy is too obscure to earn its keep. Readers who do not already know the reference will lose the thread, and readers who do know it still do not get more clarity about grounding.
- `"The profile framework sits between positions in the current debate. Five recent accounts illustrate the space."` Issue: this section is a dense parade of names, views, and compressed objections. It is hard to track on first read because the paper keeps switching authors and vocabularies without giving the reader a stable concrete example.
- `"The metaphysical overpressure lifts."` Issue: nice phrase, vague meaning. End on one concrete consequence instead of a flourish.

### Suggested focus

- Write the abstract before doing anything else.
- Bring one concrete example to the front of the profile section and keep returning to it.
- Reduce the jargon load by choosing fewer framing terms and repeating them consistently.
- Strip out the low-background-steel analogy.
- Cut the adjacent-accounts section down to the two or three contrasts that do real work.
