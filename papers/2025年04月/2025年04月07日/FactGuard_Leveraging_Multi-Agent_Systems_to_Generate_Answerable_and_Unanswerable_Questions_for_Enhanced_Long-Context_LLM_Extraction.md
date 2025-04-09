# FactGuard：借助多智能体系统生成可答与不可答的问题，以提升长上下文LLM的提取效果

发布时间：2025年04月07日

`LLM应用` `问答系统`

> FactGuard: Leveraging Multi-Agent Systems to Generate Answerable and Unanswerable Questions for Enhanced Long-Context LLM Extraction

# 摘要

> 抽取式阅读理解系统致力于从文本中精准定位问题的答案，但如何在保持高准确性的前提下准确识别不可回答的问题，始终是一个难题。尽管大型语言模型（LLMs）在阅读理解领域取得了显著突破，但这一挑战依然严峻，尤其是在处理长上下文时。为此，我们提出了一种基于多智能体协作框架的创新数据增强方法。与依赖昂贵人工标注的传统方法（如 SQuAD 2.0 数据集的构建）不同，我们的方法能够自主生成基于证据的问题-答案对，并系统性地构建不可回答的问题。通过这一方法，我们开发了包含 25,220 个可回答和不可回答问题场景的 FactGuard-Bench 数据集，上下文长度覆盖从 8K 到 128K 的范围。实验结果表明，即使是最先进的 LLM，整体准确率也仅为 61.79%。此外，我们强调了模型对不可回答问题进行推理能力的重要性，以避免生成看似合理却错误的答案。通过在多智能体协作框架内实现高效的数据选择和生成，我们的方法显著降低了传统人工标注的成本，为 LLM 的训练和优化提供了重要参考。

> Extractive reading comprehension systems are designed to locate the correct answer to a question within a given text. However, a persistent challenge lies in ensuring these models maintain high accuracy in answering questions while reliably recognizing unanswerable queries. Despite significant advances in large language models (LLMs) for reading comprehension, this issue remains critical, particularly as the length of supported contexts continues to expand. To address this challenge, we propose an innovative data augmentation methodology grounded in a multi-agent collaborative framework. Unlike traditional methods, such as the costly human annotation process required for datasets like SQuAD 2.0, our method autonomously generates evidence-based question-answer pairs and systematically constructs unanswerable questions. Using this methodology, we developed the FactGuard-Bench dataset, which comprises 25,220 examples of both answerable and unanswerable question scenarios, with context lengths ranging from 8K to 128K. Experimental evaluations conducted on seven popular LLMs reveal that even the most advanced models achieve only 61.79% overall accuracy. Furthermore, we emphasize the importance of a model's ability to reason about unanswerable questions to avoid generating plausible but incorrect answers. By implementing efficient data selection and generation within the multi-agent collaborative framework, our method significantly reduces the traditionally high costs associated with manual annotation and provides valuable insights for the training and optimization of LLMs.

[Arxiv](https://arxiv.org/abs/2504.05607)