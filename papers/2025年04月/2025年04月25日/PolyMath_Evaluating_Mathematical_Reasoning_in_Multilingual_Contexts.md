# PolyMath：多语言环境下的数学推理能力评估

发布时间：2025年04月25日

`LLM应用` `数学推理` `多语言处理`

> PolyMath: Evaluating Mathematical Reasoning in Multilingual Contexts

# 摘要

> 本文推出PolyMath，一个多语言数学推理基准测试，覆盖18种语言和4个由易到难的难度级别。该基准测试以难度全面、语言多样、翻译精良为特点，成为推理型LLM时代极具区分度的多语言数学基准。我们对先进LLMs进行了全面评估，发现即使是Deepseek-R1-671B和Qwen-QwQ-32B，也只能达到43.4和41.8的基准分数，在最高难度级别下准确率不足30%。从语言视角看，PolyMath揭示了LLMs在多语言推理中的三大挑战：（1）当前LLMs在不同语言间的推理性能差异显著；（2）推理型LLMs的输入-输出语言一致性较低，且可能与性能相关；（3）当前LLMs的思考长度因语言而异。此外，我们在指令中控制输出语言发现，这可能显著影响推理性能，尤其对某些低资源语言效果显著，为提升LLMs的多语言能力提供了重要研究方向。

> In this paper, we introduce PolyMath, a multilingual mathematical reasoning benchmark covering 18 languages and 4 easy-to-hard difficulty levels. Our benchmark ensures difficulty comprehensiveness, language diversity, and high-quality translation, making it a highly discriminative multilingual mathematical benchmark in the era of reasoning LLMs. We conduct a comprehensive evaluation for advanced LLMs and find that even Deepseek-R1-671B and Qwen-QwQ-32B, achieve only 43.4 and 41.8 benchmark scores, with less than 30% accuracy under the highest level. From a language perspective, our benchmark reveals several key challenges of LLMs in multilingual reasoning: (1) Reasoning performance varies widely across languages for current LLMs; (2) Input-output language consistency is low in reasoning LLMs and may be correlated with performance; (3) The thinking length differs significantly by language for current LLMs. Additionally, we demonstrate that controlling the output language in the instructions has the potential to affect reasoning performance, especially for some low-resource languages, suggesting a promising direction for improving multilingual capabilities in LLMs.

[Arxiv](https://arxiv.org/abs/2504.18428)