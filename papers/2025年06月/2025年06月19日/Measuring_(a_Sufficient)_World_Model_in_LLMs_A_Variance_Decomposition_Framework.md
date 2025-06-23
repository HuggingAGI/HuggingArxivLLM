# LLMs中的充分世界模型测量：方差分解框架

发布时间：2025年06月19日

`LLM理论` `人工智能`

> Measuring (a Sufficient) World Model in LLMs: A Variance Decomposition Framework

# 摘要

> 大型语言模型是否具备世界模型——即超越表面模式的结构化世界理解能力——是评估其可靠性的核心，尤其是在高风险应用中。我们提出了一种正式框架，用于评估LLM是否展现出足够稳健的世界模型。具备强大世界模型的LLM应将其大部分响应变化归因于基础目标的变化，而非表达方式的表面变化。我们引入了一种新的评估方法来衡量这一点，将模型响应的变化分解为三个组成部分：由于用户目标、用户表达和模型不稳定引起的变化。这种方法使我们能够量化模型行为中有多少是语义驱动的，而非由模型不稳定或替代措辞驱动。我们应用此框架对跨多个领域的LLMs进行了评估。结果显示，规模更大的模型将更多的输出变化归因于用户目标的变化，表明其世界模型更加稳健。然而，这种改进并非均匀：更大的模型并非在所有领域都一致地优于较小的模型，其在稳健性方面的优势通常较为有限。这些发现强调了超越基于准确性的基准，转向更直接评估模型对世界内部理解的结构和稳定性的语义诊断的重要性。

> Understanding whether large language models (LLMs) possess a world model-a structured understanding of the world that supports generalization beyond surface-level patterns-is central to assessing their reliability, especially in high-stakes applications. We propose a formal framework for evaluating whether an LLM exhibits a sufficiently robust world model, defined as producing consistent outputs across semantically equivalent prompts while distinguishing between prompts that express different intents. We introduce a new evaluation approach to measure this that decomposes model response variability into three components: variability due to user purpose, user articulation, and model instability. An LLM with a strong world model should attribute most of the variability in its responses to changes in foundational purpose rather than superficial changes in articulation. This approach allows us to quantify how much of a model's behavior is semantically grounded rather than driven by model instability or alternative wording. We apply this framework to evaluate LLMs across diverse domains. Our results show how larger models attribute a greater share of output variability to changes in user purpose, indicating a more robust world model. This improvement is not uniform, however: larger models do not consistently outperform smaller ones across all domains, and their advantage in robustness is often modest. These findings highlight the importance of moving beyond accuracy-based benchmarks toward semantic diagnostics that more directly assess the structure and stability of a model's internal understanding of the world.

[Arxiv](https://arxiv.org/abs/2506.16584)