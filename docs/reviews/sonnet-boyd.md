# Review: Groundedness Profiles

**Reviewer perspective:** Richard Boyd (originator of HPC theory)

**Date:** 2026-03-07

---

## Summary Verdict

This paper applies the Homeostatic Property Cluster framework to LLM grounding, arguing that referential grounding is a cluster property with degree structure rather than a binary threshold. The application is **creative and potentially valuable**, but it makes **critical errors** in understanding what makes an HPC kind genuinely homeostatic. The paper identifies four "stabilising mechanisms" but fails to demonstrate that these mechanisms actually produce homeostatic clustering. Correlations are asserted, not demonstrated. Projectibility is promised but not delivered.

**Recommendation:** Major revision required. The HPC framework is being misapplied. Fix the homeostatic mechanism claims or abandon the HPC framing.

---

## Section-by-Section Assessment

### §1 Introduction (lines 26-40)

**Verdict:** PASS with reservations

**Concerns:**

None for this section. The introduction correctly identifies the target paper's contribution and frames the reply's intervention.

**Reservations:**

The claim that "referential grounding isn't a single threshold to cross. It's a cluster property with degree structure" (lines 37-38) is the paper's central thesis, but at this stage it's merely asserted. The rest of the paper needs to demonstrate that groundedness actually has the causal structure of an HPC kind.

---

### §2 The target argument (lines 42-52)

**Verdict:** PASS

**Concerns:**

None. This is accurate exposition.

---

### §3 Groundedness as a cluster property (lines 54-77)

**Verdict:** FLAG — Critical failures in HPC application

**Major problems:**

#### 1. Confusing correlation with homeostatic mechanism (lines 63-64)

> "The dimensions of a system's groundedness profile — its position in a multidimensional space defined by stabilising mechanisms — are causally linked (training that improves causal-informational coupling tends to improve teleosemantic selection too) but can come apart."

This sentence reveals fundamental confusion about HPC kinds. The parenthetical claim — that training improving one dimension "tends to improve" another — is:

- **Empirically unsubstantiated:** No evidence is provided that these dimensions co-vary in actual systems
- **Theoretically weak:** "Tends to improve" suggests correlation, not homeostatic mechanism
- **Backwards:** An HPC kind isn't defined by dimensions that "can come apart" — it's defined by causal mechanisms that actively maintain clustering despite perturbations

**What's missing:** You need to show that there are actual causal processes that **actively sustain** co-occurrence of these properties and **resist** their dissociation. The biological examples I used (species, genes, disease syndromes) all involve active regulatory mechanisms. Where are those mechanisms here?

#### 2. The four "stabilising mechanisms" aren't mechanisms (lines 65-72)

The paper lists:
1. Teleosemantic selection
2. Causal-informational coupling
3. Communicative calibration
4. Inferential-role structure

**Problem:** These are dimensions of variation, not homeostatic mechanisms. A homeostatic mechanism is a causal process that tends to produce or maintain property co-occurrence. Examples from biology:

- **Gene regulation:** Feedback loops that maintain expression levels
- **Species boundaries:** Reproductive isolation mechanisms that prevent intermediate forms
- **Developmental canalization:** Robustness mechanisms that produce similar phenotypes despite genetic variation

The paper's "mechanisms" don't do this work. They're properties that might co-occur, not processes that causally sustain clustering.

**Test:** Ask yourself: If a system scores high on teleosemantic selection but low on communicative calibration, what causal process **actively pushes** it toward higher communicative calibration? The paper provides no answer because it hasn't identified genuine homeostatic mechanisms.

#### 3. Projectibility is asserted, not demonstrated (lines 63-64)

> "The profile is projectible, not merely descriptive."

This is the make-or-break claim for an HPC kind. Projectibility means: if you know a system's position on dimensions A and B, you can reliably predict its position on dimension C, because the clustering is causally maintained.

**What the paper needs to show:**
- Empirical evidence that these dimensions actually cluster in real systems
- Explanation of the causal processes that produce and maintain the clustering
- Predictions that follow from the clustering and could be tested

**What the paper provides:**
- Assertion that the clustering exists
- Assertion that it's projectible
- Promise that "knowing a system's training regime lets you predict its referential reliability across domains" (lines 125-126)

This isn't good enough. The promise is promissory. You need actual evidence.

#### 4. The dissociation examples undermine the HPC claim (lines 73-74)

> "A system might score high on inferential-role structure and communicative calibration but low on teleosemantic selection (a chat model fine-tuned for helpfulness without explicit factuality objectives). Another might score high on causal-informational coupling but low on communicative calibration (a sensor array with no interactive deployment)."

**This is exactly backwards.** In a genuine HPC kind, dissociations are **rare and informative** because homeostatic mechanisms resist them. The examples you give suggest these dimensions vary **independently** — which would mean there's no clustering to explain, no homeostatic maintenance, and therefore no HPC structure.

Compare to biological species: you don't find organisms with the genome of a wolf and the morphology of a deer, because developmental mechanisms prevent such dissociations. The fact that you **can** easily construct examples of systems with high scores on some "groundedness dimensions" and low scores on others suggests these dimensions aren't causally linked in the way HPC kinds require.

#### 5. Normativity claim needs work (lines 75-76)

> "A system can misrepresent along one dimension while performing well along another. The normativity is real but pluralistic."

This is potentially defensible, but you need to explain how pluralistic normativity differs from no normativity at all. If correctness conditions are fully dimension-specific with no causal links between dimensions, then calling it "pluralistic normativity" is just relabeling fragmentation.

---

### §4 Communicative calibration (lines 79-88)

**Verdict:** PASS with concern about mechanism identification

**Strength:**

The Clark & Wilkes-Gibbs material is well-handled, and the two-timescale distinction (within-conversation vs. inter-generational) is genuinely insightful.

**Concern:**

This section identifies a real causal process (corrective feedback across deployment cycles), but it still doesn't show how this process **homeostatic­ally links** communicative calibration to the other three dimensions. The question isn't whether communicative calibration happens — it's whether it causally produces co-occurrence with teleosemantic selection, causal-informational coupling, and inferential-role structure in a way that makes the cluster stable and projectible.

**What's missing:**

Show that systems undergoing heavy communicative calibration **thereby** improve on other dimensions, and that the improvement isn't accidental but causally sustained by the calibration process itself.

---

### §5 The octopus test revisited (lines 90-101)

**Verdict:** PASS — This is the paper's strongest section

**Strengths:**

- The "regime-sensitive" reframing is exactly right: the octopus by construction has no stabilisers operating
- The observation that contemporary LLMs differ from the octopus "in exactly these ways" (line 98) is well-supported
- The low-background steel analogy (lines 99-100) is vivid and apt
- The conclusion — that the octopus test doesn't generalize to systems with partial stabilizers — is sound

**Minor reservation:**

Even here, you're using "stabiliser" language that presupposes the HPC framework is correct. If §3's problems aren't fixed, this section's rhetorical force diminishes.

---

### §6 Adjacent accounts (lines 103-116)

**Verdict:** PASS with minor concern

**Strength:**

The five-way comparison is fair and well-positioned. The Floridi critique ("solve versus circumvent" is binary applied to an HPC kind) is particularly good.

**Concern:**

The claim about Arai & Tsugawa (lines 112-113) — that inferential role without other stabilisers remains in the "representational merry-go-round" — needs reconciliation with the relational grounding discussion in the target paper. You're asserting that inferential role can't substitute for referential anchoring, but this needs more argument, especially given that Brandomian inferentialism is specifically designed to avoid representationalist commitments.

---

### §7 Conclusion (lines 118-127)

**Verdict:** FLAG — Overpromises on projectibility

**Problem:**

Lines 125-127 promise that the framework generates "testable predictions about when those mechanisms will succeed or fail." But §3 provided no such predictions, no evidence of clustering, and no demonstration of homeostatic mechanisms.

The metaphor "the metaphysical overpressure lifts" (line 127) is rhetorically effective but substantively question-begging. The HPC framework doesn't lift metaphysical pressure — it replaces one kind of metaphysical commitment (necessary/sufficient conditions) with another (causal homeostatic mechanisms). If you haven't demonstrated the mechanisms, the pressure remains.

---

## Core Theoretical Problems

### 1. **What are the homeostatic mechanisms?**

An HPC kind requires causal processes that actively maintain property clustering. You've identified four dimensions of variation but haven't shown:

- What causal processes link them
- Whether those processes resist dissociation (homeostasis proper)
- Whether the clustering is stable across perturbations

**Example of what's needed:** Show that RLHF doesn't just improve teleosemantic selection in isolation — show that it causally drives improvements in causal-informational coupling and inferential-role structure **because** the three dimensions are mechanistically linked. Then show that this linkage is robust: perturbing one dimension creates corrective pressure toward realignment.

Without this, you have a multidimensional descriptive framework, not an HPC kind.

### 2. **Is the clustering empirically real?**

The paper asserts clustering but provides no evidence. You need:

- Data showing that systems high on one dimension tend to be high on others
- Explanation of why the correlation exists (the homeostatic mechanisms)
- Demonstration that the correlation is projectible (knowing position on some dimensions predicts position on others)

**Testable claim:** If groundedness is genuinely an HPC kind, then:

- Base models vs. RLHF-tuned models should differ systematically across all four dimensions
- Models with high causal-informational coupling should reliably show high inferential-role structure
- Interventions improving one dimension should produce measurable improvements on others

Do you have evidence for any of this? If not, the HPC framing is premature.

### 3. **Can the dimensions actually dissociate freely?**

Your dissociation examples (lines 73-74) suggest the dimensions are **independently variable**. This is fatal to the HPC claim. In genuine HPC kinds, dissociations are rare because mechanisms prevent them.

**Resolution options:**

- **Option A:** Show that the dissociations you describe are actually rare or unstable (systems with that profile collapse back toward the cluster)
- **Option B:** Weaken the HPC claim to something like "groundedness is a multidimensional space with some causal structure" but abandon projectibility claims
- **Option C:** Identify different dimensions that actually do cluster homeostatically

I suspect Option C is the right move, but it requires rethinking what the dimensions are.

---

## Suggested Focus for Revision

### Priority 1: Demonstrate homeostatic mechanisms or abandon HPC framing

You have two paths:

**Path A (Keep HPC framework):**

1. Identify actual causal processes that link your four dimensions
2. Provide empirical evidence that the dimensions cluster in real systems
3. Show that interventions on one dimension causally affect others
4. Demonstrate that the clustering is stable and projectible

This requires substantial new empirical work — probably comparing base models, RLHF models, and multimodal models across your four dimensions with quantitative measures.

**Path B (Multidimensional framework without HPC):**

1. Acknowledge that the four dimensions are independently variable
2. Drop projectibility claims
3. Reframe as a diagnostic framework rather than a natural kind claim
4. Focus on the practical value of tracking multiple dimensions separately

Path B is easier but less ambitious. It gives up the theoretical payoff of natural kind realism.

### Priority 2: Clarify what you mean by "stabilising mechanism"

Currently, you use "stabilising mechanism" to mean both:
- Dimensions of variation (e.g., "causal-informational coupling")
- Causal processes (e.g., "training that improves X tends to improve Y")

These need to be distinguished. A genuine homeostatic mechanism is a **causal process**, not a property. Revise the four-mechanism list to identify actual causal processes, or relabel them as "dimensions" and separately identify the mechanisms.

### Priority 3: Provide evidence for clustering

Find or generate data showing:
- Correlation structure across your dimensions in actual systems
- Stability of the correlations across model architectures and training regimes
- Predictive validity (dimension scores predict downstream performance)

Without this, the HPC claim is empirically ungrounded.

### Priority 4: Address the dissociation problem

Either:
- Show that the dissociation examples are unstable or rare
- Explain why freely dissociable dimensions still constitute an HPC kind (requires new argument)
- Accept that free dissociation undermines the HPC framework and revise accordingly

---

## Specific Textual Issues

### Line 63: "causally linked... but can come apart"

This is contradictory in the context of HPC theory. If they're causally linked by homeostatic mechanisms, they shouldn't easily come apart. Revise to clarify the strength and direction of causal linkage.

### Line 64: "projectible, not merely descriptive"

Assertion without demonstration. Either provide evidence or delete.

### Lines 73-74: Dissociation examples

These examples work against your thesis. Either explain why they're rare/unstable or remove them.

### Line 76: "pluralistic normativity"

Needs development. How does dimension-specific normativity differ from fragmented normativity? What holds the dimensions together if correctness conditions are fully independent?

### Lines 125-126: "testable predictions"

You haven't provided any. Either add them or remove this claim.

---

## Final Assessment

The paper has a genuinely interesting core idea: that grounding comes in degrees and varies along multiple dimensions. The octopus test discussion is sharp, the Clark & Wilkes-Gibbs material is insightful, and the comparison with adjacent accounts is fair.

But the HPC framework is being misapplied. You've identified dimensions of variation and asserted that they cluster, but you haven't demonstrated homeostatic mechanisms or provided evidence for projectible clustering. The dissociation examples actively undermine the HPC claim.

**Two options:**

1. **Ambitious revision:** Do the empirical work to demonstrate homeostatic clustering, or identify different dimensions that actually do cluster
2. **Conservative revision:** Drop the HPC framing, present this as a multidimensional diagnostic framework, and focus on the practical value of tracking multiple independently variable dimensions

Either way, the current draft overclaims. The HPC machinery does real work in biology and chemistry because homeostatic mechanisms are empirically demonstrable. If you want to use the framework for groundedness, you need to meet the same standard.

---

**Signed:** Richard Boyd (via Sonnet 4.5, 2026-03-07)
