# TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。

发布时间：2024年04月17日

`LLM应用` `经济预算`

> TREACLE: Thrifty Reasoning via Context-Aware LLM and Prompt Selection

# 摘要

> 自然语言处理领域的最新进展催生了众多供应商推出的大型语言模型（LLM）。这些模型在推理精确度、经济成本和响应延迟方面各有千秋，其准确性还受到问题表述的具体措辞影响。用户在解答问题时往往面临预算和时间的双重限制，却难以决定应选择哪款 LLM 以满足准确度和预算的双重需求。为了解决这一问题，我们提出了 TREACLE（基于上下文感知的 LLM 与提示策略的高效推理），这是一种强化学习策略，它能够综合考虑用户的经济预算和时间限制，智能选择模型和提示方案。TREACLE 利用问题上下文信息，包括问题文本嵌入（反映问题类型或难度）和响应历史记录（体现之前回答的一致性），做出明智选择。我们在多个标准推理数据集（GSM8K、CSQA 和 LLC）上进行的评估显示，TREACLE 与基准相比能够节省高达 85% 的成本，同时保持了高准确度。关键的是，它还允许用户在准确性和成本之间灵活权衡。

> Recent successes in natural language processing have led to the proliferation of large language models (LLMs) by multiple providers. Each LLM offering has different inference accuracy, monetary cost, and latency, and their accuracy further depends on the exact wording of the question (i.e., the specific prompt). At the same time, users often have a limit on monetary budget and latency to answer all their questions, and they do not know which LLMs to choose for each question to meet their accuracy and long-term budget requirements. To navigate this rich design space, we propose TREACLE (Thrifty Reasoning via Context-Aware LLM and Prompt Selection), a reinforcement learning policy that jointly selects the model and prompting scheme while respecting the user's monetary cost and latency constraints. TREACLE uses the problem context, including question text embeddings (reflecting the type or difficulty of a query) and the response history (reflecting the consistency of previous responses) to make smart decisions. Our evaluations on standard reasoning datasets (GSM8K, CSQA, and LLC ) with various LLMs and prompts show that TREACLE enables cost savings of up to 85% compared to baselines while maintaining high accuracy. Importantly, it provides the user with the ability to gracefully trade off accuracy for cost.

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x1.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x2.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x3.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x4.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x5.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x6.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x7.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x8.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x9.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x10.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x11.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x12.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x13.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x14.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x15.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x16.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x17.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x18.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x19.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x20.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x21.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x22.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x23.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x24.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x25.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x26.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x27.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x28.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x29.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x30.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x31.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x32.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x33.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x34.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x35.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x36.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x37.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x10.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x38.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x39.png)

![TREACLE：一种通过考虑上下文的大型语言模型和精心选择的提示来实现高效推理的方法。](../../../paper_images/2404.13082/x40.png)

[Arxiv](https://arxiv.org/abs/2404.13082)