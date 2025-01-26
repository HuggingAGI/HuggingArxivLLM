# Video-MMMU：多学科专业视频知识获取能力评估

发布时间：2025年01月23日

`LLM应用

**理由**：这篇论文主要讨论了大型多模态模型（LMMs）在视频知识获取方面的能力评估，提出了一个新的基准测试Video-MMMU，并量化了模型在知识获取方面的性能提升。这属于对大型语言模型（LLM）在实际应用中的性能评估和改进，因此归类为LLM应用。` `多模态学习`

> Video-MMMU: Evaluating Knowledge Acquisition from Multi-Discipline Professional Videos

# 摘要

> 人类通过感知、理解和应用知识三个阶段获取知识，而视频则是这一学习过程的有效媒介。然而，现有视频基准测试未能系统评估大型多模态模型（LMMs）的知识获取能力。为此，我们推出了Video-MMMU，一个多模态、多学科的基准测试，旨在评估LMMs从视频中获取和利用知识的能力。Video-MMMU包含300个专家级视频和900个人工标注的问题，涵盖六个学科，通过感知、理解和应用三个阶段的对齐问答对来评估知识获取。我们提出的知识增益指标Δknowledge量化了观看视频后的性能提升。评估结果显示，随着认知需求的增加，LMMs的性能急剧下降，且与人类在知识获取方面存在显著差距，这表明亟需提升LMMs从视频中学习和适应的能力。

> Humans acquire knowledge through three cognitive stages: perceiving information, comprehending knowledge, and adapting knowledge to solve novel problems. Videos serve as an effective medium for this learning process, facilitating a progression through these cognitive stages. However, existing video benchmarks fail to systematically evaluate the knowledge acquisition capabilities in Large Multimodal Models (LMMs). To address this gap, we introduce Video-MMMU, a multi-modal, multi-disciplinary benchmark designed to assess LMMs' ability to acquire and utilize knowledge from videos. Video-MMMU features a curated collection of 300 expert-level videos and 900 human-annotated questions across six disciplines, evaluating knowledge acquisition through stage-aligned question-answer pairs: Perception, Comprehension, and Adaptation. A proposed knowledge gain metric, Δknowledge, quantifies improvement in performance after video viewing. Evaluation of LMMs reveals a steep decline in performance as cognitive demands increase and highlights a significant gap between human and model knowledge acquisition, underscoring the need for methods to enhance LMMs' capability to learn and adapt from videos.

[Arxiv](https://arxiv.org/abs/2501.13826)