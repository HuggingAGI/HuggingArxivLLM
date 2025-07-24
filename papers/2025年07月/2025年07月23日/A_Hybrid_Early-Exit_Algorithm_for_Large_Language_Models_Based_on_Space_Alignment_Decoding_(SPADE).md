# 基于空间对齐解码（SPADE）的大型语言模型混合早期退出算法

发布时间：2025年07月23日

`LLM应用` `人工智能`

> A Hybrid Early-Exit Algorithm for Large Language Models Based on Space Alignment Decoding (SPADE)

# 摘要

> 大型语言模型因其深度结构而计算开销巨大。先前研究表明，中间层包含生成准确答案所需的信息，由此催生了提前退出算法，通过在较早的层终止计算来降低推理成本。然而，这些方法常因中间层与输出层表示之间的不匹配导致解码不准确，进而影响性能。为了解决这些问题，我们提出了一种名为SPADE（空间对齐解码）的新解码方法，通过传播仅包含起始标记和答案标记的最小化序列，将中间层表示与输出层对齐。我们进一步通过训练SPADE的线性近似模型优化了提前退出决策过程，该模型基于熵计算置信度指标。结合这两者，我们创建了一种混合提前退出算法，通过监控置信水平在中间层停止推理，同时利用SPADE生成高质量输出。这种方法显著降低了推理成本，同时保持了准确性，为在实际应用中部署大型语言模型提供了一种可扩展且高效的解决方案。

> Large language models are computationally expensive due to their deep structures. Prior research has shown that intermediate layers contain sufficient information to generate accurate answers, leading to the development of early-exit algorithms that reduce inference costs by terminating computation at earlier layers. However, these methods often suffer from poor performance due to misalignment between intermediate and output layer representations that lead to decoding inaccuracy. To address these challenges, we propose SPADE (SPace Alignment DEcoding), a novel decoding method that aligns intermediate layer representations with the output layer by propagating a minimally reduced sequence consisting of only the start token and the answer token. We further optimize the early-exit decision-making process by training a linear approximation of SPADE that computes entropy-based confidence metrics. Putting them together, we create a hybrid early-exit algorithm that monitors confidence levels and stops inference at intermediate layers while using SPADE to generate high-quality outputs. This approach significantly reduces inference costs without compromising accuracy, offering a scalable and efficient solution for deploying large language models in real-world applications.

[Arxiv](https://arxiv.org/abs/2507.17618)