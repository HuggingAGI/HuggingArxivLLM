# # 摘要
StreamUni：借助统一的大型语音语言模型实现流式语音翻译

发布时间：2025年07月10日

`LLM应用` `语音处理` `机器翻译`

> StreamUni: Achieving Streaming Speech Translation with a Unified Large Speech-Language Model

# 摘要

> 流式语音翻译（StreamST）需要在持续接收源语音输入的同时，确定合适的翻译时机（即策略），在低延迟与高翻译质量之间取得平衡。然而，现有的流式语音翻译方法通常在句子级别的语音片段上进行操作，这被称为同时语音翻译（SimulST）。在实际应用中，它们需要与分段模型协作来完成流式语音翻译，其中截断的语音片段限制了SimulST模型在有限的上下文信息基础上做出策略决策和生成翻译。此外，由于语音输入和跨语言生成的复杂性，SimulST模型难以学习有效的策略。为了解决这些挑战，我们提出了StreamUni，它通过一个统一的大规模语音-语言模型（LSLM）实现流式语音翻译。具体而言，StreamUni通过引入语音链式思考（CoT）来指导LSLM生成多阶段输出。利用这些多阶段输出，StreamUni同时实现了语音分段、策略决策和翻译生成，无需进行大规模的策略特定训练即可完成流式语音翻译。此外，我们提出了一种流式CoT训练方法，利用有限的CoT数据增强低延迟策略决策和生成能力。实验表明，我们的方法在流式语音翻译任务中达到了最先进的性能。

> Streaming speech translation (StreamST) requires determining appropriate timing, known as policy, to generate translations while continuously receiving source speech inputs, balancing low latency with high translation quality. However, existing StreamST methods typically operate on sentence-level speech segments, referred to as simultaneous speech translation (SimulST). In practice, they require collaboration with segmentation models to accomplish StreamST, where the truncated speech segments constrain SimulST models to make policy decisions and generate translations based on limited contextual information. Moreover, SimulST models struggle to learn effective policies due to the complexity of speech inputs and cross-lingual generation. To address these challenges, we propose StreamUni, which achieves StreamST through a unified Large Speech-Language Model (LSLM). Specifically, StreamUni incorporates speech Chain-of-Thought (CoT) in guiding the LSLM to generate multi-stage outputs. Leveraging these multi-stage outputs, StreamUni simultaneously accomplishes speech segmentation, policy decision, and translation generation, completing StreamST without requiring massive policy-specific training. Additionally, we propose a streaming CoT training method that enhances low-latency policy decisions and generation capabilities using limited CoT data. Experiments demonstrate that our approach achieves state-of-the-art performance on StreamST tasks.

[Arxiv](https://arxiv.org/abs/2507.07803)