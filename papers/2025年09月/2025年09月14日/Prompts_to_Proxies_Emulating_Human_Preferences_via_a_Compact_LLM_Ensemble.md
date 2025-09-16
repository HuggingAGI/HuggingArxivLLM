# 提示词到代理：借助紧凑LLM集成模拟人类偏好

发布时间：2025年09月14日

`Agent` `基础理论`

> Prompts to Proxies: Emulating Human Preferences via a Compact LLM Ensemble

# 摘要

> 大型语言模型（LLMs）在各类任务中模拟人类反应的能力已展露锋芒。本文提出一种全新对齐框架，将LLMs作为人类调查受访者的“代理替身”，为社会科学领域的两大棘手难题提供了经济高效且可控的解决思路：调查部署成本高企与受访者数据人口统计失衡加剧。受显示偏好理论启发，我们将对齐问题拆解为两个阶段：一是构建名为“禀赋”的多样化代理角色，模拟真实可信的受访者画像；二是基于观测数据筛选代表性子集，以此逼近真实人群分布。为落地这一范式，我们研发了P2P系统——通过结构化提示工程、熵值驱动采样与回归模型筛选，引导LLM代理呈现具备代表性的行为特征。与过度依赖个性化的方案不同，我们的对齐方法摆脱了人口统计信息束缚，仅依托汇总调查结果，兼具更强的泛化能力与简洁性。该框架不仅能提升社会科学研究的数据效率，更可作为探索多元对齐操作化的试验场。在真实意见调查数据集上的验证表明，我们对齐后的代理群体不仅能高保真复现汇总反应模式，即便缺乏人口统计条件约束，也能展现出丰富的反应多样性。

> Large language models (LLMs) have demonstrated promise in emulating human-like responses across a wide range of tasks. In this paper, we propose a novel alignment framework that treats LLMs as agent proxies for human survey respondents, affording a cost-effective and steerable solution to two pressing challenges in the social sciences: the rising cost of survey deployment and the growing demographic imbalance in survey response data. Drawing inspiration from the theory of revealed preference, we formulate alignment as a two-stage problem: constructing diverse agent personas called endowments that simulate plausible respondent profiles, and selecting a representative subset to approximate a ground-truth population based on observed data. To implement the paradigm, we introduce P2P, a system that steers LLM agents toward representative behavioral patterns using structured prompt engineering, entropy-based sampling, and regression-based selection. Unlike personalization-heavy approaches, our alignment approach is demographic-agnostic and relies only on aggregate survey results, offering better generalizability and parsimony. Beyond improving data efficiency in social science research, our framework offers a testbed for studying the operationalization of pluralistic alignment. We demonstrate the efficacy of our approach on real-world opinion survey datasets, showing that our aligned agent populations can reproduce aggregate response patterns with high fidelity and exhibit substantial response diversity, even without demographic conditioning.

[Arxiv](https://arxiv.org/abs/2509.11311)