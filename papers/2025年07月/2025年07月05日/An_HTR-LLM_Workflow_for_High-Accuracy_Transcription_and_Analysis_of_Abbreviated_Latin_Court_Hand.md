# 基于HTR-LLM的高精度转录与分析缩写拉丁法庭手稿的工作流程。

发布时间：2025年07月05日

`LLM应用` `历史文献`

> An HTR-LLM Workflow for High-Accuracy Transcription and Analysis of Abbreviated Latin Court Hand

# 摘要

> 本文提出了一种四阶段工作流程，用于高精度转录和分析具有挑战性的中世纪法律文件，并通过实证研究验证了其有效性。该流程始于一个通过创新“Clean Ground Truth”方法训练的专用手写文本识别（HTR）模型，利用大型语言模型（LLM）优化训练数据，生成可靠的基线转录（阶段一）。在阶段二中，结合原始文档图像，LLM对基线转录进行多模态后校正，提升分析准确性和可靠性。经过校正的简写文本随后通过提示引导的LLM扩展为完整的学术拉丁文（阶段三）。最后，LLM的最终处理阶段执行命名实体修正（NER），规范化专有名词并为模糊读取生成合理替代方案（阶段四）。通过详细案例研究，我们验证了该工作流程的有效性，与学术基准相比，词错误率（WER）达到2-7%的优异水平。这一混合多阶段方法不仅有效自动化了转录中最耗力的部分，还生成了高质量且可分析的输出，为当前技术环境提供了一个强大且实用的解决方案。


> This article presents and validates an ideal, four-stage workflow for the high-accuracy transcription and analysis of challenging medieval legal documents. The process begins with a specialized Handwritten Text Recognition (HTR) model, itself created using a novel "Clean Ground Truth" curation method where a Large Language Model (LLM) refines the training data. This HTR model provides a robust baseline transcription (Stage 1). In Stage 2, this baseline is fed, along with the original document image, to an LLM for multimodal post-correction, grounding the LLM's analysis and improving accuracy. The corrected, abbreviated text is then expanded into full, scholarly Latin using a prompt-guided LLM (Stage 3). A final LLM pass performs Named-Entity Correction (NEC), regularizing proper nouns and generating plausible alternatives for ambiguous readings (Stage 4). We validate this workflow through detailed case studies, achieving Word Error Rates (WER) in the range of 2-7% against scholarly ground truths. The results demonstrate that this hybrid, multi-stage approach effectively automates the most laborious aspects of transcription while producing a high-quality, analyzable output, representing a powerful and practical solution for the current technological landscape.

[Arxiv](https://arxiv.org/abs/2507.04132)