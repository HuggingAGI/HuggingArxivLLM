# VEAttack：一种与下游任务无关的视觉编码器攻击方法，针对大型视觉语言模型

发布时间：2025年05月22日

`LLM应用`

> VEAttack: Downstream-agnostic Vision Encoder Attack against Large Vision Language Models

# 摘要

> 大视觉-语言模型（LVLMs）在多模态理解和生成方面表现卓越，但其对抗攻击的脆弱性引发了对模型鲁棒性的严重担忧。现有攻击方法多针对特定任务的白盒场景，但在LVLMs的广泛应用中存在局限性，因其需昂贵的全模型梯度计算。基于视觉编码器在LVLMs中的核心地位，我们提出了一种简单而有效的视觉编码器攻击（VEAttack），专注于攻击LVLMs的视觉编码器。具体而言，我们通过最小化干净与扰动视觉特征间的余弦相似性生成对抗样本，无需访问后续语言模型、任务信息及标签，显著降低了计算开销，同时摆脱了传统白盒攻击对任务和标签的依赖。为提升攻击效果，我们提出通过优化图像令牌而非分类令牌来扰动图像。实证与理论分析表明，VEAttack可轻松泛化至多种任务。实验显示，VEAttack在图像描述任务中实现了94.5%的性能下降，在视觉问答任务中实现了75.7%的性能下降。我们还揭示了若干关键观察，为LVLM攻击与防御提供了新视角：1) 大语言模型的隐层变化，2) 令牌注意力差异，3) 转移攻击中的莫比乌斯带现象，4) 对攻击步骤的低敏感性。代码可在https://github.com/hfmei/VEAttack-LVLM获取

> Large Vision-Language Models (LVLMs) have demonstrated remarkable capabilities in multimodal understanding and generation, yet their vulnerability to adversarial attacks raises significant robustness concerns. While existing effective attacks always focus on task-specific white-box settings, these approaches are limited in the context of LVLMs, which are designed for diverse downstream tasks and require expensive full-model gradient computations. Motivated by the pivotal role and wide adoption of the vision encoder in LVLMs, we propose a simple yet effective Vision Encoder Attack (VEAttack), which targets the vision encoder of LVLMs only. Specifically, we propose to generate adversarial examples by minimizing the cosine similarity between the clean and perturbed visual features, without accessing the following large language models, task information, and labels. It significantly reduces the computational overhead while eliminating the task and label dependence of traditional white-box attacks in LVLMs. To make this simple attack effective, we propose to perturb images by optimizing image tokens instead of the classification token. We provide both empirical and theoretical evidence that VEAttack can easily generalize to various tasks. VEAttack has achieved a performance degradation of 94.5% on image caption task and 75.7% on visual question answering task. We also reveal some key observations to provide insights into LVLM attack/defense: 1) hidden layer variations of LLM, 2) token attention differential, 3) Möbius band in transfer attack, 4) low sensitivity to attack steps. The code is available at https://github.com/hfmei/VEAttack-LVLM

[Arxiv](https://arxiv.org/abs/2505.17440)