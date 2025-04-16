# LazyReview：一个发现自然语言处理领域同行评审中思维惰性的数据集

发布时间：2025年04月15日

`LLM应用` `学术出版` `同行评审`

> LazyReview A Dataset for Uncovering Lazy Thinking in NLP Peer Reviews

# 摘要

> 同行评审是科学出版物质量控制的基石。随着工作量的增加，评审过程中“快速”启发式方法的滥用——即惰性思维——已成为影响评审质量的顽固问题。自动化检测这些启发式方法可望改进同行评审流程，但目前NLP研究在这一领域仍显不足，且缺乏支持检测工具开发的现实数据集。

本研究推出LazyReview——一个标注了细粒度惰性思维类别的同行评审句子数据集。分析表明，大型语言模型（LLMs）在零-shot设置下难以准确识别这些惰性思维实例。然而，通过基于我们的数据集进行指令微调，性能可显著提升10-20个点，凸显了高质量训练数据的关键作用。

进一步的受控实验表明，获得惰性思维反馈修改的评审意见比未经此类反馈的评审更具全面性和可操作性。我们即将发布LazyReview数据集及相关增强指南，为社区培训初级评审员提供有力支持。（代码可在此处获取：https://github.com/UKPLab/arxiv2025-lazy-review）
    

> Peer review is a cornerstone of quality control in scientific publishing. With the increasing workload, the unintended use of `quick' heuristics, referred to as lazy thinking, has emerged as a recurring issue compromising review quality. Automated methods to detect such heuristics can help improve the peer-reviewing process. However, there is limited NLP research on this issue, and no real-world dataset exists to support the development of detection tools. This work introduces LazyReview, a dataset of peer-review sentences annotated with fine-grained lazy thinking categories. Our analysis reveals that Large Language Models (LLMs) struggle to detect these instances in a zero-shot setting. However, instruction-based fine-tuning on our dataset significantly boosts performance by 10-20 performance points, highlighting the importance of high-quality training data. Furthermore, a controlled experiment demonstrates that reviews revised with lazy thinking feedback are more comprehensive and actionable than those written without such feedback. We will release our dataset and the enhanced guidelines that can be used to train junior reviewers in the community. (Code available here: https://github.com/UKPLab/arxiv2025-lazy-review)

[Arxiv](https://arxiv.org/abs/2504.11042)