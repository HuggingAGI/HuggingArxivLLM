# G-VEval：一种借助 GPT-4o 来评估图像和视频字幕的通用度量标准

发布时间：2024年12月19日

`LLM应用` `字幕评估`

> G-VEval: A Versatile Metric for Evaluating Image and Video Captions Using GPT-4o

# 摘要

> 视觉字幕的评估指标至关重要，却未被充分探究。诸如 BLEU、METEOR、CIDEr 以及 ROUGE 等传统指标往往忽视了语义深度，而像 CLIP-Score、PAC-S 和 Polos 这类经过训练的指标在零样本场景中存在局限。基于高级语言模型的指标也难以契合人类的细微偏好。为应对这些问题，我们推出了 G-VEval，这是一种受 G-Eval 启发、由新的 GPT-4o 驱动的新型指标。G-VEval 在大型多模态模型中运用思维链推理，支持无参考、仅参考和组合这三种模式，能够同时处理视频和图像输入。我们还提出了 MSVD-Eval，这是用于视频字幕评估的新数据集，旨在为人类专家和评估指标构建更透明、一致的框架。它通过引入准确性、完整性、简洁性和相关性（ACCR）等不同维度，以解决现有数据集中缺乏明确标准的问题。大量结果显示，依据肯德尔 tau-b 和肯德尔 tau-c 的衡量，G-VEval 在与人类注释的相关性方面优于现有方法。这为各类字幕任务提供了灵活的解决方案，为大型语言模型理解视频内容提供了简便有效的途径，为自动字幕的发展铺平了道路。代码可在 https://github.com/ztangaj/gveval 获取。

> Evaluation metric of visual captioning is important yet not thoroughly explored. Traditional metrics like BLEU, METEOR, CIDEr, and ROUGE often miss semantic depth, while trained metrics such as CLIP-Score, PAC-S, and Polos are limited in zero-shot scenarios. Advanced Language Model-based metrics also struggle with aligning to nuanced human preferences. To address these issues, we introduce G-VEval, a novel metric inspired by G-Eval and powered by the new GPT-4o. G-VEval uses chain-of-thought reasoning in large multimodal models and supports three modes: reference-free, reference-only, and combined, accommodating both video and image inputs. We also propose MSVD-Eval, a new dataset for video captioning evaluation, to establish a more transparent and consistent framework for both human experts and evaluation metrics. It is designed to address the lack of clear criteria in existing datasets by introducing distinct dimensions of Accuracy, Completeness, Conciseness, and Relevance (ACCR). Extensive results show that G-VEval outperforms existing methods in correlation with human annotations, as measured by Kendall tau-b and Kendall tau-c. This provides a flexible solution for diverse captioning tasks and suggests a straightforward yet effective approach for large language models to understand video content, paving the way for advancements in automated captioning. Codes are available at https://github.com/ztangaj/gveval

[Arxiv](https://arxiv.org/abs/2412.13647)