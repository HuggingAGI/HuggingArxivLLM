# 针对大型语言模型的持续梯度低秩投影微调方法

发布时间：2025年07月03日

`LLM理论` `人工智能`

> Continual Gradient Low-Rank Projection Fine-Tuning for LLMs

# 摘要

> 大型语言模型（LLMs）的持续微调受限于效率与表达能力之间的权衡。低秩适配（LoRA）虽然提供了效率，但其固有的低秩特性和对显式参数约束的依赖限制了模型学习新任务和迁移知识的能力。我们提出了一种名为GORP（Gradient LOw Rank Projection）的持续学习新型训练策略，通过协同结合全秩和低秩参数，并在统一的低秩梯度子空间内联合更新，克服了这些限制。GORP在扩大优化空间的同时，保持了效率并缓解了灾难性遗忘。在持续学习基准上的广泛实验表明，与现有最先进的方法相比，GORP表现更优。代码可在https://github.com/Wcxwcxw/GORP获取。


> Continual fine-tuning of Large Language Models (LLMs) is hampered by the trade-off between efficiency and expressiveness. Low-Rank Adaptation (LoRA) offers efficiency but constrains the model's ability to learn new tasks and transfer knowledge due to its low-rank nature and reliance on explicit parameter constraints. We propose GORP (Gradient LOw Rank Projection) for Continual Learning, a novel training strategy that overcomes these limitations by synergistically combining full and low-rank parameters and jointly updating within a unified low-rank gradient subspace. GORP expands the optimization space while preserving efficiency and mitigating catastrophic forgetting. Extensive experiments on continual learning benchmarks demonstrate GORP's superior performance compared to existing state-of-the-art approaches. Code is available at https://github.com/Wcxwcxw/GORP.

[Arxiv](https://arxiv.org/abs/2507.02503)