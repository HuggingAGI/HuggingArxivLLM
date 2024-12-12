# Magneto：把小型和大型语言模型相结合以用于模式匹配

发布时间：2024年12月11日

`LLM应用` `生物医学` `模式匹配`

> Magneto: Combining Small and Large Language Models for Schema Matching

# 摘要

> 近期语言模型的进步为处理复杂的模式匹配任务带来了新契机。已有的模式匹配方法虽展现出语言模型的效用，但也暴露出重要局限：小型语言模型（SLMs）需要训练数据（获取成本高且难度大），大型语言模型（LLMs）通常计算成本高昂，还得应对上下文窗口带来的限制。我们推出了 Magneto，这是一种兼具性价比与准确性的模式匹配方案，融合了 SLMs 和 LLMs 的优势，以克服它们的不足。通过将模式匹配流程划分为检索和重排序两个阶段，Magneto 能够运用计算高效的基于 SLM 的策略得出候选匹配，再由 LLMs 进行重排序，从而在不影响匹配精度的情况下降低运行时间。我们提出了一种自监督方式来微调 SLMs，利用 LLMs 生成语法多样的训练数据，以及有效的重排序提示策略。我们还引入了一个新的基准，与领域专家合作开发，其中涵盖真实的生物医学数据集，给模式匹配方法带来新挑战。通过使用新基准和现有基准开展细致的实验评估，我们表明 Magneto 具有可扩展性，对于不同领域的数据集能实现高精度。

> Recent advances in language models opened new opportunities to address complex schema matching tasks. Schema matching approaches have been proposed that demonstrate the usefulness of language models, but they have also uncovered important limitations: Small language models (SLMs) require training data (which can be both expensive and challenging to obtain), and large language models (LLMs) often incur high computational costs and must deal with constraints imposed by context windows. We present Magneto, a cost-effective and accurate solution for schema matching that combines the advantages of SLMs and LLMs to address their limitations. By structuring the schema matching pipeline in two phases, retrieval and reranking, Magneto can use computationally efficient SLM-based strategies to derive candidate matches which can then be reranked by LLMs, thus making it possible to reduce runtime without compromising matching accuracy. We propose a self-supervised approach to fine-tune SLMs which uses LLMs to generate syntactically diverse training data, and prompting strategies that are effective for reranking. We also introduce a new benchmark, developed in collaboration with domain experts, which includes real biomedical datasets and presents new challenges to schema matching methods. Through a detailed experimental evaluation, using both our new and existing benchmarks, we show that Magneto is scalable and attains high accuracy for datasets from different domains.

[Arxiv](https://arxiv.org/abs/2412.08194)