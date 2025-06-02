# 驾驭大型语言模型，探索科学创新检测

发布时间：2025年05月30日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在科学新颖性检测中的应用，提出了构建数据集和轻量级检索器的方法，属于LLM的应用层面。` `市场营销`

> Harnessing Large Language Models for Scientific Novelty Detection

# 摘要

> 在指数级科学发展的时代，发现新颖的研究想法至关重要且充满挑战。尽管潜力无限，但缺乏合适的基准数据集阻碍了新颖性检测的研究。更重要的是，简单采用现有的自然语言处理技术，例如检索后交叉核对，并不能一概而论地解决问题，因为文本相似性和观点构念之间存在差距。本文中，我们提出利用大型语言模型（LLMs）进行科学新颖性检测（ND），并关联到市场营销和自然语言处理领域的两个新数据集。为了构建适用于ND的全面数据集，我们建议根据论文之间的关系提取闭合集合，并利用LLMs总结它们的主要观点。为了捕捉观点构念，我们提出通过蒸馏LLMs中的构念级别知识来训练一个轻量级检索器，使具有相似构念的观点得以对齐，从而实现高效准确的观点检索，用于LLMs的新颖性检测。实验表明，我们的方法在所提出的基准数据集上，始终优于其他方法，适用于观点检索和新颖性检测任务。代码和数据可在https://anonymous.4open.science/r/NoveltyDetection-10FB/获取。

> In an era of exponential scientific growth, identifying novel research ideas is crucial and challenging in academia. Despite potential, the lack of an appropriate benchmark dataset hinders the research of novelty detection. More importantly, simply adopting existing NLP technologies, e.g., retrieving and then cross-checking, is not a one-size-fits-all solution due to the gap between textual similarity and idea conception. In this paper, we propose to harness large language models (LLMs) for scientific novelty detection (ND), associated with two new datasets in marketing and NLP domains. To construct the considerate datasets for ND, we propose to extract closure sets of papers based on their relationship, and then summarize their main ideas based on LLMs. To capture idea conception, we propose to train a lightweight retriever by distilling the idea-level knowledge from LLMs to align ideas with similar conception, enabling efficient and accurate idea retrieval for LLM novelty detection. Experiments show our method consistently outperforms others on the proposed benchmark datasets for idea retrieval and ND tasks. Codes and data are available at https://anonymous.4open.science/r/NoveltyDetection-10FB/.

[Arxiv](https://arxiv.org/abs/2505.24615)