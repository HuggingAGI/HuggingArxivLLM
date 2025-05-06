# 大型语言模型的领域自适应在机械装配件分类中的应用

发布时间：2025年05月02日

`LLM应用` `机械设计` `人工智能`

> A Domain Adaptation of Large Language Models for Classifying Mechanical Assembly Components

# 摘要

> 概念设计阶段是产品开发的关键早期环节，设计师在此阶段根据功能需求生成符合设计规范的潜在方案。功能建模作为该阶段的核心，帮助设计师在确定具体结构细节前进行功能推理。功能行为结构（FBS）框架被广泛用于将功能意图转化为行为和结构描述。然而，由于缺乏结构良好且全面的功能数据，基于功能的设计效果常受影响。这种数据匮乏可能损害早期设计决策，并阻碍行为模型的开发。基于GPT架构的大型语言模型（LLMs）的最新进展为解决这一问题提供了新思路。LLMs在语言理解和自然语言处理方面表现出色，适用于自动化分类任务。本研究提出了一种基于LLM的领域适应框架，通过微调实现机械装配零件功能的自动化分类。通过对特定领域数据进行微调，LLMs能够改进传统上繁琐且主观的功能标注过程，提升其准确性和一致性。案例研究展示了将GPT-3.5 Turbo在俄勒冈州设计库数据上进行微调的过程，而在A Big CAD数据集上的评估表明，经过领域适应的LLM能够生成高质量的功能数据，增强机械零件的语义表示，并为前期工程设计探索提供更有效的支持。

> The conceptual design phase represents a critical early stage in the product development process, where designers generate potential solutions that meet predefined design specifications based on functional requirements. Functional modeling, a foundational aspect of this phase, enables designers to reason about product functions before specific structural details are determined. A widely adopted approach to functional modeling is the Function-Behavior-Structure (FBS) framework, which supports the transformation of functional intent into behavioral and structural descriptions. However, the effectiveness of function-based design is often hindered by the lack of well-structured and comprehensive functional data. This scarcity can negatively impact early design decision-making and hinder the development of accurate behavioral models. Recent advances in Large Language Models (LLMs), such as those based on GPT architectures, offer a promising avenue to address this gap. LLMs have demonstrated significant capabilities in language understanding and natural language processing (NLP), making them suitable for automated classification tasks. This study proposes a novel LLM-based domain adaptation (DA) framework using fine-tuning for the automated classification of mechanical assembly parts' functions. By fine-tuning LLMs on domain-specific datasets, the traditionally manual and subjective process of function annotation can be improved in both accuracy and consistency. A case study demonstrates fine-tuning GPT-3.5 Turbo on data from the Oregon State Design Repository (OSDR), and evaluation on the A Big CAD (ABC) dataset shows that the domain-adapted LLM can generate high-quality functional data, enhancing the semantic representation of mechanical parts and supporting more effective design exploration in early-phase engineering.

[Arxiv](https://arxiv.org/abs/2505.01627)