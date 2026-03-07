# Review: "Groundedness Profiles" from Raphaël Millière's Perspective

**Reviewer role:** Co-author of "The Vector Grounding Problem" (Coelho Mollo & Millière, 2026)

**Overall assessment:** This is a serious, well-informed engagement with our paper that understands the teleosemantic framework and respects the taxonomic work. However, the central claim—that we impose a binary framework that obscures degrees of grounding—mischaracterizes our position. We explicitly accommodate degrees along both dimensions (causal-informational relations and selection history). The "groundedness profile" framework is not a substantive alternative to our account; it's a relabeling of distinctions we already make, packaged with an HPC framework that adds theoretical overhead without clear empirical payoff.

That said, the reply makes one genuine contribution: the emphasis on communicative calibration as a *stabilizing mechanism* rather than merely a downstream consequence deserves more attention than we gave it. This is worth developing, but it doesn't require abandoning the two-condition framework.

---

## Section-by-Section Assessment

### §1 Introduction

**Verdict:** PASS with minor concerns

**Strengths:**
- Accurate characterization of our two conditions (lines 31-32)
- Acknowledges what we get right: taxonomic clarity, separating referential from relational grounding, extending teleosemantics to gradient-based selection
- Correctly identifies our descent from Harnad's Symbol Grounding Problem

**Concerns:**

1. **Line 37-38:** "But the framework invites a binary verdict—grounded or not—that obscures what's actually at stake."

   **Problem:** This is the paper's central claim, but it's false. We never say a system is either grounded or not. We say both conditions admit of degrees and can be satisfied to varying extents. See our discussion of mediated causal chains (p. 13-14) and the distinction between proximate and ultimate functions (p. 11-12). The binary reading is a strawman.

2. **Line 38:** "Referential grounding isn't a single threshold to cross."

   **Problem:** We don't claim it is. Our framework is explicitly about *conditions* that can be satisfied to varying degrees, not a threshold.

3. **Line 38-39:** "It's a cluster property with degree structure, where teleosemantic selection history is one stabilizer among several."

   **Problem:** This language ("stabilizer," "cluster property") imports Boyd's HPC framework as if it's doing theoretical work our account lacks. But our two conditions already capture the relevant degrees. What does the HPC packaging add beyond terminological novelty?

**Suggested focus:** If you want to argue that we *should* adopt an HPC framework, you need to show what explanatory or predictive work it does that our conditions don't already do. Right now it reads like conceptual repackaging, not a substantive advance.

---

### §2 The target argument

**Verdict:** PASS

**Strengths:**
- Accurate reconstruction of our taxonomy
- Correct characterization of the elimination argument
- Fair representation of our teleosemantic conditions
- Properly notes that we limit scope (we don't claim LLMs have beliefs, understanding, etc.)

**No concerns.** This is a fair, careful reading.

---

### §3 Groundedness as a cluster property

**Verdict:** FLAG—central mischaracterization

**Problem 1: We already accommodate degrees**

Lines 57-61:
> "What I want to press on is the framework's implicit binarism: the two conditions, taken jointly, create a threshold that a system either crosses or doesn't. Consider the conditions individually. Causal-informational relations admit of degrees."

**Response:** Yes, and we say this explicitly. We emphasize that LLMs' causal connections to the world are *mediated* (p. 13-14) and argue that mediation is a matter of degree, not kind. We distinguish direct perception from testimony-based learning and argue that both can ground reference, differing in *how* they establish causal-informational relations, not whether they do. This is not "implicit binarism"—it's explicit acknowledgment of degrees.

Lines 61-62:
> "Selection history raises parallel questions. The paper distinguishes proximate from ultimate functions and argues that training constitutes selection analogous to biological natural selection. But 'analogous' already signals degree."

**Response:** Correct! And we develop this at length (p. 11-12). We distinguish base pretraining from RLHF fine-tuning precisely because the selection pressure differs in strength and directness. We say the analogy is strongest for RLHF, weaker for pretraining. This is not "implicit binarism." You're pointing to our own graded analysis and calling it a missing feature.

**Problem 2: HPC framework adds overhead without gain**

Lines 62-63:
> "The move I'm proposing is to replace the threshold question ('Does this system satisfy both conditions?') with a profile question ('To what extent, and by what mechanisms, are this system's representations stabilised toward world-directed correctness?')."

**Response:** This is not a replacement. Our conditions already ask the profile question. "To what extent does this system have a selection history that tracks worldly features?" and "How robust are its causal-informational connections to the world?" are precisely the questions we analyze. Renaming them "stabilizers" and invoking Boyd doesn't change the substance.

Lines 63-64:
> "The structure here is that of a homeostatic property cluster (HPC): a category defined not by necessary and sufficient conditions but by a cluster of properties held together by causal mechanisms that tend to produce co-occurrence without guaranteeing it."

**Problem:** You haven't shown that our two conditions fail to capture the relevant variation. The HPC framework is designed for cases where properties cluster but can come apart in informative ways (Boyd's example: "species" where reproductive isolation and morphological similarity sometimes dissociate). But you haven't identified dissociations that our framework can't handle. Your four "stabilizers" either:

1. Collapse into our conditions (teleosemantic selection = our condition 2; causal-informational coupling = our condition 1), or
2. Are mechanisms that *contribute to* satisfying our conditions (communicative calibration shapes selection history; inferential-role structure contributes to causal-informational coupling for abstract terms)

**Suggested focus:** Either (a) show that our two conditions miss a *dimension* of grounding that your framework captures, or (b) show that HPC projectibility generates predictions our account can't make. Right now it's conceptual repackaging.

**Problem 3: The four "stabilizers"**

Lines 65-72: You list teleosemantic selection, causal-informational coupling, communicative calibration, and inferential-role structure.

**Response:** The first two are literally our conditions. The third (communicative calibration) is new and interesting—more below. The fourth (inferential-role structure) we explicitly reject as *sufficient* for grounding, though we acknowledge it contributes to content determination for some expressions (logical connectives, p. 9-10). But we argue it can't ground worldly reference on its own. You seem to agree (lines 71-72), so what's the dispute?

**One genuine contribution:**

Lines 69-70:
> "Third, communicative calibration: the degree to which a system's representations have been shaped by interactive feedback anchoring usage to shared worldly reference."

**Response:** This is interesting and deserves development. We treat communicative grounding as downstream of referential grounding (you need reference before you can calibrate it), and that's correct in one sense. But you're pointing to a causal mechanism—iterative corrective feedback in deployment—that *stabilizes* referential grounding over time. This isn't a separate dimension; it's a mechanism that strengthens selection history (condition 2). But the emphasis on timescales (within-conversation vs. inter-generational via RLHF) is valuable and underdeveloped in our paper. **This is worth keeping.**

---

### §4 Communicative calibration

**Verdict:** PASS with qualification

**Strengths:**
- Clark & Wilkes-Gibbs (1986) is a good citation for collaborative reference
- Putnam's division of linguistic labor is relevant
- Two-timescale analysis (within-conversation vs. inter-generational RLHF) is insightful

**Qualification:**

Lines 82-83:
> "This is correct as far as it goes. But it conflates the question of logical priority with the question of causal contribution."

**Response:** Fair. We emphasize logical priority—you need representations that *can* refer before you can calibrate their reference in a community. But you're right that causal contribution is a separate question, and communicative feedback *strengthens* referential grounding rather than merely presupposing it. The inter-generational RLHF mechanism (lines 86-87) is particularly important: corrective exchanges across millions of users shape the training of successor models, which is a form of selection for world-tracking accuracy. This fits within our framework (it's selection history, condition 2), but you're right that we undersell it.

**Suggested focus:** Develop this as a *mechanism* that satisfies our second condition, not as a competing framework. The timescale analysis is the real contribution here.

---

### §5 The octopus test revisited

**Verdict:** PASS

**Strengths:**
- Correct reconstruction of Bender & Koller's thought experiment
- Profile analysis explains the clear intuition: octopus scores zero on all dimensions
- "Regime-sensitive" is a good framing: change the stabilizers, intuitions shift
- LLM-octopus disanalogies are accurate (global corpus, RLHF feedback, deployment interaction)
- "Low-background steel" analogy is vivid and apt

**No concerns.** This section works well.

---

### §6 Adjacent accounts

**Verdict:** PASS

**Strengths:**
- Fair treatment of five recent positions
- Floridi, Havlík, Arai & Tsugawa, Williams, Manheim all accurately characterized
- Positioning is reasonable: profile framework sits between extreme skepticism and uncritical acceptance

**No concerns.** This is competent literature review.

---

### §7 Conclusion

**Verdict:** FLAG—overstates the disagreement

Lines 121-123:
> "The disagreement here is about the architecture of the answer, not its foundations. A binary framework—grounded or not—forces a verdict that the phenomena don't support."

**Response:** This is still the central mischaracterization. We don't use a binary framework. Our two conditions admit of degrees and we analyze those degrees explicitly. You're attacking a position we don't hold.

Lines 123-124:
> "Referential grounding is a cluster property stabilised by heterogeneous mechanisms: teleosemantic selection, causal-informational coupling, communicative calibration, and inferential-role structure."

**Response:** Teleosemantic selection and causal-informational coupling are our two conditions. Communicative calibration is a mechanism contributing to selection history. Inferential-role structure contributes to content determination but doesn't escape the representational merry-go-round (as you yourself acknowledge). What's the substantive difference?

Lines 125-126:
> "Instead of asking 'Is the VGP solved?' we can ask tractable, empirical questions about the homeostatic mechanisms that sustain the groundedness cluster: To what extent does RLHF stabilise world-directed correctness in fine-tuned models?"

**Response:** These *are* the questions we ask. See our analysis of RLHF (p. 14-15). You're not proposing new questions; you're restating ours in HPC terminology.

**Suggested focus:** If you want to argue for HPC reframing, show what *predictions* it generates that our framework doesn't. Right now the empirical questions you list are exactly what our conditions already ask.

---

## Summary of Concerns

### Critical problems (require revision)

1. **Central claim is false:** We do not impose a binary framework. Both conditions admit of degrees and we analyze those degrees explicitly. Lines 37-38, 57-61, 121-123 all mischaracterize our position.

2. **HPC framework does no explanatory work:** Your four "stabilizers" either collapse into our two conditions or are mechanisms contributing to them. You haven't shown what the HPC packaging adds beyond terminological overhead. Lines 62-64, 123-124.

3. **Misrepresents the disagreement:** We don't disagree about whether grounding admits of degrees. We agree. The dispute you've constructed is a strawman. Lines 121-123, 127.

### One genuine contribution worth developing

- **Communicative calibration as a stabilizing mechanism:** The emphasis on iterative corrective feedback, especially the two-timescale analysis (within-conversation vs. inter-generational RLHF), is valuable. This deserves more attention than we gave it. But it's a mechanism that satisfies our second condition (selection history), not a competing framework. §4 should be expanded and repositioned.

### Suggestions for revision

1. **Drop the binary strawman.** We accommodate degrees. If you want to argue that HPC framing is *better* than our two-condition framework, show what it predicts that we can't.

2. **Clarify the novelty claim.** Right now it reads like you're renaming our conditions "stabilizers," invoking Boyd, and claiming this is a new framework. Either show what the HPC machinery adds (projectibility? dissociations we can't handle?) or reframe the contribution as *extending* our account rather than replacing it.

3. **Foreground communicative calibration.** The two-timescale analysis (§4) is the real contribution. Develop it as a mechanism that strengthens selection history (our condition 2) rather than as a separate dimension. The RLHF feedback loop is undertheorized in our paper, and you're right to emphasize it.

4. **Cut the metaphysics.** Lines 127: "The metaphysical overpressure lifts" is rhetoric, not argument. Our framework is already naturalistic and empirically tractable. If you think HPC deflates metaphysical commitment further, say how.

---

## Final Verdict

This is a competent paper that engages seriously with our work. The taxonomy reconstruction is fair, the octopus revisit is insightful, and the literature positioning is reasonable. But the central claim—that we impose a binary framework—is false, and the HPC reframing adds overhead without clear gain.

The paper has *one* genuine contribution: the analysis of communicative calibration as a stabilizing mechanism operating on two timescales (within-conversation and inter-generational via RLHF). This is underdeveloped in our paper and worth emphasizing. But it fits within our framework (it's selection history, condition 2), so the case for an alternative architecture collapses.

**Recommendation:** Major revision required. Either (1) drop the binary strawman and reframe as an *extension* of our account emphasizing communicative calibration, or (2) provide evidence that HPC projectibility generates predictions our two-condition framework cannot.

---

## Tone Check

Am I being too harsh? Let me recalibrate. The paper is well-written, philosophically informed, and takes our work seriously. The literature engagement (§6) is excellent. The octopus section (§5) is insightful. The communicative calibration analysis (§4) is a real contribution.

But the core claim is wrong. We don't impose a binary. Our conditions are graded. The HPC repackaging doesn't add explanatory power. These aren't minor quibbles—they're the paper's central thesis. A reply paper that mischaracterizes the target's position needs to fix that before publication.

The author is capable of fixing this. The ingredients are here. Reframe as an extension, not a replacement. Foreground the calibration mechanism. Drop the strawman. This could be a strong paper.
