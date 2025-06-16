# 可信的医学AI：持续幻觉检测与消除工具 CHECK

发布时间：2025年06月10日

`LLM应用` `人工智能`

> Trustworthy AI for Medicine: Continuous Hallucination Detection and Elimination with CHECK

# 摘要

> 大型语言模型 (LLMs) 在医疗领域展现出巨大潜力，但幻觉现象仍是临床应用的主要障碍。我们提出 CHECK，一个结合结构化临床数据库和基于信息论分类器的持续学习框架，能够检测事实性和推理性幻觉。在 100 个关键临床试验的 1500 个问题上进行评估，CHECK 将 LLama3.3-70B-Instruct 的幻觉率从 31% 降至 0.3%，使开源模型达到当前最优水平。其分类器在医学基准测试中表现出色，实现了 0.95-0.96 的 AUC，包括 MedQA（USMLE）和 HealthBench 现实多轮医疗问答。通过利用幻觉概率引导 GPT-4o 的优化，并审慎增加计算资源，CHECK 将其 USMLE 通过率提高了 5 个百分点，达到 92.1% 的当前最优水平。通过将幻觉控制在临床可接受误差范围内，CHECK 为医疗及其他高风险领域中安全部署 LLM 提供了可扩展的基础。

> Large language models (LLMs) show promise in healthcare, but hallucinations remain a major barrier to clinical use. We present CHECK, a continuous-learning framework that integrates structured clinical databases with a classifier grounded in information theory to detect both factual and reasoning-based hallucinations. Evaluated on 1500 questions from 100 pivotal clinical trials, CHECK reduced LLama3.3-70B-Instruct hallucination rates from 31% to 0.3% - making an open source model state of the art. Its classifier generalized across medical benchmarks, achieving AUCs of 0.95-0.96, including on the MedQA (USMLE) benchmark and HealthBench realistic multi-turn medical questioning. By leveraging hallucination probabilities to guide GPT-4o's refinement and judiciously escalate compute, CHECK boosted its USMLE passing rate by 5 percentage points, achieving a state-of-the-art 92.1%. By suppressing hallucinations below accepted clinical error thresholds, CHECK offers a scalable foundation for safe LLM deployment in medicine and other high-stakes domains.

[Arxiv](https://arxiv.org/abs/2506.11129)