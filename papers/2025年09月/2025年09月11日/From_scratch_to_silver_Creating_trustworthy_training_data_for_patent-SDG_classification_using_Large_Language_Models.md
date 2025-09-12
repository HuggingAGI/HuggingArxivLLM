# 从无到有到精品：借助大型语言模型构建专利-SDG分类的可信训练数据

发布时间：2025年09月11日

`LLM应用` `能源与环保`

> From scratch to silver: Creating trustworthy training data for patent-SDG classification using Large Language Models

# 摘要

> 将专利按与联合国可持续发展目标（SDGs）的相关性分类，对追踪创新应对全球挑战的情况至关重要。但由于缺乏大规模标注数据集，监督学习的应用受到限制。现有方法（如关键词搜索、迁移学习和基于引用的启发式方法）在可扩展性和通用性方面存在不足。本文将专利与SDG的分类问题转化为弱监督任务，利用专利对SDG标签科学出版物的引用（非专利文献引用）作为含噪初始信号。为解决这一信号的稀疏性和噪声问题，我们构建了复合标签函数（LF），借助大型语言模型（LLMs）从专利和SDG论文中提取结构化概念——即基于专利本体的功能、解决方案与应用。通过基于排序的检索方法计算并融合跨域相似度分数。我们通过自定义的仅正例损失对LF进行校准，该损失与已知的NPL-SDG链接保持一致，同时不限制新SDG关联的发现。最终得到一个银标准的软多标签数据集，实现了专利与SDGs的映射，进而能够训练高效的多标签回归模型。我们通过两种互补策略验证所提方法：（1）基于留出的NPL标签进行内部验证，结果表明我们的方法优于多个基线（包括基于Transformer的模型和零样本LLM）；（2）利用专利引用、共同发明人及共同申请人网络的模块性进行外部验证，发现我们的标签比传统技术分类具有更强的主题、认知和组织一致性。这些结果表明，弱监督与语义对齐能够大规模提升SDG分类的准确性。

> Classifying patents by their relevance to the UN Sustainable Development Goals (SDGs) is crucial for tracking how innovation addresses global challenges. However, the absence of a large, labeled dataset limits the use of supervised learning. Existing methods, such as keyword searches, transfer learning, and citation-based heuristics, lack scalability and generalizability. This paper frames patent-to-SDG classification as a weak supervision problem, using citations from patents to SDG-tagged scientific publications (NPL citations) as a noisy initial signal. To address its sparsity and noise, we develop a composite labeling function (LF) that uses large language models (LLMs) to extract structured concepts, namely functions, solutions, and applications, from patents and SDG papers based on a patent ontology. Cross-domain similarity scores are computed and combined using a rank-based retrieval approach. The LF is calibrated via a custom positive-only loss that aligns with known NPL-SDG links without penalizing discovery of new SDG associations. The result is a silver-standard, soft multi-label dataset mapping patents to SDGs, enabling the training of effective multi-label regression models. We validate our approach through two complementary strategies: (1) internal validation against held-out NPL-based labels, where our method outperforms several baselines including transformer-based models, and zero-shot LLM; and (2) external validation using network modularity in patent citation, co-inventor, and co-applicant graphs, where our labels reveal greater thematic, cognitive, and organizational coherence than traditional technological classifications. These results show that weak supervision and semantic alignment can enhance SDG classification at scale.

[Arxiv](https://arxiv.org/abs/2509.09303)