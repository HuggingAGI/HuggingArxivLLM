# KERL：基于大型语言模型的知识增强型个性化食谱推荐系统

发布时间：2025年05月20日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在食品领域的应用，特别是将其与知识图谱（KGs）相结合，用于个性化食品推荐和食谱生成。KERL系统整合了KGs和LLMs，展示了LLM在特定领域中的实际应用，因此归类为LLM应用。` `食品推荐` `食谱生成`

> KERL: Knowledge-Enhanced Personalized Recipe Recommendation using Large Language Models

# 摘要

> 大型语言模型（LLMs）的最新进展和丰富的食品数据推动了一系列研究，旨在利用LLMs提升对食品的理解。尽管已有多个推荐系统结合了LLMs和知识图谱（KGs），但将食品相关KGs与LLMs相结合的研究仍然有限。我们提出了KERL，一个整合食品KGs和LLMs的统一系统，用于提供个性化食品推荐并生成带有微观营养信息的食谱。

KERL通过自然语言问题提取实体，从知识图谱中检索子图，并将这些子图作为上下文输入到LLM中，以选择满足约束条件的食谱。随后，系统为每个食谱生成详细的烹饪步骤和营养信息。

为了评估我们的方法，我们开发了一个基准数据集，通过整理食谱相关问题，并结合约束条件和个人偏好进行实验。通过广泛的实验验证，我们的知识图谱增强型LLM显著优于现有方法，为食品推荐、食谱生成和营养分析提供了一个完整且连贯的解决方案。

我们的代码和基准数据集已在GitHub上公开发布，链接为https://github.com/mohbattharani/KERL。


> Recent advances in large language models (LLMs) and the abundance of food data have resulted in studies to improve food understanding using LLMs. Despite several recommendation systems utilizing LLMs and Knowledge Graphs (KGs), there has been limited research on integrating food related KGs with LLMs. We introduce KERL, a unified system that leverages food KGs and LLMs to provide personalized food recommendations and generates recipes with associated micro-nutritional information. Given a natural language question, KERL extracts entities, retrieves subgraphs from the KG, which are then fed into the LLM as context to select the recipes that satisfy the constraints. Next, our system generates the cooking steps and nutritional information for each recipe. To evaluate our approach, we also develop a benchmark dataset by curating recipe related questions, combined with constraints and personal preferences. Through extensive experiments, we show that our proposed KG-augmented LLM significantly outperforms existing approaches, offering a complete and coherent solution for food recommendation, recipe generation, and nutritional analysis. Our code and benchmark datasets are publicly available at https://github.com/mohbattharani/KERL.

[Arxiv](https://arxiv.org/abs/2505.14629)