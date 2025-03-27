# 从探索到突破：基于视觉上下文缩放与自我奖励对齐的长视频理解新进展

发布时间：2025年03月26日

`LLM应用` `视频理解` `多模态模型`

> From Trial to Triumph: Advancing Long Video Understanding via Visual Context Sample Scaling and Self-reward Alignment

# 摘要

> 多模态大型语言模型（MLLMs）在视频理解方面展现出了非凡的能力。然而，理解长视频仍然充满挑战，因为模型在单次推理中只能处理有限数量的帧，可能遗漏关键视觉信息。为了解决这一难题，我们提出了一种基于视觉上下文采样的多预测生成方法，随后通过评分机制选择最优预测。具体而言，我们设计了一种基于分箱的采样策略，使MLLMs能够基于关键帧的不同组合生成多样化的答案，从而丰富视觉上下文。为了从采样的答案中确定最终预测，我们采用了一种自我奖励机制，通过线性组合三个分数来实现：频率分数、边际置信度分数和推理分数。频率分数通过多数正确性确保了稳健性，置信度对齐分数反映了预测的确定性，而类型化推理分数则通过定制策略处理视觉关键信息稀疏的情况。实验表明，该方法能够覆盖长视频问题中正确答案的高百分比，在七个数据集上的结果显示，我们的方法显著提升了三种MLLM的性能。

> Multi-modal Large language models (MLLMs) show remarkable ability in video understanding. Nevertheless, understanding long videos remains challenging as the models can only process a finite number of frames in a single inference, potentially omitting crucial visual information. To address the challenge, we propose generating multiple predictions through visual context sampling, followed by a scoring mechanism to select the final prediction. Specifically, we devise a bin-wise sampling strategy that enables MLLMs to generate diverse answers based on various combinations of keyframes, thereby enriching the visual context. To determine the final prediction from the sampled answers, we employ a self-reward by linearly combining three scores: (1) a frequency score indicating the prevalence of each option, (2) a marginal confidence score reflecting the inter-intra sample certainty of MLLM predictions, and (3) a reasoning score for different question types, including clue-guided answering for global questions and temporal self-refocusing for local questions. The frequency score ensures robustness through majority correctness, the confidence-aligned score reflects prediction certainty, and the typed-reasoning score addresses cases with sparse key visual information using tailored strategies. Experiments show that this approach covers the correct answer for a high percentage of long video questions, on seven datasets show that our method improves the performance of three MLLMs.

[Arxiv](https://arxiv.org/abs/2503.20472)