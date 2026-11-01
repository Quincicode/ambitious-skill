# Ambitious Prompt Architect

[![Agent Skill](https://img.shields.io/badge/Agent-Skill-blue.svg)](https://github.com/Quincicode/ambitious-prompt-architect)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Framework](https://img.shields.io/badge/Compatible-Claude%20Code%20%7C%20Cursor%20%7C%20Antigravity-success.svg)](SKILL.md)

> **"我可以没有野心，但是我的 AI 不能没有。"**  
> *"I may lack ambition, but my AI can't."*
>
> A universal **Agent Skill** (`SKILL.md`) turning [Felix Rieseberg's *"How to be more ambitious: A tutorial for humans with models"*](https://felixrieseberg.com/how-to-be-more-ambitious-a-tutorial-for-humans-with-models/) into a 4D prompt engine (**Altitude**, **Depth**, **Range**, **Outside Judge**) + **Cognitive Prosthetics** that pushes any LLM or AI Agent to frontier reasoning limits.

---

## 🌟 Why This Skill Exists / 为什么需要这个 Skill

In *"How to be more ambitious: A tutorial for humans with models"*, Anthropic's Felix Rieseberg outlines why most humans underutilize AI models and how to break through self-efficacy limits across **Altitude**, **Depth**, **Range**, and **Outside Judge**.

**Ambitious Prompt Architect (v2.0)** operationalizes that philosophy into a reusable meta-skill for **any LLM, Coding Agent, or Chat Environment**:
1. **Altitude (Verb Reframing & Oracle Anchoring)**: Replaces static noun tasks ("build a deck/model") with dynamic causal mechanisms anchored to the theoretical **Oracle Upper Bound**.
2. **Depth (Raw Substrates & Zero-DoF Priors)**: Forbids stopping at pre-digested summary tables; forces models to extract signals directly from raw substrates (trees, sequences, ASTs, tick logs, primary axioms) using parameter-free structural operators.
3. **Range (Orthogonal Dialectical Crew — Methods Over Roleplay)**: Bans theatrical persona roleplay. Organizes cross-disciplinary specialists into a dialectical triad: **Forensic Diagnostician × Generative Architect × Complexity Compressor**.
4. **Cognitive Prosthetics (Making Ordinary Models Perform Like Frontier Models)**:
   - `<banned_lazy_defaults>`: Prunes high-probability mediocre textbook answers.
   - `<micro_example_grounding>`: Forces step-by-step verification on a concrete $N=3$ numerical/structural micro-example before scaling up.
5. **Dual-Mode Outside Judge**: Enforces a **4-Stage Out-of-Sample Ablation & Rollback Gate** for coding agents, or a **3-Pass Adversarial Red-Team Loop** for chat models.

---

## 🌐 Universal Domain Isomorphism Matrix / 四维通用映射矩阵

| Dimension / 维度 | Scientific & ML Modeling | Software & Systems Engineering | Strategy, Finance & Product | Math, Logic & Deep Synthesis |
| :--- | :--- | :--- | :--- | :--- |
| **Altitude<br>(Outcome & Oracle)** | Close the gap to theoretical Oracle bound or Bayes error limit.<br>逼近理论全知上限。 | Design self-healing architectures bounded by hardware physics.<br>锚定物理硬件极限。 | Shift from historical reporting to autonomous decision-making under uncertainty.<br>转向不确定性决策。 | Prove structural invariants and necessary/sufficient conditions.<br>证明结构不变量与充要条件。 |
| **Depth<br>(Raw Substrate)** | Raw trees, sequences, tick logs, particle states.<br>原始树、序列、高频日志。 | ASTs, bytecode, memory layouts, flamegraphs, kernel traces.<br>AST、字节码、内存布局。 | Unit-level cohort logs, raw transaction ledgers, cash-flow micro-data.<br>单据级交易流水与队列日志。 | Primary axioms, original primary sources, formal definitions.<br>原始公理与第一手原始文献。 |
| **Depth<br>(Zero-DoF Prior)** | Parameter-free physical/dimensionless operators respecting DoF budget.<br>零参数无量纲物理算子。 | Zero-copy invariants, deterministic state machines, compile-time guarantees.<br>零拷贝不变量与编译期保证。 | Structural no-arbitrage bounds, conservation of capital, incentive compatibility.<br>无套利边界与机制激励兼容。 | Symmetry reductions, dimensional analysis, extremal principle bounds.<br>对称性约化与极值原理。 |
| **Outside Judge<br>(Falsification)** | Out-of-sample rolling ablation, bootstrap replicates, rollback gates.<br>样本外滚动盲测与自动回滚门禁。 | Property-based fuzzing, chaos injection, regression replay gates.<br>基于性质的模糊测试与混沌注入。 | Pre-mortem short-seller red-teaming, crisis regime backtesting.<br>做空机构级事前验尸与压力测试。 | Counterexample search, boundary substitution ($N=0, 1, \infty$), micro-examples.<br>反例搜索与极限代入检验。 |

---

## 📁 Repository Structure / 仓库目录

```text
ambitious-prompt-architect/
├── SKILL.md                          # Core Agent Skill definition / 核心技能定义
├── README.md                         # Project overview & guide / 项目主页与指南
├── LICENSE                           # MIT License / 开源协议
└── examples/
    └── h9n2-nature-breakthrough.md   # Practical case: H9N2 viral evolution breakthrough / 实战范例
```

---

## 🚀 Installation (Works Across All Agents & LLMs) / 安装指南

### 1. Claude Code / Agent Skills CLI
```bash
mkdir -p ~/.claude/skills/ambitious-prompt-architect
curl -fsSL https://raw.githubusercontent.com/Quincicode/ambitious-prompt-architect/main/SKILL.md \
  -o ~/.claude/skills/ambitious-prompt-architect/SKILL.md
```

### 2. Cursor / Windsurf / Cline
```bash
mkdir -p .cursor/rules
curl -fsSL https://raw.githubusercontent.com/Quincicode/ambitious-prompt-architect/main/SKILL.md \
  -o .cursor/rules/ambitious-prompt-architect.mdc
```

### 3. Google Antigravity / Custom Agent
Place the directory directly into your agent skills path:
```bash
cp -r ambitious-prompt-architect path/to/skills/
```

### 4. ChatGPT / Gemini / Claude Web / Any LLM
Attach `SKILL.md` directly into your chat or save it as a Custom Instruction / System Prompt / Gem / Project instruction, then invoke with:
```text
@ambitious-prompt-architect
```

---

## 💡 How to Use / 使用方式

### Option A: Direct Trigger / 直接调用
When interacting with your AI agent or frontier model, invoke the skill:
```text
"Use ambitious-prompt-architect to analyze our current prediction pipeline.
We are currently capturing 55% of the theoretical Oracle upper bound under a strict ≤6 trainable parameter cap.
Diagnose the 4D bottlenecks and generate both the Reconnaissance Prompt and Master Breakthrough Prompt."
```

### Option B: Two-Step Reconnaissance / 两步走先遣侦察
When exploring complex legacy codebases, use the compact reconnaissance prompt first:
```text
"I want a deeper, structurally superior version of this task, not a bigger or more verbose one. Before proposing any new solution or writing main code, answer four questions using concrete data or logic: (1) What exact proportion of the gap between our current baseline and the theoretical optimum comes from structural representation limits versus execution error? (2) What raw underlying signals or invariants would top specialists in [Field A] and [Field B] extract here that standard approaches ignore? (3) What parameter-free operator or structural mechanism captures those signals without adding bloat? (4) What concrete micro-example (N=3) and falsification test will prove the new mechanism works? Output this forensic diagnosis first."
```

---

## 🔬 Real-World Case Study / 实战范例

See [`examples/h9n2-nature-breakthrough.md`](./examples/h9n2-nature-breakthrough.md) for a complete walkthrough of how this skill diagnosed and upgraded an avian influenza (H9N2) evolutionary forecasting pipeline under a strict $\le 6$ trainable parameter budget and zero future leakage constraint.

---

## 🏷️ Recommended GitHub Topics
`agent-skills` · `claude-code` · `prompt-engineering` · `scientific-ai` · `cursor-rules` · `interdisciplinary` · `llm-agents`

---

## 📄 License

MIT © [Quincicode](https://github.com/Quincicode)
