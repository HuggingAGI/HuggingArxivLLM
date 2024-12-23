# “Align Anything”：训练全模态模型遵循带有语言反馈的指令

发布时间：2024年12月20日

`LLM应用` `跨模态`

> Align Anything: Training All-Modality Models to Follow Instructions with Language Feedback

# 摘要

> 强化学习从人类反馈（RLHF）已证实能有效提升大型语言模型的指令遵循能力，然而在跨模态领域却鲜少被探索。随着模态数量增多，让全模态模型与人类意图（比如指令遵循）相契合成为当务之急。在本研究中，我们首次尝试运用涵盖所有模态（包含文本、图像、音频和视频）的人类偏好数据来微调全模态模型（即输入和输出为任意模态，也称任意对任意模型），以确保其行为符合人类意图。这一尝试面临诸多挑战。其一，现有的开源资源中不存在大规模的全模态人类偏好数据，多数数据集局限于特定模态，主要是文本和图像。其二，在复杂的全模态场景中，RLHF 中的二元偏好对于后期训练对齐的有效性尚属未知领域。其三，缺乏系统框架来评估全模态模型的能力，特别是在模态选择和协同方面。为应对这些挑战，我们提出了“对齐万物”框架，其中包含精心标注的 20 万全模态人类偏好数据。接着，我们引入一种从统一语言反馈中学习的对齐方法，有效捕捉复杂的特定模态人类偏好，增强模型的指令遵循能力。此外，为评估后期训练对齐后全模态模型的性能提升，我们构建了一个颇具挑战性的全模态能力评估框架——“评估万物”。所有数据、模型和代码框架均已为社区开源。更多详情，请访问 https://github.com/PKU-Alignment/align-anything 。

> Reinforcement learning from human feedback (RLHF) has proven effective in enhancing the instruction-following capabilities of large language models; however, it remains underexplored in the cross-modality domain. As the number of modalities increases, aligning all-modality models with human intentions -- such as instruction following -- becomes a pressing challenge. In this work, we make the first attempt to fine-tune all-modality models (i.e. input and output with any modality, also named any-to-any models) using human preference data across all modalities (including text, image, audio, and video), ensuring its behavior aligns with human intentions. This endeavor presents several challenges. First, there is no large-scale all-modality human preference data in existing open-source resources, as most datasets are limited to specific modalities, predominantly text and image. Secondly, the effectiveness of binary preferences in RLHF for post-training alignment in complex all-modality scenarios remains an unexplored area. Finally, there is a lack of a systematic framework to evaluate the capabilities of all-modality models, particularly regarding modality selection and synergy. To address these challenges, we propose the align-anything framework, which includes meticulously annotated 200k all-modality human preference data. Then, we introduce an alignment method that learns from unified language feedback, effectively capturing complex modality-specific human preferences and enhancing the model's instruction-following capabilities. Furthermore, to assess performance improvements in all-modality models after post-training alignment, we construct a challenging all-modality capability evaluation framework -- eval-anything. All data, models, and code frameworks have been open-sourced for the community. For more details, please refer to https://github.com/PKU-Alignment/align-anything.

[Arxiv](https://arxiv.org/abs/2412.15838)