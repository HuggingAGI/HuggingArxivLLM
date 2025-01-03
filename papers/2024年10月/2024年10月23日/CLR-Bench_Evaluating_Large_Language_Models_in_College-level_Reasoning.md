# CLR-Bench: 评估大型语言模型在大学水平推理中的表现

发布时间：2024年10月23日

`LLM理论

理由：这篇论文主要关注的是对大型语言模型（LLMs）在复杂推理任务中的表现进行评估，并提出了新的评估指标（Q→A和Q→AR）。论文的核心在于探讨LLMs的推理能力，而不是具体的应用场景或技术实现。因此，它更符合“LLM理论”这一分类，因为它涉及对LLMs能力的理论分析和评估。` `人工智能`

> CLR-Bench: Evaluating Large Language Models in College-level Reasoning

# 摘要

> 大型语言模型（LLMs）在各类语言理解任务中表现卓越。尽管已有新兴基准用于评估LLMs在数学、计算机科学等领域的表现，但这些基准仅通过多项选择题的最终预测准确率来衡量。然而，仅凭选择的答案来验证LLMs的本质理解仍显不足。为此，我们推出了CLR-Bench，旨在全面评估LLMs在复杂大学水平推理中的表现。具体而言，（i）我们聚焦于计算机科学和人工智能领域的16个高难度大学学科，数据集包含5种题型，每题均附有专家详细解释。（ii）为量化LLMs的推理能力，我们引入两个新颖指标：Q$ightarrow$A用于衡量直接答案预测的表现，Q$ightarrow$AR则同时评估回答问题与提供理由的联合能力。我们在1,018个学科特定问题上对40个LLMs进行了广泛实验。结果显示，即使是表现最佳的闭源LLM——GPT-4 turbo，也倾向于“猜测”大学水平的答案，其准确率从Q$ightarrow$A的63.31%骤降至Q$ightarrow$AR的39.00%，表明其推理能力仍有待提升。

> Large language models (LLMs) have demonstrated their remarkable performance across various language understanding tasks. While emerging benchmarks have been proposed to evaluate LLMs in various domains such as mathematics and computer science, they merely measure the accuracy in terms of the final prediction on multi-choice questions. However, it remains insufficient to verify the essential understanding of LLMs given a chosen choice. To fill this gap, we present CLR-Bench to comprehensively evaluate the LLMs in complex college-level reasoning. Specifically, (i) we prioritize 16 challenging college disciplines in computer science and artificial intelligence. The dataset contains 5 types of questions, while each question is associated with detailed explanations from experts. (ii) To quantify a fair evaluation of LLMs' reasoning ability, we formalize the criteria with two novel metrics. Q$\rightarrow$A is utilized to measure the performance of direct answer prediction, and Q$\rightarrow$AR effectively considers the joint ability to answer the question and provide rationale simultaneously. Extensive experiments are conducted with 40 LLMs over 1,018 discipline-specific questions. The results demonstrate the key insights that LLMs, even the best closed-source LLM, i.e., GPT-4 turbo, tend to `guess' the college-level answers. It shows a dramatic decrease in accuracy from 63.31% Q$\rightarrow$A to 39.00% Q$\rightarrow$AR, indicating an unsatisfactory reasoning ability.

[Arxiv](https://arxiv.org/abs/2410.17558)