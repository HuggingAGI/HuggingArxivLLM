# MotionMap: 人体姿态预测中的多模态表示

发布时间：2024年12月25日

`其他

理由：这篇论文主要讨论的是人体姿态预测的多模态性问题，并提出了一种新的方法（MotionMap）来解决这一问题。虽然论文中提到了多模态性和预测的不确定性，但这些内容与Agent、RAG、LLM应用、LLM理论等分类没有直接关联。因此，这篇论文更适合归类为其他。` `人体姿态预测` `运动分析`

> MotionMap: Representing Multimodality in Human Pose Forecasting

# 摘要

> # 摘要
人体姿态预测本质上是多模态的，因为一个姿态序列可能有多个未来。然而，由于任务本身的不适定性，评估多模态性颇具挑战。为此，我们首先提出了一种新的范式，使任务适定化。尽管现有方法能够预测多模态性，但需要对大量预测进行过采样，这带来了两个关键问题：（1）能否通过高效采样少量预测来捕捉多模态性？（2）对于给定的姿态序列，哪个预测的未来更有可能发生？我们通过MotionMap解决了这些问题，这是一种基于热图的多模态表示方法。MotionMap将热图扩展到所有可能运动的空间分布，不同的局部最大值对应不同的预测。它不仅能捕捉每个观察的可变模态，还能为不同模态提供置信度度量。此外，MotionMap引入了对预测姿态序列的不确定性和可控性概念，并捕捉了难以评估但对安全至关重要的罕见模态。我们通过Human3.6M和AMASS等3D人体姿态数据集的多项实验验证了方法的有效性，并展示了其优势和局限性。项目页面：https://www.epfl.ch/labs/vita/research/prediction/motionmap/

> Human pose forecasting is inherently multimodal since multiple futures exist for an observed pose sequence. However, evaluating multimodality is challenging since the task is ill-posed. Therefore, we first propose an alternative paradigm to make the task well-posed. Next, while state-of-the-art methods predict multimodality, this requires oversampling a large volume of predictions. This raises key questions: (1) Can we capture multimodality by efficiently sampling a smaller number of predictions? (2) Subsequently, which of the predicted futures is more likely for an observed pose sequence? We address these questions with MotionMap, a simple yet effective heatmap based representation for multimodality. We extend heatmaps to represent a spatial distribution over the space of all possible motions, where different local maxima correspond to different forecasts for a given observation. MotionMap can capture a variable number of modes per observation and provide confidence measures for different modes. Further, MotionMap allows us to introduce the notion of uncertainty and controllability over the forecasted pose sequence. Finally, MotionMap captures rare modes that are non-trivial to evaluate yet critical for safety. We support our claims through multiple qualitative and quantitative experiments using popular 3D human pose datasets: Human3.6M and AMASS, highlighting the strengths and limitations of our proposed method. Project Page: https://www.epfl.ch/labs/vita/research/prediction/motionmap/

[Arxiv](https://arxiv.org/abs/2412.18883)