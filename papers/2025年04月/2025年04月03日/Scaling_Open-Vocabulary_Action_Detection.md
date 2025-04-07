# # 扩展开放词汇的动作检测研究
# Scaling Open-Vocabulary Action Detection

发布时间：2025年04月03日

`其他` `计算机视觉` `视频处理`

> Scaling Open-Vocabulary Action Detection

# 摘要

> 本研究专注于扩展开放词汇动作检测的能力。现有的动作检测方法大多局限于封闭集场景，并依赖于复杂且参数繁重的架构。将这些模型扩展到开放词汇设置面临两个关键挑战：(1) 缺乏包含大量动作类别的大规模数据集来进行稳健训练，(2) 需要对预训练的视觉-语言对比模型进行参数繁重的适应性调整，以将其转换为检测模型，这可能导致额外的非预训练参数过度拟合基础动作类别。首先，我们引入了一种仅用于视频动作检测的编码器单一的多模态模型，减少了对参数繁重架构的依赖。其次，我们提出了一种简单的弱监督训练策略，以利用现有的封闭集动作检测数据集进行预训练。最后，我们摒弃了先前工作中在开放词汇动作检测中使用的不恰当的基础到新型基准，并设计了一种新的基准，可以在不使用这些数据集进行训练的情况下对其进行评估，展示了新颖的结果，为未来的研究提供了基准。

> In this work, we focus on scaling open-vocabulary action detection. Existing approaches for action detection are predominantly limited to closed-set scenarios and rely on complex, parameter-heavy architectures. Extending these models to the open-vocabulary setting poses two key challenges: (1) the lack of large-scale datasets with many action classes for robust training, and (2) parameter-heavy adaptations to a pretrained vision-language contrastive model to convert it for detection, risking overfitting the additional non-pretrained parameters to base action classes. Firstly, we introduce an encoder-only multimodal model for video action detection, reducing the reliance on parameter-heavy additions for video action detection. Secondly, we introduce a simple weakly supervised training strategy to exploit an existing closed-set action detection dataset for pretraining. Finally, we depart from the ill-posed base-to-novel benchmark used by prior works in open-vocabulary action detection and devise a new benchmark to evaluate on existing closed-set action detection datasets without ever using them for training, showing novel results to serve as baselines for future work.

[Arxiv](https://arxiv.org/abs/2504.03096)