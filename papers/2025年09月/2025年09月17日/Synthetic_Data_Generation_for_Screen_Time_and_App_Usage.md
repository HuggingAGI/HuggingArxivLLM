# 屏幕使用时间与应用使用情况的合成数据生成

发布时间：2025年09月17日

`LLM应用` `基础理论`

> Synthetic Data Generation for Screen Time and App Usage

# 摘要

> 智能手机使用数据能为理解人与技术的互动及人类行为提供宝贵洞见。但收集大规模真实场景下的智能手机使用日志却困难重重：成本高昂、隐私顾虑、用户样本代表性不足，再加上无回应等可能扭曲结果的偏差，都让数据收集充满挑战。这些难题促使人们探索获取智能手机使用数据集的替代方案。在此背景下，Open AI的ChatGPT等大型语言模型（LLMs）为合成智能手机使用数据生成开辟了新途径，有效解决了真实数据收集的局限性。我们通过案例研究探讨了四种提示策略对生成的智能手机使用数据质量的影响，在提示设计和数据质量衡量方面提供了洞见，并报告了结合两个因素的提示策略对比：提示详细程度（描述用户画像、说明预期结果特征）和种子数据是否包含（是否加入初始真实使用示例）。研究结果显示，对于部分用例，使用LLMs生成结构化且行为合理的智能手机使用数据集是可行的，尤其当采用详细提示时效果更佳。不过，在单一合成数据集中捕捉人类行为模式的多样细微差异仍面临挑战，同时在平衡数据保真度与多样性的权衡时也存在困难。这提示我们需要特定于用例的评估指标，并建议未来研究采用更多样化的种子数据和不同的LLM模型。

> Smartphone usage data can provide valuable insights for understanding interaction with technology and human behavior. However, collecting large-scale, in-the-wild smartphone usage logs is challenging due to high costs, privacy concerns, under representative user samples and biases like non-response that can skew results. These challenges call for exploring alternative approaches to obtain smartphone usage datasets. In this context, large language models (LLMs) such as Open AI's ChatGPT present a novel approach for synthetic smartphone usage data generation, addressing limitations of real-world data collection. We describe a case study on how four prompt strategies influenced the quality of generated smartphone usage data. We contribute with insights on prompt design and measures of data quality, reporting a prompting strategy comparison combining two factors, prompt level of detail (describing a user persona, describing the expected results characteristics) and seed data inclusion (with versus without an initial real usage example). Our findings suggest that using LLMs to generate structured and behaviorally plausible smartphone use datasets is feasible for some use cases, especially when using detailed prompts. Challenges remain in capturing diverse nuances of human behavioral patterns in a single synthetic dataset, and evaluating tradeoffs between data fidelity and diversity, suggesting the need for use-case-specific evaluation metrics and future research with more diverse seed data and different LLM models.

[Arxiv](https://arxiv.org/abs/2509.13892)