# Earley驱动的动态剪枝方法实现高效的结构化解码

发布时间：2025年06月01日

`LLM应用

论文摘要：大型语言模型（LLMs）展现出了非凡的能力，但在函数调用和领域特定语言（DSL）生成等场景中，确保其输出符合严格的结构或语法规则仍具挑战性。基于上下文无关文法的约束解码通过动态构建标记对数掩码，能够保证LLMs严格遵循特定格式，但现有方法通常需要在每一步解码过程中检查LLMs词汇表中所有标记的有效性，带来显著的计算开销。为了解决这一难题，我们提出了$	extbf{ZapFormat}$，这是一种基于Earley算法的新型$	extbf{动态剪枝}$策略，能够在实时运行中识别并消除无效或冗余的Earley状态，从而显著减少Earley算法状态的内存占用。这进一步使我们能够利用状态缓存加速大规模查询的结构化生成。我们在名为Formatron的新约束解码引擎中实现了ZapFormat，并集成了现有的优化技术。通过在结构化生成任务（包括JSON生成、JSON Schema验证和语义解析）上的全面实验，我们证明Formatron不仅能够$	extbf{持续保持}$高精度的合规输出，而且与最先进的实现相比，推理速度提升了$	extbf{显著改进}$，最高可达2倍。更重要的是，Formatron适用于各种LLM架构。我们已在https://github.com/Dan-wanna-M/formatron上开源了Formatron。` `结构化生成` `领域特定语言生成`

> Earley-Driven Dynamic Pruning for Efficient Structured Decoding

# 摘要

> 大型语言模型（LLMs）展现出了非凡的能力，但在函数调用和领域特定语言（DSL）生成等场景中，确保其输出符合严格的结构或语法规则仍具挑战性。基于上下文无关文法的约束解码通过动态构建标记对数掩码，能够保证LLMs严格遵循特定格式，但现有方法通常需要在每一步解码过程中检查LLMs词汇表中所有标记的有效性，带来显著的计算开销。为了解决这一难题，我们提出了$	extbf{ZapFormat}$，这是一种基于Earley算法的新型$	extbf{动态剪枝}$策略，能够在实时运行中识别并消除无效或冗余的Earley状态，从而显著减少Earley算法状态的内存占用。这进一步使我们能够利用状态缓存加速大规模查询的结构化生成。我们在名为Formatron的新约束解码引擎中实现了ZapFormat，并集成了现有的优化技术。通过在结构化生成任务（包括JSON生成、JSON Schema验证和语义解析）上的全面实验，我们证明Formatron不仅能够$	extbf{持续保持}$高精度的合规输出，而且与最先进的实现相比，推理速度提升了$	extbf{显著改进}$，最高可达2倍。更重要的是，Formatron适用于各种LLM架构。我们已在https://github.com/Dan-wanna-M/formatron上开源了Formatron。

> Large Language Models (LLMs) have shown remarkable capabilities, yet ensuring their outputs conform to strict structural or grammatical constraints remains challenging, which is critical in function calls and domain-specific language (DSL) generation. Constrained decoding with context-free grammar is a flexible approach to guarantee LLMs' adherence to a specific format by dynamically building a token logits mask. However, creating this mask requires checking the validity of all tokens in the LLM vocabulary at every decoding step, which often incurs significant overheads in existing constrained decoding engines. To address this challenge, we propose $\textbf{ZapFormat}$, a novel $\textbf{dynamic pruning}$ strategy based on the Earley algorithm that identifies and eliminates invalid or redundant Earley states in real-time, significantly reducing memory occupation of the Earley algorithm's states. This further enables us to use a state cache to speed up structured generations on a large number of queries. We implemented ZapFormat in a new constrained decoding engine called Formatron which also incorporates existing optimizations. Through comprehensive experiments on structured generation tasks, including JSON generation, JSON Schema validation, and semantic parsing, we demonstrate that Formatron not only $\textbf{consistently maintains}$ high-precision compliant outputs but also achieves $\textbf{significant improvements}$ in inference speed up to 2x compared to state-of-the-art implementations. More importantly, Formatron is generally applicable across various LLM architectures. We release Formatron as open source at https://github.com/Dan-wanna-M/formatron.

[Arxiv](https://arxiv.org/abs/2506.01151)