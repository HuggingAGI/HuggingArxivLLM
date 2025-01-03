# FIRE: 迭代检索与验证的事实核查

发布时间：2024年10月17日

`Agent

理由：这篇论文提出了一个基于代理的迭代框架FIRE，用于长文本的事实核查。该框架通过代理机制将证据检索与声明验证结合起来，并根据置信度决定是否继续搜索或给出最终答案。这种基于代理的框架设计属于Agent的范畴，因为它涉及到智能代理的决策和迭代推理过程。` `事实核查` `信息检索`

> FIRE: Fact-checking with Iterative Retrieval and Verification

# 摘要

> # 摘要
长文本的事实核查颇具挑战，因此通常将其拆解为多个原子声明进行核查。传统方法通过检索固定数量的证据后进行验证，但这种方法成本效益不高，未能充分利用验证模型的内部知识，也无法模拟人类搜索中的迭代推理。为此，我们提出了FIRE，一种基于代理的迭代框架，将证据检索与声明验证无缝结合。FIRE通过统一机制，根据当前判断的置信度，决定是给出最终答案还是生成新的搜索查询。与现有框架相比，FIRE在性能略有提升的同时，将LLM成本平均降低7.6倍，搜索成本降低16.5倍。这些结果表明，FIRE在大规模事实核查中具有广阔的应用前景。代码已开源：https://github.com/mbzuai-nlp/fire.git。

> Fact-checking long-form text is challenging, and it is therefore common practice to break it down into multiple atomic claims. The typical approach to fact-checking these atomic claims involves retrieving a fixed number of pieces of evidence, followed by a verification step. However, this method is usually not cost-effective, as it underutilizes the verification model's internal knowledge of the claim and fails to replicate the iterative reasoning process in human search strategies. To address these limitations, we propose FIRE, a novel agent-based framework that integrates evidence retrieval and claim verification in an iterative manner. Specifically, FIRE employs a unified mechanism to decide whether to provide a final answer or generate a subsequent search query, based on its confidence in the current judgment. We compare FIRE with other strong fact-checking frameworks and find that it achieves slightly better performance while reducing large language model (LLM) costs by an average of 7.6 times and search costs by 16.5 times. These results indicate that FIRE holds promise for application in large-scale fact-checking operations. Our code is available at https://github.com/mbzuai-nlp/fire.git.

[Arxiv](https://arxiv.org/abs/2411.00784)