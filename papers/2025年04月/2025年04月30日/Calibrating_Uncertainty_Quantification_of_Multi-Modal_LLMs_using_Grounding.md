# # 基于Grounding的多模态LLM不确定性量化校准

发布时间：2025年04月30日

`LLM理论

理由：这篇论文专注于改进多模态大型语言模型的不确定性量化和校准方法，属于对LLM内在机制的理论研究。`

> Calibrating Uncertainty Quantification of Multi-Modal LLMs using Grounding

# 摘要

> 我们提出了一种专门针对多模态大型语言模型（LLMs）的不确定性量化（UQ）校准的新方法。现有的先进UQ方法依赖于LLM在不同设置下对同一输入查询生成的多个响应之间的一致性。然而，这些方法在LLM持续给出错误答案的情况下，通常会报告更高的置信度，导致置信度与准确性的校准效果不佳。为了解决这一问题，我们除了利用自身一致性外，还引入了跨模态一致性来改进多模态模型的校准效果。具体而言，我们将文本响应与视觉输入相结合。通过利用 grounding 模型的置信度来校准整体置信度。考虑到引入 grounding 模型会在流程中增加其自身的不确定性，我们采用了温度缩放——一种被广泛接受的参数校准技术——来校准 grounding 模型对生成响应准确性的置信度。我们在医学问答（Slake）和视觉问答（VQAv2）等多模态任务上评估了所提出的方法，并考虑了 LLaVA-Med 和 LLaVA 等多模态模型。实验结果表明，所提出的框架在两个任务上都显著提高了校准效果。

> We introduce a novel approach for calibrating uncertainty quantification (UQ) tailored for multi-modal large language models (LLMs). Existing state-of-the-art UQ methods rely on consistency among multiple responses generated by the LLM on an input query under diverse settings. However, these approaches often report higher confidence in scenarios where the LLM is consistently incorrect. This leads to a poorly calibrated confidence with respect to accuracy. To address this, we leverage cross-modal consistency in addition to self-consistency to improve the calibration of the multi-modal models. Specifically, we ground the textual responses to the visual inputs. The confidence from the grounding model is used to calibrate the overall confidence. Given that using a grounding model adds its own uncertainty in the pipeline, we apply temperature scaling - a widely accepted parametric calibration technique - to calibrate the grounding model's confidence in the accuracy of generated responses. We evaluate the proposed approach across multiple multi-modal tasks, such as medical question answering (Slake) and visual question answering (VQAv2), considering multi-modal models such as LLaVA-Med and LLaVA. The experiments demonstrate that the proposed framework achieves significantly improved calibration on both tasks.

[Arxiv](https://arxiv.org/abs/2505.03788)