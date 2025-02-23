# CER：增强大型语言模型推理的置信度

发布时间：2025年02月20日

`LLM理论` `人工智能`

> CER: Confidence Enhanced Reasoning in LLMs

# 摘要

> 在复杂推理任务中，尤其是涉及精准数学计算和知识密集型开放领域生成的场景下，确保大型语言模型（LLMs）的可靠性仍是一个重大挑战。本研究提出了一种不确定性感知的框架，通过系统性地在关键决策点整合模型信心，显著提升LLM的回答准确性。我们创新性地鼓励LLMs进行多步推理，并对中间答案（如数学推理中的数值结果和开放领域生成中的专有名词）进行信心量化。基于这些关键中间步骤的信心，我们评估了每个推理链的整体信心。最终，我们采用一种反映每个生成内容可靠性的聚合方法（而非让每个生成链在多数投票中平等贡献的自洽性方法），聚合生成响应路径的答案。我们使用四个LLMs在五个数据集（三个数学数据集和两个开放领域数据集）上进行了广泛实验。结果一致验证了我们新颖的信心聚合方法的有效性，在数学和开放领域生成任务中，分别比基线方法提高了7.4%和5.8%的准确性。代码可在https://github.com/Aquasar11/CER公开获取。

> Ensuring the reliability of Large Language Models (LLMs) in complex reasoning tasks remains a formidable challenge, particularly in scenarios that demand precise mathematical calculations and knowledge-intensive open-domain generation. In this work, we introduce an uncertainty-aware framework designed to enhance the accuracy of LLM responses by systematically incorporating model confidence at critical decision points. We propose an approach that encourages multi-step reasoning in LLMs and quantify the confidence of intermediate answers such as numerical results in mathematical reasoning and proper nouns in open-domain generation. Then, the overall confidence of each reasoning chain is evaluated based on confidence of these critical intermediate steps. Finally, we aggregate the answer of generated response paths in a way that reflects the reliability of each generated content (as opposed to self-consistency in which each generated chain contributes equally to majority voting). We conducted extensive experiments in five datasets, three mathematical datasets and two open-domain datasets, using four LLMs. The results consistently validate the effectiveness of our novel confidence aggregation method, leading to an accuracy improvement of up to 7.4% and 5.8% over baseline approaches in math and open-domain generation tasks, respectively. Code is publicly available at https://github.com/ Aquasar11/CER.

[Arxiv](https://arxiv.org/abs/2502.14634)