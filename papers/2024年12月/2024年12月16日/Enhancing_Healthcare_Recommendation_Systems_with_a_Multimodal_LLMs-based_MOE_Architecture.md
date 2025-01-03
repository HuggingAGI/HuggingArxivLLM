# 基于多模态LLMs的MOE架构：医疗推荐系统的增强之道

发布时间：2024年12月16日

`LLM应用

**理由**：该论文主要探讨了如何将大型语言模型（LLM）与专家混合（MOE）框架结合，用于提升医疗领域推荐系统的性能。虽然涉及多模态数据和推荐系统，但其核心是LLM在特定应用场景（医疗推荐系统）中的使用和优化，因此应归类为LLM应用。` `推荐系统`

> Enhancing Healthcare Recommendation Systems with a Multimodal LLMs-based MOE Architecture

# 摘要

> 随着多模态数据的普及，许多领域亟需能够有效整合多样化数据源的先进架构，以解决特定问题。本研究提出了一种混合推荐模型，结合专家混合（MOE）框架与大型语言模型，旨在提升医疗领域推荐系统的性能。我们构建了一个基于患者描述推荐健康食品的小型数据集，并在精确率、召回率、NDCG和MAP@5等关键指标上评估了模型性能。实验结果显示，混合模型在准确性和个性化推荐效果上均优于单独使用MOE或大型语言模型的基线模型。研究发现，图像数据对个性化推荐系统性能的提升有限，尤其在解决冷启动问题方面。此外，图像重新分类问题也影响了推荐结果，特别是在处理低质量图像或物品外观变化时，导致性能不佳。这些发现为开发强大、可扩展且高性能的推荐系统提供了宝贵见解，推动了个性化推荐技术在医疗等现实领域中的应用。

> With the increasing availability of multimodal data, many fields urgently require advanced architectures capable of effectively integrating these diverse data sources to address specific problems. This study proposes a hybrid recommendation model that combines the Mixture of Experts (MOE) framework with large language models to enhance the performance of recommendation systems in the healthcare domain. We built a small dataset for recommending healthy food based on patient descriptions and evaluated the model's performance on several key metrics, including Precision, Recall, NDCG, and MAP@5. The experimental results show that the hybrid model outperforms the baseline models, which use MOE or large language models individually, in terms of both accuracy and personalized recommendation effectiveness. The paper finds image data provided relatively limited improvement in the performance of the personalized recommendation system, particularly in addressing the cold start problem. Then, the issue of reclassification of images also affected the recommendation results, especially when dealing with low-quality images or changes in the appearance of items, leading to suboptimal performance. The findings provide valuable insights into the development of powerful, scalable, and high-performance recommendation systems, advancing the application of personalized recommendation technologies in real-world domains such as healthcare.

[Arxiv](https://arxiv.org/abs/2412.11557)