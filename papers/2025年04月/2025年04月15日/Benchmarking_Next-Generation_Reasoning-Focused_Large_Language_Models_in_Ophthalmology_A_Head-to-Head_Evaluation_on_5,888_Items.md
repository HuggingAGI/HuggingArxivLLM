# 眼科领域下一代推理导向大型语言模型评测：5,888项对比测试

发布时间：2025年04月15日

`LLM应用`

> Benchmarking Next-Generation Reasoning-Focused Large Language Models in Ophthalmology: A Head-to-Head Evaluation on 5,888 Items

# 摘要

> # 摘要
近期，专注于推理的大型语言模型（LLMs）取得了显著进展，标志着从通用型LLMs向专为复杂决策设计的模型转变，这对医学领域至关重要。然而，这些模型在眼科等专业领域中的表现仍待深入探索。

本研究全面评估并比较了四款新开发的专注于推理的LLMs——DeepSeek-R1、OpenAI o1、o3-mini 和 Gemini 2.0 Flash-Thinking——在零-shot设置下的准确性和推理能力。每款模型均使用MedMCQA数据集中的5,888道眼科选择题进行了评估。

定量评估包括准确率、Macro-F1，以及ROUGE-L、METEOR、BERTScore、BARTScore和AlignScore五项文本生成指标，均以真实推理为基准计算。此外，随机选取100道问题记录了推理时间。两位认证眼科医生还对模型在鉴别诊断问题上的回答清晰度、完整性和推理结构进行了定性评估。

结果显示，o1（0.902）和DeepSeek-R1（0.888）在准确率上表现最佳，o1在Macro-F1（0.900）上同样领先。在文本生成指标上，各模型表现各异：o3-mini在ROUGE-L（0.151）上表现突出，o1在METEOR（0.232）上领先，DeepSeek-R1和o3-mini在BERTScore（0.673）上并列第一，DeepSeek-R1（-4.105）和Gemini 2.0 Flash-Thinking（-4.127）在BARTScore上表现最佳，而o3-mini（0.181）和o1（0.176）在AlignScore上领先。

推理时间方面，各模型差异显著，DeepSeek-R1最慢（40.4秒），Gemini 2.0 Flash-Thinking最快（6.7秒）。定性评估显示，DeepSeek-R1和Gemini 2.0 Flash-Thinking倾向于提供详细全面的中间推理，而o1和o3-mini则以简洁明了的解释为主。

> Recent advances in reasoning-focused large language models (LLMs) mark a shift from general LLMs toward models designed for complex decision-making, a crucial aspect in medicine. However, their performance in specialized domains like ophthalmology remains underexplored. This study comprehensively evaluated and compared the accuracy and reasoning capabilities of four newly developed reasoning-focused LLMs, namely DeepSeek-R1, OpenAI o1, o3-mini, and Gemini 2.0 Flash-Thinking. Each model was assessed using 5,888 multiple-choice ophthalmology exam questions from the MedMCQA dataset in zero-shot setting. Quantitative evaluation included accuracy, Macro-F1, and five text-generation metrics (ROUGE-L, METEOR, BERTScore, BARTScore, and AlignScore), computed against ground-truth reasonings. Average inference time was recorded for a subset of 100 randomly selected questions. Additionally, two board-certified ophthalmologists qualitatively assessed clarity, completeness, and reasoning structure of responses to differential diagnosis questions.O1 (0.902) and DeepSeek-R1 (0.888) achieved the highest accuracy, with o1 also leading in Macro-F1 (0.900). The performance of models across the text-generation metrics varied: O3-mini excelled in ROUGE-L (0.151), o1 in METEOR (0.232), DeepSeek-R1 and o3-mini tied for BERTScore (0.673), DeepSeek-R1 (-4.105) and Gemini 2.0 Flash-Thinking (-4.127) performed best in BARTScore, while o3-mini (0.181) and o1 (0.176) led AlignScore. Inference time across the models varied, with DeepSeek-R1 being slowest (40.4 seconds) and Gemini 2.0 Flash-Thinking fastest (6.7 seconds). Qualitative evaluation revealed that DeepSeek-R1 and Gemini 2.0 Flash-Thinking tended to provide detailed and comprehensive intermediate reasoning, whereas o1 and o3-mini displayed concise and summarized justifications.

[Arxiv](https://arxiv.org/abs/2504.11186)