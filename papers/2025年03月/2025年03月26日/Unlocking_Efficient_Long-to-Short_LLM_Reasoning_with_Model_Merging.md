# 开启高效长到短的大型语言模型推理：模型合并方法

发布时间：2025年03月26日

`LLM理论` `人工智能`

> Unlocking Efficient Long-to-Short LLM Reasoning with Model Merging

# 摘要

> 从 System 1 到 System 2 推理的转变标志着 LLMs 在复杂任务处理上的重要突破，但效率问题也随之而来——模型常因过度思考而产生冗余推理，却未能相应提升输出质量。长到短（L2S）推理作为一种创新解决方案，致力于在推理深度与实际效率之间找到平衡。现有方法如监督微调（SFT）、强化学习（RL）和提示工程虽有潜力，但或计算成本过高，或不够稳定。相比之下，模型合并提供了一种高效且可靠的解决方案，通过融合 System 1 模型的快速思考能力和 System 2 模型的系统性推理能力，实现性能优化。本文将对 L2S 推理的模型合并进行全面实证研究，探索包括基于任务向量、SVD 和激活信息的多种合并方法。实验结果显示，模型合并可将平均响应长度减少高达 55%，同时保持甚至提升基线性能。通过对 1.5B/7B/14B/32B 模型的广泛评估，我们发现模型规模与合并效果之间存在显著相关性。此外，我们还深入研究了合并模型的自我批判与自我纠错能力，以及其根据任务复杂性自适应调整响应长度的能力。研究结果表明，模型合并不仅是一种高效且有效的 L2S 推理范式，更为过度思考问题提供了切实可行的解决方案，同时保持了 System 2 推理的稳健性。本研究已在 Github 上开源，地址为 https://github.com/hahahawu/Long-to-Short-via-Model-Merging。

> The transition from System 1 to System 2 reasoning in large language models (LLMs) has marked significant advancements in handling complex tasks through deliberate, iterative thinking. However, this progress often comes at the cost of efficiency, as models tend to overthink, generating redundant reasoning steps without proportional improvements in output quality. Long-to-Short (L2S) reasoning has emerged as a promising solution to this challenge, aiming to balance reasoning depth with practical efficiency. While existing approaches, such as supervised fine-tuning (SFT), reinforcement learning (RL), and prompt engineering, have shown potential, they are either computationally expensive or unstable. Model merging, on the other hand, offers a cost-effective and robust alternative by integrating the quick-thinking capabilities of System 1 models with the methodical reasoning of System 2 models. In this work, we present a comprehensive empirical study on model merging for L2S reasoning, exploring diverse methodologies, including task-vector-based, SVD-based, and activation-informed merging. Our experiments reveal that model merging can reduce average response length by up to 55% while preserving or even improving baseline performance. We also identify a strong correlation between model scale and merging efficacy with extensive evaluations on 1.5B/7B/14B/32B models. Furthermore, we investigate the merged model's ability to self-critique and self-correct, as well as its adaptive response length based on task complexity. Our findings highlight model merging as a highly efficient and effective paradigm for L2S reasoning, offering a practical solution to the overthinking problem while maintaining the robustness of System 2 reasoning. This work can be found on Github https://github.com/hahahawu/Long-to-Short-via-Model-Merging.

[Arxiv](https://arxiv.org/abs/2503.20641)