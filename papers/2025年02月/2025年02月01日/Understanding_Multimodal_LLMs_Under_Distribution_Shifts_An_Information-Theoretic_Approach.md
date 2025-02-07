# 分布变化下的多模态LLMs理解：信息论视角

发布时间：2025年02月01日

`LLM理论

理由：这篇论文提出了一个理论框架，用于量化多模态大型语言模型（MLLMs）在分布转移下的最大风险。论文的核心是引入有效互信息（EMI）这一原则性指标，并推导了分布内与分布外数据间EMI差异的上界。这些内容属于对大型语言模型的理论分析和形式化框架的构建，因此应归类为LLM理论。` `人工智能` `风险评估`

> Understanding Multimodal LLMs Under Distribution Shifts: An Information-Theoretic Approach

# 摘要

> 多模态大型语言模型（MLLMs）虽然潜力巨大，但在分布转移时表现欠佳，即评估数据与指令调优分布不一致。尽管已有研究提供了实证评估，但我们认为有必要建立一个形式化框架来刻画和量化MLLMs的风险，以确保其在现实世界中的安全可靠应用。基于信息论视角，我们提出了首个理论框架，能够量化MLLMs在分布转移下的最大风险。该框架的核心是引入有效互信息（EMI），这一原则性指标用于衡量输入查询与模型响应之间的相关性。我们推导了分布内（ID）与分布外（OOD）数据间EMI差异的上界，并将其与视觉和文本分布差异关联起来。在涵盖61个转移场景的真实基准数据集上的大量实验，验证了我们的理论见解。

> Multimodal large language models (MLLMs) have shown promising capabilities but struggle under distribution shifts, where evaluation data differ from instruction tuning distributions. Although previous works have provided empirical evaluations, we argue that establishing a formal framework that can characterize and quantify the risk of MLLMs is necessary to ensure the safe and reliable application of MLLMs in the real world. By taking an information-theoretic perspective, we propose the first theoretical framework that enables the quantification of the maximum risk of MLLMs under distribution shifts. Central to our framework is the introduction of Effective Mutual Information (EMI), a principled metric that quantifies the relevance between input queries and model responses. We derive an upper bound for the EMI difference between in-distribution (ID) and out-of-distribution (OOD) data, connecting it to visual and textual distributional discrepancies. Extensive experiments on real benchmark datasets, spanning 61 shift scenarios empirically validate our theoretical insights.

[Arxiv](https://arxiv.org/abs/2502.00577)