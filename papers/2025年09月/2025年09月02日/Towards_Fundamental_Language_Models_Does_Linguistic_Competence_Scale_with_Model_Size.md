# 走向基础语言模型：语言能力是否随模型规模而扩展？

发布时间：2025年09月02日

`LLM理论` `基础理论`

> Towards Fundamental Language Models: Does Linguistic Competence Scale with Model Size?

# 摘要

> 大型语言模型虽拥有令人惊叹的语言能力，却存在诸多公认局限，如幻觉、偏见、隐私风险及高昂计算成本。这些问题的根源在于单一整体模型将语言能力与事实记忆融为一体。本文提出并经实证验证了基础语言模型（FLM）范式，该范式倡导构建更小、具备语言能力的模型，将事实检索任务交由外部工具处理。我们从语言能力、外部事实知识和内部事实知识三个维度，对参数规模介于1.35亿至320亿之间的模型展开评估。研究发现，尽管语言能力和事实知识均随模型规模提升而增强，但内部事实知识的增长速度显著更快，这意味着模型大小与记忆能力的关联远胜于其与核心语言能力的关联。这些结果支持语言建模的模块化思路，即通过紧凑且语言能力精湛的模型作为工具增强系统的核心基础。FLM范式为打造更高效、可解释且可持续的自然语言处理解决方案开辟了新路径。

> Large Language Models offer impressive language capabilities but suffer from well-known limitations, including hallucinations, biases, privacy concerns, and high computational costs. These issues are largely driven by the combination of linguistic competence and factual memorization within a single monolithic model. This paper introduces and empirically supports the Fundamental Language Model (FLM) paradigm, which advocates for smaller, linguistically competent models that offload factual retrieval to external tools. We evaluate models ranging from 135M to 32B parameters across three dimensions: linguistic competence, external factual knowledge, and internal factual knowledge. Our findings reveal that while both linguistic competence and factual knowledge improve with scale, internal factual knowledge grows significantly faster, suggesting that model size is more closely tied to memorization than to core language ability. These results support a modular approach to language modeling, where compact, linguistically proficient models serve as the foundation for tool-augmented systems. The FLM paradigm offers a path toward more efficient, interpretable, and sustainable NLP solutions.

[Arxiv](https://arxiv.org/abs/2509.02225)