# 用大型语言模型解码邻域环境

发布时间：2025年05月12日

`LLM应用` `城市规划` `计算机视觉`

> Decoding Neighborhood Environments with Large Language Models

# 摘要

> 社区环境由住房质量、道路和人行道等物理和环境条件组成，这些因素对人类的健康和福祉产生重大影响。传统的环境评估方法，如实地调查和地理信息系统（GIS），资源消耗大，难以在大规模上评估社区环境。尽管机器学习为自动化分析提供了潜力，但标注训练数据的繁琐过程和缺乏可访问的模型阻碍了其扩展性。本研究探讨了大型语言模型（LLMs）如ChatGPT和Gemini作为工具在大规模解码社区环境（例如人行道和输电线）方面的可行性。我们训练了一个强大的基于YOLOv11的模型，该模型在检测包括路灯、人行道、输电线、公寓、单车道道路和多车道道路在内的六个环境指标方面达到了99.13%的平均准确率。然后，我们评估了四个LLMs，包括ChatGPT、Gemini、Claude和Grok，以评估它们在识别这些指标方面的可行性、鲁棒性和局限性，重点研究了提示策略和微调的影响。我们通过使用前三个LLMs的多数投票实现了超过88%的准确率，这表明LLMs可以成为无需任何训练努力来解码社区环境的有用工具。

> Neighborhood environments include physical and environmental conditions such as housing quality, roads, and sidewalks, which significantly influence human health and well-being. Traditional methods for assessing these environments, including field surveys and geographic information systems (GIS), are resource-intensive and challenging to evaluate neighborhood environments at scale. Although machine learning offers potential for automated analysis, the laborious process of labeling training data and the lack of accessible models hinder scalability. This study explores the feasibility of large language models (LLMs) such as ChatGPT and Gemini as tools for decoding neighborhood environments (e.g., sidewalk and powerline) at scale. We train a robust YOLOv11-based model, which achieves an average accuracy of 99.13% in detecting six environmental indicators, including streetlight, sidewalk, powerline, apartment, single-lane road, and multilane road. We then evaluate four LLMs, including ChatGPT, Gemini, Claude, and Grok, to assess their feasibility, robustness, and limitations in identifying these indicators, with a focus on the impact of prompting strategies and fine-tuning. We apply majority voting with the top three LLMs to achieve over 88% accuracy, which demonstrates LLMs could be a useful tool to decode the neighborhood environment without any training effort.

[Arxiv](https://arxiv.org/abs/2505.08163)