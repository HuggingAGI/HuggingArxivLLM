# 针对具有结构重要性认知的大型语言模型的自适应剪枝

发布时间：2024年12月19日

`LLM应用` `边缘计算` `模型压缩`

> Adaptive Pruning for Large Language Models with Structural Importance Awareness

# 摘要

> 大型语言模型（LLMs）近来取得的进步极大地提升了语言理解和生成的能力。然而，因其对计算和存储资源的需求颇高，在资源有限的边缘设备上部署 LLMs 颇具难度。为应对此问题，我们提出了一种全新的 LLM 模型剪枝方法——结构感知自适应剪枝（SAAP），在维持模型性能的同时大幅降低计算和内存成本。我们先是定义了一个自适应重要性融合指标，通过考量其同方差不确定性来评估 LLMs 中所有耦合结构的重要性。接着，对所有模块的重要性进行排序，确定应剪枝的特定层，以满足特定性能要求。此外，我们还研发了一种新的分组微调策略，以提升 LLMs 的推理效率。最后，我们在多个 LLMs 上针对零样本分类和文本生成这两项常见任务，对所提出的 SAAP 方法进行了评估。实验结果显示，我们的 SAAP 方法优于数种先进的基线方法，在 LLaMA-7B、Vicuna-7B 和 LLaMA-13B 上分别实现了 2.17％、2.37％和 2.39％的准确率提升。另外，SAAP 使令牌生成速度提高了 5％，展现出其在资源受限场景中的实际优势。

> The recent advancements in large language models (LLMs) have significantly improved language understanding and generation capabilities. However, it is difficult to deploy LLMs on resource-constrained edge devices due to their high computational and storage resource demands. To address this issue, we propose a novel LLM model pruning method, namely structurally-aware adaptive pruning (SAAP), to significantly reduce the computational and memory costs while maintaining model performance. We first define an adaptive importance fusion metric to evaluate the importance of all coupled structures in LLMs by considering their homoscedastic uncertainty. Then, we rank the importance of all modules to determine the specific layers that should be pruned to meet particular performance requirements. Furthermore, we develop a new group fine-tuning strategy to improve the inference efficiency of LLMs. Finally, we evaluate the proposed SAAP method on multiple LLMs across two common tasks, i.e., zero-shot classification and text generation. Experimental results show that our SAAP method outperforms several state-of-the-art baseline methods, achieving 2.17%, 2.37%, and 2.39% accuracy gains on LLaMA-7B, Vicuna-7B, and LLaMA-13B. Additionally, SAAP improves the token generation speed by 5%, showcasing its practical advantages in resource-constrained scenarios.

[Arxiv](https://arxiv.org/abs/2412.15127)