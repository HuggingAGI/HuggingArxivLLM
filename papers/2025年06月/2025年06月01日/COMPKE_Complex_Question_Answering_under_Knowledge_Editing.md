# # COMPKE: 复杂知识编辑下的问答任务
COMPKE 是一个专注于研究在知识编辑场景下处理复杂问答任务的研究方向。

发布时间：2025年06月01日

`LLM应用` `知识编辑` `问答系统`

> COMPKE: Complex Question Answering under Knowledge Editing

# 摘要

> 知识编辑作为一种高效修改大型语言模型知识的方法，已吸引了广泛关注。当前基准测试主要通过多跳问答任务来评估新注入或更新的知识。然而，我们认为这些基准测试未能有效评估模型在现实场景中的知识应用能力，特别是在需要复杂推理（如涉及一对多关系或多步逻辑交集）的情况下。为填补这一空白，我们引入了新的基准测试——COMPKE：知识编辑下的复杂问答，包含11,924个反映现实情况的复杂问题。我们对四种知识编辑方法在COMPKE上的表现进行了全面评估，发现它们在不同模型上的有效性差异显著。例如，MeLLo在GPT-4O-MINI上的准确率为39.47，但在QWEN2.5-3B上则大幅下降至3.83。我们进一步从方法论和模型特定的角度探讨了这些差异的潜在原因。数据集可在https://github.com/kzjkzj666/CompKE获取。

> Knowledge Editing, which efficiently modifies the knowledge in large language models, has gathered great attention. Current benchmarks primarily use multi-hop question answering to assess and analyze newly injected or updated knowledge. However, we argue that these benchmarks fail to effectively evaluate how well the updated models apply this knowledge in real-life scenarios, particularly when questions require complex reasoning, involving one-to-many relationships or multi-step logical intersections. To fill in this gap, we introduce a new benchmark, COMPKE: Complex Question Answering under Knowledge Editing, which includes 11,924 complex questions that reflect real-life situations. We conduct an extensive evaluation of four knowledge editing methods on COMPKE, revealing that their effectiveness varies notably across different models. For instance, MeLLo attains an accuracy of 39.47 on GPT-4O-MINI, but this drops sharply to 3.83 on QWEN2.5-3B. We further investigate the underlying causes of these disparities from both methodological and model-specific perspectives. The datasets are available at https://github.com/kzjkzj666/CompKE.

[Arxiv](https://arxiv.org/abs/2506.00829)