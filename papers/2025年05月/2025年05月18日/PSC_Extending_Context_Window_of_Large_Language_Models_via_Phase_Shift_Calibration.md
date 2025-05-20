# PSC：通过相位偏移校准扩展大型语言模型的上下文窗口

发布时间：2025年05月18日

`LLM理论

理由：这篇论文探讨了旋转位置编码（RoPE）在大型语言模型中的应用，并提出了一种新的方法来优化RoPE的频率调整。它属于对大型语言模型（LLM）内部机制的理论研究和改进，因此应归类为LLM理论。` `文本处理`

> PSC: Extending Context Window of Large Language Models via Phase Shift Calibration

# 摘要

> 旋转位置编码（Rotary Position Embedding, RoPE）是一种高效的位置编码方法，在众多大型语言模型（LLMs）中得到广泛应用。近期，许多人提出基于RoPE进一步扩展上下文窗口的方法。这些方法的核心理念是预定义或搜索一组因子来调整RoPE的基本频率。然而，由于指数级的搜索空间，现有方法很难预定义一个最优的因子。针对这一问题，我们引入了PSC（相位移校准），这是一个用于校准现有方法预定义频率的小模块。通过引入PSC，我们证明了许多现有方法可以进一步提升，例如PI、YaRN和LongRoPE。

我们在多个模型和任务上进行了大量实验。结果表明：（1）当启用PSC时，困惑度的比较减少随着上下文窗口大小从16k增加到32k，再到64k而增加。（2）我们的方法具有广泛适用性，并在多种模型和任务中表现出稳健性。代码可在https://github.com/WNQzhu/PSC获取。

> Rotary Position Embedding (RoPE) is an efficient position encoding approach and is widely utilized in numerous large language models (LLMs). Recently, a lot of methods have been put forward to further expand the context window based on RoPE. The core concept of those methods is to predefine or search for a set of factors to rescale the base frequencies of RoPE. Nevertheless, it is quite a challenge for existing methods to predefine an optimal factor due to the exponential search space. In view of this, we introduce PSC (Phase Shift Calibration), a small module for calibrating the frequencies predefined by existing methods. With the employment of PSC, we demonstrate that many existing methods can be further enhanced, like PI, YaRN, and LongRoPE. We conducted extensive experiments across multiple models and tasks. The results demonstrate that (1) when PSC is enabled, the comparative reductions in perplexity increase as the context window size is varied from 16k, to 32k, and up to 64k. (2) Our approach is broadly applicable and exhibits robustness across a variety of models and tasks. The code can be found at https://github.com/WNQzhu/PSC.

[Arxiv](https://arxiv.org/abs/2505.12423)