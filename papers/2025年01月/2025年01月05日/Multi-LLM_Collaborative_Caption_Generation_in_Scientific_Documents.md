# 科学文档中的多LLM协作标题生成

发布时间：2025年01月05日

`LLM应用

理由：这篇论文提出了一种利用多个大型语言模型（LLMs）协作生成科学图表标注的框架（MLBCAP）。该方法涉及使用LLMs进行数据质量评估、多样化标注生成和最终标注选择与精炼。虽然论文涉及多模态LLMs的使用，但其核心是LLMs在特定任务（科学图表标注生成）中的应用，因此应归类为LLM应用。` `科学图表`

> Multi-LLM Collaborative Caption Generation in Scientific Documents

# 摘要

> # 摘要
科学图表标注是一项复杂的任务，要求生成与视觉内容相符的描述。然而，现有方法往往因信息不完整而表现不佳，仅将任务视为图像到文本或文本摘要问题，导致无法生成完全捕捉细节的高质量标注。此外，arXiv论文中的现有数据包含低质量标注，给训练大型语言模型（LLMs）带来了巨大挑战。本文提出了一种名为多LLM协作图表标注生成（MLBCAP）的框架，通过利用专门LLMs处理不同子任务来解决这些问题。我们的方法分为三个模块：（质量评估）使用多模态LLMs评估训练数据质量，过滤低质量标注；（多样化标注生成）通过微调/提示多个LLMs生成候选标注；（判断）最后，提示知名LLM从候选标注中选择最佳标注，并精炼剩余不准确之处。人类评估显示，我们的方法生成的标注优于人工标注，证明了其有效性。代码可在https://github.com/teamreboott/MLBCAP获取。

> Scientific figure captioning is a complex task that requires generating contextually appropriate descriptions of visual content. However, existing methods often fall short by utilizing incomplete information, treating the task solely as either an image-to-text or text summarization problem. This limitation hinders the generation of high-quality captions that fully capture the necessary details. Moreover, existing data sourced from arXiv papers contain low-quality captions, posing significant challenges for training large language models (LLMs). In this paper, we introduce a framework called Multi-LLM Collaborative Figure Caption Generation (MLBCAP) to address these challenges by leveraging specialized LLMs for distinct sub-tasks. Our approach unfolds in three key modules: (Quality Assessment) We utilize multimodal LLMs to assess the quality of training data, enabling the filtration of low-quality captions. (Diverse Caption Generation) We then employ a strategy of fine-tuning/prompting multiple LLMs on the captioning task to generate candidate captions. (Judgment) Lastly, we prompt a prominent LLM to select the highest quality caption from the candidates, followed by refining any remaining inaccuracies. Human evaluations demonstrate that informative captions produced by our approach rank better than human-written captions, highlighting its effectiveness. Our code is available at https://github.com/teamreboott/MLBCAP

[Arxiv](https://arxiv.org/abs/2501.02552)