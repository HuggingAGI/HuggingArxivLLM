# 关联与预测：基于自然语言处理基准的人类语言模型评估研究

发布时间：2025年02月23日

`LLM应用` `NLP` `对话系统`

> Correlating and Predicting Human Evaluations of Language Models from Natural Language Processing Benchmarks

# 摘要

> 高性能对话语言模型（LMs）的崛起引发了一场从经典NLP基准到昂贵、耗时且噪声较大的人类评估的转变，但二者之间的关系仍不明确。本研究对四个Chat Llama 2模型进行了大规模分析，将其在160个标准NLP测试（如MMLU、ARC、BIG-Bench Hard）中的表现，与2000多名人类标注者对11000多个单轮和2000多个多轮对话的偏好进行了对比。结果显示，大多数NLP基准与人类评估高度相关，表明自动化指标可作为可靠的人类偏好预测器。然而，如对抗性不诚实和安全等三项人类评估与NLP基准呈负相关，另有两项则无相关性。通过过参数化的线性回归分析，我们发现NLP分数能精准预测不同规模模型的人类评估结果，为降低昂贵的人类标注成本提供了新思路。总体而言，我们的研究证实了经典NLP基准的持续价值，并揭示了如何利用它们预测真实用户满意度，为对话AI新时代的评估需求提供了新方向。

> The explosion of high-performing conversational language models (LMs) has spurred a shift from classic natural language processing (NLP) benchmarks to expensive, time-consuming and noisy human evaluations - yet the relationship between these two evaluation strategies remains hazy. In this paper, we conduct a large-scale study of four Chat Llama 2 models, comparing their performance on 160 standard NLP benchmarks (e.g., MMLU, ARC, BIG-Bench Hard) against extensive human preferences on more than 11k single-turn and 2k multi-turn dialogues from over 2k human annotators. Our findings are striking: most NLP benchmarks strongly correlate with human evaluations, suggesting that cheaper, automated metrics can serve as surprisingly reliable predictors of human preferences. Three human evaluations, such as adversarial dishonesty and safety, are anticorrelated with NLP benchmarks, while two are uncorrelated. Moreover, through overparameterized linear regressions, we show that NLP scores can accurately predict human evaluations across different model scales, offering a path to reduce costly human annotation without sacrificing rigor. Overall, our results affirm the continued value of classic benchmarks and illuminate how to harness them to anticipate real-world user satisfaction - pointing to how NLP benchmarks can be leveraged to meet evaluation needs of our new era of conversational AI.

[Arxiv](https://arxiv.org/abs/2502.18339)