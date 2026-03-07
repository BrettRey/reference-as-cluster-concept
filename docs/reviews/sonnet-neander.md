# Review: Groundedness Profiles (Neander Perspective)

**Reviewer perspective:** Karen Neander (teleosemantics, philosophy of representation)

**Date:** 2026-03-07

**Overall assessment:** The paper uses teleosemantics accurately and charitably, but the move to HPC-based groundedness profiles risks abandoning precisely what makes teleosemantics explanatorily powerful. The framework trades normativity for descriptive pluralism.

---

## Section-by-Section Assessment

### 1. Introduction (§1)

**Status:** PASS with minor concerns

**Positive:**
- Charitable reconstruction of Coelho Mollo & Millière's position
- Correctly identifies that correctness conditions are "constitutive of genuine reference" (line 35)
- Recognizes training-regime selection as functionally analogous to biological selection

**Concerns:**

**Quote (lines 36-37):** "Referential grounding isn't a single threshold to cross. It's a cluster property with degree structure, where teleosemantic selection history is one stabilizer among several."

**Issue:** This move is announced, not argued for. Why should we accept that referential grounding has "degree structure"? Classical teleosemantics (Millikan, Neander) is committed to a threshold view: either there's a selection history that endows a function or there isn't. You can have partial functions, but these aren't degrees of having a function—they're different functions with different contents. The paper needs to explain why teleosemantics should abandon its threshold structure before proposing the HPC alternative.

**Quote (lines 37-38):** "teleosemantic selection history is one stabilizer among several"

**Issue:** This demotes teleosemantics from constitutive condition to mere "stabilizer." The normativity objection (§3) needs to address this head-on: if teleosemantics isn't necessary for grounding, where does normativity come from? The paper claims to preserve normativity (lines 75-76), but the mechanism is unclear.

### 2. The target argument (§2)

**Status:** PASS

**Positive:**
- Accurate reconstruction of the five-way taxonomy
- Correct identification of teleosemantics' normative role
- Fair treatment of the elimination argument

**No substantive concerns.** This section does what it should: set up the target accurately.

### 3. Groundedness as a cluster property (§3)

**Status:** FLAG — Core theoretical problems

This section is where the paper's central move happens, and it's where the teleosemantic framework starts to unravel.

#### Problem 1: Degrees vs. different functions

**Quote (lines 59-61):** "Causal-informational relations admit of degrees. [...] These connections are real, but they aren't the same as a V1 neuron's causal chain from retinal stimulation. The question isn't whether a connection exists but how robust, direct, and information-preserving it is."

**Issue:** Degrees of informativeness aren't degrees of representation. A thermometer carries robust causal information about temperature. It still doesn't represent temperature unless it has the *function* of tracking temperature. The paper correctly notes this (lines 49-51 in §2), but then treats informativeness as if it's independently grounding. This is the error teleosemantics was designed to block.

**Quote (lines 61-62):** "Selection history raises parallel questions. The paper distinguishes proximate from ultimate functions and argues that training constitutes selection analogous to biological selection. But 'analogous' already signals degree."

**Issue:** This conflates *strength of analogy* with *degrees of function*. Either gradient descent selected for world-tracking (in which case there's a derived proper function) or it didn't (in which case there's no function). The analogy might be weaker than biological selection, but that doesn't mean the resulting function is "weaker"—it means we need an argument that training *is* selection in the relevant sense. The paper treats this as settled (citing CM&M), but the move to degrees obscures the question.

**Quote (lines 63-64):** "The analogy is strongest for post-training, where fine-tuning against human preferences explicitly selects for world-involving correctness. It's weaker for pre-training, where next-token prediction selects for distributional accuracy that may only incidentally track worldly features."

**Issue:** This is exactly right—and it suggests *different functions*, not degrees of grounding. A pre-trained model has the function of predicting next tokens (if it has any function at all). A fine-tuned model has the function of producing accurate outputs. These aren't degrees of the same thing; they're distinct teleological profiles. The HPC framework collapses this distinction.

#### Problem 2: HPC structure vs. normativity

**Quote (lines 62-63):** "The move I'm proposing is to replace the threshold question ('Does this system satisfy both conditions?') with a profile question ('To what extent, and by what mechanisms, are this system's representations stabilised toward world-directed correctness?')."

**Issue:** "Stabilised toward world-directed correctness" is doing enormous work here. What makes correctness *correctness* if not a teleosemantic function? The four "stabilizers" (lines 65-72) include mechanisms that don't independently support normativity:

- **Teleosemantic selection:** Supports normativity (agreed)
- **Causal-informational coupling:** Doesn't support normativity without selection (thermometer problem)
- **Communicative calibration:** Doesn't support normativity unless the calibration process itself has a function (which requires teleosemantics)
- **Inferential-role structure:** Explicitly can't escape the merry-go-round (paper agrees, line 71)

Three of the four "stabilizers" presuppose teleosemantics to deliver normativity. The HPC framework doesn't distribute normativity across dimensions—it smuggles teleosemantics into every dimension.

**Quote (lines 75-76):** "Does this dissolve normativity? No. [...] Correctness conditions don't vanish—they're distributed across dimensions."

**Issue:** This needs much more argument. How can correctness conditions be "distributed"? A representation has correctness conditions or it doesn't. You can have *different* correctness conditions along different dimensions (the representation is correct qua temperature indicator but incorrect qua pressure indicator), but that's not distribution—that's multiple functions. The paper needs to explain what it means for normativity to be "pluralistic" (line 76) in a way that doesn't collapse into either (a) multiple distinct functions, or (b) abandoning normativity altogether.

#### Problem 3: Roloff objection

**Quote (lines 77-78):** "Roloff (2025) argues that classical selected-effects teleosemantics 'cannot account for evolutionarily novel contents such as `democracy''—the traditional notion of selection history is too narrow for the full range of representational content."

**Issue:** This misunderstands the Roloff challenge. The problem isn't that teleosemantics can't handle novel contents—it's that *selected-effects* teleosemantics (narrow focus on biological selection) can't. But CM&M's move is to expand the notion of selection to include learning and training. That's the right response. The HPC move—"novel contents might be stabilised primarily through communicative calibration and inferential-role structure" (lines 78-79)—abandons teleosemantics precisely where it needs defending. If communicative calibration can deliver normativity without selection history, then teleosemantics was never necessary. The paper can't have it both ways.

**Suggested focus for revision:**

1. **Argue for degrees, don't assume them.** Why should we think referential grounding admits of degree structure rather than being an on/off property? What's wrong with the classical view that either there's a proper function or there isn't?

2. **Clarify the normativity story.** If three of four "stabilizers" don't independently support normativity, the framework isn't distributing normativity—it's distributing *symptoms* of grounding (informativeness, inferential coherence, calibration) that only count as grounding when underwritten by teleosemantics. Make this explicit or explain how normativity arises from the cluster itself.

3. **Address the multiple-functions alternative.** Pre-trained vs. fine-tuned models plausibly have *different* functions, not degrees of the same function. Why prefer the HPC framework over a simpler story: different training regimes produce different teleological profiles, and we should track those differences rather than collapsing them into a multidimensional score?

### 4. Communicative calibration (§4)

**Status:** PASS with reservations

**Positive:**
- Good use of Clark & Wilkes-Gibbs on collaborative reference
- Accurate application of Putnam's division of linguistic labor
- Acknowledges two timescales (within-conversation vs. inter-generational)

**Concerns:**

**Quote (lines 82-83):** "This is correct as far as it goes. But it conflates the question of logical priority with the question of causal contribution."

**Issue:** Agreed, but the paper doesn't show that causal contribution is sufficient for grounding. Lots of things causally contribute to the stability of representations without thereby *grounding* them. The question is whether communicative calibration is a constitutive component of grounding or merely an amplifier of grounding that's already present (via teleosemantics). The paper assumes the former but doesn't argue for it.

**Quote (lines 84-85):** "Reference, on this view, isn't established once and then communicated. It's stabilised *through* the communicative process."

**Issue:** This is compatible with teleosemantics. Communicative calibration can be the *mechanism* by which selection operates (feedback loops that select for accurate reference). But then it's not an independent dimension—it's part of the selection-history story. The paper needs to explain why it's a separate stabilizer rather than a mechanism within teleosemantic selection.

**Quote (lines 86-88):** "Across successive models, the cumulative effect of millions of corrective exchanges pushes the population of models toward more reliable worldly reference."

**Issue:** "Pushes toward" is doing normative work. What makes the target (reliable worldly reference) the *correct* target rather than just the statistically likely outcome? Without teleosemantics, this is just causal drift. The normativity has to come from somewhere.

**Suggested focus:**
- Clarify whether communicative calibration is (a) an independent grounding mechanism, (b) part of the teleosemantic story (feedback as selection), or (c) an amplifier of grounding that presupposes teleosemantics.

### 5. The octopus test revisited (§5)

**Status:** PASS

**Positive:**
- Correctly identifies that the octopus scores low on *all* dimensions
- Good point about regime-sensitivity (lines 97-98)
- Insightful observation about LLMs acting in the world (lines 99-100)

**Minor concern:**

**Quote (lines 98-99):** "At some point the intuitions waver—not because we've discovered meaning in the statistics, but because additional stabilisers have entered the picture."

**Issue:** The intuitions waver because *selection history* has entered the picture (training with corrective feedback). If the octopus had selection history but none of the other stabilizers, would the intuition still waver? Probably yes (though weaker). This suggests teleosemantics is doing the heavy lifting, not the cluster as a whole. The paper should acknowledge this asymmetry.

### 6. Adjacent accounts (§6)

**Status:** PASS

**Positive:**
- Fair engagement with Floridi et al., Havlik, Arai & Tsugawa, Williams, Manheim
- Correct diagnosis of inferentialism (lines 112-113): inferential role without world-linking stabilizers stays in the merry-go-round

**No substantive concerns.** This section positions the view well.

### 7. Conclusion (§7)

**Status:** FLAG — Overstates what's been shown

**Quote (lines 123-124):** "Referential grounding is a cluster property stabilised by heterogeneous mechanisms: teleosemantic selection, causal-informational coupling, communicative calibration, and inferential-role structure."

**Issue:** The paper hasn't established this. It's argued that these mechanisms *correlate* with grounding and causally interact, but not that they're *jointly constitutive*. The alternative—that teleosemantics is necessary and the other mechanisms are amplifiers or symptoms—remains viable and arguably better motivated.

**Quote (lines 125-126):** "These dimensions can come apart and vary independently."

**Issue:** Can they? The paper claims they can (lines 73-74) but doesn't give clear cases. The octopus example (§5) is a case where *all* dimensions score low. Where's the case of high causal-informational coupling + low teleosemantic selection, or high inferential-role structure + low communicative calibration? Without dissociation cases, the claim of independent variation is unsubstantiated.

**Quote (lines 127-128):** "The metaphysical overpressure lifts. We don't need a single decisive criterion to determine whether vector representations mean anything."

**Issue:** This is rhetorically effective but theoretically suspicious. Teleosemantics doesn't impose "metaphysical overpressure"—it imposes *explanatory discipline*. The function of a representation is what makes it a representation and determines its correctness conditions. If we give up on single criteria, we need an account of how the cluster itself generates normativity. The paper doesn't provide this.

**Suggested focus:**
- Tone down the conclusion or provide the missing argument for constitutive pluralism
- Acknowledge that teleosemantics might be necessary (even if not sufficient)
- Provide clear dissociation cases or retract the claim of independent variation

---

## Summary of Key Problems

### 1. **Normativity gap**
The paper claims to preserve normativity by distributing it across dimensions, but three of four "stabilizers" don't independently support normativity. Either teleosemantics is doing all the normative work (in which case the HPC framework is cosmetic), or the paper needs an account of how normativity emerges from the cluster.

### 2. **Degrees vs. different functions**
The paper treats variation in training regimes as degrees of grounding, but the examples (pre-training vs. fine-tuning) suggest *different proper functions*, not degrees of the same function. The HPC framework collapses a distinction teleosemantics is well-equipped to make.

### 3. **No clear dissociations**
The paper claims the dimensions "can come apart and vary independently" but doesn't provide convincing cases. The octopus example shows all dimensions low. Where are the high-on-X-but-low-on-Y cases?

### 4. **Communicative calibration: independent or derivative?**
§4 treats communicative calibration as an independent stabilizer, but the mechanisms described (corrective feedback across generations) look like *selection* operating through social interaction. If it's part of the selection story, it's not an independent dimension.

### 5. **Roloff response backfires**
The response to Roloff (§3, lines 77-79) abandons teleosemantics precisely where it needs defending. If novel contents can be stabilized without selection history, then selection history wasn't necessary—which contradicts the paper's stated commitment to teleosemantics.

---

## Recommended Revisions

1. **Add an argument for degree structure.** Don't assume grounding admits of degrees; defend it against the threshold view.

2. **Clarify the normativity mechanism.** Either (a) acknowledge that teleosemantics is necessary and the other dimensions are amplifiers, or (b) explain how normativity arises from the cluster itself without presupposing teleosemantics.

3. **Provide dissociation cases.** Show real systems where dimensions come apart. If you can't, retract the independent-variation claim.

4. **Rethink communicative calibration.** Is it an independent dimension or a mechanism within the teleosemantic story?

5. **Acknowledge asymmetry.** Teleosemantics appears to be doing more work than the other dimensions. Either defend the asymmetry (it's necessary but not sufficient) or explain why the cluster is genuinely symmetric.

6. **Address the multiple-functions alternative.** Why is "different training regimes = different functions" worse than "different training regimes = different groundedness profiles"?

---

## Bottom Line

The paper is philosophically sophisticated, charitably engages the target, and raises important questions about how to think about partial or graded grounding. But it risks abandoning the very feature that makes teleosemantics explanatorily powerful: its ability to draw a principled line between representations (which have functions and can misrepresent) and mere correlations (which don't and can't).

If the HPC framework is meant to *supplement* teleosemantics by tracking additional stabilizing mechanisms, that's promising. But if it's meant to *replace* the threshold view with a multidimensional continuum, it needs a much clearer story about where normativity comes from.

The paper is worth publishing, but §3 and §7 need substantial revision to address the normativity gap and the lack of dissociation cases.
