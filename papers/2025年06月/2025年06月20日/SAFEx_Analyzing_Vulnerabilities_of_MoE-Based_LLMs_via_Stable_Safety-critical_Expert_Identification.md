# SAFEx：基于稳定安全关键专家识别的MoE架构LLM漏洞分析

发布时间：2025年06月20日

`LLM理论` `人工智能` `模型安全`

> SAFEx: Analyzing Vulnerabilities of MoE-Based LLMs via Stable Safety-critical Expert Identification

# 摘要

> 基于专家混合模型的大语言模型在效率和扩展性方面取得了显著提升，但其独特的架构特性带来了尚未被充分探索的安全对齐挑战。现有的安全对齐策略主要针对密集型模型设计，难以有效应对MoE模型特有的脆弱性。本研究正式定义并系统性地探讨了MoE模型的定位脆弱性现象——即安全对齐行为依赖特定专家模块，揭示了MoE架构内在的关键风险。为此，我们提出了SAFEx框架，通过新颖的基于稳定性的专家选择（SES）算法，稳健地识别、表征和验证安全关键型专家。值得注意的是，我们的方法能够将安全关键型专家显式地分解为不同的功能组，包括负责有害内容检测的专家模块以及控制安全响应生成的专家模块。在主流MoE模型（如近期发布的Qwen3-MoE）上的广泛实验表明，其内在的安全机制严重依赖于少量特定位置的专家模块。禁用这些专家模块会显著削弱模型拒绝有害请求的能力。以FNN层拥有6144个专家的Qwen3-MoE为例，我们发现禁用仅12个已识别的安全关键型专家即可使拒绝率下降22%，这充分展示了少量专家模块对整体模型安全的决定性影响。

> Large language models based on Mixture-of-Experts have achieved substantial gains in efficiency and scalability, yet their architectural uniqueness introduces underexplored safety alignment challenges. Existing safety alignment strategies, predominantly designed for dense models, are ill-suited to address MoE-specific vulnerabilities. In this work, we formalize and systematically study MoE model's positional vulnerability - the phenomenon where safety-aligned behaviors rely on specific expert modules, revealing critical risks inherent to MoE architectures. To this end, we present SAFEx, an analytical framework that robustly identifies, characterizes, and validates the safety-critical experts using a novel Stability-based Expert Selection (SES) algorithm. Notably, our approach enables the explicit decomposition of safety-critical experts into distinct functional groups, including those responsible for harmful content detection and those controlling safe response generation. Extensive experiments on mainstream MoE models, such as the recently released Qwen3-MoE, demonstrated that their intrinsic safety mechanisms heavily rely on a small subset of positional experts. Disabling these experts significantly compromised the models' ability to refuse harmful requests. For Qwen3-MoE with 6144 experts (in the FNN layer), we find that disabling as few as 12 identified safety-critical experts can cause the refusal rate to drop by 22%, demonstrating the disproportionate impact of a small set of experts on overall model safety.

[Arxiv](https://arxiv.org/abs/2506.17368)