# 一项关于 DSPy 提词器算法的比较研究，旨在使大型语言模型评估指标与人类评估相契合

发布时间：2024年12月19日

`LLM应用` `语言模型` `幻觉检测`

> A Comparative Study of DSPy Teleprompter Algorithms for Aligning Large Language Models Evaluation Metrics to Human Evaluation

# 摘要

> 我们指出，声明式自我改进 Python（DSPy）优化器能够让大型语言模型（LLM）的提示及其评估与人类注释相契合。在 DSPy 框架下，我们针对五种提示算法，即合作提示优化（COPRO）、多阶段指令提示优化（MIPRO）、BootstrapFewShot、带有 Optuna 的 BootstrapFewShot 以及 K 近邻 Few Shot，就它们与人类评估的契合能力进行了对比分析。具体而言，我们致力于优化提示，以使幻觉检测（以 LLM 作为评判者）与公开基准数据集的人类注释的真实标签相符。我们的实验表明，优化后的提示在检测幻觉方面能够胜过各种基准方法，并且在这些实验中，某些提示算法的表现优于其他算法。

> We argue that the Declarative Self-improving Python (DSPy) optimizers are a way to align the large language model (LLM) prompts and their evaluations to the human annotations. We present a comparative analysis of five teleprompter algorithms, namely, Cooperative Prompt Optimization (COPRO), Multi-Stage Instruction Prompt Optimization (MIPRO), BootstrapFewShot, BootstrapFewShot with Optuna, and K-Nearest Neighbor Few Shot, within the DSPy framework with respect to their ability to align with human evaluations. As a concrete example, we focus on optimizing the prompt to align hallucination detection (using LLM as a judge) to human annotated ground truth labels for a publicly available benchmark dataset. Our experiments demonstrate that optimized prompts can outperform various benchmark methods to detect hallucination, and certain telemprompters outperform the others in at least these experiments.

[Arxiv](https://arxiv.org/abs/2412.15298)