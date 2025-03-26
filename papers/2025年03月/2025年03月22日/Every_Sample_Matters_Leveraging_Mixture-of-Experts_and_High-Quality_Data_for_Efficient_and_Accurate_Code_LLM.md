# # 每个样本都至关重要：融合专家网络与高质量数据，助力打造高效精准的代码大模型

发布时间：2025年03月22日

`LLM应用` `软件开发` `代码生成`

> Every Sample Matters: Leveraging Mixture-of-Experts and High-Quality Data for Efficient and Accurate Code LLM

# 摘要

> 代码大型语言模型（LLMs）的最新进展在代码生成与理解领域展现出了卓越的能力。然而，构建一个兼具全面性能与极致效率的代码LLM仍具挑战性。开源社区中已有多项尝试致力于突破性能与效率的权衡，如Qwen Coder系列和DeepSeek Coder系列。本文介绍的Ling-Coder-Lite是又一创新尝试。我们采用高效专家混合（MoE）架构，并结合一系列高质量数据整理方法（尤其是基于程序分析的技术），打造了一个高效且强大的代码LLM。在12个代表性编码基准测试中，Ling-Coder-Lite的表现与同规模的最先进模型（如Qwen2.5-Coder-7B和DeepSeek-Coder-V2-Lite）相当，同时具备优异的延迟和吞吐量表现。实际应用中，相比同规模的密集型模型，我们在不牺牲性能的前提下将部署资源减少了50%。为推动该领域进一步发展，我们开源了模型及大量高质量的训练与微调数据，访问链接为~url{https://huggingface.co/inclusionAI/Ling-Coder-lite}。

> Recent advancements in code large language models (LLMs) have demonstrated remarkable capabilities in code generation and understanding. It is still challenging to build a code LLM with comprehensive performance yet ultimate efficiency. Many attempts have been released in the open source community to break the trade-off between performance and efficiency, such as the Qwen Coder series and the DeepSeek Coder series. This paper introduces yet another attempt in this area, namely Ling-Coder-Lite. We leverage the efficient Mixture-of-Experts (MoE) architecture along with a set of high-quality data curation methods (especially those based on program analytics) to build an efficient yet powerful code LLM. Ling-Coder-Lite exhibits on-par performance on 12 representative coding benchmarks compared to state-of-the-art models of similar size, such as Qwen2.5-Coder-7B and DeepSeek-Coder-V2-Lite, while offering competitive latency and throughput. In practice, we achieve a 50\% reduction in deployment resources compared to the similar-sized dense model without performance loss. To facilitate further research and development in this area, we open-source our models as well as a substantial portion of high-quality data for the annealing and post-training stages. The models and data can be accessed at~url{https://huggingface.co/inclusionAI/Ling-Coder-lite}.

[Arxiv](https://arxiv.org/abs/2503.17793)