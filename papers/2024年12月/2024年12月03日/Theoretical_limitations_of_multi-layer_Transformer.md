# 多层 Transformer 的理论限制

发布时间：2024年12月03日

`LLM理论` `语言模型` `计算机技术`

> Theoretical limitations of multi-layer Transformer

# 摘要

> Transformers，特别是仅解码器的变体，是大多数现代大型语言模型的核心所在；然而，除了简单的 1 层情况，我们对其表达能力的了解十分有限。
  鉴于分析多层模型的难度，此前所有工作都依靠未经证实的复杂性推测来表明多层 Transformers 的局限性。在本研究中，我们为多层仅解码器 Transformers 证明了首个【无条件】下限。对于任何常数 L，我们证实任何 L 层仅解码器 Transformer 要对 n 个标记的输入执行 L 个函数的顺序组合，就需要多项式模型维度（$n^{Ω(1)}$）。
  由此，我们的成果得出：（1）多层 Transformers 的首个深度与宽度的权衡，表明 L 层模型的 L 步组合任务比（L + 1）层模型难上指数倍；（2）编码器与解码器之间的【无条件】分离，呈现出一个对于解码器而言困难但能被指数更浅和更小的编码器解决的任务；（3）思维链的可证明优势，展示出一个随着思维链而变得指数级容易的任务。
  在技术层面，我们提出了多方【自回归】【通信】【模型】，它能够捕捉仅解码器 Transformer 的计算过程。我们还引入了一种新的证明技术，该技术通过迭代找到所有可能输入的某种【不可区分】【分解】，以证明此模型中的下限。我们相信我们的新通信模型和证明技术将有助于更深入地理解 Transformers 的计算能力。

> Transformers, especially the decoder-only variants, are the backbone of most modern large language models; yet we do not have much understanding of their expressive power except for the simple $1$-layer case.
  Due to the difficulty of analyzing multi-layer models, all previous work relies on unproven complexity conjectures to show limitations for multi-layer Transformers. In this work, we prove the first $\textit{unconditional}$ lower bound against multi-layer decoder-only transformers. For any constant $L$, we prove that any $L$-layer decoder-only transformer needs a polynomial model dimension ($n^{Ω(1)}$) to perform sequential composition of $L$ functions over an input of $n$ tokens.
  As a consequence, our results give: (1) the first depth-width trade-off for multi-layer transformers, exhibiting that the $L$-step composition task is exponentially harder for $L$-layer models compared to $(L+1)$-layer ones; (2) an unconditional separation between encoder and decoder, exhibiting a hard task for decoders that can be solved by an exponentially shallower and smaller encoder; (3) a provable advantage of chain-of-thought, exhibiting a task that becomes exponentially easier with chain-of-thought.
  On the technical side, we propose the multi-party $\textit{autoregressive}$ $\textit{communication}$ $\textit{model}$ that captures the computation of a decoder-only Transformer. We also introduce a new proof technique that finds a certain $\textit{indistinguishable}$ $\textit{decomposition}$ of all possible inputs iteratively for proving lower bounds in this model. We believe our new communication model and proof technique will be helpful to further understand the computational power of transformers.

[Arxiv](https://arxiv.org/abs/2412.02975)