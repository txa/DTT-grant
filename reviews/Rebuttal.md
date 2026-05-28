We thank the reviewers for their careful and thoughtful assessment of our proposal. We are particularly encouraged by the strong overall support and constructive engagement with the project vision and methodology.

Reviewer 1 describes the proposed work as “top-notch” and notes that
“if successful, the outcome will be hugely impactful in many areas”
while emphasising that “the risk management is excellent for a theoretical project”.

Reviewer 2 characterises the proposal as “an excellent proposal” and highlights the timeliness of the work in light of recent developments in formal verification, AI, homotopy theory and higher category theory, concluding that "the stated deliverables would be very valuable if achieved”.

Reviewer 3 regards the research as “potentially groundbreaking” and identifies as strengths the proposal’s "clear” state-of-the-art presentation, “convincing” methodology, and “excellent” capability to deliver.

We are grateful for these encouraging assessments and for the constructive questions raised, which focus primarily on (1) clarifying the broader significance and envisioned applications of Directed Type Theory and (2) further explaining the mitigation strategy and staged structure of WP2. We address these points below.

(1) Broader significance and envisioned applications of DTT
***

Reviewer 3 asks:
“Could you please comment on some envisioned applications of DTT? … what specific concepts of mathematics will DTT help capture, unify … or what specific application problem will DTT help solve … in the design and implementation of proof assistants?”
We thank the reviewer for this important question, which goes to the heart of our motivation.

Our central insight is that DTT is motivated not merely by the wish to formalise directed structures, but by a broader structural principle:

Definable constructions are fundamentally natural and representation independent.
In mathematics this appears as naturality; in computer science as abstraction and parametricity. Existing foundations often treat such structure externally. HoTT successfully internalises equivalence and symmetry, but naturality and coherence conditions typically remain additional structure that must be tracked explicitly.

DTT aims to internalise these principles directly by treating morphisms, rather than only equivalences, as primitive. In this sense:

HoTT internalises equivalence; DTT aims to internalise morphism and naturality.

This perspective transcends parametricity alone and motivates several envisioned applications.

For mathematics, DTT provides a native setting for synthetic higher category theory, where coherence and naturality conditions may become intrinsic rather than externally imposed. For proof assistants, we do not envisage DTT as an immediate replacement for systems such as Lean or Agda; rather, it may provide conceptual foundations for future systems in which abstraction, coherence and relational reasoning are more intrinsic, reducing formalisation overhead. Finally, many structures arising in categorical physics and quantum foundations are fundamentally directional and process-based, making DTT a potentially natural foundational language for these settings.

2. WP2 strategy, dependencies and mitigation
***

Reviewer 3 notes that
“complete success for WP2 seems necessary to the development of WP3, WP4, WP6, and WP7”
and asks:
“Could you expand on this? … what are the implications of success in one or the other [direction]? How will these affect the following work packages?”

We thank the reviewer for highlighting this important point. WP2 is indeed central to the project, but it is intentionally designed as a diversified and exploratory work package rather than a single dependency.

The four directions pursued in WP2 have distinct roles and partially independent value:
Simplicial semantics (STT) provides a semantic route to higher-dimensional DTT and, if successful, supports the higher-dimensional development of WP5–WP7. Even partial success yields semantic frameworks for important fragments.

Directed fibrancy in HOTT offers a constructive and implementation-oriented route, with particular relevance for WP4 and for connections to systems such as Narya.
Cubical–simplicial comparison is valuable independently of a full semantic account, clarifying relationships between existing approaches and informing both theory and implementation.

General (\infinity,2))-topos semantics is explicitly exploratory and high-risk/high-reward; while potentially providing the strongest unification, it is not required for overall project success.

Consequently, later work packages are designed to proceed incrementally rather than depend on complete success of all WP2 directions. In particular, WP3 and WP4 can already proceed using 1-DTT and fragmentary semantics, while WP5–WP7 are intended to develop progressively as higher-dimensional foundations become available.

Our mitigation strategy therefore relies on staged development and multiple semantic routes. Even if a fully general semantic account remains out of reach, we expect robust semantic frameworks for substantial fragments that support the intended applications and provide a strong foundation for future work.

Conclusion
***
We thank the reviewers again for their highly encouraging and constructive feedback. The questions raised have helped us sharpen the articulation of both the broader significance of DTT and the staged strategy underlying WP2. We hope the clarifications above demonstrate that the project combines ambitious long-term goals with diversified and carefully managed routes to success.
