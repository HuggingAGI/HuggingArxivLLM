# FGBench：用于大型语言模型中基于功能基团的分子属性推理的数据集和基准测试

发布时间：2025年08月01日

`LLM应用` `药物发现`

> FGBench: A Dataset and Benchmark for Molecular Property Reasoning at Functional Group-Level in Large Language Models

# 摘要

> 大型语言模型（LLMs）在化学领域备受关注，但现有数据集多聚焦于分子性质预测，忽视了精细功能组（FG）信息的重要性。通过整合功能组级别的数据，我们可以建立分子结构与文本描述之间的联系，从而开发出更可解释且具备结构感知能力的大型语言模型，提升分子相关任务的推理能力。此外，这些精细信息还能帮助模型揭示功能组与分子性质间的潜在关联，推动分子设计和药物发现的进展。我们推出FGBench数据集，包含62.5万个具有功能组信息的分子性质推理问题。功能组在分子中被精准标注和定位，确保数据集的互操作性，为多模态应用奠定基础。FGBench涵盖245种功能组的回归与分类任务，涉及三个类别：单一功能组影响、多组相互作用及分子比较。基于7,000个精选数据的先进模型测试显示，现有大型语言模型在功能组级别推理上表现乏力，凸显了提升化学任务推理能力的迫切需求。FGBench构建数据集的方法将为生成新问答对提供基础框架，助力模型理解分子结构-性质关系。数据集和代码已开源，访问地址为\href{https://github.com/xuanliugit/FGBench}{https://github.com/xuanliugit/FGBench}。

> Large language models (LLMs) have gained significant attention in chemistry. However, most existing datasets center on molecular-level property prediction and overlook the role of fine-grained functional group (FG) information. Incorporating FG-level data can provide valuable prior knowledge that links molecular structures with textual descriptions, which can be used to build more interpretable, structure-aware LLMs for reasoning on molecule-related tasks. Moreover, LLMs can learn from such fine-grained information to uncover hidden relationships between specific functional groups and molecular properties, thereby advancing molecular design and drug discovery. Here, we introduce FGBench, a dataset comprising 625K molecular property reasoning problems with functional group information. Functional groups are precisely annotated and localized within the molecule, which ensures the dataset's interoperability thereby facilitating further multimodal applications. FGBench includes both regression and classification tasks on 245 different functional groups across three categories for molecular property reasoning: (1) single functional group impacts, (2) multiple functional group interactions, and (3) direct molecular comparisons. In the benchmark of state-of-the-art LLMs on 7K curated data, the results indicate that current LLMs struggle with FG-level property reasoning, highlighting the need to enhance reasoning capabilities in LLMs for chemistry tasks. We anticipate that the methodology employed in FGBench to construct datasets with functional group-level information will serve as a foundational framework for generating new question-answer pairs, enabling LLMs to better understand fine-grained molecular structure-property relationships. The dataset and evaluation code are available at \href{https://github.com/xuanliugit/FGBench}{https://github.com/xuanliugit/FGBench}.

[Arxiv](https://arxiv.org/abs/2508.01055)