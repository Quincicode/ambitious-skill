---
name: ambitious-skill
description: Design world-class, high-ambition prompts and execution protocols across any domain (science, coding, math, strategy, writing) using Altitude, Depth, Range, Outside Judge, and Cognitive Prosthetics. Always use when the user asks to write, optimize, upgrade, or audit a prompt, push any model from mediocre outputs to theoretical limits, or make ordinary models perform like frontier reasoning models.
---

# Ambitious Prompt Architect

Transform vague, incremental, or routine requests into high-leverage prompts and agent execution protocols that push any AI model to its theoretical performance ceiling. By combining four dimensions of ambition (Altitude, Depth, Range, Outside Judge) with Cognitive Prosthetics (test-time scaffolding that prevents lazy shortcuts), this skill forces even ordinary models to reason, verify, and innovate at the level of frontier models.

## When to Use

- Before drafting, editing, or upgrading any critical prompt across science, software engineering, mathematics, quantitative finance, product strategy, or deep synthesis.
- When an existing model, algorithm, or workflow has plateaued and needs a structural breakthrough without overfitting or bloating complexity.
- When the user wants an ordinary or mid-sized model to produce rigorous, expert-grade outputs free of generic cliches, hallucinated math, or premature shortcuts.
- When combining multi-disciplinary methodologies or Felix Rieseberg's four-dimensional ambition framework into an actionable prompt.

## Universal Domain Isomorphism Matrix

Translate the four ambition dimensions cleanly into the user's target domain using this mapping:

| Dimension | Scientific & ML Modeling | Software & Systems Engineering | Strategy, Finance & Product | Math, Logic & Deep Synthesis |
| :--- | :--- | :--- | :--- | :--- |
| **Altitude (Outcome & Oracle)** | Close the gap to the theoretical Oracle upper bound or Bayes error limit. | Design self-healing architectures bounded by hardware physics (latency/throughput limits). | Shift from reporting historical metrics to autonomous decision-making under uncertainty. | Prove structural invariants and necessary/sufficient conditions rather than listing examples. |
| **Depth (Raw Substrate)** | Raw trees, sequences, tick logs, or particle states instead of summary averages. | ASTs, bytecode, memory layouts, flamegraphs, and kernel traces instead of high-level logs. | Unit-level cohort logs, raw transaction ledgers, and cash-flow micro-data instead of slide summaries. | Primary axioms, original primary sources, and formal definitions instead of secondary summaries. |
| **Depth (Zero-DoF Prior)** | Parameter-free physical/dimensionless operators that respect strict DoF budgets. | Zero-copy invariants, deterministic state machines, and type-level compile-time guarantees. | Structural no-arbitrage bounds, conservation of capital/attention, and incentive compatibility. | Symmetry reductions, dimensional analysis, and extremal principle bounds. |
| **Outside Judge (Falsification)** | Out-of-sample rolling ablation, bootstrap replicates, and automatic rollback gates. | Property-based fuzzing, chaos injection, benchmark regression gates, and deterministic replay. | Pre-mortem short-seller red-teaming, historical backtesting on crisis regimes, and unit-economics stress tests. | Counterexample search, boundary-case substitution ($N=0, 1, \infty$), and worked micro-examples. |

## Core Workflow

### Step 1: Run the 4D Ceiling Audit

Before writing the prompt, present a concise 4-row table diagnosing why a standard prompt or current baseline settles for mediocrity across **Altitude**, **Depth**, **Range**, and **Outside Judge**.

### Step 2: Elevate Altitude (Verb Reframing and Oracle Anchoring)

- **Replace Nouns with Dynamic Verbs**: Never frame the task as producing a static artifact ("write a report", "build a model", "refactor this class"). Reframe it as driving a causal mechanism ("detect symmetry breaking before phase transition", "eliminate tail-latency amplification across lock-free queues", "convince skeptical capital allocators to reallocate resources in 15 minutes").
- **Anchor to the Theoretical Limit (Oracle)**: Define success by how much of the gap to the theoretical physical, mathematical, or information-theoretic limit is closed, rather than settling for marginal gains over a naive baseline.

### Step 3: Inject Depth and Cognitive Prosthetics (Empowering Ordinary Models)

Ordinary models fail because they take high-probability greedy shortcuts. Force the target model into deep, error-free reasoning by embedding three prosthetics into the prompt:

- **1. Banned Lazy Defaults (`<banned_lazy_defaults>`)**: Explicitly list and forbid the top 3 mediocre, textbook, or boilerplate responses the model would normally generate first. Pruning the high-probability mediocre mode forces the model's attention into high-expertise tail distributions.
- **2. Raw-Substrate & Zero-DoF Mandate**: Forbid operating on digested summaries when raw substrates exist. When overfitting or complexity creep is a risk, cap free parameters and require encoding domain knowledge into parameter-free structural operators.
- **3. Worked Micro-Example Pinning (`<micro_example_grounding>`)**: Instruct the target model that for every abstract formula, algorithm, or core mechanism it proposes, it must first trace a concrete micro-example (e.g., $N=3$ data points or a 3-node graph with real numbers) step-by-step to prove the math and logic hold before scaling up.

### Step 4: Expand Range via an Orthogonal Dialectical Crew

Do not assemble a flat list of experts who talk past one another, and strictly forbid theatrical roleplay ("write in the tone of..."). Assemble a 3-to-5 discipline crew organized as an **Orthogonal Dialectical Triad** executing real methods:

- **The Forensic Diagnostician (e.g., Forensic Statistician / Short-Seller / Systems Profiler)**: Dissects existing failures and decomposes exact error sources before any new design begins.
- **The Generative Architect (2-3 Cross-Disciplinary Specialists)**: Imports concrete mathematical or structural operators from adjacent fields (e.g., non-equilibrium statistical physics, spectral graph theory, optimal transport, mechanism design, or compiler theory) to solve the core bottleneck.
- **The Complexity Compressor (e.g., Information Theorist / Minimalist Systems Engineer)**: Applies Occam's razor to strip redundant parameters, merge overlapping steps, and enforce strict budget constraints.

### Step 5: Install the Dual-Mode Outside Judge

Ban self-congratulatory qualitative grading. Embed a strict verification protocol matched to the target model's environment:

- **For Code / Agentic Environments (4-Stage Execution & Rollback Gate)**:
  1. **Stage 1 (Forensic Residual Autopsy)**: Run a script to quantify exactly where the baseline fails against the Oracle.
  2. **Stage 2 (Operator & Micro-Example Audit)**: Verify new operators on a concrete micro-example and check orthogonality/invariants.
  3. **Stage 3 (Strict Out-of-Sample Ablation & Rollback)**: Evaluate every change against the baseline and Oracle. Mandate immediate rollback of any change that fails to yield net improvement.
  4. **Stage 4 (Stress & Multi-Regime Validation)**: Verify robustness across bootstrap replicates, edge cases, or alternative metrics.

- **For Pure-Text / Chat Environments (3-Pass In-Context Verification Loop)**:
  1. **Pass 1 (First-Principles Derivation & Micro-Example)**: Derive the core mechanism and verify it with concrete numbers on a toy case.
  2. **Pass 2 (Adversarial Red-Team Attack)**: Switch perspective to a ruthless critic and find at least 2 concrete failure modes, boundary violations, or hidden assumptions in Pass 1.
  3. **Pass 3 (Falsification-Hardened Final Deliverable)**: Rewrite and deliver the final solution that mathematically or structurally resolves the flaws exposed in Pass 2.

## Master Prompt Blueprint

Generate the final prompt for the user using these structured semantic blocks so any receiving LLM parses the instructions with zero ambiguity:

1. `<mission_altitude>`: Verb-reframed objective, baseline-to-Oracle gap definition, and audacious quantitative targets.
2. `<inviolable_constraints_and_banned_defaults>`: Hard system invariants (e.g., parameter caps, zero leakage, latency bounds) plus the explicit list of **Banned Lazy Defaults** the model is forbidden from outputting.
3. `<dialectical_crew_operations>`: Numbered methodological modules starting with Module 1 (Forensic Autopsy), specifying exact raw inputs and cross-disciplinary mathematical/structural operators.
4. `<cognitive_scaffolding_and_micro_example>`: Mandatory instruction to prove every core operator on a concrete $N=3$ numerical or structural micro-example before full implementation.
5. `<outside_judge_protocol>`: Either the 4-Stage Code Execution & Rollback Gate (for coding agents) or the 3-Pass Adversarial Verification Loop (for chat models).

## Adaptive Delivery Tiers

Always provide:

1. **The Master Breakthrough Prompt**: The complete 5-block prompt ready to copy-paste.
2. **The Two-Step Reconnaissance Prompt**: A compact diagnostic prompt the user can send first to make the model inspect raw data or failure modes before proposing solutions:

> "I want a deeper, structurally superior version of this task, not a bigger or more verbose one. Before proposing any new solution or writing main code, answer four questions using concrete data or logic: (1) What exact proportion of the gap between our current baseline and the theoretical optimum comes from structural representation limits versus execution error? (2) What raw underlying signals or invariants would top specialists in [Field A] and [Field B] extract here that standard approaches ignore? (3) What parameter-free operator or structural mechanism captures those signals without adding bloat? (4) What concrete micro-example ($N=3$) and falsification test will prove the new mechanism works? Output this forensic diagnosis first."

## Self-Audit Scorecard (Verify Before Delivering)

Before outputting the prompt to the user, verify that your drafted prompt passes all 5 checks:

- [ ] **Verb Reframing**: Is the core task defined as a dynamic causal verb rather than a static noun?
- [ ] **Lazy Default Ban**: Does the prompt explicitly outlaw the top 3 mediocre/boilerplate responses?
- [ ] **Methods Over Jargon**: Does every expert module specify a concrete operator, algorithm, or transformation rather than a persona tone?
- [ ] **Micro-Example Grounding**: Is the target model forced to verify its logic on a concrete small-scale example?
- [ ] **Falsifiable Judge**: Is there an objective rollback gate or adversarial red-team pass that prevents self-certification?
