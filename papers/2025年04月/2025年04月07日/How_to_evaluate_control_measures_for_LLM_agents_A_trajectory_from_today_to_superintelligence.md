# 如何评估 LLM 代理的控制手段？探索从当下到超级智能的发展轨迹

发布时间：2025年04月07日

`LLM理论` `AI安全` `风险管理`

> How to evaluate control measures for LLM agents? A trajectory from today to superintelligence

# 摘要

> 随着LLM代理自主造成伤害的能力增强，AI开发者将依赖更复杂的控制措施来防止可能与目标不一致的代理造成伤害。AI开发者可以通过运行控制评估来证明其控制措施的充分性：在控制评估中，红队会创建试图规避控制措施的代理。为了确保控制评估能够准确捕捉目标不一致的风险，红队的能力应与将要在控制措施下部署的代理的能力配置相匹配。

在本文中，我们提出了一种将红队能力与不断进步的AI能力相适应的系统性框架。我们没有假设代理将始终执行人类已知的最佳攻击策略，而是展示了如何通过了解代理的实际能力配置来制定相应的控制评估，从而实现更实际、更具成本效益的控制措施。我们通过考虑一系列五种虚构模型（M1-M5），它们的能力逐步提升，并定义了五个不同的AI控制级别（ACLs），来阐述我们的框架。对于每个ACL，我们提供了控制评估、控制措施和安全案例的示例规则。最后，我们展示了为什么构建一个有说服力的AI控制安全案例对于超智能LLM代理来说将需要研究突破，并强调我们最终可能需要采用替代方法来缓解目标不一致的风险。

> As LLM agents grow more capable of causing harm autonomously, AI developers will rely on increasingly sophisticated control measures to prevent possibly misaligned agents from causing harm. AI developers could demonstrate that their control measures are sufficient by running control evaluations: testing exercises in which a red team produces agents that try to subvert control measures. To ensure control evaluations accurately capture misalignment risks, the affordances granted to this red team should be adapted to the capability profiles of the agents to be deployed under control measures.
  In this paper we propose a systematic framework for adapting affordances of red teams to advancing AI capabilities. Rather than assuming that agents will always execute the best attack strategies known to humans, we demonstrate how knowledge of an agents's actual capability profile can inform proportional control evaluations, resulting in more practical and cost-effective control measures. We illustrate our framework by considering a sequence of five fictional models (M1-M5) with progressively advanced capabilities, defining five distinct AI control levels (ACLs). For each ACL, we provide example rules for control evaluation, control measures, and safety cases that could be appropriate. Finally, we show why constructing a compelling AI control safety case for superintelligent LLM agents will require research breakthroughs, highlighting that we might eventually need alternative approaches to mitigating misalignment risk.

[Arxiv](https://arxiv.org/abs/2504.05259)