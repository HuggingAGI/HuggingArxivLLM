# InfiGFusion: 基于高效Gromov-Wasserstein的对数概率图蒸馏实现模型融合

发布时间：2025年05月19日

`LLM应用` `AI研究` `模型融合`

> InfiGFusion: Graph-on-Logits Distillation via Efficient Gromov-Wasserstein for Model Fusion

# 摘要

> 大型语言模型（LLMs）的最新进展推动了将异构开源模型融合为统一系统的研究，以充分利用它们各自的互补优势。然而，现有的基于logit的融合方法虽然保持了推理效率，但未能充分考虑跨维度交互中的语义依赖关系。这些依赖关系反映了不同token类型在模型内部推理过程中的交互方式，对协调多样化生成行为的模型至关重要。为此，我们提出了	extbf{InfiGFusion}，这是首个基于结构感知的融合框架，采用了创新的	extit{Graph-on-Logits Distillation}（GLD）损失。具体而言，我们通过保留每个输出的top-$k$ logit，并跨序列位置聚合其外积，构建了一个全局协同激活图，其中节点代表词表通道，边则量化了它们的联合激活程度。为了确保高效性和可扩展性，我们设计了一种基于排序的闭式近似方法，将Gromov-Wasserstein距离的原始$O(n^4)$计算成本降低至$O(n \log n)$，并提供了可证明的近似保证。实验结果表明，GLD在多种融合设置下显著提升了融合质量和稳定性。InfiGFusion在涵盖推理、编码和数学的11个基准测试中超越了现有最优模型和融合基线。特别地，在复杂推理任务中，InfiGFusion在Multistep Arithmetic和Causal Judgement上分别比SFT提升了+35.6和+37.06，展现了其在多步推理和关系推理方面的卓越能力。

> Recent advances in large language models (LLMs) have intensified efforts to fuse heterogeneous open-source models into a unified system that inherits their complementary strengths. Existing logit-based fusion methods maintain inference efficiency but treat vocabulary dimensions independently, overlooking semantic dependencies encoded by cross-dimension interactions. These dependencies reflect how token types interact under a model's internal reasoning and are essential for aligning models with diverse generation behaviors. To explicitly model these dependencies, we propose \textbf{InfiGFusion}, the first structure-aware fusion framework with a novel \textit{Graph-on-Logits Distillation} (GLD) loss. Specifically, we retain the top-$k$ logits per output and aggregate their outer products across sequence positions to form a global co-activation graph, where nodes represent vocabulary channels and edges quantify their joint activations. To ensure scalability and efficiency, we design a sorting-based closed-form approximation that reduces the original $O(n^4)$ cost of Gromov-Wasserstein distance to $O(n \log n)$, with provable approximation guarantees. Experiments across multiple fusion settings show that GLD consistently improves fusion quality and stability. InfiGFusion outperforms SOTA models and fusion baselines across 11 benchmarks spanning reasoning, coding, and mathematics. It shows particular strength in complex reasoning tasks, with +35.6 improvement on Multistep Arithmetic and +37.06 on Causal Judgement over SFT, demonstrating superior multi-step and relational inference.

[Arxiv](https://arxiv.org/abs/2505.13893)