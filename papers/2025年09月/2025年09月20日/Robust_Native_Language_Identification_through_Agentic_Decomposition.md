# 基于智能体分解的鲁棒母语识别

发布时间：2025年09月20日

`Agent` `基础理论`

> Robust Native Language Identification through Agentic Decomposition

# 摘要

> 大型语言模型（LLMs）在母语识别（NLI）基准测试中虽常表现优异，却多依赖姓名、地点和文化刻板印象等表面上下文线索，而非反映母语（L1）影响的底层语言模式。为提升鲁棒性，过往研究曾让LLMs忽略这些线索，但我们发现，这种策略并不可靠——模型预测很容易被误导性提示左右。为此，我们提出一种受法医语言学启发的智能体NLI管道：在独立的最终综合评估前，由专门的智能体收集并分类各类语言证据，再由一个目标感知协调智能体整合所有证据，完成NLI预测。在两个基准数据集上，与标准提示方法相比，该方法显著提升了NLI对误导性上下文线索的抗干扰能力和性能稳定性。

> Large language models (LLMs) often achieve high performance in native language identification (NLI) benchmarks by leveraging superficial contextual clues such as names, locations, and cultural stereotypes, rather than the underlying linguistic patterns indicative of native language (L1) influence. To improve robustness, previous work has instructed LLMs to disregard such clues. In this work, we demonstrate that such a strategy is unreliable and model predictions can be easily altered by misleading hints. To address this problem, we introduce an agentic NLI pipeline inspired by forensic linguistics, where specialized agents accumulate and categorize diverse linguistic evidence before an independent final overall assessment. In this final assessment, a goal-aware coordinating agent synthesizes all evidence to make the NLI prediction. On two benchmark datasets, our approach significantly enhances NLI robustness against misleading contextual clues and performance consistency compared to standard prompting methods.

[Arxiv](https://arxiv.org/abs/2509.16666)