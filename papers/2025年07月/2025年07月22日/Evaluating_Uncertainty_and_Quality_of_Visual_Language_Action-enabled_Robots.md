# 评估支持视觉语言动作的机器人不确定性与质量

发布时间：2025年07月22日

`Agent` `人工智能` `机器人学`

> Evaluating Uncertainty and Quality of Visual Language Action-enabled Robots

# 摘要

> 视觉语言动作（VLA）模型是一类多模态人工智能系统，它们整合了视觉感知、自然语言理解和动作规划，使智能体能够自主解释环境、理解指令并执行具身任务。近期，这一领域取得了显著进展。然而，传统的任务成功率评估方法无法全面反映任务执行的质量和模型决策的信心。针对机器人操作任务，我们提出了专门设计的八个不确定性指标和五个质量指标。通过大规模实证研究，我们评估了这些指标的有效性，研究涵盖了来自三个最先进VLA模型的908次成功任务执行，涉及四个代表性的机器人操作任务。人类领域专家手动标注了任务质量，使我们能够分析所提指标与专家判断的相关性。结果显示，若干指标与人类评估呈现中等至强相关性，凸显了它们在评估任务质量和模型信心方面的实用性。此外，某些指标能够区分高质量、中等质量和低质量的执行，这在测试 oracle 不存在时特别有趣。我们的研究结果挑战了仅依赖二元成功率的现有评估实践，并为改进实时监控和自适应增强VLA驱动的机器人系统铺平了道路。

> Visual Language Action (VLA) models are a multi-modal class of Artificial Intelligence (AI) systems that integrate visual perception, natural language understanding, and action planning to enable agents to interpret their environment, comprehend instructions, and perform embodied tasks autonomously. Recently, significant progress has been made to advance this field. These kinds of models are typically evaluated through task success rates, which fail to capture the quality of task execution and the mode's confidence in its decisions. In this paper, we propose eight uncertainty metrics and five quality metrics specifically designed for VLA models for robotic manipulation tasks. We assess their effectiveness through a large-scale empirical study involving 908 successful task executions from three state-of-the-art VLA models across four representative robotic manipulation tasks. Human domain experts manually labeled task quality, allowing us to analyze the correlation between our proposed metrics and expert judgments. The results reveal that several metrics show moderate to strong correlation with human assessments, highlighting their utility for evaluating task quality and model confidence. Furthermore, we found that some of the metrics can discriminate between high-, medium-, and low-quality executions from unsuccessful tasks, which can be interesting when test oracles are not available. Our findings challenge the adequacy of current evaluation practices that rely solely on binary success rates and pave the way for improved real-time monitoring and adaptive enhancement of VLA-enabled robotic systems.

[Arxiv](https://arxiv.org/abs/2507.17049)