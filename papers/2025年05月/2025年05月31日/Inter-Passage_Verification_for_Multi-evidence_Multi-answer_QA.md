# # 跨段落验证在多证据多答案问答系统中的应用
本研究聚焦于多证据多答案问答系统中的跨段落验证技术，旨在提升问答系统的准确性和可靠性。

发布时间：2025年05月31日

`RAG` `问答系统`

> Inter-Passage Verification for Multi-evidence Multi-answer QA

# 摘要

> 多答案问答系统（QA），即一个问题可能有多个正确答案，为现有的检索增强生成式问答系统带来了重大挑战，因为这些系统难以检索并综合大量相关段落。为了解决这些问题，我们提出了一种新的多答案 QA 框架——**检索增强独立阅读与跨段落验证（RI$^2$VER）**。我们的框架检索大量段落，并分别处理每个段落，生成一个初始的高召回但噪声较大的答案集。然后，我们提出了一种新的跨段落验证流水线，通过（1）验证问题生成，（2）收集额外证据，（3）跨段落综合验证，来验证每个候选答案。在 QAMPARI 和 RoMQA 数据集上的评估表明，我们的框架在各种模型规模下均显著优于现有基线，平均 F1 分数提升了 11.17%。进一步分析表明，我们的跨段落验证流水线使我们的框架特别适合需要多证据综合的问题。

> Multi-answer question answering (QA), where questions can have many valid answers, presents a significant challenge for existing retrieval-augmented generation-based QA systems, as these systems struggle to retrieve and then synthesize a large number of evidence passages. To tackle these challenges, we propose a new multi-answer QA framework -- Retrieval-augmented Independent Reading with Inter-passage Verification (RI$^2$VER). Our framework retrieves a large set of passages and processes each passage individually to generate an initial high-recall but noisy answer set. Then we propose a new inter-passage verification pipeline that validates every candidate answer through (1) Verification Question Generation, (2) Gathering Additional Evidence, and (3) Verification with inter-passage synthesis. Evaluations on the QAMPARI and RoMQA datasets demonstrate that our framework significantly outperforms existing baselines across various model sizes, achieving an average F1 score improvement of 11.17%. Further analysis validates that our inter-passage verification pipeline enables our framework to be particularly beneficial for questions requiring multi-evidence synthesis.

[Arxiv](https://arxiv.org/abs/2506.00425)