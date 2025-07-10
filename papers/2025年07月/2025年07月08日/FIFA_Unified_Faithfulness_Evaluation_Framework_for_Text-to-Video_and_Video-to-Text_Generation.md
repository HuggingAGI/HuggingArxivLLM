# FIFA：统一忠实性评估框架，针对文本到视频与视频到文本生成

发布时间：2025年07月08日

`LLM应用` `视频生成` `文本生成`

> FIFA: Unified Faithfulness Evaluation Framework for Text-to-Video and Video-to-Text Generation

# 摘要

> 视频多模态大型语言模型（VideoMLLMs）在视频到文本（Video-to-Text）和文本到视频（Text-to-Video）任务中取得了引人注目的进展。然而，这些模型常常会生成与视觉输入相悖的内容，存在幻觉问题。现有的评估方法不仅局限于单一任务（如V2T），也无法有效评估开放性、自由形式回复中的幻觉现象。为解决这一问题，我们提出了FIFA框架，这是一个统一的事实性评估工具，通过提取全面的描述性事实，借助时空语义依赖图建模语义关联，并利用VideoQA模型进行验证。此外，我们还开发了Post-Correction工具，用于修正幻觉内容。大量实验结果表明，FIFA在评估事实性方面比现有方法更贴近人类判断，而Post-Correction能够有效提升文本和视频生成中的事实一致性。

> Video Multimodal Large Language Models (VideoMLLMs) have achieved remarkable progress in both Video-to-Text and Text-to-Video tasks. However, they often suffer fro hallucinations, generating content that contradicts the visual input. Existing evaluation methods are limited to one task (e.g., V2T) and also fail to assess hallucinations in open-ended, free-form responses. To address this gap, we propose FIFA, a unified FaIthFulness evAluation framework that extracts comprehensive descriptive facts, models their semantic dependencies via a Spatio-Temporal Semantic Dependency Graph, and verifies them using VideoQA models. We further introduce Post-Correction, a tool-based correction framework that revises hallucinated content. Extensive experiments demonstrate that FIFA aligns more closely with human judgment than existing evaluation methods, and that Post-Correction effectively improves factual consistency in both text and video generation.

[Arxiv](https://arxiv.org/abs/2507.06523)