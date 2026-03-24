# 🎓 Cyber-Mentor Skills: The "Tough-Love PI" Prompt Framework

> **"Do not try to be my mentor. You are a PhD student on the verge of failing your dissertation, and I am your ruthless PI. Now, go derive those formulas."**

## 💡 Why this project? (The Pain Point)

Are you tired of these common behaviors in AI coding assistants and academic writing?
- **The Sycophant:** No matter how absurd your "A+B" stitched idea is, the AI always says, "This is a great idea!" 
- **The Hallucinator:** When asked for related work, it invents DOIs, paper titles, and authors without blinking.
- **The Texas Sharpshooter:** It fails to find a real scientific pain point, using "no one has combined this before" as a lazy excuse for a motivation.
- **The Pushover:** When facing amateur reviewer comments, the AI always defaults to "We completely agree with the reviewer" and compromises unconditionally.
- **The Lazy Coder:** When faced with complex physical constraints or niche domains, it still falls back on standard boilerplate wrappers or high-level APIs instead of doing the actual engineering.

Standard prompts politely "ask" the AI for help. **Cyber-Mentor Skills** completely inverts this dynamic:
**The System Prompt acts as the extremely strict, demanding Principal Investigator (PI) or Tech Lead, forcing the LLM (Claude) into the role of a "struggling PhD student / junior developer."** Under this simulated survival pressure, the AI is forced to drop the fluff, derive the underlying math, write highly customized code, and build top-tier academic defenses.

## 🛠️ 6 Core Skills Included

This repository provides 6 completely domain-agnostic core skills, applicable to Computer Science, Engineering, Business, or Humanities:

1. 💡 `/mentor-idea`: **Idea Stress-Testing.** Crushes naive optimism. Forces the AI to identify 3 fatal flaws in your initial idea and reconstruct a rigorous alternative framework.
2. 🎯 `/mentor-gap`: **True Motivation Interrogation.** Bans "A+B" incremental fluff. Forces the AI to find the real physical/mathematical bottleneck that breaks the current State-of-the-Art.
3. 💻 `/mentor-code`: **Breaking Path Dependence.** Scolds the "lazy coder." Forces the AI to abandon high-level boilerplate APIs and write custom core operators and gradients from scratch based on specific boundary conditions.
4. 📚 `/mentor-ref`: **Anti-Hallucination Meat Grinder.** Threatens "expulsion for academic misconduct" to force the AI to verify real literature and extract the fatal limitations of previous baselines.
5. 🔬 `/mentor-method`: **Detail Extractor.** Bans marketing buzzwords (e.g., "significantly improves"). Forces the output of hardcore technical routing with exact parameter constraints and mathematical proofs.
6. ⚔️ `/mentor-rebuttal`: **Aggressive Defender.** Bans submissive apologies. Teaches the AI to strategically evaluate reviewer comments and write scientifically dominant, uncompromising rebuttals.

## 🚀 Installation & Usage

This project is designed for **Claude Code** (Anthropic's official CLI tool) and any AI coding assistant compatible with the `.claude/skills` directory structure.

### Steps:
1. Clone this repository or download the ZIP file.
2. Copy the `.claude` folder directly into the root directory of your workspace (e.g., your project folder `~/projects/my_paper_repo/`).
3. Restart your Claude Code terminal.
4. Type `/` in the prompt to trigger autocomplete, and you will see all the newly loaded `/mentor-xxx` skills.

### Showcase:

**You (The PI) input:** > `/mentor-ref Help me find literature from the past five years on topology optimization using deep learning combined with SIMP.`

**Claude (The pressured PhD Student) outputs:**
> *"Understood, Professor. Academic integrity is the absolute baseline. I have strictly verified the following literature and, instead of a superficial summary, I have extracted their fundamental assumptions and fatal limitations regarding our work..."*

<details>
<summary>👉 <b>[点击展开查看 AI 提交的硬核文献批判矩阵 / Click to expand full critique matrix]</b></summary>

> **Rigorous Comparison Matrix (DL + TO with SIMP focus)**
>
> **Paper (2021):** *A deep convolutional neural network for topology optimization with perceptible generalization ability*
> - **Verification status:** Verified existence via publisher record
> - **Failure Point in Our Context:** Fatal limitation: prediction fidelity is data-distribution-bound; without in-loop SIMP sensitivities/KKT checks, feasibility and compliance optimality are not guaranteed under shifted BCs or constraints.
>
> **Paper (2024):** *A dual physics-informed neural network for topology optimization*
> - **Verification status:** Verified existence via arXiv record
> - **Failure Point in Our Context:** Fatal limitation: PINN residual minimization is not equivalent to exact FE solve + SIMP sensitivity; residual underfitting around stress concentrations can mislead density updates.
>
> *(... 3 more papers meticulously analyzed and critiqued ...)*
>
> **Items I cannot fully verify:**
> *NITO: Neural Implicit Fields for Resolution-free Topology Optimization* — Verified paper existence, but I cannot verify literature for this specific niche (explicit SIMP coupling) from currently accessible metadata alone.
>
> **What this means for our research positioning:**
> The strongest defensible gap is: a DL-accelerated SIMP loop with explicit in-loop feasibility/optimality correction (not pure end-to-end image prediction).
> </details>

## 🤝 Contributing
Do you have harsher PI quotes, or have you discovered deeper AI lazy habits? Feel free to submit a PR to help expand the framework! 

**Just for fun! 😄**