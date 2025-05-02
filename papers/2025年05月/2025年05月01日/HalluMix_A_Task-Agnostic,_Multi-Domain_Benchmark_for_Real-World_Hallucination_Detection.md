# 混合幻觉：跨任务、跨领域的真实幻觉检测基准测试

发布时间：2025年05月01日

`LLM应用` `人工智能` `基准测试`

> HalluMix: A Task-Agnostic, Multi-Domain Benchmark for Real-World Hallucination Detection

# 摘要

> 随着大型语言模型 (LLMs) 在高风险领域的广泛应用，检测幻觉内容$unicode{x2013}$即缺乏事实依据支持的内容$unicode{x2013}$已成为关键挑战。现有幻觉检测基准通常基于合成数据，专注于抽取式问答，难以捕捉涉及多文档上下文和完整句子输出的真实场景复杂性。我们引入了 HalluMix 基准，这是一个多样化且任务无关的数据集，涵盖多个领域和格式。基于这个基准数据集，我们评估了七种幻觉检测系统$unicode{x2013}$包括开源和闭源$unicode{x2013}$，揭示了不同任务、文档长度和输入表示下的性能差异。分析结果显示，短上下文与长上下文之间存在显著性能差距，这对实际中基于检索增强生成 (RAG) 的实现具有重要启示。Quotient Detections 在整体性能中表现最佳，准确率为 0.82，F1 分数为 0.84。

> As large language models (LLMs) are increasingly deployed in high-stakes domains, detecting hallucinated content$unicode{x2013}$text that is not grounded in supporting evidence$unicode{x2013}$has become a critical challenge. Existing benchmarks for hallucination detection are often synthetically generated, narrowly focused on extractive question answering, and fail to capture the complexity of real-world scenarios involving multi-document contexts and full-sentence outputs. We introduce the HalluMix Benchmark, a diverse, task-agnostic dataset that includes examples from a range of domains and formats. Using this benchmark, we evaluate seven hallucination detection systems$unicode{x2013}$both open and closed source$unicode{x2013}$highlighting differences in performance across tasks, document lengths, and input representations. Our analysis highlights substantial performance disparities between short and long contexts, with critical implications for real-world Retrieval Augmented Generation (RAG) implementations. Quotient Detections achieves the best overall performance, with an accuracy of 0.82 and an F1 score of 0.84.

[Arxiv](https://arxiv.org/abs/2505.00506)