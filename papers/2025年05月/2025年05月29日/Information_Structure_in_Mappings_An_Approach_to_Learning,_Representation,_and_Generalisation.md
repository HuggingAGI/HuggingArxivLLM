# 研究映射中信息结构的一种方法：学习、表示与泛化

发布时间：2025年05月29日

`LLM理论` `人工智能` `认知科学`

> Information Structure in Mappings: An Approach to Learning, Representation, and Generalisation

# 摘要

> 尽管大规模神经网络取得了显著成功，我们仍缺乏统一的符号体系来描述和分析它们的表示空间。现有方法难以准确描述这些模型的表示结构、结构的形成过程以及理想结构的特征。本论文提出了一套定量方法，用于识别空间映射中的系统性结构，并以此为基础，深入研究深度学习模型如何学习信息表示、推动模型泛化的关键结构，以及设计决策对结构形成的影响。

通过识别映射中的基本结构单元，并结合信息论量化分析，我们能够跨多智能体强化学习模型、单任务序列到序列模型及大型语言模型，全面考察学习机制、结构特征及其泛化能力。此外，我们还开发了一种高效可靠的向量空间熵估计方法，使上述分析可应用于参数规模从100万到120亿的各类模型。

本研究通过实验证明，大规模认知模型的学习机制与人类认知系统存在诸多相似之处。实验结果表明，语言结构及其生成约束与推动当代神经网络性能的核心结构特征具有高度相似性，揭示了自然语言与人工神经网络在结构演化上的平行规律。


> Despite the remarkable success of large large-scale neural networks, we still lack unified notation for thinking about and describing their representational spaces. We lack methods to reliably describe how their representations are structured, how that structure emerges over training, and what kinds of structures are desirable. This thesis introduces quantitative methods for identifying systematic structure in a mapping between spaces, and leverages them to understand how deep-learning models learn to represent information, what representational structures drive generalisation, and how design decisions condition the structures that emerge. To do this I identify structural primitives present in a mapping, along with information theoretic quantifications of each. These allow us to analyse learning, structure, and generalisation across multi-agent reinforcement learning models, sequence-to-sequence models trained on a single task, and Large Language Models. I also introduce a novel, performant, approach to estimating the entropy of vector space, that allows this analysis to be applied to models ranging in size from 1 million to 12 billion parameters.
  The experiments here work to shed light on how large-scale distributed models of cognition learn, while allowing us to draw parallels between those systems and their human analogs. They show how the structures of language and the constraints that give rise to them in many ways parallel the kinds of structures that drive performance of contemporary neural networks.

[Arxiv](https://arxiv.org/abs/2505.23960)