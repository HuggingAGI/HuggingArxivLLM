# 推理能力可能会影响大语言模型的归纳推理能力。

发布时间：2025年05月30日

`LLM理论` `人工智能` `机器学习`

> Reasoning Can Hurt the Inductive Abilities of Large Language Models

# 摘要

> 大型语言模型（LLMs）在各领域取得了显著进展，但在归纳推理能力上仍有局限——具体而言，模型从少量示例中推断潜在规则的能力尚不理想。人们普遍认为，大型推理模型（LRMs）中的思维链（CoT）提示能够增强这种推理能力。我们通过创建四个受控的、诊断性的基于游戏的任务——国际象棋、德州扑克、骰子游戏和黑杰克——来验证这一假设。这些任务都涉及隐藏的人为定义规则。我们发现，思维链推理可能会降低归纳性能，且LRMs的表现往往不如不具备推理能力的模型。

为了说明这一现象，我们提出了一种理论框架，揭示了推理步骤如何通过三种失效模式放大错误：错误的任务分解、错误的子任务解决以及错误的最终答案总结。基于我们的理论和实证分析，我们引入了结构化的干预措施，根据我们识别出的失效类型来调整CoT生成过程。这些干预措施无需重新训练即可提高归纳推理的准确性。我们的研究结果表明，有效的CoT推理不仅取决于步骤数量，还取决于这些步骤是否结构良好。


> Large Language Models (LLMs) have shown remarkable progress across domains, yet their ability to perform inductive reasoning - inferring latent rules from sparse examples - remains limited. It is often assumed that chain-of-thought (CoT) prompting, as used in Large Reasoning Models (LRMs), enhances such reasoning. We investigate this assumption with creating four controlled, diagnostic game-based tasks - chess, Texas Hold'em, dice games, and blackjack - with hidden human-defined rules. We find that CoT reasoning can degrade inductive performance, with LRMs often underperforming their non-reasoning counterparts.
  To explain this, we present a theoretical framework that reveals how reasoning steps can amplify error through three failure modes: incorrect sub-task decomposition, incorrect sub-task solving, and incorrect final answer summarization. Based on our theoretical and empirical analysis, we introduce structured interventions that adapt CoT generation according to our identified failure types. These interventions improve inductive accuracy without retraining. Our findings suggest that effective (CoT) reasoning depends not only on taking more steps but also on ensuring those steps are well-structured.

[Arxiv](https://arxiv.org/abs/2505.24225)