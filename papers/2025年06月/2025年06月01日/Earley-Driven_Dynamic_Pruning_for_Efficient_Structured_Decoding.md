# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月01日

`LLM应用` `软件工程` `数据处理`

> Earley-Driven Dynamic Pruning for Efficient Structured Decoding

# 摘要

> 大型语言模型 (LLMs) 虽然能力出众，但在函数调用和领域特定语言 (DSL) 生成等场景下，确保输出符合严格的结构或语法规则仍然是一项挑战。基于上下文无关文法的受限解码通过动态构建 token logits 掩码来保证 LLMs 遵循特定格式，是一种灵活的方法。然而，现有受限解码引擎在每一步解码时都需要检查 LLM 词汇表中所有 token 的有效性，这导致显著的性能开销。为了解决这一问题，我们提出了 $	extbf{ZapFormat}$，这是一种基于 Earley 算法的 $	extbf{动态剪枝}$ 策略，能够在实时环境中识别并消除无效或冗余的 Earley 状态，从而大幅降低 Earley 算法状态的内存占用。这使我们能够利用状态缓存加速大量查询的结构化生成。我们在名为 Formatron 的新受限解码引擎中实现了 ZapFormat，该引擎还集成了现有的优化。通过在 JSON 生成、JSON Schema 验证和语义解析等结构化生成任务上的全面实验，我们证明 Formatron 不仅 $	extbf{始终维持}$ 高精度的合规输出，而且与最先进的实现相比，推理速度实现了 $	extbf{显著提升}$，最高可达 2 倍。更重要的是，Formatron 可广泛应用于各种 LLM 架构。我们已将 Formatron 作为开源项目发布在 https://github.com/Dan-wanna-M/formatron。


> Large Language Models (LLMs) have shown remarkable capabilities, yet ensuring their outputs conform to strict structural or grammatical constraints remains challenging, which is critical in function calls and domain-specific language (DSL) generation. Constrained decoding with context-free grammar is a flexible approach to guarantee LLMs' adherence to a specific format by dynamically building a token logits mask. However, creating this mask requires checking the validity of all tokens in the LLM vocabulary at every decoding step, which often incurs significant overheads in existing constrained decoding engines. To address this challenge, we propose $\textbf{ZapFormat}$, a novel $\textbf{dynamic pruning}$ strategy based on the Earley algorithm that identifies and eliminates invalid or redundant Earley states in real-time, significantly reducing memory occupation of the Earley algorithm's states. This further enables us to use a state cache to speed up structured generations on a large number of queries. We implemented ZapFormat in a new constrained decoding engine called Formatron which also incorporates existing optimizations. Through comprehensive experiments on structured generation tasks, including JSON generation, JSON Schema validation, and semantic parsing, we demonstrate that Formatron not only $\textbf{consistently maintains}$ high-precision compliant outputs but also achieves $\textbf{significant improvements}$ in inference speed up to 2x compared to state-of-the-art implementations. More importantly, Formatron is generally applicable across various LLM architectures. We release Formatron as open source at https://github.com/Dan-wanna-M/formatron.

[Arxiv](https://arxiv.org/abs/2506.01151)