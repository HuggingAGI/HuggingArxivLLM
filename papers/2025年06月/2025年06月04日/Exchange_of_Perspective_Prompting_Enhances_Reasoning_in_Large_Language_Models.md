# 通过视角交换提示提升大型语言模型的推理能力

发布时间：2025年06月04日

`LLM理论`

> Exchange of Perspective Prompting Enhances Reasoning in Large Language Models

# 摘要

> 大型语言模型（LLMs）在多种自然语言处理（NLP）任务中取得了显著进展，但其性能往往受限于对问题本身的固有理解。为突破这一限制，我们提出了一种全新的视角交换（Exchange-of-Perspective, EoP）框架，通过在不同问题定义间交换视角，打破固定思维模式，从而摆脱特定问题表述的限制。我们在8个基准数据集上进行了广泛实验，结果表明EoP能够显著提升模型性能。例如，在AQuA数据集上，性能从60.6%提升至64.2%，实现了3.6%的提升；在Math数据集上，基于GPT-4的EoP将准确率从53.9%提升至61.6%，整体提升了7.7%；在OlympiadBench Maths数据集上，性能则从43.5%提升至47.0%，实现了3.5%的提升。

> Large language models (LLMs) have made significant advancements in addressing diverse natural language processing (NLP) tasks. However, their performance is often limited by inherent comprehension of problems. To address this limitation, we propose Exchange-of-Perspective (EoP), a novel framework designed to exchange perspectives across different definitions of problem, so that it can break the fixed mindset from any particular formulation of the question. We conducted extensive and comprehensive experiments on 8 benchmarks. The results show that EoP can significantly improve performance. For instance, compared to the non-commutative baseline PHP, with GPT-3.5-Turbo and EoP, we observe a 3.6% improvement on AQuA (60.6% to 64.2%), while GPT-4-powered EoP demonstrates a 7.7% overall accuracy enhancement on Math (53.9% to 61.6%) and a 3.5% improvement on OlympiadBench Maths (43.5% to 47.0%) when using Qwen-2.5-72b.

[Arxiv](https://arxiv.org/abs/2506.03573)