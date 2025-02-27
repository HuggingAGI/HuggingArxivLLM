# MA-GTS：解决实际应用中复杂图问题的多智能体框架

发布时间：2025年02月25日

`Agent

摘要中提到的MA-GTS是一个多智能体协作框架，专注于通过多智能体系统解决图论问题，因此归类到Agent类别。` `交通优化`

> MA-GTS: A Multi-Agent Framework for Solving Complex Graph Problems in Real-World Applications

# 摘要

> 图论问题广泛存在于物流、通信网络和交通优化等实际场景中。这些问题通常复杂、噪声干扰和不规则，给传统算法带来了巨大挑战。大型语言模型（LLMs）虽然提供了潜在的解决方案，但面临着准确性有限和输入长度限制的问题。为了解决这些问题，我们提出了MA-GTS（多智能体图论求解器），一个通过多智能体协作分解复杂问题的框架。MA-GTS能够将隐式的基于文本的图数据转化为清晰的结构化图表示，并根据问题约束和图结构规模动态选择最合适的算法。这种方法不仅确保了高效的解决过程，还使得推理路径更加可解释。我们通过自建的基于现实启发的图论数据集G-REAL对MA-GTS进行了验证。实验结果表明，与现有最优方法相比，MA-GTS在效率、准确性和可扩展性方面均表现更优，且在多个基准测试中取得了优异成绩（G-REAL 94.2%，GraCoRe 96.9%，NLGraph 98.4%）。MA-GTS已在GitHub上开源，欢迎访问https://github.com/ZIKEYUAN/MA-GTS.git获取更多信息。

> Graph-theoretic problems arise in real-world applications like logistics, communication networks, and traffic optimization. These problems are often complex, noisy, and irregular, posing challenges for traditional algorithms. Large language models (LLMs) offer potential solutions but face challenges, including limited accuracy and input length constraints. To address these challenges, we propose MA-GTS (Multi-Agent Graph Theory Solver), a multi-agent framework that decomposes these complex problems through agent collaboration. MA-GTS maps the implicitly expressed text-based graph data into clear, structured graph representations and dynamically selects the most suitable algorithm based on problem constraints and graph structure scale. This approach ensures that the solution process remains efficient and the resulting reasoning path is interpretable. We validate MA-GTS using the G-REAL dataset, a real-world-inspired graph theory dataset we created. Experimental results show that MA-GTS outperforms state-of-the-art approaches in terms of efficiency, accuracy, and scalability, with strong results across multiple benchmarks (G-REAL 94.2%, GraCoRe 96.9%, NLGraph 98.4%).MA-GTS is open-sourced at https://github.com/ZIKEYUAN/MA-GTS.git.

[Arxiv](https://arxiv.org/abs/2502.18540)