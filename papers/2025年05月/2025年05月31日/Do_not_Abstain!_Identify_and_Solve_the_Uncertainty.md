# 别犹豫！直面并消除不确定性

发布时间：2025年05月31日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在处理不确定性时的行为和改进方法，属于对模型本身的理论分析和改进，而不是具体的应用场景。因此，它被归类为LLM理论。` `人工智能`

> Do not Abstain! Identify and Solve the Uncertainty

# 摘要

> 尽管大型语言模型（LLMs）在各个领域得到了广泛应用，但它们在面对不确定场景时常常表现出过度自信。现有解决方案主要依赖于回避性回答（例如，“我不知道”），却忽视了识别和解决不确定性以生成更满意回复的机会。为了系统研究并提升LLMs识别和解决不确定性来源的能力，我们引入了	extbf{ConfuseBench}这一基准测试，主要关注文档稀缺、能力限制和查询模糊性三种不确定性类型。

通过ConfuseBench的实验表明，当前LLMs难以准确识别不确定性的根本原因并加以解决。它们更倾向于将不确定性归因于查询模糊性，而忽视了能力限制，尤其是对于较弱的模型。为了解决这一挑战，我们采用了以下方法：
- 生成能够突出原始查询困惑点的情境感知型问题
- 根据问题答案的独特性判断不确定性来源
- 采用基于策略的训练方法InteractDPO生成更好的问题

实验结果证明了我们方法的有效性。

> Despite the widespread application of Large Language Models (LLMs) across various domains, they frequently exhibit overconfidence when encountering uncertain scenarios, yet existing solutions primarily rely on evasive responses (e.g., "I don't know") overlooks the opportunity of identifying and addressing the uncertainty to generate more satisfactory responses. To systematically investigate and improve LLMs' ability of recognizing and addressing the source of uncertainty, we introduce \textbf{ConfuseBench}, a benchmark mainly focus on three types of uncertainty: document scarcity, limited capability, and query ambiguity. Experiments with ConfuseBench reveal that current LLMs struggle to accurately identify the root cause of uncertainty and solve it. They prefer to attribute uncertainty to query ambiguity while overlooking capability limitations, especially for those weaker models. To tackle this challenge, we first generate context-aware inquiries that highlight the confusing aspect of the original query. Then we judge the source of uncertainty based on the uniqueness of the inquiry's answer. Further we use an on-policy training method, InteractDPO to generate better inquiries. Experimental results demonstrate the efficacy of our approach.

[Arxiv](https://arxiv.org/abs/2506.00780)