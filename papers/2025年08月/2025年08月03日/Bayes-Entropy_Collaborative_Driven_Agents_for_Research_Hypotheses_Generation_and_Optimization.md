# 基于贝叶斯-熵协同驱动的智能体实现研究假设的生成与优化

发布时间：2025年08月03日

`Agent

理由：这篇论文提出了一个名为HypoAgents的多智能体协作框架，用于自动生成科学假设。框架中结合了贝叶斯推理、信息熵驱动的搜索机制以及RAG技术，模拟科学家的思维过程。虽然RAG技术是其中的一部分，但整体框架更侧重于多智能体的协作和推理，因此归类为Agent。` `科学研究` `人工智能`

> Bayes-Entropy Collaborative Driven Agents for Research Hypotheses Generation and Optimization

# 摘要

> 面对科学知识的爆炸式增长，如何自动生成兼具新颖性、可行性和研究价值的科学假设成为关键挑战。现有基于大型语言模型的方法未能有效建模假设内在特性，也缺乏闭环反馈机制以支持优化。本研究提出了一种名为HypoAgents的多智能体协作框架，首次将贝叶斯推理与信息熵驱动的搜索机制相结合，贯穿假设生成、证据验证和假设精炼三大阶段，构建了一个模拟科学家思维过程的迭代闭环系统。具体而言，该框架首先通过多样性采样生成初始假设集，并基于综合评估新颖性、相关性和可行性的N-R-F评分建立先验信念。随后，借助检索增强生成（RAG）技术收集外部文献证据，并运用贝叶斯定理更新假设的后验概率。最后，通过信息熵公式 $H = - \sum {{p_i}\log {p_i}}$ 识别高不确定性假设，并主动进行精炼，引导假设集的迭代优化，以提升整体质量和置信度。实验结果显示，在ICLR 2025大会的100个现实研究问题数据集上，经过12轮优化迭代，生成假设的平均ELO评分提升了116.3，超越真实论文摘要基准17.8分，同时框架的整体不确定性（以香农熵衡量）显著降低了0.92。本研究为自动化科学研究提供了一个透明的概率推理框架，显著提升了机器生成研究假设的质量和可靠性。

> The exponential growth of scientific knowledge has made the automated generation of scientific hypotheses that combine novelty, feasibility, and research value a core challenge. Existing methods based on large language models fail to systematically model the inherent in hypotheses or incorporate the closed-loop feedback mechanisms crucial for refinement. This paper proposes a multi-agent collaborative framework called HypoAgents, which for the first time integrates Bayesian reasoning with an information entropy-driven search mechanism across three stages-hypotheses generation, evidence validation, and hypotheses Refinement-to construct an iterative closed-loop simulating scientists' cognitive processes. Specifically, the framework first generates an initial set of hypotheses through diversity sampling and establishes prior beliefs based on a composite novelty-relevance-feasibility (N-R-F) score. It then employs etrieval-augmented generation (RAG) to gather external literature evidence, updating the posterior probabilities of hypotheses using Bayes' theorem. Finally, it identifies high-uncertainty hypotheses using information entropy $H = - \sum {{p_i}\log {p_i}}$ and actively refines them, guiding the iterative optimization of the hypothesis set toward higher quality and confidence. Experimental results on the ICLR 2025 conference real-world research question dataset (100 research questions) show that after 12 optimization iterations, the average ELO score of generated hypotheses improves by 116.3, surpassing the benchmark of real paper abstracts by 17.8, while the framework's overall uncertainty, as measured by Shannon entropy, decreases significantly by 0.92. This study presents an interpretable probabilistic reasoning framework for automated scientific discovery, substantially improving the quality and reliability of machine-generated research hypotheses.

[Arxiv](https://arxiv.org/abs/2508.01746)