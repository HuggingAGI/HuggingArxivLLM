# 面向医学视觉-语言模型的校准感知提示学习

发布时间：2025年09月18日

`LLM应用` `医疗健康`

> Calibration-Aware Prompt Learning for Medical Vision-Language Models

# 摘要

> 医疗视觉语言模型（Med-VLMs）借助大规模图文预训练，在各类医疗影像任务中表现卓越。但其置信度校准问题尚未得到充分研究，仍是一大挑战。校准不当的预测可能引发过度自信的错误，进而削弱临床信任和决策可靠性。为此，我们提出CalibPrompt——首个在提示调优阶段校准Med-VLMs的框架。CalibPrompt在稀缺标注数据条件下，通过精心设计的校准目标优化少量可学习提示。首先，我们研究了一种正则化项，旨在使平滑准确率与模型预测置信度保持一致。其次，我们引入角度分离损失，通过最大化文本特征相似度来提升多模态Med-VLMs置信度估计的可靠性。在四个公开的Med-VLMs和五个不同的医疗影像数据集上进行的大量实验表明，CalibPrompt能在不显著降低纯净准确率的前提下，持续提升校准效果。我们的代码已开源，地址为https://github.com/iabh1shekbasu/CalibPrompt。

> Medical Vision-Language Models (Med-VLMs) have demonstrated remarkable performance across diverse medical imaging tasks by leveraging large-scale image-text pretraining. However, their confidence calibration is largely unexplored, and so remains a significant challenge. As such, miscalibrated predictions can lead to overconfident errors, undermining clinical trust and decision-making reliability. To address this, we introduce CalibPrompt, the first framework to calibrate Med-VLMs during prompt tuning. CalibPrompt optimizes a small set of learnable prompts with carefully designed calibration objectives under scarce labeled data regime. First, we study a regularizer that attempts to align the smoothed accuracy with the predicted model confidences. Second, we introduce an angular separation loss to maximize textual feature proximity toward improving the reliability in confidence estimates of multimodal Med-VLMs. Extensive experiments on four publicly available Med-VLMs and five diverse medical imaging datasets reveal that CalibPrompt consistently improves calibration without drastically affecting clean accuracy. Our code is available at https://github.com/iabh1shekbasu/CalibPrompt.

[Arxiv](https://arxiv.org/abs/2509.15226)