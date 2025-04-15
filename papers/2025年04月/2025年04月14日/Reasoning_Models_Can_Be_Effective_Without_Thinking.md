# 推理模型无需主动思考也能展现强大的效果

发布时间：2025年04月14日

`LLM应用

理由：这篇论文探讨了大语言模型在推理任务中的表现，特别是通过显式的长篇思考过程。研究者提出了NoThinking方法，展示了其在多个推理任务中的有效性，并探讨了并行缩放方法的应用。这些内容属于大语言模型的应用层面，因此归类为LLM应用。` `计算机科学`

> Reasoning Models Can Be Effective Without Thinking

# 摘要

> 近期的大语言模型（LLMs）在推理能力方面取得了显著提升，主要通过将显式的长篇思考过程作为生成的一部分来实现。在这篇论文中，我们提出疑问：这种显式思考是否真的必要？通过使用先进的DeepSeek-R1-Distill-Qwen模型，我们发现，通过简单的提示绕过思考过程（称为NoThinking）可以产生令人惊喜的有效结果。在控制token数量的情况下，NoThinking在七个具有挑战性的推理数据集上表现优于Thinking——包括数学问题解决、形式定理证明和编程——尤其是在低预算设置下，例如在ACM23上的700个token测试中，NoThinking的准确率达到51.3%，而Thinking仅为28.9%。值得注意的是，随着k的增加，NoThinking的性能在pass@k指标上变得更加有竞争力。基于这一观察，我们展示了使用NoThinking独立生成N个输出并聚合它们的并行缩放方法非常有效。在聚合过程中，如果有现成的任务特定验证器，我们使用它；否则，我们应用简单的best-of-N策略，例如基于置信度的选择。我们的方法在与使用Thinking的类似延迟的多种基线方法中表现出色，并且在显著更长的延迟（高达9倍）下与Thinking相当。总的来说，我们的研究促使人们重新思考长篇思考过程的必要性，同时也为在低预算设置或低延迟下通过并行缩放实现强大的推理性能提供了有力的参考。

> Recent LLMs have significantly improved reasoning capabilities, primarily by including an explicit, lengthy Thinking process as part of generation. In this paper, we question whether this explicit thinking is necessary. Using the state-of-the-art DeepSeek-R1-Distill-Qwen, we find that bypassing the thinking process via simple prompting, denoted as NoThinking, can be surprisingly effective. When controlling for the number of tokens, NoThinking outperforms Thinking across a diverse set of seven challenging reasoning datasets--including mathematical problem solving, formal theorem proving, and coding--especially in low-budget settings, e.g., 51.3 vs. 28.9 on ACM 23 with 700 tokens. Notably, the performance of NoThinking becomes more competitive with pass@k as k increases. Building on this observation, we demonstrate that a parallel scaling approach that uses NoThinking to generate N outputs independently and aggregates them is highly effective. For aggregation, we use task-specific verifiers when available, or we apply simple best-of-N strategies such as confidence-based selection. Our method outperforms a range of baselines with similar latency using Thinking, and is comparable to Thinking with significantly longer latency (up to 9x). Together, our research encourages a reconsideration of the necessity of lengthy thinking processes, while also establishing a competitive reference for achieving strong reasoning performance in low-budget settings or at low latency using parallel scaling.

[Arxiv](https://arxiv.org/abs/2504.09858)