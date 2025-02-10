# S$^2$-MAD：突破Token限制，提升多智能体辩论效率

发布时间：2025年02月07日

`Agent` `人工智能` `机器学习`

> S$^2$-MAD: Breaking the Token Barrier to Enhance Multi-Agent Debate Efficiency

# 摘要

> 大型语言模型（LLMs）在NLP领域表现优异，但在复杂算术和逻辑推理任务中仍具挑战。尽管链式思维（CoT）推理、自我一致性（SC）和自我纠错策略尝试通过引导模型进行顺序、多步骤推理来解决问题，但多智能体辩论（MAD）作为一种有效的提升LLMs推理能力的方法应运而生。通过增加智能体的数量和辩论的频率，LLMs的性能得到了显著提升。然而，这种策略导致token成本大幅上升，成为扩展性的一大障碍。为了解决这一问题，我们提出了一种新型稀疏化策略，旨在降低MAD中的token成本。该方法减少了智能体之间无效的信息交换和无意义的讨论，从而提升了整个辩论过程的整体效率。我们在多个数据集和各种模型上进行了对比实验，结果表明，与MAD相比，我们的方法在显著降低token成本的同时，性能下降不超过2.0%，实现了高达94.5%的token成本削减。

> Large language models (LLMs) have demonstrated remarkable capabilities across various natural language processing (NLP) scenarios, but they still face challenges when handling complex arithmetic and logical reasoning tasks. While Chain-Of-Thought (CoT) reasoning, self-consistency (SC) and self-correction strategies have attempted to guide models in sequential, multi-step reasoning, Multi-agent Debate (MAD) has emerged as a viable approach for enhancing the reasoning capabilities of LLMs. By increasing both the number of agents and the frequency of debates, the performance of LLMs improves significantly. However, this strategy results in a significant increase in token costs, presenting a barrier to scalability. To address this challenge, we introduce a novel sparsification strategy designed to reduce token costs within MAD. This approach minimizes ineffective exchanges of information and unproductive discussions among agents, thereby enhancing the overall efficiency of the debate process. We conduct comparative experiments on multiple datasets across various models, demonstrating that our approach significantly reduces the token costs in MAD to a considerable extent. Specifically, compared to MAD, our approach achieves an impressive reduction of up to 94.5\% in token costs while maintaining performance degradation below 2.0\%.

[Arxiv](https://arxiv.org/abs/2502.04790)