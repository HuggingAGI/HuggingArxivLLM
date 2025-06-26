# 思维锚点：LLM推理过程中的关键步骤究竟有哪些？

发布时间：2025年06月23日

`LLM理论` `人工智能`

> Thought Anchors: Which LLM Reasoning Steps Matter?

# 摘要

> 擅长推理的大型语言模型在多个领域取得了卓越性能，但其长篇链式推理过程由于每个标记都依赖于之前的所有标记，导致计算难以分解，带来了可解释性挑战。我们提出，从句子层面分析推理轨迹是理解推理过程的有效方法。我们开发了三种互补的归因方法：(1) 黑箱方法通过比较生成某句或其变体的100次推理结果，评估其反事实重要性；(2) 白箱方法通过分析句子对的注意力模式，识别出被后续句子过度关注的“广播”句子；(3) 因果归因方法通过抑制对某句的注意力，测量其对后续句子的影响，揭示逻辑联系。这些方法均证实了“思维锚点”的存在，即那些对推理过程具有决定性影响的关键句子，通常为规划或回溯类型。我们开源了一个工具（www.thought-anchors.com）用于可视化分析结果，并通过案例研究展示了方法间的一致性，揭示了模型的多步推理机制。这些发现凸显了句子层面分析在深入理解推理模型中的潜力。


> Reasoning large language models have recently achieved state-of-the-art performance in many fields. However, their long-form chain-of-thought reasoning creates interpretability challenges as each generated token depends on all previous ones, making the computation harder to decompose. We argue that analyzing reasoning traces at the sentence level is a promising approach to understanding reasoning processes. We present three complementary attribution methods: (1) a black-box method measuring each sentence's counterfactual importance by comparing final answers across 100 rollouts conditioned on the model generating that sentence or one with a different meaning; (2) a white-box method of aggregating attention patterns between pairs of sentences, which identified ``broadcasting'' sentences that receive disproportionate attention from all future sentences via ``receiver'' attention heads; (3) a causal attribution method measuring logical connections between sentences by suppressing attention toward one sentence and measuring the effect on each future sentence's tokens. Each method provides evidence for the existence of thought anchors, reasoning steps that have outsized importance and that disproportionately influence the subsequent reasoning process. These thought anchors are typically planning or backtracking sentences. We provide an open-source tool (www.thought-anchors.com) for visualizing the outputs of our methods, and present a case study showing converging patterns across methods that map how a model performs multi-step reasoning. The consistency across methods demonstrates the potential of sentence-level analysis for a deeper understanding of reasoning models.

[Arxiv](https://arxiv.org/abs/2506.19143)