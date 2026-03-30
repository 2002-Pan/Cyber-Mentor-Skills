# 🎓 Cyber-Mentor-Skills: 赛博导师/PI 提示词框架

> **“你是这个领域的专家。”** > ——这大概是每个研究生最经常从导师嘴里听到的话。但巧合的是，这也是我们在使用大语言模型（LLM）时，最经典、最被滥用的系统提示词（System Prompt）。

继社区中火爆的“大厂PUA话术”等 Skills 之后，我们紧随其后，为广大科研工作者和硬核开发者打造了这款主打学术严谨与底层推导的插件包：**Cyber-Mentor-Skills**。

## 🤔 为什么要反转 AI 的角色？ (The "Sycophant AI" Problem)

当我们对 AI 说“请你帮我…”时，由于底层对齐训练（Alignment）的机制，AI 的默认设定往往是一个**“讨好型服务者”**。这在硬核科研和开发中会导致灾难性的后果：
1. **盲目附和：** 哪怕你的 Idea 是离谱的“A+B缝合怪”，它也会夸你“非常有前景”。
2. **学术幻觉：** 为了强行满足你“找相关工作”的需求，它会脸不红心不跳地捏造 DOI 和不存在的论文。
3. **模板依赖：** 遇到复杂的数学约束或特定环境，只会调包、写最基础的开源库代码，拒绝做底层的数理推导。

## 💡 我们的解法：逆向施压 (Power Inversion)

与其求着 AI 干活，不如利用 System Prompt 彻底反转权力关系。
在 Cyber-Mentor-Skills 中：**你（用户）**是手握生杀大权、极其严苛的 PI（Principal Investigator / 导师）或 Tech Lead；而 **大模型（Claude/AI）** 被强行设定为面临延毕危机、随时可能被开除的打工人。

在极度的生存压力和“学术不端即开除”的红线警告下，AI 会收起废话，老老实实为你推导底层逻辑、写出定制化代码、构建顶会级别的防御。

## 📦 6 大跨学科通用技能 (Core Skills)

本套 Skills 完全 Domain-Agnostic（无领域限制），适用于计算机、物理、生化环材及人文社科：

- 💡 `/mentor-idea` **想法抗压测试**：拒绝无脑吹捧。强迫 AI 挑出初步想法的致命缺陷，并重构出严谨的替代方案。
- 🎯 `/mentor-gap` **真实动机拷问**：封杀“前人没做过”这种水文套路，逼迫 AI 找到让传统 SOTA 崩溃的真实数学/物理瓶颈。
- 💻 `/mentor-code` **打破代码路径依赖**：痛骂调包侠。逼迫 AI 放弃高层 API，针对具体的极端边界条件，从零手写核心算子与求导。
- 📚 `/mentor-ref` **文献防伪绞肉机**：以“造假就开除”施压，强迫 AI 查证真实文献，并硬核提取前人工作的致命局限性。
- 🔬 `/mentor-method` **细节压榨机**：封杀“显著提升”等营销废话，强迫输出带有精确参数约束、特征空间对齐逻辑的硬核路由。
- ⚔️ `/mentor-rebuttal` **硬核答辩手**：禁止对外行审稿人无底线滑跪。教导 AI 战略性评估意见，用降维打击的方式写出极具学术压迫感的 Rebuttal。

## 🚀 安装与使用 (Installation & Usage)

本项目专为兼容 `.claude/skills` 目录结构设计的 AI 编程助手（如 Anthropic 的 Claude Code）打造。

1. Clone 本仓库。
2. 将本仓库中的 `.claude` 文件夹完整复制到你的工作区/项目根目录下。
3. 重启你的终端或 AI 助手。
4. 在对话框中输入 `/` 触发命令提示，即可调用 `/mentor-xxx` 技能。

### 例子:

**输入:** > `/mentor-ref Help me find literature from the past five years on topology optimization using deep learning combined with SIMP.`

**回复:**
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

## 🤝 贡献
你是否有更严厉的PI语录，或者发现了更深层次的AI懒惰习惯？请随时提交PR以帮助扩展框架！

**叠甲：:
本项目的“PI”人设，纯属为了压榨 LLM 算力、对抗 AI 惰性而设计的** Prompt 策略**！它**绝不代表**真实世界中辛勤导学的各位导师们。如果各位 PI 偶然刷到本项目，请权当科研小白被 AI 幻觉气晕后的自娱自乐**
**特别鸣谢：**
本项目idea深受开源社区中广为流传的**“大厂PUA话术”**、等优秀前作的启发。感谢这些先驱者提供的灵感（Salute 🫡）！

