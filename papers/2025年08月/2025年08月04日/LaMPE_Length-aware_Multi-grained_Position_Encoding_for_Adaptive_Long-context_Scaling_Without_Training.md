# LaMPE：长度感知多粒度位置编码，实现无需训练的自适应长上下文扩展

发布时间：2025年08月04日

`LLM理论

摘要中讨论了大型语言模型在处理长上下文时的性能问题，并提出了一种新的位置编码方法LaMPE，属于模型的理论优化，因此归类为LLM理论。`

> LaMPE: Length-aware Multi-grained Position Encoding for Adaptive Long-context Scaling Without Training

# 摘要

> 当输入超出预训练上下文窗口时，大型语言模型（LLMs）的性能会显著下降，这主要归因于Rotary Position Embedding（RoPE）的出分布（OOD）行为。近期研究通过固定映射策略将出分布位置重新映射到分布范围内来缓解这一问题，但忽略了输入长度与模型有效上下文窗口之间的动态关系。为此，我们提出了无需训练的长度感知多粒度位置编码（LaMPE），该方法能够充分利用模型的有效上下文窗口，实现LLMs中自适应的长上下文扩展。受相对位置左偏频数分布的启发，LaMPE通过参数化的缩放Sigmoid函数在映射长度与输入长度之间建立动态关系，从而在不同输入长度下自适应地分配位置容量。同时，LaMPE设计了一种新颖的多粒度注意力机制，能够在不同序列区域战略性地分配位置分辨率，以捕捉精细的局部关系和长距离依赖。我们的方法无需训练，可无缝应用于各种基于RoPE的LLMs。在五个主流长上下文基准测试中，针对三种代表性的LLMs进行的广泛实验表明，与现有的长度外推方法相比，LaMPE实现了显著的性能提升。代码将在https://github.com/scar-on/LaMPE发布。

> Large language models (LLMs) experience significant performance degradation when the input exceeds the pretraining context window, primarily due to the out-of-distribution (OOD) behavior of Rotary Position Embedding (RoPE). Recent studies mitigate this problem by remapping OOD positions into the in-distribution range with fixed mapping strategies, ignoring the dynamic relationship between input length and the model's effective context window. To this end, we propose Length-aware Multi-grained Positional Encoding (LaMPE), a training-free method that fully utilizes the model's effective context window for adaptive long-context scaling in LLMs. Motivated by the left-skewed frequency distribution of relative positions, LaMPE establishes a dynamic relationship between mapping length and input length through a parametric scaled sigmoid function to adaptively allocate positional capacity across varying input lengths. Meanwhile, LaMPE devises a novel multi-grained attention mechanism that strategically allocates positional resolution across different sequence regions to capture both fine-grained locality and long-range dependencies. Our method can be seamlessly applied to a wide range of RoPE-based LLMs without training. Extensive experiments on three representative LLMs across five mainstream long-context benchmarks demonstrate that LaMPE achieves significant performance improvements compared to existing length extrapolation methods. The code will be released at https://github.com/scar-on/LaMPE.

[Arxiv](https://arxiv.org/abs/2508.02308)