# 评估多国价值观对齐的大型语言模型

发布时间：2025年04月17日

`LLM应用` `国家价值观`

> Benchmarking Multi-National Value Alignment for Large Language Models

# 摘要

> 大型语言模型（LLMs）是否与您所在国家的价值观存在冲突？答案是肯定的，但现有研究主要关注伦理审查，忽视了国家价值观的多样性，这些价值观涉及更广泛的政策、法律和道德因素。此外，依赖手动设计问卷的光谱测试基准不具备良好的扩展性。为解决这些问题，我们推出了NaVAB，一个全面的基准测试工具，用于评估LLMs与中国、美国、英国、法国和德国五个主要国家的价值观对齐情况。NaVAB通过国家价值观提取管道高效构建评估数据集。具体来说，我们提出了一种带有指令标签的建模流程来处理原始数据源，一个筛选流程来过滤价值观相关话题，以及一个带有冲突减少机制的生成流程来过滤无冲突的价值观。我们在多个国家的多种LLMs上进行了广泛实验，结果提供了识别对齐不当场景的见解。此外，NaVAB可与对齐技术结合，通过将LLMs的价值观与目标国家对齐，有效减少价值观相关问题。

> Do Large Language Models (LLMs) hold positions that conflict with your country's values? Occasionally they do! However, existing works primarily focus on ethical reviews, failing to capture the diversity of national values, which encompass broader policy, legal, and moral considerations. Furthermore, current benchmarks that rely on spectrum tests using manually designed questionnaires are not easily scalable.
  To address these limitations, we introduce NaVAB, a comprehensive benchmark to evaluate the alignment of LLMs with the values of five major nations: China, the United States, the United Kingdom, France, and Germany. NaVAB implements a national value extraction pipeline to efficiently construct value assessment datasets. Specifically, we propose a modeling procedure with instruction tagging to process raw data sources, a screening process to filter value-related topics and a generation process with a Conflict Reduction mechanism to filter non-conflicting values.We conduct extensive experiments on various LLMs across countries, and the results provide insights into assisting in the identification of misaligned scenarios. Moreover, we demonstrate that NaVAB can be combined with alignment techniques to effectively reduce value concerns by aligning LLMs' values with the target country.

[Arxiv](https://arxiv.org/abs/2504.12911)