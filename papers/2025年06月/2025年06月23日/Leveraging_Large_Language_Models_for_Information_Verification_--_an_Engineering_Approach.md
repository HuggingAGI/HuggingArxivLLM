# 借助大型语言模型的信息验证——工程化方法

发布时间：2025年06月23日

`LLM应用

摘要中详细描述了使用大型语言模型（如GPT-4）来处理和验证多媒体数据的具体方法和应用。整个流程涉及图像和视频的处理、元数据生成、数据清洗、特征提取以及自动化验证，这些都是大型语言模型在特定任务中的实际应用。因此，这篇论文属于LLM应用类别。` `多媒体`

> Leveraging Large Language Models for Information Verification -- an Engineering Approach

# 摘要

> 针对ACMMM25挑战，我们提出了一种基于大型语言模型（LLMs）的工程化方法，用于多媒体新闻源验证。我们的方法通过以下步骤处理图像和视频：首先，使用Google工具生成元数据，捕获相关内容和链接。然后，对多媒体数据进行分段、清洗并转换为帧，从中选择信息量最大的前K帧。这些帧与元数据进行交叉比对，识别共识或差异。此外，我们还提取音频转录本进行进一步验证。整个流程通过GPT-4o的提示工程实现了自动化，人工干预仅限于最终验证环节。

> For the ACMMM25 challenge, we present a practical engineering approach to multimedia news source verification, utilizing Large Language Models (LLMs) like GPT-4o as the backbone of our pipeline. Our method processes images and videos through a streamlined sequence of steps: First, we generate metadata using general-purpose queries via Google tools, capturing relevant content and links. Multimedia data is then segmented, cleaned, and converted into frames, from which we select the top-K most informative frames. These frames are cross-referenced with metadata to identify consensus or discrepancies. Additionally, audio transcripts are extracted for further verification. Noticeably, the entire pipeline is automated using GPT-4o through prompt engineering, with human intervention limited to final validation.

[Arxiv](https://arxiv.org/abs/2506.18274)