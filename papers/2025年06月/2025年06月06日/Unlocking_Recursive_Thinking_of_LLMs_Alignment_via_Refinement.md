# 开启LLM递归思维：精调对齐新思路

发布时间：2025年06月06日

`LLM理论` `人工智能` `机器学习`

> Unlocking Recursive Thinking of LLMs: Alignment via Refinement

# 摘要

> OpenAI 的 o1 系列模型证实，长形式思维链（CoT）能够显著提升模型性能。然而，大型语言模型（LLMs）在递归推理能力上仍有局限，尤其是在缺乏专家整理数据用于蒸馏的情况下。本文提出了一种名为 	extbf{AvR}（	extbf{通过精调实现对齐}）的创新方法，旨在通过长形式 CoT 充分释放 LLMs 的递归推理潜力。AvR 引入了一种结合批评与改进的精调流程，并借助可微分学习技术优化 	extbf{精调感知奖励}，使多轮合成数据能够组织成一个完整的长精调思维过程，从而实现测试时的性能扩展。实验结果表明，AvR 在性能上显著超越传统偏好优化方法。值得注意的是，仅使用 3 千个合成样本，我们的方法便能在 AlpacaEval 2.0 上将 LLaMA-3-8B-Instruct 模型的胜率提升 20\% 以上。我们的代码已开源，欢迎访问 Github 仓库（https://github.com/Banner-Z/AvR.git）查看。

> The OpenAI o1-series models have demonstrated that leveraging long-form Chain of Thought (CoT) can substantially enhance performance. However, the recursive thinking capabilities of Large Language Models (LLMs) remain limited, particularly in the absence of expert-curated data for distillation. In this paper, we propose \textbf{AvR}: \textbf{Alignment via Refinement}, a novel method aimed at unlocking the potential of LLMs for recursive reasoning through long-form CoT. AvR introduces a refinement process that integrates criticism and improvement actions, guided by differentiable learning techniques to optimize \textbf{refinement-aware rewards}. As a result, the synthesized multi-round data can be organized as a long refinement thought, further enabling test-time scaling. Experimental results show that AvR significantly outperforms conventional preference optimization methods. Notably, with only 3k synthetic samples, our method boosts the performance of the LLaMA-3-8B-Instruct model by over 20\% in win rate on AlpacaEval 2.0. Our code is available at Github (https://github.com/Banner-Z/AvR.git).

[Arxiv](https://arxiv.org/abs/2506.06009)