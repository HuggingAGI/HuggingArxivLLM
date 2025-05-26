# VeriThinker：学习验证让推理模型更高效

发布时间：2025年05月23日

`LLM应用` `链式思维`

> VeriThinker: Learning to Verify Makes Reasoning Model Efficient

# 摘要

> 大型推理模型（LRMs）擅长通过链式思维（CoT）推理处理复杂任务，但它们容易陷入过度思考，导致推理链冗长且不必要，显著增加了推理成本。为了解决这一问题，我们提出了一种名为VeriThinker的新颖方法，用于CoT压缩。与传统方法不同，传统方法通过在原始推理任务上使用合成的简洁CoT数据对LRMs进行微调，我们创新性地仅通过一个辅助验证任务对模型进行微调。通过训练LRMs准确验证CoT解决方案的正确性，模型自然变得更加精明，能够辨别后续自我反思步骤的必要性，从而有效抑制过度思考。大量实验验证表明，VeriThinker在保持甚至略微提高准确性的同时，显著缩短了推理链长度。在应用于DeepSeek-R1-Distill-Qwen-7B时，我们的方法将MATH500的推理令牌数从3790减少到2125，同时提高了0.8%的准确性（从94.0%到94.8%）；在AIME25上，令牌数从14321减少到10287，准确率提高了2.1%（从38.7%到40.8%）。此外，我们的实验还表明，VeriThinker可以零样本推广到推测性推理。代码可在https://github.com/czg1225/VeriThinker获取。


> Large Reasoning Models (LRMs) excel at complex tasks using Chain-of-Thought (CoT) reasoning. However, their tendency to overthinking leads to unnecessarily lengthy reasoning chains, dramatically increasing inference costs. To mitigate this issue, we introduce VeriThinker, a novel approach for CoT compression. Unlike conventional methods that fine-tune LRMs directly on the original reasoning task using synthetic concise CoT data, we innovatively fine-tune the model solely through an auxiliary verification task. By training LRMs to accurately verify the correctness of CoT solutions, the LRMs inherently become more discerning about the necessity of subsequent self-reflection steps, thereby effectively suppressing overthinking. Extensive experiments validate that VeriThinker substantially reduces reasoning chain lengths while maintaining or even slightly improving accuracy. When applied to DeepSeek-R1-Distill-Qwen-7B, our approach reduces reasoning tokens on MATH500 from 3790 to 2125 while improving accuracy by 0.8% (94.0% to 94.8%), and on AIME25, tokens decrease from 14321 to 10287 with a 2.1% accuracy gain (38.7% to 40.8%). Additionally, our experiments demonstrate that VeriThinker can also be zero-shot generalized to speculative reasoning. Code is available at https://github.com/czg1225/VeriThinker

[Arxiv](https://arxiv.org/abs/2505.17941)