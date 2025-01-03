# 市场研究中的大型语言模型：数据增强新视角

发布时间：2024年12月26日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）生成的数据来增强联合分析中的统计方法，特别是在市场研究中的应用。论文提出了一种新颖的统计增强方法，通过迁移学习将LLM生成的数据与真实数据结合，以减少偏差并提高估计的准确性。这属于LLM在实际应用中的具体使用案例，因此归类为“LLM应用”。` `市场研究` `消费者行为`

> Large Language Models for Market Research: A Data-augmentation Approach

# 摘要

> # 摘要
大型语言模型（LLMs）在复杂自然语言处理任务中的卓越表现，彻底革新了人工智能领域。其生成类人文本的能力为市场研究，尤其是联合分析，开辟了新天地。联合分析中，理解消费者偏好至关重要，但传统调查方法在扩展性和成本上受限，LLM生成的数据因此成为有潜力的替代方案。然而，尽管LLMs能模拟真实消费者行为，近期研究揭示LLM生成数据与人类数据间存在显著差距，且替代时易引入偏差。本文提出一种新颖的统计增强方法，巧妙融合LLM生成数据与真实数据于联合分析中。该方法运用迁移学习，仅需少量人类数据即可对LLM数据进行去偏，从而获得统计稳健、一致且渐近正态的估计器，与简单替代的朴素方法形成鲜明对比，后者因偏差加剧而难以节省数据。我们通过COVID-19疫苗偏好实证研究验证了该框架，证明其在降低估计误差、节省数据与成本方面表现卓越，节省幅度高达24.9%至79.8%。另一项跑车选择研究进一步验证了结果的稳健性。研究表明，LLM生成数据虽不能直接替代人类响应，但在稳健统计框架内，可成为宝贵补充。

> Large Language Models (LLMs) have transformed artificial intelligence by excelling in complex natural language processing tasks. Their ability to generate human-like text has opened new possibilities for market research, particularly in conjoint analysis, where understanding consumer preferences is essential but often resource-intensive. Traditional survey-based methods face limitations in scalability and cost, making LLM-generated data a promising alternative. However, while LLMs have the potential to simulate real consumer behavior, recent studies highlight a significant gap between LLM-generated and human data, with biases introduced when substituting between the two. In this paper, we address this gap by proposing a novel statistical data augmentation approach that efficiently integrates LLM-generated data with real data in conjoint analysis. Our method leverages transfer learning principles to debias the LLM-generated data using a small amount of human data. This results in statistically robust estimators with consistent and asymptotically normal properties, in contrast to naive approaches that simply substitute human data with LLM-generated data, which can exacerbate bias. We validate our framework through an empirical study on COVID-19 vaccine preferences, demonstrating its superior ability to reduce estimation error and save data and costs by 24.9\% to 79.8\%. In contrast, naive approaches fail to save data due to the inherent biases in LLM-generated data compared to human data. Another empirical study on sports car choices validates the robustness of our results. Our findings suggest that while LLM-generated data is not a direct substitute for human responses, it can serve as a valuable complement when used within a robust statistical framework.

[Arxiv](https://arxiv.org/abs/2412.19363)