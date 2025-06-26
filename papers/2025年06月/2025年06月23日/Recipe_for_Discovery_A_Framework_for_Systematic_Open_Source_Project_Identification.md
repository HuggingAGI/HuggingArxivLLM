# # 探索指南：系统化开源项目识别框架

发布时间：2025年06月23日

`LLM应用` `软件工程`

> Recipe for Discovery: A Framework for Systematic Open Source Project Identification

# 摘要

> 开源软件开发，特别是在大学和研究实验室等机构中，往往呈现分散化特征且难以追踪。尽管这些项目在科学领域产生了具有重大影响力的工具，但由于缺乏可见性和机构认知，这些成果常常未被认可。本文旨在解决这一问题，提出了一种发现、分类和分析分布式机构系统中开源软件项目的框架，并以加州大学（UC）系统为例进行案例研究。

我们利用GitHub的REST API构建了一条管道，用于发现相关仓库并提取有意义的元数据。随后，我们提出并评估了多种分类策略，包括传统机器学习模型和大型语言模型（LLMs），以区分关联项目与无关仓库，并生成对学术开源领域的准确洞察。实验结果表明，该框架在大规模应用中表现出色，成功发现超过52,000个仓库，并以高精度预测了机构关联性。


> Open source software development, particularly within institutions such as universities and research laboratories, is often decentralized and difficult to track. Despite producing highly impactful tools in science, these efforts often go unrecognized due to a lack of visibility and institutional awareness. This paper addresses the challenge of discovering, classifying, and analyzing open source software projects developed across distributed institutional systems. We present a framework for systematically identifying institutional affiliated repositories, using the University of California (UC) system as a case study.
  Using GitHub's REST API, we build a pipeline to discover relevant repositories and extract meaningful metadata. We then propose and evaluate multiple classification strategies, including both traditional machine learning models and large language models (LLMs), to distinguish affiliated projects from unrelated repositories and generate accurate insights into the academic open source landscape. Our results show that the framework is effective at scale, discovering over 52,000 repositories and predicting institutional affiliation with high accuracy.

[Arxiv](https://arxiv.org/abs/2506.18359)