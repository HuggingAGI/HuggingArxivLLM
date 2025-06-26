# GPTailor：基于层切割与拼接的大型语言模型剪枝方法

发布时间：2025年06月25日

`LLM理论

理由：这篇论文专注于大型语言模型（LLMs）的结构化剪枝和优化策略，提出了一种创新的方法来压缩模型，同时保留性能。研究涉及模型结构的调整和优化理论，属于LLM理论范畴。` `人工智能` `计算机科学`

> GPTailor: Large Language Model Pruning Through Layer Cutting and Stitching

# 摘要

> 大型语言模型（LLMs）在语言理解和生成方面表现卓越，但其庞大的规模给部署和推理带来了巨大挑战。虽然结构化剪枝为降低计算成本提供了有效途径，但现有方法多聚焦于单个模型的剪枝。本研究提出了一种创新策略，通过有策略地组合或合并来自不同微调模型变体的层，实现模型压缩。该方法通过聚合不同微调过程中强化的能力，保留了原始模型的性能。我们将LLMs的最优调整视为零阶优化问题，采用支持层移除、层选择和层合并的搜索空间。实验表明，该方法在模型剪枝方面表现优异。例如，Llama2-13B模型家族的压缩版本在移除约25%参数的同时，仍保持了97.3%的原始性能，显著优于现有最优方法。代码已开源，地址为https://github.com/Guinan-Su/auto-merge-llm。

> Large language models (LLMs) have shown remarkable capabilities in language understanding and generation. However, such impressive capability typically comes with a substantial model size, which presents significant challenges in deployment and inference. While structured pruning of model parameters offers a promising way to reduce computational costs at deployment time, current methods primarily focus on single model pruning. In this work, we develop a novel strategy to compress models by strategically combining or merging layers from finetuned model variants, which preserves the original model's abilities by aggregating capabilities accentuated in different finetunes. We pose the optimal tailoring of these LLMs as a zero-order optimization problem, adopting a search space that supports three different operations: (1) Layer removal, (2) Layer selection from different candidate models, and (3) Layer merging. Our experiments demonstrate that this approach leads to competitive model pruning, for example, for the Llama2-13B model families, our compressed models maintain approximately 97.3\% of the original performance while removing $\sim25\%$ of parameters, significantly outperforming previous state-of-the-art methods. The code is available at https://github.com/Guinan-Su/auto-merge-llm.

[Arxiv](https://arxiv.org/abs/2506.20480)