# 评估多模态大型语言模型在教育教科书问答任务中的表现

发布时间：2025年06月18日

`RAG` `人工智能`

> Evaluating Multimodal Large Language Models on Educational Textbook Question Answering

# 摘要

> 多模态大型语言模型（MLLMs）在视觉-语言任务中取得了显著成功，但它们在处理复杂长课和复杂教育图表方面的能力仍待验证。我们首次使用 CK12-QA 数据集评估了最先进的 MLLMs 在教科书问答（TQA）任务上的表现，并测试了包括 LLaVA 和 LLaMA 3.2-Vision 在内的视觉-语言模型在不同输入配置下的性能。此外，我们引入了一个轻量级的多模态检索增强生成（RAG）管道，将课程中的段落和图表整合到提示中。结果显示，检索到的教育背景显著影响模型准确性和推理能力，但也暴露出当前模型在处理问题-上下文关系方面的局限性以及噪声的潜在影响，为未来多模态 AI 驱动学习的研究指明了方向。

> Multimodal large language models (MLLMs) have recently achieved significant success in vision--language tasks. However, their capacity to reason over complex, long lessons and intricate educational diagrams that cannot be represented as a single natural image remains largely untested. In this work, we present the first evaluation of state-of-the-art MLLMs on the textbook question answering (TQA) task using the CK12-QA dataset. We assess the performance of recent vision-language models, including LLaVA and LLaMA 3.2-Vision, across various input configurations. Additionally, we introduce a lightweight multimodal retrieval-augmented generation (RAG) pipeline that integrates both paragraphs and diagrams from the lesson into the prompt. Our results demonstrate the influence of retrieved educational context on model accuracy and reasoning, while also revealing current limitations in handling question-context relationships and the potential for noise, pointing to key directions for future research in multimodal AI-driven learning.

[Arxiv](https://arxiv.org/abs/2506.21596)