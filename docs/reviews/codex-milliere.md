# Review as Raphaël Millière

## Overall assessment

This is a serious and often charitable reply. The reconstruction is strongest when it summarizes our taxonomy, our limited claim about intrinsic meaning, and our reliance on mediated causal-informational relations plus selection history. The weak point is the paper's central framing of our view as committed to a strict binary. That overstates the disagreement and, in a few places, slides into strawman territory.

My main concern is structural. The reply says, on the one hand, that our framework already contains the resources for graded analysis. On the other hand, it presents the groundedness-profile view as a distinct alternative to our account. Those claims pull in opposite directions. Either the profile framework is an internal elaboration of our view, or it rejects our constitutive claim that referential grounding requires the relevant causal-informational and historical relations. At present, it tries to do both.

## Pass / Flag by section

| Section | Verdict | Reason |
|---|---|---|
| Introduction | Flag | Fair opening summary, but the core framing already overstates the "binary" charge. |
| The target argument | Pass | This is broadly fair and accurate. |
| Groundedness as a cluster property | Flag | This is where the paper overstates the novelty of its proposal and under-describes the target view. |
| Communicative calibration | Flag | This section mischaracterizes our treatment of communicative grounding and does not show that calibration is an independent grounding-maker. |
| The octopus test revisited | Flag | The section partly restates our own anti-octopus move while presenting it as a distinct correction. |
| Adjacent accounts | Pass | Mostly tangential to the fairness question about our paper; no major mischaracterization of our view here. |
| Conclusion | Flag | The conclusion repeats the strongest overstatement: that our view is simply a binary framework that the profile view replaces. |

## Specific concerns

### Introduction

- Quote: "But the framework invites a binary verdict -- grounded or not -- that obscures what's actually at stake."  
Issue: This is too strong as a characterization of our paper. We do state constitutive conditions for referential grounding, so yes, there is a distinction between satisfying them and not satisfying them. But the paper already allows substantial variation in how those conditions are met: direct vs mediated causal relations, post-training vs pre-training vs in-context learning, and limited-domain vs broad-domain grounding. That is not the same as a crude all-or-nothing picture.

- Quote: "Referential grounding isn't a single threshold to cross."  
Issue: If this is meant as a criticism of our view, it needs more care. Our claim is that referential grounding has constitutive conditions. That is compatible with there being degrees of robustness, breadth, or reliability once those conditions are met. The reply currently treats "condition-based" and "binary in every relevant sense" as equivalent. They are not equivalent.

### The target argument

- Quote: "The sole contention is that LLM internal states can satisfy conditions for referential grounding, making their outputs intrinsically meaningful in a specific technical sense."  
Issue: This is fair. Keep this level of precision. It is one of the strongest sentences in the paper because it captures the modesty of our original claim.

- Quote: "Second, the causal-informational relations needn't be direct."  
Issue: Also fair, and important. The later critique should make more use of this point, because it already shows that our account is not beholden to a simple embodiment-versus-no-embodiment dichotomy.

### Groundedness as a cluster property

- Quote: "What I want to press on is the framework's implicit binarism: the two conditions, taken jointly, create a threshold that a system either crosses or doesn't."  
Issue: This is the central overstatement. Our paper gives necessary conditions for referential grounding. It does not follow that we deny all relevant gradience. Indeed, section 6 explicitly distinguishes stronger and weaker routes to grounding, treats some routes as speculative, and allows grounding "in some limited, formally constrained domains." If you want to argue against our constitutive conditions, do that directly. Do not redescribe them as if they commit us to a simplistic verdict on every empirical question.

- Quote: "The framework, in other words, already contains the resources for a graded analysis. The binary presentation obscures this."  
Issue: This is closer to the truth, but it cuts against the paper's novelty claim. If our framework already contains those resources, then your proposal is at most a reframing or operational elaboration unless you show that communicative calibration and inferential-role structure can do grounding work independently of the causal-informational and historical conditions we identify.

- Quote: "First, teleosemantic selection ... Second, causal-informational coupling ... Third, communicative calibration ... Fourth, inferential-role structure ..."  
Issue: As stated, these dimensions mix constitutive conditions with merely supportive or evidential factors. In our view, causal-informational relations and selection history are what make representation possible. Communicative calibration and inferential-role structure may help stabilize, detect, enrich, or transmit content, but the paper does not yet show that they are independent sources of representational normativity. Without that argument, the profile framework looks like an empirical scorecard layered on top of our account, not a competitor to it.

- Quote: "Correctness conditions don't vanish -- they're distributed across dimensions."  
Issue: This is not yet an acceptable teleosemantic claim. You need to say what it means for communicative calibration or inferential-role structure to generate correctness conditions rather than merely presuppose them or help us track them. Otherwise the profile view risks dissolving the very normativity it says it preserves.

- Quote: "The framework also addresses a pressure that the binary approach handles less gracefully. Roloff ... argues that classical selected-effects teleosemantics 'cannot account for evolutionarily novel contents such as `democracy'..."  
Issue: This is not well aimed at our paper. We explicitly discuss representations of culturally constructed notions such as "democracy" and "university," and we appeal to ontogenetic learning, testimony, and social transmission rather than a narrow species-history model. If you want to use Roloff against us, you need to explain why our broadened historical story still fails, not simply invoke the objection to classical selected-effects teleosemantics in general.

### Communicative calibration

- Quote: "Coelho Mollo and Millière identify communicative grounding as a distinct notion but set it aside."  
Issue: This is not fair to our section 4.4. We do not merely set communicative grounding aside. We explicitly say that communicative and referential grounding are distinct but related, and that calibrating reference in conversation requires communicative grounding. So the section should not suggest that we ignore or marginalize the phenomenon.

- Quote: "In their elimination argument, communicative grounding is downstream of referential grounding -- you need representations that refer before you can calibrate shared reference."  
Issue: Again too strong. Our claim is that communicative grounding is not by itself sufficient to solve the Vector Grounding Problem. That is different from saying it is merely downstream or causally idle.

- Quote: "Across successive models, the cumulative effect of millions of corrective exchanges pushes the population of models toward more reliable worldly reference."  
Issue: If this means RLHF, DPO, curation, and retraining, then it is already squarely inside our selection-history story. If it means something more than that, the paper needs to say what it is and why it is not reducible to the historical condition we already emphasize.

- Quote: "This doesn't solve the VGP by itself. But it provides a stabiliser that the binary framework systematically undercounts."  
Issue: The first sentence is right. The second is unfairly phrased. Our framework does not "undercount" communicative factors; it classifies them as distinct from referential grounding while acknowledging their relation to it. The reply should argue that communicative processes contribute to satisfying the existing conditions, or openly argue that they are partly constitutive in their own right. Right now it oscillates.

### The octopus test revisited

- Quote: "In profile terms, the octopus scores near zero on every dimension."  
Issue: This is rhetorically neat but not very probative against our paper, because our own use of the octopus test is already to challenge the intuition that text-trained systems must therefore be ungrounded. Once you add the kinds of historical and causal relations we discuss, you are already moving in our direction.

- Quote: "Suppose its training explicitly selected for factual accuracy. Suppose it had indirect causal access to the world through the content of messages that systematically track worldly events."  
Issue: Exactly. But those are recognizably our two core conditions doing the work. So this thought experiment tends to confirm our framework more than it displaces it.

- Quote: "There's a further disanalogy the octopus test can't capture: LLMs now act in the world."  
Issue: This is suggestive, but as stated it risks confusing causal impact with representational grounding. A system's effects on the linguistic environment do not by themselves establish the right causal-informational or historical relations for aboutness. This point needs much tighter control.

### Adjacent accounts

- Quote: "The profile framework acknowledges that LLMs' causal contact with the world is mediated -- a lower score on one dimension than direct sensory transduction."  
Issue: No major fairness problem here. But note that this again sounds more like an empirical refinement of our position than a genuine alternative to it.

- Quote: "Where the profile framework adds specificity is in decomposing 'sufficient referential grounding' into identifiable, independently variable dimensions."  
Issue: This is the right way to pitch the contribution if you want to avoid overstating the disagreement. "Adds specificity" is much better than "replaces a binary framework."

### Conclusion

- Quote: "A binary framework -- grounded or not -- forces a verdict that the phenomena don't support."  
Issue: This repeats the paper's main overstatement. Our paper does force a verdict about whether referential grounding is present in a given case, because we are offering constitutive conditions for that notion. But it does not force a verdict about whether all grounding-relevant phenomena collapse into a single undifferentiated bit. Your own discussion shows that our paper already allows multiple routes, grades of robustness, and domain-specific cases.

- Quote: "Referential grounding is a cluster property stabilised by heterogeneous mechanisms: teleosemantic selection, causal-informational coupling, communicative calibration, and inferential-role structure."  
Issue: This may be a useful proposal, but it is not yet shown to be compatible with the target paper. In our framework, the first two are constitutive. The latter two are, at most, ancillary unless you provide a stronger argument. The conclusion should not present this as if it had already been established.

- Quote: "We don't need a single decisive criterion to determine whether vector representations mean anything."  
Issue: This is the clearest point of departure, and it should be owned as such. Our paper does argue that there are constitutive criteria for referential grounding. If you reject that, say so directly. Do not present the disagreement as merely one of emphasis or granularity.

## Suggested focus for revision

- Recast the central disagreement. Stop saying our paper is committed to a crude all-or-nothing picture. Say instead that it offers constitutive conditions for referential grounding, and that you want to add a further robustness profile for comparing cases that satisfy those conditions to different extents or in different ways.

- Decide whether the profile view is an extension of our framework or a rival to it. If it is an extension, present communicative calibration and inferential-role structure as supporting, enriching, or operationalizing groundedness once the constitutive conditions are in place. If it is a rival, then argue explicitly that those factors can partly substitute for selection history and causal-information, and defend the resulting account of normativity.

- Fix the treatment of communicative grounding. Acknowledge that our paper already says communicative and referential grounding are distinct but related, and that calibration of reference in conversation matters. Then explain exactly where you think our treatment remains insufficient.

- Tighten the novelty claim. Much of the most persuasive material in the paper shows that our framework already permits domain-sensitive and route-sensitive analysis. Lean into that. The paper becomes stronger if it presents the profile as a useful decomposition of grounding-relevant mechanisms rather than as a wholesale replacement of an allegedly binary target.

- Clarify the normativity story. If correctness conditions are "distributed across dimensions," specify which dimensions genuinely generate them and which merely support or transmit them. Without that distinction, the teleosemantic inheritance is underspecified.

- Rework the octopus section so that it does not accidentally vindicate our view. If the difference between the octopus and actual LLMs is precisely the presence of richer causal-informational and historical relations, then say that openly. The real question is whether communicative calibration adds anything over and above those relations.
