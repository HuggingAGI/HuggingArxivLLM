# HistLLM: 基于LLM的多模态推荐统一框架，结合用户历史编码与压缩

发布时间：2025年04月14日

`LLM应用

理由：这篇论文探讨了将大型语言模型（LLMs）应用于多模态推荐任务，提出了一种新的框架HistLLM，以解决现有方法在处理文本和视觉信息时的效率和准确性问题。论文的重点在于将LLMs应用于具体任务，属于LLM应用类别。` `推荐系统`

> HistLLM: A Unified Framework for LLM-Based Multimodal Recommendation with User History Encoding and Compression

# 摘要

> 大型语言模型（LLMs）在文本数据推荐方面表现出色，但在多模态推荐任务中的应用仍待深入。虽然LLMs能通过投影函数处理多模态信息，但推荐任务常需结合文本与视觉的长提示表示用户历史，这不仅影响效率，还使模型难以准确捕捉用户偏好，进而影响推荐效果。为解决此问题，我们提出了HistLLM框架，通过用户历史编码模块（UHEM）整合文本与视觉特征，将多模态历史压缩为单一标记表示，有效提升LLMs处理用户偏好的能力。实验结果证明了该机制的有效性和高效性。

> While large language models (LLMs) have proven effective in leveraging textual data for recommendations, their application to multimodal recommendation tasks remains relatively underexplored. Although LLMs can process multimodal information through projection functions that map visual features into their semantic space, recommendation tasks often require representing users' history interactions through lengthy prompts combining text and visual elements, which not only hampers training and inference efficiency but also makes it difficult for the model to accurately capture user preferences from complex and extended prompts, leading to reduced recommendation performance. To address this challenge, we introduce HistLLM, an innovative multimodal recommendation framework that integrates textual and visual features through a User History Encoding Module (UHEM), compressing multimodal user history interactions into a single token representation, effectively facilitating LLMs in processing user preferences. Extensive experiments demonstrate the effectiveness and efficiency of our proposed mechanism.

[Arxiv](https://arxiv.org/abs/2504.10150)