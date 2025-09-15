# 溯因、行动、预测：多智能体系统自动化故障归因的因果推断框架构建

发布时间：2025年09月12日

`Agent` `基础理论`

> Abduct, Act, Predict: Scaffolding Causal Inference for Automated Failure Attribution in Multi-Agent Systems

# 摘要

> 多智能体系统中的故障归因，即精确定位决定性错误发生的具体步骤，是一项关键却悬而未决的挑战。现有方法将其当作长对话日志的模式识别任务来处理，导致步骤级准确率极低（不足17%），因此在调试复杂系统时毫无实用价值。其核心缺陷在于无法进行可靠的反事实推理——即判断纠正单个动作是否真能避免任务失败。为填补这一反事实推理空白，我们提出了Abduct-Act-Predict（A2P）框架——一种新型智能体框架，它将故障归因从模式识别转变为结构化因果推理任务。A2P在单次推理中引导大型语言模型完成规范的三步推理流程：（1）溯因（Abduction），推断智能体行为背后的潜在根本原因；（2）行动（Action），制定最小化的纠正干预措施；（3）预测（Prediction），模拟后续发展轨迹并验证干预是否能解决故障。这种结构化方法既能充分利用整个对话的全局上下文，又能为模型分析赋予严谨的因果逻辑。我们在Who&When基准测试集上的大量实验验证了其有效性：在算法生成数据集上，A2P的步骤级准确率达47.46%，较基线的16.67%提升2.85×；在更复杂的手工构建数据集上，步骤准确率为29.31%，较基线的12.07%提升2.43×。通过从因果视角重新定义问题，A2P框架为自动化故障归因提供了稳健、可验证且准确率显著提升的解决方案。

> Failure attribution in multi-agent systems -- pinpointing the exact step where a decisive error occurs -- is a critical yet unsolved challenge. Current methods treat this as a pattern recognition task over long conversation logs, leading to critically low step-level accuracy (below 17\%), which renders them impractical for debugging complex systems. Their core weakness is a fundamental inability to perform robust counterfactual reasoning: to determine if correcting a single action would have actually averted the task failure. To bridge this counterfactual inference gap, we introduce Abduct-Act-Predict (A2P) Scaffolding, a novel agent framework that transforms failure attribution from pattern recognition into a structured causal inference task. A2P explicitly guides a large language model through a formal three-step reasoning process within a single inference pass: (1) Abduction, to infer the hidden root causes behind an agent's actions; (2) Action, to define a minimal corrective intervention; and (3) Prediction, to simulate the subsequent trajectory and verify if the intervention resolves the failure. This structured approach leverages the holistic context of the entire conversation while imposing a rigorous causal logic on the model's analysis. Our extensive experiments on the Who\&When benchmark demonstrate its efficacy. On the Algorithm-Generated dataset, A2P achieves 47.46\% step-level accuracy, a 2.85$\times$ improvement over the 16.67\% of the baseline. On the more complex Hand-Crafted dataset, it achieves 29.31\% step accuracy, a 2.43$\times$ improvement over the baseline's 12.07\%. By reframing the problem through a causal lens, A2P Scaffolding provides a robust, verifiable, and significantly more accurate solution for automated failure attribution.

[Arxiv](https://arxiv.org/abs/2509.10401)