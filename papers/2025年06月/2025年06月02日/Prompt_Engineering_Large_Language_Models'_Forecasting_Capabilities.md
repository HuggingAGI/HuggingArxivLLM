# 利用提示工程提升大型语言模型的预测能力

发布时间：2025年06月02日

`LLM应用` `人工智能`

> Prompt Engineering Large Language Models' Forecasting Capabilities

# 摘要

> 提升大语言模型性能的方法多种多样。然而，许多方法如微调或高级工具使用，虽有效但耗时且昂贵。尽管提示工程成本较低且常适用于简单任务，但对于复杂领域如预测，其效果仍不明确。我们的研究表明，微小的提示调整极少能显著提升预测准确性。在首项研究中，我们测试了38个提示，涵盖Claude 3.5 Sonnet、Claude 3.5 Haiku、GPT-4o及Llama 3.1 405B等模型。次项研究中，我们引入复合提示及外部提示，并纳入o1与o1-mini等推理模型。结果显示，多数提示带来的增益微乎其微，尽管提及基准率可带来小幅提升。令人意外的是，某些策略对准确性产生了显著负面影响，尤其是鼓励模型进行贝叶斯推理时。这些结果表明，在复杂任务如预测中，基础的提示优化增益有限，暗示需采用更强大或专业化的技术以实现显著性能提升。

> Large language model performance can be improved in a large number of ways. Many such techniques, like fine-tuning or advanced tool usage, are time-intensive and expensive. Although prompt engineering is significantly cheaper and often works for simpler tasks, it remains unclear whether prompt engineering suffices for more complex domains like forecasting. Here we show that small prompt modifications rarely boost forecasting accuracy beyond a minimal baseline. In our first study, we tested 38 prompts across Claude 3.5 Sonnet, Claude 3.5 Haiku, GPT-4o, and Llama 3.1 405B. In our second, we introduced compound prompts and prompts from external sources, also including the reasoning models o1 and o1-mini. Our results show that most prompts lead to negligible gains, although references to base rates yield slight benefits. Surprisingly, some strategies showed strong negative effects on accuracy: especially encouraging the model to engage in Bayesian reasoning. These results suggest that, in the context of complex tasks like forecasting, basic prompt refinements alone offer limited gains, implying that more robust or specialized techniques may be required for substantial performance improvements in AI forecasting.

[Arxiv](https://arxiv.org/abs/2506.01578)