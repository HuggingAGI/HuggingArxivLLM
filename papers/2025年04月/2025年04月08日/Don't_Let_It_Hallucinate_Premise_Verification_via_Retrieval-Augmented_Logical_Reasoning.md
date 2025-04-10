# 别让它乱想：借助检索增强逻辑推理验证前提

发布时间：2025年04月08日

`RAG` `信息检索` `生成系统`

> Don't Let It Hallucinate: Premise Verification via Retrieval-Augmented Logical Reasoning

# 摘要

> 大型语言模型（LLMs）在生成流畅、上下文相关的回应方面表现出色，但它们也可能产生幻觉输出，尤其当用户查询包含错误前提时。这些错误前提可能误导LLMs生成虚假或误导性内容。现有的解决方案如预训练、微调和推理时技术，往往计算成本高、依赖大量数据，或缺乏主动预防机制，限制了其在实时应用中的效果。我们提出了一种基于检索的框架，能够在生成前识别并处理错误前提。具体来说，我们首先将用户查询转化为逻辑表示，然后借助检索增强生成（RAG）方法，利用事实来源验证每个前提的有效性。最后，我们将验证结果整合到LLM的提示中，确保最终输出的事实一致性。实验结果表明，该方法有效减少了幻觉现象，提高了事实准确性，且无需访问模型logits或进行大规模微调。

> Large language models (LLMs) have shown substantial capacity for generating fluent, contextually appropriate responses. However, they can produce hallucinated outputs, especially when a user query includes one or more false premises-claims that contradict established facts. Such premises can mislead LLMs into offering fabricated or misleading details. Existing approaches include pretraining, fine-tuning, and inference-time techniques that often rely on access to logits or address hallucinations after they occur. These methods tend to be computationally expensive, require extensive training data, or lack proactive mechanisms to prevent hallucination before generation, limiting their efficiency in real-time applications. We propose a retrieval-based framework that identifies and addresses false premises before generation. Our method first transforms a user's query into a logical representation, then applies retrieval-augmented generation (RAG) to assess the validity of each premise using factual sources. Finally, we incorporate the verification results into the LLM's prompt to maintain factual consistency in the final output. Experiments show that this approach effectively reduces hallucinations, improves factual accuracy, and does not require access to model logits or large-scale fine-tuning.

[Arxiv](https://arxiv.org/abs/2504.06438)