# # 基于课程指导的分层缩放策略，优化语言模型预训练效果

发布时间：2025年06月12日

`LLM理论

摘要讨论了预训练大型语言模型的训练效率，并提出了一种新的训练框架，属于模型训练策略和理论研究的范畴。因此，这篇论文被归类到LLM理论。` `问答系统`

> Curriculum-Guided Layer Scaling for Language Model Pretraining

# 摘要

> 随着预训练大型语言模型的成本日益攀升，提升训练效率始终是研究热点。受人类认知发展启发，我们提出了一种名为基于课程的层扩展（CGLS）的高效预训练框架，通过逐步叠加层的方式，将数据难度的提升与模型增长同步。在1亿参数规模下，采用从合成短篇故事到通用网络数据的课程过渡策略，CGLS在问答基准PIQA和ARC上显著优于传统方法。进一步扩展至12亿参数规模，我们利用DistilBERT基分类器对DataComp-LM语料库进行分层，并从通用文本逐步过渡到高度技术化或专业化的领域内容。实验结果表明，逐步增加模型深度与样本难度的策略，能够有效提升模型在多种下游任务中的泛化和零样本性能。总体而言，CGLS不仅解锁了逐步叠加的潜力，更为知识密集型和推理任务提供了一种简单而有效的优化策略。

> As the cost of pretraining large language models grows, there is continued interest in strategies to improve learning efficiency during this core training stage. Motivated by cognitive development, where humans gradually build knowledge as their brains mature, we propose Curriculum-Guided Layer Scaling (CGLS), a framework for compute-efficient pretraining that synchronizes increasing data difficulty with model growth through progressive layer stacking (i.e. gradually adding layers during training). At the 100M parameter scale, using a curriculum transitioning from synthetic short stories to general web data, CGLS outperforms baseline methods on the question-answering benchmarks PIQA and ARC. Pretraining at the 1.2B scale, we stratify the DataComp-LM corpus with a DistilBERT-based classifier and progress from general text to highly technical or specialized content. Our results show that progressively increasing model depth alongside sample difficulty leads to better generalization and zero-shot performance on various downstream benchmarks. Altogether, our findings demonstrate that CGLS unlocks the potential of progressive stacking, offering a simple yet effective strategy for improving generalization on knowledge-intensive and reasoning tasks.

[Arxiv](https://arxiv.org/abs/2506.11389)