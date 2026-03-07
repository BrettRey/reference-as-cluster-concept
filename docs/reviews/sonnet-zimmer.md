# Carl Zimmer Review: "Groundedness Profiles"

**Reviewer perspective:** Science writer focused on clarity, accessibility, and whether complex ideas land for readers outside the subfield.

**Overall assessment:** This paper has serious strengths—the central analogy to homeostatic property clusters is clear and powerful, and the octopus/low-background steel examples work beautifully. But the prose frequently punishes rather than rewards careful readers. Jargon density is high, abstractions arrive before examples, and key moves happen in subordinate clauses where they're easy to miss. The paper reads like it's written for the 15 people who've already read both target papers and have strong intuitions about teleosemantics. A general philosophy audience will struggle.

---

## Section-by-Section Assessment

### Introduction (§1)
**Verdict: PASS with concerns**

**What works:**
- The opening paragraph efficiently orients readers to the debate
- The explicit acknowledgment of what the target paper gets right (para 3-4) is generous and clarifying
- The core claim about cluster properties vs. binary verdicts is clear

**Problems:**

**Problem 1: Front-loading technical machinery**
> "Their answer draws on teleosemantics. Referential grounding obtains, they argue, when a system's internal states satisfy two conditions: (1) they stand in appropriate causal-informational relations to the world, and (2) they have a history of selection that has endowed them with the function of carrying this information"

This drops "teleosemantics," "causal-informational relations," and "selection history" in the first substantive paragraph with no grounding. A reader who doesn't already know what teleosemantics is will be lost. You need one concrete sentence first: "Think of how a bird's eye evolved to track prey—its internal states carry information because evolution selected for that function."

**Problem 2: Conceptual moves buried in subordinate clauses**
> "But the framework invites a binary verdict—grounded or not—that obscures what's actually at stake."

This is the paper's central criticism, but it arrives as a subordinate clause after three paragraphs of stage-setting. A science writer would lead with the tension: "But here's the problem: treating groundedness as all-or-nothing forces a verdict the phenomena don't support."

**Problem 3: Roadmap is generic**
> "Section 2 reconstructs the target argument and its taxonomy. Section 3 introduces the groundedness-profile framework..."

Every philosophy paper has this. Tell me *why* I need to read each section. What question does it answer? What puzzle does it solve?

**Suggested focus for revision:**
- Open with one concrete example before introducing technical terms
- Move the central criticism ("binary verdicts obscure what's at stake") earlier and make it a full independent clause
- Give the roadmap narrative drive—each section should solve a puzzle the previous one raised

---

### The target argument (§2)
**Verdict: FLAG**

**Problem 1: Five technical terms in the first paragraph, no examples**
> "referential, sensorimotor, relational, communicative, and epistemic"

You list five grounding notions but don't give a single concrete example until the second paragraph. And even then, the examples are abstract: "ties representations to sensory or motor states." What does that *look* like? Give me a V1 neuron, a robot arm, a chess engine—something I can picture.

**Problem 2: The merry-go-round analogy appears too late**
> "Relational grounding can't escape the representational merry-go-round: however rich the inferential structure, it doesn't by itself yield world-directed correctness conditions"

The merry-go-round is your best analogy in this section. But it's buried in a dense paragraph about inferential structure. Pull it earlier. Make it visual: "It's like defining 'dog' as 'a mammal that barks' and 'mammal' as 'an animal like dogs.' You can spin forever without touching the world."

**Problem 3: Paragraph length**
Para 2 is 148 words. Para 3 is 158 words. These are slogs. Each makes multiple complex moves—elimination argument, teleosemantics, normativity—without breaking for air. A reader has to hold too much in working memory.

**Suggested focus for revision:**
- Open with concrete examples of each grounding notion (one sentence each)
- Move the merry-go-round analogy to the start of the elimination argument
- Break the long paragraphs: one move per paragraph
- Add a sentence showing *why* the elimination matters: "This winnowing is crucial. If sensorimotor and relational grounding can't do the work alone, we need a different kind of answer."

---

### Groundedness as a cluster property (§3)
**Verdict: PASS**

**What works:**
- The HPC framing is clear and motivated
- The four-dimensional framework (teleosemantic selection, causal-informational coupling, communicative calibration, inferential-role structure) is well-organized
- The examples of systems scoring differently across dimensions are concrete and helpful

**Problem 1: The HPC concept arrives too suddenly**
> "The move I'm proposing is to replace the threshold question... with a profile question... The structure here is that of a homeostatic property cluster (HPC)"

You introduce HPC mid-paragraph as if the reader already knows what it is. This is a *philosophy of science* concept that most philosophy of language readers won't have encountered. You need a standalone paragraph introducing it with an analogy: "Think of 'species' in biology. No single trait defines a species—instead, organisms cluster around a profile of traits (morphology, genetics, behavior) that tend to co-occur because causal mechanisms stabilize them. 'Species' is a homeostatic property cluster."

**Problem 2: The projectibility claim needs more support**
> "What makes HPC kinds scientifically useful is their projectibility: the clustering is reliable enough that knowing a system's position on some dimensions supports predictions about others."

This is doing heavy lifting, but you assert it rather than demonstrate it. Give an example: "If a system scores high on teleosemantic selection (it's been trained to be factual), you can predict it will also score higher on causal-informational coupling—the training pushes both dimensions together. That's projectibility."

**Suggested focus for revision:**
- Add a standalone paragraph introducing HPC with a non-technical analogy (species, chemical elements, disease categories)
- Demonstrate projectibility with a concrete prediction rather than defining it abstractly
- Consider moving the "Does this dissolve normativity? No." paragraph earlier—readers will have that worry immediately

---

### Communicative calibration (§4)
**Verdict: PASS**

**What works:**
- The Clark & Wilkes-Gibbs example is concrete and clear
- The two-timescale distinction (within-conversation vs. inter-generational) is insightful
- The Putnam division of linguistic labor analogy lands well

**Problem 1: The key mechanism is understated**
> "Across successive models, the cumulative effect of millions of corrective exchanges pushes the population of models toward more reliable worldly reference."

This is the crucial empirical claim—that RLHF and deployment feedback constitute genuine communicative calibration—but it's stated in a subordinate clause. Make it a full sentence with emphasis: "Here's what matters: across successive generations of models, millions of corrective exchanges push outputs toward more reliable worldly reference. The mechanism isn't identical to face-to-face repair, but the functional structure is analogous."

**Suggested focus for revision:**
- Elevate the inter-generational feedback claim to its own sentence
- Consider whether readers will accept the analogy between conversational repair and RLHF—you might need to defend it more explicitly

---

### The octopus test revisited (§5)
**Verdict: PASS** (strongest section)

**What works:**
- The octopus test is already a vivid thought experiment, and you use it effectively
- The low-background steel analogy is *superb*—concrete, surprising, and it does real explanatory work
- The regime-sensitivity argument is clear: "change the stabilizers and the intuition shifts"

**Problem 1: The low-background steel analogy is buried**
> "Language produced before widespread LLM deployment is something like low-background steel manufactured before atmospheric nuclear testing—uncontaminated by a technology that has since altered the background conditions."

This is gold, but it's in the middle of a 120-word paragraph about data contamination. Pull it out. Give it its own paragraph. Explain the analogy: "Low-background steel was manufactured before nuclear testing contaminated the atmosphere with isotopes. Steel made after 1945 carries trace radiation. Scientists who need truly clean steel salvage pre-war shipwrecks. Similarly, pre-LLM text is 'clean'—it reflects human usage uncontaminated by model outputs. That's changing."

**Suggested focus for revision:**
- Give low-background steel its own paragraph with full explanation
- Consider opening the section with the octopus scenario in more detail (most readers won't remember Bender & Koller's version)

---

### Adjacent accounts (§6)
**Verdict: FLAG**

**Problem 1: Five papers in rapid succession with no connective tissue**

You present Floridi, Havlík, Arai & Tsugawa, Williams, and Manheim as a list, each in its own paragraph. But the relationships between them aren't clear. Are these competing theories? Complementary frameworks? Partial solutions? The section reads like a lit review rather than an argument.

**Problem 2: The reader has to do too much work**
> "Their categorical analysis shows that LLMs lack unmediated access to the world and therefore can't solve the grounding problem in the classical sense. The profile framework acknowledges that LLMs' causal contact with the world is mediated—a lower score on one dimension than direct sensory transduction. But 'solve versus circumvent' is a binary verdict applied to an HPC kind—like asking whether a borderline species is or isn't a natural kind, when the cluster properties come apart at the boundary."

This paragraph makes three moves: (1) Floridi's claim, (2) your response, (3) an analogy to species. But the logic connecting them isn't explicit. Why does the HPC framework dissolve the solve/circumvent distinction? You need a sentence like: "The HPC framework rejects the question. 'Solve or circumvent' presupposes a binary threshold. But if groundedness is a cluster, systems can be partially grounded—scoring high on some dimensions, low on others."

**Suggested focus for revision:**
- Organize the five accounts thematically rather than as a list (e.g., "binary verdicts," "inferentialism," "structural correspondence")
- Make the relationships explicit: which accounts does your framework subsume? Which does it reject? Which does it complement?
- Cut or condense the weaker entries (Havlík adds little)

---

### Conclusion (§7)
**Verdict: PASS with concerns**

**What works:**
- The restatement of the central claim is clear
- The list of tractable empirical questions is concrete and valuable
- The final sentence ("The groundedness profile is that framework") has appropriate closure

**Problem 1: "The metaphysical overpressure lifts"**
> "The metaphysical overpressure lifts. We don't need a single decisive criterion..."

This is vivid but unclear. What is metaphysical overpressure? The pressure to give a binary verdict? The pressure to define representation in terms of necessary and sufficient conditions? State it plainly first: "The framework removes a false burden. We don't need to decide once and for all whether LLMs 'really' represent. We need to track the mechanisms that make representations more or less reliable."

**Suggested focus for revision:**
- Clarify "metaphysical overpressure" before deploying the phrase
- Consider whether the empirical questions (para 2) should come earlier—they're the payoff

---

## Cross-Cutting Concerns

### Jargon Density
**Problem:** The paper uses technical terms from multiple subfields (philosophy of language, philosophy of science, linguistics, AI) without sufficient grounding. A reader needs fluency in teleosemantics, HPC theory, and LLM training regimes to follow the argument. Each term is defensible, but the cumulative load is high.

**Examples:**
- "teleosemantics," "causal-informational relations," "selection history" (§1, no examples)
- "homeostatic property cluster," "projectibility" (§3, defined abstractly)
- "RLHF," "in-context learning," "next-token prediction" (§3-7, assumed knowledge)

**Suggested focus:** Every technical term needs one concrete example on first use. Not a definition—an example. "Selection history: think of how a bird's eye evolved to track prey."

### Paragraph Rhythm
**Problem:** Many paragraphs exceed 100 words (§2 para 2: 148 words; §2 para 3: 158 words; §5 para 3: 120 words). Long paragraphs make multiple complex moves without breaking for air. Readers lose the thread.

**Suggested focus:** Aim for 60 words, max 100. One move per paragraph. If you're making multiple claims, break them apart.

### Examples Before Abstractions
**Problem:** The paper frequently states abstract principles and then (if at all) illustrates them. Science writing reverses this: example first, principle second.

**Example:**
> "Causal-informational relations admit of degrees." (abstraction)
> "These connections are real, but they aren't the same as a V1 neuron's causal chain from retinal stimulation." (example)

**Reversed:**
> "Consider the difference between a V1 neuron and an LLM. The neuron has a direct causal chain from retinal stimulation to firing pattern. The LLM accesses the world through text produced by humans. Both are causal connections, but they differ in directness and robustness."

**Suggested focus:** Scan for abstract claims followed by examples. Reverse the order.

### Sentences Requiring Multiple Readings
**Problem:** Some sentences are structurally complex in ways that force re-reading.

**Example:**
> "The question isn't whether grounding is categorically present or absent but how much and what kind of grounding obtains, and through which stabilizing mechanisms."

This packs three ideas into one sentence: (1) not binary, (2) degree and type, (3) mechanisms. Break it:
> "The question isn't whether grounding is present or absent. It's how much grounding a system has, what kind, and which mechanisms sustain it."

**Another example:**
> "The move I'm proposing is to replace the threshold question ('Does this system satisfy both conditions?') with a profile question ('To what extent, and by what mechanisms, are this system's representations stabilised toward world-directed correctness?')."

The parenthetical questions are themselves complex. Simplify:
> "The move is from threshold to profile. Not 'Is this system grounded?' but 'How grounded, in what ways, and by what mechanisms?'"

**Suggested focus:** Look for sentences with multiple clauses, nested parentheticals, or three+ conjuncts. Break them apart.

---

## Specific Recommendations for Revision Priority

**High priority (do these first):**
1. **§2 (The target argument):** Add concrete examples of each grounding notion. Move the merry-go-round analogy earlier. Break long paragraphs.
2. **§3 (HPC framework):** Add a standalone paragraph introducing HPC with a non-technical analogy.
3. **§5 (Octopus test):** Give low-background steel its own paragraph with full explanation.
4. **Cross-cutting:** Scan for technical terms on first use and add one-sentence concrete examples.

**Medium priority:**
5. **§1 (Introduction):** Move the central criticism earlier. Improve the roadmap.
6. **§6 (Adjacent accounts):** Organize thematically rather than as a list. Make relationships explicit.
7. **Cross-cutting:** Break paragraphs over 100 words. Aim for one move per paragraph.

**Lower priority (polish phase):**
8. **§4 (Communicative calibration):** Elevate the inter-generational feedback claim.
9. **§7 (Conclusion):** Clarify "metaphysical overpressure."
10. **Cross-cutting:** Reverse examples and abstractions where appropriate.

---

## Final Verdict

**Can the paper be understood on first read?** Not by a general philosophy audience. Readers with background in teleosemantics and HPC theory will follow it. Others will struggle with jargon density and abstraction-first exposition.

**Does the paper reward or punish careful readers?** It punishes. The best ideas (HPC framework, low-background steel, octopus regime-sensitivity) are present, but they're buried in dense paragraphs with subordinate clauses doing heavy lifting. A careful reader will extract the argument, but they'll have to work harder than necessary.

**Do the analogies land?** Mixed. The merry-go-round is underused. Low-background steel is excellent but buried. The HPC framework needs a clearer analogy on first introduction.

**Bottom line:** This is a strong philosophical argument that reads like it's written for specialists. With targeted revisions—concrete examples on first use, shorter paragraphs, examples before abstractions—it could be accessible to a much wider audience. The bones are good. The prose needs lightening.

---

**Carl Zimmer**
Science writer
Review completed: 2026-03-07
