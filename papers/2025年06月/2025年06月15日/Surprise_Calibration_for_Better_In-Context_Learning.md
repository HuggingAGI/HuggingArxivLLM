# # 惊喜校准：提升上下文学习效果
 为更好的上下文学习进行惊喜校准

发布时间：2025年06月15日

`LLM理论`

> Surprise Calibration for Better In-Context Learning

# 摘要

> 上下文学习（ICL）作为大型语言模型（LLMs）中一项强大的任务适应技术，通过少量演示即可推理出潜在的任务结构。然而，ICL仍易受先验知识和上下文演示带来的偏见影响，这可能削弱模型性能。现有偏差校准方法通常采用固定类别先验，难以适应动态ICL场景，因每个查询的上下文均不同。为解决这一问题，我们采用隐式序贯贝叶斯推理框架来解释ICL，识别出“惊讶”这一关键信号用于类别先验变化，并提出了一种创新方法——Surprise Calibration（SC）。SC通过捕捉“惊讶”来反映类别先验的时序动态，为上下文学习提供了更适应性和高效的解决方案。实验证明，SC在多种基准自然语言处理任务中显著优于现有偏差校准技术。

> In-context learning (ICL) has emerged as a powerful paradigm for task adaptation in large language models (LLMs), where models infer underlying task structures from a few demonstrations. However, ICL remains susceptible to biases that arise from prior knowledge and contextual demonstrations, which can degrade the performance of LLMs. Existing bias calibration methods typically apply fixed class priors across all inputs, limiting their efficacy in dynamic ICL settings where the context for each query differs. To address these limitations, we adopt implicit sequential Bayesian inference as a framework for interpreting ICL, identify "surprise" as an informative signal for class prior shift, and introduce a novel method--Surprise Calibration (SC). SC leverages the notion of surprise to capture the temporal dynamics of class priors, providing a more adaptive and computationally efficient solution for in-context learning. We empirically demonstrate the superiority of SC over existing bias calibration techniques across a range of benchmark natural language processing tasks.

[Arxiv](https://arxiv.org/abs/2506.12796)