# ComPO：基于比较式预言机的偏好对齐

发布时间：2025年05月08日

`LLM理论

论文摘要：直接对齐方法在将大型语言模型 (LLMs) 与人类偏好对齐方面应用日益广泛。然而，这些方法存在冗长和可能性偏移的问题，这些问题可能由噪声偏好对引发，这些偏好对会导致偏好和不偏好响应具有相似的可能性。本文的贡献包括两个方面：首先，我们提出了一种基于比较式预言机的新偏好对齐方法，并为其基本方案提供了收敛性保证；其次，我们通过启发式改进方法，并通过实验展示了实际方案在利用噪声偏好对提升 LLM 性能方面的灵活性和兼容性。我们对 Mistral-7B、Llama-3-8B 和 Gemma-2-9B 等多个基础模型和指令微调模型进行了评估，使用了 AlpacaEval 2、MT-Bench 和 Arena-Hard 等多个基准测试。实验结果表明，我们的方法是现有直接对齐方法的有效替代方案，能够克服其局限性。值得注意的是，我们的研究证明了为具有不同可能性边际的偏好对设计专用方法的重要性，这一发现与近期 \citet{Razin-2025-Unintentional} 的研究相辅相成。
LLM理论` `人工智能` `AI伦理与安全`

> ComPO: Preference Alignment via Comparison Oracles

# 摘要

> 直接对齐方法在将大型语言模型 (LLMs) 与人类偏好对齐方面应用日益广泛。然而，这些方法存在冗长和可能性偏移的问题，这些问题可能由噪声偏好对引发，这些偏好对会导致偏好和不偏好响应具有相似的可能性。本文的贡献包括两个方面：首先，我们提出了一种基于比较式预言机的新偏好对齐方法，并为其基本方案提供了收敛性保证；其次，我们通过启发式改进方法，并通过实验展示了实际方案在利用噪声偏好对提升 LLM 性能方面的灵活性和兼容性。我们对 Mistral-7B、Llama-3-8B 和 Gemma-2-9B 等多个基础模型和指令微调模型进行了评估，使用了 AlpacaEval 2、MT-Bench 和 Arena-Hard 等多个基准测试。实验结果表明，我们的方法是现有直接对齐方法的有效替代方案，能够克服其局限性。值得注意的是，我们的研究证明了为具有不同可能性边际的偏好对设计专用方法的重要性，这一发现与近期 \citet{Razin-2025-Unintentional} 的研究相辅相成。

> Direct alignment methods are increasingly used for aligning large language models (LLMs) with human preferences. However, these methods suffer from the issues of verbosity and likelihood displacement, which can be driven by the noisy preference pairs that induce similar likelihood for preferred and dispreferred responses. The contributions of this paper are two-fold. First, we propose a new preference alignment method based on comparison oracles and provide the convergence guarantee for its basic scheme. Second, we improve our method using some heuristics and conduct the experiments to demonstrate the flexibility and compatibility of practical scheme in improving the performance of LLMs using noisy preference pairs. Evaluations are conducted across multiple base and instruction-tuned models (Mistral-7B, Llama-3-8B and Gemma-2-9B) with benchmarks (AlpacaEval 2, MT-Bench and Arena-Hard). Experimental results show the effectiveness of our method as an alternative to addressing the limitations of existing direct alignment methods. A highlight of our work is that we evidence the importance of designing specialized methods for preference pairs with distinct likelihood margin, which complements the recent findings in \citet{Razin-2025-Unintentional}.

[Arxiv](https://arxiv.org/abs/2505.05465)