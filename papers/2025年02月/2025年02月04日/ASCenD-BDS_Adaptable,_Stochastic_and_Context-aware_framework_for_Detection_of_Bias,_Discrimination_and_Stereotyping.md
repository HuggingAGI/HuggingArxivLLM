# ASCenD-BDS：一个灵活、随机且具备上下文感知能力的框架，专为检测偏见、歧视和刻板印象而设计

发布时间：2025年02月04日

`LLM应用

**理由**：这篇论文主要讨论了一个用于检测大型语言模型（LLMs）在不同语言和社会文化背景下的偏见、歧视和刻板印象的框架。该框架的应用场景直接与LLMs的使用和部署相关，属于LLM在实际应用中的问题解决和改进，因此归类为LLM应用。` `社会文化分析`

> ASCenD-BDS: Adaptable, Stochastic and Context-aware framework for Detection of Bias, Discrimination and Stereotyping

# 摘要

> 大型语言模型（LLMs）的迅猛发展重塑了自然语言处理领域，但也引发了对其在不同语言和社会文化背景下部署和使用中固有偏见的深刻担忧。本文提出了一个名为ASCenD BDS（适应性、随机性和上下文感知的偏见、歧视和刻板印象检测框架）的框架。该框架采用了一种适应性、随机性和上下文感知的方法，用于检测性别、种姓、年龄、残疾、社会经济地位、语言变体等多种类别中的偏见、歧视和刻板印象。现有框架主要依赖数据集生成检测场景，如Civil Comments、Wino Gender、WinoBias、BOLD、CrowS Pairs和BBQ等。然而，这种方法只能提供有限的点解决方案。当前框架通过引入适应性、随机性和上下文感知性，克服了这一局限。上下文感知性可针对任何国家、文化或亚文化（如组织的独特文化）进行定制。本文在印度背景下建立了上下文感知性，并利用2011年印度人口普查的内容实现分类的共性。框架通过类别、子类别、STEM、X-Factor和同义词等元素，实现了适应性、随机性和上下文感知性。第3节详细描述了该框架。Saint Fox Consultancy Private Ltd的顾问团队开发了800多个STEM、10个类别和31个独特的子类别。该概念已在SFCLabs中作为产品开发的一部分进行了测试。

> The rapid evolution of Large Language Models (LLMs) has transformed natural language processing but raises critical concerns about biases inherent in their deployment and use across diverse linguistic and sociocultural contexts. This paper presents a framework named ASCenD BDS (Adaptable, Stochastic and Context-aware framework for Detection of Bias, Discrimination and Stereotyping). The framework presents approach to detecting bias, discrimination, stereotyping across various categories such as gender, caste, age, disability, socioeconomic status, linguistic variations, etc., using an approach which is Adaptive, Stochastic and Context-Aware. The existing frameworks rely heavily on usage of datasets to generate scenarios for detection of Bias, Discrimination and Stereotyping. Examples include datasets such as Civil Comments, Wino Gender, WinoBias, BOLD, CrowS Pairs and BBQ. However, such an approach provides point solutions. As a result, these datasets provide a finite number of scenarios for assessment. The current framework overcomes this limitation by having features which enable Adaptability, Stochasticity, Context Awareness. Context awareness can be customized for any nation or culture or sub-culture (for example an organization's unique culture). In this paper, context awareness in the Indian context has been established. Content has been leveraged from Indian Census 2011 to have a commonality of categorization. A framework has been developed using Category, Sub-Category, STEM, X-Factor, Synonym to enable the features for Adaptability, Stochasticity and Context awareness. The framework has been described in detail in Section 3. Overall 800 plus STEMs, 10 Categories, 31 unique SubCategories were developed by a team of consultants at Saint Fox Consultancy Private Ltd. The concept has been tested out in SFCLabs as part of product development.

[Arxiv](https://arxiv.org/abs/2502.02072)