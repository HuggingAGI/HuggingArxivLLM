# 利用大型语言模型优化Pinterest搜索相关性

发布时间：2024年10月22日

`LLM应用

解释：这篇论文主要讨论了如何将大型语言模型（LLMs）应用于提升 Pinterest 搜索的相关性评分。具体来说，论文描述了如何通过结合搜索查询和内容表示，利用生成式视觉语言模型提取的标题，以及其他文本信息来构建搜索相关性预测模型。此外，论文还提到了使用半监督学习方法和多语言 LLMs 来扩展训练数据，并展示了在大规模部署系统中的显著成果。这些内容都表明该论文属于 LLM 应用领域。` `搜索系统` `社交媒体`

> Improving Pinterest Search Relevance Using Large Language Models

# 摘要

> 为了提升 Pinterest 搜索的相关性评分，我们将大型语言模型（LLMs）融入搜索相关性模型，通过精心设计的文本表示有效预测 Pins 的相关性。我们的方法结合了搜索查询和内容表示，后者包括从生成式视觉语言模型中提取的标题，并进一步通过链接文本、历史高质量用户查询、用户策划的板块、Pin 标题和描述进行增强，构建了强大的搜索相关性预测模型。我们采用半监督学习方法，高效扩展训练数据，突破了昂贵的人工标注数据限制。通过多语言 LLMs，我们的系统将训练数据扩展到未见的语言和领域，尽管初始数据和标注者仅限于英语。此外，我们从 LLM 模型中提炼出实时可服务的模型架构和特征，并通过全面的离线实验验证了所提技术，展示了大规模部署系统的显著成果。

> To improve relevance scoring on Pinterest Search, we integrate Large Language Models (LLMs) into our search relevance model, leveraging carefully designed text representations to predict the relevance of Pins effectively. Our approach uses search queries alongside content representations that include captions extracted from a generative visual language model. These are further enriched with link-based text data, historically high-quality engaged queries, user-curated boards, Pin titles and Pin descriptions, creating robust models for predicting search relevance. We use a semi-supervised learning approach to efficiently scale up the amount of training data, expanding beyond the expensive human labeled data available. By utilizing multilingual LLMs, our system extends training data to include unseen languages and domains, despite initial data and annotator expertise being confined to English. Furthermore, we distill from the LLM-based model into real-time servable model architectures and features. We provide comprehensive offline experimental validation for our proposed techniques and demonstrate the gains achieved through the final deployed system at scale.

[Arxiv](https://arxiv.org/abs/2410.17152)