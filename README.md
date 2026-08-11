I did not touch GitHub until 22 July 2026. For the first 15 months, my cognitive bandwidth was consumed entirely by ideation: continuous, high‑density conceptual generation across multiple domains. Implementation would have been premature; the ideas had not yet stabilised, and my brain simply had no available bandwidth for anything else.

Once the ideation phase slowed into coherent groups of ideas - giving me room to breathe, rather than drowning under a high-rate continuous flow (I still have days or weeks which are consumed thusly) - I began formalising the work: learning to code, defining workflows, setting standards, and structuring the project roadmap in the correct sequence.

---

15 months of pure ideation before implementation began.

<div align="center">

| Ideas in pipeline | Research files |
| :-: | :-: |
| **150 – 200** | **9,500+** |

</div> 

---

## Purpose

Learning by building small, structured prototypes across different domains.

I'm aiming to develop "correct" workflows and documentations, and get a "feel" for different paradigms and languages.  As always, I am working from first principles; developing my own processes, as opposed to following the herd (which tends to be quite fickle).  

---

## Project Roadmap 

A structured sequence, each scoped to teach one conceptual domain at a time.
Every project is a complete system - minimal and architecturally instructive.

&nbsp;

**[`0.0` - Project Template Framework](https://github.com/WilliamMurray-research/templates)** (*C++20, SWI-Prolog, YAML*)

This repository defines the canonical template framework used across all projects. It contains multiple documents, specifications, and structural standards that together form a complete operational scaffold. Each project must instantiate this framework in full, preserving all directories, files, and structural invariants, even when individual branches contain no artefacts. The framework provides an ISO‑aligned standardisation baseline, ensuring uniformity, repeatability, and auditability across all projects. By enforcing a consistent structure and governance model, it reduces variability, reduces cognitive load, improves maintainability, increases operational efficiency, and enables tooling interoperability in accordance with established principles of technical standardisation.  
`standardisation` `structural invariants` `project scaffolding` `governance model` `workflow design` `Prolog integration` `YAML specifications` `auditability` `tooling interoperability`

---

**[`1.0` - Digital Twin Wallpaper](https://github.com/WilliamMurray-research/1-dynamic_sky_wallpaper)** (*SWI-Prolog, Python, JSON*)

A deterministic pipeline combining telemetry, symbolic reasoning, a scene DSL, and procedural rendering.  
`systems architecture` `DSL design` `Prolog` `deterministic graphics`

---

**[`2.0` – Conjecture Convergence Engine](https://github.com/WilliamMurray-research/2-conjecture_convergence_engine)** (*SWI-Prolog, Bash, llama.cpp*)

A distributed plausibility‑anchored refinement system for stabilising conjectures across multiple nodes.  
`multi‑node orchestration` `symbolic verification` `plausibility refinement` `convergence detection`

---

**[`3.0` - Knowledge Layer](https://github.com/WilliamMurray-research/3-knowledge_layer)** (*Bash + curl, PostgreSQL ≥13, Memgraph 4.x, llama.cpp (local host), .md*)

A dual‑layer system indexing and relating the entire research corpus (~9,500 files). The Knowledge Layer provides the semantic substrate required for programme‑level governance: the mature instantiations of both the Project Template Framework (0.0) and the Unified Asset Registry depend on this project for structural invariants, provenance tracking, and cross‑domain coherence.  
`relational schema` `graph databases` `semantic indexing` `knowledge-graph queries`


**[`3.1` - Knowledge Layer Sandbox](https://github.com/WilliamMurray-research/3.1-knowledge_layer_sandbox)**  

The Knowledge Layer Sandbox is a governed, synthetic micro‑ecosystem designed to validate the semantic and provenance substrates that underpin the full Knowledge Layer architecture. It provides a safe, controlled environment for testing PostgreSQL metadata schemas, Memgraph dependency graphs, deterministic SLM extraction, and Local Git provenance workflows before indexing the full 9,500‑document corpus. By operating on a small set of synthetic projects, the sandbox ensures that structural invariants, sync protocols, and metadata pipelines behave deterministically, reproducibly, and coherently across all layers of the system. This project is the mandatory precursor to large‑scale corpus ingestion, guaranteeing that the semantic backbone of the research ecosystem is stable, governed, and ready for programme‑level deployment.  

---

**[`4.0` - Local Git](https://github.com/WilliamMurray-research/4-local_git)** (*Python, Rust*)

A version‑controlled research system - a stripped-down local CLI with all extras removed.  
`Git workflows` `metadata design` `provenance tracking` `structured research`

---

**[`5.0` - Non‑Backtracking Hashimoto Simulation](https://github.com/WilliamMurray-research/5-non_backtracking_hashimoto)** (*Julia*)

Hashimoto matrices (n=6) exploring non-backtracking walks and spectral behavior.  
`graph theory` `spectral methods` `numerical computing` `Julia`

**[`5.1` – Nonlinear Sigmoidal Hashimoto Dynamics](https://github.com/WilliamMurray-research/5.1-sigmoidal_hashimoto)** (*Julia*)

A nonlinear extension of Project 5.0, introducing sigmoidal update rules and stability analysis into the n=6 Hashimoto operator. This project explores how non‑backtracking walks behave under nonlinear propagation constraints, deriving fixed points, limit cycles, and Jacobian stability conditions. It serves as the nonlinear bridge between the linear spectral foundation of 5.0 and the structured dynamical systems of 8.0, preceding the curvature‑weighted generalisation in 13.0.  
`nonlinear operators` `sigmoid dynamics` `Jacobian stability` `fixed points` `limit cycles` `non‑backtracking walks`

---

**[`6.0` - Prolog Metamorphism and Homoiconicity](https://github.com/WilliamMurray-research/6-prolog_metamorphism)** (*SWI-Prolog*)

A meta‑level logic system that rewrites its own rules, predicates, and evaluation strategy.  
`logic programming` `meta-interpreters` `rule rewriting` `symbolic metamorphism`

---

**[`7.0` - Lisp Metamorphism and Homoiconicity](https://github.com/WilliamMurray-research/7-lisp_metamorphism)** (*Common-Lisp*)

A metamorphic Lisp system exploring AST rewriting, macro transformation, and meta‑circular evaluation.  
`homoiconicity` `AST manipulation` `language design` `syntactic metamorphism`

---

**[`8.0` - Grid‑Based Hashimoto State Machine](https://github.com/WilliamMurray-research/8-grid_based_hashimoto)** (*Julia*)

Extends Project 5 into grid topologies with state transitions, absorbing endpoints, and non-backtracking constraints.  
`dynamical systems` `state machines` `grid simulation` `numerical iteration`

---

**[`9.0` - Information Representation via Tensors](https://github.com/WilliamMurray-research/9-information_tensors)** (Core math: *Julia, WolframScript* | Semantic layer: *SWI-Prolog, Lisp* | Systems & Interop layer: *Rust, Python, Python, Apache Arrow/C-ABI*) 

Studying how information can be represented directly as tensors, and how relationships between tensors generalise graph structures into higher‑dimensional topological manifolds. Focus areas include entropy, mutual information, tensor relations, and the behaviour of signal flow and compression under tensor‑based transformations.  
`information theory` `tensor algebra` `tensor relations` `signal flow` `compression` `topological manifolds`

---

**[`10.0` – AusRewrite‑T5](https://github.com/WilliamMurray-research/10-aus_rewrite)** (*encoder–decoder transformer, rule tables, constrained decoding*)

A small, rule‑constrained rewriting model that converts any English into Australian Government Style Manual + AGLC‑compliant Australian English with deterministic, semantically faithful transformations.  
`rewriting transformer` `semantic fidelity` `rule‑constrained decoding` `Australian English normalisation`

**[`10.1` - Mojo Operator Alignment & Kernel Synthesis](https://github.com/WilliamMurray-research/10.1-mojo)** (*Gemma-Coder, Modular Mojo Toolchain, MLIR Dialect Verification, Synthetic Kernel Curriculum*)

A governed, operator-tier fine-tuning pipeline aligning a coder model to Mojo’s syntax, memory ownership semantics, and MLIR-lowerable GPU/SIMD kernel patterns. Addresses high-level data sparsity via a synthetically mutated kernel curriculum grounded in hand-optimized primitives. Evaluates code generation across a strict three-stage deterministic harness: AST parsing, MLIR pass verification (`--emit mlir`), and hardware execution benchmarks against native C/CUDA baselines.  
`Mojo semantics` `MLIR dialect lowering` `SIMD/AVX/SVE vectorization` `synthetic kernel curriculum` `multi-stage compiler harness` `hardware alignment`

---

**[`11.0` - Speculative Decoding for Accuracy](https://github.com/WilliamMurray-research/11-speculative_accuracy)** (*Gemma 3 270M, Gemma 3 1B*) 

Testing the hypothesis that speculative decoding may be adopted to improve accuracy, using a two‑model pipeline in which a smaller draft model proposes tokens and a larger model performs probability‑based acceptance.  
`ML inference` `probability-based acceptance` `multi-model pipelines` `reproducible research`

---

**[`12.0` – Scaling‑Precision Ideation Lab](https://github.com/WilliamMurray-research/12-scaling_ideation)** (*llama.cpp, SWI‑Prolog, Python, quantization harness*) 

Testing the hypothesis that large low‑Q models generate and shape conjectures more effectively than smaller high‑Q models, using paired Q2–Q4 ideation and Q16 verification pipelines with blind scoring, falsifiability metrics, and domain‑specific rigs for integer sequences and functional equations.   
`quantization ablation` `mathematical ideation` `conjecture scoring` `scaling–precision crossover`

**[`12.1` – Model Parameter Scale vs. Deterministic Sampling Stability](https://github.com/WilliamMurray-research/12.1-scale_accuracy)**  (*llama.cpp, SWI‑Prolog, Python, JSON*)

A controlled ablation study examining how **model parameter scale** affects **token‑level determinism**, **logit entropy**, and **sequence stability** under fixed decoding conditions. Using a unified `llama.cpp` quantization harness and the probability‑based verification pipeline from Project 11.0, this module compares models from **270M → 70B** to determine whether smaller LLMs appear “more deterministic” due to genuinely narrower latent manifolds or simply because reduced capacity induces **entropy collapse** in the output distribution.  
`entropy analysis` `token‑variance measurement` `greedy‑alignment drift` `quantized sampling stability`

---

**[`13.0` – Non‑Uniform Hyperbolic Hashimoto Dynamics](https://github.com/WilliamMurray-research/13-hyperbolic_hashimoto)** (*Julia, SWI‑Prolog, JSON*)  

A generalisation of Projects 5 and 8 into mixed-curvature, non-uniform lattices, integrating symbolic lattice specification with curvature‑weighted non‑backtracking operators and anisotropic hyperbolic‑type dynamical evolution.  
`hyperbolic lattices` `non‑backtracking operators` `curvature‑weighted dynamics` `spectral geometry`

---

**[`14.0` – Landscape Digital Twin](https://github.com/WilliamMurray-research/14-landscape_digital_twin)**  (*Julia, SWI-Prolog, Common Lisp, Python*)

A symbolic-geometric digital twin framework modelling fragmented landscapes as a fiber bundle manifold stack, with a dynamic DSL for describing ecological entities, relations, and rewriting rules. Designed as the convergence point of the tensor algebra (9.0), Prolog metamorphism (6.0), and Lisp homoiconicity (7.0) workstreams.  
`fiber bundles` `manifold stack` `dynamic DSL` `ecological connectivity` `digital twin` `symbolic rewriting` `landscape restoration`

---

## [Unified Asset Registry](https://github.com/WilliamMurray-research/unified_asset_registry)

The Unified Asset Registry is the governed, canonical record of every formal, operational, and conceptual artefact produced across the research ecosystem. It consolidates all foundational materials - including standards, schemas, templates, compilers, DSLs, proofs, algorithms, and conceptual frameworks - into a single, structured, audit‑ready repository.  
This registry serves as the operational backbone for the broader programme: a unified source of truth that enforces structural invariants, preserves provenance, and maintains coherence across all projects and domains. It is designed for due‑diligence clarity, long‑arc stability, and reproducible governance, ensuring that every artefact is catalogued, versioned, and integrated within a consistent architectural framework.  
`provenance tracking` `structural invariants` `governed repository` `audit‑ready architecture` `programme coherence` `versioned artefacts` `canonical source‑of‑truth` `long‑arc governance` `cross‑domain integration`

---

## [Foundations](https://github.com/WilliamMurray-research/foundations)

This collection integrates the mathematical pillars of the Unified Operator Architecture (UOA) (spanning dynamical systems, symplectic geometry, symbolic dynamics, and domain theory) with a first-principles systems architecture doctrine. By pairing formal proofs and Lean 4 verification with cybernetic governance, constraint-driven runtime policies, and explicit provenance tracking, `foundations` provides the immutable structural invariants and theoretical scaffolding necessary to maintain long-arc conceptual integrity across all downstream computational prototypes.  
`Mathematics` `TheoreticalComputerScience` `SystemsArchitecture` `FormalMethods` `Cybernetics` `DynamicalSystems`

---

## [Unified Operator Architecture corpus](https://github.com/WilliamMurray-research/UOA_corpus)

**Access Level: Restricted**

The UOA corpus, mathematical formulations, and execution models are maintained in a private repository. This document defines the program's theoretical scope, domain taxonomy, and structural manifest for provenance and compliance purposes.

The UOA is attempting a unified formal language for describing how coherent global structure arises from local dynamics - and why it cannot be reduced back to them.

The conjecture is directionally compelling. The question warrants meaningful exploration.

Institutional inquiries may be directed through formal channels.

---

*Contributions are off: this is a dedication to long-arc mastery.*
