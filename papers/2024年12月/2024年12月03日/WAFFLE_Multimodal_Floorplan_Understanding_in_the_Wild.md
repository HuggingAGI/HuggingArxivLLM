# WAFFLE：对野外多模态平面图的理解

发布时间：2024年12月03日

`LLM应用` `计算机视觉`

> WAFFLE: Multimodal Floorplan Understanding in the Wild

# 摘要

> 建筑物乃人类文化的核心要素，且正愈发借助计算方法加以剖析。然而，近期有关计算建筑物理解的工作，大多聚焦于建筑物的自然图像，却忽视了界定建筑物结构的基本元素——平面图。反之，现有的平面图理解工作，其范畴极为有限，往往着眼于单一语义类别和区域的平面图（比如来自单个国家的公寓平面图）。在本项工作中，我们推出了 WAFFLE，这是一个全新的多模态平面图理解数据集，涵盖近 2 万张从互联网数据中精选的平面图图像及元数据，涉及多样的建筑类型、位置和数据格式。借助大型语言模型和多模态基础模型，我们从这些图像及其伴随的含噪元数据中整理并提取语义信息。我们证明，WAFFLE 有助于在新的建筑物理解任务（包括判别性和生成性任务）上取得进展，而这些任务依靠先前的数据集是无法实现的。我们将公开发布 WAFFLE 以及我们的代码和训练模型，为研究社区学习建筑物语义提供新的基石。

> Buildings are a central feature of human culture and are increasingly being analyzed with computational methods. However, recent works on computational building understanding have largely focused on natural imagery of buildings, neglecting the fundamental element defining a building's structure -- its floorplan. Conversely, existing works on floorplan understanding are extremely limited in scope, often focusing on floorplans of a single semantic category and region (e.g. floorplans of apartments from a single country). In this work, we introduce WAFFLE, a novel multimodal floorplan understanding dataset of nearly 20K floorplan images and metadata curated from Internet data spanning diverse building types, locations, and data formats. By using a large language model and multimodal foundation models, we curate and extract semantic information from these images and their accompanying noisy metadata. We show that WAFFLE enables progress on new building understanding tasks, both discriminative and generative, which were not feasible using prior datasets. We will publicly release WAFFLE along with our code and trained models, providing the research community with a new foundation for learning the semantics of buildings.

[Arxiv](https://arxiv.org/abs/2412.00955)