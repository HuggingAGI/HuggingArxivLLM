# 人类重识别（Human Re-ID）与大型视觉语言模型（LVLMs）相遇：我们能期待什么？

发布时间：2025年01月30日

`LLM应用

**理由**：该论文主要讨论了大型视觉语言模型（LVLMs）在特定任务（如人类重识别）中的表现，并提出了改进建议。这属于将大型语言模型（LLM）应用于具体任务的研究，因此归类为LLM应用。` `计算机视觉` `人工智能`

> Human Re-ID Meets LVLMs: What can we expect?

# 摘要

> 大型视觉语言模型（LVLMs）在内容生成、虚拟助手和多模态搜索等任务中取得了突破性进展。然而，这些模型在许多应用中的表现常被诟病，尤其是在与各领域最先进技术对比时。本研究比较了几款主流LVLMs在人类重识别任务中的表现，以专门设计的ReID PersonViT模型为基线，使用Market1501数据集进行评估。评估流程涵盖数据集整理、提示工程和指标选择，从相似度得分、分类准确率、精确率、召回率、F1分数和AUC等多个角度分析结果。结果表明，LVLMs虽有优势，但也存在严重缺陷，常导致灾难性错误，需进一步研究。我们建议未来研究应融合传统方法与LVLMs，结合双方优势，以实现性能的显著提升。

> Large vision-language models (LVLMs) have been regarded as a breakthrough advance in an astoundingly variety of tasks, from content generation to virtual assistants and multimodal search or retrieval. However, for many of these applications, the performance of these methods has been widely criticized, particularly when compared with state-of-the-art methods and technologies in each specific domain. In this work, we compare the performance of the leading large vision-language models in the human re-identification task, using as baseline the performance attained by state-of-the-art AI models specifically designed for this problem. We compare the results due to ChatGPT-4o, Gemini-2.0-Flash, Claude 3.5 Sonnet, and Qwen-VL-Max to a baseline ReID PersonViT model, using the well-known Market1501 dataset. Our evaluation pipeline includes the dataset curation, prompt engineering, and metric selection to assess the models' performance. Results are analyzed from many different perspectives: similarity scores, classification accuracy, and classification metrics, including precision, recall, F1 score, and area under curve (AUC). Our results confirm the strengths of LVLMs, but also their severe limitations that often lead to catastrophic answers and should be the scope of further research. As a concluding remark, we speculate about some further research that should fuse traditional and LVLMs to combine the strengths from both families of techniques and achieve solid improvements in performance.

[Arxiv](https://arxiv.org/abs/2501.18698)