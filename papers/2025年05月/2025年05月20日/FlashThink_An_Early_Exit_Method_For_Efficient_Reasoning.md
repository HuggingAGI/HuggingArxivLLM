# FlashThink：实现高效推理的提前退出方法

发布时间：2025年05月20日

`LLM应用

理由：该论文探讨了如何优化大型语言模型的推理过程，通过提前终止推理来提高效率，属于应用层面的研究，因此归类为LLM应用。` `人工智能`

> FlashThink: An Early Exit Method For Efficient Reasoning

# 摘要

> 大型语言模型（LLMs）在推理任务中表现出色，但往往会生成冗长的推理内容，造成巨大的计算负担。我们发现，即使是简单的推理问题，LLMs也常常产生不必要的冗长推理内容，这与直觉预期不符。初步实验表明，在生成过程中的某个时刻，模型已经能够生成正确答案，而无需完成全部推理内容。因此，我们认为可以提前终止模型的推理过程，以实现高效的推理。我们引入了一个验证模型，用于识别模型可以停止推理但仍能提供正确答案的精确时刻。在四个不同基准上的全面实验表明，我们提出的方法FlashThink能够有效缩短推理内容，同时保持模型的准确性。对于Deepseek-R1和QwQ-32B模型，我们将推理内容的长度分别减少了77.04%和77.47%，而没有降低准确性。

> Large Language Models (LLMs) have shown impressive performance in reasoning tasks. However, LLMs tend to generate excessively long reasoning content, leading to significant computational overhead. Our observations indicate that even on simple problems, LLMs tend to produce unnecessarily lengthy reasoning content, which is against intuitive expectations. Preliminary experiments show that at a certain point during the generation process, the model is already capable of producing the correct solution without completing the full reasoning content. Therefore, we consider that the reasoning process of the model can be exited early to achieve the purpose of efficient reasoning. We introduce a verification model that identifies the exact moment when the model can stop reasoning and still provide the correct answer. Comprehensive experiments on four different benchmarks demonstrate that our proposed method, FlashThink, effectively shortens the reasoning content while preserving the model accuracy. For the Deepseek-R1 and QwQ-32B models, we reduced the length of reasoning content by 77.04% and 77.47%, respectively, without reducing the accuracy.

[Arxiv](https://arxiv.org/abs/2505.13949)