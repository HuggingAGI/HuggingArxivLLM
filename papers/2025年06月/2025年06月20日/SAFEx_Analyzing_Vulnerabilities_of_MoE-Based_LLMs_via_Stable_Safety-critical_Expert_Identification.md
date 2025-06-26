# SAFEx: 利用稳定安全关键专家识别分析基于 MoE 的大型语言模型漏洞

发布时间：2025年06月20日

`LLM理论

论文摘要：基于专家混合模型（Mixture-of-Experts）的大型语言模型在效率和可扩展性方面取得了显著提升，但其独特的架构特性带来了尚未被充分探索的安全对齐挑战。现有的安全对齐策略主要针对密集型模型设计，难以有效应对专家混合模型（MoE）特有的漏洞。在本研究中，我们系统地形式化并研究了MoE模型的位置依赖性漏洞，揭示了MoE架构内在的关键风险。为此，我们提出了SAFEx，一个稳健的分析框架，通过一种新颖的基于稳定性的专家选择（SES）算法，能够可靠地识别、表征和验证关键安全专家模块。值得注意的是，我们的方法能够将关键安全专家模块显式地分解为不同的功能组，包括负责有害内容检测的模块以及控制安全响应生成的模块。在主流的MoE模型上进行的大量实验，例如近期发布的Qwen3-MoE，表明其内在的安全机制严重依赖于一小部分特定位置的专家模块。禁用这些专家模块显著削弱了模型拒绝有害请求的能力。以拥有6144个专家模块（FNN层）的Qwen3-MoE为例，我们发现禁用仅12个被识别为关键安全专家的模块，即可使拒绝率下降22%，这凸显了少量专家模块对整体模型安全的不成比例影响。

LLM理论` `人工智能` `模型安全`

> SAFEx: Analyzing Vulnerabilities of MoE-Based LLMs via Stable Safety-critical Expert Identification

# 摘要

> 基于专家混合模型（Mixture-of-Experts）的大型语言模型在效率和可扩展性方面取得了显著提升，但其独特的架构特性带来了尚未被充分探索的安全对齐挑战。现有的安全对齐策略主要针对密集型模型设计，难以有效应对专家混合模型（MoE）特有的漏洞。在本研究中，我们系统地形式化并研究了MoE模型的位置依赖性漏洞，揭示了MoE架构内在的关键风险。为此，我们提出了SAFEx，一个稳健的分析框架，通过一种新颖的基于稳定性的专家选择（SES）算法，能够可靠地识别、表征和验证关键安全专家模块。值得注意的是，我们的方法能够将关键安全专家模块显式地分解为不同的功能组，包括负责有害内容检测的模块以及控制安全响应生成的模块。在主流的MoE模型上进行的大量实验，例如近期发布的Qwen3-MoE，表明其内在的安全机制严重依赖于一小部分特定位置的专家模块。禁用这些专家模块显著削弱了模型拒绝有害请求的能力。以拥有6144个专家模块（FNN层）的Qwen3-MoE为例，我们发现禁用仅12个被识别为关键安全专家的模块，即可使拒绝率下降22%，这凸显了少量专家模块对整体模型安全的不成比例影响。

> Large language models based on Mixture-of-Experts have achieved substantial gains in efficiency and scalability, yet their architectural uniqueness introduces underexplored safety alignment challenges. Existing safety alignment strategies, predominantly designed for dense models, are ill-suited to address MoE-specific vulnerabilities. In this work, we formalize and systematically study MoE model's positional vulnerability - the phenomenon where safety-aligned behaviors rely on specific expert modules, revealing critical risks inherent to MoE architectures. To this end, we present SAFEx, an analytical framework that robustly identifies, characterizes, and validates the safety-critical experts using a novel Stability-based Expert Selection (SES) algorithm. Notably, our approach enables the explicit decomposition of safety-critical experts into distinct functional groups, including those responsible for harmful content detection and those controlling safe response generation. Extensive experiments on mainstream MoE models, such as the recently released Qwen3-MoE, demonstrated that their intrinsic safety mechanisms heavily rely on a small subset of positional experts. Disabling these experts significantly compromised the models' ability to refuse harmful requests. For Qwen3-MoE with 6144 experts (in the FNN layer), we find that disabling as few as 12 identified safety-critical experts can cause the refusal rate to drop by 22%, demonstrating the disproportionate impact of a small set of experts on overall model safety.

[Arxiv](https://arxiv.org/abs/2506.17368)