# 计划与预算：大型语言模型推理中高效且有效的推理时扩展

发布时间：2025年05月21日

`LLM理论` `大型语言模型` `推理优化`

> Plan and Budget: Effective and Efficient Test-Time Scaling on Large Language Model Reasoning

# 摘要

> 大型语言模型（LLMs）在复杂推理任务中展现出了卓越的性能，但其推理效率仍有待提升。我们发现，许多主流LLMs普遍存在一种“过度思考”的现象，即使面对简单查询，也会生成冗长且跑题的推理过程。近期研究尝试通过固定token预算来缓解这一问题，但在处理更复杂任务时却容易导致“思考不足”。通过实证分析，我们发现这种低效往往源于模糊的问题解决策略。为此，我们提出了一个理论模型——贝叶斯预算分配模型（BBAM），该模型将推理过程建模为一系列具有不同不确定性的子问题，并引入了【数学公式】$E^3$指标来衡量正确性与计算效率的平衡。基于BBAM的理论框架，我们开发了Plan-and-Budget，这是一个模型不可知的推理时优化框架，它将复杂查询分解为子问题，并通过自适应调度根据子问题的复杂性动态分配token预算。实验结果表明，Plan-and-Budget在多种任务和模型上显著提升了推理效率，实现了最高70%的准确率提升，减少了39%的token使用量，并在【数学公式】$E^3$指标上提升了187.5%。值得注意的是，该方法使一个较小的模型（DS-Qwen-32B）达到了与较大模型（DS-LLaMA-70B）相当的效率——这充分证明了Plan-and-Budget无需重新训练即可缩小性能差距的能力。我们的代码可在anonymous.4open.science/r/P-and-B-6513获取。

> Large Language Models (LLMs) have achieved remarkable success in complex reasoning tasks, but their inference remains computationally inefficient. We observe a common failure mode in many prevalent LLMs, overthinking, where models generate verbose and tangential reasoning traces even for simple queries. Recent works have tried to mitigate this by enforcing fixed token budgets, however, this can lead to underthinking, especially on harder problems. Through empirical analysis, we identify that this inefficiency often stems from unclear problem-solving strategies. To formalize this, we develop a theoretical model, BBAM (Bayesian Budget Allocation Model), which models reasoning as a sequence of sub-questions with varying uncertainty, and introduce the $E^3$ metric to capture the trade-off between correctness and computation efficiency. Building on theoretical results from BBAM, we propose Plan-and-Budget, a model-agnostic, test-time framework that decomposes complex queries into sub-questions and allocates token budgets based on estimated complexity using adaptive scheduling. Plan-and-Budget improves reasoning efficiency across a range of tasks and models, achieving up to +70% accuracy gains, -39% token reduction, and +187.5% improvement in $E^3$. Notably, it elevates a smaller model (DS-Qwen-32B) to match the efficiency of a larger model (DS-LLaMA-70B)-demonstrating Plan-and-Budget's ability to close performance gaps without retraining. Our code is available at anonymous.4open.science/r/P-and-B-6513/.

[Arxiv](https://arxiv.org/abs/2505.16122)