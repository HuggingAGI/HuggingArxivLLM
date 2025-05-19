# # 摘要
提升大型语言模型的事实准确性，扩展推理能力是关键。

发布时间：2025年05月16日

`LLM应用` `问答系统` `知识图谱`

> Scaling Reasoning can Improve Factuality in Large Language Models

# 摘要

> 最近关于大型语言模型（LLM）推理能力的研究表明，通过在推理过程中利用较长的思考过程和额外的计算资源，模型性能得到了显著提升，尤其是在涉及数学推理的任务中（Muennighoff et al., 2025）。然而，更长的推理链是否能从根本上提高事实准确性，尤其是在数学以外的领域，这一点尚不明确。在本研究中，我们深入探讨了复杂开放领域问答（QA）场景下LLM的推理能力。我们从先进的大规模推理模型（QwQ-32B 和 DeepSeek-R1-671B）中提取推理轨迹，并对从较小的指令微调模型到基于Qwen2.5的较大架构等多种模型进行了微调。为了丰富推理轨迹，我们将知识图谱中的事实信息以路径形式引入其中。我们的实验设置包括四种基线方法和六种不同的指令微调模型，这些模型在一个包含六个数据集的基准上进行了评估，涵盖超过22,600个问题。总体而言，我们进行了168次实验，并分析了约170万条推理轨迹。我们的研究表明，在单次运行中，较小的推理模型在事实准确性上比原始指令微调版本有了显著提升。此外，我们的分析表明，增加测试时计算和令牌预算，事实准确性一致提高了2-8%，进一步证实了测试时扩展在提高性能和开放领域问答任务中推理准确性方面的有效性。我们公开了所有实验材料，以供进一步研究。

> Recent studies on large language model (LLM) reasoning capabilities have demonstrated promising improvements in model performance by leveraging a lengthy thinking process and additional computational resources during inference, primarily in tasks involving mathematical reasoning (Muennighoff et al., 2025). However, it remains uncertain if longer reasoning chains inherently enhance factual accuracy, particularly beyond mathematical contexts. In this work, we thoroughly examine LLM reasoning within complex open-domain question-answering (QA) scenarios. We initially distill reasoning traces from advanced, large-scale reasoning models (QwQ-32B and DeepSeek-R1-671B), then fine-tune a variety of models ranging from smaller, instruction-tuned variants to larger architectures based on Qwen2.5. To enrich reasoning traces, we introduce factual information from knowledge graphs in the form of paths into our reasoning traces. Our experimental setup includes four baseline approaches and six different instruction-tuned models evaluated across a benchmark of six datasets, encompassing over 22.6K questions. Overall, we carry out 168 experimental runs and analyze approximately 1.7 million reasoning traces. Our findings indicate that, within a single run, smaller reasoning models achieve noticeable improvements in factual accuracy compared to their original instruction-tuned counterparts. Moreover, our analysis demonstrates that adding test-time compute and token budgets factual accuracy consistently improves by 2-8%, further confirming the effectiveness of test-time scaling for enhancing performance and consequently improving reasoning accuracy in open-domain QA tasks. We release all the experimental artifacts for further research.

[Arxiv](https://arxiv.org/abs/2505.11140)