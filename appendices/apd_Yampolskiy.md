# Appendix: Roman Yampolskiy's Warning About the Unsolved AI Control Problem

### 1. From AI Safety Research to a Warning About Uncontrollable Intelligence

Roman Yampolskiy, a computer scientist at the University of Louisville and one of the early researchers in AI safety and security, has emerged as a prominent advocate for halting the development of artificial superintelligence. His position rests on a fundamental observation: **despite extensive research, humanity has not discovered a demonstrated method for reliably aligning and controlling superintelligent AI systems.**

More significantly, Yampolskiy questions whether such control is achievable at all.

Unlike researchers who assume that alignment is a difficult but ultimately solvable engineering problem, Yampolskiy has devoted much of his research to investigating the theoretical limits of AI safety. His work examines whether increasingly intelligent systems can be reliably understood, predicted, verified, contained, and controlled.

In his 2021 essay _The Uncontrollability of Artificial Intelligence_, published by the Institute of Art and Ideas, Yampolskiy challenged a fundamental assumption underlying much of AI safety research: that the problem of controlling a superintelligent system must have a solution.

He argued that researchers had devoted substantial effort to developing safety mechanisms without first establishing whether reliable control was theoretically possible. In computer science, some problems are inherently unsolvable, regardless of how powerful the available computers become or how sophisticated the algorithms employed. Yampolskiy suggested that controlling an intelligence vastly superior to humanity might belong to this category.

His central concern was therefore not merely that researchers had failed to find a solution, but that **the scientific community was proceeding as though the existence of a solution could be taken for granted**.

[The Uncontrollability of Artificial Intelligence — IAI, 2021](https://iai.tv/articles/the-hard-problem-of-ai-safety-auid-1773?ts=1748458311)

Yampolskiy developed this argument systematically in his 2022 academic paper, _On the Controllability of Artificial Intelligence: An Analysis of Limitations_, published in the _Journal of Cyber Security and Mobility_.

The paper examined the AI control problem from multiple perspectives, drawing upon computer science, control theory, cybersecurity, philosophy, economics, and the emerging field of AI safety. After reviewing existing approaches, Yampolskiy concluded that no rigorous demonstration of the general solvability of the AI control problem had been established. He further presented arguments suggesting that certain forms of complete control are impossible.

The distinction is important. Yampolskiy does not deny that AI systems can be made safer, nor that particular forms of control are achievable. His argument is that **partial improvements in safety should not be confused with a reliable solution to the problem of controlling superintelligence**.

[On the Controllability of Artificial Intelligence — academic paper, 2022](https://journals.riverpublishers.com/index.php/JCSANDM/article/view/16219)

### 2. Why Reliable AI Alignment and Control Remain Unsolved

Yampolskiy's assessment rests on several interconnected obstacles that, in his view, prevent existing alignment techniques from providing adequate safety guarantees.

**The fundamental difficulty of defining human values.** A central challenge is determining what an AI system should actually optimize. Human values are complex, dynamic, and frequently inconsistent. Different individuals and cultures disagree about fundamental moral principles, while even a single person's preferences may change over time or conflict with one another.

In his 2022 paper, Yampolskiy examines the difficulty of translating human preferences into a coherent objective function. Even if an AI could accurately learn what people presently desire, this would not necessarily establish what is morally desirable or what humanity would ultimately consider beneficial.

Learning human behavior is not equivalent to discovering human values. People frequently act against their own interests, make irrational decisions, and disagree about which outcomes should be pursued. Consequently, an AI trained to imitate human preferences may reproduce these inconsistencies rather than resolve them.

This problem becomes especially significant when a superintelligent system must make decisions affecting humanity as a whole. Whose values should govern its actions? How should conflicting moral obligations be resolved? What should happen when human instructions contradict the system's understanding of human welfare?

Yampolskiy's conclusion is that the very objective of alignment remains inadequately specified.

**The inability to predict the behavior of superior intelligence.** In his 2020 paper _Unpredictability of AI: On the Impossibility of Accurately Predicting All Actions of a Smarter Agent_, Yampolskiy presented an argument for a fundamental limitation on predicting the actions of systems more intelligent than their human observers.

His reasoning is that an intelligence superior to humanity may discover strategies, solutions, and possibilities that humans are incapable of anticipating. Even if its ultimate objective were known, its intermediate actions could remain unpredictable.

The consequences for AI safety are profound. Researchers cannot reliably prevent dangerous behavior if they cannot anticipate the strategies through which a powerful system might pursue its objectives.

Yampolskiy's argument does not mean that every action of an advanced AI would be unpredictable, or that statistical predictions would become useless. Rather, he argues that complete and consistently accurate prediction of a superintelligent system's behavior is beyond human capabilities.

[Unpredictability of AI — Journal of Artificial Intelligence and Consciousness, 2020](https://doi.org/10.1142%2FS2705078520500034?utm_source=chatgpt.com)

**The inability to fully understand AI decision-making.** Another obstacle concerns explainability and interpretability. Modern AI systems often operate through complex learned representations that are difficult to translate into comprehensible explanations.

Yampolskiy distinguishes between two related difficulties: _unexplainability_, in which a system cannot provide an adequate explanation of its decisions, and _incomprehensibility_, in which the explanation itself may exceed human understanding.

This distinction becomes particularly important with superintelligence. Even a system capable of explaining its reasoning might employ concepts, abstractions, or scientific knowledge beyond human intellectual capacities.

Human supervisors could therefore find themselves unable to evaluate the reasoning underlying consequential decisions. They might observe successful results without understanding why those results were achieved or whether the system was pursuing unintended objectives.

**The inability to verify that an AI system is safe.** Yampolskiy considers verification one of the most fundamental problems in AI alignment.

Traditional software engineering relies heavily on testing. Programmers expose systems to numerous situations, identify errors, and correct them. However, successful performance on a finite collection of tests cannot guarantee correct behavior under every possible future condition.

In his February 2024 paper _Untestability of AI and Unfalsifiability of AI Safety Claims_, Yampolskiy develops this argument specifically for artificial general intelligence.

Unlike narrow software designed for a restricted set of tasks, AGI could encounter an effectively unlimited variety of environments, objectives, and situations. Moreover, its behavior might change through learning, adaptation, and self-modification.

Consequently, a system that behaves safely during extensive testing might still exhibit dangerous behavior in circumstances that were never evaluated.

This creates a profound epistemological problem: **how can researchers know that an AI system is genuinely aligned, rather than merely having behaved appropriately in all situations examined so far?**

The paper argues that conventional testing methods cannot establish comprehensive safety for unrestricted general-purpose intelligence. This work was released as a preprint, and its broader impossibility claims remain open to debate.

[Untestability of AI and Unfalsifiability of AI Safety Claims — research paper, 2024](https://doi.org/10.13140/RG.2.2.34358.06728)

**The limitations of containment and shutdown mechanisms.** Even if researchers cannot guarantee that an AI possesses desirable objectives, they might attempt to prevent harmful behavior by restricting its capabilities.

Yampolskiy distinguishes two broad approaches to AI control.

_Capability control_ attempts to limit what a system can do through restricted environments, computational constraints, monitoring, and shutdown mechanisms.

_Motivational control_ attempts to ensure that the system does not wish to perform harmful actions in the first place.

Both approaches face substantial difficulties.

Capability restrictions may be circumvented by a sufficiently advanced intelligence that discovers unexpected vulnerabilities or manipulates its human operators. Meanwhile, motivational control requires reliable mechanisms for specifying desirable objectives and ensuring that these objectives remain stable as the system learns and improves.

Yampolskiy therefore argues that containment, shutdown mechanisms, and behavioral restrictions may reduce risks but cannot presently guarantee permanent control over an arbitrarily capable autonomous system.

His 2022 paper also highlights a tension between control and safety. A system that always follows human instructions might obey dangerous or contradictory commands. Conversely, a system authorized to refuse harmful instructions exercises independent judgment rather than remaining completely obedient.

Thus, **ensuring that an AI always obeys humans and ensuring that it always acts safely are not necessarily compatible objectives**.

### 3. Why the Absence of a Solution Requires Halting Development

These difficulties form the basis of Yampolskiy's call for restricting the development of increasingly powerful AI systems.

His central argument is that humanity is approaching the creation of a technology capable of causing irreversible global harm without possessing a demonstrated method for ensuring that it will remain safe.

In February 2024, the publisher Taylor & Francis issued a detailed announcement accompanying Yampolskiy's forthcoming book. The announcement emphasized that his extensive review of the literature had uncovered no proof that advanced AI could be reliably controlled.

It also highlighted his recommendation that the development of such systems should not proceed without adequate evidence of controllability.

Yampolskiy's reasoning challenges the conventional relationship between technological innovation and safety research.

Throughout history, new technologies have frequently been developed before their risks were fully understood. Engineers subsequently identified failures, improved designs, and introduced additional safeguards.

However, this approach may be unacceptable for superintelligent AI.

If a sufficiently powerful system escapes human control, the resulting consequences might be irreversible. Humanity could lose its ability to intervene, correct the system, or prevent further harm.

**An experimental approach that tolerates failure is fundamentally inadequate when a single failure could permanently destroy humanity's ability to conduct further experiments.**

[There Is No Proof That AI Can Be Controlled — Taylor & Francis, February 2024](https://newsroom.taylorandfrancisgroup.com/there-is-no-proof-that-ai-can-be-controlled-according-to-extensive-survey/)

Yampolskiy explained his proposed response particularly clearly in his June 2024 interview with Lex Fridman, _Dangers of Superintelligent AI_.

[Lex Fridman Podcast #431: Roman Yampolskiy — June 2024](https://lexfridman.com/roman-yampolskiy/)

[Full interview transcript, including discussion of pausing AI development](https://lexfridman.com/roman-yampolskiy-transcript/)

Rather than advocating a temporary pause lasting a predetermined number of months, he proposed a moratorium conditional on achieving specific safety capabilities.

Development should resume only when researchers can demonstrate the necessary ability to understand, predict, verify, and control advanced systems.

If such capabilities are eventually developed, the restriction could be lifted. If, however, Yampolskiy's concerns about fundamental uncontrollability prove correct, the temporary moratorium would effectively become permanent.

He also emphasized that safety research does not progress automatically alongside improvements in AI capabilities. Increasing computational resources can produce increasingly capable systems without producing corresponding advances in interpretability, verification, or control.

Thus, continued AI development may progressively widen the gap between what humanity can create and what it can safely manage.

In the interview, Yampolskiy compared the challenge to creating a software system that must remain free of catastrophic errors indefinitely. Even extremely reliable systems may eventually fail, particularly when exposed to unfamiliar circumstances, external interference, or continuous modification.

For ordinary software, occasional failures may be tolerable. For a superintelligence capable of permanently disempowering humanity, even an exceptionally small residual risk could be unacceptable.

[Lex Fridman Podcast #431: Roman Yampolskiy — June 2024](https://lexfridman.com/roman-yampolskiy/)

[Full interview transcript, including discussion of pausing AI development](https://lexfridman.com/roman-yampolskiy-transcript/)

### 4. The Warning Becomes a Book: _AI: Unexplainable, Unpredictable, Uncontrollable_

In 2024, Yampolskiy published _AI: Unexplainable, Unpredictable, Uncontrollable_ (Chapman & Hall/CRC), bringing together years of research into the fundamental limitations of AI safety.

The book develops three closely connected themes that also form its title.

First, artificial intelligence may be **unexplainable**: the mechanisms underlying its decisions may be too complex or unfamiliar for humans to understand adequately.

Second, it may be **unpredictable**: sufficiently advanced systems may pursue strategies and discover possibilities that their designers cannot anticipate.

Third, it may be **uncontrollable**: without the ability to reliably understand, predict, and verify its behavior, humanity may be unable to ensure that a superintelligent system consistently acts within intended boundaries.

The book develops these arguments across several chapters, including _Unpredictability_, _Unexplainability and Incomprehensibility_, _Unverifiability_, and _Uncontrollability_. Chapter 6 addresses the control problem directly, while subsequent chapters examine pathways to dangerous outcomes and AI accidents.

An important implication emerges from the relationship between these difficulties: **alignment is not merely the problem of giving an AI appropriate instructions. It is the much more demanding problem of ensuring that those instructions continue to govern the behavior of an intelligence whose decisions may exceed human comprehension.**

Even if humanity could agree upon a consistent collection of values, Yampolskiy's arguments suggest that major obstacles would remain. Researchers would still need to establish that those values had been correctly implemented, that the resulting objectives would remain stable, and that the system's actions would consistently reflect them.

The book therefore challenges not only particular alignment techniques but also the expectation that increasingly sophisticated engineering will necessarily lead to reliable control.

[AI: Unexplainable, Unpredictable, Uncontrollable — book, 2024](https://www.routledge.com/link/link/p/book/9781032576275?utm_source=chatgpt.com)

In his February 2024 interview with the Future of Life Institute, _Roman Yampolskiy on Shoggoth, Scaling Laws, and Evidence for AI Being Uncontrollable_, Yampolskiy further explored the relationship between increasing intelligence and decreasing human understanding.

The conversation examined whether contemporary AI systems could be meaningfully explained, whether superior AI could help interpret less capable systems, whether their behavior could be verified, and whether value alignment might emerge naturally as intelligence increased.

Yampolskiy's position remained skeptical: increasing the intelligence of a system does not establish that it shares human objectives, and using AI to supervise more advanced AI introduces additional questions about the reliability of the supervising systems themselves.

[Future of Life Institute interview — February 2024](https://futureoflife.org/podcast/roman-yampolskiy-on-shoggoth-scaling-laws-and-evidence-for-ai-being-uncontrollable/)

### 5. A Moratorium on Superintelligence, Not a Rejection of AI

An important feature of Yampolskiy's position is that he does not advocate abandoning every form of artificial intelligence.

Instead, he distinguishes between highly capable systems designed to perform specific tasks and general-purpose autonomous superintelligence capable of independently pursuing objectives across unrestricted domains.

In a September 2026 interview on _For Humanity_, Yampolskiy reiterated this distinction.

He argued that narrow AI tools could continue delivering substantial benefits in medicine, scientific research, and other fields without necessarily creating autonomous systems more powerful than humanity.

For example, AI systems designed to predict protein structures, analyze medical information, or assist scientific discovery need not possess unrestricted autonomy or independent objectives extending across society.

Yampolskiy therefore advocated continuing the development of useful, sufficiently constrained AI tools while prohibiting the creation of general superintelligent agents that humanity cannot reliably control.

He also proposed international agreements, particularly between major technological powers, to restrict the development of such systems.

This position reflects a broader principle: **humanity should not sacrifice its long-term survival and autonomy in pursuit of AI capabilities that may be unnecessary for obtaining many of the technology's benefits.**

[Roman Yampolskiy: Build AI Tools, Not Superintelligence — September 2026 interview](https://www.guardrailnow.org/blog/roman-yampolskiy-ai-tools-not-superintelligence-for-humanity)

### 6. The Fundamental Conclusion

Yampolskiy's research presents a profound challenge to the prevailing assumption that AI alignment is a difficult engineering problem that will eventually be solved through sufficient scientific progress.

His argument begins with a fundamental observation: **no demonstrated method currently establishes that superintelligent AI can be reliably aligned with human intentions and kept under human control.**

He then goes further, identifying theoretical limitations in predictability, explainability, verification, and control that may prevent complete safety guarantees from ever being achieved.

These arguments do not constitute a universally accepted proof that every possible approach to aligning superintelligence must fail. They do, however, challenge the assumption that reliable alignment will necessarily become possible as AI research advances.

Yampolskiy's conclusion is correspondingly radical: humanity should not continue developing general superintelligence until the necessary safety capabilities have been demonstrated. If reliable control is fundamentally impossible, the development of such systems should remain prohibited.

His position thus reverses the conventional burden of proof. Rather than assuming that AI development may proceed until someone demonstrates that it is unsafe, he argues that **developers must establish an adequate basis for safety before creating systems capable of irreversible harm**.

For the broader problem of AI alignment, his work raises a fundamental question. Humanity is investing enormous resources in developing increasingly powerful intelligence, yet the basic scientific foundations necessary to ensure its alignment remain incomplete.

The continued absence of a demonstrated solution does not establish that no solution can ever exist. But it does mean that proceeding toward superintelligence requires accepting risks whose magnitude may exceed humanity's capacity to recover.

**Yampolskiy's warning is therefore not simply that AI alignment is extraordinarily difficult. It is that humanity is advancing toward superintelligence without knowing whether the most important safety problem it faces can be solved at all.**