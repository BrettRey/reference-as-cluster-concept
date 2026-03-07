# Richard Boyd Review

## Overall assessment

**Overall verdict: Flag.**

The paper has a serious and potentially useful idea: grounding should not be treated as an all-or-nothing status, and multiple causal influences may matter. But the current draft does **not yet earn the use of the Homeostatic Property Cluster framework**. What it presently offers is closer to a multidimensional assessment rubric than to an HPC account. In my framework, three things are needed:

1. A **cluster of properties**.
2. **Homeostatic mechanisms** that causally tend to produce and sustain the co-occurrence of those properties.
3. Some basis for **projectibility**: knowing that a system has some of the clustered properties should support non-accidental inferences about others.

The draft gestures at all three, but it mostly **asserts** them. It also runs together **properties, mechanisms, etiologies, and enabling conditions**. That is the central philosophical problem.

## Section verdicts

| Section | Pass/Flag | Reason |
|---|---|---|
| Introduction | **Flag** | It announces the HPC move too quickly and treats “degree structure” as if that already established an HPC kind. |
| The target argument | **Pass** | Fair reconstruction of the target paper and a useful setup for the disagreement. |
| Groundedness as a cluster property | **Flag** | This is the crucial section, and it currently conflates clustered properties with the mechanisms supposed to sustain them. Projectibility is asserted, not shown. |
| Communicative calibration | **Flag** | Identifies a plausible social influence, but does not yet show a distinct homeostatic mechanism for representational groundedness in LLMs. |
| The octopus test revisited | **Flag** | The framework is used to redescribe the case rather than to generate a tested prediction about it. |
| Adjacent accounts | **Flag** | The comparisons depend on an unearned HPC status and on analogies to natural kinds that are presently too loose. |
| Conclusion | **Flag** | Stronger than the argument warrants. It states as achieved what remains a promissory note. |

## Specific concerns

1. **Degree structure is not enough for HPC**

   > “Referential grounding isn't a single threshold to cross. It's a cluster property with degree structure...” (`main.tex:37`)

   The inference here is too fast. Many things admit of degrees without being HPC kinds. Vagueness, scalarity, and multidimensionality do not by themselves establish homeostatic clustering. You need an argument that groundedness is not merely gradable, but **kind-like** in the specific HPC sense.

2. **You treat mechanisms and dimensions as the same thing**

   > “The dimensions of a system's groundedness profile... are causally linked... At least four stabilising mechanisms are visible...” (`main.tex:63`)

   This is the draft’s deepest structural problem. In an HPC account, the **properties** cluster; the **mechanisms** help explain why. Here the paper oscillates between calling the four items “dimensions” of the profile and “stabilising mechanisms.” But those four items are not of a single type:

   - `teleosemantic selection` is an etiological process or history.
   - `communicative calibration` is a social feedback process.
   - `causal-informational coupling` looks more like a relational condition or property.
   - `inferential-role structure` looks like an organizational property or disposition.

   Until you separate **clustered properties** from **homeostatic mechanisms**, the HPC claim remains conceptually unclear.

3. **Projectibility is asserted, not demonstrated**

   > “The profile is projectible, not merely descriptive.” (`main.tex:63`)

   This sentence does argumentative work the paper has not done. An HPC kind is scientifically useful because it supports non-accidental induction. The draft gives no actual pattern of induction here. What exactly should I be able to predict from partial knowledge of a model’s groundedness profile? Across what class of systems? Under what interventions? These questions are not optional; they are central.

4. **The dissociation examples threaten the cluster claim**

   > “These dimensions can come apart.” (`main.tex:73`)

   Some dissociation is fully compatible with HPC theory. But this section currently emphasizes dissociability more than clustering. If the dimensions can come apart too freely, then you have not identified a cluster at all; you have identified a checklist. You need to say which co-occurrences are expected **non-accidentally**, which failures are exceptional, and what mechanisms explain both the usual co-occurrence and the atypical breakdowns.

5. **Normativity is not automatically ‘distributed across dimensions’**

   > “Correctness conditions don't vanish~-- they're distributed across dimensions.” (`main.tex:75`)

   This is too quick. HPC theory does not itself provide representational normativity. If teleosemantic selection is doing the norm-conferring work, say so. If the claim is instead that communicative calibration or inferential-role structure independently ground correctness conditions, that needs a separate argument. Otherwise the paper risks sliding from a theory of representational content into a looser theory of success, reliability, or social acceptability.

6. **The move from Clark-style coordination to LLM homeostasis is underargued**

   > “Reference... isn't established once and then communicated. It's stabilised *through* the communicative process.” (`main.tex:84`)

   Clark’s discussion concerns conversational coordination among agents already embedded in shared practices. That is not yet a homeostatic mechanism for a kind of representational state. The paper needs a tighter bridge from **token-level repair in conversation** to **type-level clustering of properties in model representations**.

7. **The inter-generational feedback story may collapse into teleosemantic selection**

   > “Across successive models, the cumulative effect of millions of corrective exchanges pushes the population of models toward more reliable worldly reference.” (`main.tex:86`)

   If this is a genuine mechanism, specify how it differs from the paper’s first mechanism, selection. If corrective exchanges matter because they shape future fine-tuning objectives and training data, then communicative calibration may simply be one route by which teleosemantic selection operates. That may be a perfectly good point, but then it is not clearly a distinct stabiliser. Right now the ontology of the framework is muddy.

8. **Putnam’s division of linguistic labour is doing less work here than claimed**

   > “LLMs inherit a version of this structure.” (`main.tex:88`)

   Perhaps they inherit traces of community-level usage. But Putnam’s point concerns speakers located within a normative social practice, with deference to expert users. A model trained on corpus traces is not straightforwardly a participant in that practice. This analogy may support the claim that reference can be socially mediated. It does **not yet show** a homeostatic mechanism generating the relevant cluster of properties in LLMs.

9. **The octopus case is scored after the fact**

   > “In profile terms, the octopus scores near zero on every dimension.” (`main.tex:97`)

   This is diagnostic only if the framework had antecedent predictive force. As written, the paper takes an intuition pump, redescribes it in profile language, and counts that as support for the framework. That is not enough. Show what the HPC framing would predict in advance about systems with different training histories and coupling relations, then use the octopus case as one test among others.

10. **Causal impact on the environment is not the same as grounding-relevant coupling**

   > “systems that reshape the linguistic environment they inhabit aren't merely spinning the representational merry-go-round.” (`main.tex:99`)

   This is too weak as stated. Many systems alter their environments. That does not show that their internal states participate in the right sort of causal structure for reference. The question is not whether LLMs have downstream effects, but whether those effects are embedded in causal feedback loops that help sustain the clustering of grounding-relevant properties.

11. **The appeal to species and borderline natural kinds is rhetorically risky**

   > “like asking whether a borderline species is or isn't a natural kind...” (`main.tex:108`)

   This analogy is currently strained. Species are useful exemplars in HPC discussions because there are identifiable reproductive, developmental, ecological, and evolutionary mechanisms that help sustain property clustering. The paper has not yet specified comparably robust mechanisms for groundedness. Until it does, the species comparison looks like borrowed authority rather than earned analogy.

12. **The conclusion outruns the evidence**

   > “The groundedness profile is that framework.” (`main.tex:127`)

   No: at most, the paper has identified a promising research program. It has not yet shown that groundedness is an HPC kind rather than a useful pluralist heuristic. That distinction matters.

## Suggested focus for revision

1. **Decide whether this is really an HPC claim or a pluralist profile claim.**

   If you want the Boyd/HPC framing, you need to meet the extra burden. If you do not want to meet it, scale the claim back and present the view as a multidimensional framework for assessing grounding.

2. **Separate clustered properties from homeostatic mechanisms.**

   Right now the paper mixes them. You need one level for the properties that supposedly co-occur and another for the causal processes that tend to sustain that co-occurrence.

3. **State the candidate cluster explicitly.**

   What are the grounding-relevant properties that cluster? Stability under correction? Cross-context referential reliability? Patterned misrepresentation? Robustness under domain shift? Successful deference to socially distributed expertise? The paper needs an explicit inventory.

4. **Show why the mechanisms are genuinely homeostatic.**

   For each proposed mechanism, explain how it tends to reproduce or stabilize the cluster over time. “It matters” is not enough. The question is whether it helps sustain the non-accidental co-occurrence of properties.

5. **Give actual projectibility claims.**

   Specify what should be predictable if the framework is right. For example: if a system has stronger world-involving feedback and retraining loops, what else should we expect it to do better, and under what conditions? Without this, “projectible” remains ornamental.

6. **Clarify the status of normativity.**

   If teleosemantic selection remains the sole source of correctness conditions, say that the other mechanisms stabilize reliability or anchoring without themselves conferring normativity. If not, make the alternative case explicitly.

7. **Tighten or soften the natural-kind analogy.**

   The analogy to biological natural kinds is not impossible, but it is currently too easy. Either defend the analogy by identifying comparably robust homeostatic processes, or recast the claim more modestly as an engineered or socially scaffolded cluster.

## Bottom line

The paper’s best insight is not yet that groundedness **is** an HPC kind. It is that the grounding debate may require attention to multiple interacting causal influences rather than a single threshold test. That is promising. But unless the paper distinguishes clustered properties from the mechanisms that sustain them, and unless it gives real projectibility claims, the invocation of Boyd/HPC will read as a metaphor for “complex and graded” rather than as a defensible theoretical application.
