# PG-Agent：由页面图驱动的智能体

发布时间：2025年08月27日

`Agent` `基础理论`

> PG-Agent: An Agent Powered by Page Graph

# 摘要

> 图形用户界面（GUI）智能体兼具重要的商业与社会价值，尤其在先进多模态大型语言模型（MLLMs）的驱动下，其潜力更是令人瞩目。然而现有GUI智能体多依赖跨页面的多步操作序列片段作为先验知识，却忽略了页面间复杂的转换关系，这使得智能体难以深度感知GUI环境，更难以泛化到新场景。为此，我们设计了一套自动化流程，将序列片段转化为页面图——这种图结构能显式建模通过用户动作自然关联的页面关系。为充分发挥页面图的作用，我们引入检索增强生成（RAG）技术，从页面图中高效提取可靠的GUI感知规则；同时提出定制化多智能体框架PG-Agent，通过任务分解策略将这些规则融入其中，使其能轻松应对未见过的新场景。多项基准测试结果表明，即便构建页面图的序列片段有限，PG-Agent依然表现出色，充分验证了其有效性。

> Graphical User Interface (GUI) agents possess significant commercial and social value, and GUI agents powered by advanced multimodal large language models (MLLMs) have demonstrated remarkable potential. Currently, existing GUI agents usually utilize sequential episodes of multi-step operations across pages as the prior GUI knowledge, which fails to capture the complex transition relationship between pages, making it challenging for the agents to deeply perceive the GUI environment and generalize to new scenarios. Therefore, we design an automated pipeline to transform the sequential episodes into page graphs, which explicitly model the graph structure of the pages that are naturally connected by actions. To fully utilize the page graphs, we further introduce Retrieval-Augmented Generation (RAG) technology to effectively retrieve reliable perception guidelines of GUI from them, and a tailored multi-agent framework PG-Agent with task decomposition strategy is proposed to be injected with the guidelines so that it can generalize to unseen scenarios. Extensive experiments on various benchmarks demonstrate the effectiveness of PG-Agent, even with limited episodes for page graph construction.

[Arxiv](https://arxiv.org/abs/2509.03536)