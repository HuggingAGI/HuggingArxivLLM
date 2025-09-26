# Eigen-1：基于监控RAG的自适应多智能体精化——面向科学推理

发布时间：2025年09月25日

`Agent` `基础理论`

> Eigen-1: Adaptive Multi-Agent Refinement with Monitor-Based RAG for Scientific Reasoning

# 摘要

> 大型语言模型（LLMs）近来在科学推理领域进展显著，但仍面临两大瓶颈。其一，显式检索片段推理会产生隐性“工具税”，增加额外的标记与步骤；其二，多智能体流水线常因对所有候选解取平均而削弱优质方案。为此，我们提出一个融合隐性检索与结构化协作的统一框架：核心是基于监控器的检索模块，在标记级别运作，能以最小干扰将外部知识融入推理过程。在此基础上，层次化解优化（HSR）迭代将每个候选解设为锚点，交由同伴修正；而质量感知迭代推理（QAIR）则根据解的质量动态调整优化策略。在“人类终极考试”（HLE）生物/化学黄金数据集上，该框架准确率达48.3%——刷新当前最佳纪录，较最强智能体基线提升13.4个百分点，领先前沿LLM最多18.1个百分点；同时标记用量减少53.5%，智能体步骤缩减43.7%。在SuperGPQA和TRQA数据集上的实验结果进一步验证了其跨领域鲁棒性。错误分析显示，超85%的案例中推理失败与知识缺口并存；多样性分析则揭示了鲜明的二分特征：检索任务得益于解的多样性，推理任务则更依赖共识。这些发现共同表明，隐性增强与结构化优化可有效解决显式工具使用及统一聚合的低效问题。代码地址：https://github.com/tangxiangru/Eigen-1。

> Large language models (LLMs) have recently shown strong progress on scientific reasoning, yet two major bottlenecks remain. First, explicit retrieval fragments reasoning, imposing a hidden "tool tax" of extra tokens and steps. Second, multi-agent pipelines often dilute strong solutions by averaging across all candidates. We address these challenges with a unified framework that combines implicit retrieval and structured collaboration. At its foundation, a Monitor-based retrieval module operates at the token level, integrating external knowledge with minimal disruption to reasoning. On top of this substrate, Hierarchical Solution Refinement (HSR) iteratively designates each candidate as an anchor to be repaired by its peers, while Quality-Aware Iterative Reasoning (QAIR) adapts refinement to solution quality. On Humanity's Last Exam (HLE) Bio/Chem Gold, our framework achieves 48.3\% accuracy -- the highest reported to date, surpassing the strongest agent baseline by 13.4 points and leading frontier LLMs by up to 18.1 points, while simultaneously reducing token usage by 53.5\% and agent steps by 43.7\%. Results on SuperGPQA and TRQA confirm robustness across domains. Error analysis shows that reasoning failures and knowledge gaps co-occur in over 85\% of cases, while diversity analysis reveals a clear dichotomy: retrieval tasks benefit from solution variety, whereas reasoning tasks favor consensus. Together, these findings demonstrate how implicit augmentation and structured refinement overcome the inefficiencies of explicit tool use and uniform aggregation. Code is available at: https://github.com/tangxiangru/Eigen-1.

[Arxiv](https://arxiv.org/abs/2509.21193)