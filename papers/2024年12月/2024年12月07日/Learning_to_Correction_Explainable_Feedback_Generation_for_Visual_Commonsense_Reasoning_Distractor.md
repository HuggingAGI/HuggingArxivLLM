# 学习纠错：为视觉常识推理干扰项生成可解释的反馈

发布时间：2024年12月07日

`LLM应用` `视觉推理` `多模态模型`

> Learning to Correction: Explainable Feedback Generation for Visual Commonsense Reasoning Distractor

# 摘要

> 大型多模态模型（LMMs）在视觉常识推理（VCR）任务中表现出众，此任务旨在依据图像中的视觉常识回答一道选择题。然而，LMMs 在干扰项出现时纠正潜在视觉常识错误的能力还有待深入探究。受人类教师精心设计有挑战性的干扰项来测试学生对概念或技能的理解，并协助他们识别和纠正错误以得出答案的启发，我们率先开展了让 LMMs 模拟这一纠错过程的研究。为此，我们以 GPT-4 为“教师”来收集用于纠错的可解释反馈数据集 VCR-DF，其作为评估 LMMs 在 VCR 干扰项中识别误解和澄清错误原因以得出最终答案的能力的基准。另外，我们提出了基于 LMM 的教学专家指导反馈生成（PEIFG）模型，将可学习的专家提示和多模态指令作为反馈生成的指引。实验结果显示，我们的 PEIFG 显著优于现有的 LMMs。我们认为，我们的基准为评估 LMMs 的能力开辟了新方向。

> Large multimodal models (LMMs) have shown remarkable performance in the visual commonsense reasoning (VCR) task, which aims to answer a multiple-choice question based on visual commonsense within an image. However, the ability of LMMs to correct potential visual commonsense errors in the distractor upon their occurrence is yet under-explored. Drawing inspiration from how a human teacher crafts challenging distractors to test students' comprehension of the concepts or skills and assists them in identifying and correcting errors toward the answer, we are the pioneering research for LMMs to simulate this error correction process. To this end, we employ GPT-4 as a ``teacher'' to collect the explainable feedback dataset VCR-DF for error correction, which serves as a benchmark to evaluate the ability of LMMs to identify misconceptions and clarify reasons behind the error in VCR distractors toward final answers. In addition, we propose an LMM-based Pedagogical Expert Instructed Feedback Generation (PEIFG) model to incorporate the learnable expert prompts and multimodal instruction as guidance for feedback generation. Experimental results show that our PEIFG significantly outperforms existing LMMs. We believe that our benchmark provides a new direction for evaluating the capabilities of LMMs.

[Arxiv](https://arxiv.org/abs/2412.07801)