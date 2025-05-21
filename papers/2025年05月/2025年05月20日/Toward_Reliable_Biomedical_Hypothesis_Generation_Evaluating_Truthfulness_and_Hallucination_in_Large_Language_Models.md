# 构建可靠生物医学假设生成：探索大型语言模型的真实性与幻觉

发布时间：2025年05月20日

`LLM应用` `生物医学` `科学发现`

> Toward Reliable Biomedical Hypothesis Generation: Evaluating Truthfulness and Hallucination in Large Language Models

# 摘要

> 大型语言模型（LLMs）在生物医学等科学领域展现出了巨大潜力，尤其是在假设生成方面。它们能够分析大量文献、识别模式并提出研究方向。然而，评估生成假设的真实性面临两大挑战：验证准确性耗时费力，以及LLMs的幻觉问题可能生成看似合理却错误的假设。为系统研究这些挑战，我们推出了TruthHypo，一个评估LLMs生成真实生物医学假设能力的基准，以及KnowHD，一个基于知识的幻觉检测器，用于评估假设与现有知识的契合程度。实验结果显示，LLMs在生成真实假设方面表现欠佳。通过分析推理过程中的幻觉，我们发现KnowHD提供的基于知识评分是一个有效筛选真实假设的指标。人工评估进一步证实了KnowHD在识别真实假设和加速科学发现方面的实用价值。我们的数据和源代码可在GitHub上获取。

> Large language models (LLMs) have shown significant potential in scientific disciplines such as biomedicine, particularly in hypothesis generation, where they can analyze vast literature, identify patterns, and suggest research directions. However, a key challenge lies in evaluating the truthfulness of generated hypotheses, as verifying their accuracy often requires substantial time and resources. Additionally, the hallucination problem in LLMs can lead to the generation of hypotheses that appear plausible but are ultimately incorrect, undermining their reliability. To facilitate the systematic study of these challenges, we introduce TruthHypo, a benchmark for assessing the capabilities of LLMs in generating truthful biomedical hypotheses, and KnowHD, a knowledge-based hallucination detector to evaluate how well hypotheses are grounded in existing knowledge. Our results show that LLMs struggle to generate truthful hypotheses. By analyzing hallucinations in reasoning steps, we demonstrate that the groundedness scores provided by KnowHD serve as an effective metric for filtering truthful hypotheses from the diverse outputs of LLMs. Human evaluations further validate the utility of KnowHD in identifying truthful hypotheses and accelerating scientific discovery. Our data and source code are available at https://github.com/Teddy-XiongGZ/TruthHypo.

[Arxiv](https://arxiv.org/abs/2505.14599)