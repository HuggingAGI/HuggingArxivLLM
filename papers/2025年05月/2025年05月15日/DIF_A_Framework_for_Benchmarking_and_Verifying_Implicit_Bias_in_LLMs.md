# DIF：一个用于评估和验证大型语言模型隐式偏见的框架

发布时间：2025年05月15日

`LLM理论` `社会学` `公平性`

> DIF: A Framework for Benchmarking and Verifying Implicit Bias in LLMs

# 摘要

> 近年来，随着大型语言模型（LLMs）的崛起，人们开始担忧LLMs从训练数据中继承的潜在偏见。先前研究发现，LLMs在面对不同社会背景时会改变生成回应，这表明其存在隐性偏见。我们认为，这种偏见不仅涉及伦理问题，更反映了LLMs在处理额外信息方面的技术局限。与其他衡量LLM智能的方法不同，目前尚无标准方法来评估这一特定的偏见子集。为了解决这一问题，我们开发了一种计算易于解释的基准指标——DIF（人口统计隐性公平性）的方法，通过使用社会人口统计角色来评估现有的LLM逻辑和数学问题数据集。我们的研究表明，这种方法能够统计验证LLM行为中隐性偏见的存在，并发现问答准确性与隐性偏见之间存在负相关趋势，从而支持我们的论点。

> As Large Language Models (LLMs) have risen in prominence over the past few years, there has been concern over the potential biases in LLMs inherited from the training data. Previous studies have examined how LLMs exhibit implicit bias, such as when response generation changes when different social contexts are introduced. We argue that this implicit bias is not only an ethical, but also a technical issue, as it reveals an inability of LLMs to accommodate extraneous information. However, unlike other measures of LLM intelligence, there are no standard methods to benchmark this specific subset of LLM bias. To bridge this gap, we developed a method for calculating an easily interpretable benchmark, DIF (Demographic Implicit Fairness), by evaluating preexisting LLM logic and math problem datasets with sociodemographic personas. We demonstrate that this method can statistically validate the presence of implicit bias in LLM behavior and find an inverse trend between question answering accuracy and implicit bias, supporting our argument.

[Arxiv](https://arxiv.org/abs/2505.10013)