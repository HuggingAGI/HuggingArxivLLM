# 审视推理型大型语言模型中的元认知幻觉

发布时间：2025年05月19日

`LLM理论` `人工智能`

> Auditing Meta-Cognitive Hallucinations in Reasoning Large Language Models

# 摘要

> 推理大型语言模型（RLLMs）的发展大大提升了多步骤推理能力，但同时也让幻觉问题更加频繁且难以消除。尽管现有方法通过整合外部知识、分析模型参数或自我验证来缓解幻觉问题，但它们往往未能捕捉到幻觉在推理链中如何产生和演变。我们通过审查思维链（CoT）轨迹并评估模型对潜在错误或有偏见声明的认知信心，探讨了在受限知识领域中幻觉的因果关系。分析表明，在长思维链设置中，RLLMs可能通过有缺陷的反思推理反复强化偏见和错误，最终导致幻觉推理路径的产生。令人惊讶的是，即使在幻觉的源头进行直接干预，往往也无法逆转其影响，因为推理链表现出“链式不忠诚”——一种抵抗修正并倾向于保留错误逻辑的倾向。此外，我们发现现有幻觉检测方法在复杂推理场景中的可靠性和可解释性远低于先前的假设。与需要访问模型内部的方法（如电路追踪）不同，我们的黑箱审查方法支持可解释的长链幻觉归因，提供了更好的通用性和实际应用价值。代码和数据可在以下链接获取：https://anonymous.4open.science/r/repo_for_meta_hallucination

> The development of Reasoning Large Language Models (RLLMs) has significantly improved multi-step reasoning capabilities, but it has also made hallucination problems more frequent and harder to eliminate. While existing approaches mitigate hallucinations through external knowledge integration, model parameter analysis, or self-verification, they often fail to capture how hallucinations emerge and evolve across the reasoning chain. In this work, we study the causality of hallucinations under constrained knowledge domains by auditing the Chain-of-Thought (CoT) trajectory and assessing the model's cognitive confidence in potentially erroneous or biased claims. Our analysis reveals that in long-CoT settings, RLLMs can iteratively reinforce biases and errors through flawed reflective reasoning, eventually leading to hallucinated reasoning paths. Surprisingly, even direct interventions at the origin of hallucinations often fail to reverse their effects, as reasoning chains exhibit 'chain disloyalty' -- a resistance to correction and a tendency to preserve flawed logic. Furthermore, we show that existing hallucination detection methods are less reliable and interpretable than previously assumed in complex reasoning scenarios. Unlike methods such as circuit tracing that require access to model internals, our black-box auditing approach supports interpretable long-chain hallucination attribution, offering better generalizability and practical utility. Code and data are available at: https://anonymous.4open.science/r/repo_for_meta_hallucination

[Arxiv](https://arxiv.org/abs/2505.13143)