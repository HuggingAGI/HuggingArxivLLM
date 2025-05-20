# SynDec：通过大型语言模型实现任意文本风格迁移的合成后解码方法

发布时间：2025年05月19日

`LLM应用`

> SynDec: A Synthesize-then-Decode Approach for Arbitrary Textual Style Transfer via Large Language Models

# 摘要

> 大型语言模型（LLMs）正在成为文本风格迁移领域的主导力量。然而，对于任意风格迁移任务，LLMs 面临两大核心挑战：一是对人工构造提示的高度依赖，二是模型本身固有的 rigid 风格偏见。本文提出了一种新颖的合成-解码（SynDec）方法，该方法能够自动合成高质量的提示，并在解码过程中放大其作用。具体而言，我们的方法通过选择代表性 Few-shot 样本、进行四维风格分析以及重新排序候选提示来合成提示。在 LLM 解码阶段，通过最大化有无合成提示场景下的输出概率对比度，以及提示与负样本之间的对比度，从而放大 TST 效果。我们进行了大量实验，结果表明 SynDec 在六个基准测试中的五个上优于现有最先进的基于 LLM 的方法（例如，在现代英语到伊丽莎白时期英语的迁移中，准确率提高了高达 9%）。详细的消融实验进一步验证了 SynDec 的有效性。

> Large Language Models (LLMs) are emerging as dominant forces for textual style transfer. However, for arbitrary style transfer, LLMs face two key challenges: (1) considerable reliance on manually-constructed prompts and (2) rigid stylistic biases inherent in LLMs. In this paper, we propose a novel Synthesize-then-Decode (SynDec) approach, which automatically synthesizes high-quality prompts and amplifies their roles during decoding process. Specifically, our approach synthesizes prompts by selecting representative few-shot samples, conducting a four-dimensional style analysis, and reranking the candidates. At LLM decoding stage, the TST effect is amplified by maximizing the contrast in output probabilities between scenarios with and without the synthesized prompt, as well as between prompts and negative samples. We conduct extensive experiments and the results show that SynDec outperforms existing state-of-the-art LLM-based methods on five out of six benchmarks (e.g., achieving up to a 9\% increase in accuracy for modern-to-Elizabethan English transfer). Detailed ablation studies further validate the effectiveness of SynDec.

[Arxiv](https://arxiv.org/abs/2505.12821)