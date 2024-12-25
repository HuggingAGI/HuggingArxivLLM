# 一个用于给基于 LLM 的聊天机器人排名的统计框架

发布时间：2024年12月24日

`LLM应用` `模型评估`

> A Statistical Framework for Ranking LLM-Based Chatbots

# 摘要

> 大型语言模型（LLMs）给自然语言处理带来了变革，Chatbot Arena 等框架为评估这些模型搭建了开创性的平台。借助基于人类判断的数百万次成对比较，Chatbot Arena 已成为 LLM 评估的基石，为开放式对话任务中的模型排名提供了丰富的数据集。在此基础上，我们提出了一个统计框架，融入了关键的改进，以应对成对比较分析中的特定挑战。其一，我们引入了因式化的平局模型，增强了处理平局的能力——这是人类判断比较的重要一环——显著提升了模型对观测数据的拟合度。其二，我们将框架拓展到对竞争对手之间的协方差进行建模，能够更深入地洞察性能关系，便于直观地将其划分为性能层级。其三，我们通过引入新的约束来解决因参数非唯一性导致的优化难题，确保稳定且可解释的参数估计。经过严格评估和大量实验，我们的框架在建模成对比较数据方面相比现有方法有了显著提升。为支持可重复性和实际应用，我们发布了 leaderbot，这是一个开源的 Python 包，实现了我们的模型和分析。

> Large language models (LLMs) have transformed natural language processing, with frameworks like Chatbot Arena providing pioneering platforms for evaluating these models. By facilitating millions of pairwise comparisons based on human judgments, Chatbot Arena has become a cornerstone in LLM evaluation, offering rich datasets for ranking models in open-ended conversational tasks. Building upon this foundation, we propose a statistical framework that incorporates key advancements to address specific challenges in pairwise comparison analysis. First, we introduce a factored tie model that enhances the ability to handle ties -- an integral aspect of human-judged comparisons -- significantly improving the model's fit to observed data. Second, we extend the framework to model covariance between competitors, enabling deeper insights into performance relationships and facilitating intuitive groupings into performance tiers. Third, we resolve optimization challenges arising from parameter non-uniqueness by introducing novel constraints, ensuring stable and interpretable parameter estimation. Through rigorous evaluation and extensive experimentation, our framework demonstrates substantial improvements over existing methods in modeling pairwise comparison data. To support reproducibility and practical adoption, we release leaderbot, an open-source Python package implementing our models and analyses.

[Arxiv](https://arxiv.org/abs/2412.18407)