# 大型语言模型能否处理多语言长上下文？探讨超越检索与信息堆的长上下文评估方法

发布时间：2025年04月17日

`LLM应用

论文摘要：现有的多语言长上下文基准测试大多基于“针在稻草堆中”的测试方法，主要考察模型在大量无关文本中找到特定信息的能力。然而，这种以检索为核心的评估方式目光短浅，仅凭成功召回信息并不能说明模型具备处理长上下文推理的能力。此外，这些基准测试还存在数据泄漏、短路问题以及使评估结果可预测的风险。为了解决这些局限性，我们推出了MLRBench，一个多语言长上下文推理的新合成基准测试。与现有基准测试不同，MLRBench不仅关注表面级别的信息检索，还包含了多跳推理、信息聚合和知识推理等任务。覆盖七种语言，MLRBench设计上具有并行性、抗泄漏性和可扩展性，能够适应任意长度的上下文。通过使用开源权重的大语言模型（LLM）进行的广泛实验，我们发现高资源语言和低资源语言之间存在显著差距，尤其是在需要模型聚合多个事实或预测信息缺失的任务中。我们还发现，在多语言环境下，LLMs实际利用的上下文长度不到其声称长度的30%。尽管现成的检索增强生成技术在一定程度上缓解了这一问题，但它并未真正解决长上下文的挑战。为了推动多语言LLM在评估和训练方面的改进研究，我们开源了MLRBench。

LLM应用` `多语言`

> Can LLMs reason over extended multilingual contexts? Towards long-context evaluation beyond retrieval and haystacks

# 摘要

> 现有的多语言长上下文基准测试大多基于“针在稻草堆中”的测试方法，主要考察模型在大量无关文本中找到特定信息的能力。然而，这种以检索为核心的评估方式目光短浅，仅凭成功召回信息并不能说明模型具备处理长上下文推理的能力。此外，这些基准测试还存在数据泄漏、短路问题以及使评估结果可预测的风险。为了解决这些局限性，我们推出了MLRBench，一个多语言长上下文推理的新合成基准测试。与现有基准测试不同，MLRBench不仅关注表面级别的信息检索，还包含了多跳推理、信息聚合和知识推理等任务。覆盖七种语言，MLRBench设计上具有并行性、抗泄漏性和可扩展性，能够适应任意长度的上下文。通过使用开源权重的大语言模型（LLM）进行的广泛实验，我们发现高资源语言和低资源语言之间存在显著差距，尤其是在需要模型聚合多个事实或预测信息缺失的任务中。我们还发现，在多语言环境下，LLMs实际利用的上下文长度不到其声称长度的30%。尽管现成的检索增强生成技术在一定程度上缓解了这一问题，但它并未真正解决长上下文的挑战。为了推动多语言LLM在评估和训练方面的改进研究，我们开源了MLRBench。

> Existing multilingual long-context benchmarks, often based on the popular needle-in-a-haystack test, primarily evaluate a model's ability to locate specific information buried within irrelevant texts. However, such a retrieval-centric approach is myopic and inherently limited, as successful recall alone does not indicate a model's capacity to reason over extended contexts. Moreover, these benchmarks are susceptible to data leakage, short-circuiting, and risk making the evaluation a priori identifiable. To address these limitations, we introduce MLRBench, a new synthetic benchmark for multilingual long-context reasoning. Unlike existing benchmarks, MLRBench goes beyond surface-level retrieval by including tasks that assess multi-hop inference, aggregation, and epistemic reasoning. Spanning seven languages, MLRBench is designed to be parallel, resistant to leakage, and scalable to arbitrary context lengths. Our extensive experiments with an open-weight large language model (LLM) reveal a pronounced gap between high- and low-resource languages, particularly for tasks requiring the model to aggregate multiple facts or predict the absence of information. We also find that, in multilingual settings, LLMs effectively utilize less than 30% of their claimed context length. Although off-the-shelf Retrieval Augmented Generation helps alleviate this to a certain extent, it does not solve the long-context problem. We open-source MLRBench to enable future research in improved evaluation and training of multilingual LLMs.

[Arxiv](https://arxiv.org/abs/2504.12845)