# 通过部分线性前馈网络加速大型语言模型

发布时间：2025年01月17日

`LLM理论

理由：这篇论文主要讨论了如何通过优化大型语言模型（LLMs）的激活函数来实现参数精简和推理加速。虽然涉及到了LLM的应用（如与vLLM服务系统的集成），但其核心贡献在于提出了一种新的理论方法（TARDIS）来优化LLMs的计算效率，属于对LLM理论的研究和改进。因此，将其分类为“LLM理论”更为合适。` `模型压缩`

> Accelerating Large Language Models through Partially Linear Feed-Forward Network

# 摘要

> 大型语言模型（LLMs）虽然能力强大，但庞大的参数量使其部署面临挑战。现有压缩技术（如剪枝）虽能缩小模型，但在高压缩比下精度损失严重。我们借鉴编译器优化中的常量折叠，提出了一种新思路：将LLMs中的激活函数视为线性函数，从而实现参数精简。
    然而，现代LLMs多采用复杂的非线性激活函数（如GELU），直接应用该技术存在困难。为此，我们提出了TARDIS，通过在常见输入范围内用线性函数近似非线性激活函数，优化LLMs。对于异常输入，TARDIS通过在线预测器动态切换回原始计算。
    实验表明，TARDIS在前馈网络中实现了80%的参数精简，精度比Wanda和RIA等先进剪枝方法高出65%。在实际部署中，7B模型与vLLM服务系统集成时，TARDIS实现了1.6倍的端到端推理加速，与HuggingFace实现相比加速了1.4倍，精度损失仅为10.9%。

> Large language models (LLMs) demonstrate remarkable capabilities but face deployment challenges due to their massive parameter counts. While existing compression techniques like pruning can reduce model size, it leads to significant accuracy degradation under high compression ratios. We present a novel perspective inspired by constant folding in compiler optimization. Our approach enables parameter reduction by treating activation functions in LLMs as linear functions.
  However, recent LLMs use complex non-linear activations like GELU that prevent direct application of this technique. We propose TARDIS, which enables optimization of LLMs with non-linear activations by partially approximating them with linear functions in frequently occurring input ranges. For outlier inputs, TARDIS employs an online predictor to dynamically fall back to original computations.
  Our experiments demonstrate that TARDIS achieves 80% parameter reduction in feed-forward networks, while significantly outperforming state-of-the-art pruning methods Wanda and RIA with up to 65% higher accuracy. In practical deployments for a 7B model, TARDIS achieves 1.6x end-to-end inference speedup when integrated with the vLLM serving system, and 1.4x speedup with the widely adopted HuggingFace implementation, while incurring only a 10.9% accuracy trade-off.

[Arxiv](https://arxiv.org/abs/2501.10054)