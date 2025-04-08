# DoCIA：专为语音翻译设计的在线文档级上下文整合器

发布时间：2025年04月07日

`LLM应用` `语音翻译`

> DoCIA: An Online Document-Level Context Incorporation Agent for Speech Translation

# 摘要

> # 摘要
文档级上下文在文本到文本文档级机器翻译（MT）中处理 discourse 挑战至关重要。然而，尽管自动语音识别（ASR）引入的噪声增加了 discourse 挑战，但文档级上下文在语音翻译（ST）中的整合仍未得到充分探索。本文中，我们开发了 DoCIA，这是一个在线框架，通过整合文档级上下文来提升 ST 性能。DoCIA 将 ST 管道分解为四个阶段，通过辅助的大语言模型（LLM）-基模块将文档级上下文集成到 ASR 优化、MT 和 MT 优化阶段。此外，DoCIA 以多级方式利用文档级信息，同时尽量减少计算开销。另外，引入了一种简单而有效的确定机制，以防止过多优化导致的幻觉，确保最终结果的可靠性。实验结果表明，DoCIA 在四种 LLM 上的句子和 discourse 指标均显著优于传统的 ST 基线，证明了其在提升 ST 性能方面的有效性。


> Document-level context is crucial for handling discourse challenges in text-to-text document-level machine translation (MT). Despite the increased discourse challenges introduced by noise from automatic speech recognition (ASR), the integration of document-level context in speech translation (ST) remains insufficiently explored. In this paper, we develop DoCIA, an online framework that enhances ST performance by incorporating document-level context. DoCIA decomposes the ST pipeline into four stages. Document-level context is integrated into the ASR refinement, MT, and MT refinement stages through auxiliary LLM (large language model)-based modules. Furthermore, DoCIA leverages document-level information in a multi-level manner while minimizing computational overhead. Additionally, a simple yet effective determination mechanism is introduced to prevent hallucinations from excessive refinement, ensuring the reliability of the final results. Experimental results show that DoCIA significantly outperforms traditional ST baselines in both sentence and discourse metrics across four LLMs, demonstrating its effectiveness in improving ST performance.

[Arxiv](https://arxiv.org/abs/2504.05122)