# # 精准校准 LLM 置信度：语义引导下的多提示聚合框架
精准校准 LLM 置信度：语义引导下的多提示聚合框架

发布时间：2025年03月04日

`LLM应用` `人工智能`

> Calibrating LLM Confidence with Semantic Steering: A Multi-Prompt Aggregation Framework

# 摘要

> 大型语言模型（LLMs）常出现置信度评分不一致的问题，通常会高估预测的可靠性。尽管LLMs中置信度的表达已引起关注，但关于是否能通过提示系统性地引导置信度评分，先前研究仍存在分歧。近期研究甚至认为，由提示引发的置信度变化微乎其微，暗示LLMs的置信度校准对语言干预具有刚性。与这些观点相反，我们首先通过测试GPT3.5、LLAMA3-70b、GPT4三个模型在7个基准上的表现，证实了定向置信度变化的存在。结果表明，显式指令能够在可控范围内提升或降低置信度评分。基于这一发现，我们提出了一种名为SteeringConf的新框架，包含三个组件：置信度引导、引导置信度聚合和引导答案选择。SteeringConf方法利用置信度操控机制将LLMs的置信度评分引导至多个预期方向，随后通过汇总模块整合引导后的置信度评分以生成最终预测。我们在7个基准上评估了该方法，结果表明在置信度校准和故障检测任务中，我们的方法在各项校准指标上均优于基线模型。

> Large Language Models (LLMs) often exhibit misaligned confidence scores, usually overestimating the reliability of their predictions. While verbalized confidence in Large Language Models (LLMs) has gained attention, prior work remains divided on whether confidence scores can be systematically steered through prompting. Recent studies even argue that such prompt-induced confidence shifts are negligible, suggesting LLMs' confidence calibration is rigid to linguistic interventions. Contrary to these claims, we first rigorously confirm the existence of directional confidence shifts by probing three models (including GPT3.5, LLAMA3-70b, GPT4) across 7 benchmarks, demonstrating that explicit instructions can inflate or deflate confidence scores in a regulated manner. Based on this observation, we propose a novel framework containing three components: confidence steering, steered confidence aggregation and steered answers selection, named SteeringConf. Our method, SteeringConf, leverages a confidence manipulation mechanism to steer the confidence scores of LLMs in several desired directions, followed by a summarization module that aggregates the steered confidence scores to produce a final prediction. We evaluate our method on 7 benchmarks and it consistently outperforms the baselines in terms of calibration metrics in task of confidence calibration and failure detection.

[Arxiv](https://arxiv.org/abs/2503.02863)