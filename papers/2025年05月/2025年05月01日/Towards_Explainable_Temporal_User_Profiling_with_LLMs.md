# 构建可解释的时间用户画像：基于大型语言模型

发布时间：2025年05月01日

`LLM应用` `推荐系统`

> Towards Explainable Temporal User Profiling with LLMs

# 摘要

> 准确建模用户偏好不仅能提升推荐效果，还能增强推荐系统的透明度。传统用户画像方法，如通过平均物品嵌入建模用户偏好，往往忽视用户兴趣随时间演变的复杂性，尤其是短期与长期偏好之间的相互作用。本研究利用大型语言模型（LLMs）生成用户交互历史的自然语言摘要，区分近期行为与长期倾向。我们的框架不仅建模用户随时间变化的偏好，还能生成自然语言的用户画像，这些画像可用于以可解释的方式解释推荐结果。文本画像通过预训练模型编码，注意力机制动态融合短期和长期嵌入，形成全面的用户表示。除了超越多个基线模型的推荐准确度，我们的方法还天然支持可解释性：可解释的文本摘要和注意力权重可向用户展示，解释特定推荐项被提出的理由。真实世界数据集的实验结果不仅验证了性能提升，还展示了为基于内容的推荐生成更清晰、更透明解释的潜力。

> Accurately modeling user preferences is vital not only for improving recommendation performance but also for enhancing transparency in recommender systems. Conventional user profiling methods, such as averaging item embeddings, often overlook the evolving, nuanced nature of user interests, particularly the interplay between short-term and long-term preferences. In this work, we leverage large language models (LLMs) to generate natural language summaries of users' interaction histories, distinguishing recent behaviors from more persistent tendencies. Our framework not only models temporal user preferences but also produces natural language profiles that can be used to explain recommendations in an interpretable manner. These textual profiles are encoded via a pre-trained model, and an attention mechanism dynamically fuses the short-term and long-term embeddings into a comprehensive user representation. Beyond boosting recommendation accuracy over multiple baselines, our approach naturally supports explainability: the interpretable text summaries and attention weights can be exposed to end users, offering insights into why specific items are suggested. Experiments on real-world datasets underscore both the performance gains and the promise of generating clearer, more transparent justifications for content-based recommendations.

[Arxiv](https://arxiv.org/abs/2505.00886)