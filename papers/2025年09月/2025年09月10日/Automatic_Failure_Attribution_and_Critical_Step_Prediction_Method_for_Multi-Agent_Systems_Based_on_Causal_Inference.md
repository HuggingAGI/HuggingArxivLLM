# 基于因果推断的多智能体系统故障自动归因与关键步骤预测方法

发布时间：2025年09月10日

`Agent` `基础理论`

> Automatic Failure Attribution and Critical Step Prediction Method for Multi-Agent Systems Based on Causal Inference

# 摘要

> 多智能体系统（MAS）是自动化复杂任务的核心，但故障归因难题严重阻碍了其实际落地。现有的诊断工具依赖统计相关性，存在根本性缺陷；在Who&When等挑战性基准测试中，最先进方法定位故障根本原因步骤的准确率不足15%。为填补这一关键空白，我们提出首个基于多粒度因果推断的MAS故障归因框架。该方法包含两项关键技术突破：（1）提出性能因果反转原理，通过反转执行日志数据流来精准建模性能依赖关系，并结合沙普利值定位智能体层面的责任；（2）设计新型因果发现算法CDC-MAS，通过攻克MAS交互数据的非平稳性问题，稳健识别关键故障步骤。框架的归因结果直接驱动自动化优化循环，生成针对性改进建议，并通过反事实模拟验证了建议的有效性。在Who&When和TRAIL基准测试中，该方法性能显著跃升：步骤级准确率最高达36.2%，且生成的优化方案平均将整体任务成功率提升22.4%。这项研究为调试复杂智能体交互提供了兼具理论基础与实用性的解决方案，为构建更可靠、可解释的多智能体系统奠定了基础。

> Multi-agent systems (MAS) are critical for automating complex tasks, yet their practical deployment is severely hampered by the challenge of failure attribution. Current diagnostic tools, which rely on statistical correlations, are fundamentally inadequate; on challenging benchmarks like Who\&When, state-of-the-art methods achieve less than 15\% accuracy in locating the root-cause step of a failure. To address this critical gap, we introduce the first failure attribution framework for MAS grounded in multi-granularity causal inference. Our approach makes two key technical contributions: (1) a performance causal inversion principle, which correctly models performance dependencies by reversing the data flow in execution logs, combined with Shapley values to accurately assign agent-level blame; (2) a novel causal discovery algorithm, CDC-MAS, that robustly identifies critical failure steps by tackling the non-stationary nature of MAS interaction data. The framework's attribution results directly fuel an automated optimization loop, generating targeted suggestions whose efficacy is validated via counterfactual simulations. Evaluations on the Who\&When and TRAIL benchmarks demonstrate a significant leap in performance. Our method achieves up to 36.2\% step-level accuracy. Crucially, the generated optimizations boost overall task success rates by an average of 22.4\%. This work provides a principled and effective solution for debugging complex agent interactions, paving the way for more reliable and interpretable multi-agent systems.

[Arxiv](https://arxiv.org/abs/2509.08682)