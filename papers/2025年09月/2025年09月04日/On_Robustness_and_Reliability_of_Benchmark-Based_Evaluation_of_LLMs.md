# # 论LLMs基准评估的鲁棒性与可靠性

发布时间：2025年09月04日

`LLM应用` `基础理论`

> On Robustness and Reliability of Benchmark-Based Evaluation of LLMs

# 摘要

> 大型语言模型（LLMs）的有效性评估通常依赖MMLU、ARC-C、HellaSwag等基准测试，这些测试中的问题采用原始措辞，格式固定且标准化。但现实应用中存在语言变异性，这要求模型在同一问题或查询的不同表述下仍能保持有效性。本研究系统评估LLMs对转述后基准问题的稳健性，并探究基准测试能否可靠衡量模型能力。我们针对六个常见基准的所有问题生成了多种转述版本，随后测试了34个不同规模和性能水平的最先进LLMs在这些转述问题上的有效性变化。结果显示：尽管LLM的排名在转述输入中相对稳定，但其绝对有效性分数却出现显著波动和下降。这说明LLMs在应对语言变异性时存在短板，引发了对其泛化能力及现有评估方法的质疑。此外，性能下降现象也挑战了基准测试的可靠性——高分可能无法充分反映模型对现实输入变化的稳健性。最后，我们探讨了这些发现对LLM评估方法的启示，强调需构建兼顾稳健性的基准测试，以更贴合实际部署场景。

> Large Language Models (LLMs) effectiveness is usually evaluated by means of benchmarks such as MMLU, ARC-C, or HellaSwag, where questions are presented in their original wording, thus in a fixed, standardized format. However, real-world applications involve linguistic variability, requiring models to maintain their effectiveness across diverse rewordings of the same question or query. In this study, we systematically assess the robustness of LLMs to paraphrased benchmark questions and investigate whether benchmark-based evaluations provide a reliable measure of model capabilities. We systematically generate various paraphrases of all the questions across six different common benchmarks, and measure the resulting variations in effectiveness of 34 state-of-the-art LLMs, of different size and effectiveness. Our findings reveal that while LLM rankings remain relatively stable across paraphrased inputs, absolute effectiveness scores change, and decline significantly. This suggests that LLMs struggle with linguistic variability, raising concerns about their generalization abilities and evaluation methodologies. Furthermore, the observed performance drop challenges the reliability of benchmark-based evaluations, indicating that high benchmark scores may not fully capture a model's robustness to real-world input variations. We discuss the implications of these findings for LLM evaluation methodologies, emphasizing the need for robustness-aware benchmarks that better reflect practical deployment scenarios.

[Arxiv](https://arxiv.org/abs/2509.04013)