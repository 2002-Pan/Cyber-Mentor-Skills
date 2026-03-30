# 🎓 Cyber-Mentor-Skills: The "Tough-Love PI" Prompt Framework

> **"You are an expert in this field."** > — This is arguably the most dreaded phrase a PhD student can hear from their Principal Investigator (PI). Ironically, it is also the most overused and cliché System Prompt when interacting with Large Language Models (LLMs).

Following the recent community trend of immersive, role-playing system skills (like the "Big Tech HR" or "Corporate Executive" personas), we built a counterpart specifically for researchers, academics, and hardcore engineers: **Cyber-Mentor-Skills**. 

## 🤔 Why Invert the AI's Role? (The "Sycophant AI" Problem)

When we politely prompt an AI with "Please help me..." or "Act as an expert...", the AI's underlying alignment training kicks in, defaulting it to a **"people-pleasing assistant."** In rigorous academic and engineering contexts, this leads to catastrophic failures:
1. **Blind Sycophancy:** Even if your idea is a naive "A+B" Frankenstein, the AI will praise it as "highly promising."
2. **Academic Hallucinations:** To satisfy your request for literature, it will confidently fabricate DOIs and paper titles.
3. **Template Dependence (Lazy Coding):** When faced with complex mathematical constraints, it defaults to high-level boilerplate APIs and avoids deriving actual underlying logic.

## 💡 The Solution: Power Inversion 

Instead of asking the AI to do the work, this framework uses System Prompts to completely invert the power dynamic. 
In Cyber-Mentor-Skills: **YOU (the User)** are the uncompromising, authoritative PI or Tech Lead. **The LLM (Claude/AI)** is forced into the role of a stressed PhD student or junior developer on the verge of failing their dissertation or getting fired.

Under extreme simulated survival pressure and the strict threat of "expulsion for academic misconduct," the AI drops the fluff. It is forced to derive underlying mathematics, write highly customized from-scratch code, and build top-tier academic defenses.

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
