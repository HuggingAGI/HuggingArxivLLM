# 幻觉消除：基于辩论增强的RAG方法

发布时间：2025年05月24日

`RAG` `问答系统`

> Removal of Hallucination on Hallucination: Debate-Augmented RAG

# 摘要

> 检索增强生成（RAG）通过整合外部知识提升了事实准确性，却引入了一个关键问题：错误或有偏见的检索会误导生成，加剧幻觉现象，我们将其称为“幻觉叠加”。为解决这一问题，我们提出了无需训练的 Debate-Augmented RAG（DRAG）框架，将多智能体辩论（MAD）机制融入检索与生成阶段。在检索环节，DRAG 通过正方、反方和裁判之间的结构化辩论优化检索质量，确保事实可靠性。在生成环节，DRAG 引入了信息角色不对称与对抗性辩论，增强了推理稳健性，缓解了事实不一致问题。多任务评估表明，DRAG 提升了检索可靠性，减少了由 RAG 引发的幻觉，并显著增强了整体事实准确性。我们的代码可在 https://github.com/Huenao/Debate-Augmented-RAG 获取。

> Retrieval-Augmented Generation (RAG) enhances factual accuracy by integrating external knowledge, yet it introduces a critical issue: erroneous or biased retrieval can mislead generation, compounding hallucinations, a phenomenon we term Hallucination on Hallucination. To address this, we propose Debate-Augmented RAG (DRAG), a training-free framework that integrates Multi-Agent Debate (MAD) mechanisms into both retrieval and generation stages. In retrieval, DRAG employs structured debates among proponents, opponents, and judges to refine retrieval quality and ensure factual reliability. In generation, DRAG introduces asymmetric information roles and adversarial debates, enhancing reasoning robustness and mitigating factual inconsistencies. Evaluations across multiple tasks demonstrate that DRAG improves retrieval reliability, reduces RAG-induced hallucinations, and significantly enhances overall factual accuracy. Our code is available at https://github.com/Huenao/Debate-Augmented-RAG.

[Arxiv](https://arxiv.org/abs/2505.18581)